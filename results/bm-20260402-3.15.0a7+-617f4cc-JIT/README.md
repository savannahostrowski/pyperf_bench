# Results

- fork: python/617f4cc1c2605b86b483
- version: 3.15.0a7+
- config: JIT
- commit hash: [617f4cc](https://github.com/python/cpython/commit/617f4cc)
- commit date: 2026-04-02T23:26:21+02:00
- commit merge base: [c1b20a6d96eadf1c49c511f1e480aff82b6477a4](https://github.com/python/cpython/commit/c1b20a6d96eadf1c49c511f1e480aff82b6477a4)
- ref: 617f4cc1c2605b86b483

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23941431367)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260402-blueberry-aarch64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 88.37%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260402-blueberry-aarch64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base-mem.svg)
- [📄table](bm-20260402-blueberry-aarch64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.md)
- [📈time plot](bm-20260402-blueberry-aarch64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23941431367)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260402-ripley-x86_64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc.json)

### vs. base

- Geometric mean: 1.063x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260402-ripley-x86_64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base-mem.svg)
- [📄table](bm-20260402-ripley-x86_64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.md)
- [📈time plot](bm-20260402-ripley-x86_64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23941431367)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260402-prometheus-amd64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc.json)

### vs. base

- Geometric mean: 1.214x faster (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260402-prometheus-amd64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.md)
- [📈time plot](bm-20260402-prometheus-amd64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.svg)

