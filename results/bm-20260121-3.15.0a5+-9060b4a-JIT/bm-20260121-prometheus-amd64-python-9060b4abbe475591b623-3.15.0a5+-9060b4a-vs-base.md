# Results vs. base

- fork: python
- ref: 9060b4abbe475591b623
- machine: windows-amd64
- commit hash: 9060b4a
- commit date: 2026-01-21
- overall geometric mean: 1.160x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster
- Memory change: unknown

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260121-3.15.0a5+-9060b4a/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json | results/bm-20260121-3.15.0a5+-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 341 ms                                                                                                                | 334 ms: 1.02x faster                                                                                                      |
| chameleon      | 16.9 ms                                                                                                               | 17.2 ms: 1.01x slower                                                                                                     |
| docutils       | 2.41 sec                                                                                                              | 2.42 sec: 1.01x slower                                                                                                    |
| html5lib       | 62.7 ms                                                                                                               | 56.3 ms: 1.11x faster                                                                                                     |
| tornado_http   | 158 ms                                                                                                                | 161 ms: 1.02x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.02x faster                                                                                                              |

Benchmark hidden because not significant (1): sphinx

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20260121-3.15.0a5+-9060b4a/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json | results/bm-20260121-3.15.0a5+-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json |
|----------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 307 ms                                                                                                                | 279 ms: 1.10x faster                                                                                                      |
| async_tree_memoization     | 370 ms                                                                                                                | 341 ms: 1.09x faster                                                                                                      |
| async_tree_cpu_io_mixed    | 565 ms                                                                                                                | 521 ms: 1.09x faster                                                                                                      |
| asyncio_websockets         | 228 ms                                                                                                                | 217 ms: 1.05x faster                                                                                                      |
| async_tree_memoization_tg  | 343 ms                                                                                                                | 329 ms: 1.04x faster                                                                                                      |
| async_tree_io              | 674 ms                                                                                                                | 645 ms: 1.04x faster                                                                                                      |
| async_tree_none_tg         | 272 ms                                                                                                                | 261 ms: 1.04x faster                                                                                                      |
| async_tree_cpu_io_mixed_tg | 546 ms                                                                                                                | 529 ms: 1.03x faster                                                                                                      |
| async_tree_io_tg           | 641 ms                                                                                                                | 628 ms: 1.02x faster                                                                                                      |
| asyncio_tcp                | 713 ms                                                                                                                | 709 ms: 1.01x faster                                                                                                      |
| coroutines                 | 31.0 ms                                                                                                               | 31.3 ms: 1.01x slower                                                                                                     |
| async_generators           | 465 ms                                                                                                                | 493 ms: 1.06x slower                                                                                                      |
| Geometric mean             | (ref)                                                                                                                 | 1.03x faster                                                                                                              |

Benchmark hidden because not significant (1): asyncio_tcp_ssl

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260121-3.15.0a5+-9060b4a/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json | results/bm-20260121-3.15.0a5+-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 142 ms                                                                                                                | 79.3 ms: 1.79x faster                                                                                                     |
| float          | 80.7 ms                                                                                                               | 53.8 ms: 1.50x faster                                                                                                     |
| pidigits       | 189 ms                                                                                                                | 189 ms: 1.00x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.39x faster                                                                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260121-3.15.0a5+-9060b4a/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json | results/bm-20260121-3.15.0a5+-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 142 ms                                                                                                                | 121 ms: 1.17x faster                                                                                                      |
| regex_dna      | 172 ms                                                                                                                | 155 ms: 1.11x faster                                                                                                      |
| regex_effbot   | 2.55 ms                                                                                                               | 2.58 ms: 1.01x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                 | 1.06x faster                                                                                                              |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260121-3.15.0a5+-9060b4a/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json | results/bm-20260121-3.15.0a5+-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json |
|----------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| tomli_loads          | 2.59 sec                                                                                                              | 1.67 sec: 1.55x faster                                                                                                    |
| unpickle_pure_python | 262 us                                                                                                                | 175 us: 1.50x faster                                                                                                      |
| pickle_pure_python   | 384 us                                                                                                                | 269 us: 1.43x faster                                                                                                      |
| xml_etree_generate   | 102 ms                                                                                                                | 85.0 ms: 1.20x faster                                                                                                     |
| xml_etree_process    | 70.2 ms                                                                                                               | 60.4 ms: 1.16x faster                                                                                                     |
| xml_etree_iterparse  | 110 ms                                                                                                                | 96.4 ms: 1.14x faster                                                                                                     |
| json_dumps           | 9.21 ms                                                                                                               | 8.12 ms: 1.14x faster                                                                                                     |
| unpickle_list        | 5.46 us                                                                                                               | 4.88 us: 1.12x faster                                                                                                     |
| xml_etree_parse      | 152 ms                                                                                                                | 151 ms: 1.01x faster                                                                                                      |
| pickle               | 13.7 us                                                                                                               | 13.6 us: 1.01x faster                                                                                                     |
| json_loads           | 23.3 us                                                                                                               | 25.1 us: 1.08x slower                                                                                                     |
| pickle_dict          | 31.0 us                                                                                                               | 41.1 us: 1.33x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                 | 1.12x faster                                                                                                              |

