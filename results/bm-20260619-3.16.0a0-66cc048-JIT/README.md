# Results

- fork: python/66cc04855100c3865bd0
- version: 3.16.0a0
- config: JIT
- commit hash: [66cc048](https://github.com/python/cpython/commit/66cc048)
- commit date: 2026-06-19T22:45:47+00:00
- commit merge base: [2e5843e13fcfd768a435d82e6182af403844432c](https://github.com/python/cpython/commit/2e5843e13fcfd768a435d82e6182af403844432c)
- ref: 66cc04855100c3865bd0

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27867868376)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260619-blueberry-aarch64-python-66cc04855100c3865bd0-3.16.0a0-66cc048.json)

### vs. base

- Geometric mean: 1.002x slower (HPT: reliability of 72.66%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260619-blueberry-aarch64-python-66cc04855100c3865bd0-3.16.0a0-66cc048-vs-base-mem.svg)
- [📄table](bm-20260619-blueberry-aarch64-python-66cc04855100c3865bd0-3.16.0a0-66cc048-vs-base.md)
- [📈time plot](bm-20260619-blueberry-aarch64-python-66cc04855100c3865bd0-3.16.0a0-66cc048-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27867868376)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260619-ripley-x86_64-python-66cc04855100c3865bd0-3.16.0a0-66cc048.json)

### vs. base

- Geometric mean: 1.073x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260619-ripley-x86_64-python-66cc04855100c3865bd0-3.16.0a0-66cc048-vs-base-mem.svg)
- [📄table](bm-20260619-ripley-x86_64-python-66cc04855100c3865bd0-3.16.0a0-66cc048-vs-base.md)
- [📈time plot](bm-20260619-ripley-x86_64-python-66cc04855100c3865bd0-3.16.0a0-66cc048-vs-base.svg)

