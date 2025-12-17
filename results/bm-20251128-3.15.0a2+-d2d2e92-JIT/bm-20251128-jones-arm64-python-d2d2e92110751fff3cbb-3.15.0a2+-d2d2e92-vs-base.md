# Results vs. base

- fork: python
- ref: d2d2e92110751fff3cbb
- machine: darwin-arm64
- commit hash: d2d2e92
- commit date: 2025-11-28
- overall geometric mean: 1.060x faster
- HPT reliability: 99.86%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 152 ms                                                                                                           | 150 ms: 1.02x faster                                                                                                 |
| docutils       | 1.34 sec                                                                                                         | 1.35 sec: 1.01x slower                                                                                               |
| Geometric mean | (ref)                                                                                                            | 1.00x faster                                                                                                         |

Benchmark hidden because not significant (2): html5lib, sphinx

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|-------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_none         | 142 ms                                                                                                           | 128 ms: 1.11x faster                                                                                                 |
| async_tree_none_tg      | 137 ms                                                                                                           | 130 ms: 1.06x faster                                                                                                 |
| async_tree_memoization  | 171 ms                                                                                                           | 164 ms: 1.04x faster                                                                                                 |
| async_tree_io           | 307 ms                                                                                                           | 298 ms: 1.03x faster                                                                                                 |
| async_tree_cpu_io_mixed | 354 ms                                                                                                           | 347 ms: 1.02x faster                                                                                                 |
| coroutines              | 13.5 ms                                                                                                          | 13.8 ms: 1.02x slower                                                                                                |
| async_generators        | 218 ms                                                                                                           | 232 ms: 1.06x slower                                                                                                 |
| Geometric mean          | (ref)                                                                                                            | 1.01x faster                                                                                                         |

Benchmark hidden because not significant (6): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, asyncio_tcp_ssl, asyncio_websockets, async_tree_io_tg, asyncio_tcp

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| float          | 39.7 ms                                                                                                          | 33.0 ms: 1.20x faster                                                                                                |
| nbody          | 67.9 ms                                                                                                          | 58.0 ms: 1.17x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.12x faster                                                                                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 64.5 ms                                                                                                          | 57.4 ms: 1.12x faster                                                                                                |
| regex_effbot   | 2.09 ms                                                                                                          | 1.97 ms: 1.06x faster                                                                                                |
| regex_dna      | 125 ms                                                                                                           | 123 ms: 1.01x faster                                                                                                 |
| regex_v8       | 13.4 ms                                                                                                          | 13.6 ms: 1.01x slower                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.04x faster                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 135 us                                                                                                           | 108 us: 1.25x faster                                                                                                 |
| tomli_loads          | 1.26 sec                                                                                                         | 1.02 sec: 1.24x faster                                                                                               |
| pickle_pure_python   | 188 us                                                                                                           | 156 us: 1.21x faster                                                                                                 |
| xml_etree_process    | 33.2 ms                                                                                                          | 28.2 ms: 1.18x faster                                                                                                |
| xml_etree_generate   | 46.2 ms                                                                                                          | 39.7 ms: 1.17x faster                                                                                                |
| xml_etree_iterparse  | 52.1 ms                                                                                                          | 47.5 ms: 1.10x faster                                                                                                |
| json_dumps           | 4.80 ms                                                                                                          | 4.57 ms: 1.05x faster                                                                                                |
| xml_etree_parse      | 77.4 ms                                                                                                          | 76.3 ms: 1.01x faster                                                                                                |
| pickle               | 7.13 us                                                                                                          | 7.22 us: 1.01x slower                                                                                                |
| pickle_list          | 2.45 us                                                                                                          | 2.51 us: 1.02x slower                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.08x faster                                                                                                         |

