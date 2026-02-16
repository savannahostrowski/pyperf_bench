# Results

- fork: python/c91638ca0671b8038831
- version: 3.15.0a6+
- config: JIT
- commit hash: [c91638c](https://github.com/python/cpython/commit/c91638c)
- commit date: 2026-02-15T18:43:07-08:00
- commit merge base: [300de1e98ac236bc887b49c0fbd7398266237b36](https://github.com/python/cpython/commit/300de1e98ac236bc887b49c0fbd7398266237b36)
- ref: c91638ca0671b8038831

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22057044653)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260215-blueberry-aarch64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c.json)

### vs. base

- Geometric mean: 1.009x faster (HPT: reliability of 57.42%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260215-blueberry-aarch64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base-mem.svg)
- [📄table](bm-20260215-blueberry-aarch64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base.md)
- [📈time plot](bm-20260215-blueberry-aarch64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22057044653)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260215-ripley-x86_64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c.json)

### vs. base

- Geometric mean: 1.031x faster (HPT: reliability of 72.87%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260215-ripley-x86_64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base-mem.svg)
- [📄table](bm-20260215-ripley-x86_64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base.md)
- [📈time plot](bm-20260215-ripley-x86_64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22057044653)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260215-prometheus-amd64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c.json)

### vs. base

- Geometric mean: 1.144x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260215-prometheus-amd64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base.md)
- [📈time plot](bm-20260215-prometheus-amd64-python-c91638ca0671b8038831-3.15.0a6%2B-c91638c-vs-base.svg)

