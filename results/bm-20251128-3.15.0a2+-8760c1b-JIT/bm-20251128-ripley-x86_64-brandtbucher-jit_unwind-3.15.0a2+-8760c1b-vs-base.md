# Results vs. base

- fork: brandtbucher
- ref: jit_unwind
- machine: linux-x86_64
- commit hash: 8760c1b
- commit date: 2025-11-28
- overall geometric mean: 1.005x faster
- HPT reliability: 97.97%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.00x

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|----------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| html5lib       | 66.5 ms                                                                 | 67.7 ms: 1.02x slower                                               |
| sphinx         | 1.02 sec                                                                | 1.03 sec: 1.01x slower                                              |
| Geometric mean | (ref)                                                                   | 1.01x slower                                                        |

Benchmark hidden because not significant (2): 2to3, docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|-------------------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| coroutines              | 24.2 ms                                                                 | 24.0 ms: 1.01x faster                                               |
| asyncio_tcp_ssl         | 1.56 sec                                                                | 1.57 sec: 1.00x slower                                              |
| async_tree_cpu_io_mixed | 486 ms                                                                  | 490 ms: 1.01x slower                                                |
| asyncio_tcp             | 441 ms                                                                  | 446 ms: 1.01x slower                                                |
| async_generators        | 357 ms                                                                  | 363 ms: 1.01x slower                                                |
| Geometric mean          | (ref)                                                                   | 1.00x slower                                                        |

