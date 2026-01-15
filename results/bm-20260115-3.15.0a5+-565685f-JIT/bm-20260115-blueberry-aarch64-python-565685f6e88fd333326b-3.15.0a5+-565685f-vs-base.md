# Results vs. base

- fork: python
- ref: 565685f6e88fd333326b
- machine: linux-aarch64
- commit hash: 565685f
- commit date: 2026-01-15
- overall geometric mean: 1.016x faster
- HPT reliability: 63.03%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| docutils       | 4.18 sec                                                                                                               | 4.58 sec: 1.09x slower                                                                                                     |
| html5lib       | 76.8 ms                                                                                                                | 82.2 ms: 1.07x slower                                                                                                      |
| sphinx         | 1.48 sec                                                                                                               | 1.56 sec: 1.06x slower                                                                                                     |
| tornado_http   | 162 ms                                                                                                                 | 165 ms: 1.01x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (2): 2to3, chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl  | 4.20 sec                                                                                                               | 4.18 sec: 1.00x faster                                                                                                     |
| coroutines       | 37.6 ms                                                                                                                | 38.5 ms: 1.02x slower                                                                                                      |
| async_generators | 567 ms                                                                                                                 | 614 ms: 1.08x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (10): async_tree_memoization, async_tree_none, asyncio_tcp, async_tree_cpu_io_mixed, asyncio_websockets, async_tree_io_tg, async_tree_none_tg, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 159 ms                                                                                                                 | 128 ms: 1.24x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 115 ms: 1.14x faster                                                                                                       |
| pidigits       | 326 ms                                                                                                                 | 325 ms: 1.00x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 142 ms                                                                                                                 | 139 ms: 1.02x faster                                                                                                       |
| regex_v8       | 35.5 ms                                                                                                                | 35.8 ms: 1.01x slower                                                                                                      |
| regex_effbot   | 4.41 ms                                                                                                                | 4.56 ms: 1.03x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 323 us                                                                                                                 | 242 us: 1.34x faster                                                                                                       |
| pickle_pure_python   | 444 us                                                                                                                 | 395 us: 1.12x faster                                                                                                       |
| tomli_loads          | 2.81 sec                                                                                                               | 2.55 sec: 1.10x faster                                                                                                     |
| json_dumps           | 13.9 ms                                                                                                                | 12.9 ms: 1.08x faster                                                                                                      |
| xml_etree_process    | 98.3 ms                                                                                                                | 92.7 ms: 1.06x faster                                                                                                      |
| xml_etree_generate   | 128 ms                                                                                                                 | 121 ms: 1.05x faster                                                                                                       |
| pickle_list          | 6.78 us                                                                                                                | 6.73 us: 1.01x faster                                                                                                      |
| unpickle             | 22.4 us                                                                                                                | 22.3 us: 1.00x faster                                                                                                      |
| pickle_dict          | 47.0 us                                                                                                                | 46.8 us: 1.00x faster                                                                                                      |
| json_loads           | 37.8 us                                                                                                                | 38.0 us: 1.01x slower                                                                                                      |
| unpickle_list        | 8.05 us                                                                                                                | 8.11 us: 1.01x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.05x faster                                                                                                               |

