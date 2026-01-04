# Results vs. base

- fork: python
- ref: cf6758ff9ebd6df8ac2a
- machine: linux-x86_64
- commit hash: cf6758f
- commit date: 2025-12-24
- overall geometric mean: 1.034x faster
- HPT reliability: 81.57%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 353 ms                                                                                                             | 355 ms: 1.01x slower                                                                                                   |
| chameleon      | 18.8 ms                                                                                                            | 19.3 ms: 1.03x slower                                                                                                  |
| docutils       | 3.61 sec                                                                                                           | 3.86 sec: 1.07x slower                                                                                                 |
| html5lib       | 86.6 ms                                                                                                            | 92.0 ms: 1.06x slower                                                                                                  |
| sphinx         | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| tornado_http   | 195 ms                                                                                                             | 193 ms: 1.01x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.03x slower                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|-------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| coroutines              | 34.2 ms                                                                                                            | 33.4 ms: 1.02x faster                                                                                                  |
| asyncio_tcp_ssl         | 2.07 sec                                                                                                           | 2.06 sec: 1.01x faster                                                                                                 |
| asyncio_websockets      | 777 ms                                                                                                             | 779 ms: 1.00x slower                                                                                                   |
| async_tree_cpu_io_mixed | 676 ms                                                                                                             | 683 ms: 1.01x slower                                                                                                   |
| asyncio_tcp             | 547 ms                                                                                                             | 563 ms: 1.03x slower                                                                                                   |
| async_generators        | 490 ms                                                                                                             | 511 ms: 1.04x slower                                                                                                   |
| Geometric mean          | (ref)                                                                                                              | 1.00x slower                                                                                                           |

