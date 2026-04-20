# Results

- fork: python/db3e990b98fd12fee1bf
- version: 3.15.0a8+
- config: JIT
- commit hash: [db3e990](https://github.com/python/cpython/commit/db3e990)
- commit date: 2026-04-17T16:52:16+00:00
- commit merge base: [446edda20919447fdc8b5a43f2f2ae686df82e6a](https://github.com/python/cpython/commit/446edda20919447fdc8b5a43f2f2ae686df82e6a)
- ref: db3e990b98fd12fee1bf

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24601657946)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990.json)

### vs. base

- Geometric mean: 1.010x faster (HPT: reliability of 71.96%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base-mem.svg)
- [📄table](bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.md)
- [📈time plot](bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24601657946)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990.json)

### vs. base

- Geometric mean: 1.080x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base-mem.svg)
- [📄table](bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.md)
- [📈time plot](bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.svg)

