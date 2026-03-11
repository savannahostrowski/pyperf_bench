# Results

- fork: python/ebb150e76ab4988fdcd5
- version: 3.15.0a7+
- config: JIT
- commit hash: [ebb150e](https://github.com/python/cpython/commit/ebb150e)
- commit date: 2026-03-11T08:43:27+08:00
- commit merge base: [5197ecb5e4df30ba0f6792d8bc0e36846154f58a](https://github.com/python/cpython/commit/5197ecb5e4df30ba0f6792d8bc0e36846154f58a)
- ref: ebb150e76ab4988fdcd5

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22945406605)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260311-blueberry-aarch64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e.json)

### vs. base

- Geometric mean: 1.016x faster (HPT: reliability of 74.54%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260311-blueberry-aarch64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base-mem.svg)
- [📄table](bm-20260311-blueberry-aarch64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base.md)
- [📈time plot](bm-20260311-blueberry-aarch64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22945406605)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e.json)

### vs. base

- Geometric mean: 1.049x faster (HPT: reliability of 99.91%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base-mem.svg)
- [📄table](bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base.md)
- [📈time plot](bm-20260311-ripley-x86_64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22945406605)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260311-prometheus-amd64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e.json)

### vs. base

- Geometric mean: 1.160x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260311-prometheus-amd64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base.md)
- [📈time plot](bm-20260311-prometheus-amd64-python-ebb150e76ab4988fdcd5-3.15.0a7%2B-ebb150e-vs-base.svg)

