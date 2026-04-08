# Results vs. base

- fork: pablogsal
- ref: frame_pointers
- machine: darwin-arm64
- commit hash: 9d611e5
- commit date: 2026-04-05
- overall geometric mean: 1.001x slower
- HPT reliability: 73.32%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.00x

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (6): 2to3, chameleon, docutils, html5lib, sphinx, tornado_http

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (11): asyncio_websockets, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, async_tree_io, async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_generators, async_tree_cpu_io_mixed, coroutines

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20260405-jones-arm64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-jones-arm64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|----------------|:---------------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 68.3 ms                                                               | 71.5 ms: 1.05x slower                                              |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                       |

Benchmark hidden because not significant (2): pidigits, float

Benchmarks with tag 'regex':
============================

Benchmark hidden because not significant (4): regex_effbot, regex_compile, regex_dna, regex_v8

Benchmarks with tag 'serialize':
================================

Benchmark hidden because not significant (20): base32_small, ascii85_small, base32_large, base85_small, json_dumps, base64_small, urlsafe_base64_small, ascii85_large, xml_etree_process, pickle_pure_python, tomli_loads, xml_etree_parse, base64_large, base85_large, base16_large, xml_etree_generate, json_loads, xml_etree_iterparse, unpickle_pure_python, base16_small

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (4): genshi_text, mako, genshi_xml, django_template

All benchmarks:
===============

| Benchmark      | bm-20260405-jones-arm64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-jones-arm64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|----------------|:---------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pprint_pformat | 926 ms                                                                | 906 ms: 1.02x faster                                               |
| bpe_tokeniser  | 2.62 sec                                                              | 2.61 sec: 1.01x faster                                             |
| pyflate        | 256 ms                                                                | 263 ms: 1.03x slower                                               |
| gc_traversal   | 3.18 ms                                                               | 3.26 ms: 1.03x slower                                              |
| nbody          | 68.3 ms                                                               | 71.5 ms: 1.05x slower                                              |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                       |

Benchmark hidden because not significant (103): base32_small, pprint_safe_repr, sphinx, sqlglot_v2_normalize, logging_format, sqlalchemy_imperative, ascii85_small, base32_large, sympy_integrate, genshi_text, meteor_contest, sqlalchemy_declarative, base85_small, json_dumps, base64_small, telco, thrift, sympy_sum, regex_effbot, fannkuch, scimark_sor, urlsafe_base64_small, ascii85_large, chameleon, asyncio_websockets, 2to3, tornado_http, typing_runtime_protocols, mako, xml_etree_process, pickle_pure_python, regex_compile, async_tree_io_tg, raytrace, logging_simple, sqlglot_v2_transpile, sympy_expand, scimark_sparse_mat_mult, nqueens, async_tree_memoization_tg, sympy_str, logging_silent, many_optionals, tomli_loads, async_tree_none_tg, scimark_fft, richards, xml_etree_parse, async_tree_io, shortest_path, async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_memoization, regex_dna, connected_components, comprehensions, dulwich_log, base64_large, async_generators, genshi_xml, create_gc_cycles, pycparser, base85_large, pidigits, chaos, base16_large, html5lib, mdp, xdsl_constant_fold, xml_etree_generate, sqlglot_v2_parse, json, k_core, generators, async_tree_cpu_io_mixed, hexiom, sqlite_synth, docutils, richards_super, pylint, json_loads, python_startup_no_site, deepcopy, xml_etree_iterparse, go, coroutines, subparsers, python_startup, sqlglot_v2_optimize, deltablue, deepcopy_reduce, deepcopy_memo, float, scimark_lu, unpickle_pure_python, coverage, spectral_norm, base16_small, pathlib, scimark_monte_carlo, regex_v8, django_template, crypto_pyaes

- Geometric mean (including insignificant results): 1.001x slower

# HPT report

- Reliability score: 73.32% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.00x