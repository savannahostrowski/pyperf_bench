# Results

- fork: python/a8d74c062fe3c5cb2962
- version: 3.16.0a0
- config: JIT
- commit hash: [a8d74c0](https://github.com/python/cpython/commit/a8d74c0)
- commit date: 2026-06-17T16:49:23-04:00
- commit merge base: [eff805b7a7a9678639bbcebe804864406cc4eab2](https://github.com/python/cpython/commit/eff805b7a7a9678639bbcebe804864406cc4eab2)
- ref: a8d74c062fe3c5cb2962

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27753628678)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260617-blueberry-aarch64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0.json)

### vs. base

- Geometric mean: 1.013x slower (HPT: reliability of 86.11%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260617-blueberry-aarch64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0-vs-base-mem.svg)
- [📄table](bm-20260617-blueberry-aarch64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0-vs-base.md)
- [📈time plot](bm-20260617-blueberry-aarch64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27753628678)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260617-ripley-x86_64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0.json)

### vs. base

- Geometric mean: 1.073x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260617-ripley-x86_64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0-vs-base-mem.svg)
- [📄table](bm-20260617-ripley-x86_64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0-vs-base.md)
- [📈time plot](bm-20260617-ripley-x86_64-python-a8d74c062fe3c5cb2962-3.16.0a0-a8d74c0-vs-base.svg)

