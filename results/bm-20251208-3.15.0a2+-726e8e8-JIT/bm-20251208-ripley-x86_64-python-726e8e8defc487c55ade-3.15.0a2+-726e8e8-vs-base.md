# Results vs. base

- fork: python
- ref: 726e8e8defc487c55ade
- machine: linux-x86_64
- commit hash: 726e8e8
- commit date: 2025-12-08
- overall geometric mean: 1.020x faster
- HPT reliability: 57.69%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 249 ms                                                                                                             | 252 ms: 1.01x slower                                                                                                   |
| docutils       | 2.55 sec                                                                                                           | 2.72 sec: 1.07x slower                                                                                                 |
| html5lib       | 60.2 ms                                                                                                            | 67.2 ms: 1.12x slower                                                                                                  |
| sphinx         | 966 ms                                                                                                             | 1.01 sec: 1.05x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                              | 1.06x slower                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| asyncio_websockets         | 547 ms                                                                                                             | 548 ms: 1.00x slower                                                                                                   |
| asyncio_tcp_ssl            | 1.56 sec                                                                                                           | 1.57 sec: 1.01x slower                                                                                                 |
| async_tree_io_tg           | 598 ms                                                                                                             | 606 ms: 1.01x slower                                                                                                   |
| asyncio_tcp                | 436 ms                                                                                                             | 446 ms: 1.02x slower                                                                                                   |
| async_generators           | 344 ms                                                                                                             | 356 ms: 1.04x slower                                                                                                   |
| async_tree_cpu_io_mixed_tg | 485 ms                                                                                                             | 530 ms: 1.09x slower                                                                                                   |
| async_tree_cpu_io_mixed    | 485 ms                                                                                                             | 531 ms: 1.09x slower                                                                                                   |
| Geometric mean             | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmark hidden because not significant (6): coroutines, async_tree_memoization_tg, async_tree_none, async_tree_memoization, async_tree_none_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| float          | 70.5 ms                                                                                                            | 61.2 ms: 1.15x faster                                                                                                  |
| nbody          | 89.5 ms                                                                                                            | 83.6 ms: 1.07x faster                                                                                                  |
| pidigits       | 197 ms                                                                                                             | 214 ms: 1.09x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 22.6 ms                                                                                                            | 20.5 ms: 1.10x faster                                                                                                  |
| regex_effbot   | 2.79 ms                                                                                                            | 2.66 ms: 1.05x faster                                                                                                  |
| regex_dna      | 180 ms                                                                                                             | 174 ms: 1.04x faster                                                                                                   |
| regex_compile  | 124 ms                                                                                                             | 124 ms: 1.00x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 214 us                                                                                                             | 180 us: 1.19x faster                                                                                                   |
| pickle_pure_python   | 311 us                                                                                                             | 289 us: 1.08x faster                                                                                                   |
| xml_etree_process    | 58.0 ms                                                                                                            | 54.2 ms: 1.07x faster                                                                                                  |
| xml_etree_generate   | 82.4 ms                                                                                                            | 77.5 ms: 1.06x faster                                                                                                  |
| json_dumps           | 10.0 ms                                                                                                            | 9.49 ms: 1.05x faster                                                                                                  |
| xml_etree_iterparse  | 86.0 ms                                                                                                            | 84.2 ms: 1.02x faster                                                                                                  |
| unpickle_list        | 5.18 us                                                                                                            | 5.16 us: 1.01x faster                                                                                                  |
| xml_etree_parse      | 131 ms                                                                                                             | 130 ms: 1.00x faster                                                                                                   |
| unpickle             | 14.4 us                                                                                                            | 14.6 us: 1.01x slower                                                                                                  |
| json_loads           | 28.3 us                                                                                                            | 28.7 us: 1.01x slower                                                                                                  |
| pickle               | 12.1 us                                                                                                            | 13.0 us: 1.07x slower                                                                                                  |
| pickle_dict          | 30.3 us                                                                                                            | 32.5 us: 1.07x slower                                                                                                  |
| tomli_loads          | 2.16 sec                                                                                                           | 2.32 sec: 1.08x slower                                                                                                 |
| pickle_list          | 4.95 us                                                                                                            | 5.41 us: 1.09x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                                                            | 12.8 ms: 1.00x slower                                                                                                  |
| python_startup_no_site | 7.54 ms                                                                                                            | 7.59 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.00x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 12.0 ms                                                                                                            | 10.4 ms: 1.16x faster                                                                                                  |
| genshi_text     | 20.6 ms                                                                                                            | 21.2 ms: 1.03x slower                                                                                                  |
| django_template | 35.0 ms                                                                                                            | 36.0 ms: 1.03x slower                                                                                                  |
| genshi_xml      | 48.5 ms                                                                                                            | 53.7 ms: 1.11x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.00x slower                                                                                                           |

