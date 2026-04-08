# Results vs. base

- fork: python
- ref: bce96a181350f348560f
- machine: linux-aarch64
- commit hash: bce96a1
- commit date: 2026-04-05
- overall geometric mean: 1.001x faster
- HPT reliability: 83.53%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.00x

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 437 ms                                                                      | 434 ms: 1.01x faster                                                        |
| chameleon      | 19.9 ms                                                                     | 20.1 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (4): docutils, html5lib, sphinx, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark      | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| coroutines     | 37.0 ms                                                                     | 37.5 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (10): async_tree_none, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_io, async_generators, asyncio_websockets, async_tree_none_tg, async_tree_memoization_tg, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 282 ms                                                                      | 283 ms: 1.00x slower                                                        |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 4.49 ms                                                                     | 4.51 ms: 1.00x slower                                                       |
| regex_v8       | 36.3 ms                                                                     | 36.5 ms: 1.01x slower                                                       |
| regex_dna      | 278 ms                                                                      | 280 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_pure_python | 320 us                                                                      | 317 us: 1.01x faster                                                        |
| xml_etree_process    | 99.0 ms                                                                     | 98.1 ms: 1.01x faster                                                       |
| ascii85_small        | 941 us                                                                      | 933 us: 1.01x faster                                                        |
| xml_etree_generate   | 131 ms                                                                      | 130 ms: 1.01x faster                                                        |
| base85_small         | 361 us                                                                      | 360 us: 1.00x faster                                                        |
| pickle_pure_python   | 460 us                                                                      | 459 us: 1.00x faster                                                        |
| base16_large         | 17.8 ms                                                                     | 17.7 ms: 1.00x faster                                                       |
| base64_large         | 4.11 ms                                                                     | 4.12 ms: 1.00x slower                                                       |
| urlsafe_base64_small | 576 us                                                                      | 578 us: 1.00x slower                                                        |
| base32_small         | 414 us                                                                      | 416 us: 1.01x slower                                                        |
| tomli_loads          | 2.78 sec                                                                    | 2.79 sec: 1.01x slower                                                      |
| base64_small         | 465 us                                                                      | 469 us: 1.01x slower                                                        |
| Geometric mean       | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (8): xml_etree_iterparse, base32_large, base85_large, json_loads, ascii85_large, json_dumps, xml_etree_parse, base16_small

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.0 ms                                                                     | 17.8 ms: 1.01x faster                                                       |
| python_startup_no_site | 10.5 ms                                                                     | 10.5 ms: 1.01x faster                                                       |
| Geometric mean         | (ref)                                                                       | 1.01x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|-----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 19.5 ms                                                                     | 19.4 ms: 1.01x faster                                                       |
| django_template | 49.5 ms                                                                     | 49.9 ms: 1.01x slower                                                       |
| Geometric mean  | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (2): genshi_text, genshi_xml

All benchmarks:
===============

