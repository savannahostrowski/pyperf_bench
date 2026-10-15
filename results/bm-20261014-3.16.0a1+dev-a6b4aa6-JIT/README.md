# Results

- fork: python/a6b4aa687cd9f8f95e3b
- version: 3.16.0a1+dev
- config: JIT
- commit hash: [a6b4aa6](https://github.com/python/cpython/commit/a6b4aa6)
- commit date: 2026-10-14T15:53:16-07:00
- commit merge base: [b70a5128c4ef1572e6aa24f9f3739d17eacfafef](https://github.com/python/cpython/commit/b70a5128c4ef1572e6aa24f9f3739d17eacfafef)
- ref: a6b4aa687cd9f8f95e3b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/38747766131)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261014-blueberry-aarch64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6.json)

### vs. base

- Geometric mean: 1.001x faster (HPT: reliability of 86.19%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20261014-blueberry-aarch64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6-vs-base-mem.svg)
- [📄table](bm-20261014-blueberry-aarch64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6-vs-base.md)
- [📈time plot](bm-20261014-blueberry-aarch64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/38747766131)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-142-generic-x86_64-with-glibc2.39
- [raw results](bm-20261014-ripley-x86_64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6.json)

### vs. base

- Geometric mean: 1.087x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20261014-ripley-x86_64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6-vs-base-mem.svg)
- [📄table](bm-20261014-ripley-x86_64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6-vs-base.md)
- [📈time plot](bm-20261014-ripley-x86_64-python-a6b4aa687cd9f8f95e3b-3.16.0a1%2Bdev-a6b4aa6-vs-base.svg)

