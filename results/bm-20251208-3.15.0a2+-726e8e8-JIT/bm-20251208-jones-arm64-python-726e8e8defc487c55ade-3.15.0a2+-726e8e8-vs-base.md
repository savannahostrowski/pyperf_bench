# Results vs. base

- fork: python
- ref: 726e8e8defc487c55ade
- machine: darwin-arm64
- commit hash: 726e8e8
- commit date: 2025-12-08
- overall geometric mean: 1.018x faster
- HPT reliability: 61.01%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 131 ms                                                                                                           | 133 ms: 1.02x slower                                                                                                 |
| docutils       | 1.16 sec                                                                                                         | 1.19 sec: 1.03x slower                                                                                               |
| html5lib       | 25.1 ms                                                                                                          | 25.6 ms: 1.02x slower                                                                                                |
| sphinx         | 461 ms                                                                                                           | 468 ms: 1.01x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.02x slower                                                                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg         | 121 ms                                                                                                           | 114 ms: 1.06x faster                                                                                                 |
| async_tree_none            | 119 ms                                                                                                           | 112 ms: 1.06x faster                                                                                                 |
| async_tree_io              | 270 ms                                                                                                           | 263 ms: 1.03x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 332 ms                                                                                                           | 326 ms: 1.02x faster                                                                                                 |
| async_tree_memoization     | 154 ms                                                                                                           | 152 ms: 1.01x faster                                                                                                 |
| asyncio_websockets         | 205 ms                                                                                                           | 205 ms: 1.00x slower                                                                                                 |
| async_tree_cpu_io_mixed_tg | 326 ms                                                                                                           | 330 ms: 1.01x slower                                                                                                 |
| async_tree_io_tg           | 269 ms                                                                                                           | 273 ms: 1.02x slower                                                                                                 |
| asyncio_tcp_ssl            | 649 ms                                                                                                           | 663 ms: 1.02x slower                                                                                                 |
| async_generators           | 197 ms                                                                                                           | 206 ms: 1.05x slower                                                                                                 |
| coroutines                 | 12.0 ms                                                                                                          | 13.6 ms: 1.14x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.01x slower                                                                                                         |

Benchmark hidden because not significant (2): async_tree_memoization_tg, asyncio_tcp

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| nbody          | 59.7 ms                                                                                                          | 55.6 ms: 1.07x faster                                                                                                |
| float          | 33.7 ms                                                                                                          | 31.5 ms: 1.07x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.05x faster                                                                                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 54.3 ms                                                                                                          | 50.9 ms: 1.07x faster                                                                                                |
| regex_v8       | 12.8 ms                                                                                                          | 13.0 ms: 1.01x slower                                                                                                |
| regex_dna      | 114 ms                                                                                                           | 117 ms: 1.02x slower                                                                                                 |
| regex_effbot   | 1.83 ms                                                                                                          | 1.90 ms: 1.04x slower                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.00x slower                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 118 us                                                                                                           | 103 us: 1.14x faster                                                                                                 |
| pickle_pure_python   | 165 us                                                                                                           | 146 us: 1.12x faster                                                                                                 |
| xml_etree_process    | 29.0 ms                                                                                                          | 25.8 ms: 1.12x faster                                                                                                |
| xml_etree_generate   | 41.2 ms                                                                                                          | 37.1 ms: 1.11x faster                                                                                                |
| json_dumps           | 4.53 ms                                                                                                          | 4.36 ms: 1.04x faster                                                                                                |
| xml_etree_iterparse  | 45.1 ms                                                                                                          | 43.6 ms: 1.03x faster                                                                                                |
| xml_etree_parse      | 73.3 ms                                                                                                          | 72.0 ms: 1.02x faster                                                                                                |
| pickle_dict          | 14.1 us                                                                                                          | 14.3 us: 1.01x slower                                                                                                |
| unpickle             | 7.14 us                                                                                                          | 7.33 us: 1.03x slower                                                                                                |
| unpickle_list        | 2.26 us                                                                                                          | 2.33 us: 1.03x slower                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.04x faster                                                                                                         |

