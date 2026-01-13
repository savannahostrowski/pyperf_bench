# Results vs. base

- fork: python
- ref: 95259116ecb4346b570b
- machine: linux-aarch64
- commit hash: 9525911
- commit date: 2026-01-09
- overall geometric mean: 1.030x faster
- HPT reliability: 98.10%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 428 ms                                                                                                                 | 434 ms: 1.01x slower                                                                                                       |
| docutils       | 4.31 sec                                                                                                               | 4.80 sec: 1.11x slower                                                                                                     |
| html5lib       | 80.2 ms                                                                                                                | 88.8 ms: 1.11x slower                                                                                                      |
| sphinx         | 1.53 sec                                                                                                               | 1.61 sec: 1.05x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|--------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp        | 1.21 sec                                                                                                               | 1.20 sec: 1.01x faster                                                                                                     |
| asyncio_websockets | 898 ms                                                                                                                 | 890 ms: 1.01x faster                                                                                                       |
| async_generators   | 603 ms                                                                                                                 | 632 ms: 1.05x slower                                                                                                       |
| Geometric mean     | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (10): async_tree_none_tg, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_none, asyncio_tcp_ssl, coroutines, async_tree_cpu_io_mixed, async_tree_memoization_tg, async_tree_memoization, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 166 ms                                                                                                                 | 134 ms: 1.24x faster                                                                                                       |
| float          | 134 ms                                                                                                                 | 114 ms: 1.17x faster                                                                                                       |
| pidigits       | 337 ms                                                                                                                 | 328 ms: 1.03x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.14x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 294 ms                                                                                                                 | 287 ms: 1.02x faster                                                                                                       |
| regex_effbot   | 4.56 ms                                                                                                                | 4.65 ms: 1.02x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (2): regex_v8, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 336 us                                                                                                                 | 259 us: 1.30x faster                                                                                                       |
| pickle_pure_python   | 472 us                                                                                                                 | 386 us: 1.22x faster                                                                                                       |
| tomli_loads          | 3.10 sec                                                                                                               | 2.73 sec: 1.13x faster                                                                                                     |
| xml_etree_generate   | 138 ms                                                                                                                 | 125 ms: 1.10x faster                                                                                                       |
| xml_etree_process    | 105 ms                                                                                                                 | 96.4 ms: 1.09x faster                                                                                                      |
| json_dumps           | 14.8 ms                                                                                                                | 13.7 ms: 1.08x faster                                                                                                      |
| xml_etree_parse      | 256 ms                                                                                                                 | 248 ms: 1.03x faster                                                                                                       |
| pickle_list          | 7.01 us                                                                                                                | 6.80 us: 1.03x faster                                                                                                      |
| xml_etree_iterparse  | 205 ms                                                                                                                 | 199 ms: 1.03x faster                                                                                                       |
| pickle_dict          | 48.8 us                                                                                                                | 47.6 us: 1.02x faster                                                                                                      |
| pickle               | 19.0 us                                                                                                                | 18.6 us: 1.02x faster                                                                                                      |
| unpickle             | 23.5 us                                                                                                                | 23.2 us: 1.01x faster                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.07x faster                                                                                                               |

Benchmark hidden because not significant (2): unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup | 18.2 ms                                                                                                                | 18.1 ms: 1.01x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.5 ms                                                                                                                | 18.1 ms: 1.14x faster                                                                                                      |
| django_template | 52.7 ms                                                                                                                | 53.6 ms: 1.02x slower                                                                                                      |
| genshi_text     | 35.0 ms                                                                                                                | 36.0 ms: 1.03x slower                                                                                                      |
| genshi_xml      | 81.9 ms                                                                                                                | 98.2 ms: 1.20x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

All benchmarks:
===============