Benchmark hidden because not significant (2): pickle_list, unpickle

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260121-3.15.0a5+-9060b4a/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json | results/bm-20260121-3.15.0a5+-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json |
|-----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| mako            | 12.2 ms                                                                                                               | 9.12 ms: 1.33x faster                                                                                                     |
| genshi_text     | 27.6 ms                                                                                                               | 21.9 ms: 1.26x faster                                                                                                     |
| genshi_xml      | 64.7 ms                                                                                                               | 57.1 ms: 1.13x faster                                                                                                     |
| django_template | 41.8 ms                                                                                                               | 39.2 ms: 1.06x faster                                                                                                     |
| Geometric mean  | (ref)                                                                                                                 | 1.19x faster                                                                                                              |

All benchmarks:
===============

| Benchmark                  | results/bm-20260121-3.15.0a5+-9060b4a/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json | results/bm-20260121-3.15.0a5+-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5+-9060b4a.json |
|----------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| richards                   | 50.5 ms                                                                                                               | 18.0 ms: 2.80x faster                                                                                                     |
| richards_super             | 58.0 ms                                                                                                               | 21.5 ms: 2.70x faster                                                                                                     |
| scimark_lu                 | 137 ms                                                                                                                | 72.8 ms: 1.89x faster                                                                                                     |
| nbody                      | 142 ms                                                                                                                | 79.3 ms: 1.79x faster                                                                                                     |
| scimark_sor                | 163 ms                                                                                                                | 92.7 ms: 1.76x faster                                                                                                     |
| deltablue                  | 4.18 ms                                                                                                               | 2.67 ms: 1.56x faster                                                                                                     |
| fannkuch                   | 538 ms                                                                                                                | 346 ms: 1.55x faster                                                                                                      |
| tomli_loads                | 2.59 sec                                                                                                              | 1.67 sec: 1.55x faster                                                                                                    |
| logging_silent             | 116 ns                                                                                                                | 75.9 ns: 1.53x faster                                                                                                     |
| scimark_fft                | 404 ms                                                                                                                | 267 ms: 1.52x faster                                                                                                      |
| scimark_monte_carlo        | 83.5 ms                                                                                                               | 55.1 ms: 1.52x faster                                                                                                     |
| float                      | 80.7 ms                                                                                                               | 53.8 ms: 1.50x faster                                                                                                     |
| unpickle_pure_python       | 262 us                                                                                                                | 175 us: 1.50x faster                                                                                                      |
| pyflate                    | 499 ms                                                                                                                | 344 ms: 1.45x faster                                                                                                      |
| go                         | 137 ms                                                                                                                | 94.6 ms: 1.45x faster                                                                                                     |
| nqueens                    | 110 ms                                                                                                                | 76.0 ms: 1.44x faster                                                                                                     |
| pickle_pure_python         | 384 us                                                                                                                | 269 us: 1.43x faster                                                                                                      |
| deepcopy_memo              | 33.6 us                                                                                                               | 23.9 us: 1.41x faster                                                                                                     |
| pprint_safe_repr           | 873 ms                                                                                                                | 631 ms: 1.38x faster                                                                                                      |
| pprint_pformat             | 1.78 sec                                                                                                              | 1.30 sec: 1.37x faster                                                                                                    |
| spectral_norm              | 129 ms                                                                                                                | 94.3 ms: 1.37x faster                                                                                                     |
| comprehensions             | 20.1 us                                                                                                               | 15.0 us: 1.34x faster                                                                                                     |
| scimark_sparse_mat_mult    | 5.60 ms                                                                                                               | 4.17 ms: 1.34x faster                                                                                                     |
| mako                       | 12.2 ms                                                                                                               | 9.12 ms: 1.33x faster                                                                                                     |
| crypto_pyaes               | 93.1 ms                                                                                                               | 70.5 ms: 1.32x faster                                                                                                     |
| chaos                      | 75.3 ms                                                                                                               | 58.3 ms: 1.29x faster                                                                                                     |
| genshi_text                | 27.6 ms                                                                                                               | 21.9 ms: 1.26x faster                                                                                                     |
| hexiom                     | 7.77 ms                                                                                                               | 6.35 ms: 1.22x faster                                                                                                     |
| bpe_tokeniser              | 5.09 sec                                                                                                              | 4.18 sec: 1.22x faster                                                                                                    |
| deepcopy                   | 288 us                                                                                                                | 238 us: 1.21x faster                                                                                                      |
| deepcopy_reduce            | 3.15 us                                                                                                               | 2.60 us: 1.21x faster                                                                                                     |
| sqlglot_v2_parse           | 1.47 ms                                                                                                               | 1.22 ms: 1.20x faster                                                                                                     |
| xml_etree_generate         | 102 ms                                                                                                                | 85.0 ms: 1.20x faster                                                                                                     |
| meteor_contest             | 118 ms                                                                                                                | 99.8 ms: 1.19x faster                                                                                                     |
| regex_compile              | 142 ms                                                                                                                | 121 ms: 1.17x faster                                                                                                      |
| xml_etree_process          | 70.2 ms                                                                                                               | 60.4 ms: 1.16x faster                                                                                                     |
| raytrace                   | 326 ms                                                                                                                | 280 ms: 1.16x faster                                                                                                      |
| xml_etree_iterparse        | 110 ms                                                                                                                | 96.4 ms: 1.14x faster                                                                                                     |
| json_dumps                 | 9.21 ms                                                                                                               | 8.12 ms: 1.14x faster                                                                                                     |
| genshi_xml                 | 64.7 ms                                                                                                               | 57.1 ms: 1.13x faster                                                                                                     |
| sqlglot_v2_transpile       | 1.75 ms                                                                                                               | 1.54 ms: 1.13x faster                                                                                                     |
| unpickle_list              | 5.46 us                                                                                                               | 4.88 us: 1.12x faster                                                                                                     |
| telco                      | 7.88 ms                                                                                                               | 7.07 ms: 1.11x faster                                                                                                     |
| html5lib                   | 62.7 ms                                                                                                               | 56.3 ms: 1.11x faster                                                                                                     |
| regex_dna                  | 172 ms                                                                                                                | 155 ms: 1.11x faster                                                                                                      |
| async_tree_none            | 307 ms                                                                                                                | 279 ms: 1.10x faster                                                                                                      |
| pycparser                  | 1.18 sec                                                                                                              | 1.08 sec: 1.09x faster                                                                                                    |
| async_tree_memoization     | 370 ms                                                                                                                | 341 ms: 1.09x faster                                                                                                      |
| async_tree_cpu_io_mixed    | 565 ms                                                                                                                | 521 ms: 1.09x faster                                                                                                      |
| logging_format             | 11.9 us                                                                                                               | 10.9 us: 1.08x faster                                                                                                     |
| connected_components       | 495 ms                                                                                                                | 456 ms: 1.08x faster                                                                                                      |
| sqlite_synth               | 2.70 us                                                                                                               | 2.51 us: 1.08x faster                                                                                                     |
| k_core                     | 2.27 sec                                                                                                              | 2.12 sec: 1.07x faster                                                                                                    |
| logging_simple             | 10.8 us                                                                                                               | 10.1 us: 1.07x faster                                                                                                     |
| django_template            | 41.8 ms                                                                                                               | 39.2 ms: 1.06x faster                                                                                                     |
| shortest_path              | 524 ms                                                                                                                | 493 ms: 1.06x faster                                                                                                      |
| asyncio_websockets         | 228 ms                                                                                                                | 217 ms: 1.05x faster                                                                                                      |
| typing_runtime_protocols   | 183 us                                                                                                                | 174 us: 1.05x faster                                                                                                      |
| async_tree_memoization_tg  | 343 ms                                                                                                                | 329 ms: 1.04x faster                                                                                                      |
| async_tree_io              | 674 ms                                                                                                                | 645 ms: 1.04x faster                                                                                                      |
| async_tree_none_tg         | 272 ms                                                                                                                | 261 ms: 1.04x faster                                                                                                      |
| json                       | 4.63 ms                                                                                                               | 4.44 ms: 1.04x faster                                                                                                     |
| bench_thread_pool          | 1.29 ms                                                                                                               | 1.24 ms: 1.04x faster                                                                                                     |
| async_tree_cpu_io_mixed_tg | 546 ms                                                                                                                | 529 ms: 1.03x faster                                                                                                      |
| sqlalchemy_declarative     | 110 ms                                                                                                                | 107 ms: 1.03x faster                                                                                                      |
| subparsers                 | 10.9 ms                                                                                                               | 10.7 ms: 1.02x faster                                                                                                     |
| 2to3                       | 341 ms                                                                                                                | 334 ms: 1.02x faster                                                                                                      |
| async_tree_io_tg           | 641 ms                                                                                                                | 628 ms: 1.02x faster                                                                                                      |
| xml_etree_parse            | 152 ms                                                                                                                | 151 ms: 1.01x faster                                                                                                      |
| bench_mp_pool              | 131 ms                                                                                                                | 130 ms: 1.01x faster                                                                                                      |
| create_gc_cycles           | 1.43 ms                                                                                                               | 1.42 ms: 1.01x faster                                                                                                     |
| pickle                     | 13.7 us                                                                                                               | 13.6 us: 1.01x faster                                                                                                     |
| asyncio_tcp                | 713 ms                                                                                                                | 709 ms: 1.01x faster                                                                                                      |
| pidigits                   | 189 ms                                                                                                                | 189 ms: 1.00x slower                                                                                                      |
| docutils                   | 2.41 sec                                                                                                              | 2.42 sec: 1.01x slower                                                                                                    |
| regex_effbot               | 2.55 ms                                                                                                               | 2.58 ms: 1.01x slower                                                                                                     |
| coroutines                 | 31.0 ms                                                                                                               | 31.3 ms: 1.01x slower                                                                                                     |
| gc_traversal               | 3.41 ms                                                                                                               | 3.46 ms: 1.01x slower                                                                                                     |
| chameleon                  | 16.9 ms                                                                                                               | 17.2 ms: 1.01x slower                                                                                                     |
| tornado_http               | 158 ms                                                                                                                | 161 ms: 1.02x slower                                                                                                      |
| sqlglot_v2_normalize       | 125 ms                                                                                                                | 127 ms: 1.02x slower                                                                                                      |
| pathlib                    | 120 ms                                                                                                                | 123 ms: 1.02x slower                                                                                                      |
| sympy_integrate            | 18.7 ms                                                                                                               | 19.1 ms: 1.02x slower                                                                                                     |
| generators                 | 38.2 ms                                                                                                               | 39.0 ms: 1.02x slower                                                                                                     |
| thrift                     | 842 us                                                                                                                | 860 us: 1.02x slower                                                                                                      |
| unpack_sequence            | 60.3 ns                                                                                                               | 61.9 ns: 1.03x slower                                                                                                     |
| sqlalchemy_imperative      | 16.7 ms                                                                                                               | 17.2 ms: 1.03x slower                                                                                                     |
| sympy_sum                  | 145 ms                                                                                                                | 151 ms: 1.04x slower                                                                                                      |
| sympy_expand               | 490 ms                                                                                                                | 511 ms: 1.04x slower                                                                                                      |
| many_optionals             | 590 us                                                                                                                | 617 us: 1.04x slower                                                                                                      |
| sympy_str                  | 286 ms                                                                                                                | 302 ms: 1.06x slower                                                                                                      |
| async_generators           | 465 ms                                                                                                                | 493 ms: 1.06x slower                                                                                                      |
| dulwich_log                | 83.7 ms                                                                                                               | 88.7 ms: 1.06x slower                                                                                                     |
| mdp                        | 1.37 sec                                                                                                              | 1.45 sec: 1.06x slower                                                                                                    |
| pylint                     | 299 ms                                                                                                                | 320 ms: 1.07x slower                                                                                                      |
| json_loads                 | 23.3 us                                                                                                               | 25.1 us: 1.08x slower                                                                                                     |
| pickle_dict                | 31.0 us                                                                                                               | 41.1 us: 1.33x slower                                                                                                     |
| Geometric mean             | (ref)                                                                                                                 | 1.15x faster                                                                                                              |

Benchmark hidden because not significant (10): sphinx, pickle_list, unpickle, python_startup, sqlglot_v2_optimize, asyncio_tcp_ssl, coverage, xdsl_constant_fold, python_startup_no_site, regex_v8

- Geometric mean (including insignificant results): 1.160x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.06x
- 99% likely to have a speedup of 1.04x

# Memory
- memory change: unknown