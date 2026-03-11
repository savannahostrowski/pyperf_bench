# Results vs. base

- fork: python
- ref: ebb150e76ab4988fdcd5
- machine: linux-x86_64
- commit hash: ebb150e
- commit date: 2026-03-11
- overall geometric mean: 1.049x faster
- HPT reliability: 99.91%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.01x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 19.0 ms                                                                                                            | 19.3 ms: 1.01x slower                                                                                                  |
| docutils       | 3.62 sec                                                                                                           | 3.90 sec: 1.08x slower                                                                                                 |
| html5lib       | 86.4 ms                                                                                                            | 91.6 ms: 1.06x slower                                                                                                  |
| sphinx         | 1.38 sec                                                                                                           | 1.46 sec: 1.06x slower                                                                                                 |
| tornado_http   | 191 ms                                                                                                             | 192 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.04x slower                                                                                                           |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_memoization_tg | 416 ms                                                                                                             | 400 ms: 1.04x faster                                                                                                   |
| async_tree_none           | 347 ms                                                                                                             | 335 ms: 1.03x faster                                                                                                   |
| async_tree_io             | 786 ms                                                                                                             | 771 ms: 1.02x faster                                                                                                   |
| async_tree_cpu_io_mixed   | 693 ms                                                                                                             | 685 ms: 1.01x faster                                                                                                   |
| coroutines                | 32.7 ms                                                                                                            | 33.2 ms: 1.01x slower                                                                                                  |
| async_generators          | 475 ms                                                                                                             | 502 ms: 1.06x slower                                                                                                   |
| Geometric mean            | (ref)                                                                                                              | 1.01x faster                                                                                                           |

