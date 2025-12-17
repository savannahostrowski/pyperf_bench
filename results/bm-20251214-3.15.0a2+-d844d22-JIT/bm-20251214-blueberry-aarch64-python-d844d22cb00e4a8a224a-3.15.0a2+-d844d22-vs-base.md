# Results vs. base

- fork: python
- ref: d844d22cb00e4a8a224a
- machine: linux-aarch64
- commit hash: d844d22
- commit date: 2025-12-14
- overall geometric mean: 1.020x faster
- HPT reliability: 77.99%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 427 ms                                                                                                                 | 430 ms: 1.01x slower                                                                                                       |
| html5lib       | 82.2 ms                                                                                                                | 96.4 ms: 1.17x slower                                                                                                      |
| sphinx         | 1.58 sec                                                                                                               | 1.64 sec: 1.04x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines                | 43.1 ms                                                                                                                | 40.0 ms: 1.08x faster                                                                                                      |
| asyncio_tcp               | 1.14 sec                                                                                                               | 1.11 sec: 1.02x faster                                                                                                     |
| asyncio_tcp_ssl           | 4.19 sec                                                                                                               | 4.22 sec: 1.01x slower                                                                                                     |
| async_tree_memoization_tg | 658 ms                                                                                                                 | 687 ms: 1.04x slower                                                                                                       |
| async_tree_io_tg          | 1.24 sec                                                                                                               | 1.30 sec: 1.05x slower                                                                                                     |
| async_generators          | 590 ms                                                                                                                 | 629 ms: 1.07x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (7): async_tree_none_tg, asyncio_websockets, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 173 ms                                                                                                                 | 129 ms: 1.34x faster                                                                                                       |
| float          | 133 ms                                                                                                                 | 117 ms: 1.14x faster                                                                                                       |
| pidigits       | 338 ms                                                                                                                 | 332 ms: 1.02x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.16x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 305 ms                                                                                                                 | 282 ms: 1.08x faster                                                                                                       |
| regex_effbot   | 4.84 ms                                                                                                                | 4.63 ms: 1.05x faster                                                                                                      |
| regex_v8       | 38.3 ms                                                                                                                | 37.1 ms: 1.03x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 350 us                                                                                                                 | 277 us: 1.26x faster                                                                                                       |
| pickle_pure_python   | 487 us                                                                                                                 | 422 us: 1.16x faster                                                                                                       |
| xml_etree_generate   | 148 ms                                                                                                                 | 128 ms: 1.15x faster                                                                                                       |
| tomli_loads          | 3.68 sec                                                                                                               | 3.26 sec: 1.13x faster                                                                                                     |
| xml_etree_process    | 110 ms                                                                                                                 | 97.5 ms: 1.13x faster                                                                                                      |
| pickle_dict          | 50.1 us                                                                                                                | 47.4 us: 1.06x faster                                                                                                      |
| json_loads           | 42.0 us                                                                                                                | 39.7 us: 1.06x faster                                                                                                      |
| xml_etree_parse      | 263 ms                                                                                                                 | 250 ms: 1.05x faster                                                                                                       |
| unpickle_list        | 8.98 us                                                                                                                | 8.59 us: 1.05x faster                                                                                                      |
| json_dumps           | 15.4 ms                                                                                                                | 14.7 ms: 1.04x faster                                                                                                      |
| pickle               | 19.4 us                                                                                                                | 18.6 us: 1.04x faster                                                                                                      |
| pickle_list          | 7.12 us                                                                                                                | 6.89 us: 1.03x faster                                                                                                      |
| unpickle             | 24.3 us                                                                                                                | 23.6 us: 1.03x faster                                                                                                      |
| xml_etree_iterparse  | 207 ms                                                                                                                 | 205 ms: 1.01x faster                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.08x faster                                                                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.6 ms                                                                                                                | 18.0 ms: 1.04x faster                                                                                                      |
| python_startup_no_site | 10.9 ms                                                                                                                | 10.6 ms: 1.02x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 21.3 ms                                                                                                                | 18.8 ms: 1.14x faster                                                                                                      |
| django_template | 54.4 ms                                                                                                                | 56.0 ms: 1.03x slower                                                                                                      |
| genshi_text     | 35.9 ms                                                                                                                | 39.1 ms: 1.09x slower                                                                                                      |
| genshi_xml      | 81.3 ms                                                                                                                | 104 ms: 1.28x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json | results/bm-20251214-3.15.0a2+-d844d22-JIT/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 68.3 ms                                                                                                                | 46.0 ms: 1.48x faster                                                                                                      |
| richards_super            | 78.0 ms                                                                                                                | 53.4 ms: 1.46x faster                                                                                                      |
| nbody                     | 173 ms                                                                                                                 | 129 ms: 1.34x faster                                                                                                       |
| logging_silent            | 171 ns                                                                                                                 | 131 ns: 1.30x faster                                                                                                       |
| unpickle_pure_python      | 350 us                                                                                                                 | 277 us: 1.26x faster                                                                                                       |
| scimark_fft               | 519 ms                                                                                                                 | 428 ms: 1.21x faster                                                                                                       |
| scimark_sor               | 188 ms                                                                                                                 | 160 ms: 1.18x faster                                                                                                       |
| deltablue                 | 5.45 ms                                                                                                                | 4.71 ms: 1.16x faster                                                                                                      |
| pickle_pure_python        | 487 us                                                                                                                 | 422 us: 1.16x faster                                                                                                       |
| xml_etree_generate        | 148 ms                                                                                                                 | 128 ms: 1.15x faster                                                                                                       |
| float                     | 133 ms                                                                                                                 | 117 ms: 1.14x faster                                                                                                       |
| mako                      | 21.3 ms                                                                                                                | 18.8 ms: 1.14x faster                                                                                                      |
| scimark_monte_carlo       | 106 ms                                                                                                                 | 94.0 ms: 1.13x faster                                                                                                      |
| tomli_loads               | 3.68 sec                                                                                                               | 3.26 sec: 1.13x faster                                                                                                     |
| xml_etree_process         | 110 ms                                                                                                                 | 97.5 ms: 1.13x faster                                                                                                      |
| deepcopy_memo             | 42.7 us                                                                                                                | 38.4 us: 1.11x faster                                                                                                      |
| pyflate                   | 771 ms                                                                                                                 | 706 ms: 1.09x faster                                                                                                       |
| regex_dna                 | 305 ms                                                                                                                 | 282 ms: 1.08x faster                                                                                                       |
| coroutines                | 43.1 ms                                                                                                                | 40.0 ms: 1.08x faster                                                                                                      |
| fannkuch                  | 651 ms                                                                                                                 | 606 ms: 1.07x faster                                                                                                       |
| scimark_sparse_mat_mult   | 8.42 ms                                                                                                                | 7.85 ms: 1.07x faster                                                                                                      |
| sqlite_synth              | 4.95 us                                                                                                                | 4.63 us: 1.07x faster                                                                                                      |
| spectral_norm             | 164 ms                                                                                                                 | 154 ms: 1.06x faster                                                                                                       |
| bpe_tokeniser             | 7.65 sec                                                                                                               | 7.23 sec: 1.06x faster                                                                                                     |
| pickle_dict               | 50.1 us                                                                                                                | 47.4 us: 1.06x faster                                                                                                      |
| json_loads                | 42.0 us                                                                                                                | 39.7 us: 1.06x faster                                                                                                      |
| scimark_lu                | 181 ms                                                                                                                 | 172 ms: 1.05x faster                                                                                                       |
| xml_etree_parse           | 263 ms                                                                                                                 | 250 ms: 1.05x faster                                                                                                       |
| unpickle_list             | 8.98 us                                                                                                                | 8.59 us: 1.05x faster                                                                                                      |
| regex_effbot              | 4.84 ms                                                                                                                | 4.63 ms: 1.05x faster                                                                                                      |
| json                      | 7.24 ms                                                                                                                | 6.93 ms: 1.05x faster                                                                                                      |
| telco                     | 213 ms                                                                                                                 | 204 ms: 1.04x faster                                                                                                       |
| json_dumps                | 15.4 ms                                                                                                                | 14.7 ms: 1.04x faster                                                                                                      |
| pickle                    | 19.4 us                                                                                                                | 18.6 us: 1.04x faster                                                                                                      |
| crypto_pyaes              | 113 ms                                                                                                                 | 109 ms: 1.04x faster                                                                                                       |
| python_startup            | 18.6 ms                                                                                                                | 18.0 ms: 1.04x faster                                                                                                      |
| pickle_list               | 7.12 us                                                                                                                | 6.89 us: 1.03x faster                                                                                                      |
| unpickle                  | 24.3 us                                                                                                                | 23.6 us: 1.03x faster                                                                                                      |
| regex_v8                  | 38.3 ms                                                                                                                | 37.1 ms: 1.03x faster                                                                                                      |
| generators                | 52.8 ms                                                                                                                | 51.4 ms: 1.03x faster                                                                                                      |
| python_startup_no_site    | 10.9 ms                                                                                                                | 10.6 ms: 1.02x faster                                                                                                      |
| asyncio_tcp               | 1.14 sec                                                                                                               | 1.11 sec: 1.02x faster                                                                                                     |
| logging_simple            | 8.86 us                                                                                                                | 8.68 us: 1.02x faster                                                                                                      |
| pidigits                  | 338 ms                                                                                                                 | 332 ms: 1.02x faster                                                                                                       |
| meteor_contest            | 146 ms                                                                                                                 | 143 ms: 1.02x faster                                                                                                       |
| raytrace                  | 428 ms                                                                                                                 | 420 ms: 1.02x faster                                                                                                       |
| connected_components      | 851 ms                                                                                                                 | 836 ms: 1.02x faster                                                                                                       |
| shortest_path             | 899 ms                                                                                                                 | 886 ms: 1.02x faster                                                                                                       |
| create_gc_cycles          | 9.18 ms                                                                                                                | 9.07 ms: 1.01x faster                                                                                                      |
| gc_traversal              | 15.1 ms                                                                                                                | 14.9 ms: 1.01x faster                                                                                                      |
| xml_etree_iterparse       | 207 ms                                                                                                                 | 205 ms: 1.01x faster                                                                                                       |
| k_core                    | 4.10 sec                                                                                                               | 4.06 sec: 1.01x faster                                                                                                     |
| asyncio_tcp_ssl           | 4.19 sec                                                                                                               | 4.22 sec: 1.01x slower                                                                                                     |
| 2to3                      | 427 ms                                                                                                                 | 430 ms: 1.01x slower                                                                                                       |
| sqlalchemy_imperative     | 22.4 ms                                                                                                                | 22.7 ms: 1.01x slower                                                                                                      |
| pprint_safe_repr          | 1.13 sec                                                                                                               | 1.15 sec: 1.02x slower                                                                                                     |
| sqlglot_v2_optimize       | 79.5 ms                                                                                                                | 81.3 ms: 1.02x slower                                                                                                      |
| pprint_pformat            | 2.33 sec                                                                                                               | 2.39 sec: 1.03x slower                                                                                                     |
| sqlglot_v2_normalize      | 164 ms                                                                                                                 | 168 ms: 1.03x slower                                                                                                       |
| django_template           | 54.4 ms                                                                                                                | 56.0 ms: 1.03x slower                                                                                                      |
| xdsl_constant_fold        | 59.6 ms                                                                                                                | 61.4 ms: 1.03x slower                                                                                                      |
| comprehensions            | 26.7 us                                                                                                                | 27.6 us: 1.03x slower                                                                                                      |
| sphinx                    | 1.58 sec                                                                                                               | 1.64 sec: 1.04x slower                                                                                                     |
| logging_format            | 9.42 us                                                                                                                | 9.80 us: 1.04x slower                                                                                                      |
| pylint                    | 437 ms                                                                                                                 | 455 ms: 1.04x slower                                                                                                       |
| deepcopy_reduce           | 4.32 us                                                                                                                | 4.51 us: 1.04x slower                                                                                                      |
| async_tree_memoization_tg | 658 ms                                                                                                                 | 687 ms: 1.04x slower                                                                                                       |
| async_tree_io_tg          | 1.24 sec                                                                                                               | 1.30 sec: 1.05x slower                                                                                                     |
| pycparser                 | 1.60 sec                                                                                                               | 1.68 sec: 1.05x slower                                                                                                     |
| typing_runtime_protocols  | 243 us                                                                                                                 | 256 us: 1.05x slower                                                                                                       |
| chaos                     | 90.6 ms                                                                                                                | 95.8 ms: 1.06x slower                                                                                                      |
| go                        | 173 ms                                                                                                                 | 184 ms: 1.06x slower                                                                                                       |
| async_generators          | 590 ms                                                                                                                 | 629 ms: 1.07x slower                                                                                                       |
| hexiom                    | 9.23 ms                                                                                                                | 10.0 ms: 1.09x slower                                                                                                      |
| many_optionals            | 928 us                                                                                                                 | 1.01 ms: 1.09x slower                                                                                                      |
| genshi_text               | 35.9 ms                                                                                                                | 39.1 ms: 1.09x slower                                                                                                      |
| mdp                       | 2.55 sec                                                                                                               | 2.80 sec: 1.10x slower                                                                                                     |
| deepcopy                  | 387 us                                                                                                                 | 436 us: 1.13x slower                                                                                                       |
| nqueens                   | 124 ms                                                                                                                 | 141 ms: 1.14x slower                                                                                                       |
| unpack_sequence           | 74.8 ns                                                                                                                | 87.1 ns: 1.17x slower                                                                                                      |
| html5lib                  | 82.2 ms                                                                                                                | 96.4 ms: 1.17x slower                                                                                                      |
| dulwich_log               | 66.1 ms                                                                                                                | 82.0 ms: 1.24x slower                                                                                                      |
| bench_mp_pool             | 170 ms                                                                                                                 | 212 ms: 1.25x slower                                                                                                       |
| genshi_xml                | 81.3 ms                                                                                                                | 104 ms: 1.28x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (18): async_tree_none_tg, coverage, sqlalchemy_declarative, thrift, asyncio_websockets, sqlglot_v2_transpile, pathlib, chameleon, regex_compile, bench_thread_pool, async_tree_cpu_io_mixed_tg, tornado_http, async_tree_io, sqlglot_v2_parse, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization, subparsers
Ignored benchmarks (5) of results/bm-20251214-3.15.0a2+-d844d22/bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2+-d844d22.json: docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.020x faster

# HPT report

- Reliability score: 77.99% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x