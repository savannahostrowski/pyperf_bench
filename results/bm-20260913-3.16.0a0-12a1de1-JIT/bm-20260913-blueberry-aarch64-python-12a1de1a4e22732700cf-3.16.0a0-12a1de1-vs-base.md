# Results vs. base

- fork: python
- ref: 12a1de1a4e22732700cf
- machine: linux-aarch64
- commit hash: 12a1de1
- commit date: 2026-09-13
- overall geometric mean: 1.007x slower
- HPT reliability: 94.41%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.05x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 404 ms                                                                                                               | 409 ms: 1.01x slower                                                                                                     |
| chameleon      | 21.5 ms                                                                                                              | 20.7 ms: 1.04x faster                                                                                                    |
| docutils       | 3.71 sec                                                                                                             | 4.69 sec: 1.27x slower                                                                                                   |
| html5lib       | 75.0 ms                                                                                                              | 116 ms: 1.55x slower                                                                                                     |
| sphinx         | 1.54 sec                                                                                                             | 1.80 sec: 1.17x slower                                                                                                   |
| tornado_http   | 166 ms                                                                                                               | 185 ms: 1.11x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                | 1.16x slower                                                                                                             |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|---------------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| coroutines                | 40.9 ms                                                                                                              | 39.1 ms: 1.05x faster                                                                                                    |
| async_tree_none_tg        | 610 ms                                                                                                               | 593 ms: 1.03x faster                                                                                                     |
| async_generators          | 595 ms                                                                                                               | 610 ms: 1.02x slower                                                                                                     |
| asyncio_tcp_ssl           | 3.24 sec                                                                                                             | 3.39 sec: 1.05x slower                                                                                                   |
| async_tree_memoization_tg | 750 ms                                                                                                               | 785 ms: 1.05x slower                                                                                                     |
| async_tree_cpu_io_mixed   | 1.03 sec                                                                                                             | 1.09 sec: 1.05x slower                                                                                                   |
| asyncio_tcp               | 724 ms                                                                                                               | 784 ms: 1.08x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                | 1.01x slower                                                                                                             |

Benchmark hidden because not significant (6): async_tree_io_tg, async_tree_cpu_io_mixed_tg, asyncio_websockets, async_tree_none, async_tree_io, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 171 ms                                                                                                               | 109 ms: 1.57x faster                                                                                                     |
| float          | 117 ms                                                                                                               | 92.0 ms: 1.27x faster                                                                                                    |
| Geometric mean | (ref)                                                                                                                | 1.26x faster                                                                                                             |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 289 ms                                                                                                               | 267 ms: 1.08x faster                                                                                                     |
| regex_v8       | 38.4 ms                                                                                                              | 35.9 ms: 1.07x faster                                                                                                    |
| regex_effbot   | 4.86 ms                                                                                                              | 4.65 ms: 1.05x faster                                                                                                    |
| regex_compile  | 191 ms                                                                                                               | 216 ms: 1.13x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                | 1.02x faster                                                                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|----------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| base64_small         | 526 us                                                                                                               | 414 us: 1.27x faster                                                                                                     |
| base32_small         | 470 us                                                                                                               | 397 us: 1.19x faster                                                                                                     |
| pickle_pure_python   | 485 us                                                                                                               | 427 us: 1.13x faster                                                                                                     |
| base85_small         | 401 us                                                                                                               | 367 us: 1.10x faster                                                                                                     |
| base16_small         | 658 us                                                                                                               | 606 us: 1.09x faster                                                                                                     |
| json_dumps           | 14.0 ms                                                                                                              | 13.1 ms: 1.07x faster                                                                                                    |
| urlsafe_base64_small | 603 us                                                                                                               | 570 us: 1.06x faster                                                                                                     |
| xml_etree_parse      | 279 ms                                                                                                               | 264 ms: 1.06x faster                                                                                                     |
| ascii85_small        | 1.12 ms                                                                                                              | 1.06 ms: 1.05x faster                                                                                                    |
| json_loads           | 39.7 us                                                                                                              | 38.6 us: 1.03x faster                                                                                                    |
| unpickle             | 24.1 us                                                                                                              | 23.5 us: 1.02x faster                                                                                                    |
| xml_etree_iterparse  | 209 ms                                                                                                               | 205 ms: 1.02x faster                                                                                                     |
| unpickle_list        | 8.61 us                                                                                                              | 8.97 us: 1.04x slower                                                                                                    |
| tomli_loads          | 3.17 sec                                                                                                             | 3.97 sec: 1.25x slower                                                                                                   |
| Geometric mean       | (ref)                                                                                                                | 1.03x faster                                                                                                             |

