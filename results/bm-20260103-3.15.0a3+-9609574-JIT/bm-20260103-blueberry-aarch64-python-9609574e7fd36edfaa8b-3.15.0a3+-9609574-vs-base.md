# Results vs. base

- fork: python
- ref: 9609574e7fd36edfaa8b
- machine: linux-aarch64
- commit hash: 9609574
- commit date: 2026-01-03
- overall geometric mean: 1.022x faster
- HPT reliability: 74.23%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 441 ms                                                                                                                 | 456 ms: 1.03x slower                                                                                                       |
| docutils       | 4.57 sec                                                                                                               | 5.08 sec: 1.11x slower                                                                                                     |
| html5lib       | 84.6 ms                                                                                                                | 94.8 ms: 1.12x slower                                                                                                      |
| sphinx         | 1.65 sec                                                                                                               | 1.73 sec: 1.05x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl  | 4.59 sec                                                                                                               | 4.65 sec: 1.01x slower                                                                                                     |
| async_tree_io_tg | 1.28 sec                                                                                                               | 1.31 sec: 1.02x slower                                                                                                     |
| async_tree_io    | 1.26 sec                                                                                                               | 1.30 sec: 1.03x slower                                                                                                     |
| async_generators | 617 ms                                                                                                                 | 673 ms: 1.09x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (9): coroutines, async_tree_none_tg, asyncio_tcp, asyncio_websockets, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 178 ms                                                                                                                 | 149 ms: 1.19x faster                                                                                                       |
| float          | 137 ms                                                                                                                 | 119 ms: 1.15x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.11x faster                                                                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 318 ms                                                                                                                 | 305 ms: 1.04x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (3): regex_v8, regex_effbot, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 368 us                                                                                                                 | 284 us: 1.30x faster                                                                                                       |
| pickle_pure_python   | 511 us                                                                                                                 | 428 us: 1.19x faster                                                                                                       |
| xml_etree_process    | 113 ms                                                                                                                 | 103 ms: 1.09x faster                                                                                                       |
| xml_etree_generate   | 149 ms                                                                                                                 | 137 ms: 1.09x faster                                                                                                       |
| tomli_loads          | 3.69 sec                                                                                                               | 3.40 sec: 1.09x faster                                                                                                     |
| pickle               | 21.4 us                                                                                                                | 20.3 us: 1.05x faster                                                                                                      |
| pickle_dict          | 54.9 us                                                                                                                | 52.7 us: 1.04x faster                                                                                                      |
| xml_etree_iterparse  | 215 ms                                                                                                                 | 211 ms: 1.02x faster                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.06x faster                                                                                                               |

