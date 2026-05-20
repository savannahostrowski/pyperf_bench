# Results

- fork: python/1f3c2679f1a2a106019c
- version: 3.16.0a0
- config: JIT
- commit hash: [1f3c267](https://github.com/python/cpython/commit/1f3c267)
- commit date: 2026-05-19T16:01:15-07:00
- commit merge base: [79088e0d82931c21fa72eadc416a18b7b0fdf9c1](https://github.com/python/cpython/commit/79088e0d82931c21fa72eadc416a18b7b0fdf9c1)
- ref: 1f3c2679f1a2a106019c

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26155969273)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260519-blueberry-aarch64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267.json)

### vs. base

- Geometric mean: 1.022x slower (HPT: reliability of 96.41%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260519-blueberry-aarch64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267-vs-base-mem.svg)
- [📄table](bm-20260519-blueberry-aarch64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267-vs-base.md)
- [📈time plot](bm-20260519-blueberry-aarch64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26155969273)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260519-ripley-x86_64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260519-ripley-x86_64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267-vs-base-mem.svg)
- [📄table](bm-20260519-ripley-x86_64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267-vs-base.md)
- [📈time plot](bm-20260519-ripley-x86_64-python-1f3c2679f1a2a106019c-3.16.0a0-1f3c267-vs-base.svg)

