# Results vs. base

- fork: python
- ref: 33efd7178e269cbd0423
- machine: linux-aarch64
- commit hash: 33efd71
- commit date: 2025-11-26
- overall geometric mean: 1.040x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 374 ms                                                                                                                 | 386 ms: 1.03x slower                                                                                                       |
| docutils       | 3.90 sec                                                                                                               | 4.90 sec: 1.26x slower                                                                                                     |
| html5lib       | 73.8 ms                                                                                                                | 105 ms: 1.42x slower                                                                                                       |
| sphinx         | 1.40 sec                                                                                                               | 29.4 ms: 47.55x faster                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 2.25x faster                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_io    | 1.04 sec                                                                                                               | 1.06 sec: 1.02x slower                                                                                                     |
| async_generators | 586 ms                                                                                                                 | 600 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl  | 2.80 sec                                                                                                               | 2.86 sec: 1.02x slower                                                                                                     |
| async_tree_none  | 441 ms                                                                                                                 | 455 ms: 1.03x slower                                                                                                       |
| coroutines       | 36.6 ms                                                                                                                | 38.0 ms: 1.04x slower                                                                                                      |
| asyncio_tcp      | 640 ms                                                                                                                 | 666 ms: 1.04x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (7): async_tree_none_tg, async_tree_cpu_io_mixed_tg, asyncio_websockets, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 109 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| pidigits       | 327 ms                                                                                                                 | 328 ms: 1.00x slower                                                                                                       |
| nbody          | 149 ms                                                                                                                 | 153 ms: 1.02x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 269 ms                                                                                                                 | 265 ms: 1.02x faster                                                                                                       |
| regex_v8       | 35.6 ms                                                                                                                | 35.5 ms: 1.00x faster                                                                                                      |
| regex_effbot   | 4.44 ms                                                                                                                | 4.56 ms: 1.03x slower                                                                                                      |
| regex_compile  | 143 ms                                                                                                                 | 179 ms: 1.25x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 308 us                                                                                                                 | 290 us: 1.06x faster                                                                                                       |
| xml_etree_generate   | 127 ms                                                                                                                 | 123 ms: 1.03x faster                                                                                                       |
| xml_etree_process    | 95.5 ms                                                                                                                | 93.0 ms: 1.03x faster                                                                                                      |
| xml_etree_parse      | 226 ms                                                                                                                 | 223 ms: 1.01x faster                                                                                                       |
| pickle_dict          | 47.2 us                                                                                                                | 46.8 us: 1.01x faster                                                                                                      |
| json_dumps           | 13.9 ms                                                                                                                | 13.8 ms: 1.01x faster                                                                                                      |
| pickle               | 18.5 us                                                                                                                | 18.6 us: 1.00x slower                                                                                                      |
| pickle_list          | 6.81 us                                                                                                                | 6.83 us: 1.00x slower                                                                                                      |
| pickle_pure_python   | 441 us                                                                                                                 | 445 us: 1.01x slower                                                                                                       |
| unpickle             | 21.5 us                                                                                                                | 21.8 us: 1.01x slower                                                                                                      |
| xml_etree_iterparse  | 180 ms                                                                                                                 | 182 ms: 1.01x slower                                                                                                       |
| tomli_loads          | 2.86 sec                                                                                                               | 3.12 sec: 1.09x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (2): json_loads, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 16.2 ms                                                                                                                | 16.4 ms: 1.01x slower                                                                                                      |
| python_startup_no_site | 9.35 ms                                                                                                                | 9.49 ms: 1.01x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.6 ms                                                                                                                | 15.7 ms: 1.06x faster                                                                                                      |
| django_template | 49.7 ms                                                                                                                | 54.5 ms: 1.10x slower                                                                                                      |
| genshi_text     | 31.5 ms                                                                                                                | 41.6 ms: 1.32x slower                                                                                                      |
| genshi_xml      | 71.2 ms                                                                                                                | 121 ms: 1.70x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.23x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20251126-3.15.0a2+-33efd71/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json | results/bm-20251126-3.15.0a2+-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2+-33efd71.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| sphinx                   | 1.40 sec                                                                                                               | 29.4 ms: 47.55x faster                                                                                                     |
| logging_silent           | 158 ns                                                                                                                 | 137 ns: 1.16x faster                                                                                                       |
| unpickle_pure_python     | 308 us                                                                                                                 | 290 us: 1.06x faster                                                                                                       |
| mako                     | 16.6 ms                                                                                                                | 15.7 ms: 1.06x faster                                                                                                      |
| scimark_fft              | 467 ms                                                                                                                 | 445 ms: 1.05x faster                                                                                                       |
| float                    | 109 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| xml_etree_generate       | 127 ms                                                                                                                 | 123 ms: 1.03x faster                                                                                                       |
| spectral_norm            | 147 ms                                                                                                                 | 142 ms: 1.03x faster                                                                                                       |
| xml_etree_process        | 95.5 ms                                                                                                                | 93.0 ms: 1.03x faster                                                                                                      |
| regex_dna                | 269 ms                                                                                                                 | 265 ms: 1.02x faster                                                                                                       |
| json                     | 6.71 ms                                                                                                                | 6.61 ms: 1.02x faster                                                                                                      |
| xml_etree_parse          | 226 ms                                                                                                                 | 223 ms: 1.01x faster                                                                                                       |
| pickle_dict              | 47.2 us                                                                                                                | 46.8 us: 1.01x faster                                                                                                      |
| json_dumps               | 13.9 ms                                                                                                                | 13.8 ms: 1.01x faster                                                                                                      |
| regex_v8                 | 35.6 ms                                                                                                                | 35.5 ms: 1.00x faster                                                                                                      |
| scimark_sparse_mat_mult  | 7.70 ms                                                                                                                | 7.68 ms: 1.00x faster                                                                                                      |
| pidigits                 | 327 ms                                                                                                                 | 328 ms: 1.00x slower                                                                                                       |
| pickle                   | 18.5 us                                                                                                                | 18.6 us: 1.00x slower                                                                                                      |
| pickle_list              | 6.81 us                                                                                                                | 6.83 us: 1.00x slower                                                                                                      |
| gc_traversal             | 13.2 ms                                                                                                                | 13.3 ms: 1.01x slower                                                                                                      |
| python_startup           | 16.2 ms                                                                                                                | 16.4 ms: 1.01x slower                                                                                                      |
| pickle_pure_python       | 441 us                                                                                                                 | 445 us: 1.01x slower                                                                                                       |
| generators               | 45.8 ms                                                                                                                | 46.3 ms: 1.01x slower                                                                                                      |
| unpickle                 | 21.5 us                                                                                                                | 21.8 us: 1.01x slower                                                                                                      |
| xml_etree_iterparse      | 180 ms                                                                                                                 | 182 ms: 1.01x slower                                                                                                       |
| python_startup_no_site   | 9.35 ms                                                                                                                | 9.49 ms: 1.01x slower                                                                                                      |
| scimark_lu               | 166 ms                                                                                                                 | 169 ms: 1.02x slower                                                                                                       |
| async_tree_io            | 1.04 sec                                                                                                               | 1.06 sec: 1.02x slower                                                                                                     |
| scimark_sor              | 169 ms                                                                                                                 | 173 ms: 1.02x slower                                                                                                       |
| async_generators         | 586 ms                                                                                                                 | 600 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl          | 2.80 sec                                                                                                               | 2.86 sec: 1.02x slower                                                                                                     |
| nbody                    | 149 ms                                                                                                                 | 153 ms: 1.02x slower                                                                                                       |
| regex_effbot             | 4.44 ms                                                                                                                | 4.56 ms: 1.03x slower                                                                                                      |
| logging_format           | 8.75 us                                                                                                                | 9.03 us: 1.03x slower                                                                                                      |
| async_tree_none          | 441 ms                                                                                                                 | 455 ms: 1.03x slower                                                                                                       |
| 2to3                     | 374 ms                                                                                                                 | 386 ms: 1.03x slower                                                                                                       |
| coroutines               | 36.6 ms                                                                                                                | 38.0 ms: 1.04x slower                                                                                                      |
| pyflate                  | 671 ms                                                                                                                 | 696 ms: 1.04x slower                                                                                                       |
| logging_simple           | 7.84 us                                                                                                                | 8.14 us: 1.04x slower                                                                                                      |
| scimark_monte_carlo      | 95.7 ms                                                                                                                | 99.5 ms: 1.04x slower                                                                                                      |
| asyncio_tcp              | 640 ms                                                                                                                 | 666 ms: 1.04x slower                                                                                                       |
| bench_thread_pool        | 1.12 ms                                                                                                                | 1.16 ms: 1.04x slower                                                                                                      |
| telco                    | 187 ms                                                                                                                 | 195 ms: 1.05x slower                                                                                                       |
| meteor_contest           | 136 ms                                                                                                                 | 143 ms: 1.05x slower                                                                                                       |
| pathlib                  | 21.4 ms                                                                                                                | 22.6 ms: 1.05x slower                                                                                                      |
| deltablue                | 4.76 ms                                                                                                                | 5.02 ms: 1.05x slower                                                                                                      |
| fannkuch                 | 576 ms                                                                                                                 | 615 ms: 1.07x slower                                                                                                       |
| richards_super           | 70.3 ms                                                                                                                | 75.2 ms: 1.07x slower                                                                                                      |
| thrift                   | 1.08 ms                                                                                                                | 1.17 ms: 1.08x slower                                                                                                      |
| richards                 | 62.3 ms                                                                                                                | 67.6 ms: 1.09x slower                                                                                                      |
| tomli_loads              | 2.86 sec                                                                                                               | 3.12 sec: 1.09x slower                                                                                                     |
| crypto_pyaes             | 101 ms                                                                                                                 | 110 ms: 1.09x slower                                                                                                       |
| django_template          | 49.7 ms                                                                                                                | 54.5 ms: 1.10x slower                                                                                                      |
| sqlglot_v2_normalize     | 150 ms                                                                                                                 | 165 ms: 1.10x slower                                                                                                       |
| sqlglot_v2_optimize      | 72.8 ms                                                                                                                | 80.2 ms: 1.10x slower                                                                                                      |
| deepcopy_reduce          | 4.02 us                                                                                                                | 4.44 us: 1.11x slower                                                                                                      |
| sqlglot_v2_parse         | 1.69 ms                                                                                                                | 1.88 ms: 1.11x slower                                                                                                      |
| pylint                   | 390 ms                                                                                                                 | 435 ms: 1.12x slower                                                                                                       |
| many_optionals           | 1.27 ms                                                                                                                | 1.42 ms: 1.12x slower                                                                                                      |
| sqlglot_v2_transpile     | 2.07 ms                                                                                                                | 2.36 ms: 1.14x slower                                                                                                      |
| typing_runtime_protocols | 218 us                                                                                                                 | 250 us: 1.14x slower                                                                                                       |
| raytrace                 | 380 ms                                                                                                                 | 439 ms: 1.16x slower                                                                                                       |
| sympy_integrate          | 23.0 ms                                                                                                                | 27.2 ms: 1.18x slower                                                                                                      |
| mdp                      | 2.24 sec                                                                                                               | 2.71 sec: 1.21x slower                                                                                                     |
| sympy_sum                | 169 ms                                                                                                                 | 205 ms: 1.21x slower                                                                                                       |
| pycparser                | 1.61 sec                                                                                                               | 1.97 sec: 1.22x slower                                                                                                     |
| comprehensions           | 23.9 us                                                                                                                | 29.9 us: 1.25x slower                                                                                                      |
| regex_compile            | 143 ms                                                                                                                 | 179 ms: 1.25x slower                                                                                                       |
| docutils                 | 3.90 sec                                                                                                               | 4.90 sec: 1.26x slower                                                                                                     |
| chaos                    | 79.9 ms                                                                                                                | 101 ms: 1.27x slower                                                                                                       |
| sympy_str                | 318 ms                                                                                                                 | 404 ms: 1.27x slower                                                                                                       |
| sympy_expand             | 553 ms                                                                                                                 | 709 ms: 1.28x slower                                                                                                       |
| nqueens                  | 119 ms                                                                                                                 | 155 ms: 1.30x slower                                                                                                       |
| genshi_text              | 31.5 ms                                                                                                                | 41.6 ms: 1.32x slower                                                                                                      |
| pprint_safe_repr         | 1.03 sec                                                                                                               | 1.36 sec: 1.33x slower                                                                                                     |
| pprint_pformat           | 2.11 sec                                                                                                               | 2.85 sec: 1.35x slower                                                                                                     |
| deepcopy                 | 370 us                                                                                                                 | 510 us: 1.38x slower                                                                                                       |
| hexiom                   | 8.37 ms                                                                                                                | 11.7 ms: 1.40x slower                                                                                                      |
| html5lib                 | 73.8 ms                                                                                                                | 105 ms: 1.42x slower                                                                                                       |
| dulwich_log              | 60.5 ms                                                                                                                | 88.7 ms: 1.47x slower                                                                                                      |
| go                       | 154 ms                                                                                                                 | 233 ms: 1.51x slower                                                                                                       |
| genshi_xml               | 71.2 ms                                                                                                                | 121 ms: 1.70x slower                                                                                                       |
| unpack_sequence          | 60.8 ns                                                                                                                | 106 ns: 1.75x slower                                                                                                       |
| bench_mp_pool            | 130 ms                                                                                                                 | 246 ms: 1.88x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (15): async_tree_none_tg, async_tree_cpu_io_mixed_tg, create_gc_cycles, coverage, bpe_tokeniser, deepcopy_memo, asyncio_websockets, json_loads, unpickle_list, sqlite_synth, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_io_tg, subparsers

- Geometric mean (including insignificant results): 1.040x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x

# Memory
- memory change: 1.02x