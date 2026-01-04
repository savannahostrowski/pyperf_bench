# Results vs. base

- fork: python
- ref: e46f28c6afce9c85e4bc
- machine: linux-x86_64
- commit hash: e46f28c
- commit date: 2025-12-19
- overall geometric mean: 1.031x faster
- HPT reliability: 86.51%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 352 ms                                                                                                             | 355 ms: 1.01x slower                                                                                                   |
| chameleon      | 18.8 ms                                                                                                            | 18.5 ms: 1.02x faster                                                                                                  |
| docutils       | 3.63 sec                                                                                                           | 3.83 sec: 1.05x slower                                                                                                 |
| html5lib       | 86.2 ms                                                                                                            | 94.0 ms: 1.09x slower                                                                                                  |
| sphinx         | 1.37 sec                                                                                                           | 1.43 sec: 1.04x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                              | 1.03x slower                                                                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|--------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp        | 575 ms                                                                                                             | 565 ms: 1.02x faster                                                                                                   |
| async_tree_io_tg   | 804 ms                                                                                                             | 800 ms: 1.00x faster                                                                                                   |
| asyncio_websockets | 778 ms                                                                                                             | 779 ms: 1.00x slower                                                                                                   |
| asyncio_tcp_ssl    | 2.04 sec                                                                                                           | 2.06 sec: 1.01x slower                                                                                                 |
| coroutines         | 33.7 ms                                                                                                            | 34.3 ms: 1.02x slower                                                                                                  |
| async_generators   | 497 ms                                                                                                             | 539 ms: 1.08x slower                                                                                                   |
| Geometric mean     | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmark hidden because not significant (7): async_tree_none_tg, async_tree_memoization_tg, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 132 ms                                                                                                             | 107 ms: 1.23x faster                                                                                                   |
| float          | 100 ms                                                                                                             | 86.1 ms: 1.17x faster                                                                                                  |
| pidigits       | 287 ms                                                                                                             | 276 ms: 1.04x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.14x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 32.6 ms                                                                                                            | 30.6 ms: 1.07x faster                                                                                                  |
| regex_effbot   | 3.94 ms                                                                                                            | 3.78 ms: 1.04x faster                                                                                                  |
| regex_dna      | 255 ms                                                                                                             | 249 ms: 1.03x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 303 us                                                                                                             | 249 us: 1.21x faster                                                                                                   |
| pickle_pure_python   | 442 us                                                                                                             | 396 us: 1.12x faster                                                                                                   |
| tomli_loads          | 3.06 sec                                                                                                           | 2.83 sec: 1.08x faster                                                                                                 |
| xml_etree_process    | 82.2 ms                                                                                                            | 76.6 ms: 1.07x faster                                                                                                  |
| xml_etree_generate   | 118 ms                                                                                                             | 111 ms: 1.06x faster                                                                                                   |
| json_dumps           | 14.3 ms                                                                                                            | 13.5 ms: 1.06x faster                                                                                                  |
| unpickle_list        | 7.73 us                                                                                                            | 7.42 us: 1.04x faster                                                                                                  |
| pickle_list          | 7.56 us                                                                                                            | 7.31 us: 1.03x faster                                                                                                  |
| json_loads           | 40.6 us                                                                                                            | 39.6 us: 1.02x faster                                                                                                  |
| pickle               | 18.4 us                                                                                                            | 18.0 us: 1.02x faster                                                                                                  |
| xml_etree_parse      | 186 ms                                                                                                             | 185 ms: 1.00x faster                                                                                                   |
| pickle_dict          | 46.1 us                                                                                                            | 46.4 us: 1.01x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (2): unpickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| python_startup         | 17.7 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako           | 16.8 ms                                                                                                            | 15.8 ms: 1.06x faster                                                                                                  |
| genshi_text    | 30.3 ms                                                                                                            | 30.7 ms: 1.01x slower                                                                                                  |
| genshi_xml     | 71.8 ms                                                                                                            | 77.0 ms: 1.07x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.00x slower                                                                                                           |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark               | results/bm-20251219-3.15.0a3+-e46f28c/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json | results/bm-20251219-3.15.0a3+-e46f28c-JIT/bm-20251219-ripley-x86_64-python-e46f28c6afce9c85e4bc-3.15.0a3+-e46f28c.json |
|-------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                | 60.5 ms                                                                                                            | 26.3 ms: 2.30x faster                                                                                                  |
| richards_super          | 69.5 ms                                                                                                            | 32.1 ms: 2.17x faster                                                                                                  |
| logging_silent          | 145 ns                                                                                                             | 117 ns: 1.24x faster                                                                                                   |
| nbody                   | 132 ms                                                                                                             | 107 ms: 1.23x faster                                                                                                   |
| unpickle_pure_python    | 303 us                                                                                                             | 249 us: 1.21x faster                                                                                                   |
| deltablue               | 4.62 ms                                                                                                            | 3.86 ms: 1.20x faster                                                                                                  |
| scimark_monte_carlo     | 89.3 ms                                                                                                            | 74.7 ms: 1.19x faster                                                                                                  |
| scimark_fft             | 441 ms                                                                                                             | 371 ms: 1.19x faster                                                                                                   |
| float                   | 100 ms                                                                                                             | 86.1 ms: 1.17x faster                                                                                                  |
| bench_mp_pool           | 239 ms                                                                                                             | 206 ms: 1.16x faster                                                                                                   |
| go                      | 151 ms                                                                                                             | 132 ms: 1.15x faster                                                                                                   |
| pyflate                 | 583 ms                                                                                                             | 510 ms: 1.14x faster                                                                                                   |
| pickle_pure_python      | 442 us                                                                                                             | 396 us: 1.12x faster                                                                                                   |
| fannkuch                | 553 ms                                                                                                             | 504 ms: 1.10x faster                                                                                                   |
| tomli_loads             | 3.06 sec                                                                                                           | 2.83 sec: 1.08x faster                                                                                                 |
| pprint_safe_repr        | 993 ms                                                                                                             | 926 ms: 1.07x faster                                                                                                   |
| xml_etree_process       | 82.2 ms                                                                                                            | 76.6 ms: 1.07x faster                                                                                                  |
| json                    | 7.40 ms                                                                                                            | 6.93 ms: 1.07x faster                                                                                                  |
| gc_traversal            | 6.78 ms                                                                                                            | 6.36 ms: 1.07x faster                                                                                                  |
| regex_v8                | 32.6 ms                                                                                                            | 30.6 ms: 1.07x faster                                                                                                  |
| mako                    | 16.8 ms                                                                                                            | 15.8 ms: 1.06x faster                                                                                                  |
| xml_etree_generate      | 118 ms                                                                                                             | 111 ms: 1.06x faster                                                                                                   |
| json_dumps              | 14.3 ms                                                                                                            | 13.5 ms: 1.06x faster                                                                                                  |
| deepcopy_memo           | 37.8 us                                                                                                            | 35.6 us: 1.06x faster                                                                                                  |
| chaos                   | 79.5 ms                                                                                                            | 75.3 ms: 1.06x faster                                                                                                  |
| scimark_sor             | 152 ms                                                                                                             | 145 ms: 1.05x faster                                                                                                   |
| pprint_pformat          | 2.02 sec                                                                                                           | 1.93 sec: 1.05x faster                                                                                                 |
| bpe_tokeniser           | 5.92 sec                                                                                                           | 5.68 sec: 1.04x faster                                                                                                 |
| unpickle_list           | 7.73 us                                                                                                            | 7.42 us: 1.04x faster                                                                                                  |
| pidigits                | 287 ms                                                                                                             | 276 ms: 1.04x faster                                                                                                   |
| spectral_norm           | 130 ms                                                                                                             | 125 ms: 1.04x faster                                                                                                   |
| regex_effbot            | 3.94 ms                                                                                                            | 3.78 ms: 1.04x faster                                                                                                  |
| scimark_sparse_mat_mult | 6.38 ms                                                                                                            | 6.15 ms: 1.04x faster                                                                                                  |
| scimark_lu              | 154 ms                                                                                                             | 149 ms: 1.04x faster                                                                                                   |
| pickle_list             | 7.56 us                                                                                                            | 7.31 us: 1.03x faster                                                                                                  |
| thrift                  | 1.10 ms                                                                                                            | 1.06 ms: 1.03x faster                                                                                                  |
| crypto_pyaes            | 98.0 ms                                                                                                            | 95.2 ms: 1.03x faster                                                                                                  |
| sqlite_synth            | 3.28 us                                                                                                            | 3.19 us: 1.03x faster                                                                                                  |
| connected_components    | 453 ms                                                                                                             | 442 ms: 1.03x faster                                                                                                   |
| regex_dna               | 255 ms                                                                                                             | 249 ms: 1.03x faster                                                                                                   |
| k_core                  | 2.24 sec                                                                                                           | 2.18 sec: 1.03x faster                                                                                                 |
| json_loads              | 40.6 us                                                                                                            | 39.6 us: 1.02x faster                                                                                                  |
| pickle                  | 18.4 us                                                                                                            | 18.0 us: 1.02x faster                                                                                                  |
| coverage                | 119 ms                                                                                                             | 116 ms: 1.02x faster                                                                                                   |
| asyncio_tcp             | 575 ms                                                                                                             | 565 ms: 1.02x faster                                                                                                   |
| meteor_contest          | 145 ms                                                                                                             | 143 ms: 1.02x faster                                                                                                   |
| chameleon               | 18.8 ms                                                                                                            | 18.5 ms: 1.02x faster                                                                                                  |
| create_gc_cycles        | 2.89 ms                                                                                                            | 2.85 ms: 1.01x faster                                                                                                  |
| shortest_path           | 507 ms                                                                                                             | 504 ms: 1.01x faster                                                                                                   |
| sqlglot_v2_parse        | 1.70 ms                                                                                                            | 1.69 ms: 1.01x faster                                                                                                  |
| async_tree_io_tg        | 804 ms                                                                                                             | 800 ms: 1.00x faster                                                                                                   |
| xml_etree_parse         | 186 ms                                                                                                             | 185 ms: 1.00x faster                                                                                                   |
| asyncio_websockets      | 778 ms                                                                                                             | 779 ms: 1.00x slower                                                                                                   |
| bench_thread_pool       | 1.75 ms                                                                                                            | 1.76 ms: 1.00x slower                                                                                                  |
| pickle_dict             | 46.1 us                                                                                                            | 46.4 us: 1.01x slower                                                                                                  |
| 2to3                    | 352 ms                                                                                                             | 355 ms: 1.01x slower                                                                                                   |
| python_startup_no_site  | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| asyncio_tcp_ssl         | 2.04 sec                                                                                                           | 2.06 sec: 1.01x slower                                                                                                 |
| telco                   | 228 ms                                                                                                             | 231 ms: 1.01x slower                                                                                                   |
| python_startup          | 17.7 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| deepcopy_reduce         | 3.67 us                                                                                                            | 3.72 us: 1.01x slower                                                                                                  |
| logging_format          | 9.45 us                                                                                                            | 9.57 us: 1.01x slower                                                                                                  |
| genshi_text             | 30.3 ms                                                                                                            | 30.7 ms: 1.01x slower                                                                                                  |
| comprehensions          | 22.6 us                                                                                                            | 23.0 us: 1.02x slower                                                                                                  |
| coroutines              | 33.7 ms                                                                                                            | 34.3 ms: 1.02x slower                                                                                                  |
| sqlalchemy_imperative   | 29.3 ms                                                                                                            | 29.8 ms: 1.02x slower                                                                                                  |
| generators              | 40.0 ms                                                                                                            | 41.0 ms: 1.03x slower                                                                                                  |
| deepcopy                | 346 us                                                                                                             | 357 us: 1.03x slower                                                                                                   |
| pathlib                 | 25.2 ms                                                                                                            | 26.0 ms: 1.03x slower                                                                                                  |
| pycparser               | 1.52 sec                                                                                                           | 1.57 sec: 1.03x slower                                                                                                 |
| sqlalchemy_declarative  | 185 ms                                                                                                             | 191 ms: 1.03x slower                                                                                                   |
| hexiom                  | 8.14 ms                                                                                                            | 8.46 ms: 1.04x slower                                                                                                  |
| sphinx                  | 1.37 sec                                                                                                           | 1.43 sec: 1.04x slower                                                                                                 |
| raytrace                | 360 ms                                                                                                             | 375 ms: 1.04x slower                                                                                                   |
| xdsl_constant_fold      | 64.2 ms                                                                                                            | 66.9 ms: 1.04x slower                                                                                                  |
| docutils                | 3.63 sec                                                                                                           | 3.83 sec: 1.05x slower                                                                                                 |
| dulwich_log             | 99.2 ms                                                                                                            | 105 ms: 1.05x slower                                                                                                   |
| many_optionals          | 1.36 ms                                                                                                            | 1.44 ms: 1.06x slower                                                                                                  |
| sympy_integrate         | 26.9 ms                                                                                                            | 28.4 ms: 1.06x slower                                                                                                  |
| genshi_xml              | 71.8 ms                                                                                                            | 77.0 ms: 1.07x slower                                                                                                  |
| sqlglot_v2_optimize     | 72.6 ms                                                                                                            | 77.9 ms: 1.07x slower                                                                                                  |
| sqlglot_v2_normalize    | 146 ms                                                                                                             | 157 ms: 1.08x slower                                                                                                   |
| nqueens                 | 112 ms                                                                                                             | 121 ms: 1.08x slower                                                                                                   |
| async_generators        | 497 ms                                                                                                             | 539 ms: 1.08x slower                                                                                                   |
| sympy_expand            | 687 ms                                                                                                             | 746 ms: 1.09x slower                                                                                                   |
| pylint                  | 403 ms                                                                                                             | 438 ms: 1.09x slower                                                                                                   |
| html5lib                | 86.2 ms                                                                                                            | 94.0 ms: 1.09x slower                                                                                                  |
| sympy_sum               | 221 ms                                                                                                             | 245 ms: 1.11x slower                                                                                                   |
| sympy_str               | 394 ms                                                                                                             | 439 ms: 1.11x slower                                                                                                   |
| unpack_sequence         | 65.5 ns                                                                                                            | 73.8 ns: 1.13x slower                                                                                                  |
| mdp                     | 1.66 sec                                                                                                           | 1.92 sec: 1.16x slower                                                                                                 |
| Geometric mean          | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (16): django_template, unpickle, async_tree_none_tg, xml_etree_iterparse, subparsers, async_tree_memoization_tg, async_tree_memoization, async_tree_cpu_io_mixed, regex_compile, async_tree_cpu_io_mixed_tg, async_tree_io, typing_runtime_protocols, tornado_http, logging_simple, sqlglot_v2_transpile, async_tree_none

- Geometric mean (including insignificant results): 1.031x faster

# HPT report

- Reliability score: 86.51% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x