# Results

- fork: python/ef1fce0a69a19360643f
- version: 3.16.0a1+dev
- config: JIT
- commit hash: [ef1fce0](https://github.com/python/cpython/commit/ef1fce0)
- commit date: 2026-10-29T14:23:07-07:00
- commit merge base: [7515b64aa7231e8a8cf5271155829a208d789583](https://github.com/python/cpython/commit/7515b64aa7231e8a8cf5271155829a208d789583)
- ref: ef1fce0a69a19360643f

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/41083270623)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261029-blueberry-aarch64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0.json)

### vs. base

- Geometric mean: 1.008x slower (HPT: reliability of 90.54%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20261029-blueberry-aarch64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0-vs-base-mem.svg)
- [📄table](bm-20261029-blueberry-aarch64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0-vs-base.md)
- [📈time plot](bm-20261029-blueberry-aarch64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/41083270623)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-142-generic-x86_64-with-glibc2.39
- [raw results](bm-20261029-ripley-x86_64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0.json)

### vs. base

- Geometric mean: 1.090x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20261029-ripley-x86_64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0-vs-base-mem.svg)
- [📄table](bm-20261029-ripley-x86_64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0-vs-base.md)
- [📈time plot](bm-20261029-ripley-x86_64-python-ef1fce0a69a19360643f-3.16.0a1%2Bdev-ef1fce0-vs-base.svg)

