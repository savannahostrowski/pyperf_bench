# Results vs. base

- fork: python
- ref: c90863ac3dcbc5b0b8f9
- machine: darwin-arm64
- commit hash: c90863a
- commit date: 2025-12-12
- overall geometric mean: 1.095x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 134 ms                                                                                                           | 129 ms: 1.04x faster                                                                                                 |
| chameleon      | 7.56 ms                                                                                                          | 7.53 ms: 1.00x faster                                                                                                |
| html5lib       | 25.5 ms                                                                                                          | 24.2 ms: 1.05x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.02x faster                                                                                                         |

Benchmark hidden because not significant (2): sphinx, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 117 ms                                                                                                           | 110 ms: 1.06x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 329 ms                                                                                                           | 313 ms: 1.05x faster                                                                                                 |
| async_tree_memoization     | 154 ms                                                                                                           | 148 ms: 1.05x faster                                                                                                 |
| async_tree_io_tg           | 277 ms                                                                                                           | 265 ms: 1.04x faster                                                                                                 |
| async_tree_none_tg         | 117 ms                                                                                                           | 113 ms: 1.04x faster                                                                                                 |
| async_tree_io              | 269 ms                                                                                                           | 260 ms: 1.04x faster                                                                                                 |
| async_tree_cpu_io_mixed_tg | 329 ms                                                                                                           | 320 ms: 1.03x faster                                                                                                 |
| asyncio_tcp                | 168 ms                                                                                                           | 163 ms: 1.03x faster                                                                                                 |
| async_tree_memoization_tg  | 155 ms                                                                                                           | 152 ms: 1.02x faster                                                                                                 |
| asyncio_tcp_ssl            | 661 ms                                                                                                           | 651 ms: 1.02x faster                                                                                                 |
| asyncio_websockets         | 206 ms                                                                                                           | 205 ms: 1.00x faster                                                                                                 |
| async_generators           | 198 ms                                                                                                           | 207 ms: 1.05x slower                                                                                                 |
| coroutines                 | 12.3 ms                                                                                                          | 13.6 ms: 1.11x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.02x faster                                                                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| nbody          | 61.0 ms                                                                                                          | 42.7 ms: 1.43x faster                                                                                                |
| float          | 33.8 ms                                                                                                          | 27.0 ms: 1.25x faster                                                                                                |
| pidigits       | 218 ms                                                                                                           | 214 ms: 1.02x faster                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.22x faster                                                                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 56.0 ms                                                                                                          | 48.5 ms: 1.15x faster                                                                                                |
| regex_effbot   | 1.98 ms                                                                                                          | 1.87 ms: 1.06x faster                                                                                                |
| regex_dna      | 117 ms                                                                                                           | 116 ms: 1.00x faster                                                                                                 |
| regex_v8       | 12.8 ms                                                                                                          | 12.9 ms: 1.01x slower                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.05x faster                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 117 us                                                                                                           | 86.0 us: 1.36x faster                                                                                                |
| tomli_loads          | 1.23 sec                                                                                                         | 955 ms: 1.29x faster                                                                                                 |
| pickle_pure_python   | 170 us                                                                                                           | 133 us: 1.28x faster                                                                                                 |
| xml_etree_process    | 29.7 ms                                                                                                          | 24.7 ms: 1.20x faster                                                                                                |
| xml_etree_generate   | 41.6 ms                                                                                                          | 35.2 ms: 1.18x faster                                                                                                |
| json_dumps           | 4.51 ms                                                                                                          | 4.21 ms: 1.07x faster                                                                                                |
| xml_etree_iterparse  | 45.0 ms                                                                                                          | 43.2 ms: 1.04x faster                                                                                                |
| xml_etree_parse      | 73.0 ms                                                                                                          | 72.4 ms: 1.01x faster                                                                                                |
| pickle_dict          | 14.3 us                                                                                                          | 14.2 us: 1.00x faster                                                                                                |
| json_loads           | 12.7 us                                                                                                          | 12.7 us: 1.00x faster                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.09x faster                                                                                                         |

