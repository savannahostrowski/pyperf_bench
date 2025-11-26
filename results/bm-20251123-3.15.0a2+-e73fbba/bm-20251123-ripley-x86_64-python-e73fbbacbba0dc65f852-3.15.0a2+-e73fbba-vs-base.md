# Results vs. base

- fork: python
- ref: e73fbbacbba0dc65f852
- machine: linux-x86_64
- commit hash: e73fbba
- commit date: 2025-11-23
- overall geometric mean: 1.002x slower
- HPT reliability: 99.01%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.00x

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|----------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 249 ms                                                                  | 252 ms: 1.01x slower                                                    |
| html5lib       | 60.1 ms                                                                 | 61.0 ms: 1.02x slower                                                   |
| sphinx         | 976 ms                                                                  | 971 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                                   | 1.00x slower                                                            |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|---------------------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| asyncio_tcp_ssl           | 1.60 sec                                                                | 1.62 sec: 1.01x slower                                                  |
| async_tree_memoization_tg | 309 ms                                                                  | 313 ms: 1.01x slower                                                    |
| asyncio_tcp               | 482 ms                                                                  | 491 ms: 1.02x slower                                                    |
| Geometric mean            | (ref)                                                                   | 1.00x slower                                                            |

Benchmark hidden because not significant (10): async_tree_io_tg, async_tree_io, async_tree_cpu_io_mixed, asyncio_websockets, async_tree_memoization, coroutines, async_tree_cpu_io_mixed_tg, async_generators, async_tree_none_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|----------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 70.8 ms                                                                 | 69.3 ms: 1.02x faster                                                   |
| nbody          | 88.3 ms                                                                 | 86.6 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                                   | 1.01x faster                                                            |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|----------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 124 ms                                                                  | 125 ms: 1.01x slower                                                    |
| regex_dna      | 183 ms                                                                  | 189 ms: 1.03x slower                                                    |
| regex_effbot   | 2.79 ms                                                                 | 2.91 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                                   | 1.02x slower                                                            |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|----------------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpickle             | 14.4 us                                                                 | 13.9 us: 1.04x faster                                                   |
| pickle_dict          | 32.1 us                                                                 | 31.6 us: 1.02x faster                                                   |
| json_loads           | 29.1 us                                                                 | 28.6 us: 1.02x faster                                                   |
| pickle_list          | 5.17 us                                                                 | 5.12 us: 1.01x faster                                                   |
| pickle               | 12.6 us                                                                 | 12.5 us: 1.01x faster                                                   |
| xml_etree_parse      | 132 ms                                                                  | 130 ms: 1.01x faster                                                    |
| xml_etree_generate   | 82.2 ms                                                                 | 82.1 ms: 1.00x faster                                                   |
| pickle_pure_python   | 308 us                                                                  | 309 us: 1.00x slower                                                    |
| unpickle_pure_python | 208 us                                                                  | 209 us: 1.01x slower                                                    |
| json_dumps           | 9.34 ms                                                                 | 9.55 ms: 1.02x slower                                                   |
| Geometric mean       | (ref)                                                                   | 1.00x faster                                                            |

