# Results

- fork: python/461b1d96313de02992d2
- version: 3.16.0a0
- config: JIT
- commit hash: [461b1d9](https://github.com/python/cpython/commit/461b1d9)
- commit date: 2026-05-14T23:10:39+02:00
- commit merge base: [c62c3710dc795a60c3c3dc8e2aeeeb16c06da197](https://github.com/python/cpython/commit/c62c3710dc795a60c3c3dc8e2aeeeb16c06da197)
- ref: 461b1d96313de02992d2

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25911842889)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260514-blueberry-aarch64-python-461b1d96313de02992d2-3.16.0a0-461b1d9.json)

### vs. base

- Geometric mean: 1.017x slower (HPT: reliability of 91.63%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260514-blueberry-aarch64-python-461b1d96313de02992d2-3.16.0a0-461b1d9-vs-base-mem.svg)
- [📄table](bm-20260514-blueberry-aarch64-python-461b1d96313de02992d2-3.16.0a0-461b1d9-vs-base.md)
- [📈time plot](bm-20260514-blueberry-aarch64-python-461b1d96313de02992d2-3.16.0a0-461b1d9-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25911842889)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260514-ripley-x86_64-python-461b1d96313de02992d2-3.16.0a0-461b1d9.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260514-ripley-x86_64-python-461b1d96313de02992d2-3.16.0a0-461b1d9-vs-base-mem.svg)
- [📄table](bm-20260514-ripley-x86_64-python-461b1d96313de02992d2-3.16.0a0-461b1d9-vs-base.md)
- [📈time plot](bm-20260514-ripley-x86_64-python-461b1d96313de02992d2-3.16.0a0-461b1d9-vs-base.svg)

