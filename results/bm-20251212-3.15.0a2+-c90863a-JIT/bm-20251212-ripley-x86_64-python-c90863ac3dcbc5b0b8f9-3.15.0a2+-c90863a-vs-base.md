# Results vs. base

- fork: python
- ref: c90863ac3dcbc5b0b8f9
- machine: linux-x86_64
- commit hash: c90863a
- commit date: 2025-12-12
- overall geometric mean: 1.029x faster
- HPT reliability: 82.59%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.04x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 250 ms                                                                                                             | 252 ms: 1.01x slower                                                                                                   |
| chameleon      | 13.1 ms                                                                                                            | 13.2 ms: 1.00x slower                                                                                                  |
| html5lib       | 59.3 ms                                                                                                            | 66.3 ms: 1.12x slower                                                                                                  |
| sphinx         | 972 ms                                                                                                             | 1.01 sec: 1.04x slower                                                                                                 |
| tornado_http   | 140 ms                                                                                                             | 143 ms: 1.02x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.04x slower                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp               | 444 ms                                                                                                             | 436 ms: 1.02x faster                                                                                                   |
| asyncio_tcp_ssl           | 1.56 sec                                                                                                           | 1.56 sec: 1.00x faster                                                                                                 |
| async_tree_io_tg          | 599 ms                                                                                                             | 603 ms: 1.01x slower                                                                                                   |
| async_tree_memoization_tg | 306 ms                                                                                                             | 311 ms: 1.02x slower                                                                                                   |
| async_generators          | 355 ms                                                                                                             | 373 ms: 1.05x slower                                                                                                   |
| Geometric mean            | (ref)                                                                                                              | 1.00x slower                                                                                                           |

Benchmark hidden because not significant (8): async_tree_none, async_tree_cpu_io_mixed_tg, coroutines, async_tree_cpu_io_mixed, asyncio_websockets, async_tree_io, async_tree_memoization, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 91.6 ms                                                                                                            | 72.8 ms: 1.26x faster                                                                                                  |
| float          | 69.3 ms                                                                                                            | 60.7 ms: 1.14x faster                                                                                                  |
| pidigits       | 192 ms                                                                                                             | 209 ms: 1.09x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.10x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 2.75 ms                                                                                                            | 2.56 ms: 1.08x faster                                                                                                  |
| regex_v8       | 22.1 ms                                                                                                            | 20.8 ms: 1.07x faster                                                                                                  |
| regex_dna      | 165 ms                                                                                                             | 166 ms: 1.00x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 214 us                                                                                                             | 182 us: 1.17x faster                                                                                                   |
| xml_etree_process    | 59.8 ms                                                                                                            | 54.7 ms: 1.09x faster                                                                                                  |
| pickle_pure_python   | 308 us                                                                                                             | 283 us: 1.09x faster                                                                                                   |
| json_dumps           | 10.00 ms                                                                                                           | 9.22 ms: 1.08x faster                                                                                                  |
| xml_etree_generate   | 84.0 ms                                                                                                            | 78.1 ms: 1.08x faster                                                                                                  |
| tomli_loads          | 2.15 sec                                                                                                           | 2.09 sec: 1.03x faster                                                                                                 |
| xml_etree_iterparse  | 85.2 ms                                                                                                            | 83.5 ms: 1.02x faster                                                                                                  |
| pickle_dict          | 33.4 us                                                                                                            | 32.9 us: 1.02x faster                                                                                                  |
| pickle_list          | 5.29 us                                                                                                            | 5.30 us: 1.00x slower                                                                                                  |
| unpickle_list        | 5.09 us                                                                                                            | 5.25 us: 1.03x slower                                                                                                  |
| pickle               | 12.6 us                                                                                                            | 13.1 us: 1.04x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (3): xml_etree_parse, unpickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 12.7 ms                                                                                                            | 12.9 ms: 1.01x slower                                                                                                  |
| python_startup_no_site | 7.50 ms                                                                                                            | 7.58 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 11.8 ms                                                                                                            | 10.7 ms: 1.10x faster                                                                                                  |
| genshi_text     | 20.8 ms                                                                                                            | 21.1 ms: 1.01x slower                                                                                                  |
| django_template | 34.5 ms                                                                                                            | 35.5 ms: 1.03x slower                                                                                                  |
| genshi_xml      | 48.3 ms                                                                                                            | 52.8 ms: 1.09x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.01x slower                                                                                                           |

All benchmarks:
===============

