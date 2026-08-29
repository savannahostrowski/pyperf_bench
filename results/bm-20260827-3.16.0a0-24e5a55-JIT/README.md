# Results

- fork: python/24e5a55ccb0c5db68136
- version: 3.16.0a0
- config: JIT
- commit hash: [24e5a55](https://github.com/python/cpython/commit/24e5a55)
- commit date: 2026-08-27T21:11:05+01:00
- commit merge base: [45e5b1b0a97795e2ac82a306ce366efd55bd15b4](https://github.com/python/cpython/commit/45e5b1b0a97795e2ac82a306ce366efd55bd15b4)
- ref: 24e5a55ccb0c5db68136

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33209638110)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260827-blueberry-aarch64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55.json)

### vs. base

- Geometric mean: 1.024x slower (HPT: reliability of 97.26%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260827-blueberry-aarch64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55-vs-base-mem.svg)
- [📄table](bm-20260827-blueberry-aarch64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55-vs-base.md)
- [📈time plot](bm-20260827-blueberry-aarch64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33209638110)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260827-ripley-x86_64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55.json)

### vs. base

- Geometric mean: 1.076x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260827-ripley-x86_64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55-vs-base-mem.svg)
- [📄table](bm-20260827-ripley-x86_64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55-vs-base.md)
- [📈time plot](bm-20260827-ripley-x86_64-python-24e5a55ccb0c5db68136-3.16.0a0-24e5a55-vs-base.svg)

