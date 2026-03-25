# Results

- fork: python/60093096ba62110151d8
- version: 3.15.0a7+
- config: JIT
- commit hash: [6009309](https://github.com/python/cpython/commit/6009309)
- commit date: 2026-03-24T14:29:37-04:00
- commit merge base: [535b09c19d2147e52f0257f2a7dbd78e617f8cce](https://github.com/python/cpython/commit/535b09c19d2147e52f0257f2a7dbd78e617f8cce)
- ref: 60093096ba62110151d8

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23533838052)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260324-blueberry-aarch64-python-60093096ba62110151d8-3.15.0a7%2B-6009309.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 84.00%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260324-blueberry-aarch64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base-mem.svg)
- [📄table](bm-20260324-blueberry-aarch64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base.md)
- [📈time plot](bm-20260324-blueberry-aarch64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23533838052)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260324-ripley-x86_64-python-60093096ba62110151d8-3.15.0a7%2B-6009309.json)

### vs. base

- Geometric mean: 1.064x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260324-ripley-x86_64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base-mem.svg)
- [📄table](bm-20260324-ripley-x86_64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base.md)
- [📈time plot](bm-20260324-ripley-x86_64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23533838052)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260324-prometheus-amd64-python-60093096ba62110151d8-3.15.0a7%2B-6009309.json)

### vs. base

- Geometric mean: 1.224x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260324-prometheus-amd64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base.md)
- [📈time plot](bm-20260324-prometheus-amd64-python-60093096ba62110151d8-3.15.0a7%2B-6009309-vs-base.svg)

