# Results vs. base

- fork: python
- ref: 37fe9a90c5f99fd3830b
- machine: darwin-arm64
- commit hash: 37fe9a9
- commit date: 2025-12-09
- overall geometric mean: 1.023x faster
- HPT reliability: 94.52%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (4): 2to3, docutils, html5lib, sphinx

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251209-3.15.0a2+-37fe9a9/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json | results/bm-20251209-3.15.0a2+-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 120 ms                                                                                                           | 114 ms: 1.05x faster                                                                                                 |
| async_tree_none_tg         | 121 ms                                                                                                           | 115 ms: 1.05x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 333 ms                                                                                                           | 322 ms: 1.03x faster                                                                                                 |
| async_tree_io              | 273 ms                                                                                                           | 264 ms: 1.03x faster                                                                                                 |
| async_tree_memoization     | 155 ms                                                                                                           | 151 ms: 1.02x faster                                                                                                 |
| async_tree_cpu_io_mixed_tg | 328 ms                                                                                                           | 321 ms: 1.02x faster                                                                                                 |
| asyncio_tcp_ssl            | 661 ms                                                                                                           | 652 ms: 1.01x faster                                                                                                 |
| asyncio_websockets         | 205 ms                                                                                                           | 205 ms: 1.00x faster                                                                                                 |
| async_generators           | 196 ms                                                                                                           | 209 ms: 1.06x slower                                                                                                 |
| coroutines                 | 12.2 ms                                                                                                          | 13.5 ms: 1.11x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.01x faster                                                                                                         |

