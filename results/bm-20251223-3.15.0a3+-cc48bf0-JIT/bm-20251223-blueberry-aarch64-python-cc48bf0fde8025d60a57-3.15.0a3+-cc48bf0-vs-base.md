# Results vs. base

- fork: python
- ref: cc48bf0fde8025d60a57
- machine: linux-aarch64
- commit hash: cc48bf0
- commit date: 2025-12-23
- overall geometric mean: 1.013x faster
- HPT reliability: 68.78%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 427 ms                                                                                                                 | 424 ms: 1.01x faster                                                                                                       |
| chameleon      | 21.1 ms                                                                                                                | 20.5 ms: 1.03x faster                                                                                                      |
| docutils       | 4.22 sec                                                                                                               | 4.77 sec: 1.13x slower                                                                                                     |
| html5lib       | 77.8 ms                                                                                                                | 88.0 ms: 1.13x slower                                                                                                      |
| sphinx         | 1.49 sec                                                                                                               | 1.59 sec: 1.07x slower                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines                | 39.8 ms                                                                                                                | 38.3 ms: 1.04x faster                                                                                                      |
| async_tree_none_tg        | 538 ms                                                                                                                 | 522 ms: 1.03x faster                                                                                                       |
| asyncio_websockets        | 874 ms                                                                                                                 | 869 ms: 1.01x faster                                                                                                       |
| async_tree_io_tg          | 1.20 sec                                                                                                               | 1.26 sec: 1.05x slower                                                                                                     |
| async_tree_memoization_tg | 625 ms                                                                                                                 | 664 ms: 1.06x slower                                                                                                       |
| async_generators          | 561 ms                                                                                                                 | 613 ms: 1.09x slower                                                                                                       |
| asyncio_tcp               | 1.10 sec                                                                                                               | 1.24 sec: 1.13x slower                                                                                                     |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                               |

