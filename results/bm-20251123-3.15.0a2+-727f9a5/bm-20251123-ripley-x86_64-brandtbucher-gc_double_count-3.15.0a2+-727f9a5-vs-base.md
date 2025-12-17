# Results vs. base

- fork: brandtbucher
- ref: gc_double_count
- machine: linux-x86_64
- commit hash: 727f9a5
- commit date: 2025-11-23
- overall geometric mean: 1.000x slower
- HPT reliability: 74.85%
- HPT 99th percentile: 1.00x faster
- Memory change: 0.99x

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|----------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| 2to3           | 252 ms                                                                  | 253 ms: 1.01x slower                                                     |
| docutils       | 2.57 sec                                                                | 2.54 sec: 1.01x faster                                                   |
| sphinx         | 971 ms                                                                  | 983 ms: 1.01x slower                                                     |
| Geometric mean | (ref)                                                                   | 1.00x faster                                                             |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|-------------------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| asyncio_tcp             | 491 ms                                                                  | 483 ms: 1.02x faster                                                     |
| async_generators        | 338 ms                                                                  | 343 ms: 1.01x slower                                                     |
| async_tree_cpu_io_mixed | 488 ms                                                                  | 502 ms: 1.03x slower                                                     |
| async_tree_none_tg      | 251 ms                                                                  | 263 ms: 1.04x slower                                                     |
| async_tree_memoization  | 301 ms                                                                  | 318 ms: 1.06x slower                                                     |
| coroutines              | 23.8 ms                                                                 | 25.5 ms: 1.07x slower                                                    |
| async_tree_io_tg        | 582 ms                                                                  | 621 ms: 1.07x slower                                                     |
| async_tree_none         | 245 ms                                                                  | 271 ms: 1.11x slower                                                     |
| async_tree_io           | 553 ms                                                                  | 614 ms: 1.11x slower                                                     |
| Geometric mean          | (ref)                                                                   | 1.04x slower                                                             |

Benchmark hidden because not significant (4): asyncio_websockets, asyncio_tcp_ssl, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|----------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| pidigits       | 200 ms                                                                  | 201 ms: 1.00x slower                                                     |
| nbody          | 86.6 ms                                                                 | 88.8 ms: 1.03x slower                                                    |
| Geometric mean | (ref)                                                                   | 1.01x slower                                                             |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|----------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_effbot   | 2.91 ms                                                                 | 2.69 ms: 1.08x faster                                                    |
| regex_dna      | 189 ms                                                                  | 176 ms: 1.07x faster                                                     |
| regex_v8       | 23.7 ms                                                                 | 22.8 ms: 1.04x faster                                                    |
| regex_compile  | 125 ms                                                                  | 123 ms: 1.01x faster                                                     |
| Geometric mean | (ref)                                                                   | 1.05x faster                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|---------------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| json_dumps          | 9.55 ms                                                                 | 9.48 ms: 1.01x faster                                                    |
| tomli_loads         | 1.90 sec                                                                | 1.89 sec: 1.01x faster                                                   |
| pickle_pure_python  | 309 us                                                                  | 310 us: 1.00x slower                                                     |
| pickle              | 12.5 us                                                                 | 12.6 us: 1.01x slower                                                    |
| xml_etree_process   | 57.9 ms                                                                 | 58.4 ms: 1.01x slower                                                    |
| xml_etree_generate  | 82.1 ms                                                                 | 83.0 ms: 1.01x slower                                                    |
| json_loads          | 28.6 us                                                                 | 29.1 us: 1.01x slower                                                    |
| xml_etree_parse     | 130 ms                                                                  | 134 ms: 1.02x slower                                                     |
| unpickle            | 13.9 us                                                                 | 14.3 us: 1.03x slower                                                    |
| pickle_dict         | 31.6 us                                                                 | 32.9 us: 1.04x slower                                                    |
| pickle_list         | 5.12 us                                                                 | 5.36 us: 1.05x slower                                                    |
| xml_etree_iterparse | 85.9 ms                                                                 | 90.4 ms: 1.05x slower                                                    |
| Geometric mean      | (ref)                                                                   | 1.02x slower                                                             |

Benchmark hidden because not significant (2): unpickle_list, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|----------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup | 12.8 ms                                                                 | 12.8 ms: 1.00x faster                                                    |
| Geometric mean | (ref)                                                                   | 1.00x faster                                                             |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|----------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| genshi_xml     | 49.8 ms                                                                 | 48.8 ms: 1.02x faster                                                    |
| mako           | 11.7 ms                                                                 | 11.9 ms: 1.02x slower                                                    |
| Geometric mean | (ref)                                                                   | 1.00x faster                                                             |

