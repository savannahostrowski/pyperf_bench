# Results

- fork: python/bc31217fe432b5ede148
- version: 3.16.0a0
- config: JIT
- commit hash: [bc31217](https://github.com/python/cpython/commit/bc31217)
- commit date: 2026-08-12T20:16:47+00:00
- commit merge base: [5dfa606af39d1e21d130205ce0efbb7a10e124f7](https://github.com/python/cpython/commit/5dfa606af39d1e21d130205ce0efbb7a10e124f7)
- ref: bc31217fe432b5ede148

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31689962567)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260812-blueberry-aarch64-python-bc31217fe432b5ede148-3.16.0a0-bc31217.json)

### vs. base

- Geometric mean: 1.005x slower (HPT: reliability of 57.54%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260812-blueberry-aarch64-python-bc31217fe432b5ede148-3.16.0a0-bc31217-vs-base-mem.svg)
- [📄table](bm-20260812-blueberry-aarch64-python-bc31217fe432b5ede148-3.16.0a0-bc31217-vs-base.md)
- [📈time plot](bm-20260812-blueberry-aarch64-python-bc31217fe432b5ede148-3.16.0a0-bc31217-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31689962567)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260812-ripley-x86_64-python-bc31217fe432b5ede148-3.16.0a0-bc31217.json)

### vs. base

- Geometric mean: 1.072x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260812-ripley-x86_64-python-bc31217fe432b5ede148-3.16.0a0-bc31217-vs-base-mem.svg)
- [📄table](bm-20260812-ripley-x86_64-python-bc31217fe432b5ede148-3.16.0a0-bc31217-vs-base.md)
- [📈time plot](bm-20260812-ripley-x86_64-python-bc31217fe432b5ede148-3.16.0a0-bc31217-vs-base.svg)

