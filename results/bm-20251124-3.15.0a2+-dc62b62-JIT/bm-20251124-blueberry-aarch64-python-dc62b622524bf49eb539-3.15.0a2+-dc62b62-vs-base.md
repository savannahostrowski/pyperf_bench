# Results vs. base

- fork: python
- ref: dc62b622524bf49eb539
- machine: linux-aarch64
- commit hash: dc62b62
- commit date: 2025-11-24
- overall geometric mean: 1.108x faster
- HPT reliability: 89.63%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 375 ms                                                                                                                 | 383 ms: 1.02x slower                                                                                                       |
| docutils       | 5.71 sec                                                                                                               | 4.81 sec: 1.19x faster                                                                                                     |
| html5lib       | 91.0 ms                                                                                                                | 105 ms: 1.15x slower                                                                                                       |
| sphinx         | 1.75 sec                                                                                                               | 28.8 ms: 60.73x faster                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 2.80x faster                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg         | 454 ms                                                                                                                 | 440 ms: 1.03x faster                                                                                                       |
| async_tree_cpu_io_mixed_tg | 850 ms                                                                                                                 | 828 ms: 1.03x faster                                                                                                       |
| asyncio_websockets         | 830 ms                                                                                                                 | 818 ms: 1.01x faster                                                                                                       |
| coroutines                 | 36.8 ms                                                                                                                | 36.9 ms: 1.00x slower                                                                                                      |
| asyncio_tcp_ssl            | 2.83 sec                                                                                                               | 2.86 sec: 1.01x slower                                                                                                     |
| async_tree_none            | 443 ms                                                                                                                 | 454 ms: 1.02x slower                                                                                                       |
| async_generators           | 575 ms                                                                                                                 | 614 ms: 1.07x slower                                                                                                       |
| Geometric mean             | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed, async_tree_memoization_tg, asyncio_tcp, async_tree_io_tg, async_tree_memoization, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 132 ms                                                                                                                 | 104 ms: 1.27x faster                                                                                                       |
| pidigits       | 325 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| nbody          | 148 ms                                                                                                                 | 154 ms: 1.04x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.07x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 38.4 ms                                                                                                                | 35.5 ms: 1.08x faster                                                                                                      |
| regex_dna      | 278 ms                                                                                                                 | 264 ms: 1.05x faster                                                                                                       |
| regex_effbot   | 4.66 ms                                                                                                                | 4.54 ms: 1.03x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.04x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| xml_etree_iterparse  | 244 ms                                                                                                                 | 179 ms: 1.36x faster                                                                                                       |
| xml_etree_parse      | 287 ms                                                                                                                 | 223 ms: 1.29x faster                                                                                                       |
| xml_etree_generate   | 156 ms                                                                                                                 | 124 ms: 1.26x faster                                                                                                       |
| unpickle_pure_python | 354 us                                                                                                                 | 286 us: 1.24x faster                                                                                                       |
| xml_etree_process    | 112 ms                                                                                                                 | 92.5 ms: 1.21x faster                                                                                                      |
| json_dumps           | 14.9 ms                                                                                                                | 13.7 ms: 1.08x faster                                                                                                      |
| json_loads           | 40.9 us                                                                                                                | 37.9 us: 1.08x faster                                                                                                      |
| unpickle             | 23.0 us                                                                                                                | 21.8 us: 1.06x faster                                                                                                      |
| tomli_loads          | 3.21 sec                                                                                                               | 3.06 sec: 1.05x faster                                                                                                     |
| unpickle_list        | 8.28 us                                                                                                                | 8.10 us: 1.02x faster                                                                                                      |
| pickle_list          | 6.88 us                                                                                                                | 6.81 us: 1.01x faster                                                                                                      |
| pickle_dict          | 47.1 us                                                                                                                | 47.0 us: 1.00x faster                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.11x faster                                                                                                               |