Benchmark hidden because not significant (7): async_tree_none_tg, async_tree_memoization_tg, async_tree_io_tg, async_tree_none, async_tree_io, async_tree_memoization, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 130 ms                                                                                                             | 105 ms: 1.24x faster                                                                                                   |
| float          | 102 ms                                                                                                             | 83.8 ms: 1.22x faster                                                                                                  |
| pidigits       | 286 ms                                                                                                             | 274 ms: 1.04x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.16x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 175 ms                                                                                                             | 174 ms: 1.01x faster                                                                                                   |
| regex_effbot   | 4.13 ms                                                                                                            | 4.20 ms: 1.02x slower                                                                                                  |
| regex_dna      | 267 ms                                                                                                             | 272 ms: 1.02x slower                                                                                                   |
| regex_v8       | 31.8 ms                                                                                                            | 33.5 ms: 1.05x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.02x slower                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 300 us                                                                                                             | 251 us: 1.19x faster                                                                                                   |
| pickle_pure_python   | 439 us                                                                                                             | 395 us: 1.11x faster                                                                                                   |
| xml_etree_process    | 82.9 ms                                                                                                            | 76.9 ms: 1.08x faster                                                                                                  |
| json_dumps           | 14.5 ms                                                                                                            | 13.5 ms: 1.08x faster                                                                                                  |
| xml_etree_generate   | 119 ms                                                                                                             | 111 ms: 1.07x faster                                                                                                   |
| tomli_loads          | 3.06 sec                                                                                                           | 2.88 sec: 1.06x faster                                                                                                 |
| pickle_dict          | 47.0 us                                                                                                            | 44.6 us: 1.05x faster                                                                                                  |
| xml_etree_iterparse  | 121 ms                                                                                                             | 120 ms: 1.02x faster                                                                                                   |
| json_loads           | 40.1 us                                                                                                            | 39.6 us: 1.01x faster                                                                                                  |
| unpickle             | 20.9 us                                                                                                            | 20.7 us: 1.01x faster                                                                                                  |
| pickle               | 18.0 us                                                                                                            | 17.8 us: 1.01x faster                                                                                                  |
| pickle_list          | 7.17 us                                                                                                            | 7.32 us: 1.02x slower                                                                                                  |
| unpickle_list        | 7.51 us                                                                                                            | 7.71 us: 1.03x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| python_startup         | 17.7 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako           | 17.2 ms                                                                                                            | 15.3 ms: 1.12x faster                                                                                                  |
| genshi_text    | 29.9 ms                                                                                                            | 30.1 ms: 1.01x slower                                                                                                  |
| genshi_xml     | 70.5 ms                                                                                                            | 74.3 ms: 1.05x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                | results/bm-20251224-3.15.0a3+-cf6758f/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json | results/bm-20251224-3.15.0a3+-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3+-cf6758f.json |
|--------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                 | 61.1 ms                                                                                                            | 26.0 ms: 2.35x faster                                                                                                  |
| richards_super           | 68.5 ms                                                                                                            | 31.1 ms: 2.20x faster                                                                                                  |
| logging_silent           | 146 ns                                                                                                             | 118 ns: 1.24x faster                                                                                                   |
| nbody                    | 130 ms                                                                                                             | 105 ms: 1.24x faster                                                                                                   |
| deltablue                | 4.75 ms                                                                                                            | 3.85 ms: 1.23x faster                                                                                                  |
| float                    | 102 ms                                                                                                             | 83.8 ms: 1.22x faster                                                                                                  |
| scimark_fft              | 444 ms                                                                                                             | 370 ms: 1.20x faster                                                                                                   |
| unpickle_pure_python     | 300 us                                                                                                             | 251 us: 1.19x faster                                                                                                   |
| scimark_monte_carlo      | 89.2 ms                                                                                                            | 75.6 ms: 1.18x faster                                                                                                  |
| pyflate                  | 590 ms                                                                                                             | 519 ms: 1.14x faster                                                                                                   |
| go                       | 151 ms                                                                                                             | 133 ms: 1.13x faster                                                                                                   |
| bench_mp_pool            | 245 ms                                                                                                             | 218 ms: 1.12x faster                                                                                                   |
| mako                     | 17.2 ms                                                                                                            | 15.3 ms: 1.12x faster                                                                                                  |
| pickle_pure_python       | 439 us                                                                                                             | 395 us: 1.11x faster                                                                                                   |
| gc_traversal             | 6.84 ms                                                                                                            | 6.16 ms: 1.11x faster                                                                                                  |
| fannkuch                 | 552 ms                                                                                                             | 500 ms: 1.10x faster                                                                                                   |
| spectral_norm            | 136 ms                                                                                                             | 124 ms: 1.10x faster                                                                                                   |
| xml_etree_process        | 82.9 ms                                                                                                            | 76.9 ms: 1.08x faster                                                                                                  |
| json_dumps               | 14.5 ms                                                                                                            | 13.5 ms: 1.08x faster                                                                                                  |
| xml_etree_generate       | 119 ms                                                                                                             | 111 ms: 1.07x faster                                                                                                   |
| tomli_loads              | 3.06 sec                                                                                                           | 2.88 sec: 1.06x faster                                                                                                 |
| pickle_dict              | 47.0 us                                                                                                            | 44.6 us: 1.05x faster                                                                                                  |
| chaos                    | 80.0 ms                                                                                                            | 76.2 ms: 1.05x faster                                                                                                  |
| json                     | 7.31 ms                                                                                                            | 6.97 ms: 1.05x faster                                                                                                  |
| bpe_tokeniser            | 5.95 sec                                                                                                           | 5.68 sec: 1.05x faster                                                                                                 |
| crypto_pyaes             | 98.9 ms                                                                                                            | 94.6 ms: 1.05x faster                                                                                                  |
| pidigits                 | 286 ms                                                                                                             | 274 ms: 1.04x faster                                                                                                   |
| deepcopy_memo            | 37.1 us                                                                                                            | 35.6 us: 1.04x faster                                                                                                  |
| scimark_sor              | 152 ms                                                                                                             | 146 ms: 1.04x faster                                                                                                   |
| pprint_safe_repr         | 984 ms                                                                                                             | 945 ms: 1.04x faster                                                                                                   |
| pprint_pformat           | 2.01 sec                                                                                                           | 1.94 sec: 1.04x faster                                                                                                 |
| connected_components     | 460 ms                                                                                                             | 444 ms: 1.04x faster                                                                                                   |
| meteor_contest           | 144 ms                                                                                                             | 139 ms: 1.03x faster                                                                                                   |
| k_core                   | 2.26 sec                                                                                                           | 2.20 sec: 1.03x faster                                                                                                 |
| coroutines               | 34.2 ms                                                                                                            | 33.4 ms: 1.02x faster                                                                                                  |
| sqlite_synth             | 3.25 us                                                                                                            | 3.18 us: 1.02x faster                                                                                                  |
| scimark_lu               | 153 ms                                                                                                             | 149 ms: 1.02x faster                                                                                                   |
| deepcopy_reduce          | 3.68 us                                                                                                            | 3.59 us: 1.02x faster                                                                                                  |
| shortest_path            | 511 ms                                                                                                             | 501 ms: 1.02x faster                                                                                                   |
| xml_etree_iterparse      | 121 ms                                                                                                             | 120 ms: 1.02x faster                                                                                                   |
| subparsers               | 13.2 ms                                                                                                            | 13.0 ms: 1.02x faster                                                                                                  |
| json_loads               | 40.1 us                                                                                                            | 39.6 us: 1.01x faster                                                                                                  |
| unpickle                 | 20.9 us                                                                                                            | 20.7 us: 1.01x faster                                                                                                  |
| sqlglot_v2_parse         | 1.69 ms                                                                                                            | 1.67 ms: 1.01x faster                                                                                                  |
| pickle                   | 18.0 us                                                                                                            | 17.8 us: 1.01x faster                                                                                                  |
| deepcopy                 | 346 us                                                                                                             | 342 us: 1.01x faster                                                                                                   |
| regex_compile            | 175 ms                                                                                                             | 174 ms: 1.01x faster                                                                                                   |
| tornado_http             | 195 ms                                                                                                             | 193 ms: 1.01x faster                                                                                                   |
| asyncio_tcp_ssl          | 2.07 sec                                                                                                           | 2.06 sec: 1.01x faster                                                                                                 |
| create_gc_cycles         | 2.88 ms                                                                                                            | 2.87 ms: 1.00x faster                                                                                                  |
| scimark_sparse_mat_mult  | 6.24 ms                                                                                                            | 6.23 ms: 1.00x faster                                                                                                  |
| asyncio_websockets       | 777 ms                                                                                                             | 779 ms: 1.00x slower                                                                                                   |
| 2to3                     | 353 ms                                                                                                             | 355 ms: 1.01x slower                                                                                                   |
| bench_thread_pool        | 1.74 ms                                                                                                            | 1.75 ms: 1.01x slower                                                                                                  |
| genshi_text              | 29.9 ms                                                                                                            | 30.1 ms: 1.01x slower                                                                                                  |
| python_startup_no_site   | 10.4 ms                                                                                                            | 10.5 ms: 1.01x slower                                                                                                  |
| sqlalchemy_declarative   | 187 ms                                                                                                             | 189 ms: 1.01x slower                                                                                                   |
| python_startup           | 17.7 ms                                                                                                            | 17.9 ms: 1.01x slower                                                                                                  |
| async_tree_cpu_io_mixed  | 676 ms                                                                                                             | 683 ms: 1.01x slower                                                                                                   |
| typing_runtime_protocols | 220 us                                                                                                             | 223 us: 1.01x slower                                                                                                   |
| comprehensions           | 22.6 us                                                                                                            | 22.8 us: 1.01x slower                                                                                                  |
| pathlib                  | 25.1 ms                                                                                                            | 25.4 ms: 1.01x slower                                                                                                  |
| xdsl_constant_fold       | 65.5 ms                                                                                                            | 66.4 ms: 1.01x slower                                                                                                  |
| sqlglot_v2_transpile     | 2.14 ms                                                                                                            | 2.18 ms: 1.02x slower                                                                                                  |
| regex_effbot             | 4.13 ms                                                                                                            | 4.20 ms: 1.02x slower                                                                                                  |
| regex_dna                | 267 ms                                                                                                             | 272 ms: 1.02x slower                                                                                                   |
| pickle_list              | 7.17 us                                                                                                            | 7.32 us: 1.02x slower                                                                                                  |
| generators               | 40.1 ms                                                                                                            | 41.0 ms: 1.02x slower                                                                                                  |
| chameleon                | 18.8 ms                                                                                                            | 19.3 ms: 1.03x slower                                                                                                  |
| unpickle_list            | 7.51 us                                                                                                            | 7.71 us: 1.03x slower                                                                                                  |
| hexiom                   | 8.18 ms                                                                                                            | 8.40 ms: 1.03x slower                                                                                                  |
| telco                    | 227 ms                                                                                                             | 234 ms: 1.03x slower                                                                                                   |
| sphinx                   | 1.38 sec                                                                                                           | 1.42 sec: 1.03x slower                                                                                                 |
| asyncio_tcp              | 547 ms                                                                                                             | 563 ms: 1.03x slower                                                                                                   |
| raytrace                 | 359 ms                                                                                                             | 371 ms: 1.04x slower                                                                                                   |
| dulwich_log              | 99.4 ms                                                                                                            | 103 ms: 1.04x slower                                                                                                   |
| async_generators         | 490 ms                                                                                                             | 511 ms: 1.04x slower                                                                                                   |
| sympy_integrate          | 27.3 ms                                                                                                            | 28.5 ms: 1.05x slower                                                                                                  |
| many_optionals           | 1.36 ms                                                                                                            | 1.43 ms: 1.05x slower                                                                                                  |
| regex_v8                 | 31.8 ms                                                                                                            | 33.5 ms: 1.05x slower                                                                                                  |
| genshi_xml               | 70.5 ms                                                                                                            | 74.3 ms: 1.05x slower                                                                                                  |
| sympy_expand             | 690 ms                                                                                                             | 727 ms: 1.05x slower                                                                                                   |
| sqlglot_v2_optimize      | 72.7 ms                                                                                                            | 76.9 ms: 1.06x slower                                                                                                  |
| nqueens                  | 112 ms                                                                                                             | 119 ms: 1.06x slower                                                                                                   |
| html5lib                 | 86.6 ms                                                                                                            | 92.0 ms: 1.06x slower                                                                                                  |
| sympy_sum                | 225 ms                                                                                                             | 240 ms: 1.07x slower                                                                                                   |
| docutils                 | 3.61 sec                                                                                                           | 3.86 sec: 1.07x slower                                                                                                 |
| pylint                   | 404 ms                                                                                                             | 433 ms: 1.07x slower                                                                                                   |
| sqlglot_v2_normalize     | 146 ms                                                                                                             | 157 ms: 1.08x slower                                                                                                   |
| sympy_str                | 397 ms                                                                                                             | 434 ms: 1.09x slower                                                                                                   |
| mdp                      | 1.65 sec                                                                                                           | 1.92 sec: 1.17x slower                                                                                                 |
| unpack_sequence          | 54.9 ns                                                                                                            | 66.2 ns: 1.21x slower                                                                                                  |
| Geometric mean           | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (15): async_tree_none_tg, logging_format, logging_simple, pycparser, async_tree_memoization_tg, xml_etree_parse, async_tree_io_tg, async_tree_none, async_tree_io, thrift, async_tree_memoization, django_template, coverage, sqlalchemy_imperative, async_tree_cpu_io_mixed_tg

- Geometric mean (including insignificant results): 1.034x faster

# HPT report

- Reliability score: 81.57% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x