# Results

- fork: python/b062727097e997bcb900
- version: 3.16.0a0
- config: JIT
- commit hash: [b062727](https://github.com/python/cpython/commit/b062727)
- commit date: 2026-08-22T19:45:59+01:00
- commit merge base: [6f42535b333b6d2d56ba2b27e436c37e8ae63a02](https://github.com/python/cpython/commit/6f42535b333b6d2d56ba2b27e436c37e8ae63a02)
- ref: b062727097e997bcb900

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32631214543)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260822-blueberry-aarch64-python-b062727097e997bcb900-3.16.0a0-b062727.json)

### vs. base

- Geometric mean: 1.019x slower (HPT: reliability of 97.72%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260822-blueberry-aarch64-python-b062727097e997bcb900-3.16.0a0-b062727-vs-base-mem.svg)
- [📄table](bm-20260822-blueberry-aarch64-python-b062727097e997bcb900-3.16.0a0-b062727-vs-base.md)
- [📈time plot](bm-20260822-blueberry-aarch64-python-b062727097e997bcb900-3.16.0a0-b062727-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32631214543)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260822-ripley-x86_64-python-b062727097e997bcb900-3.16.0a0-b062727.json)

### vs. base

- Geometric mean: 1.076x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260822-ripley-x86_64-python-b062727097e997bcb900-3.16.0a0-b062727-vs-base-mem.svg)
- [📄table](bm-20260822-ripley-x86_64-python-b062727097e997bcb900-3.16.0a0-b062727-vs-base.md)
- [📈time plot](bm-20260822-ripley-x86_64-python-b062727097e997bcb900-3.16.0a0-b062727-vs-base.svg)

