# Results vs. base

- fork: python
- ref: 979d92fefc0b6863c978
- machine: linux-aarch64
- commit hash: 979d92f
- commit date: 2026-01-24
- overall geometric mean: 1.025x faster
- HPT reliability: 95.07%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 426 ms                                                                                                                 | 421 ms: 1.01x faster                                                                                                       |
| chameleon      | 20.2 ms                                                                                                                | 19.9 ms: 1.02x faster                                                                                                      |
| docutils       | 4.24 sec                                                                                                               | 4.62 sec: 1.09x slower                                                                                                     |
| html5lib       | 76.8 ms                                                                                                                | 81.7 ms: 1.06x slower                                                                                                      |
| sphinx         | 1.48 sec                                                                                                               | 1.56 sec: 1.05x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|--------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_io_tg   | 1.25 sec                                                                                                               | 1.22 sec: 1.03x faster                                                                                                     |
| asyncio_websockets | 858 ms                                                                                                                 | 860 ms: 1.00x slower                                                                                                       |
| asyncio_tcp_ssl    | 4.20 sec                                                                                                               | 4.23 sec: 1.01x slower                                                                                                     |
| coroutines         | 37.8 ms                                                                                                                | 38.0 ms: 1.01x slower                                                                                                      |
| async_generators   | 571 ms                                                                                                                 | 608 ms: 1.06x slower                                                                                                       |
| Geometric mean     | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (8): async_tree_io, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_memoization, async_tree_none_tg, asyncio_tcp, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 159 ms                                                                                                                 | 127 ms: 1.25x faster                                                                                                       |
| float          | 132 ms                                                                                                                 | 115 ms: 1.15x faster                                                                                                       |
| pidigits       | 328 ms                                                                                                                 | 327 ms: 1.00x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.13x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 143 ms                                                                                                                 | 138 ms: 1.04x faster                                                                                                       |
| regex_dna      | 288 ms                                                                                                                 | 282 ms: 1.02x faster                                                                                                       |
| regex_v8       | 36.1 ms                                                                                                                | 35.8 ms: 1.01x faster                                                                                                      |
| regex_effbot   | 4.44 ms                                                                                                                | 4.55 ms: 1.03x slower                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 320 us                                                                                                                 | 246 us: 1.30x faster                                                                                                       |
| pickle_pure_python   | 472 us                                                                                                                 | 391 us: 1.20x faster                                                                                                       |
| tomli_loads          | 2.81 sec                                                                                                               | 2.52 sec: 1.11x faster                                                                                                     |
| xml_etree_generate   | 130 ms                                                                                                                 | 120 ms: 1.08x faster                                                                                                       |
| xml_etree_process    | 98.4 ms                                                                                                                | 91.8 ms: 1.07x faster                                                                                                      |
| json_dumps           | 13.9 ms                                                                                                                | 13.0 ms: 1.07x faster                                                                                                      |
| xml_etree_parse      | 246 ms                                                                                                                 | 239 ms: 1.03x faster                                                                                                       |
| xml_etree_iterparse  | 199 ms                                                                                                                 | 196 ms: 1.01x faster                                                                                                       |
| unpickle_list        | 8.12 us                                                                                                                | 8.03 us: 1.01x faster                                                                                                      |
| unpickle             | 22.3 us                                                                                                                | 22.2 us: 1.00x faster                                                                                                      |
| pickle_list          | 6.80 us                                                                                                                | 6.78 us: 1.00x faster                                                                                                      |
| pickle               | 18.5 us                                                                                                                | 18.8 us: 1.02x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.06x faster                                                                                                               |