All benchmarks:
===============

| Benchmark                  | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                   | 41.6 ms                                                                                                            | 20.9 ms: 1.99x faster                                                                                                  |
| richards_super             | 47.6 ms                                                                                                            | 25.3 ms: 1.88x faster                                                                                                  |
| scimark_fft                | 310 ms                                                                                                             | 255 ms: 1.22x faster                                                                                                   |
| bench_mp_pool              | 252 ms                                                                                                             | 210 ms: 1.20x faster                                                                                                   |
| unpickle_pure_python       | 214 us                                                                                                             | 180 us: 1.19x faster                                                                                                   |
| spectral_norm              | 97.2 ms                                                                                                            | 83.1 ms: 1.17x faster                                                                                                  |
| logging_silent             | 101 ns                                                                                                             | 86.9 ns: 1.16x faster                                                                                                  |
| mako                       | 12.0 ms                                                                                                            | 10.4 ms: 1.16x faster                                                                                                  |
| float                      | 70.5 ms                                                                                                            | 61.2 ms: 1.15x faster                                                                                                  |
| deltablue                  | 3.30 ms                                                                                                            | 2.87 ms: 1.15x faster                                                                                                  |
| scimark_monte_carlo        | 62.0 ms                                                                                                            | 55.1 ms: 1.12x faster                                                                                                  |
| pyflate                    | 422 ms                                                                                                             | 376 ms: 1.12x faster                                                                                                   |
| fannkuch                   | 398 ms                                                                                                             | 355 ms: 1.12x faster                                                                                                   |
| scimark_sor                | 108 ms                                                                                                             | 97.5 ms: 1.11x faster                                                                                                  |
| regex_v8                   | 22.6 ms                                                                                                            | 20.5 ms: 1.10x faster                                                                                                  |
| deepcopy_memo              | 27.7 us                                                                                                            | 25.3 us: 1.10x faster                                                                                                  |
| scimark_lu                 | 111 ms                                                                                                             | 102 ms: 1.09x faster                                                                                                   |
| pickle_pure_python         | 311 us                                                                                                             | 289 us: 1.08x faster                                                                                                   |
| xml_etree_process          | 58.0 ms                                                                                                            | 54.2 ms: 1.07x faster                                                                                                  |
| nbody                      | 89.5 ms                                                                                                            | 83.6 ms: 1.07x faster                                                                                                  |
| xml_etree_generate         | 82.4 ms                                                                                                            | 77.5 ms: 1.06x faster                                                                                                  |
| bpe_tokeniser              | 4.25 sec                                                                                                           | 4.01 sec: 1.06x faster                                                                                                 |
| json_dumps                 | 10.0 ms                                                                                                            | 9.49 ms: 1.05x faster                                                                                                  |
| crypto_pyaes               | 69.8 ms                                                                                                            | 66.3 ms: 1.05x faster                                                                                                  |
| regex_effbot               | 2.79 ms                                                                                                            | 2.66 ms: 1.05x faster                                                                                                  |
| pprint_safe_repr           | 703 ms                                                                                                             | 673 ms: 1.05x faster                                                                                                   |
| deepcopy_reduce            | 2.64 us                                                                                                            | 2.53 us: 1.04x faster                                                                                                  |
| comprehensions             | 16.3 us                                                                                                            | 15.6 us: 1.04x faster                                                                                                  |
| pprint_pformat             | 1.44 sec                                                                                                           | 1.38 sec: 1.04x faster                                                                                                 |
| go                         | 106 ms                                                                                                             | 102 ms: 1.04x faster                                                                                                   |
| regex_dna                  | 180 ms                                                                                                             | 174 ms: 1.04x faster                                                                                                   |
| connected_components       | 377 ms                                                                                                             | 366 ms: 1.03x faster                                                                                                   |
| scimark_sparse_mat_mult    | 4.30 ms                                                                                                            | 4.19 ms: 1.03x faster                                                                                                  |
| json                       | 5.13 ms                                                                                                            | 5.01 ms: 1.02x faster                                                                                                  |
| xml_etree_iterparse        | 86.0 ms                                                                                                            | 84.2 ms: 1.02x faster                                                                                                  |
| shortest_path              | 418 ms                                                                                                             | 409 ms: 1.02x faster                                                                                                   |
| logging_simple             | 5.79 us                                                                                                            | 5.73 us: 1.01x faster                                                                                                  |
| deepcopy                   | 247 us                                                                                                             | 244 us: 1.01x faster                                                                                                   |
| meteor_contest             | 99.2 ms                                                                                                            | 98.5 ms: 1.01x faster                                                                                                  |
| telco                      | 160 ms                                                                                                             | 159 ms: 1.01x faster                                                                                                   |
| k_core                     | 1.83 sec                                                                                                           | 1.81 sec: 1.01x faster                                                                                                 |
| unpickle_list              | 5.18 us                                                                                                            | 5.16 us: 1.01x faster                                                                                                  |
| xml_etree_parse            | 131 ms                                                                                                             | 130 ms: 1.00x faster                                                                                                   |
| regex_compile              | 124 ms                                                                                                             | 124 ms: 1.00x faster                                                                                                   |
| asyncio_websockets         | 547 ms                                                                                                             | 548 ms: 1.00x slower                                                                                                   |
| python_startup             | 12.8 ms                                                                                                            | 12.8 ms: 1.00x slower                                                                                                  |
| coverage                   | 82.3 ms                                                                                                            | 82.6 ms: 1.00x slower                                                                                                  |
| logging_format             | 6.47 us                                                                                                            | 6.50 us: 1.00x slower                                                                                                  |
| python_startup_no_site     | 7.54 ms                                                                                                            | 7.59 ms: 1.01x slower                                                                                                  |
| generators                 | 29.2 ms                                                                                                            | 29.4 ms: 1.01x slower                                                                                                  |
| subparsers                 | 9.18 ms                                                                                                            | 9.25 ms: 1.01x slower                                                                                                  |
| sqlglot_v2_transpile       | 1.51 ms                                                                                                            | 1.52 ms: 1.01x slower                                                                                                  |
| asyncio_tcp_ssl            | 1.56 sec                                                                                                           | 1.57 sec: 1.01x slower                                                                                                 |
| unpickle                   | 14.4 us                                                                                                            | 14.6 us: 1.01x slower                                                                                                  |
| sqlglot_v2_parse           | 1.22 ms                                                                                                            | 1.23 ms: 1.01x slower                                                                                                  |
| async_tree_io_tg           | 598 ms                                                                                                             | 606 ms: 1.01x slower                                                                                                   |
| 2to3                       | 249 ms                                                                                                             | 252 ms: 1.01x slower                                                                                                   |
| json_loads                 | 28.3 us                                                                                                            | 28.7 us: 1.01x slower                                                                                                  |
| typing_runtime_protocols   | 156 us                                                                                                             | 158 us: 1.01x slower                                                                                                   |
| bench_thread_pool          | 1.21 ms                                                                                                            | 1.23 ms: 1.01x slower                                                                                                  |
| pycparser                  | 1.08 sec                                                                                                           | 1.10 sec: 1.02x slower                                                                                                 |
| sqlite_synth               | 2.24 us                                                                                                            | 2.28 us: 1.02x slower                                                                                                  |
| asyncio_tcp                | 436 ms                                                                                                             | 446 ms: 1.02x slower                                                                                                   |
| genshi_text                | 20.6 ms                                                                                                            | 21.2 ms: 1.03x slower                                                                                                  |
| django_template            | 35.0 ms                                                                                                            | 36.0 ms: 1.03x slower                                                                                                  |
| async_generators           | 344 ms                                                                                                             | 356 ms: 1.04x slower                                                                                                   |
| raytrace                   | 253 ms                                                                                                             | 263 ms: 1.04x slower                                                                                                   |
| sphinx                     | 966 ms                                                                                                             | 1.01 sec: 1.05x slower                                                                                                 |
| hexiom                     | 5.81 ms                                                                                                            | 6.12 ms: 1.05x slower                                                                                                  |
| sqlglot_v2_normalize       | 102 ms                                                                                                             | 108 ms: 1.05x slower                                                                                                   |
| many_optionals             | 940 us                                                                                                             | 995 us: 1.06x slower                                                                                                   |
| nqueens                    | 78.9 ms                                                                                                            | 83.6 ms: 1.06x slower                                                                                                  |
| sqlglot_v2_optimize        | 51.1 ms                                                                                                            | 54.2 ms: 1.06x slower                                                                                                  |
| docutils                   | 2.55 sec                                                                                                           | 2.72 sec: 1.07x slower                                                                                                 |
| pickle                     | 12.1 us                                                                                                            | 13.0 us: 1.07x slower                                                                                                  |
| pickle_dict                | 30.3 us                                                                                                            | 32.5 us: 1.07x slower                                                                                                  |
| tomli_loads                | 2.16 sec                                                                                                           | 2.32 sec: 1.08x slower                                                                                                 |
| gc_traversal               | 4.20 ms                                                                                                            | 4.55 ms: 1.08x slower                                                                                                  |
| pidigits                   | 197 ms                                                                                                             | 214 ms: 1.09x slower                                                                                                   |
| dulwich_log                | 67.1 ms                                                                                                            | 73.1 ms: 1.09x slower                                                                                                  |
| sympy_integrate            | 19.1 ms                                                                                                            | 20.9 ms: 1.09x slower                                                                                                  |
| pickle_list                | 4.95 us                                                                                                            | 5.41 us: 1.09x slower                                                                                                  |
| async_tree_cpu_io_mixed_tg | 485 ms                                                                                                             | 530 ms: 1.09x slower                                                                                                   |
| pylint                     | 285 ms                                                                                                             | 312 ms: 1.09x slower                                                                                                   |
| async_tree_cpu_io_mixed    | 485 ms                                                                                                             | 531 ms: 1.09x slower                                                                                                   |
| sympy_expand               | 458 ms                                                                                                             | 502 ms: 1.10x slower                                                                                                   |
| genshi_xml                 | 48.5 ms                                                                                                            | 53.7 ms: 1.11x slower                                                                                                  |
| sympy_sum                  | 154 ms                                                                                                             | 171 ms: 1.12x slower                                                                                                   |
| html5lib                   | 60.2 ms                                                                                                            | 67.2 ms: 1.12x slower                                                                                                  |
| mdp                        | 1.17 sec                                                                                                           | 1.34 sec: 1.14x slower                                                                                                 |
| sympy_str                  | 270 ms                                                                                                             | 308 ms: 1.14x slower                                                                                                   |
| unpack_sequence            | 41.6 ns                                                                                                            | 90.5 ns: 2.17x slower                                                                                                  |
| Geometric mean             | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmark hidden because not significant (10): coroutines, thrift, chaos, pathlib, async_tree_memoization_tg, create_gc_cycles, async_tree_none, async_tree_memoization, async_tree_none_tg, async_tree_io

- Geometric mean (including insignificant results): 1.020x faster

# HPT report

- Reliability score: 57.69% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.02x