# Results vs. base

- fork: python
- ref: e4058d7cb115286c3c53
- machine: linux-aarch64
- commit hash: e4058d7
- commit date: 2025-12-18
- overall geometric mean: 1.014x faster
- HPT reliability: 65.87%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 429 ms                                                                                                                 | 431 ms: 1.00x slower                                                                                                       |
| chameleon      | 21.1 ms                                                                                                                | 20.8 ms: 1.02x faster                                                                                                      |
| docutils       | 4.30 sec                                                                                                               | 4.78 sec: 1.11x slower                                                                                                     |
| html5lib       | 79.4 ms                                                                                                                | 92.1 ms: 1.16x slower                                                                                                      |
| sphinx         | 1.50 sec                                                                                                               | 1.59 sec: 1.06x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp               | 1.13 sec                                                                                                               | 1.06 sec: 1.06x faster                                                                                                     |
| coroutines                | 39.9 ms                                                                                                                | 39.4 ms: 1.01x faster                                                                                                      |
| asyncio_tcp_ssl           | 4.10 sec                                                                                                               | 4.07 sec: 1.01x faster                                                                                                     |
| asyncio_websockets        | 879 ms                                                                                                                 | 873 ms: 1.01x faster                                                                                                       |
| async_tree_io             | 1.16 sec                                                                                                               | 1.19 sec: 1.03x slower                                                                                                     |
| async_tree_memoization_tg | 634 ms                                                                                                                 | 674 ms: 1.06x slower                                                                                                       |
| async_tree_io_tg          | 1.17 sec                                                                                                               | 1.26 sec: 1.08x slower                                                                                                     |
| async_generators          | 562 ms                                                                                                                 | 617 ms: 1.10x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (5): async_tree_none, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 164 ms                                                                                                                 | 145 ms: 1.13x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 118 ms: 1.11x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.08x faster                                                                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 36.7 ms                                                                                                                | 35.4 ms: 1.04x faster                                                                                                      |
| regex_dna      | 281 ms                                                                                                                 | 284 ms: 1.01x slower                                                                                                       |
| regex_effbot   | 4.41 ms                                                                                                                | 4.51 ms: 1.02x slower                                                                                                      |
| regex_compile  | 150 ms                                                                                                                 | 157 ms: 1.05x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 331 us                                                                                                                 | 250 us: 1.32x faster                                                                                                       |
| pickle_pure_python   | 460 us                                                                                                                 | 387 us: 1.19x faster                                                                                                       |
| xml_etree_generate   | 139 ms                                                                                                                 | 125 ms: 1.11x faster                                                                                                       |
| tomli_loads          | 3.43 sec                                                                                                               | 3.15 sec: 1.09x faster                                                                                                     |
| xml_etree_process    | 103 ms                                                                                                                 | 94.3 ms: 1.09x faster                                                                                                      |
| json_dumps           | 14.5 ms                                                                                                                | 13.5 ms: 1.07x faster                                                                                                      |
| xml_etree_parse      | 253 ms                                                                                                                 | 241 ms: 1.05x faster                                                                                                       |
| unpickle             | 23.6 us                                                                                                                | 22.5 us: 1.05x faster                                                                                                      |
| unpickle_list        | 8.40 us                                                                                                                | 8.15 us: 1.03x faster                                                                                                      |
| xml_etree_iterparse  | 201 ms                                                                                                                 | 198 ms: 1.01x faster                                                                                                       |
| pickle_list          | 6.85 us                                                                                                                | 6.89 us: 1.01x slower                                                                                                      |
| json_loads           | 38.8 us                                                                                                                | 39.2 us: 1.01x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.07x faster                                                                                                               |

