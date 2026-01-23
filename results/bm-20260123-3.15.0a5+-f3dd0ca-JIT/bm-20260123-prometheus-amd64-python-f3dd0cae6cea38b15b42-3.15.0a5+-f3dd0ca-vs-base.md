# Results vs. base

- fork: python
- ref: f3dd0cae6cea38b15b42
- machine: windows-amd64
- commit hash: f3dd0ca
- commit date: 2026-01-23
- overall geometric mean: 1.141x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster
- Memory change: unknown

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 16.6 ms                                                                                                               | 16.8 ms: 1.01x slower                                                                                                     |
| docutils       | 2.41 sec                                                                                                              | 2.42 sec: 1.01x slower                                                                                                    |
| html5lib       | 61.9 ms                                                                                                               | 56.5 ms: 1.10x faster                                                                                                     |
| sphinx         | 984 ms                                                                                                                | 973 ms: 1.01x faster                                                                                                      |
| tornado_http   | 156 ms                                                                                                                | 161 ms: 1.03x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.01x faster                                                                                                              |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none            | 306 ms                                                                                                                | 283 ms: 1.08x faster                                                                                                      |
| async_tree_memoization     | 368 ms                                                                                                                | 345 ms: 1.07x faster                                                                                                      |
| async_tree_cpu_io_mixed    | 559 ms                                                                                                                | 536 ms: 1.04x faster                                                                                                      |
| async_tree_none_tg         | 271 ms                                                                                                                | 264 ms: 1.03x faster                                                                                                      |
| async_tree_cpu_io_mixed_tg | 541 ms                                                                                                                | 533 ms: 1.02x faster                                                                                                      |
| asyncio_tcp_ssl            | 2.13 sec                                                                                                              | 2.12 sec: 1.01x faster                                                                                                    |
| asyncio_websockets         | 209 ms                                                                                                                | 209 ms: 1.00x slower                                                                                                      |
| coroutines                 | 30.7 ms                                                                                                               | 31.2 ms: 1.01x slower                                                                                                     |
| async_generators           | 457 ms                                                                                                                | 483 ms: 1.06x slower                                                                                                      |
| Geometric mean             | (ref)                                                                                                                 | 1.02x faster                                                                                                              |

Benchmark hidden because not significant (4): async_tree_io, async_tree_memoization_tg, async_tree_io_tg, asyncio_tcp

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 135 ms                                                                                                                | 79.4 ms: 1.70x faster                                                                                                     |
| float          | 79.0 ms                                                                                                               | 53.2 ms: 1.49x faster                                                                                                     |
| pidigits       | 187 ms                                                                                                                | 188 ms: 1.00x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.36x faster                                                                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                                                                                | 127 ms: 1.11x faster                                                                                                      |
| regex_dna      | 175 ms                                                                                                                | 163 ms: 1.07x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                 | 1.04x faster                                                                                                              |

Benchmark hidden because not significant (2): regex_effbot, regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 258 us                                                                                                                | 172 us: 1.50x faster                                                                                                      |
| tomli_loads          | 2.46 sec                                                                                                              | 1.67 sec: 1.47x faster                                                                                                    |
| pickle_pure_python   | 380 us                                                                                                                | 273 us: 1.39x faster                                                                                                      |
| xml_etree_generate   | 101 ms                                                                                                                | 85.7 ms: 1.17x faster                                                                                                     |
| json_dumps           | 9.42 ms                                                                                                               | 8.21 ms: 1.15x faster                                                                                                     |
| pickle               | 15.4 us                                                                                                               | 13.6 us: 1.13x faster                                                                                                     |
| xml_etree_process    | 69.6 ms                                                                                                               | 61.6 ms: 1.13x faster                                                                                                     |
| xml_etree_iterparse  | 108 ms                                                                                                                | 102 ms: 1.06x faster                                                                                                      |
| unpickle_list        | 5.53 us                                                                                                               | 5.36 us: 1.03x faster                                                                                                     |
| pickle_list          | 4.83 us                                                                                                               | 4.77 us: 1.01x faster                                                                                                     |
| pickle_dict          | 32.9 us                                                                                                               | 33.2 us: 1.01x slower                                                                                                     |
| json_loads           | 24.2 us                                                                                                               | 25.5 us: 1.05x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                 | 1.13x faster                                                                                                              |

