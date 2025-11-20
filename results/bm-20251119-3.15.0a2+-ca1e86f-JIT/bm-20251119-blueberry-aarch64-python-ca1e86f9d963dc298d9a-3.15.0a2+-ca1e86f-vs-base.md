# Results vs. base

- fork: python
- ref: ca1e86f9d963dc298d9a
- machine: linux-aarch64
- commit hash: ca1e86f
- commit date: 2025-11-19
- overall geometric mean: 1.073x slower
- HPT reliability: 99.82%
- HPT 99th percentile: 1.00x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 412 ms                                                                                                                 | 383 ms: 1.08x faster                                                                                                       |
| html5lib       | 74.8 ms                                                                                                                | 106 ms: 1.41x slower                                                                                                       |
| sphinx         | 1.39 sec                                                                                                               | 1.60 sec: 1.15x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.15x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp                | 1.76 sec                                                                                                               | 690 ms: 2.56x faster                                                                                                       |
| async_tree_io_tg           | 1.40 sec                                                                                                               | 1.04 sec: 1.35x faster                                                                                                     |
| async_tree_memoization_tg  | 769 ms                                                                                                                 | 580 ms: 1.33x faster                                                                                                       |
| async_tree_io              | 1.38 sec                                                                                                               | 1.04 sec: 1.32x faster                                                                                                     |
| asyncio_tcp_ssl            | 4.01 sec                                                                                                               | 3.04 sec: 1.32x faster                                                                                                     |
| async_tree_memoization     | 789 ms                                                                                                                 | 609 ms: 1.30x faster                                                                                                       |
| async_tree_cpu_io_mixed_tg | 1.08 sec                                                                                                               | 842 ms: 1.28x faster                                                                                                       |
| async_tree_none            | 563 ms                                                                                                                 | 447 ms: 1.26x faster                                                                                                       |
| async_tree_cpu_io_mixed    | 1.09 sec                                                                                                               | 875 ms: 1.25x faster                                                                                                       |
| async_tree_none_tg         | 553 ms                                                                                                                 | 453 ms: 1.22x faster                                                                                                       |
| coroutines                 | 36.8 ms                                                                                                                | 36.9 ms: 1.00x slower                                                                                                      |
| async_generators           | 608 ms                                                                                                                 | 621 ms: 1.02x slower                                                                                                       |
| Geometric mean             | (ref)                                                                                                                  | 1.28x faster                                                                                                               |

