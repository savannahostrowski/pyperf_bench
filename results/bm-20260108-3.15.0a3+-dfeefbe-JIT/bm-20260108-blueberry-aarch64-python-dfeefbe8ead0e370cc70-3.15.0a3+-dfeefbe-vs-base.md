# Results vs. base

- fork: python
- ref: dfeefbe8ead0e370cc70
- machine: linux-aarch64
- commit hash: dfeefbe
- commit date: 2026-01-08
- overall geometric mean: 1.031x faster
- HPT reliability: 97.38%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 429 ms                                                                                                                 | 431 ms: 1.01x slower                                                                                                       |
| docutils       | 4.33 sec                                                                                                               | 4.74 sec: 1.09x slower                                                                                                     |
| html5lib       | 80.1 ms                                                                                                                | 88.5 ms: 1.11x slower                                                                                                      |
| sphinx         | 1.52 sec                                                                                                               | 1.56 sec: 1.03x slower                                                                                                     |
| tornado_http   | 172 ms                                                                                                                 | 166 ms: 1.04x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp      | 1.23 sec                                                                                                               | 1.18 sec: 1.04x faster                                                                                                     |
| coroutines       | 40.1 ms                                                                                                                | 41.4 ms: 1.03x slower                                                                                                      |
| async_generators | 595 ms                                                                                                                 | 634 ms: 1.07x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (10): async_tree_cpu_io_mixed, asyncio_tcp_ssl, async_tree_memoization_tg, asyncio_websockets, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_none, async_tree_io_tg, async_tree_io, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 162 ms                                                                                                                 | 135 ms: 1.19x faster                                                                                                       |
| float          | 133 ms                                                                                                                 | 115 ms: 1.15x faster                                                                                                       |
| pidigits       | 338 ms                                                                                                                 | 324 ms: 1.04x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.13x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 38.6 ms                                                                                                                | 35.5 ms: 1.08x faster                                                                                                      |
| regex_dna      | 289 ms                                                                                                                 | 273 ms: 1.06x faster                                                                                                       |
| regex_effbot   | 4.58 ms                                                                                                                | 4.35 ms: 1.05x faster                                                                                                      |
| regex_compile  | 150 ms                                                                                                                 | 148 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x faster                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 339 us                                                                                                                 | 250 us: 1.36x faster                                                                                                       |
| pickle_pure_python   | 478 us                                                                                                                 | 384 us: 1.24x faster                                                                                                       |
| tomli_loads          | 3.03 sec                                                                                                               | 2.66 sec: 1.14x faster                                                                                                     |
| xml_etree_generate   | 138 ms                                                                                                                 | 122 ms: 1.13x faster                                                                                                       |
| json_dumps           | 14.8 ms                                                                                                                | 13.3 ms: 1.11x faster                                                                                                      |
| xml_etree_process    | 104 ms                                                                                                                 | 94.9 ms: 1.10x faster                                                                                                      |
| pickle_list          | 7.17 us                                                                                                                | 6.75 us: 1.06x faster                                                                                                      |
| xml_etree_iterparse  | 205 ms                                                                                                                 | 193 ms: 1.06x faster                                                                                                       |
| xml_etree_parse      | 255 ms                                                                                                                 | 241 ms: 1.06x faster                                                                                                       |
| pickle_dict          | 49.4 us                                                                                                                | 47.2 us: 1.05x faster                                                                                                      |
| unpickle             | 24.0 us                                                                                                                | 23.0 us: 1.04x faster                                                                                                      |
| unpickle_list        | 8.50 us                                                                                                                | 8.30 us: 1.02x faster                                                                                                      |
| json_loads           | 39.4 us                                                                                                                | 38.8 us: 1.01x faster                                                                                                      |
| pickle               | 19.2 us                                                                                                                | 18.9 us: 1.01x faster                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.10x faster                                                                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup | 18.1 ms                                                                                                                | 18.0 ms: 1.01x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.6 ms                                                                                                                | 18.1 ms: 1.14x faster                                                                                                      |
| genshi_text     | 34.3 ms                                                                                                                | 35.4 ms: 1.03x slower                                                                                                      |
| django_template | 52.4 ms                                                                                                                | 54.9 ms: 1.05x slower                                                                                                      |
| genshi_xml      | 79.0 ms                                                                                                                | 96.4 ms: 1.22x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

All benchmarks:
===============

