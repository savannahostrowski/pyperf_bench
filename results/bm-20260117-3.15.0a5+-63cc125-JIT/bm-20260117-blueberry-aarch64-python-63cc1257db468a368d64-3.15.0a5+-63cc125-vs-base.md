# Results vs. base

- fork: python
- ref: 63cc1257db468a368d64
- machine: linux-aarch64
- commit hash: 63cc125
- commit date: 2026-01-17
- overall geometric mean: 1.018x faster
- HPT reliability: 84.08%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| docutils       | 4.16 sec                                                                                                               | 4.61 sec: 1.11x slower                                                                                                     |
| html5lib       | 76.5 ms                                                                                                                | 82.2 ms: 1.08x slower                                                                                                      |
| sphinx         | 1.47 sec                                                                                                               | 1.56 sec: 1.06x slower                                                                                                     |
| tornado_http   | 162 ms                                                                                                                 | 164 ms: 1.01x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (2): 2to3, chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|--------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl    | 4.22 sec                                                                                                               | 4.20 sec: 1.01x faster                                                                                                     |
| asyncio_websockets | 857 ms                                                                                                                 | 860 ms: 1.00x slower                                                                                                       |
| coroutines         | 37.3 ms                                                                                                                | 37.8 ms: 1.01x slower                                                                                                      |
| async_generators   | 572 ms                                                                                                                 | 595 ms: 1.04x slower                                                                                                       |
| asyncio_tcp        | 1.16 sec                                                                                                               | 1.21 sec: 1.04x slower                                                                                                     |
| Geometric mean     | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (8): async_tree_none, async_tree_io, async_tree_memoization, async_tree_none_tg, async_tree_io_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 158 ms                                                                                                                 | 128 ms: 1.23x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 114 ms: 1.15x faster                                                                                                       |
| pidigits       | 326 ms                                                                                                                 | 325 ms: 1.00x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 143 ms                                                                                                                 | 140 ms: 1.02x faster                                                                                                       |
| regex_v8       | 36.3 ms                                                                                                                | 35.6 ms: 1.02x faster                                                                                                      |
| regex_dna      | 279 ms                                                                                                                 | 275 ms: 1.01x faster                                                                                                       |
| regex_effbot   | 4.39 ms                                                                                                                | 4.34 ms: 1.01x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 319 us                                                                                                                 | 245 us: 1.30x faster                                                                                                       |
| pickle_pure_python   | 450 us                                                                                                                 | 389 us: 1.16x faster                                                                                                       |
| tomli_loads          | 2.82 sec                                                                                                               | 2.59 sec: 1.09x faster                                                                                                     |
| xml_etree_generate   | 128 ms                                                                                                                 | 120 ms: 1.06x faster                                                                                                       |
| xml_etree_process    | 97.9 ms                                                                                                                | 92.6 ms: 1.06x faster                                                                                                      |
| json_dumps           | 13.8 ms                                                                                                                | 13.1 ms: 1.05x faster                                                                                                      |
| xml_etree_parse      | 242 ms                                                                                                                 | 240 ms: 1.01x faster                                                                                                       |
| pickle_list          | 6.81 us                                                                                                                | 6.80 us: 1.00x faster                                                                                                      |
| unpickle             | 22.2 us                                                                                                                | 22.3 us: 1.00x slower                                                                                                      |
| json_loads           | 37.6 us                                                                                                                | 37.8 us: 1.01x slower                                                                                                      |
| pickle               | 18.6 us                                                                                                                | 19.0 us: 1.02x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.05x faster                                                                                                               |

