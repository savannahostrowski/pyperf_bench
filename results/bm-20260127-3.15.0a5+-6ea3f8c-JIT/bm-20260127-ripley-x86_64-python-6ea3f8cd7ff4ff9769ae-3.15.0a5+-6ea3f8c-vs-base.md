# Results vs. base

- fork: python
- ref: 6ea3f8cd7ff4ff9769ae
- machine: linux-x86_64
- commit hash: 6ea3f8c
- commit date: 2026-01-27
- overall geometric mean: 1.039x faster
- HPT reliability: 91.75%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 355 ms                                                                                                             | 356 ms: 1.00x slower                                                                                                   |
| chameleon      | 18.9 ms                                                                                                            | 19.1 ms: 1.01x slower                                                                                                  |
| docutils       | 3.60 sec                                                                                                           | 3.79 sec: 1.05x slower                                                                                                 |
| html5lib       | 85.9 ms                                                                                                            | 89.1 ms: 1.04x slower                                                                                                  |
| sphinx         | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| tornado_http   | 192 ms                                                                                                             | 193 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| coroutines             | 34.5 ms                                                                                                            | 33.3 ms: 1.03x faster                                                                                                  |
| async_tree_memoization | 422 ms                                                                                                             | 412 ms: 1.02x faster                                                                                                   |
| async_tree_none        | 339 ms                                                                                                             | 331 ms: 1.02x faster                                                                                                   |
| asyncio_tcp            | 565 ms                                                                                                             | 557 ms: 1.01x faster                                                                                                   |
| async_generators       | 489 ms                                                                                                             | 514 ms: 1.05x slower                                                                                                   |
| Geometric mean         | (ref)                                                                                                              | 1.00x faster                                                                                                           |

Benchmark hidden because not significant (8): async_tree_io, async_tree_memoization_tg, async_tree_none_tg, async_tree_cpu_io_mixed, asyncio_websockets, asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| float          | 103 ms                                                                                                             | 81.9 ms: 1.26x faster                                                                                                  |
| nbody          | 129 ms                                                                                                             | 107 ms: 1.20x faster                                                                                                   |
| pidigits       | 276 ms                                                                                                             | 276 ms: 1.00x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.15x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.14 ms                                                                                                            | 3.99 ms: 1.04x faster                                                                                                  |
| regex_dna      | 268 ms                                                                                                             | 262 ms: 1.03x faster                                                                                                   |
| regex_compile  | 176 ms                                                                                                             | 177 ms: 1.00x slower                                                                                                   |
| regex_v8       | 31.7 ms                                                                                                            | 34.3 ms: 1.08x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.00x slower                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 304 us                                                                                                             | 248 us: 1.22x faster                                                                                                   |
| tomli_loads          | 2.63 sec                                                                                                           | 2.34 sec: 1.12x faster                                                                                                 |
| pickle_pure_python   | 443 us                                                                                                             | 401 us: 1.10x faster                                                                                                   |
| pickle_dict          | 45.0 us                                                                                                            | 42.0 us: 1.07x faster                                                                                                  |
| xml_etree_generate   | 118 ms                                                                                                             | 111 ms: 1.06x faster                                                                                                   |
| xml_etree_process    | 82.1 ms                                                                                                            | 77.6 ms: 1.06x faster                                                                                                  |
| json_dumps           | 13.7 ms                                                                                                            | 13.2 ms: 1.04x faster                                                                                                  |
| pickle_list          | 7.34 us                                                                                                            | 7.24 us: 1.01x faster                                                                                                  |
| xml_etree_iterparse  | 122 ms                                                                                                             | 121 ms: 1.01x faster                                                                                                   |
| pickle               | 18.1 us                                                                                                            | 18.2 us: 1.01x slower                                                                                                  |
| json_loads           | 40.7 us                                                                                                            | 41.0 us: 1.01x slower                                                                                                  |
| unpickle             | 20.5 us                                                                                                            | 21.1 us: 1.03x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.8 ms                                                                                                            | 17.9 ms: 1.00x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.1 ms                                                                                                            | 15.2 ms: 1.12x faster                                                                                                  |
| genshi_text     | 31.0 ms                                                                                                            | 29.8 ms: 1.04x faster                                                                                                  |
| django_template | 51.1 ms                                                                                                            | 51.6 ms: 1.01x slower                                                                                                  |
| genshi_xml      | 71.6 ms                                                                                                            | 76.1 ms: 1.06x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.02x faster                                                                                                           |

All benchmarks:
===============