Benchmark hidden because not significant (6): json_dumps, pickle_list, json_loads, unpickle, xml_etree_parse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 11.2 ms                                                                                                                | 11.4 ms: 1.02x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 21.8 ms                                                                                                                | 19.3 ms: 1.13x faster                                                                                                      |
| genshi_text    | 36.2 ms                                                                                                                | 41.1 ms: 1.13x slower                                                                                                      |
| genshi_xml     | 85.7 ms                                                                                                                | 108 ms: 1.26x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark               | results/bm-20260103-3.15.0a3+-9609574/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json | results/bm-20260103-3.15.0a3+-9609574-JIT/bm-20260103-blueberry-aarch64-python-9609574e7fd36edfaa8b-3.15.0a3+-9609574.json |
|-------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                | 73.2 ms                                                                                                                | 40.3 ms: 1.82x faster                                                                                                      |
| richards_super          | 81.8 ms                                                                                                                | 48.3 ms: 1.69x faster                                                                                                      |
| unpickle_pure_python    | 368 us                                                                                                                 | 284 us: 1.30x faster                                                                                                       |
| logging_silent          | 180 ns                                                                                                                 | 141 ns: 1.27x faster                                                                                                       |
| scimark_monte_carlo     | 113 ms                                                                                                                 | 92.8 ms: 1.22x faster                                                                                                      |
| pickle_pure_python      | 511 us                                                                                                                 | 428 us: 1.19x faster                                                                                                       |
| nbody                   | 178 ms                                                                                                                 | 149 ms: 1.19x faster                                                                                                       |
| scimark_lu              | 194 ms                                                                                                                 | 166 ms: 1.17x faster                                                                                                       |
| deltablue               | 5.61 ms                                                                                                                | 4.80 ms: 1.17x faster                                                                                                      |
| float                   | 137 ms                                                                                                                 | 119 ms: 1.15x faster                                                                                                       |
| scimark_fft             | 545 ms                                                                                                                 | 478 ms: 1.14x faster                                                                                                       |
| pyflate                 | 811 ms                                                                                                                 | 714 ms: 1.14x faster                                                                                                       |
| mako                    | 21.8 ms                                                                                                                | 19.3 ms: 1.13x faster                                                                                                      |
| deepcopy_memo           | 45.1 us                                                                                                                | 40.0 us: 1.13x faster                                                                                                      |
| scimark_sor             | 195 ms                                                                                                                 | 176 ms: 1.11x faster                                                                                                       |
| sqlite_synth            | 5.27 us                                                                                                                | 4.80 us: 1.10x faster                                                                                                      |
| fannkuch                | 661 ms                                                                                                                 | 605 ms: 1.09x faster                                                                                                       |
| xml_etree_process       | 113 ms                                                                                                                 | 103 ms: 1.09x faster                                                                                                       |
| xml_etree_generate      | 149 ms                                                                                                                 | 137 ms: 1.09x faster                                                                                                       |
| tomli_loads             | 3.69 sec                                                                                                               | 3.40 sec: 1.09x faster                                                                                                     |
| spectral_norm           | 174 ms                                                                                                                 | 160 ms: 1.08x faster                                                                                                       |
| go                      | 179 ms                                                                                                                 | 169 ms: 1.06x faster                                                                                                       |
| meteor_contest          | 156 ms                                                                                                                 | 147 ms: 1.06x faster                                                                                                       |
| pickle                  | 21.4 us                                                                                                                | 20.3 us: 1.05x faster                                                                                                      |
| bpe_tokeniser           | 7.90 sec                                                                                                               | 7.53 sec: 1.05x faster                                                                                                     |
| scimark_sparse_mat_mult | 9.14 ms                                                                                                                | 8.76 ms: 1.04x faster                                                                                                      |
| regex_dna               | 318 ms                                                                                                                 | 305 ms: 1.04x faster                                                                                                       |
| pickle_dict             | 54.9 us                                                                                                                | 52.7 us: 1.04x faster                                                                                                      |
| sqlglot_v2_parse        | 1.90 ms                                                                                                                | 1.83 ms: 1.04x faster                                                                                                      |
| telco                   | 223 ms                                                                                                                 | 216 ms: 1.03x faster                                                                                                       |
| logging_simple          | 9.10 us                                                                                                                | 8.86 us: 1.03x faster                                                                                                      |
| connected_components    | 868 ms                                                                                                                 | 847 ms: 1.02x faster                                                                                                       |
| raytrace                | 456 ms                                                                                                                 | 445 ms: 1.02x faster                                                                                                       |
| k_core                  | 4.15 sec                                                                                                               | 4.06 sec: 1.02x faster                                                                                                     |
| xml_etree_iterparse     | 215 ms                                                                                                                 | 211 ms: 1.02x faster                                                                                                       |
| shortest_path           | 916 ms                                                                                                                 | 902 ms: 1.02x faster                                                                                                       |
| asyncio_tcp_ssl         | 4.59 sec                                                                                                               | 4.65 sec: 1.01x slower                                                                                                     |
| create_gc_cycles        | 9.17 ms                                                                                                                | 9.31 ms: 1.02x slower                                                                                                      |
| python_startup_no_site  | 11.2 ms                                                                                                                | 11.4 ms: 1.02x slower                                                                                                      |
| async_tree_io_tg        | 1.28 sec                                                                                                               | 1.31 sec: 1.02x slower                                                                                                     |
| async_tree_io           | 1.26 sec                                                                                                               | 1.30 sec: 1.03x slower                                                                                                     |
| pycparser               | 1.68 sec                                                                                                               | 1.73 sec: 1.03x slower                                                                                                     |
| json                    | 7.29 ms                                                                                                                | 7.53 ms: 1.03x slower                                                                                                      |
| 2to3                    | 441 ms                                                                                                                 | 456 ms: 1.03x slower                                                                                                       |
| thrift                  | 1.26 ms                                                                                                                | 1.31 ms: 1.04x slower                                                                                                      |
| xdsl_constant_fold      | 63.6 ms                                                                                                                | 66.1 ms: 1.04x slower                                                                                                      |
| sphinx                  | 1.65 sec                                                                                                               | 1.73 sec: 1.05x slower                                                                                                     |
| coverage                | 137 ms                                                                                                                 | 144 ms: 1.05x slower                                                                                                       |
| sympy_integrate         | 26.0 ms                                                                                                                | 27.3 ms: 1.05x slower                                                                                                      |
| sqlglot_v2_normalize    | 172 ms                                                                                                                 | 181 ms: 1.05x slower                                                                                                       |
| sqlglot_v2_optimize     | 81.7 ms                                                                                                                | 86.1 ms: 1.05x slower                                                                                                      |
| pylint                  | 458 ms                                                                                                                 | 486 ms: 1.06x slower                                                                                                       |
| hexiom                  | 9.66 ms                                                                                                                | 10.3 ms: 1.06x slower                                                                                                      |
| many_optionals          | 960 us                                                                                                                 | 1.04 ms: 1.08x slower                                                                                                      |
| sympy_sum               | 197 ms                                                                                                                 | 214 ms: 1.09x slower                                                                                                       |
| nqueens                 | 134 ms                                                                                                                 | 146 ms: 1.09x slower                                                                                                       |
| async_generators        | 617 ms                                                                                                                 | 673 ms: 1.09x slower                                                                                                       |
| deepcopy                | 421 us                                                                                                                 | 461 us: 1.10x slower                                                                                                       |
| sympy_str               | 375 ms                                                                                                                 | 411 ms: 1.10x slower                                                                                                       |
| mdp                     | 2.61 sec                                                                                                               | 2.89 sec: 1.11x slower                                                                                                     |
| docutils                | 4.57 sec                                                                                                               | 5.08 sec: 1.11x slower                                                                                                     |
| html5lib                | 84.6 ms                                                                                                                | 94.8 ms: 1.12x slower                                                                                                      |
| unpack_sequence         | 76.6 ns                                                                                                                | 86.3 ns: 1.13x slower                                                                                                      |
| sympy_expand            | 636 ms                                                                                                                 | 721 ms: 1.13x slower                                                                                                       |
| genshi_text             | 36.2 ms                                                                                                                | 41.1 ms: 1.13x slower                                                                                                      |
| dulwich_log             | 71.1 ms                                                                                                                | 86.4 ms: 1.22x slower                                                                                                      |
| genshi_xml              | 85.7 ms                                                                                                                | 108 ms: 1.26x slower                                                                                                       |
| Geometric mean          | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (40): sqlglot_v2_transpile, json_dumps, coroutines, pickle_list, crypto_pyaes, sqlalchemy_declarative, async_tree_none_tg, pathlib, json_loads, regex_v8, django_template, bench_thread_pool, asyncio_tcp, tornado_http, chameleon, generators, unpickle, pprint_safe_repr, logging_format, gc_traversal, regex_effbot, deepcopy_reduce, pprint_pformat, regex_compile, asyncio_websockets, xml_etree_parse, python_startup, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_memoization_tg, pidigits, async_tree_cpu_io_mixed_tg, comprehensions, chaos, unpickle_list, subparsers, async_tree_none, typing_runtime_protocols, sqlalchemy_imperative, bench_mp_pool

- Geometric mean (including insignificant results): 1.022x faster

# HPT report

- Reliability score: 74.23% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x