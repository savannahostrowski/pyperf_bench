# Results

- fork: python/e56f86fb6cc7cf14c255
- version: 3.16.0a0
- config: JIT
- commit hash: [e56f86f](https://github.com/python/cpython/commit/e56f86f)
- commit date: 2026-09-04T17:15:44+00:00
- commit merge base: [3a7a22b5b0cf292ab9e7d046980085c227f7fdaa](https://github.com/python/cpython/commit/3a7a22b5b0cf292ab9e7d046980085c227f7fdaa)
- ref: e56f86fb6cc7cf14c255

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33966179766)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260904-blueberry-aarch64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f.json)

### vs. base

- Geometric mean: 1.015x slower (HPT: reliability of 97.99%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260904-blueberry-aarch64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f-vs-base-mem.svg)
- [📄table](bm-20260904-blueberry-aarch64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f-vs-base.md)
- [📈time plot](bm-20260904-blueberry-aarch64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33966179766)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260904-ripley-x86_64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260904-ripley-x86_64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f-vs-base-mem.svg)
- [📄table](bm-20260904-ripley-x86_64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f-vs-base.md)
- [📈time plot](bm-20260904-ripley-x86_64-python-e56f86fb6cc7cf14c255-3.16.0a0-e56f86f-vs-base.svg)

