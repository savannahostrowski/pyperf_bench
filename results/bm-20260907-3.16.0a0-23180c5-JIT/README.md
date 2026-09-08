# Results

- fork: python/23180c50082fe98784c7
- version: 3.16.0a0
- config: JIT
- commit hash: [23180c5](https://github.com/python/cpython/commit/23180c5)
- commit date: 2026-09-07T22:44:20+03:00
- commit merge base: [23525c90f539f621c802f2725e91ff234a69e1e0](https://github.com/python/cpython/commit/23525c90f539f621c802f2725e91ff234a69e1e0)
- ref: 23180c50082fe98784c7

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34231791819)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260907-blueberry-aarch64-python-23180c50082fe98784c7-3.16.0a0-23180c5.json)

### vs. base

- Geometric mean: 1.024x slower (HPT: reliability of 99.87%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260907-blueberry-aarch64-python-23180c50082fe98784c7-3.16.0a0-23180c5-vs-base-mem.svg)
- [📄table](bm-20260907-blueberry-aarch64-python-23180c50082fe98784c7-3.16.0a0-23180c5-vs-base.md)
- [📈time plot](bm-20260907-blueberry-aarch64-python-23180c50082fe98784c7-3.16.0a0-23180c5-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34231791819)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260907-ripley-x86_64-python-23180c50082fe98784c7-3.16.0a0-23180c5.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260907-ripley-x86_64-python-23180c50082fe98784c7-3.16.0a0-23180c5-vs-base-mem.svg)
- [📄table](bm-20260907-ripley-x86_64-python-23180c50082fe98784c7-3.16.0a0-23180c5-vs-base.md)
- [📈time plot](bm-20260907-ripley-x86_64-python-23180c50082fe98784c7-3.16.0a0-23180c5-vs-base.svg)

