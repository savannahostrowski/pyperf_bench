# Results

- fork: python/main
- version: 3.15.0a1+
- config: JIT
- commit hash: [7b0b708](https://github.com/python/cpython/commit/7b0b708)
- commit date: 2025-11-19T09:48:51+08:00
- commit merge base: [ce791541769a41beabec0f515cd62e504d46ff1c](https://github.com/python/cpython/commit/ce791541769a41beabec0f515cd62e504d46ff1c)
- fork: python/7b0b70867586ef7109de
- ref: 7b0b70867586ef7109de, main

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19490816413)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708.json)

### vs. base

- Geometric mean: 1.103x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base-mem.svg)
- [📄table](bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base.md)
- [📈time plot](bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19488709243)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251119-ripley-x86_64-python-main-3.15.0a1%2B-7b0b708.json)

### vs. base

- Geometric mean: 1.974x faster (HPT: reliability of 84.13%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 2to3, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, bpe_tokeniser, chaos, comprehensions, coroutines, coverage, create_gc_cycles, crypto_pyaes, deepcopy, deepcopy_memo, deepcopy_reduce, deltablue, django_template, docutils, dulwich_log, fannkuch, float, gc_traversal, generators, genshi_text, genshi_xml, go, hexiom, html5lib, json, json_dumps, json_loads, logging_format, logging_silent, logging_simple, mako, many_optionals, mdp, meteor_contest, nbody, nqueens, pathlib, pickle, pickle_dict, pickle_list, pickle_pure_python, pidigits, pprint_pformat, pprint_safe_repr, pycparser, pyflate, pylint, python_startup, python_startup_no_site, raytrace, regex_compile, regex_dna, regex_effbot, regex_v8, richards_super, scimark_fft, scimark_lu, scimark_monte_carlo, scimark_sor, scimark_sparse_mat_mult, spectral_norm, sphinx, sqlglot_v2_normalize, sqlglot_v2_optimize, sqlglot_v2_parse, sqlglot_v2_transpile, sqlite_synth, subparsers, sympy_expand, sympy_integrate, sympy_str, sympy_sum, telco, thrift, tomli_loads, typing_runtime_protocols, unpack_sequence, unpickle, unpickle_list, unpickle_pure_python, xml_etree_generate, xml_etree_iterparse, xml_etree_parse, xml_etree_process
- [🧠memory plot](bm-20251119-ripley-x86_64-python-main-3.15.0a1%2B-7b0b708-vs-base-mem.svg)
- [📄table](bm-20251119-ripley-x86_64-python-main-3.15.0a1%2B-7b0b708-vs-base.md)
- [📈time plot](bm-20251119-ripley-x86_64-python-main-3.15.0a1%2B-7b0b708-vs-base.svg)

