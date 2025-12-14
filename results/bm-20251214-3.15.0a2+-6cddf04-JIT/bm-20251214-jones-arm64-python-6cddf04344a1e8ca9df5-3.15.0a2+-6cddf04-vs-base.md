# Results vs. base

- fork: python
- ref: 6cddf04344a1e8ca9df5
- machine: darwin-arm64
- commit hash: 6cddf04
- commit date: 2025-12-14
- overall geometric mean: 1.092x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 135 ms                                                                                                           | 132 ms: 1.02x faster                                                                                                 |
| chameleon      | 7.60 ms                                                                                                          | 7.63 ms: 1.00x slower                                                                                                |
| html5lib       | 25.7 ms                                                                                                          | 24.0 ms: 1.07x faster                                                                                                |
| sphinx         | 464 ms                                                                                                           | 461 ms: 1.01x faster                                                                                                 |
| tornado_http   | 52.2 ms                                                                                                          | 51.5 ms: 1.01x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.02x faster                                                                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 118 ms                                                                                                           | 111 ms: 1.07x faster                                                                                                 |
| async_tree_memoization     | 156 ms                                                                                                           | 148 ms: 1.05x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 329 ms                                                                                                           | 317 ms: 1.04x faster                                                                                                 |
| async_tree_io              | 271 ms                                                                                                           | 261 ms: 1.04x faster                                                                                                 |
| async_tree_io_tg           | 277 ms                                                                                                           | 268 ms: 1.03x faster                                                                                                 |
| asyncio_tcp                | 169 ms                                                                                                           | 164 ms: 1.03x faster                                                                                                 |
| asyncio_tcp_ssl            | 663 ms                                                                                                           | 650 ms: 1.02x faster                                                                                                 |
| async_tree_memoization_tg  | 155 ms                                                                                                           | 153 ms: 1.02x faster                                                                                                 |
| async_tree_cpu_io_mixed_tg | 329 ms                                                                                                           | 324 ms: 1.02x faster                                                                                                 |
| asyncio_websockets         | 205 ms                                                                                                           | 205 ms: 1.00x faster                                                                                                 |
| async_generators           | 198 ms                                                                                                           | 208 ms: 1.05x slower                                                                                                 |
| coroutines                 | 12.4 ms                                                                                                          | 13.9 ms: 1.12x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.01x faster                                                                                                         |