Benchmark hidden because not significant (2): pickle_dict, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.7 ms                                                                                                                | 17.9 ms: 1.01x slower                                                                                                      |
| python_startup_no_site | 10.4 ms                                                                                                                | 10.6 ms: 1.01x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 20.3 ms                                                                                                                | 18.5 ms: 1.10x faster                                                                                                      |
| genshi_text    | 34.3 ms                                                                                                                | 38.1 ms: 1.11x slower                                                                                                      |
| genshi_xml     | 79.0 ms                                                                                                                | 101 ms: 1.28x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.07x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                 | results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json | results/bm-20251218-3.15.0a3+-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 64.0 ms                                                                                                                | 38.6 ms: 1.66x faster                                                                                                      |
| richards_super            | 73.9 ms                                                                                                                | 46.2 ms: 1.60x faster                                                                                                      |
| logging_silent            | 166 ns                                                                                                                 | 124 ns: 1.34x faster                                                                                                       |
| unpickle_pure_python      | 331 us                                                                                                                 | 250 us: 1.32x faster                                                                                                       |
| deltablue                 | 5.26 ms                                                                                                                | 4.42 ms: 1.19x faster                                                                                                      |
| pickle_pure_python        | 460 us                                                                                                                 | 387 us: 1.19x faster                                                                                                       |
| scimark_fft               | 497 ms                                                                                                                 | 432 ms: 1.15x faster                                                                                                       |
| spectral_norm             | 159 ms                                                                                                                 | 140 ms: 1.14x faster                                                                                                       |
| deepcopy_memo             | 41.7 us                                                                                                                | 36.8 us: 1.13x faster                                                                                                      |
| nbody                     | 164 ms                                                                                                                 | 145 ms: 1.13x faster                                                                                                       |
| scimark_monte_carlo       | 101 ms                                                                                                                 | 89.4 ms: 1.13x faster                                                                                                      |
| scimark_sor               | 176 ms                                                                                                                 | 156 ms: 1.13x faster                                                                                                       |
| float                     | 131 ms                                                                                                                 | 118 ms: 1.11x faster                                                                                                       |
| xml_etree_generate        | 139 ms                                                                                                                 | 125 ms: 1.11x faster                                                                                                       |
| mako                      | 20.3 ms                                                                                                                | 18.5 ms: 1.10x faster                                                                                                      |
| pyflate                   | 745 ms                                                                                                                 | 683 ms: 1.09x faster                                                                                                       |
| tomli_loads               | 3.43 sec                                                                                                               | 3.15 sec: 1.09x faster                                                                                                     |
| xml_etree_process         | 103 ms                                                                                                                 | 94.3 ms: 1.09x faster                                                                                                      |
| fannkuch                  | 624 ms                                                                                                                 | 577 ms: 1.08x faster                                                                                                       |
| crypto_pyaes              | 110 ms                                                                                                                 | 102 ms: 1.08x faster                                                                                                       |
| json_dumps                | 14.5 ms                                                                                                                | 13.5 ms: 1.07x faster                                                                                                      |
| asyncio_tcp               | 1.13 sec                                                                                                               | 1.06 sec: 1.06x faster                                                                                                     |
| coverage                  | 132 ms                                                                                                                 | 126 ms: 1.05x faster                                                                                                       |
| xml_etree_parse           | 253 ms                                                                                                                 | 241 ms: 1.05x faster                                                                                                       |
| unpickle                  | 23.6 us                                                                                                                | 22.5 us: 1.05x faster                                                                                                      |
| bpe_tokeniser             | 7.31 sec                                                                                                               | 7.03 sec: 1.04x faster                                                                                                     |
| scimark_lu                | 174 ms                                                                                                                 | 168 ms: 1.04x faster                                                                                                       |
| sqlite_synth              | 4.59 us                                                                                                                | 4.43 us: 1.04x faster                                                                                                      |
| regex_v8                  | 36.7 ms                                                                                                                | 35.4 ms: 1.04x faster                                                                                                      |
| unpickle_list             | 8.40 us                                                                                                                | 8.15 us: 1.03x faster                                                                                                      |
| scimark_sparse_mat_mult   | 8.26 ms                                                                                                                | 8.02 ms: 1.03x faster                                                                                                      |
| json                      | 6.86 ms                                                                                                                | 6.69 ms: 1.03x faster                                                                                                      |
| deepcopy_reduce           | 4.30 us                                                                                                                | 4.20 us: 1.02x faster                                                                                                      |
| telco                     | 203 ms                                                                                                                 | 199 ms: 1.02x faster                                                                                                       |
| chameleon                 | 21.1 ms                                                                                                                | 20.8 ms: 1.02x faster                                                                                                      |
| go                        | 162 ms                                                                                                                 | 160 ms: 1.02x faster                                                                                                       |
| xml_etree_iterparse       | 201 ms                                                                                                                 | 198 ms: 1.01x faster                                                                                                       |
| coroutines                | 39.9 ms                                                                                                                | 39.4 ms: 1.01x faster                                                                                                      |
| gc_traversal              | 14.8 ms                                                                                                                | 14.7 ms: 1.01x faster                                                                                                      |
| asyncio_tcp_ssl           | 4.10 sec                                                                                                               | 4.07 sec: 1.01x faster                                                                                                     |
| asyncio_websockets        | 879 ms                                                                                                                 | 873 ms: 1.01x faster                                                                                                       |
| shortest_path             | 886 ms                                                                                                                 | 888 ms: 1.00x slower                                                                                                       |
| 2to3                      | 429 ms                                                                                                                 | 431 ms: 1.00x slower                                                                                                       |
| pickle_list               | 6.85 us                                                                                                                | 6.89 us: 1.01x slower                                                                                                      |
| regex_dna                 | 281 ms                                                                                                                 | 284 ms: 1.01x slower                                                                                                       |
| meteor_contest            | 138 ms                                                                                                                 | 140 ms: 1.01x slower                                                                                                       |
| python_startup            | 17.7 ms                                                                                                                | 17.9 ms: 1.01x slower                                                                                                      |
| python_startup_no_site    | 10.4 ms                                                                                                                | 10.6 ms: 1.01x slower                                                                                                      |
| logging_simple            | 8.30 us                                                                                                                | 8.40 us: 1.01x slower                                                                                                      |
| sqlalchemy_declarative    | 161 ms                                                                                                                 | 163 ms: 1.01x slower                                                                                                       |
| json_loads                | 38.8 us                                                                                                                | 39.2 us: 1.01x slower                                                                                                      |
| logging_format            | 9.06 us                                                                                                                | 9.18 us: 1.01x slower                                                                                                      |
| raytrace                  | 404 ms                                                                                                                 | 410 ms: 1.02x slower                                                                                                       |
| pathlib                   | 21.6 ms                                                                                                                | 21.9 ms: 1.02x slower                                                                                                      |
| regex_effbot              | 4.41 ms                                                                                                                | 4.51 ms: 1.02x slower                                                                                                      |
| async_tree_io             | 1.16 sec                                                                                                               | 1.19 sec: 1.03x slower                                                                                                     |
| pprint_pformat            | 2.22 sec                                                                                                               | 2.29 sec: 1.03x slower                                                                                                     |
| pprint_safe_repr          | 1.07 sec                                                                                                               | 1.11 sec: 1.03x slower                                                                                                     |
| typing_runtime_protocols  | 238 us                                                                                                                 | 248 us: 1.04x slower                                                                                                       |
| xdsl_constant_fold        | 57.5 ms                                                                                                                | 59.9 ms: 1.04x slower                                                                                                      |
| sqlglot_v2_optimize       | 75.8 ms                                                                                                                | 79.1 ms: 1.04x slower                                                                                                      |
| regex_compile             | 150 ms                                                                                                                 | 157 ms: 1.05x slower                                                                                                       |
| sqlalchemy_imperative     | 21.3 ms                                                                                                                | 22.4 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_normalize      | 155 ms                                                                                                                 | 164 ms: 1.06x slower                                                                                                       |
| async_tree_memoization_tg | 634 ms                                                                                                                 | 674 ms: 1.06x slower                                                                                                       |
| sphinx                    | 1.50 sec                                                                                                               | 1.59 sec: 1.06x slower                                                                                                     |
| async_tree_io_tg          | 1.17 sec                                                                                                               | 1.26 sec: 1.08x slower                                                                                                     |
| pycparser                 | 1.51 sec                                                                                                               | 1.64 sec: 1.09x slower                                                                                                     |
| many_optionals            | 929 us                                                                                                                 | 1.01 ms: 1.09x slower                                                                                                      |
| pylint                    | 414 ms                                                                                                                 | 452 ms: 1.09x slower                                                                                                       |
| hexiom                    | 8.73 ms                                                                                                                | 9.54 ms: 1.09x slower                                                                                                      |
| async_generators          | 562 ms                                                                                                                 | 617 ms: 1.10x slower                                                                                                       |
| deepcopy                  | 377 us                                                                                                                 | 420 us: 1.11x slower                                                                                                       |
| genshi_text               | 34.3 ms                                                                                                                | 38.1 ms: 1.11x slower                                                                                                      |
| docutils                  | 4.30 sec                                                                                                               | 4.78 sec: 1.11x slower                                                                                                     |
| mdp                       | 2.47 sec                                                                                                               | 2.84 sec: 1.15x slower                                                                                                     |
| html5lib                  | 79.4 ms                                                                                                                | 92.1 ms: 1.16x slower                                                                                                      |
| nqueens                   | 120 ms                                                                                                                 | 140 ms: 1.17x slower                                                                                                       |
| dulwich_log               | 65.6 ms                                                                                                                | 78.2 ms: 1.19x slower                                                                                                      |
| unpack_sequence           | 67.8 ns                                                                                                                | 86.0 ns: 1.27x slower                                                                                                      |
| genshi_xml                | 79.0 ms                                                                                                                | 101 ms: 1.28x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (22): bench_thread_pool, tornado_http, comprehensions, sqlglot_v2_parse, django_template, pickle_dict, pickle, subparsers, create_gc_cycles, async_tree_none, pidigits, thrift, k_core, chaos, connected_components, generators, async_tree_memoization, async_tree_cpu_io_mixed, sqlglot_v2_transpile, async_tree_cpu_io_mixed_tg, async_tree_none_tg, bench_mp_pool
Ignored benchmarks (4) of results/bm-20251218-3.15.0a3+-e4058d7/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3+-e4058d7.json: sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.014x faster

# HPT report

- Reliability score: 65.87% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x