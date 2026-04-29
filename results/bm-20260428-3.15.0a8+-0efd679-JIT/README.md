# Results

- fork: python/0efd679a6ce3b57ec3c5
- version: 3.15.0a8+
- config: JIT
- commit hash: [0efd679](https://github.com/python/cpython/commit/0efd679)
- commit date: 2026-04-28T00:06:23+01:00
- commit merge base: [005555a3f0ae20ee8154eb4ee172e1e355144c8c](https://github.com/python/cpython/commit/005555a3f0ae20ee8154eb4ee172e1e355144c8c)
- ref: 0efd679a6ce3b57ec3c5

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25046140627)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260428-blueberry-aarch64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679.json)

### vs. base

- Geometric mean: 1.014x faster (HPT: reliability of 51.95%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260428-blueberry-aarch64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base-mem.svg)
- [📄table](bm-20260428-blueberry-aarch64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.md)
- [📈time plot](bm-20260428-blueberry-aarch64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25046140627)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260428-ripley-x86_64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679.json)

### vs. base

- Geometric mean: 1.086x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260428-ripley-x86_64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base-mem.svg)
- [📄table](bm-20260428-ripley-x86_64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.md)
- [📈time plot](bm-20260428-ripley-x86_64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.svg)

