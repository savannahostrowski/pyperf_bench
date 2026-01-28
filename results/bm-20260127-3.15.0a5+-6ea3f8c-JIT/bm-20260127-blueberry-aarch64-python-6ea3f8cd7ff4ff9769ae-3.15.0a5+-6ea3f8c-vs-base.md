# Results vs. base

- fork: python
- ref: 6ea3f8cd7ff4ff9769ae
- machine: linux-aarch64
- commit hash: 6ea3f8c
- commit date: 2026-01-27
- overall geometric mean: 1.024x faster
- HPT reliability: 77.09%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| docutils       | 4.19 sec                                                                                                               | 4.61 sec: 1.10x slower                                                                                                     |
| html5lib       | 77.2 ms                                                                                                                | 81.1 ms: 1.05x slower                                                                                                      |
| sphinx         | 1.46 sec                                                                                                               | 1.55 sec: 1.06x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (3): 2to3, chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp      | 1.24 sec                                                                                                               | 1.17 sec: 1.06x faster                                                                                                     |
| coroutines       | 37.6 ms                                                                                                                | 37.9 ms: 1.01x slower                                                                                                      |
| async_generators | 574 ms                                                                                                                 | 611 ms: 1.06x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (10): async_tree_memoization, async_tree_cpu_io_mixed, async_tree_io_tg, async_tree_io, asyncio_websockets, asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_none_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 158 ms                                                                                                                 | 129 ms: 1.23x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 115 ms: 1.13x faster                                                                                                       |
| pidigits       | 328 ms                                                                                                                 | 327 ms: 1.00x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                                                                                 | 137 ms: 1.05x faster                                                                                                       |
| regex_effbot   | 4.42 ms                                                                                                                | 4.34 ms: 1.02x faster                                                                                                      |
| regex_dna      | 280 ms                                                                                                                 | 278 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 319 us                                                                                                                 | 246 us: 1.30x faster                                                                                                       |
| pickle_pure_python   | 452 us                                                                                                                 | 391 us: 1.16x faster                                                                                                       |
| tomli_loads          | 2.85 sec                                                                                                               | 2.57 sec: 1.11x faster                                                                                                     |
| xml_etree_generate   | 131 ms                                                                                                                 | 120 ms: 1.10x faster                                                                                                       |
| xml_etree_process    | 98.9 ms                                                                                                                | 92.2 ms: 1.07x faster                                                                                                      |
| json_dumps           | 13.9 ms                                                                                                                | 13.0 ms: 1.07x faster                                                                                                      |
| xml_etree_parse      | 242 ms                                                                                                                 | 239 ms: 1.01x faster                                                                                                       |
| pickle_list          | 6.81 us                                                                                                                | 6.72 us: 1.01x faster                                                                                                      |
| pickle               | 18.7 us                                                                                                                | 18.6 us: 1.01x faster                                                                                                      |
| pickle_dict          | 47.1 us                                                                                                                | 46.8 us: 1.01x faster                                                                                                      |
| json_loads           | 38.0 us                                                                                                                | 38.2 us: 1.01x slower                                                                                                      |
| unpickle             | 22.2 us                                                                                                                | 22.4 us: 1.01x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.06x faster                                                                                                               |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.4 ms                                                                                                                | 18.0 ms: 1.04x slower                                                                                                      |
| python_startup_no_site | 10.2 ms                                                                                                                | 10.6 ms: 1.05x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.0 ms                                                                                                                | 17.6 ms: 1.14x faster                                                                                                      |
| django_template | 50.1 ms                                                                                                                | 52.4 ms: 1.05x slower                                                                                                      |
| genshi_text     | 32.5 ms                                                                                                                | 34.0 ms: 1.05x slower                                                                                                      |
| genshi_xml      | 74.3 ms                                                                                                                | 89.8 ms: 1.21x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

All benchmarks:
===============

