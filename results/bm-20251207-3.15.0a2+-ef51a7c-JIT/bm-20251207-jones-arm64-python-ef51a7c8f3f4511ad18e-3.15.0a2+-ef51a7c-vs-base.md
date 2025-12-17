# Results vs. base

- fork: python
- ref: ef51a7c8f3f4511ad18e
- machine: darwin-arm64
- commit hash: ef51a7c
- commit date: 2025-12-07
- overall geometric mean: 1.013x faster
- HPT reliability: 65.35%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 133 ms                                                                                                           | 136 ms: 1.03x slower                                                                                                 |
| docutils       | 1.16 sec                                                                                                         | 1.21 sec: 1.04x slower                                                                                               |
| html5lib       | 25.3 ms                                                                                                          | 25.7 ms: 1.02x slower                                                                                                |
| sphinx         | 460 ms                                                                                                           | 475 ms: 1.03x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.03x slower                                                                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 120 ms                                                                                                           | 115 ms: 1.04x faster                                                                                                 |
| async_tree_io              | 271 ms                                                                                                           | 268 ms: 1.01x faster                                                                                                 |
| asyncio_websockets         | 205 ms                                                                                                           | 206 ms: 1.00x slower                                                                                                 |
| async_tree_cpu_io_mixed_tg | 327 ms                                                                                                           | 330 ms: 1.01x slower                                                                                                 |
| asyncio_tcp_ssl            | 649 ms                                                                                                           | 662 ms: 1.02x slower                                                                                                 |
| async_tree_io_tg           | 269 ms                                                                                                           | 277 ms: 1.03x slower                                                                                                 |
| asyncio_tcp                | 162 ms                                                                                                           | 169 ms: 1.04x slower                                                                                                 |
| async_generators           | 199 ms                                                                                                           | 214 ms: 1.07x slower                                                                                                 |
| coroutines                 | 12.3 ms                                                                                                          | 13.7 ms: 1.12x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.02x slower                                                                                                         |

