# Results vs. base

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: c99f766
- commit date: 2026-01-04
- overall geometric mean: 1.142x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x slower
- Memory change: unknown

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 343 ms                                                                     | 464 ms: 1.35x slower                                       |
| chameleon      | 16.4 ms                                                                    | 28.2 ms: 1.72x slower                                      |
| docutils       | 2.42 sec                                                                   | 3.19 sec: 1.32x slower                                     |
| html5lib       | 62.7 ms                                                                    | 84.0 ms: 1.34x slower                                      |
| sphinx         | 1.00 sec                                                                   | 1.33 sec: 1.32x slower                                     |
| tornado_http   | 159 ms                                                                     | 201 ms: 1.27x slower                                       |
| Geometric mean | (ref)                                                                      | 1.38x slower                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|----------------------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| asyncio_websockets         | 211 ms                                                                     | 226 ms: 1.07x slower                                       |
| async_tree_cpu_io_mixed    | 561 ms                                                                     | 766 ms: 1.37x slower                                       |
| async_tree_cpu_io_mixed_tg | 541 ms                                                                     | 758 ms: 1.40x slower                                       |
| async_tree_memoization     | 370 ms                                                                     | 518 ms: 1.40x slower                                       |
| async_tree_none            | 304 ms                                                                     | 435 ms: 1.43x slower                                       |
| async_generators           | 466 ms                                                                     | 669 ms: 1.44x slower                                       |
| async_tree_io              | 672 ms                                                                     | 976 ms: 1.45x slower                                       |
| async_tree_memoization_tg  | 342 ms                                                                     | 518 ms: 1.51x slower                                       |
| async_tree_io_tg           | 640 ms                                                                     | 976 ms: 1.53x slower                                       |
| async_tree_none_tg         | 273 ms                                                                     | 417 ms: 1.53x slower                                       |
| coroutines                 | 29.7 ms                                                                    | 46.5 ms: 1.57x slower                                      |
| Geometric mean             | (ref)                                                                      | 1.42x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 135 ms                                                                     | 80.7 ms: 1.68x faster                                      |
| float          | 77.1 ms                                                                    | 55.5 ms: 1.39x faster                                      |
| pidigits       | 190 ms                                                                     | 184 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                                      | 1.34x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 146 ms                                                                     | 177 ms: 1.21x slower                                       |
| regex_v8       | 24.0 ms                                                                    | 29.5 ms: 1.23x slower                                      |
| regex_effbot   | 2.55 ms                                                                    | 3.16 ms: 1.24x slower                                      |
| Geometric mean | (ref)                                                                      | 1.17x slower                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|----------------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_pure_python | 280 us                                                                     | 233 us: 1.20x faster                                       |
| tomli_loads          | 2.47 sec                                                                   | 2.32 sec: 1.07x faster                                     |
| pickle_pure_python   | 380 us                                                                     | 388 us: 1.02x slower                                       |
| json_dumps           | 9.33 ms                                                                    | 11.1 ms: 1.18x slower                                      |
| xml_etree_iterparse  | 111 ms                                                                     | 135 ms: 1.22x slower                                       |
| xml_etree_parse      | 154 ms                                                                     | 196 ms: 1.27x slower                                       |
| xml_etree_generate   | 100 ms                                                                     | 138 ms: 1.38x slower                                       |
| xml_etree_process    | 69.4 ms                                                                    | 102 ms: 1.47x slower                                       |
| json_loads           | 23.4 us                                                                    | 37.2 us: 1.59x slower                                      |
| Geometric mean       | (ref)                                                                      | 1.19x slower                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|------------------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 24.3 ms                                                                    | 25.5 ms: 1.05x slower                                      |
| python_startup         | 33.2 ms                                                                    | 35.8 ms: 1.08x slower                                      |
| Geometric mean         | (ref)                                                                      | 1.06x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|-----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 12.2 ms                                                                    | 11.8 ms: 1.03x faster                                      |
| genshi_text     | 26.8 ms                                                                    | 31.0 ms: 1.16x slower                                      |
| genshi_xml      | 64.1 ms                                                                    | 76.1 ms: 1.19x slower                                      |
| django_template | 41.4 ms                                                                    | 65.7 ms: 1.59x slower                                      |
| Geometric mean  | (ref)                                                                      | 1.20x slower                                               |

All benchmarks:
===============