Benchmark hidden because not significant (4): json_loads, pickle_list, tomli_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 10.2 ms                                                                                                          | 10.4 ms: 1.02x slower                                                                                                |
| python_startup_no_site | 7.19 ms                                                                                                          | 7.43 ms: 1.03x slower                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.03x slower                                                                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 5.93 ms                                                                                                          | 5.17 ms: 1.15x faster                                                                                                |
| genshi_text     | 11.9 ms                                                                                                          | 11.5 ms: 1.04x faster                                                                                                |
| django_template | 16.0 ms                                                                                                          | 15.6 ms: 1.03x faster                                                                                                |
| genshi_xml      | 25.5 ms                                                                                                          | 25.6 ms: 1.01x slower                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.05x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20251208-3.15.0a2+-726e8e8/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json | results/bm-20251208-3.15.0a2+-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2+-726e8e8.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                   | 24.1 ms                                                                                                          | 15.7 ms: 1.53x faster                                                                                                |
| richards_super             | 27.3 ms                                                                                                          | 18.0 ms: 1.52x faster                                                                                                |
| pprint_safe_repr           | 383 ms                                                                                                           | 319 ms: 1.20x faster                                                                                                 |
| deepcopy_memo              | 15.0 us                                                                                                          | 12.5 us: 1.20x faster                                                                                                |
| pprint_pformat             | 771 ms                                                                                                           | 647 ms: 1.19x faster                                                                                                 |
| mako                       | 5.93 ms                                                                                                          | 5.17 ms: 1.15x faster                                                                                                |
| scimark_monte_carlo        | 34.6 ms                                                                                                          | 30.2 ms: 1.14x faster                                                                                                |
| unpickle_pure_python       | 118 us                                                                                                           | 103 us: 1.14x faster                                                                                                 |
| scimark_sor                | 61.4 ms                                                                                                          | 54.5 ms: 1.13x faster                                                                                                |
| pickle_pure_python         | 165 us                                                                                                           | 146 us: 1.12x faster                                                                                                 |
| xml_etree_process          | 29.0 ms                                                                                                          | 25.8 ms: 1.12x faster                                                                                                |
| xml_etree_generate         | 41.2 ms                                                                                                          | 37.1 ms: 1.11x faster                                                                                                |
| scimark_fft                | 143 ms                                                                                                           | 130 ms: 1.10x faster                                                                                                 |
| fannkuch                   | 216 ms                                                                                                           | 197 ms: 1.10x faster                                                                                                 |
| nbody                      | 59.7 ms                                                                                                          | 55.6 ms: 1.07x faster                                                                                                |
| pyflate                    | 225 ms                                                                                                           | 210 ms: 1.07x faster                                                                                                 |
| deepcopy                   | 123 us                                                                                                           | 115 us: 1.07x faster                                                                                                 |
| float                      | 33.7 ms                                                                                                          | 31.5 ms: 1.07x faster                                                                                                |
| regex_compile              | 54.3 ms                                                                                                          | 50.9 ms: 1.07x faster                                                                                                |
| comprehensions             | 9.10 us                                                                                                          | 8.52 us: 1.07x faster                                                                                                |
| deepcopy_reduce            | 1.32 us                                                                                                          | 1.23 us: 1.07x faster                                                                                                |
| async_tree_none_tg         | 121 ms                                                                                                           | 114 ms: 1.06x faster                                                                                                 |
| async_tree_none            | 119 ms                                                                                                           | 112 ms: 1.06x faster                                                                                                 |
| unpack_sequence            | 41.2 ns                                                                                                          | 38.9 ns: 1.06x faster                                                                                                |
| meteor_contest             | 60.1 ms                                                                                                          | 57.2 ms: 1.05x faster                                                                                                |
| telco                      | 3.20 ms                                                                                                          | 3.08 ms: 1.04x faster                                                                                                |
| json_dumps                 | 4.53 ms                                                                                                          | 4.36 ms: 1.04x faster                                                                                                |
| logging_format             | 2.81 us                                                                                                          | 2.71 us: 1.04x faster                                                                                                |
| genshi_text                | 11.9 ms                                                                                                          | 11.5 ms: 1.04x faster                                                                                                |
| logging_simple             | 2.55 us                                                                                                          | 2.46 us: 1.04x faster                                                                                                |
| xml_etree_iterparse        | 45.1 ms                                                                                                          | 43.6 ms: 1.03x faster                                                                                                |
| sqlglot_v2_parse           | 609 us                                                                                                           | 590 us: 1.03x faster                                                                                                 |
| sqlite_synth               | 1.14 us                                                                                                          | 1.10 us: 1.03x faster                                                                                                |
| thrift                     | 358 us                                                                                                           | 347 us: 1.03x faster                                                                                                 |
| deltablue                  | 1.74 ms                                                                                                          | 1.69 ms: 1.03x faster                                                                                                |
| async_tree_io              | 270 ms                                                                                                           | 263 ms: 1.03x faster                                                                                                 |
| django_template            | 16.0 ms                                                                                                          | 15.6 ms: 1.03x faster                                                                                                |
| crypto_pyaes               | 41.7 ms                                                                                                          | 40.6 ms: 1.03x faster                                                                                                |
| typing_runtime_protocols   | 76.3 us                                                                                                          | 74.3 us: 1.03x faster                                                                                                |
| json                       | 2.28 ms                                                                                                          | 2.22 ms: 1.02x faster                                                                                                |
| logging_silent             | 49.6 ns                                                                                                          | 48.5 ns: 1.02x faster                                                                                                |
| subparsers                 | 4.81 ms                                                                                                          | 4.71 ms: 1.02x faster                                                                                                |
| bpe_tokeniser              | 2.30 sec                                                                                                         | 2.25 sec: 1.02x faster                                                                                               |
| xml_etree_parse            | 73.3 ms                                                                                                          | 72.0 ms: 1.02x faster                                                                                                |
| async_tree_cpu_io_mixed    | 332 ms                                                                                                           | 326 ms: 1.02x faster                                                                                                 |
| async_tree_memoization     | 154 ms                                                                                                           | 152 ms: 1.01x faster                                                                                                 |
| sqlglot_v2_transpile       | 740 us                                                                                                           | 736 us: 1.01x faster                                                                                                 |
| go                         | 65.1 ms                                                                                                          | 64.7 ms: 1.01x faster                                                                                                |
| generators                 | 21.0 ms                                                                                                          | 20.9 ms: 1.01x faster                                                                                                |
| asyncio_websockets         | 205 ms                                                                                                           | 205 ms: 1.00x slower                                                                                                 |
| genshi_xml                 | 25.5 ms                                                                                                          | 25.6 ms: 1.01x slower                                                                                                |
| pickle_dict                | 14.1 us                                                                                                          | 14.3 us: 1.01x slower                                                                                                |
| async_tree_cpu_io_mixed_tg | 326 ms                                                                                                           | 330 ms: 1.01x slower                                                                                                 |
| regex_v8                   | 12.8 ms                                                                                                          | 13.0 ms: 1.01x slower                                                                                                |
| sphinx                     | 461 ms                                                                                                           | 468 ms: 1.01x slower                                                                                                 |
| raytrace                   | 132 ms                                                                                                           | 134 ms: 1.02x slower                                                                                                 |
| html5lib                   | 25.1 ms                                                                                                          | 25.6 ms: 1.02x slower                                                                                                |
| async_tree_io_tg           | 269 ms                                                                                                           | 273 ms: 1.02x slower                                                                                                 |
| nqueens                    | 46.7 ms                                                                                                          | 47.5 ms: 1.02x slower                                                                                                |
| python_startup             | 10.2 ms                                                                                                          | 10.4 ms: 1.02x slower                                                                                                |
| asyncio_tcp_ssl            | 649 ms                                                                                                           | 663 ms: 1.02x slower                                                                                                 |
| 2to3                       | 131 ms                                                                                                           | 133 ms: 1.02x slower                                                                                                 |
| regex_dna                  | 114 ms                                                                                                           | 117 ms: 1.02x slower                                                                                                 |
| bench_mp_pool              | 52.4 ms                                                                                                          | 53.7 ms: 1.02x slower                                                                                                |
| coverage                   | 36.3 ms                                                                                                          | 37.3 ms: 1.03x slower                                                                                                |
| unpickle                   | 7.14 us                                                                                                          | 7.33 us: 1.03x slower                                                                                                |
| docutils                   | 1.16 sec                                                                                                         | 1.19 sec: 1.03x slower                                                                                               |
| unpickle_list              | 2.26 us                                                                                                          | 2.33 us: 1.03x slower                                                                                                |
| sqlglot_v2_normalize       | 53.6 ms                                                                                                          | 55.3 ms: 1.03x slower                                                                                                |
| python_startup_no_site     | 7.19 ms                                                                                                          | 7.43 ms: 1.03x slower                                                                                                |
| chaos                      | 29.1 ms                                                                                                          | 30.0 ms: 1.03x slower                                                                                                |
| regex_effbot               | 1.83 ms                                                                                                          | 1.90 ms: 1.04x slower                                                                                                |
| dulwich_log                | 20.9 ms                                                                                                          | 21.8 ms: 1.04x slower                                                                                                |
| create_gc_cycles           | 1.01 ms                                                                                                          | 1.06 ms: 1.04x slower                                                                                                |
| shortest_path              | 245 ms                                                                                                           | 256 ms: 1.04x slower                                                                                                 |
| k_core                     | 988 ms                                                                                                           | 1.03 sec: 1.05x slower                                                                                               |
| async_generators           | 197 ms                                                                                                           | 206 ms: 1.05x slower                                                                                                 |
| gc_traversal               | 2.52 ms                                                                                                          | 2.66 ms: 1.06x slower                                                                                                |
| connected_components       | 226 ms                                                                                                           | 239 ms: 1.06x slower                                                                                                 |
| sqlglot_v2_optimize        | 25.9 ms                                                                                                          | 27.5 ms: 1.06x slower                                                                                                |
| scimark_sparse_mat_mult    | 2.15 ms                                                                                                          | 2.28 ms: 1.06x slower                                                                                                |
| spectral_norm              | 46.2 ms                                                                                                          | 49.3 ms: 1.07x slower                                                                                                |
| sympy_expand               | 196 ms                                                                                                           | 209 ms: 1.07x slower                                                                                                 |
| djangocms                  | 4.87 us                                                                                                          | 5.25 us: 1.08x slower                                                                                                |
| hexiom                     | 3.36 ms                                                                                                          | 3.64 ms: 1.08x slower                                                                                                |
| scimark_lu                 | 50.4 ms                                                                                                          | 55.0 ms: 1.09x slower                                                                                                |
| sympy_sum                  | 62.7 ms                                                                                                          | 69.6 ms: 1.11x slower                                                                                                |
| sympy_str                  | 116 ms                                                                                                           | 129 ms: 1.11x slower                                                                                                 |
| coroutines                 | 12.0 ms                                                                                                          | 13.6 ms: 1.14x slower                                                                                                |
| sympy_integrate            | 8.40 ms                                                                                                          | 9.55 ms: 1.14x slower                                                                                                |
| mdp                        | 615 ms                                                                                                           | 702 ms: 1.14x slower                                                                                                 |
| pylint                     | 124 ms                                                                                                           | 142 ms: 1.14x slower                                                                                                 |
| Geometric mean             | (ref)                                                                                                            | 1.02x faster                                                                                                         |

Benchmark hidden because not significant (11): pycparser, json_loads, async_tree_memoization_tg, bench_thread_pool, pickle_list, pidigits, tomli_loads, many_optionals, pathlib, pickle, asyncio_tcp

- Geometric mean (including insignificant results): 1.018x faster

# HPT report

- Reliability score: 61.01% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x