| Benchmark                | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1 |
|--------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pathlib                  | 22.2 ms                                                                     | 21.3 ms: 1.04x faster                                                       |
| coverage                 | 125 ms                                                                      | 123 ms: 1.02x faster                                                        |
| connected_components     | 846 ms                                                                      | 835 ms: 1.01x faster                                                        |
| shortest_path            | 896 ms                                                                      | 885 ms: 1.01x faster                                                        |
| meteor_contest           | 138 ms                                                                      | 136 ms: 1.01x faster                                                        |
| telco                    | 190 ms                                                                      | 188 ms: 1.01x faster                                                        |
| python_startup           | 18.0 ms                                                                     | 17.8 ms: 1.01x faster                                                       |
| mdp                      | 2.39 sec                                                                    | 2.37 sec: 1.01x faster                                                      |
| unpickle_pure_python     | 320 us                                                                      | 317 us: 1.01x faster                                                        |
| many_optionals           | 917 us                                                                      | 909 us: 1.01x faster                                                        |
| xml_etree_process        | 99.0 ms                                                                     | 98.1 ms: 1.01x faster                                                       |
| ascii85_small            | 941 us                                                                      | 933 us: 1.01x faster                                                        |
| 2to3                     | 437 ms                                                                      | 434 ms: 1.01x faster                                                        |
| logging_format           | 8.81 us                                                                     | 8.75 us: 1.01x faster                                                       |
| create_gc_cycles         | 9.33 ms                                                                     | 9.26 ms: 1.01x faster                                                       |
| python_startup_no_site   | 10.5 ms                                                                     | 10.5 ms: 1.01x faster                                                       |
| dulwich_log              | 61.4 ms                                                                     | 61.0 ms: 1.01x faster                                                       |
| mako                     | 19.5 ms                                                                     | 19.4 ms: 1.01x faster                                                       |
| pyflate                  | 718 ms                                                                      | 713 ms: 1.01x faster                                                        |
| xml_etree_generate       | 131 ms                                                                      | 130 ms: 1.01x faster                                                        |
| sympy_sum                | 173 ms                                                                      | 172 ms: 1.01x faster                                                        |
| richards_super           | 72.0 ms                                                                     | 71.5 ms: 1.01x faster                                                       |
| comprehensions           | 24.4 us                                                                     | 24.3 us: 1.01x faster                                                       |
| chaos                    | 82.7 ms                                                                     | 82.3 ms: 1.01x faster                                                       |
| logging_simple           | 8.02 us                                                                     | 7.98 us: 1.00x faster                                                       |
| sqlglot_v2_normalize     | 148 ms                                                                      | 148 ms: 1.00x faster                                                        |
| scimark_lu               | 167 ms                                                                      | 166 ms: 1.00x faster                                                        |
| base85_small             | 361 us                                                                      | 360 us: 1.00x faster                                                        |
| generators               | 47.0 ms                                                                     | 46.9 ms: 1.00x faster                                                       |
| pickle_pure_python       | 460 us                                                                      | 459 us: 1.00x faster                                                        |
| base16_large             | 17.8 ms                                                                     | 17.7 ms: 1.00x faster                                                       |
| pidigits                 | 282 ms                                                                      | 283 ms: 1.00x slower                                                        |
| spectral_norm            | 145 ms                                                                      | 145 ms: 1.00x slower                                                        |
| base64_large             | 4.11 ms                                                                     | 4.12 ms: 1.00x slower                                                       |
| k_core                   | 4.08 sec                                                                    | 4.09 sec: 1.00x slower                                                      |
| sqlalchemy_declarative   | 157 ms                                                                      | 158 ms: 1.00x slower                                                        |
| urlsafe_base64_small     | 576 us                                                                      | 578 us: 1.00x slower                                                        |
| regex_effbot             | 4.49 ms                                                                     | 4.51 ms: 1.00x slower                                                       |
| scimark_sor              | 169 ms                                                                      | 170 ms: 1.00x slower                                                        |
| thrift                   | 1.11 ms                                                                     | 1.11 ms: 1.01x slower                                                       |
| base32_small             | 414 us                                                                      | 416 us: 1.01x slower                                                        |
| tomli_loads              | 2.78 sec                                                                    | 2.79 sec: 1.01x slower                                                      |
| scimark_sparse_mat_mult  | 7.84 ms                                                                     | 7.89 ms: 1.01x slower                                                       |
| deepcopy_memo            | 40.4 us                                                                     | 40.6 us: 1.01x slower                                                       |
| bpe_tokeniser            | 6.76 sec                                                                    | 6.80 sec: 1.01x slower                                                      |
| base64_small             | 465 us                                                                      | 469 us: 1.01x slower                                                        |
| regex_v8                 | 36.3 ms                                                                     | 36.5 ms: 1.01x slower                                                       |
| json                     | 6.67 ms                                                                     | 6.72 ms: 1.01x slower                                                       |
| django_template          | 49.5 ms                                                                     | 49.9 ms: 1.01x slower                                                       |
| regex_dna                | 278 ms                                                                      | 280 ms: 1.01x slower                                                        |
| pprint_pformat           | 2.11 sec                                                                    | 2.13 sec: 1.01x slower                                                      |
| pprint_safe_repr         | 1.04 sec                                                                    | 1.05 sec: 1.01x slower                                                      |
| crypto_pyaes             | 102 ms                                                                      | 103 ms: 1.01x slower                                                        |
| chameleon                | 19.9 ms                                                                     | 20.1 ms: 1.01x slower                                                       |
| fannkuch                 | 570 ms                                                                      | 576 ms: 1.01x slower                                                        |
| deepcopy_reduce          | 3.93 us                                                                     | 3.97 us: 1.01x slower                                                       |
| coroutines               | 37.0 ms                                                                     | 37.5 ms: 1.01x slower                                                       |
| raytrace                 | 386 ms                                                                      | 391 ms: 1.01x slower                                                        |
| typing_runtime_protocols | 230 us                                                                      | 234 us: 1.02x slower                                                        |
| Geometric mean           | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (49): docutils, async_tree_none, async_tree_cpu_io_mixed, pylint, pycparser, xml_etree_iterparse, async_tree_memoization, sphinx, sympy_integrate, async_tree_cpu_io_mixed_tg, scimark_monte_carlo, sympy_expand, float, async_tree_io, hexiom, xdsl_constant_fold, richards, async_generators, sympy_str, base32_large, base85_large, genshi_text, sqlglot_v2_parse, genshi_xml, asyncio_websockets, sqlglot_v2_transpile, json_loads, scimark_fft, sqlglot_v2_optimize, ascii85_large, regex_compile, html5lib, json_dumps, logging_silent, go, xml_etree_parse, sqlite_synth, gc_traversal, base16_small, sqlalchemy_imperative, nqueens, deepcopy, nbody, tornado_http, deltablue, async_tree_none_tg, async_tree_memoization_tg, async_tree_io_tg, subparsers
Ignored benchmarks (10) of results/bm-20260405-3.15.0a7+-bce96a1/bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7+-bce96a1.json: asyncio_tcp, asyncio_tcp_ssl, bench_mp_pool, bench_thread_pool, pickle, pickle_dict, pickle_list, unpack_sequence, unpickle, unpickle_list

- Geometric mean (including insignificant results): 1.001x faster

# HPT report

- Reliability score: 83.53% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.00x