Benchmark hidden because not significant (2): pickle_dict, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                                                                                | 10.3 ms: 1.01x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 19.9 ms                                                                                                                | 17.6 ms: 1.13x faster                                                                                                      |
| django_template | 50.1 ms                                                                                                                | 50.7 ms: 1.01x slower                                                                                                      |
| genshi_text     | 32.5 ms                                                                                                                | 34.9 ms: 1.07x slower                                                                                                      |
| genshi_xml      | 74.6 ms                                                                                                                | 91.1 ms: 1.22x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20260124-3.15.0a5+-979d92f/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json | results/bm-20260124-3.15.0a5+-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5+-979d92f.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 64.4 ms                                                                                                                | 37.4 ms: 1.72x faster                                                                                                      |
| richards_super           | 72.6 ms                                                                                                                | 44.4 ms: 1.63x faster                                                                                                      |
| scimark_lu               | 165 ms                                                                                                                 | 120 ms: 1.38x faster                                                                                                       |
| logging_silent           | 158 ns                                                                                                                 | 119 ns: 1.32x faster                                                                                                       |
| scimark_sor              | 169 ms                                                                                                                 | 129 ms: 1.31x faster                                                                                                       |
| unpickle_pure_python     | 320 us                                                                                                                 | 246 us: 1.30x faster                                                                                                       |
| nbody                    | 159 ms                                                                                                                 | 127 ms: 1.25x faster                                                                                                       |
| deepcopy_memo            | 40.4 us                                                                                                                | 32.4 us: 1.25x faster                                                                                                      |
| pickle_pure_python       | 472 us                                                                                                                 | 391 us: 1.20x faster                                                                                                       |
| deltablue                | 4.91 ms                                                                                                                | 4.17 ms: 1.18x faster                                                                                                      |
| float                    | 132 ms                                                                                                                 | 115 ms: 1.15x faster                                                                                                       |
| scimark_fft              | 479 ms                                                                                                                 | 417 ms: 1.15x faster                                                                                                       |
| spectral_norm            | 150 ms                                                                                                                 | 132 ms: 1.14x faster                                                                                                       |
| mako                     | 19.9 ms                                                                                                                | 17.6 ms: 1.13x faster                                                                                                      |
| fannkuch                 | 583 ms                                                                                                                 | 521 ms: 1.12x faster                                                                                                       |
| tomli_loads              | 2.81 sec                                                                                                               | 2.52 sec: 1.11x faster                                                                                                     |
| xml_etree_generate       | 130 ms                                                                                                                 | 120 ms: 1.08x faster                                                                                                       |
| xml_etree_process        | 98.4 ms                                                                                                                | 91.8 ms: 1.07x faster                                                                                                      |
| json_dumps               | 13.9 ms                                                                                                                | 13.0 ms: 1.07x faster                                                                                                      |
| pyflate                  | 724 ms                                                                                                                 | 684 ms: 1.06x faster                                                                                                       |
| deepcopy_reduce          | 4.08 us                                                                                                                | 3.86 us: 1.06x faster                                                                                                      |
| bpe_tokeniser            | 6.87 sec                                                                                                               | 6.57 sec: 1.04x faster                                                                                                     |
| scimark_sparse_mat_mult  | 8.03 ms                                                                                                                | 7.69 ms: 1.04x faster                                                                                                      |
| scimark_monte_carlo      | 98.8 ms                                                                                                                | 94.7 ms: 1.04x faster                                                                                                      |
| regex_compile            | 143 ms                                                                                                                 | 138 ms: 1.04x faster                                                                                                       |
| subparsers               | 15.2 ms                                                                                                                | 14.6 ms: 1.04x faster                                                                                                      |
| connected_components     | 849 ms                                                                                                                 | 822 ms: 1.03x faster                                                                                                       |
| pprint_safe_repr         | 1.05 sec                                                                                                               | 1.02 sec: 1.03x faster                                                                                                     |
| xml_etree_parse          | 246 ms                                                                                                                 | 239 ms: 1.03x faster                                                                                                       |
| json                     | 6.71 ms                                                                                                                | 6.52 ms: 1.03x faster                                                                                                      |
| crypto_pyaes             | 101 ms                                                                                                                 | 98.5 ms: 1.03x faster                                                                                                      |
| async_tree_io_tg         | 1.25 sec                                                                                                               | 1.22 sec: 1.03x faster                                                                                                     |
| sqlite_synth             | 4.48 us                                                                                                                | 4.37 us: 1.03x faster                                                                                                      |
| pprint_pformat           | 2.13 sec                                                                                                               | 2.08 sec: 1.02x faster                                                                                                     |
| regex_dna                | 288 ms                                                                                                                 | 282 ms: 1.02x faster                                                                                                       |
| meteor_contest           | 135 ms                                                                                                                 | 132 ms: 1.02x faster                                                                                                       |
| shortest_path            | 896 ms                                                                                                                 | 879 ms: 1.02x faster                                                                                                       |
| chameleon                | 20.2 ms                                                                                                                | 19.9 ms: 1.02x faster                                                                                                      |
| thrift                   | 1.13 ms                                                                                                                | 1.11 ms: 1.01x faster                                                                                                      |
| xml_etree_iterparse      | 199 ms                                                                                                                 | 196 ms: 1.01x faster                                                                                                       |
| k_core                   | 4.09 sec                                                                                                               | 4.04 sec: 1.01x faster                                                                                                     |
| 2to3                     | 426 ms                                                                                                                 | 421 ms: 1.01x faster                                                                                                       |
| unpickle_list            | 8.12 us                                                                                                                | 8.03 us: 1.01x faster                                                                                                      |
| logging_simple           | 8.04 us                                                                                                                | 7.96 us: 1.01x faster                                                                                                      |
| coverage                 | 121 ms                                                                                                                 | 120 ms: 1.01x faster                                                                                                       |
| regex_v8                 | 36.1 ms                                                                                                                | 35.8 ms: 1.01x faster                                                                                                      |
| raytrace                 | 386 ms                                                                                                                 | 384 ms: 1.01x faster                                                                                                       |
| create_gc_cycles         | 9.25 ms                                                                                                                | 9.21 ms: 1.00x faster                                                                                                      |
| telco                    | 195 ms                                                                                                                 | 194 ms: 1.00x faster                                                                                                       |
| unpickle                 | 22.3 us                                                                                                                | 22.2 us: 1.00x faster                                                                                                      |
| pickle_list              | 6.80 us                                                                                                                | 6.78 us: 1.00x faster                                                                                                      |
| pidigits                 | 328 ms                                                                                                                 | 327 ms: 1.00x faster                                                                                                       |
| asyncio_websockets       | 858 ms                                                                                                                 | 860 ms: 1.00x slower                                                                                                       |
| python_startup_no_site   | 10.2 ms                                                                                                                | 10.3 ms: 1.01x slower                                                                                                      |
| asyncio_tcp_ssl          | 4.20 sec                                                                                                               | 4.23 sec: 1.01x slower                                                                                                     |
| coroutines               | 37.8 ms                                                                                                                | 38.0 ms: 1.01x slower                                                                                                      |
| deepcopy                 | 355 us                                                                                                                 | 357 us: 1.01x slower                                                                                                       |
| logging_format           | 8.83 us                                                                                                                | 8.89 us: 1.01x slower                                                                                                      |
| generators               | 47.3 ms                                                                                                                | 47.7 ms: 1.01x slower                                                                                                      |
| typing_runtime_protocols | 228 us                                                                                                                 | 231 us: 1.01x slower                                                                                                       |
| django_template          | 50.1 ms                                                                                                                | 50.7 ms: 1.01x slower                                                                                                      |
| bench_thread_pool        | 1.14 ms                                                                                                                | 1.16 ms: 1.01x slower                                                                                                      |
| sqlalchemy_declarative   | 157 ms                                                                                                                 | 160 ms: 1.02x slower                                                                                                       |
| pickle                   | 18.5 us                                                                                                                | 18.8 us: 1.02x slower                                                                                                      |
| gc_traversal             | 14.3 ms                                                                                                                | 14.6 ms: 1.02x slower                                                                                                      |
| regex_effbot             | 4.44 ms                                                                                                                | 4.55 ms: 1.03x slower                                                                                                      |
| chaos                    | 81.2 ms                                                                                                                | 83.7 ms: 1.03x slower                                                                                                      |
| sqlalchemy_imperative    | 21.0 ms                                                                                                                | 21.6 ms: 1.03x slower                                                                                                      |
| xdsl_constant_fold       | 56.5 ms                                                                                                                | 58.3 ms: 1.03x slower                                                                                                      |
| comprehensions           | 24.2 us                                                                                                                | 25.1 us: 1.04x slower                                                                                                      |
| pycparser                | 1.50 sec                                                                                                               | 1.57 sec: 1.04x slower                                                                                                     |
| many_optionals           | 942 us                                                                                                                 | 988 us: 1.05x slower                                                                                                       |
| sphinx                   | 1.48 sec                                                                                                               | 1.56 sec: 1.05x slower                                                                                                     |
| go                       | 156 ms                                                                                                                 | 165 ms: 1.06x slower                                                                                                       |
| sqlglot_v2_normalize     | 147 ms                                                                                                                 | 155 ms: 1.06x slower                                                                                                       |
| nqueens                  | 119 ms                                                                                                                 | 126 ms: 1.06x slower                                                                                                       |
| html5lib                 | 76.8 ms                                                                                                                | 81.7 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_parse         | 1.66 ms                                                                                                                | 1.76 ms: 1.06x slower                                                                                                      |
| async_generators         | 571 ms                                                                                                                 | 608 ms: 1.06x slower                                                                                                       |
| sqlglot_v2_optimize      | 71.7 ms                                                                                                                | 76.6 ms: 1.07x slower                                                                                                      |
| sympy_integrate          | 23.1 ms                                                                                                                | 24.7 ms: 1.07x slower                                                                                                      |
| genshi_text              | 32.5 ms                                                                                                                | 34.9 ms: 1.07x slower                                                                                                      |
| pylint                   | 413 ms                                                                                                                 | 448 ms: 1.08x slower                                                                                                       |
| hexiom                   | 8.29 ms                                                                                                                | 9.01 ms: 1.09x slower                                                                                                      |
| dulwich_log              | 62.9 ms                                                                                                                | 68.5 ms: 1.09x slower                                                                                                      |
| docutils                 | 4.24 sec                                                                                                               | 4.62 sec: 1.09x slower                                                                                                     |
| mdp                      | 2.47 sec                                                                                                               | 2.71 sec: 1.10x slower                                                                                                     |
| sympy_sum                | 172 ms                                                                                                                 | 193 ms: 1.12x slower                                                                                                       |
| sympy_str                | 323 ms                                                                                                                 | 363 ms: 1.12x slower                                                                                                       |
| sympy_expand             | 554 ms                                                                                                                 | 629 ms: 1.13x slower                                                                                                       |
| unpack_sequence          | 63.1 ns                                                                                                                | 76.2 ns: 1.21x slower                                                                                                      |
| genshi_xml               | 74.6 ms                                                                                                                | 91.1 ms: 1.22x slower                                                                                                      |
| bench_mp_pool            | 132 ms                                                                                                                 | 187 ms: 1.42x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (14): async_tree_io, sqlglot_v2_transpile, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, tornado_http, pathlib, python_startup, async_tree_memoization, pickle_dict, json_loads, async_tree_none_tg, asyncio_tcp, async_tree_none

- Geometric mean (including insignificant results): 1.025x faster

# HPT report

- Reliability score: 95.07% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x