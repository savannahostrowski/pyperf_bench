# Results vs. base

- fork: python
- ref: b1c4bdaaf74ded2039b7
- machine: linux-x86_64
- commit hash: b1c4bda
- commit date: 2026-06-22
- overall geometric mean: 1.070x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| chameleon      | 18.6 ms                                                                                                          | 17.6 ms: 1.06x faster                                                                                                |
| docutils       | 3.48 sec                                                                                                         | 3.57 sec: 1.03x slower                                                                                               |
| html5lib       | 84.9 ms                                                                                                          | 98.1 ms: 1.16x slower                                                                                                |
| sphinx         | 1.39 sec                                                                                                         | 1.41 sec: 1.02x slower                                                                                               |
| Geometric mean | (ref)                                                                                                            | 1.02x slower                                                                                                         |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| async_tree_memoization     | 513 ms                                                                                                           | 470 ms: 1.09x faster                                                                                                 |
| async_tree_none_tg         | 407 ms                                                                                                           | 377 ms: 1.08x faster                                                                                                 |
| async_tree_none            | 402 ms                                                                                                           | 375 ms: 1.07x faster                                                                                                 |
| async_tree_cpu_io_mixed_tg | 767 ms                                                                                                           | 725 ms: 1.06x faster                                                                                                 |
| async_tree_memoization_tg  | 500 ms                                                                                                           | 475 ms: 1.05x faster                                                                                                 |
| async_tree_io_tg           | 1.01 sec                                                                                                         | 961 ms: 1.05x faster                                                                                                 |
| async_tree_cpu_io_mixed    | 748 ms                                                                                                           | 722 ms: 1.04x faster                                                                                                 |
| asyncio_tcp                | 591 ms                                                                                                           | 572 ms: 1.03x faster                                                                                                 |
| async_tree_io              | 967 ms                                                                                                           | 940 ms: 1.03x faster                                                                                                 |
| asyncio_tcp_ssl            | 2.07 sec                                                                                                         | 2.04 sec: 1.01x faster                                                                                               |
| async_generators           | 487 ms                                                                                                           | 503 ms: 1.03x slower                                                                                                 |
| coroutines                 | 32.5 ms                                                                                                          | 33.7 ms: 1.04x slower                                                                                                |
| Geometric mean             | (ref)                                                                                                            | 1.03x faster                                                                                                         |

Benchmark hidden because not significant (1): asyncio_websockets

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| nbody          | 129 ms                                                                                                           | 91.3 ms: 1.42x faster                                                                                                |
| float          | 105 ms                                                                                                           | 77.5 ms: 1.36x faster                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.24x faster                                                                                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 175 ms                                                                                                           | 171 ms: 1.03x faster                                                                                                 |
| regex_v8       | 30.2 ms                                                                                                          | 30.0 ms: 1.01x faster                                                                                                |
| regex_dna      | 247 ms                                                                                                           | 249 ms: 1.01x slower                                                                                                 |
| regex_effbot   | 3.86 ms                                                                                                          | 4.02 ms: 1.04x slower                                                                                                |
| Geometric mean | (ref)                                                                                                            | 1.00x slower                                                                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 296 us                                                                                                           | 259 us: 1.14x faster                                                                                                 |
| pickle_pure_python   | 436 us                                                                                                           | 383 us: 1.14x faster                                                                                                 |
| json_dumps           | 14.1 ms                                                                                                          | 12.8 ms: 1.10x faster                                                                                                |
| base32_small         | 425 us                                                                                                           | 388 us: 1.09x faster                                                                                                 |
| base64_small         | 459 us                                                                                                           | 423 us: 1.08x faster                                                                                                 |
| xml_etree_process    | 86.9 ms                                                                                                          | 80.2 ms: 1.08x faster                                                                                                |
| base16_large         | 15.5 ms                                                                                                          | 14.7 ms: 1.05x faster                                                                                                |
| urlsafe_base64_small | 511 us                                                                                                           | 488 us: 1.05x faster                                                                                                 |
| pickle_list          | 8.12 us                                                                                                          | 7.75 us: 1.05x faster                                                                                                |
| xml_etree_generate   | 123 ms                                                                                                           | 118 ms: 1.04x faster                                                                                                 |
| unpickle_list        | 7.71 us                                                                                                          | 7.44 us: 1.04x faster                                                                                                |
| tomli_loads          | 2.64 sec                                                                                                         | 2.55 sec: 1.04x faster                                                                                               |
| ascii85_small        | 1.03 ms                                                                                                          | 998 us: 1.03x faster                                                                                                 |
| unpickle             | 22.0 us                                                                                                          | 21.3 us: 1.03x faster                                                                                                |
| base85_small         | 377 us                                                                                                           | 367 us: 1.03x faster                                                                                                 |
| xml_etree_iterparse  | 129 ms                                                                                                           | 125 ms: 1.03x faster                                                                                                 |
| base16_small         | 777 us                                                                                                           | 759 us: 1.02x faster                                                                                                 |
| json_loads           | 39.4 us                                                                                                          | 38.9 us: 1.01x faster                                                                                                |
| base85_large         | 7.56 ms                                                                                                          | 7.55 ms: 1.00x faster                                                                                                |
| base64_large         | 3.52 ms                                                                                                          | 3.52 ms: 1.00x faster                                                                                                |
| base32_large         | 4.44 ms                                                                                                          | 4.44 ms: 1.00x faster                                                                                                |
| ascii85_large        | 20.5 ms                                                                                                          | 20.5 ms: 1.00x slower                                                                                                |
| pickle_dict          | 47.3 us                                                                                                          | 48.8 us: 1.03x slower                                                                                                |
| Geometric mean       | (ref)                                                                                                            | 1.04x faster                                                                                                         |

