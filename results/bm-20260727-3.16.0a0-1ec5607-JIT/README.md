# Results

- fork: python/1ec56076642091c446ec
- version: 3.16.0a0
- config: JIT
- commit hash: [1ec5607](https://github.com/python/cpython/commit/1ec5607)
- commit date: 2026-07-27T13:45:40-07:00
- commit merge base: [0284ce81c9615432473abac709d5b261a49399ad](https://github.com/python/cpython/commit/0284ce81c9615432473abac709d5b261a49399ad)
- ref: 1ec56076642091c446ec

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30354444429)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260727-blueberry-aarch64-python-1ec56076642091c446ec-3.16.0a0-1ec5607.json)

### vs. base

- Geometric mean: 1.026x faster (HPT: reliability of 98.85%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260727-blueberry-aarch64-python-1ec56076642091c446ec-3.16.0a0-1ec5607-vs-base-mem.svg)
- [📄table](bm-20260727-blueberry-aarch64-python-1ec56076642091c446ec-3.16.0a0-1ec5607-vs-base.md)
- [📈time plot](bm-20260727-blueberry-aarch64-python-1ec56076642091c446ec-3.16.0a0-1ec5607-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30354444429)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260727-ripley-x86_64-python-1ec56076642091c446ec-3.16.0a0-1ec5607.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260727-ripley-x86_64-python-1ec56076642091c446ec-3.16.0a0-1ec5607-vs-base-mem.svg)
- [📄table](bm-20260727-ripley-x86_64-python-1ec56076642091c446ec-3.16.0a0-1ec5607-vs-base.md)
- [📈time plot](bm-20260727-ripley-x86_64-python-1ec56076642091c446ec-3.16.0a0-1ec5607-vs-base.svg)

