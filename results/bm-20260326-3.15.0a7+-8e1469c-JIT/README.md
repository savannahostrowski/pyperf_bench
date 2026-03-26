# Results

- fork: python/8e1469c952fb9db57efd
- version: 3.15.0a7+
- config: JIT
- commit hash: [8e1469c](https://github.com/python/cpython/commit/8e1469c)
- commit date: 2026-03-26T00:11:20+01:00
- commit merge base: [9343518c6f413b2231b17c56065e5cf823aa0d2a](https://github.com/python/cpython/commit/9343518c6f413b2231b17c56065e5cf823aa0d2a)
- ref: 8e1469c952fb9db57efd

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23586984515)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260326-blueberry-aarch64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c.json)

### vs. base

- Geometric mean: 1.006x slower (HPT: reliability of 97.68%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260326-blueberry-aarch64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base-mem.svg)
- [📄table](bm-20260326-blueberry-aarch64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base.md)
- [📈time plot](bm-20260326-blueberry-aarch64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23586984515)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260326-ripley-x86_64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c.json)

### vs. base

- Geometric mean: 1.061x faster (HPT: reliability of 99.86%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260326-ripley-x86_64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base-mem.svg)
- [📄table](bm-20260326-ripley-x86_64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base.md)
- [📈time plot](bm-20260326-ripley-x86_64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23586984515)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260326-prometheus-amd64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c.json)

### vs. base

- Geometric mean: 1.209x faster (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260326-prometheus-amd64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base.md)
- [📈time plot](bm-20260326-prometheus-amd64-python-8e1469c952fb9db57efd-3.15.0a7%2B-8e1469c-vs-base.svg)