| Benchmark               | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|-------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                | 60.0 ms                                                                                                            | 25.7 ms: 2.34x faster                                                                                                  |
| richards_super          | 68.5 ms                                                                                                            | 30.9 ms: 2.22x faster                                                                                                  |
| scimark_lu              | 155 ms                                                                                                             | 113 ms: 1.37x faster                                                                                                   |
| float                   | 103 ms                                                                                                             | 81.9 ms: 1.26x faster                                                                                                  |
| scimark_sor             | 152 ms                                                                                                             | 123 ms: 1.23x faster                                                                                                   |
| unpickle_pure_python    | 304 us                                                                                                             | 248 us: 1.22x faster                                                                                                   |
| logging_silent          | 142 ns                                                                                                             | 118 ns: 1.20x faster                                                                                                   |
| nbody                   | 129 ms                                                                                                             | 107 ms: 1.20x faster                                                                                                   |
| deltablue               | 4.74 ms                                                                                                            | 3.95 ms: 1.20x faster                                                                                                  |
| scimark_monte_carlo     | 88.9 ms                                                                                                            | 74.5 ms: 1.19x faster                                                                                                  |
| deepcopy_memo           | 37.9 us                                                                                                            | 32.5 us: 1.17x faster                                                                                                  |
| scimark_fft             | 432 ms                                                                                                             | 372 ms: 1.16x faster                                                                                                   |
| pprint_safe_repr        | 997 ms                                                                                                             | 884 ms: 1.13x faster                                                                                                   |
| spectral_norm           | 133 ms                                                                                                             | 118 ms: 1.13x faster                                                                                                   |
| mako                    | 17.1 ms                                                                                                            | 15.2 ms: 1.12x faster                                                                                                  |
| tomli_loads             | 2.63 sec                                                                                                           | 2.34 sec: 1.12x faster                                                                                                 |
| pyflate                 | 585 ms                                                                                                             | 526 ms: 1.11x faster                                                                                                   |
| pprint_pformat          | 2.05 sec                                                                                                           | 1.85 sec: 1.11x faster                                                                                                 |
| pickle_pure_python      | 443 us                                                                                                             | 401 us: 1.10x faster                                                                                                   |
| fannkuch                | 549 ms                                                                                                             | 499 ms: 1.10x faster                                                                                                   |
| go                      | 153 ms                                                                                                             | 143 ms: 1.07x faster                                                                                                   |
| pickle_dict             | 45.0 us                                                                                                            | 42.0 us: 1.07x faster                                                                                                  |
| scimark_sparse_mat_mult | 6.54 ms                                                                                                            | 6.13 ms: 1.07x faster                                                                                                  |
| xml_etree_generate      | 118 ms                                                                                                             | 111 ms: 1.06x faster                                                                                                   |
| deepcopy_reduce         | 3.67 us                                                                                                            | 3.46 us: 1.06x faster                                                                                                  |
| xml_etree_process       | 82.1 ms                                                                                                            | 77.6 ms: 1.06x faster                                                                                                  |
| bpe_tokeniser           | 6.02 sec                                                                                                           | 5.72 sec: 1.05x faster                                                                                                 |
| genshi_text             | 31.0 ms                                                                                                            | 29.8 ms: 1.04x faster                                                                                                  |
| json_dumps              | 13.7 ms                                                                                                            | 13.2 ms: 1.04x faster                                                                                                  |
| regex_effbot            | 4.14 ms                                                                                                            | 3.99 ms: 1.04x faster                                                                                                  |
| chaos                   | 78.9 ms                                                                                                            | 76.2 ms: 1.03x faster                                                                                                  |
| coroutines              | 34.5 ms                                                                                                            | 33.3 ms: 1.03x faster                                                                                                  |
| sqlite_synth            | 3.25 us                                                                                                            | 3.15 us: 1.03x faster                                                                                                  |
| connected_components    | 457 ms                                                                                                             | 443 ms: 1.03x faster                                                                                                   |
| sqlglot_v2_parse        | 1.71 ms                                                                                                            | 1.66 ms: 1.03x faster                                                                                                  |
| meteor_contest          | 147 ms                                                                                                             | 143 ms: 1.03x faster                                                                                                   |
| k_core                  | 2.25 sec                                                                                                           | 2.19 sec: 1.03x faster                                                                                                 |
| comprehensions          | 23.1 us                                                                                                            | 22.5 us: 1.03x faster                                                                                                  |
| regex_dna               | 268 ms                                                                                                             | 262 ms: 1.03x faster                                                                                                   |
| deepcopy                | 332 us                                                                                                             | 324 us: 1.03x faster                                                                                                   |
| async_tree_memoization  | 422 ms                                                                                                             | 412 ms: 1.02x faster                                                                                                   |
| async_tree_none         | 339 ms                                                                                                             | 331 ms: 1.02x faster                                                                                                   |
| sqlglot_v2_transpile    | 2.17 ms                                                                                                            | 2.12 ms: 1.02x faster                                                                                                  |
| crypto_pyaes            | 99.1 ms                                                                                                            | 97.2 ms: 1.02x faster                                                                                                  |
| json                    | 7.28 ms                                                                                                            | 7.16 ms: 1.02x faster                                                                                                  |
| shortest_path           | 509 ms                                                                                                             | 500 ms: 1.02x faster                                                                                                   |
| pickle_list             | 7.34 us                                                                                                            | 7.24 us: 1.01x faster                                                                                                  |
| asyncio_tcp             | 565 ms                                                                                                             | 557 ms: 1.01x faster                                                                                                   |
| xml_etree_iterparse     | 122 ms                                                                                                             | 121 ms: 1.01x faster                                                                                                   |
| coverage                | 117 ms                                                                                                             | 116 ms: 1.01x faster                                                                                                   |
| pidigits                | 276 ms                                                                                                             | 276 ms: 1.00x faster                                                                                                   |
| gc_traversal            | 6.53 ms                                                                                                            | 6.54 ms: 1.00x slower                                                                                                  |
| regex_compile           | 176 ms                                                                                                             | 177 ms: 1.00x slower                                                                                                   |
| 2to3                    | 355 ms                                                                                                             | 356 ms: 1.00x slower                                                                                                   |
| python_startup          | 17.8 ms                                                                                                            | 17.9 ms: 1.00x slower                                                                                                  |
| bench_thread_pool       | 1.75 ms                                                                                                            | 1.76 ms: 1.01x slower                                                                                                  |
| pickle                  | 18.1 us                                                                                                            | 18.2 us: 1.01x slower                                                                                                  |
| tornado_http            | 192 ms                                                                                                             | 193 ms: 1.01x slower                                                                                                   |
| json_loads              | 40.7 us                                                                                                            | 41.0 us: 1.01x slower                                                                                                  |
| pathlib                 | 25.3 ms                                                                                                            | 25.5 ms: 1.01x slower                                                                                                  |
| python_startup_no_site  | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| chameleon               | 18.9 ms                                                                                                            | 19.1 ms: 1.01x slower                                                                                                  |
| django_template         | 51.1 ms                                                                                                            | 51.6 ms: 1.01x slower                                                                                                  |
| nqueens                 | 112 ms                                                                                                             | 114 ms: 1.02x slower                                                                                                   |
| sqlalchemy_declarative  | 184 ms                                                                                                             | 188 ms: 1.02x slower                                                                                                   |
| dulwich_log             | 98.7 ms                                                                                                            | 101 ms: 1.02x slower                                                                                                   |
| pycparser               | 1.53 sec                                                                                                           | 1.57 sec: 1.02x slower                                                                                                 |
| thrift                  | 1.09 ms                                                                                                            | 1.12 ms: 1.03x slower                                                                                                  |
| sphinx                  | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| unpickle                | 20.5 us                                                                                                            | 21.1 us: 1.03x slower                                                                                                  |
| html5lib                | 85.9 ms                                                                                                            | 89.1 ms: 1.04x slower                                                                                                  |
| sympy_expand            | 706 ms                                                                                                             | 732 ms: 1.04x slower                                                                                                   |
| xdsl_constant_fold      | 65.2 ms                                                                                                            | 68.0 ms: 1.04x slower                                                                                                  |
| generators              | 40.3 ms                                                                                                            | 42.2 ms: 1.05x slower                                                                                                  |
| sqlglot_v2_optimize     | 73.1 ms                                                                                                            | 76.6 ms: 1.05x slower                                                                                                  |
| sympy_integrate         | 27.4 ms                                                                                                            | 28.8 ms: 1.05x slower                                                                                                  |
| raytrace                | 360 ms                                                                                                             | 378 ms: 1.05x slower                                                                                                   |
| async_generators        | 489 ms                                                                                                             | 514 ms: 1.05x slower                                                                                                   |
| unpack_sequence         | 63.9 ns                                                                                                            | 67.3 ns: 1.05x slower                                                                                                  |
| docutils                | 3.60 sec                                                                                                           | 3.79 sec: 1.05x slower                                                                                                 |
| logging_simple          | 8.28 us                                                                                                            | 8.75 us: 1.06x slower                                                                                                  |
| hexiom                  | 8.13 ms                                                                                                            | 8.60 ms: 1.06x slower                                                                                                  |
| logging_format          | 9.45 us                                                                                                            | 10.0 us: 1.06x slower                                                                                                  |
| genshi_xml              | 71.6 ms                                                                                                            | 76.1 ms: 1.06x slower                                                                                                  |
| many_optionals          | 1.34 ms                                                                                                            | 1.43 ms: 1.07x slower                                                                                                  |
| telco                   | 227 ms                                                                                                             | 244 ms: 1.08x slower                                                                                                   |
| sqlglot_v2_normalize    | 145 ms                                                                                                             | 156 ms: 1.08x slower                                                                                                   |
| regex_v8                | 31.7 ms                                                                                                            | 34.3 ms: 1.08x slower                                                                                                  |
| pylint                  | 403 ms                                                                                                             | 438 ms: 1.09x slower                                                                                                   |
| sympy_sum               | 221 ms                                                                                                             | 244 ms: 1.10x slower                                                                                                   |
| sympy_str               | 393 ms                                                                                                             | 442 ms: 1.12x slower                                                                                                   |
| mdp                     | 1.67 sec                                                                                                           | 1.92 sec: 1.15x slower                                                                                                 |
| Geometric mean          | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (15): bench_mp_pool, async_tree_io, async_tree_memoization_tg, async_tree_none_tg, unpickle_list, xml_etree_parse, create_gc_cycles, async_tree_cpu_io_mixed, typing_runtime_protocols, asyncio_websockets, asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, subparsers, sqlalchemy_imperative, async_tree_io_tg

- Geometric mean (including insignificant results): 1.039x faster

# HPT report

- Reliability score: 91.75% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x