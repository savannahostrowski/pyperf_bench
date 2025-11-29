# Results vs. base

- fork: python
- ref: d2d2e92110751fff3cbb
- machine: linux-aarch64
- commit hash: d2d2e92
- commit date: 2025-11-28
- overall geometric mean: 1.087x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 375 ms                                                                                                                 | 387 ms: 1.03x slower                                                                                                       |
| docutils       | 3.90 sec                                                                                                               | 4.83 sec: 1.24x slower                                                                                                     |
| html5lib       | 74.0 ms                                                                                                                | 105 ms: 1.42x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.18x slower                                                                                                               |

Benchmark hidden because not significant (1): sphinx

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines                | 36.2 ms                                                                                                                | 36.9 ms: 1.02x slower                                                                                                      |
| asyncio_tcp_ssl           | 2.80 sec                                                                                                               | 2.88 sec: 1.03x slower                                                                                                     |
| async_tree_io_tg          | 1.06 sec                                                                                                               | 1.09 sec: 1.03x slower                                                                                                     |
| async_tree_memoization_tg | 561 ms                                                                                                                 | 593 ms: 1.06x slower                                                                                                       |
| asyncio_tcp               | 648 ms                                                                                                                 | 690 ms: 1.06x slower                                                                                                       |
| async_generators          | 555 ms                                                                                                                 | 604 ms: 1.09x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (7): asyncio_websockets, async_tree_none, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 109 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| pidigits       | 324 ms                                                                                                                 | 325 ms: 1.00x slower                                                                                                       |
| nbody          | 145 ms                                                                                                                 | 154 ms: 1.06x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.46 ms                                                                                                                | 4.39 ms: 1.02x faster                                                                                                      |
| regex_v8       | 35.4 ms                                                                                                                | 35.5 ms: 1.00x slower                                                                                                      |
| regex_dna      | 258 ms                                                                                                                 | 265 ms: 1.02x slower                                                                                                       |
| regex_compile  | 141 ms                                                                                                                 | 176 ms: 1.25x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| xml_etree_parse      | 240 ms                                                                                                                 | 221 ms: 1.09x faster                                                                                                       |
| unpickle_pure_python | 317 us                                                                                                                 | 292 us: 1.09x faster                                                                                                       |
| xml_etree_iterparse  | 183 ms                                                                                                                 | 180 ms: 1.02x faster                                                                                                       |
| xml_etree_generate   | 126 ms                                                                                                                 | 124 ms: 1.01x faster                                                                                                       |
| xml_etree_process    | 94.1 ms                                                                                                                | 93.1 ms: 1.01x faster                                                                                                      |
| pickle               | 18.3 us                                                                                                                | 18.3 us: 1.00x faster                                                                                                      |
| json_dumps           | 13.8 ms                                                                                                                | 13.9 ms: 1.01x slower                                                                                                      |
| unpickle_list        | 8.02 us                                                                                                                | 8.15 us: 1.02x slower                                                                                                      |
| pickle_pure_python   | 435 us                                                                                                                 | 446 us: 1.03x slower                                                                                                       |
| unpickle             | 22.1 us                                                                                                                | 23.4 us: 1.06x slower                                                                                                      |
| tomli_loads          | 3.20 sec                                                                                                               | 3.86 sec: 1.21x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (3): json_loads, pickle_dict, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 16.2 ms                                                                                                                | 16.4 ms: 1.01x slower                                                                                                      |
| python_startup_no_site | 9.34 ms                                                                                                                | 9.52 ms: 1.02x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.5 ms                                                                                                                | 15.7 ms: 1.05x faster                                                                                                      |
| django_template | 49.5 ms                                                                                                                | 54.3 ms: 1.10x slower                                                                                                      |
| genshi_text     | 31.4 ms                                                                                                                | 40.3 ms: 1.28x slower                                                                                                      |
| genshi_xml      | 71.0 ms                                                                                                                | 117 ms: 1.64x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.22x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| logging_silent            | 155 ns                                                                                                                 | 137 ns: 1.13x faster                                                                                                       |
| xml_etree_parse           | 240 ms                                                                                                                 | 221 ms: 1.09x faster                                                                                                       |
| unpickle_pure_python      | 317 us                                                                                                                 | 292 us: 1.09x faster                                                                                                       |
| spectral_norm             | 151 ms                                                                                                                 | 143 ms: 1.06x faster                                                                                                       |
| mako                      | 16.5 ms                                                                                                                | 15.7 ms: 1.05x faster                                                                                                      |
| float                     | 109 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| scimark_fft               | 461 ms                                                                                                                 | 442 ms: 1.04x faster                                                                                                       |
| xml_etree_iterparse       | 183 ms                                                                                                                 | 180 ms: 1.02x faster                                                                                                       |
| deepcopy_memo             | 39.8 us                                                                                                                | 39.1 us: 1.02x faster                                                                                                      |
| json                      | 6.70 ms                                                                                                                | 6.59 ms: 1.02x faster                                                                                                      |
| regex_effbot              | 4.46 ms                                                                                                                | 4.39 ms: 1.02x faster                                                                                                      |
| xml_etree_generate        | 126 ms                                                                                                                 | 124 ms: 1.01x faster                                                                                                       |
| xml_etree_process         | 94.1 ms                                                                                                                | 93.1 ms: 1.01x faster                                                                                                      |
| scimark_sparse_mat_mult   | 7.89 ms                                                                                                                | 7.81 ms: 1.01x faster                                                                                                      |
| create_gc_cycles          | 7.72 ms                                                                                                                | 7.66 ms: 1.01x faster                                                                                                      |
| gc_traversal              | 13.2 ms                                                                                                                | 13.2 ms: 1.00x faster                                                                                                      |
| pickle                    | 18.3 us                                                                                                                | 18.3 us: 1.00x faster                                                                                                      |
| pidigits                  | 324 ms                                                                                                                 | 325 ms: 1.00x slower                                                                                                       |
| regex_v8                  | 35.4 ms                                                                                                                | 35.5 ms: 1.00x slower                                                                                                      |
| scimark_sor               | 170 ms                                                                                                                 | 171 ms: 1.00x slower                                                                                                       |
| bpe_tokeniser             | 6.67 sec                                                                                                               | 6.72 sec: 1.01x slower                                                                                                     |
| json_dumps                | 13.8 ms                                                                                                                | 13.9 ms: 1.01x slower                                                                                                      |
| python_startup            | 16.2 ms                                                                                                                | 16.4 ms: 1.01x slower                                                                                                      |
| unpickle_list             | 8.02 us                                                                                                                | 8.15 us: 1.02x slower                                                                                                      |
| coverage                  | 121 ms                                                                                                                 | 123 ms: 1.02x slower                                                                                                       |
| coroutines                | 36.2 ms                                                                                                                | 36.9 ms: 1.02x slower                                                                                                      |
| subparsers                | 59.0 ms                                                                                                                | 60.1 ms: 1.02x slower                                                                                                      |
| python_startup_no_site    | 9.34 ms                                                                                                                | 9.52 ms: 1.02x slower                                                                                                      |
| scimark_lu                | 165 ms                                                                                                                 | 168 ms: 1.02x slower                                                                                                       |
| regex_dna                 | 258 ms                                                                                                                 | 265 ms: 1.02x slower                                                                                                       |
| pickle_pure_python        | 435 us                                                                                                                 | 446 us: 1.03x slower                                                                                                       |
| asyncio_tcp_ssl           | 2.80 sec                                                                                                               | 2.88 sec: 1.03x slower                                                                                                     |
| async_tree_io_tg          | 1.06 sec                                                                                                               | 1.09 sec: 1.03x slower                                                                                                     |
| 2to3                      | 375 ms                                                                                                                 | 387 ms: 1.03x slower                                                                                                       |
| pyflate                   | 662 ms                                                                                                                 | 688 ms: 1.04x slower                                                                                                       |
| logging_format            | 8.62 us                                                                                                                | 8.98 us: 1.04x slower                                                                                                      |
| scimark_monte_carlo       | 94.9 ms                                                                                                                | 98.9 ms: 1.04x slower                                                                                                      |
| pathlib                   | 21.8 ms                                                                                                                | 22.8 ms: 1.04x slower                                                                                                      |
| generators                | 44.3 ms                                                                                                                | 46.3 ms: 1.05x slower                                                                                                      |
| logging_simple            | 7.80 us                                                                                                                | 8.15 us: 1.05x slower                                                                                                      |
| bench_thread_pool         | 1.12 ms                                                                                                                | 1.17 ms: 1.05x slower                                                                                                      |
| typing_runtime_protocols  | 248 us                                                                                                                 | 260 us: 1.05x slower                                                                                                       |
| deltablue                 | 4.70 ms                                                                                                                | 4.94 ms: 1.05x slower                                                                                                      |
| async_tree_memoization_tg | 561 ms                                                                                                                 | 593 ms: 1.06x slower                                                                                                       |
| unpickle                  | 22.1 us                                                                                                                | 23.4 us: 1.06x slower                                                                                                      |
| nbody                     | 145 ms                                                                                                                 | 154 ms: 1.06x slower                                                                                                       |
| meteor_contest            | 134 ms                                                                                                                 | 143 ms: 1.06x slower                                                                                                       |
| asyncio_tcp               | 648 ms                                                                                                                 | 690 ms: 1.06x slower                                                                                                       |
| richards_super            | 70.0 ms                                                                                                                | 75.4 ms: 1.08x slower                                                                                                      |
| richards                  | 62.1 ms                                                                                                                | 67.0 ms: 1.08x slower                                                                                                      |
| deepcopy_reduce           | 3.97 us                                                                                                                | 4.29 us: 1.08x slower                                                                                                      |
| crypto_pyaes              | 100 ms                                                                                                                 | 109 ms: 1.08x slower                                                                                                       |
| async_generators          | 555 ms                                                                                                                 | 604 ms: 1.09x slower                                                                                                       |
| django_template           | 49.5 ms                                                                                                                | 54.3 ms: 1.10x slower                                                                                                      |
| fannkuch                  | 565 ms                                                                                                                 | 620 ms: 1.10x slower                                                                                                       |
| pylint                    | 393 ms                                                                                                                 | 433 ms: 1.10x slower                                                                                                       |
| sqlglot_v2_transpile      | 2.89 ms                                                                                                                | 3.19 ms: 1.10x slower                                                                                                      |
| many_optionals            | 1.26 ms                                                                                                                | 1.41 ms: 1.12x slower                                                                                                      |
| raytrace                  | 379 ms                                                                                                                 | 439 ms: 1.16x slower                                                                                                       |
| pycparser                 | 1.63 sec                                                                                                               | 1.93 sec: 1.18x slower                                                                                                     |
| thrift                    | 1.24 ms                                                                                                                | 1.48 ms: 1.19x slower                                                                                                      |
| mdp                       | 2.24 sec                                                                                                               | 2.67 sec: 1.19x slower                                                                                                     |
| tomli_loads               | 3.20 sec                                                                                                               | 3.86 sec: 1.21x slower                                                                                                     |
| telco                     | 206 ms                                                                                                                 | 250 ms: 1.21x slower                                                                                                       |
| sqlglot_v2_parse          | 2.13 ms                                                                                                                | 2.61 ms: 1.22x slower                                                                                                      |
| docutils                  | 3.90 sec                                                                                                               | 4.83 sec: 1.24x slower                                                                                                     |
| regex_compile             | 141 ms                                                                                                                 | 176 ms: 1.25x slower                                                                                                       |
| sqlglot_v2_optimize       | 86.9 ms                                                                                                                | 108 ms: 1.25x slower                                                                                                       |
| deepcopy                  | 360 us                                                                                                                 | 451 us: 1.25x slower                                                                                                       |
| comprehensions            | 23.6 us                                                                                                                | 29.8 us: 1.27x slower                                                                                                      |
| chaos                     | 79.0 ms                                                                                                                | 101 ms: 1.28x slower                                                                                                       |
| genshi_text               | 31.4 ms                                                                                                                | 40.3 ms: 1.28x slower                                                                                                      |
| nqueens                   | 117 ms                                                                                                                 | 155 ms: 1.32x slower                                                                                                       |
| pprint_pformat            | 2.10 sec                                                                                                               | 2.81 sec: 1.34x slower                                                                                                     |
| pprint_safe_repr          | 1.03 sec                                                                                                               | 1.37 sec: 1.34x slower                                                                                                     |
| sympy_str                 | 469 ms                                                                                                                 | 662 ms: 1.41x slower                                                                                                       |
| hexiom                    | 8.29 ms                                                                                                                | 11.7 ms: 1.42x slower                                                                                                      |
| html5lib                  | 74.0 ms                                                                                                                | 105 ms: 1.42x slower                                                                                                       |
| sympy_integrate           | 33.5 ms                                                                                                                | 48.7 ms: 1.45x slower                                                                                                      |
| dulwich_log               | 61.2 ms                                                                                                                | 89.2 ms: 1.46x slower                                                                                                      |
| go                        | 152 ms                                                                                                                 | 227 ms: 1.49x slower                                                                                                       |
| genshi_xml                | 71.0 ms                                                                                                                | 117 ms: 1.64x slower                                                                                                       |
| sympy_expand              | 642 ms                                                                                                                 | 1.08 sec: 1.68x slower                                                                                                     |
| unpack_sequence           | 63.4 ns                                                                                                                | 117 ns: 1.84x slower                                                                                                       |
| bench_mp_pool             | 122 ms                                                                                                                 | 375 ms: 3.08x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.11x slower                                                                                                               |

Benchmark hidden because not significant (14): sqlite_synth, sqlglot_v2_normalize, json_loads, pickle_dict, asyncio_websockets, pickle_list, async_tree_none, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_memoization, sympy_sum, sphinx

- Geometric mean (including insignificant results): 1.087x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x

# Memory
- memory change: 1.03x