Benchmark hidden because not significant (4): unpickle_list, pickle_dict, unpickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup | 12.2 ms                                                                                                          | 12.1 ms: 1.01x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.00x faster                                                                                                         |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 6.71 ms                                                                                                          | 5.57 ms: 1.20x faster                                                                                                |
| genshi_text     | 13.5 ms                                                                                                          | 12.4 ms: 1.09x faster                                                                                                |
| genshi_xml      | 28.7 ms                                                                                                          | 27.8 ms: 1.04x faster                                                                                                |
| django_template | 18.1 ms                                                                                                          | 17.8 ms: 1.02x faster                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.08x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                | results/bm-20251128-3.15.0a2+-d2d2e92/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json | results/bm-20251128-3.15.0a2+-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2+-d2d2e92.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards                 | 27.7 ms                                                                                                          | 16.5 ms: 1.68x faster                                                                                                |
| richards_super           | 31.2 ms                                                                                                          | 19.3 ms: 1.62x faster                                                                                                |
| deepcopy_memo            | 18.3 us                                                                                                          | 13.3 us: 1.38x faster                                                                                                |
| pprint_safe_repr         | 438 ms                                                                                                           | 344 ms: 1.27x faster                                                                                                 |
| pprint_pformat           | 888 ms                                                                                                           | 703 ms: 1.26x faster                                                                                                 |
| scimark_sor              | 72.5 ms                                                                                                          | 57.6 ms: 1.26x faster                                                                                                |
| unpickle_pure_python     | 135 us                                                                                                           | 108 us: 1.25x faster                                                                                                 |
| tomli_loads              | 1.26 sec                                                                                                         | 1.02 sec: 1.24x faster                                                                                               |
| scimark_monte_carlo      | 39.0 ms                                                                                                          | 32.1 ms: 1.22x faster                                                                                                |
| pickle_pure_python       | 188 us                                                                                                           | 156 us: 1.21x faster                                                                                                 |
| float                    | 39.7 ms                                                                                                          | 33.0 ms: 1.20x faster                                                                                                |
| mako                     | 6.71 ms                                                                                                          | 5.57 ms: 1.20x faster                                                                                                |
| fannkuch                 | 240 ms                                                                                                           | 201 ms: 1.20x faster                                                                                                 |
| logging_silent           | 61.4 ns                                                                                                          | 51.8 ns: 1.19x faster                                                                                                |
| xml_etree_process        | 33.2 ms                                                                                                          | 28.2 ms: 1.18x faster                                                                                                |
| nbody                    | 67.9 ms                                                                                                          | 58.0 ms: 1.17x faster                                                                                                |
| xml_etree_generate       | 46.2 ms                                                                                                          | 39.7 ms: 1.17x faster                                                                                                |
| comprehensions           | 10.4 us                                                                                                          | 8.98 us: 1.16x faster                                                                                                |
| deepcopy                 | 144 us                                                                                                           | 124 us: 1.16x faster                                                                                                 |
| pyflate                  | 269 ms                                                                                                           | 235 ms: 1.14x faster                                                                                                 |
| scimark_fft              | 152 ms                                                                                                           | 134 ms: 1.14x faster                                                                                                 |
| deltablue                | 2.09 ms                                                                                                          | 1.86 ms: 1.13x faster                                                                                                |
| regex_compile            | 64.5 ms                                                                                                          | 57.4 ms: 1.12x faster                                                                                                |
| async_tree_none          | 142 ms                                                                                                           | 128 ms: 1.11x faster                                                                                                 |
| xml_etree_iterparse      | 52.1 ms                                                                                                          | 47.5 ms: 1.10x faster                                                                                                |
| go                       | 75.4 ms                                                                                                          | 68.9 ms: 1.09x faster                                                                                                |
| genshi_text              | 13.5 ms                                                                                                          | 12.4 ms: 1.09x faster                                                                                                |
| scimark_lu               | 63.0 ms                                                                                                          | 58.4 ms: 1.08x faster                                                                                                |
| meteor_contest           | 66.5 ms                                                                                                          | 61.9 ms: 1.07x faster                                                                                                |
| bpe_tokeniser            | 2.56 sec                                                                                                         | 2.38 sec: 1.07x faster                                                                                               |
| sqlglot_v2_parse         | 704 us                                                                                                           | 659 us: 1.07x faster                                                                                                 |
| deepcopy_reduce          | 1.48 us                                                                                                          | 1.39 us: 1.06x faster                                                                                                |
| telco                    | 3.41 ms                                                                                                          | 3.21 ms: 1.06x faster                                                                                                |
| hexiom                   | 4.08 ms                                                                                                          | 3.84 ms: 1.06x faster                                                                                                |
| regex_effbot             | 2.09 ms                                                                                                          | 1.97 ms: 1.06x faster                                                                                                |
| async_tree_none_tg       | 137 ms                                                                                                           | 130 ms: 1.06x faster                                                                                                 |
| sqlglot_v2_transpile     | 854 us                                                                                                           | 809 us: 1.06x faster                                                                                                 |
| json_dumps               | 4.80 ms                                                                                                          | 4.57 ms: 1.05x faster                                                                                                |
| crypto_pyaes             | 45.1 ms                                                                                                          | 43.0 ms: 1.05x faster                                                                                                |
| nqueens                  | 52.2 ms                                                                                                          | 49.8 ms: 1.05x faster                                                                                                |
| typing_runtime_protocols | 85.6 us                                                                                                          | 81.8 us: 1.05x faster                                                                                                |
| async_tree_memoization   | 171 ms                                                                                                           | 164 ms: 1.04x faster                                                                                                 |
| genshi_xml               | 28.7 ms                                                                                                          | 27.8 ms: 1.04x faster                                                                                                |
| thrift                   | 385 us                                                                                                           | 372 us: 1.03x faster                                                                                                 |
| async_tree_io            | 307 ms                                                                                                           | 298 ms: 1.03x faster                                                                                                 |
| json                     | 2.36 ms                                                                                                          | 2.30 ms: 1.03x faster                                                                                                |
| pathlib                  | 14.1 ms                                                                                                          | 13.7 ms: 1.02x faster                                                                                                |
| async_tree_cpu_io_mixed  | 354 ms                                                                                                           | 347 ms: 1.02x faster                                                                                                 |
| logging_format           | 3.12 us                                                                                                          | 3.06 us: 1.02x faster                                                                                                |
| django_template          | 18.1 ms                                                                                                          | 17.8 ms: 1.02x faster                                                                                                |
| 2to3                     | 152 ms                                                                                                           | 150 ms: 1.02x faster                                                                                                 |
| xml_etree_parse          | 77.4 ms                                                                                                          | 76.3 ms: 1.01x faster                                                                                                |
| bench_thread_pool        | 509 us                                                                                                           | 502 us: 1.01x faster                                                                                                 |
| sqlite_synth             | 1.18 us                                                                                                          | 1.16 us: 1.01x faster                                                                                                |
| regex_dna                | 125 ms                                                                                                           | 123 ms: 1.01x faster                                                                                                 |
| python_startup           | 12.2 ms                                                                                                          | 12.1 ms: 1.01x faster                                                                                                |
| gc_traversal             | 2.72 ms                                                                                                          | 2.71 ms: 1.00x faster                                                                                                |
| chaos                    | 32.5 ms                                                                                                          | 32.7 ms: 1.01x slower                                                                                                |
| docutils                 | 1.34 sec                                                                                                         | 1.35 sec: 1.01x slower                                                                                               |
| many_optionals           | 517 us                                                                                                           | 522 us: 1.01x slower                                                                                                 |
| raytrace                 | 146 ms                                                                                                           | 148 ms: 1.01x slower                                                                                                 |
| sqlglot_v2_optimize      | 29.7 ms                                                                                                          | 30.0 ms: 1.01x slower                                                                                                |
| pickle                   | 7.13 us                                                                                                          | 7.22 us: 1.01x slower                                                                                                |
| regex_v8                 | 13.4 ms                                                                                                          | 13.6 ms: 1.01x slower                                                                                                |
| spectral_norm            | 51.8 ms                                                                                                          | 52.7 ms: 1.02x slower                                                                                                |
| sqlglot_v2_normalize     | 60.6 ms                                                                                                          | 61.7 ms: 1.02x slower                                                                                                |
| coroutines               | 13.5 ms                                                                                                          | 13.8 ms: 1.02x slower                                                                                                |
| pickle_list              | 2.45 us                                                                                                          | 2.51 us: 1.02x slower                                                                                                |
| generators               | 22.0 ms                                                                                                          | 22.6 ms: 1.03x slower                                                                                                |
| subparsers               | 22.8 ms                                                                                                          | 23.4 ms: 1.03x slower                                                                                                |
| coverage                 | 38.3 ms                                                                                                          | 39.5 ms: 1.03x slower                                                                                                |
| sympy_expand             | 221 ms                                                                                                           | 229 ms: 1.03x slower                                                                                                 |
| bench_mp_pool            | 55.3 ms                                                                                                          | 57.2 ms: 1.03x slower                                                                                                |
| dulwich_log              | 21.8 ms                                                                                                          | 22.6 ms: 1.04x slower                                                                                                |
| pycparser                | 600 ms                                                                                                           | 626 ms: 1.04x slower                                                                                                 |
| scimark_sparse_mat_mult  | 2.20 ms                                                                                                          | 2.32 ms: 1.05x slower                                                                                                |
| djangocms                | 5.81 us                                                                                                          | 6.16 us: 1.06x slower                                                                                                |
| async_generators         | 218 ms                                                                                                           | 232 ms: 1.06x slower                                                                                                 |
| sympy_str                | 132 ms                                                                                                           | 141 ms: 1.07x slower                                                                                                 |
| sympy_sum                | 70.9 ms                                                                                                          | 76.6 ms: 1.08x slower                                                                                                |
| sympy_integrate          | 9.44 ms                                                                                                          | 10.4 ms: 1.10x slower                                                                                                |
| pylint                   | 141 ms                                                                                                           | 157 ms: 1.12x slower                                                                                                 |
| mdp                      | 674 ms                                                                                                           | 755 ms: 1.12x slower                                                                                                 |
| unpack_sequence          | 36.8 ns                                                                                                          | 42.2 ns: 1.15x slower                                                                                                |
| Geometric mean           | (ref)                                                                                                            | 1.05x faster                                                                                                         |

Benchmark hidden because not significant (16): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, asyncio_tcp_ssl, unpickle_list, pickle_dict, unpickle, asyncio_websockets, pidigits, python_startup_no_site, async_tree_io_tg, html5lib, sphinx, logging_simple, create_gc_cycles, json_loads, asyncio_tcp

- Geometric mean (including insignificant results): 1.060x faster

# HPT report

- Reliability score: 99.86% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x