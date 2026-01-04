# Results vs. base

- fork: python
- ref: e5ad7b7694c47555e3ea
- machine: linux-aarch64
- commit hash: e5ad7b7
- commit date: 2026-01-01
- overall geometric mean: 1.029x faster
- HPT reliability: 97.56%
- HPT 99th percentile: 1.00x faster
- Memory change: 1.03x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 428 ms                                                                                                                 | 423 ms: 1.01x faster                                                                                                       |
| chameleon      | 21.0 ms                                                                                                                | 20.3 ms: 1.04x faster                                                                                                      |
| docutils       | 4.27 sec                                                                                                               | 4.68 sec: 1.10x slower                                                                                                     |
| html5lib       | 78.1 ms                                                                                                                | 87.6 ms: 1.12x slower                                                                                                      |
| sphinx         | 1.52 sec                                                                                                               | 1.58 sec: 1.04x slower                                                                                                     |
| tornado_http   | 168 ms                                                                                                                 | 170 ms: 1.01x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_io    | 1.33 sec                                                                                                               | 1.22 sec: 1.08x faster                                                                                                     |
| async_generators | 573 ms                                                                                                                 | 599 ms: 1.05x slower                                                                                                       |
| Geometric mean   | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (11): async_tree_none, asyncio_websockets, async_tree_cpu_io_mixed, coroutines, asyncio_tcp_ssl, async_tree_io_tg, asyncio_tcp, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_none_tg, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| nbody          | 160 ms                                                                                                                 | 131 ms: 1.22x faster                                                                                                       |
| float          | 131 ms                                                                                                                 | 114 ms: 1.15x faster                                                                                                       |
| pidigits       | 330 ms                                                                                                                 | 328 ms: 1.01x faster                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.12x faster                                                                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 297 ms                                                                                                                 | 284 ms: 1.04x faster                                                                                                       |
| regex_v8       | 37.4 ms                                                                                                                | 36.1 ms: 1.03x faster                                                                                                      |
| regex_compile  | 153 ms                                                                                                                 | 149 ms: 1.03x faster                                                                                                       |
| regex_effbot   | 4.60 ms                                                                                                                | 4.55 ms: 1.01x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.03x faster                                                                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 333 us                                                                                                                 | 251 us: 1.33x faster                                                                                                       |
| pickle_pure_python   | 475 us                                                                                                                 | 383 us: 1.24x faster                                                                                                       |
| tomli_loads          | 3.40 sec                                                                                                               | 3.11 sec: 1.09x faster                                                                                                     |
| xml_etree_process    | 102 ms                                                                                                                 | 95.9 ms: 1.07x faster                                                                                                      |
| xml_etree_generate   | 134 ms                                                                                                                 | 126 ms: 1.07x faster                                                                                                       |
| json_dumps           | 14.1 ms                                                                                                                | 13.2 ms: 1.07x faster                                                                                                      |
| pickle_list          | 6.93 us                                                                                                                | 6.68 us: 1.04x faster                                                                                                      |
| pickle_dict          | 48.2 us                                                                                                                | 46.7 us: 1.03x faster                                                                                                      |
| unpickle_list        | 8.47 us                                                                                                                | 8.28 us: 1.02x faster                                                                                                      |
| xml_etree_parse      | 250 ms                                                                                                                 | 245 ms: 1.02x faster                                                                                                       |
| json_loads           | 39.0 us                                                                                                                | 38.3 us: 1.02x faster                                                                                                      |
| pickle               | 18.7 us                                                                                                                | 18.4 us: 1.01x faster                                                                                                      |
| xml_etree_iterparse  | 202 ms                                                                                                                 | 200 ms: 1.01x faster                                                                                                       |
| Geometric mean       | (ref)                                                                                                                  | 1.07x faster                                                                                                               |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark      | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup | 17.8 ms                                                                                                                | 17.6 ms: 1.01x faster                                                                                                      |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 20.4 ms                                                                                                                | 17.7 ms: 1.16x faster                                                                                                      |
| django_template | 51.4 ms                                                                                                                | 52.0 ms: 1.01x slower                                                                                                      |
| genshi_text     | 33.8 ms                                                                                                                | 35.9 ms: 1.06x slower                                                                                                      |
| genshi_xml      | 77.8 ms                                                                                                                | 96.8 ms: 1.24x slower                                                                                                      |
| Geometric mean  | (ref)                                                                                                                  | 1.04x slower                                                                                                               |

All benchmarks:
===============

