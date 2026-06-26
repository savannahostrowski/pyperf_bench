# Results

- fork: python/55bc3126e0a09a8e940d
- version: 3.16.0a0
- config: JIT
- commit hash: [55bc312](https://github.com/python/cpython/commit/55bc312)
- commit date: 2026-06-25T18:06:07+00:00
- commit merge base: [bef570622263ecd58563f0474693c19c8545de73](https://github.com/python/cpython/commit/bef570622263ecd58563f0474693c19c8545de73)
- ref: 55bc3126e0a09a8e940d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28231488970)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260625-blueberry-aarch64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312.json)

### vs. base

- Geometric mean: 1.008x slower (HPT: reliability of 89.40%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260625-blueberry-aarch64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312-vs-base-mem.svg)
- [📄table](bm-20260625-blueberry-aarch64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312-vs-base.md)
- [📈time plot](bm-20260625-blueberry-aarch64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28231488970)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260625-ripley-x86_64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260625-ripley-x86_64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312-vs-base-mem.svg)
- [📄table](bm-20260625-ripley-x86_64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312-vs-base.md)
- [📈time plot](bm-20260625-ripley-x86_64-python-55bc3126e0a09a8e940d-3.16.0a0-55bc312-vs-base.svg)