Benchmark hidden because not significant (4): pickle_list, pickle, unpickle, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 7.38 ms                                                                                                          | 7.33 ms: 1.01x faster                                                                                                |
| python_startup         | 10.2 ms                                                                                                          | 10.4 ms: 1.02x slower                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.01x slower                                                                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 6.07 ms                                                                                                          | 4.69 ms: 1.30x faster                                                                                                |
| genshi_text     | 12.3 ms                                                                                                          | 10.9 ms: 1.13x faster                                                                                                |
| django_template | 16.4 ms                                                                                                          | 15.1 ms: 1.08x faster                                                                                                |
| genshi_xml      | 26.2 ms                                                                                                          | 24.9 ms: 1.05x faster                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.14x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json | results/bm-20251212-3.15.0a2+-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                   | 25.4 ms                                                                                                          | 12.3 ms: 2.06x faster                                                                                                |
| richards_super             | 28.4 ms                                                                                                          | 14.8 ms: 1.92x faster                                                                                                |
| nbody                      | 61.0 ms                                                                                                          | 42.7 ms: 1.43x faster                                                                                                |
| unpickle_pure_python       | 117 us                                                                                                           | 86.0 us: 1.36x faster                                                                                                |
| scimark_monte_carlo        | 34.8 ms                                                                                                          | 25.6 ms: 1.36x faster                                                                                                |
| logging_silent             | 48.7 ns                                                                                                          | 37.1 ns: 1.31x faster                                                                                                |
| scimark_sor                | 62.3 ms                                                                                                          | 47.7 ms: 1.31x faster                                                                                                |
| scimark_fft                | 144 ms                                                                                                           | 111 ms: 1.30x faster                                                                                                 |
| mako                       | 6.07 ms                                                                                                          | 4.69 ms: 1.30x faster                                                                                                |
| tomli_loads                | 1.23 sec                                                                                                         | 955 ms: 1.29x faster                                                                                                 |
| deltablue                  | 1.74 ms                                                                                                          | 1.36 ms: 1.28x faster                                                                                                |
| pickle_pure_python         | 170 us                                                                                                           | 133 us: 1.28x faster                                                                                                 |
| pyflate                    | 229 ms                                                                                                           | 180 ms: 1.28x faster                                                                                                 |
| pprint_safe_repr           | 386 ms                                                                                                           | 304 ms: 1.27x faster                                                                                                 |
| pprint_pformat             | 780 ms                                                                                                           | 616 ms: 1.26x faster                                                                                                 |
| float                      | 33.8 ms                                                                                                          | 27.0 ms: 1.25x faster                                                                                                |
| deepcopy_memo              | 15.6 us                                                                                                          | 12.6 us: 1.24x faster                                                                                                |
| crypto_pyaes               | 41.9 ms                                                                                                          | 33.9 ms: 1.24x faster                                                                                                |
| fannkuch                   | 213 ms                                                                                                           | 177 ms: 1.20x faster                                                                                                 |
| xml_etree_process          | 29.7 ms                                                                                                          | 24.7 ms: 1.20x faster                                                                                                |
| go                         | 66.8 ms                                                                                                          | 56.1 ms: 1.19x faster                                                                                                |
| comprehensions             | 8.98 us                                                                                                          | 7.59 us: 1.18x faster                                                                                                |
| xml_etree_generate         | 41.6 ms                                                                                                          | 35.2 ms: 1.18x faster                                                                                                |
| regex_compile              | 56.0 ms                                                                                                          | 48.5 ms: 1.15x faster                                                                                                |
| sqlglot_v2_parse           | 618 us                                                                                                           | 546 us: 1.13x faster                                                                                                 |
| genshi_text                | 12.3 ms                                                                                                          | 10.9 ms: 1.13x faster                                                                                                |
| bpe_tokeniser              | 2.33 sec                                                                                                         | 2.07 sec: 1.12x faster                                                                                               |
| chaos                      | 28.9 ms                                                                                                          | 26.1 ms: 1.11x faster                                                                                                |
| deepcopy                   | 128 us                                                                                                           | 115 us: 1.11x faster                                                                                                 |
| meteor_contest             | 59.6 ms                                                                                                          | 54.4 ms: 1.10x faster                                                                                                |
| deepcopy_reduce            | 1.35 us                                                                                                          | 1.23 us: 1.10x faster                                                                                                |
| telco                      | 3.22 ms                                                                                                          | 2.95 ms: 1.09x faster                                                                                                |
| spectral_norm              | 46.4 ms                                                                                                          | 42.4 ms: 1.09x faster                                                                                                |
| sqlglot_v2_transpile       | 751 us                                                                                                           | 693 us: 1.08x faster                                                                                                 |
| hexiom                     | 3.38 ms                                                                                                          | 3.12 ms: 1.08x faster                                                                                                |
| django_template            | 16.4 ms                                                                                                          | 15.1 ms: 1.08x faster                                                                                                |
| nqueens                    | 46.4 ms                                                                                                          | 43.0 ms: 1.08x faster                                                                                                |
| logging_simple             | 2.62 us                                                                                                          | 2.44 us: 1.07x faster                                                                                                |
| json_dumps                 | 4.51 ms                                                                                                          | 4.21 ms: 1.07x faster                                                                                                |
| logging_format             | 2.88 us                                                                                                          | 2.70 us: 1.07x faster                                                                                                |
| async_tree_none            | 117 ms                                                                                                           | 110 ms: 1.06x faster                                                                                                 |
| thrift                     | 359 us                                                                                                           | 338 us: 1.06x faster                                                                                                 |
| subparsers                 | 4.91 ms                                                                                                          | 4.63 ms: 1.06x faster                                                                                                |
| scimark_lu                 | 51.1 ms                                                                                                          | 48.2 ms: 1.06x faster                                                                                                |
| regex_effbot               | 1.98 ms                                                                                                          | 1.87 ms: 1.06x faster                                                                                                |
| raytrace                   | 132 ms                                                                                                           | 125 ms: 1.05x faster                                                                                                 |
| genshi_xml                 | 26.2 ms                                                                                                          | 24.9 ms: 1.05x faster                                                                                                |
| html5lib                   | 25.5 ms                                                                                                          | 24.2 ms: 1.05x faster                                                                                                |
| async_tree_cpu_io_mixed    | 329 ms                                                                                                           | 313 ms: 1.05x faster                                                                                                 |
| pycparser                  | 537 ms                                                                                                           | 512 ms: 1.05x faster                                                                                                 |
| json                       | 2.27 ms                                                                                                          | 2.17 ms: 1.05x faster                                                                                                |
| async_tree_memoization     | 154 ms                                                                                                           | 148 ms: 1.05x faster                                                                                                 |
| async_tree_io_tg           | 277 ms                                                                                                           | 265 ms: 1.04x faster                                                                                                 |
| many_optionals             | 348 us                                                                                                           | 334 us: 1.04x faster                                                                                                 |
| xml_etree_iterparse        | 45.0 ms                                                                                                          | 43.2 ms: 1.04x faster                                                                                                |
| 2to3                       | 134 ms                                                                                                           | 129 ms: 1.04x faster                                                                                                 |
| scimark_sparse_mat_mult    | 2.16 ms                                                                                                          | 2.08 ms: 1.04x faster                                                                                                |
| async_tree_none_tg         | 117 ms                                                                                                           | 113 ms: 1.04x faster                                                                                                 |
| async_tree_io              | 269 ms                                                                                                           | 260 ms: 1.04x faster                                                                                                 |
| k_core                     | 989 ms                                                                                                           | 959 ms: 1.03x faster                                                                                                 |
| typing_runtime_protocols   | 76.4 us                                                                                                          | 74.2 us: 1.03x faster                                                                                                |
| async_tree_cpu_io_mixed_tg | 329 ms                                                                                                           | 320 ms: 1.03x faster                                                                                                 |
| asyncio_tcp                | 168 ms                                                                                                           | 163 ms: 1.03x faster                                                                                                 |
| sqlalchemy_imperative      | 5.86 ms                                                                                                          | 5.71 ms: 1.03x faster                                                                                                |
| pidigits                   | 218 ms                                                                                                           | 214 ms: 1.02x faster                                                                                                 |
| async_tree_memoization_tg  | 155 ms                                                                                                           | 152 ms: 1.02x faster                                                                                                 |
| gc_traversal               | 2.52 ms                                                                                                          | 2.48 ms: 1.02x faster                                                                                                |
| asyncio_tcp_ssl            | 661 ms                                                                                                           | 651 ms: 1.02x faster                                                                                                 |
| pathlib                    | 12.6 ms                                                                                                          | 12.5 ms: 1.01x faster                                                                                                |
| bench_thread_pool          | 475 us                                                                                                           | 470 us: 1.01x faster                                                                                                 |
| sqlite_synth               | 1.12 us                                                                                                          | 1.11 us: 1.01x faster                                                                                                |
| create_gc_cycles           | 1.03 ms                                                                                                          | 1.02 ms: 1.01x faster                                                                                                |
| xml_etree_parse            | 73.0 ms                                                                                                          | 72.4 ms: 1.01x faster                                                                                                |
| python_startup_no_site     | 7.38 ms                                                                                                          | 7.33 ms: 1.01x faster                                                                                                |
| regex_dna                  | 117 ms                                                                                                           | 116 ms: 1.00x faster                                                                                                 |
| chameleon                  | 7.56 ms                                                                                                          | 7.53 ms: 1.00x faster                                                                                                |
| pickle_dict                | 14.3 us                                                                                                          | 14.2 us: 1.00x faster                                                                                                |
| json_loads                 | 12.7 us                                                                                                          | 12.7 us: 1.00x faster                                                                                                |
| asyncio_websockets         | 206 ms                                                                                                           | 205 ms: 1.00x faster                                                                                                 |
| connected_components       | 227 ms                                                                                                           | 229 ms: 1.01x slower                                                                                                 |
| shortest_path              | 246 ms                                                                                                           | 248 ms: 1.01x slower                                                                                                 |
| regex_v8                   | 12.8 ms                                                                                                          | 12.9 ms: 1.01x slower                                                                                                |
| sqlalchemy_declarative     | 50.3 ms                                                                                                          | 50.9 ms: 1.01x slower                                                                                                |
| sqlglot_v2_normalize       | 54.5 ms                                                                                                          | 55.2 ms: 1.01x slower                                                                                                |
| python_startup             | 10.2 ms                                                                                                          | 10.4 ms: 1.02x slower                                                                                                |
| sqlglot_v2_optimize        | 26.4 ms                                                                                                          | 27.1 ms: 1.02x slower                                                                                                |
| coverage                   | 36.6 ms                                                                                                          | 37.7 ms: 1.03x slower                                                                                                |
| djangocms                  | 4.85 us                                                                                                          | 5.01 us: 1.03x slower                                                                                                |
| generators                 | 20.0 ms                                                                                                          | 20.7 ms: 1.03x slower                                                                                                |
| async_generators           | 198 ms                                                                                                           | 207 ms: 1.05x slower                                                                                                 |
| pylint                     | 131 ms                                                                                                           | 140 ms: 1.06x slower                                                                                                 |
| coroutines                 | 12.3 ms                                                                                                          | 13.6 ms: 1.11x slower                                                                                                |
| mdp                        | 615 ms                                                                                                           | 684 ms: 1.11x slower                                                                                                 |
| unpack_sequence            | 36.2 ns                                                                                                          | 40.6 ns: 1.12x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.09x faster                                                                                                         |

Benchmark hidden because not significant (9): xdsl_constant_fold, bench_mp_pool, sphinx, dulwich_log, pickle_list, pickle, unpickle, unpickle_list, tornado_http
Ignored benchmarks (5) of results/bm-20251212-3.15.0a2+-c90863a/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2+-c90863a.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.095x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.03x

# Memory
- memory change: 1.03x