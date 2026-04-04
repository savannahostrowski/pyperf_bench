# Results vs. base

- fork: python
- ref: dea4083aa952c955a7c3
- machine: windows-amd64
- commit hash: dea4083
- commit date: 2026-04-03
- overall geometric mean: 1.006x slower
- HPT reliability: 99.15%
- HPT 99th percentile: 1.00x slower
- Memory change: unknown

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20260403-prometheus-amd64-python-main-3.15.0a7+-80d0a85 | bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083 |
|----------------|:----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 309 ms                                                     | 310 ms: 1.00x slower                                                       |
| chameleon      | 14.3 ms                                                    | 13.9 ms: 1.03x faster                                                      |
| docutils       | 2.46 sec                                                   | 2.44 sec: 1.01x faster                                                     |
| html5lib       | 63.6 ms                                                    | 62.2 ms: 1.02x faster                                                      |
| sphinx         | 986 ms                                                     | 1.04 sec: 1.06x slower                                                     |
| tornado_http   | 155 ms                                                     | 169 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                      | 1.01x slower                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20260403-prometheus-amd64-python-main-3.15.0a7+-80d0a85 | bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083 |
|----------------------------|:----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 494 ms                                                     | 480 ms: 1.03x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                     | 484 ms: 1.02x faster                                                       |
| async_generators           | 404 ms                                                     | 410 ms: 1.01x slower                                                       |
| coroutines                 | 21.5 ms                                                    | 22.9 ms: 1.06x slower                                                      |
| asyncio_websockets         | 209 ms                                                     | 234 ms: 1.12x slower                                                       |
| Geometric mean             | (ref)                                                      | 1.01x slower                                                               |

Benchmark hidden because not significant (6): async_tree_memoization, async_tree_none, async_tree_io_tg, async_tree_none_tg, async_tree_io, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20260403-prometheus-amd64-python-main-3.15.0a7+-80d0a85 | bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083 |
|----------------|:----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 54.3 ms                                                    | 53.5 ms: 1.02x faster                                                      |
| nbody          | 70.4 ms                                                    | 71.6 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                      | 1.00x slower                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20260403-prometheus-amd64-python-main-3.15.0a7+-80d0a85 | bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083 |
|----------------|:----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 2.64 ms                                                    | 2.39 ms: 1.10x faster                                                      |
| regex_dna      | 169 ms                                                     | 157 ms: 1.08x faster                                                       |
| regex_compile  | 117 ms                                                     | 115 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                      | 1.05x faster                                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20260403-prometheus-amd64-python-main-3.15.0a7+-80d0a85 | bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083 |
|----------------------|:----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| ascii85_large        | 16.4 ms                                                    | 14.9 ms: 1.10x faster                                                      |
| base16_small         | 587 us                                                     | 541 us: 1.08x faster                                                       |
| base16_large         | 11.6 ms                                                    | 10.9 ms: 1.07x faster                                                      |
| json_loads           | 24.4 us                                                    | 23.2 us: 1.05x faster                                                      |
| unpickle_pure_python | 204 us                                                     | 197 us: 1.03x faster                                                       |
| base85_small         | 246 us                                                     | 243 us: 1.01x faster                                                       |
| pickle_pure_python   | 285 us                                                     | 282 us: 1.01x faster                                                       |
| base64_large         | 2.81 ms                                                    | 2.79 ms: 1.01x faster                                                      |
| base32_large         | 3.91 ms                                                    | 3.88 ms: 1.01x faster                                                      |
| base32_small         | 239 us                                                     | 241 us: 1.01x slower                                                       |
| base85_large         | 5.42 ms                                                    | 5.51 ms: 1.02x slower                                                      |
| json_dumps           | 8.08 ms                                                    | 8.34 ms: 1.03x slower                                                      |
| tomli_loads          | 1.45 sec                                                   | 1.51 sec: 1.04x slower                                                     |
| base64_small         | 247 us                                                     | 259 us: 1.05x slower                                                       |
| xml_etree_parse      | 148 ms                                                     | 157 ms: 1.06x slower                                                       |
| xml_etree_generate   | 82.9 ms                                                    | 90.3 ms: 1.09x slower                                                      |
| xml_etree_process    | 54.3 ms                                                    | 59.2 ms: 1.09x slower                                                      |
| xml_etree_iterparse  | 91.5 ms                                                    | 104 ms: 1.14x slower                                                       |
| Geometric mean       | (ref)                                                      | 1.01x slower                                                               |

