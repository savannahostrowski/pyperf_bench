# Results vs. base

- fork: python
- ref: 5348c200f5b26d6dd21d
- machine: linux-aarch64
- commit hash: 5348c20
- commit date: 2025-11-16
- overall geometric mean: 1.079x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 377 ms                                                                                                                 | 460 ms: 1.22x slower                                                                                                       |
| html5lib       | 74.7 ms                                                                                                                | 108 ms: 1.44x slower                                                                                                       |
| sphinx         | 1.40 sec                                                                                                               | 1.62 sec: 1.16x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.27x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines                | 36.5 ms                                                                                                                | 36.6 ms: 1.00x slower                                                                                                      |
| asyncio_tcp_ssl           | 3.05 sec                                                                                                               | 3.07 sec: 1.01x slower                                                                                                     |
| asyncio_tcp               | 692 ms                                                                                                                 | 700 ms: 1.01x slower                                                                                                       |
| async_tree_memoization_tg | 583 ms                                                                                                                 | 597 ms: 1.02x slower                                                                                                       |
| async_generators          | 584 ms                                                                                                                 | 630 ms: 1.08x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (8): async_tree_io_tg, asyncio_websockets, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_io, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 113 ms                                                                                                                 | 105 ms: 1.08x faster                                                                                                       |
| pidigits       | 324 ms                                                                                                                 | 325 ms: 1.00x slower                                                                                                       |
| nbody          | 150 ms                                                                                                                 | 154 ms: 1.03x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.38 ms                                                                                                                | 4.39 ms: 1.00x slower                                                                                                      |
| regex_v8       | 35.5 ms                                                                                                                | 35.6 ms: 1.00x slower                                                                                                      |
| regex_compile  | 144 ms                                                                                                                 | 176 ms: 1.22x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 316 us                                                                                                                 | 285 us: 1.11x faster                                                                                                       |
| xml_etree_process    | 96.0 ms                                                                                                                | 93.4 ms: 1.03x faster                                                                                                      |
| xml_etree_generate   | 127 ms                                                                                                                 | 125 ms: 1.02x faster                                                                                                       |
| xml_etree_parse      | 227 ms                                                                                                                 | 224 ms: 1.02x faster                                                                                                       |
| xml_etree_iterparse  | 184 ms                                                                                                                 | 182 ms: 1.01x faster                                                                                                       |
| unpickle             | 21.8 us                                                                                                                | 21.6 us: 1.01x faster                                                                                                      |
| unpickle_list        | 8.04 us                                                                                                                | 8.00 us: 1.00x faster                                                                                                      |
| json_dumps           | 13.8 ms                                                                                                                | 13.7 ms: 1.00x faster                                                                                                      |
| json_loads           | 38.3 us                                                                                                                | 38.1 us: 1.00x faster                                                                                                      |
| pickle               | 18.7 us                                                                                                                | 18.6 us: 1.00x faster                                                                                                      |
| pickle_pure_python   | 445 us                                                                                                                 | 448 us: 1.01x slower                                                                                                       |
| pickle_dict          | 46.5 us                                                                                                                | 46.9 us: 1.01x slower                                                                                                      |
| tomli_loads          | 2.87 sec                                                                                                               | 3.12 sec: 1.09x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 9.45 ms                                                                                                                | 9.51 ms: 1.01x slower                                                                                                      |
| python_startup         | 16.3 ms                                                                                                                | 16.5 ms: 1.01x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.9 ms                                                                                                                | 15.8 ms: 1.07x faster                                                                                                      |
| django_template | 49.6 ms                                                                                                                | 55.8 ms: 1.12x slower                                                                                                      |
| genshi_text     | 32.0 ms                                                                                                                | 40.5 ms: 1.26x slower                                                                                                      |
| genshi_xml      | 73.0 ms                                                                                                                | 122 ms: 1.67x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.22x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json | results/bm-20251116-3.15.0a1+-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| logging_silent            | 156 ns                                                                                                                 | 137 ns: 1.14x faster                                                                                                       |
| unpickle_pure_python      | 316 us                                                                                                                 | 285 us: 1.11x faster                                                                                                       |
| float                     | 113 ms                                                                                                                 | 105 ms: 1.08x faster                                                                                                       |
| mako                      | 16.9 ms                                                                                                                | 15.8 ms: 1.07x faster                                                                                                      |
| scimark_fft               | 464 ms                                                                                                                 | 443 ms: 1.05x faster                                                                                                       |
| sqlite_synth              | 4.54 us                                                                                                                | 4.41 us: 1.03x faster                                                                                                      |
| xml_etree_process         | 96.0 ms                                                                                                                | 93.4 ms: 1.03x faster                                                                                                      |
| create_gc_cycles          | 7.85 ms                                                                                                                | 7.67 ms: 1.02x faster                                                                                                      |
| deepcopy_memo             | 40.4 us                                                                                                                | 39.7 us: 1.02x faster                                                                                                      |
| json                      | 6.77 ms                                                                                                                | 6.66 ms: 1.02x faster                                                                                                      |
| xml_etree_generate        | 127 ms                                                                                                                 | 125 ms: 1.02x faster                                                                                                       |
| xml_etree_parse           | 227 ms                                                                                                                 | 224 ms: 1.02x faster                                                                                                       |
| spectral_norm             | 145 ms                                                                                                                 | 143 ms: 1.01x faster                                                                                                       |
| scimark_lu                | 169 ms                                                                                                                 | 167 ms: 1.01x faster                                                                                                       |
| coverage                  | 123 ms                                                                                                                 | 122 ms: 1.01x faster                                                                                                       |
| xml_etree_iterparse       | 184 ms                                                                                                                 | 182 ms: 1.01x faster                                                                                                       |
| gc_traversal              | 13.3 ms                                                                                                                | 13.2 ms: 1.01x faster                                                                                                      |
| unpickle                  | 21.8 us                                                                                                                | 21.6 us: 1.01x faster                                                                                                      |
| unpickle_list             | 8.04 us                                                                                                                | 8.00 us: 1.00x faster                                                                                                      |
| json_dumps                | 13.8 ms                                                                                                                | 13.7 ms: 1.00x faster                                                                                                      |
| json_loads                | 38.3 us                                                                                                                | 38.1 us: 1.00x faster                                                                                                      |
| pickle                    | 18.7 us                                                                                                                | 18.6 us: 1.00x faster                                                                                                      |
| pidigits                  | 324 ms                                                                                                                 | 325 ms: 1.00x slower                                                                                                       |
| regex_effbot              | 4.38 ms                                                                                                                | 4.39 ms: 1.00x slower                                                                                                      |
| regex_v8                  | 35.5 ms                                                                                                                | 35.6 ms: 1.00x slower                                                                                                      |
| coroutines                | 36.5 ms                                                                                                                | 36.6 ms: 1.00x slower                                                                                                      |
| pickle_pure_python        | 445 us                                                                                                                 | 448 us: 1.01x slower                                                                                                       |
| python_startup_no_site    | 9.45 ms                                                                                                                | 9.51 ms: 1.01x slower                                                                                                      |
| bpe_tokeniser             | 6.76 sec                                                                                                               | 6.80 sec: 1.01x slower                                                                                                     |
| scimark_sparse_mat_mult   | 7.62 ms                                                                                                                | 7.68 ms: 1.01x slower                                                                                                      |
| asyncio_tcp_ssl           | 3.05 sec                                                                                                               | 3.07 sec: 1.01x slower                                                                                                     |
| scimark_sor               | 168 ms                                                                                                                 | 170 ms: 1.01x slower                                                                                                       |
| pickle_dict               | 46.5 us                                                                                                                | 46.9 us: 1.01x slower                                                                                                      |
| python_startup            | 16.3 ms                                                                                                                | 16.5 ms: 1.01x slower                                                                                                      |
| scimark_monte_carlo       | 96.8 ms                                                                                                                | 97.8 ms: 1.01x slower                                                                                                      |
| asyncio_tcp               | 692 ms                                                                                                                 | 700 ms: 1.01x slower                                                                                                       |
| subparsers                | 59.2 ms                                                                                                                | 60.4 ms: 1.02x slower                                                                                                      |
| pyflate                   | 676 ms                                                                                                                 | 691 ms: 1.02x slower                                                                                                       |
| async_tree_memoization_tg | 583 ms                                                                                                                 | 597 ms: 1.02x slower                                                                                                       |
| nbody                     | 150 ms                                                                                                                 | 154 ms: 1.03x slower                                                                                                       |
| generators                | 44.6 ms                                                                                                                | 46.0 ms: 1.03x slower                                                                                                      |
| bench_thread_pool         | 1.12 ms                                                                                                                | 1.16 ms: 1.04x slower                                                                                                      |
| pathlib                   | 21.4 ms                                                                                                                | 22.4 ms: 1.04x slower                                                                                                      |
| deltablue                 | 4.80 ms                                                                                                                | 5.02 ms: 1.05x slower                                                                                                      |
| telco                     | 186 ms                                                                                                                 | 195 ms: 1.05x slower                                                                                                       |
| thrift                    | 1.12 ms                                                                                                                | 1.18 ms: 1.05x slower                                                                                                      |
| richards_super            | 70.9 ms                                                                                                                | 74.8 ms: 1.05x slower                                                                                                      |
| meteor_contest            | 134 ms                                                                                                                 | 141 ms: 1.06x slower                                                                                                       |
| deepcopy_reduce           | 4.06 us                                                                                                                | 4.30 us: 1.06x slower                                                                                                      |
| fannkuch                  | 572 ms                                                                                                                 | 609 ms: 1.06x slower                                                                                                       |
| logging_simple            | 7.68 us                                                                                                                | 8.19 us: 1.07x slower                                                                                                      |
| richards                  | 63.0 ms                                                                                                                | 67.3 ms: 1.07x slower                                                                                                      |
| logging_format            | 8.50 us                                                                                                                | 9.12 us: 1.07x slower                                                                                                      |
| async_generators          | 584 ms                                                                                                                 | 630 ms: 1.08x slower                                                                                                       |
| crypto_pyaes              | 102 ms                                                                                                                 | 111 ms: 1.09x slower                                                                                                       |
| tomli_loads               | 2.87 sec                                                                                                               | 3.12 sec: 1.09x slower                                                                                                     |
| sqlglot_v2_parse          | 1.71 ms                                                                                                                | 1.87 ms: 1.09x slower                                                                                                      |
| sqlglot_v2_normalize      | 147 ms                                                                                                                 | 164 ms: 1.11x slower                                                                                                       |
| pylint                    | 394 ms                                                                                                                 | 438 ms: 1.11x slower                                                                                                       |
| django_template           | 49.6 ms                                                                                                                | 55.8 ms: 1.12x slower                                                                                                      |
| many_optionals            | 1.26 ms                                                                                                                | 1.42 ms: 1.13x slower                                                                                                      |
| sqlglot_v2_optimize       | 71.2 ms                                                                                                                | 80.6 ms: 1.13x slower                                                                                                      |
| sqlglot_v2_transpile      | 2.09 ms                                                                                                                | 2.36 ms: 1.13x slower                                                                                                      |
| raytrace                  | 380 ms                                                                                                                 | 438 ms: 1.15x slower                                                                                                       |
| sphinx                    | 1.40 sec                                                                                                               | 1.62 sec: 1.16x slower                                                                                                     |
| typing_runtime_protocols  | 222 us                                                                                                                 | 258 us: 1.16x slower                                                                                                       |
| mdp                       | 2.31 sec                                                                                                               | 2.69 sec: 1.17x slower                                                                                                     |
| sympy_integrate           | 22.8 ms                                                                                                                | 27.2 ms: 1.19x slower                                                                                                      |
| pycparser                 | 1.62 sec                                                                                                               | 1.97 sec: 1.22x slower                                                                                                     |
| regex_compile             | 144 ms                                                                                                                 | 176 ms: 1.22x slower                                                                                                       |
| 2to3                      | 377 ms                                                                                                                 | 460 ms: 1.22x slower                                                                                                       |
| sympy_sum                 | 169 ms                                                                                                                 | 207 ms: 1.22x slower                                                                                                       |
| chaos                     | 80.1 ms                                                                                                                | 98.9 ms: 1.23x slower                                                                                                      |
| comprehensions            | 24.0 us                                                                                                                | 30.1 us: 1.25x slower                                                                                                      |
| genshi_text               | 32.0 ms                                                                                                                | 40.5 ms: 1.26x slower                                                                                                      |
| nqueens                   | 119 ms                                                                                                                 | 151 ms: 1.27x slower                                                                                                       |
| sympy_str                 | 316 ms                                                                                                                 | 409 ms: 1.29x slower                                                                                                       |
| sympy_expand              | 545 ms                                                                                                                 | 712 ms: 1.31x slower                                                                                                       |
| deepcopy                  | 369 us                                                                                                                 | 496 us: 1.34x slower                                                                                                       |
| hexiom                    | 8.45 ms                                                                                                                | 11.7 ms: 1.39x slower                                                                                                      |
| pprint_pformat            | 2.11 sec                                                                                                               | 2.95 sec: 1.40x slower                                                                                                     |
| pprint_safe_repr          | 1.03 sec                                                                                                               | 1.45 sec: 1.40x slower                                                                                                     |
| html5lib                  | 74.7 ms                                                                                                                | 108 ms: 1.44x slower                                                                                                       |
| dulwich_log               | 61.1 ms                                                                                                                | 90.2 ms: 1.48x slower                                                                                                      |
| go                        | 155 ms                                                                                                                 | 235 ms: 1.52x slower                                                                                                       |
| unpack_sequence           | 64.4 ns                                                                                                                | 99.9 ns: 1.55x slower                                                                                                      |
| genshi_xml                | 73.0 ms                                                                                                                | 122 ms: 1.67x slower                                                                                                       |
| bench_mp_pool             | 127 ms                                                                                                                 | 307 ms: 2.41x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.09x slower                                                                                                               |

Benchmark hidden because not significant (10): regex_dna, async_tree_io_tg, pickle_list, asyncio_websockets, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_io, async_tree_memoization
Ignored benchmarks (1) of results/bm-20251116-3.15.0a1+-5348c20/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1+-5348c20.json: docutils

- Geometric mean (including insignificant results): 1.079x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x

# Memory
- memory change: 1.03x