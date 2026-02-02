# Results vs. base

- fork: python
- ref: 3a0e1835563e6acfa305
- machine: linux-aarch64
- commit hash: 3a0e183
- commit date: 2026-02-01
- overall geometric mean: 1.012x faster
- HPT reliability: 66.82%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 421 ms                                                                                                                 | 432 ms: 1.03x slower                                                                                                       |
| chameleon      | 19.9 ms                                                                                                                | 19.7 ms: 1.01x faster                                                                                                      |
| docutils       | 4.19 sec                                                                                                               | 4.64 sec: 1.11x slower                                                                                                     |
| html5lib       | 76.6 ms                                                                                                                | 82.5 ms: 1.08x slower                                                                                                      |
| sphinx         | 1.46 sec                                                                                                               | 1.56 sec: 1.06x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl  | 4.19 sec                                                                                                               | 4.22 sec: 1.01x slower                                                                                                     |
| coroutines       | 36.8 ms                                                                                                                | 37.1 ms: 1.01x slower                                                                                                      |
| asyncio_tcp      | 1.18 sec                                                                                                               | 1.20 sec: 1.02x slower                                                                                                     |
| async_generators | 571 ms                                                                                                                 | 608 ms: 1.07x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (9): async_tree_io_tg, async_tree_none_tg, async_tree_memoization, async_tree_none, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_io, async_tree_cpu_io_mixed_tg, asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 160 ms                                                                                                                 | 133 ms: 1.20x faster                                                                                                       |
| float          | 132 ms                                                                                                                 | 116 ms: 1.14x faster                                                                                                       |
| pidigits       | 325 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.11x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.47 ms                                                                                                                | 4.40 ms: 1.02x faster                                                                                                      |
| regex_v8       | 35.9 ms                                                                                                                | 35.8 ms: 1.00x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (2): regex_dna, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 317 us                                                                                                                 | 244 us: 1.30x faster                                                                                                       |
| pickle_pure_python   | 448 us                                                                                                                 | 384 us: 1.17x faster                                                                                                       |
| tomli_loads          | 2.85 sec                                                                                                               | 2.57 sec: 1.11x faster                                                                                                     |
| xml_etree_generate   | 129 ms                                                                                                                 | 120 ms: 1.08x faster                                                                                                       |
| xml_etree_process    | 98.4 ms                                                                                                                | 92.5 ms: 1.06x faster                                                                                                      |
| json_dumps           | 13.7 ms                                                                                                                | 12.9 ms: 1.06x faster                                                                                                      |
| xml_etree_parse      | 242 ms                                                                                                                 | 238 ms: 1.02x faster                                                                                                       |
| pickle_list          | 6.79 us                                                                                                                | 6.72 us: 1.01x faster                                                                                                      |
| pickle               | 18.6 us                                                                                                                | 18.5 us: 1.01x faster                                                                                                      |
| json_loads           | 38.0 us                                                                                                                | 37.8 us: 1.00x faster                                                                                                      |
| pickle_dict          | 46.8 us                                                                                                                | 47.0 us: 1.00x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.06x faster                                                                                                               |

