# Results vs. base

- fork: python
- ref: cb1dc91dcb1eb6637d1c
- machine: linux-aarch64
- commit hash: cb1dc91
- commit date: 2026-02-03
- overall geometric mean: 1.025x faster
- HPT reliability: 96.09%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 424 ms                                                                                                                 | 429 ms: 1.01x slower                                                                                                       |
| chameleon      | 20.3 ms                                                                                                                | 19.8 ms: 1.02x faster                                                                                                      |
| docutils       | 4.22 sec                                                                                                               | 4.59 sec: 1.09x slower                                                                                                     |
| html5lib       | 77.0 ms                                                                                                                | 81.0 ms: 1.05x slower                                                                                                      |
| sphinx         | 1.47 sec                                                                                                               | 1.54 sec: 1.04x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_io_tg          | 1.25 sec                                                                                                               | 1.19 sec: 1.04x faster                                                                                                     |
| async_tree_none_tg        | 546 ms                                                                                                                 | 526 ms: 1.04x faster                                                                                                       |
| async_tree_io             | 1.27 sec                                                                                                               | 1.24 sec: 1.03x faster                                                                                                     |
| async_tree_memoization_tg | 660 ms                                                                                                                 | 645 ms: 1.02x faster                                                                                                       |
| coroutines                | 36.8 ms                                                                                                                | 37.1 ms: 1.01x slower                                                                                                      |
| asyncio_tcp               | 1.17 sec                                                                                                               | 1.19 sec: 1.01x slower                                                                                                     |
| async_generators          | 576 ms                                                                                                                 | 606 ms: 1.05x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (6): async_tree_none, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_cpu_io_mixed_tg, asyncio_tcp_ssl, asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 159 ms                                                                                                                 | 130 ms: 1.23x faster                                                                                                       |
| float          | 132 ms                                                                                                                 | 115 ms: 1.14x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 142 ms                                                                                                                 | 136 ms: 1.05x faster                                                                                                       |
| regex_dna      | 285 ms                                                                                                                 | 278 ms: 1.03x faster                                                                                                       |
| regex_effbot   | 4.46 ms                                                                                                                | 4.37 ms: 1.02x faster                                                                                                      |
| regex_v8       | 35.8 ms                                                                                                                | 35.6 ms: 1.01x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 319 us                                                                                                                 | 244 us: 1.31x faster                                                                                                       |
| pickle_pure_python   | 450 us                                                                                                                 | 394 us: 1.14x faster                                                                                                       |
| xml_etree_process    | 98.5 ms                                                                                                                | 90.3 ms: 1.09x faster                                                                                                      |
| tomli_loads          | 2.79 sec                                                                                                               | 2.59 sec: 1.08x faster                                                                                                     |
| xml_etree_generate   | 128 ms                                                                                                                 | 119 ms: 1.08x faster                                                                                                       |
| json_dumps           | 13.9 ms                                                                                                                | 13.1 ms: 1.06x faster                                                                                                      |
| xml_etree_parse      | 243 ms                                                                                                                 | 240 ms: 1.01x faster                                                                                                       |
| pickle_list          | 6.86 us                                                                                                                | 6.78 us: 1.01x faster                                                                                                      |
| xml_etree_iterparse  | 199 ms                                                                                                                 | 197 ms: 1.01x faster                                                                                                       |
| pickle_dict          | 47.0 us                                                                                                                | 46.8 us: 1.00x faster                                                                                                      |
| unpickle_list        | 8.02 us                                                                                                                | 8.07 us: 1.01x slower                                                                                                      |
| unpickle             | 22.3 us                                                                                                                | 22.5 us: 1.01x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.05x faster                                                                                                               |

