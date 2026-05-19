# Results

- fork: python/57a0e570d36f41b953a9
- version: 3.16.0a0
- config: JIT
- commit hash: [57a0e57](https://github.com/python/cpython/commit/57a0e57)
- commit date: 2026-05-18T16:26:08-07:00
- commit merge base: [56737483c2ffdaadfec648fd38d409c6b10941c0](https://github.com/python/cpython/commit/56737483c2ffdaadfec648fd38d409c6b10941c0)
- ref: 57a0e570d36f41b953a9

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26091110073)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260518-blueberry-aarch64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 75.99%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260518-blueberry-aarch64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57-vs-base-mem.svg)
- [📄table](bm-20260518-blueberry-aarch64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57-vs-base.md)
- [📈time plot](bm-20260518-blueberry-aarch64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26091110073)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260518-ripley-x86_64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57.json)

### vs. base

- Geometric mean: 1.072x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260518-ripley-x86_64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57-vs-base-mem.svg)
- [📄table](bm-20260518-ripley-x86_64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57-vs-base.md)
- [📈time plot](bm-20260518-ripley-x86_64-python-57a0e570d36f41b953a9-3.16.0a0-57a0e57-vs-base.svg)

