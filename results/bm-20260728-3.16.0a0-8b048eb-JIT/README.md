# Results

- fork: python/8b048eb35eb7f83dbff8
- version: 3.16.0a0
- config: JIT
- commit hash: [8b048eb](https://github.com/python/cpython/commit/8b048eb)
- commit date: 2026-07-28T20:35:26+03:00
- commit merge base: [e3634bb44f7f1395dcb1b7ab3736811e9e2a4589](https://github.com/python/cpython/commit/e3634bb44f7f1395dcb1b7ab3736811e9e2a4589)
- ref: 8b048eb35eb7f83dbff8

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30447685831)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260728-blueberry-aarch64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb.json)

### vs. base

- Geometric mean: 1.033x slower (HPT: reliability of 99.97%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260728-blueberry-aarch64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb-vs-base-mem.svg)
- [📄table](bm-20260728-blueberry-aarch64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb-vs-base.md)
- [📈time plot](bm-20260728-blueberry-aarch64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30447685831)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260728-ripley-x86_64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb.json)

### vs. base

- Geometric mean: 1.067x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260728-ripley-x86_64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb-vs-base-mem.svg)
- [📄table](bm-20260728-ripley-x86_64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb-vs-base.md)
- [📈time plot](bm-20260728-ripley-x86_64-python-8b048eb35eb7f83dbff8-3.16.0a0-8b048eb-vs-base.svg)