Benchmark hidden because not significant (3): xml_etree_iterparse, unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.4 ms                                                                                                                | 17.9 ms: 1.03x slower                                                                                                      |
| python_startup_no_site | 9.99 ms                                                                                                                | 10.3 ms: 1.03x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.1 ms                                                                                                                | 17.6 ms: 1.14x faster                                                                                                      |
| django_template | 50.0 ms                                                                                                                | 51.9 ms: 1.04x slower                                                                                                      |
| genshi_text     | 32.3 ms                                                                                                                | 34.8 ms: 1.08x slower                                                                                                      |
| genshi_xml      | 73.5 ms                                                                                                                | 93.1 ms: 1.27x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20260117-3.15.0a5+-63cc125/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json | results/bm-20260117-3.15.0a5+-63cc125-JIT/bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5+-63cc125.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 63.3 ms                                                                                                                | 37.1 ms: 1.70x faster                                                                                                      |
| richards_super           | 71.7 ms                                                                                                                | 43.7 ms: 1.64x faster                                                                                                      |
| scimark_lu               | 165 ms                                                                                                                 | 121 ms: 1.36x faster                                                                                                       |
| logging_silent           | 159 ns                                                                                                                 | 120 ns: 1.32x faster                                                                                                       |
| scimark_sor              | 168 ms                                                                                                                 | 129 ms: 1.30x faster                                                                                                       |
| unpickle_pure_python     | 319 us                                                                                                                 | 245 us: 1.30x faster                                                                                                       |
| nbody                    | 158 ms                                                                                                                 | 128 ms: 1.23x faster                                                                                                       |
| scimark_monte_carlo      | 97.6 ms                                                                                                                | 82.2 ms: 1.19x faster                                                                                                      |
| deltablue                | 4.86 ms                                                                                                                | 4.16 ms: 1.17x faster                                                                                                      |
| pickle_pure_python       | 450 us                                                                                                                 | 389 us: 1.16x faster                                                                                                       |
| float                    | 131 ms                                                                                                                 | 114 ms: 1.15x faster                                                                                                       |
| mako                     | 20.1 ms                                                                                                                | 17.6 ms: 1.14x faster                                                                                                      |
| scimark_fft              | 477 ms                                                                                                                 | 421 ms: 1.13x faster                                                                                                       |
| spectral_norm            | 151 ms                                                                                                                 | 134 ms: 1.12x faster                                                                                                       |
| deepcopy_memo            | 39.8 us                                                                                                                | 35.9 us: 1.11x faster                                                                                                      |
| fannkuch                 | 572 ms                                                                                                                 | 519 ms: 1.10x faster                                                                                                       |
| pyflate                  | 727 ms                                                                                                                 | 663 ms: 1.10x faster                                                                                                       |
| tomli_loads              | 2.82 sec                                                                                                               | 2.59 sec: 1.09x faster                                                                                                     |
| xml_etree_generate       | 128 ms                                                                                                                 | 120 ms: 1.06x faster                                                                                                       |
| xml_etree_process        | 97.9 ms                                                                                                                | 92.6 ms: 1.06x faster                                                                                                      |
| json_dumps               | 13.8 ms                                                                                                                | 13.1 ms: 1.05x faster                                                                                                      |
| go                       | 155 ms                                                                                                                 | 148 ms: 1.05x faster                                                                                                       |
| sqlite_synth             | 4.53 us                                                                                                                | 4.35 us: 1.04x faster                                                                                                      |
| sqlglot_v2_parse         | 1.66 ms                                                                                                                | 1.60 ms: 1.04x faster                                                                                                      |
| bpe_tokeniser            | 6.88 sec                                                                                                               | 6.64 sec: 1.04x faster                                                                                                     |
| json                     | 6.65 ms                                                                                                                | 6.45 ms: 1.03x faster                                                                                                      |
| scimark_sparse_mat_mult  | 8.00 ms                                                                                                                | 7.78 ms: 1.03x faster                                                                                                      |
| coverage                 | 122 ms                                                                                                                 | 119 ms: 1.02x faster                                                                                                       |
| shortest_path            | 893 ms                                                                                                                 | 872 ms: 1.02x faster                                                                                                       |
| regex_compile            | 143 ms                                                                                                                 | 140 ms: 1.02x faster                                                                                                       |
| connected_components     | 842 ms                                                                                                                 | 824 ms: 1.02x faster                                                                                                       |
| crypto_pyaes             | 100 ms                                                                                                                 | 98.5 ms: 1.02x faster                                                                                                      |
| regex_v8                 | 36.3 ms                                                                                                                | 35.6 ms: 1.02x faster                                                                                                      |
| deepcopy_reduce          | 3.86 us                                                                                                                | 3.78 us: 1.02x faster                                                                                                      |
| meteor_contest           | 135 ms                                                                                                                 | 133 ms: 1.01x faster                                                                                                       |
| bench_thread_pool        | 1.17 ms                                                                                                                | 1.16 ms: 1.01x faster                                                                                                      |
| k_core                   | 4.09 sec                                                                                                               | 4.04 sec: 1.01x faster                                                                                                     |
| regex_dna                | 279 ms                                                                                                                 | 275 ms: 1.01x faster                                                                                                       |
| gc_traversal             | 14.6 ms                                                                                                                | 14.4 ms: 1.01x faster                                                                                                      |
| regex_effbot             | 4.39 ms                                                                                                                | 4.34 ms: 1.01x faster                                                                                                      |
| pprint_safe_repr         | 1.05 sec                                                                                                               | 1.04 sec: 1.01x faster                                                                                                     |
| raytrace                 | 385 ms                                                                                                                 | 382 ms: 1.01x faster                                                                                                       |
| xml_etree_parse          | 242 ms                                                                                                                 | 240 ms: 1.01x faster                                                                                                       |
| thrift                   | 1.10 ms                                                                                                                | 1.09 ms: 1.01x faster                                                                                                      |
| asyncio_tcp_ssl          | 4.22 sec                                                                                                               | 4.20 sec: 1.01x faster                                                                                                     |
| pidigits                 | 326 ms                                                                                                                 | 325 ms: 1.00x faster                                                                                                       |
| pickle_list              | 6.81 us                                                                                                                | 6.80 us: 1.00x faster                                                                                                      |
| asyncio_websockets       | 857 ms                                                                                                                 | 860 ms: 1.00x slower                                                                                                       |
| unpickle                 | 22.2 us                                                                                                                | 22.3 us: 1.00x slower                                                                                                      |
| json_loads               | 37.6 us                                                                                                                | 37.8 us: 1.01x slower                                                                                                      |
| sqlalchemy_declarative   | 157 ms                                                                                                                 | 158 ms: 1.01x slower                                                                                                       |
| pathlib                  | 21.9 ms                                                                                                                | 22.2 ms: 1.01x slower                                                                                                      |
| coroutines               | 37.3 ms                                                                                                                | 37.8 ms: 1.01x slower                                                                                                      |
| tornado_http             | 162 ms                                                                                                                 | 164 ms: 1.01x slower                                                                                                       |
| telco                    | 191 ms                                                                                                                 | 194 ms: 1.02x slower                                                                                                       |
| comprehensions           | 24.3 us                                                                                                                | 24.7 us: 1.02x slower                                                                                                      |
| generators               | 47.0 ms                                                                                                                | 47.9 ms: 1.02x slower                                                                                                      |
| pickle                   | 18.6 us                                                                                                                | 19.0 us: 1.02x slower                                                                                                      |
| logging_format           | 8.63 us                                                                                                                | 8.82 us: 1.02x slower                                                                                                      |
| python_startup           | 17.4 ms                                                                                                                | 17.9 ms: 1.03x slower                                                                                                      |
| python_startup_no_site   | 9.99 ms                                                                                                                | 10.3 ms: 1.03x slower                                                                                                      |
| logging_simple           | 7.76 us                                                                                                                | 8.01 us: 1.03x slower                                                                                                      |
| chaos                    | 81.8 ms                                                                                                                | 84.6 ms: 1.03x slower                                                                                                      |
| sqlalchemy_imperative    | 20.7 ms                                                                                                                | 21.4 ms: 1.03x slower                                                                                                      |
| django_template          | 50.0 ms                                                                                                                | 51.9 ms: 1.04x slower                                                                                                      |
| async_generators         | 572 ms                                                                                                                 | 595 ms: 1.04x slower                                                                                                       |
| asyncio_tcp              | 1.16 sec                                                                                                               | 1.21 sec: 1.04x slower                                                                                                     |
| xdsl_constant_fold       | 55.7 ms                                                                                                                | 58.2 ms: 1.05x slower                                                                                                      |
| sqlglot_v2_normalize     | 149 ms                                                                                                                 | 157 ms: 1.05x slower                                                                                                       |
| sqlglot_v2_optimize      | 72.3 ms                                                                                                                | 76.4 ms: 1.06x slower                                                                                                      |
| sphinx                   | 1.47 sec                                                                                                               | 1.56 sec: 1.06x slower                                                                                                     |
| pycparser                | 1.46 sec                                                                                                               | 1.56 sec: 1.07x slower                                                                                                     |
| sympy_integrate          | 23.1 ms                                                                                                                | 24.7 ms: 1.07x slower                                                                                                      |
| many_optionals           | 929 us                                                                                                                 | 996 us: 1.07x slower                                                                                                       |
| hexiom                   | 8.32 ms                                                                                                                | 8.93 ms: 1.07x slower                                                                                                      |
| html5lib                 | 76.5 ms                                                                                                                | 82.2 ms: 1.08x slower                                                                                                      |
| typing_runtime_protocols | 225 us                                                                                                                 | 242 us: 1.08x slower                                                                                                       |
| genshi_text              | 32.3 ms                                                                                                                | 34.8 ms: 1.08x slower                                                                                                      |
| pylint                   | 411 ms                                                                                                                 | 444 ms: 1.08x slower                                                                                                       |
| deepcopy                 | 343 us                                                                                                                 | 370 us: 1.08x slower                                                                                                       |
| nqueens                  | 118 ms                                                                                                                 | 128 ms: 1.08x slower                                                                                                       |
| docutils                 | 4.16 sec                                                                                                               | 4.61 sec: 1.11x slower                                                                                                     |
| sympy_sum                | 170 ms                                                                                                                 | 191 ms: 1.13x slower                                                                                                       |
| mdp                      | 2.40 sec                                                                                                               | 2.74 sec: 1.14x slower                                                                                                     |
| sympy_str                | 319 ms                                                                                                                 | 369 ms: 1.15x slower                                                                                                       |
| dulwich_log              | 61.8 ms                                                                                                                | 71.9 ms: 1.16x slower                                                                                                      |
| sympy_expand             | 553 ms                                                                                                                 | 653 ms: 1.18x slower                                                                                                       |
| genshi_xml               | 73.5 ms                                                                                                                | 93.1 ms: 1.27x slower                                                                                                      |
| unpack_sequence          | 64.8 ns                                                                                                                | 82.8 ns: 1.28x slower                                                                                                      |
| bench_mp_pool            | 112 ms                                                                                                                 | 212 ms: 1.88x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (17): sqlglot_v2_transpile, async_tree_none, async_tree_io, async_tree_memoization, async_tree_none_tg, async_tree_io_tg, xml_etree_iterparse, subparsers, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, unpickle_list, pickle_dict, 2to3, chameleon, pprint_pformat, async_tree_memoization_tg, create_gc_cycles

- Geometric mean (including insignificant results): 1.018x faster

# HPT report

- Reliability score: 84.08% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x