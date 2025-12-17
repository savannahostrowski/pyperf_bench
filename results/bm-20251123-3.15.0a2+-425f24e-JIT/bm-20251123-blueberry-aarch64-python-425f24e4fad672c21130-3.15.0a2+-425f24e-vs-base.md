# Results vs. base

- fork: python
- ref: 425f24e4fad672c21130
- machine: linux-aarch64
- commit hash: 425f24e
- commit date: 2025-11-23
- overall geometric mean: 1.029x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower
- Memory change: 1.02x

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 375 ms                                                                                                                 | 383 ms: 1.02x slower                                                                                                       |
| html5lib       | 74.5 ms                                                                                                                | 104 ms: 1.39x slower                                                                                                       |
| sphinx         | 1.39 sec                                                                                                               | 29.1 ms: 47.71x faster                                                                                                     |
| Geometric mean | (ref)                                                                                                                  | 3.22x faster                                                                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|--------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg | 460 ms                                                                                                                 | 443 ms: 1.04x faster                                                                                                       |
| coroutines         | 37.0 ms                                                                                                                | 36.6 ms: 1.01x faster                                                                                                      |
| asyncio_websockets | 818 ms                                                                                                                 | 822 ms: 1.00x slower                                                                                                       |
| asyncio_tcp_ssl    | 2.97 sec                                                                                                               | 3.03 sec: 1.02x slower                                                                                                     |
| asyncio_tcp        | 655 ms                                                                                                                 | 680 ms: 1.04x slower                                                                                                       |
| async_tree_none    | 435 ms                                                                                                                 | 452 ms: 1.04x slower                                                                                                       |
| async_generators   | 560 ms                                                                                                                 | 627 ms: 1.12x slower                                                                                                       |
| Geometric mean     | (ref)                                                                                                                  | 1.01x slower                                                                                                               |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_io_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| float          | 109 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| nbody          | 149 ms                                                                                                                 | 155 ms: 1.04x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.00x faster                                                                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 4.45 ms                                                                                                                | 4.43 ms: 1.00x faster                                                                                                      |
| regex_v8       | 35.6 ms                                                                                                                | 35.5 ms: 1.00x faster                                                                                                      |
| regex_compile  | 146 ms                                                                                                                 | 174 ms: 1.20x slower                                                                                                       |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 317 us                                                                                                                 | 288 us: 1.10x faster                                                                                                       |
| json_dumps           | 14.0 ms                                                                                                                | 13.6 ms: 1.03x faster                                                                                                      |
| xml_etree_process    | 94.6 ms                                                                                                                | 92.7 ms: 1.02x faster                                                                                                      |
| xml_etree_parse      | 224 ms                                                                                                                 | 221 ms: 1.02x faster                                                                                                       |
| xml_etree_generate   | 127 ms                                                                                                                 | 125 ms: 1.01x faster                                                                                                       |
| json_loads           | 38.4 us                                                                                                                | 38.0 us: 1.01x faster                                                                                                      |
| pickle_pure_python   | 445 us                                                                                                                 | 441 us: 1.01x faster                                                                                                       |
| xml_etree_iterparse  | 181 ms                                                                                                                 | 180 ms: 1.01x faster                                                                                                       |
| unpickle_list        | 8.01 us                                                                                                                | 8.05 us: 1.00x slower                                                                                                      |
| pickle               | 18.6 us                                                                                                                | 18.6 us: 1.01x slower                                                                                                      |
| pickle_list          | 6.78 us                                                                                                                | 6.83 us: 1.01x slower                                                                                                      |
| pickle_dict          | 46.6 us                                                                                                                | 47.1 us: 1.01x slower                                                                                                      |
| tomli_loads          | 2.86 sec                                                                                                               | 2.96 sec: 1.03x slower                                                                                                     |
| Geometric mean       | (ref)                                                                                                                  | 1.01x faster                                                                                                               |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 9.42 ms                                                                                                                | 9.49 ms: 1.01x slower                                                                                                      |
| Geometric mean         | (ref)                                                                                                                  | 1.00x slower                                                                                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|-----------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| mako            | 16.5 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| django_template | 50.8 ms                                                                                                                | 53.9 ms: 1.06x slower                                                                                                      |
| genshi_text     | 32.5 ms                                                                                                                | 39.5 ms: 1.22x slower                                                                                                      |
| genshi_xml      | 72.0 ms                                                                                                                | 118 ms: 1.64x slower                                                                                                       |
| Geometric mean  | (ref)                                                                                                                  | 1.19x slower                                                                                                               |

All benchmarks:
===============

