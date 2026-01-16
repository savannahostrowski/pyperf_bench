# Results vs. base

- fork: python
- ref: c461aa99e2fabbaf5859
- machine: linux-x86_64
- commit hash: c461aa9
- commit date: 2026-01-15
- overall geometric mean: 1.045x faster
- HPT reliability: 99.53%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 19.0 ms                                                                                                            | 18.9 ms: 1.01x faster                                                                                                  |
| docutils       | 3.60 sec                                                                                                           | 3.79 sec: 1.05x slower                                                                                                 |
| html5lib       | 85.5 ms                                                                                                            | 90.7 ms: 1.06x slower                                                                                                  |
| sphinx         | 1.36 sec                                                                                                           | 1.42 sec: 1.04x slower                                                                                                 |
| tornado_http   | 191 ms                                                                                                             | 193 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_none           | 336 ms                                                                                                             | 324 ms: 1.04x faster                                                                                                   |
| async_tree_memoization    | 417 ms                                                                                                             | 403 ms: 1.04x faster                                                                                                   |
| async_tree_memoization_tg | 409 ms                                                                                                             | 395 ms: 1.03x faster                                                                                                   |
| async_tree_none_tg        | 348 ms                                                                                                             | 337 ms: 1.03x faster                                                                                                   |
| async_tree_io             | 761 ms                                                                                                             | 746 ms: 1.02x faster                                                                                                   |
| async_tree_cpu_io_mixed   | 672 ms                                                                                                             | 659 ms: 1.02x faster                                                                                                   |
| asyncio_tcp_ssl           | 2.08 sec                                                                                                           | 2.04 sec: 1.02x faster                                                                                                 |
| async_tree_io_tg          | 773 ms                                                                                                             | 761 ms: 1.02x faster                                                                                                   |
| asyncio_websockets        | 780 ms                                                                                                             | 779 ms: 1.00x faster                                                                                                   |
| coroutines                | 33.5 ms                                                                                                            | 34.3 ms: 1.03x slower                                                                                                  |
| asyncio_tcp               | 559 ms                                                                                                             | 574 ms: 1.03x slower                                                                                                   |
| async_generators          | 482 ms                                                                                                             | 505 ms: 1.05x slower                                                                                                   |
| Geometric mean            | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 133 ms                                                                                                             | 105 ms: 1.27x faster                                                                                                   |
| float          | 102 ms                                                                                                             | 81.4 ms: 1.25x faster                                                                                                  |
| pidigits       | 287 ms                                                                                                             | 291 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.16x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 179 ms                                                                                                             | 171 ms: 1.05x faster                                                                                                   |
| regex_v8       | 31.6 ms                                                                                                            | 30.7 ms: 1.03x faster                                                                                                  |
| regex_effbot   | 3.89 ms                                                                                                            | 3.92 ms: 1.01x slower                                                                                                  |
| regex_dna      | 237 ms                                                                                                             | 253 ms: 1.07x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.00x slower                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 306 us                                                                                                             | 252 us: 1.21x faster                                                                                                   |
| tomli_loads          | 2.66 sec                                                                                                           | 2.36 sec: 1.13x faster                                                                                                 |
| pickle_pure_python   | 442 us                                                                                                             | 395 us: 1.12x faster                                                                                                   |
| json_dumps           | 14.2 ms                                                                                                            | 13.2 ms: 1.08x faster                                                                                                  |
| xml_etree_process    | 83.3 ms                                                                                                            | 77.2 ms: 1.08x faster                                                                                                  |
| xml_etree_generate   | 118 ms                                                                                                             | 111 ms: 1.07x faster                                                                                                   |
| pickle_dict          | 47.3 us                                                                                                            | 45.5 us: 1.04x faster                                                                                                  |
| pickle_list          | 7.41 us                                                                                                            | 7.25 us: 1.02x faster                                                                                                  |
| xml_etree_iterparse  | 121 ms                                                                                                             | 119 ms: 1.02x faster                                                                                                   |
| xml_etree_parse      | 188 ms                                                                                                             | 186 ms: 1.01x faster                                                                                                   |
| unpickle_list        | 7.37 us                                                                                                            | 7.59 us: 1.03x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (3): pickle, json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| python_startup         | 17.8 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.0 ms                                                                                                            | 15.4 ms: 1.11x faster                                                                                                  |
| genshi_text     | 30.7 ms                                                                                                            | 29.9 ms: 1.03x faster                                                                                                  |
| django_template | 49.8 ms                                                                                                            | 50.9 ms: 1.02x slower                                                                                                  |
| genshi_xml      | 71.8 ms                                                                                                            | 77.8 ms: 1.08x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.01x faster                                                                                                           |

