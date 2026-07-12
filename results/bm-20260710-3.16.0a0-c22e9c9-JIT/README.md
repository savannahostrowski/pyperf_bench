# Results

- fork: python/c22e9c9daef4d97a3fdf
- version: 3.16.0a0
- config: JIT
- commit hash: [c22e9c9](https://github.com/python/cpython/commit/c22e9c9)
- commit date: 2026-07-10T11:40:12-07:00
- commit merge base: [0293eacc248421de3f87ba13ead53e7184a81697](https://github.com/python/cpython/commit/0293eacc248421de3f87ba13ead53e7184a81697)
- ref: c22e9c9daef4d97a3fdf

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29149111430)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260710-blueberry-aarch64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9.json)

### vs. base

- Geometric mean: 1.000x slower (HPT: reliability of 73.51%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260710-blueberry-aarch64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9-vs-base-mem.svg)
- [📄table](bm-20260710-blueberry-aarch64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9-vs-base.md)
- [📈time plot](bm-20260710-blueberry-aarch64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29149111430)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260710-ripley-x86_64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9.json)

### vs. base

- Geometric mean: 1.076x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260710-ripley-x86_64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9-vs-base-mem.svg)
- [📄table](bm-20260710-ripley-x86_64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9-vs-base.md)
- [📈time plot](bm-20260710-ripley-x86_64-python-c22e9c9daef4d97a3fdf-3.16.0a0-c22e9c9-vs-base.svg)