Benchmark hidden because not significant (4): async_tree_none_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| nbody          | 61.1 ms                                                                                                          | 55.7 ms: 1.10x faster                                                                                                |
| float          | 33.3 ms                                                                                                          | 31.8 ms: 1.05x faster                                                                                                |
| pidigits       | 212 ms                                                                                                           | 217 ms: 1.02x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.04x faster                                                                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 56.4 ms                                                                                                          | 52.4 ms: 1.08x faster                                                                                                |
| regex_effbot   | 1.89 ms                                                                                                          | 1.82 ms: 1.04x faster                                                                                                |
| regex_v8       | 12.8 ms                                                                                                          | 12.9 ms: 1.00x slower                                                                                                |
| regex_dna      | 114 ms                                                                                                           | 115 ms: 1.01x slower                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.03x faster                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| tomli_loads          | 1.13 sec                                                                                                         | 958 ms: 1.18x faster                                                                                                 |
| pickle_pure_python   | 171 us                                                                                                           | 148 us: 1.15x faster                                                                                                 |
| xml_etree_process    | 29.5 ms                                                                                                          | 26.3 ms: 1.12x faster                                                                                                |
| unpickle_pure_python | 117 us                                                                                                           | 106 us: 1.11x faster                                                                                                 |
| xml_etree_generate   | 41.7 ms                                                                                                          | 37.9 ms: 1.10x faster                                                                                                |
| xml_etree_iterparse  | 45.0 ms                                                                                                          | 44.1 ms: 1.02x faster                                                                                                |
| json_dumps           | 4.49 ms                                                                                                          | 4.40 ms: 1.02x faster                                                                                                |
| json_loads           | 13.0 us                                                                                                          | 12.8 us: 1.02x faster                                                                                                |
| xml_etree_parse      | 72.8 ms                                                                                                          | 71.8 ms: 1.01x faster                                                                                                |
| unpickle             | 7.27 us                                                                                                          | 7.32 us: 1.01x slower                                                                                                |
| pickle_list          | 2.38 us                                                                                                          | 2.40 us: 1.01x slower                                                                                                |
| unpickle_list        | 2.33 us                                                                                                          | 2.35 us: 1.01x slower                                                                                                |
| pickle               | 6.74 us                                                                                                          | 6.82 us: 1.01x slower                                                                                                |
| pickle_dict          | 14.2 us                                                                                                          | 14.5 us: 1.02x slower                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.05x faster                                                                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 7.27 ms                                                                                                          | 7.42 ms: 1.02x slower                                                                                                |
| python_startup         | 10.2 ms                                                                                                          | 10.4 ms: 1.02x slower                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.02x slower                                                                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 6.08 ms                                                                                                          | 5.20 ms: 1.17x faster                                                                                                |
| genshi_text     | 12.3 ms                                                                                                          | 11.7 ms: 1.05x faster                                                                                                |
| django_template | 16.4 ms                                                                                                          | 16.2 ms: 1.01x faster                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.05x faster                                                                                                         |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark                  | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                   | 24.6 ms                                                                                                          | 16.1 ms: 1.53x faster                                                                                                |
| richards_super             | 27.6 ms                                                                                                          | 18.6 ms: 1.49x faster                                                                                                |
| deepcopy_memo              | 15.6 us                                                                                                          | 12.8 us: 1.22x faster                                                                                                |
| pprint_safe_repr           | 390 ms                                                                                                           | 321 ms: 1.21x faster                                                                                                 |
| pprint_pformat             | 791 ms                                                                                                           | 654 ms: 1.21x faster                                                                                                 |
| tomli_loads                | 1.13 sec                                                                                                         | 958 ms: 1.18x faster                                                                                                 |
| mako                       | 6.08 ms                                                                                                          | 5.20 ms: 1.17x faster                                                                                                |
| pickle_pure_python         | 171 us                                                                                                           | 148 us: 1.15x faster                                                                                                 |
| scimark_sor                | 62.7 ms                                                                                                          | 54.5 ms: 1.15x faster                                                                                                |
| scimark_fft                | 145 ms                                                                                                           | 128 ms: 1.13x faster                                                                                                 |
| scimark_monte_carlo        | 34.6 ms                                                                                                          | 30.5 ms: 1.13x faster                                                                                                |
| xml_etree_process          | 29.5 ms                                                                                                          | 26.3 ms: 1.12x faster                                                                                                |
| fannkuch                   | 217 ms                                                                                                           | 195 ms: 1.12x faster                                                                                                 |
| unpickle_pure_python       | 117 us                                                                                                           | 106 us: 1.11x faster                                                                                                 |
| xml_etree_generate         | 41.7 ms                                                                                                          | 37.9 ms: 1.10x faster                                                                                                |
| pyflate                    | 228 ms                                                                                                           | 208 ms: 1.10x faster                                                                                                 |
| deepcopy                   | 129 us                                                                                                           | 117 us: 1.10x faster                                                                                                 |
| nbody                      | 61.1 ms                                                                                                          | 55.7 ms: 1.10x faster                                                                                                |
| regex_compile              | 56.4 ms                                                                                                          | 52.4 ms: 1.08x faster                                                                                                |
| deepcopy_reduce            | 1.35 us                                                                                                          | 1.26 us: 1.07x faster                                                                                                |
| telco                      | 3.22 ms                                                                                                          | 3.05 ms: 1.05x faster                                                                                                |
| comprehensions             | 8.96 us                                                                                                          | 8.51 us: 1.05x faster                                                                                                |
| genshi_text                | 12.3 ms                                                                                                          | 11.7 ms: 1.05x faster                                                                                                |
| float                      | 33.3 ms                                                                                                          | 31.8 ms: 1.05x faster                                                                                                |
| async_tree_none            | 120 ms                                                                                                           | 115 ms: 1.04x faster                                                                                                 |
| bpe_tokeniser              | 2.33 sec                                                                                                         | 2.24 sec: 1.04x faster                                                                                               |
| regex_effbot               | 1.89 ms                                                                                                          | 1.82 ms: 1.04x faster                                                                                                |
| thrift                     | 362 us                                                                                                           | 353 us: 1.03x faster                                                                                                 |
| meteor_contest             | 59.6 ms                                                                                                          | 58.1 ms: 1.03x faster                                                                                                |
| json                       | 2.27 ms                                                                                                          | 2.22 ms: 1.02x faster                                                                                                |
| logging_simple             | 2.59 us                                                                                                          | 2.52 us: 1.02x faster                                                                                                |
| sqlite_synth               | 1.13 us                                                                                                          | 1.10 us: 1.02x faster                                                                                                |
| xml_etree_iterparse        | 45.0 ms                                                                                                          | 44.1 ms: 1.02x faster                                                                                                |
| json_dumps                 | 4.49 ms                                                                                                          | 4.40 ms: 1.02x faster                                                                                                |
| logging_format             | 2.83 us                                                                                                          | 2.78 us: 1.02x faster                                                                                                |
| sqlglot_v2_parse           | 617 us                                                                                                           | 607 us: 1.02x faster                                                                                                 |
| crypto_pyaes               | 41.7 ms                                                                                                          | 41.1 ms: 1.02x faster                                                                                                |
| json_loads                 | 13.0 us                                                                                                          | 12.8 us: 1.02x faster                                                                                                |
| async_tree_io              | 271 ms                                                                                                           | 268 ms: 1.01x faster                                                                                                 |
| xml_etree_parse            | 72.8 ms                                                                                                          | 71.8 ms: 1.01x faster                                                                                                |
| typing_runtime_protocols   | 77.6 us                                                                                                          | 76.7 us: 1.01x faster                                                                                                |
| django_template            | 16.4 ms                                                                                                          | 16.2 ms: 1.01x faster                                                                                                |
| subparsers                 | 4.87 ms                                                                                                          | 4.82 ms: 1.01x faster                                                                                                |
| pathlib                    | 12.6 ms                                                                                                          | 12.5 ms: 1.01x faster                                                                                                |
| scimark_sparse_mat_mult    | 2.18 ms                                                                                                          | 2.17 ms: 1.01x faster                                                                                                |
| regex_v8                   | 12.8 ms                                                                                                          | 12.9 ms: 1.00x slower                                                                                                |
| asyncio_websockets         | 205 ms                                                                                                           | 206 ms: 1.00x slower                                                                                                 |
| sqlglot_v2_transpile       | 754 us                                                                                                           | 757 us: 1.00x slower                                                                                                 |
| regex_dna                  | 114 ms                                                                                                           | 115 ms: 1.01x slower                                                                                                 |
| bench_thread_pool          | 475 us                                                                                                           | 479 us: 1.01x slower                                                                                                 |
| unpickle                   | 7.27 us                                                                                                          | 7.32 us: 1.01x slower                                                                                                |
| pickle_list                | 2.38 us                                                                                                          | 2.40 us: 1.01x slower                                                                                                |
| async_tree_cpu_io_mixed_tg | 327 ms                                                                                                           | 330 ms: 1.01x slower                                                                                                 |
| go                         | 65.6 ms                                                                                                          | 66.3 ms: 1.01x slower                                                                                                |
| unpickle_list              | 2.33 us                                                                                                          | 2.35 us: 1.01x slower                                                                                                |
| pickle                     | 6.74 us                                                                                                          | 6.82 us: 1.01x slower                                                                                                |
| pycparser                  | 536 ms                                                                                                           | 546 ms: 1.02x slower                                                                                                 |
| logging_silent             | 49.1 ns                                                                                                          | 49.9 ns: 1.02x slower                                                                                                |
| html5lib                   | 25.3 ms                                                                                                          | 25.7 ms: 1.02x slower                                                                                                |
| pickle_dict                | 14.2 us                                                                                                          | 14.5 us: 1.02x slower                                                                                                |
| python_startup_no_site     | 7.27 ms                                                                                                          | 7.42 ms: 1.02x slower                                                                                                |
| pidigits                   | 212 ms                                                                                                           | 217 ms: 1.02x slower                                                                                                 |
| asyncio_tcp_ssl            | 649 ms                                                                                                           | 662 ms: 1.02x slower                                                                                                 |
| python_startup             | 10.2 ms                                                                                                          | 10.4 ms: 1.02x slower                                                                                                |
| nqueens                    | 46.7 ms                                                                                                          | 47.9 ms: 1.03x slower                                                                                                |
| 2to3                       | 133 ms                                                                                                           | 136 ms: 1.03x slower                                                                                                 |
| gc_traversal               | 2.46 ms                                                                                                          | 2.53 ms: 1.03x slower                                                                                                |
| bench_mp_pool              | 52.4 ms                                                                                                          | 53.9 ms: 1.03x slower                                                                                                |
| async_tree_io_tg           | 269 ms                                                                                                           | 277 ms: 1.03x slower                                                                                                 |
| create_gc_cycles           | 999 us                                                                                                           | 1.03 ms: 1.03x slower                                                                                                |
| sphinx                     | 460 ms                                                                                                           | 475 ms: 1.03x slower                                                                                                 |
| dulwich_log                | 21.2 ms                                                                                                          | 21.9 ms: 1.03x slower                                                                                                |
| docutils                   | 1.16 sec                                                                                                         | 1.21 sec: 1.04x slower                                                                                               |
| asyncio_tcp                | 162 ms                                                                                                           | 169 ms: 1.04x slower                                                                                                 |
| shortest_path              | 245 ms                                                                                                           | 255 ms: 1.04x slower                                                                                                 |
| many_optionals             | 337 us                                                                                                           | 351 us: 1.04x slower                                                                                                 |
| sqlglot_v2_normalize       | 54.5 ms                                                                                                          | 56.8 ms: 1.04x slower                                                                                                |
| chaos                      | 29.0 ms                                                                                                          | 30.4 ms: 1.05x slower                                                                                                |
| connected_components       | 227 ms                                                                                                           | 238 ms: 1.05x slower                                                                                                 |
| raytrace                   | 131 ms                                                                                                           | 137 ms: 1.05x slower                                                                                                 |
| spectral_norm              | 46.9 ms                                                                                                          | 49.2 ms: 1.05x slower                                                                                                |
| k_core                     | 980 ms                                                                                                           | 1.03 sec: 1.05x slower                                                                                               |
| sqlglot_v2_optimize        | 26.4 ms                                                                                                          | 28.0 ms: 1.06x slower                                                                                                |
| coverage                   | 36.3 ms                                                                                                          | 38.7 ms: 1.07x slower                                                                                                |
| sympy_expand               | 200 ms                                                                                                           | 213 ms: 1.07x slower                                                                                                 |
| async_generators           | 199 ms                                                                                                           | 214 ms: 1.07x slower                                                                                                 |
| djangocms                  | 4.90 us                                                                                                          | 5.31 us: 1.08x slower                                                                                                |
| scimark_lu                 | 50.8 ms                                                                                                          | 55.2 ms: 1.09x slower                                                                                                |
| hexiom                     | 3.35 ms                                                                                                          | 3.68 ms: 1.10x slower                                                                                                |
| sympy_sum                  | 63.6 ms                                                                                                          | 70.4 ms: 1.11x slower                                                                                                |
| coroutines                 | 12.3 ms                                                                                                          | 13.7 ms: 1.12x slower                                                                                                |
| sympy_str                  | 117 ms                                                                                                           | 132 ms: 1.12x slower                                                                                                 |
| generators                 | 20.2 ms                                                                                                          | 22.7 ms: 1.13x slower                                                                                                |
| sympy_integrate            | 8.51 ms                                                                                                          | 9.67 ms: 1.14x slower                                                                                                |
| mdp                        | 614 ms                                                                                                           | 712 ms: 1.16x slower                                                                                                 |
| pylint                     | 125 ms                                                                                                           | 145 ms: 1.16x slower                                                                                                 |
| unpack_sequence            | 35.8 ns                                                                                                          | 42.7 ns: 1.19x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.01x faster                                                                                                         |

Benchmark hidden because not significant (6): async_tree_none_tg, async_tree_memoization, deltablue, genshi_xml, async_tree_memoization_tg, async_tree_cpu_io_mixed

- Geometric mean (including insignificant results): 1.013x faster

# HPT report

- Reliability score: 65.35% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.02x