# Results

- fork: python/227b9d326ec7eba35942
- version: 3.15.0a2+
- config: JIT
- commit hash: [227b9d3](https://github.com/python/cpython/commit/227b9d3)
- commit date: 2025-11-22T21:59:14+00:00
- commit merge base: [425fd85ca360a39a1a3fb16f09c448cb93ff794a](https://github.com/python/cpython/commit/425fd85ca360a39a1a3fb16f09c448cb93ff794a)
- ref: 227b9d326ec7eba35942

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19603185148)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251122-blueberry-aarch64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3.json)

### vs. base

- Geometric mean: 1.023x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251122-blueberry-aarch64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base-mem.svg)
- [📄table](bm-20251122-blueberry-aarch64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.md)
- [📈time plot](bm-20251122-blueberry-aarch64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19603185148)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3.json)

### vs. base

- Geometric mean: 1.062x faster (HPT: reliability of 55.72%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base-mem.svg)
- [📄table](bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.md)
- [📈time plot](bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.svg)

