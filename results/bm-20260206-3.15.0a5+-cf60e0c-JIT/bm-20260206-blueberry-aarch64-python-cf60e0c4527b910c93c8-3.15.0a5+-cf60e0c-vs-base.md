# Results vs. base

- fork: python
- ref: cf60e0c4527b910c93c8
- machine: linux-aarch64
- commit hash: cf60e0c
- commit date: 2026-02-06
- overall geometric mean: 1.008x faster
- HPT reliability: 63.03%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.04x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 425 ms                                                                                                                 | 421 ms: 1.01x faster                                                                                                       |
| docutils       | 4.18 sec                                                                                                               | 4.64 sec: 1.11x slower                                                                                                     |
| html5lib       | 77.0 ms                                                                                                                | 83.2 ms: 1.08x slower                                                                                                      |
| sphinx         | 1.48 sec                                                                                                               | 1.56 sec: 1.05x slower                                                                                                     |
| tornado_http   | 162 ms                                                                                                                 | 164 ms: 1.02x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines       | 36.8 ms                                                                                                                | 37.2 ms: 1.01x slower                                                                                                      |
| async_tree_io    | 1.32 sec                                                                                                               | 1.33 sec: 1.01x slower                                                                                                     |
| async_generators | 577 ms                                                                                                                 | 606 ms: 1.05x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (10): async_tree_memoization, async_tree_memoization_tg, async_tree_none_tg, async_tree_cpu_io_mixed, asyncio_tcp, async_tree_cpu_io_mixed_tg, asyncio_websockets, async_tree_io_tg, asyncio_tcp_ssl, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 159 ms                                                                                                                 | 129 ms: 1.23x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 118 ms: 1.11x faster                                                                                                       |
| pidigits       | 328 ms                                                                                                                 | 324 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.11x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.44 ms                                                                                                                | 4.35 ms: 1.02x faster                                                                                                      |
| regex_dna      | 280 ms                                                                                                                 | 276 ms: 1.02x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (2): regex_compile, regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 317 us                                                                                                                 | 281 us: 1.13x faster                                                                                                       |
| tomli_loads          | 2.85 sec                                                                                                               | 2.58 sec: 1.11x faster                                                                                                     |
| xml_etree_process    | 98.1 ms                                                                                                                | 92.2 ms: 1.06x faster                                                                                                      |
| json_dumps           | 14.0 ms                                                                                                                | 13.1 ms: 1.06x faster                                                                                                      |
| xml_etree_generate   | 128 ms                                                                                                                 | 121 ms: 1.06x faster                                                                                                       |
| pickle               | 18.8 us                                                                                                                | 18.3 us: 1.03x faster                                                                                                      |
| pickle_list          | 6.80 us                                                                                                                | 6.74 us: 1.01x faster                                                                                                      |
| pickle_dict          | 47.0 us                                                                                                                | 46.7 us: 1.00x faster                                                                                                      |
| json_loads           | 37.9 us                                                                                                                | 38.2 us: 1.01x slower                                                                                                      |
| unpickle             | 22.1 us                                                                                                                | 22.5 us: 1.02x slower                                                                                                      |
| xml_etree_parse      | 242 ms                                                                                                                 | 247 ms: 1.02x slower                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (3): unpickle_list, xml_etree_iterparse, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.4 ms                                                                                                                | 10.3 ms: 1.01x faster                                                                                                      |
| python_startup         | 17.7 ms                                                                                                                | 17.6 ms: 1.01x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.9 ms                                                                                                                | 17.7 ms: 1.12x faster                                                                                                      |
| django_template | 50.3 ms                                                                                                                | 52.1 ms: 1.04x slower                                                                                                      |
| genshi_text     | 31.9 ms                                                                                                                | 34.8 ms: 1.09x slower                                                                                                      |
| genshi_xml      | 72.9 ms                                                                                                                | 91.0 ms: 1.25x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

All benchmarks:
===============