Benchmark hidden because not significant (11): xml_etree_generate, unpickle_pure_python, ascii85_large, xml_etree_process, base16_large, base85_large, pickle_dict, pickle_list, base32_large, pickle, base64_large

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|------------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 18.0 ms                                                                                                              | 18.0 ms: 1.00x slower                                                                                                    |
| python_startup_no_site | 10.5 ms                                                                                                              | 10.6 ms: 1.01x slower                                                                                                    |
| Geometric mean         | (ref)                                                                                                                | 1.01x slower                                                                                                             |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|-----------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.0 ms                                                                                                              | 16.1 ms: 1.18x faster                                                                                                    |
| django_template | 56.9 ms                                                                                                              | 77.7 ms: 1.36x slower                                                                                                    |
| Geometric mean  | (ref)                                                                                                                | 1.07x slower                                                                                                             |

All benchmarks:
===============

| Benchmark                 | results/bm-20260913-3.16.0a0-12a1de1/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json | results/bm-20260913-3.16.0a0-12a1de1-JIT/bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json |
|---------------------------|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|
| richards_super            | 80.2 ms                                                                                                              | 49.8 ms: 1.61x faster                                                                                                    |
| richards                  | 69.9 ms                                                                                                              | 44.6 ms: 1.57x faster                                                                                                    |
| nbody                     | 171 ms                                                                                                               | 109 ms: 1.57x faster                                                                                                     |
| scimark_lu                | 198 ms                                                                                                               | 137 ms: 1.45x faster                                                                                                     |
| scimark_sor               | 184 ms                                                                                                               | 127 ms: 1.45x faster                                                                                                     |
| spectral_norm             | 159 ms                                                                                                               | 116 ms: 1.37x faster                                                                                                     |
| float                     | 117 ms                                                                                                               | 92.0 ms: 1.27x faster                                                                                                    |
| base64_small              | 526 us                                                                                                               | 414 us: 1.27x faster                                                                                                     |
| deepcopy_memo             | 43.9 us                                                                                                              | 34.9 us: 1.26x faster                                                                                                    |
| base32_small              | 470 us                                                                                                               | 397 us: 1.19x faster                                                                                                     |
| mako                      | 19.0 ms                                                                                                              | 16.1 ms: 1.18x faster                                                                                                    |
| scimark_fft               | 516 ms                                                                                                               | 437 ms: 1.18x faster                                                                                                     |
| pickle_pure_python        | 485 us                                                                                                               | 427 us: 1.13x faster                                                                                                     |
| deltablue                 | 5.24 ms                                                                                                              | 4.69 ms: 1.12x faster                                                                                                    |
| scimark_sparse_mat_mult   | 8.49 ms                                                                                                              | 7.70 ms: 1.10x faster                                                                                                    |
| base85_small              | 401 us                                                                                                               | 367 us: 1.10x faster                                                                                                     |
| base16_small              | 658 us                                                                                                               | 606 us: 1.09x faster                                                                                                     |
| regex_dna                 | 289 ms                                                                                                               | 267 ms: 1.08x faster                                                                                                     |
| json_dumps                | 14.0 ms                                                                                                              | 13.1 ms: 1.07x faster                                                                                                    |
| regex_v8                  | 38.4 ms                                                                                                              | 35.9 ms: 1.07x faster                                                                                                    |
| urlsafe_base64_small      | 603 us                                                                                                               | 570 us: 1.06x faster                                                                                                     |
| xml_etree_parse           | 279 ms                                                                                                               | 264 ms: 1.06x faster                                                                                                     |
| ascii85_small             | 1.12 ms                                                                                                              | 1.06 ms: 1.05x faster                                                                                                    |
| regex_effbot              | 4.86 ms                                                                                                              | 4.65 ms: 1.05x faster                                                                                                    |
| coroutines                | 40.9 ms                                                                                                              | 39.1 ms: 1.05x faster                                                                                                    |
| chameleon                 | 21.5 ms                                                                                                              | 20.7 ms: 1.04x faster                                                                                                    |
| crypto_pyaes              | 109 ms                                                                                                               | 105 ms: 1.04x faster                                                                                                     |
| fannkuch                  | 603 ms                                                                                                               | 582 ms: 1.04x faster                                                                                                     |
| typing_runtime_protocols  | 191 us                                                                                                               | 185 us: 1.03x faster                                                                                                     |
| nqueens                   | 123 ms                                                                                                               | 119 ms: 1.03x faster                                                                                                     |
| json_loads                | 39.7 us                                                                                                              | 38.6 us: 1.03x faster                                                                                                    |
| async_tree_none_tg        | 610 ms                                                                                                               | 593 ms: 1.03x faster                                                                                                     |
| meteor_contest            | 148 ms                                                                                                               | 144 ms: 1.03x faster                                                                                                     |
| unpickle                  | 24.1 us                                                                                                              | 23.5 us: 1.02x faster                                                                                                    |
| json                      | 6.91 ms                                                                                                              | 6.77 ms: 1.02x faster                                                                                                    |
| xml_etree_iterparse       | 209 ms                                                                                                               | 205 ms: 1.02x faster                                                                                                     |
| bpe_tokeniser             | 7.24 sec                                                                                                             | 7.13 sec: 1.02x faster                                                                                                   |
| pyflate                   | 705 ms                                                                                                               | 695 ms: 1.02x faster                                                                                                     |
| connected_components      | 749 ms                                                                                                               | 740 ms: 1.01x faster                                                                                                     |
| python_startup            | 18.0 ms                                                                                                              | 18.0 ms: 1.00x slower                                                                                                    |
| shortest_path             | 795 ms                                                                                                               | 799 ms: 1.01x slower                                                                                                     |
| create_gc_cycles          | 6.89 ms                                                                                                              | 6.93 ms: 1.01x slower                                                                                                    |
| python_startup_no_site    | 10.5 ms                                                                                                              | 10.6 ms: 1.01x slower                                                                                                    |
| 2to3                      | 404 ms                                                                                                               | 409 ms: 1.01x slower                                                                                                     |
| pprint_pformat            | 2.39 sec                                                                                                             | 2.44 sec: 1.02x slower                                                                                                   |
| async_generators          | 595 ms                                                                                                               | 610 ms: 1.02x slower                                                                                                     |
| logging_format            | 9.57 us                                                                                                              | 9.80 us: 1.02x slower                                                                                                    |
| pprint_safe_repr          | 1.14 sec                                                                                                             | 1.18 sec: 1.03x slower                                                                                                   |
| unpickle_list             | 8.61 us                                                                                                              | 8.97 us: 1.04x slower                                                                                                    |
| chaos                     | 89.5 ms                                                                                                              | 93.5 ms: 1.05x slower                                                                                                    |
| asyncio_tcp_ssl           | 3.24 sec                                                                                                             | 3.39 sec: 1.05x slower                                                                                                   |
| logging_simple            | 8.62 us                                                                                                              | 9.02 us: 1.05x slower                                                                                                    |
| async_tree_memoization_tg | 750 ms                                                                                                               | 785 ms: 1.05x slower                                                                                                     |
| async_tree_cpu_io_mixed   | 1.03 sec                                                                                                             | 1.09 sec: 1.05x slower                                                                                                   |
| subparsers                | 15.2 ms                                                                                                              | 16.0 ms: 1.05x slower                                                                                                    |
| sqlalchemy_declarative    | 169 ms                                                                                                               | 178 ms: 1.06x slower                                                                                                     |
| raytrace                  | 425 ms                                                                                                               | 452 ms: 1.07x slower                                                                                                     |
| thrift                    | 1.21 ms                                                                                                              | 1.30 ms: 1.07x slower                                                                                                    |
| asyncio_tcp               | 724 ms                                                                                                               | 784 ms: 1.08x slower                                                                                                     |
| sqlglot_v2_optimize       | 80.6 ms                                                                                                              | 87.4 ms: 1.08x slower                                                                                                    |
| sqlglot_v2_normalize      | 164 ms                                                                                                               | 181 ms: 1.10x slower                                                                                                     |
| tornado_http              | 166 ms                                                                                                               | 185 ms: 1.11x slower                                                                                                     |
| sqlglot_v2_transpile      | 2.14 ms                                                                                                              | 2.40 ms: 1.12x slower                                                                                                    |
| hexiom                    | 8.72 ms                                                                                                              | 9.81 ms: 1.12x slower                                                                                                    |
| regex_compile             | 191 ms                                                                                                               | 216 ms: 1.13x slower                                                                                                     |
| sqlglot_v2_parse          | 1.71 ms                                                                                                              | 1.94 ms: 1.14x slower                                                                                                    |
| pylint                    | 176 ms                                                                                                               | 201 ms: 1.14x slower                                                                                                     |
| sympy_integrate           | 24.7 ms                                                                                                              | 28.5 ms: 1.15x slower                                                                                                    |
| telco                     | 207 ms                                                                                                               | 241 ms: 1.16x slower                                                                                                     |
| sphinx                    | 1.54 sec                                                                                                             | 1.80 sec: 1.17x slower                                                                                                   |
| go                        | 169 ms                                                                                                               | 203 ms: 1.20x slower                                                                                                     |
| mdp                       | 2.39 sec                                                                                                             | 2.88 sec: 1.20x slower                                                                                                   |
| many_optionals            | 876 us                                                                                                               | 1.06 ms: 1.21x slower                                                                                                    |
| sympy_sum                 | 189 ms                                                                                                               | 229 ms: 1.21x slower                                                                                                     |
| sympy_expand              | 618 ms                                                                                                               | 748 ms: 1.21x slower                                                                                                     |
| sympy_str                 | 353 ms                                                                                                               | 433 ms: 1.23x slower                                                                                                     |
| deepcopy                  | 384 us                                                                                                               | 474 us: 1.23x slower                                                                                                     |
| tomli_loads               | 3.17 sec                                                                                                             | 3.97 sec: 1.25x slower                                                                                                   |
| docutils                  | 3.71 sec                                                                                                             | 4.69 sec: 1.27x slower                                                                                                   |
| k_core                    | 4.07 sec                                                                                                             | 5.16 sec: 1.27x slower                                                                                                   |
| pycparser                 | 1.74 sec                                                                                                             | 2.29 sec: 1.31x slower                                                                                                   |
| dulwich_log               | 67.2 ms                                                                                                              | 88.9 ms: 1.32x slower                                                                                                    |
| deepcopy_reduce           | 4.30 us                                                                                                              | 5.75 us: 1.34x slower                                                                                                    |
| xdsl_constant_fold        | 58.1 ms                                                                                                              | 78.0 ms: 1.34x slower                                                                                                    |
| sqlalchemy_imperative     | 21.6 ms                                                                                                              | 29.1 ms: 1.35x slower                                                                                                    |
| django_template           | 56.9 ms                                                                                                              | 77.7 ms: 1.36x slower                                                                                                    |
| html5lib                  | 75.0 ms                                                                                                              | 116 ms: 1.55x slower                                                                                                     |
| unpack_sequence           | 67.8 ns                                                                                                              | 163 ns: 2.41x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                | 1.02x slower                                                                                                             |

Benchmark hidden because not significant (28): logging_silent, xml_etree_generate, coverage, unpickle_pure_python, async_tree_io_tg, ascii85_large, pathlib, xml_etree_process, async_tree_cpu_io_mixed_tg, generators, base16_large, pidigits, asyncio_websockets, async_tree_none, gc_traversal, async_tree_io, base85_large, pickle_dict, scimark_monte_carlo, pickle_list, base32_large, comprehensions, bench_thread_pool, sqlite_synth, pickle, async_tree_memoization, base64_large, bench_mp_pool

- Geometric mean (including insignificant results): 1.007x slower

# HPT report

- Reliability score: 94.41% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.05x