Benchmark hidden because not significant (3): pickle, xml_etree_iterparse, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.1 ms                                                                                                                | 10.3 ms: 1.02x slower                                                                                                      |
| python_startup         | 17.2 ms                                                                                                                | 17.8 ms: 1.04x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.9 ms                                                                                                                | 17.5 ms: 1.14x faster                                                                                                      |
| django_template | 51.1 ms                                                                                                                | 52.8 ms: 1.03x slower                                                                                                      |
| genshi_text     | 32.1 ms                                                                                                                | 35.1 ms: 1.09x slower                                                                                                      |
| genshi_xml      | 73.9 ms                                                                                                                | 92.5 ms: 1.25x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20260115-3.15.0a5+-565685f/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json | results/bm-20260115-3.15.0a5+-565685f-JIT/bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5+-565685f.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 62.7 ms                                                                                                                | 37.2 ms: 1.69x faster                                                                                                      |
| richards_super           | 70.7 ms                                                                                                                | 43.9 ms: 1.61x faster                                                                                                      |
| scimark_lu               | 164 ms                                                                                                                 | 121 ms: 1.36x faster                                                                                                       |
| unpickle_pure_python     | 323 us                                                                                                                 | 242 us: 1.34x faster                                                                                                       |
| logging_silent           | 158 ns                                                                                                                 | 120 ns: 1.31x faster                                                                                                       |
| scimark_sor              | 169 ms                                                                                                                 | 129 ms: 1.31x faster                                                                                                       |
| nbody                    | 159 ms                                                                                                                 | 128 ms: 1.24x faster                                                                                                       |
| scimark_monte_carlo      | 97.0 ms                                                                                                                | 82.5 ms: 1.17x faster                                                                                                      |
| deltablue                | 4.88 ms                                                                                                                | 4.17 ms: 1.17x faster                                                                                                      |
| deepcopy_memo            | 39.8 us                                                                                                                | 34.8 us: 1.14x faster                                                                                                      |
| float                    | 131 ms                                                                                                                 | 115 ms: 1.14x faster                                                                                                       |
| mako                     | 19.9 ms                                                                                                                | 17.5 ms: 1.14x faster                                                                                                      |
| scimark_fft              | 477 ms                                                                                                                 | 420 ms: 1.13x faster                                                                                                       |
| pickle_pure_python       | 444 us                                                                                                                 | 395 us: 1.12x faster                                                                                                       |
| pyflate                  | 726 ms                                                                                                                 | 658 ms: 1.10x faster                                                                                                       |
| tomli_loads              | 2.81 sec                                                                                                               | 2.55 sec: 1.10x faster                                                                                                     |
| fannkuch                 | 574 ms                                                                                                                 | 528 ms: 1.09x faster                                                                                                       |
| spectral_norm            | 150 ms                                                                                                                 | 138 ms: 1.09x faster                                                                                                       |
| json_dumps               | 13.9 ms                                                                                                                | 12.9 ms: 1.08x faster                                                                                                      |
| xml_etree_process        | 98.3 ms                                                                                                                | 92.7 ms: 1.06x faster                                                                                                      |
| xml_etree_generate       | 128 ms                                                                                                                 | 121 ms: 1.05x faster                                                                                                       |
| bpe_tokeniser            | 6.80 sec                                                                                                               | 6.56 sec: 1.04x faster                                                                                                     |
| go                       | 155 ms                                                                                                                 | 151 ms: 1.03x faster                                                                                                       |
| scimark_sparse_mat_mult  | 7.95 ms                                                                                                                | 7.74 ms: 1.03x faster                                                                                                      |
| connected_components     | 848 ms                                                                                                                 | 826 ms: 1.03x faster                                                                                                       |
| regex_compile            | 142 ms                                                                                                                 | 139 ms: 1.02x faster                                                                                                       |
| json                     | 6.67 ms                                                                                                                | 6.51 ms: 1.02x faster                                                                                                      |
| sqlite_synth             | 4.46 us                                                                                                                | 4.36 us: 1.02x faster                                                                                                      |
| shortest_path            | 894 ms                                                                                                                 | 878 ms: 1.02x faster                                                                                                       |
| create_gc_cycles         | 9.09 ms                                                                                                                | 8.92 ms: 1.02x faster                                                                                                      |
| crypto_pyaes             | 100 ms                                                                                                                 | 98.4 ms: 1.02x faster                                                                                                      |
| deepcopy_reduce          | 3.93 us                                                                                                                | 3.87 us: 1.02x faster                                                                                                      |
| logging_simple           | 8.01 us                                                                                                                | 7.90 us: 1.01x faster                                                                                                      |
| coverage                 | 122 ms                                                                                                                 | 121 ms: 1.01x faster                                                                                                       |
| thrift                   | 1.13 ms                                                                                                                | 1.12 ms: 1.01x faster                                                                                                      |
| k_core                   | 4.07 sec                                                                                                               | 4.03 sec: 1.01x faster                                                                                                     |
| pickle_list              | 6.78 us                                                                                                                | 6.73 us: 1.01x faster                                                                                                      |
| raytrace                 | 387 ms                                                                                                                 | 384 ms: 1.01x faster                                                                                                       |
| gc_traversal             | 14.7 ms                                                                                                                | 14.7 ms: 1.01x faster                                                                                                      |
| bench_thread_pool        | 1.15 ms                                                                                                                | 1.15 ms: 1.00x faster                                                                                                      |
| unpickle                 | 22.4 us                                                                                                                | 22.3 us: 1.00x faster                                                                                                      |
| asyncio_tcp_ssl          | 4.20 sec                                                                                                               | 4.18 sec: 1.00x faster                                                                                                     |
| pidigits                 | 326 ms                                                                                                                 | 325 ms: 1.00x faster                                                                                                       |
| pickle_dict              | 47.0 us                                                                                                                | 46.8 us: 1.00x faster                                                                                                      |
| meteor_contest           | 134 ms                                                                                                                 | 135 ms: 1.00x slower                                                                                                       |
| json_loads               | 37.8 us                                                                                                                | 38.0 us: 1.01x slower                                                                                                      |
| unpickle_list            | 8.05 us                                                                                                                | 8.11 us: 1.01x slower                                                                                                      |
| regex_v8                 | 35.5 ms                                                                                                                | 35.8 ms: 1.01x slower                                                                                                      |
| typing_runtime_protocols | 229 us                                                                                                                 | 231 us: 1.01x slower                                                                                                       |
| comprehensions           | 24.4 us                                                                                                                | 24.7 us: 1.01x slower                                                                                                      |
| pathlib                  | 22.0 ms                                                                                                                | 22.3 ms: 1.01x slower                                                                                                      |
| tornado_http             | 162 ms                                                                                                                 | 165 ms: 1.01x slower                                                                                                       |
| sqlalchemy_declarative   | 156 ms                                                                                                                 | 158 ms: 1.02x slower                                                                                                       |
| telco                    | 192 ms                                                                                                                 | 195 ms: 1.02x slower                                                                                                       |
| pprint_safe_repr         | 1.02 sec                                                                                                               | 1.05 sec: 1.02x slower                                                                                                     |
| python_startup_no_site   | 10.1 ms                                                                                                                | 10.3 ms: 1.02x slower                                                                                                      |
| coroutines               | 37.6 ms                                                                                                                | 38.5 ms: 1.02x slower                                                                                                      |
| pprint_pformat           | 2.08 sec                                                                                                               | 2.14 sec: 1.03x slower                                                                                                     |
| django_template          | 51.1 ms                                                                                                                | 52.8 ms: 1.03x slower                                                                                                      |
| regex_effbot             | 4.41 ms                                                                                                                | 4.56 ms: 1.03x slower                                                                                                      |
| deepcopy                 | 347 us                                                                                                                 | 360 us: 1.04x slower                                                                                                       |
| python_startup           | 17.2 ms                                                                                                                | 17.8 ms: 1.04x slower                                                                                                      |
| chaos                    | 81.5 ms                                                                                                                | 84.6 ms: 1.04x slower                                                                                                      |
| generators               | 47.4 ms                                                                                                                | 49.4 ms: 1.04x slower                                                                                                      |
| xdsl_constant_fold       | 56.1 ms                                                                                                                | 58.5 ms: 1.04x slower                                                                                                      |
| sqlalchemy_imperative    | 20.8 ms                                                                                                                | 21.9 ms: 1.05x slower                                                                                                      |
| sphinx                   | 1.48 sec                                                                                                               | 1.56 sec: 1.06x slower                                                                                                     |
| sqlglot_v2_normalize     | 146 ms                                                                                                                 | 155 ms: 1.06x slower                                                                                                       |
| many_optionals           | 933 us                                                                                                                 | 990 us: 1.06x slower                                                                                                       |
| sqlglot_v2_optimize      | 71.6 ms                                                                                                                | 76.2 ms: 1.06x slower                                                                                                      |
| pycparser                | 1.48 sec                                                                                                               | 1.57 sec: 1.07x slower                                                                                                     |
| html5lib                 | 76.8 ms                                                                                                                | 82.2 ms: 1.07x slower                                                                                                      |
| sqlglot_v2_parse         | 1.64 ms                                                                                                                | 1.76 ms: 1.08x slower                                                                                                      |
| hexiom                   | 8.29 ms                                                                                                                | 8.92 ms: 1.08x slower                                                                                                      |
| sympy_integrate          | 23.0 ms                                                                                                                | 24.8 ms: 1.08x slower                                                                                                      |
| nqueens                  | 118 ms                                                                                                                 | 127 ms: 1.08x slower                                                                                                       |
| async_generators         | 567 ms                                                                                                                 | 614 ms: 1.08x slower                                                                                                       |
| pylint                   | 411 ms                                                                                                                 | 450 ms: 1.09x slower                                                                                                       |
| genshi_text              | 32.1 ms                                                                                                                | 35.1 ms: 1.09x slower                                                                                                      |
| docutils                 | 4.18 sec                                                                                                               | 4.58 sec: 1.09x slower                                                                                                     |
| sympy_sum                | 171 ms                                                                                                                 | 191 ms: 1.11x slower                                                                                                       |
| dulwich_log              | 62.0 ms                                                                                                                | 69.7 ms: 1.12x slower                                                                                                      |
| mdp                      | 2.42 sec                                                                                                               | 2.72 sec: 1.13x slower                                                                                                     |
| sympy_str                | 320 ms                                                                                                                 | 369 ms: 1.15x slower                                                                                                       |
| sympy_expand             | 550 ms                                                                                                                 | 650 ms: 1.18x slower                                                                                                       |
| unpack_sequence          | 66.4 ns                                                                                                                | 79.2 ns: 1.19x slower                                                                                                      |
| bench_mp_pool            | 177 ms                                                                                                                 | 217 ms: 1.23x slower                                                                                                       |
| genshi_xml               | 73.9 ms                                                                                                                | 92.5 ms: 1.25x slower                                                                                                      |
| Geometric mean           | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (19): async_tree_memoization, async_tree_none, asyncio_tcp, sqlglot_v2_transpile, subparsers, async_tree_cpu_io_mixed, pickle, logging_format, xml_etree_iterparse, chameleon, asyncio_websockets, regex_dna, 2to3, xml_etree_parse, async_tree_io_tg, async_tree_none_tg, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg

- Geometric mean (including insignificant results): 1.016x faster

# HPT report

- Reliability score: 63.03% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x