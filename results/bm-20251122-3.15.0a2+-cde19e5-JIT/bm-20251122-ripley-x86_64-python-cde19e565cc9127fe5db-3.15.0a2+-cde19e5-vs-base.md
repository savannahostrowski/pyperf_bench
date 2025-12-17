# Results vs. base

- fork: python
- ref: cde19e565cc9127fe5db
- machine: linux-x86_64
- commit hash: cde19e5
- commit date: 2025-11-22
- overall geometric mean: 1.074x faster
- HPT reliability: 92.96%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 251 ms                                                                                                             | 253 ms: 1.01x slower                                                                                                   |
| html5lib       | 60.9 ms                                                                                                            | 67.1 ms: 1.10x slower                                                                                                  |
| sphinx         | 971 ms                                                                                                             | 20.7 ms: 46.97x faster                                                                                                 |
| Geometric mean | (ref)                                                                                                              | 3.48x faster                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 500 ms                                                                                                             | 482 ms: 1.04x faster                                                                                                   |
| async_tree_cpu_io_mixed_tg | 502 ms                                                                                                             | 489 ms: 1.03x faster                                                                                                   |
| asyncio_tcp                | 488 ms                                                                                                             | 482 ms: 1.01x faster                                                                                                   |
| coroutines                 | 24.2 ms                                                                                                            | 24.0 ms: 1.01x faster                                                                                                  |
| asyncio_tcp_ssl            | 1.60 sec                                                                                                           | 1.61 sec: 1.01x slower                                                                                                 |
| async_tree_memoization_tg  | 311 ms                                                                                                             | 318 ms: 1.02x slower                                                                                                   |
| async_generators           | 344 ms                                                                                                             | 354 ms: 1.03x slower                                                                                                   |
| Geometric mean             | (ref)                                                                                                              | 1.00x faster                                                                                                           |

Benchmark hidden because not significant (6): async_tree_none, async_tree_none_tg, asyncio_websockets, async_tree_io, async_tree_memoization, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| float          | 70.7 ms                                                                                                            | 60.2 ms: 1.17x faster                                                                                                  |
| pidigits       | 205 ms                                                                                                             | 193 ms: 1.07x faster                                                                                                   |
| nbody          | 87.9 ms                                                                                                            | 84.7 ms: 1.04x faster                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.09x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 2.71 ms                                                                                                            | 2.58 ms: 1.05x faster                                                                                                  |
| regex_dna      | 175 ms                                                                                                             | 173 ms: 1.01x faster                                                                                                   |
| regex_v8       | 21.4 ms                                                                                                            | 21.7 ms: 1.02x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 208 us                                                                                                             | 181 us: 1.15x faster                                                                                                   |
| xml_etree_process    | 58.3 ms                                                                                                            | 54.9 ms: 1.06x faster                                                                                                  |
| xml_etree_generate   | 82.7 ms                                                                                                            | 78.5 ms: 1.05x faster                                                                                                  |
| tomli_loads          | 1.92 sec                                                                                                           | 1.82 sec: 1.05x faster                                                                                                 |
| pickle_pure_python   | 308 us                                                                                                             | 296 us: 1.04x faster                                                                                                   |
| pickle_list          | 5.42 us                                                                                                            | 5.23 us: 1.04x faster                                                                                                  |
| json_loads           | 29.4 us                                                                                                            | 28.6 us: 1.03x faster                                                                                                  |
| pickle_dict          | 32.7 us                                                                                                            | 31.9 us: 1.02x faster                                                                                                  |
| xml_etree_iterparse  | 87.1 ms                                                                                                            | 85.9 ms: 1.01x faster                                                                                                  |
| pickle               | 12.9 us                                                                                                            | 12.7 us: 1.01x faster                                                                                                  |
| xml_etree_parse      | 137 ms                                                                                                             | 135 ms: 1.01x faster                                                                                                   |
| unpickle_list        | 5.33 us                                                                                                            | 5.27 us: 1.01x faster                                                                                                  |
| json_dumps           | 9.37 ms                                                                                                            | 9.26 ms: 1.01x faster                                                                                                  |
| unpickle             | 14.1 us                                                                                                            | 14.2 us: 1.01x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 7.58 ms                                                                                                            | 7.61 ms: 1.00x slower                                                                                                  |
| python_startup         | 12.8 ms                                                                                                            | 12.9 ms: 1.00x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.00x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 11.9 ms                                                                                                            | 10.6 ms: 1.12x faster                                                                                                  |
| django_template | 35.5 ms                                                                                                            | 35.0 ms: 1.01x faster                                                                                                  |
| genshi_text     | 21.0 ms                                                                                                            | 21.5 ms: 1.02x slower                                                                                                  |
| genshi_xml      | 48.4 ms                                                                                                            | 52.4 ms: 1.08x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.01x faster                                                                                                           |

