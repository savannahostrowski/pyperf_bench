# Results

- fork: python/54607eec34b42d377a12
- version: 3.15.0a8+
- config: JIT
- commit hash: [54607ee](https://github.com/python/cpython/commit/54607ee)
- commit date: 2026-04-15T22:48:14+01:00
- commit merge base: [eb2f634b831ae235c2ebd4cbeab97a40e7d8724e](https://github.com/python/cpython/commit/eb2f634b831ae235c2ebd4cbeab97a40e7d8724e)
- ref: 54607eec34b42d377a12

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24503180715)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260415-blueberry-aarch64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee.json)

### vs. base

- Geometric mean: 1.002x faster (HPT: reliability of 82.74%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260415-blueberry-aarch64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base-mem.svg)
- [📄table](bm-20260415-blueberry-aarch64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.md)
- [📈time plot](bm-20260415-blueberry-aarch64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24503180715)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260415-ripley-x86_64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee.json)

### vs. base

- Geometric mean: 1.084x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260415-ripley-x86_64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base-mem.svg)
- [📄table](bm-20260415-ripley-x86_64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.md)
- [📈time plot](bm-20260415-ripley-x86_64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.svg)

