# Results

- fork: python/4e0677ac610d9e890503
- version: 3.16.0a1+dev
- config: JIT
- commit hash: [4e0677a](https://github.com/python/cpython/commit/4e0677a)
- commit date: 2026-11-02T10:18:34+09:00
- commit merge base: [4b21d154b4864531641f90e1b87108575e673d75](https://github.com/python/cpython/commit/4b21d154b4864531641f90e1b87108575e673d75)
- ref: 4e0677ac610d9e890503

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/41508673314)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261102-blueberry-aarch64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a.json)

### vs. base

- Geometric mean: 1.006x slower (HPT: reliability of 98.49%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20261102-blueberry-aarch64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a-vs-base-mem.svg)
- [📄table](bm-20261102-blueberry-aarch64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a-vs-base.md)
- [📈time plot](bm-20261102-blueberry-aarch64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/41508673314)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-142-generic-x86_64-with-glibc2.39
- [raw results](bm-20261102-ripley-x86_64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a.json)

### vs. base

- Geometric mean: 1.089x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20261102-ripley-x86_64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a-vs-base-mem.svg)
- [📄table](bm-20261102-ripley-x86_64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a-vs-base.md)
- [📈time plot](bm-20261102-ripley-x86_64-python-4e0677ac610d9e890503-3.16.0a1%2Bdev-4e0677a-vs-base.svg)

