# Results

- fork: python/1277a5e5820ee7478654
- version: 3.16.0a1+dev
- config: JIT
- commit hash: [1277a5e](https://github.com/python/cpython/commit/1277a5e)
- commit date: 2026-10-20T17:25:31-07:00
- commit merge base: [f9c0e1ea27a8731fecc3395ae31fc88277ff24b3](https://github.com/python/cpython/commit/f9c0e1ea27a8731fecc3395ae31fc88277ff24b3)
- ref: 1277a5e5820ee7478654

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/39616458375)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261020-blueberry-aarch64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e.json)

### vs. base

- Geometric mean: 1.006x faster (HPT: reliability of 57.31%, 1.00x faster at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20261020-blueberry-aarch64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e-vs-base-mem.svg)
- [📄table](bm-20261020-blueberry-aarch64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e-vs-base.md)
- [📈time plot](bm-20261020-blueberry-aarch64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/39616458375)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-142-generic-x86_64-with-glibc2.39
- [raw results](bm-20261020-ripley-x86_64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e.json)

### vs. base

- Geometric mean: 1.096x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20261020-ripley-x86_64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e-vs-base-mem.svg)
- [📄table](bm-20261020-ripley-x86_64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e-vs-base.md)
- [📈time plot](bm-20261020-ripley-x86_64-python-1277a5e5820ee7478654-3.16.0a1%2Bdev-1277a5e-vs-base.svg)

