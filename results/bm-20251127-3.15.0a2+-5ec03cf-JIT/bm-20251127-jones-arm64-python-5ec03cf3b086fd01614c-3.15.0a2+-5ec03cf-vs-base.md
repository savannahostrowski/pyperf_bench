# Results vs. base

- fork: python
- ref: 5ec03cf3b086fd01614c
- machine: darwin-arm64
- commit hash: 5ec03cf
- commit date: 2025-11-27
- overall geometric mean: 1.075x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 153 ms                                                                                                           | 149 ms: 1.03x faster                                                                                                 |
| html5lib       | 28.2 ms                                                                                                          | 27.9 ms: 1.01x faster                                                                                                |
| sphinx         | 526 ms                                                                                                           | 519 ms: 1.01x faster                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.01x faster                                                                                                         |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 144 ms                                                                                                           | 128 ms: 1.13x faster                                                                                                 |
| async_tree_none_tg         | 138 ms                                                                                                           | 129 ms: 1.07x faster                                                                                                 |
| async_tree_memoization     | 172 ms                                                                                                           | 164 ms: 1.05x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 355 ms                                                                                                           | 340 ms: 1.04x faster                                                                                                 |
| async_tree_io              | 309 ms                                                                                                           | 297 ms: 1.04x faster                                                                                                 |
| async_tree_cpu_io_mixed_tg | 353 ms                                                                                                           | 343 ms: 1.03x faster                                                                                                 |
| async_tree_io_tg           | 306 ms                                                                                                           | 299 ms: 1.02x faster                                                                                                 |
| async_tree_memoization_tg  | 170 ms                                                                                                           | 168 ms: 1.01x faster                                                                                                 |
| asyncio_tcp_ssl            | 903 ms                                                                                                           | 894 ms: 1.01x faster                                                                                                 |
| coroutines                 | 14.1 ms                                                                                                          | 14.0 ms: 1.01x faster                                                                                                |
| async_generators           | 220 ms                                                                                                           | 229 ms: 1.04x slower                                                                                                 |
| Geometric mean             | (ref)                                                                                                            | 1.02x faster                                                                                                         |

