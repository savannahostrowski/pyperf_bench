# Results vs. base

- fork: python
- ref: c461aa99e2fabbaf5859
- machine: windows-amd64
- commit hash: c461aa9
- commit date: 2026-01-15
- overall geometric mean: 1.144x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster
- Memory change: unknown

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 340 ms                                                                                                                | 336 ms: 1.01x faster                                                                                                      |
| chameleon      | 16.4 ms                                                                                                               | 16.9 ms: 1.03x slower                                                                                                     |
| html5lib       | 62.4 ms                                                                                                               | 56.4 ms: 1.11x faster                                                                                                     |
| sphinx         | 982 ms                                                                                                                | 974 ms: 1.01x faster                                                                                                      |
| tornado_http   | 158 ms                                                                                                                | 161 ms: 1.02x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.01x faster                                                                                                              |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|-------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none         | 306 ms                                                                                                                | 286 ms: 1.07x faster                                                                                                      |
| async_tree_memoization  | 367 ms                                                                                                                | 352 ms: 1.04x faster                                                                                                      |
| async_tree_io           | 678 ms                                                                                                                | 657 ms: 1.03x faster                                                                                                      |
| async_tree_cpu_io_mixed | 551 ms                                                                                                                | 543 ms: 1.02x faster                                                                                                      |
| async_tree_none_tg      | 273 ms                                                                                                                | 271 ms: 1.01x faster                                                                                                      |
| coroutines              | 30.8 ms                                                                                                               | 31.0 ms: 1.01x slower                                                                                                     |
| asyncio_tcp             | 711 ms                                                                                                                | 717 ms: 1.01x slower                                                                                                      |
| asyncio_tcp_ssl         | 2.12 sec                                                                                                              | 2.14 sec: 1.01x slower                                                                                                    |
| async_generators        | 467 ms                                                                                                                | 501 ms: 1.07x slower                                                                                                      |
| Geometric mean          | (ref)                                                                                                                 | 1.01x faster                                                                                                              |

Benchmark hidden because not significant (4): async_tree_memoization_tg, async_tree_io_tg, async_tree_cpu_io_mixed_tg, asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 132 ms                                                                                                                | 79.8 ms: 1.65x faster                                                                                                     |
| float          | 78.7 ms                                                                                                               | 53.2 ms: 1.48x faster                                                                                                     |
| pidigits       | 187 ms                                                                                                                | 188 ms: 1.01x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.34x faster                                                                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 142 ms                                                                                                                | 122 ms: 1.16x faster                                                                                                      |
| regex_dna      | 172 ms                                                                                                                | 154 ms: 1.12x faster                                                                                                      |
| regex_effbot   | 2.59 ms                                                                                                               | 2.55 ms: 1.02x faster                                                                                                     |
| Geometric mean | (ref)                                                                                                                 | 1.07x faster                                                                                                              |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| tomli_loads          | 2.51 sec                                                                                                              | 1.69 sec: 1.49x faster                                                                                                    |
| unpickle_pure_python | 255 us                                                                                                                | 175 us: 1.46x faster                                                                                                      |
| pickle_pure_python   | 380 us                                                                                                                | 269 us: 1.42x faster                                                                                                      |
| xml_etree_generate   | 100 ms                                                                                                                | 86.1 ms: 1.16x faster                                                                                                     |
| json_dumps           | 9.31 ms                                                                                                               | 8.21 ms: 1.13x faster                                                                                                     |
| xml_etree_process    | 69.3 ms                                                                                                               | 61.4 ms: 1.13x faster                                                                                                     |
| unpickle_list        | 5.55 us                                                                                                               | 4.92 us: 1.13x faster                                                                                                     |
| xml_etree_iterparse  | 109 ms                                                                                                                | 100 ms: 1.09x faster                                                                                                      |
| pickle               | 14.5 us                                                                                                               | 13.5 us: 1.08x faster                                                                                                     |
| pickle_list          | 4.98 us                                                                                                               | 4.76 us: 1.05x faster                                                                                                     |
| xml_etree_parse      | 152 ms                                                                                                                | 151 ms: 1.01x faster                                                                                                      |
| pickle_dict          | 30.8 us                                                                                                               | 31.5 us: 1.03x slower                                                                                                     |
| json_loads           | 23.5 us                                                                                                               | 25.5 us: 1.08x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                 | 1.13x faster                                                                                                              |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| python_startup | 32.6 ms                                                                                                               | 32.8 ms: 1.01x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                 | 1.00x slower                                                                                                              |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|-----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| mako            | 12.4 ms                                                                                                               | 9.17 ms: 1.35x faster                                                                                                     |
| genshi_text     | 26.8 ms                                                                                                               | 22.0 ms: 1.22x faster                                                                                                     |
| genshi_xml      | 62.0 ms                                                                                                               | 57.7 ms: 1.07x faster                                                                                                     |
| django_template | 41.4 ms                                                                                                               | 39.9 ms: 1.04x faster                                                                                                     |
| Geometric mean  | (ref)                                                                                                                 | 1.16x faster                                                                                                              |

