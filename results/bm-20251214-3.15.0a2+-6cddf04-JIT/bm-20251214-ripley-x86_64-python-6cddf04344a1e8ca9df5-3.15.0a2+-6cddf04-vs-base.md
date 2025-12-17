# Results vs. base

- fork: python
- ref: 6cddf04344a1e8ca9df5
- machine: linux-x86_64
- commit hash: 6cddf04
- commit date: 2025-12-14
- overall geometric mean: 1.030x faster
- HPT reliability: 84.29%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 250 ms                                                                                                             | 254 ms: 1.01x slower                                                                                                   |
| chameleon      | 13.2 ms                                                                                                            | 13.0 ms: 1.01x faster                                                                                                  |
| html5lib       | 60.0 ms                                                                                                            | 67.0 ms: 1.12x slower                                                                                                  |
| sphinx         | 976 ms                                                                                                             | 1.02 sec: 1.04x slower                                                                                                 |
| tornado_http   | 141 ms                                                                                                             | 143 ms: 1.02x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.03x slower                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp               | 441 ms                                                                                                             | 438 ms: 1.01x faster                                                                                                   |
| coroutines                | 23.8 ms                                                                                                            | 23.9 ms: 1.01x slower                                                                                                  |
| async_tree_memoization_tg | 308 ms                                                                                                             | 310 ms: 1.01x slower                                                                                                   |
| async_tree_io_tg          | 596 ms                                                                                                             | 600 ms: 1.01x slower                                                                                                   |
| async_tree_cpu_io_mixed   | 478 ms                                                                                                             | 486 ms: 1.02x slower                                                                                                   |
| async_generators          | 357 ms                                                                                                             | 375 ms: 1.05x slower                                                                                                   |
| Geometric mean            | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmark hidden because not significant (7): async_tree_none_tg, asyncio_websockets, asyncio_tcp_ssl, async_tree_memoization, async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 87.6 ms                                                                                                            | 71.6 ms: 1.22x faster                                                                                                  |
| float          | 71.0 ms                                                                                                            | 60.0 ms: 1.18x faster                                                                                                  |
| pidigits       | 206 ms                                                                                                             | 193 ms: 1.07x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.16x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 22.4 ms                                                                                                            | 21.2 ms: 1.05x faster                                                                                                  |
| regex_dna      | 177 ms                                                                                                             | 173 ms: 1.02x faster                                                                                                   |
| regex_effbot   | 2.78 ms                                                                                                            | 2.74 ms: 1.01x faster                                                                                                  |
| regex_compile  | 123 ms                                                                                                             | 123 ms: 1.00x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 214 us                                                                                                             | 184 us: 1.17x faster                                                                                                   |
| pickle_pure_python   | 314 us                                                                                                             | 286 us: 1.10x faster                                                                                                   |
| json_dumps           | 9.96 ms                                                                                                            | 9.34 ms: 1.07x faster                                                                                                  |
| xml_etree_generate   | 83.5 ms                                                                                                            | 78.5 ms: 1.06x faster                                                                                                  |
| unpickle_list        | 5.46 us                                                                                                            | 5.17 us: 1.06x faster                                                                                                  |
| xml_etree_process    | 58.5 ms                                                                                                            | 55.5 ms: 1.05x faster                                                                                                  |
| tomli_loads          | 2.13 sec                                                                                                           | 2.04 sec: 1.04x faster                                                                                                 |
| unpickle             | 15.0 us                                                                                                            | 14.7 us: 1.02x faster                                                                                                  |
| json_loads           | 28.1 us                                                                                                            | 28.0 us: 1.00x faster                                                                                                  |
| pickle               | 12.7 us                                                                                                            | 12.7 us: 1.00x faster                                                                                                  |
| pickle_list          | 5.22 us                                                                                                            | 5.25 us: 1.01x slower                                                                                                  |
| xml_etree_parse      | 133 ms                                                                                                             | 136 ms: 1.02x slower                                                                                                   |
| pickle_dict          | 32.1 us                                                                                                            | 32.8 us: 1.02x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 7.49 ms                                                                                                            | 7.59 ms: 1.01x slower                                                                                                  |
| python_startup         | 12.7 ms                                                                                                            | 12.9 ms: 1.02x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|-----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako            | 12.1 ms                                                                                                            | 10.6 ms: 1.15x faster                                                                                                  |
| django_template | 34.8 ms                                                                                                            | 35.5 ms: 1.02x slower                                                                                                  |
| genshi_xml      | 49.0 ms                                                                                                            | 51.1 ms: 1.04x slower                                                                                                  |
| Geometric mean  | (ref)                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (1): genshi_text