Benchmark hidden because not significant (1): async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| nbody          | 61.3 ms                                                                                                          | 42.7 ms: 1.43x faster                                                                                                |
| float          | 34.1 ms                                                                                                          | 27.0 ms: 1.26x faster                                                                                                |
| pidigits       | 221 ms                                                                                                           | 217 ms: 1.02x faster                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.23x faster                                                                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 56.9 ms                                                                                                          | 48.4 ms: 1.17x faster                                                                                                |
| regex_effbot   | 1.97 ms                                                                                                          | 1.85 ms: 1.07x faster                                                                                                |
| regex_dna      | 117 ms                                                                                                           | 115 ms: 1.02x faster                                                                                                 |
| regex_v8       | 12.9 ms                                                                                                          | 12.7 ms: 1.01x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.07x faster                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 118 us                                                                                                           | 85.2 us: 1.38x faster                                                                                                |
| tomli_loads          | 1.24 sec                                                                                                         | 953 ms: 1.30x faster                                                                                                 |
| pickle_pure_python   | 172 us                                                                                                           | 134 us: 1.28x faster                                                                                                 |
| xml_etree_process    | 29.7 ms                                                                                                          | 24.8 ms: 1.20x faster                                                                                                |
| xml_etree_generate   | 41.6 ms                                                                                                          | 35.3 ms: 1.18x faster                                                                                                |
| json_dumps           | 4.57 ms                                                                                                          | 4.18 ms: 1.09x faster                                                                                                |
| xml_etree_iterparse  | 44.8 ms                                                                                                          | 43.3 ms: 1.04x faster                                                                                                |
| unpickle_list        | 2.34 us                                                                                                          | 2.30 us: 1.02x faster                                                                                                |
| xml_etree_parse      | 73.0 ms                                                                                                          | 71.9 ms: 1.02x faster                                                                                                |
| pickle               | 6.77 us                                                                                                          | 6.70 us: 1.01x faster                                                                                                |
| pickle_dict          | 14.3 us                                                                                                          | 14.2 us: 1.01x faster                                                                                                |
| pickle_list          | 2.35 us                                                                                                          | 2.33 us: 1.01x faster                                                                                                |
| unpickle             | 7.24 us                                                                                                          | 7.30 us: 1.01x slower                                                                                                |
| json_loads           | 12.7 us                                                                                                          | 12.8 us: 1.01x slower                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.10x faster                                                                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 7.41 ms                                                                                                          | 7.33 ms: 1.01x faster                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.01x faster                                                                                                         |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 6.03 ms                                                                                                          | 4.72 ms: 1.28x faster                                                                                                |
| genshi_text     | 12.3 ms                                                                                                          | 10.5 ms: 1.18x faster                                                                                                |
| django_template | 16.5 ms                                                                                                          | 15.3 ms: 1.08x faster                                                                                                |
| genshi_xml      | 26.4 ms                                                                                                          | 24.7 ms: 1.07x faster                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.15x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                   | 25.3 ms                                                                                                          | 12.3 ms: 2.05x faster                                                                                                |
| richards_super             | 28.4 ms                                                                                                          | 14.4 ms: 1.98x faster                                                                                                |
| nbody                      | 61.3 ms                                                                                                          | 42.7 ms: 1.43x faster                                                                                                |
| unpickle_pure_python       | 118 us                                                                                                           | 85.2 us: 1.38x faster                                                                                                |
| scimark_monte_carlo        | 34.9 ms                                                                                                          | 25.6 ms: 1.36x faster                                                                                                |
| scimark_sor                | 64.0 ms                                                                                                          | 47.5 ms: 1.35x faster                                                                                                |
| logging_silent             | 49.3 ns                                                                                                          | 37.0 ns: 1.33x faster                                                                                                |
| tomli_loads                | 1.24 sec                                                                                                         | 953 ms: 1.30x faster                                                                                                 |
| scimark_fft                | 146 ms                                                                                                           | 112 ms: 1.30x faster                                                                                                 |
| pprint_safe_repr           | 393 ms                                                                                                           | 303 ms: 1.30x faster                                                                                                 |
| pprint_pformat             | 798 ms                                                                                                           | 620 ms: 1.29x faster                                                                                                 |
| deltablue                  | 1.75 ms                                                                                                          | 1.37 ms: 1.28x faster                                                                                                |
| pickle_pure_python         | 172 us                                                                                                           | 134 us: 1.28x faster                                                                                                 |
| mako                       | 6.03 ms                                                                                                          | 4.72 ms: 1.28x faster                                                                                                |
| pyflate                    | 229 ms                                                                                                           | 181 ms: 1.27x faster                                                                                                 |
| float                      | 34.1 ms                                                                                                          | 27.0 ms: 1.26x faster                                                                                                |
| crypto_pyaes               | 41.8 ms                                                                                                          | 33.9 ms: 1.23x faster                                                                                                |
| comprehensions             | 9.08 us                                                                                                          | 7.36 us: 1.23x faster                                                                                                |
| deepcopy_memo              | 15.7 us                                                                                                          | 12.7 us: 1.23x faster                                                                                                |
| fannkuch                   | 217 ms                                                                                                           | 178 ms: 1.22x faster                                                                                                 |
| xml_etree_process          | 29.7 ms                                                                                                          | 24.8 ms: 1.20x faster                                                                                                |
| go                         | 66.9 ms                                                                                                          | 56.2 ms: 1.19x faster                                                                                                |
| xml_etree_generate         | 41.6 ms                                                                                                          | 35.3 ms: 1.18x faster                                                                                                |
| genshi_text                | 12.3 ms                                                                                                          | 10.5 ms: 1.18x faster                                                                                                |
| regex_compile              | 56.9 ms                                                                                                          | 48.4 ms: 1.17x faster                                                                                                |
| deepcopy                   | 129 us                                                                                                           | 112 us: 1.15x faster                                                                                                 |
| sqlglot_v2_parse           | 624 us                                                                                                           | 548 us: 1.14x faster                                                                                                 |
| bpe_tokeniser              | 2.35 sec                                                                                                         | 2.08 sec: 1.13x faster                                                                                               |
| chaos                      | 29.3 ms                                                                                                          | 25.9 ms: 1.13x faster                                                                                                |
| scimark_lu                 | 54.0 ms                                                                                                          | 48.2 ms: 1.12x faster                                                                                                |
| meteor_contest             | 58.8 ms                                                                                                          | 53.0 ms: 1.11x faster                                                                                                |
| spectral_norm              | 46.8 ms                                                                                                          | 42.4 ms: 1.10x faster                                                                                                |
| deepcopy_reduce            | 1.35 us                                                                                                          | 1.23 us: 1.10x faster                                                                                                |
| telco                      | 3.21 ms                                                                                                          | 2.93 ms: 1.09x faster                                                                                                |
| json_dumps                 | 4.57 ms                                                                                                          | 4.18 ms: 1.09x faster                                                                                                |
| sqlglot_v2_transpile       | 756 us                                                                                                           | 695 us: 1.09x faster                                                                                                 |
| hexiom                     | 3.39 ms                                                                                                          | 3.12 ms: 1.09x faster                                                                                                |
| nqueens                    | 46.6 ms                                                                                                          | 42.9 ms: 1.09x faster                                                                                                |
| django_template            | 16.5 ms                                                                                                          | 15.3 ms: 1.08x faster                                                                                                |
| logging_simple             | 2.63 us                                                                                                          | 2.44 us: 1.08x faster                                                                                                |
| genshi_xml                 | 26.4 ms                                                                                                          | 24.7 ms: 1.07x faster                                                                                                |
| async_tree_none            | 118 ms                                                                                                           | 111 ms: 1.07x faster                                                                                                 |
| html5lib                   | 25.7 ms                                                                                                          | 24.0 ms: 1.07x faster                                                                                                |
| regex_effbot               | 1.97 ms                                                                                                          | 1.85 ms: 1.07x faster                                                                                                |
| subparsers                 | 4.93 ms                                                                                                          | 4.64 ms: 1.06x faster                                                                                                |
| logging_format             | 2.87 us                                                                                                          | 2.72 us: 1.06x faster                                                                                                |
| pycparser                  | 538 ms                                                                                                           | 513 ms: 1.05x faster                                                                                                 |
| raytrace                   | 132 ms                                                                                                           | 126 ms: 1.05x faster                                                                                                 |
| async_tree_memoization     | 156 ms                                                                                                           | 148 ms: 1.05x faster                                                                                                 |
| scimark_sparse_mat_mult    | 2.17 ms                                                                                                          | 2.09 ms: 1.04x faster                                                                                                |
| many_optionals             | 350 us                                                                                                           | 336 us: 1.04x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 329 ms                                                                                                           | 317 ms: 1.04x faster                                                                                                 |
| async_tree_io              | 271 ms                                                                                                           | 261 ms: 1.04x faster                                                                                                 |
| xml_etree_iterparse        | 44.8 ms                                                                                                          | 43.3 ms: 1.04x faster                                                                                                |
| typing_runtime_protocols   | 77.1 us                                                                                                          | 74.4 us: 1.04x faster                                                                                                |
| async_tree_io_tg           | 277 ms                                                                                                           | 268 ms: 1.03x faster                                                                                                 |
| thrift                     | 356 us                                                                                                           | 344 us: 1.03x faster                                                                                                 |
| asyncio_tcp                | 169 ms                                                                                                           | 164 ms: 1.03x faster                                                                                                 |
| k_core                     | 990 ms                                                                                                           | 961 ms: 1.03x faster                                                                                                 |
| json                       | 2.25 ms                                                                                                          | 2.19 ms: 1.03x faster                                                                                                |
| shortest_path              | 246 ms                                                                                                           | 240 ms: 1.02x faster                                                                                                 |
| 2to3                       | 135 ms                                                                                                           | 132 ms: 1.02x faster                                                                                                 |
| regex_dna                  | 117 ms                                                                                                           | 115 ms: 1.02x faster                                                                                                 |
| gc_traversal               | 2.52 ms                                                                                                          | 2.46 ms: 1.02x faster                                                                                                |
| unpickle_list              | 2.34 us                                                                                                          | 2.30 us: 1.02x faster                                                                                                |
| bench_thread_pool          | 477 us                                                                                                           | 468 us: 1.02x faster                                                                                                 |
| asyncio_tcp_ssl            | 663 ms                                                                                                           | 650 ms: 1.02x faster                                                                                                 |
| create_gc_cycles           | 1.02 ms                                                                                                          | 1.01 ms: 1.02x faster                                                                                                |
| connected_components       | 226 ms                                                                                                           | 222 ms: 1.02x faster                                                                                                 |
| sqlalchemy_imperative      | 5.84 ms                                                                                                          | 5.74 ms: 1.02x faster                                                                                                |
| async_tree_memoization_tg  | 155 ms                                                                                                           | 153 ms: 1.02x faster                                                                                                 |
| pidigits                   | 221 ms                                                                                                           | 217 ms: 1.02x faster                                                                                                 |
| xml_etree_parse            | 73.0 ms                                                                                                          | 71.9 ms: 1.02x faster                                                                                                |
| async_tree_cpu_io_mixed_tg | 329 ms                                                                                                           | 324 ms: 1.02x faster                                                                                                 |
| regex_v8                   | 12.9 ms                                                                                                          | 12.7 ms: 1.01x faster                                                                                                |
| tornado_http               | 52.2 ms                                                                                                          | 51.5 ms: 1.01x faster                                                                                                |
| python_startup_no_site     | 7.41 ms                                                                                                          | 7.33 ms: 1.01x faster                                                                                                |
| bench_mp_pool              | 53.2 ms                                                                                                          | 52.6 ms: 1.01x faster                                                                                                |
| pickle                     | 6.77 us                                                                                                          | 6.70 us: 1.01x faster                                                                                                |
| sqlite_synth               | 1.12 us                                                                                                          | 1.11 us: 1.01x faster                                                                                                |
| pickle_dict                | 14.3 us                                                                                                          | 14.2 us: 1.01x faster                                                                                                |
| pathlib                    | 12.6 ms                                                                                                          | 12.5 ms: 1.01x faster                                                                                                |
| sphinx                     | 464 ms                                                                                                           | 461 ms: 1.01x faster                                                                                                 |
| pickle_list                | 2.35 us                                                                                                          | 2.33 us: 1.01x faster                                                                                                |
| xdsl_constant_fold         | 18.3 ms                                                                                                          | 18.2 ms: 1.00x faster                                                                                                |
| asyncio_websockets         | 205 ms                                                                                                           | 205 ms: 1.00x faster                                                                                                 |
| sqlalchemy_declarative     | 50.5 ms                                                                                                          | 50.7 ms: 1.00x slower                                                                                                |
| chameleon                  | 7.60 ms                                                                                                          | 7.63 ms: 1.00x slower                                                                                                |
| unpickle                   | 7.24 us                                                                                                          | 7.30 us: 1.01x slower                                                                                                |
| json_loads                 | 12.7 us                                                                                                          | 12.8 us: 1.01x slower                                                                                                |
| sqlglot_v2_normalize       | 54.6 ms                                                                                                          | 55.1 ms: 1.01x slower                                                                                                |
| sqlglot_v2_optimize        | 26.6 ms                                                                                                          | 26.9 ms: 1.01x slower                                                                                                |
| generators                 | 20.0 ms                                                                                                          | 20.5 ms: 1.02x slower                                                                                                |
| djangocms                  | 4.77 us                                                                                                          | 4.96 us: 1.04x slower                                                                                                |
| coverage                   | 36.8 ms                                                                                                          | 38.2 ms: 1.04x slower                                                                                                |
| async_generators           | 198 ms                                                                                                           | 208 ms: 1.05x slower                                                                                                 |
| pylint                     | 132 ms                                                                                                           | 140 ms: 1.06x slower                                                                                                 |
| mdp                        | 613 ms                                                                                                           | 686 ms: 1.12x slower                                                                                                 |
| coroutines                 | 12.4 ms                                                                                                          | 13.9 ms: 1.12x slower                                                                                                |
| unpack_sequence            | 36.2 ns                                                                                                          | 41.3 ns: 1.14x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.09x faster                                                                                                         |

Benchmark hidden because not significant (3): async_tree_none_tg, python_startup, dulwich_log
Ignored benchmarks (5) of results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-jones-arm64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.092x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x

# Memory
- memory change: 1.02x