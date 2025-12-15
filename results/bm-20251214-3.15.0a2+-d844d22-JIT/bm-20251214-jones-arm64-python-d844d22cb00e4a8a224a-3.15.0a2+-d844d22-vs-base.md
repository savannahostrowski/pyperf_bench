# Results vs. base

- fork: python
- ref: d844d22cb00e4a8a224a
- machine: darwin-arm64
- commit hash: d844d22
- commit date: 2025-12-14
- overall geometric mean: 1.082x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 132 ms                                                                                                           | 131 ms: 1.01x faster                                                                                                 |
| chameleon      | 7.69 ms                                                                                                          | 7.63 ms: 1.01x faster                                                                                                |
| html5lib       | 25.5 ms                                                                                                          | 24.3 ms: 1.05x faster                                                                                                |
| tornado_http   | 51.3 ms                                                                                                          | 52.0 ms: 1.01x slower                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.01x faster                                                                                                         |

Benchmark hidden because not significant (1): sphinx

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 117 ms                                                                                                           | 112 ms: 1.04x faster                                                                                                 |
| async_tree_none_tg         | 118 ms                                                                                                           | 114 ms: 1.03x faster                                                                                                 |
| async_tree_io              | 270 ms                                                                                                           | 264 ms: 1.02x faster                                                                                                 |
| async_tree_memoization     | 154 ms                                                                                                           | 151 ms: 1.02x faster                                                                                                 |
| asyncio_websockets         | 205 ms                                                                                                           | 206 ms: 1.00x slower                                                                                                 |
| async_tree_cpu_io_mixed    | 320 ms                                                                                                           | 326 ms: 1.02x slower                                                                                                 |
| asyncio_tcp_ssl            | 651 ms                                                                                                           | 662 ms: 1.02x slower                                                                                                 |
| async_tree_cpu_io_mixed_tg | 322 ms                                                                                                           | 330 ms: 1.03x slower                                                                                                 |
| asyncio_tcp                | 164 ms                                                                                                           | 169 ms: 1.03x slower                                                                                                 |
| async_generators           | 196 ms                                                                                                           | 207 ms: 1.06x slower                                                                                                 |
| coroutines                 | 12.4 ms                                                                                                          | 13.9 ms: 1.12x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.01x slower                                                                                                         |

Benchmark hidden because not significant (2): async_tree_io_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| nbody          | 63.0 ms                                                                                                          | 42.7 ms: 1.48x faster                                                                                                |
| float          | 34.7 ms                                                                                                          | 27.3 ms: 1.27x faster                                                                                                |
| pidigits       | 213 ms                                                                                                           | 223 ms: 1.04x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.22x faster                                                                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 56.6 ms                                                                                                          | 48.5 ms: 1.17x faster                                                                                                |
| regex_effbot   | 1.98 ms                                                                                                          | 1.87 ms: 1.06x faster                                                                                                |
| regex_dna      | 115 ms                                                                                                           | 116 ms: 1.01x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.05x faster                                                                                                         |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 121 us                                                                                                           | 86.6 us: 1.40x faster                                                                                                |
| tomli_loads          | 1.22 sec                                                                                                         | 948 ms: 1.29x faster                                                                                                 |
| pickle_pure_python   | 172 us                                                                                                           | 137 us: 1.25x faster                                                                                                 |
| xml_etree_process    | 29.9 ms                                                                                                          | 24.9 ms: 1.20x faster                                                                                                |
| xml_etree_generate   | 41.6 ms                                                                                                          | 35.5 ms: 1.17x faster                                                                                                |
| json_dumps           | 4.54 ms                                                                                                          | 4.22 ms: 1.08x faster                                                                                                |
| xml_etree_iterparse  | 45.0 ms                                                                                                          | 42.9 ms: 1.05x faster                                                                                                |
| xml_etree_parse      | 73.0 ms                                                                                                          | 71.4 ms: 1.02x faster                                                                                                |
| pickle               | 6.76 us                                                                                                          | 6.69 us: 1.01x faster                                                                                                |
| pickle_list          | 2.35 us                                                                                                          | 2.34 us: 1.01x faster                                                                                                |
| json_loads           | 12.6 us                                                                                                          | 12.7 us: 1.00x slower                                                                                                |
| pickle_dict          | 14.3 us                                                                                                          | 14.5 us: 1.01x slower                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.10x faster                                                                                                         |