All benchmarks:
===============

| Benchmark                  | results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json | results/bm-20251122-3.15.0a2+-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json |
|----------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| sphinx                     | 971 ms                                                                                                             | 20.7 ms: 46.97x faster                                                                                                 |
| richards                   | 42.0 ms                                                                                                            | 20.6 ms: 2.04x faster                                                                                                  |
| richards_super             | 47.7 ms                                                                                                            | 24.5 ms: 1.95x faster                                                                                                  |
| bench_mp_pool              | 277 ms                                                                                                             | 217 ms: 1.28x faster                                                                                                   |
| logging_silent             | 102 ns                                                                                                             | 83.0 ns: 1.23x faster                                                                                                  |
| scimark_fft                | 310 ms                                                                                                             | 252 ms: 1.23x faster                                                                                                   |
| deltablue                  | 3.35 ms                                                                                                            | 2.84 ms: 1.18x faster                                                                                                  |
| gc_traversal               | 5.01 ms                                                                                                            | 4.26 ms: 1.18x faster                                                                                                  |
| float                      | 70.7 ms                                                                                                            | 60.2 ms: 1.17x faster                                                                                                  |
| unpickle_pure_python       | 208 us                                                                                                             | 181 us: 1.15x faster                                                                                                   |
| spectral_norm              | 93.0 ms                                                                                                            | 81.9 ms: 1.14x faster                                                                                                  |
| scimark_sor                | 107 ms                                                                                                             | 95.2 ms: 1.13x faster                                                                                                  |
| mako                       | 11.9 ms                                                                                                            | 10.6 ms: 1.12x faster                                                                                                  |
| pyflate                    | 420 ms                                                                                                             | 378 ms: 1.11x faster                                                                                                   |
| scimark_monte_carlo        | 61.0 ms                                                                                                            | 54.9 ms: 1.11x faster                                                                                                  |
| chaos                      | 57.4 ms                                                                                                            | 53.3 ms: 1.08x faster                                                                                                  |
| deepcopy_memo              | 26.6 us                                                                                                            | 24.8 us: 1.07x faster                                                                                                  |
| scimark_lu                 | 111 ms                                                                                                             | 104 ms: 1.07x faster                                                                                                   |
| fannkuch                   | 388 ms                                                                                                             | 362 ms: 1.07x faster                                                                                                   |
| pidigits                   | 205 ms                                                                                                             | 193 ms: 1.07x faster                                                                                                   |
| xml_etree_process          | 58.3 ms                                                                                                            | 54.9 ms: 1.06x faster                                                                                                  |
| thrift                     | 760 us                                                                                                             | 718 us: 1.06x faster                                                                                                   |
| xml_etree_generate         | 82.7 ms                                                                                                            | 78.5 ms: 1.05x faster                                                                                                  |
| bpe_tokeniser              | 4.19 sec                                                                                                           | 3.98 sec: 1.05x faster                                                                                                 |
| regex_effbot               | 2.71 ms                                                                                                            | 2.58 ms: 1.05x faster                                                                                                  |
| tomli_loads                | 1.92 sec                                                                                                           | 1.82 sec: 1.05x faster                                                                                                 |
| scimark_sparse_mat_mult    | 4.44 ms                                                                                                            | 4.24 ms: 1.05x faster                                                                                                  |
| sqlite_synth               | 2.25 us                                                                                                            | 2.15 us: 1.05x faster                                                                                                  |
| pickle_pure_python         | 308 us                                                                                                             | 296 us: 1.04x faster                                                                                                   |
| nbody                      | 87.9 ms                                                                                                            | 84.7 ms: 1.04x faster                                                                                                  |
| async_tree_cpu_io_mixed    | 500 ms                                                                                                             | 482 ms: 1.04x faster                                                                                                   |
| pickle_list                | 5.42 us                                                                                                            | 5.23 us: 1.04x faster                                                                                                  |
| deepcopy_reduce            | 2.64 us                                                                                                            | 2.56 us: 1.03x faster                                                                                                  |
| crypto_pyaes               | 68.5 ms                                                                                                            | 66.5 ms: 1.03x faster                                                                                                  |
| json_loads                 | 29.4 us                                                                                                            | 28.6 us: 1.03x faster                                                                                                  |
| go                         | 106 ms                                                                                                             | 103 ms: 1.03x faster                                                                                                   |
| async_tree_cpu_io_mixed_tg | 502 ms                                                                                                             | 489 ms: 1.03x faster                                                                                                   |
| pathlib                    | 18.1 ms                                                                                                            | 17.6 ms: 1.03x faster                                                                                                  |
| pickle_dict                | 32.7 us                                                                                                            | 31.9 us: 1.02x faster                                                                                                  |
| json                       | 5.15 ms                                                                                                            | 5.03 ms: 1.02x faster                                                                                                  |
| pprint_safe_repr           | 705 ms                                                                                                             | 689 ms: 1.02x faster                                                                                                   |
| logging_simple             | 5.98 us                                                                                                            | 5.89 us: 1.02x faster                                                                                                  |
| pprint_pformat             | 1.44 sec                                                                                                           | 1.42 sec: 1.01x faster                                                                                                 |
| django_template            | 35.5 ms                                                                                                            | 35.0 ms: 1.01x faster                                                                                                  |
| regex_dna                  | 175 ms                                                                                                             | 173 ms: 1.01x faster                                                                                                   |
| xml_etree_iterparse        | 87.1 ms                                                                                                            | 85.9 ms: 1.01x faster                                                                                                  |
| pickle                     | 12.9 us                                                                                                            | 12.7 us: 1.01x faster                                                                                                  |
| xml_etree_parse            | 137 ms                                                                                                             | 135 ms: 1.01x faster                                                                                                   |
| unpickle_list              | 5.33 us                                                                                                            | 5.27 us: 1.01x faster                                                                                                  |
| json_dumps                 | 9.37 ms                                                                                                            | 9.26 ms: 1.01x faster                                                                                                  |
| asyncio_tcp                | 488 ms                                                                                                             | 482 ms: 1.01x faster                                                                                                   |
| coroutines                 | 24.2 ms                                                                                                            | 24.0 ms: 1.01x faster                                                                                                  |
| meteor_contest             | 98.5 ms                                                                                                            | 97.9 ms: 1.01x faster                                                                                                  |
| coverage                   | 81.3 ms                                                                                                            | 81.5 ms: 1.00x slower                                                                                                  |
| python_startup_no_site     | 7.58 ms                                                                                                            | 7.61 ms: 1.00x slower                                                                                                  |
| python_startup             | 12.8 ms                                                                                                            | 12.9 ms: 1.00x slower                                                                                                  |
| asyncio_tcp_ssl            | 1.60 sec                                                                                                           | 1.61 sec: 1.01x slower                                                                                                 |
| unpickle                   | 14.1 us                                                                                                            | 14.2 us: 1.01x slower                                                                                                  |
| 2to3                       | 251 ms                                                                                                             | 253 ms: 1.01x slower                                                                                                   |
| create_gc_cycles           | 2.07 ms                                                                                                            | 2.10 ms: 1.01x slower                                                                                                  |
| sqlglot_v2_transpile       | 1.50 ms                                                                                                            | 1.52 ms: 1.01x slower                                                                                                  |
| subparsers                 | 44.3 ms                                                                                                            | 45.0 ms: 1.02x slower                                                                                                  |
| comprehensions             | 15.9 us                                                                                                            | 16.2 us: 1.02x slower                                                                                                  |
| regex_v8                   | 21.4 ms                                                                                                            | 21.7 ms: 1.02x slower                                                                                                  |
| telco                      | 158 ms                                                                                                             | 161 ms: 1.02x slower                                                                                                   |
| deepcopy                   | 247 us                                                                                                             | 251 us: 1.02x slower                                                                                                   |
| async_tree_memoization_tg  | 311 ms                                                                                                             | 318 ms: 1.02x slower                                                                                                   |
| genshi_text                | 21.0 ms                                                                                                            | 21.5 ms: 1.02x slower                                                                                                  |
| generators                 | 28.3 ms                                                                                                            | 29.0 ms: 1.02x slower                                                                                                  |
| async_generators           | 344 ms                                                                                                             | 354 ms: 1.03x slower                                                                                                   |
| pycparser                  | 1.07 sec                                                                                                           | 1.10 sec: 1.03x slower                                                                                                 |
| typing_runtime_protocols   | 151 us                                                                                                             | 156 us: 1.03x slower                                                                                                   |
| sqlglot_v2_parse           | 1.21 ms                                                                                                            | 1.25 ms: 1.03x slower                                                                                                  |
| raytrace                   | 254 ms                                                                                                             | 263 ms: 1.04x slower                                                                                                   |
| sqlglot_v2_optimize        | 51.0 ms                                                                                                            | 53.1 ms: 1.04x slower                                                                                                  |
| sqlglot_v2_normalize       | 102 ms                                                                                                             | 107 ms: 1.05x slower                                                                                                   |
| hexiom                     | 5.67 ms                                                                                                            | 5.99 ms: 1.06x slower                                                                                                  |
| many_optionals             | 1.21 ms                                                                                                            | 1.29 ms: 1.06x slower                                                                                                  |
| dulwich_log                | 69.5 ms                                                                                                            | 75.2 ms: 1.08x slower                                                                                                  |
| genshi_xml                 | 48.4 ms                                                                                                            | 52.4 ms: 1.08x slower                                                                                                  |
| nqueens                    | 78.2 ms                                                                                                            | 85.0 ms: 1.09x slower                                                                                                  |
| pylint                     | 287 ms                                                                                                             | 314 ms: 1.09x slower                                                                                                   |
| html5lib                   | 60.9 ms                                                                                                            | 67.1 ms: 1.10x slower                                                                                                  |
| sympy_expand               | 461 ms                                                                                                             | 511 ms: 1.11x slower                                                                                                   |
| sympy_sum                  | 155 ms                                                                                                             | 172 ms: 1.11x slower                                                                                                   |
| sympy_integrate            | 19.0 ms                                                                                                            | 21.3 ms: 1.12x slower                                                                                                  |
| sympy_str                  | 274 ms                                                                                                             | 313 ms: 1.14x slower                                                                                                   |
| mdp                        | 1.15 sec                                                                                                           | 1.37 sec: 1.18x slower                                                                                                 |
| unpack_sequence            | 42.1 ns                                                                                                            | 90.8 ns: 2.16x slower                                                                                                  |
| Geometric mean             | (ref)                                                                                                              | 1.06x faster                                                                                                           |

Benchmark hidden because not significant (9): async_tree_none, async_tree_none_tg, logging_format, regex_compile, asyncio_websockets, async_tree_io, async_tree_memoization, bench_thread_pool, async_tree_io_tg
Ignored benchmarks (1) of results/bm-20251122-3.15.0a2+-cde19e5/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2+-cde19e5.json: docutils

- Geometric mean (including insignificant results): 1.074x faster

# HPT report

- Reliability score: 92.96% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.02x