Benchmark hidden because not significant (1): asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| pidigits       | 325 ms                                                                                                                 | 340 ms: 1.05x slower                                                                                                       |
| nbody          | 150 ms                                                                                                                 | 161 ms: 1.07x slower                                                                                                       |
| float          | 109 ms                                                                                                                 | 128 ms: 1.17x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.10x slower                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 35.9 ms                                                                                                                | 35.6 ms: 1.01x faster                                                                                                      |
| regex_compile  | 144 ms                                                                                                                 | 174 ms: 1.21x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (2): regex_dna, regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| xml_etree_process    | 111 ms                                                                                                                 | 91.3 ms: 1.22x faster                                                                                                      |
| xml_etree_generate   | 143 ms                                                                                                                 | 123 ms: 1.16x faster                                                                                                       |
| unpickle_pure_python | 315 us                                                                                                                 | 283 us: 1.11x faster                                                                                                       |
| xml_etree_iterparse  | 187 ms                                                                                                                 | 181 ms: 1.04x faster                                                                                                       |
| xml_etree_parse      | 226 ms                                                                                                                 | 224 ms: 1.01x faster                                                                                                       |
| unpickle_list        | 8.08 us                                                                                                                | 8.00 us: 1.01x faster                                                                                                      |
| json_dumps           | 13.8 ms                                                                                                                | 13.7 ms: 1.01x faster                                                                                                      |
| pickle_list          | 6.74 us                                                                                                                | 7.02 us: 1.04x slower                                                                                                      |
| pickle_dict          | 46.9 us                                                                                                                | 48.9 us: 1.04x slower                                                                                                      |
| tomli_loads          | 2.87 sec                                                                                                               | 3.00 sec: 1.05x slower                                                                                                     |
| pickle               | 18.3 us                                                                                                                | 20.2 us: 1.11x slower                                                                                                      |
| pickle_pure_python   | 441 us                                                                                                                 | 612 us: 1.39x slower                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (2): json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup | 16.4 ms                                                                                                                | 16.3 ms: 1.01x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.5 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| genshi_text     | 32.5 ms                                                                                                                | 40.2 ms: 1.24x slower                                                                                                      |
| django_template | 50.8 ms                                                                                                                | 67.1 ms: 1.32x slower                                                                                                      |
| genshi_xml      | 74.4 ms                                                                                                                | 118 ms: 1.58x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.25x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                  | results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json | results/bm-20251119-3.15.0a2+-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp                | 1.76 sec                                                                                                               | 690 ms: 2.56x faster                                                                                                       |
| async_tree_io_tg           | 1.40 sec                                                                                                               | 1.04 sec: 1.35x faster                                                                                                     |
| async_tree_memoization_tg  | 769 ms                                                                                                                 | 580 ms: 1.33x faster                                                                                                       |
| async_tree_io              | 1.38 sec                                                                                                               | 1.04 sec: 1.32x faster                                                                                                     |
| asyncio_tcp_ssl            | 4.01 sec                                                                                                               | 3.04 sec: 1.32x faster                                                                                                     |
| async_tree_memoization     | 789 ms                                                                                                                 | 609 ms: 1.30x faster                                                                                                       |
| async_tree_cpu_io_mixed_tg | 1.08 sec                                                                                                               | 842 ms: 1.28x faster                                                                                                       |
| async_tree_none            | 563 ms                                                                                                                 | 447 ms: 1.26x faster                                                                                                       |
| async_tree_cpu_io_mixed    | 1.09 sec                                                                                                               | 875 ms: 1.25x faster                                                                                                       |
| async_tree_none_tg         | 553 ms                                                                                                                 | 453 ms: 1.22x faster                                                                                                       |
| xml_etree_process          | 111 ms                                                                                                                 | 91.3 ms: 1.22x faster                                                                                                      |
| xml_etree_generate         | 143 ms                                                                                                                 | 123 ms: 1.16x faster                                                                                                       |
| logging_silent             | 156 ns                                                                                                                 | 138 ns: 1.14x faster                                                                                                       |
| unpickle_pure_python       | 315 us                                                                                                                 | 283 us: 1.11x faster                                                                                                       |
| 2to3                       | 412 ms                                                                                                                 | 383 ms: 1.08x faster                                                                                                       |
| subparsers                 | 64.2 ms                                                                                                                | 59.7 ms: 1.08x faster                                                                                                      |
| mako                       | 16.5 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| json                       | 6.88 ms                                                                                                                | 6.60 ms: 1.04x faster                                                                                                      |
| scimark_fft                | 465 ms                                                                                                                 | 449 ms: 1.04x faster                                                                                                       |
| xml_etree_iterparse        | 187 ms                                                                                                                 | 181 ms: 1.04x faster                                                                                                       |
| spectral_norm              | 145 ms                                                                                                                 | 143 ms: 1.01x faster                                                                                                       |
| xml_etree_parse            | 226 ms                                                                                                                 | 224 ms: 1.01x faster                                                                                                       |
| unpickle_list              | 8.08 us                                                                                                                | 8.00 us: 1.01x faster                                                                                                      |
| regex_v8                   | 35.9 ms                                                                                                                | 35.6 ms: 1.01x faster                                                                                                      |
| json_dumps                 | 13.8 ms                                                                                                                | 13.7 ms: 1.01x faster                                                                                                      |
| python_startup             | 16.4 ms                                                                                                                | 16.3 ms: 1.01x faster                                                                                                      |
| scimark_lu                 | 168 ms                                                                                                                 | 167 ms: 1.00x faster                                                                                                       |
| telco                      | 192 ms                                                                                                                 | 192 ms: 1.00x slower                                                                                                       |
| coroutines                 | 36.8 ms                                                                                                                | 36.9 ms: 1.00x slower                                                                                                      |
| logging_format             | 8.90 us                                                                                                                | 8.97 us: 1.01x slower                                                                                                      |
| logging_simple             | 7.88 us                                                                                                                | 7.99 us: 1.01x slower                                                                                                      |
| scimark_monte_carlo        | 96.9 ms                                                                                                                | 98.4 ms: 1.02x slower                                                                                                      |
| scimark_sparse_mat_mult    | 7.62 ms                                                                                                                | 7.74 ms: 1.02x slower                                                                                                      |
| async_generators           | 608 ms                                                                                                                 | 621 ms: 1.02x slower                                                                                                       |
| thrift                     | 1.13 ms                                                                                                                | 1.17 ms: 1.03x slower                                                                                                      |
| scimark_sor                | 169 ms                                                                                                                 | 175 ms: 1.04x slower                                                                                                       |
| generators                 | 44.7 ms                                                                                                                | 46.4 ms: 1.04x slower                                                                                                      |
| pickle_list                | 6.74 us                                                                                                                | 7.02 us: 1.04x slower                                                                                                      |
| pickle_dict                | 46.9 us                                                                                                                | 48.9 us: 1.04x slower                                                                                                      |
| pidigits                   | 325 ms                                                                                                                 | 340 ms: 1.05x slower                                                                                                       |
| tomli_loads                | 2.87 sec                                                                                                               | 3.00 sec: 1.05x slower                                                                                                     |
| typing_runtime_protocols   | 232 us                                                                                                                 | 243 us: 1.05x slower                                                                                                       |
| sqlite_synth               | 4.37 us                                                                                                                | 4.59 us: 1.05x slower                                                                                                      |
| richards_super             | 70.5 ms                                                                                                                | 74.5 ms: 1.06x slower                                                                                                      |
| richards                   | 62.5 ms                                                                                                                | 66.5 ms: 1.06x slower                                                                                                      |
| deepcopy_memo              | 39.6 us                                                                                                                | 42.1 us: 1.06x slower                                                                                                      |
| nbody                      | 150 ms                                                                                                                 | 161 ms: 1.07x slower                                                                                                       |
| sqlglot_v2_normalize       | 148 ms                                                                                                                 | 162 ms: 1.09x slower                                                                                                       |
| many_optionals             | 1.27 ms                                                                                                                | 1.39 ms: 1.10x slower                                                                                                      |
| fannkuch                   | 570 ms                                                                                                                 | 630 ms: 1.10x slower                                                                                                       |
| pylint                     | 392 ms                                                                                                                 | 433 ms: 1.11x slower                                                                                                       |
| pickle                     | 18.3 us                                                                                                                | 20.2 us: 1.11x slower                                                                                                      |
| sqlglot_v2_optimize        | 71.8 ms                                                                                                                | 79.7 ms: 1.11x slower                                                                                                      |
| sqlglot_v2_transpile       | 2.09 ms                                                                                                                | 2.34 ms: 1.12x slower                                                                                                      |
| sqlglot_v2_parse           | 1.63 ms                                                                                                                | 1.85 ms: 1.14x slower                                                                                                      |
| pyflate                    | 673 ms                                                                                                                 | 769 ms: 1.14x slower                                                                                                       |
| sphinx                     | 1.39 sec                                                                                                               | 1.60 sec: 1.15x slower                                                                                                     |
| raytrace                   | 381 ms                                                                                                                 | 438 ms: 1.15x slower                                                                                                       |
| deepcopy_reduce            | 3.94 us                                                                                                                | 4.55 us: 1.15x slower                                                                                                      |
| deltablue                  | 4.80 ms                                                                                                                | 5.58 ms: 1.16x slower                                                                                                      |
| sympy_integrate            | 23.0 ms                                                                                                                | 26.9 ms: 1.17x slower                                                                                                      |
| float                      | 109 ms                                                                                                                 | 128 ms: 1.17x slower                                                                                                       |
| meteor_contest             | 135 ms                                                                                                                 | 159 ms: 1.18x slower                                                                                                       |
| sympy_sum                  | 171 ms                                                                                                                 | 204 ms: 1.20x slower                                                                                                       |
| crypto_pyaes               | 102 ms                                                                                                                 | 123 ms: 1.21x slower                                                                                                       |
| regex_compile              | 144 ms                                                                                                                 | 174 ms: 1.21x slower                                                                                                       |
| mdp                        | 2.24 sec                                                                                                               | 2.72 sec: 1.22x slower                                                                                                     |
| genshi_text                | 32.5 ms                                                                                                                | 40.2 ms: 1.24x slower                                                                                                      |
| sympy_str                  | 321 ms                                                                                                                 | 401 ms: 1.25x slower                                                                                                       |
| sympy_expand               | 556 ms                                                                                                                 | 699 ms: 1.26x slower                                                                                                       |
| comprehensions             | 23.9 us                                                                                                                | 30.3 us: 1.27x slower                                                                                                      |
| bpe_tokeniser              | 6.70 sec                                                                                                               | 8.50 sec: 1.27x slower                                                                                                     |
| pathlib                    | 21.9 ms                                                                                                                | 27.8 ms: 1.27x slower                                                                                                      |
| django_template            | 50.8 ms                                                                                                                | 67.1 ms: 1.32x slower                                                                                                      |
| chaos                      | 80.5 ms                                                                                                                | 108 ms: 1.34x slower                                                                                                       |
| deepcopy                   | 366 us                                                                                                                 | 499 us: 1.36x slower                                                                                                       |
| gc_traversal               | 13.2 ms                                                                                                                | 18.1 ms: 1.37x slower                                                                                                      |
| nqueens                    | 119 ms                                                                                                                 | 165 ms: 1.38x slower                                                                                                       |
| hexiom                     | 8.38 ms                                                                                                                | 11.6 ms: 1.38x slower                                                                                                      |
| pickle_pure_python         | 441 us                                                                                                                 | 612 us: 1.39x slower                                                                                                       |
| html5lib                   | 74.8 ms                                                                                                                | 106 ms: 1.41x slower                                                                                                       |
| create_gc_cycles           | 7.68 ms                                                                                                                | 11.0 ms: 1.43x slower                                                                                                      |
| go                         | 154 ms                                                                                                                 | 231 ms: 1.49x slower                                                                                                       |
| genshi_xml                 | 74.4 ms                                                                                                                | 118 ms: 1.58x slower                                                                                                       |
| unpack_sequence            | 63.3 ns                                                                                                                | 101 ns: 1.59x slower                                                                                                       |
| pprint_safe_repr           | 1.05 sec                                                                                                               | 1.72 sec: 1.64x slower                                                                                                     |
| pprint_pformat             | 2.14 sec                                                                                                               | 3.65 sec: 1.70x slower                                                                                                     |
| pycparser                  | 1.62 sec                                                                                                               | 3.05 sec: 1.88x slower                                                                                                     |
| dulwich_log                | 62.2 ms                                                                                                                | 119 ms: 1.92x slower                                                                                                       |
| bench_thread_pool          | 1.13 ms                                                                                                                | 2.26 ms: 2.00x slower                                                                                                      |
| Geometric mean             | (ref)                                                                                                                  | 1.09x slower                                                                                                               |

Benchmark hidden because not significant (8): regex_dna, python_startup_no_site, regex_effbot, json_loads, unpickle, asyncio_websockets, coverage, bench_mp_pool
Ignored benchmarks (1) of results/bm-20251119-3.15.0a2+-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2+-ca1e86f.json: docutils

- Geometric mean (including insignificant results): 1.073x slower

# HPT report

- Reliability score: 99.82% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x

# Memory
- memory change: 1.03x