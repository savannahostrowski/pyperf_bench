# Results

- fork: python/69a6612ff02c022d17f9
- version: 3.16.0a0
- config: JIT
- commit hash: [69a6612](https://github.com/python/cpython/commit/69a6612)
- commit date: 2026-09-09T17:08:37-07:00
- commit merge base: [939865532c00e25842209f56953abe0361ab22a1](https://github.com/python/cpython/commit/939865532c00e25842209f56953abe0361ab22a1)
- ref: 69a6612ff02c022d17f9

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34482689675)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260909-blueberry-aarch64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 94.01%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260909-blueberry-aarch64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612-vs-base-mem.svg)
- [📄table](bm-20260909-blueberry-aarch64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612-vs-base.md)
- [📈time plot](bm-20260909-blueberry-aarch64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34482689675)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260909-ripley-x86_64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260909-ripley-x86_64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612-vs-base-mem.svg)
- [📄table](bm-20260909-ripley-x86_64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612-vs-base.md)
- [📈time plot](bm-20260909-ripley-x86_64-python-69a6612ff02c022d17f9-3.16.0a0-69a6612-vs-base.svg)

