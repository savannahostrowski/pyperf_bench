# Results vs. base

- fork: python
- ref: ccbe41e27cdb44103318
- machine: linux-aarch64
- commit hash: ccbe41e
- commit date: 2026-01-30
- overall geometric mean: 1.023x faster
- HPT reliability: 75.28%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 20.1 ms                                                                                                                | 19.9 ms: 1.01x faster                                                                                                      |
| docutils       | 4.20 sec                                                                                                               | 4.55 sec: 1.08x slower                                                                                                     |
| html5lib       | 77.8 ms                                                                                                                | 81.5 ms: 1.05x slower                                                                                                      |
| sphinx         | 1.49 sec                                                                                                               | 1.55 sec: 1.04x slower                                                                                                     |
| tornado_http   | 163 ms                                                                                                                 | 164 ms: 1.01x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|--------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg | 546 ms                                                                                                                 | 529 ms: 1.03x faster                                                                                                       |
| async_tree_io_tg   | 1.24 sec                                                                                                               | 1.20 sec: 1.03x faster                                                                                                     |
| asyncio_tcp        | 1.18 sec                                                                                                               | 1.16 sec: 1.02x faster                                                                                                     |
| coroutines         | 36.7 ms                                                                                                                | 37.1 ms: 1.01x slower                                                                                                      |
| async_generators   | 566 ms                                                                                                                 | 599 ms: 1.06x slower                                                                                                       |
| Geometric mean     | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (8): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization, asyncio_websockets, asyncio_tcp_ssl, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 160 ms                                                                                                                 | 131 ms: 1.22x faster                                                                                                       |
| float          | 132 ms                                                                                                                 | 114 ms: 1.16x faster                                                                                                       |
| pidigits       | 325 ms                                                                                                                 | 327 ms: 1.01x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 143 ms                                                                                                                 | 138 ms: 1.04x faster                                                                                                       |
| regex_effbot   | 4.49 ms                                                                                                                | 4.40 ms: 1.02x faster                                                                                                      |
| regex_v8       | 36.1 ms                                                                                                                | 35.8 ms: 1.01x faster                                                                                                      |
| regex_dna      | 281 ms                                                                                                                 | 280 ms: 1.00x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 320 us                                                                                                                 | 247 us: 1.30x faster                                                                                                       |
| pickle_pure_python   | 460 us                                                                                                                 | 395 us: 1.16x faster                                                                                                       |
| tomli_loads          | 2.83 sec                                                                                                               | 2.57 sec: 1.10x faster                                                                                                     |
| xml_etree_process    | 98.7 ms                                                                                                                | 91.7 ms: 1.08x faster                                                                                                      |
| json_dumps           | 13.8 ms                                                                                                                | 12.9 ms: 1.07x faster                                                                                                      |
| xml_etree_generate   | 128 ms                                                                                                                 | 120 ms: 1.07x faster                                                                                                       |
| pickle_list          | 6.86 us                                                                                                                | 6.74 us: 1.02x faster                                                                                                      |
| xml_etree_parse      | 244 ms                                                                                                                 | 241 ms: 1.01x faster                                                                                                       |
| pickle               | 18.8 us                                                                                                                | 18.6 us: 1.01x faster                                                                                                      |
| unpickle_list        | 8.04 us                                                                                                                | 8.02 us: 1.00x faster                                                                                                      |
| json_loads           | 38.0 us                                                                                                                | 37.9 us: 1.00x faster                                                                                                      |
| pickle_dict          | 46.6 us                                                                                                                | 46.8 us: 1.00x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.06x faster                                                                                                               |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.7 ms                                                                                                                | 17.3 ms: 1.02x faster                                                                                                      |
| python_startup_no_site | 10.3 ms                                                                                                                | 10.3 ms: 1.01x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 19.8 ms                                                                                                                | 17.4 ms: 1.14x faster                                                                                                      |
| genshi_text    | 32.2 ms                                                                                                                | 35.4 ms: 1.10x slower                                                                                                      |
| genshi_xml     | 73.6 ms                                                                                                                | 92.8 ms: 1.26x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                | results/bm-20260130-3.15.0a5+-ccbe41e/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json | results/bm-20260130-3.15.0a5+-ccbe41e-JIT/bm-20260130-blueberry-aarch64-python-ccbe41e27cdb44103318-3.15.0a5+-ccbe41e.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 63.4 ms                                                                                                                | 37.4 ms: 1.69x faster                                                                                                      |
| richards_super           | 71.4 ms                                                                                                                | 44.6 ms: 1.60x faster                                                                                                      |
| scimark_lu               | 166 ms                                                                                                                 | 119 ms: 1.39x faster                                                                                                       |
| logging_silent           | 157 ns                                                                                                                 | 119 ns: 1.32x faster                                                                                                       |
| scimark_sor              | 169 ms                                                                                                                 | 129 ms: 1.32x faster                                                                                                       |
| unpickle_pure_python     | 320 us                                                                                                                 | 247 us: 1.30x faster                                                                                                       |
| deepcopy_memo            | 39.9 us                                                                                                                | 32.4 us: 1.23x faster                                                                                                      |
| nbody                    | 160 ms                                                                                                                 | 131 ms: 1.22x faster                                                                                                       |
| deltablue                | 4.87 ms                                                                                                                | 4.16 ms: 1.17x faster                                                                                                      |
| pickle_pure_python       | 460 us                                                                                                                 | 395 us: 1.16x faster                                                                                                       |
| float                    | 132 ms                                                                                                                 | 114 ms: 1.16x faster                                                                                                       |
| scimark_fft              | 482 ms                                                                                                                 | 416 ms: 1.16x faster                                                                                                       |
| spectral_norm            | 150 ms                                                                                                                 | 132 ms: 1.14x faster                                                                                                       |
| mako                     | 19.8 ms                                                                                                                | 17.4 ms: 1.14x faster                                                                                                      |
| tomli_loads              | 2.83 sec                                                                                                               | 2.57 sec: 1.10x faster                                                                                                     |
| xml_etree_process        | 98.7 ms                                                                                                                | 91.7 ms: 1.08x faster                                                                                                      |
| fannkuch                 | 579 ms                                                                                                                 | 539 ms: 1.07x faster                                                                                                       |
| json_dumps               | 13.8 ms                                                                                                                | 12.9 ms: 1.07x faster                                                                                                      |
| xml_etree_generate       | 128 ms                                                                                                                 | 120 ms: 1.07x faster                                                                                                       |
| pyflate                  | 731 ms                                                                                                                 | 685 ms: 1.07x faster                                                                                                       |
| scimark_sparse_mat_mult  | 8.10 ms                                                                                                                | 7.62 ms: 1.06x faster                                                                                                      |
| create_gc_cycles         | 9.12 ms                                                                                                                | 8.66 ms: 1.05x faster                                                                                                      |
| regex_compile            | 143 ms                                                                                                                 | 138 ms: 1.04x faster                                                                                                       |
| scimark_monte_carlo      | 98.6 ms                                                                                                                | 95.1 ms: 1.04x faster                                                                                                      |
| bpe_tokeniser            | 6.88 sec                                                                                                               | 6.66 sec: 1.03x faster                                                                                                     |
| async_tree_none_tg       | 546 ms                                                                                                                 | 529 ms: 1.03x faster                                                                                                       |
| connected_components     | 849 ms                                                                                                                 | 824 ms: 1.03x faster                                                                                                       |
| json                     | 6.73 ms                                                                                                                | 6.54 ms: 1.03x faster                                                                                                      |
| crypto_pyaes             | 99.6 ms                                                                                                                | 97.1 ms: 1.03x faster                                                                                                      |
| async_tree_io_tg         | 1.24 sec                                                                                                               | 1.20 sec: 1.03x faster                                                                                                     |
| regex_effbot             | 4.49 ms                                                                                                                | 4.40 ms: 1.02x faster                                                                                                      |
| deepcopy_reduce          | 3.95 us                                                                                                                | 3.87 us: 1.02x faster                                                                                                      |
| python_startup           | 17.7 ms                                                                                                                | 17.3 ms: 1.02x faster                                                                                                      |
| shortest_path            | 898 ms                                                                                                                 | 881 ms: 1.02x faster                                                                                                       |
| pickle_list              | 6.86 us                                                                                                                | 6.74 us: 1.02x faster                                                                                                      |
| asyncio_tcp              | 1.18 sec                                                                                                               | 1.16 sec: 1.02x faster                                                                                                     |
| xml_etree_parse          | 244 ms                                                                                                                 | 241 ms: 1.01x faster                                                                                                       |
| meteor_contest           | 135 ms                                                                                                                 | 134 ms: 1.01x faster                                                                                                       |
| sqlite_synth             | 4.47 us                                                                                                                | 4.42 us: 1.01x faster                                                                                                      |
| pickle                   | 18.8 us                                                                                                                | 18.6 us: 1.01x faster                                                                                                      |
| gc_traversal             | 14.6 ms                                                                                                                | 14.5 ms: 1.01x faster                                                                                                      |
| chameleon                | 20.1 ms                                                                                                                | 19.9 ms: 1.01x faster                                                                                                      |
| regex_v8                 | 36.1 ms                                                                                                                | 35.8 ms: 1.01x faster                                                                                                      |
| logging_simple           | 7.97 us                                                                                                                | 7.93 us: 1.01x faster                                                                                                      |
| regex_dna                | 281 ms                                                                                                                 | 280 ms: 1.00x faster                                                                                                       |
| k_core                   | 4.09 sec                                                                                                               | 4.07 sec: 1.00x faster                                                                                                     |
| bench_thread_pool        | 1.14 ms                                                                                                                | 1.14 ms: 1.00x faster                                                                                                      |
| unpickle_list            | 8.04 us                                                                                                                | 8.02 us: 1.00x faster                                                                                                      |
| json_loads               | 38.0 us                                                                                                                | 37.9 us: 1.00x faster                                                                                                      |
| pickle_dict              | 46.6 us                                                                                                                | 46.8 us: 1.00x slower                                                                                                      |
| logging_format           | 8.76 us                                                                                                                | 8.80 us: 1.00x slower                                                                                                      |
| python_startup_no_site   | 10.3 ms                                                                                                                | 10.3 ms: 1.01x slower                                                                                                      |
| generators               | 46.9 ms                                                                                                                | 47.2 ms: 1.01x slower                                                                                                      |
| subparsers               | 14.9 ms                                                                                                                | 15.0 ms: 1.01x slower                                                                                                      |
| pidigits                 | 325 ms                                                                                                                 | 327 ms: 1.01x slower                                                                                                       |
| tornado_http             | 163 ms                                                                                                                 | 164 ms: 1.01x slower                                                                                                       |
| typing_runtime_protocols | 227 us                                                                                                                 | 229 us: 1.01x slower                                                                                                       |
| thrift                   | 1.12 ms                                                                                                                | 1.13 ms: 1.01x slower                                                                                                      |
| coroutines               | 36.7 ms                                                                                                                | 37.1 ms: 1.01x slower                                                                                                      |
| telco                    | 191 ms                                                                                                                 | 193 ms: 1.01x slower                                                                                                       |
| coverage                 | 121 ms                                                                                                                 | 123 ms: 1.01x slower                                                                                                       |
| pathlib                  | 22.1 ms                                                                                                                | 22.6 ms: 1.02x slower                                                                                                      |
| chaos                    | 81.8 ms                                                                                                                | 83.7 ms: 1.02x slower                                                                                                      |
| xdsl_constant_fold       | 56.3 ms                                                                                                                | 57.6 ms: 1.02x slower                                                                                                      |
| sqlalchemy_declarative   | 158 ms                                                                                                                 | 162 ms: 1.03x slower                                                                                                       |
| sqlalchemy_imperative    | 20.6 ms                                                                                                                | 21.2 ms: 1.03x slower                                                                                                      |
| sphinx                   | 1.49 sec                                                                                                               | 1.55 sec: 1.04x slower                                                                                                     |
| deepcopy                 | 345 us                                                                                                                 | 359 us: 1.04x slower                                                                                                       |
| comprehensions           | 24.2 us                                                                                                                | 25.2 us: 1.04x slower                                                                                                      |
| pycparser                | 1.50 sec                                                                                                               | 1.56 sec: 1.04x slower                                                                                                     |
| go                       | 156 ms                                                                                                                 | 163 ms: 1.04x slower                                                                                                       |
| html5lib                 | 77.8 ms                                                                                                                | 81.5 ms: 1.05x slower                                                                                                      |
| many_optionals           | 946 us                                                                                                                 | 999 us: 1.06x slower                                                                                                       |
| async_generators         | 566 ms                                                                                                                 | 599 ms: 1.06x slower                                                                                                       |
| sqlglot_v2_optimize      | 72.4 ms                                                                                                                | 76.8 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_normalize     | 149 ms                                                                                                                 | 158 ms: 1.06x slower                                                                                                       |
| pylint                   | 414 ms                                                                                                                 | 441 ms: 1.06x slower                                                                                                       |
| sqlglot_v2_parse         | 1.65 ms                                                                                                                | 1.76 ms: 1.06x slower                                                                                                      |
| sympy_integrate          | 23.1 ms                                                                                                                | 24.7 ms: 1.07x slower                                                                                                      |
| docutils                 | 4.20 sec                                                                                                               | 4.55 sec: 1.08x slower                                                                                                     |
| nqueens                  | 118 ms                                                                                                                 | 129 ms: 1.09x slower                                                                                                       |
| dulwich_log              | 60.5 ms                                                                                                                | 66.2 ms: 1.09x slower                                                                                                      |
| hexiom                   | 8.29 ms                                                                                                                | 9.08 ms: 1.10x slower                                                                                                      |
| genshi_text              | 32.2 ms                                                                                                                | 35.4 ms: 1.10x slower                                                                                                      |
| sympy_sum                | 171 ms                                                                                                                 | 190 ms: 1.11x slower                                                                                                       |
| sympy_str                | 325 ms                                                                                                                 | 360 ms: 1.11x slower                                                                                                       |
| sympy_expand             | 563 ms                                                                                                                 | 625 ms: 1.11x slower                                                                                                       |
| mdp                      | 2.43 sec                                                                                                               | 2.70 sec: 1.11x slower                                                                                                     |
| genshi_xml               | 73.6 ms                                                                                                                | 92.8 ms: 1.26x slower                                                                                                      |
| unpack_sequence          | 61.3 ns                                                                                                                | 80.6 ns: 1.31x slower                                                                                                      |
| Geometric mean           | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (17): sqlglot_v2_transpile, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_cpu_io_mixed, pprint_pformat, django_template, xml_etree_iterparse, async_tree_memoization, unpickle, asyncio_websockets, raytrace, asyncio_tcp_ssl, pprint_safe_repr, 2to3, async_tree_none, bench_mp_pool

- Geometric mean (including insignificant results): 1.023x faster

# HPT report

- Reliability score: 75.28% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x