| Benchmark               | results/bm-20260109-3.15.0a3+-9525911/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json | results/bm-20260109-3.15.0a3+-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3+-9525911.json |
|-------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                | 66.3 ms                                                                                                                | 38.1 ms: 1.74x faster                                                                                                      |
| richards_super          | 74.9 ms                                                                                                                | 45.3 ms: 1.65x faster                                                                                                      |
| unpickle_pure_python    | 336 us                                                                                                                 | 259 us: 1.30x faster                                                                                                       |
| logging_silent          | 167 ns                                                                                                                 | 130 ns: 1.29x faster                                                                                                       |
| nbody                   | 166 ms                                                                                                                 | 134 ms: 1.24x faster                                                                                                       |
| pickle_pure_python      | 472 us                                                                                                                 | 386 us: 1.22x faster                                                                                                       |
| deepcopy_memo           | 43.7 us                                                                                                                | 36.4 us: 1.20x faster                                                                                                      |
| scimark_monte_carlo     | 103 ms                                                                                                                 | 86.3 ms: 1.20x faster                                                                                                      |
| deltablue               | 5.27 ms                                                                                                                | 4.44 ms: 1.19x faster                                                                                                      |
| pyflate                 | 774 ms                                                                                                                 | 660 ms: 1.17x faster                                                                                                       |
| float                   | 134 ms                                                                                                                 | 114 ms: 1.17x faster                                                                                                       |
| scimark_fft             | 515 ms                                                                                                                 | 441 ms: 1.17x faster                                                                                                       |
| mako                    | 20.5 ms                                                                                                                | 18.1 ms: 1.14x faster                                                                                                      |
| tomli_loads             | 3.10 sec                                                                                                               | 2.73 sec: 1.13x faster                                                                                                     |
| scimark_sor             | 178 ms                                                                                                                 | 158 ms: 1.13x faster                                                                                                       |
| scimark_lu              | 175 ms                                                                                                                 | 155 ms: 1.13x faster                                                                                                       |
| xml_etree_generate      | 138 ms                                                                                                                 | 125 ms: 1.10x faster                                                                                                       |
| spectral_norm           | 160 ms                                                                                                                 | 146 ms: 1.10x faster                                                                                                       |
| xml_etree_process       | 105 ms                                                                                                                 | 96.4 ms: 1.09x faster                                                                                                      |
| json_dumps              | 14.8 ms                                                                                                                | 13.7 ms: 1.08x faster                                                                                                      |
| fannkuch                | 619 ms                                                                                                                 | 572 ms: 1.08x faster                                                                                                       |
| go                      | 167 ms                                                                                                                 | 156 ms: 1.07x faster                                                                                                       |
| meteor_contest          | 144 ms                                                                                                                 | 135 ms: 1.07x faster                                                                                                       |
| pprint_pformat          | 2.31 sec                                                                                                               | 2.17 sec: 1.06x faster                                                                                                     |
| crypto_pyaes            | 110 ms                                                                                                                 | 103 ms: 1.06x faster                                                                                                       |
| sqlite_synth            | 4.74 us                                                                                                                | 4.49 us: 1.06x faster                                                                                                      |
| bpe_tokeniser           | 7.45 sec                                                                                                               | 7.05 sec: 1.06x faster                                                                                                     |
| sqlglot_v2_parse        | 1.78 ms                                                                                                                | 1.68 ms: 1.06x faster                                                                                                      |
| deepcopy_reduce         | 4.21 us                                                                                                                | 4.02 us: 1.05x faster                                                                                                      |
| pprint_safe_repr        | 1.11 sec                                                                                                               | 1.06 sec: 1.05x faster                                                                                                     |
| coverage                | 133 ms                                                                                                                 | 128 ms: 1.04x faster                                                                                                       |
| scimark_sparse_mat_mult | 8.48 ms                                                                                                                | 8.19 ms: 1.04x faster                                                                                                      |
| xml_etree_parse         | 256 ms                                                                                                                 | 248 ms: 1.03x faster                                                                                                       |
| raytrace                | 418 ms                                                                                                                 | 405 ms: 1.03x faster                                                                                                       |
| pickle_list             | 7.01 us                                                                                                                | 6.80 us: 1.03x faster                                                                                                      |
| bench_thread_pool       | 1.31 ms                                                                                                                | 1.27 ms: 1.03x faster                                                                                                      |
| generators              | 51.2 ms                                                                                                                | 49.8 ms: 1.03x faster                                                                                                      |
| pidigits                | 337 ms                                                                                                                 | 328 ms: 1.03x faster                                                                                                       |
| xml_etree_iterparse     | 205 ms                                                                                                                 | 199 ms: 1.03x faster                                                                                                       |
| logging_format          | 9.46 us                                                                                                                | 9.21 us: 1.03x faster                                                                                                      |
| pickle_dict             | 48.8 us                                                                                                                | 47.6 us: 1.02x faster                                                                                                      |
| regex_dna               | 294 ms                                                                                                                 | 287 ms: 1.02x faster                                                                                                       |
| pickle                  | 19.0 us                                                                                                                | 18.6 us: 1.02x faster                                                                                                      |
| connected_components    | 848 ms                                                                                                                 | 832 ms: 1.02x faster                                                                                                       |
| json                    | 6.94 ms                                                                                                                | 6.83 ms: 1.02x faster                                                                                                      |
| shortest_path           | 898 ms                                                                                                                 | 885 ms: 1.01x faster                                                                                                       |
| logging_simple          | 8.53 us                                                                                                                | 8.41 us: 1.01x faster                                                                                                      |
| pathlib                 | 22.5 ms                                                                                                                | 22.2 ms: 1.01x faster                                                                                                      |
| k_core                  | 4.08 sec                                                                                                               | 4.03 sec: 1.01x faster                                                                                                     |
| unpickle                | 23.5 us                                                                                                                | 23.2 us: 1.01x faster                                                                                                      |
| asyncio_tcp             | 1.21 sec                                                                                                               | 1.20 sec: 1.01x faster                                                                                                     |
| asyncio_websockets      | 898 ms                                                                                                                 | 890 ms: 1.01x faster                                                                                                       |
| python_startup          | 18.2 ms                                                                                                                | 18.1 ms: 1.01x faster                                                                                                      |
| telco                   | 201 ms                                                                                                                 | 202 ms: 1.01x slower                                                                                                       |
| 2to3                    | 428 ms                                                                                                                 | 434 ms: 1.01x slower                                                                                                       |
| thrift                  | 1.17 ms                                                                                                                | 1.19 ms: 1.01x slower                                                                                                      |
| django_template         | 52.7 ms                                                                                                                | 53.6 ms: 1.02x slower                                                                                                      |
| regex_effbot            | 4.56 ms                                                                                                                | 4.65 ms: 1.02x slower                                                                                                      |
| sqlglot_v2_normalize    | 161 ms                                                                                                                 | 164 ms: 1.02x slower                                                                                                       |
| genshi_text             | 35.0 ms                                                                                                                | 36.0 ms: 1.03x slower                                                                                                      |
| xdsl_constant_fold      | 58.2 ms                                                                                                                | 59.9 ms: 1.03x slower                                                                                                      |
| pycparser               | 1.57 sec                                                                                                               | 1.62 sec: 1.04x slower                                                                                                     |
| sympy_integrate         | 24.6 ms                                                                                                                | 25.5 ms: 1.04x slower                                                                                                      |
| sqlalchemy_imperative   | 21.8 ms                                                                                                                | 22.7 ms: 1.04x slower                                                                                                      |
| async_generators        | 603 ms                                                                                                                 | 632 ms: 1.05x slower                                                                                                       |
| sqlglot_v2_optimize     | 76.0 ms                                                                                                                | 79.8 ms: 1.05x slower                                                                                                      |
| sphinx                  | 1.53 sec                                                                                                               | 1.61 sec: 1.05x slower                                                                                                     |
| pylint                  | 426 ms                                                                                                                 | 449 ms: 1.05x slower                                                                                                       |
| hexiom                  | 8.94 ms                                                                                                                | 9.48 ms: 1.06x slower                                                                                                      |
| many_optionals          | 928 us                                                                                                                 | 1.00 ms: 1.08x slower                                                                                                      |
| sympy_sum               | 180 ms                                                                                                                 | 196 ms: 1.09x slower                                                                                                       |
| mdp                     | 2.50 sec                                                                                                               | 2.75 sec: 1.10x slower                                                                                                     |
| html5lib                | 80.2 ms                                                                                                                | 88.8 ms: 1.11x slower                                                                                                      |
| sympy_str               | 342 ms                                                                                                                 | 380 ms: 1.11x slower                                                                                                       |
| docutils                | 4.31 sec                                                                                                               | 4.80 sec: 1.11x slower                                                                                                     |
| dulwich_log             | 66.0 ms                                                                                                                | 73.5 ms: 1.11x slower                                                                                                      |
| nqueens                 | 119 ms                                                                                                                 | 133 ms: 1.12x slower                                                                                                       |
| sympy_expand            | 604 ms                                                                                                                 | 676 ms: 1.12x slower                                                                                                       |
| unpack_sequence         | 68.6 ns                                                                                                                | 82.2 ns: 1.20x slower                                                                                                      |
| genshi_xml              | 81.9 ms                                                                                                                | 98.2 ms: 1.20x slower                                                                                                      |
| Geometric mean          | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (27): sqlglot_v2_transpile, async_tree_none_tg, async_tree_io, async_tree_cpu_io_mixed_tg, typing_runtime_protocols, chameleon, gc_traversal, subparsers, async_tree_none, regex_v8, python_startup_no_site, tornado_http, asyncio_tcp_ssl, unpickle_list, json_loads, coroutines, sqlalchemy_declarative, async_tree_cpu_io_mixed, regex_compile, async_tree_memoization_tg, comprehensions, deepcopy, async_tree_memoization, create_gc_cycles, async_tree_io_tg, chaos, bench_mp_pool

- Geometric mean (including insignificant results): 1.030x faster

# HPT report

- Reliability score: 98.10% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x