| Benchmark               | results/bm-20260108-3.15.0a3+-dfeefbe/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json | results/bm-20260108-3.15.0a3+-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3+-dfeefbe.json |
|-------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                | 66.5 ms                                                                                                                | 37.0 ms: 1.80x faster                                                                                                      |
| richards_super          | 75.7 ms                                                                                                                | 45.1 ms: 1.68x faster                                                                                                      |
| unpickle_pure_python    | 339 us                                                                                                                 | 250 us: 1.36x faster                                                                                                       |
| logging_silent          | 169 ns                                                                                                                 | 125 ns: 1.35x faster                                                                                                       |
| pickle_pure_python      | 478 us                                                                                                                 | 384 us: 1.24x faster                                                                                                       |
| scimark_monte_carlo     | 103 ms                                                                                                                 | 83.6 ms: 1.24x faster                                                                                                      |
| scimark_sor             | 181 ms                                                                                                                 | 150 ms: 1.21x faster                                                                                                       |
| nbody                   | 162 ms                                                                                                                 | 135 ms: 1.19x faster                                                                                                       |
| scimark_fft             | 503 ms                                                                                                                 | 426 ms: 1.18x faster                                                                                                       |
| scimark_lu              | 177 ms                                                                                                                 | 150 ms: 1.18x faster                                                                                                       |
| deepcopy_memo           | 43.3 us                                                                                                                | 37.0 us: 1.17x faster                                                                                                      |
| deltablue               | 5.13 ms                                                                                                                | 4.40 ms: 1.17x faster                                                                                                      |
| spectral_norm           | 157 ms                                                                                                                 | 136 ms: 1.16x faster                                                                                                       |
| pyflate                 | 756 ms                                                                                                                 | 654 ms: 1.16x faster                                                                                                       |
| float                   | 133 ms                                                                                                                 | 115 ms: 1.15x faster                                                                                                       |
| tomli_loads             | 3.03 sec                                                                                                               | 2.66 sec: 1.14x faster                                                                                                     |
| mako                    | 20.6 ms                                                                                                                | 18.1 ms: 1.14x faster                                                                                                      |
| xml_etree_generate      | 138 ms                                                                                                                 | 122 ms: 1.13x faster                                                                                                       |
| json_dumps              | 14.8 ms                                                                                                                | 13.3 ms: 1.11x faster                                                                                                      |
| fannkuch                | 616 ms                                                                                                                 | 555 ms: 1.11x faster                                                                                                       |
| sqlite_synth            | 4.86 us                                                                                                                | 4.42 us: 1.10x faster                                                                                                      |
| xml_etree_process       | 104 ms                                                                                                                 | 94.9 ms: 1.10x faster                                                                                                      |
| regex_v8                | 38.6 ms                                                                                                                | 35.5 ms: 1.08x faster                                                                                                      |
| sqlglot_v2_parse        | 1.73 ms                                                                                                                | 1.62 ms: 1.07x faster                                                                                                      |
| pprint_safe_repr        | 1.10 sec                                                                                                               | 1.03 sec: 1.07x faster                                                                                                     |
| pprint_pformat          | 2.29 sec                                                                                                               | 2.15 sec: 1.07x faster                                                                                                     |
| pickle_list             | 7.17 us                                                                                                                | 6.75 us: 1.06x faster                                                                                                      |
| scimark_sparse_mat_mult | 8.27 ms                                                                                                                | 7.79 ms: 1.06x faster                                                                                                      |
| go                      | 167 ms                                                                                                                 | 157 ms: 1.06x faster                                                                                                       |
| thrift                  | 1.17 ms                                                                                                                | 1.11 ms: 1.06x faster                                                                                                      |
| xml_etree_iterparse     | 205 ms                                                                                                                 | 193 ms: 1.06x faster                                                                                                       |
| raytrace                | 417 ms                                                                                                                 | 394 ms: 1.06x faster                                                                                                       |
| xml_etree_parse         | 255 ms                                                                                                                 | 241 ms: 1.06x faster                                                                                                       |
| regex_dna               | 289 ms                                                                                                                 | 273 ms: 1.06x faster                                                                                                       |
| sqlglot_v2_transpile    | 2.28 ms                                                                                                                | 2.17 ms: 1.05x faster                                                                                                      |
| regex_effbot            | 4.58 ms                                                                                                                | 4.35 ms: 1.05x faster                                                                                                      |
| pickle_dict             | 49.4 us                                                                                                                | 47.2 us: 1.05x faster                                                                                                      |
| json                    | 6.99 ms                                                                                                                | 6.68 ms: 1.05x faster                                                                                                      |
| meteor_contest          | 141 ms                                                                                                                 | 135 ms: 1.05x faster                                                                                                       |
| asyncio_tcp             | 1.23 sec                                                                                                               | 1.18 sec: 1.04x faster                                                                                                     |
| unpickle                | 24.0 us                                                                                                                | 23.0 us: 1.04x faster                                                                                                      |
| telco                   | 207 ms                                                                                                                 | 198 ms: 1.04x faster                                                                                                       |
| pidigits                | 338 ms                                                                                                                 | 324 ms: 1.04x faster                                                                                                       |
| create_gc_cycles        | 9.37 ms                                                                                                                | 9.01 ms: 1.04x faster                                                                                                      |
| bpe_tokeniser           | 7.34 sec                                                                                                               | 7.06 sec: 1.04x faster                                                                                                     |
| deepcopy_reduce         | 4.17 us                                                                                                                | 4.01 us: 1.04x faster                                                                                                      |
| crypto_pyaes            | 107 ms                                                                                                                 | 103 ms: 1.04x faster                                                                                                       |
| tornado_http            | 172 ms                                                                                                                 | 166 ms: 1.04x faster                                                                                                       |
| sqlalchemy_declarative  | 165 ms                                                                                                                 | 161 ms: 1.03x faster                                                                                                       |
| unpickle_list           | 8.50 us                                                                                                                | 8.30 us: 1.02x faster                                                                                                      |
| coverage                | 132 ms                                                                                                                 | 129 ms: 1.02x faster                                                                                                       |
| connected_components    | 846 ms                                                                                                                 | 827 ms: 1.02x faster                                                                                                       |
| logging_simple          | 8.38 us                                                                                                                | 8.21 us: 1.02x faster                                                                                                      |
| pathlib                 | 22.4 ms                                                                                                                | 22.1 ms: 1.02x faster                                                                                                      |
| json_loads              | 39.4 us                                                                                                                | 38.8 us: 1.01x faster                                                                                                      |
| regex_compile           | 150 ms                                                                                                                 | 148 ms: 1.01x faster                                                                                                       |
| pickle                  | 19.2 us                                                                                                                | 18.9 us: 1.01x faster                                                                                                      |
| logging_format          | 9.21 us                                                                                                                | 9.10 us: 1.01x faster                                                                                                      |
| shortest_path           | 893 ms                                                                                                                 | 882 ms: 1.01x faster                                                                                                       |
| k_core                  | 4.07 sec                                                                                                               | 4.03 sec: 1.01x faster                                                                                                     |
| comprehensions          | 25.6 us                                                                                                                | 25.3 us: 1.01x faster                                                                                                      |
| python_startup          | 18.1 ms                                                                                                                | 18.0 ms: 1.01x faster                                                                                                      |
| gc_traversal            | 14.8 ms                                                                                                                | 14.7 ms: 1.00x faster                                                                                                      |
| 2to3                    | 429 ms                                                                                                                 | 431 ms: 1.01x slower                                                                                                       |
| xdsl_constant_fold      | 58.0 ms                                                                                                                | 59.6 ms: 1.03x slower                                                                                                      |
| sphinx                  | 1.52 sec                                                                                                               | 1.56 sec: 1.03x slower                                                                                                     |
| sqlglot_v2_normalize    | 154 ms                                                                                                                 | 159 ms: 1.03x slower                                                                                                       |
| coroutines              | 40.1 ms                                                                                                                | 41.4 ms: 1.03x slower                                                                                                      |
| genshi_text             | 34.3 ms                                                                                                                | 35.4 ms: 1.03x slower                                                                                                      |
| generators              | 48.9 ms                                                                                                                | 50.8 ms: 1.04x slower                                                                                                      |
| pylint                  | 428 ms                                                                                                                 | 444 ms: 1.04x slower                                                                                                       |
| chaos                   | 87.7 ms                                                                                                                | 92.0 ms: 1.05x slower                                                                                                      |
| django_template         | 52.4 ms                                                                                                                | 54.9 ms: 1.05x slower                                                                                                      |
| deepcopy                | 369 us                                                                                                                 | 389 us: 1.06x slower                                                                                                       |
| sympy_sum               | 181 ms                                                                                                                 | 192 ms: 1.06x slower                                                                                                       |
| async_generators        | 595 ms                                                                                                                 | 634 ms: 1.07x slower                                                                                                       |
| sympy_str               | 342 ms                                                                                                                 | 371 ms: 1.08x slower                                                                                                       |
| mdp                     | 2.51 sec                                                                                                               | 2.72 sec: 1.09x slower                                                                                                     |
| many_optionals          | 927 us                                                                                                                 | 1.01 ms: 1.09x slower                                                                                                      |
| docutils                | 4.33 sec                                                                                                               | 4.74 sec: 1.09x slower                                                                                                     |
| nqueens                 | 120 ms                                                                                                                 | 132 ms: 1.10x slower                                                                                                       |
| hexiom                  | 8.71 ms                                                                                                                | 9.59 ms: 1.10x slower                                                                                                      |
| html5lib                | 80.1 ms                                                                                                                | 88.5 ms: 1.11x slower                                                                                                      |
| sympy_expand            | 593 ms                                                                                                                 | 656 ms: 1.11x slower                                                                                                       |
| dulwich_log             | 64.3 ms                                                                                                                | 73.5 ms: 1.14x slower                                                                                                      |
| bench_mp_pool           | 171 ms                                                                                                                 | 198 ms: 1.16x slower                                                                                                       |
| unpack_sequence         | 65.7 ns                                                                                                                | 77.3 ns: 1.18x slower                                                                                                      |
| genshi_xml              | 79.0 ms                                                                                                                | 96.4 ms: 1.22x slower                                                                                                      |
| bench_thread_pool       | 1.31 ms                                                                                                                | 2.99 ms: 2.28x slower                                                                                                      |
| Geometric mean          | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmark hidden because not significant (18): async_tree_cpu_io_mixed, subparsers, typing_runtime_protocols, chameleon, asyncio_tcp_ssl, async_tree_memoization_tg, python_startup_no_site, sqlglot_v2_optimize, asyncio_websockets, sqlalchemy_imperative, pycparser, sympy_integrate, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_none, async_tree_io_tg, async_tree_io, async_tree_none_tg

- Geometric mean (including insignificant results): 1.031x faster

# HPT report

- Reliability score: 97.38% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x