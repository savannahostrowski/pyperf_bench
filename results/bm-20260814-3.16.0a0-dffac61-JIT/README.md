# Results

- fork: python/dffac6163e693cf80ed4
- version: 3.16.0a0
- config: JIT
- commit hash: [dffac61](https://github.com/python/cpython/commit/dffac61)
- commit date: 2026-08-14T14:17:23-07:00
- commit merge base: [bc6749cc3b5ae4a5e88a6cc2d5b3bebbe354eae6](https://github.com/python/cpython/commit/bc6749cc3b5ae4a5e88a6cc2d5b3bebbe354eae6)
- ref: dffac6163e693cf80ed4

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31877105324)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260814-blueberry-aarch64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61.json)

### vs. base

- Geometric mean: 1.005x slower (HPT: reliability of 84.72%, 1.00x slower at 99th %ile)
- Memory usage: 1.07x
- [🧠memory plot](bm-20260814-blueberry-aarch64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base-mem.svg)
- [📄table](bm-20260814-blueberry-aarch64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.md)
- [📈time plot](bm-20260814-blueberry-aarch64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31877105324)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260814-ripley-x86_64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260814-ripley-x86_64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base-mem.svg)
- [📄table](bm-20260814-ripley-x86_64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.md)
- [📈time plot](bm-20260814-ripley-x86_64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.svg)

