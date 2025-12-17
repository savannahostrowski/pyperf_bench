# Results vs. base

- fork: python
- ref: bc9e63dd9d2931771415
- machine: linux-aarch64
- commit hash: bc9e63d
- commit date: 2025-11-26
- overall geometric mean: 1.074x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json | results/bm-20251126-3.15.0a2+-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 375 ms                                                                                                                 | 384 ms: 1.03x slower                                                                                                       |
| html5lib       | 74.2 ms                                                                                                                | 105 ms: 1.42x slower                                                                                                       |
| sphinx         | 1.40 sec                                                                                                               | 1.60 sec: 1.14x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.18x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json | results/bm-20251126-3.15.0a2+-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 845 ms                                                                                                                 | 820 ms: 1.03x faster                                                                                                       |
| asyncio_websockets         | 816 ms                                                                                                                 | 819 ms: 1.00x slower                                                                                                       |
| coroutines                 | 36.9 ms                                                                                                                | 37.5 ms: 1.02x slower                                                                                                      |
| asyncio_tcp_ssl            | 2.81 sec                                                                                                               | 2.87 sec: 1.02x slower                                                                                                     |
| asyncio_tcp                | 669 ms                                                                                                                 | 687 ms: 1.03x slower                                                                                                       |
| async_generators           | 576 ms                                                                                                                 | 623 ms: 1.08x slower                                                                                                       |
| Geometric mean             | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (7): async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization, async_tree_io, async_tree_memoization_tg, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json | results/bm-20251126-3.15.0a2+-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 111 ms                                                                                                                 | 105 ms: 1.06x faster                                                                                                       |
| nbody          | 154 ms                                                                                                                 | 153 ms: 1.00x faster                                                                                                       |
| pidigits       | 324 ms                                                                                                                 | 324 ms: 1.00x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json | results/bm-20251126-3.15.0a2+-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 35.9 ms                                                                                                                | 35.3 ms: 1.02x faster                                                                                                      |
| regex_dna      | 268 ms                                                                                                                 | 265 ms: 1.01x faster                                                                                                       |
| regex_effbot   | 4.44 ms                                                                                                                | 4.39 ms: 1.01x faster                                                                                                      |
| regex_compile  | 144 ms                                                                                                                 | 178 ms: 1.23x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json | results/bm-20251126-3.15.0a2+-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 312 us                                                                                                                 | 287 us: 1.09x faster                                                                                                       |
| xml_etree_generate   | 129 ms                                                                                                                 | 124 ms: 1.04x faster                                                                                                       |
| xml_etree_process    | 95.2 ms                                                                                                                | 92.5 ms: 1.03x faster                                                                                                      |
| json_dumps           | 13.8 ms                                                                                                                | 13.5 ms: 1.02x faster                                                                                                      |
| xml_etree_parse      | 226 ms                                                                                                                 | 223 ms: 1.01x faster                                                                                                       |
| json_loads           | 38.1 us                                                                                                                | 37.9 us: 1.01x faster                                                                                                      |
| unpickle             | 21.5 us                                                                                                                | 21.5 us: 1.00x faster                                                                                                      |
| pickle_pure_python   | 443 us                                                                                                                 | 446 us: 1.01x slower                                                                                                       |
| xml_etree_iterparse  | 180 ms                                                                                                                 | 181 ms: 1.01x slower                                                                                                       |
| pickle               | 18.5 us                                                                                                                | 18.7 us: 1.01x slower                                                                                                      |
| pickle_list          | 6.79 us                                                                                                                | 6.86 us: 1.01x slower                                                                                                      |
| tomli_loads          | 2.86 sec                                                                                                               | 3.08 sec: 1.08x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (2): unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json | results/bm-20251126-3.15.0a2+-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.6 ms                                                                                                                | 15.7 ms: 1.05x faster                                                                                                      |
| django_template | 48.7 ms                                                                                                                | 54.1 ms: 1.11x slower                                                                                                      |
| genshi_text     | 31.7 ms                                                                                                                | 41.3 ms: 1.30x slower                                                                                                      |
| genshi_xml      | 71.7 ms                                                                                                                | 121 ms: 1.69x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.23x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                  | results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json | results/bm-20251126-3.15.0a2+-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| logging_silent             | 156 ns                                                                                                                 | 137 ns: 1.14x faster                                                                                                       |
| unpickle_pure_python       | 312 us                                                                                                                 | 287 us: 1.09x faster                                                                                                       |
| scimark_fft                | 473 ms                                                                                                                 | 444 ms: 1.07x faster                                                                                                       |
| float                      | 111 ms                                                                                                                 | 105 ms: 1.06x faster                                                                                                       |
| mako                       | 16.6 ms                                                                                                                | 15.7 ms: 1.05x faster                                                                                                      |
| xml_etree_generate         | 129 ms                                                                                                                 | 124 ms: 1.04x faster                                                                                                       |
| async_tree_cpu_io_mixed_tg | 845 ms                                                                                                                 | 820 ms: 1.03x faster                                                                                                       |
| xml_etree_process          | 95.2 ms                                                                                                                | 92.5 ms: 1.03x faster                                                                                                      |
| spectral_norm              | 147 ms                                                                                                                 | 143 ms: 1.03x faster                                                                                                       |
| sqlite_synth               | 4.57 us                                                                                                                | 4.48 us: 1.02x faster                                                                                                      |
| json_dumps                 | 13.8 ms                                                                                                                | 13.5 ms: 1.02x faster                                                                                                      |
| regex_v8                   | 35.9 ms                                                                                                                | 35.3 ms: 1.02x faster                                                                                                      |
| xml_etree_parse            | 226 ms                                                                                                                 | 223 ms: 1.01x faster                                                                                                       |
| regex_dna                  | 268 ms                                                                                                                 | 265 ms: 1.01x faster                                                                                                       |
| regex_effbot               | 4.44 ms                                                                                                                | 4.39 ms: 1.01x faster                                                                                                      |
| json                       | 6.66 ms                                                                                                                | 6.59 ms: 1.01x faster                                                                                                      |
| coverage                   | 121 ms                                                                                                                 | 120 ms: 1.01x faster                                                                                                       |
| scimark_sparse_mat_mult    | 7.71 ms                                                                                                                | 7.65 ms: 1.01x faster                                                                                                      |
| json_loads                 | 38.1 us                                                                                                                | 37.9 us: 1.01x faster                                                                                                      |
| deepcopy_memo              | 40.0 us                                                                                                                | 39.8 us: 1.00x faster                                                                                                      |
| nbody                      | 154 ms                                                                                                                 | 153 ms: 1.00x faster                                                                                                       |
| unpickle                   | 21.5 us                                                                                                                | 21.5 us: 1.00x faster                                                                                                      |
| pidigits                   | 324 ms                                                                                                                 | 324 ms: 1.00x slower                                                                                                       |
| asyncio_websockets         | 816 ms                                                                                                                 | 819 ms: 1.00x slower                                                                                                       |
| pickle_pure_python         | 443 us                                                                                                                 | 446 us: 1.01x slower                                                                                                       |
| scimark_lu                 | 166 ms                                                                                                                 | 167 ms: 1.01x slower                                                                                                       |
| gc_traversal               | 13.1 ms                                                                                                                | 13.2 ms: 1.01x slower                                                                                                      |
| create_gc_cycles           | 7.61 ms                                                                                                                | 7.67 ms: 1.01x slower                                                                                                      |
| xml_etree_iterparse        | 180 ms                                                                                                                 | 181 ms: 1.01x slower                                                                                                       |
| pickle                     | 18.5 us                                                                                                                | 18.7 us: 1.01x slower                                                                                                      |
| pickle_list                | 6.79 us                                                                                                                | 6.86 us: 1.01x slower                                                                                                      |
| bpe_tokeniser              | 6.72 sec                                                                                                               | 6.79 sec: 1.01x slower                                                                                                     |
| scimark_sor                | 170 ms                                                                                                                 | 173 ms: 1.01x slower                                                                                                       |
| coroutines                 | 36.9 ms                                                                                                                | 37.5 ms: 1.02x slower                                                                                                      |
| telco                      | 189 ms                                                                                                                 | 192 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl            | 2.81 sec                                                                                                               | 2.87 sec: 1.02x slower                                                                                                     |
| 2to3                       | 375 ms                                                                                                                 | 384 ms: 1.03x slower                                                                                                       |
| pyflate                    | 670 ms                                                                                                                 | 687 ms: 1.03x slower                                                                                                       |
| asyncio_tcp                | 669 ms                                                                                                                 | 687 ms: 1.03x slower                                                                                                       |
| generators                 | 45.0 ms                                                                                                                | 46.3 ms: 1.03x slower                                                                                                      |
| logging_format             | 8.78 us                                                                                                                | 9.07 us: 1.03x slower                                                                                                      |
| bench_thread_pool          | 1.13 ms                                                                                                                | 1.17 ms: 1.03x slower                                                                                                      |
| logging_simple             | 7.90 us                                                                                                                | 8.19 us: 1.04x slower                                                                                                      |
| pathlib                    | 21.3 ms                                                                                                                | 22.1 ms: 1.04x slower                                                                                                      |
| meteor_contest             | 133 ms                                                                                                                 | 140 ms: 1.05x slower                                                                                                       |
| deltablue                  | 4.76 ms                                                                                                                | 5.00 ms: 1.05x slower                                                                                                      |
| richards_super             | 71.3 ms                                                                                                                | 75.5 ms: 1.06x slower                                                                                                      |
| richards                   | 63.4 ms                                                                                                                | 68.2 ms: 1.08x slower                                                                                                      |
| tomli_loads                | 2.86 sec                                                                                                               | 3.08 sec: 1.08x slower                                                                                                     |
| deepcopy_reduce            | 4.00 us                                                                                                                | 4.32 us: 1.08x slower                                                                                                      |
| crypto_pyaes               | 101 ms                                                                                                                 | 109 ms: 1.08x slower                                                                                                       |
| async_generators           | 576 ms                                                                                                                 | 623 ms: 1.08x slower                                                                                                       |
| fannkuch                   | 574 ms                                                                                                                 | 625 ms: 1.09x slower                                                                                                       |
| typing_runtime_protocols   | 227 us                                                                                                                 | 247 us: 1.09x slower                                                                                                       |
| sqlglot_v2_optimize        | 72.4 ms                                                                                                                | 79.8 ms: 1.10x slower                                                                                                      |
| pylint                     | 391 ms                                                                                                                 | 432 ms: 1.10x slower                                                                                                       |
| many_optionals             | 1.27 ms                                                                                                                | 1.41 ms: 1.10x slower                                                                                                      |
| thrift                     | 1.07 ms                                                                                                                | 1.18 ms: 1.11x slower                                                                                                      |
| django_template            | 48.7 ms                                                                                                                | 54.1 ms: 1.11x slower                                                                                                      |
| sqlglot_v2_normalize       | 148 ms                                                                                                                 | 166 ms: 1.12x slower                                                                                                       |
| sqlglot_v2_transpile       | 2.09 ms                                                                                                                | 2.36 ms: 1.13x slower                                                                                                      |
| raytrace                   | 381 ms                                                                                                                 | 435 ms: 1.14x slower                                                                                                       |
| sphinx                     | 1.40 sec                                                                                                               | 1.60 sec: 1.14x slower                                                                                                     |
| sqlglot_v2_parse           | 1.63 ms                                                                                                                | 1.89 ms: 1.16x slower                                                                                                      |
| sympy_integrate            | 23.1 ms                                                                                                                | 27.2 ms: 1.18x slower                                                                                                      |
| mdp                        | 2.27 sec                                                                                                               | 2.70 sec: 1.19x slower                                                                                                     |
| sympy_sum                  | 171 ms                                                                                                                 | 203 ms: 1.19x slower                                                                                                       |
| regex_compile              | 144 ms                                                                                                                 | 178 ms: 1.23x slower                                                                                                       |
| pycparser                  | 1.61 sec                                                                                                               | 1.99 sec: 1.24x slower                                                                                                     |
| chaos                      | 80.9 ms                                                                                                                | 100 ms: 1.24x slower                                                                                                       |
| comprehensions             | 23.9 us                                                                                                                | 30.0 us: 1.26x slower                                                                                                      |
| sympy_str                  | 319 ms                                                                                                                 | 401 ms: 1.26x slower                                                                                                       |
| sympy_expand               | 548 ms                                                                                                                 | 690 ms: 1.26x slower                                                                                                       |
| nqueens                    | 119 ms                                                                                                                 | 152 ms: 1.28x slower                                                                                                       |
| deepcopy                   | 365 us                                                                                                                 | 474 us: 1.30x slower                                                                                                       |
| genshi_text                | 31.7 ms                                                                                                                | 41.3 ms: 1.30x slower                                                                                                      |
| pprint_safe_repr           | 1.04 sec                                                                                                               | 1.41 sec: 1.35x slower                                                                                                     |
| hexiom                     | 8.44 ms                                                                                                                | 11.6 ms: 1.37x slower                                                                                                      |
| pprint_pformat             | 2.10 sec                                                                                                               | 2.90 sec: 1.38x slower                                                                                                     |
| dulwich_log                | 60.1 ms                                                                                                                | 84.6 ms: 1.41x slower                                                                                                      |
| html5lib                   | 74.2 ms                                                                                                                | 105 ms: 1.42x slower                                                                                                       |
| go                         | 156 ms                                                                                                                 | 229 ms: 1.47x slower                                                                                                       |
| unpack_sequence            | 62.8 ns                                                                                                                | 101 ns: 1.61x slower                                                                                                       |
| genshi_xml                 | 71.7 ms                                                                                                                | 121 ms: 1.69x slower                                                                                                       |
| bench_mp_pool              | 133 ms                                                                                                                 | 280 ms: 2.10x slower                                                                                                       |
| Geometric mean             | (ref)                                                                                                                  | 1.08x slower                                                                                                               |

Benchmark hidden because not significant (13): async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_none, python_startup, unpickle_list, python_startup_no_site, async_tree_memoization, scimark_monte_carlo, pickle_dict, async_tree_io, async_tree_memoization_tg, subparsers, async_tree_io_tg
Ignored benchmarks (1) of results/bm-20251126-3.15.0a2+-bc9e63d/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2+-bc9e63d.json: docutils

- Geometric mean (including insignificant results): 1.074x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x

# Memory
- memory change: 1.02x