| Benchmark                  | bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766 | bm-20260104-prometheus-amd64-python-main-3.15.0a3+-c99f766 |
|----------------------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------:|
| richards                   | 51.3 ms                                                                    | 19.5 ms: 2.64x faster                                      |
| richards_super             | 57.4 ms                                                                    | 24.0 ms: 2.39x faster                                      |
| nbody                      | 135 ms                                                                     | 80.7 ms: 1.68x faster                                      |
| scimark_fft                | 392 ms                                                                     | 281 ms: 1.39x faster                                       |
| float                      | 77.1 ms                                                                    | 55.5 ms: 1.39x faster                                      |
| scimark_sparse_mat_mult    | 5.23 ms                                                                    | 3.79 ms: 1.38x faster                                      |
| scimark_monte_carlo        | 79.8 ms                                                                    | 59.0 ms: 1.35x faster                                      |
| pyflate                    | 493 ms                                                                     | 380 ms: 1.30x faster                                       |
| spectral_norm              | 126 ms                                                                     | 99.2 ms: 1.27x faster                                      |
| logging_silent             | 113 ns                                                                     | 89.7 ns: 1.26x faster                                      |
| fannkuch                   | 514 ms                                                                     | 423 ms: 1.22x faster                                       |
| unpickle_pure_python       | 280 us                                                                     | 233 us: 1.20x faster                                       |
| scimark_lu                 | 134 ms                                                                     | 113 ms: 1.18x faster                                       |
| deepcopy_memo              | 34.0 us                                                                    | 29.0 us: 1.17x faster                                      |
| scimark_sor                | 156 ms                                                                     | 136 ms: 1.15x faster                                       |
| go                         | 132 ms                                                                     | 117 ms: 1.13x faster                                       |
| meteor_contest             | 116 ms                                                                     | 108 ms: 1.08x faster                                       |
| tomli_loads                | 2.47 sec                                                                   | 2.32 sec: 1.07x faster                                     |
| comprehensions             | 19.5 us                                                                    | 18.4 us: 1.06x faster                                      |
| connected_components       | 483 ms                                                                     | 459 ms: 1.05x faster                                       |
| deltablue                  | 4.32 ms                                                                    | 4.10 ms: 1.05x faster                                      |
| shortest_path              | 516 ms                                                                     | 497 ms: 1.04x faster                                       |
| mako                       | 12.2 ms                                                                    | 11.8 ms: 1.03x faster                                      |
| pidigits                   | 190 ms                                                                     | 184 ms: 1.03x faster                                       |
| k_core                     | 2.26 sec                                                                   | 2.23 sec: 1.01x faster                                     |
| crypto_pyaes               | 90.4 ms                                                                    | 91.0 ms: 1.01x slower                                      |
| pickle_pure_python         | 380 us                                                                     | 388 us: 1.02x slower                                       |
| pprint_safe_repr           | 874 ms                                                                     | 894 ms: 1.02x slower                                       |
| pprint_pformat             | 1.78 sec                                                                   | 1.85 sec: 1.04x slower                                     |
| python_startup_no_site     | 24.3 ms                                                                    | 25.5 ms: 1.05x slower                                      |
| asyncio_websockets         | 211 ms                                                                     | 226 ms: 1.07x slower                                       |
| chaos                      | 74.5 ms                                                                    | 80.2 ms: 1.08x slower                                      |
| python_startup             | 33.2 ms                                                                    | 35.8 ms: 1.08x slower                                      |
| bpe_tokeniser              | 5.03 sec                                                                   | 5.44 sec: 1.08x slower                                     |
| hexiom                     | 7.81 ms                                                                    | 8.49 ms: 1.09x slower                                      |
| pathlib                    | 129 ms                                                                     | 143 ms: 1.11x slower                                       |
| nqueens                    | 108 ms                                                                     | 124 ms: 1.15x slower                                       |
| genshi_text                | 26.8 ms                                                                    | 31.0 ms: 1.16x slower                                      |
| create_gc_cycles           | 1.41 ms                                                                    | 1.65 ms: 1.17x slower                                      |
| json_dumps                 | 9.33 ms                                                                    | 11.1 ms: 1.18x slower                                      |
| genshi_xml                 | 64.1 ms                                                                    | 76.1 ms: 1.19x slower                                      |
| regex_compile              | 146 ms                                                                     | 177 ms: 1.21x slower                                       |
| xml_etree_iterparse        | 111 ms                                                                     | 135 ms: 1.22x slower                                       |
| sqlite_synth               | 2.71 us                                                                    | 3.31 us: 1.22x slower                                      |
| regex_v8                   | 24.0 ms                                                                    | 29.5 ms: 1.23x slower                                      |
| sqlglot_v2_parse           | 1.48 ms                                                                    | 1.83 ms: 1.24x slower                                      |
| regex_effbot               | 2.55 ms                                                                    | 3.16 ms: 1.24x slower                                      |
| telco                      | 7.78 ms                                                                    | 9.68 ms: 1.24x slower                                      |
| gc_traversal               | 3.43 ms                                                                    | 4.27 ms: 1.25x slower                                      |
| tornado_http               | 159 ms                                                                     | 201 ms: 1.27x slower                                       |
| xml_etree_parse            | 154 ms                                                                     | 196 ms: 1.27x slower                                       |
| pycparser                  | 1.17 sec                                                                   | 1.49 sec: 1.27x slower                                     |
| raytrace                   | 324 ms                                                                     | 415 ms: 1.28x slower                                       |
| sqlalchemy_declarative     | 109 ms                                                                     | 140 ms: 1.28x slower                                       |
| deepcopy                   | 294 us                                                                     | 381 us: 1.29x slower                                       |
| sqlglot_v2_transpile       | 1.78 ms                                                                    | 2.32 ms: 1.30x slower                                      |
| docutils                   | 2.42 sec                                                                   | 3.19 sec: 1.32x slower                                     |
| sphinx                     | 1.00 sec                                                                   | 1.33 sec: 1.32x slower                                     |
| html5lib                   | 62.7 ms                                                                    | 84.0 ms: 1.34x slower                                      |
| 2to3                       | 343 ms                                                                     | 464 ms: 1.35x slower                                       |
| async_tree_cpu_io_mixed    | 561 ms                                                                     | 766 ms: 1.37x slower                                       |
| xml_etree_generate         | 100 ms                                                                     | 138 ms: 1.38x slower                                       |
| dulwich_log                | 87.4 ms                                                                    | 121 ms: 1.39x slower                                       |
| async_tree_cpu_io_mixed_tg | 541 ms                                                                     | 758 ms: 1.40x slower                                       |
| async_tree_memoization     | 370 ms                                                                     | 518 ms: 1.40x slower                                       |
| sympy_integrate            | 18.9 ms                                                                    | 26.5 ms: 1.40x slower                                      |
| pylint                     | 302 ms                                                                     | 427 ms: 1.41x slower                                       |
| sqlalchemy_imperative      | 16.6 ms                                                                    | 23.7 ms: 1.42x slower                                      |
| sympy_sum                  | 146 ms                                                                     | 209 ms: 1.43x slower                                       |
| async_tree_none            | 304 ms                                                                     | 435 ms: 1.43x slower                                       |
| async_generators           | 466 ms                                                                     | 669 ms: 1.44x slower                                       |
| async_tree_io              | 672 ms                                                                     | 976 ms: 1.45x slower                                       |
| logging_simple             | 11.0 us                                                                    | 16.0 us: 1.46x slower                                      |
| logging_format             | 12.0 us                                                                    | 17.6 us: 1.47x slower                                      |
| coverage                   | 90.1 ms                                                                    | 133 ms: 1.47x slower                                       |
| xml_etree_process          | 69.4 ms                                                                    | 102 ms: 1.47x slower                                       |
| json                       | 4.37 ms                                                                    | 6.46 ms: 1.48x slower                                      |
| sympy_str                  | 290 ms                                                                     | 431 ms: 1.48x slower                                       |
| many_optionals             | 590 us                                                                     | 878 us: 1.49x slower                                       |
| subparsers                 | 11.1 ms                                                                    | 16.6 ms: 1.49x slower                                      |
| async_tree_memoization_tg  | 342 ms                                                                     | 518 ms: 1.51x slower                                       |
| async_tree_io_tg           | 640 ms                                                                     | 976 ms: 1.53x slower                                       |
| async_tree_none_tg         | 273 ms                                                                     | 417 ms: 1.53x slower                                       |
| sqlglot_v2_optimize        | 60.8 ms                                                                    | 93.2 ms: 1.53x slower                                      |
| mdp                        | 1.36 sec                                                                   | 2.10 sec: 1.54x slower                                     |
| sympy_expand               | 505 ms                                                                     | 781 ms: 1.54x slower                                       |
| xdsl_constant_fold         | 46.9 ms                                                                    | 72.9 ms: 1.55x slower                                      |
| typing_runtime_protocols   | 183 us                                                                     | 286 us: 1.56x slower                                       |
| coroutines                 | 29.7 ms                                                                    | 46.5 ms: 1.57x slower                                      |
| django_template            | 41.4 ms                                                                    | 65.7 ms: 1.59x slower                                      |
| json_loads                 | 23.4 us                                                                    | 37.2 us: 1.59x slower                                      |
| deepcopy_reduce            | 3.15 us                                                                    | 5.12 us: 1.63x slower                                      |
| sqlglot_v2_normalize       | 127 ms                                                                     | 208 ms: 1.64x slower                                       |
| thrift                     | 837 us                                                                     | 1.42 ms: 1.70x slower                                      |
| generators                 | 37.3 ms                                                                    | 63.6 ms: 1.71x slower                                      |
| chameleon                  | 16.4 ms                                                                    | 28.2 ms: 1.72x slower                                      |
| Geometric mean             | (ref)                                                                      | 1.17x slower                                               |

Benchmark hidden because not significant (1): regex_dna
Ignored benchmarks (10) of results/bm-20260104-3.15.0a3+-c99f766/bm-20260104-prometheus-amd64-python-c99f7667436d8978b407-3.15.0a3+-c99f766.json: asyncio_tcp, asyncio_tcp_ssl, bench_mp_pool, bench_thread_pool, pickle, pickle_dict, pickle_list, unpack_sequence, unpickle, unpickle_list

- Geometric mean (including insignificant results): 1.142x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.15x
- 95% likely to have a slowdown of 1.12x
- 99% likely to have a slowdown of 1.08x

# Memory
- memory change: unknown