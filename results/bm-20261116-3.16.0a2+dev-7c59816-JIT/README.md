# Results

- fork: python/7c59816cb4d3db8387c4
- version: 3.16.0a2+dev
- config: JIT
- commit hash: [7c59816](https://github.com/python/cpython/commit/7c59816)
- commit date: 2026-11-16T11:05:00+09:00
- commit merge base: [2e14c838544c6c36b9095544b4b6c994d3832678](https://github.com/python/cpython/commit/2e14c838544c6c36b9095544b4b6c994d3832678)
- ref: 7c59816cb4d3db8387c4

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/43939037082)
- cpu model: missing
- platform: Linux-6.12.115+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261116-blueberry-aarch64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816.json)

### vs. base

- Geometric mean: 1.003x faster (HPT: reliability of 79.06%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20261116-blueberry-aarch64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816-vs-base-mem.svg)
- [📄table](bm-20261116-blueberry-aarch64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816-vs-base.md)
- [📈time plot](bm-20261116-blueberry-aarch64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/43939037082)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-149-generic-x86_64-with-glibc2.39
- [raw results](bm-20261116-ripley-x86_64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816.json)

### vs. base

- Geometric mean: 1.087x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20261116-ripley-x86_64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816-vs-base-mem.svg)
- [📄table](bm-20261116-ripley-x86_64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816-vs-base.md)
- [📈time plot](bm-20261116-ripley-x86_64-python-7c59816cb4d3db8387c4-3.16.0a2%2Bdev-7c59816-vs-base.svg)

