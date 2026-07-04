# Results

- fork: python/548c7314138b85cab3b9
- version: 3.16.0a0
- config: JIT
- commit hash: [548c731](https://github.com/python/cpython/commit/548c731)
- commit date: 2026-07-03T14:01:58-07:00
- commit merge base: [cde31ec135905472f1137dddcc8227af2430d89c](https://github.com/python/cpython/commit/cde31ec135905472f1137dddcc8227af2430d89c)
- ref: 548c7314138b85cab3b9

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28703972184)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260703-blueberry-aarch64-python-548c7314138b85cab3b9-3.16.0a0-548c731.json)

### vs. base

- Geometric mean: 1.001x slower (HPT: reliability of 67.68%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260703-blueberry-aarch64-python-548c7314138b85cab3b9-3.16.0a0-548c731-vs-base-mem.svg)
- [📄table](bm-20260703-blueberry-aarch64-python-548c7314138b85cab3b9-3.16.0a0-548c731-vs-base.md)
- [📈time plot](bm-20260703-blueberry-aarch64-python-548c7314138b85cab3b9-3.16.0a0-548c731-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28703972184)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260703-ripley-x86_64-python-548c7314138b85cab3b9-3.16.0a0-548c731.json)

### vs. base

- Geometric mean: 1.073x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260703-ripley-x86_64-python-548c7314138b85cab3b9-3.16.0a0-548c731-vs-base-mem.svg)
- [📄table](bm-20260703-ripley-x86_64-python-548c7314138b85cab3b9-3.16.0a0-548c731-vs-base.md)
- [📈time plot](bm-20260703-ripley-x86_64-python-548c7314138b85cab3b9-3.16.0a0-548c731-vs-base.svg)

