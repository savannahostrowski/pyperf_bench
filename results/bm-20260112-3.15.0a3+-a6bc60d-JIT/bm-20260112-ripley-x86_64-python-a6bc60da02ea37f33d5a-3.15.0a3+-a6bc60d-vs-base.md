# Results vs. base

- fork: python
- ref: a6bc60da02ea37f33d5a
- machine: linux-x86_64
- commit hash: a6bc60d
- commit date: 2026-01-12
- overall geometric mean: 1.041x faster
- HPT reliability: 97.34%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 356 ms                                                                                                             | 355 ms: 1.00x faster                                                                                                   |
| docutils       | 3.64 sec                                                                                                           | 3.80 sec: 1.04x slower                                                                                                 |
| html5lib       | 85.0 ms                                                                                                            | 90.7 ms: 1.07x slower                                                                                                  |
| sphinx         | 1.37 sec                                                                                                           | 1.41 sec: 1.03x slower                                                                                                 |
| tornado_http   | 191 ms                                                                                                             | 192 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg         | 344 ms                                                                                                             | 327 ms: 1.05x faster                                                                                                   |
| async_tree_memoization     | 417 ms                                                                                                             | 404 ms: 1.03x faster                                                                                                   |
| async_tree_none            | 334 ms                                                                                                             | 326 ms: 1.03x faster                                                                                                   |
| async_tree_io              | 760 ms                                                                                                             | 743 ms: 1.02x faster                                                                                                   |
| asyncio_tcp_ssl            | 2.06 sec                                                                                                           | 2.03 sec: 1.02x faster                                                                                                 |
| coroutines                 | 34.2 ms                                                                                                            | 33.7 ms: 1.01x faster                                                                                                  |
| async_tree_cpu_io_mixed_tg | 695 ms                                                                                                             | 707 ms: 1.02x slower                                                                                                   |
| async_tree_io_tg           | 768 ms                                                                                                             | 783 ms: 1.02x slower                                                                                                   |
| async_tree_cpu_io_mixed    | 682 ms                                                                                                             | 709 ms: 1.04x slower                                                                                                   |
| async_generators           | 487 ms                                                                                                             | 509 ms: 1.04x slower                                                                                                   |
| Geometric mean             | (ref)                                                                                                              | 1.00x faster                                                                                                           |

Benchmark hidden because not significant (3): async_tree_memoization_tg, asyncio_websockets, asyncio_tcp

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| float          | 102 ms                                                                                                             | 81.6 ms: 1.25x faster                                                                                                  |
| nbody          | 127 ms                                                                                                             | 106 ms: 1.19x faster                                                                                                   |
| pidigits       | 299 ms                                                                                                             | 304 ms: 1.02x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.14x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.18 ms                                                                                                            | 3.73 ms: 1.12x faster                                                                                                  |
| regex_v8       | 32.0 ms                                                                                                            | 30.6 ms: 1.05x faster                                                                                                  |
| regex_dna      | 254 ms                                                                                                             | 246 ms: 1.04x faster                                                                                                   |
| regex_compile  | 176 ms                                                                                                             | 175 ms: 1.01x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.05x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 301 us                                                                                                             | 254 us: 1.19x faster                                                                                                   |
| pickle_pure_python   | 437 us                                                                                                             | 391 us: 1.12x faster                                                                                                   |
| tomli_loads          | 2.61 sec                                                                                                           | 2.38 sec: 1.10x faster                                                                                                 |
| xml_etree_process    | 82.7 ms                                                                                                            | 76.0 ms: 1.09x faster                                                                                                  |
| xml_etree_generate   | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| json_dumps           | 13.8 ms                                                                                                            | 12.8 ms: 1.08x faster                                                                                                  |
| unpickle_list        | 7.63 us                                                                                                            | 7.41 us: 1.03x faster                                                                                                  |
| xml_etree_iterparse  | 122 ms                                                                                                             | 119 ms: 1.03x faster                                                                                                   |
| unpickle             | 21.0 us                                                                                                            | 20.7 us: 1.01x faster                                                                                                  |
| pickle_dict          | 46.7 us                                                                                                            | 48.2 us: 1.03x slower                                                                                                  |
| pickle_list          | 7.29 us                                                                                                            | 7.62 us: 1.04x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (3): xml_etree_parse, pickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.8 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.1 ms                                                                                                            | 15.0 ms: 1.14x faster                                                                                                  |
| genshi_text     | 30.9 ms                                                                                                            | 30.1 ms: 1.03x faster                                                                                                  |
| django_template | 49.7 ms                                                                                                            | 50.5 ms: 1.02x slower                                                                                                  |
| genshi_xml      | 73.5 ms                                                                                                            | 76.1 ms: 1.04x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.03x faster                                                                                                           |

