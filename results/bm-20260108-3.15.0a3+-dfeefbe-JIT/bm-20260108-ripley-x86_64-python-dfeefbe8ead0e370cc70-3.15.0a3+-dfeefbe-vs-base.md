# Results vs. base

- fork: python
- ref: dfeefbe8ead0e370cc70
- machine: linux-x86_64
- commit hash: dfeefbe
- commit date: 2026-01-08
- overall geometric mean: 1.030x faster
- HPT reliability: 95.33%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 358 ms                                                                                                             | 356 ms: 1.01x faster                                                                                                   |
| docutils       | 3.60 sec                                                                                                           | 3.85 sec: 1.07x slower                                                                                                 |
| html5lib       | 85.1 ms                                                                                                            | 92.5 ms: 1.09x slower                                                                                                  |
| sphinx         | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| tornado_http   | 193 ms                                                                                                             | 196 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.03x slower                                                                                                           |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| coroutines                 | 35.1 ms                                                                                                            | 34.2 ms: 1.03x faster                                                                                                  |
| async_tree_none            | 339 ms                                                                                                             | 331 ms: 1.02x faster                                                                                                   |
| async_tree_cpu_io_mixed_tg | 694 ms                                                                                                             | 684 ms: 1.01x faster                                                                                                   |
| async_tree_memoization_tg  | 405 ms                                                                                                             | 400 ms: 1.01x faster                                                                                                   |
| async_tree_cpu_io_mixed    | 683 ms                                                                                                             | 675 ms: 1.01x faster                                                                                                   |
| asyncio_websockets         | 778 ms                                                                                                             | 779 ms: 1.00x slower                                                                                                   |
| asyncio_tcp_ssl            | 2.04 sec                                                                                                           | 2.04 sec: 1.00x slower                                                                                                 |
| asyncio_tcp                | 552 ms                                                                                                             | 564 ms: 1.02x slower                                                                                                   |
| async_generators           | 485 ms                                                                                                             | 509 ms: 1.05x slower                                                                                                   |
| Geometric mean             | (ref)                                                                                                              | 1.00x faster                                                                                                           |

Benchmark hidden because not significant (4): async_tree_none_tg, async_tree_io, async_tree_memoization, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 134 ms                                                                                                             | 106 ms: 1.26x faster                                                                                                   |
| float          | 103 ms                                                                                                             | 82.0 ms: 1.25x faster                                                                                                  |
| pidigits       | 275 ms                                                                                                             | 276 ms: 1.00x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.16x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 32.6 ms                                                                                                            | 30.6 ms: 1.06x faster                                                                                                  |
| regex_compile  | 179 ms                                                                                                             | 175 ms: 1.03x faster                                                                                                   |
| regex_effbot   | 3.95 ms                                                                                                            | 4.00 ms: 1.01x slower                                                                                                  |
| regex_dna      | 244 ms                                                                                                             | 254 ms: 1.04x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 305 us                                                                                                             | 252 us: 1.21x faster                                                                                                   |
| tomli_loads          | 2.70 sec                                                                                                           | 2.42 sec: 1.11x faster                                                                                                 |
| pickle_pure_python   | 441 us                                                                                                             | 400 us: 1.10x faster                                                                                                   |
| xml_etree_generate   | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| xml_etree_process    | 83.6 ms                                                                                                            | 77.7 ms: 1.08x faster                                                                                                  |
| json_dumps           | 14.0 ms                                                                                                            | 13.3 ms: 1.06x faster                                                                                                  |
| xml_etree_iterparse  | 122 ms                                                                                                             | 120 ms: 1.02x faster                                                                                                   |
| unpickle_list        | 7.59 us                                                                                                            | 7.47 us: 1.02x faster                                                                                                  |
| json_loads           | 40.2 us                                                                                                            | 39.9 us: 1.01x faster                                                                                                  |
| unpickle             | 20.8 us                                                                                                            | 21.0 us: 1.01x slower                                                                                                  |
| pickle               | 17.9 us                                                                                                            | 18.2 us: 1.02x slower                                                                                                  |
| pickle_dict          | 45.4 us                                                                                                            | 46.2 us: 1.02x slower                                                                                                  |
| pickle_list          | 7.25 us                                                                                                            | 7.49 us: 1.03x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.7 ms                                                                                                            | 18.5 ms: 1.05x slower                                                                                                  |
| python_startup_no_site | 10.4 ms                                                                                                            | 11.1 ms: 1.07x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.06x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.0 ms                                                                                                            | 15.2 ms: 1.12x faster                                                                                                  |
| django_template | 50.8 ms                                                                                                            | 51.3 ms: 1.01x slower                                                                                                  |
| genshi_xml      | 72.4 ms                                                                                                            | 79.5 ms: 1.10x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.00x faster                                                                                                           |