| Benchmark                | results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json | results/bm-20251123-3.15.0a2+-425f24e-JIT/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| sphinx                   | 1.39 sec                                                                                                               | 29.1 ms: 47.71x faster                                                                                                     |
| logging_silent           | 157 ns                                                                                                                 | 137 ns: 1.15x faster                                                                                                       |
| unpickle_pure_python     | 317 us                                                                                                                 | 288 us: 1.10x faster                                                                                                       |
| mako                     | 16.5 ms                                                                                                                | 15.6 ms: 1.06x faster                                                                                                      |
| float                    | 109 ms                                                                                                                 | 104 ms: 1.05x faster                                                                                                       |
| async_tree_none_tg       | 460 ms                                                                                                                 | 443 ms: 1.04x faster                                                                                                       |
| scimark_fft              | 467 ms                                                                                                                 | 452 ms: 1.03x faster                                                                                                       |
| json                     | 6.84 ms                                                                                                                | 6.63 ms: 1.03x faster                                                                                                      |
| deepcopy_memo            | 40.5 us                                                                                                                | 39.4 us: 1.03x faster                                                                                                      |
| json_dumps               | 14.0 ms                                                                                                                | 13.6 ms: 1.03x faster                                                                                                      |
| xml_etree_process        | 94.6 ms                                                                                                                | 92.7 ms: 1.02x faster                                                                                                      |
| scimark_lu               | 170 ms                                                                                                                 | 167 ms: 1.02x faster                                                                                                       |
| scimark_sor              | 170 ms                                                                                                                 | 167 ms: 1.02x faster                                                                                                       |
| xml_etree_parse          | 224 ms                                                                                                                 | 221 ms: 1.02x faster                                                                                                       |
| xml_etree_generate       | 127 ms                                                                                                                 | 125 ms: 1.01x faster                                                                                                       |
| spectral_norm            | 145 ms                                                                                                                 | 143 ms: 1.01x faster                                                                                                       |
| json_loads               | 38.4 us                                                                                                                | 38.0 us: 1.01x faster                                                                                                      |
| coroutines               | 37.0 ms                                                                                                                | 36.6 ms: 1.01x faster                                                                                                      |
| pickle_pure_python       | 445 us                                                                                                                 | 441 us: 1.01x faster                                                                                                       |
| bpe_tokeniser            | 6.86 sec                                                                                                               | 6.80 sec: 1.01x faster                                                                                                     |
| coverage                 | 120 ms                                                                                                                 | 119 ms: 1.01x faster                                                                                                       |
| xml_etree_iterparse      | 181 ms                                                                                                                 | 180 ms: 1.01x faster                                                                                                       |
| regex_effbot             | 4.45 ms                                                                                                                | 4.43 ms: 1.00x faster                                                                                                      |
| regex_v8                 | 35.6 ms                                                                                                                | 35.5 ms: 1.00x faster                                                                                                      |
| asyncio_websockets       | 818 ms                                                                                                                 | 822 ms: 1.00x slower                                                                                                       |
| unpickle_list            | 8.01 us                                                                                                                | 8.05 us: 1.00x slower                                                                                                      |
| pickle                   | 18.6 us                                                                                                                | 18.6 us: 1.01x slower                                                                                                      |
| pickle_list              | 6.78 us                                                                                                                | 6.83 us: 1.01x slower                                                                                                      |
| python_startup_no_site   | 9.42 ms                                                                                                                | 9.49 ms: 1.01x slower                                                                                                      |
| telco                    | 190 ms                                                                                                                 | 192 ms: 1.01x slower                                                                                                       |
| pickle_dict              | 46.6 us                                                                                                                | 47.1 us: 1.01x slower                                                                                                      |
| 2to3                     | 375 ms                                                                                                                 | 383 ms: 1.02x slower                                                                                                       |
| asyncio_tcp_ssl          | 2.97 sec                                                                                                               | 3.03 sec: 1.02x slower                                                                                                     |
| scimark_monte_carlo      | 97.5 ms                                                                                                                | 100 ms: 1.03x slower                                                                                                       |
| thrift                   | 1.12 ms                                                                                                                | 1.15 ms: 1.03x slower                                                                                                      |
| deltablue                | 4.75 ms                                                                                                                | 4.90 ms: 1.03x slower                                                                                                      |
| pathlib                  | 21.3 ms                                                                                                                | 21.9 ms: 1.03x slower                                                                                                      |
| deepcopy_reduce          | 4.10 us                                                                                                                | 4.22 us: 1.03x slower                                                                                                      |
| generators               | 44.8 ms                                                                                                                | 46.3 ms: 1.03x slower                                                                                                      |
| tomli_loads              | 2.86 sec                                                                                                               | 2.96 sec: 1.03x slower                                                                                                     |
| subparsers               | 58.1 ms                                                                                                                | 60.1 ms: 1.04x slower                                                                                                      |
| asyncio_tcp              | 655 ms                                                                                                                 | 680 ms: 1.04x slower                                                                                                       |
| bench_thread_pool        | 1.11 ms                                                                                                                | 1.15 ms: 1.04x slower                                                                                                      |
| async_tree_none          | 435 ms                                                                                                                 | 452 ms: 1.04x slower                                                                                                       |
| nbody                    | 149 ms                                                                                                                 | 155 ms: 1.04x slower                                                                                                       |
| pyflate                  | 672 ms                                                                                                                 | 701 ms: 1.04x slower                                                                                                       |
| richards_super           | 70.2 ms                                                                                                                | 73.6 ms: 1.05x slower                                                                                                      |
| meteor_contest           | 135 ms                                                                                                                 | 142 ms: 1.05x slower                                                                                                       |
| logging_simple           | 7.71 us                                                                                                                | 8.08 us: 1.05x slower                                                                                                      |
| logging_format           | 8.52 us                                                                                                                | 8.97 us: 1.05x slower                                                                                                      |
| django_template          | 50.8 ms                                                                                                                | 53.9 ms: 1.06x slower                                                                                                      |
| richards                 | 62.2 ms                                                                                                                | 66.5 ms: 1.07x slower                                                                                                      |
| sqlglot_v2_normalize     | 151 ms                                                                                                                 | 162 ms: 1.08x slower                                                                                                       |
| fannkuch                 | 569 ms                                                                                                                 | 613 ms: 1.08x slower                                                                                                       |
| sqlglot_v2_optimize      | 72.1 ms                                                                                                                | 78.1 ms: 1.08x slower                                                                                                      |
| crypto_pyaes             | 101 ms                                                                                                                 | 110 ms: 1.09x slower                                                                                                       |
| typing_runtime_protocols | 222 us                                                                                                                 | 244 us: 1.10x slower                                                                                                       |
| pylint                   | 391 ms                                                                                                                 | 431 ms: 1.10x slower                                                                                                       |
| many_optionals           | 1.25 ms                                                                                                                | 1.40 ms: 1.12x slower                                                                                                      |
| sqlglot_v2_transpile     | 2.09 ms                                                                                                                | 2.34 ms: 1.12x slower                                                                                                      |
| async_generators         | 560 ms                                                                                                                 | 627 ms: 1.12x slower                                                                                                       |
| sqlglot_v2_parse         | 1.63 ms                                                                                                                | 1.85 ms: 1.13x slower                                                                                                      |
| raytrace                 | 381 ms                                                                                                                 | 435 ms: 1.14x slower                                                                                                       |
| sympy_integrate          | 22.9 ms                                                                                                                | 26.5 ms: 1.16x slower                                                                                                      |
| pycparser                | 1.61 sec                                                                                                               | 1.90 sec: 1.18x slower                                                                                                     |
| mdp                      | 2.25 sec                                                                                                               | 2.68 sec: 1.19x slower                                                                                                     |
| regex_compile            | 146 ms                                                                                                                 | 174 ms: 1.20x slower                                                                                                       |
| sympy_sum                | 169 ms                                                                                                                 | 204 ms: 1.21x slower                                                                                                       |
| genshi_text              | 32.5 ms                                                                                                                | 39.5 ms: 1.22x slower                                                                                                      |
| comprehensions           | 23.8 us                                                                                                                | 29.2 us: 1.23x slower                                                                                                      |
| sympy_str                | 319 ms                                                                                                                 | 394 ms: 1.23x slower                                                                                                       |
| sympy_expand             | 554 ms                                                                                                                 | 684 ms: 1.24x slower                                                                                                       |
| pprint_safe_repr         | 1.06 sec                                                                                                               | 1.32 sec: 1.24x slower                                                                                                     |
| chaos                    | 79.9 ms                                                                                                                | 99.9 ms: 1.25x slower                                                                                                      |
| deepcopy                 | 377 us                                                                                                                 | 479 us: 1.27x slower                                                                                                       |
| nqueens                  | 118 ms                                                                                                                 | 151 ms: 1.28x slower                                                                                                       |
| pprint_pformat           | 2.16 sec                                                                                                               | 2.78 sec: 1.29x slower                                                                                                     |
| hexiom                   | 8.30 ms                                                                                                                | 11.4 ms: 1.38x slower                                                                                                      |
| html5lib                 | 74.5 ms                                                                                                                | 104 ms: 1.39x slower                                                                                                       |
| dulwich_log              | 61.0 ms                                                                                                                | 86.4 ms: 1.42x slower                                                                                                      |
| go                       | 155 ms                                                                                                                 | 227 ms: 1.46x slower                                                                                                       |
| unpack_sequence          | 63.9 ns                                                                                                                | 103 ns: 1.61x slower                                                                                                       |
| genshi_xml               | 72.0 ms                                                                                                                | 118 ms: 1.64x slower                                                                                                       |
| bench_mp_pool            | 129 ms                                                                                                                 | 261 ms: 2.03x slower                                                                                                       |
| Geometric mean           | (ref)                                                                                                                  | 1.03x slower                                                                                                               |

Benchmark hidden because not significant (14): async_tree_cpu_io_mixed_tg, scimark_sparse_mat_mult, async_tree_memoization_tg, sqlite_synth, gc_traversal, unpickle, pidigits, python_startup, create_gc_cycles, async_tree_io_tg, regex_dna, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_io
Ignored benchmarks (1) of results/bm-20251123-3.15.0a2+-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2+-425f24e.json: docutils

- Geometric mean (including insignificant results): 1.029x slower

# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x

# Memory
- memory change: 1.02x