# Results

- fork: python/5c3decad66bdef425ea0
- version: 3.15.0a8+
- config: JIT
- commit hash: [5c3deca](https://github.com/python/cpython/commit/5c3deca)
- commit date: 2026-04-14T20:11:42+00:00
- commit merge base: [0012686d92fe51f426bcd6797e2f2a50ad4ac74f](https://github.com/python/cpython/commit/0012686d92fe51f426bcd6797e2f2a50ad4ac74f)
- ref: 5c3decad66bdef425ea0

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24447422550)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260414-blueberry-aarch64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca.json)

### vs. base

- Geometric mean: 1.006x faster (HPT: reliability of 69.13%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260414-blueberry-aarch64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base-mem.svg)
- [📄table](bm-20260414-blueberry-aarch64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.md)
- [📈time plot](bm-20260414-blueberry-aarch64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24447422550)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260414-ripley-x86_64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca.json)

### vs. base

- Geometric mean: 1.084x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260414-ripley-x86_64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base-mem.svg)
- [📄table](bm-20260414-ripley-x86_64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.md)
- [📈time plot](bm-20260414-ripley-x86_64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.svg)

