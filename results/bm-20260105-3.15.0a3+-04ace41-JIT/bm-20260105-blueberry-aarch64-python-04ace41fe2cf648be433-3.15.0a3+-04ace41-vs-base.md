# Results vs. base

- fork: python
- ref: 04ace41fe2cf648be433
- machine: linux-aarch64
- commit hash: 04ace41
- commit date: 2026-01-05
- overall geometric mean: 1.016x faster
- HPT reliability: 57.25%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 21.5 ms                                                                                                                | 20.7 ms: 1.04x faster                                                                                                      |
| docutils       | 4.31 sec                                                                                                               | 4.72 sec: 1.10x slower                                                                                                     |
| html5lib       | 78.6 ms                                                                                                                | 88.7 ms: 1.13x slower                                                                                                      |
| sphinx         | 1.51 sec                                                                                                               | 1.65 sec: 1.10x slower                                                                                                     |
| tornado_http   | 170 ms                                                                                                                 | 174 ms: 1.02x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|--------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg | 559 ms                                                                                                                 | 537 ms: 1.04x faster                                                                                                       |
| coroutines         | 41.2 ms                                                                                                                | 40.1 ms: 1.03x faster                                                                                                      |
| asyncio_tcp_ssl    | 4.46 sec                                                                                                               | 4.43 sec: 1.01x faster                                                                                                     |
| asyncio_tcp        | 1.24 sec                                                                                                               | 1.26 sec: 1.01x slower                                                                                                     |
| async_generators   | 604 ms                                                                                                                 | 613 ms: 1.01x slower                                                                                                       |
| Geometric mean     | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (8): async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_memoization, asyncio_websockets, async_tree_memoization_tg, async_tree_none, async_tree_io_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 162 ms                                                                                                                 | 135 ms: 1.20x faster                                                                                                       |
| float          | 132 ms                                                                                                                 | 114 ms: 1.16x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.64 ms                                                                                                                | 4.49 ms: 1.03x faster                                                                                                      |
| regex_v8       | 37.1 ms                                                                                                                | 36.6 ms: 1.02x faster                                                                                                      |
| regex_dna      | 285 ms                                                                                                                 | 288 ms: 1.01x slower                                                                                                       |
| regex_compile  | 150 ms                                                                                                                 | 153 ms: 1.02x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 330 us                                                                                                                 | 260 us: 1.27x faster                                                                                                       |
| pickle_pure_python   | 459 us                                                                                                                 | 385 us: 1.19x faster                                                                                                       |
| json_dumps           | 14.7 ms                                                                                                                | 13.5 ms: 1.09x faster                                                                                                      |
| tomli_loads          | 3.00 sec                                                                                                               | 2.76 sec: 1.09x faster                                                                                                     |
| xml_etree_generate   | 133 ms                                                                                                                 | 128 ms: 1.04x faster                                                                                                       |
| xml_etree_process    | 103 ms                                                                                                                 | 99.2 ms: 1.04x faster                                                                                                      |
| json_loads           | 39.4 us                                                                                                                | 38.4 us: 1.03x faster                                                                                                      |
| pickle_list          | 6.89 us                                                                                                                | 6.82 us: 1.01x faster                                                                                                      |
| unpickle             | 23.1 us                                                                                                                | 23.4 us: 1.01x slower                                                                                                      |
| unpickle_list        | 8.41 us                                                                                                                | 8.55 us: 1.02x slower                                                                                                      |
| pickle               | 18.4 us                                                                                                                | 18.9 us: 1.03x slower                                                                                                      |
| xml_etree_parse      | 249 ms                                                                                                                 | 257 ms: 1.03x slower                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.4 ms                                                                                                                | 10.7 ms: 1.03x slower                                                                                                      |
| python_startup         | 17.6 ms                                                                                                                | 18.1 ms: 1.03x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 20.6 ms                                                                                                                | 18.0 ms: 1.14x faster                                                                                                      |
| genshi_text    | 34.6 ms                                                                                                                | 35.4 ms: 1.02x slower                                                                                                      |
| genshi_xml     | 77.7 ms                                                                                                                | 95.8 ms: 1.23x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                | results/bm-20260105-3.15.0a3+-04ace41/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json | results/bm-20260105-3.15.0a3+-04ace41-JIT/bm-20260105-blueberry-aarch64-python-04ace41fe2cf648be433-3.15.0a3+-04ace41.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 64.5 ms                                                                                                                | 38.0 ms: 1.70x faster                                                                                                      |
| richards_super           | 73.2 ms                                                                                                                | 46.0 ms: 1.59x faster                                                                                                      |
| logging_silent           | 166 ns                                                                                                                 | 120 ns: 1.38x faster                                                                                                       |
| unpickle_pure_python     | 330 us                                                                                                                 | 260 us: 1.27x faster                                                                                                       |
| nbody                    | 162 ms                                                                                                                 | 135 ms: 1.20x faster                                                                                                       |
| deltablue                | 5.21 ms                                                                                                                | 4.34 ms: 1.20x faster                                                                                                      |
| pickle_pure_python       | 459 us                                                                                                                 | 385 us: 1.19x faster                                                                                                       |
| scimark_monte_carlo      | 100 ms                                                                                                                 | 86.5 ms: 1.16x faster                                                                                                      |
| pyflate                  | 765 ms                                                                                                                 | 658 ms: 1.16x faster                                                                                                       |
| deepcopy_memo            | 42.4 us                                                                                                                | 36.5 us: 1.16x faster                                                                                                      |
| float                    | 132 ms                                                                                                                 | 114 ms: 1.16x faster                                                                                                       |
| mako                     | 20.6 ms                                                                                                                | 18.0 ms: 1.14x faster                                                                                                      |
| scimark_sor              | 175 ms                                                                                                                 | 157 ms: 1.12x faster                                                                                                       |
| scimark_fft              | 497 ms                                                                                                                 | 445 ms: 1.12x faster                                                                                                       |
| scimark_lu               | 172 ms                                                                                                                 | 156 ms: 1.11x faster                                                                                                       |
| fannkuch                 | 607 ms                                                                                                                 | 554 ms: 1.10x faster                                                                                                       |
| go                       | 165 ms                                                                                                                 | 151 ms: 1.09x faster                                                                                                       |
| json_dumps               | 14.7 ms                                                                                                                | 13.5 ms: 1.09x faster                                                                                                      |
| tomli_loads              | 3.00 sec                                                                                                               | 2.76 sec: 1.09x faster                                                                                                     |
| spectral_norm            | 156 ms                                                                                                                 | 145 ms: 1.07x faster                                                                                                       |
| bpe_tokeniser            | 7.41 sec                                                                                                               | 6.96 sec: 1.07x faster                                                                                                     |
| json                     | 7.04 ms                                                                                                                | 6.71 ms: 1.05x faster                                                                                                      |
| xml_etree_generate       | 133 ms                                                                                                                 | 128 ms: 1.04x faster                                                                                                       |
| async_tree_none_tg       | 559 ms                                                                                                                 | 537 ms: 1.04x faster                                                                                                       |
| chameleon                | 21.5 ms                                                                                                                | 20.7 ms: 1.04x faster                                                                                                      |
| xml_etree_process        | 103 ms                                                                                                                 | 99.2 ms: 1.04x faster                                                                                                      |
| regex_effbot             | 4.64 ms                                                                                                                | 4.49 ms: 1.03x faster                                                                                                      |
| pathlib                  | 22.5 ms                                                                                                                | 21.8 ms: 1.03x faster                                                                                                      |
| connected_components     | 851 ms                                                                                                                 | 827 ms: 1.03x faster                                                                                                       |
| sqlite_synth             | 4.67 us                                                                                                                | 4.53 us: 1.03x faster                                                                                                      |
| logging_format           | 9.20 us                                                                                                                | 8.93 us: 1.03x faster                                                                                                      |
| coroutines               | 41.2 ms                                                                                                                | 40.1 ms: 1.03x faster                                                                                                      |
| json_loads               | 39.4 us                                                                                                                | 38.4 us: 1.03x faster                                                                                                      |
| meteor_contest           | 141 ms                                                                                                                 | 137 ms: 1.03x faster                                                                                                       |
| shortest_path            | 895 ms                                                                                                                 | 875 ms: 1.02x faster                                                                                                       |
| regex_v8                 | 37.1 ms                                                                                                                | 36.6 ms: 1.02x faster                                                                                                      |
| raytrace                 | 406 ms                                                                                                                 | 400 ms: 1.01x faster                                                                                                       |
| scimark_sparse_mat_mult  | 8.25 ms                                                                                                                | 8.15 ms: 1.01x faster                                                                                                      |
| logging_simple           | 8.27 us                                                                                                                | 8.17 us: 1.01x faster                                                                                                      |
| comprehensions           | 25.7 us                                                                                                                | 25.4 us: 1.01x faster                                                                                                      |
| gc_traversal             | 14.7 ms                                                                                                                | 14.5 ms: 1.01x faster                                                                                                      |
| pickle_list              | 6.89 us                                                                                                                | 6.82 us: 1.01x faster                                                                                                      |
| k_core                   | 4.07 sec                                                                                                               | 4.05 sec: 1.01x faster                                                                                                     |
| asyncio_tcp_ssl          | 4.46 sec                                                                                                               | 4.43 sec: 1.01x faster                                                                                                     |
| pprint_safe_repr         | 1.07 sec                                                                                                               | 1.06 sec: 1.01x faster                                                                                                     |
| regex_dna                | 285 ms                                                                                                                 | 288 ms: 1.01x slower                                                                                                       |
| asyncio_tcp              | 1.24 sec                                                                                                               | 1.26 sec: 1.01x slower                                                                                                     |
| unpickle                 | 23.1 us                                                                                                                | 23.4 us: 1.01x slower                                                                                                      |
| async_generators         | 604 ms                                                                                                                 | 613 ms: 1.01x slower                                                                                                       |
| unpickle_list            | 8.41 us                                                                                                                | 8.55 us: 1.02x slower                                                                                                      |
| regex_compile            | 150 ms                                                                                                                 | 153 ms: 1.02x slower                                                                                                       |
| genshi_text              | 34.6 ms                                                                                                                | 35.4 ms: 1.02x slower                                                                                                      |
| tornado_http             | 170 ms                                                                                                                 | 174 ms: 1.02x slower                                                                                                       |
| python_startup_no_site   | 10.4 ms                                                                                                                | 10.7 ms: 1.03x slower                                                                                                      |
| pickle                   | 18.4 us                                                                                                                | 18.9 us: 1.03x slower                                                                                                      |
| python_startup           | 17.6 ms                                                                                                                | 18.1 ms: 1.03x slower                                                                                                      |
| xml_etree_parse          | 249 ms                                                                                                                 | 257 ms: 1.03x slower                                                                                                       |
| create_gc_cycles         | 8.81 ms                                                                                                                | 9.13 ms: 1.04x slower                                                                                                      |
| sqlalchemy_declarative   | 160 ms                                                                                                                 | 166 ms: 1.04x slower                                                                                                       |
| thrift                   | 1.16 ms                                                                                                                | 1.21 ms: 1.05x slower                                                                                                      |
| hexiom                   | 8.90 ms                                                                                                                | 9.30 ms: 1.05x slower                                                                                                      |
| deepcopy                 | 387 us                                                                                                                 | 407 us: 1.05x slower                                                                                                       |
| typing_runtime_protocols | 236 us                                                                                                                 | 249 us: 1.05x slower                                                                                                       |
| mdp                      | 2.56 sec                                                                                                               | 2.75 sec: 1.07x slower                                                                                                     |
| pycparser                | 1.52 sec                                                                                                               | 1.63 sec: 1.07x slower                                                                                                     |
| sqlglot_v2_optimize      | 75.3 ms                                                                                                                | 81.0 ms: 1.08x slower                                                                                                      |
| pylint                   | 419 ms                                                                                                                 | 451 ms: 1.08x slower                                                                                                       |
| sqlalchemy_imperative    | 21.2 ms                                                                                                                | 22.9 ms: 1.08x slower                                                                                                      |
| many_optionals           | 935 us                                                                                                                 | 1.01 ms: 1.08x slower                                                                                                      |
| sympy_integrate          | 23.8 ms                                                                                                                | 25.7 ms: 1.08x slower                                                                                                      |
| xdsl_constant_fold       | 56.8 ms                                                                                                                | 61.8 ms: 1.09x slower                                                                                                      |
| sqlglot_v2_normalize     | 155 ms                                                                                                                 | 168 ms: 1.09x slower                                                                                                       |
| docutils                 | 4.31 sec                                                                                                               | 4.72 sec: 1.10x slower                                                                                                     |
| sphinx                   | 1.51 sec                                                                                                               | 1.65 sec: 1.10x slower                                                                                                     |
| sympy_sum                | 177 ms                                                                                                                 | 198 ms: 1.12x slower                                                                                                       |
| html5lib                 | 78.6 ms                                                                                                                | 88.7 ms: 1.13x slower                                                                                                      |
| sympy_str                | 336 ms                                                                                                                 | 383 ms: 1.14x slower                                                                                                       |
| sympy_expand             | 581 ms                                                                                                                 | 673 ms: 1.16x slower                                                                                                       |
| nqueens                  | 119 ms                                                                                                                 | 138 ms: 1.16x slower                                                                                                       |
| dulwich_log              | 63.5 ms                                                                                                                | 76.2 ms: 1.20x slower                                                                                                      |
| genshi_xml               | 77.7 ms                                                                                                                | 95.8 ms: 1.23x slower                                                                                                      |
| unpack_sequence          | 67.7 ns                                                                                                                | 83.8 ns: 1.24x slower                                                                                                      |
| bench_mp_pool            | 154 ms                                                                                                                 | 270 ms: 1.75x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (24): bench_thread_pool, async_tree_cpu_io_mixed, coverage, async_tree_cpu_io_mixed_tg, generators, crypto_pyaes, async_tree_memoization, xml_etree_iterparse, 2to3, chaos, subparsers, sqlglot_v2_parse, asyncio_websockets, pickle_dict, deepcopy_reduce, pidigits, async_tree_memoization_tg, pprint_pformat, telco, sqlglot_v2_transpile, django_template, async_tree_none, async_tree_io_tg, async_tree_io

- Geometric mean (including insignificant results): 1.016x faster

# HPT report

- Reliability score: 57.25% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x