All benchmarks:
===============

| Benchmark                 | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-ripley-x86_64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                  | 60.3 ms                                                                                                            | 26.2 ms: 2.30x faster                                                                                                  |
| richards_super            | 69.7 ms                                                                                                            | 31.8 ms: 2.19x faster                                                                                                  |
| scimark_lu                | 152 ms                                                                                                             | 111 ms: 1.37x faster                                                                                                   |
| nbody                     | 133 ms                                                                                                             | 105 ms: 1.27x faster                                                                                                   |
| float                     | 102 ms                                                                                                             | 81.4 ms: 1.25x faster                                                                                                  |
| scimark_sor               | 152 ms                                                                                                             | 123 ms: 1.23x faster                                                                                                   |
| scimark_monte_carlo       | 88.8 ms                                                                                                            | 72.6 ms: 1.22x faster                                                                                                  |
| logging_silent            | 142 ns                                                                                                             | 117 ns: 1.21x faster                                                                                                   |
| unpickle_pure_python      | 306 us                                                                                                             | 252 us: 1.21x faster                                                                                                   |
| deltablue                 | 4.73 ms                                                                                                            | 3.91 ms: 1.21x faster                                                                                                  |
| scimark_fft               | 443 ms                                                                                                             | 370 ms: 1.20x faster                                                                                                   |
| pyflate                   | 592 ms                                                                                                             | 511 ms: 1.16x faster                                                                                                   |
| go                        | 151 ms                                                                                                             | 132 ms: 1.14x faster                                                                                                   |
| fannkuch                  | 563 ms                                                                                                             | 497 ms: 1.13x faster                                                                                                   |
| tomli_loads               | 2.66 sec                                                                                                           | 2.36 sec: 1.13x faster                                                                                                 |
| pickle_pure_python        | 442 us                                                                                                             | 395 us: 1.12x faster                                                                                                   |
| spectral_norm             | 135 ms                                                                                                             | 121 ms: 1.12x faster                                                                                                   |
| mako                      | 17.0 ms                                                                                                            | 15.4 ms: 1.11x faster                                                                                                  |
| deepcopy_memo             | 37.9 us                                                                                                            | 34.8 us: 1.09x faster                                                                                                  |
| pprint_pformat            | 2.04 sec                                                                                                           | 1.87 sec: 1.09x faster                                                                                                 |
| gc_traversal              | 6.80 ms                                                                                                            | 6.27 ms: 1.09x faster                                                                                                  |
| json_dumps                | 14.2 ms                                                                                                            | 13.2 ms: 1.08x faster                                                                                                  |
| xml_etree_process         | 83.3 ms                                                                                                            | 77.2 ms: 1.08x faster                                                                                                  |
| pprint_safe_repr          | 990 ms                                                                                                             | 922 ms: 1.07x faster                                                                                                   |
| chaos                     | 80.7 ms                                                                                                            | 75.4 ms: 1.07x faster                                                                                                  |
| xml_etree_generate        | 118 ms                                                                                                             | 111 ms: 1.07x faster                                                                                                   |
| deepcopy_reduce           | 3.66 us                                                                                                            | 3.43 us: 1.07x faster                                                                                                  |
| sqlite_synth              | 3.31 us                                                                                                            | 3.12 us: 1.06x faster                                                                                                  |
| crypto_pyaes              | 101 ms                                                                                                             | 95.3 ms: 1.06x faster                                                                                                  |
| regex_compile             | 179 ms                                                                                                             | 171 ms: 1.05x faster                                                                                                   |
| pickle_dict               | 47.3 us                                                                                                            | 45.5 us: 1.04x faster                                                                                                  |
| bpe_tokeniser             | 6.03 sec                                                                                                           | 5.80 sec: 1.04x faster                                                                                                 |
| scimark_sparse_mat_mult   | 6.28 ms                                                                                                            | 6.04 ms: 1.04x faster                                                                                                  |
| async_tree_none           | 336 ms                                                                                                             | 324 ms: 1.04x faster                                                                                                   |
| async_tree_memoization    | 417 ms                                                                                                             | 403 ms: 1.04x faster                                                                                                   |
| async_tree_memoization_tg | 409 ms                                                                                                             | 395 ms: 1.03x faster                                                                                                   |
| async_tree_none_tg        | 348 ms                                                                                                             | 337 ms: 1.03x faster                                                                                                   |
| create_gc_cycles          | 2.90 ms                                                                                                            | 2.81 ms: 1.03x faster                                                                                                  |
| regex_v8                  | 31.6 ms                                                                                                            | 30.7 ms: 1.03x faster                                                                                                  |
| connected_components      | 457 ms                                                                                                             | 445 ms: 1.03x faster                                                                                                   |
| deepcopy                  | 332 us                                                                                                             | 323 us: 1.03x faster                                                                                                   |
| json                      | 7.19 ms                                                                                                            | 6.99 ms: 1.03x faster                                                                                                  |
| genshi_text               | 30.7 ms                                                                                                            | 29.9 ms: 1.03x faster                                                                                                  |
| coverage                  | 118 ms                                                                                                             | 115 ms: 1.02x faster                                                                                                   |
| pickle_list               | 7.41 us                                                                                                            | 7.25 us: 1.02x faster                                                                                                  |
| k_core                    | 2.23 sec                                                                                                           | 2.18 sec: 1.02x faster                                                                                                 |
| xml_etree_iterparse       | 121 ms                                                                                                             | 119 ms: 1.02x faster                                                                                                   |
| async_tree_io             | 761 ms                                                                                                             | 746 ms: 1.02x faster                                                                                                   |
| async_tree_cpu_io_mixed   | 672 ms                                                                                                             | 659 ms: 1.02x faster                                                                                                   |
| sqlglot_v2_parse          | 1.70 ms                                                                                                            | 1.67 ms: 1.02x faster                                                                                                  |
| asyncio_tcp_ssl           | 2.08 sec                                                                                                           | 2.04 sec: 1.02x faster                                                                                                 |
| async_tree_io_tg          | 773 ms                                                                                                             | 761 ms: 1.02x faster                                                                                                   |
| shortest_path             | 511 ms                                                                                                             | 504 ms: 1.01x faster                                                                                                   |
| meteor_contest            | 144 ms                                                                                                             | 142 ms: 1.01x faster                                                                                                   |
| xml_etree_parse           | 188 ms                                                                                                             | 186 ms: 1.01x faster                                                                                                   |
| comprehensions            | 22.9 us                                                                                                            | 22.7 us: 1.01x faster                                                                                                  |
| pycparser                 | 1.60 sec                                                                                                           | 1.58 sec: 1.01x faster                                                                                                 |
| chameleon                 | 19.0 ms                                                                                                            | 18.9 ms: 1.01x faster                                                                                                  |
| asyncio_websockets        | 780 ms                                                                                                             | 779 ms: 1.00x faster                                                                                                   |
| tornado_http              | 191 ms                                                                                                             | 193 ms: 1.01x slower                                                                                                   |
| regex_effbot              | 3.89 ms                                                                                                            | 3.92 ms: 1.01x slower                                                                                                  |
| pathlib                   | 25.7 ms                                                                                                            | 25.9 ms: 1.01x slower                                                                                                  |
| python_startup_no_site    | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| python_startup            | 17.8 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| pidigits                  | 287 ms                                                                                                             | 291 ms: 1.01x slower                                                                                                   |
| sympy_expand              | 717 ms                                                                                                             | 729 ms: 1.02x slower                                                                                                   |
| telco                     | 228 ms                                                                                                             | 232 ms: 1.02x slower                                                                                                   |
| sqlalchemy_imperative     | 28.9 ms                                                                                                            | 29.5 ms: 1.02x slower                                                                                                  |
| django_template           | 49.8 ms                                                                                                            | 50.9 ms: 1.02x slower                                                                                                  |
| typing_runtime_protocols  | 222 us                                                                                                             | 228 us: 1.02x slower                                                                                                   |
| coroutines                | 33.5 ms                                                                                                            | 34.3 ms: 1.03x slower                                                                                                  |
| nqueens                   | 111 ms                                                                                                             | 114 ms: 1.03x slower                                                                                                   |
| asyncio_tcp               | 559 ms                                                                                                             | 574 ms: 1.03x slower                                                                                                   |
| sqlalchemy_declarative    | 185 ms                                                                                                             | 191 ms: 1.03x slower                                                                                                   |
| logging_format            | 9.48 us                                                                                                            | 9.76 us: 1.03x slower                                                                                                  |
| unpickle_list             | 7.37 us                                                                                                            | 7.59 us: 1.03x slower                                                                                                  |
| logging_simple            | 8.35 us                                                                                                            | 8.62 us: 1.03x slower                                                                                                  |
| xdsl_constant_fold        | 64.7 ms                                                                                                            | 66.9 ms: 1.03x slower                                                                                                  |
| hexiom                    | 8.08 ms                                                                                                            | 8.37 ms: 1.04x slower                                                                                                  |
| sympy_integrate           | 27.5 ms                                                                                                            | 28.6 ms: 1.04x slower                                                                                                  |
| raytrace                  | 363 ms                                                                                                             | 377 ms: 1.04x slower                                                                                                   |
| sphinx                    | 1.36 sec                                                                                                           | 1.42 sec: 1.04x slower                                                                                                 |
| async_generators          | 482 ms                                                                                                             | 505 ms: 1.05x slower                                                                                                   |
| sqlglot_v2_optimize       | 72.7 ms                                                                                                            | 76.4 ms: 1.05x slower                                                                                                  |
| docutils                  | 3.60 sec                                                                                                           | 3.79 sec: 1.05x slower                                                                                                 |
| sqlglot_v2_normalize      | 145 ms                                                                                                             | 152 ms: 1.05x slower                                                                                                   |
| html5lib                  | 85.5 ms                                                                                                            | 90.7 ms: 1.06x slower                                                                                                  |
| regex_dna                 | 237 ms                                                                                                             | 253 ms: 1.07x slower                                                                                                   |
| sympy_sum                 | 225 ms                                                                                                             | 241 ms: 1.07x slower                                                                                                   |
| dulwich_log               | 95.5 ms                                                                                                            | 103 ms: 1.08x slower                                                                                                   |
| many_optionals            | 1.34 ms                                                                                                            | 1.45 ms: 1.08x slower                                                                                                  |
| genshi_xml                | 71.8 ms                                                                                                            | 77.8 ms: 1.08x slower                                                                                                  |
| pylint                    | 400 ms                                                                                                             | 436 ms: 1.09x slower                                                                                                   |
| generators                | 39.5 ms                                                                                                            | 43.0 ms: 1.09x slower                                                                                                  |
| sympy_str                 | 403 ms                                                                                                             | 439 ms: 1.09x slower                                                                                                   |
| mdp                       | 1.67 sec                                                                                                           | 1.93 sec: 1.15x slower                                                                                                 |
| unpack_sequence           | 66.0 ns                                                                                                            | 99.2 ns: 1.50x slower                                                                                                  |
| Geometric mean            | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (10): bench_mp_pool, async_tree_cpu_io_mixed_tg, sqlglot_v2_transpile, pickle, 2to3, bench_thread_pool, thrift, json_loads, subparsers, unpickle

- Geometric mean (including insignificant results): 1.045x faster

# HPT report

- Reliability score: 99.53% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x