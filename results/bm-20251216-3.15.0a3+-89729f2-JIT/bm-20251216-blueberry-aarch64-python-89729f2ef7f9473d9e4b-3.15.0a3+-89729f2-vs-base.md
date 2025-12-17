# Results vs. base

- fork: python
- ref: 89729f2ef7f9473d9e4b
- machine: linux-aarch64
- commit hash: 89729f2
- commit date: 2025-12-17
- overall geometric mean: 1.009x faster
- HPT reliability: 65.29%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 430 ms                                                                                                                 | 435 ms: 1.01x slower                                                                                                       |
| docutils       | 4.38 sec                                                                                                               | 5.00 sec: 1.14x slower                                                                                                     |
| html5lib       | 81.1 ms                                                                                                                | 94.0 ms: 1.16x slower                                                                                                      |
| sphinx         | 1.56 sec                                                                                                               | 1.64 sec: 1.05x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp                | 1.15 sec                                                                                                               | 1.09 sec: 1.06x faster                                                                                                     |
| asyncio_websockets         | 906 ms                                                                                                                 | 922 ms: 1.02x slower                                                                                                       |
| async_tree_io              | 1.24 sec                                                                                                               | 1.28 sec: 1.03x slower                                                                                                     |
| asyncio_tcp_ssl            | 4.17 sec                                                                                                               | 4.30 sec: 1.03x slower                                                                                                     |
| async_tree_cpu_io_mixed_tg | 952 ms                                                                                                                 | 986 ms: 1.04x slower                                                                                                       |
| async_tree_cpu_io_mixed    | 974 ms                                                                                                                 | 1.01 sec: 1.04x slower                                                                                                     |
| async_tree_none            | 513 ms                                                                                                                 | 537 ms: 1.05x slower                                                                                                       |
| async_tree_memoization     | 712 ms                                                                                                                 | 748 ms: 1.05x slower                                                                                                       |
| async_tree_memoization_tg  | 663 ms                                                                                                                 | 709 ms: 1.07x slower                                                                                                       |
| async_tree_io_tg           | 1.24 sec                                                                                                               | 1.34 sec: 1.08x slower                                                                                                     |
| async_generators           | 588 ms                                                                                                                 | 645 ms: 1.10x slower                                                                                                       |
| Geometric mean             | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (2): coroutines, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 179 ms                                                                                                                 | 149 ms: 1.21x faster                                                                                                       |
| float          | 132 ms                                                                                                                 | 119 ms: 1.12x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.11x faster                                                                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 38.3 ms                                                                                                                | 36.6 ms: 1.05x faster                                                                                                      |
| regex_dna      | 299 ms                                                                                                                 | 294 ms: 1.02x faster                                                                                                       |
| regex_effbot   | 4.71 ms                                                                                                                | 4.64 ms: 1.02x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 341 us                                                                                                                 | 266 us: 1.28x faster                                                                                                       |
| pickle_pure_python   | 475 us                                                                                                                 | 412 us: 1.15x faster                                                                                                       |
| xml_etree_generate   | 146 ms                                                                                                                 | 129 ms: 1.12x faster                                                                                                       |
| tomli_loads          | 3.55 sec                                                                                                               | 3.19 sec: 1.11x faster                                                                                                     |
| xml_etree_process    | 104 ms                                                                                                                 | 99.3 ms: 1.05x faster                                                                                                      |
| json_dumps           | 14.9 ms                                                                                                                | 14.3 ms: 1.05x faster                                                                                                      |
| unpickle_list        | 8.95 us                                                                                                                | 8.57 us: 1.04x faster                                                                                                      |
| xml_etree_parse      | 261 ms                                                                                                                 | 251 ms: 1.04x faster                                                                                                       |
| xml_etree_iterparse  | 208 ms                                                                                                                 | 203 ms: 1.02x faster                                                                                                       |
| pickle_list          | 7.07 us                                                                                                                | 7.18 us: 1.01x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.06x faster                                                                                                               |