Benchmark hidden because not significant (3): asyncio_tcp, async_tree_memoization_tg, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251209-3.15.0a2+-37fe9a9/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json | results/bm-20251209-3.15.0a2+-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| nbody          | 61.0 ms                                                                                                          | 55.8 ms: 1.09x faster                                                                                                |
| float          | 33.7 ms                                                                                                          | 31.6 ms: 1.07x faster                                                                                                |
| pidigits       | 215 ms                                                                                                           | 213 ms: 1.01x faster                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.06x faster                                                                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251209-3.15.0a2+-37fe9a9/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json | results/bm-20251209-3.15.0a2+-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 55.1 ms                                                                                                          | 51.8 ms: 1.06x faster                                                                                                |
| regex_effbot   | 1.84 ms                                                                                                          | 1.83 ms: 1.01x faster                                                                                                |
| regex_dna      | 115 ms                                                                                                           | 114 ms: 1.01x faster                                                                                                 |
| regex_v8       | 12.8 ms                                                                                                          | 12.9 ms: 1.01x slower                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.02x faster                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251209-3.15.0a2+-37fe9a9/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json | results/bm-20251209-3.15.0a2+-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 116 us                                                                                                           | 103 us: 1.13x faster                                                                                                 |
| pickle_pure_python   | 165 us                                                                                                           | 147 us: 1.12x faster                                                                                                 |
| xml_etree_process    | 28.9 ms                                                                                                          | 26.1 ms: 1.11x faster                                                                                                |
| xml_etree_generate   | 41.1 ms                                                                                                          | 37.2 ms: 1.10x faster                                                                                                |
| xml_etree_iterparse  | 45.7 ms                                                                                                          | 43.6 ms: 1.05x faster                                                                                                |
| xml_etree_parse      | 74.4 ms                                                                                                          | 72.3 ms: 1.03x faster                                                                                                |
| json_dumps           | 4.45 ms                                                                                                          | 4.37 ms: 1.02x faster                                                                                                |
| pickle_list          | 2.38 us                                                                                                          | 2.36 us: 1.01x faster                                                                                                |
| json_loads           | 12.9 us                                                                                                          | 12.9 us: 1.00x faster                                                                                                |
| pickle_dict          | 14.2 us                                                                                                          | 14.3 us: 1.01x slower                                                                                                |
| pickle               | 6.70 us                                                                                                          | 6.81 us: 1.02x slower                                                                                                |
| unpickle_list        | 2.28 us                                                                                                          | 2.32 us: 1.02x slower                                                                                                |
| unpickle             | 7.09 us                                                                                                          | 7.33 us: 1.03x slower                                                                                                |
| tomli_loads          | 1.22 sec                                                                                                         | 1.27 sec: 1.04x slower                                                                                               |
| Geometric mean       | (ref)                                                                                                            | 1.03x faster                                                                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251209-3.15.0a2+-37fe9a9/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json | results/bm-20251209-3.15.0a2+-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                                                          | 10.2 ms: 1.01x faster                                                                                                |
| python_startup_no_site | 7.27 ms                                                                                                          | 7.36 ms: 1.01x slower                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.00x slower                                                                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251209-3.15.0a2+-37fe9a9/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json | results/bm-20251209-3.15.0a2+-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 5.84 ms                                                                                                          | 5.14 ms: 1.14x faster                                                                                                |
| genshi_text     | 11.9 ms                                                                                                          | 11.5 ms: 1.04x faster                                                                                                |
| django_template | 16.0 ms                                                                                                          | 16.1 ms: 1.00x slower                                                                                                |
| genshi_xml      | 25.6 ms                                                                                                          | 26.5 ms: 1.04x slower                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.03x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20251209-3.15.0a2+-37fe9a9/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json | results/bm-20251209-3.15.0a2+-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2+-37fe9a9.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                   | 24.2 ms                                                                                                          | 15.4 ms: 1.57x faster                                                                                                |
| richards_super             | 27.4 ms                                                                                                          | 17.8 ms: 1.54x faster                                                                                                |
| pprint_safe_repr           | 384 ms                                                                                                           | 320 ms: 1.20x faster                                                                                                 |
| pprint_pformat             | 775 ms                                                                                                           | 651 ms: 1.19x faster                                                                                                 |
| deepcopy_memo              | 14.8 us                                                                                                          | 12.5 us: 1.19x faster                                                                                                |
| scimark_monte_carlo        | 34.5 ms                                                                                                          | 29.8 ms: 1.16x faster                                                                                                |
| mako                       | 5.84 ms                                                                                                          | 5.14 ms: 1.14x faster                                                                                                |
| scimark_sor                | 61.5 ms                                                                                                          | 54.2 ms: 1.14x faster                                                                                                |
| scimark_fft                | 145 ms                                                                                                           | 128 ms: 1.14x faster                                                                                                 |
| unpickle_pure_python       | 116 us                                                                                                           | 103 us: 1.13x faster                                                                                                 |
| pickle_pure_python         | 165 us                                                                                                           | 147 us: 1.12x faster                                                                                                 |
| xml_etree_process          | 28.9 ms                                                                                                          | 26.1 ms: 1.11x faster                                                                                                |
| xml_etree_generate         | 41.1 ms                                                                                                          | 37.2 ms: 1.10x faster                                                                                                |
| nbody                      | 61.0 ms                                                                                                          | 55.8 ms: 1.09x faster                                                                                                |
| fannkuch                   | 217 ms                                                                                                           | 200 ms: 1.08x faster                                                                                                 |
| pyflate                    | 223 ms                                                                                                           | 208 ms: 1.07x faster                                                                                                 |
| float                      | 33.7 ms                                                                                                          | 31.6 ms: 1.07x faster                                                                                                |
| regex_compile              | 55.1 ms                                                                                                          | 51.8 ms: 1.06x faster                                                                                                |
| meteor_contest             | 60.0 ms                                                                                                          | 56.5 ms: 1.06x faster                                                                                                |
| deepcopy                   | 123 us                                                                                                           | 117 us: 1.06x faster                                                                                                 |
| comprehensions             | 8.98 us                                                                                                          | 8.49 us: 1.06x faster                                                                                                |
| telco                      | 3.20 ms                                                                                                          | 3.04 ms: 1.05x faster                                                                                                |
| async_tree_none            | 120 ms                                                                                                           | 114 ms: 1.05x faster                                                                                                 |
| async_tree_none_tg         | 121 ms                                                                                                           | 115 ms: 1.05x faster                                                                                                 |
| deepcopy_reduce            | 1.30 us                                                                                                          | 1.24 us: 1.05x faster                                                                                                |
| xml_etree_iterparse        | 45.7 ms                                                                                                          | 43.6 ms: 1.05x faster                                                                                                |
| genshi_text                | 11.9 ms                                                                                                          | 11.5 ms: 1.04x faster                                                                                                |
| create_gc_cycles           | 1.03 ms                                                                                                          | 997 us: 1.03x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 333 ms                                                                                                           | 322 ms: 1.03x faster                                                                                                 |
| bpe_tokeniser              | 2.30 sec                                                                                                         | 2.23 sec: 1.03x faster                                                                                               |
| async_tree_io              | 273 ms                                                                                                           | 264 ms: 1.03x faster                                                                                                 |
| unpack_sequence            | 40.7 ns                                                                                                          | 39.5 ns: 1.03x faster                                                                                                |
| xml_etree_parse            | 74.4 ms                                                                                                          | 72.3 ms: 1.03x faster                                                                                                |
| logging_format             | 2.82 us                                                                                                          | 2.75 us: 1.03x faster                                                                                                |
| subparsers                 | 4.86 ms                                                                                                          | 4.72 ms: 1.03x faster                                                                                                |
| async_tree_memoization     | 155 ms                                                                                                           | 151 ms: 1.02x faster                                                                                                 |
| sqlite_synth               | 1.13 us                                                                                                          | 1.11 us: 1.02x faster                                                                                                |
| many_optionals             | 347 us                                                                                                           | 339 us: 1.02x faster                                                                                                 |
| logging_simple             | 2.57 us                                                                                                          | 2.52 us: 1.02x faster                                                                                                |
| async_tree_cpu_io_mixed_tg | 328 ms                                                                                                           | 321 ms: 1.02x faster                                                                                                 |
| thrift                     | 360 us                                                                                                           | 353 us: 1.02x faster                                                                                                 |
| json_dumps                 | 4.45 ms                                                                                                          | 4.37 ms: 1.02x faster                                                                                                |
| sqlglot_v2_parse           | 607 us                                                                                                           | 597 us: 1.02x faster                                                                                                 |
| gc_traversal               | 2.52 ms                                                                                                          | 2.48 ms: 1.02x faster                                                                                                |
| crypto_pyaes               | 41.5 ms                                                                                                          | 40.9 ms: 1.01x faster                                                                                                |
| json                       | 2.27 ms                                                                                                          | 2.24 ms: 1.01x faster                                                                                                |
| generators                 | 21.1 ms                                                                                                          | 20.9 ms: 1.01x faster                                                                                                |
| asyncio_tcp_ssl            | 661 ms                                                                                                           | 652 ms: 1.01x faster                                                                                                 |
| python_startup             | 10.3 ms                                                                                                          | 10.2 ms: 1.01x faster                                                                                                |
| regex_effbot               | 1.84 ms                                                                                                          | 1.83 ms: 1.01x faster                                                                                                |
| pidigits                   | 215 ms                                                                                                           | 213 ms: 1.01x faster                                                                                                 |
| regex_dna                  | 115 ms                                                                                                           | 114 ms: 1.01x faster                                                                                                 |
| deltablue                  | 1.70 ms                                                                                                          | 1.69 ms: 1.01x faster                                                                                                |
| pickle_list                | 2.38 us                                                                                                          | 2.36 us: 1.01x faster                                                                                                |
| pathlib                    | 12.5 ms                                                                                                          | 12.5 ms: 1.01x faster                                                                                                |
| json_loads                 | 12.9 us                                                                                                          | 12.9 us: 1.00x faster                                                                                                |
| bench_thread_pool          | 475 us                                                                                                           | 474 us: 1.00x faster                                                                                                 |
| asyncio_websockets         | 205 ms                                                                                                           | 205 ms: 1.00x faster                                                                                                 |
| django_template            | 16.0 ms                                                                                                          | 16.1 ms: 1.00x slower                                                                                                |
| sqlglot_v2_transpile       | 741 us                                                                                                           | 744 us: 1.01x slower                                                                                                 |
| regex_v8                   | 12.8 ms                                                                                                          | 12.9 ms: 1.01x slower                                                                                                |
| pickle_dict                | 14.2 us                                                                                                          | 14.3 us: 1.01x slower                                                                                                |
| bench_mp_pool              | 52.7 ms                                                                                                          | 53.3 ms: 1.01x slower                                                                                                |
| python_startup_no_site     | 7.27 ms                                                                                                          | 7.36 ms: 1.01x slower                                                                                                |
| scimark_sparse_mat_mult    | 2.15 ms                                                                                                          | 2.18 ms: 1.01x slower                                                                                                |
| raytrace                   | 133 ms                                                                                                           | 135 ms: 1.01x slower                                                                                                 |
| pickle                     | 6.70 us                                                                                                          | 6.81 us: 1.02x slower                                                                                                |
| unpickle_list              | 2.28 us                                                                                                          | 2.32 us: 1.02x slower                                                                                                |
| nqueens                    | 46.5 ms                                                                                                          | 47.4 ms: 1.02x slower                                                                                                |
| pycparser                  | 535 ms                                                                                                           | 545 ms: 1.02x slower                                                                                                 |
| go                         | 64.2 ms                                                                                                          | 65.6 ms: 1.02x slower                                                                                                |
| dulwich_log                | 21.2 ms                                                                                                          | 21.8 ms: 1.03x slower                                                                                                |
| k_core                     | 995 ms                                                                                                           | 1.02 sec: 1.03x slower                                                                                               |
| shortest_path              | 245 ms                                                                                                           | 253 ms: 1.03x slower                                                                                                 |
| unpickle                   | 7.09 us                                                                                                          | 7.33 us: 1.03x slower                                                                                                |
| coverage                   | 36.5 ms                                                                                                          | 37.8 ms: 1.03x slower                                                                                                |
| genshi_xml                 | 25.6 ms                                                                                                          | 26.5 ms: 1.04x slower                                                                                                |
| connected_components       | 227 ms                                                                                                           | 236 ms: 1.04x slower                                                                                                 |
| sqlglot_v2_normalize       | 53.9 ms                                                                                                          | 56.1 ms: 1.04x slower                                                                                                |
| tomli_loads                | 1.22 sec                                                                                                         | 1.27 sec: 1.04x slower                                                                                               |
| chaos                      | 29.0 ms                                                                                                          | 30.3 ms: 1.05x slower                                                                                                |
| djangocms                  | 4.94 us                                                                                                          | 5.20 us: 1.05x slower                                                                                                |
| sqlglot_v2_optimize        | 26.1 ms                                                                                                          | 27.7 ms: 1.06x slower                                                                                                |
| scimark_lu                 | 51.3 ms                                                                                                          | 54.4 ms: 1.06x slower                                                                                                |
| async_generators           | 196 ms                                                                                                           | 209 ms: 1.06x slower                                                                                                 |
| spectral_norm              | 46.3 ms                                                                                                          | 49.9 ms: 1.08x slower                                                                                                |
| sympy_expand               | 197 ms                                                                                                           | 216 ms: 1.09x slower                                                                                                 |
| hexiom                     | 3.32 ms                                                                                                          | 3.66 ms: 1.10x slower                                                                                                |
| sympy_sum                  | 63.1 ms                                                                                                          | 69.8 ms: 1.11x slower                                                                                                |
| coroutines                 | 12.2 ms                                                                                                          | 13.5 ms: 1.11x slower                                                                                                |
| pylint                     | 126 ms                                                                                                           | 141 ms: 1.12x slower                                                                                                 |
| mdp                        | 619 ms                                                                                                           | 696 ms: 1.12x slower                                                                                                 |
| sympy_str                  | 116 ms                                                                                                           | 132 ms: 1.13x slower                                                                                                 |
| sympy_integrate            | 8.40 ms                                                                                                          | 9.59 ms: 1.14x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.02x faster                                                                                                         |

Benchmark hidden because not significant (9): asyncio_tcp, async_tree_memoization_tg, docutils, 2to3, async_tree_io_tg, html5lib, logging_silent, typing_runtime_protocols, sphinx

- Geometric mean (including insignificant results): 1.023x faster

# HPT report

- Reliability score: 94.52% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x