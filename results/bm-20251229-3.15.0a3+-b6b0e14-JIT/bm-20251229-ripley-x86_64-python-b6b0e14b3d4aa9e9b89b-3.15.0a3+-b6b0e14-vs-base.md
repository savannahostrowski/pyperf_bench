# Results vs. base

- fork: python
- ref: b6b0e14b3d4aa9e9b89b
- machine: linux-x86_64
- commit hash: b6b0e14
- commit date: 2025-12-29
- overall geometric mean: 1.030x faster
- HPT reliability: 79.35%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 353 ms                                                                                                             | 352 ms: 1.00x faster                                                                                                   |
| docutils       | 3.61 sec                                                                                                           | 3.84 sec: 1.07x slower                                                                                                 |
| html5lib       | 85.0 ms                                                                                                            | 91.8 ms: 1.08x slower                                                                                                  |
| sphinx         | 1.37 sec                                                                                                           | 1.41 sec: 1.03x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                              | 1.03x slower                                                                                                           |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| coroutines                 | 34.2 ms                                                                                                            | 33.5 ms: 1.02x faster                                                                                                  |
| asyncio_tcp                | 552 ms                                                                                                             | 546 ms: 1.01x faster                                                                                                   |
| asyncio_tcp_ssl            | 2.05 sec                                                                                                           | 2.03 sec: 1.01x faster                                                                                                 |
| async_tree_memoization_tg  | 411 ms                                                                                                             | 413 ms: 1.01x slower                                                                                                   |
| async_tree_io_tg           | 798 ms                                                                                                             | 802 ms: 1.01x slower                                                                                                   |
| async_generators           | 479 ms                                                                                                             | 506 ms: 1.06x slower                                                                                                   |
| async_tree_cpu_io_mixed_tg | 684 ms                                                                                                             | 743 ms: 1.09x slower                                                                                                   |
| async_tree_cpu_io_mixed    | 685 ms                                                                                                             | 746 ms: 1.09x slower                                                                                                   |
| Geometric mean             | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmark hidden because not significant (5): async_tree_none_tg, async_tree_memoization, asyncio_websockets, async_tree_io, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 136 ms                                                                                                             | 106 ms: 1.29x faster                                                                                                   |
| float          | 101 ms                                                                                                             | 84.3 ms: 1.20x faster                                                                                                  |
| pidigits       | 276 ms                                                                                                             | 309 ms: 1.12x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.11x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 32.2 ms                                                                                                            | 30.3 ms: 1.06x faster                                                                                                  |
| regex_effbot   | 4.00 ms                                                                                                            | 3.87 ms: 1.03x faster                                                                                                  |
| regex_compile  | 176 ms                                                                                                             | 174 ms: 1.01x faster                                                                                                   |
| regex_dna      | 248 ms                                                                                                             | 250 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 299 us                                                                                                             | 253 us: 1.18x faster                                                                                                   |
| pickle_pure_python   | 440 us                                                                                                             | 398 us: 1.11x faster                                                                                                   |
| json_dumps           | 14.2 ms                                                                                                            | 13.2 ms: 1.08x faster                                                                                                  |
| tomli_loads          | 2.99 sec                                                                                                           | 2.82 sec: 1.06x faster                                                                                                 |
| xml_etree_generate   | 118 ms                                                                                                             | 111 ms: 1.06x faster                                                                                                   |
| xml_etree_process    | 81.7 ms                                                                                                            | 78.9 ms: 1.04x faster                                                                                                  |
| pickle_dict          | 47.4 us                                                                                                            | 46.4 us: 1.02x faster                                                                                                  |
| pickle               | 18.5 us                                                                                                            | 18.1 us: 1.02x faster                                                                                                  |
| pickle_list          | 7.66 us                                                                                                            | 7.52 us: 1.02x faster                                                                                                  |
| xml_etree_parse      | 187 ms                                                                                                             | 185 ms: 1.01x faster                                                                                                   |
| unpickle             | 20.8 us                                                                                                            | 20.7 us: 1.01x faster                                                                                                  |
| json_loads           | 39.9 us                                                                                                            | 40.6 us: 1.02x slower                                                                                                  |
| unpickle_list        | 7.45 us                                                                                                            | 7.63 us: 1.02x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.7 ms                                                                                                            | 17.8 ms: 1.01x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.0 ms                                                                                                            | 15.3 ms: 1.11x faster                                                                                                  |
| django_template | 50.9 ms                                                                                                            | 50.0 ms: 1.02x faster                                                                                                  |
| genshi_xml      | 70.1 ms                                                                                                            | 75.3 ms: 1.07x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmark hidden because not significant (1): genshi_text

