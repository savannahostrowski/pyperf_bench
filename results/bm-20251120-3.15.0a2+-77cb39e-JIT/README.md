# Results

- fork: python/77cb39e0c7ef606ef68a
- version: 3.15.0a2+
- config: JIT
- commit hash: [77cb39e](https://github.com/python/cpython/commit/77cb39e)
- commit date: 2025-11-20T18:41:58+00:00
- commit merge base: [b3383085f9c63cf4034bec13c5b20140757bebc9](https://github.com/python/cpython/commit/b3383085f9c63cf4034bec13c5b20140757bebc9)
- ref: 77cb39e0c7ef606ef68a

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19555416583)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e.json)

### vs. base

- Geometric mean: 1.066x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base-mem.svg)
- [📄table](bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.md)
- [📈time plot](bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19555416583)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251120-ripley-x86_64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e.json)

### vs. base

- Geometric mean: 1.010x faster (HPT: reliability of 87.92%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 docutils, subparsers
- [🧠memory plot](bm-20251120-ripley-x86_64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base-mem.svg)
- [📄table](bm-20251120-ripley-x86_64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.md)
- [📈time plot](bm-20251120-ripley-x86_64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.svg)

