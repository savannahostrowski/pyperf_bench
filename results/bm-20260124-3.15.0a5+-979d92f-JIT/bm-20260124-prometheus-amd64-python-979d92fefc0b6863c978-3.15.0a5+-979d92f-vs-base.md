# Results vs. base

- fork: python
- ref: 979d92fefc0b6863c978
- machine: windows-amd64
- commit hash: 979d92f
- commit date: 2026-01-24
- overall geometric mean: 1.162x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster
- Memory change: unknown

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 340 ms                                                                                                                | 338 ms: 1.01x faster                                                                                                      |
| chameleon      | 16.4 ms                                                                                                               | 16.7 ms: 1.02x slower                                                                                                     |
| html5lib       | 62.3 ms                                                                                                               | 55.8 ms: 1.12x faster                                                                                                     |
| sphinx         | 986 ms                                                                                                                | 963 ms: 1.02x faster                                                                                                      |
| tornado_http   | 157 ms                                                                                                                | 160 ms: 1.02x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.02x faster                                                                                                              |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|---------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| asyncio_websockets        | 228 ms                                                                                                                | 210 ms: 1.09x faster                                                                                                      |
| async_tree_none           | 306 ms                                                                                                                | 283 ms: 1.08x faster                                                                                                      |
| async_tree_memoization    | 368 ms                                                                                                                | 341 ms: 1.08x faster                                                                                                      |
| async_tree_io             | 674 ms                                                                                                                | 651 ms: 1.04x faster                                                                                                      |
| async_tree_cpu_io_mixed   | 554 ms                                                                                                                | 539 ms: 1.03x faster                                                                                                      |
| async_tree_none_tg        | 271 ms                                                                                                                | 264 ms: 1.03x faster                                                                                                      |
| async_tree_memoization_tg | 343 ms                                                                                                                | 335 ms: 1.02x faster                                                                                                      |
| asyncio_tcp_ssl           | 2.12 sec                                                                                                              | 2.13 sec: 1.01x slower                                                                                                    |
| asyncio_tcp               | 704 ms                                                                                                                | 711 ms: 1.01x slower                                                                                                      |
| async_generators          | 463 ms                                                                                                                | 474 ms: 1.02x slower                                                                                                      |
| coroutines                | 30.5 ms                                                                                                               | 32.2 ms: 1.06x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                 | 1.02x faster                                                                                                              |

Benchmark hidden because not significant (2): async_tree_io_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 140 ms                                                                                                                | 79.1 ms: 1.77x faster                                                                                                     |
| float          | 81.5 ms                                                                                                               | 53.1 ms: 1.54x faster                                                                                                     |
| Geometric mean | (ref)                                                                                                                 | 1.40x faster                                                                                                              |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 175 ms                                                                                                                | 153 ms: 1.14x faster                                                                                                      |
| regex_compile  | 142 ms                                                                                                                | 127 ms: 1.12x faster                                                                                                      |
| regex_effbot   | 2.67 ms                                                                                                               | 2.47 ms: 1.08x faster                                                                                                     |
| regex_v8       | 23.6 ms                                                                                                               | 23.9 ms: 1.02x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                 | 1.08x faster                                                                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| tomli_loads          | 2.49 sec                                                                                                              | 1.58 sec: 1.58x faster                                                                                                    |
| unpickle_pure_python | 264 us                                                                                                                | 172 us: 1.53x faster                                                                                                      |
| pickle_pure_python   | 380 us                                                                                                                | 273 us: 1.39x faster                                                                                                      |
| xml_etree_generate   | 102 ms                                                                                                                | 85.3 ms: 1.19x faster                                                                                                     |
| xml_etree_process    | 70.7 ms                                                                                                               | 61.0 ms: 1.16x faster                                                                                                     |
| xml_etree_iterparse  | 111 ms                                                                                                                | 100 ms: 1.11x faster                                                                                                      |
| json_dumps           | 9.15 ms                                                                                                               | 8.31 ms: 1.10x faster                                                                                                     |
| unpickle             | 15.9 us                                                                                                               | 15.1 us: 1.05x faster                                                                                                     |
| pickle_list          | 5.06 us                                                                                                               | 4.89 us: 1.03x faster                                                                                                     |
| xml_etree_parse      | 154 ms                                                                                                                | 150 ms: 1.03x faster                                                                                                      |
| pickle               | 13.8 us                                                                                                               | 13.6 us: 1.02x faster                                                                                                     |
| json_loads           | 23.8 us                                                                                                               | 24.9 us: 1.05x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                 | 1.14x faster                                                                                                              |

