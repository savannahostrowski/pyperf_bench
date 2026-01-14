# Results vs. base

- fork: python
- ref: 1857a40807daeae3a1bf
- machine: linux-aarch64
- commit hash: 1857a40
- commit date: 2026-01-14
- overall geometric mean: 1.023x faster
- HPT reliability: 92.40%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 432 ms                                                                                                                 | 429 ms: 1.01x faster                                                                                                       |
| docutils       | 4.18 sec                                                                                                               | 4.62 sec: 1.11x slower                                                                                                     |
| html5lib       | 76.5 ms                                                                                                                | 81.0 ms: 1.06x slower                                                                                                      |
| sphinx         | 1.47 sec                                                                                                               | 1.55 sec: 1.05x slower                                                                                                     |
| tornado_http   | 161 ms                                                                                                                 | 163 ms: 1.02x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| coroutines       | 37.3 ms                                                                                                                | 37.0 ms: 1.01x faster                                                                                                      |
| asyncio_tcp_ssl  | 4.18 sec                                                                                                               | 4.21 sec: 1.01x slower                                                                                                     |
| async_generators | 584 ms                                                                                                                 | 617 ms: 1.06x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (10): async_tree_none, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, asyncio_tcp, asyncio_websockets, async_tree_io, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 159 ms                                                                                                                 | 130 ms: 1.22x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 115 ms: 1.14x faster                                                                                                       |
| pidigits       | 329 ms                                                                                                                 | 325 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 143 ms                                                                                                                 | 138 ms: 1.04x faster                                                                                                       |
| regex_v8       | 35.4 ms                                                                                                                | 34.2 ms: 1.03x faster                                                                                                      |
| regex_effbot   | 4.38 ms                                                                                                                | 4.36 ms: 1.00x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 319 us                                                                                                                 | 244 us: 1.31x faster                                                                                                       |
| pickle_pure_python   | 444 us                                                                                                                 | 383 us: 1.16x faster                                                                                                       |
| tomli_loads          | 2.80 sec                                                                                                               | 2.58 sec: 1.09x faster                                                                                                     |
| json_dumps           | 13.9 ms                                                                                                                | 12.9 ms: 1.08x faster                                                                                                      |
| xml_etree_process    | 98.3 ms                                                                                                                | 92.3 ms: 1.06x faster                                                                                                      |
| xml_etree_generate   | 129 ms                                                                                                                 | 122 ms: 1.06x faster                                                                                                       |
| xml_etree_parse      | 250 ms                                                                                                                 | 238 ms: 1.05x faster                                                                                                       |
| xml_etree_iterparse  | 201 ms                                                                                                                 | 193 ms: 1.04x faster                                                                                                       |
| unpickle             | 22.5 us                                                                                                                | 22.1 us: 1.02x faster                                                                                                      |
| json_loads           | 37.7 us                                                                                                                | 37.8 us: 1.00x slower                                                                                                      |
| unpickle_list        | 7.96 us                                                                                                                | 8.09 us: 1.02x slower                                                                                                      |
| pickle               | 18.3 us                                                                                                                | 18.7 us: 1.02x slower                                                                                                      |
| Geometric mean       | (ref)                                                                                                                  | 1.06x faster                                                                                                               |