Benchmark hidden because not significant (1): genshi_text

All benchmarks:
===============

| Benchmark                  | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                   | 60.8 ms                                                                                                            | 25.7 ms: 2.36x faster                                                                                                  |
| richards_super             | 68.9 ms                                                                                                            | 31.0 ms: 2.22x faster                                                                                                  |
| nbody                      | 134 ms                                                                                                             | 106 ms: 1.26x faster                                                                                                   |
| logging_silent             | 150 ns                                                                                                             | 119 ns: 1.26x faster                                                                                                   |
| float                      | 103 ms                                                                                                             | 82.0 ms: 1.25x faster                                                                                                  |
| unpickle_pure_python       | 305 us                                                                                                             | 252 us: 1.21x faster                                                                                                   |
| deltablue                  | 4.71 ms                                                                                                            | 3.88 ms: 1.21x faster                                                                                                  |
| scimark_monte_carlo        | 89.0 ms                                                                                                            | 73.7 ms: 1.21x faster                                                                                                  |
| bench_mp_pool              | 268 ms                                                                                                             | 224 ms: 1.20x faster                                                                                                   |
| scimark_fft                | 445 ms                                                                                                             | 374 ms: 1.19x faster                                                                                                   |
| pyflate                    | 595 ms                                                                                                             | 509 ms: 1.17x faster                                                                                                   |
| spectral_norm              | 141 ms                                                                                                             | 122 ms: 1.16x faster                                                                                                   |
| go                         | 152 ms                                                                                                             | 132 ms: 1.15x faster                                                                                                   |
| fannkuch                   | 572 ms                                                                                                             | 501 ms: 1.14x faster                                                                                                   |
| mako                       | 17.0 ms                                                                                                            | 15.2 ms: 1.12x faster                                                                                                  |
| tomli_loads                | 2.70 sec                                                                                                           | 2.42 sec: 1.11x faster                                                                                                 |
| scimark_lu                 | 156 ms                                                                                                             | 141 ms: 1.11x faster                                                                                                   |
| pickle_pure_python         | 441 us                                                                                                             | 400 us: 1.10x faster                                                                                                   |
| deepcopy_memo              | 38.2 us                                                                                                            | 34.9 us: 1.09x faster                                                                                                  |
| scimark_sparse_mat_mult    | 6.63 ms                                                                                                            | 6.08 ms: 1.09x faster                                                                                                  |
| pprint_safe_repr           | 1.01 sec                                                                                                           | 936 ms: 1.08x faster                                                                                                   |
| xml_etree_generate         | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| xml_etree_process          | 83.6 ms                                                                                                            | 77.7 ms: 1.08x faster                                                                                                  |
| pprint_pformat             | 2.06 sec                                                                                                           | 1.92 sec: 1.07x faster                                                                                                 |
| regex_v8                   | 32.6 ms                                                                                                            | 30.6 ms: 1.06x faster                                                                                                  |
| gc_traversal               | 6.73 ms                                                                                                            | 6.34 ms: 1.06x faster                                                                                                  |
| scimark_sor                | 153 ms                                                                                                             | 145 ms: 1.06x faster                                                                                                   |
| json_dumps                 | 14.0 ms                                                                                                            | 13.3 ms: 1.06x faster                                                                                                  |
| bpe_tokeniser              | 6.10 sec                                                                                                           | 5.80 sec: 1.05x faster                                                                                                 |
| chaos                      | 80.0 ms                                                                                                            | 76.1 ms: 1.05x faster                                                                                                  |
| crypto_pyaes               | 102 ms                                                                                                             | 98.0 ms: 1.04x faster                                                                                                  |
| json                       | 7.35 ms                                                                                                            | 7.05 ms: 1.04x faster                                                                                                  |
| deepcopy                   | 336 us                                                                                                             | 322 us: 1.04x faster                                                                                                   |
| deepcopy_reduce            | 3.66 us                                                                                                            | 3.52 us: 1.04x faster                                                                                                  |
| meteor_contest             | 147 ms                                                                                                             | 141 ms: 1.04x faster                                                                                                   |
| logging_simple             | 8.64 us                                                                                                            | 8.35 us: 1.03x faster                                                                                                  |
| sqlglot_v2_parse           | 1.73 ms                                                                                                            | 1.67 ms: 1.03x faster                                                                                                  |
| coroutines                 | 35.1 ms                                                                                                            | 34.2 ms: 1.03x faster                                                                                                  |
| regex_compile              | 179 ms                                                                                                             | 175 ms: 1.03x faster                                                                                                   |
| connected_components       | 456 ms                                                                                                             | 445 ms: 1.03x faster                                                                                                   |
| async_tree_none            | 339 ms                                                                                                             | 331 ms: 1.02x faster                                                                                                   |
| sqlite_synth               | 3.20 us                                                                                                            | 3.14 us: 1.02x faster                                                                                                  |
| subparsers                 | 13.2 ms                                                                                                            | 13.0 ms: 1.02x faster                                                                                                  |
| typing_runtime_protocols   | 230 us                                                                                                             | 226 us: 1.02x faster                                                                                                   |
| xml_etree_iterparse        | 122 ms                                                                                                             | 120 ms: 1.02x faster                                                                                                   |
| unpickle_list              | 7.59 us                                                                                                            | 7.47 us: 1.02x faster                                                                                                  |
| shortest_path              | 509 ms                                                                                                             | 501 ms: 1.02x faster                                                                                                   |
| async_tree_cpu_io_mixed_tg | 694 ms                                                                                                             | 684 ms: 1.01x faster                                                                                                   |
| async_tree_memoization_tg  | 405 ms                                                                                                             | 400 ms: 1.01x faster                                                                                                   |
| async_tree_cpu_io_mixed    | 683 ms                                                                                                             | 675 ms: 1.01x faster                                                                                                   |
| comprehensions             | 23.3 us                                                                                                            | 23.0 us: 1.01x faster                                                                                                  |
| sqlglot_v2_transpile       | 2.18 ms                                                                                                            | 2.16 ms: 1.01x faster                                                                                                  |
| json_loads                 | 40.2 us                                                                                                            | 39.9 us: 1.01x faster                                                                                                  |
| k_core                     | 2.23 sec                                                                                                           | 2.21 sec: 1.01x faster                                                                                                 |
| 2to3                       | 358 ms                                                                                                             | 356 ms: 1.01x faster                                                                                                   |
| asyncio_websockets         | 778 ms                                                                                                             | 779 ms: 1.00x slower                                                                                                   |
| asyncio_tcp_ssl            | 2.04 sec                                                                                                           | 2.04 sec: 1.00x slower                                                                                                 |
| pidigits                   | 275 ms                                                                                                             | 276 ms: 1.00x slower                                                                                                   |
| unpickle                   | 20.8 us                                                                                                            | 21.0 us: 1.01x slower                                                                                                  |
| django_template            | 50.8 ms                                                                                                            | 51.3 ms: 1.01x slower                                                                                                  |
| sqlalchemy_imperative      | 29.3 ms                                                                                                            | 29.6 ms: 1.01x slower                                                                                                  |
| tornado_http               | 193 ms                                                                                                             | 196 ms: 1.01x slower                                                                                                   |
| regex_effbot               | 3.95 ms                                                                                                            | 4.00 ms: 1.01x slower                                                                                                  |
| pickle                     | 17.9 us                                                                                                            | 18.2 us: 1.02x slower                                                                                                  |
| pickle_dict                | 45.4 us                                                                                                            | 46.2 us: 1.02x slower                                                                                                  |
| create_gc_cycles           | 2.83 ms                                                                                                            | 2.89 ms: 1.02x slower                                                                                                  |
| nqueens                    | 113 ms                                                                                                             | 115 ms: 1.02x slower                                                                                                   |
| asyncio_tcp                | 552 ms                                                                                                             | 564 ms: 1.02x slower                                                                                                   |
| sqlalchemy_declarative     | 186 ms                                                                                                             | 190 ms: 1.02x slower                                                                                                   |
| hexiom                     | 8.33 ms                                                                                                            | 8.60 ms: 1.03x slower                                                                                                  |
| pickle_list                | 7.25 us                                                                                                            | 7.49 us: 1.03x slower                                                                                                  |
| xdsl_constant_fold         | 65.6 ms                                                                                                            | 67.8 ms: 1.03x slower                                                                                                  |
| thrift                     | 1.07 ms                                                                                                            | 1.11 ms: 1.03x slower                                                                                                  |
| sphinx                     | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| raytrace                   | 364 ms                                                                                                             | 377 ms: 1.04x slower                                                                                                   |
| many_optionals             | 1.38 ms                                                                                                            | 1.44 ms: 1.04x slower                                                                                                  |
| regex_dna                  | 244 ms                                                                                                             | 254 ms: 1.04x slower                                                                                                   |
| telco                      | 228 ms                                                                                                             | 238 ms: 1.04x slower                                                                                                   |
| generators                 | 41.1 ms                                                                                                            | 43.0 ms: 1.05x slower                                                                                                  |
| python_startup             | 17.7 ms                                                                                                            | 18.5 ms: 1.05x slower                                                                                                  |
| sympy_integrate            | 27.6 ms                                                                                                            | 29.0 ms: 1.05x slower                                                                                                  |
| async_generators           | 485 ms                                                                                                             | 509 ms: 1.05x slower                                                                                                   |
| sqlglot_v2_optimize        | 72.8 ms                                                                                                            | 76.7 ms: 1.05x slower                                                                                                  |
| sqlglot_v2_normalize       | 145 ms                                                                                                             | 153 ms: 1.06x slower                                                                                                   |
| dulwich_log                | 97.4 ms                                                                                                            | 104 ms: 1.06x slower                                                                                                   |
| python_startup_no_site     | 10.4 ms                                                                                                            | 11.1 ms: 1.07x slower                                                                                                  |
| docutils                   | 3.60 sec                                                                                                           | 3.85 sec: 1.07x slower                                                                                                 |
| pylint                     | 402 ms                                                                                                             | 437 ms: 1.09x slower                                                                                                   |
| html5lib                   | 85.1 ms                                                                                                            | 92.5 ms: 1.09x slower                                                                                                  |
| genshi_xml                 | 72.4 ms                                                                                                            | 79.5 ms: 1.10x slower                                                                                                  |
| sympy_sum                  | 224 ms                                                                                                             | 247 ms: 1.10x slower                                                                                                   |
| sympy_expand               | 677 ms                                                                                                             | 749 ms: 1.11x slower                                                                                                   |
| sympy_str                  | 397 ms                                                                                                             | 445 ms: 1.12x slower                                                                                                   |
| mdp                        | 1.67 sec                                                                                                           | 1.97 sec: 1.18x slower                                                                                                 |
| unpack_sequence            | 59.4 ns                                                                                                            | 98.9 ns: 1.66x slower                                                                                                  |
| bench_thread_pool          | 1.73 ms                                                                                                            | 3.91 ms: 2.26x slower                                                                                                  |
| Geometric mean             | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (11): async_tree_none_tg, genshi_text, chameleon, xml_etree_parse, async_tree_io, async_tree_memoization, coverage, pycparser, pathlib, logging_format, async_tree_io_tg

- Geometric mean (including insignificant results): 1.030x faster

# HPT report

- Reliability score: 95.33% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x