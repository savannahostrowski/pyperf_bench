# Results

- fork: brandtbucher/jit_unwind
- version: 3.15.0a2+
- config: JIT
- commit hash: [8760c1b](https://github.com/brandtbucher/cpython/commit/8760c1b)
- commit date: 2025-11-28T10:51:13-08:00
- commit merge base: [9ac14288d7147dbbae08a8ffd8581e0f5e6fd706](https://github.com/python/cpython/commit/9ac14288d7147dbbae08a8ffd8581e0f5e6fd706)
- ref: jit_unwind

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19828008374)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2%2B-8760c1b.json)

### vs. base

- Geometric mean: 1.005x faster (HPT: reliability of 97.97%, 1.00x faster at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2%2B-8760c1b-vs-base-mem.svg)
- [📄table](bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2%2B-8760c1b-vs-base.md)
- [📈time plot](bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2%2B-8760c1b-vs-base.svg)

