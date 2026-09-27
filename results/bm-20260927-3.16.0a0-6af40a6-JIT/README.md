# Results

- fork: python/6af40a682881f8442e1b
- version: 3.16.0a0
- config: JIT
- commit hash: [6af40a6](https://github.com/python/cpython/commit/6af40a6)
- commit date: 2026-09-27T01:12:32+00:00
- commit merge base: [1e8ff18a1215b711136b4377282e392583847d62](https://github.com/python/cpython/commit/1e8ff18a1215b711136b4377282e392583847d62)
- ref: 6af40a682881f8442e1b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/36326549512)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260927-blueberry-aarch64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 85.17%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260927-blueberry-aarch64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6-vs-base-mem.svg)
- [📄table](bm-20260927-blueberry-aarch64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6-vs-base.md)
- [📈time plot](bm-20260927-blueberry-aarch64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/36326549512)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260927-ripley-x86_64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6.json)

### vs. base

- Geometric mean: 1.078x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260927-ripley-x86_64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6-vs-base-mem.svg)
- [📄table](bm-20260927-ripley-x86_64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6-vs-base.md)
- [📈time plot](bm-20260927-ripley-x86_64-python-6af40a682881f8442e1b-3.16.0a0-6af40a6-vs-base.svg)

