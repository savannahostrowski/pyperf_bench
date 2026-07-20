# Results

- fork: python/a1d580430c81c298d267
- version: 3.16.0a0
- config: JIT
- commit hash: [a1d5804](https://github.com/python/cpython/commit/a1d5804)
- commit date: 2026-07-18T21:46:16+02:00
- commit merge base: [a85a674b57b7f12e77ac4bef2398c09f36fec75a](https://github.com/python/cpython/commit/a85a674b57b7f12e77ac4bef2398c09f36fec75a)
- ref: a1d580430c81c298d267

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29683653228)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260718-blueberry-aarch64-python-a1d580430c81c298d267-3.16.0a0-a1d5804.json)

### vs. base

- Geometric mean: 1.001x slower (HPT: reliability of 72.77%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260718-blueberry-aarch64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base-mem.svg)
- [📄table](bm-20260718-blueberry-aarch64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.md)
- [📈time plot](bm-20260718-blueberry-aarch64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29683653228)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260718-ripley-x86_64-python-a1d580430c81c298d267-3.16.0a0-a1d5804.json)

### vs. base

- Geometric mean: 1.065x faster (HPT: reliability of 99.97%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260718-ripley-x86_64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base-mem.svg)
- [📄table](bm-20260718-ripley-x86_64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.md)
- [📈time plot](bm-20260718-ripley-x86_64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.svg)