Benchmark hidden because not significant (8): async_tree_memoization, async_tree_io, async_tree_io_tg, async_tree_none_tg, async_tree_none, asyncio_websockets, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|----------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 202 ms                                                                  | 194 ms: 1.04x faster                                                |
| nbody          | 87.4 ms                                                                 | 88.1 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                                   | 1.01x faster                                                        |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|----------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_v8       | 21.9 ms                                                                 | 21.0 ms: 1.04x faster                                               |
| regex_effbot   | 2.79 ms                                                                 | 2.68 ms: 1.04x faster                                               |
| regex_compile  | 126 ms                                                                  | 124 ms: 1.01x faster                                                |
| regex_dna      | 178 ms                                                                  | 176 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                                   | 1.03x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|----------------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| xml_etree_parse      | 135 ms                                                                  | 129 ms: 1.05x faster                                                |
| unpickle             | 14.4 us                                                                 | 13.9 us: 1.03x faster                                               |
| pickle_list          | 5.28 us                                                                 | 5.12 us: 1.03x faster                                               |
| unpickle_list        | 5.33 us                                                                 | 5.17 us: 1.03x faster                                               |
| xml_etree_iterparse  | 85.8 ms                                                                 | 83.7 ms: 1.03x faster                                               |
| xml_etree_process    | 54.5 ms                                                                 | 53.5 ms: 1.02x faster                                               |
| pickle_dict          | 32.5 us                                                                 | 32.0 us: 1.02x faster                                               |
| pickle               | 12.6 us                                                                 | 12.5 us: 1.01x faster                                               |
| unpickle_pure_python | 183 us                                                                  | 182 us: 1.01x faster                                                |
| json_loads           | 28.4 us                                                                 | 28.1 us: 1.01x faster                                               |
| xml_etree_generate   | 78.0 ms                                                                 | 77.4 ms: 1.01x faster                                               |
| tomli_loads          | 1.84 sec                                                                | 1.83 sec: 1.01x faster                                              |
| pickle_pure_python   | 291 us                                                                  | 295 us: 1.01x slower                                                |
| json_dumps           | 9.28 ms                                                                 | 9.44 ms: 1.02x slower                                               |
| Geometric mean       | (ref)                                                                   | 1.01x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|----------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup | 13.0 ms                                                                 | 12.9 ms: 1.00x faster                                               |
| Geometric mean | (ref)                                                                   | 1.00x faster                                                        |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|-----------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| genshi_text     | 22.0 ms                                                                 | 21.5 ms: 1.02x faster                                               |
| django_template | 34.9 ms                                                                 | 34.3 ms: 1.02x faster                                               |
| mako            | 10.7 ms                                                                 | 10.6 ms: 1.01x faster                                               |
| Geometric mean  | (ref)                                                                   | 1.01x faster                                                        |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark                | bm-20251126-ripley-x86_64-python-9ac14288d7147dbbae08-3.15.0a2+-9ac1428 | bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2+-8760c1b |
|--------------------------|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| xml_etree_parse          | 135 ms                                                                  | 129 ms: 1.05x faster                                                |
| pidigits                 | 202 ms                                                                  | 194 ms: 1.04x faster                                                |
| regex_v8                 | 21.9 ms                                                                 | 21.0 ms: 1.04x faster                                               |
| regex_effbot             | 2.79 ms                                                                 | 2.68 ms: 1.04x faster                                               |
| unpickle                 | 14.4 us                                                                 | 13.9 us: 1.03x faster                                               |
| pickle_list              | 5.28 us                                                                 | 5.12 us: 1.03x faster                                               |
| dulwich_log              | 73.3 ms                                                                 | 71.1 ms: 1.03x faster                                               |
| unpickle_list            | 5.33 us                                                                 | 5.17 us: 1.03x faster                                               |
| deepcopy                 | 253 us                                                                  | 245 us: 1.03x faster                                                |
| xml_etree_iterparse      | 85.8 ms                                                                 | 83.7 ms: 1.03x faster                                               |
| scimark_sor              | 97.8 ms                                                                 | 95.5 ms: 1.02x faster                                               |
| genshi_text              | 22.0 ms                                                                 | 21.5 ms: 1.02x faster                                               |
| deepcopy_memo            | 25.1 us                                                                 | 24.6 us: 1.02x faster                                               |
| pprint_pformat           | 1.49 sec                                                                | 1.46 sec: 1.02x faster                                              |
| xml_etree_process        | 54.5 ms                                                                 | 53.5 ms: 1.02x faster                                               |
| deltablue                | 2.94 ms                                                                 | 2.89 ms: 1.02x faster                                               |
| django_template          | 34.9 ms                                                                 | 34.3 ms: 1.02x faster                                               |
| pprint_safe_repr         | 714 ms                                                                  | 702 ms: 1.02x faster                                                |
| pickle_dict              | 32.5 us                                                                 | 32.0 us: 1.02x faster                                               |
| hexiom                   | 6.13 ms                                                                 | 6.03 ms: 1.02x faster                                               |
| nqueens                  | 86.2 ms                                                                 | 84.9 ms: 1.02x faster                                               |
| regex_compile            | 126 ms                                                                  | 124 ms: 1.01x faster                                                |
| richards                 | 20.8 ms                                                                 | 20.5 ms: 1.01x faster                                               |
| logging_format           | 6.61 us                                                                 | 6.53 us: 1.01x faster                                               |
| sqlite_synth             | 2.21 us                                                                 | 2.18 us: 1.01x faster                                               |
| sqlglot_v2_optimize      | 54.1 ms                                                                 | 53.5 ms: 1.01x faster                                               |
| go                       | 102 ms                                                                  | 101 ms: 1.01x faster                                                |
| regex_dna                | 178 ms                                                                  | 176 ms: 1.01x faster                                                |
| mako                     | 10.7 ms                                                                 | 10.6 ms: 1.01x faster                                               |
| typing_runtime_protocols | 158 us                                                                  | 156 us: 1.01x faster                                                |
| sqlglot_v2_parse         | 1.24 ms                                                                 | 1.23 ms: 1.01x faster                                               |
| richards_super           | 24.8 ms                                                                 | 24.5 ms: 1.01x faster                                               |
| deepcopy_reduce          | 2.57 us                                                                 | 2.54 us: 1.01x faster                                               |
| pickle                   | 12.6 us                                                                 | 12.5 us: 1.01x faster                                               |
| meteor_contest           | 97.7 ms                                                                 | 96.8 ms: 1.01x faster                                               |
| pycparser                | 1.10 sec                                                                | 1.09 sec: 1.01x faster                                              |
| raytrace                 | 261 ms                                                                  | 259 ms: 1.01x faster                                                |
| unpickle_pure_python     | 183 us                                                                  | 182 us: 1.01x faster                                                |
| json_loads               | 28.4 us                                                                 | 28.1 us: 1.01x faster                                               |
| coroutines               | 24.2 ms                                                                 | 24.0 ms: 1.01x faster                                               |
| sqlglot_v2_transpile     | 1.53 ms                                                                 | 1.52 ms: 1.01x faster                                               |
| pyflate                  | 385 ms                                                                  | 382 ms: 1.01x faster                                                |
| xml_etree_generate       | 78.0 ms                                                                 | 77.4 ms: 1.01x faster                                               |
| telco                    | 162 ms                                                                  | 161 ms: 1.01x faster                                                |
| comprehensions           | 16.2 us                                                                 | 16.1 us: 1.01x faster                                               |
| crypto_pyaes             | 66.4 ms                                                                 | 66.0 ms: 1.01x faster                                               |
| tomli_loads              | 1.84 sec                                                                | 1.83 sec: 1.01x faster                                              |
| coverage                 | 82.2 ms                                                                 | 81.8 ms: 1.01x faster                                               |
| sqlglot_v2_normalize     | 109 ms                                                                  | 109 ms: 1.00x faster                                                |
| python_startup           | 13.0 ms                                                                 | 12.9 ms: 1.00x faster                                               |
| bpe_tokeniser            | 4.00 sec                                                                | 4.01 sec: 1.00x slower                                              |
| scimark_lu               | 101 ms                                                                  | 102 ms: 1.00x slower                                                |
| asyncio_tcp_ssl          | 1.56 sec                                                                | 1.57 sec: 1.00x slower                                              |
| spectral_norm            | 82.4 ms                                                                 | 82.7 ms: 1.00x slower                                               |
| scimark_fft              | 256 ms                                                                  | 258 ms: 1.01x slower                                                |
| subparsers               | 46.0 ms                                                                 | 46.3 ms: 1.01x slower                                               |
| sympy_sum                | 171 ms                                                                  | 173 ms: 1.01x slower                                                |
| thrift                   | 739 us                                                                  | 745 us: 1.01x slower                                                |
| nbody                    | 87.4 ms                                                                 | 88.1 ms: 1.01x slower                                               |
| pathlib                  | 17.7 ms                                                                 | 17.8 ms: 1.01x slower                                               |
| async_tree_cpu_io_mixed  | 486 ms                                                                  | 490 ms: 1.01x slower                                                |
| sympy_expand             | 506 ms                                                                  | 510 ms: 1.01x slower                                                |
| asyncio_tcp              | 441 ms                                                                  | 446 ms: 1.01x slower                                                |
| fannkuch                 | 364 ms                                                                  | 368 ms: 1.01x slower                                                |
| sphinx                   | 1.02 sec                                                                | 1.03 sec: 1.01x slower                                              |
| pickle_pure_python       | 291 us                                                                  | 295 us: 1.01x slower                                                |
| create_gc_cycles         | 2.05 ms                                                                 | 2.08 ms: 1.01x slower                                               |
| async_generators         | 357 ms                                                                  | 363 ms: 1.01x slower                                                |
| json_dumps               | 9.28 ms                                                                 | 9.44 ms: 1.02x slower                                               |
| html5lib                 | 66.5 ms                                                                 | 67.7 ms: 1.02x slower                                               |
| many_optionals           | 1.28 ms                                                                 | 1.31 ms: 1.02x slower                                               |
| generators               | 29.4 ms                                                                 | 30.2 ms: 1.03x slower                                               |
| gc_traversal             | 4.34 ms                                                                 | 4.61 ms: 1.06x slower                                               |
| Geometric mean           | (ref)                                                                   | 1.01x faster                                                        |

Benchmark hidden because not significant (26): bench_mp_pool, unpack_sequence, async_tree_memoization, async_tree_io, float, async_tree_io_tg, async_tree_none_tg, async_tree_none, genshi_xml, scimark_monte_carlo, logging_silent, json, bench_thread_pool, logging_simple, docutils, 2to3, python_startup_no_site, asyncio_websockets, scimark_sparse_mat_mult, chaos, async_tree_memoization_tg, sympy_str, pylint, mdp, sympy_integrate, async_tree_cpu_io_mixed_tg

- Geometric mean (including insignificant results): 1.005x faster

# HPT report

- Reliability score: 97.97% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.00x