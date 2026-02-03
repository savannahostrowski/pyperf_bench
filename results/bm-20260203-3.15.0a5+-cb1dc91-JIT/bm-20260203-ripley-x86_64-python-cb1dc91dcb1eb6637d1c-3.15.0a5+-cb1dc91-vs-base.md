# Results vs. base

- fork: python
- ref: cb1dc91dcb1eb6637d1c
- machine: linux-x86_64
- commit hash: cb1dc91
- commit date: 2026-02-03
- overall geometric mean: 1.046x faster
- HPT reliability: 98.85%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 354 ms                                                                                                             | 356 ms: 1.01x slower                                                                                                   |
| chameleon      | 19.0 ms                                                                                                            | 18.7 ms: 1.02x faster                                                                                                  |
| docutils       | 3.65 sec                                                                                                           | 3.83 sec: 1.05x slower                                                                                                 |
| html5lib       | 85.3 ms                                                                                                            | 88.2 ms: 1.03x slower                                                                                                  |
| sphinx         | 1.37 sec                                                                                                           | 1.41 sec: 1.03x slower                                                                                                 |
| tornado_http   | 192 ms                                                                                                             | 194 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_memoization     | 410 ms                                                                                                             | 392 ms: 1.05x faster                                                                                                   |
| async_tree_none            | 348 ms                                                                                                             | 333 ms: 1.04x faster                                                                                                   |
| async_tree_none_tg         | 343 ms                                                                                                             | 333 ms: 1.03x faster                                                                                                   |
| async_tree_cpu_io_mixed    | 674 ms                                                                                                             | 656 ms: 1.03x faster                                                                                                   |
| async_tree_cpu_io_mixed_tg | 680 ms                                                                                                             | 664 ms: 1.02x faster                                                                                                   |
| async_tree_memoization_tg  | 402 ms                                                                                                             | 395 ms: 1.02x faster                                                                                                   |
| async_tree_io              | 782 ms                                                                                                             | 770 ms: 1.02x faster                                                                                                   |
| coroutines                 | 34.0 ms                                                                                                            | 33.4 ms: 1.02x faster                                                                                                  |
| asyncio_tcp_ssl            | 2.07 sec                                                                                                           | 2.04 sec: 1.01x faster                                                                                                 |
| async_generators           | 482 ms                                                                                                             | 501 ms: 1.04x slower                                                                                                   |
| Geometric mean             | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (3): async_tree_io_tg, asyncio_tcp, asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 131 ms                                                                                                             | 105 ms: 1.25x faster                                                                                                   |
| float          | 101 ms                                                                                                             | 81.2 ms: 1.24x faster                                                                                                  |
| pidigits       | 277 ms                                                                                                             | 279 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.15x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.06 ms                                                                                                            | 3.92 ms: 1.04x faster                                                                                                  |
| regex_compile  | 175 ms                                                                                                             | 173 ms: 1.01x faster                                                                                                   |
| regex_dna      | 251 ms                                                                                                             | 260 ms: 1.03x slower                                                                                                   |
| regex_v8       | 30.7 ms                                                                                                            | 33.3 ms: 1.08x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 304 us                                                                                                             | 248 us: 1.23x faster                                                                                                   |
| tomli_loads          | 2.60 sec                                                                                                           | 2.33 sec: 1.11x faster                                                                                                 |
| pickle_pure_python   | 438 us                                                                                                             | 397 us: 1.10x faster                                                                                                   |
| pickle_dict          | 46.2 us                                                                                                            | 42.1 us: 1.10x faster                                                                                                  |
| xml_etree_generate   | 119 ms                                                                                                             | 111 ms: 1.08x faster                                                                                                   |
| xml_etree_process    | 82.9 ms                                                                                                            | 77.4 ms: 1.07x faster                                                                                                  |
| json_dumps           | 13.9 ms                                                                                                            | 13.3 ms: 1.05x faster                                                                                                  |
| pickle               | 18.6 us                                                                                                            | 17.9 us: 1.04x faster                                                                                                  |
| pickle_list          | 7.38 us                                                                                                            | 7.22 us: 1.02x faster                                                                                                  |
| json_loads           | 40.6 us                                                                                                            | 39.9 us: 1.02x faster                                                                                                  |
| unpickle_list        | 7.69 us                                                                                                            | 7.58 us: 1.01x faster                                                                                                  |
| xml_etree_iterparse  | 122 ms                                                                                                             | 120 ms: 1.01x faster                                                                                                   |
| unpickle             | 21.5 us                                                                                                            | 21.3 us: 1.01x faster                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.06x faster                                                                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.8 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako           | 17.1 ms                                                                                                            | 15.2 ms: 1.13x faster                                                                                                  |
| genshi_text    | 30.3 ms                                                                                                            | 29.6 ms: 1.02x faster                                                                                                  |
| genshi_xml     | 70.5 ms                                                                                                            | 74.0 ms: 1.05x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                  | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-ripley-x86_64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                   | 60.3 ms                                                                                                            | 25.0 ms: 2.41x faster                                                                                                  |
| richards_super             | 68.9 ms                                                                                                            | 30.4 ms: 2.27x faster                                                                                                  |
| scimark_lu                 | 156 ms                                                                                                             | 113 ms: 1.38x faster                                                                                                   |
| logging_silent             | 144 ns                                                                                                             | 115 ns: 1.26x faster                                                                                                   |
| nbody                      | 131 ms                                                                                                             | 105 ms: 1.25x faster                                                                                                   |
| scimark_sor                | 152 ms                                                                                                             | 122 ms: 1.24x faster                                                                                                   |
| float                      | 101 ms                                                                                                             | 81.2 ms: 1.24x faster                                                                                                  |
| deltablue                  | 4.70 ms                                                                                                            | 3.82 ms: 1.23x faster                                                                                                  |
| unpickle_pure_python       | 304 us                                                                                                             | 248 us: 1.23x faster                                                                                                   |
| scimark_monte_carlo        | 89.5 ms                                                                                                            | 74.4 ms: 1.20x faster                                                                                                  |
| deepcopy_memo              | 37.3 us                                                                                                            | 31.6 us: 1.18x faster                                                                                                  |
| scimark_fft                | 438 ms                                                                                                             | 372 ms: 1.18x faster                                                                                                   |
| pprint_safe_repr           | 989 ms                                                                                                             | 872 ms: 1.13x faster                                                                                                   |
| spectral_norm              | 131 ms                                                                                                             | 117 ms: 1.13x faster                                                                                                   |
| mako                       | 17.1 ms                                                                                                            | 15.2 ms: 1.13x faster                                                                                                  |
| pyflate                    | 583 ms                                                                                                             | 521 ms: 1.12x faster                                                                                                   |
| fannkuch                   | 550 ms                                                                                                             | 492 ms: 1.12x faster                                                                                                   |
| tomli_loads                | 2.60 sec                                                                                                           | 2.33 sec: 1.11x faster                                                                                                 |
| pprint_pformat             | 2.02 sec                                                                                                           | 1.82 sec: 1.11x faster                                                                                                 |
| pickle_pure_python         | 438 us                                                                                                             | 397 us: 1.10x faster                                                                                                   |
| pickle_dict                | 46.2 us                                                                                                            | 42.1 us: 1.10x faster                                                                                                  |
| xml_etree_generate         | 119 ms                                                                                                             | 111 ms: 1.08x faster                                                                                                   |
| go                         | 150 ms                                                                                                             | 139 ms: 1.08x faster                                                                                                   |
| xml_etree_process          | 82.9 ms                                                                                                            | 77.4 ms: 1.07x faster                                                                                                  |
| deepcopy_reduce            | 3.65 us                                                                                                            | 3.41 us: 1.07x faster                                                                                                  |
| gc_traversal               | 6.16 ms                                                                                                            | 5.80 ms: 1.06x faster                                                                                                  |
| sqlite_synth               | 3.31 us                                                                                                            | 3.15 us: 1.05x faster                                                                                                  |
| scimark_sparse_mat_mult    | 6.38 ms                                                                                                            | 6.08 ms: 1.05x faster                                                                                                  |
| chaos                      | 80.3 ms                                                                                                            | 76.7 ms: 1.05x faster                                                                                                  |
| async_tree_memoization     | 410 ms                                                                                                             | 392 ms: 1.05x faster                                                                                                   |
| connected_components       | 458 ms                                                                                                             | 438 ms: 1.05x faster                                                                                                   |
| json_dumps                 | 13.9 ms                                                                                                            | 13.3 ms: 1.05x faster                                                                                                  |
| bpe_tokeniser              | 6.02 sec                                                                                                           | 5.76 sec: 1.05x faster                                                                                                 |
| pickle                     | 18.6 us                                                                                                            | 17.9 us: 1.04x faster                                                                                                  |
| async_tree_none            | 348 ms                                                                                                             | 333 ms: 1.04x faster                                                                                                   |
| sqlglot_v2_parse           | 1.70 ms                                                                                                            | 1.63 ms: 1.04x faster                                                                                                  |
| json                       | 7.26 ms                                                                                                            | 7.00 ms: 1.04x faster                                                                                                  |
| regex_effbot               | 4.06 ms                                                                                                            | 3.92 ms: 1.04x faster                                                                                                  |
| async_tree_none_tg         | 343 ms                                                                                                             | 333 ms: 1.03x faster                                                                                                   |
| deepcopy                   | 331 us                                                                                                             | 321 us: 1.03x faster                                                                                                   |
| async_tree_cpu_io_mixed    | 674 ms                                                                                                             | 656 ms: 1.03x faster                                                                                                   |
| k_core                     | 2.23 sec                                                                                                           | 2.17 sec: 1.03x faster                                                                                                 |
| async_tree_cpu_io_mixed_tg | 680 ms                                                                                                             | 664 ms: 1.02x faster                                                                                                   |
| genshi_text                | 30.3 ms                                                                                                            | 29.6 ms: 1.02x faster                                                                                                  |
| pickle_list                | 7.38 us                                                                                                            | 7.22 us: 1.02x faster                                                                                                  |
| sqlglot_v2_transpile       | 2.16 ms                                                                                                            | 2.11 ms: 1.02x faster                                                                                                  |
| thrift                     | 1.10 ms                                                                                                            | 1.07 ms: 1.02x faster                                                                                                  |
| meteor_contest             | 145 ms                                                                                                             | 142 ms: 1.02x faster                                                                                                   |
| shortest_path              | 508 ms                                                                                                             | 498 ms: 1.02x faster                                                                                                   |
| async_tree_memoization_tg  | 402 ms                                                                                                             | 395 ms: 1.02x faster                                                                                                   |
| json_loads                 | 40.6 us                                                                                                            | 39.9 us: 1.02x faster                                                                                                  |
| async_tree_io              | 782 ms                                                                                                             | 770 ms: 1.02x faster                                                                                                   |
| coroutines                 | 34.0 ms                                                                                                            | 33.4 ms: 1.02x faster                                                                                                  |
| chameleon                  | 19.0 ms                                                                                                            | 18.7 ms: 1.02x faster                                                                                                  |
| asyncio_tcp_ssl            | 2.07 sec                                                                                                           | 2.04 sec: 1.01x faster                                                                                                 |
| unpickle_list              | 7.69 us                                                                                                            | 7.58 us: 1.01x faster                                                                                                  |
| regex_compile              | 175 ms                                                                                                             | 173 ms: 1.01x faster                                                                                                   |
| xml_etree_iterparse        | 122 ms                                                                                                             | 120 ms: 1.01x faster                                                                                                   |
| coverage                   | 117 ms                                                                                                             | 116 ms: 1.01x faster                                                                                                   |
| crypto_pyaes               | 97.1 ms                                                                                                            | 96.1 ms: 1.01x faster                                                                                                  |
| unpickle                   | 21.5 us                                                                                                            | 21.3 us: 1.01x faster                                                                                                  |
| 2to3                       | 354 ms                                                                                                             | 356 ms: 1.01x slower                                                                                                   |
| create_gc_cycles           | 2.81 ms                                                                                                            | 2.83 ms: 1.01x slower                                                                                                  |
| pidigits                   | 277 ms                                                                                                             | 279 ms: 1.01x slower                                                                                                   |
| tornado_http               | 192 ms                                                                                                             | 194 ms: 1.01x slower                                                                                                   |
| logging_format             | 9.44 us                                                                                                            | 9.56 us: 1.01x slower                                                                                                  |
| python_startup             | 17.8 ms                                                                                                            | 18.0 ms: 1.01x slower                                                                                                  |
| python_startup_no_site     | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| xdsl_constant_fold         | 65.0 ms                                                                                                            | 66.1 ms: 1.02x slower                                                                                                  |
| sqlalchemy_declarative     | 185 ms                                                                                                             | 189 ms: 1.02x slower                                                                                                   |
| telco                      | 226 ms                                                                                                             | 231 ms: 1.02x slower                                                                                                   |
| generators                 | 39.8 ms                                                                                                            | 40.7 ms: 1.02x slower                                                                                                  |
| hexiom                     | 8.19 ms                                                                                                            | 8.42 ms: 1.03x slower                                                                                                  |
| sphinx                     | 1.37 sec                                                                                                           | 1.41 sec: 1.03x slower                                                                                                 |
| logging_simple             | 8.34 us                                                                                                            | 8.60 us: 1.03x slower                                                                                                  |
| pycparser                  | 1.54 sec                                                                                                           | 1.59 sec: 1.03x slower                                                                                                 |
| regex_dna                  | 251 ms                                                                                                             | 260 ms: 1.03x slower                                                                                                   |
| html5lib                   | 85.3 ms                                                                                                            | 88.2 ms: 1.03x slower                                                                                                  |
| async_generators           | 482 ms                                                                                                             | 501 ms: 1.04x slower                                                                                                   |
| many_optionals             | 1.37 ms                                                                                                            | 1.42 ms: 1.04x slower                                                                                                  |
| sympy_expand               | 698 ms                                                                                                             | 729 ms: 1.04x slower                                                                                                   |
| raytrace                   | 360 ms                                                                                                             | 376 ms: 1.04x slower                                                                                                   |
| dulwich_log                | 97.0 ms                                                                                                            | 101 ms: 1.04x slower                                                                                                   |
| genshi_xml                 | 70.5 ms                                                                                                            | 74.0 ms: 1.05x slower                                                                                                  |
| docutils                   | 3.65 sec                                                                                                           | 3.83 sec: 1.05x slower                                                                                                 |
| sympy_integrate            | 27.4 ms                                                                                                            | 28.9 ms: 1.05x slower                                                                                                  |
| sqlglot_v2_optimize        | 72.1 ms                                                                                                            | 76.7 ms: 1.06x slower                                                                                                  |
| sqlglot_v2_normalize       | 143 ms                                                                                                             | 154 ms: 1.07x slower                                                                                                   |
| pylint                     | 399 ms                                                                                                             | 431 ms: 1.08x slower                                                                                                   |
| unpack_sequence            | 59.9 ns                                                                                                            | 64.7 ns: 1.08x slower                                                                                                  |
| regex_v8                   | 30.7 ms                                                                                                            | 33.3 ms: 1.08x slower                                                                                                  |
| sympy_sum                  | 223 ms                                                                                                             | 245 ms: 1.10x slower                                                                                                   |
| sympy_str                  | 395 ms                                                                                                             | 442 ms: 1.12x slower                                                                                                   |
| mdp                        | 1.65 sec                                                                                                           | 1.92 sec: 1.16x slower                                                                                                 |
| Geometric mean             | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (13): bench_mp_pool, async_tree_io_tg, django_template, comprehensions, asyncio_tcp, bench_thread_pool, typing_runtime_protocols, asyncio_websockets, xml_etree_parse, pathlib, nqueens, subparsers, sqlalchemy_imperative

- Geometric mean (including insignificant results): 1.046x faster

# HPT report

- Reliability score: 98.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x