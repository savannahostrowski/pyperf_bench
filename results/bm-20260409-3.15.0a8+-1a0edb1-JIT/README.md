# Results

- fork: python/1a0edb1fa899c067f19b
- version: 3.15.0a8+
- config: JIT
- commit hash: [1a0edb1](https://github.com/python/cpython/commit/1a0edb1)
- commit date: 2026-04-09T16:21:49-04:00
- commit merge base: [0f492326647a760ab6d66d20334c3308df64a02d](https://github.com/python/cpython/commit/0f492326647a760ab6d66d20334c3308df64a02d)
- ref: 1a0edb1fa899c067f19b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24236504160)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260409-blueberry-aarch64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1.json)

### vs. base

- Geometric mean: 1.009x slower (HPT: reliability of 75.88%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260409-blueberry-aarch64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1-vs-base-mem.svg)
- [📄table](bm-20260409-blueberry-aarch64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1-vs-base.md)
- [📈time plot](bm-20260409-blueberry-aarch64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24236504160)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260409-ripley-x86_64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1.json)

### vs. base

- Geometric mean: 1.062x faster (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260409-ripley-x86_64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1-vs-base-mem.svg)
- [📄table](bm-20260409-ripley-x86_64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1-vs-base.md)
- [📈time plot](bm-20260409-ripley-x86_64-python-1a0edb1fa899c067f19b-3.15.0a8%2B-1a0edb1-vs-base.svg)

