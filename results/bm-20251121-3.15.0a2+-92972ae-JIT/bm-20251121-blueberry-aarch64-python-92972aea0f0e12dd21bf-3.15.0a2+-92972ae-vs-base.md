# Results vs. base

- fork: python
- ref: 92972aea0f0e12dd21bf
- machine: linux-aarch64
- commit hash: 92972ae
- commit date: 2025-11-21
- overall geometric mean: 1.039x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 376 ms                                                                                                                 | 384 ms: 1.02x slower                                                                                                       |
| html5lib       | 75.0 ms                                                                                                                | 105 ms: 1.40x slower                                                                                                       |
| sphinx         | 1.39 sec                                                                                                               | 28.8 ms: 48.28x faster                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 3.23x faster                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines                | 36.9 ms                                                                                                                | 36.4 ms: 1.01x faster                                                                                                      |
| asyncio_websockets        | 823 ms                                                                                                                 | 821 ms: 1.00x faster                                                                                                       |
| asyncio_tcp               | 664 ms                                                                                                                 | 677 ms: 1.02x slower                                                                                                       |
| async_tree_memoization_tg | 575 ms                                                                                                                 | 586 ms: 1.02x slower                                                                                                       |
| async_tree_io             | 1.03 sec                                                                                                               | 1.05 sec: 1.02x slower                                                                                                     |
| asyncio_tcp_ssl           | 2.97 sec                                                                                                               | 3.05 sec: 1.02x slower                                                                                                     |
| async_tree_none           | 435 ms                                                                                                                 | 449 ms: 1.03x slower                                                                                                       |
| async_generators          | 569 ms                                                                                                                 | 618 ms: 1.09x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_io_tg, async_tree_memoization, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 110 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| pidigits       | 328 ms                                                                                                                 | 342 ms: 1.04x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 35.8 ms                                                                                                                | 35.7 ms: 1.00x faster                                                                                                      |
| regex_effbot   | 4.38 ms                                                                                                                | 4.44 ms: 1.01x slower                                                                                                      |
| regex_compile  | 144 ms                                                                                                                 | 174 ms: 1.21x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 312 us                                                                                                                 | 285 us: 1.10x faster                                                                                                       |
| xml_etree_process    | 97.5 ms                                                                                                                | 91.7 ms: 1.06x faster                                                                                                      |
| xml_etree_generate   | 130 ms                                                                                                                 | 123 ms: 1.06x faster                                                                                                       |
| json_dumps           | 14.1 ms                                                                                                                | 13.8 ms: 1.02x faster                                                                                                      |
| json_loads           | 38.3 us                                                                                                                | 37.9 us: 1.01x faster                                                                                                      |
| xml_etree_parse      | 228 ms                                                                                                                 | 225 ms: 1.01x faster                                                                                                       |
| pickle               | 18.3 us                                                                                                                | 18.1 us: 1.01x faster                                                                                                      |
| unpickle             | 21.6 us                                                                                                                | 21.5 us: 1.00x faster                                                                                                      |
| pickle_dict          | 46.9 us                                                                                                                | 46.8 us: 1.00x faster                                                                                                      |
| pickle_list          | 6.76 us                                                                                                                | 6.80 us: 1.01x slower                                                                                                      |
| tomli_loads          | 2.89 sec                                                                                                               | 3.00 sec: 1.04x slower                                                                                                     |
| pickle_pure_python   | 451 us                                                                                                                 | 476 us: 1.06x slower                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 9.40 ms                                                                                                                | 9.47 ms: 1.01x slower                                                                                                      |
| python_startup         | 16.3 ms                                                                                                                | 17.3 ms: 1.06x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.5 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| django_template | 51.6 ms                                                                                                                | 53.1 ms: 1.03x slower                                                                                                      |
| genshi_text     | 31.9 ms                                                                                                                | 39.2 ms: 1.23x slower                                                                                                      |
| genshi_xml      | 72.4 ms                                                                                                                | 118 ms: 1.64x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.18x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json | results/bm-20251121-3.15.0a2+-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| sphinx                    | 1.39 sec                                                                                                               | 28.8 ms: 48.28x faster                                                                                                     |
| logging_silent            | 157 ns                                                                                                                 | 138 ns: 1.13x faster                                                                                                       |
| unpickle_pure_python      | 312 us                                                                                                                 | 285 us: 1.10x faster                                                                                                       |
| xml_etree_process         | 97.5 ms                                                                                                                | 91.7 ms: 1.06x faster                                                                                                      |
| mako                      | 16.5 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| xml_etree_generate        | 130 ms                                                                                                                 | 123 ms: 1.06x faster                                                                                                       |
| float                     | 110 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| scimark_fft               | 468 ms                                                                                                                 | 450 ms: 1.04x faster                                                                                                       |
| sqlite_synth              | 4.51 us                                                                                                                | 4.35 us: 1.04x faster                                                                                                      |
| spectral_norm             | 146 ms                                                                                                                 | 142 ms: 1.03x faster                                                                                                       |
| json                      | 6.75 ms                                                                                                                | 6.61 ms: 1.02x faster                                                                                                      |
| json_dumps                | 14.1 ms                                                                                                                | 13.8 ms: 1.02x faster                                                                                                      |
| deepcopy_memo             | 39.5 us                                                                                                                | 38.9 us: 1.02x faster                                                                                                      |
| coroutines                | 36.9 ms                                                                                                                | 36.4 ms: 1.01x faster                                                                                                      |
| json_loads                | 38.3 us                                                                                                                | 37.9 us: 1.01x faster                                                                                                      |
| bpe_tokeniser             | 6.72 sec                                                                                                               | 6.64 sec: 1.01x faster                                                                                                     |
| xml_etree_parse           | 228 ms                                                                                                                 | 225 ms: 1.01x faster                                                                                                       |
| coverage                  | 121 ms                                                                                                                 | 120 ms: 1.01x faster                                                                                                       |
| pickle                    | 18.3 us                                                                                                                | 18.1 us: 1.01x faster                                                                                                      |
| pathlib                   | 21.8 ms                                                                                                                | 21.7 ms: 1.01x faster                                                                                                      |
| unpickle                  | 21.6 us                                                                                                                | 21.5 us: 1.00x faster                                                                                                      |
| regex_v8                  | 35.8 ms                                                                                                                | 35.7 ms: 1.00x faster                                                                                                      |
| pickle_dict               | 46.9 us                                                                                                                | 46.8 us: 1.00x faster                                                                                                      |
| asyncio_websockets        | 823 ms                                                                                                                 | 821 ms: 1.00x faster                                                                                                       |
| logging_simple            | 7.94 us                                                                                                                | 7.98 us: 1.01x slower                                                                                                      |
| pickle_list               | 6.76 us                                                                                                                | 6.80 us: 1.01x slower                                                                                                      |
| scimark_lu                | 165 ms                                                                                                                 | 166 ms: 1.01x slower                                                                                                       |
| python_startup_no_site    | 9.40 ms                                                                                                                | 9.47 ms: 1.01x slower                                                                                                      |
| create_gc_cycles          | 7.63 ms                                                                                                                | 7.70 ms: 1.01x slower                                                                                                      |
| generators                | 45.2 ms                                                                                                                | 45.7 ms: 1.01x slower                                                                                                      |
| scimark_sor               | 169 ms                                                                                                                 | 171 ms: 1.01x slower                                                                                                       |
| telco                     | 190 ms                                                                                                                 | 192 ms: 1.01x slower                                                                                                       |
| regex_effbot              | 4.38 ms                                                                                                                | 4.44 ms: 1.01x slower                                                                                                      |
| scimark_monte_carlo       | 96.4 ms                                                                                                                | 97.8 ms: 1.02x slower                                                                                                      |
| asyncio_tcp               | 664 ms                                                                                                                 | 677 ms: 1.02x slower                                                                                                       |
| async_tree_memoization_tg | 575 ms                                                                                                                 | 586 ms: 1.02x slower                                                                                                       |
| deltablue                 | 4.81 ms                                                                                                                | 4.90 ms: 1.02x slower                                                                                                      |
| async_tree_io             | 1.03 sec                                                                                                               | 1.05 sec: 1.02x slower                                                                                                     |
| 2to3                      | 376 ms                                                                                                                 | 384 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl           | 2.97 sec                                                                                                               | 3.05 sec: 1.02x slower                                                                                                     |
| django_template           | 51.6 ms                                                                                                                | 53.1 ms: 1.03x slower                                                                                                      |
| async_tree_none           | 435 ms                                                                                                                 | 449 ms: 1.03x slower                                                                                                       |
| meteor_contest            | 134 ms                                                                                                                 | 138 ms: 1.03x slower                                                                                                       |
| tomli_loads               | 2.89 sec                                                                                                               | 3.00 sec: 1.04x slower                                                                                                     |
| richards_super            | 70.5 ms                                                                                                                | 73.4 ms: 1.04x slower                                                                                                      |
| bench_thread_pool         | 1.11 ms                                                                                                                | 1.15 ms: 1.04x slower                                                                                                      |
| pidigits                  | 328 ms                                                                                                                 | 342 ms: 1.04x slower                                                                                                       |
| typing_runtime_protocols  | 226 us                                                                                                                 | 236 us: 1.04x slower                                                                                                       |
| thrift                    | 1.12 ms                                                                                                                | 1.18 ms: 1.05x slower                                                                                                      |
| pickle_pure_python        | 451 us                                                                                                                 | 476 us: 1.06x slower                                                                                                       |
| python_startup            | 16.3 ms                                                                                                                | 17.3 ms: 1.06x slower                                                                                                      |
| deepcopy_reduce           | 3.95 us                                                                                                                | 4.21 us: 1.06x slower                                                                                                      |
| fannkuch                  | 574 ms                                                                                                                 | 611 ms: 1.07x slower                                                                                                       |
| richards                  | 62.5 ms                                                                                                                | 67.1 ms: 1.07x slower                                                                                                      |
| crypto_pyaes              | 103 ms                                                                                                                 | 110 ms: 1.07x slower                                                                                                       |
| scimark_sparse_mat_mult   | 7.70 ms                                                                                                                | 8.31 ms: 1.08x slower                                                                                                      |
| async_generators          | 569 ms                                                                                                                 | 618 ms: 1.09x slower                                                                                                       |
| sqlglot_v2_optimize       | 71.5 ms                                                                                                                | 78.7 ms: 1.10x slower                                                                                                      |
| sqlglot_v2_normalize      | 148 ms                                                                                                                 | 163 ms: 1.10x slower                                                                                                       |
| many_optionals            | 1.26 ms                                                                                                                | 1.40 ms: 1.11x slower                                                                                                      |
| raytrace                  | 384 ms                                                                                                                 | 431 ms: 1.12x slower                                                                                                       |
| sqlglot_v2_transpile      | 2.10 ms                                                                                                                | 2.36 ms: 1.13x slower                                                                                                      |
| sqlglot_v2_parse          | 1.64 ms                                                                                                                | 1.89 ms: 1.15x slower                                                                                                      |
| sympy_integrate           | 22.9 ms                                                                                                                | 26.8 ms: 1.17x slower                                                                                                      |
| pyflate                   | 669 ms                                                                                                                 | 783 ms: 1.17x slower                                                                                                       |
| sympy_sum                 | 171 ms                                                                                                                 | 203 ms: 1.19x slower                                                                                                       |
| mdp                       | 2.24 sec                                                                                                               | 2.68 sec: 1.20x slower                                                                                                     |
| regex_compile             | 144 ms                                                                                                                 | 174 ms: 1.21x slower                                                                                                       |
| chaos                     | 80.7 ms                                                                                                                | 99.1 ms: 1.23x slower                                                                                                      |
| comprehensions            | 24.1 us                                                                                                                | 29.5 us: 1.23x slower                                                                                                      |
| genshi_text               | 31.9 ms                                                                                                                | 39.2 ms: 1.23x slower                                                                                                      |
| sympy_expand              | 554 ms                                                                                                                 | 682 ms: 1.23x slower                                                                                                       |
| sympy_str                 | 321 ms                                                                                                                 | 396 ms: 1.23x slower                                                                                                       |
| nqueens                   | 120 ms                                                                                                                 | 153 ms: 1.27x slower                                                                                                       |
| deepcopy                  | 362 us                                                                                                                 | 476 us: 1.32x slower                                                                                                       |
| hexiom                    | 8.42 ms                                                                                                                | 11.4 ms: 1.35x slower                                                                                                      |
| html5lib                  | 75.0 ms                                                                                                                | 105 ms: 1.40x slower                                                                                                       |
| dulwich_log               | 62.0 ms                                                                                                                | 86.8 ms: 1.40x slower                                                                                                      |
| go                        | 156 ms                                                                                                                 | 229 ms: 1.47x slower                                                                                                       |
| unpack_sequence           | 67.8 ns                                                                                                                | 104 ns: 1.53x slower                                                                                                       |
| bench_mp_pool             | 202 ms                                                                                                                 | 316 ms: 1.56x slower                                                                                                       |
| pprint_safe_repr          | 1.06 sec                                                                                                               | 1.65 sec: 1.57x slower                                                                                                     |
| genshi_xml                | 72.4 ms                                                                                                                | 118 ms: 1.64x slower                                                                                                       |
| pprint_pformat            | 2.15 sec                                                                                                               | 3.60 sec: 1.67x slower                                                                                                     |
| pylint                    | 392 ms                                                                                                                 | 702 ms: 1.79x slower                                                                                                       |
| pycparser                 | 1.60 sec                                                                                                               | 2.95 sec: 1.84x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (12): async_tree_cpu_io_mixed_tg, regex_dna, gc_traversal, unpickle_list, xml_etree_iterparse, nbody, logging_format, subparsers, async_tree_cpu_io_mixed, async_tree_io_tg, async_tree_memoization, async_tree_none_tg
Ignored benchmarks (1) of results/bm-20251121-3.15.0a2+-92972ae/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2+-92972ae.json: docutils

- Geometric mean (including insignificant results): 1.039x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x

# Memory
- memory change: 1.02x