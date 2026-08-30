# Results

- fork: python/41b3f0af266b408438ca
- version: 3.16.0a0
- config: JIT
- commit hash: [41b3f0a](https://github.com/python/cpython/commit/41b3f0a)
- commit date: 2026-08-29T22:40:37+01:00
- commit merge base: [c8ca336e6b321a4ff680ea426cc8a84bfb599bd2](https://github.com/python/cpython/commit/c8ca336e6b321a4ff680ea426cc8a84bfb599bd2)
- ref: 41b3f0af266b408438ca

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33316572747)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260829-blueberry-aarch64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a.json)

### vs. base

- Geometric mean: 1.014x slower (HPT: reliability of 96.11%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260829-blueberry-aarch64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base-mem.svg)
- [📄table](bm-20260829-blueberry-aarch64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.md)
- [📈time plot](bm-20260829-blueberry-aarch64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33316572747)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260829-ripley-x86_64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260829-ripley-x86_64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base-mem.svg)
- [📄table](bm-20260829-ripley-x86_64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.md)
- [📈time plot](bm-20260829-ripley-x86_64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.svg)