All benchmarks:
===============

| Benchmark                | results/bm-20260115-3.15.0a5+-c461aa9/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json | results/bm-20260115-3.15.0a5+-c461aa9-JIT/bm-20260115-prometheus-amd64-python-c461aa99e2fabbaf5859-3.15.0a5+-c461aa9.json |
|--------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 49.6 ms                                                                                                               | 17.8 ms: 2.79x faster                                                                                                     |
| richards_super           | 56.5 ms                                                                                                               | 21.5 ms: 2.63x faster                                                                                                     |
| scimark_lu               | 136 ms                                                                                                                | 71.9 ms: 1.89x faster                                                                                                     |
| scimark_sor              | 160 ms                                                                                                                | 92.4 ms: 1.73x faster                                                                                                     |
| nbody                    | 132 ms                                                                                                                | 79.8 ms: 1.65x faster                                                                                                     |
| deltablue                | 4.12 ms                                                                                                               | 2.67 ms: 1.54x faster                                                                                                     |
| scimark_fft              | 380 ms                                                                                                                | 252 ms: 1.51x faster                                                                                                      |
| tomli_loads              | 2.51 sec                                                                                                              | 1.69 sec: 1.49x faster                                                                                                    |
| logging_silent           | 116 ns                                                                                                                | 77.8 ns: 1.49x faster                                                                                                     |
| float                    | 78.7 ms                                                                                                               | 53.2 ms: 1.48x faster                                                                                                     |
| unpickle_pure_python     | 255 us                                                                                                                | 175 us: 1.46x faster                                                                                                      |
| pyflate                  | 493 ms                                                                                                                | 338 ms: 1.46x faster                                                                                                      |
| scimark_monte_carlo      | 78.7 ms                                                                                                               | 54.2 ms: 1.45x faster                                                                                                     |
| go                       | 137 ms                                                                                                                | 94.3 ms: 1.45x faster                                                                                                     |
| fannkuch                 | 520 ms                                                                                                                | 359 ms: 1.45x faster                                                                                                      |
| pickle_pure_python       | 380 us                                                                                                                | 269 us: 1.42x faster                                                                                                      |
| pprint_safe_repr         | 887 ms                                                                                                                | 632 ms: 1.40x faster                                                                                                      |
| pprint_pformat           | 1.82 sec                                                                                                              | 1.31 sec: 1.39x faster                                                                                                    |
| spectral_norm            | 131 ms                                                                                                                | 94.6 ms: 1.39x faster                                                                                                     |
| nqueens                  | 108 ms                                                                                                                | 78.3 ms: 1.38x faster                                                                                                     |
| mako                     | 12.4 ms                                                                                                               | 9.17 ms: 1.35x faster                                                                                                     |
| scimark_sparse_mat_mult  | 5.46 ms                                                                                                               | 4.11 ms: 1.33x faster                                                                                                     |
| chaos                    | 75.3 ms                                                                                                               | 57.2 ms: 1.32x faster                                                                                                     |
| comprehensions           | 19.9 us                                                                                                               | 15.1 us: 1.31x faster                                                                                                     |
| crypto_pyaes             | 92.3 ms                                                                                                               | 70.7 ms: 1.31x faster                                                                                                     |
| deepcopy_memo            | 33.3 us                                                                                                               | 27.2 us: 1.22x faster                                                                                                     |
| genshi_text              | 26.8 ms                                                                                                               | 22.0 ms: 1.22x faster                                                                                                     |
| bpe_tokeniser            | 5.08 sec                                                                                                              | 4.23 sec: 1.20x faster                                                                                                    |
| deepcopy                 | 285 us                                                                                                                | 238 us: 1.20x faster                                                                                                      |
| sqlglot_v2_parse         | 1.46 ms                                                                                                               | 1.21 ms: 1.20x faster                                                                                                     |
| meteor_contest           | 119 ms                                                                                                                | 99.3 ms: 1.20x faster                                                                                                     |
| deepcopy_reduce          | 3.12 us                                                                                                               | 2.63 us: 1.19x faster                                                                                                     |
| xml_etree_generate       | 100 ms                                                                                                                | 86.1 ms: 1.16x faster                                                                                                     |
| regex_compile            | 142 ms                                                                                                                | 122 ms: 1.16x faster                                                                                                      |
| raytrace                 | 323 ms                                                                                                                | 279 ms: 1.16x faster                                                                                                      |
| hexiom                   | 7.64 ms                                                                                                               | 6.61 ms: 1.16x faster                                                                                                     |
| sqlglot_v2_transpile     | 1.74 ms                                                                                                               | 1.52 ms: 1.14x faster                                                                                                     |
| json_dumps               | 9.31 ms                                                                                                               | 8.21 ms: 1.13x faster                                                                                                     |
| xml_etree_process        | 69.3 ms                                                                                                               | 61.4 ms: 1.13x faster                                                                                                     |
| unpickle_list            | 5.55 us                                                                                                               | 4.92 us: 1.13x faster                                                                                                     |
| telco                    | 7.83 ms                                                                                                               | 6.98 ms: 1.12x faster                                                                                                     |
| regex_dna                | 172 ms                                                                                                                | 154 ms: 1.12x faster                                                                                                      |
| html5lib                 | 62.4 ms                                                                                                               | 56.4 ms: 1.11x faster                                                                                                     |
| xml_etree_iterparse      | 109 ms                                                                                                                | 100 ms: 1.09x faster                                                                                                      |
| logging_format           | 12.0 us                                                                                                               | 11.2 us: 1.08x faster                                                                                                     |
| pickle                   | 14.5 us                                                                                                               | 13.5 us: 1.08x faster                                                                                                     |
| pycparser                | 1.17 sec                                                                                                              | 1.09 sec: 1.07x faster                                                                                                    |
| genshi_xml               | 62.0 ms                                                                                                               | 57.7 ms: 1.07x faster                                                                                                     |
| k_core                   | 2.27 sec                                                                                                              | 2.12 sec: 1.07x faster                                                                                                    |
| async_tree_none          | 306 ms                                                                                                                | 286 ms: 1.07x faster                                                                                                      |
| logging_simple           | 11.1 us                                                                                                               | 10.4 us: 1.07x faster                                                                                                     |
| connected_components     | 486 ms                                                                                                                | 455 ms: 1.07x faster                                                                                                      |
| shortest_path            | 520 ms                                                                                                                | 493 ms: 1.06x faster                                                                                                      |
| json                     | 4.59 ms                                                                                                               | 4.36 ms: 1.05x faster                                                                                                     |
| pickle_list              | 4.98 us                                                                                                               | 4.76 us: 1.05x faster                                                                                                     |
| sqlite_synth             | 2.66 us                                                                                                               | 2.54 us: 1.04x faster                                                                                                     |
| async_tree_memoization   | 367 ms                                                                                                                | 352 ms: 1.04x faster                                                                                                      |
| django_template          | 41.4 ms                                                                                                               | 39.9 ms: 1.04x faster                                                                                                     |
| async_tree_io            | 678 ms                                                                                                                | 657 ms: 1.03x faster                                                                                                      |
| typing_runtime_protocols | 179 us                                                                                                                | 175 us: 1.03x faster                                                                                                      |
| bench_thread_pool        | 1.29 ms                                                                                                               | 1.26 ms: 1.02x faster                                                                                                     |
| regex_effbot             | 2.59 ms                                                                                                               | 2.55 ms: 1.02x faster                                                                                                     |
| async_tree_cpu_io_mixed  | 551 ms                                                                                                                | 543 ms: 1.02x faster                                                                                                      |
| 2to3                     | 340 ms                                                                                                                | 336 ms: 1.01x faster                                                                                                      |
| subparsers               | 10.9 ms                                                                                                               | 10.8 ms: 1.01x faster                                                                                                     |
| async_tree_none_tg       | 273 ms                                                                                                                | 271 ms: 1.01x faster                                                                                                      |
| sphinx                   | 982 ms                                                                                                                | 974 ms: 1.01x faster                                                                                                      |
| xml_etree_parse          | 152 ms                                                                                                                | 151 ms: 1.01x faster                                                                                                      |
| python_startup           | 32.6 ms                                                                                                               | 32.8 ms: 1.01x slower                                                                                                     |
| bench_mp_pool            | 129 ms                                                                                                                | 130 ms: 1.01x slower                                                                                                      |
| coroutines               | 30.8 ms                                                                                                               | 31.0 ms: 1.01x slower                                                                                                     |
| pidigits                 | 187 ms                                                                                                                | 188 ms: 1.01x slower                                                                                                      |
| asyncio_tcp              | 711 ms                                                                                                                | 717 ms: 1.01x slower                                                                                                      |
| asyncio_tcp_ssl          | 2.12 sec                                                                                                              | 2.14 sec: 1.01x slower                                                                                                    |
| xdsl_constant_fold       | 46.8 ms                                                                                                               | 47.4 ms: 1.01x slower                                                                                                     |
| coverage                 | 93.1 ms                                                                                                               | 94.3 ms: 1.01x slower                                                                                                     |
| sympy_integrate          | 18.9 ms                                                                                                               | 19.2 ms: 1.02x slower                                                                                                     |
| sqlglot_v2_normalize     | 122 ms                                                                                                                | 125 ms: 1.02x slower                                                                                                      |
| tornado_http             | 158 ms                                                                                                                | 161 ms: 1.02x slower                                                                                                      |
| create_gc_cycles         | 1.41 ms                                                                                                               | 1.44 ms: 1.02x slower                                                                                                     |
| pickle_dict              | 30.8 us                                                                                                               | 31.5 us: 1.03x slower                                                                                                     |
| chameleon                | 16.4 ms                                                                                                               | 16.9 ms: 1.03x slower                                                                                                     |
| sqlalchemy_imperative    | 16.9 ms                                                                                                               | 17.5 ms: 1.04x slower                                                                                                     |
| thrift                   | 839 us                                                                                                                | 871 us: 1.04x slower                                                                                                      |
| sympy_sum                | 146 ms                                                                                                                | 152 ms: 1.04x slower                                                                                                      |
| sympy_expand             | 491 ms                                                                                                                | 511 ms: 1.04x slower                                                                                                      |
| many_optionals           | 596 us                                                                                                                | 623 us: 1.05x slower                                                                                                      |
| sympy_str                | 287 ms                                                                                                                | 301 ms: 1.05x slower                                                                                                      |
| dulwich_log              | 84.9 ms                                                                                                               | 89.1 ms: 1.05x slower                                                                                                     |
| pylint                   | 300 ms                                                                                                                | 320 ms: 1.07x slower                                                                                                      |
| mdp                      | 1.37 sec                                                                                                              | 1.46 sec: 1.07x slower                                                                                                    |
| async_generators         | 467 ms                                                                                                                | 501 ms: 1.07x slower                                                                                                      |
| json_loads               | 23.5 us                                                                                                               | 25.5 us: 1.08x slower                                                                                                     |
| generators               | 37.4 ms                                                                                                               | 40.9 ms: 1.09x slower                                                                                                     |
| unpack_sequence          | 53.9 ns                                                                                                               | 62.0 ns: 1.15x slower                                                                                                     |
| Geometric mean           | (ref)                                                                                                                 | 1.13x faster                                                                                                              |

Benchmark hidden because not significant (12): async_tree_memoization_tg, async_tree_io_tg, regex_v8, async_tree_cpu_io_mixed_tg, sqlalchemy_declarative, sqlglot_v2_optimize, python_startup_no_site, unpickle, docutils, pathlib, gc_traversal, asyncio_websockets

- Geometric mean (including insignificant results): 1.144x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x

# Memory
- memory change: unknown