All benchmarks:
===============

| Benchmark                  | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-ripley-x86_64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                   | 60.8 ms                                                                                                            | 26.1 ms: 2.33x faster                                                                                                  |
| richards_super             | 69.3 ms                                                                                                            | 31.4 ms: 2.21x faster                                                                                                  |
| nbody                      | 136 ms                                                                                                             | 106 ms: 1.29x faster                                                                                                   |
| deltablue                  | 4.71 ms                                                                                                            | 3.83 ms: 1.23x faster                                                                                                  |
| logging_silent             | 146 ns                                                                                                             | 119 ns: 1.23x faster                                                                                                   |
| float                      | 101 ms                                                                                                             | 84.3 ms: 1.20x faster                                                                                                  |
| unpickle_pure_python       | 299 us                                                                                                             | 253 us: 1.18x faster                                                                                                   |
| scimark_fft                | 440 ms                                                                                                             | 376 ms: 1.17x faster                                                                                                   |
| bench_mp_pool              | 264 ms                                                                                                             | 228 ms: 1.16x faster                                                                                                   |
| scimark_monte_carlo        | 88.3 ms                                                                                                            | 76.1 ms: 1.16x faster                                                                                                  |
| go                         | 150 ms                                                                                                             | 132 ms: 1.14x faster                                                                                                   |
| pyflate                    | 588 ms                                                                                                             | 518 ms: 1.14x faster                                                                                                   |
| mako                       | 17.0 ms                                                                                                            | 15.3 ms: 1.11x faster                                                                                                  |
| pickle_pure_python         | 440 us                                                                                                             | 398 us: 1.11x faster                                                                                                   |
| fannkuch                   | 550 ms                                                                                                             | 502 ms: 1.10x faster                                                                                                   |
| scimark_lu                 | 154 ms                                                                                                             | 142 ms: 1.08x faster                                                                                                   |
| json_dumps                 | 14.2 ms                                                                                                            | 13.2 ms: 1.08x faster                                                                                                  |
| spectral_norm              | 133 ms                                                                                                             | 125 ms: 1.07x faster                                                                                                   |
| pprint_safe_repr           | 991 ms                                                                                                             | 931 ms: 1.06x faster                                                                                                   |
| deepcopy_memo              | 37.4 us                                                                                                            | 35.1 us: 1.06x faster                                                                                                  |
| regex_v8                   | 32.2 ms                                                                                                            | 30.3 ms: 1.06x faster                                                                                                  |
| scimark_sor                | 153 ms                                                                                                             | 144 ms: 1.06x faster                                                                                                   |
| tomli_loads                | 2.99 sec                                                                                                           | 2.82 sec: 1.06x faster                                                                                                 |
| meteor_contest             | 148 ms                                                                                                             | 140 ms: 1.06x faster                                                                                                   |
| pprint_pformat             | 2.02 sec                                                                                                           | 1.90 sec: 1.06x faster                                                                                                 |
| xml_etree_generate         | 118 ms                                                                                                             | 111 ms: 1.06x faster                                                                                                   |
| chaos                      | 79.2 ms                                                                                                            | 75.3 ms: 1.05x faster                                                                                                  |
| crypto_pyaes               | 98.4 ms                                                                                                            | 93.6 ms: 1.05x faster                                                                                                  |
| thrift                     | 1.11 ms                                                                                                            | 1.06 ms: 1.05x faster                                                                                                  |
| bpe_tokeniser              | 6.01 sec                                                                                                           | 5.76 sec: 1.04x faster                                                                                                 |
| xml_etree_process          | 81.7 ms                                                                                                            | 78.9 ms: 1.04x faster                                                                                                  |
| sqlite_synth               | 3.27 us                                                                                                            | 3.16 us: 1.03x faster                                                                                                  |
| scimark_sparse_mat_mult    | 6.51 ms                                                                                                            | 6.31 ms: 1.03x faster                                                                                                  |
| regex_effbot               | 4.00 ms                                                                                                            | 3.87 ms: 1.03x faster                                                                                                  |
| deepcopy_reduce            | 3.70 us                                                                                                            | 3.60 us: 1.03x faster                                                                                                  |
| json                       | 7.31 ms                                                                                                            | 7.13 ms: 1.02x faster                                                                                                  |
| logging_format             | 9.58 us                                                                                                            | 9.36 us: 1.02x faster                                                                                                  |
| pickle_dict                | 47.4 us                                                                                                            | 46.4 us: 1.02x faster                                                                                                  |
| pickle                     | 18.5 us                                                                                                            | 18.1 us: 1.02x faster                                                                                                  |
| coroutines                 | 34.2 ms                                                                                                            | 33.5 ms: 1.02x faster                                                                                                  |
| pickle_list                | 7.66 us                                                                                                            | 7.52 us: 1.02x faster                                                                                                  |
| shortest_path              | 508 ms                                                                                                             | 498 ms: 1.02x faster                                                                                                   |
| django_template            | 50.9 ms                                                                                                            | 50.0 ms: 1.02x faster                                                                                                  |
| connected_components       | 454 ms                                                                                                             | 446 ms: 1.02x faster                                                                                                   |
| logging_simple             | 8.41 us                                                                                                            | 8.27 us: 1.02x faster                                                                                                  |
| regex_compile              | 176 ms                                                                                                             | 174 ms: 1.01x faster                                                                                                   |
| deepcopy                   | 342 us                                                                                                             | 338 us: 1.01x faster                                                                                                   |
| asyncio_tcp                | 552 ms                                                                                                             | 546 ms: 1.01x faster                                                                                                   |
| sqlalchemy_imperative      | 29.0 ms                                                                                                            | 28.7 ms: 1.01x faster                                                                                                  |
| xml_etree_parse            | 187 ms                                                                                                             | 185 ms: 1.01x faster                                                                                                   |
| asyncio_tcp_ssl            | 2.05 sec                                                                                                           | 2.03 sec: 1.01x faster                                                                                                 |
| k_core                     | 2.22 sec                                                                                                           | 2.20 sec: 1.01x faster                                                                                                 |
| sqlglot_v2_parse           | 1.69 ms                                                                                                            | 1.68 ms: 1.01x faster                                                                                                  |
| unpickle                   | 20.8 us                                                                                                            | 20.7 us: 1.01x faster                                                                                                  |
| 2to3                       | 353 ms                                                                                                             | 352 ms: 1.00x faster                                                                                                   |
| async_tree_memoization_tg  | 411 ms                                                                                                             | 413 ms: 1.01x slower                                                                                                   |
| async_tree_io_tg           | 798 ms                                                                                                             | 802 ms: 1.01x slower                                                                                                   |
| python_startup             | 17.7 ms                                                                                                            | 17.8 ms: 1.01x slower                                                                                                  |
| regex_dna                  | 248 ms                                                                                                             | 250 ms: 1.01x slower                                                                                                   |
| pathlib                    | 25.1 ms                                                                                                            | 25.3 ms: 1.01x slower                                                                                                  |
| telco                      | 227 ms                                                                                                             | 228 ms: 1.01x slower                                                                                                   |
| python_startup_no_site     | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| sqlalchemy_declarative     | 185 ms                                                                                                             | 187 ms: 1.01x slower                                                                                                   |
| generators                 | 40.2 ms                                                                                                            | 40.7 ms: 1.01x slower                                                                                                  |
| create_gc_cycles           | 2.82 ms                                                                                                            | 2.87 ms: 1.02x slower                                                                                                  |
| json_loads                 | 39.9 us                                                                                                            | 40.6 us: 1.02x slower                                                                                                  |
| unpickle_list              | 7.45 us                                                                                                            | 7.63 us: 1.02x slower                                                                                                  |
| sphinx                     | 1.37 sec                                                                                                           | 1.41 sec: 1.03x slower                                                                                                 |
| xdsl_constant_fold         | 65.1 ms                                                                                                            | 67.4 ms: 1.04x slower                                                                                                  |
| many_optionals             | 1.37 ms                                                                                                            | 1.42 ms: 1.04x slower                                                                                                  |
| pycparser                  | 1.53 sec                                                                                                           | 1.60 sec: 1.05x slower                                                                                                 |
| sympy_integrate            | 27.3 ms                                                                                                            | 28.5 ms: 1.05x slower                                                                                                  |
| raytrace                   | 361 ms                                                                                                             | 378 ms: 1.05x slower                                                                                                   |
| async_generators           | 479 ms                                                                                                             | 506 ms: 1.06x slower                                                                                                   |
| sqlglot_v2_optimize        | 72.8 ms                                                                                                            | 76.9 ms: 1.06x slower                                                                                                  |
| sympy_expand               | 692 ms                                                                                                             | 732 ms: 1.06x slower                                                                                                   |
| gc_traversal               | 5.86 ms                                                                                                            | 6.22 ms: 1.06x slower                                                                                                  |
| docutils                   | 3.61 sec                                                                                                           | 3.84 sec: 1.07x slower                                                                                                 |
| hexiom                     | 8.01 ms                                                                                                            | 8.58 ms: 1.07x slower                                                                                                  |
| dulwich_log                | 96.6 ms                                                                                                            | 104 ms: 1.07x slower                                                                                                   |
| genshi_xml                 | 70.1 ms                                                                                                            | 75.3 ms: 1.07x slower                                                                                                  |
| html5lib                   | 85.0 ms                                                                                                            | 91.8 ms: 1.08x slower                                                                                                  |
| sqlglot_v2_normalize       | 144 ms                                                                                                             | 155 ms: 1.08x slower                                                                                                   |
| pylint                     | 401 ms                                                                                                             | 433 ms: 1.08x slower                                                                                                   |
| sympy_sum                  | 222 ms                                                                                                             | 240 ms: 1.08x slower                                                                                                   |
| async_tree_cpu_io_mixed_tg | 684 ms                                                                                                             | 743 ms: 1.09x slower                                                                                                   |
| nqueens                    | 112 ms                                                                                                             | 122 ms: 1.09x slower                                                                                                   |
| async_tree_cpu_io_mixed    | 685 ms                                                                                                             | 746 ms: 1.09x slower                                                                                                   |
| sympy_str                  | 397 ms                                                                                                             | 435 ms: 1.10x slower                                                                                                   |
| pidigits                   | 276 ms                                                                                                             | 309 ms: 1.12x slower                                                                                                   |
| mdp                        | 1.65 sec                                                                                                           | 1.94 sec: 1.17x slower                                                                                                 |
| unpack_sequence            | 56.9 ns                                                                                                            | 68.0 ns: 1.19x slower                                                                                                  |
| Geometric mean             | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (15): async_tree_none_tg, async_tree_memoization, tornado_http, xml_etree_iterparse, genshi_text, bench_thread_pool, subparsers, chameleon, asyncio_websockets, comprehensions, typing_runtime_protocols, coverage, async_tree_io, sqlglot_v2_transpile, async_tree_none

- Geometric mean (including insignificant results): 1.030x faster

# HPT report

- Reliability score: 79.35% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x