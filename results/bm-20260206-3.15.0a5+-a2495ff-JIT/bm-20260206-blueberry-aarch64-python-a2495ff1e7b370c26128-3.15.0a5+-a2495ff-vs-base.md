# Results vs. base

- fork: python
- ref: a2495ff1e7b370c26128
- machine: linux-aarch64
- commit hash: a2495ff
- commit date: 2026-02-06
- overall geometric mean: 1.012x faster
- HPT reliability: 73.52%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.04x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 423 ms                                                                                                                 | 419 ms: 1.01x faster                                                                                                       |
| chameleon      | 20.0 ms                                                                                                                | 19.9 ms: 1.01x faster                                                                                                      |
| docutils       | 4.14 sec                                                                                                               | 4.67 sec: 1.13x slower                                                                                                     |
| html5lib       | 77.2 ms                                                                                                                | 83.2 ms: 1.08x slower                                                                                                      |
| sphinx         | 1.47 sec                                                                                                               | 1.57 sec: 1.07x slower                                                                                                     |
| tornado_http   | 161 ms                                                                                                                 | 166 ms: 1.03x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none  | 544 ms                                                                                                                 | 526 ms: 1.03x faster                                                                                                       |
| async_tree_io    | 1.34 sec                                                                                                               | 1.32 sec: 1.01x faster                                                                                                     |
| coroutines       | 36.8 ms                                                                                                                | 37.2 ms: 1.01x slower                                                                                                      |
| asyncio_tcp      | 1.17 sec                                                                                                               | 1.21 sec: 1.03x slower                                                                                                     |
| async_generators | 577 ms                                                                                                                 | 599 ms: 1.04x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (8): async_tree_none_tg, async_tree_memoization, async_tree_io_tg, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, asyncio_tcp_ssl, asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 160 ms                                                                                                                 | 127 ms: 1.26x faster                                                                                                       |
| float          | 132 ms                                                                                                                 | 118 ms: 1.12x faster                                                                                                       |
| pidigits       | 325 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 35.7 ms                                                                                                                | 35.9 ms: 1.00x slower                                                                                                      |
| regex_dna      | 274 ms                                                                                                                 | 278 ms: 1.01x slower                                                                                                       |
| regex_effbot   | 4.39 ms                                                                                                                | 4.44 ms: 1.01x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 320 us                                                                                                                 | 278 us: 1.15x faster                                                                                                       |
| tomli_loads          | 2.83 sec                                                                                                               | 2.58 sec: 1.10x faster                                                                                                     |
| json_dumps           | 14.0 ms                                                                                                                | 12.9 ms: 1.09x faster                                                                                                      |
| xml_etree_generate   | 129 ms                                                                                                                 | 120 ms: 1.08x faster                                                                                                       |
| xml_etree_process    | 97.4 ms                                                                                                                | 91.2 ms: 1.07x faster                                                                                                      |
| pickle_list          | 6.89 us                                                                                                                | 6.76 us: 1.02x faster                                                                                                      |
| xml_etree_iterparse  | 200 ms                                                                                                                 | 196 ms: 1.02x faster                                                                                                       |
| pickle               | 18.8 us                                                                                                                | 18.9 us: 1.00x slower                                                                                                      |
| unpickle_list        | 8.01 us                                                                                                                | 8.08 us: 1.01x slower                                                                                                      |
| xml_etree_parse      | 242 ms                                                                                                                 | 245 ms: 1.01x slower                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (4): json_loads, pickle_pure_python, pickle_dict, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.3 ms                                                                                                                | 17.4 ms: 1.01x slower                                                                                                      |
| python_startup_no_site | 10.1 ms                                                                                                                | 10.3 ms: 1.02x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.7 ms                                                                                                                | 17.3 ms: 1.14x faster                                                                                                      |
| django_template | 50.4 ms                                                                                                                | 50.8 ms: 1.01x slower                                                                                                      |
| genshi_text     | 32.4 ms                                                                                                                | 34.7 ms: 1.07x slower                                                                                                      |
| genshi_xml      | 75.4 ms                                                                                                                | 90.3 ms: 1.20x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20260206-3.15.0a5+-a2495ff/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json | results/bm-20260206-3.15.0a5+-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5+-a2495ff.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 62.5 ms                                                                                                                | 38.7 ms: 1.62x faster                                                                                                      |
| richards_super           | 70.7 ms                                                                                                                | 46.0 ms: 1.54x faster                                                                                                      |
| scimark_lu               | 165 ms                                                                                                                 | 122 ms: 1.36x faster                                                                                                       |
| scimark_sor              | 168 ms                                                                                                                 | 131 ms: 1.28x faster                                                                                                       |
| logging_silent           | 158 ns                                                                                                                 | 123 ns: 1.28x faster                                                                                                       |
| nbody                    | 160 ms                                                                                                                 | 127 ms: 1.26x faster                                                                                                       |
| deepcopy_memo            | 39.6 us                                                                                                                | 32.5 us: 1.22x faster                                                                                                      |
| scimark_fft              | 478 ms                                                                                                                 | 414 ms: 1.15x faster                                                                                                       |
| unpickle_pure_python     | 320 us                                                                                                                 | 278 us: 1.15x faster                                                                                                       |
| spectral_norm            | 151 ms                                                                                                                 | 132 ms: 1.14x faster                                                                                                       |
| mako                     | 19.7 ms                                                                                                                | 17.3 ms: 1.14x faster                                                                                                      |
| deltablue                | 4.87 ms                                                                                                                | 4.28 ms: 1.14x faster                                                                                                      |
| float                    | 132 ms                                                                                                                 | 118 ms: 1.12x faster                                                                                                       |
| tomli_loads              | 2.83 sec                                                                                                               | 2.58 sec: 1.10x faster                                                                                                     |
| json_dumps               | 14.0 ms                                                                                                                | 12.9 ms: 1.09x faster                                                                                                      |
| fannkuch                 | 578 ms                                                                                                                 | 534 ms: 1.08x faster                                                                                                       |
| xml_etree_generate       | 129 ms                                                                                                                 | 120 ms: 1.08x faster                                                                                                       |
| xml_etree_process        | 97.4 ms                                                                                                                | 91.2 ms: 1.07x faster                                                                                                      |
| sqlite_synth             | 4.38 us                                                                                                                | 4.11 us: 1.07x faster                                                                                                      |
| scimark_sparse_mat_mult  | 7.99 ms                                                                                                                | 7.56 ms: 1.06x faster                                                                                                      |
| bpe_tokeniser            | 6.82 sec                                                                                                               | 6.47 sec: 1.05x faster                                                                                                     |
| json                     | 6.77 ms                                                                                                                | 6.47 ms: 1.05x faster                                                                                                      |
| scimark_monte_carlo      | 97.3 ms                                                                                                                | 93.3 ms: 1.04x faster                                                                                                      |
| async_tree_none          | 544 ms                                                                                                                 | 526 ms: 1.03x faster                                                                                                       |
| meteor_contest           | 136 ms                                                                                                                 | 132 ms: 1.03x faster                                                                                                       |
| gc_traversal             | 13.4 ms                                                                                                                | 13.1 ms: 1.03x faster                                                                                                      |
| create_gc_cycles         | 9.14 ms                                                                                                                | 8.92 ms: 1.03x faster                                                                                                      |
| connected_components     | 846 ms                                                                                                                 | 827 ms: 1.02x faster                                                                                                       |
| pickle_list              | 6.89 us                                                                                                                | 6.76 us: 1.02x faster                                                                                                      |
| deepcopy_reduce          | 3.81 us                                                                                                                | 3.74 us: 1.02x faster                                                                                                      |
| xml_etree_iterparse      | 200 ms                                                                                                                 | 196 ms: 1.02x faster                                                                                                       |
| pyflate                  | 724 ms                                                                                                                 | 712 ms: 1.02x faster                                                                                                       |
| k_core                   | 4.11 sec                                                                                                               | 4.05 sec: 1.01x faster                                                                                                     |
| async_tree_io            | 1.34 sec                                                                                                               | 1.32 sec: 1.01x faster                                                                                                     |
| pprint_pformat           | 2.12 sec                                                                                                               | 2.09 sec: 1.01x faster                                                                                                     |
| shortest_path            | 892 ms                                                                                                                 | 881 ms: 1.01x faster                                                                                                       |
| subparsers               | 14.9 ms                                                                                                                | 14.8 ms: 1.01x faster                                                                                                      |
| 2to3                     | 423 ms                                                                                                                 | 419 ms: 1.01x faster                                                                                                       |
| bench_thread_pool        | 1.16 ms                                                                                                                | 1.15 ms: 1.01x faster                                                                                                      |
| crypto_pyaes             | 99.2 ms                                                                                                                | 98.4 ms: 1.01x faster                                                                                                      |
| chameleon                | 20.0 ms                                                                                                                | 19.9 ms: 1.01x faster                                                                                                      |
| pprint_safe_repr         | 1.04 sec                                                                                                               | 1.03 sec: 1.01x faster                                                                                                     |
| regex_v8                 | 35.7 ms                                                                                                                | 35.9 ms: 1.00x slower                                                                                                      |
| pickle                   | 18.8 us                                                                                                                | 18.9 us: 1.00x slower                                                                                                      |
| python_startup           | 17.3 ms                                                                                                                | 17.4 ms: 1.01x slower                                                                                                      |
| logging_format           | 8.69 us                                                                                                                | 8.75 us: 1.01x slower                                                                                                      |
| django_template          | 50.4 ms                                                                                                                | 50.8 ms: 1.01x slower                                                                                                      |
| pidigits                 | 325 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| unpickle_list            | 8.01 us                                                                                                                | 8.08 us: 1.01x slower                                                                                                      |
| regex_dna                | 274 ms                                                                                                                 | 278 ms: 1.01x slower                                                                                                       |
| coroutines               | 36.8 ms                                                                                                                | 37.2 ms: 1.01x slower                                                                                                      |
| typing_runtime_protocols | 226 us                                                                                                                 | 228 us: 1.01x slower                                                                                                       |
| xml_etree_parse          | 242 ms                                                                                                                 | 245 ms: 1.01x slower                                                                                                       |
| regex_effbot             | 4.39 ms                                                                                                                | 4.44 ms: 1.01x slower                                                                                                      |
| python_startup_no_site   | 10.1 ms                                                                                                                | 10.3 ms: 1.02x slower                                                                                                      |
| comprehensions           | 24.3 us                                                                                                                | 24.7 us: 1.02x slower                                                                                                      |
| sqlalchemy_declarative   | 156 ms                                                                                                                 | 160 ms: 1.02x slower                                                                                                       |
| telco                    | 186 ms                                                                                                                 | 190 ms: 1.03x slower                                                                                                       |
| tornado_http             | 161 ms                                                                                                                 | 166 ms: 1.03x slower                                                                                                       |
| generators               | 46.9 ms                                                                                                                | 48.3 ms: 1.03x slower                                                                                                      |
| pathlib                  | 21.2 ms                                                                                                                | 21.8 ms: 1.03x slower                                                                                                      |
| asyncio_tcp              | 1.17 sec                                                                                                               | 1.21 sec: 1.03x slower                                                                                                     |
| xdsl_constant_fold       | 56.1 ms                                                                                                                | 58.3 ms: 1.04x slower                                                                                                      |
| async_generators         | 577 ms                                                                                                                 | 599 ms: 1.04x slower                                                                                                       |
| chaos                    | 81.3 ms                                                                                                                | 84.9 ms: 1.04x slower                                                                                                      |
| sqlalchemy_imperative    | 20.4 ms                                                                                                                | 21.4 ms: 1.05x slower                                                                                                      |
| sqlglot_v2_normalize     | 148 ms                                                                                                                 | 156 ms: 1.06x slower                                                                                                       |
| sqlglot_v2_optimize      | 72.0 ms                                                                                                                | 76.6 ms: 1.06x slower                                                                                                      |
| sphinx                   | 1.47 sec                                                                                                               | 1.57 sec: 1.07x slower                                                                                                     |
| many_optionals           | 935 us                                                                                                                 | 1000 us: 1.07x slower                                                                                                      |
| sympy_integrate          | 23.2 ms                                                                                                                | 24.8 ms: 1.07x slower                                                                                                      |
| genshi_text              | 32.4 ms                                                                                                                | 34.7 ms: 1.07x slower                                                                                                      |
| sqlglot_v2_parse         | 1.63 ms                                                                                                                | 1.75 ms: 1.07x slower                                                                                                      |
| deepcopy                 | 338 us                                                                                                                 | 363 us: 1.07x slower                                                                                                       |
| pylint                   | 413 ms                                                                                                                 | 445 ms: 1.08x slower                                                                                                       |
| html5lib                 | 77.2 ms                                                                                                                | 83.2 ms: 1.08x slower                                                                                                      |
| go                       | 154 ms                                                                                                                 | 167 ms: 1.08x slower                                                                                                       |
| dulwich_log              | 61.4 ms                                                                                                                | 66.6 ms: 1.09x slower                                                                                                      |
| hexiom                   | 8.31 ms                                                                                                                | 9.02 ms: 1.09x slower                                                                                                      |
| thrift                   | 1.08 ms                                                                                                                | 1.19 ms: 1.10x slower                                                                                                      |
| nqueens                  | 118 ms                                                                                                                 | 129 ms: 1.10x slower                                                                                                       |
| mdp                      | 2.43 sec                                                                                                               | 2.67 sec: 1.10x slower                                                                                                     |
| pycparser                | 1.47 sec                                                                                                               | 1.62 sec: 1.10x slower                                                                                                     |
| raytrace                 | 384 ms                                                                                                                 | 427 ms: 1.11x slower                                                                                                       |
| sympy_sum                | 171 ms                                                                                                                 | 190 ms: 1.11x slower                                                                                                       |
| docutils                 | 4.14 sec                                                                                                               | 4.67 sec: 1.13x slower                                                                                                     |
| sympy_str                | 321 ms                                                                                                                 | 364 ms: 1.14x slower                                                                                                       |
| sympy_expand             | 556 ms                                                                                                                 | 638 ms: 1.15x slower                                                                                                       |
| genshi_xml               | 75.4 ms                                                                                                                | 90.3 ms: 1.20x slower                                                                                                      |
| unpack_sequence          | 63.9 ns                                                                                                                | 78.7 ns: 1.23x slower                                                                                                      |
| Geometric mean           | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (17): async_tree_none_tg, sqlglot_v2_transpile, async_tree_memoization, async_tree_io_tg, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, json_loads, pickle_pure_python, asyncio_tcp_ssl, logging_simple, asyncio_websockets, coverage, pickle_dict, unpickle, regex_compile, bench_mp_pool

- Geometric mean (including insignificant results): 1.012x faster

# HPT report

- Reliability score: 73.52% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.04x