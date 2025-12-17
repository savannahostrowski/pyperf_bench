# Results

- fork: python/b3b63e8d6d296b879fdd
- version: 3.15.0a2+
- config: JIT
- commit hash: [b3b63e8](https://github.com/python/cpython/commit/b3b63e8)
- commit date: 2025-11-19T08:16:03-06:00
- commit merge base: [96f496a949b05054d0d043c3085f00cec2f83bf5](https://github.com/python/cpython/commit/96f496a949b05054d0d043c3085f00cec2f83bf5)
- ref: b3b63e8d6d296b879fdd

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19508302612)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8.json)

### vs. base

- Geometric mean: 1.024x slower (HPT: reliability of 74.27%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base-mem.svg)
- [📄table](bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.md)
- [📈time plot](bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19508302612)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8.json)

### vs. base

- Geometric mean: 1.010x faster (HPT: reliability of 97.14%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base-mem.svg)
- [📄table](bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.md)
- [📈time plot](bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.svg)

