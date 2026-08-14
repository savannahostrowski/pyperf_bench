# Results

- fork: python/46c355fabff5833b77f7
- version: 3.16.0a0
- config: JIT
- commit hash: [46c355f](https://github.com/python/cpython/commit/46c355f)
- commit date: 2026-08-13T21:50:50+02:00
- commit merge base: [5ea393501e308586a689acab6d78ff74b365045b](https://github.com/python/cpython/commit/5ea393501e308586a689acab6d78ff74b365045b)
- ref: 46c355fabff5833b77f7

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31790880776)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260813-blueberry-aarch64-python-46c355fabff5833b77f7-3.16.0a0-46c355f.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 77.04%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260813-blueberry-aarch64-python-46c355fabff5833b77f7-3.16.0a0-46c355f-vs-base-mem.svg)
- [📄table](bm-20260813-blueberry-aarch64-python-46c355fabff5833b77f7-3.16.0a0-46c355f-vs-base.md)
- [📈time plot](bm-20260813-blueberry-aarch64-python-46c355fabff5833b77f7-3.16.0a0-46c355f-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31790880776)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260813-ripley-x86_64-python-46c355fabff5833b77f7-3.16.0a0-46c355f.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260813-ripley-x86_64-python-46c355fabff5833b77f7-3.16.0a0-46c355f-vs-base-mem.svg)
- [📄table](bm-20260813-ripley-x86_64-python-46c355fabff5833b77f7-3.16.0a0-46c355f-vs-base.md)
- [📈time plot](bm-20260813-ripley-x86_64-python-46c355fabff5833b77f7-3.16.0a0-46c355f-vs-base.svg)

