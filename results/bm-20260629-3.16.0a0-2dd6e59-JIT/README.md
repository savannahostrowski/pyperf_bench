# Results

- fork: python/2dd6e59aea24220975cc
- version: 3.16.0a0
- config: JIT
- commit hash: [2dd6e59](https://github.com/python/cpython/commit/2dd6e59)
- commit date: 2026-06-29T23:18:19+00:00
- commit merge base: [bc3fa17c30cc95664a663c47ab9938fdf9cb1429](https://github.com/python/cpython/commit/bc3fa17c30cc95664a663c47ab9938fdf9cb1429)
- ref: 2dd6e59aea24220975cc

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28437053816)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260629-blueberry-aarch64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59.json)

### vs. base

- Geometric mean: 1.009x slower (HPT: reliability of 88.06%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260629-blueberry-aarch64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59-vs-base-mem.svg)
- [📄table](bm-20260629-blueberry-aarch64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59-vs-base.md)
- [📈time plot](bm-20260629-blueberry-aarch64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28437053816)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260629-ripley-x86_64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59.json)

### vs. base

- Geometric mean: 1.073x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260629-ripley-x86_64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59-vs-base-mem.svg)
- [📄table](bm-20260629-ripley-x86_64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59-vs-base.md)
- [📈time plot](bm-20260629-ripley-x86_64-python-2dd6e59aea24220975cc-3.16.0a0-2dd6e59-vs-base.svg)

