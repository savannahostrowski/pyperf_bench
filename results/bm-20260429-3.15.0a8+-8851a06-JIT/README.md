# Results

- fork: python/8851a06e6e7ff23d91e5
- version: 3.15.0a8+
- config: JIT
- commit hash: [8851a06](https://github.com/python/cpython/commit/8851a06)
- commit date: 2026-04-29T18:33:05+03:00
- commit merge base: [025a82f138b9a59c2cb842aaa8835206f0879b20](https://github.com/python/cpython/commit/025a82f138b9a59c2cb842aaa8835206f0879b20)
- ref: 8851a06e6e7ff23d91e5

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25158828706)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260429-blueberry-aarch64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06.json)

### vs. base

- Geometric mean: 1.004x faster (HPT: reliability of 51.03%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260429-blueberry-aarch64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base-mem.svg)
- [📄table](bm-20260429-blueberry-aarch64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.md)
- [📈time plot](bm-20260429-blueberry-aarch64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25158828706)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06.json)

### vs. base

- Geometric mean: 1.091x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base-mem.svg)
- [📄table](bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.md)
- [📈time plot](bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.svg)

