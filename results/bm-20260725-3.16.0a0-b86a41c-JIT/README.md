# Results

- fork: python/b86a41cbf631c959d274
- version: 3.16.0a0
- config: JIT
- commit hash: [b86a41c](https://github.com/python/cpython/commit/b86a41c)
- commit date: 2026-07-25T16:42:44+02:00
- commit merge base: [587d0d11a630a893baca945383de71b07fbc854f](https://github.com/python/cpython/commit/587d0d11a630a893baca945383de71b07fbc854f)
- ref: b86a41cbf631c959d274

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30198864293)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260725-blueberry-aarch64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 68.36%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260725-blueberry-aarch64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base-mem.svg)
- [📄table](bm-20260725-blueberry-aarch64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.md)
- [📈time plot](bm-20260725-blueberry-aarch64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30198864293)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260725-ripley-x86_64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c.json)

### vs. base

- Geometric mean: 1.068x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260725-ripley-x86_64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base-mem.svg)
- [📄table](bm-20260725-ripley-x86_64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.md)
- [📈time plot](bm-20260725-ripley-x86_64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.svg)

