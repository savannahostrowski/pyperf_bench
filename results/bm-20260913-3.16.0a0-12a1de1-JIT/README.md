# Results

- fork: python/12a1de1a4e22732700cf
- version: 3.16.0a0
- config: JIT
- commit hash: [12a1de1](https://github.com/python/cpython/commit/12a1de1)
- commit date: 2026-09-13T00:28:39+00:00
- commit merge base: [1a703ab9e6a050b40c469788ec7758713c6bf62b](https://github.com/python/cpython/commit/1a703ab9e6a050b40c469788ec7758713c6bf62b)
- ref: 12a1de1a4e22732700cf

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34760628064)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 94.41%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1-vs-base-mem.svg)
- [📄table](bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1-vs-base.md)
- [📈time plot](bm-20260913-blueberry-aarch64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34760628064)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260913-ripley-x86_64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1.json)

### vs. base

- Geometric mean: 1.082x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260913-ripley-x86_64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1-vs-base-mem.svg)
- [📄table](bm-20260913-ripley-x86_64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1-vs-base.md)
- [📈time plot](bm-20260913-ripley-x86_64-python-12a1de1a4e22732700cf-3.16.0a0-12a1de1-vs-base.svg)