Benchmark hidden because not significant (3): unpickle_list, xml_etree_iterparse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.4 ms                                                                                                                | 17.9 ms: 1.03x slower                                                                                                      |
| python_startup_no_site | 10.2 ms                                                                                                                | 10.5 ms: 1.03x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.8 ms                                                                                                                | 17.6 ms: 1.12x faster                                                                                                      |
| django_template | 49.7 ms                                                                                                                | 52.4 ms: 1.05x slower                                                                                                      |
| genshi_text     | 31.8 ms                                                                                                                | 34.9 ms: 1.10x slower                                                                                                      |
| genshi_xml      | 72.7 ms                                                                                                                | 92.3 ms: 1.27x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.07x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20260201-3.15.0a5+-3a0e183/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json | results/bm-20260201-3.15.0a5+-3a0e183-JIT/bm-20260201-blueberry-aarch64-python-3a0e1835563e6acfa305-3.15.0a5+-3a0e183.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 66.0 ms                                                                                                                | 37.6 ms: 1.75x faster                                                                                                      |
| richards_super           | 74.1 ms                                                                                                                | 45.1 ms: 1.64x faster                                                                                                      |
| scimark_lu               | 166 ms                                                                                                                 | 121 ms: 1.37x faster                                                                                                       |
| logging_silent           | 157 ns                                                                                                                 | 119 ns: 1.31x faster                                                                                                       |
| scimark_sor              | 169 ms                                                                                                                 | 130 ms: 1.30x faster                                                                                                       |
| unpickle_pure_python     | 317 us                                                                                                                 | 244 us: 1.30x faster                                                                                                       |
| deepcopy_memo            | 39.9 us                                                                                                                | 32.5 us: 1.22x faster                                                                                                      |
| nbody                    | 160 ms                                                                                                                 | 133 ms: 1.20x faster                                                                                                       |
| pickle_pure_python       | 448 us                                                                                                                 | 384 us: 1.17x faster                                                                                                       |
| deltablue                | 4.86 ms                                                                                                                | 4.18 ms: 1.16x faster                                                                                                      |
| float                    | 132 ms                                                                                                                 | 116 ms: 1.14x faster                                                                                                       |
| scimark_fft              | 477 ms                                                                                                                 | 422 ms: 1.13x faster                                                                                                       |
| spectral_norm            | 150 ms                                                                                                                 | 133 ms: 1.13x faster                                                                                                       |
| mako                     | 19.8 ms                                                                                                                | 17.6 ms: 1.12x faster                                                                                                      |
| tomli_loads              | 2.85 sec                                                                                                               | 2.57 sec: 1.11x faster                                                                                                     |
| xml_etree_generate       | 129 ms                                                                                                                 | 120 ms: 1.08x faster                                                                                                       |
| xml_etree_process        | 98.4 ms                                                                                                                | 92.5 ms: 1.06x faster                                                                                                      |
| json_dumps               | 13.7 ms                                                                                                                | 12.9 ms: 1.06x faster                                                                                                      |
| bpe_tokeniser            | 6.86 sec                                                                                                               | 6.52 sec: 1.05x faster                                                                                                     |
| pyflate                  | 732 ms                                                                                                                 | 696 ms: 1.05x faster                                                                                                       |
| fannkuch                 | 578 ms                                                                                                                 | 555 ms: 1.04x faster                                                                                                       |
| json                     | 6.70 ms                                                                                                                | 6.45 ms: 1.04x faster                                                                                                      |
| scimark_monte_carlo      | 99.1 ms                                                                                                                | 95.6 ms: 1.04x faster                                                                                                      |
| sqlite_synth             | 4.52 us                                                                                                                | 4.36 us: 1.04x faster                                                                                                      |
| xml_etree_parse          | 242 ms                                                                                                                 | 238 ms: 1.02x faster                                                                                                       |
| regex_effbot             | 4.47 ms                                                                                                                | 4.40 ms: 1.02x faster                                                                                                      |
| meteor_contest           | 135 ms                                                                                                                 | 133 ms: 1.02x faster                                                                                                       |
| connected_components     | 847 ms                                                                                                                 | 834 ms: 1.02x faster                                                                                                       |
| pickle_list              | 6.79 us                                                                                                                | 6.72 us: 1.01x faster                                                                                                      |
| crypto_pyaes             | 99.3 ms                                                                                                                | 98.4 ms: 1.01x faster                                                                                                      |
| chameleon                | 19.9 ms                                                                                                                | 19.7 ms: 1.01x faster                                                                                                      |
| pickle                   | 18.6 us                                                                                                                | 18.5 us: 1.01x faster                                                                                                      |
| scimark_sparse_mat_mult  | 7.95 ms                                                                                                                | 7.90 ms: 1.01x faster                                                                                                      |
| json_loads               | 38.0 us                                                                                                                | 37.8 us: 1.00x faster                                                                                                      |
| regex_v8                 | 35.9 ms                                                                                                                | 35.8 ms: 1.00x faster                                                                                                      |
| pickle_dict              | 46.8 us                                                                                                                | 47.0 us: 1.00x slower                                                                                                      |
| pidigits                 | 325 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| pprint_pformat           | 2.13 sec                                                                                                               | 2.14 sec: 1.01x slower                                                                                                     |
| asyncio_tcp_ssl          | 4.19 sec                                                                                                               | 4.22 sec: 1.01x slower                                                                                                     |
| k_core                   | 4.06 sec                                                                                                               | 4.10 sec: 1.01x slower                                                                                                     |
| coroutines               | 36.8 ms                                                                                                                | 37.1 ms: 1.01x slower                                                                                                      |
| gc_traversal             | 14.4 ms                                                                                                                | 14.6 ms: 1.01x slower                                                                                                      |
| logging_format           | 8.65 us                                                                                                                | 8.77 us: 1.01x slower                                                                                                      |
| pprint_safe_repr         | 1.04 sec                                                                                                               | 1.06 sec: 1.01x slower                                                                                                     |
| thrift                   | 1.08 ms                                                                                                                | 1.10 ms: 1.02x slower                                                                                                      |
| asyncio_tcp              | 1.18 sec                                                                                                               | 1.20 sec: 1.02x slower                                                                                                     |
| typing_runtime_protocols | 228 us                                                                                                                 | 232 us: 1.02x slower                                                                                                       |
| logging_simple           | 7.85 us                                                                                                                | 8.02 us: 1.02x slower                                                                                                      |
| generators               | 46.6 ms                                                                                                                | 47.8 ms: 1.03x slower                                                                                                      |
| python_startup           | 17.4 ms                                                                                                                | 17.9 ms: 1.03x slower                                                                                                      |
| 2to3                     | 421 ms                                                                                                                 | 432 ms: 1.03x slower                                                                                                       |
| pathlib                  | 22.0 ms                                                                                                                | 22.6 ms: 1.03x slower                                                                                                      |
| python_startup_no_site   | 10.2 ms                                                                                                                | 10.5 ms: 1.03x slower                                                                                                      |
| telco                    | 189 ms                                                                                                                 | 195 ms: 1.03x slower                                                                                                       |
| sqlalchemy_declarative   | 155 ms                                                                                                                 | 161 ms: 1.03x slower                                                                                                       |
| deepcopy_reduce          | 3.82 us                                                                                                                | 3.96 us: 1.04x slower                                                                                                      |
| chaos                    | 82.4 ms                                                                                                                | 85.4 ms: 1.04x slower                                                                                                      |
| comprehensions           | 24.1 us                                                                                                                | 25.0 us: 1.04x slower                                                                                                      |
| create_gc_cycles         | 8.84 ms                                                                                                                | 9.17 ms: 1.04x slower                                                                                                      |
| deepcopy                 | 342 us                                                                                                                 | 360 us: 1.05x slower                                                                                                       |
| sqlalchemy_imperative    | 20.6 ms                                                                                                                | 21.7 ms: 1.05x slower                                                                                                      |
| xdsl_constant_fold       | 55.5 ms                                                                                                                | 58.5 ms: 1.05x slower                                                                                                      |
| django_template          | 49.7 ms                                                                                                                | 52.4 ms: 1.05x slower                                                                                                      |
| sphinx                   | 1.46 sec                                                                                                               | 1.56 sec: 1.06x slower                                                                                                     |
| go                       | 155 ms                                                                                                                 | 165 ms: 1.06x slower                                                                                                       |
| async_generators         | 571 ms                                                                                                                 | 608 ms: 1.07x slower                                                                                                       |
| sympy_integrate          | 23.0 ms                                                                                                                | 24.8 ms: 1.08x slower                                                                                                      |
| html5lib                 | 76.6 ms                                                                                                                | 82.5 ms: 1.08x slower                                                                                                      |
| sqlglot_v2_optimize      | 71.4 ms                                                                                                                | 76.8 ms: 1.08x slower                                                                                                      |
| pycparser                | 1.48 sec                                                                                                               | 1.59 sec: 1.08x slower                                                                                                     |
| sqlglot_v2_normalize     | 145 ms                                                                                                                 | 157 ms: 1.08x slower                                                                                                       |
| sqlglot_v2_parse         | 1.64 ms                                                                                                                | 1.77 ms: 1.08x slower                                                                                                      |
| pylint                   | 411 ms                                                                                                                 | 445 ms: 1.08x slower                                                                                                       |
| many_optionals           | 933 us                                                                                                                 | 1.01 ms: 1.08x slower                                                                                                      |
| genshi_text              | 31.8 ms                                                                                                                | 34.9 ms: 1.10x slower                                                                                                      |
| hexiom                   | 8.27 ms                                                                                                                | 9.08 ms: 1.10x slower                                                                                                      |
| docutils                 | 4.19 sec                                                                                                               | 4.64 sec: 1.11x slower                                                                                                     |
| nqueens                  | 117 ms                                                                                                                 | 130 ms: 1.11x slower                                                                                                       |
| dulwich_log              | 61.3 ms                                                                                                                | 68.4 ms: 1.12x slower                                                                                                      |
| sympy_sum                | 170 ms                                                                                                                 | 190 ms: 1.12x slower                                                                                                       |
| mdp                      | 2.41 sec                                                                                                               | 2.74 sec: 1.14x slower                                                                                                     |
| sympy_str                | 320 ms                                                                                                                 | 365 ms: 1.14x slower                                                                                                       |
| sympy_expand             | 553 ms                                                                                                                 | 636 ms: 1.15x slower                                                                                                       |
| unpack_sequence          | 67.7 ns                                                                                                                | 81.8 ns: 1.21x slower                                                                                                      |
| genshi_xml               | 72.7 ms                                                                                                                | 92.3 ms: 1.27x slower                                                                                                      |
| bench_mp_pool            | 153 ms                                                                                                                 | 230 ms: 1.50x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (21): async_tree_io_tg, async_tree_none_tg, async_tree_memoization, sqlglot_v2_transpile, async_tree_none, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_io, async_tree_cpu_io_mixed_tg, coverage, regex_dna, unpickle_list, raytrace, xml_etree_iterparse, shortest_path, asyncio_websockets, unpickle, regex_compile, bench_thread_pool, subparsers, tornado_http

- Geometric mean (including insignificant results): 1.012x faster

# HPT report

- Reliability score: 66.82% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x