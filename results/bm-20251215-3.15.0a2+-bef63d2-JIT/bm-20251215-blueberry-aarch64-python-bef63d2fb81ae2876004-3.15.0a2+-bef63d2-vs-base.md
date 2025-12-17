# Results vs. base

- fork: python
- ref: bef63d2fb81ae2876004
- machine: linux-aarch64
- commit hash: bef63d2
- commit date: 2025-12-15
- overall geometric mean: 1.024x faster
- HPT reliability: 96.91%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| html5lib       | 81.6 ms                                                                                                                | 97.3 ms: 1.19x slower                                                                                                      |
| sphinx         | 1.55 sec                                                                                                               | 1.61 sec: 1.04x slower                                                                                                     |
| tornado_http   | 171 ms                                                                                                                 | 168 ms: 1.02x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (2): 2to3, chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp               | 1.15 sec                                                                                                               | 1.09 sec: 1.05x faster                                                                                                     |
| coroutines                | 41.7 ms                                                                                                                | 40.6 ms: 1.03x faster                                                                                                      |
| asyncio_websockets        | 914 ms                                                                                                                 | 903 ms: 1.01x faster                                                                                                       |
| async_generators          | 599 ms                                                                                                                 | 629 ms: 1.05x slower                                                                                                       |
| async_tree_memoization_tg | 662 ms                                                                                                                 | 696 ms: 1.05x slower                                                                                                       |
| async_tree_io_tg          | 1.24 sec                                                                                                               | 1.31 sec: 1.06x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (7): async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_none, asyncio_tcp_ssl, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 176 ms                                                                                                                 | 140 ms: 1.26x faster                                                                                                       |
| float          | 135 ms                                                                                                                 | 118 ms: 1.14x faster                                                                                                       |
| pidigits       | 345 ms                                                                                                                 | 326 ms: 1.06x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.15x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 38.3 ms                                                                                                                | 35.9 ms: 1.07x faster                                                                                                      |
| regex_effbot   | 4.74 ms                                                                                                                | 4.53 ms: 1.04x faster                                                                                                      |
| regex_dna      | 296 ms                                                                                                                 | 287 ms: 1.03x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 342 us                                                                                                                 | 266 us: 1.29x faster                                                                                                       |
| pickle_pure_python   | 478 us                                                                                                                 | 414 us: 1.16x faster                                                                                                       |
| xml_etree_process    | 108 ms                                                                                                                 | 96.7 ms: 1.12x faster                                                                                                      |
| tomli_loads          | 3.51 sec                                                                                                               | 3.19 sec: 1.10x faster                                                                                                     |
| xml_etree_generate   | 141 ms                                                                                                                 | 130 ms: 1.09x faster                                                                                                       |
| json_dumps           | 15.6 ms                                                                                                                | 14.5 ms: 1.08x faster                                                                                                      |
| pickle_dict          | 49.9 us                                                                                                                | 47.6 us: 1.05x faster                                                                                                      |
| pickle_list          | 7.16 us                                                                                                                | 6.85 us: 1.05x faster                                                                                                      |
| unpickle_list        | 8.65 us                                                                                                                | 8.32 us: 1.04x faster                                                                                                      |
| unpickle             | 23.9 us                                                                                                                | 23.1 us: 1.04x faster                                                                                                      |
| pickle               | 19.7 us                                                                                                                | 19.1 us: 1.03x faster                                                                                                      |
| xml_etree_iterparse  | 207 ms                                                                                                                 | 200 ms: 1.03x faster                                                                                                       |
| xml_etree_parse      | 257 ms                                                                                                                 | 251 ms: 1.02x faster                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.08x faster                                                                                                               |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.5 ms                                                                                                                | 17.8 ms: 1.04x faster                                                                                                      |
| python_startup_no_site | 10.8 ms                                                                                                                | 10.5 ms: 1.03x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 20.9 ms                                                                                                                | 18.6 ms: 1.12x faster                                                                                                      |
| genshi_text    | 35.7 ms                                                                                                                | 39.6 ms: 1.11x slower                                                                                                      |
| genshi_xml     | 80.7 ms                                                                                                                | 108 ms: 1.34x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.07x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                 | results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json | results/bm-20251215-3.15.0a2+-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards_super            | 77.1 ms                                                                                                                | 50.0 ms: 1.54x faster                                                                                                      |
| richards                  | 66.6 ms                                                                                                                | 44.0 ms: 1.51x faster                                                                                                      |
| logging_silent            | 179 ns                                                                                                                 | 129 ns: 1.39x faster                                                                                                       |
| unpickle_pure_python      | 342 us                                                                                                                 | 266 us: 1.29x faster                                                                                                       |
| nbody                     | 176 ms                                                                                                                 | 140 ms: 1.26x faster                                                                                                       |
| scimark_sor               | 186 ms                                                                                                                 | 157 ms: 1.19x faster                                                                                                       |
| scimark_fft               | 519 ms                                                                                                                 | 438 ms: 1.19x faster                                                                                                       |
| pickle_pure_python        | 478 us                                                                                                                 | 414 us: 1.16x faster                                                                                                       |
| float                     | 135 ms                                                                                                                 | 118 ms: 1.14x faster                                                                                                       |
| pyflate                   | 779 ms                                                                                                                 | 686 ms: 1.13x faster                                                                                                       |
| deltablue                 | 5.31 ms                                                                                                                | 4.68 ms: 1.13x faster                                                                                                      |
| scimark_monte_carlo       | 104 ms                                                                                                                 | 91.8 ms: 1.13x faster                                                                                                      |
| mako                      | 20.9 ms                                                                                                                | 18.6 ms: 1.12x faster                                                                                                      |
| xml_etree_process         | 108 ms                                                                                                                 | 96.7 ms: 1.12x faster                                                                                                      |
| spectral_norm             | 163 ms                                                                                                                 | 147 ms: 1.11x faster                                                                                                       |
| tomli_loads               | 3.51 sec                                                                                                               | 3.19 sec: 1.10x faster                                                                                                     |
| deepcopy_memo             | 43.7 us                                                                                                                | 39.9 us: 1.09x faster                                                                                                      |
| scimark_lu                | 183 ms                                                                                                                 | 168 ms: 1.09x faster                                                                                                       |
| xml_etree_generate        | 141 ms                                                                                                                 | 130 ms: 1.09x faster                                                                                                       |
| scimark_sparse_mat_mult   | 8.89 ms                                                                                                                | 8.18 ms: 1.09x faster                                                                                                      |
| sqlite_synth              | 4.90 us                                                                                                                | 4.51 us: 1.08x faster                                                                                                      |
| fannkuch                  | 644 ms                                                                                                                 | 594 ms: 1.08x faster                                                                                                       |
| json_dumps                | 15.6 ms                                                                                                                | 14.5 ms: 1.08x faster                                                                                                      |
| bpe_tokeniser             | 7.63 sec                                                                                                               | 7.13 sec: 1.07x faster                                                                                                     |
| regex_v8                  | 38.3 ms                                                                                                                | 35.9 ms: 1.07x faster                                                                                                      |
| pidigits                  | 345 ms                                                                                                                 | 326 ms: 1.06x faster                                                                                                       |
| thrift                    | 1.22 ms                                                                                                                | 1.15 ms: 1.06x faster                                                                                                      |
| asyncio_tcp               | 1.15 sec                                                                                                               | 1.09 sec: 1.05x faster                                                                                                     |
| pickle_dict               | 49.9 us                                                                                                                | 47.6 us: 1.05x faster                                                                                                      |
| json                      | 7.29 ms                                                                                                                | 6.97 ms: 1.05x faster                                                                                                      |
| pickle_list               | 7.16 us                                                                                                                | 6.85 us: 1.05x faster                                                                                                      |
| regex_effbot              | 4.74 ms                                                                                                                | 4.53 ms: 1.04x faster                                                                                                      |
| python_startup            | 18.5 ms                                                                                                                | 17.8 ms: 1.04x faster                                                                                                      |
| unpickle_list             | 8.65 us                                                                                                                | 8.32 us: 1.04x faster                                                                                                      |
| unpickle                  | 23.9 us                                                                                                                | 23.1 us: 1.04x faster                                                                                                      |
| regex_dna                 | 296 ms                                                                                                                 | 287 ms: 1.03x faster                                                                                                       |
| pickle                    | 19.7 us                                                                                                                | 19.1 us: 1.03x faster                                                                                                      |
| xml_etree_iterparse       | 207 ms                                                                                                                 | 200 ms: 1.03x faster                                                                                                       |
| sqlalchemy_declarative    | 168 ms                                                                                                                 | 163 ms: 1.03x faster                                                                                                       |
| sqlglot_v2_parse          | 1.77 ms                                                                                                                | 1.72 ms: 1.03x faster                                                                                                      |
| python_startup_no_site    | 10.8 ms                                                                                                                | 10.5 ms: 1.03x faster                                                                                                      |
| coroutines                | 41.7 ms                                                                                                                | 40.6 ms: 1.03x faster                                                                                                      |
| generators                | 52.9 ms                                                                                                                | 51.5 ms: 1.03x faster                                                                                                      |
| telco                     | 203 ms                                                                                                                 | 198 ms: 1.03x faster                                                                                                       |
| xml_etree_parse           | 257 ms                                                                                                                 | 251 ms: 1.02x faster                                                                                                       |
| connected_components      | 852 ms                                                                                                                 | 833 ms: 1.02x faster                                                                                                       |
| tornado_http              | 171 ms                                                                                                                 | 168 ms: 1.02x faster                                                                                                       |
| shortest_path             | 898 ms                                                                                                                 | 885 ms: 1.01x faster                                                                                                       |
| asyncio_websockets        | 914 ms                                                                                                                 | 903 ms: 1.01x faster                                                                                                       |
| k_core                    | 4.09 sec                                                                                                               | 4.05 sec: 1.01x faster                                                                                                     |
| pathlib                   | 22.7 ms                                                                                                                | 22.5 ms: 1.01x faster                                                                                                      |
| gc_traversal              | 15.0 ms                                                                                                                | 14.9 ms: 1.01x faster                                                                                                      |
| pycparser                 | 1.59 sec                                                                                                               | 1.61 sec: 1.02x slower                                                                                                     |
| pylint                    | 435 ms                                                                                                                 | 448 ms: 1.03x slower                                                                                                       |
| sphinx                    | 1.55 sec                                                                                                               | 1.61 sec: 1.04x slower                                                                                                     |
| comprehensions            | 27.0 us                                                                                                                | 28.3 us: 1.05x slower                                                                                                      |
| async_generators          | 599 ms                                                                                                                 | 629 ms: 1.05x slower                                                                                                       |
| async_tree_memoization_tg | 662 ms                                                                                                                 | 696 ms: 1.05x slower                                                                                                       |
| chaos                     | 91.5 ms                                                                                                                | 96.3 ms: 1.05x slower                                                                                                      |
| async_tree_io_tg          | 1.24 sec                                                                                                               | 1.31 sec: 1.06x slower                                                                                                     |
| go                        | 173 ms                                                                                                                 | 184 ms: 1.06x slower                                                                                                       |
| many_optionals            | 929 us                                                                                                                 | 998 us: 1.07x slower                                                                                                       |
| hexiom                    | 9.21 ms                                                                                                                | 10.1 ms: 1.10x slower                                                                                                      |
| nqueens                   | 125 ms                                                                                                                 | 139 ms: 1.11x slower                                                                                                       |
| deepcopy                  | 385 us                                                                                                                 | 428 us: 1.11x slower                                                                                                       |
| genshi_text               | 35.7 ms                                                                                                                | 39.6 ms: 1.11x slower                                                                                                      |
| mdp                       | 2.56 sec                                                                                                               | 2.90 sec: 1.13x slower                                                                                                     |
| unpack_sequence           | 71.5 ns                                                                                                                | 82.4 ns: 1.15x slower                                                                                                      |
| html5lib                  | 81.6 ms                                                                                                                | 97.3 ms: 1.19x slower                                                                                                      |
| dulwich_log               | 65.7 ms                                                                                                                | 79.6 ms: 1.21x slower                                                                                                      |
| genshi_xml                | 80.7 ms                                                                                                                | 108 ms: 1.34x slower                                                                                                       |
| bench_mp_pool             | 188 ms                                                                                                                 | 264 ms: 1.40x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (30): crypto_pyaes, logging_simple, meteor_contest, raytrace, async_tree_cpu_io_mixed_tg, json_loads, xdsl_constant_fold, chameleon, async_tree_none_tg, create_gc_cycles, sqlglot_v2_transpile, async_tree_none, django_template, asyncio_tcp_ssl, pprint_safe_repr, sqlalchemy_imperative, typing_runtime_protocols, 2to3, subparsers, async_tree_cpu_io_mixed, coverage, sqlglot_v2_optimize, deepcopy_reduce, pprint_pformat, sqlglot_v2_normalize, regex_compile, logging_format, async_tree_io, async_tree_memoization, bench_thread_pool
Ignored benchmarks (5) of results/bm-20251215-3.15.0a2+-bef63d2/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2+-bef63d2.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.024x faster

# HPT report

- Reliability score: 96.91% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x