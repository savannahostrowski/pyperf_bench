# Results vs. base

- fork: python
- ref: 77cb39e0c7ef606ef68a
- machine: linux-aarch64
- commit hash: 77cb39e
- commit date: 2025-11-20
- overall geometric mean: 1.066x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 376 ms                                                                                                                 | 383 ms: 1.02x slower                                                                                                       |
| html5lib       | 74.1 ms                                                                                                                | 108 ms: 1.45x slower                                                                                                       |
| sphinx         | 1.51 sec                                                                                                               | 1.61 sec: 1.07x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.16x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl           | 2.97 sec                                                                                                               | 3.04 sec: 1.02x slower                                                                                                     |
| async_tree_cpu_io_mixed   | 862 ms                                                                                                                 | 882 ms: 1.02x slower                                                                                                       |
| async_tree_io             | 1.02 sec                                                                                                               | 1.05 sec: 1.03x slower                                                                                                     |
| async_tree_memoization_tg | 570 ms                                                                                                                 | 588 ms: 1.03x slower                                                                                                       |
| asyncio_tcp               | 656 ms                                                                                                                 | 678 ms: 1.03x slower                                                                                                       |
| async_tree_none           | 438 ms                                                                                                                 | 457 ms: 1.04x slower                                                                                                       |
| async_generators          | 591 ms                                                                                                                 | 622 ms: 1.05x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (6): asyncio_websockets, coroutines, async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 109 ms                                                                                                                 | 104 ms: 1.04x faster                                                                                                       |
| pidigits       | 324 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| nbody          | 149 ms                                                                                                                 | 154 ms: 1.03x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 36.8 ms                                                                                                                | 35.3 ms: 1.04x faster                                                                                                      |
| regex_effbot   | 4.44 ms                                                                                                                | 4.41 ms: 1.01x faster                                                                                                      |
| regex_compile  | 144 ms                                                                                                                 | 176 ms: 1.23x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                                                                                 | 283 us: 1.11x faster                                                                                                       |
| xml_etree_process    | 97.4 ms                                                                                                                | 93.0 ms: 1.05x faster                                                                                                      |
| xml_etree_parse      | 230 ms                                                                                                                 | 221 ms: 1.04x faster                                                                                                       |
| xml_etree_generate   | 127 ms                                                                                                                 | 123 ms: 1.03x faster                                                                                                       |
| json_dumps           | 14.0 ms                                                                                                                | 13.6 ms: 1.02x faster                                                                                                      |
| xml_etree_iterparse  | 186 ms                                                                                                                 | 182 ms: 1.02x faster                                                                                                       |
| json_loads           | 38.5 us                                                                                                                | 37.7 us: 1.02x faster                                                                                                      |
| pickle_list          | 6.82 us                                                                                                                | 6.73 us: 1.01x faster                                                                                                      |
| pickle_pure_python   | 444 us                                                                                                                 | 442 us: 1.00x faster                                                                                                       |
| unpickle_list        | 8.00 us                                                                                                                | 8.04 us: 1.01x slower                                                                                                      |
| unpickle             | 21.4 us                                                                                                                | 21.6 us: 1.01x slower                                                                                                      |
| pickle_dict          | 46.9 us                                                                                                                | 47.3 us: 1.01x slower                                                                                                      |
| tomli_loads          | 2.86 sec                                                                                                               | 3.12 sec: 1.09x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 16.5 ms                                                                                                                | 16.3 ms: 1.01x faster                                                                                                      |
| python_startup_no_site | 9.52 ms                                                                                                                | 9.43 ms: 1.01x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.5 ms                                                                                                                | 15.7 ms: 1.05x faster                                                                                                      |
| django_template | 50.3 ms                                                                                                                | 54.8 ms: 1.09x slower                                                                                                      |
| genshi_text     | 31.9 ms                                                                                                                | 40.1 ms: 1.26x slower                                                                                                      |
| genshi_xml      | 73.3 ms                                                                                                                | 120 ms: 1.64x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.21x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json | results/bm-20251120-3.15.0a2+-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| logging_silent            | 156 ns                                                                                                                 | 138 ns: 1.13x faster                                                                                                       |
| scimark_sparse_mat_mult   | 8.53 ms                                                                                                                | 7.66 ms: 1.11x faster                                                                                                      |
| unpickle_pure_python      | 315 us                                                                                                                 | 283 us: 1.11x faster                                                                                                       |
| scimark_fft               | 492 ms                                                                                                                 | 444 ms: 1.11x faster                                                                                                       |
| scimark_lu                | 178 ms                                                                                                                 | 166 ms: 1.08x faster                                                                                                       |
| scimark_sor               | 178 ms                                                                                                                 | 169 ms: 1.05x faster                                                                                                       |
| mako                      | 16.5 ms                                                                                                                | 15.7 ms: 1.05x faster                                                                                                      |
| xml_etree_process         | 97.4 ms                                                                                                                | 93.0 ms: 1.05x faster                                                                                                      |
| float                     | 109 ms                                                                                                                 | 104 ms: 1.04x faster                                                                                                       |
| regex_v8                  | 36.8 ms                                                                                                                | 35.3 ms: 1.04x faster                                                                                                      |
| xml_etree_parse           | 230 ms                                                                                                                 | 221 ms: 1.04x faster                                                                                                       |
| deepcopy_memo             | 40.4 us                                                                                                                | 38.9 us: 1.04x faster                                                                                                      |
| json                      | 6.88 ms                                                                                                                | 6.64 ms: 1.04x faster                                                                                                      |
| xml_etree_generate        | 127 ms                                                                                                                 | 123 ms: 1.03x faster                                                                                                       |
| json_dumps                | 14.0 ms                                                                                                                | 13.6 ms: 1.02x faster                                                                                                      |
| xml_etree_iterparse       | 186 ms                                                                                                                 | 182 ms: 1.02x faster                                                                                                       |
| json_loads                | 38.5 us                                                                                                                | 37.7 us: 1.02x faster                                                                                                      |
| python_startup            | 16.5 ms                                                                                                                | 16.3 ms: 1.01x faster                                                                                                      |
| pickle_list               | 6.82 us                                                                                                                | 6.73 us: 1.01x faster                                                                                                      |
| bpe_tokeniser             | 6.73 sec                                                                                                               | 6.67 sec: 1.01x faster                                                                                                     |
| python_startup_no_site    | 9.52 ms                                                                                                                | 9.43 ms: 1.01x faster                                                                                                      |
| regex_effbot              | 4.44 ms                                                                                                                | 4.41 ms: 1.01x faster                                                                                                      |
| coverage                  | 120 ms                                                                                                                 | 120 ms: 1.01x faster                                                                                                       |
| pickle_pure_python        | 444 us                                                                                                                 | 442 us: 1.00x faster                                                                                                       |
| unpickle_list             | 8.00 us                                                                                                                | 8.04 us: 1.01x slower                                                                                                      |
| unpickle                  | 21.4 us                                                                                                                | 21.6 us: 1.01x slower                                                                                                      |
| pickle_dict               | 46.9 us                                                                                                                | 47.3 us: 1.01x slower                                                                                                      |
| pidigits                  | 324 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| telco                     | 189 ms                                                                                                                 | 192 ms: 1.01x slower                                                                                                       |
| 2to3                      | 376 ms                                                                                                                 | 383 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl           | 2.97 sec                                                                                                               | 3.04 sec: 1.02x slower                                                                                                     |
| async_tree_cpu_io_mixed   | 862 ms                                                                                                                 | 882 ms: 1.02x slower                                                                                                       |
| logging_simple            | 7.93 us                                                                                                                | 8.15 us: 1.03x slower                                                                                                      |
| async_tree_io             | 1.02 sec                                                                                                               | 1.05 sec: 1.03x slower                                                                                                     |
| nbody                     | 149 ms                                                                                                                 | 154 ms: 1.03x slower                                                                                                       |
| async_tree_memoization_tg | 570 ms                                                                                                                 | 588 ms: 1.03x slower                                                                                                       |
| generators                | 44.8 ms                                                                                                                | 46.3 ms: 1.03x slower                                                                                                      |
| asyncio_tcp               | 656 ms                                                                                                                 | 678 ms: 1.03x slower                                                                                                       |
| pyflate                   | 675 ms                                                                                                                 | 699 ms: 1.03x slower                                                                                                       |
| meteor_contest            | 133 ms                                                                                                                 | 138 ms: 1.04x slower                                                                                                       |
| logging_format            | 8.69 us                                                                                                                | 9.01 us: 1.04x slower                                                                                                      |
| subparsers                | 57.7 ms                                                                                                                | 60.1 ms: 1.04x slower                                                                                                      |
| bench_thread_pool         | 1.10 ms                                                                                                                | 1.15 ms: 1.04x slower                                                                                                      |
| async_tree_none           | 438 ms                                                                                                                 | 457 ms: 1.04x slower                                                                                                       |
| async_generators          | 591 ms                                                                                                                 | 622 ms: 1.05x slower                                                                                                       |
| deltablue                 | 4.73 ms                                                                                                                | 4.98 ms: 1.05x slower                                                                                                      |
| fannkuch                  | 575 ms                                                                                                                 | 607 ms: 1.05x slower                                                                                                       |
| richards                  | 62.7 ms                                                                                                                | 66.8 ms: 1.06x slower                                                                                                      |
| richards_super            | 71.0 ms                                                                                                                | 75.7 ms: 1.07x slower                                                                                                      |
| sphinx                    | 1.51 sec                                                                                                               | 1.61 sec: 1.07x slower                                                                                                     |
| thrift                    | 1.08 ms                                                                                                                | 1.15 ms: 1.07x slower                                                                                                      |
| typing_runtime_protocols  | 223 us                                                                                                                 | 240 us: 1.08x slower                                                                                                       |
| pathlib                   | 21.0 ms                                                                                                                | 22.8 ms: 1.09x slower                                                                                                      |
| deepcopy_reduce           | 4.04 us                                                                                                                | 4.41 us: 1.09x slower                                                                                                      |
| django_template           | 50.3 ms                                                                                                                | 54.8 ms: 1.09x slower                                                                                                      |
| tomli_loads               | 2.86 sec                                                                                                               | 3.12 sec: 1.09x slower                                                                                                     |
| crypto_pyaes              | 101 ms                                                                                                                 | 110 ms: 1.10x slower                                                                                                       |
| pylint                    | 391 ms                                                                                                                 | 434 ms: 1.11x slower                                                                                                       |
| sqlglot_v2_optimize       | 73.1 ms                                                                                                                | 81.5 ms: 1.11x slower                                                                                                      |
| sqlglot_v2_normalize      | 150 ms                                                                                                                 | 167 ms: 1.11x slower                                                                                                       |
| sqlglot_v2_transpile      | 2.11 ms                                                                                                                | 2.37 ms: 1.13x slower                                                                                                      |
| many_optionals            | 1.25 ms                                                                                                                | 1.41 ms: 1.13x slower                                                                                                      |
| sqlglot_v2_parse          | 1.65 ms                                                                                                                | 1.88 ms: 1.14x slower                                                                                                      |
| raytrace                  | 381 ms                                                                                                                 | 440 ms: 1.16x slower                                                                                                       |
| pycparser                 | 1.68 sec                                                                                                               | 1.94 sec: 1.16x slower                                                                                                     |
| sympy_integrate           | 22.9 ms                                                                                                                | 27.1 ms: 1.18x slower                                                                                                      |
| sympy_sum                 | 172 ms                                                                                                                 | 205 ms: 1.20x slower                                                                                                       |
| mdp                       | 2.22 sec                                                                                                               | 2.66 sec: 1.20x slower                                                                                                     |
| regex_compile             | 144 ms                                                                                                                 | 176 ms: 1.23x slower                                                                                                       |
| chaos                     | 80.2 ms                                                                                                                | 99.5 ms: 1.24x slower                                                                                                      |
| comprehensions            | 24.1 us                                                                                                                | 29.9 us: 1.24x slower                                                                                                      |
| genshi_text               | 31.9 ms                                                                                                                | 40.1 ms: 1.26x slower                                                                                                      |
| sympy_str                 | 322 ms                                                                                                                 | 406 ms: 1.26x slower                                                                                                       |
| sympy_expand              | 555 ms                                                                                                                 | 707 ms: 1.27x slower                                                                                                       |
| nqueens                   | 118 ms                                                                                                                 | 151 ms: 1.28x slower                                                                                                       |
| pprint_pformat            | 2.18 sec                                                                                                               | 2.87 sec: 1.32x slower                                                                                                     |
| pprint_safe_repr          | 1.06 sec                                                                                                               | 1.43 sec: 1.34x slower                                                                                                     |
| deepcopy                  | 370 us                                                                                                                 | 503 us: 1.36x slower                                                                                                       |
| hexiom                    | 8.38 ms                                                                                                                | 11.5 ms: 1.37x slower                                                                                                      |
| bench_mp_pool             | 159 ms                                                                                                                 | 221 ms: 1.39x slower                                                                                                       |
| dulwich_log               | 61.7 ms                                                                                                                | 87.7 ms: 1.42x slower                                                                                                      |
| html5lib                  | 74.1 ms                                                                                                                | 108 ms: 1.45x slower                                                                                                       |
| go                        | 155 ms                                                                                                                 | 232 ms: 1.50x slower                                                                                                       |
| unpack_sequence           | 63.1 ns                                                                                                                | 101 ns: 1.60x slower                                                                                                       |
| genshi_xml                | 73.3 ms                                                                                                                | 120 ms: 1.64x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.08x slower                                                                                                               |

Benchmark hidden because not significant (13): spectral_norm, gc_traversal, asyncio_websockets, pickle, coroutines, sqlite_synth, regex_dna, create_gc_cycles, scimark_monte_carlo, async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization
Ignored benchmarks (1) of results/bm-20251120-3.15.0a2+-77cb39e/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2+-77cb39e.json: docutils

- Geometric mean (including insignificant results): 1.066x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x

# Memory
- memory change: 1.03x