# Results vs. base

- fork: python
- ref: fa3abf5a51d42b2d62e1
- machine: linux-x86_64
- commit hash: fa3abf5
- commit date: 2026-01-20
- overall geometric mean: 1.050x faster
- HPT reliability: 99.92%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 357 ms                                                                                                             | 354 ms: 1.01x faster                                                                                                   |
| docutils       | 3.64 sec                                                                                                           | 3.82 sec: 1.05x slower                                                                                                 |
| html5lib       | 87.0 ms                                                                                                            | 90.0 ms: 1.04x slower                                                                                                  |
| sphinx         | 1.37 sec                                                                                                           | 1.40 sec: 1.02x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_none           | 342 ms                                                                                                             | 323 ms: 1.06x faster                                                                                                   |
| async_tree_memoization    | 424 ms                                                                                                             | 408 ms: 1.04x faster                                                                                                   |
| async_tree_io             | 773 ms                                                                                                             | 750 ms: 1.03x faster                                                                                                   |
| coroutines                | 34.5 ms                                                                                                            | 33.5 ms: 1.03x faster                                                                                                  |
| async_tree_memoization_tg | 406 ms                                                                                                             | 394 ms: 1.03x faster                                                                                                   |
| async_tree_none_tg        | 343 ms                                                                                                             | 333 ms: 1.03x faster                                                                                                   |
| async_tree_cpu_io_mixed   | 690 ms                                                                                                             | 673 ms: 1.02x faster                                                                                                   |
| asyncio_tcp_ssl           | 2.08 sec                                                                                                           | 2.07 sec: 1.00x faster                                                                                                 |
| async_generators          | 484 ms                                                                                                             | 509 ms: 1.05x slower                                                                                                   |
| Geometric mean            | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (4): async_tree_io_tg, async_tree_cpu_io_mixed_tg, asyncio_tcp, asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| float          | 104 ms                                                                                                             | 83.0 ms: 1.25x faster                                                                                                  |
| nbody          | 129 ms                                                                                                             | 107 ms: 1.21x faster                                                                                                   |
| pidigits       | 286 ms                                                                                                             | 275 ms: 1.04x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.16x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.07 ms                                                                                                            | 3.80 ms: 1.07x faster                                                                                                  |
| regex_compile  | 178 ms                                                                                                             | 171 ms: 1.04x faster                                                                                                   |
| regex_v8       | 30.7 ms                                                                                                            | 29.9 ms: 1.03x faster                                                                                                  |
| regex_dna      | 252 ms                                                                                                             | 249 ms: 1.01x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 305 us                                                                                                             | 254 us: 1.20x faster                                                                                                   |
| tomli_loads          | 2.68 sec                                                                                                           | 2.35 sec: 1.14x faster                                                                                                 |
| pickle_pure_python   | 440 us                                                                                                             | 401 us: 1.10x faster                                                                                                   |
| xml_etree_process    | 83.9 ms                                                                                                            | 77.3 ms: 1.09x faster                                                                                                  |
| xml_etree_generate   | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| json_dumps           | 14.0 ms                                                                                                            | 13.1 ms: 1.07x faster                                                                                                  |
| xml_etree_iterparse  | 124 ms                                                                                                             | 120 ms: 1.03x faster                                                                                                   |
| pickle_dict          | 45.2 us                                                                                                            | 44.3 us: 1.02x faster                                                                                                  |
| xml_etree_parse      | 189 ms                                                                                                             | 186 ms: 1.02x faster                                                                                                   |
| json_loads           | 40.6 us                                                                                                            | 40.2 us: 1.01x faster                                                                                                  |
| unpickle             | 21.2 us                                                                                                            | 21.1 us: 1.01x faster                                                                                                  |
| unpickle_list        | 7.51 us                                                                                                            | 7.56 us: 1.01x slower                                                                                                  |
| pickle_list          | 7.18 us                                                                                                            | 7.36 us: 1.03x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.8 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.4 ms                                                                                                            | 15.2 ms: 1.15x faster                                                                                                  |
| django_template | 51.3 ms                                                                                                            | 49.9 ms: 1.03x faster                                                                                                  |
| genshi_text     | 30.5 ms                                                                                                            | 30.2 ms: 1.01x faster                                                                                                  |
| genshi_xml      | 71.5 ms                                                                                                            | 75.6 ms: 1.06x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.03x faster                                                                                                           |

All benchmarks:
===============

