# Results vs. base

- fork: python
- ref: b6b0e14b3d4aa9e9b89b
- machine: linux-aarch64
- commit hash: b6b0e14
- commit date: 2025-12-29
- overall geometric mean: 1.001x faster
- HPT reliability: 90.34%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 20.1 ms                                                                                                                | 20.5 ms: 1.02x slower                                                                                                      |
| docutils       | 4.19 sec                                                                                                               | 4.72 sec: 1.13x slower                                                                                                     |
| html5lib       | 76.9 ms                                                                                                                | 89.0 ms: 1.16x slower                                                                                                      |
| sphinx         | 1.47 sec                                                                                                               | 1.58 sec: 1.08x slower                                                                                                     |
| tornado_http   | 162 ms                                                                                                                 | 165 ms: 1.02x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.07x slower                                                                                                               |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg        | 535 ms                                                                                                                 | 513 ms: 1.04x faster                                                                                                       |
| asyncio_tcp_ssl           | 4.28 sec                                                                                                               | 4.32 sec: 1.01x slower                                                                                                     |
| async_tree_io_tg          | 1.23 sec                                                                                                               | 1.26 sec: 1.02x slower                                                                                                     |
| async_generators          | 576 ms                                                                                                                 | 598 ms: 1.04x slower                                                                                                       |
| async_tree_memoization_tg | 642 ms                                                                                                                 | 669 ms: 1.04x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (8): coroutines, asyncio_tcp, async_tree_cpu_io_mixed_tg, async_tree_none, asyncio_websockets, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 158 ms                                                                                                                 | 133 ms: 1.19x faster                                                                                                       |
| float          | 127 ms                                                                                                                 | 117 ms: 1.09x faster                                                                                                       |
| pidigits       | 327 ms                                                                                                                 | 324 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.09x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 36.1 ms                                                                                                                | 35.9 ms: 1.00x faster                                                                                                      |
| regex_dna      | 277 ms                                                                                                                 | 281 ms: 1.01x slower                                                                                                       |
| regex_effbot   | 4.39 ms                                                                                                                | 4.51 ms: 1.03x slower                                                                                                      |
| regex_compile  | 143 ms                                                                                                                 | 150 ms: 1.05x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 318 us                                                                                                                 | 243 us: 1.31x faster                                                                                                       |
| pickle_pure_python   | 445 us                                                                                                                 | 388 us: 1.15x faster                                                                                                       |
| tomli_loads          | 3.24 sec                                                                                                               | 3.04 sec: 1.07x faster                                                                                                     |
| xml_etree_generate   | 129 ms                                                                                                                 | 121 ms: 1.07x faster                                                                                                       |
| xml_etree_process    | 98.4 ms                                                                                                                | 92.9 ms: 1.06x faster                                                                                                      |
| json_dumps           | 14.0 ms                                                                                                                | 13.5 ms: 1.04x faster                                                                                                      |
| pickle_list          | 6.84 us                                                                                                                | 6.74 us: 1.01x faster                                                                                                      |
| unpickle             | 22.4 us                                                                                                                | 22.3 us: 1.00x faster                                                                                                      |
| pickle_dict          | 46.8 us                                                                                                                | 47.0 us: 1.00x slower                                                                                                      |
| xml_etree_parse      | 245 ms                                                                                                                 | 249 ms: 1.02x slower                                                                                                       |
| unpickle_list        | 7.99 us                                                                                                                | 8.11 us: 1.02x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmark hidden because not significant (3): pickle, xml_etree_iterparse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup | 17.4 ms                                                                                                                | 17.4 ms: 1.00x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.8 ms                                                                                                                | 18.0 ms: 1.10x faster                                                                                                      |
| django_template | 51.1 ms                                                                                                                | 54.8 ms: 1.07x slower                                                                                                      |
| genshi_text     | 32.1 ms                                                                                                                | 35.8 ms: 1.12x slower                                                                                                      |
| genshi_xml      | 76.1 ms                                                                                                                | 93.2 ms: 1.22x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.08x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251229-3.15.0a3+-b6b0e14/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json | results/bm-20251229-3.15.0a3+-b6b0e14-JIT/bm-20251229-blueberry-aarch64-python-b6b0e14b3d4aa9e9b89b-3.15.0a3+-b6b0e14.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 62.4 ms                                                                                                                | 38.5 ms: 1.62x faster                                                                                                      |
| richards_super            | 70.9 ms                                                                                                                | 46.1 ms: 1.54x faster                                                                                                      |
| logging_silent            | 160 ns                                                                                                                 | 119 ns: 1.35x faster                                                                                                       |
| unpickle_pure_python      | 318 us                                                                                                                 | 243 us: 1.31x faster                                                                                                       |
| nbody                     | 158 ms                                                                                                                 | 133 ms: 1.19x faster                                                                                                       |
| deltablue                 | 5.04 ms                                                                                                                | 4.32 ms: 1.17x faster                                                                                                      |
| pickle_pure_python        | 445 us                                                                                                                 | 388 us: 1.15x faster                                                                                                       |
| scimark_monte_carlo       | 97.1 ms                                                                                                                | 85.4 ms: 1.14x faster                                                                                                      |
| scimark_fft               | 472 ms                                                                                                                 | 424 ms: 1.11x faster                                                                                                       |
| deepcopy_memo             | 40.3 us                                                                                                                | 36.3 us: 1.11x faster                                                                                                      |
| pyflate                   | 733 ms                                                                                                                 | 663 ms: 1.11x faster                                                                                                       |
| scimark_sor               | 168 ms                                                                                                                 | 152 ms: 1.10x faster                                                                                                       |
| spectral_norm             | 149 ms                                                                                                                 | 136 ms: 1.10x faster                                                                                                       |
| mako                      | 19.8 ms                                                                                                                | 18.0 ms: 1.10x faster                                                                                                      |
| float                     | 127 ms                                                                                                                 | 117 ms: 1.09x faster                                                                                                       |
| scimark_lu                | 164 ms                                                                                                                 | 152 ms: 1.08x faster                                                                                                       |
| fannkuch                  | 589 ms                                                                                                                 | 549 ms: 1.07x faster                                                                                                       |
| tomli_loads               | 3.24 sec                                                                                                               | 3.04 sec: 1.07x faster                                                                                                     |
| xml_etree_generate        | 129 ms                                                                                                                 | 121 ms: 1.07x faster                                                                                                       |
| xml_etree_process         | 98.4 ms                                                                                                                | 92.9 ms: 1.06x faster                                                                                                      |
| bpe_tokeniser             | 7.11 sec                                                                                                               | 6.74 sec: 1.05x faster                                                                                                     |
| async_tree_none_tg        | 535 ms                                                                                                                 | 513 ms: 1.04x faster                                                                                                       |
| go                        | 157 ms                                                                                                                 | 151 ms: 1.04x faster                                                                                                       |
| meteor_contest            | 138 ms                                                                                                                 | 133 ms: 1.04x faster                                                                                                       |
| json_dumps                | 14.0 ms                                                                                                                | 13.5 ms: 1.04x faster                                                                                                      |
| connected_components      | 844 ms                                                                                                                 | 825 ms: 1.02x faster                                                                                                       |
| crypto_pyaes              | 104 ms                                                                                                                 | 102 ms: 1.02x faster                                                                                                       |
| json                      | 6.75 ms                                                                                                                | 6.62 ms: 1.02x faster                                                                                                      |
| create_gc_cycles          | 9.06 ms                                                                                                                | 8.92 ms: 1.01x faster                                                                                                      |
| pickle_list               | 6.84 us                                                                                                                | 6.74 us: 1.01x faster                                                                                                      |
| k_core                    | 4.08 sec                                                                                                               | 4.03 sec: 1.01x faster                                                                                                     |
| pathlib                   | 22.1 ms                                                                                                                | 21.9 ms: 1.01x faster                                                                                                      |
| pidigits                  | 327 ms                                                                                                                 | 324 ms: 1.01x faster                                                                                                       |
| sqlite_synth              | 4.49 us                                                                                                                | 4.46 us: 1.01x faster                                                                                                      |
| shortest_path             | 885 ms                                                                                                                 | 879 ms: 1.01x faster                                                                                                       |
| unpickle                  | 22.4 us                                                                                                                | 22.3 us: 1.00x faster                                                                                                      |
| regex_v8                  | 36.1 ms                                                                                                                | 35.9 ms: 1.00x faster                                                                                                      |
| python_startup            | 17.4 ms                                                                                                                | 17.4 ms: 1.00x faster                                                                                                      |
| pickle_dict               | 46.8 us                                                                                                                | 47.0 us: 1.00x slower                                                                                                      |
| thrift                    | 1.12 ms                                                                                                                | 1.13 ms: 1.01x slower                                                                                                      |
| asyncio_tcp_ssl           | 4.28 sec                                                                                                               | 4.32 sec: 1.01x slower                                                                                                     |
| coverage                  | 125 ms                                                                                                                 | 127 ms: 1.01x slower                                                                                                       |
| regex_dna                 | 277 ms                                                                                                                 | 281 ms: 1.01x slower                                                                                                       |
| telco                     | 189 ms                                                                                                                 | 192 ms: 1.02x slower                                                                                                       |
| xml_etree_parse           | 245 ms                                                                                                                 | 249 ms: 1.02x slower                                                                                                       |
| unpickle_list             | 7.99 us                                                                                                                | 8.11 us: 1.02x slower                                                                                                      |
| generators                | 47.4 ms                                                                                                                | 48.1 ms: 1.02x slower                                                                                                      |
| comprehensions            | 25.0 us                                                                                                                | 25.4 us: 1.02x slower                                                                                                      |
| async_tree_io_tg          | 1.23 sec                                                                                                               | 1.26 sec: 1.02x slower                                                                                                     |
| tornado_http              | 162 ms                                                                                                                 | 165 ms: 1.02x slower                                                                                                       |
| raytrace                  | 386 ms                                                                                                                 | 393 ms: 1.02x slower                                                                                                       |
| chameleon                 | 20.1 ms                                                                                                                | 20.5 ms: 1.02x slower                                                                                                      |
| sqlglot_v2_parse          | 1.64 ms                                                                                                                | 1.68 ms: 1.02x slower                                                                                                      |
| deepcopy_reduce           | 4.11 us                                                                                                                | 4.22 us: 1.03x slower                                                                                                      |
| regex_effbot              | 4.39 ms                                                                                                                | 4.51 ms: 1.03x slower                                                                                                      |
| logging_format            | 8.67 us                                                                                                                | 8.91 us: 1.03x slower                                                                                                      |
| logging_simple            | 7.91 us                                                                                                                | 8.16 us: 1.03x slower                                                                                                      |
| async_generators          | 576 ms                                                                                                                 | 598 ms: 1.04x slower                                                                                                       |
| typing_runtime_protocols  | 225 us                                                                                                                 | 234 us: 1.04x slower                                                                                                       |
| async_tree_memoization_tg | 642 ms                                                                                                                 | 669 ms: 1.04x slower                                                                                                       |
| sqlalchemy_declarative    | 154 ms                                                                                                                 | 161 ms: 1.04x slower                                                                                                       |
| regex_compile             | 143 ms                                                                                                                 | 150 ms: 1.05x slower                                                                                                       |
| xdsl_constant_fold        | 55.4 ms                                                                                                                | 59.2 ms: 1.07x slower                                                                                                      |
| many_optionals            | 946 us                                                                                                                 | 1.01 ms: 1.07x slower                                                                                                      |
| django_template           | 51.1 ms                                                                                                                | 54.8 ms: 1.07x slower                                                                                                      |
| sqlalchemy_imperative     | 20.3 ms                                                                                                                | 21.8 ms: 1.07x slower                                                                                                      |
| sphinx                    | 1.47 sec                                                                                                               | 1.58 sec: 1.08x slower                                                                                                     |
| sqlglot_v2_optimize       | 71.9 ms                                                                                                                | 77.5 ms: 1.08x slower                                                                                                      |
| pylint                    | 411 ms                                                                                                                 | 443 ms: 1.08x slower                                                                                                       |
| sympy_integrate           | 23.0 ms                                                                                                                | 24.8 ms: 1.08x slower                                                                                                      |
| pprint_safe_repr          | 1.01 sec                                                                                                               | 1.09 sec: 1.08x slower                                                                                                     |
| chaos                     | 83.8 ms                                                                                                                | 90.9 ms: 1.08x slower                                                                                                      |
| hexiom                    | 8.39 ms                                                                                                                | 9.10 ms: 1.08x slower                                                                                                      |
| pprint_pformat            | 2.07 sec                                                                                                               | 2.25 sec: 1.09x slower                                                                                                     |
| sqlglot_v2_normalize      | 148 ms                                                                                                                 | 161 ms: 1.09x slower                                                                                                       |
| pycparser                 | 1.48 sec                                                                                                               | 1.64 sec: 1.11x slower                                                                                                     |
| deepcopy                  | 371 us                                                                                                                 | 410 us: 1.11x slower                                                                                                       |
| sympy_sum                 | 171 ms                                                                                                                 | 191 ms: 1.11x slower                                                                                                       |
| genshi_text               | 32.1 ms                                                                                                                | 35.8 ms: 1.12x slower                                                                                                      |
| docutils                  | 4.19 sec                                                                                                               | 4.72 sec: 1.13x slower                                                                                                     |
| sympy_str                 | 319 ms                                                                                                                 | 366 ms: 1.15x slower                                                                                                       |
| mdp                       | 2.40 sec                                                                                                               | 2.76 sec: 1.15x slower                                                                                                     |
| html5lib                  | 76.9 ms                                                                                                                | 89.0 ms: 1.16x slower                                                                                                      |
| sympy_expand              | 549 ms                                                                                                                 | 641 ms: 1.17x slower                                                                                                       |
| nqueens                   | 118 ms                                                                                                                 | 138 ms: 1.17x slower                                                                                                       |
| dulwich_log               | 62.5 ms                                                                                                                | 74.3 ms: 1.19x slower                                                                                                      |
| genshi_xml                | 76.1 ms                                                                                                                | 93.2 ms: 1.22x slower                                                                                                      |
| unpack_sequence           | 68.3 ns                                                                                                                | 83.7 ns: 1.23x slower                                                                                                      |
| bench_mp_pool             | 174 ms                                                                                                                 | 219 ms: 1.26x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (18): coroutines, asyncio_tcp, gc_traversal, pickle, async_tree_cpu_io_mixed_tg, python_startup_no_site, scimark_sparse_mat_mult, xml_etree_iterparse, async_tree_none, 2to3, asyncio_websockets, bench_thread_pool, json_loads, subparsers, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization, sqlglot_v2_transpile

- Geometric mean (including insignificant results): 1.001x faster

# HPT report

- Reliability score: 90.34% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x