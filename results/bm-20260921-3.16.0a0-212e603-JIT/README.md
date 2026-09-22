# Results

- fork: python/212e6035133957a66f1a
- version: 3.16.0a0
- config: JIT
- commit hash: [212e603](https://github.com/python/cpython/commit/212e603)
- commit date: 2026-09-21T17:00:06-04:00
- commit merge base: [02fae7a9594953c1d8b298b08d6faa99a5c18975](https://github.com/python/cpython/commit/02fae7a9594953c1d8b298b08d6faa99a5c18975)
- ref: 212e6035133957a66f1a

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35736940735)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260921-blueberry-aarch64-python-212e6035133957a66f1a-3.16.0a0-212e603.json)

### vs. base

- Geometric mean: 1.000x slower (HPT: reliability of 83.40%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260921-blueberry-aarch64-python-212e6035133957a66f1a-3.16.0a0-212e603-vs-base-mem.svg)
- [📄table](bm-20260921-blueberry-aarch64-python-212e6035133957a66f1a-3.16.0a0-212e603-vs-base.md)
- [📈time plot](bm-20260921-blueberry-aarch64-python-212e6035133957a66f1a-3.16.0a0-212e603-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35736940735)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260921-ripley-x86_64-python-212e6035133957a66f1a-3.16.0a0-212e603.json)

### vs. base

- Geometric mean: 1.081x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260921-ripley-x86_64-python-212e6035133957a66f1a-3.16.0a0-212e603-vs-base-mem.svg)
- [📄table](bm-20260921-ripley-x86_64-python-212e6035133957a66f1a-3.16.0a0-212e603-vs-base.md)
- [📈time plot](bm-20260921-ripley-x86_64-python-212e6035133957a66f1a-3.16.0a0-212e603-vs-base.svg)