Benchmark hidden because not significant (2): pickle_pure_python, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 31.2 ms                                                                                                                | 16.4 ms: 1.91x faster                                                                                                      |
| python_startup_no_site | 17.7 ms                                                                                                                | 9.54 ms: 1.86x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.88x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako           | 18.8 ms                                                                                                                | 15.5 ms: 1.21x faster                                                                                                      |
| genshi_text    | 36.3 ms                                                                                                                | 40.5 ms: 1.12x slower                                                                                                      |
| genshi_xml     | 77.7 ms                                                                                                                | 120 ms: 1.54x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.09x slower                                                                                                               |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                  | results/bm-20251124-3.15.0a2+-dc62b62/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json | results/bm-20251124-3.15.0a2+-dc62b62-JIT/bm-20251124-blueberry-aarch64-python-dc62b622524bf49eb539-3.15.0a2+-dc62b62.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| sphinx                     | 1.75 sec                                                                                                               | 28.8 ms: 60.73x faster                                                                                                     |
| bench_thread_pool          | 3.59 ms                                                                                                                | 1.15 ms: 3.12x faster                                                                                                      |
| python_startup             | 31.2 ms                                                                                                                | 16.4 ms: 1.91x faster                                                                                                      |
| python_startup_no_site     | 17.7 ms                                                                                                                | 9.54 ms: 1.86x faster                                                                                                      |
| create_gc_cycles           | 13.5 ms                                                                                                                | 7.72 ms: 1.75x faster                                                                                                      |
| pylint                     | 633 ms                                                                                                                 | 433 ms: 1.46x faster                                                                                                       |
| xml_etree_iterparse        | 244 ms                                                                                                                 | 179 ms: 1.36x faster                                                                                                       |
| gc_traversal               | 17.9 ms                                                                                                                | 13.2 ms: 1.35x faster                                                                                                      |
| sympy_sum                  | 264 ms                                                                                                                 | 203 ms: 1.30x faster                                                                                                       |
| xml_etree_parse            | 287 ms                                                                                                                 | 223 ms: 1.29x faster                                                                                                       |
| bpe_tokeniser              | 8.81 sec                                                                                                               | 6.83 sec: 1.29x faster                                                                                                     |
| dulwich_log                | 112 ms                                                                                                                 | 86.8 ms: 1.29x faster                                                                                                      |
| float                      | 132 ms                                                                                                                 | 104 ms: 1.27x faster                                                                                                       |
| xml_etree_generate         | 156 ms                                                                                                                 | 124 ms: 1.26x faster                                                                                                       |
| unpickle_pure_python       | 354 us                                                                                                                 | 286 us: 1.24x faster                                                                                                       |
| xml_etree_process          | 112 ms                                                                                                                 | 92.5 ms: 1.21x faster                                                                                                      |
| mako                       | 18.8 ms                                                                                                                | 15.5 ms: 1.21x faster                                                                                                      |
| docutils                   | 5.71 sec                                                                                                               | 4.81 sec: 1.19x faster                                                                                                     |
| sympy_integrate            | 31.9 ms                                                                                                                | 27.1 ms: 1.18x faster                                                                                                      |
| sympy_str                  | 468 ms                                                                                                                 | 399 ms: 1.17x faster                                                                                                       |
| sqlglot_v2_parse           | 2.16 ms                                                                                                                | 1.85 ms: 1.17x faster                                                                                                      |
| sqlglot_v2_transpile       | 2.69 ms                                                                                                                | 2.33 ms: 1.15x faster                                                                                                      |
| logging_silent             | 157 ns                                                                                                                 | 136 ns: 1.15x faster                                                                                                       |
| pycparser                  | 2.16 sec                                                                                                               | 1.88 sec: 1.14x faster                                                                                                     |
| json                       | 7.39 ms                                                                                                                | 6.57 ms: 1.13x faster                                                                                                      |
| logging_simple             | 9.00 us                                                                                                                | 8.02 us: 1.12x faster                                                                                                      |
| telco                      | 214 ms                                                                                                                 | 192 ms: 1.11x faster                                                                                                       |
| logging_format             | 9.93 us                                                                                                                | 8.96 us: 1.11x faster                                                                                                      |
| pyflate                    | 762 ms                                                                                                                 | 695 ms: 1.10x faster                                                                                                       |
| sympy_expand               | 755 ms                                                                                                                 | 692 ms: 1.09x faster                                                                                                       |
| scimark_fft                | 487 ms                                                                                                                 | 447 ms: 1.09x faster                                                                                                       |
| regex_v8                   | 38.4 ms                                                                                                                | 35.5 ms: 1.08x faster                                                                                                      |
| json_dumps                 | 14.9 ms                                                                                                                | 13.7 ms: 1.08x faster                                                                                                      |
| json_loads                 | 40.9 us                                                                                                                | 37.9 us: 1.08x faster                                                                                                      |
| sqlite_synth               | 4.76 us                                                                                                                | 4.42 us: 1.08x faster                                                                                                      |
| deltablue                  | 5.30 ms                                                                                                                | 4.94 ms: 1.07x faster                                                                                                      |
| sqlglot_v2_optimize        | 84.4 ms                                                                                                                | 78.7 ms: 1.07x faster                                                                                                      |
| thrift                     | 1.24 ms                                                                                                                | 1.17 ms: 1.06x faster                                                                                                      |
| unpickle                   | 23.0 us                                                                                                                | 21.8 us: 1.06x faster                                                                                                      |
| regex_dna                  | 278 ms                                                                                                                 | 264 ms: 1.05x faster                                                                                                       |
| tomli_loads                | 3.21 sec                                                                                                               | 3.06 sec: 1.05x faster                                                                                                     |
| sqlglot_v2_normalize       | 171 ms                                                                                                                 | 164 ms: 1.04x faster                                                                                                       |
| deepcopy_memo              | 40.9 us                                                                                                                | 39.3 us: 1.04x faster                                                                                                      |
| async_tree_none_tg         | 454 ms                                                                                                                 | 440 ms: 1.03x faster                                                                                                       |
| async_tree_cpu_io_mixed_tg | 850 ms                                                                                                                 | 828 ms: 1.03x faster                                                                                                       |
| regex_effbot               | 4.66 ms                                                                                                                | 4.54 ms: 1.03x faster                                                                                                      |
| unpickle_list              | 8.28 us                                                                                                                | 8.10 us: 1.02x faster                                                                                                      |
| spectral_norm              | 150 ms                                                                                                                 | 147 ms: 1.02x faster                                                                                                       |
| coverage                   | 121 ms                                                                                                                 | 119 ms: 1.02x faster                                                                                                       |
| scimark_sparse_mat_mult    | 7.79 ms                                                                                                                | 7.68 ms: 1.02x faster                                                                                                      |
| scimark_lu                 | 173 ms                                                                                                                 | 171 ms: 1.01x faster                                                                                                       |
| asyncio_websockets         | 830 ms                                                                                                                 | 818 ms: 1.01x faster                                                                                                       |
| generators                 | 46.9 ms                                                                                                                | 46.2 ms: 1.01x faster                                                                                                      |
| pickle_list                | 6.88 us                                                                                                                | 6.81 us: 1.01x faster                                                                                                      |
| pickle_dict                | 47.1 us                                                                                                                | 47.0 us: 1.00x faster                                                                                                      |
| coroutines                 | 36.8 ms                                                                                                                | 36.9 ms: 1.00x slower                                                                                                      |
| scimark_sor                | 170 ms                                                                                                                 | 171 ms: 1.01x slower                                                                                                       |
| pidigits                   | 325 ms                                                                                                                 | 328 ms: 1.01x slower                                                                                                       |
| asyncio_tcp_ssl            | 2.83 sec                                                                                                               | 2.86 sec: 1.01x slower                                                                                                     |
| deepcopy_reduce            | 4.17 us                                                                                                                | 4.25 us: 1.02x slower                                                                                                      |
| 2to3                       | 375 ms                                                                                                                 | 383 ms: 1.02x slower                                                                                                       |
| typing_runtime_protocols   | 237 us                                                                                                                 | 242 us: 1.02x slower                                                                                                       |
| subparsers                 | 58.7 ms                                                                                                                | 60.0 ms: 1.02x slower                                                                                                      |
| richards_super             | 72.9 ms                                                                                                                | 74.6 ms: 1.02x slower                                                                                                      |
| async_tree_none            | 443 ms                                                                                                                 | 454 ms: 1.02x slower                                                                                                       |
| crypto_pyaes               | 107 ms                                                                                                                 | 110 ms: 1.03x slower                                                                                                       |
| pathlib                    | 21.4 ms                                                                                                                | 22.0 ms: 1.03x slower                                                                                                      |
| nbody                      | 148 ms                                                                                                                 | 154 ms: 1.04x slower                                                                                                       |
| richards                   | 64.5 ms                                                                                                                | 67.3 ms: 1.04x slower                                                                                                      |
| scimark_monte_carlo        | 95.9 ms                                                                                                                | 100 ms: 1.05x slower                                                                                                       |
| raytrace                   | 411 ms                                                                                                                 | 433 ms: 1.05x slower                                                                                                       |
| fannkuch                   | 583 ms                                                                                                                 | 616 ms: 1.06x slower                                                                                                       |
| async_generators           | 575 ms                                                                                                                 | 614 ms: 1.07x slower                                                                                                       |
| meteor_contest             | 133 ms                                                                                                                 | 144 ms: 1.08x slower                                                                                                       |
| chaos                      | 89.5 ms                                                                                                                | 99.7 ms: 1.11x slower                                                                                                      |
| genshi_text                | 36.3 ms                                                                                                                | 40.5 ms: 1.12x slower                                                                                                      |
| many_optionals             | 1.25 ms                                                                                                                | 1.41 ms: 1.13x slower                                                                                                      |
| html5lib                   | 91.0 ms                                                                                                                | 105 ms: 1.15x slower                                                                                                       |
| mdp                        | 2.30 sec                                                                                                               | 2.68 sec: 1.16x slower                                                                                                     |
| deepcopy                   | 410 us                                                                                                                 | 486 us: 1.19x slower                                                                                                       |
| comprehensions             | 24.6 us                                                                                                                | 29.6 us: 1.20x slower                                                                                                      |
| nqueens                    | 119 ms                                                                                                                 | 147 ms: 1.24x slower                                                                                                       |
| hexiom                     | 9.13 ms                                                                                                                | 11.4 ms: 1.25x slower                                                                                                      |
| pprint_pformat             | 2.19 sec                                                                                                               | 2.78 sec: 1.27x slower                                                                                                     |
| pprint_safe_repr           | 1.04 sec                                                                                                               | 1.35 sec: 1.30x slower                                                                                                     |
| go                         | 165 ms                                                                                                                 | 230 ms: 1.39x slower                                                                                                       |
| unpack_sequence            | 68.0 ns                                                                                                                | 102 ns: 1.49x slower                                                                                                       |
| genshi_xml                 | 77.7 ms                                                                                                                | 120 ms: 1.54x slower                                                                                                       |
| bench_mp_pool              | 85.7 ms                                                                                                                | 276 ms: 3.22x slower                                                                                                       |
| Geometric mean             | (ref)                                                                                                                  | 1.08x faster                                                                                                               |

Benchmark hidden because not significant (10): pickle_pure_python, pickle, async_tree_cpu_io_mixed, async_tree_memoization_tg, regex_compile, django_template, asyncio_tcp, async_tree_io_tg, async_tree_memoization, async_tree_io

- Geometric mean (including insignificant results): 1.108x faster

# HPT report

- Reliability score: 89.63% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x