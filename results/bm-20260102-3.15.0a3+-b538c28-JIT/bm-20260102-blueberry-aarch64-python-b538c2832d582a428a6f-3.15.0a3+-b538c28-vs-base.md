# Results vs. base

- fork: python
- ref: b538c2832d582a428a6f
- machine: linux-aarch64
- commit hash: b538c28
- commit date: 2026-01-02
- overall geometric mean: 1.028x faster
- HPT reliability: 88.47%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| docutils       | 4.37 sec                                                                                                               | 4.84 sec: 1.11x slower                                                                                                     |
| html5lib       | 80.6 ms                                                                                                                | 91.2 ms: 1.13x slower                                                                                                      |
| sphinx         | 1.56 sec                                                                                                               | 1.60 sec: 1.03x slower                                                                                                     |
| tornado_http   | 174 ms                                                                                                                 | 171 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (2): 2to3, chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl           | 4.50 sec                                                                                                               | 4.45 sec: 1.01x faster                                                                                                     |
| asyncio_websockets        | 908 ms                                                                                                                 | 902 ms: 1.01x faster                                                                                                       |
| asyncio_tcp               | 1.17 sec                                                                                                               | 1.19 sec: 1.02x slower                                                                                                     |
| async_tree_memoization_tg | 663 ms                                                                                                                 | 675 ms: 1.02x slower                                                                                                       |
| async_generators          | 590 ms                                                                                                                 | 637 ms: 1.08x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (8): async_tree_none, coroutines, async_tree_io, async_tree_cpu_io_mixed, async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 168 ms                                                                                                                 | 142 ms: 1.18x faster                                                                                                       |
| float          | 134 ms                                                                                                                 | 116 ms: 1.15x faster                                                                                                       |
| pidigits       | 345 ms                                                                                                                 | 330 ms: 1.05x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 37.8 ms                                                                                                                | 36.8 ms: 1.03x faster                                                                                                      |
| regex_dna      | 295 ms                                                                                                                 | 287 ms: 1.02x faster                                                                                                       |
| regex_effbot   | 4.72 ms                                                                                                                | 4.78 ms: 1.01x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 355 us                                                                                                                 | 263 us: 1.35x faster                                                                                                       |
| pickle_pure_python   | 484 us                                                                                                                 | 398 us: 1.22x faster                                                                                                       |
| tomli_loads          | 3.52 sec                                                                                                               | 3.07 sec: 1.15x faster                                                                                                     |
| xml_etree_generate   | 143 ms                                                                                                                 | 130 ms: 1.10x faster                                                                                                       |
| xml_etree_process    | 108 ms                                                                                                                 | 98.6 ms: 1.09x faster                                                                                                      |
| pickle_dict          | 50.7 us                                                                                                                | 47.6 us: 1.07x faster                                                                                                      |
| xml_etree_iterparse  | 207 ms                                                                                                                 | 197 ms: 1.05x faster                                                                                                       |
| xml_etree_parse      | 258 ms                                                                                                                 | 247 ms: 1.04x faster                                                                                                       |
| pickle_list          | 7.13 us                                                                                                                | 6.86 us: 1.04x faster                                                                                                      |
| json_dumps           | 14.6 ms                                                                                                                | 14.1 ms: 1.03x faster                                                                                                      |
| unpickle_list        | 8.89 us                                                                                                                | 8.61 us: 1.03x faster                                                                                                      |
| pickle               | 19.4 us                                                                                                                | 18.9 us: 1.03x faster                                                                                                      |
| unpickle             | 23.5 us                                                                                                                | 23.1 us: 1.02x faster                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.08x faster                                                                                                               |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.5 ms                                                                                                                | 17.8 ms: 1.04x faster                                                                                                      |
| python_startup_no_site | 10.8 ms                                                                                                                | 10.4 ms: 1.04x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 21.2 ms                                                                                                                | 19.0 ms: 1.12x faster                                                                                                      |
| genshi_text    | 35.5 ms                                                                                                                | 39.3 ms: 1.11x slower                                                                                                      |
| genshi_xml     | 80.7 ms                                                                                                                | 102 ms: 1.26x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                 | results/bm-20260102-3.15.0a3+-b538c28/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json | results/bm-20260102-3.15.0a3+-b538c28-JIT/bm-20260102-blueberry-aarch64-python-b538c2832d582a428a6f-3.15.0a3+-b538c28.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 67.5 ms                                                                                                                | 38.1 ms: 1.77x faster                                                                                                      |
| richards_super            | 76.3 ms                                                                                                                | 45.5 ms: 1.68x faster                                                                                                      |
| unpickle_pure_python      | 355 us                                                                                                                 | 263 us: 1.35x faster                                                                                                       |
| logging_silent            | 170 ns                                                                                                                 | 134 ns: 1.27x faster                                                                                                       |
| pickle_pure_python        | 484 us                                                                                                                 | 398 us: 1.22x faster                                                                                                       |
| scimark_monte_carlo       | 105 ms                                                                                                                 | 86.9 ms: 1.20x faster                                                                                                      |
| scimark_fft               | 525 ms                                                                                                                 | 443 ms: 1.19x faster                                                                                                       |
| nbody                     | 168 ms                                                                                                                 | 142 ms: 1.18x faster                                                                                                       |
| deltablue                 | 5.33 ms                                                                                                                | 4.57 ms: 1.17x faster                                                                                                      |
| spectral_norm             | 163 ms                                                                                                                 | 140 ms: 1.16x faster                                                                                                       |
| scimark_sor               | 181 ms                                                                                                                 | 156 ms: 1.16x faster                                                                                                       |
| pyflate                   | 777 ms                                                                                                                 | 672 ms: 1.15x faster                                                                                                       |
| float                     | 134 ms                                                                                                                 | 116 ms: 1.15x faster                                                                                                       |
| scimark_lu                | 179 ms                                                                                                                 | 156 ms: 1.15x faster                                                                                                       |
| tomli_loads               | 3.52 sec                                                                                                               | 3.07 sec: 1.15x faster                                                                                                     |
| mako                      | 21.2 ms                                                                                                                | 19.0 ms: 1.12x faster                                                                                                      |
| sqlite_synth              | 5.03 us                                                                                                                | 4.54 us: 1.11x faster                                                                                                      |
| xml_etree_generate        | 143 ms                                                                                                                 | 130 ms: 1.10x faster                                                                                                       |
| xml_etree_process         | 108 ms                                                                                                                 | 98.6 ms: 1.09x faster                                                                                                      |
| fannkuch                  | 636 ms                                                                                                                 | 585 ms: 1.09x faster                                                                                                       |
| deepcopy_memo             | 42.2 us                                                                                                                | 38.9 us: 1.09x faster                                                                                                      |
| sqlglot_v2_parse          | 1.79 ms                                                                                                                | 1.67 ms: 1.07x faster                                                                                                      |
| pickle_dict               | 50.7 us                                                                                                                | 47.6 us: 1.07x faster                                                                                                      |
| bpe_tokeniser             | 7.62 sec                                                                                                               | 7.16 sec: 1.06x faster                                                                                                     |
| sqlglot_v2_transpile      | 2.33 ms                                                                                                                | 2.20 ms: 1.06x faster                                                                                                      |
| scimark_sparse_mat_mult   | 8.58 ms                                                                                                                | 8.15 ms: 1.05x faster                                                                                                      |
| typing_runtime_protocols  | 257 us                                                                                                                 | 245 us: 1.05x faster                                                                                                       |
| telco                     | 212 ms                                                                                                                 | 202 ms: 1.05x faster                                                                                                       |
| xml_etree_iterparse       | 207 ms                                                                                                                 | 197 ms: 1.05x faster                                                                                                       |
| pidigits                  | 345 ms                                                                                                                 | 330 ms: 1.05x faster                                                                                                       |
| xml_etree_parse           | 258 ms                                                                                                                 | 247 ms: 1.04x faster                                                                                                       |
| python_startup            | 18.5 ms                                                                                                                | 17.8 ms: 1.04x faster                                                                                                      |
| pickle_list               | 7.13 us                                                                                                                | 6.86 us: 1.04x faster                                                                                                      |
| python_startup_no_site    | 10.8 ms                                                                                                                | 10.4 ms: 1.04x faster                                                                                                      |
| json                      | 7.33 ms                                                                                                                | 7.08 ms: 1.04x faster                                                                                                      |
| json_dumps                | 14.6 ms                                                                                                                | 14.1 ms: 1.03x faster                                                                                                      |
| unpickle_list             | 8.89 us                                                                                                                | 8.61 us: 1.03x faster                                                                                                      |
| sqlalchemy_declarative    | 170 ms                                                                                                                 | 165 ms: 1.03x faster                                                                                                       |
| raytrace                  | 422 ms                                                                                                                 | 409 ms: 1.03x faster                                                                                                       |
| pickle                    | 19.4 us                                                                                                                | 18.9 us: 1.03x faster                                                                                                      |
| regex_v8                  | 37.8 ms                                                                                                                | 36.8 ms: 1.03x faster                                                                                                      |
| pprint_pformat            | 2.27 sec                                                                                                               | 2.21 sec: 1.03x faster                                                                                                     |
| regex_dna                 | 295 ms                                                                                                                 | 287 ms: 1.02x faster                                                                                                       |
| go                        | 167 ms                                                                                                                 | 163 ms: 1.02x faster                                                                                                       |
| pprint_safe_repr          | 1.09 sec                                                                                                               | 1.07 sec: 1.02x faster                                                                                                     |
| connected_components      | 851 ms                                                                                                                 | 833 ms: 1.02x faster                                                                                                       |
| unpickle                  | 23.5 us                                                                                                                | 23.1 us: 1.02x faster                                                                                                      |
| tornado_http              | 174 ms                                                                                                                 | 171 ms: 1.01x faster                                                                                                       |
| create_gc_cycles          | 9.22 ms                                                                                                                | 9.10 ms: 1.01x faster                                                                                                      |
| shortest_path             | 899 ms                                                                                                                 | 888 ms: 1.01x faster                                                                                                       |
| asyncio_tcp_ssl           | 4.50 sec                                                                                                               | 4.45 sec: 1.01x faster                                                                                                     |
| pathlib                   | 22.5 ms                                                                                                                | 22.3 ms: 1.01x faster                                                                                                      |
| k_core                    | 4.07 sec                                                                                                               | 4.03 sec: 1.01x faster                                                                                                     |
| asyncio_websockets        | 908 ms                                                                                                                 | 902 ms: 1.01x faster                                                                                                       |
| regex_effbot              | 4.72 ms                                                                                                                | 4.78 ms: 1.01x slower                                                                                                      |
| gc_traversal              | 14.9 ms                                                                                                                | 15.1 ms: 1.01x slower                                                                                                      |
| asyncio_tcp               | 1.17 sec                                                                                                               | 1.19 sec: 1.02x slower                                                                                                     |
| async_tree_memoization_tg | 663 ms                                                                                                                 | 675 ms: 1.02x slower                                                                                                       |
| sympy_integrate           | 24.7 ms                                                                                                                | 25.3 ms: 1.02x slower                                                                                                      |
| generators                | 50.3 ms                                                                                                                | 51.5 ms: 1.02x slower                                                                                                      |
| pycparser                 | 1.57 sec                                                                                                               | 1.62 sec: 1.03x slower                                                                                                     |
| sphinx                    | 1.56 sec                                                                                                               | 1.60 sec: 1.03x slower                                                                                                     |
| chaos                     | 88.3 ms                                                                                                                | 92.0 ms: 1.04x slower                                                                                                      |
| deepcopy_reduce           | 4.25 us                                                                                                                | 4.42 us: 1.04x slower                                                                                                      |
| pylint                    | 430 ms                                                                                                                 | 448 ms: 1.04x slower                                                                                                       |
| sympy_sum                 | 185 ms                                                                                                                 | 196 ms: 1.06x slower                                                                                                       |
| sympy_str                 | 352 ms                                                                                                                 | 377 ms: 1.07x slower                                                                                                       |
| many_optionals            | 932 us                                                                                                                 | 1.00 ms: 1.08x slower                                                                                                      |
| async_generators          | 590 ms                                                                                                                 | 637 ms: 1.08x slower                                                                                                       |
| hexiom                    | 8.91 ms                                                                                                                | 9.72 ms: 1.09x slower                                                                                                      |
| sympy_expand              | 602 ms                                                                                                                 | 658 ms: 1.09x slower                                                                                                       |
| nqueens                   | 123 ms                                                                                                                 | 135 ms: 1.10x slower                                                                                                       |
| genshi_text               | 35.5 ms                                                                                                                | 39.3 ms: 1.11x slower                                                                                                      |
| docutils                  | 4.37 sec                                                                                                               | 4.84 sec: 1.11x slower                                                                                                     |
| deepcopy                  | 391 us                                                                                                                 | 434 us: 1.11x slower                                                                                                       |
| mdp                       | 2.52 sec                                                                                                               | 2.81 sec: 1.11x slower                                                                                                     |
| html5lib                  | 80.6 ms                                                                                                                | 91.2 ms: 1.13x slower                                                                                                      |
| unpack_sequence           | 70.3 ns                                                                                                                | 81.7 ns: 1.16x slower                                                                                                      |
| dulwich_log               | 67.7 ms                                                                                                                | 80.7 ms: 1.19x slower                                                                                                      |
| genshi_xml                | 80.7 ms                                                                                                                | 102 ms: 1.26x slower                                                                                                       |
| bench_mp_pool             | 129 ms                                                                                                                 | 188 ms: 1.46x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (26): sqlglot_v2_optimize, meteor_contest, thrift, logging_simple, logging_format, regex_compile, async_tree_none, comprehensions, bench_thread_pool, crypto_pyaes, json_loads, coverage, 2to3, xdsl_constant_fold, coroutines, sqlalchemy_imperative, async_tree_io, chameleon, subparsers, async_tree_cpu_io_mixed, async_tree_none_tg, async_tree_cpu_io_mixed_tg, sqlglot_v2_normalize, async_tree_io_tg, async_tree_memoization, django_template

- Geometric mean (including insignificant results): 1.028x faster

# HPT report

- Reliability score: 88.47% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x