Benchmark hidden because not significant (2): pickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.4 ms                                                                                                                | 18.0 ms: 1.03x slower                                                                                                      |
| python_startup_no_site | 10.2 ms                                                                                                                | 10.6 ms: 1.04x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.9 ms                                                                                                                | 17.5 ms: 1.14x faster                                                                                                      |
| django_template | 49.7 ms                                                                                                                | 51.4 ms: 1.03x slower                                                                                                      |
| genshi_text     | 32.2 ms                                                                                                                | 34.4 ms: 1.07x slower                                                                                                      |
| genshi_xml      | 73.6 ms                                                                                                                | 91.0 ms: 1.24x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20260203-3.15.0a5+-cb1dc91/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json | results/bm-20260203-3.15.0a5+-cb1dc91-JIT/bm-20260203-blueberry-aarch64-python-cb1dc91dcb1eb6637d1c-3.15.0a5+-cb1dc91.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 63.6 ms                                                                                                                | 37.7 ms: 1.69x faster                                                                                                      |
| richards_super            | 72.2 ms                                                                                                                | 44.2 ms: 1.63x faster                                                                                                      |
| scimark_lu                | 165 ms                                                                                                                 | 119 ms: 1.39x faster                                                                                                       |
| logging_silent            | 158 ns                                                                                                                 | 119 ns: 1.33x faster                                                                                                       |
| unpickle_pure_python      | 319 us                                                                                                                 | 244 us: 1.31x faster                                                                                                       |
| scimark_sor               | 167 ms                                                                                                                 | 128 ms: 1.30x faster                                                                                                       |
| deepcopy_memo             | 40.2 us                                                                                                                | 32.2 us: 1.25x faster                                                                                                      |
| nbody                     | 159 ms                                                                                                                 | 130 ms: 1.23x faster                                                                                                       |
| deltablue                 | 4.86 ms                                                                                                                | 4.13 ms: 1.18x faster                                                                                                      |
| scimark_fft               | 476 ms                                                                                                                 | 414 ms: 1.15x faster                                                                                                       |
| pickle_pure_python        | 450 us                                                                                                                 | 394 us: 1.14x faster                                                                                                       |
| float                     | 132 ms                                                                                                                 | 115 ms: 1.14x faster                                                                                                       |
| mako                      | 19.9 ms                                                                                                                | 17.5 ms: 1.14x faster                                                                                                      |
| spectral_norm             | 150 ms                                                                                                                 | 136 ms: 1.10x faster                                                                                                       |
| xml_etree_process         | 98.5 ms                                                                                                                | 90.3 ms: 1.09x faster                                                                                                      |
| fannkuch                  | 574 ms                                                                                                                 | 526 ms: 1.09x faster                                                                                                       |
| bpe_tokeniser             | 6.95 sec                                                                                                               | 6.44 sec: 1.08x faster                                                                                                     |
| tomli_loads               | 2.79 sec                                                                                                               | 2.59 sec: 1.08x faster                                                                                                     |
| xml_etree_generate        | 128 ms                                                                                                                 | 119 ms: 1.08x faster                                                                                                       |
| scimark_sparse_mat_mult   | 8.10 ms                                                                                                                | 7.58 ms: 1.07x faster                                                                                                      |
| gc_traversal              | 14.3 ms                                                                                                                | 13.4 ms: 1.07x faster                                                                                                      |
| json_dumps                | 13.9 ms                                                                                                                | 13.1 ms: 1.06x faster                                                                                                      |
| regex_compile             | 142 ms                                                                                                                 | 136 ms: 1.05x faster                                                                                                       |
| async_tree_io_tg          | 1.25 sec                                                                                                               | 1.19 sec: 1.04x faster                                                                                                     |
| scimark_monte_carlo       | 98.2 ms                                                                                                                | 94.7 ms: 1.04x faster                                                                                                      |
| async_tree_none_tg        | 546 ms                                                                                                                 | 526 ms: 1.04x faster                                                                                                       |
| pyflate                   | 726 ms                                                                                                                 | 701 ms: 1.04x faster                                                                                                       |
| pprint_safe_repr          | 1.04 sec                                                                                                               | 1.00 sec: 1.03x faster                                                                                                     |
| deepcopy_reduce           | 3.94 us                                                                                                                | 3.82 us: 1.03x faster                                                                                                      |
| thrift                    | 1.11 ms                                                                                                                | 1.08 ms: 1.03x faster                                                                                                      |
| pprint_pformat            | 2.12 sec                                                                                                               | 2.06 sec: 1.03x faster                                                                                                     |
| sqlite_synth              | 4.50 us                                                                                                                | 4.37 us: 1.03x faster                                                                                                      |
| async_tree_io             | 1.27 sec                                                                                                               | 1.24 sec: 1.03x faster                                                                                                     |
| regex_dna                 | 285 ms                                                                                                                 | 278 ms: 1.03x faster                                                                                                       |
| json                      | 6.68 ms                                                                                                                | 6.52 ms: 1.03x faster                                                                                                      |
| async_tree_memoization_tg | 660 ms                                                                                                                 | 645 ms: 1.02x faster                                                                                                       |
| chameleon                 | 20.3 ms                                                                                                                | 19.8 ms: 1.02x faster                                                                                                      |
| regex_effbot              | 4.46 ms                                                                                                                | 4.37 ms: 1.02x faster                                                                                                      |
| xml_etree_parse           | 243 ms                                                                                                                 | 240 ms: 1.01x faster                                                                                                       |
| raytrace                  | 389 ms                                                                                                                 | 384 ms: 1.01x faster                                                                                                       |
| pathlib                   | 22.0 ms                                                                                                                | 21.8 ms: 1.01x faster                                                                                                      |
| pickle_list               | 6.86 us                                                                                                                | 6.78 us: 1.01x faster                                                                                                      |
| bench_thread_pool         | 1.15 ms                                                                                                                | 1.14 ms: 1.01x faster                                                                                                      |
| crypto_pyaes              | 99.2 ms                                                                                                                | 98.1 ms: 1.01x faster                                                                                                      |
| xml_etree_iterparse       | 199 ms                                                                                                                 | 197 ms: 1.01x faster                                                                                                       |
| regex_v8                  | 35.8 ms                                                                                                                | 35.6 ms: 1.01x faster                                                                                                      |
| meteor_contest            | 135 ms                                                                                                                 | 134 ms: 1.01x faster                                                                                                       |
| connected_components      | 844 ms                                                                                                                 | 840 ms: 1.00x faster                                                                                                       |
| pickle_dict               | 47.0 us                                                                                                                | 46.8 us: 1.00x faster                                                                                                      |
| k_core                    | 4.10 sec                                                                                                               | 4.08 sec: 1.00x faster                                                                                                     |
| shortest_path             | 893 ms                                                                                                                 | 891 ms: 1.00x faster                                                                                                       |
| unpickle_list             | 8.02 us                                                                                                                | 8.07 us: 1.01x slower                                                                                                      |
| unpickle                  | 22.3 us                                                                                                                | 22.5 us: 1.01x slower                                                                                                      |
| coroutines                | 36.8 ms                                                                                                                | 37.1 ms: 1.01x slower                                                                                                      |
| logging_simple            | 7.85 us                                                                                                                | 7.93 us: 1.01x slower                                                                                                      |
| 2to3                      | 424 ms                                                                                                                 | 429 ms: 1.01x slower                                                                                                       |
| deepcopy                  | 344 us                                                                                                                 | 349 us: 1.01x slower                                                                                                       |
| asyncio_tcp               | 1.17 sec                                                                                                               | 1.19 sec: 1.01x slower                                                                                                     |
| sqlalchemy_declarative    | 157 ms                                                                                                                 | 159 ms: 1.01x slower                                                                                                       |
| logging_format            | 8.61 us                                                                                                                | 8.74 us: 1.01x slower                                                                                                      |
| chaos                     | 81.6 ms                                                                                                                | 82.9 ms: 1.02x slower                                                                                                      |
| comprehensions            | 24.3 us                                                                                                                | 24.8 us: 1.02x slower                                                                                                      |
| python_startup            | 17.4 ms                                                                                                                | 18.0 ms: 1.03x slower                                                                                                      |
| django_template           | 49.7 ms                                                                                                                | 51.4 ms: 1.03x slower                                                                                                      |
| xdsl_constant_fold        | 55.7 ms                                                                                                                | 57.6 ms: 1.03x slower                                                                                                      |
| python_startup_no_site    | 10.2 ms                                                                                                                | 10.6 ms: 1.04x slower                                                                                                      |
| sqlglot_v2_normalize      | 148 ms                                                                                                                 | 154 ms: 1.04x slower                                                                                                       |
| sqlglot_v2_optimize       | 72.4 ms                                                                                                                | 75.5 ms: 1.04x slower                                                                                                      |
| sphinx                    | 1.47 sec                                                                                                               | 1.54 sec: 1.04x slower                                                                                                     |
| go                        | 155 ms                                                                                                                 | 162 ms: 1.05x slower                                                                                                       |
| create_gc_cycles          | 8.71 ms                                                                                                                | 9.12 ms: 1.05x slower                                                                                                      |
| async_generators          | 576 ms                                                                                                                 | 606 ms: 1.05x slower                                                                                                       |
| html5lib                  | 77.0 ms                                                                                                                | 81.0 ms: 1.05x slower                                                                                                      |
| sympy_integrate           | 23.3 ms                                                                                                                | 24.6 ms: 1.06x slower                                                                                                      |
| nqueens                   | 118 ms                                                                                                                 | 125 ms: 1.06x slower                                                                                                       |
| sqlalchemy_imperative     | 20.4 ms                                                                                                                | 21.6 ms: 1.06x slower                                                                                                      |
| dulwich_log               | 61.8 ms                                                                                                                | 65.4 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_parse          | 1.64 ms                                                                                                                | 1.75 ms: 1.06x slower                                                                                                      |
| pylint                    | 415 ms                                                                                                                 | 442 ms: 1.07x slower                                                                                                       |
| pycparser                 | 1.49 sec                                                                                                               | 1.59 sec: 1.07x slower                                                                                                     |
| genshi_text               | 32.2 ms                                                                                                                | 34.4 ms: 1.07x slower                                                                                                      |
| many_optionals            | 934 us                                                                                                                 | 1.00 ms: 1.07x slower                                                                                                      |
| hexiom                    | 8.31 ms                                                                                                                | 8.96 ms: 1.08x slower                                                                                                      |
| docutils                  | 4.22 sec                                                                                                               | 4.59 sec: 1.09x slower                                                                                                     |
| sympy_sum                 | 173 ms                                                                                                                 | 190 ms: 1.10x slower                                                                                                       |
| mdp                       | 2.44 sec                                                                                                               | 2.69 sec: 1.10x slower                                                                                                     |
| sympy_str                 | 322 ms                                                                                                                 | 362 ms: 1.12x slower                                                                                                       |
| sympy_expand              | 556 ms                                                                                                                 | 626 ms: 1.13x slower                                                                                                       |
| unpack_sequence           | 68.0 ns                                                                                                                | 80.1 ns: 1.18x slower                                                                                                      |
| genshi_xml                | 73.6 ms                                                                                                                | 91.0 ms: 1.24x slower                                                                                                      |
| bench_mp_pool             | 156 ms                                                                                                                 | 203 ms: 1.30x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (16): sqlglot_v2_transpile, async_tree_none, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_cpu_io_mixed_tg, asyncio_tcp_ssl, pickle, json_loads, subparsers, telco, pidigits, asyncio_websockets, coverage, generators, typing_runtime_protocols, tornado_http

- Geometric mean (including insignificant results): 1.025x faster

# HPT report

- Reliability score: 96.09% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x