Benchmark hidden because not significant (2): asyncio_websockets, asyncio_tcp

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| float          | 41.5 ms                                                                                                          | 33.4 ms: 1.24x faster                                                                                                |
| nbody          | 70.0 ms                                                                                                          | 57.7 ms: 1.21x faster                                                                                                |
| pidigits       | 237 ms                                                                                                           | 236 ms: 1.00x faster                                                                                                 |
| Geometric mean | (ref)                                                                                                            | 1.15x faster                                                                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 65.8 ms                                                                                                          | 57.3 ms: 1.15x faster                                                                                                |
| regex_effbot   | 2.05 ms                                                                                                          | 1.92 ms: 1.07x faster                                                                                                |
| regex_dna      | 126 ms                                                                                                           | 124 ms: 1.02x faster                                                                                                 |
| regex_v8       | 13.6 ms                                                                                                          | 13.5 ms: 1.01x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.06x faster                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 141 us                                                                                                           | 109 us: 1.29x faster                                                                                                 |
| tomli_loads          | 1.31 sec                                                                                                         | 1.02 sec: 1.28x faster                                                                                               |
| pickle_pure_python   | 194 us                                                                                                           | 156 us: 1.24x faster                                                                                                 |
| xml_etree_process    | 33.9 ms                                                                                                          | 28.5 ms: 1.19x faster                                                                                                |
| xml_etree_generate   | 47.0 ms                                                                                                          | 39.7 ms: 1.19x faster                                                                                                |
| xml_etree_iterparse  | 52.2 ms                                                                                                          | 47.4 ms: 1.10x faster                                                                                                |
| json_dumps           | 4.80 ms                                                                                                          | 4.51 ms: 1.07x faster                                                                                                |
| xml_etree_parse      | 78.2 ms                                                                                                          | 76.1 ms: 1.03x faster                                                                                                |
| pickle               | 7.12 us                                                                                                          | 7.06 us: 1.01x faster                                                                                                |
| json_loads           | 13.4 us                                                                                                          | 13.3 us: 1.01x faster                                                                                                |
| unpickle_list        | 2.35 us                                                                                                          | 2.36 us: 1.01x slower                                                                                                |
| unpickle             | 7.56 us                                                                                                          | 7.63 us: 1.01x slower                                                                                                |
| pickle_list          | 2.46 us                                                                                                          | 2.49 us: 1.01x slower                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.09x faster                                                                                                         |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 8.43 ms                                                                                                          | 8.98 ms: 1.06x slower                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.03x slower                                                                                                         |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 7.02 ms                                                                                                          | 5.57 ms: 1.26x faster                                                                                                |
| genshi_text     | 13.8 ms                                                                                                          | 12.3 ms: 1.12x faster                                                                                                |
| genshi_xml      | 29.3 ms                                                                                                          | 27.6 ms: 1.06x faster                                                                                                |
| django_template | 18.4 ms                                                                                                          | 17.8 ms: 1.03x faster                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.11x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json | results/bm-20251127-3.15.0a2+-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                   | 28.4 ms                                                                                                          | 16.6 ms: 1.72x faster                                                                                                |
| richards_super             | 31.9 ms                                                                                                          | 19.1 ms: 1.67x faster                                                                                                |
| deepcopy_memo              | 19.2 us                                                                                                          | 13.4 us: 1.43x faster                                                                                                |
| pprint_safe_repr           | 451 ms                                                                                                           | 345 ms: 1.31x faster                                                                                                 |
| logging_silent             | 64.5 ns                                                                                                          | 49.6 ns: 1.30x faster                                                                                                |
| pprint_pformat             | 909 ms                                                                                                           | 700 ms: 1.30x faster                                                                                                 |
| unpickle_pure_python       | 141 us                                                                                                           | 109 us: 1.29x faster                                                                                                 |
| scimark_sor                | 74.0 ms                                                                                                          | 57.4 ms: 1.29x faster                                                                                                |
| tomli_loads                | 1.31 sec                                                                                                         | 1.02 sec: 1.28x faster                                                                                               |
| scimark_monte_carlo        | 40.3 ms                                                                                                          | 31.6 ms: 1.27x faster                                                                                                |
| mako                       | 7.02 ms                                                                                                          | 5.57 ms: 1.26x faster                                                                                                |
| float                      | 41.5 ms                                                                                                          | 33.4 ms: 1.24x faster                                                                                                |
| pickle_pure_python         | 194 us                                                                                                           | 156 us: 1.24x faster                                                                                                 |
| fannkuch                   | 247 ms                                                                                                           | 201 ms: 1.23x faster                                                                                                 |
| nbody                      | 70.0 ms                                                                                                          | 57.7 ms: 1.21x faster                                                                                                |
| scimark_fft                | 159 ms                                                                                                           | 132 ms: 1.20x faster                                                                                                 |
| deepcopy                   | 148 us                                                                                                           | 124 us: 1.20x faster                                                                                                 |
| xml_etree_process          | 33.9 ms                                                                                                          | 28.5 ms: 1.19x faster                                                                                                |
| xml_etree_generate         | 47.0 ms                                                                                                          | 39.7 ms: 1.19x faster                                                                                                |
| comprehensions             | 10.6 us                                                                                                          | 8.93 us: 1.18x faster                                                                                                |
| pyflate                    | 275 ms                                                                                                           | 233 ms: 1.18x faster                                                                                                 |
| deltablue                  | 2.13 ms                                                                                                          | 1.85 ms: 1.15x faster                                                                                                |
| regex_compile              | 65.8 ms                                                                                                          | 57.3 ms: 1.15x faster                                                                                                |
| deepcopy_reduce            | 1.53 us                                                                                                          | 1.35 us: 1.13x faster                                                                                                |
| async_tree_none            | 144 ms                                                                                                           | 128 ms: 1.13x faster                                                                                                 |
| go                         | 78.1 ms                                                                                                          | 69.6 ms: 1.12x faster                                                                                                |
| genshi_text                | 13.8 ms                                                                                                          | 12.3 ms: 1.12x faster                                                                                                |
| sqlglot_v2_parse           | 727 us                                                                                                           | 651 us: 1.12x faster                                                                                                 |
| scimark_lu                 | 65.2 ms                                                                                                          | 58.5 ms: 1.12x faster                                                                                                |
| bpe_tokeniser              | 2.62 sec                                                                                                         | 2.37 sec: 1.11x faster                                                                                               |
| xml_etree_iterparse        | 52.2 ms                                                                                                          | 47.4 ms: 1.10x faster                                                                                                |
| sqlglot_v2_transpile       | 877 us                                                                                                           | 805 us: 1.09x faster                                                                                                 |
| meteor_contest             | 66.5 ms                                                                                                          | 61.2 ms: 1.09x faster                                                                                                |
| hexiom                     | 4.15 ms                                                                                                          | 3.86 ms: 1.07x faster                                                                                                |
| async_tree_none_tg         | 138 ms                                                                                                           | 129 ms: 1.07x faster                                                                                                 |
| crypto_pyaes               | 45.8 ms                                                                                                          | 42.9 ms: 1.07x faster                                                                                                |
| regex_effbot               | 2.05 ms                                                                                                          | 1.92 ms: 1.07x faster                                                                                                |
| json_dumps                 | 4.80 ms                                                                                                          | 4.51 ms: 1.07x faster                                                                                                |
| telco                      | 3.43 ms                                                                                                          | 3.22 ms: 1.06x faster                                                                                                |
| genshi_xml                 | 29.3 ms                                                                                                          | 27.6 ms: 1.06x faster                                                                                                |
| typing_runtime_protocols   | 86.7 us                                                                                                          | 81.7 us: 1.06x faster                                                                                                |
| nqueens                    | 52.7 ms                                                                                                          | 49.8 ms: 1.06x faster                                                                                                |
| logging_simple             | 2.93 us                                                                                                          | 2.76 us: 1.06x faster                                                                                                |
| logging_format             | 3.19 us                                                                                                          | 3.03 us: 1.05x faster                                                                                                |
| async_tree_memoization     | 172 ms                                                                                                           | 164 ms: 1.05x faster                                                                                                 |
| thrift                     | 388 us                                                                                                           | 372 us: 1.04x faster                                                                                                 |
| sqlite_synth               | 1.20 us                                                                                                          | 1.15 us: 1.04x faster                                                                                                |
| async_tree_cpu_io_mixed    | 355 ms                                                                                                           | 340 ms: 1.04x faster                                                                                                 |
| async_tree_io              | 309 ms                                                                                                           | 297 ms: 1.04x faster                                                                                                 |
| chaos                      | 33.9 ms                                                                                                          | 32.6 ms: 1.04x faster                                                                                                |
| generators                 | 22.7 ms                                                                                                          | 22.0 ms: 1.03x faster                                                                                                |
| django_template            | 18.4 ms                                                                                                          | 17.8 ms: 1.03x faster                                                                                                |
| async_tree_cpu_io_mixed_tg | 353 ms                                                                                                           | 343 ms: 1.03x faster                                                                                                 |
| xml_etree_parse            | 78.2 ms                                                                                                          | 76.1 ms: 1.03x faster                                                                                                |
| spectral_norm              | 52.9 ms                                                                                                          | 51.6 ms: 1.03x faster                                                                                                |
| 2to3                       | 153 ms                                                                                                           | 149 ms: 1.03x faster                                                                                                 |
| raytrace                   | 151 ms                                                                                                           | 148 ms: 1.02x faster                                                                                                 |
| bench_thread_pool          | 512 us                                                                                                           | 500 us: 1.02x faster                                                                                                 |
| async_tree_io_tg           | 306 ms                                                                                                           | 299 ms: 1.02x faster                                                                                                 |
| json                       | 2.35 ms                                                                                                          | 2.31 ms: 1.02x faster                                                                                                |
| pathlib                    | 14.2 ms                                                                                                          | 13.9 ms: 1.02x faster                                                                                                |
| regex_dna                  | 126 ms                                                                                                           | 124 ms: 1.02x faster                                                                                                 |
| html5lib                   | 28.2 ms                                                                                                          | 27.9 ms: 1.01x faster                                                                                                |
| sphinx                     | 526 ms                                                                                                           | 519 ms: 1.01x faster                                                                                                 |
| async_tree_memoization_tg  | 170 ms                                                                                                           | 168 ms: 1.01x faster                                                                                                 |
| asyncio_tcp_ssl            | 903 ms                                                                                                           | 894 ms: 1.01x faster                                                                                                 |
| regex_v8                   | 13.6 ms                                                                                                          | 13.5 ms: 1.01x faster                                                                                                |
| pickle                     | 7.12 us                                                                                                          | 7.06 us: 1.01x faster                                                                                                |
| json_loads                 | 13.4 us                                                                                                          | 13.3 us: 1.01x faster                                                                                                |
| coroutines                 | 14.1 ms                                                                                                          | 14.0 ms: 1.01x faster                                                                                                |
| pidigits                   | 237 ms                                                                                                           | 236 ms: 1.00x faster                                                                                                 |
| unpickle_list              | 2.35 us                                                                                                          | 2.36 us: 1.01x slower                                                                                                |
| sympy_expand               | 224 ms                                                                                                           | 226 ms: 1.01x slower                                                                                                 |
| unpickle                   | 7.56 us                                                                                                          | 7.63 us: 1.01x slower                                                                                                |
| pickle_list                | 2.46 us                                                                                                          | 2.49 us: 1.01x slower                                                                                                |
| coverage                   | 38.9 ms                                                                                                          | 39.3 ms: 1.01x slower                                                                                                |
| scimark_sparse_mat_mult    | 2.25 ms                                                                                                          | 2.28 ms: 1.01x slower                                                                                                |
| subparsers                 | 22.9 ms                                                                                                          | 23.3 ms: 1.02x slower                                                                                                |
| pycparser                  | 609 ms                                                                                                           | 628 ms: 1.03x slower                                                                                                 |
| async_generators           | 220 ms                                                                                                           | 229 ms: 1.04x slower                                                                                                 |
| bench_mp_pool              | 55.2 ms                                                                                                          | 57.6 ms: 1.04x slower                                                                                                |
| sympy_str                  | 133 ms                                                                                                           | 140 ms: 1.05x slower                                                                                                 |
| gc_traversal               | 2.74 ms                                                                                                          | 2.88 ms: 1.05x slower                                                                                                |
| djangocms                  | 5.80 us                                                                                                          | 6.15 us: 1.06x slower                                                                                                |
| sympy_sum                  | 71.0 ms                                                                                                          | 75.4 ms: 1.06x slower                                                                                                |
| python_startup_no_site     | 8.43 ms                                                                                                          | 8.98 ms: 1.06x slower                                                                                                |
| sympy_integrate            | 9.51 ms                                                                                                          | 10.3 ms: 1.08x slower                                                                                                |
| mdp                        | 692 ms                                                                                                           | 749 ms: 1.08x slower                                                                                                 |
| pylint                     | 142 ms                                                                                                           | 157 ms: 1.11x slower                                                                                                 |
| unpack_sequence            | 37.3 ns                                                                                                          | 41.6 ns: 1.12x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.07x faster                                                                                                         |

Benchmark hidden because not significant (9): asyncio_websockets, python_startup, pickle_dict, sqlglot_v2_normalize, create_gc_cycles, sqlglot_v2_optimize, many_optionals, docutils, asyncio_tcp
Ignored benchmarks (1) of results/bm-20251127-3.15.0a2+-5ec03cf/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2+-5ec03cf.json: dulwich_log

- Geometric mean (including insignificant results): 1.075x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x

# Memory
- memory change: 1.03x