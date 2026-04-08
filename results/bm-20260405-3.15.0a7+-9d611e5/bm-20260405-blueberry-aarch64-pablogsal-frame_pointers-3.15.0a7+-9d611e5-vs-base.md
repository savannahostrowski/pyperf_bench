# Results vs. base

- fork: pablogsal
- ref: frame_pointers
- machine: linux-aarch64
- commit hash: 9d611e5
- commit date: 2026-04-05
- overall geometric mean: 1.001x slower
- HPT reliability: 97.22%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.00x

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|----------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| 2to3           | 437 ms                                                                      | 433 ms: 1.01x faster                                                     |
| chameleon      | 19.9 ms                                                                     | 20.1 ms: 1.01x slower                                                    |
| Geometric mean | (ref)                                                                       | 1.00x faster                                                             |

Benchmark hidden because not significant (4): docutils, html5lib, sphinx, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|--------------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| asyncio_websockets | 851 ms                                                                      | 849 ms: 1.00x faster                                                     |
| coroutines         | 37.0 ms                                                                     | 37.4 ms: 1.01x slower                                                    |
| Geometric mean     | (ref)                                                                       | 1.01x slower                                                             |

Benchmark hidden because not significant (9): async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none, async_tree_io, async_generators, async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_memoization_tg, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|----------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| nbody          | 157 ms                                                                      | 160 ms: 1.02x slower                                                     |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                             |

Benchmark hidden because not significant (2): pidigits, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|----------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_v8       | 36.3 ms                                                                     | 35.4 ms: 1.02x faster                                                    |
| regex_effbot   | 4.49 ms                                                                     | 4.40 ms: 1.02x faster                                                    |
| regex_dna      | 278 ms                                                                      | 276 ms: 1.01x faster                                                     |
| regex_compile  | 145 ms                                                                      | 147 ms: 1.02x slower                                                     |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|----------------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| ascii85_large        | 20.1 ms                                                                     | 19.1 ms: 1.05x faster                                                    |
| ascii85_small        | 941 us                                                                      | 913 us: 1.03x faster                                                     |
| xml_etree_parse      | 245 ms                                                                      | 240 ms: 1.02x faster                                                     |
| base85_large         | 8.01 ms                                                                     | 7.87 ms: 1.02x faster                                                    |
| xml_etree_iterparse  | 198 ms                                                                      | 196 ms: 1.01x faster                                                     |
| unpickle_pure_python | 320 us                                                                      | 318 us: 1.01x faster                                                     |
| base85_small         | 361 us                                                                      | 360 us: 1.00x faster                                                     |
| base16_large         | 17.8 ms                                                                     | 17.7 ms: 1.00x faster                                                    |
| pickle_pure_python   | 460 us                                                                      | 463 us: 1.01x slower                                                     |
| json_loads           | 37.9 us                                                                     | 38.1 us: 1.01x slower                                                    |
| xml_etree_generate   | 131 ms                                                                      | 133 ms: 1.02x slower                                                     |
| json_dumps           | 13.6 ms                                                                     | 13.9 ms: 1.02x slower                                                    |
| tomli_loads          | 2.78 sec                                                                    | 2.84 sec: 1.02x slower                                                   |
| Geometric mean       | (ref)                                                                       | 1.00x faster                                                             |

