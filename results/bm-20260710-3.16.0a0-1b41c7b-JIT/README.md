# Results

- fork: python/1b41c7b722b77d9c02c6
- version: 3.16.0a0
- config: JIT
- commit hash: [1b41c7b](https://github.com/python/cpython/commit/1b41c7b)
- commit date: 2026-07-10T01:29:53+02:00
- commit merge base: [87e5aac5ec85939cbd7623c0d7b4acc3cffd14ef](https://github.com/python/cpython/commit/87e5aac5ec85939cbd7623c0d7b4acc3cffd14ef)
- ref: 1b41c7b722b77d9c02c6

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29090916093)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260710-blueberry-aarch64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b.json)

### vs. base

- Geometric mean: 1.009x slower (HPT: reliability of 90.42%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260710-blueberry-aarch64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b-vs-base-mem.svg)
- [📄table](bm-20260710-blueberry-aarch64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b-vs-base.md)
- [📈time plot](bm-20260710-blueberry-aarch64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29090916093)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260710-ripley-x86_64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b.json)

### vs. base

- Geometric mean: 1.072x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260710-ripley-x86_64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b-vs-base-mem.svg)
- [📄table](bm-20260710-ripley-x86_64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b-vs-base.md)
- [📈time plot](bm-20260710-ripley-x86_64-python-1b41c7b722b77d9c02c6-3.16.0a0-1b41c7b-vs-base.svg)

