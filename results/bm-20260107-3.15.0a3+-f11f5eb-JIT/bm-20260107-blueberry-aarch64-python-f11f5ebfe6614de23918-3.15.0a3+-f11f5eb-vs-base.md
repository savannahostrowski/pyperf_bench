# Results vs. base

- fork: python
- ref: f11f5ebfe6614de23918
- machine: linux-aarch64
- commit hash: f11f5eb
- commit date: 2026-01-07
- overall geometric mean: 1.035x faster
- HPT reliability: 96.59%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 21.7 ms                                                                                                                | 21.1 ms: 1.03x faster                                                                                                      |
| docutils       | 4.37 sec                                                                                                               | 4.78 sec: 1.09x slower                                                                                                     |
| html5lib       | 79.7 ms                                                                                                                | 89.2 ms: 1.12x slower                                                                                                      |
| sphinx         | 1.54 sec                                                                                                               | 1.58 sec: 1.03x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_io             | 1.34 sec                                                                                                               | 1.25 sec: 1.07x faster                                                                                                     |
| async_tree_none           | 542 ms                                                                                                                 | 518 ms: 1.05x faster                                                                                                       |
| asyncio_tcp_ssl           | 4.49 sec                                                                                                               | 4.46 sec: 1.01x faster                                                                                                     |
| async_tree_memoization_tg | 651 ms                                                                                                                 | 662 ms: 1.02x slower                                                                                                       |
| async_tree_io_tg          | 1.24 sec                                                                                                               | 1.27 sec: 1.02x slower                                                                                                     |
| asyncio_tcp               | 1.24 sec                                                                                                               | 1.30 sec: 1.05x slower                                                                                                     |
| async_generators          | 600 ms                                                                                                                 | 645 ms: 1.07x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (6): coroutines, async_tree_cpu_io_mixed, asyncio_websockets, async_tree_none_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 168 ms                                                                                                                 | 137 ms: 1.23x faster                                                                                                       |
| float          | 133 ms                                                                                                                 | 115 ms: 1.16x faster                                                                                                       |
| pidigits       | 339 ms                                                                                                                 | 328 ms: 1.03x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.14x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 301 ms                                                                                                                 | 284 ms: 1.06x faster                                                                                                       |
| regex_effbot   | 4.68 ms                                                                                                                | 4.45 ms: 1.05x faster                                                                                                      |
| regex_v8       | 38.0 ms                                                                                                                | 36.2 ms: 1.05x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 330 us                                                                                                                 | 259 us: 1.27x faster                                                                                                       |
| pickle_pure_python   | 473 us                                                                                                                 | 381 us: 1.24x faster                                                                                                       |
| tomli_loads          | 3.07 sec                                                                                                               | 2.71 sec: 1.13x faster                                                                                                     |
| json_dumps           | 14.8 ms                                                                                                                | 13.7 ms: 1.08x faster                                                                                                      |
| xml_etree_process    | 105 ms                                                                                                                 | 97.4 ms: 1.08x faster                                                                                                      |
| xml_etree_generate   | 137 ms                                                                                                                 | 128 ms: 1.07x faster                                                                                                       |
| pickle_dict          | 49.3 us                                                                                                                | 46.6 us: 1.06x faster                                                                                                      |
| pickle_list          | 7.15 us                                                                                                                | 6.82 us: 1.05x faster                                                                                                      |
| xml_etree_parse      | 258 ms                                                                                                                 | 248 ms: 1.04x faster                                                                                                       |
| xml_etree_iterparse  | 206 ms                                                                                                                 | 200 ms: 1.03x faster                                                                                                       |
| pickle               | 19.3 us                                                                                                                | 18.9 us: 1.02x faster                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.08x faster                                                                                                               |

Benchmark hidden because not significant (3): unpickle_list, json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.5 ms                                                                                                                | 17.8 ms: 1.04x faster                                                                                                      |
| python_startup_no_site | 10.9 ms                                                                                                                | 10.5 ms: 1.03x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.7 ms                                                                                                                | 18.0 ms: 1.15x faster                                                                                                      |
| django_template | 53.0 ms                                                                                                                | 54.9 ms: 1.04x slower                                                                                                      |
| genshi_xml      | 80.3 ms                                                                                                                | 98.7 ms: 1.23x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmark hidden because not significant (1): genshi_text

All benchmarks:
===============

