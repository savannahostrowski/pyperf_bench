# Results

- fork: python/5056ac552a413b394fd1
- version: 3.16.0a0
- config: JIT
- commit hash: [5056ac5](https://github.com/python/cpython/commit/5056ac5)
- commit date: 2026-09-03T00:10:23+03:00
- commit merge base: [d16a691111503798820a4b3a60ffae7b76c4d85a](https://github.com/python/cpython/commit/d16a691111503798820a4b3a60ffae7b76c4d85a)
- ref: 5056ac552a413b394fd1

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33760941117)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260903-blueberry-aarch64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5.json)

### vs. base

- Geometric mean: 1.014x slower (HPT: reliability of 99.40%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260903-blueberry-aarch64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5-vs-base-mem.svg)
- [📄table](bm-20260903-blueberry-aarch64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5-vs-base.md)
- [📈time plot](bm-20260903-blueberry-aarch64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33760941117)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260903-ripley-x86_64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260903-ripley-x86_64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5-vs-base-mem.svg)
- [📄table](bm-20260903-ripley-x86_64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5-vs-base.md)
- [📈time plot](bm-20260903-ripley-x86_64-python-5056ac552a413b394fd1-3.16.0a0-5056ac5-vs-base.svg)

