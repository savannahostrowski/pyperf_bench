# Results

- fork: python/5ffefdb108094a44e843
- version: 3.16.0a0
- config: JIT
- commit hash: [5ffefdb](https://github.com/python/cpython/commit/5ffefdb)
- commit date: 2026-08-07T15:16:25-07:00
- commit merge base: [115400b5090f14233b72b255e483b4485c868100](https://github.com/python/cpython/commit/115400b5090f14233b72b255e483b4485c868100)
- ref: 5ffefdb108094a44e843

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31251101686)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260807-blueberry-aarch64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb.json)

### vs. base

- Geometric mean: 1.028x slower (HPT: reliability of 99.87%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260807-blueberry-aarch64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb-vs-base-mem.svg)
- [📄table](bm-20260807-blueberry-aarch64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb-vs-base.md)
- [📈time plot](bm-20260807-blueberry-aarch64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31251101686)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260807-ripley-x86_64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260807-ripley-x86_64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb-vs-base-mem.svg)
- [📄table](bm-20260807-ripley-x86_64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb-vs-base.md)
- [📈time plot](bm-20260807-ripley-x86_64-python-5ffefdb108094a44e843-3.16.0a0-5ffefdb-vs-base.svg)