Benchmark hidden because not significant (7): base64_small, base32_large, base64_large, base32_small, base16_small, urlsafe_base64_small, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|------------------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup         | 18.0 ms                                                                     | 17.7 ms: 1.01x faster                                                    |
| python_startup_no_site | 10.5 ms                                                                     | 10.4 ms: 1.01x faster                                                    |
| Geometric mean         | (ref)                                                                       | 1.01x faster                                                             |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|-----------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| genshi_text     | 32.3 ms                                                                     | 32.4 ms: 1.00x slower                                                    |
| mako            | 19.5 ms                                                                     | 19.7 ms: 1.01x slower                                                    |
| django_template | 49.5 ms                                                                     | 50.3 ms: 1.02x slower                                                    |
| Geometric mean  | (ref)                                                                       | 1.01x slower                                                             |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark                | bm-20260405-blueberry-aarch64-python-b07becb57371b733b9cc-3.15.0a7+-b07becb | bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7+-9d611e5 |
|--------------------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| ascii85_large            | 20.1 ms                                                                     | 19.1 ms: 1.05x faster                                                    |
| pathlib                  | 22.2 ms                                                                     | 21.4 ms: 1.04x faster                                                    |
| ascii85_small            | 941 us                                                                      | 913 us: 1.03x faster                                                     |
| logging_format           | 8.81 us                                                                     | 8.58 us: 1.03x faster                                                    |
| regex_v8                 | 36.3 ms                                                                     | 35.4 ms: 1.02x faster                                                    |
| logging_simple           | 8.02 us                                                                     | 7.86 us: 1.02x faster                                                    |
| regex_effbot             | 4.49 ms                                                                     | 4.40 ms: 1.02x faster                                                    |
| xml_etree_parse          | 245 ms                                                                      | 240 ms: 1.02x faster                                                     |
| telco                    | 190 ms                                                                      | 186 ms: 1.02x faster                                                     |
| base85_large             | 8.01 ms                                                                     | 7.87 ms: 1.02x faster                                                    |
| python_startup           | 18.0 ms                                                                     | 17.7 ms: 1.01x faster                                                    |
| deepcopy                 | 353 us                                                                      | 349 us: 1.01x faster                                                     |
| mdp                      | 2.39 sec                                                                    | 2.36 sec: 1.01x faster                                                   |
| coverage                 | 125 ms                                                                      | 124 ms: 1.01x faster                                                     |
| 2to3                     | 437 ms                                                                      | 433 ms: 1.01x faster                                                     |
| python_startup_no_site   | 10.5 ms                                                                     | 10.4 ms: 1.01x faster                                                    |
| richards                 | 63.5 ms                                                                     | 62.9 ms: 1.01x faster                                                    |
| richards_super           | 72.0 ms                                                                     | 71.3 ms: 1.01x faster                                                    |
| xml_etree_iterparse      | 198 ms                                                                      | 196 ms: 1.01x faster                                                     |
| deepcopy_reduce          | 3.93 us                                                                     | 3.90 us: 1.01x faster                                                    |
| regex_dna                | 278 ms                                                                      | 276 ms: 1.01x faster                                                     |
| unpickle_pure_python     | 320 us                                                                      | 318 us: 1.01x faster                                                     |
| meteor_contest           | 138 ms                                                                      | 137 ms: 1.01x faster                                                     |
| base85_small             | 361 us                                                                      | 360 us: 1.00x faster                                                     |
| base16_large             | 17.8 ms                                                                     | 17.7 ms: 1.00x faster                                                    |
| asyncio_websockets       | 851 ms                                                                      | 849 ms: 1.00x faster                                                     |
| genshi_text              | 32.3 ms                                                                     | 32.4 ms: 1.00x slower                                                    |
| hexiom                   | 8.44 ms                                                                     | 8.47 ms: 1.00x slower                                                    |
| sqlglot_v2_optimize      | 72.2 ms                                                                     | 72.6 ms: 1.00x slower                                                    |
| connected_components     | 846 ms                                                                      | 850 ms: 1.00x slower                                                     |
| pyflate                  | 718 ms                                                                      | 721 ms: 1.00x slower                                                     |
| pickle_pure_python       | 460 us                                                                      | 463 us: 1.01x slower                                                     |
| json_loads               | 37.9 us                                                                     | 38.1 us: 1.01x slower                                                    |
| mako                     | 19.5 ms                                                                     | 19.7 ms: 1.01x slower                                                    |
| dulwich_log              | 61.4 ms                                                                     | 61.9 ms: 1.01x slower                                                    |
| bpe_tokeniser            | 6.76 sec                                                                    | 6.81 sec: 1.01x slower                                                   |
| scimark_lu               | 167 ms                                                                      | 168 ms: 1.01x slower                                                     |
| comprehensions           | 24.4 us                                                                     | 24.6 us: 1.01x slower                                                    |
| go                       | 157 ms                                                                      | 158 ms: 1.01x slower                                                     |
| chameleon                | 19.9 ms                                                                     | 20.1 ms: 1.01x slower                                                    |
| nqueens                  | 114 ms                                                                      | 115 ms: 1.01x slower                                                     |
| coroutines               | 37.0 ms                                                                     | 37.4 ms: 1.01x slower                                                    |
| deepcopy_memo            | 40.4 us                                                                     | 40.8 us: 1.01x slower                                                    |
| chaos                    | 82.7 ms                                                                     | 83.8 ms: 1.01x slower                                                    |
| fannkuch                 | 570 ms                                                                      | 578 ms: 1.01x slower                                                     |
| sqlalchemy_imperative    | 20.4 ms                                                                     | 20.7 ms: 1.01x slower                                                    |
| generators               | 47.0 ms                                                                     | 47.8 ms: 1.02x slower                                                    |
| xml_etree_generate       | 131 ms                                                                      | 133 ms: 1.02x slower                                                     |
| scimark_fft              | 471 ms                                                                      | 478 ms: 1.02x slower                                                     |
| nbody                    | 157 ms                                                                      | 160 ms: 1.02x slower                                                     |
| json_dumps               | 13.6 ms                                                                     | 13.9 ms: 1.02x slower                                                    |
| scimark_sparse_mat_mult  | 7.84 ms                                                                     | 7.98 ms: 1.02x slower                                                    |
| django_template          | 49.5 ms                                                                     | 50.3 ms: 1.02x slower                                                    |
| regex_compile            | 145 ms                                                                      | 147 ms: 1.02x slower                                                     |
| raytrace                 | 386 ms                                                                      | 393 ms: 1.02x slower                                                     |
| pprint_safe_repr         | 1.04 sec                                                                    | 1.06 sec: 1.02x slower                                                   |
| thrift                   | 1.11 ms                                                                     | 1.13 ms: 1.02x slower                                                    |
| typing_runtime_protocols | 230 us                                                                      | 235 us: 1.02x slower                                                     |
| pprint_pformat           | 2.11 sec                                                                    | 2.16 sec: 1.02x slower                                                   |
| tomli_loads              | 2.78 sec                                                                    | 2.84 sec: 1.02x slower                                                   |
| spectral_norm            | 145 ms                                                                      | 150 ms: 1.03x slower                                                     |
| crypto_pyaes             | 102 ms                                                                      | 105 ms: 1.04x slower                                                     |
| Geometric mean           | (ref)                                                                       | 1.00x slower                                                             |

Benchmark hidden because not significant (46): docutils, sqlglot_v2_transpile, genshi_xml, subparsers, async_tree_cpu_io_mixed, sympy_sum, pycparser, sphinx, deltablue, sympy_expand, sqlglot_v2_parse, gc_traversal, sympy_integrate, base64_small, logging_silent, json, tornado_http, async_tree_memoization, html5lib, many_optionals, base32_large, k_core, base64_large, pidigits, scimark_sor, base32_small, create_gc_cycles, scimark_monte_carlo, base16_small, shortest_path, pylint, sqlalchemy_declarative, urlsafe_base64_small, xdsl_constant_fold, async_tree_none, sqlglot_v2_normalize, sympy_str, sqlite_synth, async_tree_io, xml_etree_process, async_generators, async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_memoization_tg, float, async_tree_io_tg

- Geometric mean (including insignificant results): 1.001x slower

# HPT report

- Reliability score: 97.22% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.00x