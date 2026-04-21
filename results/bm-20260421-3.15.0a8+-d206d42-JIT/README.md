# Results

- fork: python/d206d42834b2a34aee11
- version: 3.15.0a8+
- config: JIT
- commit hash: [d206d42](https://github.com/python/cpython/commit/d206d42)
- commit date: 2026-04-21T07:04:50+08:00
- commit merge base: [f6ed7c0acbd9234226cab5cca12f9d312809103e](https://github.com/python/cpython/commit/f6ed7c0acbd9234226cab5cca12f9d312809103e)
- ref: d206d42834b2a34aee11

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24715261557)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260421-blueberry-aarch64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42.json)

### vs. base

- Geometric mean: 1.001x slower (HPT: reliability of 93.01%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260421-blueberry-aarch64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base-mem.svg)
- [📄table](bm-20260421-blueberry-aarch64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.md)
- [📈time plot](bm-20260421-blueberry-aarch64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24715261557)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42.json)

### vs. base

- Geometric mean: 1.082x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base-mem.svg)
- [📄table](bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.md)
- [📈time plot](bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.svg)

