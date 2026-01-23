# Results vs. base

- fork: python
- ref: f3dd0cae6cea38b15b42
- machine: linux-x86_64
- commit hash: f3dd0ca
- commit date: 2026-01-23
- overall geometric mean: 1.051x faster
- HPT reliability: 99.64%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 358 ms                                                                                                             | 355 ms: 1.01x faster                                                                                                   |
| chameleon      | 19.2 ms                                                                                                            | 19.1 ms: 1.01x faster                                                                                                  |
| docutils       | 3.64 sec                                                                                                           | 3.81 sec: 1.05x slower                                                                                                 |
| html5lib       | 86.8 ms                                                                                                            | 87.7 ms: 1.01x slower                                                                                                  |
| sphinx         | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_memoization | 423 ms                                                                                                             | 410 ms: 1.03x faster                                                                                                   |
| async_tree_none        | 335 ms                                                                                                             | 327 ms: 1.02x faster                                                                                                   |
| coroutines             | 34.2 ms                                                                                                            | 33.9 ms: 1.01x faster                                                                                                  |
| asyncio_tcp            | 549 ms                                                                                                             | 555 ms: 1.01x slower                                                                                                   |
| async_generators       | 488 ms                                                                                                             | 507 ms: 1.04x slower                                                                                                   |
| Geometric mean         | (ref)                                                                                                              | 1.00x faster                                                                                                           |

Benchmark hidden because not significant (8): async_tree_none_tg, async_tree_memoization_tg, async_tree_io, async_tree_cpu_io_mixed, asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, asyncio_websockets, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 130 ms                                                                                                             | 105 ms: 1.25x faster                                                                                                   |
| float          | 97.8 ms                                                                                                            | 82.1 ms: 1.19x faster                                                                                                  |
| pidigits       | 277 ms                                                                                                             | 286 ms: 1.03x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.13x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 32.4 ms                                                                                                            | 29.5 ms: 1.10x faster                                                                                                  |
| regex_compile  | 179 ms                                                                                                             | 173 ms: 1.03x faster                                                                                                   |
| regex_effbot   | 3.99 ms                                                                                                            | 3.91 ms: 1.02x faster                                                                                                  |
| regex_dna      | 249 ms                                                                                                             | 250 ms: 1.00x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 309 us                                                                                                             | 253 us: 1.22x faster                                                                                                   |
| tomli_loads          | 2.64 sec                                                                                                           | 2.31 sec: 1.14x faster                                                                                                 |
| pickle_pure_python   | 444 us                                                                                                             | 400 us: 1.11x faster                                                                                                   |
| xml_etree_process    | 83.2 ms                                                                                                            | 76.5 ms: 1.09x faster                                                                                                  |
| json_dumps           | 13.9 ms                                                                                                            | 12.9 ms: 1.08x faster                                                                                                  |
| xml_etree_generate   | 119 ms                                                                                                             | 111 ms: 1.07x faster                                                                                                   |
| json_loads           | 40.3 us                                                                                                            | 39.6 us: 1.02x faster                                                                                                  |
| pickle_list          | 7.33 us                                                                                                            | 7.26 us: 1.01x faster                                                                                                  |
| unpickle_list        | 7.57 us                                                                                                            | 7.66 us: 1.01x slower                                                                                                  |
| pickle               | 17.7 us                                                                                                            | 18.0 us: 1.02x slower                                                                                                  |
| pickle_dict          | 41.8 us                                                                                                            | 44.2 us: 1.06x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (3): xml_etree_parse, unpickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.8 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.2 ms                                                                                                            | 15.1 ms: 1.14x faster                                                                                                  |
| genshi_text     | 30.9 ms                                                                                                            | 30.1 ms: 1.03x faster                                                                                                  |
| django_template | 51.4 ms                                                                                                            | 50.2 ms: 1.02x faster                                                                                                  |
| genshi_xml      | 73.3 ms                                                                                                            | 75.5 ms: 1.03x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.04x faster                                                                                                           |

All benchmarks:
===============

