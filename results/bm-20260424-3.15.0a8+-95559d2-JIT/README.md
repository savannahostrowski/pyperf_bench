# Results

- fork: python/95559d2a7e0071342dff
- version: 3.15.0a8+
- config: JIT
- commit hash: [95559d2](https://github.com/python/cpython/commit/95559d2)
- commit date: 2026-04-24T11:22:05-07:00
- commit merge base: [665b7dfcfa240e02760f58bed5ca29ec01d028e6](https://github.com/python/cpython/commit/665b7dfcfa240e02760f58bed5ca29ec01d028e6)
- ref: 95559d2a7e0071342dff

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24927719217)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260424-blueberry-aarch64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2.json)

### vs. base

- Geometric mean: 1.011x faster (HPT: reliability of 65.26%, 1.00x faster at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260424-blueberry-aarch64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base-mem.svg)
- [📄table](bm-20260424-blueberry-aarch64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.md)
- [📈time plot](bm-20260424-blueberry-aarch64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24927719217)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260424-ripley-x86_64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2.json)

### vs. base

- Geometric mean: 1.084x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260424-ripley-x86_64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base-mem.svg)
- [📄table](bm-20260424-ripley-x86_64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.md)
- [📈time plot](bm-20260424-ripley-x86_64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.svg)

