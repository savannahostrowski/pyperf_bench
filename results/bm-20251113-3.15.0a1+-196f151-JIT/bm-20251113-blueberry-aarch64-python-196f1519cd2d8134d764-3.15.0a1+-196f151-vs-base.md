# Results vs. base

- fork: python
- ref: 196f1519cd2d8134d764
- machine: linux-aarch64
- commit hash: 196f151
- commit date: 2025-11-13
- overall geometric mean: 1.009x faster
- HPT reliability: 85.33%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 434 ms                                                                                                                 | 451 ms: 1.04x slower                                                                                                       |
| docutils       | 5.52 sec                                                                                                               | 4.63 sec: 1.19x faster                                                                                                     |
| sphinx         | 1.61 sec                                                                                                               | 1.64 sec: 1.02x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl           | 3.01 sec                                                                                                               | 3.04 sec: 1.01x slower                                                                                                     |
| asyncio_tcp               | 665 ms                                                                                                                 | 671 ms: 1.01x slower                                                                                                       |
| async_tree_memoization_tg | 612 ms                                                                                                                 | 625 ms: 1.02x slower                                                                                                       |
| async_generators          | 628 ms                                                                                                                 | 666 ms: 1.06x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (9): async_tree_io, async_tree_memoization, asyncio_websockets, async_tree_none, async_tree_cpu_io_mixed, coroutines, async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 169 ms                                                                                                                 | 160 ms: 1.05x faster                                                                                                       |
| pidigits       | 340 ms                                                                                                                 | 335 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 38.1 ms                                                                                                                | 37.6 ms: 1.01x faster                                                                                                      |
| regex_dna      | 272 ms                                                                                                                 | 271 ms: 1.01x faster                                                                                                       |
| regex_compile  | 179 ms                                                                                                                 | 182 ms: 1.01x slower                                                                                                       |
| regex_effbot   | 4.45 ms                                                                                                                | 4.64 ms: 1.04x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 389 us                                                                                                                 | 364 us: 1.07x faster                                                                                                       |
| tomli_loads          | 3.41 sec                                                                                                               | 3.21 sec: 1.06x faster                                                                                                     |
| xml_etree_generate   | 167 ms                                                                                                                 | 160 ms: 1.05x faster                                                                                                       |
| unpickle             | 27.0 us                                                                                                                | 26.0 us: 1.04x faster                                                                                                      |
| xml_etree_parse      | 279 ms                                                                                                                 | 273 ms: 1.02x faster                                                                                                       |
| xml_etree_iterparse  | 214 ms                                                                                                                 | 212 ms: 1.01x faster                                                                                                       |
| pickle_dict          | 49.6 us                                                                                                                | 49.5 us: 1.00x faster                                                                                                      |
| pickle               | 22.1 us                                                                                                                | 22.2 us: 1.00x slower                                                                                                      |
| pickle_list          | 7.79 us                                                                                                                | 7.84 us: 1.01x slower                                                                                                      |
| pickle_pure_python   | 533 us                                                                                                                 | 538 us: 1.01x slower                                                                                                       |
| json_dumps           | 17.1 ms                                                                                                                | 17.3 ms: 1.01x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (3): xml_etree_process, json_loads, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.1 ms                                                                                                                | 18.3 ms: 1.01x slower                                                                                                      |
| python_startup_no_site | 10.3 ms                                                                                                                | 10.5 ms: 1.02x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| django_template | 73.2 ms                                                                                                                | 66.0 ms: 1.11x faster                                                                                                      |
| mako            | 21.2 ms                                                                                                                | 20.8 ms: 1.02x faster                                                                                                      |
| genshi_text     | 38.2 ms                                                                                                                | 39.2 ms: 1.03x slower                                                                                                      |
| genshi_xml      | 88.8 ms                                                                                                                | 92.5 ms: 1.04x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251113-3.15.0a1+-196f151/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json | results/bm-20251113-3.15.0a1+-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1+-196f151.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| bench_thread_pool         | 3.91 ms                                                                                                                | 1.28 ms: 3.06x faster                                                                                                      |
| pylint                    | 593 ms                                                                                                                 | 452 ms: 1.31x faster                                                                                                       |
| docutils                  | 5.52 sec                                                                                                               | 4.63 sec: 1.19x faster                                                                                                     |
| pycparser                 | 2.28 sec                                                                                                               | 1.97 sec: 1.16x faster                                                                                                     |
| bpe_tokeniser             | 9.24 sec                                                                                                               | 7.99 sec: 1.16x faster                                                                                                     |
| django_template           | 73.2 ms                                                                                                                | 66.0 ms: 1.11x faster                                                                                                      |
| pyflate                   | 801 ms                                                                                                                 | 725 ms: 1.11x faster                                                                                                       |
| deepcopy_reduce           | 5.27 us                                                                                                                | 4.89 us: 1.08x faster                                                                                                      |
| chaos                     | 108 ms                                                                                                                 | 101 ms: 1.07x faster                                                                                                       |
| unpickle_pure_python      | 389 us                                                                                                                 | 364 us: 1.07x faster                                                                                                       |
| tomli_loads               | 3.41 sec                                                                                                               | 3.21 sec: 1.06x faster                                                                                                     |
| scimark_fft               | 545 ms                                                                                                                 | 515 ms: 1.06x faster                                                                                                       |
| unpack_sequence           | 81.5 ns                                                                                                                | 77.3 ns: 1.06x faster                                                                                                      |
| deepcopy                  | 468 us                                                                                                                 | 444 us: 1.05x faster                                                                                                       |
| nbody                     | 169 ms                                                                                                                 | 160 ms: 1.05x faster                                                                                                       |
| xml_etree_generate        | 167 ms                                                                                                                 | 160 ms: 1.05x faster                                                                                                       |
| unpickle                  | 27.0 us                                                                                                                | 26.0 us: 1.04x faster                                                                                                      |
| deltablue                 | 5.69 ms                                                                                                                | 5.50 ms: 1.03x faster                                                                                                      |
| scimark_sparse_mat_mult   | 8.90 ms                                                                                                                | 8.61 ms: 1.03x faster                                                                                                      |
| deepcopy_memo             | 49.4 us                                                                                                                | 48.2 us: 1.02x faster                                                                                                      |
| xml_etree_parse           | 279 ms                                                                                                                 | 273 ms: 1.02x faster                                                                                                       |
| gc_traversal              | 12.2 ms                                                                                                                | 12.0 ms: 1.02x faster                                                                                                      |
| mako                      | 21.2 ms                                                                                                                | 20.8 ms: 1.02x faster                                                                                                      |
| coverage                  | 146 ms                                                                                                                 | 143 ms: 1.02x faster                                                                                                       |
| crypto_pyaes              | 130 ms                                                                                                                 | 128 ms: 1.02x faster                                                                                                       |
| thrift                    | 1.37 ms                                                                                                                | 1.35 ms: 1.02x faster                                                                                                      |
| regex_v8                  | 38.1 ms                                                                                                                | 37.6 ms: 1.01x faster                                                                                                      |
| logging_simple            | 9.59 us                                                                                                                | 9.47 us: 1.01x faster                                                                                                      |
| pidigits                  | 340 ms                                                                                                                 | 335 ms: 1.01x faster                                                                                                       |
| mdp                       | 2.54 sec                                                                                                               | 2.52 sec: 1.01x faster                                                                                                     |
| xml_etree_iterparse       | 214 ms                                                                                                                 | 212 ms: 1.01x faster                                                                                                       |
| spectral_norm             | 193 ms                                                                                                                 | 191 ms: 1.01x faster                                                                                                       |
| sqlite_synth              | 5.53 us                                                                                                                | 5.50 us: 1.01x faster                                                                                                      |
| richards                  | 75.4 ms                                                                                                                | 74.9 ms: 1.01x faster                                                                                                      |
| regex_dna                 | 272 ms                                                                                                                 | 271 ms: 1.01x faster                                                                                                       |
| telco                     | 246 ms                                                                                                                 | 245 ms: 1.00x faster                                                                                                       |
| logging_format            | 10.5 us                                                                                                                | 10.5 us: 1.00x faster                                                                                                      |
| pickle_dict               | 49.6 us                                                                                                                | 49.5 us: 1.00x faster                                                                                                      |
| pickle                    | 22.1 us                                                                                                                | 22.2 us: 1.00x slower                                                                                                      |
| pickle_list               | 7.79 us                                                                                                                | 7.84 us: 1.01x slower                                                                                                      |
| generators                | 49.0 ms                                                                                                                | 49.3 ms: 1.01x slower                                                                                                      |
| asyncio_tcp_ssl           | 3.01 sec                                                                                                               | 3.04 sec: 1.01x slower                                                                                                     |
| sympy_sum                 | 205 ms                                                                                                                 | 207 ms: 1.01x slower                                                                                                       |
| asyncio_tcp               | 665 ms                                                                                                                 | 671 ms: 1.01x slower                                                                                                       |
| pickle_pure_python        | 533 us                                                                                                                 | 538 us: 1.01x slower                                                                                                       |
| regex_compile             | 179 ms                                                                                                                 | 182 ms: 1.01x slower                                                                                                       |
| pathlib                   | 25.4 ms                                                                                                                | 25.7 ms: 1.01x slower                                                                                                      |
| python_startup            | 18.1 ms                                                                                                                | 18.3 ms: 1.01x slower                                                                                                      |
| logging_silent            | 175 ns                                                                                                                 | 177 ns: 1.01x slower                                                                                                       |
| json_dumps                | 17.1 ms                                                                                                                | 17.3 ms: 1.01x slower                                                                                                      |
| sphinx                    | 1.61 sec                                                                                                               | 1.64 sec: 1.02x slower                                                                                                     |
| sqlglot_v2_parse          | 1.99 ms                                                                                                                | 2.02 ms: 1.02x slower                                                                                                      |
| python_startup_no_site    | 10.3 ms                                                                                                                | 10.5 ms: 1.02x slower                                                                                                      |
| async_tree_memoization_tg | 612 ms                                                                                                                 | 625 ms: 1.02x slower                                                                                                       |
| typing_runtime_protocols  | 300 us                                                                                                                 | 306 us: 1.02x slower                                                                                                       |
| sqlglot_v2_transpile      | 2.50 ms                                                                                                                | 2.56 ms: 1.02x slower                                                                                                      |
| scimark_lu                | 220 ms                                                                                                                 | 225 ms: 1.02x slower                                                                                                       |
| sqlglot_v2_normalize      | 186 ms                                                                                                                 | 191 ms: 1.03x slower                                                                                                       |
| genshi_text               | 38.2 ms                                                                                                                | 39.2 ms: 1.03x slower                                                                                                      |
| sympy_str                 | 396 ms                                                                                                                 | 407 ms: 1.03x slower                                                                                                       |
| sympy_integrate           | 26.7 ms                                                                                                                | 27.5 ms: 1.03x slower                                                                                                      |
| go                        | 170 ms                                                                                                                 | 175 ms: 1.03x slower                                                                                                       |
| dulwich_log               | 72.8 ms                                                                                                                | 75.1 ms: 1.03x slower                                                                                                      |
| many_optionals            | 1.56 ms                                                                                                                | 1.61 ms: 1.03x slower                                                                                                      |
| sqlglot_v2_optimize       | 89.0 ms                                                                                                                | 92.2 ms: 1.04x slower                                                                                                      |
| raytrace                  | 456 ms                                                                                                                 | 472 ms: 1.04x slower                                                                                                       |
| 2to3                      | 434 ms                                                                                                                 | 451 ms: 1.04x slower                                                                                                       |
| genshi_xml                | 88.8 ms                                                                                                                | 92.5 ms: 1.04x slower                                                                                                      |
| regex_effbot              | 4.45 ms                                                                                                                | 4.64 ms: 1.04x slower                                                                                                      |
| nqueens                   | 149 ms                                                                                                                 | 156 ms: 1.04x slower                                                                                                       |
| scimark_monte_carlo       | 117 ms                                                                                                                 | 122 ms: 1.04x slower                                                                                                       |
| sympy_expand              | 693 ms                                                                                                                 | 730 ms: 1.05x slower                                                                                                       |
| async_generators          | 628 ms                                                                                                                 | 666 ms: 1.06x slower                                                                                                       |
| fannkuch                  | 730 ms                                                                                                                 | 778 ms: 1.07x slower                                                                                                       |
| meteor_contest            | 153 ms                                                                                                                 | 168 ms: 1.10x slower                                                                                                       |
| hexiom                    | 9.77 ms                                                                                                                | 10.9 ms: 1.11x slower                                                                                                      |
| comprehensions            | 27.3 us                                                                                                                | 31.2 us: 1.14x slower                                                                                                      |
| pprint_safe_repr          | 1.42 sec                                                                                                               | 1.65 sec: 1.17x slower                                                                                                     |
| pprint_pformat            | 2.88 sec                                                                                                               | 3.41 sec: 1.18x slower                                                                                                     |
| bench_mp_pool             | 123 ms                                                                                                                 | 256 ms: 2.07x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (19): async_tree_io, xml_etree_process, json_loads, json, async_tree_memoization, asyncio_websockets, unpickle_list, richards_super, scimark_sor, async_tree_none, async_tree_cpu_io_mixed, coroutines, create_gc_cycles, subparsers, async_tree_io_tg, float, async_tree_cpu_io_mixed_tg, html5lib, async_tree_none_tg

- Geometric mean (including insignificant results): 1.009x faster

# HPT report

- Reliability score: 85.33% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.02x