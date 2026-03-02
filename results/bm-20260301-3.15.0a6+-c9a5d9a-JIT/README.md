# Results

- fork: python/c9a5d9aae48a9faa553a
- version: 3.15.0a6+
- config: JIT
- commit hash: [c9a5d9a](https://github.com/python/cpython/commit/c9a5d9a)
- commit date: 2026-03-01T11:48:28-08:00
- commit merge base: [41fa2dbc0ef5232efae42630119ba20a2efb3ad7](https://github.com/python/cpython/commit/41fa2dbc0ef5232efae42630119ba20a2efb3ad7)
- ref: c9a5d9aae48a9faa553a

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22569462853)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260301-blueberry-aarch64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a.json)

### vs. base

- Geometric mean: 1.018x faster (HPT: reliability of 83.72%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260301-blueberry-aarch64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base-mem.svg)
- [📄table](bm-20260301-blueberry-aarch64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.md)
- [📈time plot](bm-20260301-blueberry-aarch64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22569462853)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260301-ripley-x86_64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a.json)

### vs. base

- Geometric mean: 1.044x faster (HPT: reliability of 93.45%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260301-ripley-x86_64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base-mem.svg)
- [📄table](bm-20260301-ripley-x86_64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.md)
- [📈time plot](bm-20260301-ripley-x86_64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22569462853)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260301-prometheus-amd64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a.json)

### vs. base

- Geometric mean: 1.180x faster (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260301-prometheus-amd64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.md)
- [📈time plot](bm-20260301-prometheus-amd64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.svg)

