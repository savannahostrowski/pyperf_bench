# Results

- fork: python/776573c9f08f70ae9cb2
- version: 3.16.0a0
- config: JIT
- commit hash: [776573c](https://github.com/python/cpython/commit/776573c)
- commit date: 2026-05-26T21:16:16+00:00
- commit merge base: [8ab7b43a14bed4780febbd7586a41cfe459aa6d5](https://github.com/python/cpython/commit/8ab7b43a14bed4780febbd7586a41cfe459aa6d5)
- ref: 776573c9f08f70ae9cb2

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26505699375)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260526-blueberry-aarch64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c.json)

### vs. base

- Geometric mean: 1.009x slower (HPT: reliability of 85.16%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260526-blueberry-aarch64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base-mem.svg)
- [📄table](bm-20260526-blueberry-aarch64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.md)
- [📈time plot](bm-20260526-blueberry-aarch64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26505699375)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base-mem.svg)
- [📄table](bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.md)
- [📈time plot](bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.svg)