All benchmarks:
===============

| Benchmark                 | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                  | 42.3 ms                                                                                                            | 19.7 ms: 2.15x faster                                                                                                  |
| richards_super            | 48.3 ms                                                                                                            | 23.3 ms: 2.07x faster                                                                                                  |
| nbody                     | 87.6 ms                                                                                                            | 71.6 ms: 1.22x faster                                                                                                  |
| deltablue                 | 3.37 ms                                                                                                            | 2.77 ms: 1.21x faster                                                                                                  |
| bench_mp_pool             | 247 ms                                                                                                             | 207 ms: 1.19x faster                                                                                                   |
| float                     | 71.0 ms                                                                                                            | 60.0 ms: 1.18x faster                                                                                                  |
| logging_silent            | 99.9 ns                                                                                                            | 84.4 ns: 1.18x faster                                                                                                  |
| scimark_fft               | 304 ms                                                                                                             | 258 ms: 1.18x faster                                                                                                   |
| unpickle_pure_python      | 214 us                                                                                                             | 184 us: 1.17x faster                                                                                                   |
| scimark_monte_carlo       | 63.3 ms                                                                                                            | 55.0 ms: 1.15x faster                                                                                                  |
| mako                      | 12.1 ms                                                                                                            | 10.6 ms: 1.15x faster                                                                                                  |
| pyflate                   | 429 ms                                                                                                             | 382 ms: 1.12x faster                                                                                                   |
| scimark_sor               | 108 ms                                                                                                             | 97.2 ms: 1.11x faster                                                                                                  |
| spectral_norm             | 93.3 ms                                                                                                            | 84.4 ms: 1.11x faster                                                                                                  |
| fannkuch                  | 398 ms                                                                                                             | 362 ms: 1.10x faster                                                                                                   |
| pickle_pure_python        | 314 us                                                                                                             | 286 us: 1.10x faster                                                                                                   |
| gc_traversal              | 4.82 ms                                                                                                            | 4.45 ms: 1.08x faster                                                                                                  |
| go                        | 106 ms                                                                                                             | 98.1 ms: 1.08x faster                                                                                                  |
| chaos                     | 56.4 ms                                                                                                            | 52.6 ms: 1.07x faster                                                                                                  |
| deepcopy_memo             | 26.3 us                                                                                                            | 24.5 us: 1.07x faster                                                                                                  |
| pidigits                  | 206 ms                                                                                                             | 193 ms: 1.07x faster                                                                                                   |
| json_dumps                | 9.96 ms                                                                                                            | 9.34 ms: 1.07x faster                                                                                                  |
| xml_etree_generate        | 83.5 ms                                                                                                            | 78.5 ms: 1.06x faster                                                                                                  |
| unpickle_list             | 5.46 us                                                                                                            | 5.17 us: 1.06x faster                                                                                                  |
| crypto_pyaes              | 70.4 ms                                                                                                            | 66.7 ms: 1.06x faster                                                                                                  |
| regex_v8                  | 22.4 ms                                                                                                            | 21.2 ms: 1.05x faster                                                                                                  |
| xml_etree_process         | 58.5 ms                                                                                                            | 55.5 ms: 1.05x faster                                                                                                  |
| tomli_loads               | 2.13 sec                                                                                                           | 2.04 sec: 1.04x faster                                                                                                 |
| pprint_safe_repr          | 697 ms                                                                                                             | 667 ms: 1.04x faster                                                                                                   |
| meteor_contest            | 103 ms                                                                                                             | 98.3 ms: 1.04x faster                                                                                                  |
| bpe_tokeniser             | 4.20 sec                                                                                                           | 4.05 sec: 1.04x faster                                                                                                 |
| json                      | 5.10 ms                                                                                                            | 4.92 ms: 1.04x faster                                                                                                  |
| deepcopy_reduce           | 2.64 us                                                                                                            | 2.55 us: 1.03x faster                                                                                                  |
| pprint_pformat            | 1.42 sec                                                                                                           | 1.38 sec: 1.03x faster                                                                                                 |
| connected_components      | 376 ms                                                                                                             | 365 ms: 1.03x faster                                                                                                   |
| scimark_lu                | 109 ms                                                                                                             | 107 ms: 1.02x faster                                                                                                   |
| k_core                    | 1.84 sec                                                                                                           | 1.80 sec: 1.02x faster                                                                                                 |
| regex_dna                 | 177 ms                                                                                                             | 173 ms: 1.02x faster                                                                                                   |
| deepcopy                  | 243 us                                                                                                             | 238 us: 1.02x faster                                                                                                   |
| thrift                    | 758 us                                                                                                             | 743 us: 1.02x faster                                                                                                   |
| coverage                  | 83.3 ms                                                                                                            | 81.7 ms: 1.02x faster                                                                                                  |
| unpickle                  | 15.0 us                                                                                                            | 14.7 us: 1.02x faster                                                                                                  |
| shortest_path             | 416 ms                                                                                                             | 409 ms: 1.02x faster                                                                                                   |
| sqlite_synth              | 2.28 us                                                                                                            | 2.25 us: 1.01x faster                                                                                                  |
| chameleon                 | 13.2 ms                                                                                                            | 13.0 ms: 1.01x faster                                                                                                  |
| regex_effbot              | 2.78 ms                                                                                                            | 2.74 ms: 1.01x faster                                                                                                  |
| logging_simple            | 5.91 us                                                                                                            | 5.82 us: 1.01x faster                                                                                                  |
| logging_format            | 6.65 us                                                                                                            | 6.57 us: 1.01x faster                                                                                                  |
| asyncio_tcp               | 441 ms                                                                                                             | 438 ms: 1.01x faster                                                                                                   |
| scimark_sparse_mat_mult   | 4.34 ms                                                                                                            | 4.32 ms: 1.00x faster                                                                                                  |
| json_loads                | 28.1 us                                                                                                            | 28.0 us: 1.00x faster                                                                                                  |
| pickle                    | 12.7 us                                                                                                            | 12.7 us: 1.00x faster                                                                                                  |
| regex_compile             | 123 ms                                                                                                             | 123 ms: 1.00x faster                                                                                                   |
| coroutines                | 23.8 ms                                                                                                            | 23.9 ms: 1.01x slower                                                                                                  |
| bench_thread_pool         | 1.22 ms                                                                                                            | 1.23 ms: 1.01x slower                                                                                                  |
| pickle_list               | 5.22 us                                                                                                            | 5.25 us: 1.01x slower                                                                                                  |
| async_tree_memoization_tg | 308 ms                                                                                                             | 310 ms: 1.01x slower                                                                                                   |
| async_tree_io_tg          | 596 ms                                                                                                             | 600 ms: 1.01x slower                                                                                                   |
| subparsers                | 9.30 ms                                                                                                            | 9.41 ms: 1.01x slower                                                                                                  |
| python_startup_no_site    | 7.49 ms                                                                                                            | 7.59 ms: 1.01x slower                                                                                                  |
| 2to3                      | 250 ms                                                                                                             | 254 ms: 1.01x slower                                                                                                   |
| python_startup            | 12.7 ms                                                                                                            | 12.9 ms: 1.02x slower                                                                                                  |
| sqlalchemy_imperative     | 20.7 ms                                                                                                            | 21.1 ms: 1.02x slower                                                                                                  |
| comprehensions            | 16.1 us                                                                                                            | 16.4 us: 1.02x slower                                                                                                  |
| typing_runtime_protocols  | 155 us                                                                                                             | 158 us: 1.02x slower                                                                                                   |
| async_tree_cpu_io_mixed   | 478 ms                                                                                                             | 486 ms: 1.02x slower                                                                                                   |
| tornado_http              | 141 ms                                                                                                             | 143 ms: 1.02x slower                                                                                                   |
| telco                     | 157 ms                                                                                                             | 161 ms: 1.02x slower                                                                                                   |
| xml_etree_parse           | 133 ms                                                                                                             | 136 ms: 1.02x slower                                                                                                   |
| django_template           | 34.8 ms                                                                                                            | 35.5 ms: 1.02x slower                                                                                                  |
| sqlglot_v2_parse          | 1.21 ms                                                                                                            | 1.23 ms: 1.02x slower                                                                                                  |
| pickle_dict               | 32.1 us                                                                                                            | 32.8 us: 1.02x slower                                                                                                  |
| sqlalchemy_declarative    | 130 ms                                                                                                             | 133 ms: 1.03x slower                                                                                                   |
| raytrace                  | 253 ms                                                                                                             | 260 ms: 1.03x slower                                                                                                   |
| sqlglot_v2_transpile      | 1.49 ms                                                                                                            | 1.53 ms: 1.03x slower                                                                                                  |
| xdsl_constant_fold        | 44.4 ms                                                                                                            | 45.9 ms: 1.03x slower                                                                                                  |
| sphinx                    | 976 ms                                                                                                             | 1.02 sec: 1.04x slower                                                                                                 |
| genshi_xml                | 49.0 ms                                                                                                            | 51.1 ms: 1.04x slower                                                                                                  |
| many_optionals            | 944 us                                                                                                             | 984 us: 1.04x slower                                                                                                   |
| pycparser                 | 1.08 sec                                                                                                           | 1.12 sec: 1.04x slower                                                                                                 |
| dulwich_log               | 68.4 ms                                                                                                            | 71.5 ms: 1.04x slower                                                                                                  |
| hexiom                    | 5.80 ms                                                                                                            | 6.07 ms: 1.05x slower                                                                                                  |
| async_generators          | 357 ms                                                                                                             | 375 ms: 1.05x slower                                                                                                   |
| generators                | 27.2 ms                                                                                                            | 28.8 ms: 1.06x slower                                                                                                  |
| sqlglot_v2_normalize      | 103 ms                                                                                                             | 109 ms: 1.06x slower                                                                                                   |
| sqlglot_v2_optimize       | 50.9 ms                                                                                                            | 54.5 ms: 1.07x slower                                                                                                  |
| nqueens                   | 79.6 ms                                                                                                            | 86.6 ms: 1.09x slower                                                                                                  |
| pylint                    | 286 ms                                                                                                             | 311 ms: 1.09x slower                                                                                                   |
| html5lib                  | 60.0 ms                                                                                                            | 67.0 ms: 1.12x slower                                                                                                  |
| mdp                       | 1.17 sec                                                                                                           | 1.35 sec: 1.16x slower                                                                                                 |
| unpack_sequence           | 47.6 ns                                                                                                            | 81.9 ns: 1.72x slower                                                                                                  |
| Geometric mean            | (ref)                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (11): async_tree_none_tg, genshi_text, xml_etree_iterparse, pathlib, asyncio_websockets, asyncio_tcp_ssl, create_gc_cycles, async_tree_memoization, async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_io
Ignored benchmarks (5) of results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-ripley-x86_64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.030x faster

# HPT report

- Reliability score: 84.29% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x