Benchmark hidden because not significant (2): xml_etree_parse, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 17.5 ms                                                                                                          | 17.7 ms: 1.01x slower                                                                                                |
| python_startup_no_site | 9.84 ms                                                                                                          | 10.0 ms: 1.02x slower                                                                                                |
| Geometric mean         | (ref)                                                                                                            | 1.01x slower                                                                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| mako            | 17.6 ms                                                                                                          | 14.2 ms: 1.24x faster                                                                                                |
| django_template | 51.2 ms                                                                                                          | 57.1 ms: 1.12x slower                                                                                                |
| Geometric mean  | (ref)                                                                                                            | 1.05x faster                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20260622-3.16.0a0-b1c4bda/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json | results/bm-20260622-3.16.0a0-b1c4bda-JIT/bm-20260622-ripley-x86_64-python-b1c4bdaaf74ded2039b7-3.16.0a0-b1c4bda.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| richards_super             | 69.3 ms                                                                                                          | 29.4 ms: 2.35x faster                                                                                                |
| richards                   | 60.7 ms                                                                                                          | 26.8 ms: 2.27x faster                                                                                                |
| bench_mp_pool              | 242 ms                                                                                                           | 157 ms: 1.55x faster                                                                                                 |
| nbody                      | 129 ms                                                                                                           | 91.3 ms: 1.42x faster                                                                                                |
| scimark_sor                | 151 ms                                                                                                           | 110 ms: 1.38x faster                                                                                                 |
| scimark_lu                 | 161 ms                                                                                                           | 117 ms: 1.37x faster                                                                                                 |
| float                      | 105 ms                                                                                                           | 77.5 ms: 1.36x faster                                                                                                |
| spectral_norm              | 131 ms                                                                                                           | 101 ms: 1.29x faster                                                                                                 |
| scimark_monte_carlo        | 90.4 ms                                                                                                          | 72.8 ms: 1.24x faster                                                                                                |
| mako                       | 17.6 ms                                                                                                          | 14.2 ms: 1.24x faster                                                                                                |
| scimark_fft                | 460 ms                                                                                                           | 372 ms: 1.24x faster                                                                                                 |
| deepcopy_memo              | 37.3 us                                                                                                          | 31.3 us: 1.19x faster                                                                                                |
| telco                      | 227 ms                                                                                                           | 193 ms: 1.18x faster                                                                                                 |
| deltablue                  | 4.54 ms                                                                                                          | 3.86 ms: 1.18x faster                                                                                                |
| pprint_safe_repr           | 1.02 sec                                                                                                         | 876 ms: 1.16x faster                                                                                                 |
| pyflate                    | 573 ms                                                                                                           | 494 ms: 1.16x faster                                                                                                 |
| fannkuch                   | 536 ms                                                                                                           | 468 ms: 1.14x faster                                                                                                 |
| unpickle_pure_python       | 296 us                                                                                                           | 259 us: 1.14x faster                                                                                                 |
| nqueens                    | 104 ms                                                                                                           | 91.6 ms: 1.14x faster                                                                                                |
| pickle_pure_python         | 436 us                                                                                                           | 383 us: 1.14x faster                                                                                                 |
| scimark_sparse_mat_mult    | 6.77 ms                                                                                                          | 5.96 ms: 1.14x faster                                                                                                |
| chaos                      | 77.5 ms                                                                                                          | 69.0 ms: 1.12x faster                                                                                                |
| pprint_pformat             | 2.06 sec                                                                                                         | 1.85 sec: 1.11x faster                                                                                               |
| logging_simple             | 8.52 us                                                                                                          | 7.69 us: 1.11x faster                                                                                                |
| logging_format             | 9.74 us                                                                                                          | 8.83 us: 1.10x faster                                                                                                |
| json_dumps                 | 14.1 ms                                                                                                          | 12.8 ms: 1.10x faster                                                                                                |
| base32_small               | 425 us                                                                                                           | 388 us: 1.09x faster                                                                                                 |
| async_tree_memoization     | 513 ms                                                                                                           | 470 ms: 1.09x faster                                                                                                 |
| base64_small               | 459 us                                                                                                           | 423 us: 1.08x faster                                                                                                 |
| xml_etree_process          | 86.9 ms                                                                                                          | 80.2 ms: 1.08x faster                                                                                                |
| async_tree_none_tg         | 407 ms                                                                                                           | 377 ms: 1.08x faster                                                                                                 |
| gc_traversal               | 5.85 ms                                                                                                          | 5.42 ms: 1.08x faster                                                                                                |
| sqlglot_v2_normalize       | 147 ms                                                                                                           | 136 ms: 1.08x faster                                                                                                 |
| async_tree_none            | 402 ms                                                                                                           | 375 ms: 1.07x faster                                                                                                 |
| comprehensions             | 22.2 us                                                                                                          | 20.8 us: 1.07x faster                                                                                                |
| typing_runtime_protocols   | 166 us                                                                                                           | 156 us: 1.07x faster                                                                                                 |
| chameleon                  | 18.6 ms                                                                                                          | 17.6 ms: 1.06x faster                                                                                                |
| async_tree_cpu_io_mixed_tg | 767 ms                                                                                                           | 725 ms: 1.06x faster                                                                                                 |
| async_tree_memoization_tg  | 500 ms                                                                                                           | 475 ms: 1.05x faster                                                                                                 |
| base16_large               | 15.5 ms                                                                                                          | 14.7 ms: 1.05x faster                                                                                                |
| bpe_tokeniser              | 5.94 sec                                                                                                         | 5.65 sec: 1.05x faster                                                                                               |
| async_tree_io_tg           | 1.01 sec                                                                                                         | 961 ms: 1.05x faster                                                                                                 |
| urlsafe_base64_small       | 511 us                                                                                                           | 488 us: 1.05x faster                                                                                                 |
| crypto_pyaes               | 98.4 ms                                                                                                          | 93.9 ms: 1.05x faster                                                                                                |
| pickle_list                | 8.12 us                                                                                                          | 7.75 us: 1.05x faster                                                                                                |
| meteor_contest             | 143 ms                                                                                                           | 137 ms: 1.05x faster                                                                                                 |
| shortest_path              | 513 ms                                                                                                           | 491 ms: 1.05x faster                                                                                                 |
| connected_components       | 459 ms                                                                                                           | 439 ms: 1.04x faster                                                                                                 |
| sqlite_synth               | 3.13 us                                                                                                          | 3.01 us: 1.04x faster                                                                                                |
| subparsers                 | 13.4 ms                                                                                                          | 12.9 ms: 1.04x faster                                                                                                |
| xml_etree_generate         | 123 ms                                                                                                           | 118 ms: 1.04x faster                                                                                                 |
| sqlglot_v2_transpile       | 2.04 ms                                                                                                          | 1.97 ms: 1.04x faster                                                                                                |
| unpickle_list              | 7.71 us                                                                                                          | 7.44 us: 1.04x faster                                                                                                |
| async_tree_cpu_io_mixed    | 748 ms                                                                                                           | 722 ms: 1.04x faster                                                                                                 |
| tomli_loads                | 2.64 sec                                                                                                         | 2.55 sec: 1.04x faster                                                                                               |
| asyncio_tcp                | 591 ms                                                                                                           | 572 ms: 1.03x faster                                                                                                 |
| ascii85_small              | 1.03 ms                                                                                                          | 998 us: 1.03x faster                                                                                                 |
| json                       | 7.18 ms                                                                                                          | 6.95 ms: 1.03x faster                                                                                                |
| unpickle                   | 22.0 us                                                                                                          | 21.3 us: 1.03x faster                                                                                                |
| sqlglot_v2_parse           | 1.61 ms                                                                                                          | 1.56 ms: 1.03x faster                                                                                                |
| async_tree_io              | 967 ms                                                                                                           | 940 ms: 1.03x faster                                                                                                 |
| sqlglot_v2_optimize        | 72.7 ms                                                                                                          | 70.7 ms: 1.03x faster                                                                                                |
| go                         | 146 ms                                                                                                           | 142 ms: 1.03x faster                                                                                                 |
| base85_small               | 377 us                                                                                                           | 367 us: 1.03x faster                                                                                                 |
| regex_compile              | 175 ms                                                                                                           | 171 ms: 1.03x faster                                                                                                 |
| sympy_expand               | 659 ms                                                                                                           | 642 ms: 1.03x faster                                                                                                 |
| xml_etree_iterparse        | 129 ms                                                                                                           | 125 ms: 1.03x faster                                                                                                 |
| base16_small               | 777 us                                                                                                           | 759 us: 1.02x faster                                                                                                 |
| pathlib                    | 25.1 ms                                                                                                          | 24.5 ms: 1.02x faster                                                                                                |
| create_gc_cycles           | 2.54 ms                                                                                                          | 2.50 ms: 1.02x faster                                                                                                |
| raytrace                   | 357 ms                                                                                                           | 351 ms: 1.02x faster                                                                                                 |
| json_loads                 | 39.4 us                                                                                                          | 38.9 us: 1.01x faster                                                                                                |
| asyncio_tcp_ssl            | 2.07 sec                                                                                                         | 2.04 sec: 1.01x faster                                                                                               |
| coverage                   | 119 ms                                                                                                           | 117 ms: 1.01x faster                                                                                                 |
| regex_v8                   | 30.2 ms                                                                                                          | 30.0 ms: 1.01x faster                                                                                                |
| base85_large               | 7.56 ms                                                                                                          | 7.55 ms: 1.00x faster                                                                                                |
| base64_large               | 3.52 ms                                                                                                          | 3.52 ms: 1.00x faster                                                                                                |
| base32_large               | 4.44 ms                                                                                                          | 4.44 ms: 1.00x faster                                                                                                |
| ascii85_large              | 20.5 ms                                                                                                          | 20.5 ms: 1.00x slower                                                                                                |
| regex_dna                  | 247 ms                                                                                                           | 249 ms: 1.01x slower                                                                                                 |
| sqlalchemy_declarative     | 186 ms                                                                                                           | 188 ms: 1.01x slower                                                                                                 |
| python_startup             | 17.5 ms                                                                                                          | 17.7 ms: 1.01x slower                                                                                                |
| python_startup_no_site     | 9.84 ms                                                                                                          | 10.0 ms: 1.02x slower                                                                                                |
| sphinx                     | 1.39 sec                                                                                                         | 1.41 sec: 1.02x slower                                                                                               |
| deepcopy                   | 333 us                                                                                                           | 341 us: 1.02x slower                                                                                                 |
| sqlalchemy_imperative      | 28.7 ms                                                                                                          | 29.4 ms: 1.02x slower                                                                                                |
| thrift                     | 1.10 ms                                                                                                          | 1.13 ms: 1.02x slower                                                                                                |
| docutils                   | 3.48 sec                                                                                                         | 3.57 sec: 1.03x slower                                                                                               |
| pickle_dict                | 47.3 us                                                                                                          | 48.8 us: 1.03x slower                                                                                                |
| sympy_str                  | 391 ms                                                                                                           | 403 ms: 1.03x slower                                                                                                 |
| pycparser                  | 1.57 sec                                                                                                         | 1.62 sec: 1.03x slower                                                                                               |
| async_generators           | 487 ms                                                                                                           | 503 ms: 1.03x slower                                                                                                 |
| deepcopy_reduce            | 3.64 us                                                                                                          | 3.78 us: 1.04x slower                                                                                                |
| coroutines                 | 32.5 ms                                                                                                          | 33.7 ms: 1.04x slower                                                                                                |
| regex_effbot               | 3.86 ms                                                                                                          | 4.02 ms: 1.04x slower                                                                                                |
| sympy_integrate            | 27.3 ms                                                                                                          | 28.4 ms: 1.04x slower                                                                                                |
| generators                 | 40.0 ms                                                                                                          | 41.9 ms: 1.05x slower                                                                                                |
| xdsl_constant_fold         | 64.0 ms                                                                                                          | 67.8 ms: 1.06x slower                                                                                                |
| pylint                     | 162 ms                                                                                                           | 171 ms: 1.06x slower                                                                                                 |
| many_optionals             | 1.30 ms                                                                                                          | 1.40 ms: 1.07x slower                                                                                                |
| sympy_sum                  | 225 ms                                                                                                           | 243 ms: 1.08x slower                                                                                                 |
| mdp                        | 1.63 sec                                                                                                         | 1.77 sec: 1.09x slower                                                                                               |
| k_core                     | 2.49 sec                                                                                                         | 2.77 sec: 1.11x slower                                                                                               |
| django_template            | 51.2 ms                                                                                                          | 57.1 ms: 1.12x slower                                                                                                |
| html5lib                   | 84.9 ms                                                                                                          | 98.1 ms: 1.16x slower                                                                                                |
| unpack_sequence            | 62.5 ns                                                                                                          | 108 ns: 1.73x slower                                                                                                 |
| Geometric mean             | (ref)                                                                                                            | 1.06x faster                                                                                                         |

Benchmark hidden because not significant (10): logging_silent, hexiom, xml_etree_parse, bench_thread_pool, tornado_http, 2to3, asyncio_websockets, pidigits, pickle, dulwich_log

- Geometric mean (including insignificant results): 1.070x faster

# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x

# Memory
- memory change: 1.02x