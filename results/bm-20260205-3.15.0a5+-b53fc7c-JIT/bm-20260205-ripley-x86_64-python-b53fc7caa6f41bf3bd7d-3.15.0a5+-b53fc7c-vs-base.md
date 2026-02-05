# Results vs. base

- fork: python
- ref: b53fc7caa6f41bf3bd7d
- machine: linux-x86_64
- commit hash: b53fc7c
- commit date: 2026-02-05
- overall geometric mean: 1.037x faster
- HPT reliability: 95.31%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 354 ms                                                                                                             | 355 ms: 1.00x slower                                                                                                   |
| chameleon      | 19.2 ms                                                                                                            | 19.2 ms: 1.00x slower                                                                                                  |
| docutils       | 3.60 sec                                                                                                           | 3.95 sec: 1.10x slower                                                                                                 |
| html5lib       | 85.7 ms                                                                                                            | 90.9 ms: 1.06x slower                                                                                                  |
| sphinx         | 1.38 sec                                                                                                           | 1.43 sec: 1.03x slower                                                                                                 |
| tornado_http   | 192 ms                                                                                                             | 193 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.03x slower                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_none           | 347 ms                                                                                                             | 337 ms: 1.03x faster                                                                                                   |
| async_tree_memoization    | 412 ms                                                                                                             | 401 ms: 1.03x faster                                                                                                   |
| async_tree_memoization_tg | 405 ms                                                                                                             | 396 ms: 1.02x faster                                                                                                   |
| async_tree_cpu_io_mixed   | 678 ms                                                                                                             | 665 ms: 1.02x faster                                                                                                   |
| async_tree_io             | 787 ms                                                                                                             | 775 ms: 1.02x faster                                                                                                   |
| asyncio_tcp_ssl           | 2.04 sec                                                                                                           | 2.06 sec: 1.01x slower                                                                                                 |
| asyncio_tcp               | 559 ms                                                                                                             | 566 ms: 1.01x slower                                                                                                   |
| async_generators          | 483 ms                                                                                                             | 502 ms: 1.04x slower                                                                                                   |
| coroutines                | 32.7 ms                                                                                                            | 34.0 ms: 1.04x slower                                                                                                  |
| Geometric mean            | (ref)                                                                                                              | 1.00x faster                                                                                                           |

