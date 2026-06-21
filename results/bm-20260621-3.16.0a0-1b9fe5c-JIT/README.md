# Results

- fork: python/1b9fe5c7226eccc8b269
- version: 3.16.0a0
- config: JIT
- commit hash: [1b9fe5c](https://github.com/python/cpython/commit/1b9fe5c)
- commit date: 2026-06-21T01:26:53+03:00
- commit merge base: [aec0aed197872adf96d3f25fd5ea624508fcddbf](https://github.com/python/cpython/commit/aec0aed197872adf96d3f25fd5ea624508fcddbf)
- ref: 1b9fe5c7226eccc8b269

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27901224405)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260621-blueberry-aarch64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 74.44%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260621-blueberry-aarch64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c-vs-base-mem.svg)
- [📄table](bm-20260621-blueberry-aarch64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c-vs-base.md)
- [📈time plot](bm-20260621-blueberry-aarch64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27901224405)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260621-ripley-x86_64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c.json)

### vs. base

- Geometric mean: 1.078x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260621-ripley-x86_64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c-vs-base-mem.svg)
- [📄table](bm-20260621-ripley-x86_64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c-vs-base.md)
- [📈time plot](bm-20260621-ripley-x86_64-python-1b9fe5c7226eccc8b269-3.16.0a0-1b9fe5c-vs-base.svg)

