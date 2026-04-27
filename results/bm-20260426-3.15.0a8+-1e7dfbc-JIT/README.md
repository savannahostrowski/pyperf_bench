# Results

- fork: python/1e7dfbce930d6abd4e54
- version: 3.15.0a8+
- config: JIT
- commit hash: [1e7dfbc](https://github.com/python/cpython/commit/1e7dfbc)
- commit date: 2026-04-26T22:14:33+03:00
- commit merge base: [5d416324c56cd6f262fa123f41b97b48631bea79](https://github.com/python/cpython/commit/5d416324c56cd6f262fa123f41b97b48631bea79)
- ref: 1e7dfbce930d6abd4e54

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24988286958)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260426-blueberry-aarch64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc.json)

### vs. base

- Geometric mean: 1.029x faster (HPT: reliability of 98.97%, 1.00x faster at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260426-blueberry-aarch64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base-mem.svg)
- [📄table](bm-20260426-blueberry-aarch64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.md)
- [📈time plot](bm-20260426-blueberry-aarch64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24988286958)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260426-ripley-x86_64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc.json)

### vs. base

- Geometric mean: 1.082x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260426-ripley-x86_64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base-mem.svg)
- [📄table](bm-20260426-ripley-x86_64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.md)
- [📈time plot](bm-20260426-ripley-x86_64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.svg)