| Benchmark               | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-ripley-x86_64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|-------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                | 60.7 ms                                                                                                            | 25.7 ms: 2.36x faster                                                                                                  |
| richards_super          | 69.4 ms                                                                                                            | 31.0 ms: 2.24x faster                                                                                                  |
| scimark_lu              | 155 ms                                                                                                             | 113 ms: 1.37x faster                                                                                                   |
| nbody                   | 130 ms                                                                                                             | 105 ms: 1.25x faster                                                                                                   |
| logging_silent          | 146 ns                                                                                                             | 118 ns: 1.24x faster                                                                                                   |
| unpickle_pure_python    | 309 us                                                                                                             | 253 us: 1.22x faster                                                                                                   |
| scimark_monte_carlo     | 91.8 ms                                                                                                            | 75.1 ms: 1.22x faster                                                                                                  |
| scimark_sor             | 151 ms                                                                                                             | 123 ms: 1.22x faster                                                                                                   |
| deltablue               | 4.74 ms                                                                                                            | 3.93 ms: 1.21x faster                                                                                                  |
| float                   | 97.8 ms                                                                                                            | 82.1 ms: 1.19x faster                                                                                                  |
| bench_mp_pool           | 242 ms                                                                                                             | 203 ms: 1.19x faster                                                                                                   |
| scimark_fft             | 434 ms                                                                                                             | 369 ms: 1.17x faster                                                                                                   |
| deepcopy_memo           | 37.9 us                                                                                                            | 32.2 us: 1.17x faster                                                                                                  |
| pprint_safe_repr        | 1.02 sec                                                                                                           | 885 ms: 1.15x faster                                                                                                   |
| tomli_loads             | 2.64 sec                                                                                                           | 2.31 sec: 1.14x faster                                                                                                 |
| mako                    | 17.2 ms                                                                                                            | 15.1 ms: 1.14x faster                                                                                                  |
| pprint_pformat          | 2.07 sec                                                                                                           | 1.83 sec: 1.13x faster                                                                                                 |
| gc_traversal            | 6.60 ms                                                                                                            | 5.92 ms: 1.11x faster                                                                                                  |
| pickle_pure_python      | 444 us                                                                                                             | 400 us: 1.11x faster                                                                                                   |
| fannkuch                | 556 ms                                                                                                             | 501 ms: 1.11x faster                                                                                                   |
| pyflate                 | 593 ms                                                                                                             | 537 ms: 1.11x faster                                                                                                   |
| regex_v8                | 32.4 ms                                                                                                            | 29.5 ms: 1.10x faster                                                                                                  |
| xml_etree_process       | 83.2 ms                                                                                                            | 76.5 ms: 1.09x faster                                                                                                  |
| scimark_sparse_mat_mult | 6.63 ms                                                                                                            | 6.11 ms: 1.09x faster                                                                                                  |
| json_dumps              | 13.9 ms                                                                                                            | 12.9 ms: 1.08x faster                                                                                                  |
| go                      | 152 ms                                                                                                             | 141 ms: 1.08x faster                                                                                                   |
| deepcopy_reduce         | 3.70 us                                                                                                            | 3.44 us: 1.08x faster                                                                                                  |
| xml_etree_generate      | 119 ms                                                                                                             | 111 ms: 1.07x faster                                                                                                   |
| deepcopy                | 333 us                                                                                                             | 315 us: 1.06x faster                                                                                                   |
| bpe_tokeniser           | 6.06 sec                                                                                                           | 5.72 sec: 1.06x faster                                                                                                 |
| spectral_norm           | 132 ms                                                                                                             | 125 ms: 1.06x faster                                                                                                   |
| crypto_pyaes            | 101 ms                                                                                                             | 96.2 ms: 1.05x faster                                                                                                  |
| sqlglot_v2_parse        | 1.72 ms                                                                                                            | 1.64 ms: 1.05x faster                                                                                                  |
| chaos                   | 79.9 ms                                                                                                            | 76.8 ms: 1.04x faster                                                                                                  |
| json                    | 7.26 ms                                                                                                            | 6.98 ms: 1.04x faster                                                                                                  |
| k_core                  | 2.24 sec                                                                                                           | 2.17 sec: 1.04x faster                                                                                                 |
| regex_compile           | 179 ms                                                                                                             | 173 ms: 1.03x faster                                                                                                   |
| async_tree_memoization  | 423 ms                                                                                                             | 410 ms: 1.03x faster                                                                                                   |
| connected_components    | 456 ms                                                                                                             | 442 ms: 1.03x faster                                                                                                   |
| shortest_path           | 513 ms                                                                                                             | 499 ms: 1.03x faster                                                                                                   |
| sqlite_synth            | 3.21 us                                                                                                            | 3.12 us: 1.03x faster                                                                                                  |
| genshi_text             | 30.9 ms                                                                                                            | 30.1 ms: 1.03x faster                                                                                                  |
| sqlglot_v2_transpile    | 2.19 ms                                                                                                            | 2.13 ms: 1.03x faster                                                                                                  |
| async_tree_none         | 335 ms                                                                                                             | 327 ms: 1.02x faster                                                                                                   |
| django_template         | 51.4 ms                                                                                                            | 50.2 ms: 1.02x faster                                                                                                  |
| comprehensions          | 23.3 us                                                                                                            | 22.8 us: 1.02x faster                                                                                                  |
| regex_effbot            | 3.99 ms                                                                                                            | 3.91 ms: 1.02x faster                                                                                                  |
| meteor_contest          | 144 ms                                                                                                             | 141 ms: 1.02x faster                                                                                                   |
| json_loads              | 40.3 us                                                                                                            | 39.6 us: 1.02x faster                                                                                                  |
| sqlalchemy_imperative   | 29.8 ms                                                                                                            | 29.3 ms: 1.02x faster                                                                                                  |
| coverage                | 117 ms                                                                                                             | 116 ms: 1.01x faster                                                                                                   |
| nqueens                 | 114 ms                                                                                                             | 112 ms: 1.01x faster                                                                                                   |
| logging_simple          | 8.58 us                                                                                                            | 8.50 us: 1.01x faster                                                                                                  |
| 2to3                    | 358 ms                                                                                                             | 355 ms: 1.01x faster                                                                                                   |
| pickle_list             | 7.33 us                                                                                                            | 7.26 us: 1.01x faster                                                                                                  |
| coroutines              | 34.2 ms                                                                                                            | 33.9 ms: 1.01x faster                                                                                                  |
| chameleon               | 19.2 ms                                                                                                            | 19.1 ms: 1.01x faster                                                                                                  |
| regex_dna               | 249 ms                                                                                                             | 250 ms: 1.00x slower                                                                                                   |
| python_startup          | 17.8 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| python_startup_no_site  | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| html5lib                | 86.8 ms                                                                                                            | 87.7 ms: 1.01x slower                                                                                                  |
| asyncio_tcp             | 549 ms                                                                                                             | 555 ms: 1.01x slower                                                                                                   |
| unpickle_list           | 7.57 us                                                                                                            | 7.66 us: 1.01x slower                                                                                                  |
| thrift                  | 1.10 ms                                                                                                            | 1.11 ms: 1.01x slower                                                                                                  |
| pathlib                 | 25.4 ms                                                                                                            | 25.8 ms: 1.01x slower                                                                                                  |
| hexiom                  | 8.30 ms                                                                                                            | 8.44 ms: 1.02x slower                                                                                                  |
| pickle                  | 17.7 us                                                                                                            | 18.0 us: 1.02x slower                                                                                                  |
| sympy_expand            | 708 ms                                                                                                             | 723 ms: 1.02x slower                                                                                                   |
| genshi_xml              | 73.3 ms                                                                                                            | 75.5 ms: 1.03x slower                                                                                                  |
| sphinx                  | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| pidigits                | 277 ms                                                                                                             | 286 ms: 1.03x slower                                                                                                   |
| raytrace                | 363 ms                                                                                                             | 374 ms: 1.03x slower                                                                                                   |
| pycparser               | 1.55 sec                                                                                                           | 1.61 sec: 1.03x slower                                                                                                 |
| many_optionals          | 1.36 ms                                                                                                            | 1.41 ms: 1.04x slower                                                                                                  |
| sqlglot_v2_optimize     | 73.7 ms                                                                                                            | 76.5 ms: 1.04x slower                                                                                                  |
| async_generators        | 488 ms                                                                                                             | 507 ms: 1.04x slower                                                                                                   |
| sympy_integrate         | 27.6 ms                                                                                                            | 28.7 ms: 1.04x slower                                                                                                  |
| sqlglot_v2_normalize    | 147 ms                                                                                                             | 153 ms: 1.04x slower                                                                                                   |
| docutils                | 3.64 sec                                                                                                           | 3.81 sec: 1.05x slower                                                                                                 |
| telco                   | 230 ms                                                                                                             | 242 ms: 1.05x slower                                                                                                   |
| pickle_dict             | 41.8 us                                                                                                            | 44.2 us: 1.06x slower                                                                                                  |
| pylint                  | 409 ms                                                                                                             | 433 ms: 1.06x slower                                                                                                   |
| generators              | 40.0 ms                                                                                                            | 43.4 ms: 1.08x slower                                                                                                  |
| sympy_str               | 400 ms                                                                                                             | 437 ms: 1.09x slower                                                                                                   |
| sympy_sum               | 221 ms                                                                                                             | 243 ms: 1.10x slower                                                                                                   |
| mdp                     | 1.67 sec                                                                                                           | 1.95 sec: 1.17x slower                                                                                                 |
| unpack_sequence         | 61.4 ns                                                                                                            | 97.8 ns: 1.59x slower                                                                                                  |
| Geometric mean          | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (20): async_tree_none_tg, subparsers, async_tree_memoization_tg, async_tree_io, async_tree_cpu_io_mixed, sqlalchemy_declarative, xml_etree_parse, asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, asyncio_websockets, create_gc_cycles, dulwich_log, bench_thread_pool, unpickle, tornado_http, async_tree_io_tg, xml_etree_iterparse, xdsl_constant_fold, logging_format, typing_runtime_protocols

- Geometric mean (including insignificant results): 1.051x faster

# HPT report

- Reliability score: 99.64% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x