| Benchmark               | results/bm-20260127-3.15.0a5+-6ea3f8c/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json | results/bm-20260127-3.15.0a5+-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5+-6ea3f8c.json |
|-------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                | 64.0 ms                                                                                                                | 37.7 ms: 1.70x faster                                                                                                      |
| richards_super          | 72.6 ms                                                                                                                | 44.6 ms: 1.63x faster                                                                                                      |
| scimark_lu              | 165 ms                                                                                                                 | 120 ms: 1.38x faster                                                                                                       |
| logging_silent          | 158 ns                                                                                                                 | 119 ns: 1.33x faster                                                                                                       |
| scimark_sor             | 169 ms                                                                                                                 | 128 ms: 1.31x faster                                                                                                       |
| unpickle_pure_python    | 319 us                                                                                                                 | 246 us: 1.30x faster                                                                                                       |
| deepcopy_memo           | 40.7 us                                                                                                                | 32.4 us: 1.26x faster                                                                                                      |
| nbody                   | 158 ms                                                                                                                 | 129 ms: 1.23x faster                                                                                                       |
| deltablue               | 4.93 ms                                                                                                                | 4.16 ms: 1.19x faster                                                                                                      |
| pickle_pure_python      | 452 us                                                                                                                 | 391 us: 1.16x faster                                                                                                       |
| spectral_norm           | 150 ms                                                                                                                 | 131 ms: 1.15x faster                                                                                                       |
| scimark_fft             | 477 ms                                                                                                                 | 417 ms: 1.14x faster                                                                                                       |
| mako                    | 20.0 ms                                                                                                                | 17.6 ms: 1.14x faster                                                                                                      |
| float                   | 131 ms                                                                                                                 | 115 ms: 1.13x faster                                                                                                       |
| tomli_loads             | 2.85 sec                                                                                                               | 2.57 sec: 1.11x faster                                                                                                     |
| xml_etree_generate      | 131 ms                                                                                                                 | 120 ms: 1.10x faster                                                                                                       |
| scimark_sparse_mat_mult | 8.44 ms                                                                                                                | 7.72 ms: 1.09x faster                                                                                                      |
| fannkuch                | 580 ms                                                                                                                 | 539 ms: 1.08x faster                                                                                                       |
| xml_etree_process       | 98.9 ms                                                                                                                | 92.2 ms: 1.07x faster                                                                                                      |
| json_dumps              | 13.9 ms                                                                                                                | 13.0 ms: 1.07x faster                                                                                                      |
| bpe_tokeniser           | 6.93 sec                                                                                                               | 6.51 sec: 1.06x faster                                                                                                     |
| asyncio_tcp             | 1.24 sec                                                                                                               | 1.17 sec: 1.06x faster                                                                                                     |
| pyflate                 | 737 ms                                                                                                                 | 703 ms: 1.05x faster                                                                                                       |
| regex_compile           | 144 ms                                                                                                                 | 137 ms: 1.05x faster                                                                                                       |
| scimark_monte_carlo     | 97.9 ms                                                                                                                | 94.3 ms: 1.04x faster                                                                                                      |
| subparsers              | 15.3 ms                                                                                                                | 14.8 ms: 1.04x faster                                                                                                      |
| meteor_contest          | 136 ms                                                                                                                 | 132 ms: 1.03x faster                                                                                                       |
| connected_components    | 846 ms                                                                                                                 | 823 ms: 1.03x faster                                                                                                       |
| pprint_safe_repr        | 1.05 sec                                                                                                               | 1.03 sec: 1.02x faster                                                                                                     |
| deepcopy_reduce         | 3.90 us                                                                                                                | 3.82 us: 1.02x faster                                                                                                      |
| pprint_pformat          | 2.13 sec                                                                                                               | 2.09 sec: 1.02x faster                                                                                                     |
| pathlib                 | 22.7 ms                                                                                                                | 22.2 ms: 1.02x faster                                                                                                      |
| regex_effbot            | 4.42 ms                                                                                                                | 4.34 ms: 1.02x faster                                                                                                      |
| shortest_path           | 892 ms                                                                                                                 | 877 ms: 1.02x faster                                                                                                       |
| json                    | 6.69 ms                                                                                                                | 6.58 ms: 1.02x faster                                                                                                      |
| crypto_pyaes            | 101 ms                                                                                                                 | 99.0 ms: 1.02x faster                                                                                                      |
| xml_etree_parse         | 242 ms                                                                                                                 | 239 ms: 1.01x faster                                                                                                       |
| pickle_list             | 6.81 us                                                                                                                | 6.72 us: 1.01x faster                                                                                                      |
| sqlite_synth            | 4.39 us                                                                                                                | 4.34 us: 1.01x faster                                                                                                      |
| raytrace                | 390 ms                                                                                                                 | 386 ms: 1.01x faster                                                                                                       |
| coverage                | 121 ms                                                                                                                 | 120 ms: 1.01x faster                                                                                                       |
| regex_dna               | 280 ms                                                                                                                 | 278 ms: 1.01x faster                                                                                                       |
| pickle                  | 18.7 us                                                                                                                | 18.6 us: 1.01x faster                                                                                                      |
| pickle_dict             | 47.1 us                                                                                                                | 46.8 us: 1.01x faster                                                                                                      |
| bench_thread_pool       | 1.14 ms                                                                                                                | 1.14 ms: 1.00x faster                                                                                                      |
| pidigits                | 328 ms                                                                                                                 | 327 ms: 1.00x faster                                                                                                       |
| comprehensions          | 24.4 us                                                                                                                | 24.5 us: 1.00x slower                                                                                                      |
| thrift                  | 1.10 ms                                                                                                                | 1.10 ms: 1.00x slower                                                                                                      |
| logging_simple          | 7.87 us                                                                                                                | 7.92 us: 1.01x slower                                                                                                      |
| generators              | 47.4 ms                                                                                                                | 47.6 ms: 1.01x slower                                                                                                      |
| json_loads              | 38.0 us                                                                                                                | 38.2 us: 1.01x slower                                                                                                      |
| unpickle                | 22.2 us                                                                                                                | 22.4 us: 1.01x slower                                                                                                      |
| sqlalchemy_declarative  | 157 ms                                                                                                                 | 159 ms: 1.01x slower                                                                                                       |
| coroutines              | 37.6 ms                                                                                                                | 37.9 ms: 1.01x slower                                                                                                      |
| deepcopy                | 349 us                                                                                                                 | 352 us: 1.01x slower                                                                                                       |
| logging_format          | 8.66 us                                                                                                                | 8.87 us: 1.02x slower                                                                                                      |
| xdsl_constant_fold      | 56.5 ms                                                                                                                | 58.0 ms: 1.03x slower                                                                                                      |
| create_gc_cycles        | 8.87 ms                                                                                                                | 9.13 ms: 1.03x slower                                                                                                      |
| chaos                   | 82.1 ms                                                                                                                | 84.6 ms: 1.03x slower                                                                                                      |
| pycparser               | 1.50 sec                                                                                                               | 1.55 sec: 1.04x slower                                                                                                     |
| python_startup          | 17.4 ms                                                                                                                | 18.0 ms: 1.04x slower                                                                                                      |
| django_template         | 50.1 ms                                                                                                                | 52.4 ms: 1.05x slower                                                                                                      |
| python_startup_no_site  | 10.2 ms                                                                                                                | 10.6 ms: 1.05x slower                                                                                                      |
| go                      | 157 ms                                                                                                                 | 164 ms: 1.05x slower                                                                                                       |
| genshi_text             | 32.5 ms                                                                                                                | 34.0 ms: 1.05x slower                                                                                                      |
| nqueens                 | 121 ms                                                                                                                 | 127 ms: 1.05x slower                                                                                                       |
| html5lib                | 77.2 ms                                                                                                                | 81.1 ms: 1.05x slower                                                                                                      |
| sqlglot_v2_optimize     | 72.3 ms                                                                                                                | 76.0 ms: 1.05x slower                                                                                                      |
| sympy_integrate         | 23.2 ms                                                                                                                | 24.5 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_normalize    | 147 ms                                                                                                                 | 156 ms: 1.06x slower                                                                                                       |
| sphinx                  | 1.46 sec                                                                                                               | 1.55 sec: 1.06x slower                                                                                                     |
| many_optionals          | 940 us                                                                                                                 | 1.00 ms: 1.06x slower                                                                                                      |
| async_generators        | 574 ms                                                                                                                 | 611 ms: 1.06x slower                                                                                                       |
| sqlalchemy_imperative   | 20.3 ms                                                                                                                | 21.7 ms: 1.07x slower                                                                                                      |
| sqlglot_v2_parse        | 1.65 ms                                                                                                                | 1.76 ms: 1.07x slower                                                                                                      |
| hexiom                  | 8.38 ms                                                                                                                | 9.00 ms: 1.07x slower                                                                                                      |
| pylint                  | 414 ms                                                                                                                 | 445 ms: 1.07x slower                                                                                                       |
| dulwich_log             | 62.5 ms                                                                                                                | 67.6 ms: 1.08x slower                                                                                                      |
| mdp                     | 2.48 sec                                                                                                               | 2.69 sec: 1.08x slower                                                                                                     |
| sympy_sum               | 173 ms                                                                                                                 | 189 ms: 1.10x slower                                                                                                       |
| docutils                | 4.19 sec                                                                                                               | 4.61 sec: 1.10x slower                                                                                                     |
| sympy_str               | 326 ms                                                                                                                 | 361 ms: 1.11x slower                                                                                                       |
| sympy_expand            | 562 ms                                                                                                                 | 635 ms: 1.13x slower                                                                                                       |
| unpack_sequence         | 66.0 ns                                                                                                                | 79.7 ns: 1.21x slower                                                                                                      |
| genshi_xml              | 74.3 ms                                                                                                                | 89.8 ms: 1.21x slower                                                                                                      |
| bench_mp_pool           | 123 ms                                                                                                                 | 213 ms: 1.73x slower                                                                                                       |
| Geometric mean          | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (21): async_tree_memoization, async_tree_cpu_io_mixed, sqlglot_v2_transpile, async_tree_io_tg, typing_runtime_protocols, gc_traversal, async_tree_io, tornado_http, k_core, unpickle_list, regex_v8, asyncio_websockets, chameleon, asyncio_tcp_ssl, telco, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, xml_etree_iterparse, 2to3, async_tree_none_tg, async_tree_none

- Geometric mean (including insignificant results): 1.024x faster

# HPT report

- Reliability score: 77.09% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x