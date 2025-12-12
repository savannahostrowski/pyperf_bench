# Results vs. base

- fork: python
- ref: ef51a7c8f3f4511ad18e
- machine: linux-aarch64
- commit hash: ef51a7c
- commit date: 2025-12-07
- overall geometric mean: 1.100x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 380 ms                                                                                                                 | 384 ms: 1.01x slower                                                                                                       |
| docutils       | 3.91 sec                                                                                                               | 7.96 sec: 2.04x slower                                                                                                     |
| html5lib       | 73.7 ms                                                                                                                | 106 ms: 1.44x slower                                                                                                       |
| sphinx         | 1.39 sec                                                                                                               | 1.60 sec: 1.15x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.36x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none  | 466 ms                                                                                                                 | 453 ms: 1.03x faster                                                                                                       |
| async_tree_io_tg | 1.07 sec                                                                                                               | 1.06 sec: 1.02x faster                                                                                                     |
| asyncio_tcp      | 665 ms                                                                                                                 | 653 ms: 1.02x faster                                                                                                       |
| coroutines       | 37.2 ms                                                                                                                | 37.0 ms: 1.00x faster                                                                                                      |
| asyncio_tcp_ssl  | 2.80 sec                                                                                                               | 2.85 sec: 1.02x slower                                                                                                     |
| async_generators | 566 ms                                                                                                                 | 609 ms: 1.08x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (7): async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization_tg, asyncio_websockets, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 150 ms                                                                                                                 | 153 ms: 1.02x slower                                                                                                       |
| pidigits       | 325 ms                                                                                                                 | 335 ms: 1.03x slower                                                                                                       |
| float          | 110 ms                                                                                                                 | 122 ms: 1.11x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 36.5 ms                                                                                                                | 35.8 ms: 1.02x faster                                                                                                      |
| regex_dna      | 269 ms                                                                                                                 | 266 ms: 1.01x faster                                                                                                       |
| regex_compile  | 143 ms                                                                                                                 | 176 ms: 1.22x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 316 us                                                                                                                 | 284 us: 1.12x faster                                                                                                       |
| xml_etree_process    | 94.6 ms                                                                                                                | 92.0 ms: 1.03x faster                                                                                                      |
| xml_etree_generate   | 127 ms                                                                                                                 | 125 ms: 1.02x faster                                                                                                       |
| xml_etree_parse      | 225 ms                                                                                                                 | 221 ms: 1.02x faster                                                                                                       |
| unpickle_list        | 8.08 us                                                                                                                | 8.05 us: 1.00x faster                                                                                                      |
| json_dumps           | 13.6 ms                                                                                                                | 13.7 ms: 1.01x slower                                                                                                      |
| xml_etree_iterparse  | 179 ms                                                                                                                 | 181 ms: 1.01x slower                                                                                                       |
| pickle_dict          | 47.0 us                                                                                                                | 47.7 us: 1.01x slower                                                                                                      |
| json_loads           | 37.7 us                                                                                                                | 38.3 us: 1.01x slower                                                                                                      |
| pickle_list          | 6.78 us                                                                                                                | 6.93 us: 1.02x slower                                                                                                      |
| pickle               | 18.6 us                                                                                                                | 20.1 us: 1.08x slower                                                                                                      |
| tomli_loads          | 2.85 sec                                                                                                               | 3.09 sec: 1.08x slower                                                                                                     |
| pickle_pure_python   | 444 us                                                                                                                 | 573 us: 1.29x slower                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 9.30 ms                                                                                                                | 9.43 ms: 1.01x slower                                                                                                      |
| python_startup         | 16.2 ms                                                                                                                | 16.4 ms: 1.01x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.0 ms                                                                                                                | 15.5 ms: 1.10x faster                                                                                                      |
| django_template | 49.6 ms                                                                                                                | 60.7 ms: 1.22x slower                                                                                                      |
| genshi_text     | 31.8 ms                                                                                                                | 39.4 ms: 1.24x slower                                                                                                      |
| genshi_xml      | 72.3 ms                                                                                                                | 114 ms: 1.58x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.22x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20251207-3.15.0a2+-ef51a7c/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json | results/bm-20251207-3.15.0a2+-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2+-ef51a7c.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| logging_silent           | 159 ns                                                                                                                 | 137 ns: 1.16x faster                                                                                                       |
| unpickle_pure_python     | 316 us                                                                                                                 | 284 us: 1.12x faster                                                                                                       |
| mako                     | 17.0 ms                                                                                                                | 15.5 ms: 1.10x faster                                                                                                      |
| scimark_fft              | 464 ms                                                                                                                 | 445 ms: 1.04x faster                                                                                                       |
| xml_etree_process        | 94.6 ms                                                                                                                | 92.0 ms: 1.03x faster                                                                                                      |
| async_tree_none          | 466 ms                                                                                                                 | 453 ms: 1.03x faster                                                                                                       |
| regex_v8                 | 36.5 ms                                                                                                                | 35.8 ms: 1.02x faster                                                                                                      |
| spectral_norm            | 147 ms                                                                                                                 | 144 ms: 1.02x faster                                                                                                       |
| async_tree_io_tg         | 1.07 sec                                                                                                               | 1.06 sec: 1.02x faster                                                                                                     |
| xml_etree_generate       | 127 ms                                                                                                                 | 125 ms: 1.02x faster                                                                                                       |
| asyncio_tcp              | 665 ms                                                                                                                 | 653 ms: 1.02x faster                                                                                                       |
| xml_etree_parse          | 225 ms                                                                                                                 | 221 ms: 1.02x faster                                                                                                       |
| regex_dna                | 269 ms                                                                                                                 | 266 ms: 1.01x faster                                                                                                       |
| bpe_tokeniser            | 6.71 sec                                                                                                               | 6.66 sec: 1.01x faster                                                                                                     |
| coroutines               | 37.2 ms                                                                                                                | 37.0 ms: 1.00x faster                                                                                                      |
| unpickle_list            | 8.08 us                                                                                                                | 8.05 us: 1.00x faster                                                                                                      |
| shortest_path            | 754 ms                                                                                                                 | 755 ms: 1.00x slower                                                                                                       |
| logging_simple           | 8.03 us                                                                                                                | 8.06 us: 1.00x slower                                                                                                      |
| scimark_sor              | 170 ms                                                                                                                 | 171 ms: 1.01x slower                                                                                                       |
| json_dumps               | 13.6 ms                                                                                                                | 13.7 ms: 1.01x slower                                                                                                      |
| 2to3                     | 380 ms                                                                                                                 | 384 ms: 1.01x slower                                                                                                       |
| xml_etree_iterparse      | 179 ms                                                                                                                 | 181 ms: 1.01x slower                                                                                                       |
| python_startup_no_site   | 9.30 ms                                                                                                                | 9.43 ms: 1.01x slower                                                                                                      |
| pickle_dict              | 47.0 us                                                                                                                | 47.7 us: 1.01x slower                                                                                                      |
| json_loads               | 37.7 us                                                                                                                | 38.3 us: 1.01x slower                                                                                                      |
| python_startup           | 16.2 ms                                                                                                                | 16.4 ms: 1.01x slower                                                                                                      |
| generators               | 45.1 ms                                                                                                                | 45.8 ms: 1.02x slower                                                                                                      |
| telco                    | 191 ms                                                                                                                 | 194 ms: 1.02x slower                                                                                                       |
| logging_format           | 8.81 us                                                                                                                | 8.97 us: 1.02x slower                                                                                                      |
| asyncio_tcp_ssl          | 2.80 sec                                                                                                               | 2.85 sec: 1.02x slower                                                                                                     |
| coverage                 | 121 ms                                                                                                                 | 124 ms: 1.02x slower                                                                                                       |
| pickle_list              | 6.78 us                                                                                                                | 6.93 us: 1.02x slower                                                                                                      |
| nbody                    | 150 ms                                                                                                                 | 153 ms: 1.02x slower                                                                                                       |
| subparsers               | 14.5 ms                                                                                                                | 14.9 ms: 1.03x slower                                                                                                      |
| pidigits                 | 325 ms                                                                                                                 | 335 ms: 1.03x slower                                                                                                       |
| pyflate                  | 675 ms                                                                                                                 | 697 ms: 1.03x slower                                                                                                       |
| thrift                   | 1.13 ms                                                                                                                | 1.17 ms: 1.04x slower                                                                                                      |
| meteor_contest           | 135 ms                                                                                                                 | 140 ms: 1.04x slower                                                                                                       |
| gc_traversal             | 13.2 ms                                                                                                                | 13.9 ms: 1.05x slower                                                                                                      |
| deepcopy_memo            | 40.7 us                                                                                                                | 43.2 us: 1.06x slower                                                                                                      |
| richards                 | 62.2 ms                                                                                                                | 66.7 ms: 1.07x slower                                                                                                      |
| async_generators         | 566 ms                                                                                                                 | 609 ms: 1.08x slower                                                                                                       |
| pickle                   | 18.6 us                                                                                                                | 20.1 us: 1.08x slower                                                                                                      |
| tomli_loads              | 2.85 sec                                                                                                               | 3.09 sec: 1.08x slower                                                                                                     |
| richards_super           | 70.2 ms                                                                                                                | 76.1 ms: 1.08x slower                                                                                                      |
| fannkuch                 | 580 ms                                                                                                                 | 629 ms: 1.08x slower                                                                                                       |
| typing_runtime_protocols | 219 us                                                                                                                 | 239 us: 1.09x slower                                                                                                       |
| sqlglot_v2_optimize      | 71.8 ms                                                                                                                | 79.1 ms: 1.10x slower                                                                                                      |
| sqlglot_v2_normalize     | 150 ms                                                                                                                 | 165 ms: 1.10x slower                                                                                                       |
| float                    | 110 ms                                                                                                                 | 122 ms: 1.11x slower                                                                                                       |
| pylint                   | 391 ms                                                                                                                 | 436 ms: 1.11x slower                                                                                                       |
| sqlglot_v2_transpile     | 2.10 ms                                                                                                                | 2.35 ms: 1.12x slower                                                                                                      |
| sqlglot_v2_parse         | 1.65 ms                                                                                                                | 1.85 ms: 1.12x slower                                                                                                      |
| sphinx                   | 1.39 sec                                                                                                               | 1.60 sec: 1.15x slower                                                                                                     |
| many_optionals           | 911 us                                                                                                                 | 1.05 ms: 1.15x slower                                                                                                      |
| deepcopy_reduce          | 4.12 us                                                                                                                | 4.74 us: 1.15x slower                                                                                                      |
| raytrace                 | 379 ms                                                                                                                 | 440 ms: 1.16x slower                                                                                                       |
| mdp                      | 2.28 sec                                                                                                               | 2.66 sec: 1.17x slower                                                                                                     |
| sympy_integrate          | 23.1 ms                                                                                                                | 27.1 ms: 1.17x slower                                                                                                      |
| pycparser                | 1.62 sec                                                                                                               | 1.92 sec: 1.18x slower                                                                                                     |
| crypto_pyaes             | 101 ms                                                                                                                 | 120 ms: 1.18x slower                                                                                                       |
| deltablue                | 4.84 ms                                                                                                                | 5.78 ms: 1.19x slower                                                                                                      |
| sympy_sum                | 170 ms                                                                                                                 | 205 ms: 1.20x slower                                                                                                       |
| regex_compile            | 143 ms                                                                                                                 | 176 ms: 1.22x slower                                                                                                       |
| django_template          | 49.6 ms                                                                                                                | 60.7 ms: 1.22x slower                                                                                                      |
| genshi_text              | 31.8 ms                                                                                                                | 39.4 ms: 1.24x slower                                                                                                      |
| sympy_str                | 322 ms                                                                                                                 | 400 ms: 1.24x slower                                                                                                       |
| sympy_expand             | 554 ms                                                                                                                 | 694 ms: 1.25x slower                                                                                                       |
| pickle_pure_python       | 444 us                                                                                                                 | 573 us: 1.29x slower                                                                                                       |
| k_core                   | 3.48 sec                                                                                                               | 4.62 sec: 1.33x slower                                                                                                     |
| nqueens                  | 119 ms                                                                                                                 | 162 ms: 1.36x slower                                                                                                       |
| hexiom                   | 8.40 ms                                                                                                                | 11.5 ms: 1.37x slower                                                                                                      |
| pathlib                  | 21.2 ms                                                                                                                | 29.2 ms: 1.38x slower                                                                                                      |
| html5lib                 | 73.7 ms                                                                                                                | 106 ms: 1.44x slower                                                                                                       |
| unpack_sequence          | 68.5 ns                                                                                                                | 99.1 ns: 1.45x slower                                                                                                      |
| comprehensions           | 24.1 us                                                                                                                | 35.3 us: 1.46x slower                                                                                                      |
| create_gc_cycles         | 7.70 ms                                                                                                                | 11.3 ms: 1.47x slower                                                                                                      |
| go                       | 155 ms                                                                                                                 | 230 ms: 1.48x slower                                                                                                       |
| chaos                    | 80.5 ms                                                                                                                | 120 ms: 1.49x slower                                                                                                       |
| bench_mp_pool            | 139 ms                                                                                                                 | 208 ms: 1.49x slower                                                                                                       |
| deepcopy                 | 368 us                                                                                                                 | 554 us: 1.50x slower                                                                                                       |
| pprint_pformat           | 2.11 sec                                                                                                               | 3.22 sec: 1.53x slower                                                                                                     |
| pprint_safe_repr         | 1.03 sec                                                                                                               | 1.63 sec: 1.58x slower                                                                                                     |
| genshi_xml               | 72.3 ms                                                                                                                | 114 ms: 1.58x slower                                                                                                       |
| docutils                 | 3.91 sec                                                                                                               | 7.96 sec: 2.04x slower                                                                                                     |
| bench_thread_pool        | 1.11 ms                                                                                                                | 2.67 ms: 2.39x slower                                                                                                      |
| dulwich_log              | 61.0 ms                                                                                                                | 165 ms: 2.70x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.13x slower                                                                                                               |

Benchmark hidden because not significant (15): async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization_tg, json, scimark_monte_carlo, connected_components, scimark_sparse_mat_mult, regex_effbot, asyncio_websockets, sqlite_synth, unpickle, scimark_lu, async_tree_memoization

- Geometric mean (including insignificant results): 1.100x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x

# Memory
- memory change: 1.03x