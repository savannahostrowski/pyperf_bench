# Results vs. base

- fork: python
- ref: 229ed3dd1f97b2f87629
- machine: linux-aarch64
- commit hash: 229ed3d
- commit date: 2025-11-30
- overall geometric mean: 1.078x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 375 ms                                                                                                                 | 382 ms: 1.02x slower                                                                                                       |
| docutils       | 3.91 sec                                                                                                               | 4.80 sec: 1.23x slower                                                                                                     |
| html5lib       | 74.7 ms                                                                                                                | 105 ms: 1.41x slower                                                                                                       |
| sphinx         | 1.39 sec                                                                                                               | 1.62 sec: 1.16x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.20x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl  | 2.80 sec                                                                                                               | 2.86 sec: 1.02x slower                                                                                                     |
| coroutines       | 36.5 ms                                                                                                                | 37.4 ms: 1.02x slower                                                                                                      |
| async_generators | 567 ms                                                                                                                 | 596 ms: 1.05x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (10): async_tree_none_tg, async_tree_cpu_io_mixed_tg, asyncio_websockets, async_tree_io, asyncio_tcp, async_tree_io_tg, async_tree_none, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 109 ms                                                                                                                 | 104 ms: 1.04x faster                                                                                                       |
| pidigits       | 324 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| nbody          | 147 ms                                                                                                                 | 154 ms: 1.05x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.40 ms                                                                                                                | 4.38 ms: 1.00x faster                                                                                                      |
| regex_v8       | 35.2 ms                                                                                                                | 35.5 ms: 1.01x slower                                                                                                      |
| regex_dna      | 262 ms                                                                                                                 | 264 ms: 1.01x slower                                                                                                       |
| regex_compile  | 143 ms                                                                                                                 | 175 ms: 1.23x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 310 us                                                                                                                 | 283 us: 1.10x faster                                                                                                       |
| xml_etree_process    | 94.8 ms                                                                                                                | 92.8 ms: 1.02x faster                                                                                                      |
| xml_etree_generate   | 127 ms                                                                                                                 | 125 ms: 1.02x faster                                                                                                       |
| json_loads           | 37.9 us                                                                                                                | 37.8 us: 1.00x faster                                                                                                      |
| xml_etree_parse      | 225 ms                                                                                                                 | 226 ms: 1.00x slower                                                                                                       |
| pickle               | 18.4 us                                                                                                                | 18.5 us: 1.01x slower                                                                                                      |
| xml_etree_iterparse  | 181 ms                                                                                                                 | 183 ms: 1.01x slower                                                                                                       |
| pickle_pure_python   | 437 us                                                                                                                 | 445 us: 1.02x slower                                                                                                       |
| json_dumps           | 13.6 ms                                                                                                                | 13.8 ms: 1.02x slower                                                                                                      |
| pickle_list          | 6.73 us                                                                                                                | 6.88 us: 1.02x slower                                                                                                      |
| tomli_loads          | 2.83 sec                                                                                                               | 3.03 sec: 1.07x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (3): unpickle, unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 16.4 ms                                                                                                                | 16.3 ms: 1.01x faster                                                                                                      |
| python_startup_no_site | 9.44 ms                                                                                                                | 9.42 ms: 1.00x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.6 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| django_template | 48.1 ms                                                                                                                | 54.0 ms: 1.12x slower                                                                                                      |
| genshi_text     | 31.2 ms                                                                                                                | 40.0 ms: 1.28x slower                                                                                                      |
| genshi_xml      | 70.6 ms                                                                                                                | 116 ms: 1.64x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.22x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20251130-3.15.0a2+-229ed3d/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json | results/bm-20251130-3.15.0a2+-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2+-229ed3d.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| logging_silent           | 156 ns                                                                                                                 | 137 ns: 1.14x faster                                                                                                       |
| unpickle_pure_python     | 310 us                                                                                                                 | 283 us: 1.10x faster                                                                                                       |
| mako                     | 16.6 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| float                    | 109 ms                                                                                                                 | 104 ms: 1.04x faster                                                                                                       |
| scimark_fft              | 464 ms                                                                                                                 | 446 ms: 1.04x faster                                                                                                       |
| xml_etree_process        | 94.8 ms                                                                                                                | 92.8 ms: 1.02x faster                                                                                                      |
| xml_etree_generate       | 127 ms                                                                                                                 | 125 ms: 1.02x faster                                                                                                       |
| deepcopy_memo            | 39.5 us                                                                                                                | 38.9 us: 1.02x faster                                                                                                      |
| spectral_norm            | 144 ms                                                                                                                 | 143 ms: 1.01x faster                                                                                                       |
| python_startup           | 16.4 ms                                                                                                                | 16.3 ms: 1.01x faster                                                                                                      |
| sqlite_synth             | 4.53 us                                                                                                                | 4.51 us: 1.00x faster                                                                                                      |
| json                     | 6.67 ms                                                                                                                | 6.64 ms: 1.00x faster                                                                                                      |
| regex_effbot             | 4.40 ms                                                                                                                | 4.38 ms: 1.00x faster                                                                                                      |
| json_loads               | 37.9 us                                                                                                                | 37.8 us: 1.00x faster                                                                                                      |
| python_startup_no_site   | 9.44 ms                                                                                                                | 9.42 ms: 1.00x faster                                                                                                      |
| xml_etree_parse          | 225 ms                                                                                                                 | 226 ms: 1.00x slower                                                                                                       |
| pickle                   | 18.4 us                                                                                                                | 18.5 us: 1.01x slower                                                                                                      |
| regex_v8                 | 35.2 ms                                                                                                                | 35.5 ms: 1.01x slower                                                                                                      |
| regex_dna                | 262 ms                                                                                                                 | 264 ms: 1.01x slower                                                                                                       |
| scimark_sparse_mat_mult  | 7.58 ms                                                                                                                | 7.64 ms: 1.01x slower                                                                                                      |
| pidigits                 | 324 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| xml_etree_iterparse      | 181 ms                                                                                                                 | 183 ms: 1.01x slower                                                                                                       |
| meteor_contest           | 136 ms                                                                                                                 | 138 ms: 1.02x slower                                                                                                       |
| pickle_pure_python       | 437 us                                                                                                                 | 445 us: 1.02x slower                                                                                                       |
| json_dumps               | 13.6 ms                                                                                                                | 13.8 ms: 1.02x slower                                                                                                      |
| 2to3                     | 375 ms                                                                                                                 | 382 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl          | 2.80 sec                                                                                                               | 2.86 sec: 1.02x slower                                                                                                     |
| scimark_monte_carlo      | 95.5 ms                                                                                                                | 97.6 ms: 1.02x slower                                                                                                      |
| pickle_list              | 6.73 us                                                                                                                | 6.88 us: 1.02x slower                                                                                                      |
| scimark_lu               | 164 ms                                                                                                                 | 168 ms: 1.02x slower                                                                                                       |
| pathlib                  | 21.6 ms                                                                                                                | 22.0 ms: 1.02x slower                                                                                                      |
| coroutines               | 36.5 ms                                                                                                                | 37.4 ms: 1.02x slower                                                                                                      |
| subparsers               | 58.3 ms                                                                                                                | 59.8 ms: 1.03x slower                                                                                                      |
| telco                    | 187 ms                                                                                                                 | 192 ms: 1.03x slower                                                                                                       |
| scimark_sor              | 168 ms                                                                                                                 | 173 ms: 1.03x slower                                                                                                       |
| bench_thread_pool        | 1.12 ms                                                                                                                | 1.16 ms: 1.04x slower                                                                                                      |
| pyflate                  | 666 ms                                                                                                                 | 691 ms: 1.04x slower                                                                                                       |
| generators               | 44.6 ms                                                                                                                | 46.4 ms: 1.04x slower                                                                                                      |
| deltablue                | 4.70 ms                                                                                                                | 4.91 ms: 1.04x slower                                                                                                      |
| nbody                    | 147 ms                                                                                                                 | 154 ms: 1.05x slower                                                                                                       |
| async_generators         | 567 ms                                                                                                                 | 596 ms: 1.05x slower                                                                                                       |
| fannkuch                 | 578 ms                                                                                                                 | 610 ms: 1.06x slower                                                                                                       |
| logging_format           | 8.71 us                                                                                                                | 9.22 us: 1.06x slower                                                                                                      |
| logging_simple           | 7.94 us                                                                                                                | 8.41 us: 1.06x slower                                                                                                      |
| richards_super           | 70.2 ms                                                                                                                | 74.5 ms: 1.06x slower                                                                                                      |
| thrift                   | 1.11 ms                                                                                                                | 1.18 ms: 1.07x slower                                                                                                      |
| tomli_loads              | 2.83 sec                                                                                                               | 3.03 sec: 1.07x slower                                                                                                     |
| deepcopy_reduce          | 3.95 us                                                                                                                | 4.24 us: 1.08x slower                                                                                                      |
| typing_runtime_protocols | 218 us                                                                                                                 | 235 us: 1.08x slower                                                                                                       |
| richards                 | 62.4 ms                                                                                                                | 67.2 ms: 1.08x slower                                                                                                      |
| sqlglot_v2_parse         | 1.69 ms                                                                                                                | 1.85 ms: 1.10x slower                                                                                                      |
| sqlglot_v2_optimize      | 71.3 ms                                                                                                                | 78.5 ms: 1.10x slower                                                                                                      |
| sqlglot_v2_normalize     | 148 ms                                                                                                                 | 163 ms: 1.11x slower                                                                                                       |
| pylint                   | 392 ms                                                                                                                 | 434 ms: 1.11x slower                                                                                                       |
| crypto_pyaes             | 99.9 ms                                                                                                                | 111 ms: 1.11x slower                                                                                                       |
| django_template          | 48.1 ms                                                                                                                | 54.0 ms: 1.12x slower                                                                                                      |
| many_optionals           | 1.25 ms                                                                                                                | 1.41 ms: 1.13x slower                                                                                                      |
| sqlglot_v2_transpile     | 2.07 ms                                                                                                                | 2.33 ms: 1.13x slower                                                                                                      |
| raytrace                 | 378 ms                                                                                                                 | 432 ms: 1.14x slower                                                                                                       |
| sphinx                   | 1.39 sec                                                                                                               | 1.62 sec: 1.16x slower                                                                                                     |
| sympy_integrate          | 22.8 ms                                                                                                                | 26.9 ms: 1.18x slower                                                                                                      |
| pycparser                | 1.61 sec                                                                                                               | 1.91 sec: 1.19x slower                                                                                                     |
| sympy_sum                | 167 ms                                                                                                                 | 203 ms: 1.21x slower                                                                                                       |
| mdp                      | 2.23 sec                                                                                                               | 2.72 sec: 1.22x slower                                                                                                     |
| comprehensions           | 24.0 us                                                                                                                | 29.3 us: 1.22x slower                                                                                                      |
| regex_compile            | 143 ms                                                                                                                 | 175 ms: 1.23x slower                                                                                                       |
| docutils                 | 3.91 sec                                                                                                               | 4.80 sec: 1.23x slower                                                                                                     |
| deepcopy                 | 363 us                                                                                                                 | 452 us: 1.24x slower                                                                                                       |
| chaos                    | 79.6 ms                                                                                                                | 99.2 ms: 1.25x slower                                                                                                      |
| sympy_str                | 316 ms                                                                                                                 | 399 ms: 1.26x slower                                                                                                       |
| nqueens                  | 118 ms                                                                                                                 | 149 ms: 1.26x slower                                                                                                       |
| sympy_expand             | 545 ms                                                                                                                 | 694 ms: 1.27x slower                                                                                                       |
| genshi_text              | 31.2 ms                                                                                                                | 40.0 ms: 1.28x slower                                                                                                      |
| hexiom                   | 8.34 ms                                                                                                                | 11.5 ms: 1.38x slower                                                                                                      |
| pprint_pformat           | 2.11 sec                                                                                                               | 2.93 sec: 1.39x slower                                                                                                     |
| pprint_safe_repr         | 1.03 sec                                                                                                               | 1.43 sec: 1.39x slower                                                                                                     |
| html5lib                 | 74.7 ms                                                                                                                | 105 ms: 1.41x slower                                                                                                       |
| dulwich_log              | 60.9 ms                                                                                                                | 88.4 ms: 1.45x slower                                                                                                      |
| go                       | 153 ms                                                                                                                 | 232 ms: 1.51x slower                                                                                                       |
| unpack_sequence          | 66.6 ns                                                                                                                | 102 ns: 1.52x slower                                                                                                       |
| genshi_xml               | 70.6 ms                                                                                                                | 116 ms: 1.64x slower                                                                                                       |
| bench_mp_pool            | 116 ms                                                                                                                 | 267 ms: 2.29x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.09x slower                                                                                                               |

Benchmark hidden because not significant (17): async_tree_none_tg, async_tree_cpu_io_mixed_tg, coverage, gc_traversal, unpickle, unpickle_list, asyncio_websockets, pickle_dict, bpe_tokeniser, async_tree_io, asyncio_tcp, create_gc_cycles, async_tree_io_tg, async_tree_none, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_memoization

- Geometric mean (including insignificant results): 1.078x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x

# Memory
- memory change: 1.03x