Benchmark hidden because not significant (2): django_template, genshi_text

All benchmarks:
===============

| Benchmark                | bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2+-e73fbba | bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2+-727f9a5 |
|--------------------------|:-----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_effbot             | 2.91 ms                                                                 | 2.69 ms: 1.08x faster                                                    |
| regex_dna                | 189 ms                                                                  | 176 ms: 1.07x faster                                                     |
| gc_traversal             | 4.52 ms                                                                 | 4.23 ms: 1.07x faster                                                    |
| pylint                   | 286 ms                                                                  | 268 ms: 1.07x faster                                                     |
| scimark_sparse_mat_mult  | 4.47 ms                                                                 | 4.23 ms: 1.06x faster                                                    |
| logging_silent           | 102 ns                                                                  | 97.2 ns: 1.05x faster                                                    |
| regex_v8                 | 23.7 ms                                                                 | 22.8 ms: 1.04x faster                                                    |
| thrift                   | 766 us                                                                  | 748 us: 1.02x faster                                                     |
| spectral_norm            | 93.2 ms                                                                 | 91.1 ms: 1.02x faster                                                    |
| deepcopy_memo            | 26.3 us                                                                 | 25.8 us: 1.02x faster                                                    |
| comprehensions           | 15.9 us                                                                 | 15.6 us: 1.02x faster                                                    |
| sympy_integrate          | 19.1 ms                                                                 | 18.7 ms: 1.02x faster                                                    |
| deepcopy                 | 245 us                                                                  | 241 us: 1.02x faster                                                     |
| create_gc_cycles         | 2.05 ms                                                                 | 2.01 ms: 1.02x faster                                                    |
| genshi_xml               | 49.8 ms                                                                 | 48.8 ms: 1.02x faster                                                    |
| pprint_safe_repr         | 701 ms                                                                  | 688 ms: 1.02x faster                                                     |
| asyncio_tcp              | 491 ms                                                                  | 483 ms: 1.02x faster                                                     |
| sympy_str                | 274 ms                                                                  | 270 ms: 1.02x faster                                                     |
| telco                    | 158 ms                                                                  | 156 ms: 1.02x faster                                                     |
| sympy_sum                | 156 ms                                                                  | 154 ms: 1.01x faster                                                     |
| docutils                 | 2.57 sec                                                                | 2.54 sec: 1.01x faster                                                   |
| pprint_pformat           | 1.43 sec                                                                | 1.41 sec: 1.01x faster                                                   |
| pathlib                  | 18.0 ms                                                                 | 17.8 ms: 1.01x faster                                                    |
| regex_compile            | 125 ms                                                                  | 123 ms: 1.01x faster                                                     |
| go                       | 107 ms                                                                  | 105 ms: 1.01x faster                                                     |
| hexiom                   | 5.63 ms                                                                 | 5.57 ms: 1.01x faster                                                    |
| sqlglot_v2_optimize      | 50.9 ms                                                                 | 50.4 ms: 1.01x faster                                                    |
| scimark_lu               | 110 ms                                                                  | 109 ms: 1.01x faster                                                     |
| raytrace                 | 252 ms                                                                  | 249 ms: 1.01x faster                                                     |
| sqlglot_v2_parse         | 1.21 ms                                                                 | 1.20 ms: 1.01x faster                                                    |
| logging_format           | 6.68 us                                                                 | 6.62 us: 1.01x faster                                                    |
| nqueens                  | 78.7 ms                                                                 | 78.0 ms: 1.01x faster                                                    |
| scimark_sor              | 107 ms                                                                  | 106 ms: 1.01x faster                                                     |
| sympy_expand             | 463 ms                                                                  | 459 ms: 1.01x faster                                                     |
| logging_simple           | 5.86 us                                                                 | 5.82 us: 1.01x faster                                                    |
| sqlglot_v2_normalize     | 100 ms                                                                  | 99.6 ms: 1.01x faster                                                    |
| json_dumps               | 9.55 ms                                                                 | 9.48 ms: 1.01x faster                                                    |
| richards                 | 41.8 ms                                                                 | 41.5 ms: 1.01x faster                                                    |
| tomli_loads              | 1.90 sec                                                                | 1.89 sec: 1.01x faster                                                   |
| bench_thread_pool        | 1.31 ms                                                                 | 1.30 ms: 1.01x faster                                                    |
| mdp                      | 1.16 sec                                                                | 1.15 sec: 1.01x faster                                                   |
| python_startup           | 12.8 ms                                                                 | 12.8 ms: 1.00x faster                                                    |
| pyflate                  | 420 ms                                                                  | 419 ms: 1.00x faster                                                     |
| deltablue                | 3.36 ms                                                                 | 3.36 ms: 1.00x faster                                                    |
| crypto_pyaes             | 69.1 ms                                                                 | 69.2 ms: 1.00x slower                                                    |
| pickle_pure_python       | 309 us                                                                  | 310 us: 1.00x slower                                                     |
| fannkuch                 | 389 ms                                                                  | 390 ms: 1.00x slower                                                     |
| pidigits                 | 200 ms                                                                  | 201 ms: 1.00x slower                                                     |
| meteor_contest           | 98.6 ms                                                                 | 99.1 ms: 1.00x slower                                                    |
| 2to3                     | 252 ms                                                                  | 253 ms: 1.01x slower                                                     |
| scimark_fft              | 301 ms                                                                  | 303 ms: 1.01x slower                                                     |
| pickle                   | 12.5 us                                                                 | 12.6 us: 1.01x slower                                                    |
| generators               | 27.8 ms                                                                 | 28.0 ms: 1.01x slower                                                    |
| xml_etree_process        | 57.9 ms                                                                 | 58.4 ms: 1.01x slower                                                    |
| xml_etree_generate       | 82.1 ms                                                                 | 83.0 ms: 1.01x slower                                                    |
| pycparser                | 1.10 sec                                                                | 1.11 sec: 1.01x slower                                                   |
| sphinx                   | 971 ms                                                                  | 983 ms: 1.01x slower                                                     |
| richards_super           | 47.8 ms                                                                 | 48.5 ms: 1.01x slower                                                    |
| async_generators         | 338 ms                                                                  | 343 ms: 1.01x slower                                                     |
| json_loads               | 28.6 us                                                                 | 29.1 us: 1.01x slower                                                    |
| mako                     | 11.7 ms                                                                 | 11.9 ms: 1.02x slower                                                    |
| scimark_monte_carlo      | 60.2 ms                                                                 | 61.2 ms: 1.02x slower                                                    |
| subparsers               | 43.3 ms                                                                 | 44.0 ms: 1.02x slower                                                    |
| bpe_tokeniser            | 4.22 sec                                                                | 4.29 sec: 1.02x slower                                                   |
| typing_runtime_protocols | 152 us                                                                  | 155 us: 1.02x slower                                                     |
| json                     | 5.08 ms                                                                 | 5.18 ms: 1.02x slower                                                    |
| xml_etree_parse          | 130 ms                                                                  | 134 ms: 1.02x slower                                                     |
| nbody                    | 86.6 ms                                                                 | 88.8 ms: 1.03x slower                                                    |
| unpickle                 | 13.9 us                                                                 | 14.3 us: 1.03x slower                                                    |
| async_tree_cpu_io_mixed  | 488 ms                                                                  | 502 ms: 1.03x slower                                                     |
| pickle_dict              | 31.6 us                                                                 | 32.9 us: 1.04x slower                                                    |
| sqlite_synth             | 2.30 us                                                                 | 2.41 us: 1.04x slower                                                    |
| async_tree_none_tg       | 251 ms                                                                  | 263 ms: 1.04x slower                                                     |
| pickle_list              | 5.12 us                                                                 | 5.36 us: 1.05x slower                                                    |
| xml_etree_iterparse      | 85.9 ms                                                                 | 90.4 ms: 1.05x slower                                                    |
| async_tree_memoization   | 301 ms                                                                  | 318 ms: 1.06x slower                                                     |
| coroutines               | 23.8 ms                                                                 | 25.5 ms: 1.07x slower                                                    |
| async_tree_io_tg         | 582 ms                                                                  | 621 ms: 1.07x slower                                                     |
| async_tree_none          | 245 ms                                                                  | 271 ms: 1.11x slower                                                     |
| async_tree_io            | 553 ms                                                                  | 614 ms: 1.11x slower                                                     |
| unpack_sequence          | 39.1 ns                                                                 | 44.7 ns: 1.14x slower                                                    |
| Geometric mean           | (ref)                                                                   | 1.00x slower                                                             |

Benchmark hidden because not significant (18): html5lib, django_template, dulwich_log, many_optionals, deepcopy_reduce, unpickle_list, genshi_text, asyncio_websockets, chaos, unpickle_pure_python, python_startup_no_site, coverage, float, asyncio_tcp_ssl, sqlglot_v2_transpile, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, bench_mp_pool

- Geometric mean (including insignificant results): 1.000x slower

# HPT report

- Reliability score: 74.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 0.99x