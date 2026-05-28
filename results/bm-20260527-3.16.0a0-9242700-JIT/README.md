# Results

- fork: python/9242700c149c490c56d2
- version: 3.16.0a0
- config: JIT
- commit hash: [9242700](https://github.com/python/cpython/commit/9242700)
- commit date: 2026-05-27T18:03:34-04:00
- commit merge base: [24c6bbc92b6dd0ce9b7ff799049498299f70f97d](https://github.com/python/cpython/commit/24c6bbc92b6dd0ce9b7ff799049498299f70f97d)
- ref: 9242700c149c490c56d2

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26569366637)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260527-blueberry-aarch64-python-9242700c149c490c56d2-3.16.0a0-9242700.json)

### vs. base

- Geometric mean: 1.014x slower (HPT: reliability of 79.57%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260527-blueberry-aarch64-python-9242700c149c490c56d2-3.16.0a0-9242700-vs-base-mem.svg)
- [📄table](bm-20260527-blueberry-aarch64-python-9242700c149c490c56d2-3.16.0a0-9242700-vs-base.md)
- [📈time plot](bm-20260527-blueberry-aarch64-python-9242700c149c490c56d2-3.16.0a0-9242700-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26569366637)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260527-ripley-x86_64-python-9242700c149c490c56d2-3.16.0a0-9242700.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260527-ripley-x86_64-python-9242700c149c490c56d2-3.16.0a0-9242700-vs-base-mem.svg)
- [📄table](bm-20260527-ripley-x86_64-python-9242700c149c490c56d2-3.16.0a0-9242700-vs-base.md)
- [📈time plot](bm-20260527-ripley-x86_64-python-9242700c149c490c56d2-3.16.0a0-9242700-vs-base.svg)