Benchmark hidden because not significant (2): ascii85_small, urlsafe_base64_small

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20260403-prometheus-amd64-python-main-3.15.0a7+-80d0a85 | bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083 |
|----------------|:----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako           | 10.1 ms                                                    | 9.94 ms: 1.02x faster                                                      |
| Geometric mean | (ref)                                                      | 1.00x faster                                                               |

Benchmark hidden because not significant (3): django_template, genshi_xml, genshi_text

All benchmarks:
===============

| Benchmark                  | bm-20260403-prometheus-amd64-python-main-3.15.0a7+-80d0a85 | bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083 |
|----------------------------|:----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| ascii85_large              | 16.4 ms                                                    | 14.9 ms: 1.10x faster                                                      |
| regex_effbot               | 2.64 ms                                                    | 2.39 ms: 1.10x faster                                                      |
| base16_small               | 587 us                                                     | 541 us: 1.08x faster                                                       |
| regex_dna                  | 169 ms                                                     | 157 ms: 1.08x faster                                                       |
| base16_large               | 11.6 ms                                                    | 10.9 ms: 1.07x faster                                                      |
| logging_silent             | 81.3 ns                                                    | 76.5 ns: 1.06x faster                                                      |
| json_loads                 | 24.4 us                                                    | 23.2 us: 1.05x faster                                                      |
| unpickle_pure_python       | 204 us                                                     | 197 us: 1.03x faster                                                       |
| hexiom                     | 6.03 ms                                                    | 5.84 ms: 1.03x faster                                                      |
| chameleon                  | 14.3 ms                                                    | 13.9 ms: 1.03x faster                                                      |
| scimark_lu                 | 75.2 ms                                                    | 72.9 ms: 1.03x faster                                                      |
| async_tree_cpu_io_mixed_tg | 494 ms                                                     | 480 ms: 1.03x faster                                                       |
| pprint_pformat             | 1.43 sec                                                   | 1.39 sec: 1.03x faster                                                     |
| pprint_safe_repr           | 699 ms                                                     | 681 ms: 1.03x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                     | 484 ms: 1.02x faster                                                       |
| json                       | 4.47 ms                                                    | 4.37 ms: 1.02x faster                                                      |
| html5lib                   | 63.6 ms                                                    | 62.2 ms: 1.02x faster                                                      |
| meteor_contest             | 97.7 ms                                                    | 95.9 ms: 1.02x faster                                                      |
| regex_compile              | 117 ms                                                     | 115 ms: 1.02x faster                                                       |
| mako                       | 10.1 ms                                                    | 9.94 ms: 1.02x faster                                                      |
| float                      | 54.3 ms                                                    | 53.5 ms: 1.02x faster                                                      |
| base85_small               | 246 us                                                     | 243 us: 1.01x faster                                                       |
| pickle_pure_python         | 285 us                                                     | 282 us: 1.01x faster                                                       |
| raytrace                   | 263 ms                                                     | 260 ms: 1.01x faster                                                       |
| docutils                   | 2.46 sec                                                   | 2.44 sec: 1.01x faster                                                     |
| base64_large               | 2.81 ms                                                    | 2.79 ms: 1.01x faster                                                      |
| base32_large               | 3.91 ms                                                    | 3.88 ms: 1.01x faster                                                      |
| 2to3                       | 309 ms                                                     | 310 ms: 1.00x slower                                                       |
| sqlite_synth               | 2.33 us                                                    | 2.34 us: 1.01x slower                                                      |
| base32_small               | 239 us                                                     | 241 us: 1.01x slower                                                       |
| nqueens                    | 66.3 ms                                                    | 66.8 ms: 1.01x slower                                                      |
| create_gc_cycles           | 1.46 ms                                                    | 1.48 ms: 1.01x slower                                                      |
| scimark_sor                | 76.7 ms                                                    | 77.7 ms: 1.01x slower                                                      |
| async_generators           | 404 ms                                                     | 410 ms: 1.01x slower                                                       |
| sqlglot_v2_optimize        | 50.0 ms                                                    | 50.7 ms: 1.01x slower                                                      |
| crypto_pyaes               | 65.8 ms                                                    | 66.7 ms: 1.01x slower                                                      |
| bpe_tokeniser              | 3.73 sec                                                   | 3.78 sec: 1.01x slower                                                     |
| go                         | 106 ms                                                     | 108 ms: 1.02x slower                                                       |
| nbody                      | 70.4 ms                                                    | 71.6 ms: 1.02x slower                                                      |
| base85_large               | 5.42 ms                                                    | 5.51 ms: 1.02x slower                                                      |
| mdp                        | 1.13 sec                                                   | 1.15 sec: 1.02x slower                                                     |
| typing_runtime_protocols   | 149 us                                                     | 152 us: 1.02x slower                                                       |
| deepcopy                   | 220 us                                                     | 224 us: 1.02x slower                                                       |
| sympy_sum                  | 143 ms                                                     | 146 ms: 1.02x slower                                                       |
| richards                   | 24.9 ms                                                    | 25.3 ms: 1.02x slower                                                      |
| sympy_str                  | 274 ms                                                     | 280 ms: 1.02x slower                                                       |
| logging_format             | 8.55 us                                                    | 8.72 us: 1.02x slower                                                      |
| chaos                      | 49.9 ms                                                    | 50.9 ms: 1.02x slower                                                      |
| sqlglot_v2_transpile       | 1.42 ms                                                    | 1.45 ms: 1.02x slower                                                      |
| deepcopy_memo              | 22.1 us                                                    | 22.6 us: 1.02x slower                                                      |
| spectral_norm              | 67.3 ms                                                    | 68.8 ms: 1.02x slower                                                      |
| sympy_expand               | 470 ms                                                     | 480 ms: 1.02x slower                                                       |
| subparsers                 | 8.79 ms                                                    | 9.00 ms: 1.02x slower                                                      |
| shortest_path              | 481 ms                                                     | 492 ms: 1.02x slower                                                       |
| sympy_integrate            | 17.6 ms                                                    | 18.0 ms: 1.02x slower                                                      |
| pyflate                    | 347 ms                                                     | 356 ms: 1.03x slower                                                       |
| scimark_fft                | 239 ms                                                     | 245 ms: 1.03x slower                                                       |
| gc_traversal               | 3.35 ms                                                    | 3.46 ms: 1.03x slower                                                      |
| comprehensions             | 14.2 us                                                    | 14.7 us: 1.03x slower                                                      |
| json_dumps                 | 8.08 ms                                                    | 8.34 ms: 1.03x slower                                                      |
| richards_super             | 29.8 ms                                                    | 30.8 ms: 1.03x slower                                                      |
| sqlalchemy_imperative      | 17.1 ms                                                    | 17.6 ms: 1.03x slower                                                      |
| xdsl_constant_fold         | 48.9 ms                                                    | 50.9 ms: 1.04x slower                                                      |
| coverage                   | 83.0 ms                                                    | 86.6 ms: 1.04x slower                                                      |
| tomli_loads                | 1.45 sec                                                   | 1.51 sec: 1.04x slower                                                     |
| sqlalchemy_declarative     | 97.9 ms                                                    | 102 ms: 1.05x slower                                                       |
| base64_small               | 247 us                                                     | 259 us: 1.05x slower                                                       |
| scimark_monte_carlo        | 50.4 ms                                                    | 52.9 ms: 1.05x slower                                                      |
| xml_etree_parse            | 148 ms                                                     | 157 ms: 1.06x slower                                                       |
| sphinx                     | 986 ms                                                     | 1.04 sec: 1.06x slower                                                     |
| coroutines                 | 21.5 ms                                                    | 22.9 ms: 1.06x slower                                                      |
| xml_etree_generate         | 82.9 ms                                                    | 90.3 ms: 1.09x slower                                                      |
| xml_etree_process          | 54.3 ms                                                    | 59.2 ms: 1.09x slower                                                      |
| tornado_http               | 155 ms                                                     | 169 ms: 1.09x slower                                                       |
| asyncio_websockets         | 209 ms                                                     | 234 ms: 1.12x slower                                                       |
| xml_etree_iterparse        | 91.5 ms                                                    | 104 ms: 1.14x slower                                                       |
| Geometric mean             | (ref)                                                      | 1.01x slower                                                               |

Benchmark hidden because not significant (32): regex_v8, python_startup_no_site, dulwich_log, deepcopy_reduce, async_tree_memoization, async_tree_none, pycparser, async_tree_io_tg, django_template, pylint, many_optionals, python_startup, sqlglot_v2_parse, connected_components, ascii85_small, generators, urlsafe_base64_small, pathlib, pidigits, telco, fannkuch, deltablue, scimark_sparse_mat_mult, thrift, genshi_xml, logging_simple, genshi_text, sqlglot_v2_normalize, async_tree_none_tg, k_core, async_tree_io, async_tree_memoization_tg
Ignored benchmarks (10) of results/bm-20260403-3.15.0a7+-dea4083-JIT,TAILCALL/bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7+-dea4083.json: asyncio_tcp, asyncio_tcp_ssl, bench_mp_pool, bench_thread_pool, pickle, pickle_dict, pickle_list, unpack_sequence, unpickle, unpickle_list

- Geometric mean (including insignificant results): 1.006x slower

# HPT report

- Reliability score: 99.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: unknown