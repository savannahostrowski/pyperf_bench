# Results

- fork: python/c6fd7de64ac7591a9708
- version: 3.16.0a0
- config: JIT
- commit hash: [c6fd7de](https://github.com/python/cpython/commit/c6fd7de)
- commit date: 2026-05-10T15:22:16-07:00
- commit merge base: [b45319e13273ee17e84e6b8c459f03b141518289](https://github.com/python/cpython/commit/b45319e13273ee17e84e6b8c459f03b141518289)
- ref: c6fd7de64ac7591a9708

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25664366768)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260510-blueberry-aarch64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de.json)

### vs. base

- Geometric mean: 1.010x slower (HPT: reliability of 86.58%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260510-blueberry-aarch64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de-vs-base-mem.svg)
- [📄table](bm-20260510-blueberry-aarch64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de-vs-base.md)
- [📈time plot](bm-20260510-blueberry-aarch64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25664366768)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260510-ripley-x86_64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de.json)

### vs. base

- Geometric mean: 1.070x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260510-ripley-x86_64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de-vs-base-mem.svg)
- [📄table](bm-20260510-ripley-x86_64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de-vs-base.md)
- [📈time plot](bm-20260510-ripley-x86_64-python-c6fd7de64ac7591a9708-3.16.0a0-c6fd7de-vs-base.svg)

