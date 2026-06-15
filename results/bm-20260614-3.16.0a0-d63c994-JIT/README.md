# Results

- fork: python/d63c9940f0bcc5497c42
- version: 3.16.0a0
- config: JIT
- commit hash: [d63c994](https://github.com/python/cpython/commit/d63c994)
- commit date: 2026-06-14T19:17:45+00:00
- commit merge base: [a7007322c2a70b01e7c2a9e6b3f8f222d241c7d7](https://github.com/python/cpython/commit/a7007322c2a70b01e7c2a9e6b3f8f222d241c7d7)
- ref: d63c9940f0bcc5497c42

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27542345537)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260614-blueberry-aarch64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994.json)

### vs. base

- Geometric mean: 1.010x slower (HPT: reliability of 85.16%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260614-blueberry-aarch64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994-vs-base-mem.svg)
- [📄table](bm-20260614-blueberry-aarch64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994-vs-base.md)
- [📈time plot](bm-20260614-blueberry-aarch64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27542345537)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260614-ripley-x86_64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260614-ripley-x86_64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994-vs-base-mem.svg)
- [📄table](bm-20260614-ripley-x86_64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994-vs-base.md)
- [📈time plot](bm-20260614-ripley-x86_64-python-d63c9940f0bcc5497c42-3.16.0a0-d63c994-vs-base.svg)