Benchmark hidden because not significant (4): async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 126 ms                                                                                                             | 107 ms: 1.18x faster                                                                                                   |
| float          | 101 ms                                                                                                             | 86.0 ms: 1.17x faster                                                                                                  |
| pidigits       | 286 ms                                                                                                             | 288 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.11x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.23 ms                                                                                                            | 4.12 ms: 1.03x faster                                                                                                  |
| regex_compile  | 178 ms                                                                                                             | 177 ms: 1.01x faster                                                                                                   |
| regex_dna      | 255 ms                                                                                                             | 269 ms: 1.05x slower                                                                                                   |
| regex_v8       | 31.8 ms                                                                                                            | 34.0 ms: 1.07x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| tomli_loads          | 2.62 sec                                                                                                           | 2.30 sec: 1.14x faster                                                                                                 |
| xml_etree_generate   | 118 ms                                                                                                             | 110 ms: 1.07x faster                                                                                                   |
| json_dumps           | 13.8 ms                                                                                                            | 13.0 ms: 1.06x faster                                                                                                  |
| xml_etree_process    | 82.4 ms                                                                                                            | 77.8 ms: 1.06x faster                                                                                                  |
| unpickle_pure_python | 302 us                                                                                                             | 285 us: 1.06x faster                                                                                                   |
| xml_etree_iterparse  | 123 ms                                                                                                             | 120 ms: 1.03x faster                                                                                                   |
| pickle               | 18.3 us                                                                                                            | 18.1 us: 1.02x faster                                                                                                  |
| unpickle_list        | 7.67 us                                                                                                            | 7.63 us: 1.00x faster                                                                                                  |
| pickle_list          | 7.34 us                                                                                                            | 7.45 us: 1.02x slower                                                                                                  |
| pickle_pure_python   | 440 us                                                                                                             | 447 us: 1.02x slower                                                                                                   |
| unpickle             | 20.9 us                                                                                                            | 21.3 us: 1.02x slower                                                                                                  |
| pickle_dict          | 43.5 us                                                                                                            | 45.9 us: 1.06x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (2): json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.8 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako           | 17.0 ms                                                                                                            | 15.4 ms: 1.10x faster                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                 | results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json | results/bm-20260205-3.15.0a5+-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                  | 60.3 ms                                                                                                            | 26.3 ms: 2.30x faster                                                                                                  |
| richards_super            | 68.9 ms                                                                                                            | 32.0 ms: 2.15x faster                                                                                                  |
| scimark_lu                | 155 ms                                                                                                             | 115 ms: 1.34x faster                                                                                                   |
| scimark_sor               | 154 ms                                                                                                             | 124 ms: 1.24x faster                                                                                                   |
| scimark_monte_carlo       | 89.0 ms                                                                                                            | 74.1 ms: 1.20x faster                                                                                                  |
| deltablue                 | 4.74 ms                                                                                                            | 3.96 ms: 1.20x faster                                                                                                  |
| spectral_norm             | 138 ms                                                                                                             | 117 ms: 1.19x faster                                                                                                   |
| nbody                     | 126 ms                                                                                                             | 107 ms: 1.18x faster                                                                                                   |
| float                     | 101 ms                                                                                                             | 86.0 ms: 1.17x faster                                                                                                  |
| logging_silent            | 141 ns                                                                                                             | 121 ns: 1.17x faster                                                                                                   |
| bench_mp_pool             | 254 ms                                                                                                             | 220 ms: 1.16x faster                                                                                                   |
| scimark_fft               | 432 ms                                                                                                             | 374 ms: 1.16x faster                                                                                                   |
| deepcopy_memo             | 37.2 us                                                                                                            | 32.4 us: 1.15x faster                                                                                                  |
| tomli_loads               | 2.62 sec                                                                                                           | 2.30 sec: 1.14x faster                                                                                                 |
| pyflate                   | 592 ms                                                                                                             | 526 ms: 1.13x faster                                                                                                   |
| pprint_safe_repr          | 993 ms                                                                                                             | 890 ms: 1.12x faster                                                                                                   |
| fannkuch                  | 558 ms                                                                                                             | 500 ms: 1.12x faster                                                                                                   |
| mako                      | 17.0 ms                                                                                                            | 15.4 ms: 1.10x faster                                                                                                  |
| pprint_pformat            | 2.02 sec                                                                                                           | 1.85 sec: 1.10x faster                                                                                                 |
| deepcopy_reduce           | 3.64 us                                                                                                            | 3.39 us: 1.07x faster                                                                                                  |
| xml_etree_generate        | 118 ms                                                                                                             | 110 ms: 1.07x faster                                                                                                   |
| json_dumps                | 13.8 ms                                                                                                            | 13.0 ms: 1.06x faster                                                                                                  |
| xml_etree_process         | 82.4 ms                                                                                                            | 77.8 ms: 1.06x faster                                                                                                  |
| go                        | 152 ms                                                                                                             | 144 ms: 1.06x faster                                                                                                   |
| unpickle_pure_python      | 302 us                                                                                                             | 285 us: 1.06x faster                                                                                                   |
| bpe_tokeniser             | 6.05 sec                                                                                                           | 5.74 sec: 1.05x faster                                                                                                 |
| connected_components      | 458 ms                                                                                                             | 438 ms: 1.05x faster                                                                                                   |
| deepcopy                  | 338 us                                                                                                             | 323 us: 1.05x faster                                                                                                   |
| scimark_sparse_mat_mult   | 6.34 ms                                                                                                            | 6.08 ms: 1.04x faster                                                                                                  |
| shortest_path             | 513 ms                                                                                                             | 494 ms: 1.04x faster                                                                                                   |
| sqlglot_v2_parse          | 1.72 ms                                                                                                            | 1.66 ms: 1.03x faster                                                                                                  |
| crypto_pyaes              | 98.9 ms                                                                                                            | 95.8 ms: 1.03x faster                                                                                                  |
| sqlite_synth              | 3.18 us                                                                                                            | 3.08 us: 1.03x faster                                                                                                  |
| async_tree_none           | 347 ms                                                                                                             | 337 ms: 1.03x faster                                                                                                   |
| json                      | 7.16 ms                                                                                                            | 6.96 ms: 1.03x faster                                                                                                  |
| regex_effbot              | 4.23 ms                                                                                                            | 4.12 ms: 1.03x faster                                                                                                  |
| xml_etree_iterparse       | 123 ms                                                                                                             | 120 ms: 1.03x faster                                                                                                   |
| sqlglot_v2_transpile      | 2.18 ms                                                                                                            | 2.13 ms: 1.03x faster                                                                                                  |
| async_tree_memoization    | 412 ms                                                                                                             | 401 ms: 1.03x faster                                                                                                   |
| async_tree_memoization_tg | 405 ms                                                                                                             | 396 ms: 1.02x faster                                                                                                   |
| meteor_contest            | 146 ms                                                                                                             | 143 ms: 1.02x faster                                                                                                   |
| chaos                     | 79.5 ms                                                                                                            | 78.0 ms: 1.02x faster                                                                                                  |
| async_tree_cpu_io_mixed   | 678 ms                                                                                                             | 665 ms: 1.02x faster                                                                                                   |
| pickle                    | 18.3 us                                                                                                            | 18.1 us: 1.02x faster                                                                                                  |
| async_tree_io             | 787 ms                                                                                                             | 775 ms: 1.02x faster                                                                                                   |
| logging_format            | 9.65 us                                                                                                            | 9.54 us: 1.01x faster                                                                                                  |
| k_core                    | 2.22 sec                                                                                                           | 2.20 sec: 1.01x faster                                                                                                 |
| regex_compile             | 178 ms                                                                                                             | 177 ms: 1.01x faster                                                                                                   |
| unpickle_list             | 7.67 us                                                                                                            | 7.63 us: 1.00x faster                                                                                                  |
| 2to3                      | 354 ms                                                                                                             | 355 ms: 1.00x slower                                                                                                   |
| chameleon                 | 19.2 ms                                                                                                            | 19.2 ms: 1.00x slower                                                                                                  |
| pidigits                  | 286 ms                                                                                                             | 288 ms: 1.01x slower                                                                                                   |
| coverage                  | 116 ms                                                                                                             | 117 ms: 1.01x slower                                                                                                   |
| asyncio_tcp_ssl           | 2.04 sec                                                                                                           | 2.06 sec: 1.01x slower                                                                                                 |
| tornado_http              | 192 ms                                                                                                             | 193 ms: 1.01x slower                                                                                                   |
| python_startup            | 17.8 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| python_startup_no_site    | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| telco                     | 226 ms                                                                                                             | 228 ms: 1.01x slower                                                                                                   |
| asyncio_tcp               | 559 ms                                                                                                             | 566 ms: 1.01x slower                                                                                                   |
| sqlalchemy_declarative    | 185 ms                                                                                                             | 187 ms: 1.01x slower                                                                                                   |
| pathlib                   | 24.9 ms                                                                                                            | 25.2 ms: 1.01x slower                                                                                                  |
| pickle_list               | 7.34 us                                                                                                            | 7.45 us: 1.02x slower                                                                                                  |
| gc_traversal              | 6.35 ms                                                                                                            | 6.45 ms: 1.02x slower                                                                                                  |
| create_gc_cycles          | 2.87 ms                                                                                                            | 2.91 ms: 1.02x slower                                                                                                  |
| pickle_pure_python        | 440 us                                                                                                             | 447 us: 1.02x slower                                                                                                   |
| unpickle                  | 20.9 us                                                                                                            | 21.3 us: 1.02x slower                                                                                                  |
| many_optionals            | 1.37 ms                                                                                                            | 1.41 ms: 1.03x slower                                                                                                  |
| sphinx                    | 1.38 sec                                                                                                           | 1.43 sec: 1.03x slower                                                                                                 |
| xdsl_constant_fold        | 64.8 ms                                                                                                            | 67.2 ms: 1.04x slower                                                                                                  |
| sympy_expand              | 718 ms                                                                                                             | 744 ms: 1.04x slower                                                                                                   |
| async_generators          | 483 ms                                                                                                             | 502 ms: 1.04x slower                                                                                                   |
| nqueens                   | 113 ms                                                                                                             | 117 ms: 1.04x slower                                                                                                   |
| dulwich_log               | 97.8 ms                                                                                                            | 102 ms: 1.04x slower                                                                                                   |
| coroutines                | 32.7 ms                                                                                                            | 34.0 ms: 1.04x slower                                                                                                  |
| sqlglot_v2_normalize      | 148 ms                                                                                                             | 154 ms: 1.04x slower                                                                                                   |
| sqlglot_v2_optimize       | 73.6 ms                                                                                                            | 76.7 ms: 1.04x slower                                                                                                  |
| sympy_integrate           | 27.5 ms                                                                                                            | 28.8 ms: 1.05x slower                                                                                                  |
| generators                | 39.7 ms                                                                                                            | 41.7 ms: 1.05x slower                                                                                                  |
| regex_dna                 | 255 ms                                                                                                             | 269 ms: 1.05x slower                                                                                                   |
| pickle_dict               | 43.5 us                                                                                                            | 45.9 us: 1.06x slower                                                                                                  |
| html5lib                  | 85.7 ms                                                                                                            | 90.9 ms: 1.06x slower                                                                                                  |
| regex_v8                  | 31.8 ms                                                                                                            | 34.0 ms: 1.07x slower                                                                                                  |
| hexiom                    | 7.96 ms                                                                                                            | 8.58 ms: 1.08x slower                                                                                                  |
| pylint                    | 399 ms                                                                                                             | 430 ms: 1.08x slower                                                                                                   |
| sympy_sum                 | 224 ms                                                                                                             | 245 ms: 1.09x slower                                                                                                   |
| docutils                  | 3.60 sec                                                                                                           | 3.95 sec: 1.10x slower                                                                                                 |
| sympy_str                 | 402 ms                                                                                                             | 444 ms: 1.11x slower                                                                                                   |
| raytrace                  | 360 ms                                                                                                             | 410 ms: 1.14x slower                                                                                                   |
| mdp                       | 1.65 sec                                                                                                           | 1.91 sec: 1.16x slower                                                                                                 |
| unpack_sequence           | 55.6 ns                                                                                                            | 70.8 ns: 1.27x slower                                                                                                  |
| Geometric mean            | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (15): async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, django_template, subparsers, sqlalchemy_imperative, typing_runtime_protocols, json_loads, logging_simple, xml_etree_parse, asyncio_websockets, comprehensions, pycparser, bench_thread_pool, thrift
Ignored benchmarks (2) of results/bm-20260205-3.15.0a5+-b53fc7c/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5+-b53fc7c.json: genshi_text, genshi_xml

- Geometric mean (including insignificant results): 1.037x faster

# HPT report

- Reliability score: 95.31% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x