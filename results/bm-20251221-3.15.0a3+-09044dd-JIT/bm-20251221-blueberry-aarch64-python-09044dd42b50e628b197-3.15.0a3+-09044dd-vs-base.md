# Results vs. base

- fork: python
- ref: 09044dd42b50e628b197
- machine: linux-aarch64
- commit hash: 09044dd
- commit date: 2025-12-21
- overall geometric mean: 1.014x slower
- HPT reliability: 96.06%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 424 ms                                                                                                                 | 426 ms: 1.00x slower                                                                                                       |
| docutils       | 4.25 sec                                                                                                               | 4.75 sec: 1.12x slower                                                                                                     |
| html5lib       | 78.2 ms                                                                                                                | 91.6 ms: 1.17x slower                                                                                                      |
| sphinx         | 1.47 sec                                                                                                               | 1.64 sec: 1.12x slower                                                                                                     |
| tornado_http   | 162 ms                                                                                                                 | 171 ms: 1.06x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.08x slower                                                                                                               |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp               | 1.15 sec                                                                                                               | 1.05 sec: 1.09x faster                                                                                                     |
| async_tree_io_tg          | 1.22 sec                                                                                                               | 1.26 sec: 1.03x slower                                                                                                     |
| async_tree_memoization_tg | 636 ms                                                                                                                 | 675 ms: 1.06x slower                                                                                                       |
| async_generators          | 567 ms                                                                                                                 | 604 ms: 1.07x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (9): async_tree_none_tg, async_tree_memoization, coroutines, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_none, asyncio_websockets, asyncio_tcp_ssl, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 164 ms                                                                                                                 | 136 ms: 1.21x faster                                                                                                       |
| float          | 130 ms                                                                                                                 | 117 ms: 1.11x faster                                                                                                       |
| pidigits       | 327 ms                                                                                                                 | 328 ms: 1.00x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.10x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 281 ms                                                                                                                 | 289 ms: 1.03x slower                                                                                                       |
| regex_effbot   | 4.39 ms                                                                                                                | 4.70 ms: 1.07x slower                                                                                                      |
| regex_compile  | 143 ms                                                                                                                 | 161 ms: 1.12x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                                                                                 | 272 us: 1.18x faster                                                                                                       |
| pickle_pure_python   | 455 us                                                                                                                 | 390 us: 1.17x faster                                                                                                       |
| json_dumps           | 14.4 ms                                                                                                                | 13.5 ms: 1.07x faster                                                                                                      |
| xml_etree_generate   | 131 ms                                                                                                                 | 128 ms: 1.02x faster                                                                                                       |
| xml_etree_process    | 98.4 ms                                                                                                                | 96.5 ms: 1.02x faster                                                                                                      |
| xml_etree_parse      | 248 ms                                                                                                                 | 246 ms: 1.01x faster                                                                                                       |
| tomli_loads          | 3.24 sec                                                                                                               | 3.27 sec: 1.01x slower                                                                                                     |
| json_loads           | 38.7 us                                                                                                                | 39.0 us: 1.01x slower                                                                                                      |
| unpickle_list        | 8.16 us                                                                                                                | 8.32 us: 1.02x slower                                                                                                      |
| unpickle             | 22.5 us                                                                                                                | 23.0 us: 1.02x slower                                                                                                      |
| pickle_dict          | 46.8 us                                                                                                                | 48.2 us: 1.03x slower                                                                                                      |
| pickle               | 18.5 us                                                                                                                | 19.3 us: 1.04x slower                                                                                                      |
| pickle_list          | 6.78 us                                                                                                                | 7.09 us: 1.05x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.7 ms                                                                                                                | 18.0 ms: 1.01x slower                                                                                                      |
| python_startup_no_site | 10.3 ms                                                                                                                | 10.5 ms: 1.02x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.1 ms                                                                                                                | 18.4 ms: 1.09x faster                                                                                                      |
| django_template | 52.4 ms                                                                                                                | 54.5 ms: 1.04x slower                                                                                                      |
| genshi_text     | 33.6 ms                                                                                                                | 37.0 ms: 1.10x slower                                                                                                      |
| genshi_xml      | 75.9 ms                                                                                                                | 101 ms: 1.33x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.09x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251221-3.15.0a3+-09044dd/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json | results/bm-20251221-3.15.0a3+-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3+-09044dd.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 63.0 ms                                                                                                                | 40.3 ms: 1.56x faster                                                                                                      |
| richards_super            | 71.3 ms                                                                                                                | 46.9 ms: 1.52x faster                                                                                                      |
| logging_silent            | 165 ns                                                                                                                 | 124 ns: 1.33x faster                                                                                                       |
| nbody                     | 164 ms                                                                                                                 | 136 ms: 1.21x faster                                                                                                       |
| unpickle_pure_python      | 321 us                                                                                                                 | 272 us: 1.18x faster                                                                                                       |
| pickle_pure_python        | 455 us                                                                                                                 | 390 us: 1.17x faster                                                                                                       |
| deepcopy_memo             | 43.4 us                                                                                                                | 37.8 us: 1.15x faster                                                                                                      |
| deltablue                 | 5.16 ms                                                                                                                | 4.50 ms: 1.15x faster                                                                                                      |
| float                     | 130 ms                                                                                                                 | 117 ms: 1.11x faster                                                                                                       |
| asyncio_tcp               | 1.15 sec                                                                                                               | 1.05 sec: 1.09x faster                                                                                                     |
| mako                      | 20.1 ms                                                                                                                | 18.4 ms: 1.09x faster                                                                                                      |
| fannkuch                  | 615 ms                                                                                                                 | 566 ms: 1.09x faster                                                                                                       |
| spectral_norm             | 155 ms                                                                                                                 | 143 ms: 1.09x faster                                                                                                       |
| scimark_fft               | 483 ms                                                                                                                 | 444 ms: 1.09x faster                                                                                                       |
| scimark_monte_carlo       | 98.9 ms                                                                                                                | 91.7 ms: 1.08x faster                                                                                                      |
| json_dumps                | 14.4 ms                                                                                                                | 13.5 ms: 1.07x faster                                                                                                      |
| pyflate                   | 723 ms                                                                                                                 | 679 ms: 1.06x faster                                                                                                       |
| bpe_tokeniser             | 7.37 sec                                                                                                               | 7.01 sec: 1.05x faster                                                                                                     |
| scimark_sor               | 172 ms                                                                                                                 | 165 ms: 1.04x faster                                                                                                       |
| crypto_pyaes              | 108 ms                                                                                                                 | 103 ms: 1.04x faster                                                                                                       |
| json                      | 6.81 ms                                                                                                                | 6.66 ms: 1.02x faster                                                                                                      |
| xml_etree_generate        | 131 ms                                                                                                                 | 128 ms: 1.02x faster                                                                                                       |
| xml_etree_process         | 98.4 ms                                                                                                                | 96.5 ms: 1.02x faster                                                                                                      |
| k_core                    | 4.08 sec                                                                                                               | 4.01 sec: 1.02x faster                                                                                                     |
| meteor_contest            | 140 ms                                                                                                                 | 137 ms: 1.02x faster                                                                                                       |
| go                        | 162 ms                                                                                                                 | 160 ms: 1.02x faster                                                                                                       |
| logging_simple            | 8.35 us                                                                                                                | 8.24 us: 1.01x faster                                                                                                      |
| sqlite_synth              | 4.70 us                                                                                                                | 4.64 us: 1.01x faster                                                                                                      |
| connected_components      | 841 ms                                                                                                                 | 833 ms: 1.01x faster                                                                                                       |
| xml_etree_parse           | 248 ms                                                                                                                 | 246 ms: 1.01x faster                                                                                                       |
| shortest_path             | 896 ms                                                                                                                 | 889 ms: 1.01x faster                                                                                                       |
| pidigits                  | 327 ms                                                                                                                 | 328 ms: 1.00x slower                                                                                                       |
| 2to3                      | 424 ms                                                                                                                 | 426 ms: 1.00x slower                                                                                                       |
| tomli_loads               | 3.24 sec                                                                                                               | 3.27 sec: 1.01x slower                                                                                                     |
| json_loads                | 38.7 us                                                                                                                | 39.0 us: 1.01x slower                                                                                                      |
| python_startup            | 17.7 ms                                                                                                                | 18.0 ms: 1.01x slower                                                                                                      |
| scimark_lu                | 168 ms                                                                                                                 | 171 ms: 1.02x slower                                                                                                       |
| unpickle_list             | 8.16 us                                                                                                                | 8.32 us: 1.02x slower                                                                                                      |
| chaos                     | 87.6 ms                                                                                                                | 89.4 ms: 1.02x slower                                                                                                      |
| python_startup_no_site    | 10.3 ms                                                                                                                | 10.5 ms: 1.02x slower                                                                                                      |
| unpickle                  | 22.5 us                                                                                                                | 23.0 us: 1.02x slower                                                                                                      |
| regex_dna                 | 281 ms                                                                                                                 | 289 ms: 1.03x slower                                                                                                       |
| pickle_dict               | 46.8 us                                                                                                                | 48.2 us: 1.03x slower                                                                                                      |
| async_tree_io_tg          | 1.22 sec                                                                                                               | 1.26 sec: 1.03x slower                                                                                                     |
| telco                     | 192 ms                                                                                                                 | 199 ms: 1.04x slower                                                                                                       |
| deepcopy_reduce           | 4.22 us                                                                                                                | 4.37 us: 1.04x slower                                                                                                      |
| scimark_sparse_mat_mult   | 8.05 ms                                                                                                                | 8.36 ms: 1.04x slower                                                                                                      |
| django_template           | 52.4 ms                                                                                                                | 54.5 ms: 1.04x slower                                                                                                      |
| pickle                    | 18.5 us                                                                                                                | 19.3 us: 1.04x slower                                                                                                      |
| pickle_list               | 6.78 us                                                                                                                | 7.09 us: 1.05x slower                                                                                                      |
| sqlglot_v2_parse          | 1.66 ms                                                                                                                | 1.74 ms: 1.05x slower                                                                                                      |
| pathlib                   | 22.0 ms                                                                                                                | 23.1 ms: 1.05x slower                                                                                                      |
| raytrace                  | 393 ms                                                                                                                 | 414 ms: 1.05x slower                                                                                                       |
| tornado_http              | 162 ms                                                                                                                 | 171 ms: 1.06x slower                                                                                                       |
| sqlglot_v2_transpile      | 2.16 ms                                                                                                                | 2.29 ms: 1.06x slower                                                                                                      |
| async_tree_memoization_tg | 636 ms                                                                                                                 | 675 ms: 1.06x slower                                                                                                       |
| async_generators          | 567 ms                                                                                                                 | 604 ms: 1.07x slower                                                                                                       |
| sqlalchemy_declarative    | 156 ms                                                                                                                 | 166 ms: 1.07x slower                                                                                                       |
| regex_effbot              | 4.39 ms                                                                                                                | 4.70 ms: 1.07x slower                                                                                                      |
| pprint_safe_repr          | 1.02 sec                                                                                                               | 1.10 sec: 1.07x slower                                                                                                     |
| thrift                    | 1.11 ms                                                                                                                | 1.19 ms: 1.07x slower                                                                                                      |
| sympy_integrate           | 23.3 ms                                                                                                                | 25.1 ms: 1.08x slower                                                                                                      |
| many_optionals            | 926 us                                                                                                                 | 1.01 ms: 1.09x slower                                                                                                      |
| pprint_pformat            | 2.11 sec                                                                                                               | 2.31 sec: 1.09x slower                                                                                                     |
| xdsl_constant_fold        | 56.1 ms                                                                                                                | 61.4 ms: 1.09x slower                                                                                                      |
| genshi_text               | 33.6 ms                                                                                                                | 37.0 ms: 1.10x slower                                                                                                      |
| pylint                    | 412 ms                                                                                                                 | 455 ms: 1.10x slower                                                                                                       |
| typing_runtime_protocols  | 226 us                                                                                                                 | 250 us: 1.11x slower                                                                                                       |
| sqlalchemy_imperative     | 20.4 ms                                                                                                                | 22.7 ms: 1.11x slower                                                                                                      |
| docutils                  | 4.25 sec                                                                                                               | 4.75 sec: 1.12x slower                                                                                                     |
| sphinx                    | 1.47 sec                                                                                                               | 1.64 sec: 1.12x slower                                                                                                     |
| pycparser                 | 1.48 sec                                                                                                               | 1.66 sec: 1.12x slower                                                                                                     |
| hexiom                    | 8.63 ms                                                                                                                | 9.67 ms: 1.12x slower                                                                                                      |
| sqlglot_v2_optimize       | 72.7 ms                                                                                                                | 81.6 ms: 1.12x slower                                                                                                      |
| regex_compile             | 143 ms                                                                                                                 | 161 ms: 1.12x slower                                                                                                       |
| mdp                       | 2.47 sec                                                                                                               | 2.78 sec: 1.13x slower                                                                                                     |
| sqlglot_v2_normalize      | 148 ms                                                                                                                 | 168 ms: 1.13x slower                                                                                                       |
| deepcopy                  | 374 us                                                                                                                 | 429 us: 1.15x slower                                                                                                       |
| sympy_sum                 | 172 ms                                                                                                                 | 198 ms: 1.15x slower                                                                                                       |
| html5lib                  | 78.2 ms                                                                                                                | 91.6 ms: 1.17x slower                                                                                                      |
| nqueens                   | 119 ms                                                                                                                 | 140 ms: 1.17x slower                                                                                                       |
| sympy_str                 | 322 ms                                                                                                                 | 381 ms: 1.18x slower                                                                                                       |
| sympy_expand              | 555 ms                                                                                                                 | 661 ms: 1.19x slower                                                                                                       |
| dulwich_log               | 62.7 ms                                                                                                                | 78.1 ms: 1.25x slower                                                                                                      |
| unpack_sequence           | 69.1 ns                                                                                                                | 87.8 ns: 1.27x slower                                                                                                      |
| genshi_xml                | 75.9 ms                                                                                                                | 101 ms: 1.33x slower                                                                                                       |
| bench_mp_pool             | 176 ms                                                                                                                 | 241 ms: 1.37x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (20): async_tree_none_tg, async_tree_memoization, coroutines, async_tree_cpu_io_mixed_tg, comprehensions, generators, gc_traversal, logging_format, async_tree_cpu_io_mixed, async_tree_none, regex_v8, chameleon, asyncio_websockets, create_gc_cycles, xml_etree_iterparse, subparsers, asyncio_tcp_ssl, async_tree_io, coverage, bench_thread_pool

- Geometric mean (including insignificant results): 1.014x slower

# HPT report

- Reliability score: 96.06% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x