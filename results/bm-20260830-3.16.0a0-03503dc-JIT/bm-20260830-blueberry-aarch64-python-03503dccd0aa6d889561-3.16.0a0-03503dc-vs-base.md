# Results vs. base

- fork: python
- ref: 03503dccd0aa6d889561
- machine: linux-aarch64
- commit hash: 03503dc
- commit date: 2026-08-30
- overall geometric mean: 1.016x slower
- HPT reliability: 99.21%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.05x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 402 ms                                                                                                               | 399 ms: 1.01x faster                                                                                                     |
| docutils       | 3.56 sec                                                                                                             | 4.43 sec: 1.24x slower                                                                                                   |
| html5lib       | 71.3 ms                                                                                                              | 108 ms: 1.51x slower                                                                                                     |
| sphinx         | 1.50 sec                                                                                                             | 1.73 sec: 1.15x slower                                                                                                   |
| tornado_http   | 161 ms                                                                                                               | 176 ms: 1.09x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                | 1.15x slower                                                                                                             |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|---------------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| asyncio_websockets        | 839 ms                                                                                                               | 848 ms: 1.01x slower                                                                                                     |
| asyncio_tcp_ssl           | 3.11 sec                                                                                                             | 3.22 sec: 1.04x slower                                                                                                   |
| async_tree_io             | 1.35 sec                                                                                                             | 1.39 sec: 1.04x slower                                                                                                   |
| async_tree_memoization_tg | 713 ms                                                                                                               | 744 ms: 1.04x slower                                                                                                     |
| async_generators          | 567 ms                                                                                                               | 592 ms: 1.04x slower                                                                                                     |
| asyncio_tcp               | 699 ms                                                                                                               | 732 ms: 1.05x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                | 1.01x slower                                                                                                             |

Benchmark hidden because not significant (7): async_tree_none_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, coroutines, async_tree_none, async_tree_cpu_io_mixed, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 162 ms                                                                                                               | 105 ms: 1.55x faster                                                                                                     |
| float          | 112 ms                                                                                                               | 89.1 ms: 1.26x faster                                                                                                    |
| Geometric mean | (ref)                                                                                                                | 1.25x faster                                                                                                             |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 35.8 ms                                                                                                              | 34.4 ms: 1.04x faster                                                                                                    |
| regex_dna      | 275 ms                                                                                                               | 266 ms: 1.03x faster                                                                                                     |
| regex_effbot   | 4.55 ms                                                                                                              | 4.49 ms: 1.01x faster                                                                                                    |
| regex_compile  | 178 ms                                                                                                               | 204 ms: 1.14x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                | 1.01x slower                                                                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|----------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| base64_small         | 494 us                                                                                                               | 400 us: 1.24x faster                                                                                                     |
| pickle_pure_python   | 451 us                                                                                                               | 389 us: 1.16x faster                                                                                                     |
| base32_small         | 450 us                                                                                                               | 395 us: 1.14x faster                                                                                                     |
| base85_small         | 382 us                                                                                                               | 348 us: 1.10x faster                                                                                                     |
| urlsafe_base64_small | 554 us                                                                                                               | 524 us: 1.06x faster                                                                                                     |
| ascii85_small        | 1.06 ms                                                                                                              | 1.02 ms: 1.04x faster                                                                                                    |
| json_dumps           | 13.2 ms                                                                                                              | 12.7 ms: 1.04x faster                                                                                                    |
| base16_small         | 833 us                                                                                                               | 820 us: 1.02x faster                                                                                                     |
| unpickle             | 23.0 us                                                                                                              | 22.8 us: 1.01x faster                                                                                                    |
| ascii85_large        | 23.6 ms                                                                                                              | 23.8 ms: 1.01x slower                                                                                                    |
| base16_large         | 17.3 ms                                                                                                              | 17.4 ms: 1.01x slower                                                                                                    |
| base85_large         | 8.09 ms                                                                                                              | 8.16 ms: 1.01x slower                                                                                                    |
| base64_large         | 4.29 ms                                                                                                              | 4.35 ms: 1.01x slower                                                                                                    |
| unpickle_list        | 8.34 us                                                                                                              | 8.47 us: 1.01x slower                                                                                                    |
| pickle_dict          | 48.9 us                                                                                                              | 49.7 us: 1.02x slower                                                                                                    |
| xml_etree_parse      | 255 ms                                                                                                               | 261 ms: 1.02x slower                                                                                                     |
| tomli_loads          | 3.03 sec                                                                                                             | 3.77 sec: 1.24x slower                                                                                                   |
| Geometric mean       | (ref)                                                                                                                | 1.02x faster                                                                                                             |