Benchmark hidden because not significant (2): pickle_dict, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup | 17.6 ms                                                                                                                | 17.6 ms: 1.00x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.0 ms                                                                                                                | 17.5 ms: 1.14x faster                                                                                                      |
| django_template | 49.0 ms                                                                                                                | 51.6 ms: 1.05x slower                                                                                                      |
| genshi_text     | 32.5 ms                                                                                                                | 36.2 ms: 1.11x slower                                                                                                      |
| genshi_xml      | 75.3 ms                                                                                                                | 93.2 ms: 1.24x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.06x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20260114-3.15.0a4+-1857a40/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json | results/bm-20260114-3.15.0a4+-1857a40-JIT/bm-20260114-blueberry-aarch64-python-1857a40807daeae3a1bf-3.15.0a4+-1857a40.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards                 | 62.9 ms                                                                                                                | 37.0 ms: 1.70x faster                                                                                                      |
| richards_super           | 70.6 ms                                                                                                                | 43.5 ms: 1.62x faster                                                                                                      |
| scimark_lu               | 165 ms                                                                                                                 | 119 ms: 1.38x faster                                                                                                       |
| logging_silent           | 158 ns                                                                                                                 | 120 ns: 1.33x faster                                                                                                       |
| unpickle_pure_python     | 319 us                                                                                                                 | 244 us: 1.31x faster                                                                                                       |
| scimark_sor              | 169 ms                                                                                                                 | 132 ms: 1.28x faster                                                                                                       |
| scimark_monte_carlo      | 99.0 ms                                                                                                                | 80.1 ms: 1.24x faster                                                                                                      |
| nbody                    | 159 ms                                                                                                                 | 130 ms: 1.22x faster                                                                                                       |
| deltablue                | 4.91 ms                                                                                                                | 4.19 ms: 1.17x faster                                                                                                      |
| deepcopy_memo            | 40.8 us                                                                                                                | 35.0 us: 1.17x faster                                                                                                      |
| pickle_pure_python       | 444 us                                                                                                                 | 383 us: 1.16x faster                                                                                                       |
| float                    | 131 ms                                                                                                                 | 115 ms: 1.14x faster                                                                                                       |
| mako                     | 20.0 ms                                                                                                                | 17.5 ms: 1.14x faster                                                                                                      |
| scimark_fft              | 476 ms                                                                                                                 | 418 ms: 1.14x faster                                                                                                       |
| spectral_norm            | 150 ms                                                                                                                 | 132 ms: 1.13x faster                                                                                                       |
| pyflate                  | 736 ms                                                                                                                 | 650 ms: 1.13x faster                                                                                                       |
| fannkuch                 | 577 ms                                                                                                                 | 530 ms: 1.09x faster                                                                                                       |
| tomli_loads              | 2.80 sec                                                                                                               | 2.58 sec: 1.09x faster                                                                                                     |
| json_dumps               | 13.9 ms                                                                                                                | 12.9 ms: 1.08x faster                                                                                                      |
| xml_etree_process        | 98.3 ms                                                                                                                | 92.3 ms: 1.06x faster                                                                                                      |
| xml_etree_generate       | 129 ms                                                                                                                 | 122 ms: 1.06x faster                                                                                                       |
| go                       | 155 ms                                                                                                                 | 147 ms: 1.06x faster                                                                                                       |
| xml_etree_parse          | 250 ms                                                                                                                 | 238 ms: 1.05x faster                                                                                                       |
| xml_etree_iterparse      | 201 ms                                                                                                                 | 193 ms: 1.04x faster                                                                                                       |
| meteor_contest           | 136 ms                                                                                                                 | 131 ms: 1.04x faster                                                                                                       |
| crypto_pyaes             | 101 ms                                                                                                                 | 97.1 ms: 1.04x faster                                                                                                      |
| regex_compile            | 143 ms                                                                                                                 | 138 ms: 1.04x faster                                                                                                       |
| coverage                 | 124 ms                                                                                                                 | 120 ms: 1.04x faster                                                                                                       |
| bpe_tokeniser            | 6.84 sec                                                                                                               | 6.60 sec: 1.04x faster                                                                                                     |
| regex_v8                 | 35.4 ms                                                                                                                | 34.2 ms: 1.03x faster                                                                                                      |
| json                     | 6.67 ms                                                                                                                | 6.47 ms: 1.03x faster                                                                                                      |
| connected_components     | 852 ms                                                                                                                 | 827 ms: 1.03x faster                                                                                                       |
| scimark_sparse_mat_mult  | 8.00 ms                                                                                                                | 7.77 ms: 1.03x faster                                                                                                      |
| create_gc_cycles         | 9.20 ms                                                                                                                | 8.99 ms: 1.02x faster                                                                                                      |
| shortest_path            | 898 ms                                                                                                                 | 880 ms: 1.02x faster                                                                                                       |
| unpickle                 | 22.5 us                                                                                                                | 22.1 us: 1.02x faster                                                                                                      |
| pidigits                 | 329 ms                                                                                                                 | 325 ms: 1.01x faster                                                                                                       |
| raytrace                 | 384 ms                                                                                                                 | 381 ms: 1.01x faster                                                                                                       |
| k_core                   | 4.07 sec                                                                                                               | 4.04 sec: 1.01x faster                                                                                                     |
| coroutines               | 37.3 ms                                                                                                                | 37.0 ms: 1.01x faster                                                                                                      |
| 2to3                     | 432 ms                                                                                                                 | 429 ms: 1.01x faster                                                                                                       |
| thrift                   | 1.12 ms                                                                                                                | 1.11 ms: 1.01x faster                                                                                                      |
| regex_effbot             | 4.38 ms                                                                                                                | 4.36 ms: 1.00x faster                                                                                                      |
| python_startup           | 17.6 ms                                                                                                                | 17.6 ms: 1.00x faster                                                                                                      |
| json_loads               | 37.7 us                                                                                                                | 37.8 us: 1.00x slower                                                                                                      |
| generators               | 47.8 ms                                                                                                                | 48.0 ms: 1.00x slower                                                                                                      |
| asyncio_tcp_ssl          | 4.18 sec                                                                                                               | 4.21 sec: 1.01x slower                                                                                                     |
| logging_simple           | 7.93 us                                                                                                                | 7.99 us: 1.01x slower                                                                                                      |
| logging_format           | 8.75 us                                                                                                                | 8.84 us: 1.01x slower                                                                                                      |
| typing_runtime_protocols | 227 us                                                                                                                 | 230 us: 1.01x slower                                                                                                       |
| pprint_safe_repr         | 1.05 sec                                                                                                               | 1.07 sec: 1.02x slower                                                                                                     |
| unpickle_list            | 7.96 us                                                                                                                | 8.09 us: 1.02x slower                                                                                                      |
| tornado_http             | 161 ms                                                                                                                 | 163 ms: 1.02x slower                                                                                                       |
| deepcopy_reduce          | 3.82 us                                                                                                                | 3.88 us: 1.02x slower                                                                                                      |
| bench_thread_pool        | 1.15 ms                                                                                                                | 1.17 ms: 1.02x slower                                                                                                      |
| pprint_pformat           | 2.14 sec                                                                                                               | 2.18 sec: 1.02x slower                                                                                                     |
| pickle                   | 18.3 us                                                                                                                | 18.7 us: 1.02x slower                                                                                                      |
| comprehensions           | 24.4 us                                                                                                                | 24.9 us: 1.02x slower                                                                                                      |
| pycparser                | 1.48 sec                                                                                                               | 1.52 sec: 1.02x slower                                                                                                     |
| sqlalchemy_declarative   | 156 ms                                                                                                                 | 160 ms: 1.03x slower                                                                                                       |
| xdsl_constant_fold       | 56.4 ms                                                                                                                | 58.6 ms: 1.04x slower                                                                                                      |
| sqlalchemy_imperative    | 20.5 ms                                                                                                                | 21.4 ms: 1.04x slower                                                                                                      |
| sqlglot_v2_normalize     | 146 ms                                                                                                                 | 153 ms: 1.04x slower                                                                                                       |
| chaos                    | 81.2 ms                                                                                                                | 84.9 ms: 1.05x slower                                                                                                      |
| sqlglot_v2_parse         | 1.66 ms                                                                                                                | 1.75 ms: 1.05x slower                                                                                                      |
| sphinx                   | 1.47 sec                                                                                                               | 1.55 sec: 1.05x slower                                                                                                     |
| django_template          | 49.0 ms                                                                                                                | 51.6 ms: 1.05x slower                                                                                                      |
| async_generators         | 584 ms                                                                                                                 | 617 ms: 1.06x slower                                                                                                       |
| html5lib                 | 76.5 ms                                                                                                                | 81.0 ms: 1.06x slower                                                                                                      |
| sqlglot_v2_optimize      | 71.5 ms                                                                                                                | 75.9 ms: 1.06x slower                                                                                                      |
| many_optionals           | 938 us                                                                                                                 | 997 us: 1.06x slower                                                                                                       |
| sympy_integrate          | 23.0 ms                                                                                                                | 24.5 ms: 1.06x slower                                                                                                      |
| deepcopy                 | 342 us                                                                                                                 | 365 us: 1.07x slower                                                                                                       |
| hexiom                   | 8.38 ms                                                                                                                | 8.97 ms: 1.07x slower                                                                                                      |
| pylint                   | 411 ms                                                                                                                 | 445 ms: 1.08x slower                                                                                                       |
| docutils                 | 4.18 sec                                                                                                               | 4.62 sec: 1.11x slower                                                                                                     |
| nqueens                  | 118 ms                                                                                                                 | 131 ms: 1.11x slower                                                                                                       |
| dulwich_log              | 62.6 ms                                                                                                                | 69.5 ms: 1.11x slower                                                                                                      |
| genshi_text              | 32.5 ms                                                                                                                | 36.2 ms: 1.11x slower                                                                                                      |
| sympy_sum                | 171 ms                                                                                                                 | 190 ms: 1.11x slower                                                                                                       |
| mdp                      | 2.41 sec                                                                                                               | 2.73 sec: 1.13x slower                                                                                                     |
| sympy_str                | 320 ms                                                                                                                 | 364 ms: 1.14x slower                                                                                                       |
| sympy_expand             | 551 ms                                                                                                                 | 636 ms: 1.15x slower                                                                                                       |
| unpack_sequence          | 67.2 ns                                                                                                                | 83.2 ns: 1.24x slower                                                                                                      |
| genshi_xml               | 75.3 ms                                                                                                                | 93.2 ms: 1.24x slower                                                                                                      |
| Geometric mean           | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (22): bench_mp_pool, async_tree_none, sqlglot_v2_transpile, subparsers, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, asyncio_tcp, telco, pathlib, pickle_dict, regex_dna, python_startup_no_site, asyncio_websockets, gc_traversal, chameleon, pickle_list, async_tree_io, sqlite_synth, async_tree_io_tg

- Geometric mean (including insignificant results): 1.023x faster

# HPT report

- Reliability score: 92.40% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x