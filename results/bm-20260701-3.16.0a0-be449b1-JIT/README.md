# Results

- fork: python/be449b1c6ad739a40a7d
- version: 3.16.0a0
- config: JIT
- commit hash: [be449b1](https://github.com/python/cpython/commit/be449b1)
- commit date: 2026-07-01T19:00:18-04:00
- commit merge base: [3428762f33c6c064998f5b0c385cdfd0f0c2e198](https://github.com/python/cpython/commit/3428762f33c6c064998f5b0c385cdfd0f0c2e198)
- ref: be449b1c6ad739a40a7d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28581963037)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260701-blueberry-aarch64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 71.70%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260701-blueberry-aarch64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1-vs-base-mem.svg)
- [📄table](bm-20260701-blueberry-aarch64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1-vs-base.md)
- [📈time plot](bm-20260701-blueberry-aarch64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28581963037)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260701-ripley-x86_64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260701-ripley-x86_64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1-vs-base-mem.svg)
- [📄table](bm-20260701-ripley-x86_64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1-vs-base.md)
- [📈time plot](bm-20260701-ripley-x86_64-python-be449b1c6ad739a40a7d-3.16.0a0-be449b1-vs-base.svg)