Benchmark hidden because not significant (6): asyncio_tcp_ssl, async_tree_none, async_tree_memoization, async_tree_io, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 158 ms                                                                                                                 | 132 ms: 1.20x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 118 ms: 1.10x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.10x faster                                                                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 282 ms                                                                                                                 | 279 ms: 1.01x faster                                                                                                       |
| regex_effbot   | 4.42 ms                                                                                                                | 4.46 ms: 1.01x slower                                                                                                      |
| regex_compile  | 148 ms                                                                                                                 | 151 ms: 1.02x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 331 us                                                                                                                 | 246 us: 1.35x faster                                                                                                       |
| pickle_pure_python   | 457 us                                                                                                                 | 386 us: 1.18x faster                                                                                                       |
| xml_etree_process    | 103 ms                                                                                                                 | 91.7 ms: 1.13x faster                                                                                                      |
| xml_etree_generate   | 135 ms                                                                                                                 | 122 ms: 1.11x faster                                                                                                       |
| json_dumps           | 14.1 ms                                                                                                                | 13.2 ms: 1.07x faster                                                                                                      |
| tomli_loads          | 3.32 sec                                                                                                               | 3.11 sec: 1.07x faster                                                                                                     |
| unpickle_list        | 8.39 us                                                                                                                | 8.13 us: 1.03x faster                                                                                                      |
| xml_etree_iterparse  | 199 ms                                                                                                                 | 193 ms: 1.03x faster                                                                                                       |
| unpickle             | 22.9 us                                                                                                                | 22.5 us: 1.02x faster                                                                                                      |
| pickle_dict          | 46.9 us                                                                                                                | 46.5 us: 1.01x faster                                                                                                      |
| json_loads           | 38.2 us                                                                                                                | 37.9 us: 1.01x faster                                                                                                      |
| xml_etree_parse      | 243 ms                                                                                                                 | 246 ms: 1.01x slower                                                                                                       |
| pickle               | 18.2 us                                                                                                                | 18.5 us: 1.02x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.07x faster                                                                                                               |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.4 ms                                                                                                                | 10.2 ms: 1.01x faster                                                                                                      |
| python_startup         | 17.6 ms                                                                                                                | 17.4 ms: 1.01x faster                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.0 ms                                                                                                                | 17.7 ms: 1.13x faster                                                                                                      |
| django_template | 52.4 ms                                                                                                                | 53.5 ms: 1.02x slower                                                                                                      |
| genshi_text     | 33.0 ms                                                                                                                | 35.4 ms: 1.07x slower                                                                                                      |
| genshi_xml      | 75.9 ms                                                                                                                | 96.1 ms: 1.27x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                 | results/bm-20251223-3.15.0a3+-cc48bf0/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json | results/bm-20251223-3.15.0a3+-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3+-cc48bf0.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                  | 64.1 ms                                                                                                                | 38.6 ms: 1.66x faster                                                                                                      |
| richards_super            | 72.4 ms                                                                                                                | 46.5 ms: 1.56x faster                                                                                                      |
| unpickle_pure_python      | 331 us                                                                                                                 | 246 us: 1.35x faster                                                                                                       |
| logging_silent            | 160 ns                                                                                                                 | 119 ns: 1.35x faster                                                                                                       |
| nbody                     | 158 ms                                                                                                                 | 132 ms: 1.20x faster                                                                                                       |
| scimark_monte_carlo       | 101 ms                                                                                                                 | 84.7 ms: 1.20x faster                                                                                                      |
| pickle_pure_python        | 457 us                                                                                                                 | 386 us: 1.18x faster                                                                                                       |
| deltablue                 | 5.10 ms                                                                                                                | 4.33 ms: 1.18x faster                                                                                                      |
| spectral_norm             | 153 ms                                                                                                                 | 134 ms: 1.14x faster                                                                                                       |
| scimark_fft               | 486 ms                                                                                                                 | 427 ms: 1.14x faster                                                                                                       |
| deepcopy_memo             | 42.4 us                                                                                                                | 37.4 us: 1.13x faster                                                                                                      |
| scimark_sor               | 173 ms                                                                                                                 | 152 ms: 1.13x faster                                                                                                       |
| mako                      | 20.0 ms                                                                                                                | 17.7 ms: 1.13x faster                                                                                                      |
| xml_etree_process         | 103 ms                                                                                                                 | 91.7 ms: 1.13x faster                                                                                                      |
| xml_etree_generate        | 135 ms                                                                                                                 | 122 ms: 1.11x faster                                                                                                       |
| pyflate                   | 738 ms                                                                                                                 | 667 ms: 1.11x faster                                                                                                       |
| fannkuch                  | 598 ms                                                                                                                 | 541 ms: 1.10x faster                                                                                                       |
| float                     | 131 ms                                                                                                                 | 118 ms: 1.10x faster                                                                                                       |
| bpe_tokeniser             | 7.21 sec                                                                                                               | 6.71 sec: 1.07x faster                                                                                                     |
| sqlite_synth              | 4.65 us                                                                                                                | 4.34 us: 1.07x faster                                                                                                      |
| json_dumps                | 14.1 ms                                                                                                                | 13.2 ms: 1.07x faster                                                                                                      |
| tomli_loads               | 3.32 sec                                                                                                               | 3.11 sec: 1.07x faster                                                                                                     |
| scimark_lu                | 170 ms                                                                                                                 | 160 ms: 1.06x faster                                                                                                       |
| json                      | 6.86 ms                                                                                                                | 6.47 ms: 1.06x faster                                                                                                      |
| coroutines                | 39.8 ms                                                                                                                | 38.3 ms: 1.04x faster                                                                                                      |
| unpickle_list             | 8.39 us                                                                                                                | 8.13 us: 1.03x faster                                                                                                      |
| chameleon                 | 21.1 ms                                                                                                                | 20.5 ms: 1.03x faster                                                                                                      |
| async_tree_none_tg        | 538 ms                                                                                                                 | 522 ms: 1.03x faster                                                                                                       |
| raytrace                  | 397 ms                                                                                                                 | 386 ms: 1.03x faster                                                                                                       |
| xml_etree_iterparse       | 199 ms                                                                                                                 | 193 ms: 1.03x faster                                                                                                       |
| go                        | 160 ms                                                                                                                 | 156 ms: 1.02x faster                                                                                                       |
| telco                     | 195 ms                                                                                                                 | 191 ms: 1.02x faster                                                                                                       |
| unpickle                  | 22.9 us                                                                                                                | 22.5 us: 1.02x faster                                                                                                      |
| scimark_sparse_mat_mult   | 8.03 ms                                                                                                                | 7.89 ms: 1.02x faster                                                                                                      |
| k_core                    | 4.07 sec                                                                                                               | 4.02 sec: 1.01x faster                                                                                                     |
| logging_simple            | 8.05 us                                                                                                                | 7.94 us: 1.01x faster                                                                                                      |
| python_startup_no_site    | 10.4 ms                                                                                                                | 10.2 ms: 1.01x faster                                                                                                      |
| regex_dna                 | 282 ms                                                                                                                 | 279 ms: 1.01x faster                                                                                                       |
| connected_components      | 847 ms                                                                                                                 | 839 ms: 1.01x faster                                                                                                       |
| pickle_dict               | 46.9 us                                                                                                                | 46.5 us: 1.01x faster                                                                                                      |
| crypto_pyaes              | 103 ms                                                                                                                 | 102 ms: 1.01x faster                                                                                                       |
| python_startup            | 17.6 ms                                                                                                                | 17.4 ms: 1.01x faster                                                                                                      |
| meteor_contest            | 136 ms                                                                                                                 | 135 ms: 1.01x faster                                                                                                       |
| 2to3                      | 427 ms                                                                                                                 | 424 ms: 1.01x faster                                                                                                       |
| json_loads                | 38.2 us                                                                                                                | 37.9 us: 1.01x faster                                                                                                      |
| asyncio_websockets        | 874 ms                                                                                                                 | 869 ms: 1.01x faster                                                                                                       |
| shortest_path             | 889 ms                                                                                                                 | 886 ms: 1.00x faster                                                                                                       |
| regex_effbot              | 4.42 ms                                                                                                                | 4.46 ms: 1.01x slower                                                                                                      |
| sqlalchemy_declarative    | 158 ms                                                                                                                 | 159 ms: 1.01x slower                                                                                                       |
| create_gc_cycles          | 8.90 ms                                                                                                                | 8.99 ms: 1.01x slower                                                                                                      |
| xml_etree_parse           | 243 ms                                                                                                                 | 246 ms: 1.01x slower                                                                                                       |
| chaos                     | 84.9 ms                                                                                                                | 86.1 ms: 1.01x slower                                                                                                      |
| generators                | 47.7 ms                                                                                                                | 48.5 ms: 1.02x slower                                                                                                      |
| pprint_safe_repr          | 1.05 sec                                                                                                               | 1.07 sec: 1.02x slower                                                                                                     |
| django_template           | 52.4 ms                                                                                                                | 53.5 ms: 1.02x slower                                                                                                      |
| regex_compile             | 148 ms                                                                                                                 | 151 ms: 1.02x slower                                                                                                       |
| pickle                    | 18.2 us                                                                                                                | 18.5 us: 1.02x slower                                                                                                      |
| pprint_pformat            | 2.15 sec                                                                                                               | 2.20 sec: 1.03x slower                                                                                                     |
| sqlglot_v2_normalize      | 154 ms                                                                                                                 | 159 ms: 1.03x slower                                                                                                       |
| sqlglot_v2_optimize       | 74.5 ms                                                                                                                | 77.2 ms: 1.04x slower                                                                                                      |
| coverage                  | 125 ms                                                                                                                 | 130 ms: 1.04x slower                                                                                                       |
| comprehensions            | 25.0 us                                                                                                                | 26.2 us: 1.05x slower                                                                                                      |
| xdsl_constant_fold        | 56.0 ms                                                                                                                | 58.8 ms: 1.05x slower                                                                                                      |
| async_tree_io_tg          | 1.20 sec                                                                                                               | 1.26 sec: 1.05x slower                                                                                                     |
| sqlalchemy_imperative     | 20.6 ms                                                                                                                | 21.8 ms: 1.06x slower                                                                                                      |
| pycparser                 | 1.49 sec                                                                                                               | 1.57 sec: 1.06x slower                                                                                                     |
| deepcopy                  | 380 us                                                                                                                 | 403 us: 1.06x slower                                                                                                       |
| async_tree_memoization_tg | 625 ms                                                                                                                 | 664 ms: 1.06x slower                                                                                                       |
| typing_runtime_protocols  | 231 us                                                                                                                 | 246 us: 1.07x slower                                                                                                       |
| sphinx                    | 1.49 sec                                                                                                               | 1.59 sec: 1.07x slower                                                                                                     |
| genshi_text               | 33.0 ms                                                                                                                | 35.4 ms: 1.07x slower                                                                                                      |
| sympy_integrate           | 23.3 ms                                                                                                                | 25.1 ms: 1.08x slower                                                                                                      |
| pylint                    | 411 ms                                                                                                                 | 447 ms: 1.09x slower                                                                                                       |
| many_optionals            | 923 us                                                                                                                 | 1.01 ms: 1.09x slower                                                                                                      |
| async_generators          | 561 ms                                                                                                                 | 613 ms: 1.09x slower                                                                                                       |
| hexiom                    | 8.58 ms                                                                                                                | 9.40 ms: 1.09x slower                                                                                                      |
| sympy_sum                 | 173 ms                                                                                                                 | 190 ms: 1.10x slower                                                                                                       |
| sympy_expand              | 569 ms                                                                                                                 | 638 ms: 1.12x slower                                                                                                       |
| sympy_str                 | 327 ms                                                                                                                 | 368 ms: 1.12x slower                                                                                                       |
| asyncio_tcp               | 1.10 sec                                                                                                               | 1.24 sec: 1.13x slower                                                                                                     |
| html5lib                  | 77.8 ms                                                                                                                | 88.0 ms: 1.13x slower                                                                                                      |
| docutils                  | 4.22 sec                                                                                                               | 4.77 sec: 1.13x slower                                                                                                     |
| mdp                       | 2.42 sec                                                                                                               | 2.76 sec: 1.14x slower                                                                                                     |
| nqueens                   | 119 ms                                                                                                                 | 139 ms: 1.17x slower                                                                                                       |
| dulwich_log               | 61.8 ms                                                                                                                | 77.8 ms: 1.26x slower                                                                                                      |
| genshi_xml                | 75.9 ms                                                                                                                | 96.1 ms: 1.27x slower                                                                                                      |
| unpack_sequence           | 63.8 ns                                                                                                                | 86.3 ns: 1.35x slower                                                                                                      |
| bench_mp_pool             | 142 ms                                                                                                                 | 259 ms: 1.83x slower                                                                                                       |
| Geometric mean            | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (19): subparsers, asyncio_tcp_ssl, async_tree_none, thrift, async_tree_memoization, regex_v8, sqlglot_v2_parse, pathlib, pidigits, pickle_list, async_tree_io, gc_traversal, logging_format, bench_thread_pool, tornado_http, deepcopy_reduce, async_tree_cpu_io_mixed, sqlglot_v2_transpile, async_tree_cpu_io_mixed_tg

- Geometric mean (including insignificant results): 1.013x faster

# HPT report

- Reliability score: 68.78% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x