| Benchmark                 | results/bm-20260120-3.15.0a5+-fa3abf5/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json | results/bm-20260120-3.15.0a5+-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5+-fa3abf5.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                  | 60.4 ms                                                                                                            | 25.8 ms: 2.34x faster                                                                                                  |
| richards_super            | 68.9 ms                                                                                                            | 31.4 ms: 2.19x faster                                                                                                  |
| scimark_lu                | 155 ms                                                                                                             | 112 ms: 1.38x faster                                                                                                   |
| float                     | 104 ms                                                                                                             | 83.0 ms: 1.25x faster                                                                                                  |
| scimark_sor               | 152 ms                                                                                                             | 123 ms: 1.23x faster                                                                                                   |
| deltablue                 | 4.69 ms                                                                                                            | 3.86 ms: 1.21x faster                                                                                                  |
| logging_silent            | 144 ns                                                                                                             | 119 ns: 1.21x faster                                                                                                   |
| nbody                     | 129 ms                                                                                                             | 107 ms: 1.21x faster                                                                                                   |
| scimark_monte_carlo       | 88.1 ms                                                                                                            | 73.2 ms: 1.20x faster                                                                                                  |
| unpickle_pure_python      | 305 us                                                                                                             | 254 us: 1.20x faster                                                                                                   |
| pyflate                   | 596 ms                                                                                                             | 511 ms: 1.17x faster                                                                                                   |
| scimark_fft               | 439 ms                                                                                                             | 376 ms: 1.17x faster                                                                                                   |
| mako                      | 17.4 ms                                                                                                            | 15.2 ms: 1.15x faster                                                                                                  |
| go                        | 151 ms                                                                                                             | 133 ms: 1.14x faster                                                                                                   |
| tomli_loads               | 2.68 sec                                                                                                           | 2.35 sec: 1.14x faster                                                                                                 |
| pprint_pformat            | 2.06 sec                                                                                                           | 1.82 sec: 1.13x faster                                                                                                 |
| pprint_safe_repr          | 1.01 sec                                                                                                           | 899 ms: 1.12x faster                                                                                                   |
| fannkuch                  | 558 ms                                                                                                             | 502 ms: 1.11x faster                                                                                                   |
| deepcopy_memo             | 38.5 us                                                                                                            | 34.8 us: 1.11x faster                                                                                                  |
| pickle_pure_python        | 440 us                                                                                                             | 401 us: 1.10x faster                                                                                                   |
| spectral_norm             | 136 ms                                                                                                             | 124 ms: 1.09x faster                                                                                                   |
| xml_etree_process         | 83.9 ms                                                                                                            | 77.3 ms: 1.09x faster                                                                                                  |
| xml_etree_generate        | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| regex_effbot              | 4.07 ms                                                                                                            | 3.80 ms: 1.07x faster                                                                                                  |
| deepcopy_reduce           | 3.66 us                                                                                                            | 3.43 us: 1.07x faster                                                                                                  |
| json_dumps                | 14.0 ms                                                                                                            | 13.1 ms: 1.07x faster                                                                                                  |
| scimark_sparse_mat_mult   | 6.48 ms                                                                                                            | 6.10 ms: 1.06x faster                                                                                                  |
| async_tree_none           | 342 ms                                                                                                             | 323 ms: 1.06x faster                                                                                                   |
| deepcopy                  | 334 us                                                                                                             | 316 us: 1.06x faster                                                                                                   |
| chaos                     | 79.8 ms                                                                                                            | 75.9 ms: 1.05x faster                                                                                                  |
| sqlglot_v2_parse          | 1.73 ms                                                                                                            | 1.65 ms: 1.05x faster                                                                                                  |
| bpe_tokeniser             | 6.04 sec                                                                                                           | 5.78 sec: 1.04x faster                                                                                                 |
| crypto_pyaes              | 102 ms                                                                                                             | 97.3 ms: 1.04x faster                                                                                                  |
| regex_compile             | 178 ms                                                                                                             | 171 ms: 1.04x faster                                                                                                   |
| pidigits                  | 286 ms                                                                                                             | 275 ms: 1.04x faster                                                                                                   |
| connected_components      | 459 ms                                                                                                             | 442 ms: 1.04x faster                                                                                                   |
| async_tree_memoization    | 424 ms                                                                                                             | 408 ms: 1.04x faster                                                                                                   |
| meteor_contest            | 147 ms                                                                                                             | 142 ms: 1.04x faster                                                                                                   |
| sqlite_synth              | 3.22 us                                                                                                            | 3.12 us: 1.03x faster                                                                                                  |
| xml_etree_iterparse       | 124 ms                                                                                                             | 120 ms: 1.03x faster                                                                                                   |
| async_tree_io             | 773 ms                                                                                                             | 750 ms: 1.03x faster                                                                                                   |
| coroutines                | 34.5 ms                                                                                                            | 33.5 ms: 1.03x faster                                                                                                  |
| async_tree_memoization_tg | 406 ms                                                                                                             | 394 ms: 1.03x faster                                                                                                   |
| async_tree_none_tg        | 343 ms                                                                                                             | 333 ms: 1.03x faster                                                                                                   |
| django_template           | 51.3 ms                                                                                                            | 49.9 ms: 1.03x faster                                                                                                  |
| regex_v8                  | 30.7 ms                                                                                                            | 29.9 ms: 1.03x faster                                                                                                  |
| async_tree_cpu_io_mixed   | 690 ms                                                                                                             | 673 ms: 1.02x faster                                                                                                   |
| sqlglot_v2_transpile      | 2.19 ms                                                                                                            | 2.14 ms: 1.02x faster                                                                                                  |
| k_core                    | 2.23 sec                                                                                                           | 2.18 sec: 1.02x faster                                                                                                 |
| pickle_dict               | 45.2 us                                                                                                            | 44.3 us: 1.02x faster                                                                                                  |
| shortest_path             | 511 ms                                                                                                             | 503 ms: 1.02x faster                                                                                                   |
| xml_etree_parse           | 189 ms                                                                                                             | 186 ms: 1.02x faster                                                                                                   |
| json                      | 7.20 ms                                                                                                            | 7.09 ms: 1.02x faster                                                                                                  |
| regex_dna                 | 252 ms                                                                                                             | 249 ms: 1.01x faster                                                                                                   |
| typing_runtime_protocols  | 229 us                                                                                                             | 226 us: 1.01x faster                                                                                                   |
| logging_format            | 9.73 us                                                                                                            | 9.62 us: 1.01x faster                                                                                                  |
| json_loads                | 40.6 us                                                                                                            | 40.2 us: 1.01x faster                                                                                                  |
| genshi_text               | 30.5 ms                                                                                                            | 30.2 ms: 1.01x faster                                                                                                  |
| unpickle                  | 21.2 us                                                                                                            | 21.1 us: 1.01x faster                                                                                                  |
| 2to3                      | 357 ms                                                                                                             | 354 ms: 1.01x faster                                                                                                   |
| bench_thread_pool         | 1.75 ms                                                                                                            | 1.74 ms: 1.00x faster                                                                                                  |
| asyncio_tcp_ssl           | 2.08 sec                                                                                                           | 2.07 sec: 1.00x faster                                                                                                 |
| unpickle_list             | 7.51 us                                                                                                            | 7.56 us: 1.01x slower                                                                                                  |
| sqlalchemy_declarative    | 186 ms                                                                                                             | 188 ms: 1.01x slower                                                                                                   |
| python_startup            | 17.8 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| python_startup_no_site    | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| create_gc_cycles          | 2.85 ms                                                                                                            | 2.90 ms: 1.02x slower                                                                                                  |
| hexiom                    | 8.16 ms                                                                                                            | 8.33 ms: 1.02x slower                                                                                                  |
| sphinx                    | 1.37 sec                                                                                                           | 1.40 sec: 1.02x slower                                                                                                 |
| pickle_list               | 7.18 us                                                                                                            | 7.36 us: 1.03x slower                                                                                                  |
| xdsl_constant_fold        | 65.1 ms                                                                                                            | 66.9 ms: 1.03x slower                                                                                                  |
| sympy_integrate           | 27.8 ms                                                                                                            | 28.6 ms: 1.03x slower                                                                                                  |
| telco                     | 227 ms                                                                                                             | 234 ms: 1.03x slower                                                                                                   |
| html5lib                  | 87.0 ms                                                                                                            | 90.0 ms: 1.04x slower                                                                                                  |
| dulwich_log               | 98.0 ms                                                                                                            | 101 ms: 1.04x slower                                                                                                   |
| generators                | 40.1 ms                                                                                                            | 42.0 ms: 1.05x slower                                                                                                  |
| many_optionals            | 1.37 ms                                                                                                            | 1.43 ms: 1.05x slower                                                                                                  |
| thrift                    | 1.08 ms                                                                                                            | 1.13 ms: 1.05x slower                                                                                                  |
| raytrace                  | 360 ms                                                                                                             | 378 ms: 1.05x slower                                                                                                   |
| sqlalchemy_imperative     | 28.5 ms                                                                                                            | 29.9 ms: 1.05x slower                                                                                                  |
| docutils                  | 3.64 sec                                                                                                           | 3.82 sec: 1.05x slower                                                                                                 |
| async_generators          | 484 ms                                                                                                             | 509 ms: 1.05x slower                                                                                                   |
| pycparser                 | 1.53 sec                                                                                                           | 1.61 sec: 1.05x slower                                                                                                 |
| sqlglot_v2_optimize       | 73.8 ms                                                                                                            | 77.6 ms: 1.05x slower                                                                                                  |
| sqlglot_v2_normalize      | 147 ms                                                                                                             | 155 ms: 1.06x slower                                                                                                   |
| genshi_xml                | 71.5 ms                                                                                                            | 75.6 ms: 1.06x slower                                                                                                  |
| pylint                    | 404 ms                                                                                                             | 433 ms: 1.07x slower                                                                                                   |
| sympy_sum                 | 225 ms                                                                                                             | 243 ms: 1.08x slower                                                                                                   |
| sympy_str                 | 402 ms                                                                                                             | 437 ms: 1.09x slower                                                                                                   |
| unpack_sequence           | 58.8 ns                                                                                                            | 64.1 ns: 1.09x slower                                                                                                  |
| mdp                       | 1.68 sec                                                                                                           | 1.96 sec: 1.17x slower                                                                                                 |
| Geometric mean            | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (16): bench_mp_pool, async_tree_io_tg, async_tree_cpu_io_mixed_tg, pathlib, subparsers, pickle, asyncio_tcp, asyncio_websockets, chameleon, gc_traversal, comprehensions, tornado_http, logging_simple, coverage, nqueens, sympy_expand

- Geometric mean (including insignificant results): 1.050x faster

# HPT report

- Reliability score: 99.92% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x