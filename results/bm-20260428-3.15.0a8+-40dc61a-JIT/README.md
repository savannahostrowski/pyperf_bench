# Results

- fork: python/40dc61a0e0672810c393
- version: 3.15.0a8+
- config: JIT
- commit hash: [40dc61a](https://github.com/python/cpython/commit/40dc61a)
- commit date: 2026-04-28T21:45:38+03:00
- commit merge base: [933e2dd6cfec50ca45fd75f47ce5190c58ce28be](https://github.com/python/cpython/commit/933e2dd6cfec50ca45fd75f47ce5190c58ce28be)
- ref: 40dc61a0e0672810c393

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25102050613)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260428-blueberry-aarch64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a.json)

### vs. base

- Geometric mean: 1.008x faster (HPT: reliability of 53.36%, 1.00x faster at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260428-blueberry-aarch64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base-mem.svg)
- [📄table](bm-20260428-blueberry-aarch64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.md)
- [📈time plot](bm-20260428-blueberry-aarch64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25102050613)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260428-ripley-x86_64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a.json)

### vs. base

- Geometric mean: 1.081x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260428-ripley-x86_64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base-mem.svg)
- [📄table](bm-20260428-ripley-x86_64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.md)
- [📈time plot](bm-20260428-ripley-x86_64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.svg)