Benchmark hidden because not significant (4): xml_etree_iterparse, tomli_loads, xml_etree_process, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|----------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup | 12.8 ms                                                                 | 12.8 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                                   | 1.00x slower                                                            |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|----------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako           | 11.8 ms                                                                 | 11.7 ms: 1.01x faster                                                   |
| genshi_text    | 20.3 ms                                                                 | 20.8 ms: 1.02x slower                                                   |
| genshi_xml     | 48.0 ms                                                                 | 49.8 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                                   | 1.01x slower                                                            |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                 | bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2+-227b9d3 | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba |
|---------------------------|:-----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpack_sequence           | 40.7 ns                                                                 | 39.1 ns: 1.04x faster                                                   |
| unpickle                  | 14.4 us                                                                 | 13.9 us: 1.04x faster                                                   |
| subparsers                | 44.9 ms                                                                 | 43.3 ms: 1.04x faster                                                   |
| generators                | 28.7 ms                                                                 | 27.8 ms: 1.03x faster                                                   |
| float                     | 70.8 ms                                                                 | 69.3 ms: 1.02x faster                                                   |
| nbody                     | 88.3 ms                                                                 | 86.6 ms: 1.02x faster                                                   |
| pickle_dict               | 32.1 us                                                                 | 31.6 us: 1.02x faster                                                   |
| sympy_expand              | 471 ms                                                                  | 463 ms: 1.02x faster                                                    |
| typing_runtime_protocols  | 155 us                                                                  | 152 us: 1.02x faster                                                    |
| json_loads                | 29.1 us                                                                 | 28.6 us: 1.02x faster                                                   |
| comprehensions            | 16.1 us                                                                 | 15.9 us: 1.01x faster                                                   |
| many_optionals            | 1.23 ms                                                                 | 1.21 ms: 1.01x faster                                                   |
| pickle_list               | 5.17 us                                                                 | 5.12 us: 1.01x faster                                                   |
| hexiom                    | 5.68 ms                                                                 | 5.63 ms: 1.01x faster                                                   |
| sqlglot_v2_normalize      | 101 ms                                                                  | 100 ms: 1.01x faster                                                    |
| scimark_sor               | 108 ms                                                                  | 107 ms: 1.01x faster                                                    |
| pickle                    | 12.6 us                                                                 | 12.5 us: 1.01x faster                                                   |
| mako                      | 11.8 ms                                                                 | 11.7 ms: 1.01x faster                                                   |
| xml_etree_parse           | 132 ms                                                                  | 130 ms: 1.01x faster                                                    |
| pprint_safe_repr          | 706 ms                                                                  | 701 ms: 1.01x faster                                                    |
| pprint_pformat            | 1.44 sec                                                                | 1.43 sec: 1.01x faster                                                  |
| sphinx                    | 976 ms                                                                  | 971 ms: 1.01x faster                                                    |
| gc_traversal              | 4.55 ms                                                                 | 4.52 ms: 1.00x faster                                                   |
| sqlglot_v2_optimize       | 51.1 ms                                                                 | 50.9 ms: 1.00x faster                                                   |
| chaos                     | 56.2 ms                                                                 | 56.0 ms: 1.00x faster                                                   |
| xml_etree_generate        | 82.2 ms                                                                 | 82.1 ms: 1.00x faster                                                   |
| logging_silent            | 101 ns                                                                  | 102 ns: 1.00x slower                                                    |
| scimark_monte_carlo       | 60.1 ms                                                                 | 60.2 ms: 1.00x slower                                                   |
| python_startup            | 12.8 ms                                                                 | 12.8 ms: 1.00x slower                                                   |
| pickle_pure_python        | 308 us                                                                  | 309 us: 1.00x slower                                                    |
| bench_thread_pool         | 1.31 ms                                                                 | 1.31 ms: 1.00x slower                                                   |
| crypto_pyaes              | 68.9 ms                                                                 | 69.1 ms: 1.00x slower                                                   |
| scimark_lu                | 109 ms                                                                  | 110 ms: 1.00x slower                                                    |
| nqueens                   | 78.4 ms                                                                 | 78.7 ms: 1.00x slower                                                   |
| meteor_contest            | 98.1 ms                                                                 | 98.6 ms: 1.00x slower                                                   |
| sympy_str                 | 273 ms                                                                  | 274 ms: 1.01x slower                                                    |
| go                        | 106 ms                                                                  | 107 ms: 1.01x slower                                                    |
| unpickle_pure_python      | 208 us                                                                  | 209 us: 1.01x slower                                                    |
| deepcopy_memo             | 26.1 us                                                                 | 26.3 us: 1.01x slower                                                   |
| regex_compile             | 124 ms                                                                  | 125 ms: 1.01x slower                                                    |
| coverage                  | 81.2 ms                                                                 | 81.9 ms: 1.01x slower                                                   |
| logging_simple            | 5.81 us                                                                 | 5.86 us: 1.01x slower                                                   |
| 2to3                      | 249 ms                                                                  | 252 ms: 1.01x slower                                                    |
| fannkuch                  | 386 ms                                                                  | 389 ms: 1.01x slower                                                    |
| thrift                    | 759 us                                                                  | 766 us: 1.01x slower                                                    |
| dulwich_log               | 67.9 ms                                                                 | 68.5 ms: 1.01x slower                                                   |
| raytrace                  | 249 ms                                                                  | 252 ms: 1.01x slower                                                    |
| bpe_tokeniser             | 4.17 sec                                                                | 4.22 sec: 1.01x slower                                                  |
| asyncio_tcp_ssl           | 1.60 sec                                                                | 1.62 sec: 1.01x slower                                                  |
| sqlite_synth              | 2.27 us                                                                 | 2.30 us: 1.01x slower                                                   |
| async_tree_memoization_tg | 309 ms                                                                  | 313 ms: 1.01x slower                                                    |
| sympy_integrate           | 18.9 ms                                                                 | 19.1 ms: 1.01x slower                                                   |
| html5lib                  | 60.1 ms                                                                 | 61.0 ms: 1.02x slower                                                   |
| pathlib                   | 17.7 ms                                                                 | 18.0 ms: 1.02x slower                                                   |
| pyflate                   | 413 ms                                                                  | 420 ms: 1.02x slower                                                    |
| asyncio_tcp               | 482 ms                                                                  | 491 ms: 1.02x slower                                                    |
| pycparser                 | 1.07 sec                                                                | 1.10 sec: 1.02x slower                                                  |
| sympy_sum                 | 153 ms                                                                  | 156 ms: 1.02x slower                                                    |
| json_dumps                | 9.34 ms                                                                 | 9.55 ms: 1.02x slower                                                   |
| genshi_text               | 20.3 ms                                                                 | 20.8 ms: 1.02x slower                                                   |
| spectral_norm             | 90.9 ms                                                                 | 93.2 ms: 1.02x slower                                                   |
| deepcopy                  | 239 us                                                                  | 245 us: 1.03x slower                                                    |
| telco                     | 153 ms                                                                  | 158 ms: 1.03x slower                                                    |
| regex_dna                 | 183 ms                                                                  | 189 ms: 1.03x slower                                                    |
| genshi_xml                | 48.0 ms                                                                 | 49.8 ms: 1.04x slower                                                   |
| regex_effbot              | 2.79 ms                                                                 | 2.91 ms: 1.04x slower                                                   |
| scimark_sparse_mat_mult   | 4.27 ms                                                                 | 4.47 ms: 1.05x slower                                                   |
| Geometric mean            | (ref)                                                                   | 1.00x slower                                                            |

Benchmark hidden because not significant (32): async_tree_io_tg, json, async_tree_io, sqlglot_v2_parse, create_gc_cycles, async_tree_cpu_io_mixed, scimark_fft, xml_etree_iterparse, sqlglot_v2_transpile, mdp, pylint, asyncio_websockets, python_startup_no_site, richards, pidigits, richards_super, tomli_loads, docutils, deltablue, async_tree_memoization, coroutines, logging_format, xml_etree_process, async_tree_cpu_io_mixed_tg, unpickle_list, django_template, deepcopy_reduce, async_generators, regex_v8, async_tree_none_tg, async_tree_none, bench_mp_pool

- Geometric mean (including insignificant results): 1.002x slower

# HPT report

- Reliability score: 99.01% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.00x