All benchmarks:
===============

| Benchmark                  | results/bm-20260112-3.15.0a3+-a6bc60d/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json | results/bm-20260112-3.15.0a3+-a6bc60d-JIT/bm-20260112-ripley-x86_64-python-a6bc60da02ea37f33d5a-3.15.0a3+-a6bc60d.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                   | 61.2 ms                                                                                                            | 26.1 ms: 2.34x faster                                                                                                  |
| richards_super             | 69.3 ms                                                                                                            | 31.3 ms: 2.22x faster                                                                                                  |
| float                      | 102 ms                                                                                                             | 81.6 ms: 1.25x faster                                                                                                  |
| logging_silent             | 141 ns                                                                                                             | 116 ns: 1.22x faster                                                                                                   |
| scimark_monte_carlo        | 90.0 ms                                                                                                            | 74.1 ms: 1.22x faster                                                                                                  |
| deltablue                  | 4.70 ms                                                                                                            | 3.88 ms: 1.21x faster                                                                                                  |
| nbody                      | 127 ms                                                                                                             | 106 ms: 1.19x faster                                                                                                   |
| unpickle_pure_python       | 301 us                                                                                                             | 254 us: 1.19x faster                                                                                                   |
| bench_mp_pool              | 281 ms                                                                                                             | 244 ms: 1.15x faster                                                                                                   |
| go                         | 151 ms                                                                                                             | 131 ms: 1.15x faster                                                                                                   |
| scimark_fft                | 429 ms                                                                                                             | 375 ms: 1.14x faster                                                                                                   |
| mako                       | 17.1 ms                                                                                                            | 15.0 ms: 1.14x faster                                                                                                  |
| pyflate                    | 585 ms                                                                                                             | 517 ms: 1.13x faster                                                                                                   |
| pprint_safe_repr           | 1.01 sec                                                                                                           | 900 ms: 1.13x faster                                                                                                   |
| regex_effbot               | 4.18 ms                                                                                                            | 3.73 ms: 1.12x faster                                                                                                  |
| pprint_pformat             | 2.06 sec                                                                                                           | 1.84 sec: 1.12x faster                                                                                                 |
| pickle_pure_python         | 437 us                                                                                                             | 391 us: 1.12x faster                                                                                                   |
| tomli_loads                | 2.61 sec                                                                                                           | 2.38 sec: 1.10x faster                                                                                                 |
| scimark_lu                 | 154 ms                                                                                                             | 140 ms: 1.10x faster                                                                                                   |
| fannkuch                   | 550 ms                                                                                                             | 502 ms: 1.10x faster                                                                                                   |
| xml_etree_process          | 82.7 ms                                                                                                            | 76.0 ms: 1.09x faster                                                                                                  |
| xml_etree_generate         | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| json_dumps                 | 13.8 ms                                                                                                            | 12.8 ms: 1.08x faster                                                                                                  |
| spectral_norm              | 132 ms                                                                                                             | 124 ms: 1.07x faster                                                                                                   |
| deepcopy_memo              | 37.6 us                                                                                                            | 35.3 us: 1.07x faster                                                                                                  |
| deepcopy_reduce            | 3.70 us                                                                                                            | 3.48 us: 1.06x faster                                                                                                  |
| bpe_tokeniser              | 6.08 sec                                                                                                           | 5.76 sec: 1.06x faster                                                                                                 |
| async_tree_none_tg         | 344 ms                                                                                                             | 327 ms: 1.05x faster                                                                                                   |
| chaos                      | 79.5 ms                                                                                                            | 75.9 ms: 1.05x faster                                                                                                  |
| deepcopy                   | 333 us                                                                                                             | 318 us: 1.05x faster                                                                                                   |
| regex_v8                   | 32.0 ms                                                                                                            | 30.6 ms: 1.05x faster                                                                                                  |
| json                       | 7.31 ms                                                                                                            | 7.00 ms: 1.04x faster                                                                                                  |
| sqlite_synth               | 3.28 us                                                                                                            | 3.15 us: 1.04x faster                                                                                                  |
| crypto_pyaes               | 101 ms                                                                                                             | 96.9 ms: 1.04x faster                                                                                                  |
| connected_components       | 455 ms                                                                                                             | 438 ms: 1.04x faster                                                                                                   |
| regex_dna                  | 254 ms                                                                                                             | 246 ms: 1.04x faster                                                                                                   |
| async_tree_memoization     | 417 ms                                                                                                             | 404 ms: 1.03x faster                                                                                                   |
| shortest_path              | 512 ms                                                                                                             | 496 ms: 1.03x faster                                                                                                   |
| unpickle_list              | 7.63 us                                                                                                            | 7.41 us: 1.03x faster                                                                                                  |
| scimark_sor                | 151 ms                                                                                                             | 146 ms: 1.03x faster                                                                                                   |
| xml_etree_iterparse        | 122 ms                                                                                                             | 119 ms: 1.03x faster                                                                                                   |
| k_core                     | 2.23 sec                                                                                                           | 2.17 sec: 1.03x faster                                                                                                 |
| async_tree_none            | 334 ms                                                                                                             | 326 ms: 1.03x faster                                                                                                   |
| gc_traversal               | 6.45 ms                                                                                                            | 6.29 ms: 1.03x faster                                                                                                  |
| genshi_text                | 30.9 ms                                                                                                            | 30.1 ms: 1.03x faster                                                                                                  |
| async_tree_io              | 760 ms                                                                                                             | 743 ms: 1.02x faster                                                                                                   |
| sqlglot_v2_parse           | 1.71 ms                                                                                                            | 1.68 ms: 1.02x faster                                                                                                  |
| logging_format             | 9.53 us                                                                                                            | 9.38 us: 1.02x faster                                                                                                  |
| logging_simple             | 8.44 us                                                                                                            | 8.31 us: 1.02x faster                                                                                                  |
| asyncio_tcp_ssl            | 2.06 sec                                                                                                           | 2.03 sec: 1.02x faster                                                                                                 |
| coroutines                 | 34.2 ms                                                                                                            | 33.7 ms: 1.01x faster                                                                                                  |
| unpickle                   | 21.0 us                                                                                                            | 20.7 us: 1.01x faster                                                                                                  |
| meteor_contest             | 144 ms                                                                                                             | 142 ms: 1.01x faster                                                                                                   |
| pathlib                    | 25.5 ms                                                                                                            | 25.2 ms: 1.01x faster                                                                                                  |
| comprehensions             | 23.1 us                                                                                                            | 22.8 us: 1.01x faster                                                                                                  |
| scimark_sparse_mat_mult    | 6.15 ms                                                                                                            | 6.07 ms: 1.01x faster                                                                                                  |
| regex_compile              | 176 ms                                                                                                             | 175 ms: 1.01x faster                                                                                                   |
| sqlglot_v2_transpile       | 2.18 ms                                                                                                            | 2.16 ms: 1.01x faster                                                                                                  |
| create_gc_cycles           | 2.89 ms                                                                                                            | 2.86 ms: 1.01x faster                                                                                                  |
| 2to3                       | 356 ms                                                                                                             | 355 ms: 1.00x faster                                                                                                   |
| coverage                   | 117 ms                                                                                                             | 116 ms: 1.00x faster                                                                                                   |
| bench_thread_pool          | 1.74 ms                                                                                                            | 1.75 ms: 1.01x slower                                                                                                  |
| tornado_http               | 191 ms                                                                                                             | 192 ms: 1.01x slower                                                                                                   |
| python_startup             | 17.8 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| sqlalchemy_declarative     | 185 ms                                                                                                             | 187 ms: 1.01x slower                                                                                                   |
| python_startup_no_site     | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| nqueens                    | 112 ms                                                                                                             | 113 ms: 1.01x slower                                                                                                   |
| sqlalchemy_imperative      | 28.6 ms                                                                                                            | 29.0 ms: 1.01x slower                                                                                                  |
| typing_runtime_protocols   | 224 us                                                                                                             | 227 us: 1.02x slower                                                                                                   |
| pidigits                   | 299 ms                                                                                                             | 304 ms: 1.02x slower                                                                                                   |
| django_template            | 49.7 ms                                                                                                            | 50.5 ms: 1.02x slower                                                                                                  |
| async_tree_cpu_io_mixed_tg | 695 ms                                                                                                             | 707 ms: 1.02x slower                                                                                                   |
| async_tree_io_tg           | 768 ms                                                                                                             | 783 ms: 1.02x slower                                                                                                   |
| xdsl_constant_fold         | 65.5 ms                                                                                                            | 67.2 ms: 1.03x slower                                                                                                  |
| telco                      | 227 ms                                                                                                             | 234 ms: 1.03x slower                                                                                                   |
| pickle_dict                | 46.7 us                                                                                                            | 48.2 us: 1.03x slower                                                                                                  |
| sphinx                     | 1.37 sec                                                                                                           | 1.41 sec: 1.03x slower                                                                                                 |
| sympy_integrate            | 27.5 ms                                                                                                            | 28.4 ms: 1.03x slower                                                                                                  |
| genshi_xml                 | 73.5 ms                                                                                                            | 76.1 ms: 1.04x slower                                                                                                  |
| generators                 | 39.3 ms                                                                                                            | 40.8 ms: 1.04x slower                                                                                                  |
| raytrace                   | 359 ms                                                                                                             | 373 ms: 1.04x slower                                                                                                   |
| async_tree_cpu_io_mixed    | 682 ms                                                                                                             | 709 ms: 1.04x slower                                                                                                   |
| async_generators           | 487 ms                                                                                                             | 509 ms: 1.04x slower                                                                                                   |
| docutils                   | 3.64 sec                                                                                                           | 3.80 sec: 1.04x slower                                                                                                 |
| pickle_list                | 7.29 us                                                                                                            | 7.62 us: 1.04x slower                                                                                                  |
| many_optionals             | 1.37 ms                                                                                                            | 1.43 ms: 1.04x slower                                                                                                  |
| sqlglot_v2_optimize        | 72.7 ms                                                                                                            | 76.3 ms: 1.05x slower                                                                                                  |
| sqlglot_v2_normalize       | 146 ms                                                                                                             | 153 ms: 1.05x slower                                                                                                   |
| dulwich_log                | 97.2 ms                                                                                                            | 102 ms: 1.05x slower                                                                                                   |
| html5lib                   | 85.0 ms                                                                                                            | 90.7 ms: 1.07x slower                                                                                                  |
| pylint                     | 405 ms                                                                                                             | 433 ms: 1.07x slower                                                                                                   |
| sympy_expand               | 686 ms                                                                                                             | 735 ms: 1.07x slower                                                                                                   |
| hexiom                     | 7.99 ms                                                                                                            | 8.64 ms: 1.08x slower                                                                                                  |
| sympy_sum                  | 221 ms                                                                                                             | 242 ms: 1.09x slower                                                                                                   |
| sympy_str                  | 394 ms                                                                                                             | 442 ms: 1.12x slower                                                                                                   |
| unpack_sequence            | 58.6 ns                                                                                                            | 67.2 ns: 1.15x slower                                                                                                  |
| mdp                        | 1.68 sec                                                                                                           | 1.96 sec: 1.17x slower                                                                                                 |
| Geometric mean             | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (10): xml_etree_parse, subparsers, thrift, chameleon, async_tree_memoization_tg, asyncio_websockets, asyncio_tcp, pickle, json_loads, pycparser

- Geometric mean (including insignificant results): 1.041x faster

# HPT report

- Reliability score: 97.34% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x