Benchmark hidden because not significant (7): async_tree_none_tg, async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization, asyncio_tcp_ssl, asyncio_websockets, asyncio_tcp

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 132 ms                                                                                                             | 104 ms: 1.28x faster                                                                                                   |
| float          | 96.4 ms                                                                                                            | 81.3 ms: 1.19x faster                                                                                                  |
| pidigits       | 287 ms                                                                                                             | 282 ms: 1.02x faster                                                                                                   |
| Geometric mean | (ref)                                                                                                              | 1.15x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 31.8 ms                                                                                                            | 29.7 ms: 1.07x faster                                                                                                  |
| regex_dna      | 253 ms                                                                                                             | 241 ms: 1.05x faster                                                                                                   |
| regex_effbot   | 3.96 ms                                                                                                            | 3.82 ms: 1.04x faster                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|----------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| tomli_loads          | 2.61 sec                                                                                                           | 2.20 sec: 1.19x faster                                                                                                 |
| base64_small         | 403 us                                                                                                             | 340 us: 1.18x faster                                                                                                   |
| urlsafe_base64_small | 600 us                                                                                                             | 521 us: 1.15x faster                                                                                                   |
| json_dumps           | 14.1 ms                                                                                                            | 12.6 ms: 1.12x faster                                                                                                  |
| xml_etree_process    | 83.8 ms                                                                                                            | 77.0 ms: 1.09x faster                                                                                                  |
| ascii85_small        | 994 us                                                                                                             | 916 us: 1.08x faster                                                                                                   |
| xml_etree_generate   | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| unpickle_pure_python | 302 us                                                                                                             | 279 us: 1.08x faster                                                                                                   |
| base85_small         | 302 us                                                                                                             | 281 us: 1.08x faster                                                                                                   |
| pickle_dict          | 50.7 us                                                                                                            | 47.9 us: 1.06x faster                                                                                                  |
| pickle_list          | 7.31 us                                                                                                            | 7.07 us: 1.03x faster                                                                                                  |
| base32_large         | 661 ms                                                                                                             | 640 ms: 1.03x faster                                                                                                   |
| base32_small         | 12.6 ms                                                                                                            | 12.2 ms: 1.03x faster                                                                                                  |
| xml_etree_iterparse  | 124 ms                                                                                                             | 120 ms: 1.03x faster                                                                                                   |
| xml_etree_parse      | 191 ms                                                                                                             | 186 ms: 1.02x faster                                                                                                   |
| pickle               | 18.6 us                                                                                                            | 18.3 us: 1.02x faster                                                                                                  |
| base85_large         | 8.28 ms                                                                                                            | 8.28 ms: 1.00x slower                                                                                                  |
| ascii85_large        | 21.9 ms                                                                                                            | 21.9 ms: 1.00x slower                                                                                                  |
| base64_large         | 3.45 ms                                                                                                            | 3.45 ms: 1.00x slower                                                                                                  |
| pickle_pure_python   | 441 us                                                                                                             | 447 us: 1.01x slower                                                                                                   |
| unpickle             | 20.7 us                                                                                                            | 21.6 us: 1.04x slower                                                                                                  |
| base16_small         | 519 us                                                                                                             | 543 us: 1.05x slower                                                                                                   |
| base16_large         | 11.7 ms                                                                                                            | 13.2 ms: 1.13x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (2): json_loads, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.1 ms                                                                                                            | 18.2 ms: 1.00x slower                                                                                                  |
| python_startup_no_site | 10.7 ms                                                                                                            | 10.7 ms: 1.01x slower                                                                                                  |
| Geometric mean         | (ref)                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|----------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako           | 17.2 ms                                                                                                            | 15.3 ms: 1.13x faster                                                                                                  |
| Geometric mean | (ref)                                                                                                              | 1.06x faster                                                                                                           |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                 | results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json | results/bm-20260311-3.15.0a7+-ebb150e-JIT/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json |
|---------------------------|:------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| richards                  | 59.8 ms                                                                                                            | 24.8 ms: 2.41x faster                                                                                                  |
| richards_super            | 68.3 ms                                                                                                            | 30.3 ms: 2.25x faster                                                                                                  |
| scimark_lu                | 157 ms                                                                                                             | 114 ms: 1.38x faster                                                                                                   |
| nbody                     | 132 ms                                                                                                             | 104 ms: 1.28x faster                                                                                                   |
| scimark_fft               | 460 ms                                                                                                             | 367 ms: 1.25x faster                                                                                                   |
| deltablue                 | 4.75 ms                                                                                                            | 3.90 ms: 1.22x faster                                                                                                  |
| scimark_monte_carlo       | 89.3 ms                                                                                                            | 74.0 ms: 1.21x faster                                                                                                  |
| logging_silent            | 140 ns                                                                                                             | 116 ns: 1.21x faster                                                                                                   |
| scimark_sor               | 149 ms                                                                                                             | 124 ms: 1.20x faster                                                                                                   |
| tomli_loads               | 2.61 sec                                                                                                           | 2.20 sec: 1.19x faster                                                                                                 |
| float                     | 96.4 ms                                                                                                            | 81.3 ms: 1.19x faster                                                                                                  |
| base64_small              | 403 us                                                                                                             | 340 us: 1.18x faster                                                                                                   |
| deepcopy_memo             | 37.7 us                                                                                                            | 31.9 us: 1.18x faster                                                                                                  |
| spectral_norm             | 130 ms                                                                                                             | 113 ms: 1.15x faster                                                                                                   |
| urlsafe_base64_small      | 600 us                                                                                                             | 521 us: 1.15x faster                                                                                                   |
| pyflate                   | 582 ms                                                                                                             | 508 ms: 1.15x faster                                                                                                   |
| mako                      | 17.2 ms                                                                                                            | 15.3 ms: 1.13x faster                                                                                                  |
| json_dumps                | 14.1 ms                                                                                                            | 12.6 ms: 1.12x faster                                                                                                  |
| pprint_pformat            | 2.10 sec                                                                                                           | 1.89 sec: 1.11x faster                                                                                                 |
| fannkuch                  | 541 ms                                                                                                             | 488 ms: 1.11x faster                                                                                                   |
| scimark_sparse_mat_mult   | 6.56 ms                                                                                                            | 5.96 ms: 1.10x faster                                                                                                  |
| pprint_safe_repr          | 1.03 sec                                                                                                           | 941 ms: 1.09x faster                                                                                                   |
| xml_etree_process         | 83.8 ms                                                                                                            | 77.0 ms: 1.09x faster                                                                                                  |
| ascii85_small             | 994 us                                                                                                             | 916 us: 1.08x faster                                                                                                   |
| xml_etree_generate        | 119 ms                                                                                                             | 110 ms: 1.08x faster                                                                                                   |
| unpickle_pure_python      | 302 us                                                                                                             | 279 us: 1.08x faster                                                                                                   |
| comprehensions            | 23.2 us                                                                                                            | 21.4 us: 1.08x faster                                                                                                  |
| base85_small              | 302 us                                                                                                             | 281 us: 1.08x faster                                                                                                   |
| regex_v8                  | 31.8 ms                                                                                                            | 29.7 ms: 1.07x faster                                                                                                  |
| pickle_dict               | 50.7 us                                                                                                            | 47.9 us: 1.06x faster                                                                                                  |
| json                      | 7.45 ms                                                                                                            | 7.06 ms: 1.05x faster                                                                                                  |
| regex_dna                 | 253 ms                                                                                                             | 241 ms: 1.05x faster                                                                                                   |
| nqueens                   | 108 ms                                                                                                             | 103 ms: 1.05x faster                                                                                                   |
| crypto_pyaes              | 97.9 ms                                                                                                            | 93.2 ms: 1.05x faster                                                                                                  |
| bpe_tokeniser             | 5.89 sec                                                                                                           | 5.64 sec: 1.04x faster                                                                                                 |
| async_tree_memoization_tg | 416 ms                                                                                                             | 400 ms: 1.04x faster                                                                                                   |
| connected_components      | 459 ms                                                                                                             | 442 ms: 1.04x faster                                                                                                   |
| subparsers                | 13.2 ms                                                                                                            | 12.8 ms: 1.04x faster                                                                                                  |
| regex_effbot              | 3.96 ms                                                                                                            | 3.82 ms: 1.04x faster                                                                                                  |
| pickle_list               | 7.31 us                                                                                                            | 7.07 us: 1.03x faster                                                                                                  |
| async_tree_none           | 347 ms                                                                                                             | 335 ms: 1.03x faster                                                                                                   |
| base32_large              | 661 ms                                                                                                             | 640 ms: 1.03x faster                                                                                                   |
| deepcopy_reduce           | 3.68 us                                                                                                            | 3.56 us: 1.03x faster                                                                                                  |
| base32_small              | 12.6 ms                                                                                                            | 12.2 ms: 1.03x faster                                                                                                  |
| xml_etree_iterparse       | 124 ms                                                                                                             | 120 ms: 1.03x faster                                                                                                   |
| sqlglot_v2_parse          | 1.72 ms                                                                                                            | 1.67 ms: 1.03x faster                                                                                                  |
| xml_etree_parse           | 191 ms                                                                                                             | 186 ms: 1.02x faster                                                                                                   |
| sqlglot_v2_transpile      | 2.17 ms                                                                                                            | 2.12 ms: 1.02x faster                                                                                                  |
| deepcopy                  | 339 us                                                                                                             | 331 us: 1.02x faster                                                                                                   |
| generators                | 41.0 ms                                                                                                            | 40.1 ms: 1.02x faster                                                                                                  |
| sqlite_synth              | 3.18 us                                                                                                            | 3.11 us: 1.02x faster                                                                                                  |
| go                        | 150 ms                                                                                                             | 146 ms: 1.02x faster                                                                                                   |
| shortest_path             | 510 ms                                                                                                             | 501 ms: 1.02x faster                                                                                                   |
| async_tree_io             | 786 ms                                                                                                             | 771 ms: 1.02x faster                                                                                                   |
| pickle                    | 18.6 us                                                                                                            | 18.3 us: 1.02x faster                                                                                                  |
| pidigits                  | 287 ms                                                                                                             | 282 ms: 1.02x faster                                                                                                   |
| chaos                     | 76.4 ms                                                                                                            | 75.4 ms: 1.01x faster                                                                                                  |
| async_tree_cpu_io_mixed   | 693 ms                                                                                                             | 685 ms: 1.01x faster                                                                                                   |
| coverage                  | 118 ms                                                                                                             | 118 ms: 1.01x faster                                                                                                   |
| telco                     | 226 ms                                                                                                             | 225 ms: 1.00x faster                                                                                                   |
| base85_large              | 8.28 ms                                                                                                            | 8.28 ms: 1.00x slower                                                                                                  |
| ascii85_large             | 21.9 ms                                                                                                            | 21.9 ms: 1.00x slower                                                                                                  |
| base64_large              | 3.45 ms                                                                                                            | 3.45 ms: 1.00x slower                                                                                                  |
| python_startup            | 18.1 ms                                                                                                            | 18.2 ms: 1.00x slower                                                                                                  |
| python_startup_no_site    | 10.7 ms                                                                                                            | 10.7 ms: 1.01x slower                                                                                                  |
| logging_simple            | 8.45 us                                                                                                            | 8.52 us: 1.01x slower                                                                                                  |
| tornado_http              | 191 ms                                                                                                             | 192 ms: 1.01x slower                                                                                                   |
| thrift                    | 1.12 ms                                                                                                            | 1.13 ms: 1.01x slower                                                                                                  |
| k_core                    | 2.23 sec                                                                                                           | 2.26 sec: 1.01x slower                                                                                                 |
| chameleon                 | 19.0 ms                                                                                                            | 19.3 ms: 1.01x slower                                                                                                  |
| coroutines                | 32.7 ms                                                                                                            | 33.2 ms: 1.01x slower                                                                                                  |
| pickle_pure_python        | 441 us                                                                                                             | 447 us: 1.01x slower                                                                                                   |
| sqlalchemy_declarative    | 185 ms                                                                                                             | 188 ms: 1.02x slower                                                                                                   |
| sqlglot_v2_optimize       | 72.6 ms                                                                                                            | 73.9 ms: 1.02x slower                                                                                                  |
| pycparser                 | 1.60 sec                                                                                                           | 1.63 sec: 1.02x slower                                                                                                 |
| xdsl_constant_fold        | 65.1 ms                                                                                                            | 66.4 ms: 1.02x slower                                                                                                  |
| sqlglot_v2_normalize      | 145 ms                                                                                                             | 148 ms: 1.03x slower                                                                                                   |
| sympy_integrate           | 27.5 ms                                                                                                            | 28.2 ms: 1.03x slower                                                                                                  |
| create_gc_cycles          | 2.87 ms                                                                                                            | 2.96 ms: 1.03x slower                                                                                                  |
| sympy_expand              | 700 ms                                                                                                             | 725 ms: 1.03x slower                                                                                                   |
| sympy_str                 | 400 ms                                                                                                             | 414 ms: 1.04x slower                                                                                                   |
| gc_traversal              | 6.31 ms                                                                                                            | 6.55 ms: 1.04x slower                                                                                                  |
| many_optionals            | 1.36 ms                                                                                                            | 1.42 ms: 1.04x slower                                                                                                  |
| unpickle                  | 20.7 us                                                                                                            | 21.6 us: 1.04x slower                                                                                                  |
| base16_small              | 519 us                                                                                                             | 543 us: 1.05x slower                                                                                                   |
| dulwich_log               | 97.4 ms                                                                                                            | 102 ms: 1.05x slower                                                                                                   |
| sympy_sum                 | 224 ms                                                                                                             | 235 ms: 1.05x slower                                                                                                   |
| mdp                       | 1.65 sec                                                                                                           | 1.73 sec: 1.05x slower                                                                                                 |
| async_generators          | 475 ms                                                                                                             | 502 ms: 1.06x slower                                                                                                   |
| sphinx                    | 1.38 sec                                                                                                           | 1.46 sec: 1.06x slower                                                                                                 |
| html5lib                  | 86.4 ms                                                                                                            | 91.6 ms: 1.06x slower                                                                                                  |
| docutils                  | 3.62 sec                                                                                                           | 3.90 sec: 1.08x slower                                                                                                 |
| sqlalchemy_imperative     | 28.7 ms                                                                                                            | 31.1 ms: 1.08x slower                                                                                                  |
| base16_large              | 11.7 ms                                                                                                            | 13.2 ms: 1.13x slower                                                                                                  |
| raytrace                  | 361 ms                                                                                                             | 412 ms: 1.14x slower                                                                                                   |
| unpack_sequence           | 66.2 ns                                                                                                            | 111 ns: 1.67x slower                                                                                                   |
| Geometric mean            | (ref)                                                                                                              | 1.04x faster                                                                                                           |

Benchmark hidden because not significant (20): bench_mp_pool, async_tree_none_tg, async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization, bench_thread_pool, typing_runtime_protocols, json_loads, django_template, asyncio_tcp_ssl, meteor_contest, asyncio_websockets, 2to3, asyncio_tcp, regex_compile, logging_format, pathlib, hexiom, pylint, unpickle_list
Ignored benchmarks (2) of results/bm-20260311-3.15.0a7+-ebb150e/bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7+-ebb150e.json: genshi_text, genshi_xml

- Geometric mean (including insignificant results): 1.049x faster

# HPT report

- Reliability score: 99.91% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.01x