Benchmark hidden because not significant (4): json_loads, unpickle, pickle_dict, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 11.0 ms                                                                                                                | 10.8 ms: 1.01x faster                                                                                                      |
| python_startup         | 18.6 ms                                                                                                                | 18.4 ms: 1.01x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.8 ms                                                                                                                | 18.9 ms: 1.10x faster                                                                                                      |
| django_template | 53.1 ms                                                                                                                | 57.0 ms: 1.07x slower                                                                                                      |
| genshi_text     | 34.4 ms                                                                                                                | 40.0 ms: 1.16x slower                                                                                                      |
| genshi_xml      | 79.5 ms                                                                                                                | 106 ms: 1.33x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.11x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                  | results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json | results/bm-20251216-3.15.0a3+-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                   | 68.2 ms                                                                                                                | 39.9 ms: 1.71x faster                                                                                                      |
| richards_super             | 77.4 ms                                                                                                                | 47.3 ms: 1.63x faster                                                                                                      |
| logging_silent             | 169 ns                                                                                                                 | 131 ns: 1.29x faster                                                                                                       |
| unpickle_pure_python       | 341 us                                                                                                                 | 266 us: 1.28x faster                                                                                                       |
| nbody                      | 179 ms                                                                                                                 | 149 ms: 1.21x faster                                                                                                       |
| scimark_monte_carlo        | 108 ms                                                                                                                 | 91.1 ms: 1.18x faster                                                                                                      |
| deltablue                  | 5.31 ms                                                                                                                | 4.59 ms: 1.16x faster                                                                                                      |
| scimark_fft                | 525 ms                                                                                                                 | 454 ms: 1.16x faster                                                                                                       |
| pickle_pure_python         | 475 us                                                                                                                 | 412 us: 1.15x faster                                                                                                       |
| scimark_sor                | 184 ms                                                                                                                 | 159 ms: 1.15x faster                                                                                                       |
| spectral_norm              | 166 ms                                                                                                                 | 146 ms: 1.13x faster                                                                                                       |
| xml_etree_generate         | 146 ms                                                                                                                 | 129 ms: 1.12x faster                                                                                                       |
| pyflate                    | 783 ms                                                                                                                 | 698 ms: 1.12x faster                                                                                                       |
| float                      | 132 ms                                                                                                                 | 119 ms: 1.12x faster                                                                                                       |
| tomli_loads                | 3.55 sec                                                                                                               | 3.19 sec: 1.11x faster                                                                                                     |
| deepcopy_memo              | 42.6 us                                                                                                                | 38.6 us: 1.10x faster                                                                                                      |
| mako                       | 20.8 ms                                                                                                                | 18.9 ms: 1.10x faster                                                                                                      |
| asyncio_tcp                | 1.15 sec                                                                                                               | 1.09 sec: 1.06x faster                                                                                                     |
| raytrace                   | 435 ms                                                                                                                 | 410 ms: 1.06x faster                                                                                                       |
| xml_etree_process          | 104 ms                                                                                                                 | 99.3 ms: 1.05x faster                                                                                                      |
| regex_v8                   | 38.3 ms                                                                                                                | 36.6 ms: 1.05x faster                                                                                                      |
| json_dumps                 | 14.9 ms                                                                                                                | 14.3 ms: 1.05x faster                                                                                                      |
| unpickle_list              | 8.95 us                                                                                                                | 8.57 us: 1.04x faster                                                                                                      |
| xml_etree_parse            | 261 ms                                                                                                                 | 251 ms: 1.04x faster                                                                                                       |
| sqlite_synth               | 4.83 us                                                                                                                | 4.65 us: 1.04x faster                                                                                                      |
| bpe_tokeniser              | 7.64 sec                                                                                                               | 7.37 sec: 1.04x faster                                                                                                     |
| coverage                   | 137 ms                                                                                                                 | 133 ms: 1.03x faster                                                                                                       |
| go                         | 169 ms                                                                                                                 | 164 ms: 1.03x faster                                                                                                       |
| xml_etree_iterparse        | 208 ms                                                                                                                 | 203 ms: 1.02x faster                                                                                                       |
| scimark_lu                 | 179 ms                                                                                                                 | 175 ms: 1.02x faster                                                                                                       |
| shortest_path              | 907 ms                                                                                                                 | 890 ms: 1.02x faster                                                                                                       |
| regex_dna                  | 299 ms                                                                                                                 | 294 ms: 1.02x faster                                                                                                       |
| connected_components       | 855 ms                                                                                                                 | 840 ms: 1.02x faster                                                                                                       |
| regex_effbot               | 4.71 ms                                                                                                                | 4.64 ms: 1.02x faster                                                                                                      |
| python_startup_no_site     | 11.0 ms                                                                                                                | 10.8 ms: 1.01x faster                                                                                                      |
| python_startup             | 18.6 ms                                                                                                                | 18.4 ms: 1.01x faster                                                                                                      |
| k_core                     | 4.08 sec                                                                                                               | 4.06 sec: 1.00x faster                                                                                                     |
| 2to3                       | 430 ms                                                                                                                 | 435 ms: 1.01x slower                                                                                                       |
| pickle_list                | 7.07 us                                                                                                                | 7.18 us: 1.01x slower                                                                                                      |
| pathlib                    | 22.8 ms                                                                                                                | 23.2 ms: 1.02x slower                                                                                                      |
| asyncio_websockets         | 906 ms                                                                                                                 | 922 ms: 1.02x slower                                                                                                       |
| generators                 | 51.1 ms                                                                                                                | 52.3 ms: 1.02x slower                                                                                                      |
| logging_simple             | 8.65 us                                                                                                                | 8.86 us: 1.02x slower                                                                                                      |
| subparsers                 | 14.9 ms                                                                                                                | 15.4 ms: 1.03x slower                                                                                                      |
| async_tree_io              | 1.24 sec                                                                                                               | 1.28 sec: 1.03x slower                                                                                                     |
| asyncio_tcp_ssl            | 4.17 sec                                                                                                               | 4.30 sec: 1.03x slower                                                                                                     |
| fannkuch                   | 629 ms                                                                                                                 | 649 ms: 1.03x slower                                                                                                       |
| async_tree_cpu_io_mixed_tg | 952 ms                                                                                                                 | 986 ms: 1.04x slower                                                                                                       |
| sqlalchemy_imperative      | 22.3 ms                                                                                                                | 23.1 ms: 1.04x slower                                                                                                      |
| sqlglot_v2_optimize        | 79.2 ms                                                                                                                | 82.2 ms: 1.04x slower                                                                                                      |
| comprehensions             | 26.2 us                                                                                                                | 27.2 us: 1.04x slower                                                                                                      |
| async_tree_cpu_io_mixed    | 974 ms                                                                                                                 | 1.01 sec: 1.04x slower                                                                                                     |
| pprint_pformat             | 2.31 sec                                                                                                               | 2.41 sec: 1.04x slower                                                                                                     |
| sqlglot_v2_normalize       | 161 ms                                                                                                                 | 168 ms: 1.05x slower                                                                                                       |
| sphinx                     | 1.56 sec                                                                                                               | 1.64 sec: 1.05x slower                                                                                                     |
| bench_thread_pool          | 1.30 ms                                                                                                                | 1.36 ms: 1.05x slower                                                                                                      |
| async_tree_none            | 513 ms                                                                                                                 | 537 ms: 1.05x slower                                                                                                       |
| async_tree_memoization     | 712 ms                                                                                                                 | 748 ms: 1.05x slower                                                                                                       |
| xdsl_constant_fold         | 58.9 ms                                                                                                                | 62.2 ms: 1.06x slower                                                                                                      |
| typing_runtime_protocols   | 243 us                                                                                                                 | 257 us: 1.06x slower                                                                                                       |
| pprint_safe_repr           | 1.09 sec                                                                                                               | 1.16 sec: 1.07x slower                                                                                                     |
| async_tree_memoization_tg  | 663 ms                                                                                                                 | 709 ms: 1.07x slower                                                                                                       |
| deepcopy_reduce            | 4.26 us                                                                                                                | 4.56 us: 1.07x slower                                                                                                      |
| pylint                     | 433 ms                                                                                                                 | 463 ms: 1.07x slower                                                                                                       |
| django_template            | 53.1 ms                                                                                                                | 57.0 ms: 1.07x slower                                                                                                      |
| pycparser                  | 1.59 sec                                                                                                               | 1.71 sec: 1.07x slower                                                                                                     |
| async_tree_io_tg           | 1.24 sec                                                                                                               | 1.34 sec: 1.08x slower                                                                                                     |
| many_optionals             | 931 us                                                                                                                 | 1.01 ms: 1.08x slower                                                                                                      |
| deepcopy                   | 392 us                                                                                                                 | 431 us: 1.10x slower                                                                                                       |
| async_generators           | 588 ms                                                                                                                 | 645 ms: 1.10x slower                                                                                                       |
| hexiom                     | 9.27 ms                                                                                                                | 10.2 ms: 1.10x slower                                                                                                      |
| mdp                        | 2.53 sec                                                                                                               | 2.87 sec: 1.13x slower                                                                                                     |
| docutils                   | 4.38 sec                                                                                                               | 5.00 sec: 1.14x slower                                                                                                     |
| html5lib                   | 81.1 ms                                                                                                                | 94.0 ms: 1.16x slower                                                                                                      |
| genshi_text                | 34.4 ms                                                                                                                | 40.0 ms: 1.16x slower                                                                                                      |
| nqueens                    | 123 ms                                                                                                                 | 145 ms: 1.18x slower                                                                                                       |
| unpack_sequence            | 71.4 ns                                                                                                                | 85.2 ns: 1.19x slower                                                                                                      |
| dulwich_log                | 65.3 ms                                                                                                                | 82.3 ms: 1.26x slower                                                                                                      |
| bench_mp_pool              | 200 ms                                                                                                                 | 260 ms: 1.30x slower                                                                                                       |
| genshi_xml                 | 79.5 ms                                                                                                                | 106 ms: 1.33x slower                                                                                                       |
| Geometric mean             | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (23): sqlglot_v2_parse, meteor_contest, sqlglot_v2_transpile, json_loads, unpickle, crypto_pyaes, sqlalchemy_declarative, pidigits, telco, chaos, logging_format, pickle_dict, json, gc_traversal, thrift, chameleon, pickle, regex_compile, create_gc_cycles, tornado_http, scimark_sparse_mat_mult, coroutines, async_tree_none_tg
Ignored benchmarks (4) of results/bm-20251216-3.15.0a3+-89729f2/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3+-89729f2.json: sympy_expand, sympy_integrate, sympy_str, sympy_sum

- Geometric mean (including insignificant results): 1.009x faster

# HPT report

- Reliability score: 65.29% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x