| Benchmark               | results/bm-20260206-3.15.0a5+-cf60e0c/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json | results/bm-20260206-3.15.0a5+-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5+-cf60e0c.json |
|-------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                | 62.1 ms                                                                                                                | 38.8 ms: 1.60x faster                                                                                                      |
| richards_super          | 70.1 ms                                                                                                                | 45.2 ms: 1.55x faster                                                                                                      |
| scimark_lu              | 166 ms                                                                                                                 | 122 ms: 1.36x faster                                                                                                       |
| scimark_sor             | 168 ms                                                                                                                 | 131 ms: 1.28x faster                                                                                                       |
| logging_silent          | 157 ns                                                                                                                 | 123 ns: 1.28x faster                                                                                                       |
| nbody                   | 159 ms                                                                                                                 | 129 ms: 1.23x faster                                                                                                       |
| deepcopy_memo           | 39.6 us                                                                                                                | 32.8 us: 1.21x faster                                                                                                      |
| scimark_fft             | 480 ms                                                                                                                 | 418 ms: 1.15x faster                                                                                                       |
| spectral_norm           | 152 ms                                                                                                                 | 132 ms: 1.14x faster                                                                                                       |
| deltablue               | 4.85 ms                                                                                                                | 4.29 ms: 1.13x faster                                                                                                      |
| unpickle_pure_python    | 317 us                                                                                                                 | 281 us: 1.13x faster                                                                                                       |
| mako                    | 19.9 ms                                                                                                                | 17.7 ms: 1.12x faster                                                                                                      |
| float                   | 131 ms                                                                                                                 | 118 ms: 1.11x faster                                                                                                       |
| tomli_loads             | 2.85 sec                                                                                                               | 2.58 sec: 1.11x faster                                                                                                     |
| xml_etree_process       | 98.1 ms                                                                                                                | 92.2 ms: 1.06x faster                                                                                                      |
| json_dumps              | 14.0 ms                                                                                                                | 13.1 ms: 1.06x faster                                                                                                      |
| pyflate                 | 741 ms                                                                                                                 | 698 ms: 1.06x faster                                                                                                       |
| xml_etree_generate      | 128 ms                                                                                                                 | 121 ms: 1.06x faster                                                                                                       |
| bpe_tokeniser           | 6.81 sec                                                                                                               | 6.46 sec: 1.05x faster                                                                                                     |
| fannkuch                | 574 ms                                                                                                                 | 549 ms: 1.05x faster                                                                                                       |
| json                    | 6.76 ms                                                                                                                | 6.57 ms: 1.03x faster                                                                                                      |
| scimark_sparse_mat_mult | 7.88 ms                                                                                                                | 7.65 ms: 1.03x faster                                                                                                      |
| pickle                  | 18.8 us                                                                                                                | 18.3 us: 1.03x faster                                                                                                      |
| connected_components    | 849 ms                                                                                                                 | 826 ms: 1.03x faster                                                                                                       |
| coverage                | 123 ms                                                                                                                 | 120 ms: 1.02x faster                                                                                                       |
| regex_effbot            | 4.44 ms                                                                                                                | 4.35 ms: 1.02x faster                                                                                                      |
| regex_dna               | 280 ms                                                                                                                 | 276 ms: 1.02x faster                                                                                                       |
| shortest_path           | 894 ms                                                                                                                 | 880 ms: 1.02x faster                                                                                                       |
| pathlib                 | 22.0 ms                                                                                                                | 21.7 ms: 1.01x faster                                                                                                      |
| sqlite_synth            | 4.31 us                                                                                                                | 4.25 us: 1.01x faster                                                                                                      |
| scimark_monte_carlo     | 96.5 ms                                                                                                                | 95.2 ms: 1.01x faster                                                                                                      |
| python_startup_no_site  | 10.4 ms                                                                                                                | 10.3 ms: 1.01x faster                                                                                                      |
| 2to3                    | 425 ms                                                                                                                 | 421 ms: 1.01x faster                                                                                                       |
| pidigits                | 328 ms                                                                                                                 | 324 ms: 1.01x faster                                                                                                       |
| pickle_list             | 6.80 us                                                                                                                | 6.74 us: 1.01x faster                                                                                                      |
| python_startup          | 17.7 ms                                                                                                                | 17.6 ms: 1.01x faster                                                                                                      |
| crypto_pyaes            | 98.8 ms                                                                                                                | 98.1 ms: 1.01x faster                                                                                                      |
| telco                   | 187 ms                                                                                                                 | 186 ms: 1.01x faster                                                                                                       |
| bench_thread_pool       | 1.15 ms                                                                                                                | 1.14 ms: 1.01x faster                                                                                                      |
| pickle_dict             | 47.0 us                                                                                                                | 46.7 us: 1.00x faster                                                                                                      |
| sqlalchemy_declarative  | 157 ms                                                                                                                 | 157 ms: 1.00x slower                                                                                                       |
| deepcopy_reduce         | 3.84 us                                                                                                                | 3.86 us: 1.01x slower                                                                                                      |
| pprint_pformat          | 2.07 sec                                                                                                               | 2.09 sec: 1.01x slower                                                                                                     |
| json_loads              | 37.9 us                                                                                                                | 38.2 us: 1.01x slower                                                                                                      |
| coroutines              | 36.8 ms                                                                                                                | 37.2 ms: 1.01x slower                                                                                                      |
| async_tree_io           | 1.32 sec                                                                                                               | 1.33 sec: 1.01x slower                                                                                                     |
| pprint_safe_repr        | 1.02 sec                                                                                                               | 1.03 sec: 1.01x slower                                                                                                     |
| tornado_http            | 162 ms                                                                                                                 | 164 ms: 1.02x slower                                                                                                       |
| unpickle                | 22.1 us                                                                                                                | 22.5 us: 1.02x slower                                                                                                      |
| subparsers              | 14.7 ms                                                                                                                | 15.0 ms: 1.02x slower                                                                                                      |
| xml_etree_parse         | 242 ms                                                                                                                 | 247 ms: 1.02x slower                                                                                                       |
| logging_format          | 8.67 us                                                                                                                | 8.94 us: 1.03x slower                                                                                                      |
| generators              | 47.3 ms                                                                                                                | 48.8 ms: 1.03x slower                                                                                                      |
| django_template         | 50.3 ms                                                                                                                | 52.1 ms: 1.04x slower                                                                                                      |
| logging_simple          | 7.79 us                                                                                                                | 8.09 us: 1.04x slower                                                                                                      |
| xdsl_constant_fold      | 55.4 ms                                                                                                                | 57.9 ms: 1.04x slower                                                                                                      |
| deepcopy                | 343 us                                                                                                                 | 358 us: 1.05x slower                                                                                                       |
| sqlalchemy_imperative   | 20.4 ms                                                                                                                | 21.3 ms: 1.05x slower                                                                                                      |
| async_generators        | 577 ms                                                                                                                 | 606 ms: 1.05x slower                                                                                                       |
| sphinx                  | 1.48 sec                                                                                                               | 1.56 sec: 1.05x slower                                                                                                     |
| comprehensions          | 24.1 us                                                                                                                | 25.4 us: 1.06x slower                                                                                                      |
| chaos                   | 81.3 ms                                                                                                                | 86.0 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_optimize     | 72.1 ms                                                                                                                | 76.3 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_normalize    | 147 ms                                                                                                                 | 156 ms: 1.06x slower                                                                                                       |
| go                      | 154 ms                                                                                                                 | 165 ms: 1.07x slower                                                                                                       |
| many_optionals          | 933 us                                                                                                                 | 998 us: 1.07x slower                                                                                                       |
| pylint                  | 411 ms                                                                                                                 | 442 ms: 1.08x slower                                                                                                       |
| pycparser               | 1.47 sec                                                                                                               | 1.58 sec: 1.08x slower                                                                                                     |
| sqlglot_v2_parse        | 1.65 ms                                                                                                                | 1.78 ms: 1.08x slower                                                                                                      |
| html5lib                | 77.0 ms                                                                                                                | 83.2 ms: 1.08x slower                                                                                                      |
| sympy_integrate         | 23.0 ms                                                                                                                | 24.9 ms: 1.08x slower                                                                                                      |
| nqueens                 | 119 ms                                                                                                                 | 129 ms: 1.08x slower                                                                                                       |
| thrift                  | 1.10 ms                                                                                                                | 1.19 ms: 1.08x slower                                                                                                      |
| genshi_text             | 31.9 ms                                                                                                                | 34.8 ms: 1.09x slower                                                                                                      |
| raytrace                | 384 ms                                                                                                                 | 422 ms: 1.10x slower                                                                                                       |
| hexiom                  | 8.26 ms                                                                                                                | 9.13 ms: 1.11x slower                                                                                                      |
| docutils                | 4.18 sec                                                                                                               | 4.64 sec: 1.11x slower                                                                                                     |
| sympy_sum               | 170 ms                                                                                                                 | 190 ms: 1.12x slower                                                                                                       |
| sympy_str               | 320 ms                                                                                                                 | 360 ms: 1.13x slower                                                                                                       |
| mdp                     | 2.35 sec                                                                                                               | 2.67 sec: 1.14x slower                                                                                                     |
| dulwich_log             | 60.1 ms                                                                                                                | 68.5 ms: 1.14x slower                                                                                                      |
| sympy_expand            | 552 ms                                                                                                                 | 635 ms: 1.15x slower                                                                                                       |
| unpack_sequence         | 65.8 ns                                                                                                                | 78.7 ns: 1.20x slower                                                                                                      |
| genshi_xml              | 72.9 ms                                                                                                                | 91.0 ms: 1.25x slower                                                                                                      |
| Geometric mean          | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (23): async_tree_memoization, async_tree_memoization_tg, sqlglot_v2_transpile, async_tree_none_tg, async_tree_cpu_io_mixed, typing_runtime_protocols, asyncio_tcp, gc_traversal, async_tree_cpu_io_mixed_tg, create_gc_cycles, regex_compile, k_core, unpickle_list, xml_etree_iterparse, pickle_pure_python, regex_v8, asyncio_websockets, meteor_contest, chameleon, async_tree_io_tg, asyncio_tcp_ssl, async_tree_none, bench_mp_pool

- Geometric mean (including insignificant results): 1.008x faster

# HPT report

- Reliability score: 63.03% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.04x