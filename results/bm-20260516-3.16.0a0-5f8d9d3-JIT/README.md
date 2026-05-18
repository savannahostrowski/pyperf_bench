# Results

- fork: python/5f8d9d35753e22946880
- version: 3.16.0a0
- config: JIT
- commit hash: [5f8d9d3](https://github.com/python/cpython/commit/5f8d9d3)
- commit date: 2026-05-16T11:24:41-07:00
- commit merge base: [a7ed0c9e1dee1397e80e2e0d90d110155da2bc30](https://github.com/python/cpython/commit/a7ed0c9e1dee1397e80e2e0d90d110155da2bc30)
- ref: 5f8d9d35753e22946880

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25987332975)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260516-blueberry-aarch64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3.json)

### vs. base

- Geometric mean: 1.018x slower (HPT: reliability of 97.05%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260516-blueberry-aarch64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3-vs-base-mem.svg)
- [📄table](bm-20260516-blueberry-aarch64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3-vs-base.md)
- [📈time plot](bm-20260516-blueberry-aarch64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25987332975)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260516-ripley-x86_64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3.json)

### vs. base

- Geometric mean: 1.063x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260516-ripley-x86_64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3-vs-base-mem.svg)
- [📄table](bm-20260516-ripley-x86_64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3-vs-base.md)
- [📈time plot](bm-20260516-ripley-x86_64-python-5f8d9d35753e22946880-3.16.0a0-5f8d9d3-vs-base.svg)

