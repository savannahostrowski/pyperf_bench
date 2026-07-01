# Results

- fork: python/a5be0d81cb74fabe563b
- version: 3.16.0a0
- config: JIT
- commit hash: [a5be0d8](https://github.com/python/cpython/commit/a5be0d8)
- commit date: 2026-06-30T22:49:01+02:00
- commit merge base: [f37602ad7d4b78f55d935be66f6373320fe0aee5](https://github.com/python/cpython/commit/f37602ad7d4b78f55d935be66f6373320fe0aee5)
- ref: a5be0d81cb74fabe563b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28510769597)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260630-blueberry-aarch64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 78.56%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260630-blueberry-aarch64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8-vs-base-mem.svg)
- [📄table](bm-20260630-blueberry-aarch64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8-vs-base.md)
- [📈time plot](bm-20260630-blueberry-aarch64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28510769597)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260630-ripley-x86_64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260630-ripley-x86_64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8-vs-base-mem.svg)
- [📄table](bm-20260630-ripley-x86_64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8-vs-base.md)
- [📈time plot](bm-20260630-ripley-x86_64-python-a5be0d81cb74fabe563b-3.16.0a0-a5be0d8-vs-base.svg)

