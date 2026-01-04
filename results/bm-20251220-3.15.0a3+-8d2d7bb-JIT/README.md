# Results

- fork: python/8d2d7bb2e754f8649a68
- version: 3.15.0a3+
- config: JIT
- commit hash: [8d2d7bb](https://github.com/python/cpython/commit/8d2d7bb)
- commit date: 2025-12-20T23:42:06+00:00
- commit merge base: [2b4feee648b7af0ccca8dee167fdd21cfb0bd23a](https://github.com/python/cpython/commit/2b4feee648b7af0ccca8dee167fdd21cfb0bd23a)
- ref: 8d2d7bb2e754f8649a68

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20401998634)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251220-blueberry-aarch64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb.json)

### vs. base

- Geometric mean: 1.014x slower (HPT: reliability of 99.05%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251220-blueberry-aarch64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base-mem.svg)
- [📄table](bm-20251220-blueberry-aarch64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.md)
- [📈time plot](bm-20251220-blueberry-aarch64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20401998634)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251220-ripley-x86_64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb.json)

### vs. base

- Geometric mean: 1.035x faster (HPT: reliability of 85.95%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251220-ripley-x86_64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base-mem.svg)
- [📄table](bm-20251220-ripley-x86_64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.md)
- [📈time plot](bm-20251220-ripley-x86_64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.svg)