| Benchmark                 | results/bm-20260107-3.15.0a3+-f11f5eb/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json | results/bm-20260107-3.15.0a3+-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3+-f11f5eb.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 68.7 ms                                                                                                                | 37.9 ms: 1.81x faster                                                                                                      |
| richards_super            | 75.0 ms                                                                                                                | 44.8 ms: 1.67x faster                                                                                                      |
| logging_silent            | 168 ns                                                                                                                 | 126 ns: 1.33x faster                                                                                                       |
| unpickle_pure_python      | 330 us                                                                                                                 | 259 us: 1.27x faster                                                                                                       |
| scimark_monte_carlo       | 105 ms                                                                                                                 | 82.8 ms: 1.27x faster                                                                                                      |
| pickle_pure_python        | 473 us                                                                                                                 | 381 us: 1.24x faster                                                                                                       |
| nbody                     | 168 ms                                                                                                                 | 137 ms: 1.23x faster                                                                                                       |
| deltablue                 | 5.26 ms                                                                                                                | 4.38 ms: 1.20x faster                                                                                                      |
| deepcopy_memo             | 43.8 us                                                                                                                | 36.6 us: 1.20x faster                                                                                                      |
| scimark_fft               | 511 ms                                                                                                                 | 432 ms: 1.18x faster                                                                                                       |
| pyflate                   | 768 ms                                                                                                                 | 651 ms: 1.18x faster                                                                                                       |
| float                     | 133 ms                                                                                                                 | 115 ms: 1.16x faster                                                                                                       |
| scimark_lu                | 177 ms                                                                                                                 | 153 ms: 1.15x faster                                                                                                       |
| mako                      | 20.7 ms                                                                                                                | 18.0 ms: 1.15x faster                                                                                                      |
| scimark_sor               | 179 ms                                                                                                                 | 156 ms: 1.15x faster                                                                                                       |
| tomli_loads               | 3.07 sec                                                                                                               | 2.71 sec: 1.13x faster                                                                                                     |
| spectral_norm             | 158 ms                                                                                                                 | 140 ms: 1.13x faster                                                                                                       |
| fannkuch                  | 625 ms                                                                                                                 | 557 ms: 1.12x faster                                                                                                       |
| json_dumps                | 14.8 ms                                                                                                                | 13.7 ms: 1.08x faster                                                                                                      |
| xml_etree_process         | 105 ms                                                                                                                 | 97.4 ms: 1.08x faster                                                                                                      |
| pprint_safe_repr          | 1.12 sec                                                                                                               | 1.04 sec: 1.08x faster                                                                                                     |
| async_tree_io             | 1.34 sec                                                                                                               | 1.25 sec: 1.07x faster                                                                                                     |
| pprint_pformat            | 2.30 sec                                                                                                               | 2.15 sec: 1.07x faster                                                                                                     |
| go                        | 163 ms                                                                                                                 | 152 ms: 1.07x faster                                                                                                       |
| xml_etree_generate        | 137 ms                                                                                                                 | 128 ms: 1.07x faster                                                                                                       |
| bpe_tokeniser             | 7.45 sec                                                                                                               | 6.98 sec: 1.07x faster                                                                                                     |
| pathlib                   | 23.5 ms                                                                                                                | 22.1 ms: 1.06x faster                                                                                                      |
| sqlglot_v2_parse          | 1.80 ms                                                                                                                | 1.69 ms: 1.06x faster                                                                                                      |
| regex_dna                 | 301 ms                                                                                                                 | 284 ms: 1.06x faster                                                                                                       |
| pickle_dict               | 49.3 us                                                                                                                | 46.6 us: 1.06x faster                                                                                                      |
| meteor_contest            | 142 ms                                                                                                                 | 134 ms: 1.06x faster                                                                                                       |
| raytrace                  | 426 ms                                                                                                                 | 404 ms: 1.05x faster                                                                                                       |
| regex_effbot              | 4.68 ms                                                                                                                | 4.45 ms: 1.05x faster                                                                                                      |
| regex_v8                  | 38.0 ms                                                                                                                | 36.2 ms: 1.05x faster                                                                                                      |
| pickle_list               | 7.15 us                                                                                                                | 6.82 us: 1.05x faster                                                                                                      |
| async_tree_none           | 542 ms                                                                                                                 | 518 ms: 1.05x faster                                                                                                       |
| scimark_sparse_mat_mult   | 8.28 ms                                                                                                                | 7.96 ms: 1.04x faster                                                                                                      |
| xml_etree_parse           | 258 ms                                                                                                                 | 248 ms: 1.04x faster                                                                                                       |
| python_startup            | 18.5 ms                                                                                                                | 17.8 ms: 1.04x faster                                                                                                      |
| sqlite_synth              | 4.71 us                                                                                                                | 4.54 us: 1.04x faster                                                                                                      |
| pidigits                  | 339 ms                                                                                                                 | 328 ms: 1.03x faster                                                                                                       |
| gc_traversal              | 14.9 ms                                                                                                                | 14.4 ms: 1.03x faster                                                                                                      |
| deepcopy_reduce           | 4.37 us                                                                                                                | 4.23 us: 1.03x faster                                                                                                      |
| python_startup_no_site    | 10.9 ms                                                                                                                | 10.5 ms: 1.03x faster                                                                                                      |
| xml_etree_iterparse       | 206 ms                                                                                                                 | 200 ms: 1.03x faster                                                                                                       |
| chameleon                 | 21.7 ms                                                                                                                | 21.1 ms: 1.03x faster                                                                                                      |
| json                      | 6.96 ms                                                                                                                | 6.76 ms: 1.03x faster                                                                                                      |
| create_gc_cycles          | 9.15 ms                                                                                                                | 8.89 ms: 1.03x faster                                                                                                      |
| pickle                    | 19.3 us                                                                                                                | 18.9 us: 1.02x faster                                                                                                      |
| connected_components      | 846 ms                                                                                                                 | 828 ms: 1.02x faster                                                                                                       |
| k_core                    | 4.10 sec                                                                                                               | 4.04 sec: 1.01x faster                                                                                                     |
| shortest_path             | 891 ms                                                                                                                 | 884 ms: 1.01x faster                                                                                                       |
| asyncio_tcp_ssl           | 4.49 sec                                                                                                               | 4.46 sec: 1.01x faster                                                                                                     |
| async_tree_memoization_tg | 651 ms                                                                                                                 | 662 ms: 1.02x slower                                                                                                       |
| generators                | 50.0 ms                                                                                                                | 51.0 ms: 1.02x slower                                                                                                      |
| sqlglot_v2_normalize      | 159 ms                                                                                                                 | 162 ms: 1.02x slower                                                                                                       |
| async_tree_io_tg          | 1.24 sec                                                                                                               | 1.27 sec: 1.02x slower                                                                                                     |
| sphinx                    | 1.54 sec                                                                                                               | 1.58 sec: 1.03x slower                                                                                                     |
| django_template           | 53.0 ms                                                                                                                | 54.9 ms: 1.04x slower                                                                                                      |
| pylint                    | 427 ms                                                                                                                 | 447 ms: 1.05x slower                                                                                                       |
| xdsl_constant_fold        | 58.3 ms                                                                                                                | 61.0 ms: 1.05x slower                                                                                                      |
| asyncio_tcp               | 1.24 sec                                                                                                               | 1.30 sec: 1.05x slower                                                                                                     |
| sympy_integrate           | 24.3 ms                                                                                                                | 25.5 ms: 1.05x slower                                                                                                      |
| sqlglot_v2_optimize       | 76.4 ms                                                                                                                | 80.6 ms: 1.05x slower                                                                                                      |
| chaos                     | 86.5 ms                                                                                                                | 91.4 ms: 1.06x slower                                                                                                      |
| deepcopy                  | 388 us                                                                                                                 | 414 us: 1.07x slower                                                                                                       |
| async_generators          | 600 ms                                                                                                                 | 645 ms: 1.07x slower                                                                                                       |
| mdp                       | 2.55 sec                                                                                                               | 2.74 sec: 1.08x slower                                                                                                     |
| many_optionals            | 936 us                                                                                                                 | 1.01 ms: 1.08x slower                                                                                                      |
| sympy_sum                 | 181 ms                                                                                                                 | 196 ms: 1.08x slower                                                                                                       |
| hexiom                    | 8.74 ms                                                                                                                | 9.49 ms: 1.08x slower                                                                                                      |
| docutils                  | 4.37 sec                                                                                                               | 4.78 sec: 1.09x slower                                                                                                     |
| nqueens                   | 118 ms                                                                                                                 | 131 ms: 1.10x slower                                                                                                       |
| sympy_str                 | 343 ms                                                                                                                 | 381 ms: 1.11x slower                                                                                                       |
| html5lib                  | 79.7 ms                                                                                                                | 89.2 ms: 1.12x slower                                                                                                      |
| dulwich_log               | 66.5 ms                                                                                                                | 74.6 ms: 1.12x slower                                                                                                      |
| sympy_expand              | 598 ms                                                                                                                 | 674 ms: 1.13x slower                                                                                                       |
| genshi_xml                | 80.3 ms                                                                                                                | 98.7 ms: 1.23x slower                                                                                                      |
| unpack_sequence           | 65.5 ns                                                                                                                | 83.4 ns: 1.27x slower                                                                                                      |
| bench_mp_pool             | 133 ms                                                                                                                 | 233 ms: 1.76x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (27): coroutines, sqlglot_v2_transpile, coverage, bench_thread_pool, thrift, crypto_pyaes, async_tree_cpu_io_mixed, sqlalchemy_declarative, regex_compile, unpickle_list, json_loads, asyncio_websockets, unpickle, typing_runtime_protocols, telco, logging_simple, comprehensions, sqlalchemy_imperative, subparsers, 2to3, logging_format, pycparser, async_tree_none_tg, genshi_text, async_tree_memoization, tornado_http, async_tree_cpu_io_mixed_tg

- Geometric mean (including insignificant results): 1.035x faster

# HPT report

- Reliability score: 96.59% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x