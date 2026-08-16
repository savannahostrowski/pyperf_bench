# Results

- fork: python/e3287f631f3c88ed8019
- version: 3.16.0a0
- config: JIT
- commit hash: [e3287f6](https://github.com/python/cpython/commit/e3287f6)
- commit date: 2026-08-15T20:47:06+00:00
- commit merge base: [1a52eaedce6f1d32cdb5ee18ecec74cfd82d5550](https://github.com/python/cpython/commit/1a52eaedce6f1d32cdb5ee18ecec74cfd82d5550)
- ref: e3287f631f3c88ed8019

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31939220037)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260815-blueberry-aarch64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6.json)

### vs. base

- Geometric mean: 1.006x slower (HPT: reliability of 77.13%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260815-blueberry-aarch64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base-mem.svg)
- [📄table](bm-20260815-blueberry-aarch64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.md)
- [📈time plot](bm-20260815-blueberry-aarch64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31939220037)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260815-ripley-x86_64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6.json)

### vs. base

- Geometric mean: 1.070x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260815-ripley-x86_64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base-mem.svg)
- [📄table](bm-20260815-ripley-x86_64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.md)
- [📈time plot](bm-20260815-ripley-x86_64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.svg)

