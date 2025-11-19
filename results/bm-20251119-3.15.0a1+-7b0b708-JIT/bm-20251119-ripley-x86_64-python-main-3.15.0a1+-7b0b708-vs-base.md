# Results vs. base

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 7b0b708
- commit date: 2025-11-19
- overall geometric mean: 1.974x faster
- HPT reliability: 84.13%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

| Benchmark | bm-20251119-ripley-x86_64-python-7b0b70867586ef7109de-3.15.0a1+-7b0b708 | bm-20251119-ripley-x86_64-python-main-3.15.0a1+-7b0b708 |
|-----------|:-----------------------------------------------------------------------:|:-------------------------------------------------------:|
| richards  | 41.1 ms                                                                 | 20.8 ms: 1.97x faster                                   |
Ignored benchmarks (98) of results/bm-20251119-3.15.0a1+-7b0b708/bm-20251119-ripley-x86_64-python-7b0b70867586ef7109de-3.15.0a1+-7b0b708.json: 2to3, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, bpe_tokeniser, chaos, comprehensions, coroutines, coverage, create_gc_cycles, crypto_pyaes, deepcopy, deepcopy_memo, deepcopy_reduce, deltablue, django_template, docutils, dulwich_log, fannkuch, float, gc_traversal, generators, genshi_text, genshi_xml, go, hexiom, html5lib, json, json_dumps, json_loads, logging_format, logging_silent, logging_simple, mako, many_optionals, mdp, meteor_contest, nbody, nqueens, pathlib, pickle, pickle_dict, pickle_list, pickle_pure_python, pidigits, pprint_pformat, pprint_safe_repr, pycparser, pyflate, pylint, python_startup, python_startup_no_site, raytrace, regex_compile, regex_dna, regex_effbot, regex_v8, richards_super, scimark_fft, scimark_lu, scimark_monte_carlo, scimark_sor, scimark_sparse_mat_mult, spectral_norm, sphinx, sqlglot_v2_normalize, sqlglot_v2_optimize, sqlglot_v2_parse, sqlglot_v2_transpile, sqlite_synth, subparsers, sympy_expand, sympy_integrate, sympy_str, sympy_sum, telco, thrift, tomli_loads, typing_runtime_protocols, unpack_sequence, unpickle, unpickle_list, unpickle_pure_python, xml_etree_generate, xml_etree_iterparse, xml_etree_parse, xml_etree_process

- Geometric mean (including insignificant results): 1.974x faster

# HPT report

- Reliability score: 84.13% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x