Benchmark hidden because not significant (2): unpickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|-----------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| mako            | 12.1 ms                                                                                                               | 9.11 ms: 1.33x faster                                                                                                     |
| genshi_text     | 26.3 ms                                                                                                               | 22.1 ms: 1.19x faster                                                                                                     |
| genshi_xml      | 60.9 ms                                                                                                               | 57.4 ms: 1.06x faster                                                                                                     |
| django_template | 40.7 ms                                                                                                               | 39.2 ms: 1.04x faster                                                                                                     |
| Geometric mean  | (ref)                                                                                                                 | 1.15x faster                                                                                                              |

All benchmarks:
===============

| Benchmark                  | results/bm-20260123-3.15.0a5+-f3dd0ca/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json | results/bm-20260123-3.15.0a5+-f3dd0ca-JIT/bm-20260123-prometheus-amd64-python-f3dd0cae6cea38b15b42-3.15.0a5+-f3dd0ca.json |
|----------------------------|:---------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|
| richards                   | 49.8 ms                                                                                                               | 17.3 ms: 2.87x faster                                                                                                     |
| richards_super             | 56.8 ms                                                                                                               | 21.1 ms: 2.69x faster                                                                                                     |
| scimark_lu                 | 135 ms                                                                                                                | 74.2 ms: 1.82x faster                                                                                                     |
| nbody                      | 135 ms                                                                                                                | 79.4 ms: 1.70x faster                                                                                                     |
| scimark_sor                | 156 ms                                                                                                                | 93.4 ms: 1.67x faster                                                                                                     |
| logging_silent             | 128 ns                                                                                                                | 76.3 ns: 1.67x faster                                                                                                     |
| deltablue                  | 4.12 ms                                                                                                               | 2.69 ms: 1.53x faster                                                                                                     |
| deepcopy_memo              | 34.7 us                                                                                                               | 23.0 us: 1.50x faster                                                                                                     |
| unpickle_pure_python       | 258 us                                                                                                                | 172 us: 1.50x faster                                                                                                      |
| scimark_fft                | 383 ms                                                                                                                | 258 ms: 1.49x faster                                                                                                      |
| float                      | 79.0 ms                                                                                                               | 53.2 ms: 1.49x faster                                                                                                     |
| tomli_loads                | 2.46 sec                                                                                                              | 1.67 sec: 1.47x faster                                                                                                    |
| pyflate                    | 507 ms                                                                                                                | 359 ms: 1.41x faster                                                                                                      |
| pickle_pure_python         | 380 us                                                                                                                | 273 us: 1.39x faster                                                                                                      |
| pprint_safe_repr           | 868 ms                                                                                                                | 629 ms: 1.38x faster                                                                                                      |
| pprint_pformat             | 1.77 sec                                                                                                              | 1.29 sec: 1.38x faster                                                                                                    |
| scimark_monte_carlo        | 80.2 ms                                                                                                               | 58.6 ms: 1.37x faster                                                                                                     |
| spectral_norm              | 127 ms                                                                                                                | 93.0 ms: 1.37x faster                                                                                                     |
| nqueens                    | 106 ms                                                                                                                | 78.5 ms: 1.35x faster                                                                                                     |
| scimark_sparse_mat_mult    | 5.24 ms                                                                                                               | 3.90 ms: 1.34x faster                                                                                                     |
| mako                       | 12.1 ms                                                                                                               | 9.11 ms: 1.33x faster                                                                                                     |
| fannkuch                   | 502 ms                                                                                                                | 381 ms: 1.32x faster                                                                                                      |
| comprehensions             | 19.8 us                                                                                                               | 15.2 us: 1.30x faster                                                                                                     |
| crypto_pyaes               | 91.3 ms                                                                                                               | 70.3 ms: 1.30x faster                                                                                                     |
| chaos                      | 74.7 ms                                                                                                               | 58.1 ms: 1.29x faster                                                                                                     |
| go                         | 133 ms                                                                                                                | 107 ms: 1.24x faster                                                                                                      |
| bpe_tokeniser              | 5.08 sec                                                                                                              | 4.22 sec: 1.20x faster                                                                                                    |
| hexiom                     | 7.63 ms                                                                                                               | 6.42 ms: 1.19x faster                                                                                                     |
| genshi_text                | 26.3 ms                                                                                                               | 22.1 ms: 1.19x faster                                                                                                     |
| sqlglot_v2_parse           | 1.43 ms                                                                                                               | 1.21 ms: 1.19x faster                                                                                                     |
| deepcopy_reduce            | 3.14 us                                                                                                               | 2.66 us: 1.18x faster                                                                                                     |
| meteor_contest             | 118 ms                                                                                                                | 101 ms: 1.18x faster                                                                                                      |
| xml_etree_generate         | 101 ms                                                                                                                | 85.7 ms: 1.17x faster                                                                                                     |
| raytrace                   | 323 ms                                                                                                                | 278 ms: 1.16x faster                                                                                                      |
| deepcopy                   | 285 us                                                                                                                | 247 us: 1.16x faster                                                                                                      |
| telco                      | 7.90 ms                                                                                                               | 6.86 ms: 1.15x faster                                                                                                     |
| json_dumps                 | 9.42 ms                                                                                                               | 8.21 ms: 1.15x faster                                                                                                     |
| pickle                     | 15.4 us                                                                                                               | 13.6 us: 1.13x faster                                                                                                     |
| xml_etree_process          | 69.6 ms                                                                                                               | 61.6 ms: 1.13x faster                                                                                                     |
| sqlglot_v2_transpile       | 1.72 ms                                                                                                               | 1.53 ms: 1.12x faster                                                                                                     |
| gc_traversal               | 3.53 ms                                                                                                               | 3.17 ms: 1.11x faster                                                                                                     |
| regex_compile              | 141 ms                                                                                                                | 127 ms: 1.11x faster                                                                                                      |
| logging_simple             | 11.0 us                                                                                                               | 9.97 us: 1.10x faster                                                                                                     |
| html5lib                   | 61.9 ms                                                                                                               | 56.5 ms: 1.10x faster                                                                                                     |
| logging_format             | 11.9 us                                                                                                               | 10.9 us: 1.09x faster                                                                                                     |
| async_tree_none            | 306 ms                                                                                                                | 283 ms: 1.08x faster                                                                                                      |
| pycparser                  | 1.18 sec                                                                                                              | 1.09 sec: 1.08x faster                                                                                                    |
| regex_dna                  | 175 ms                                                                                                                | 163 ms: 1.07x faster                                                                                                      |
| async_tree_memoization     | 368 ms                                                                                                                | 345 ms: 1.07x faster                                                                                                      |
| sqlite_synth               | 2.69 us                                                                                                               | 2.52 us: 1.07x faster                                                                                                     |
| xml_etree_iterparse        | 108 ms                                                                                                                | 102 ms: 1.06x faster                                                                                                      |
| genshi_xml                 | 60.9 ms                                                                                                               | 57.4 ms: 1.06x faster                                                                                                     |
| k_core                     | 2.26 sec                                                                                                              | 2.13 sec: 1.06x faster                                                                                                    |
| connected_components       | 485 ms                                                                                                                | 460 ms: 1.05x faster                                                                                                      |
| async_tree_cpu_io_mixed    | 559 ms                                                                                                                | 536 ms: 1.04x faster                                                                                                      |
| django_template            | 40.7 ms                                                                                                               | 39.2 ms: 1.04x faster                                                                                                     |
| shortest_path              | 514 ms                                                                                                                | 496 ms: 1.04x faster                                                                                                      |
| unpickle_list              | 5.53 us                                                                                                               | 5.36 us: 1.03x faster                                                                                                     |
| async_tree_none_tg         | 271 ms                                                                                                                | 264 ms: 1.03x faster                                                                                                      |
| typing_runtime_protocols   | 181 us                                                                                                                | 176 us: 1.03x faster                                                                                                      |
| json                       | 4.57 ms                                                                                                               | 4.46 ms: 1.03x faster                                                                                                     |
| async_tree_cpu_io_mixed_tg | 541 ms                                                                                                                | 533 ms: 1.02x faster                                                                                                      |
| pickle_list                | 4.83 us                                                                                                               | 4.77 us: 1.01x faster                                                                                                     |
| sphinx                     | 984 ms                                                                                                                | 973 ms: 1.01x faster                                                                                                      |
| sqlalchemy_declarative     | 109 ms                                                                                                                | 108 ms: 1.01x faster                                                                                                      |
| bench_thread_pool          | 1.27 ms                                                                                                               | 1.26 ms: 1.01x faster                                                                                                     |
| subparsers                 | 10.8 ms                                                                                                               | 10.8 ms: 1.01x faster                                                                                                     |
| asyncio_tcp_ssl            | 2.13 sec                                                                                                              | 2.12 sec: 1.01x faster                                                                                                    |
| asyncio_websockets         | 209 ms                                                                                                                | 209 ms: 1.00x slower                                                                                                      |
| pidigits                   | 187 ms                                                                                                                | 188 ms: 1.00x slower                                                                                                      |
| docutils                   | 2.41 sec                                                                                                              | 2.42 sec: 1.01x slower                                                                                                    |
| pickle_dict                | 32.9 us                                                                                                               | 33.2 us: 1.01x slower                                                                                                     |
| chameleon                  | 16.6 ms                                                                                                               | 16.8 ms: 1.01x slower                                                                                                     |
| bench_mp_pool              | 129 ms                                                                                                                | 130 ms: 1.01x slower                                                                                                      |
| xdsl_constant_fold         | 46.8 ms                                                                                                               | 47.4 ms: 1.01x slower                                                                                                     |
| pathlib                    | 122 ms                                                                                                                | 123 ms: 1.01x slower                                                                                                      |
| coroutines                 | 30.7 ms                                                                                                               | 31.2 ms: 1.01x slower                                                                                                     |
| sqlglot_v2_normalize       | 123 ms                                                                                                                | 125 ms: 1.02x slower                                                                                                      |
| create_gc_cycles           | 1.38 ms                                                                                                               | 1.40 ms: 1.02x slower                                                                                                     |
| sympy_integrate            | 18.9 ms                                                                                                               | 19.3 ms: 1.02x slower                                                                                                     |
| thrift                     | 845 us                                                                                                                | 865 us: 1.02x slower                                                                                                      |
| tornado_http               | 156 ms                                                                                                                | 161 ms: 1.03x slower                                                                                                      |
| sympy_expand               | 496 ms                                                                                                                | 513 ms: 1.03x slower                                                                                                      |
| sympy_sum                  | 146 ms                                                                                                                | 152 ms: 1.04x slower                                                                                                      |
| sqlalchemy_imperative      | 16.5 ms                                                                                                               | 17.1 ms: 1.04x slower                                                                                                     |
| dulwich_log                | 84.3 ms                                                                                                               | 88.2 ms: 1.05x slower                                                                                                     |
| json_loads                 | 24.2 us                                                                                                               | 25.5 us: 1.05x slower                                                                                                     |
| sympy_str                  | 287 ms                                                                                                                | 303 ms: 1.06x slower                                                                                                      |
| many_optionals             | 590 us                                                                                                                | 624 us: 1.06x slower                                                                                                      |
| async_generators           | 457 ms                                                                                                                | 483 ms: 1.06x slower                                                                                                      |
| pylint                     | 298 ms                                                                                                                | 319 ms: 1.07x slower                                                                                                      |
| mdp                        | 1.34 sec                                                                                                              | 1.44 sec: 1.08x slower                                                                                                    |
| generators                 | 36.7 ms                                                                                                               | 40.7 ms: 1.11x slower                                                                                                     |
| unpack_sequence            | 54.6 ns                                                                                                               | 89.7 ns: 1.64x slower                                                                                                     |
| Geometric mean             | (ref)                                                                                                                 | 1.13x faster                                                                                                              |

Benchmark hidden because not significant (13): async_tree_io, async_tree_memoization_tg, regex_effbot, python_startup_no_site, coverage, 2to3, async_tree_io_tg, asyncio_tcp, sqlglot_v2_optimize, python_startup, unpickle, xml_etree_parse, regex_v8

- Geometric mean (including insignificant results): 1.141x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x

# Memory
- memory change: unknown