| Benchmark                 | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                  | 42.4 ms                                                                                                            | 19.5 ms: 2.18x faster                                                                                                  |
| richards_super            | 48.1 ms                                                                                                            | 23.3 ms: 2.06x faster                                                                                                  |
| bench_mp_pool             | 277 ms                                                                                                             | 201 ms: 1.37x faster                                                                                                   |
| nbody                     | 91.6 ms                                                                                                            | 72.8 ms: 1.26x faster                                                                                                  |
| scimark_fft               | 310 ms                                                                                                             | 256 ms: 1.21x faster                                                                                                   |
| logging_silent            | 101 ns                                                                                                             | 85.3 ns: 1.18x faster                                                                                                  |
| unpickle_pure_python      | 214 us                                                                                                             | 182 us: 1.17x faster                                                                                                   |
| deltablue                 | 3.28 ms                                                                                                            | 2.82 ms: 1.16x faster                                                                                                  |
| scimark_monte_carlo       | 63.4 ms                                                                                                            | 55.0 ms: 1.15x faster                                                                                                  |
| float                     | 69.3 ms                                                                                                            | 60.7 ms: 1.14x faster                                                                                                  |
| spectral_norm             | 95.5 ms                                                                                                            | 86.4 ms: 1.11x faster                                                                                                  |
| mako                      | 11.8 ms                                                                                                            | 10.7 ms: 1.10x faster                                                                                                  |
| scimark_sor               | 108 ms                                                                                                             | 98.0 ms: 1.10x faster                                                                                                  |
| xml_etree_process         | 59.8 ms                                                                                                            | 54.7 ms: 1.09x faster                                                                                                  |
| pickle_pure_python        | 308 us                                                                                                             | 283 us: 1.09x faster                                                                                                   |
| chaos                     | 57.0 ms                                                                                                            | 52.4 ms: 1.09x faster                                                                                                  |
| json_dumps                | 10.00 ms                                                                                                           | 9.22 ms: 1.08x faster                                                                                                  |
| scimark_lu                | 111 ms                                                                                                             | 102 ms: 1.08x faster                                                                                                   |
| deepcopy_memo             | 27.4 us                                                                                                            | 25.3 us: 1.08x faster                                                                                                  |
| regex_effbot              | 2.75 ms                                                                                                            | 2.56 ms: 1.08x faster                                                                                                  |
| xml_etree_generate        | 84.0 ms                                                                                                            | 78.1 ms: 1.08x faster                                                                                                  |
| pyflate                   | 422 ms                                                                                                             | 393 ms: 1.07x faster                                                                                                   |
| fannkuch                  | 390 ms                                                                                                             | 364 ms: 1.07x faster                                                                                                   |
| regex_v8                  | 22.1 ms                                                                                                            | 20.8 ms: 1.07x faster                                                                                                  |
| go                        | 105 ms                                                                                                             | 99.4 ms: 1.05x faster                                                                                                  |
| bpe_tokeniser             | 4.21 sec                                                                                                           | 4.05 sec: 1.04x faster                                                                                                 |
| json                      | 5.13 ms                                                                                                            | 4.94 ms: 1.04x faster                                                                                                  |
| thrift                    | 781 us                                                                                                             | 754 us: 1.04x faster                                                                                                   |
| crypto_pyaes              | 68.9 ms                                                                                                            | 66.7 ms: 1.03x faster                                                                                                  |
| sqlite_synth              | 2.28 us                                                                                                            | 2.20 us: 1.03x faster                                                                                                  |
| pprint_safe_repr          | 705 ms                                                                                                             | 685 ms: 1.03x faster                                                                                                   |
| tomli_loads               | 2.15 sec                                                                                                           | 2.09 sec: 1.03x faster                                                                                                 |
| meteor_contest            | 101 ms                                                                                                             | 98.0 ms: 1.03x faster                                                                                                  |
| gc_traversal              | 4.58 ms                                                                                                            | 4.46 ms: 1.03x faster                                                                                                  |
| connected_components      | 376 ms                                                                                                             | 366 ms: 1.03x faster                                                                                                   |
| coverage                  | 83.1 ms                                                                                                            | 81.2 ms: 1.02x faster                                                                                                  |
| xml_etree_iterparse       | 85.2 ms                                                                                                            | 83.5 ms: 1.02x faster                                                                                                  |
| asyncio_tcp               | 444 ms                                                                                                             | 436 ms: 1.02x faster                                                                                                   |
| k_core                    | 1.83 sec                                                                                                           | 1.80 sec: 1.02x faster                                                                                                 |
| pickle_dict               | 33.4 us                                                                                                            | 32.9 us: 1.02x faster                                                                                                  |
| pprint_pformat            | 1.44 sec                                                                                                           | 1.42 sec: 1.01x faster                                                                                                 |
| shortest_path             | 417 ms                                                                                                             | 413 ms: 1.01x faster                                                                                                   |
| create_gc_cycles          | 2.07 ms                                                                                                            | 2.06 ms: 1.01x faster                                                                                                  |
| asyncio_tcp_ssl           | 1.56 sec                                                                                                           | 1.56 sec: 1.00x faster                                                                                                 |
| pickle_list               | 5.29 us                                                                                                            | 5.30 us: 1.00x slower                                                                                                  |
| regex_dna                 | 165 ms                                                                                                             | 166 ms: 1.00x slower                                                                                                   |
| chameleon                 | 13.1 ms                                                                                                            | 13.2 ms: 1.00x slower                                                                                                  |
| logging_format            | 6.72 us                                                                                                            | 6.76 us: 1.01x slower                                                                                                  |
| async_tree_io_tg          | 599 ms                                                                                                             | 603 ms: 1.01x slower                                                                                                   |
| deepcopy_reduce           | 2.63 us                                                                                                            | 2.65 us: 1.01x slower                                                                                                  |
| 2to3                      | 250 ms                                                                                                             | 252 ms: 1.01x slower                                                                                                   |
| sqlglot_v2_parse          | 1.20 ms                                                                                                            | 1.22 ms: 1.01x slower                                                                                                  |
| python_startup            | 12.7 ms                                                                                                            | 12.9 ms: 1.01x slower                                                                                                  |
| python_startup_no_site    | 7.50 ms                                                                                                            | 7.58 ms: 1.01x slower                                                                                                  |
| genshi_text               | 20.8 ms                                                                                                            | 21.1 ms: 1.01x slower                                                                                                  |
| bench_thread_pool         | 1.22 ms                                                                                                            | 1.23 ms: 1.01x slower                                                                                                  |
| sqlglot_v2_transpile      | 1.50 ms                                                                                                            | 1.52 ms: 1.02x slower                                                                                                  |
| async_tree_memoization_tg | 306 ms                                                                                                             | 311 ms: 1.02x slower                                                                                                   |
| xdsl_constant_fold        | 45.2 ms                                                                                                            | 46.1 ms: 1.02x slower                                                                                                  |
| tornado_http              | 140 ms                                                                                                             | 143 ms: 1.02x slower                                                                                                   |
| comprehensions            | 16.1 us                                                                                                            | 16.5 us: 1.02x slower                                                                                                  |
| telco                     | 157 ms                                                                                                             | 162 ms: 1.03x slower                                                                                                   |
| django_template           | 34.5 ms                                                                                                            | 35.5 ms: 1.03x slower                                                                                                  |
| unpickle_list             | 5.09 us                                                                                                            | 5.25 us: 1.03x slower                                                                                                  |
| scimark_sparse_mat_mult   | 4.25 ms                                                                                                            | 4.39 ms: 1.03x slower                                                                                                  |
| pathlib                   | 17.6 ms                                                                                                            | 18.2 ms: 1.03x slower                                                                                                  |
| sqlalchemy_declarative    | 129 ms                                                                                                             | 133 ms: 1.03x slower                                                                                                   |
| subparsers                | 9.11 ms                                                                                                            | 9.42 ms: 1.03x slower                                                                                                  |
| raytrace                  | 252 ms                                                                                                             | 261 ms: 1.03x slower                                                                                                   |
| sqlalchemy_imperative     | 20.8 ms                                                                                                            | 21.5 ms: 1.04x slower                                                                                                  |
| generators                | 27.2 ms                                                                                                            | 28.2 ms: 1.04x slower                                                                                                  |
| sphinx                    | 972 ms                                                                                                             | 1.01 sec: 1.04x slower                                                                                                 |
| pickle                    | 12.6 us                                                                                                            | 13.1 us: 1.04x slower                                                                                                  |
| many_optionals            | 952 us                                                                                                             | 994 us: 1.04x slower                                                                                                   |
| async_generators          | 355 ms                                                                                                             | 373 ms: 1.05x slower                                                                                                   |
| sqlglot_v2_optimize       | 50.9 ms                                                                                                            | 54.4 ms: 1.07x slower                                                                                                  |
| sqlglot_v2_normalize      | 102 ms                                                                                                             | 110 ms: 1.07x slower                                                                                                   |
| hexiom                    | 5.74 ms                                                                                                            | 6.17 ms: 1.08x slower                                                                                                  |
| pylint                    | 287 ms                                                                                                             | 309 ms: 1.08x slower                                                                                                   |
| nqueens                   | 79.5 ms                                                                                                            | 86.0 ms: 1.08x slower                                                                                                  |
| pidigits                  | 192 ms                                                                                                             | 209 ms: 1.09x slower                                                                                                   |
| dulwich_log               | 67.2 ms                                                                                                            | 73.2 ms: 1.09x slower                                                                                                  |
| genshi_xml                | 48.3 ms                                                                                                            | 52.8 ms: 1.09x slower                                                                                                  |
| html5lib                  | 59.3 ms                                                                                                            | 66.3 ms: 1.12x slower                                                                                                  |
| mdp                       | 1.17 sec                                                                                                           | 1.35 sec: 1.16x slower                                                                                                 |
| unpack_sequence           | 44.6 ns                                                                                                            | 82.2 ns: 1.84x slower                                                                                                  |
| Geometric mean            | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (16): async_tree_none, async_tree_cpu_io_mixed_tg, deepcopy, xml_etree_parse, coroutines, async_tree_cpu_io_mixed, asyncio_websockets, unpickle, pycparser, json_loads, regex_compile, async_tree_io, logging_simple, async_tree_memoization, async_tree_none_tg, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.029x faster

# HPT report

- Reliability score: 82.59% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.04x