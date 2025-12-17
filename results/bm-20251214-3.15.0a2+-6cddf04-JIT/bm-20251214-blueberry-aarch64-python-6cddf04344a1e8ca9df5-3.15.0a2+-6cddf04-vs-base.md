# Results vs. base

- fork: python
- ref: 6cddf04344a1e8ca9df5
- machine: linux-aarch64
- commit hash: 6cddf04
- commit date: 2025-12-14
- overall geometric mean: 1.036x faster
- HPT reliability: 99.14%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 429 ms                                                                                                                 | 430 ms: 1.00x slower                                                                                                       |
| chameleon      | 22.1 ms                                                                                                                | 21.5 ms: 1.03x faster                                                                                                      |
| html5lib       | 82.5 ms                                                                                                                | 95.8 ms: 1.16x slower                                                                                                      |
| sphinx         | 1.58 sec                                                                                                               | 1.62 sec: 1.03x slower                                                                                                     |
| tornado_http   | 176 ms                                                                                                                 | 170 ms: 1.03x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg        | 550 ms                                                                                                                 | 526 ms: 1.05x faster                                                                                                       |
| asyncio_tcp               | 1.14 sec                                                                                                               | 1.09 sec: 1.04x faster                                                                                                     |
| coroutines                | 42.0 ms                                                                                                                | 40.7 ms: 1.03x faster                                                                                                      |
| asyncio_websockets        | 913 ms                                                                                                                 | 895 ms: 1.02x faster                                                                                                       |
| asyncio_tcp_ssl           | 4.22 sec                                                                                                               | 4.18 sec: 1.01x faster                                                                                                     |
| async_tree_io_tg          | 1.26 sec                                                                                                               | 1.29 sec: 1.02x slower                                                                                                     |
| async_tree_memoization_tg | 659 ms                                                                                                                 | 680 ms: 1.03x slower                                                                                                       |
| async_generators          | 586 ms                                                                                                                 | 625 ms: 1.07x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 163 ms                                                                                                                 | 125 ms: 1.31x faster                                                                                                       |
| float          | 135 ms                                                                                                                 | 115 ms: 1.18x faster                                                                                                       |
| pidigits       | 346 ms                                                                                                                 | 330 ms: 1.05x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.17x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.80 ms                                                                                                                | 4.48 ms: 1.07x faster                                                                                                      |
| regex_v8       | 38.2 ms                                                                                                                | 36.3 ms: 1.05x faster                                                                                                      |
| regex_dna      | 303 ms                                                                                                                 | 288 ms: 1.05x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 347 us                                                                                                                 | 269 us: 1.29x faster                                                                                                       |
| pickle_pure_python   | 474 us                                                                                                                 | 413 us: 1.15x faster                                                                                                       |
| xml_etree_generate   | 146 ms                                                                                                                 | 128 ms: 1.14x faster                                                                                                       |
| tomli_loads          | 3.63 sec                                                                                                               | 3.27 sec: 1.11x faster                                                                                                     |
| xml_etree_parse      | 269 ms                                                                                                                 | 246 ms: 1.09x faster                                                                                                       |
| xml_etree_process    | 107 ms                                                                                                                 | 98.3 ms: 1.09x faster                                                                                                      |
| json_dumps           | 15.6 ms                                                                                                                | 14.4 ms: 1.08x faster                                                                                                      |
| pickle               | 19.9 us                                                                                                                | 18.4 us: 1.08x faster                                                                                                      |
| unpickle             | 25.2 us                                                                                                                | 23.4 us: 1.08x faster                                                                                                      |
| pickle_list          | 7.34 us                                                                                                                | 6.82 us: 1.08x faster                                                                                                      |
| unpickle_list        | 8.77 us                                                                                                                | 8.24 us: 1.06x faster                                                                                                      |
| json_loads           | 41.5 us                                                                                                                | 39.8 us: 1.04x faster                                                                                                      |
| pickle_dict          | 49.4 us                                                                                                                | 47.4 us: 1.04x faster                                                                                                      |
| xml_etree_iterparse  | 208 ms                                                                                                                 | 200 ms: 1.04x faster                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.10x faster                                                                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.6 ms                                                                                                                | 18.0 ms: 1.03x faster                                                                                                      |
| python_startup_no_site | 11.0 ms                                                                                                                | 10.6 ms: 1.03x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 20.9 ms                                                                                                                | 18.0 ms: 1.17x faster                                                                                                      |
| genshi_text    | 35.7 ms                                                                                                                | 38.4 ms: 1.08x slower                                                                                                      |
| genshi_xml     | 80.9 ms                                                                                                                | 107 ms: 1.33x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                 | results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json | results/bm-20251214-3.15.0a2+-6cddf04-JIT/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 69.4 ms                                                                                                                | 46.9 ms: 1.48x faster                                                                                                      |
| richards_super            | 77.6 ms                                                                                                                | 52.7 ms: 1.47x faster                                                                                                      |
| logging_silent            | 174 ns                                                                                                                 | 127 ns: 1.37x faster                                                                                                       |
| nbody                     | 163 ms                                                                                                                 | 125 ms: 1.31x faster                                                                                                       |
| unpickle_pure_python      | 347 us                                                                                                                 | 269 us: 1.29x faster                                                                                                       |
| scimark_fft               | 520 ms                                                                                                                 | 425 ms: 1.22x faster                                                                                                       |
| scimark_sor               | 192 ms                                                                                                                 | 160 ms: 1.20x faster                                                                                                       |
| deltablue                 | 5.52 ms                                                                                                                | 4.68 ms: 1.18x faster                                                                                                      |
| float                     | 135 ms                                                                                                                 | 115 ms: 1.18x faster                                                                                                       |
| scimark_monte_carlo       | 106 ms                                                                                                                 | 90.7 ms: 1.17x faster                                                                                                      |
| deepcopy_memo             | 43.5 us                                                                                                                | 37.3 us: 1.17x faster                                                                                                      |
| mako                      | 20.9 ms                                                                                                                | 18.0 ms: 1.17x faster                                                                                                      |
| spectral_norm             | 162 ms                                                                                                                 | 140 ms: 1.16x faster                                                                                                       |
| pickle_pure_python        | 474 us                                                                                                                 | 413 us: 1.15x faster                                                                                                       |
| xml_etree_generate        | 146 ms                                                                                                                 | 128 ms: 1.14x faster                                                                                                       |
| scimark_lu                | 187 ms                                                                                                                 | 167 ms: 1.12x faster                                                                                                       |
| scimark_sparse_mat_mult   | 8.66 ms                                                                                                                | 7.77 ms: 1.11x faster                                                                                                      |
| pyflate                   | 794 ms                                                                                                                 | 715 ms: 1.11x faster                                                                                                       |
| tomli_loads               | 3.63 sec                                                                                                               | 3.27 sec: 1.11x faster                                                                                                     |
| fannkuch                  | 660 ms                                                                                                                 | 602 ms: 1.10x faster                                                                                                       |
| bpe_tokeniser             | 7.76 sec                                                                                                               | 7.10 sec: 1.09x faster                                                                                                     |
| xml_etree_parse           | 269 ms                                                                                                                 | 246 ms: 1.09x faster                                                                                                       |
| xml_etree_process         | 107 ms                                                                                                                 | 98.3 ms: 1.09x faster                                                                                                      |
| json_dumps                | 15.6 ms                                                                                                                | 14.4 ms: 1.08x faster                                                                                                      |
| pickle                    | 19.9 us                                                                                                                | 18.4 us: 1.08x faster                                                                                                      |
| logging_simple            | 9.03 us                                                                                                                | 8.36 us: 1.08x faster                                                                                                      |
| sqlite_synth              | 4.93 us                                                                                                                | 4.57 us: 1.08x faster                                                                                                      |
| unpickle                  | 25.2 us                                                                                                                | 23.4 us: 1.08x faster                                                                                                      |
| pickle_list               | 7.34 us                                                                                                                | 6.82 us: 1.08x faster                                                                                                      |
| regex_effbot              | 4.80 ms                                                                                                                | 4.48 ms: 1.07x faster                                                                                                      |
| raytrace                  | 427 ms                                                                                                                 | 399 ms: 1.07x faster                                                                                                       |
| json                      | 7.31 ms                                                                                                                | 6.86 ms: 1.07x faster                                                                                                      |
| unpickle_list             | 8.77 us                                                                                                                | 8.24 us: 1.06x faster                                                                                                      |
| meteor_contest            | 148 ms                                                                                                                 | 140 ms: 1.06x faster                                                                                                       |
| telco                     | 216 ms                                                                                                                 | 204 ms: 1.06x faster                                                                                                       |
| regex_v8                  | 38.2 ms                                                                                                                | 36.3 ms: 1.05x faster                                                                                                      |
| sqlalchemy_declarative    | 173 ms                                                                                                                 | 164 ms: 1.05x faster                                                                                                       |
| regex_dna                 | 303 ms                                                                                                                 | 288 ms: 1.05x faster                                                                                                       |
| pidigits                  | 346 ms                                                                                                                 | 330 ms: 1.05x faster                                                                                                       |
| thrift                    | 1.23 ms                                                                                                                | 1.18 ms: 1.05x faster                                                                                                      |
| async_tree_none_tg        | 550 ms                                                                                                                 | 526 ms: 1.05x faster                                                                                                       |
| json_loads                | 41.5 us                                                                                                                | 39.8 us: 1.04x faster                                                                                                      |
| pickle_dict               | 49.4 us                                                                                                                | 47.4 us: 1.04x faster                                                                                                      |
| xml_etree_iterparse       | 208 ms                                                                                                                 | 200 ms: 1.04x faster                                                                                                       |
| asyncio_tcp               | 1.14 sec                                                                                                               | 1.09 sec: 1.04x faster                                                                                                     |
| pprint_safe_repr          | 1.15 sec                                                                                                               | 1.11 sec: 1.04x faster                                                                                                     |
| tornado_http              | 176 ms                                                                                                                 | 170 ms: 1.03x faster                                                                                                       |
| python_startup            | 18.6 ms                                                                                                                | 18.0 ms: 1.03x faster                                                                                                      |
| coroutines                | 42.0 ms                                                                                                                | 40.7 ms: 1.03x faster                                                                                                      |
| generators                | 52.1 ms                                                                                                                | 50.4 ms: 1.03x faster                                                                                                      |
| sqlglot_v2_parse          | 1.82 ms                                                                                                                | 1.76 ms: 1.03x faster                                                                                                      |
| logging_format            | 9.62 us                                                                                                                | 9.32 us: 1.03x faster                                                                                                      |
| python_startup_no_site    | 11.0 ms                                                                                                                | 10.6 ms: 1.03x faster                                                                                                      |
| connected_components      | 854 ms                                                                                                                 | 829 ms: 1.03x faster                                                                                                       |
| chameleon                 | 22.1 ms                                                                                                                | 21.5 ms: 1.03x faster                                                                                                      |
| gc_traversal              | 15.2 ms                                                                                                                | 14.7 ms: 1.03x faster                                                                                                      |
| shortest_path             | 902 ms                                                                                                                 | 883 ms: 1.02x faster                                                                                                       |
| create_gc_cycles          | 9.32 ms                                                                                                                | 9.14 ms: 1.02x faster                                                                                                      |
| asyncio_websockets        | 913 ms                                                                                                                 | 895 ms: 1.02x faster                                                                                                       |
| pprint_pformat            | 2.34 sec                                                                                                               | 2.29 sec: 1.02x faster                                                                                                     |
| asyncio_tcp_ssl           | 4.22 sec                                                                                                               | 4.18 sec: 1.01x faster                                                                                                     |
| k_core                    | 4.10 sec                                                                                                               | 4.07 sec: 1.01x faster                                                                                                     |
| 2to3                      | 429 ms                                                                                                                 | 430 ms: 1.00x slower                                                                                                       |
| async_tree_io_tg          | 1.26 sec                                                                                                               | 1.29 sec: 1.02x slower                                                                                                     |
| pycparser                 | 1.62 sec                                                                                                               | 1.66 sec: 1.03x slower                                                                                                     |
| sphinx                    | 1.58 sec                                                                                                               | 1.62 sec: 1.03x slower                                                                                                     |
| async_tree_memoization_tg | 659 ms                                                                                                                 | 680 ms: 1.03x slower                                                                                                       |
| pylint                    | 436 ms                                                                                                                 | 450 ms: 1.03x slower                                                                                                       |
| chaos                     | 88.9 ms                                                                                                                | 92.5 ms: 1.04x slower                                                                                                      |
| go                        | 172 ms                                                                                                                 | 181 ms: 1.05x slower                                                                                                       |
| hexiom                    | 9.61 ms                                                                                                                | 10.2 ms: 1.07x slower                                                                                                      |
| async_generators          | 586 ms                                                                                                                 | 625 ms: 1.07x slower                                                                                                       |
| many_optionals            | 936 us                                                                                                                 | 999 us: 1.07x slower                                                                                                       |
| genshi_text               | 35.7 ms                                                                                                                | 38.4 ms: 1.08x slower                                                                                                      |
| deepcopy                  | 401 us                                                                                                                 | 432 us: 1.08x slower                                                                                                       |
| mdp                       | 2.51 sec                                                                                                               | 2.80 sec: 1.12x slower                                                                                                     |
| nqueens                   | 123 ms                                                                                                                 | 141 ms: 1.14x slower                                                                                                       |
| html5lib                  | 82.5 ms                                                                                                                | 95.8 ms: 1.16x slower                                                                                                      |
| dulwich_log               | 67.3 ms                                                                                                                | 78.8 ms: 1.17x slower                                                                                                      |
| unpack_sequence           | 69.1 ns                                                                                                                | 86.8 ns: 1.26x slower                                                                                                      |
| genshi_xml                | 80.9 ms                                                                                                                | 107 ms: 1.33x slower                                                                                                       |
| bench_mp_pool             | 174 ms                                                                                                                 | 243 ms: 1.40x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmark hidden because not significant (20): typing_runtime_protocols, crypto_pyaes, subparsers, sqlalchemy_imperative, bench_thread_pool, async_tree_cpu_io_mixed_tg, sqlglot_v2_optimize, async_tree_none, pathlib, sqlglot_v2_transpile, regex_compile, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_io, sqlglot_v2_normalize, comprehensions, deepcopy_reduce, coverage, xdsl_constant_fold, django_template
Ignored benchmarks (5) of results/bm-20251214-3.15.0a2+-6cddf04/bm-20251214-blueberry-aarch64-python-6cddf04344a1e8ca9df5-3.15.0a2+-6cddf04.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.036x faster

# HPT report

- Reliability score: 99.14% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x