Benchmark hidden because not significant (2): pickle_dict, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 24.0 ms                                                                                                               | 24.1 ms: 1.01x slower                                                                                                     |
| Geometric mean         | (ref)                                                                                                                 | 1.01x slower                                                                                                              |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|-----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| mako            | 12.7 ms                                                                                                               | 9.24 ms: 1.37x faster                                                                                                     |
| genshi_text     | 27.4 ms                                                                                                               | 22.0 ms: 1.25x faster                                                                                                     |
| genshi_xml      | 63.2 ms                                                                                                               | 56.4 ms: 1.12x faster                                                                                                     |
| django_template | 41.4 ms                                                                                                               | 38.7 ms: 1.07x faster                                                                                                     |
| Geometric mean  | (ref)                                                                                                                 | 1.20x faster                                                                                                              |

All benchmarks:
===============

| Benchmark                 | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|---------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 51.1 ms                                                                                                               | 17.2 ms: 2.97x faster                                                                                                     |
| richards_super            | 58.3 ms                                                                                                               | 21.1 ms: 2.77x faster                                                                                                     |
| scimark_lu                | 140 ms                                                                                                                | 70.3 ms: 1.99x faster                                                                                                     |
| nbody                     | 140 ms                                                                                                                | 79.1 ms: 1.77x faster                                                                                                     |
| scimark_sor               | 158 ms                                                                                                                | 94.0 ms: 1.68x faster                                                                                                     |
| deepcopy_memo             | 34.2 us                                                                                                               | 21.1 us: 1.62x faster                                                                                                     |
| logging_silent            | 124 ns                                                                                                                | 78.3 ns: 1.59x faster                                                                                                     |
| tomli_loads               | 2.49 sec                                                                                                              | 1.58 sec: 1.58x faster                                                                                                    |
| deltablue                 | 4.23 ms                                                                                                               | 2.72 ms: 1.56x faster                                                                                                     |
| scimark_fft               | 384 ms                                                                                                                | 249 ms: 1.54x faster                                                                                                      |
| float                     | 81.5 ms                                                                                                               | 53.1 ms: 1.54x faster                                                                                                     |
| unpickle_pure_python      | 264 us                                                                                                                | 172 us: 1.53x faster                                                                                                      |
| spectral_norm             | 127 ms                                                                                                                | 84.2 ms: 1.51x faster                                                                                                     |
| scimark_sparse_mat_mult   | 5.19 ms                                                                                                               | 3.61 ms: 1.44x faster                                                                                                     |
| fannkuch                  | 518 ms                                                                                                                | 366 ms: 1.42x faster                                                                                                      |
| nqueens                   | 109 ms                                                                                                                | 77.7 ms: 1.41x faster                                                                                                     |
| pyflate                   | 493 ms                                                                                                                | 351 ms: 1.40x faster                                                                                                      |
| pickle_pure_python        | 380 us                                                                                                                | 273 us: 1.39x faster                                                                                                      |
| pprint_pformat            | 1.79 sec                                                                                                              | 1.30 sec: 1.38x faster                                                                                                    |
| scimark_monte_carlo       | 80.2 ms                                                                                                               | 58.1 ms: 1.38x faster                                                                                                     |
| mako                      | 12.7 ms                                                                                                               | 9.24 ms: 1.37x faster                                                                                                     |
| comprehensions            | 20.3 us                                                                                                               | 15.0 us: 1.36x faster                                                                                                     |
| pprint_safe_repr          | 874 ms                                                                                                                | 644 ms: 1.36x faster                                                                                                      |
| chaos                     | 76.0 ms                                                                                                               | 58.5 ms: 1.30x faster                                                                                                     |
| crypto_pyaes              | 91.2 ms                                                                                                               | 70.6 ms: 1.29x faster                                                                                                     |
| go                        | 136 ms                                                                                                                | 107 ms: 1.27x faster                                                                                                      |
| genshi_text               | 27.4 ms                                                                                                               | 22.0 ms: 1.25x faster                                                                                                     |
| hexiom                    | 7.89 ms                                                                                                               | 6.40 ms: 1.23x faster                                                                                                     |
| sqlglot_v2_parse          | 1.48 ms                                                                                                               | 1.21 ms: 1.23x faster                                                                                                     |
| deepcopy                  | 290 us                                                                                                                | 237 us: 1.22x faster                                                                                                      |
| bpe_tokeniser             | 5.08 sec                                                                                                              | 4.17 sec: 1.22x faster                                                                                                    |
| deepcopy_reduce           | 3.14 us                                                                                                               | 2.59 us: 1.21x faster                                                                                                     |
| raytrace                  | 331 ms                                                                                                                | 276 ms: 1.20x faster                                                                                                      |
| xml_etree_generate        | 102 ms                                                                                                                | 85.3 ms: 1.19x faster                                                                                                     |
| telco                     | 8.01 ms                                                                                                               | 6.83 ms: 1.17x faster                                                                                                     |
| meteor_contest            | 118 ms                                                                                                                | 101 ms: 1.17x faster                                                                                                      |
| xml_etree_process         | 70.7 ms                                                                                                               | 61.0 ms: 1.16x faster                                                                                                     |
| sqlglot_v2_transpile      | 1.76 ms                                                                                                               | 1.52 ms: 1.16x faster                                                                                                     |
| regex_dna                 | 175 ms                                                                                                                | 153 ms: 1.14x faster                                                                                                      |
| genshi_xml                | 63.2 ms                                                                                                               | 56.4 ms: 1.12x faster                                                                                                     |
| regex_compile             | 142 ms                                                                                                                | 127 ms: 1.12x faster                                                                                                      |
| html5lib                  | 62.3 ms                                                                                                               | 55.8 ms: 1.12x faster                                                                                                     |
| xml_etree_iterparse       | 111 ms                                                                                                                | 100 ms: 1.11x faster                                                                                                      |
| json_dumps                | 9.15 ms                                                                                                               | 8.31 ms: 1.10x faster                                                                                                     |
| pycparser                 | 1.20 sec                                                                                                              | 1.10 sec: 1.10x faster                                                                                                    |
| connected_components      | 487 ms                                                                                                                | 447 ms: 1.09x faster                                                                                                      |
| asyncio_websockets        | 228 ms                                                                                                                | 210 ms: 1.09x faster                                                                                                      |
| k_core                    | 2.28 sec                                                                                                              | 2.11 sec: 1.08x faster                                                                                                    |
| async_tree_none           | 306 ms                                                                                                                | 283 ms: 1.08x faster                                                                                                      |
| async_tree_memoization    | 368 ms                                                                                                                | 341 ms: 1.08x faster                                                                                                      |
| regex_effbot              | 2.67 ms                                                                                                               | 2.47 ms: 1.08x faster                                                                                                     |
| django_template           | 41.4 ms                                                                                                               | 38.7 ms: 1.07x faster                                                                                                     |
| logging_simple            | 10.9 us                                                                                                               | 10.2 us: 1.06x faster                                                                                                     |
| typing_runtime_protocols  | 183 us                                                                                                                | 172 us: 1.06x faster                                                                                                      |
| sqlite_synth              | 2.66 us                                                                                                               | 2.50 us: 1.06x faster                                                                                                     |
| shortest_path             | 517 ms                                                                                                                | 490 ms: 1.06x faster                                                                                                      |
| unpickle                  | 15.9 us                                                                                                               | 15.1 us: 1.05x faster                                                                                                     |
| logging_format            | 11.5 us                                                                                                               | 11.0 us: 1.04x faster                                                                                                     |
| async_tree_io             | 674 ms                                                                                                                | 651 ms: 1.04x faster                                                                                                      |
| pickle_list               | 5.06 us                                                                                                               | 4.89 us: 1.03x faster                                                                                                     |
| bench_thread_pool         | 1.29 ms                                                                                                               | 1.25 ms: 1.03x faster                                                                                                     |
| sqlalchemy_declarative    | 110 ms                                                                                                                | 107 ms: 1.03x faster                                                                                                      |
| xml_etree_parse           | 154 ms                                                                                                                | 150 ms: 1.03x faster                                                                                                      |
| async_tree_cpu_io_mixed   | 554 ms                                                                                                                | 539 ms: 1.03x faster                                                                                                      |
| async_tree_none_tg        | 271 ms                                                                                                                | 264 ms: 1.03x faster                                                                                                      |
| subparsers                | 10.9 ms                                                                                                               | 10.7 ms: 1.03x faster                                                                                                     |
| async_tree_memoization_tg | 343 ms                                                                                                                | 335 ms: 1.02x faster                                                                                                      |
| sphinx                    | 986 ms                                                                                                                | 963 ms: 1.02x faster                                                                                                      |
| sqlglot_v2_optimize       | 59.3 ms                                                                                                               | 58.0 ms: 1.02x faster                                                                                                     |
| pickle                    | 13.8 us                                                                                                               | 13.6 us: 1.02x faster                                                                                                     |
| 2to3                      | 340 ms                                                                                                                | 338 ms: 1.01x faster                                                                                                      |
| python_startup_no_site    | 24.0 ms                                                                                                               | 24.1 ms: 1.01x slower                                                                                                     |
| bench_mp_pool             | 129 ms                                                                                                                | 130 ms: 1.01x slower                                                                                                      |
| asyncio_tcp_ssl           | 2.12 sec                                                                                                              | 2.13 sec: 1.01x slower                                                                                                    |
| create_gc_cycles          | 1.40 ms                                                                                                               | 1.41 ms: 1.01x slower                                                                                                     |
| sympy_integrate           | 19.0 ms                                                                                                               | 19.2 ms: 1.01x slower                                                                                                     |
| asyncio_tcp               | 704 ms                                                                                                                | 711 ms: 1.01x slower                                                                                                      |
| xdsl_constant_fold        | 46.6 ms                                                                                                               | 47.1 ms: 1.01x slower                                                                                                     |
| sqlglot_v2_normalize      | 124 ms                                                                                                                | 125 ms: 1.01x slower                                                                                                      |
| sqlalchemy_imperative     | 16.8 ms                                                                                                               | 17.0 ms: 1.01x slower                                                                                                     |
| regex_v8                  | 23.6 ms                                                                                                               | 23.9 ms: 1.02x slower                                                                                                     |
| pathlib                   | 121 ms                                                                                                                | 123 ms: 1.02x slower                                                                                                      |
| chameleon                 | 16.4 ms                                                                                                               | 16.7 ms: 1.02x slower                                                                                                     |
| sympy_expand              | 496 ms                                                                                                                | 505 ms: 1.02x slower                                                                                                      |
| tornado_http              | 157 ms                                                                                                                | 160 ms: 1.02x slower                                                                                                      |
| async_generators          | 463 ms                                                                                                                | 474 ms: 1.02x slower                                                                                                      |
| coverage                  | 90.1 ms                                                                                                               | 92.2 ms: 1.02x slower                                                                                                     |
| thrift                    | 837 us                                                                                                                | 856 us: 1.02x slower                                                                                                      |
| sympy_sum                 | 146 ms                                                                                                                | 150 ms: 1.03x slower                                                                                                      |
| sympy_str                 | 288 ms                                                                                                                | 297 ms: 1.03x slower                                                                                                      |
| many_optionals            | 593 us                                                                                                                | 615 us: 1.04x slower                                                                                                      |
| mdp                       | 1.37 sec                                                                                                              | 1.42 sec: 1.04x slower                                                                                                    |
| dulwich_log               | 85.5 ms                                                                                                               | 89.0 ms: 1.04x slower                                                                                                     |
| json_loads                | 23.8 us                                                                                                               | 24.9 us: 1.05x slower                                                                                                     |
| coroutines                | 30.5 ms                                                                                                               | 32.2 ms: 1.06x slower                                                                                                     |
| pylint                    | 300 ms                                                                                                                | 317 ms: 1.06x slower                                                                                                      |
| gc_traversal              | 3.11 ms                                                                                                               | 3.43 ms: 1.10x slower                                                                                                     |
| unpack_sequence           | 62.2 ns                                                                                                               | 92.4 ns: 1.48x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                 | 1.15x faster                                                                                                              |

Benchmark hidden because not significant (9): async_tree_io_tg, json, async_tree_cpu_io_mixed_tg, docutils, pidigits, generators, pickle_dict, unpickle_list, python_startup

- Geometric mean (including insignificant results): 1.162x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.03x

# Memory
- memory change: unknown