| Benchmark             | results/bm-20260101-3.15.0a3+-e5ad7b7/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json | results/bm-20260101-3.15.0a3+-e5ad7b7-JIT/bm-20260101-blueberry-aarch64-python-e5ad7b7694c47555e3ea-3.15.0a3+-e5ad7b7.json |
|-----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| richards              | 64.7 ms                                                                                                                | 38.6 ms: 1.68x faster                                                                                                      |
| richards_super        | 72.7 ms                                                                                                                | 45.5 ms: 1.60x faster                                                                                                      |
| logging_silent        | 165 ns                                                                                                                 | 119 ns: 1.38x faster                                                                                                       |
| unpickle_pure_python  | 333 us                                                                                                                 | 251 us: 1.33x faster                                                                                                       |
| pickle_pure_python    | 475 us                                                                                                                 | 383 us: 1.24x faster                                                                                                       |
| nbody                 | 160 ms                                                                                                                 | 131 ms: 1.22x faster                                                                                                       |
| deltablue             | 5.10 ms                                                                                                                | 4.28 ms: 1.19x faster                                                                                                      |
| deepcopy_memo         | 42.2 us                                                                                                                | 35.9 us: 1.18x faster                                                                                                      |
| scimark_monte_carlo   | 101 ms                                                                                                                 | 86.6 ms: 1.16x faster                                                                                                      |
| mako                  | 20.4 ms                                                                                                                | 17.7 ms: 1.16x faster                                                                                                      |
| float                 | 131 ms                                                                                                                 | 114 ms: 1.15x faster                                                                                                       |
| pyflate               | 752 ms                                                                                                                 | 665 ms: 1.13x faster                                                                                                       |
| scimark_fft           | 492 ms                                                                                                                 | 435 ms: 1.13x faster                                                                                                       |
| fannkuch              | 610 ms                                                                                                                 | 545 ms: 1.12x faster                                                                                                       |
| scimark_lu            | 170 ms                                                                                                                 | 152 ms: 1.12x faster                                                                                                       |
| scimark_sor           | 173 ms                                                                                                                 | 155 ms: 1.12x faster                                                                                                       |
| spectral_norm         | 154 ms                                                                                                                 | 139 ms: 1.11x faster                                                                                                       |
| tomli_loads           | 3.40 sec                                                                                                               | 3.11 sec: 1.09x faster                                                                                                     |
| bpe_tokeniser         | 7.42 sec                                                                                                               | 6.83 sec: 1.09x faster                                                                                                     |
| async_tree_io         | 1.33 sec                                                                                                               | 1.22 sec: 1.08x faster                                                                                                     |
| deepcopy_reduce       | 4.35 us                                                                                                                | 4.06 us: 1.07x faster                                                                                                      |
| xml_etree_process     | 102 ms                                                                                                                 | 95.9 ms: 1.07x faster                                                                                                      |
| xml_etree_generate    | 134 ms                                                                                                                 | 126 ms: 1.07x faster                                                                                                       |
| json_dumps            | 14.1 ms                                                                                                                | 13.2 ms: 1.07x faster                                                                                                      |
| go                    | 161 ms                                                                                                                 | 151 ms: 1.06x faster                                                                                                       |
| json                  | 7.00 ms                                                                                                                | 6.65 ms: 1.05x faster                                                                                                      |
| crypto_pyaes          | 106 ms                                                                                                                 | 101 ms: 1.05x faster                                                                                                       |
| sqlglot_v2_parse      | 1.71 ms                                                                                                                | 1.64 ms: 1.05x faster                                                                                                      |
| pprint_safe_repr      | 1.09 sec                                                                                                               | 1.04 sec: 1.05x faster                                                                                                     |
| regex_dna             | 297 ms                                                                                                                 | 284 ms: 1.04x faster                                                                                                       |
| pickle_list           | 6.93 us                                                                                                                | 6.68 us: 1.04x faster                                                                                                      |
| chameleon             | 21.0 ms                                                                                                                | 20.3 ms: 1.04x faster                                                                                                      |
| sqlite_synth          | 4.67 us                                                                                                                | 4.50 us: 1.04x faster                                                                                                      |
| regex_v8              | 37.4 ms                                                                                                                | 36.1 ms: 1.03x faster                                                                                                      |
| bench_thread_pool     | 1.29 ms                                                                                                                | 1.24 ms: 1.03x faster                                                                                                      |
| pickle_dict           | 48.2 us                                                                                                                | 46.7 us: 1.03x faster                                                                                                      |
| raytrace              | 412 ms                                                                                                                 | 399 ms: 1.03x faster                                                                                                       |
| thrift                | 1.17 ms                                                                                                                | 1.14 ms: 1.03x faster                                                                                                      |
| regex_compile         | 153 ms                                                                                                                 | 149 ms: 1.03x faster                                                                                                       |
| telco                 | 200 ms                                                                                                                 | 195 ms: 1.03x faster                                                                                                       |
| connected_components  | 844 ms                                                                                                                 | 823 ms: 1.03x faster                                                                                                       |
| shortest_path         | 895 ms                                                                                                                 | 874 ms: 1.02x faster                                                                                                       |
| unpickle_list         | 8.47 us                                                                                                                | 8.28 us: 1.02x faster                                                                                                      |
| pprint_pformat        | 2.21 sec                                                                                                               | 2.16 sec: 1.02x faster                                                                                                     |
| meteor_contest        | 139 ms                                                                                                                 | 136 ms: 1.02x faster                                                                                                       |
| xml_etree_parse       | 250 ms                                                                                                                 | 245 ms: 1.02x faster                                                                                                       |
| coverage              | 130 ms                                                                                                                 | 127 ms: 1.02x faster                                                                                                       |
| logging_simple        | 8.38 us                                                                                                                | 8.22 us: 1.02x faster                                                                                                      |
| json_loads            | 39.0 us                                                                                                                | 38.3 us: 1.02x faster                                                                                                      |
| pickle                | 18.7 us                                                                                                                | 18.4 us: 1.01x faster                                                                                                      |
| 2to3                  | 428 ms                                                                                                                 | 423 ms: 1.01x faster                                                                                                       |
| logging_format        | 9.11 us                                                                                                                | 9.01 us: 1.01x faster                                                                                                      |
| regex_effbot          | 4.60 ms                                                                                                                | 4.55 ms: 1.01x faster                                                                                                      |
| python_startup        | 17.8 ms                                                                                                                | 17.6 ms: 1.01x faster                                                                                                      |
| xml_etree_iterparse   | 202 ms                                                                                                                 | 200 ms: 1.01x faster                                                                                                       |
| pidigits              | 330 ms                                                                                                                 | 328 ms: 1.01x faster                                                                                                       |
| k_core                | 4.07 sec                                                                                                               | 4.05 sec: 1.00x faster                                                                                                     |
| tornado_http          | 168 ms                                                                                                                 | 170 ms: 1.01x slower                                                                                                       |
| django_template       | 51.4 ms                                                                                                                | 52.0 ms: 1.01x slower                                                                                                      |
| sqlglot_v2_optimize   | 76.1 ms                                                                                                                | 77.9 ms: 1.02x slower                                                                                                      |
| deepcopy              | 390 us                                                                                                                 | 400 us: 1.03x slower                                                                                                       |
| chaos                 | 86.2 ms                                                                                                                | 88.4 ms: 1.03x slower                                                                                                      |
| pycparser             | 1.53 sec                                                                                                               | 1.58 sec: 1.03x slower                                                                                                     |
| sqlalchemy_imperative | 21.5 ms                                                                                                                | 22.2 ms: 1.03x slower                                                                                                      |
| xdsl_constant_fold    | 57.2 ms                                                                                                                | 59.3 ms: 1.04x slower                                                                                                      |
| sphinx                | 1.52 sec                                                                                                               | 1.58 sec: 1.04x slower                                                                                                     |
| hexiom                | 8.72 ms                                                                                                                | 9.09 ms: 1.04x slower                                                                                                      |
| many_optionals        | 953 us                                                                                                                 | 994 us: 1.04x slower                                                                                                       |
| async_generators      | 573 ms                                                                                                                 | 599 ms: 1.05x slower                                                                                                       |
| sympy_integrate       | 24.0 ms                                                                                                                | 25.1 ms: 1.05x slower                                                                                                      |
| sqlglot_v2_normalize  | 153 ms                                                                                                                 | 161 ms: 1.05x slower                                                                                                       |
| genshi_text           | 33.8 ms                                                                                                                | 35.9 ms: 1.06x slower                                                                                                      |
| pylint                | 415 ms                                                                                                                 | 443 ms: 1.07x slower                                                                                                       |
| sympy_sum             | 179 ms                                                                                                                 | 192 ms: 1.07x slower                                                                                                       |
| sympy_expand          | 591 ms                                                                                                                 | 640 ms: 1.08x slower                                                                                                       |
| sympy_str             | 338 ms                                                                                                                 | 367 ms: 1.09x slower                                                                                                       |
| docutils              | 4.27 sec                                                                                                               | 4.68 sec: 1.10x slower                                                                                                     |
| nqueens               | 120 ms                                                                                                                 | 132 ms: 1.11x slower                                                                                                       |
| mdp                   | 2.43 sec                                                                                                               | 2.70 sec: 1.11x slower                                                                                                     |
| html5lib              | 78.1 ms                                                                                                                | 87.6 ms: 1.12x slower                                                                                                      |
| dulwich_log           | 62.5 ms                                                                                                                | 76.1 ms: 1.22x slower                                                                                                      |
| genshi_xml            | 77.8 ms                                                                                                                | 96.8 ms: 1.24x slower                                                                                                      |
| bench_mp_pool         | 174 ms                                                                                                                 | 235 ms: 1.35x slower                                                                                                       |
| unpack_sequence       | 63.1 ns                                                                                                                | 85.7 ns: 1.36x slower                                                                                                      |
| Geometric mean        | (ref)                                                                                                                  | 1.02x faster                                                                                                               |

Benchmark hidden because not significant (23): sqlglot_v2_transpile, async_tree_none, subparsers, asyncio_websockets, unpickle, pathlib, comprehensions, gc_traversal, async_tree_cpu_io_mixed, generators, typing_runtime_protocols, python_startup_no_site, coroutines, sqlalchemy_declarative, asyncio_tcp_ssl, async_tree_io_tg, scimark_sparse_mat_mult, create_gc_cycles, asyncio_tcp, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_none_tg, async_tree_memoization

- Geometric mean (including insignificant results): 1.029x faster

# HPT report

- Reliability score: 97.56% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x

# Memory
- memory change: 1.03x