Benchmark hidden because not significant (2): unpickle, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 7.32 ms                                                                                                          | 7.39 ms: 1.01x slower                                                                                                |
| python_startup         | 10.1 ms                                                                                                          | 10.3 ms: 1.02x slower                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.01x slower                                                                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 6.17 ms                                                                                                          | 4.87 ms: 1.27x faster                                                                                                |
| genshi_text     | 12.3 ms                                                                                                          | 10.7 ms: 1.15x faster                                                                                                |
| django_template | 16.6 ms                                                                                                          | 15.5 ms: 1.07x faster                                                                                                |
| genshi_xml      | 26.2 ms                                                                                                          | 24.7 ms: 1.06x faster                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.13x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                   | 25.5 ms                                                                                                          | 12.1 ms: 2.10x faster                                                                                                |
| richards_super             | 28.4 ms                                                                                                          | 14.6 ms: 1.94x faster                                                                                                |
| nbody                      | 63.0 ms                                                                                                          | 42.7 ms: 1.48x faster                                                                                                |
| unpickle_pure_python       | 121 us                                                                                                           | 86.6 us: 1.40x faster                                                                                                |
| scimark_monte_carlo        | 34.8 ms                                                                                                          | 25.7 ms: 1.36x faster                                                                                                |
| logging_silent             | 49.3 ns                                                                                                          | 37.2 ns: 1.33x faster                                                                                                |
| scimark_sor                | 63.2 ms                                                                                                          | 48.2 ms: 1.31x faster                                                                                                |
| deltablue                  | 1.78 ms                                                                                                          | 1.37 ms: 1.30x faster                                                                                                |
| tomli_loads                | 1.22 sec                                                                                                         | 948 ms: 1.29x faster                                                                                                 |
| pprint_safe_repr           | 393 ms                                                                                                           | 305 ms: 1.29x faster                                                                                                 |
| pyflate                    | 231 ms                                                                                                           | 179 ms: 1.29x faster                                                                                                 |
| pprint_pformat             | 791 ms                                                                                                           | 618 ms: 1.28x faster                                                                                                 |
| scimark_fft                | 143 ms                                                                                                           | 112 ms: 1.28x faster                                                                                                 |
| float                      | 34.7 ms                                                                                                          | 27.3 ms: 1.27x faster                                                                                                |
| mako                       | 6.17 ms                                                                                                          | 4.87 ms: 1.27x faster                                                                                                |
| pickle_pure_python         | 172 us                                                                                                           | 137 us: 1.25x faster                                                                                                 |
| crypto_pyaes               | 42.3 ms                                                                                                          | 34.5 ms: 1.22x faster                                                                                                |
| deepcopy_memo              | 16.1 us                                                                                                          | 13.2 us: 1.22x faster                                                                                                |
| go                         | 67.6 ms                                                                                                          | 55.9 ms: 1.21x faster                                                                                                |
| fannkuch                   | 216 ms                                                                                                           | 179 ms: 1.21x faster                                                                                                 |
| comprehensions             | 9.03 us                                                                                                          | 7.49 us: 1.21x faster                                                                                                |
| xml_etree_process          | 29.9 ms                                                                                                          | 24.9 ms: 1.20x faster                                                                                                |
| xml_etree_generate         | 41.6 ms                                                                                                          | 35.5 ms: 1.17x faster                                                                                                |
| regex_compile              | 56.6 ms                                                                                                          | 48.5 ms: 1.17x faster                                                                                                |
| genshi_text                | 12.3 ms                                                                                                          | 10.7 ms: 1.15x faster                                                                                                |
| meteor_contest             | 59.5 ms                                                                                                          | 52.4 ms: 1.14x faster                                                                                                |
| sqlglot_v2_parse           | 626 us                                                                                                           | 552 us: 1.13x faster                                                                                                 |
| chaos                      | 29.5 ms                                                                                                          | 26.1 ms: 1.13x faster                                                                                                |
| deepcopy                   | 127 us                                                                                                           | 113 us: 1.12x faster                                                                                                 |
| nqueens                    | 47.8 ms                                                                                                          | 42.5 ms: 1.12x faster                                                                                                |
| bpe_tokeniser              | 2.32 sec                                                                                                         | 2.08 sec: 1.11x faster                                                                                               |
| deepcopy_reduce            | 1.36 us                                                                                                          | 1.22 us: 1.11x faster                                                                                                |
| spectral_norm              | 46.5 ms                                                                                                          | 42.2 ms: 1.10x faster                                                                                                |
| hexiom                     | 3.38 ms                                                                                                          | 3.10 ms: 1.09x faster                                                                                                |
| sqlglot_v2_transpile       | 760 us                                                                                                           | 699 us: 1.09x faster                                                                                                 |
| telco                      | 3.19 ms                                                                                                          | 2.95 ms: 1.08x faster                                                                                                |
| json_dumps                 | 4.54 ms                                                                                                          | 4.22 ms: 1.08x faster                                                                                                |
| logging_simple             | 2.63 us                                                                                                          | 2.45 us: 1.07x faster                                                                                                |
| scimark_lu                 | 51.8 ms                                                                                                          | 48.5 ms: 1.07x faster                                                                                                |
| django_template            | 16.6 ms                                                                                                          | 15.5 ms: 1.07x faster                                                                                                |
| logging_format             | 2.87 us                                                                                                          | 2.70 us: 1.06x faster                                                                                                |
| genshi_xml                 | 26.2 ms                                                                                                          | 24.7 ms: 1.06x faster                                                                                                |
| regex_effbot               | 1.98 ms                                                                                                          | 1.87 ms: 1.06x faster                                                                                                |
| raytrace                   | 133 ms                                                                                                           | 126 ms: 1.06x faster                                                                                                 |
| pycparser                  | 542 ms                                                                                                           | 515 ms: 1.05x faster                                                                                                 |
| xml_etree_iterparse        | 45.0 ms                                                                                                          | 42.9 ms: 1.05x faster                                                                                                |
| thrift                     | 360 us                                                                                                           | 344 us: 1.05x faster                                                                                                 |
| html5lib                   | 25.5 ms                                                                                                          | 24.3 ms: 1.05x faster                                                                                                |
| async_tree_none            | 117 ms                                                                                                           | 112 ms: 1.04x faster                                                                                                 |
| typing_runtime_protocols   | 77.8 us                                                                                                          | 74.6 us: 1.04x faster                                                                                                |
| scimark_sparse_mat_mult    | 2.17 ms                                                                                                          | 2.08 ms: 1.04x faster                                                                                                |
| subparsers                 | 4.94 ms                                                                                                          | 4.75 ms: 1.04x faster                                                                                                |
| async_tree_none_tg         | 118 ms                                                                                                           | 114 ms: 1.03x faster                                                                                                 |
| xml_etree_parse            | 73.0 ms                                                                                                          | 71.4 ms: 1.02x faster                                                                                                |
| async_tree_io              | 270 ms                                                                                                           | 264 ms: 1.02x faster                                                                                                 |
| async_tree_memoization     | 154 ms                                                                                                           | 151 ms: 1.02x faster                                                                                                 |
| json                       | 2.24 ms                                                                                                          | 2.19 ms: 1.02x faster                                                                                                |
| k_core                     | 986 ms                                                                                                           | 967 ms: 1.02x faster                                                                                                 |
| sqlalchemy_imperative      | 5.85 ms                                                                                                          | 5.79 ms: 1.01x faster                                                                                                |
| pickle                     | 6.76 us                                                                                                          | 6.69 us: 1.01x faster                                                                                                |
| bench_thread_pool          | 475 us                                                                                                           | 471 us: 1.01x faster                                                                                                 |
| 2to3                       | 132 ms                                                                                                           | 131 ms: 1.01x faster                                                                                                 |
| pathlib                    | 12.5 ms                                                                                                          | 12.5 ms: 1.01x faster                                                                                                |
| chameleon                  | 7.69 ms                                                                                                          | 7.63 ms: 1.01x faster                                                                                                |
| pickle_list                | 2.35 us                                                                                                          | 2.34 us: 1.01x faster                                                                                                |
| sqlite_synth               | 1.12 us                                                                                                          | 1.12 us: 1.00x faster                                                                                                |
| shortest_path              | 243 ms                                                                                                           | 244 ms: 1.00x slower                                                                                                 |
| json_loads                 | 12.6 us                                                                                                          | 12.7 us: 1.00x slower                                                                                                |
| asyncio_websockets         | 205 ms                                                                                                           | 206 ms: 1.00x slower                                                                                                 |
| regex_dna                  | 115 ms                                                                                                           | 116 ms: 1.01x slower                                                                                                 |
| many_optionals             | 342 us                                                                                                           | 344 us: 1.01x slower                                                                                                 |
| gc_traversal               | 2.51 ms                                                                                                          | 2.54 ms: 1.01x slower                                                                                                |
| python_startup_no_site     | 7.32 ms                                                                                                          | 7.39 ms: 1.01x slower                                                                                                |
| sqlglot_v2_optimize        | 26.6 ms                                                                                                          | 26.9 ms: 1.01x slower                                                                                                |
| dulwich_log                | 21.3 ms                                                                                                          | 21.7 ms: 1.01x slower                                                                                                |
| tornado_http               | 51.3 ms                                                                                                          | 52.0 ms: 1.01x slower                                                                                                |
| pickle_dict                | 14.3 us                                                                                                          | 14.5 us: 1.01x slower                                                                                                |
| async_tree_cpu_io_mixed    | 320 ms                                                                                                           | 326 ms: 1.02x slower                                                                                                 |
| asyncio_tcp_ssl            | 651 ms                                                                                                           | 662 ms: 1.02x slower                                                                                                 |
| python_startup             | 10.1 ms                                                                                                          | 10.3 ms: 1.02x slower                                                                                                |
| sqlalchemy_declarative     | 50.0 ms                                                                                                          | 51.0 ms: 1.02x slower                                                                                                |
| bench_mp_pool              | 52.5 ms                                                                                                          | 53.6 ms: 1.02x slower                                                                                                |
| async_tree_cpu_io_mixed_tg | 322 ms                                                                                                           | 330 ms: 1.03x slower                                                                                                 |
| asyncio_tcp                | 164 ms                                                                                                           | 169 ms: 1.03x slower                                                                                                 |
| coverage                   | 36.4 ms                                                                                                          | 37.9 ms: 1.04x slower                                                                                                |
| generators                 | 20.0 ms                                                                                                          | 20.8 ms: 1.04x slower                                                                                                |
| pidigits                   | 213 ms                                                                                                           | 223 ms: 1.04x slower                                                                                                 |
| create_gc_cycles           | 991 us                                                                                                           | 1.04 ms: 1.05x slower                                                                                                |
| async_generators           | 196 ms                                                                                                           | 207 ms: 1.06x slower                                                                                                 |
| djangocms                  | 4.76 us                                                                                                          | 5.05 us: 1.06x slower                                                                                                |
| pylint                     | 131 ms                                                                                                           | 141 ms: 1.08x slower                                                                                                 |
| mdp                        | 612 ms                                                                                                           | 682 ms: 1.12x slower                                                                                                 |
| coroutines                 | 12.4 ms                                                                                                          | 13.9 ms: 1.12x slower                                                                                                |
| unpack_sequence            | 35.8 ns                                                                                                          | 40.3 ns: 1.13x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.08x faster                                                                                                         |

Benchmark hidden because not significant (9): async_tree_io_tg, connected_components, unpickle, xdsl_constant_fold, regex_v8, sphinx, sqlglot_v2_normalize, unpickle_list, async_tree_memoization_tg
Ignored benchmarks (5) of results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.082x faster

# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x

# Memory
- memory change: 1.02x