Benchmark hidden because not significant (8): unpickle_pure_python, xml_etree_iterparse, json_loads, pickle, pickle_list, xml_etree_generate, base32_large, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|------------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.4 ms                                                                                                              | 17.5 ms: 1.00x slower                                                                                                    |
| python_startup_no_site | 10.2 ms                                                                                                              | 10.3 ms: 1.01x slower                                                                                                    |
| Geometric mean         | (ref)                                                                                                                | 1.01x slower                                                                                                             |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|-----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.5 ms                                                                                                              | 15.3 ms: 1.15x faster                                                                                                    |
| django_template | 52.5 ms                                                                                                              | 70.8 ms: 1.35x slower                                                                                                    |
| Geometric mean  | (ref)                                                                                                                | 1.09x slower                                                                                                             |

All benchmarks:
===============

| Benchmark                 | results/bm-20260830-3.16.0a0-03503dc/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json | results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json |
|---------------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 67.5 ms                                                                                                              | 42.1 ms: 1.60x faster                                                                                                    |
| richards_super            | 75.7 ms                                                                                                              | 48.0 ms: 1.58x faster                                                                                                    |
| nbody                     | 162 ms                                                                                                               | 105 ms: 1.55x faster                                                                                                     |
| scimark_lu                | 190 ms                                                                                                               | 135 ms: 1.41x faster                                                                                                     |
| spectral_norm             | 152 ms                                                                                                               | 111 ms: 1.37x faster                                                                                                     |
| scimark_sor               | 174 ms                                                                                                               | 129 ms: 1.35x faster                                                                                                     |
| deepcopy_memo             | 41.3 us                                                                                                              | 32.8 us: 1.26x faster                                                                                                    |
| float                     | 112 ms                                                                                                               | 89.1 ms: 1.26x faster                                                                                                    |
| base64_small              | 494 us                                                                                                               | 400 us: 1.24x faster                                                                                                     |
| pickle_pure_python        | 451 us                                                                                                               | 389 us: 1.16x faster                                                                                                     |
| scimark_fft               | 493 ms                                                                                                               | 426 ms: 1.16x faster                                                                                                     |
| mako                      | 17.5 ms                                                                                                              | 15.3 ms: 1.15x faster                                                                                                    |
| base32_small              | 450 us                                                                                                               | 395 us: 1.14x faster                                                                                                     |
| base85_small              | 382 us                                                                                                               | 348 us: 1.10x faster                                                                                                     |
| deltablue                 | 4.96 ms                                                                                                              | 4.58 ms: 1.08x faster                                                                                                    |
| crypto_pyaes              | 107 ms                                                                                                               | 101 ms: 1.06x faster                                                                                                     |
| urlsafe_base64_small      | 554 us                                                                                                               | 524 us: 1.06x faster                                                                                                     |
| scimark_sparse_mat_mult   | 8.19 ms                                                                                                              | 7.86 ms: 1.04x faster                                                                                                    |
| regex_v8                  | 35.8 ms                                                                                                              | 34.4 ms: 1.04x faster                                                                                                    |
| ascii85_small             | 1.06 ms                                                                                                              | 1.02 ms: 1.04x faster                                                                                                    |
| json_dumps                | 13.2 ms                                                                                                              | 12.7 ms: 1.04x faster                                                                                                    |
| fannkuch                  | 569 ms                                                                                                               | 550 ms: 1.03x faster                                                                                                     |
| regex_dna                 | 275 ms                                                                                                               | 266 ms: 1.03x faster                                                                                                     |
| pyflate                   | 682 ms                                                                                                               | 662 ms: 1.03x faster                                                                                                     |
| bpe_tokeniser             | 6.85 sec                                                                                                             | 6.69 sec: 1.02x faster                                                                                                   |
| meteor_contest            | 139 ms                                                                                                               | 136 ms: 1.02x faster                                                                                                     |
| nqueens                   | 112 ms                                                                                                               | 110 ms: 1.02x faster                                                                                                     |
| base16_small              | 833 us                                                                                                               | 820 us: 1.02x faster                                                                                                     |
| json                      | 6.60 ms                                                                                                              | 6.50 ms: 1.02x faster                                                                                                    |
| sqlite_synth              | 4.55 us                                                                                                              | 4.48 us: 1.01x faster                                                                                                    |
| regex_effbot              | 4.55 ms                                                                                                              | 4.49 ms: 1.01x faster                                                                                                    |
| unpickle                  | 23.0 us                                                                                                              | 22.8 us: 1.01x faster                                                                                                    |
| 2to3                      | 402 ms                                                                                                               | 399 ms: 1.01x faster                                                                                                     |
| connected_components      | 733 ms                                                                                                               | 736 ms: 1.00x slower                                                                                                     |
| python_startup            | 17.4 ms                                                                                                              | 17.5 ms: 1.00x slower                                                                                                    |
| pathlib                   | 21.9 ms                                                                                                              | 22.0 ms: 1.01x slower                                                                                                    |
| create_gc_cycles          | 6.78 ms                                                                                                              | 6.83 ms: 1.01x slower                                                                                                    |
| ascii85_large             | 23.6 ms                                                                                                              | 23.8 ms: 1.01x slower                                                                                                    |
| gc_traversal              | 9.92 ms                                                                                                              | 10.0 ms: 1.01x slower                                                                                                    |
| base16_large              | 17.3 ms                                                                                                              | 17.4 ms: 1.01x slower                                                                                                    |
| base85_large              | 8.09 ms                                                                                                              | 8.16 ms: 1.01x slower                                                                                                    |
| python_startup_no_site    | 10.2 ms                                                                                                              | 10.3 ms: 1.01x slower                                                                                                    |
| asyncio_websockets        | 839 ms                                                                                                               | 848 ms: 1.01x slower                                                                                                     |
| logging_silent            | 155 ns                                                                                                               | 157 ns: 1.01x slower                                                                                                     |
| base64_large              | 4.29 ms                                                                                                              | 4.35 ms: 1.01x slower                                                                                                    |
| unpickle_list             | 8.34 us                                                                                                              | 8.47 us: 1.01x slower                                                                                                    |
| pickle_dict               | 48.9 us                                                                                                              | 49.7 us: 1.02x slower                                                                                                    |
| shortest_path             | 778 ms                                                                                                               | 792 ms: 1.02x slower                                                                                                     |
| generators                | 47.6 ms                                                                                                              | 48.5 ms: 1.02x slower                                                                                                    |
| subparsers                | 15.1 ms                                                                                                              | 15.4 ms: 1.02x slower                                                                                                    |
| xml_etree_parse           | 255 ms                                                                                                               | 261 ms: 1.02x slower                                                                                                     |
| asyncio_tcp_ssl           | 3.11 sec                                                                                                             | 3.22 sec: 1.04x slower                                                                                                   |
| async_tree_io             | 1.35 sec                                                                                                             | 1.39 sec: 1.04x slower                                                                                                   |
| async_tree_memoization_tg | 713 ms                                                                                                               | 744 ms: 1.04x slower                                                                                                     |
| async_generators          | 567 ms                                                                                                               | 592 ms: 1.04x slower                                                                                                     |
| comprehensions            | 24.6 us                                                                                                              | 25.7 us: 1.04x slower                                                                                                    |
| thrift                    | 1.18 ms                                                                                                              | 1.23 ms: 1.05x slower                                                                                                    |
| asyncio_tcp               | 699 ms                                                                                                               | 732 ms: 1.05x slower                                                                                                     |
| logging_simple            | 8.29 us                                                                                                              | 8.70 us: 1.05x slower                                                                                                    |
| logging_format            | 9.02 us                                                                                                              | 9.53 us: 1.06x slower                                                                                                    |
| sqlglot_v2_optimize       | 76.0 ms                                                                                                              | 81.5 ms: 1.07x slower                                                                                                    |
| sqlalchemy_declarative    | 157 ms                                                                                                               | 169 ms: 1.08x slower                                                                                                     |
| sqlglot_v2_normalize      | 155 ms                                                                                                               | 168 ms: 1.08x slower                                                                                                     |
| tornado_http              | 161 ms                                                                                                               | 176 ms: 1.09x slower                                                                                                     |
| sqlglot_v2_parse          | 1.64 ms                                                                                                              | 1.79 ms: 1.09x slower                                                                                                    |
| pprint_pformat            | 2.22 sec                                                                                                             | 2.43 sec: 1.10x slower                                                                                                   |
| raytrace                  | 396 ms                                                                                                               | 439 ms: 1.11x slower                                                                                                     |
| chaos                     | 83.4 ms                                                                                                              | 92.3 ms: 1.11x slower                                                                                                    |
| pprint_safe_repr          | 1.06 sec                                                                                                             | 1.18 sec: 1.11x slower                                                                                                   |
| sympy_integrate           | 23.9 ms                                                                                                              | 27.3 ms: 1.14x slower                                                                                                    |
| regex_compile             | 178 ms                                                                                                               | 204 ms: 1.14x slower                                                                                                     |
| sqlglot_v2_transpile      | 2.02 ms                                                                                                              | 2.32 ms: 1.15x slower                                                                                                    |
| sphinx                    | 1.50 sec                                                                                                             | 1.73 sec: 1.15x slower                                                                                                   |
| pylint                    | 167 ms                                                                                                               | 195 ms: 1.16x slower                                                                                                     |
| hexiom                    | 8.26 ms                                                                                                              | 9.64 ms: 1.17x slower                                                                                                    |
| go                        | 160 ms                                                                                                               | 189 ms: 1.18x slower                                                                                                     |
| many_optionals            | 870 us                                                                                                               | 1.03 ms: 1.18x slower                                                                                                    |
| telco                     | 198 ms                                                                                                               | 234 ms: 1.18x slower                                                                                                     |
| deepcopy                  | 360 us                                                                                                               | 434 us: 1.21x slower                                                                                                     |
| sympy_sum                 | 180 ms                                                                                                               | 217 ms: 1.21x slower                                                                                                     |
| mdp                       | 2.29 sec                                                                                                             | 2.79 sec: 1.22x slower                                                                                                   |
| sympy_str                 | 337 ms                                                                                                               | 417 ms: 1.24x slower                                                                                                     |
| sympy_expand              | 578 ms                                                                                                               | 718 ms: 1.24x slower                                                                                                     |
| tomli_loads               | 3.03 sec                                                                                                             | 3.77 sec: 1.24x slower                                                                                                   |
| docutils                  | 3.56 sec                                                                                                             | 4.43 sec: 1.24x slower                                                                                                   |
| deepcopy_reduce           | 4.18 us                                                                                                              | 5.21 us: 1.25x slower                                                                                                    |
| k_core                    | 4.03 sec                                                                                                             | 5.12 sec: 1.27x slower                                                                                                   |
| pycparser                 | 1.66 sec                                                                                                             | 2.14 sec: 1.29x slower                                                                                                   |
| dulwich_log               | 63.7 ms                                                                                                              | 83.7 ms: 1.31x slower                                                                                                    |
| sqlalchemy_imperative     | 20.5 ms                                                                                                              | 27.0 ms: 1.32x slower                                                                                                    |
| django_template           | 52.5 ms                                                                                                              | 70.8 ms: 1.35x slower                                                                                                    |
| xdsl_constant_fold        | 55.6 ms                                                                                                              | 75.3 ms: 1.36x slower                                                                                                    |
| html5lib                  | 71.3 ms                                                                                                              | 108 ms: 1.51x slower                                                                                                     |
| unpack_sequence           | 67.8 ns                                                                                                              | 157 ns: 2.32x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                | 1.03x slower                                                                                                             |

Benchmark hidden because not significant (22): async_tree_none_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, coroutines, coverage, unpickle_pure_python, scimark_monte_carlo, async_tree_none, xml_etree_iterparse, pidigits, typing_runtime_protocols, async_tree_cpu_io_mixed, json_loads, pickle, pickle_list, async_tree_io_tg, xml_etree_generate, base32_large, chameleon, xml_etree_process, bench_thread_pool, bench_mp_pool

- Geometric mean (including insignificant results): 1.016x slower

# HPT report

- Reliability score: 99.21% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.05x