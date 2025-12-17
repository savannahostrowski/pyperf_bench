# Results vs. base

- fork: python
- ref: 8801c6dec79275e9b588
- machine: linux-aarch64
- commit hash: 8801c6d
- commit date: 2025-12-02
- overall geometric mean: 1.040x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 374 ms                                                                                                                 | 388 ms: 1.04x slower                                                                                                       |
| docutils       | 5.90 sec                                                                                                               | 4.85 sec: 1.22x faster                                                                                                     |
| html5lib       | 92.1 ms                                                                                                                | 106 ms: 1.15x slower                                                                                                       |
| sphinx         | 1.39 sec                                                                                                               | 1.62 sec: 1.16x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines       | 36.9 ms                                                                                                                | 36.8 ms: 1.00x faster                                                                                                      |
| asyncio_tcp_ssl  | 2.82 sec                                                                                                               | 2.87 sec: 1.02x slower                                                                                                     |
| asyncio_tcp      | 650 ms                                                                                                                 | 685 ms: 1.05x slower                                                                                                       |
| async_generators | 559 ms                                                                                                                 | 598 ms: 1.07x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (9): async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_io, asyncio_websockets, async_tree_io_tg, async_tree_memoization_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 130 ms                                                                                                                 | 104 ms: 1.25x faster                                                                                                       |
| pidigits       | 328 ms                                                                                                                 | 327 ms: 1.00x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.08x faster                                                                                                               |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 266 ms                                                                                                                 | 260 ms: 1.02x faster                                                                                                       |
| regex_v8       | 35.7 ms                                                                                                                | 35.9 ms: 1.01x slower                                                                                                      |
| regex_compile  | 144 ms                                                                                                                 | 175 ms: 1.21x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 310 us                                                                                                                 | 282 us: 1.10x faster                                                                                                       |
| json_loads           | 40.2 us                                                                                                                | 37.9 us: 1.06x faster                                                                                                      |
| json_dumps           | 14.3 ms                                                                                                                | 13.8 ms: 1.04x faster                                                                                                      |
| xml_etree_process    | 95.6 ms                                                                                                                | 92.2 ms: 1.04x faster                                                                                                      |
| xml_etree_generate   | 129 ms                                                                                                                 | 124 ms: 1.04x faster                                                                                                       |
| unpickle_list        | 8.15 us                                                                                                                | 7.98 us: 1.02x faster                                                                                                      |
| pickle_pure_python   | 449 us                                                                                                                 | 441 us: 1.02x faster                                                                                                       |
| xml_etree_iterparse  | 182 ms                                                                                                                 | 183 ms: 1.01x slower                                                                                                       |
| pickle_list          | 6.76 us                                                                                                                | 6.85 us: 1.01x slower                                                                                                      |
| tomli_loads          | 2.86 sec                                                                                                               | 3.04 sec: 1.06x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (4): unpickle, pickle, pickle_dict, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 9.39 ms                                                                                                                | 9.56 ms: 1.02x slower                                                                                                      |
| python_startup         | 16.2 ms                                                                                                                | 16.7 ms: 1.03x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.6 ms                                                                                                                | 15.8 ms: 1.25x faster                                                                                                      |
| django_template | 48.1 ms                                                                                                                | 53.9 ms: 1.12x slower                                                                                                      |
| genshi_text     | 34.9 ms                                                                                                                | 40.1 ms: 1.15x slower                                                                                                      |
| genshi_xml      | 98.3 ms                                                                                                                | 115 ms: 1.17x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20251202-3.15.0a2+-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json | results/bm-20251202-3.15.0a2+-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2+-8801c6d.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| create_gc_cycles         | 14.5 ms                                                                                                                | 7.66 ms: 1.89x faster                                                                                                      |
| float                    | 130 ms                                                                                                                 | 104 ms: 1.25x faster                                                                                                       |
| mako                     | 19.6 ms                                                                                                                | 15.8 ms: 1.25x faster                                                                                                      |
| gc_traversal             | 16.2 ms                                                                                                                | 13.2 ms: 1.23x faster                                                                                                      |
| docutils                 | 5.90 sec                                                                                                               | 4.85 sec: 1.22x faster                                                                                                     |
| logging_silent           | 159 ns                                                                                                                 | 137 ns: 1.16x faster                                                                                                       |
| logging_simple           | 9.10 us                                                                                                                | 8.02 us: 1.13x faster                                                                                                      |
| logging_format           | 9.85 us                                                                                                                | 8.92 us: 1.10x faster                                                                                                      |
| unpickle_pure_python     | 310 us                                                                                                                 | 282 us: 1.10x faster                                                                                                       |
| json                     | 7.25 ms                                                                                                                | 6.61 ms: 1.10x faster                                                                                                      |
| mdp                      | 2.90 sec                                                                                                               | 2.72 sec: 1.07x faster                                                                                                     |
| json_loads               | 40.2 us                                                                                                                | 37.9 us: 1.06x faster                                                                                                      |
| scimark_fft              | 470 ms                                                                                                                 | 444 ms: 1.06x faster                                                                                                       |
| json_dumps               | 14.3 ms                                                                                                                | 13.8 ms: 1.04x faster                                                                                                      |
| xml_etree_process        | 95.6 ms                                                                                                                | 92.2 ms: 1.04x faster                                                                                                      |
| xml_etree_generate       | 129 ms                                                                                                                 | 124 ms: 1.04x faster                                                                                                       |
| deepcopy_memo            | 40.0 us                                                                                                                | 38.8 us: 1.03x faster                                                                                                      |
| spectral_norm            | 147 ms                                                                                                                 | 143 ms: 1.03x faster                                                                                                       |
| sqlite_synth             | 4.62 us                                                                                                                | 4.49 us: 1.03x faster                                                                                                      |
| regex_dna                | 266 ms                                                                                                                 | 260 ms: 1.02x faster                                                                                                       |
| unpickle_list            | 8.15 us                                                                                                                | 7.98 us: 1.02x faster                                                                                                      |
| pickle_pure_python       | 449 us                                                                                                                 | 441 us: 1.02x faster                                                                                                       |
| bpe_tokeniser            | 6.70 sec                                                                                                               | 6.67 sec: 1.00x faster                                                                                                     |
| coroutines               | 36.9 ms                                                                                                                | 36.8 ms: 1.00x faster                                                                                                      |
| pidigits                 | 328 ms                                                                                                                 | 327 ms: 1.00x faster                                                                                                       |
| scimark_sparse_mat_mult  | 7.67 ms                                                                                                                | 7.69 ms: 1.00x slower                                                                                                      |
| xml_etree_iterparse      | 182 ms                                                                                                                 | 183 ms: 1.01x slower                                                                                                       |
| regex_v8                 | 35.7 ms                                                                                                                | 35.9 ms: 1.01x slower                                                                                                      |
| scimark_lu               | 166 ms                                                                                                                 | 167 ms: 1.01x slower                                                                                                       |
| generators               | 45.7 ms                                                                                                                | 46.3 ms: 1.01x slower                                                                                                      |
| pickle_list              | 6.76 us                                                                                                                | 6.85 us: 1.01x slower                                                                                                      |
| python_startup_no_site   | 9.39 ms                                                                                                                | 9.56 ms: 1.02x slower                                                                                                      |
| coverage                 | 122 ms                                                                                                                 | 124 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl          | 2.82 sec                                                                                                               | 2.87 sec: 1.02x slower                                                                                                     |
| pathlib                  | 21.4 ms                                                                                                                | 21.9 ms: 1.02x slower                                                                                                      |
| python_startup           | 16.2 ms                                                                                                                | 16.7 ms: 1.03x slower                                                                                                      |
| subparsers               | 58.4 ms                                                                                                                | 60.2 ms: 1.03x slower                                                                                                      |
| deltablue                | 4.77 ms                                                                                                                | 4.91 ms: 1.03x slower                                                                                                      |
| scimark_monte_carlo      | 96.1 ms                                                                                                                | 99.4 ms: 1.03x slower                                                                                                      |
| bench_thread_pool        | 1.11 ms                                                                                                                | 1.15 ms: 1.03x slower                                                                                                      |
| telco                    | 187 ms                                                                                                                 | 194 ms: 1.04x slower                                                                                                       |
| 2to3                     | 374 ms                                                                                                                 | 388 ms: 1.04x slower                                                                                                       |
| richards_super           | 71.0 ms                                                                                                                | 73.7 ms: 1.04x slower                                                                                                      |
| thrift                   | 1.13 ms                                                                                                                | 1.17 ms: 1.04x slower                                                                                                      |
| pyflate                  | 670 ms                                                                                                                 | 701 ms: 1.05x slower                                                                                                       |
| deepcopy_reduce          | 4.03 us                                                                                                                | 4.24 us: 1.05x slower                                                                                                      |
| scimark_sor              | 169 ms                                                                                                                 | 178 ms: 1.05x slower                                                                                                       |
| asyncio_tcp              | 650 ms                                                                                                                 | 685 ms: 1.05x slower                                                                                                       |
| meteor_contest           | 133 ms                                                                                                                 | 141 ms: 1.06x slower                                                                                                       |
| richards                 | 63.0 ms                                                                                                                | 66.7 ms: 1.06x slower                                                                                                      |
| tomli_loads              | 2.86 sec                                                                                                               | 3.04 sec: 1.06x slower                                                                                                     |
| fannkuch                 | 576 ms                                                                                                                 | 615 ms: 1.07x slower                                                                                                       |
| typing_runtime_protocols | 223 us                                                                                                                 | 239 us: 1.07x slower                                                                                                       |
| async_generators         | 559 ms                                                                                                                 | 598 ms: 1.07x slower                                                                                                       |
| sqlglot_v2_optimize      | 71.9 ms                                                                                                                | 79.2 ms: 1.10x slower                                                                                                      |
| crypto_pyaes             | 100 ms                                                                                                                 | 111 ms: 1.11x slower                                                                                                       |
| django_template          | 48.1 ms                                                                                                                | 53.9 ms: 1.12x slower                                                                                                      |
| sqlglot_v2_normalize     | 148 ms                                                                                                                 | 167 ms: 1.12x slower                                                                                                       |
| sqlglot_v2_transpile     | 2.08 ms                                                                                                                | 2.34 ms: 1.13x slower                                                                                                      |
| dulwich_log              | 77.5 ms                                                                                                                | 87.3 ms: 1.13x slower                                                                                                      |
| pylint                   | 392 ms                                                                                                                 | 441 ms: 1.13x slower                                                                                                       |
| raytrace                 | 381 ms                                                                                                                 | 431 ms: 1.13x slower                                                                                                       |
| many_optionals           | 1.26 ms                                                                                                                | 1.42 ms: 1.13x slower                                                                                                      |
| sqlglot_v2_parse         | 1.63 ms                                                                                                                | 1.85 ms: 1.14x slower                                                                                                      |
| html5lib                 | 92.1 ms                                                                                                                | 106 ms: 1.15x slower                                                                                                       |
| genshi_text              | 34.9 ms                                                                                                                | 40.1 ms: 1.15x slower                                                                                                      |
| sphinx                   | 1.39 sec                                                                                                               | 1.62 sec: 1.16x slower                                                                                                     |
| genshi_xml               | 98.3 ms                                                                                                                | 115 ms: 1.17x slower                                                                                                       |
| pycparser                | 1.61 sec                                                                                                               | 1.91 sec: 1.19x slower                                                                                                     |
| sympy_integrate          | 22.8 ms                                                                                                                | 27.2 ms: 1.19x slower                                                                                                      |
| regex_compile            | 144 ms                                                                                                                 | 175 ms: 1.21x slower                                                                                                       |
| deepcopy                 | 370 us                                                                                                                 | 455 us: 1.23x slower                                                                                                       |
| chaos                    | 80.2 ms                                                                                                                | 98.9 ms: 1.23x slower                                                                                                      |
| comprehensions           | 23.8 us                                                                                                                | 29.4 us: 1.23x slower                                                                                                      |
| sympy_sum                | 167 ms                                                                                                                 | 207 ms: 1.24x slower                                                                                                       |
| nqueens                  | 119 ms                                                                                                                 | 151 ms: 1.26x slower                                                                                                       |
| sympy_str                | 315 ms                                                                                                                 | 404 ms: 1.28x slower                                                                                                       |
| sympy_expand             | 543 ms                                                                                                                 | 699 ms: 1.29x slower                                                                                                       |
| hexiom                   | 8.93 ms                                                                                                                | 11.5 ms: 1.29x slower                                                                                                      |
| pprint_safe_repr         | 1.04 sec                                                                                                               | 1.38 sec: 1.33x slower                                                                                                     |
| pprint_pformat           | 2.12 sec                                                                                                               | 2.86 sec: 1.35x slower                                                                                                     |
| go                       | 160 ms                                                                                                                 | 225 ms: 1.41x slower                                                                                                       |
| unpack_sequence          | 67.6 ns                                                                                                                | 101 ns: 1.50x slower                                                                                                       |
| bench_mp_pool            | 121 ms                                                                                                                 | 220 ms: 1.82x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (15): async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_io, unpickle, pickle, regex_effbot, pickle_dict, nbody, asyncio_websockets, xml_etree_parse, async_tree_io_tg, async_tree_memoization_tg, async_tree_none

- Geometric mean (including insignificant results): 1.040x slower

# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x

# Memory
- memory change: 1.03x