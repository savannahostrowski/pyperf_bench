# Results

- fork: python/09e8c382312b145b710d
- version: 3.15.0a6+
- config: JIT
- commit hash: [09e8c38](https://github.com/python/cpython/commit/09e8c38)
- commit date: 2026-02-28T02:24:06+00:00
- commit merge base: [2e2109d2248d9b59d1085d428831457c12cd32c0](https://github.com/python/cpython/commit/2e2109d2248d9b59d1085d428831457c12cd32c0)
- ref: 09e8c382312b145b710d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22517769881)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260228-blueberry-aarch64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38.json)

### vs. base

- Geometric mean: 1.013x faster (HPT: reliability of 51.47%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260228-blueberry-aarch64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base-mem.svg)
- [📄table](bm-20260228-blueberry-aarch64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.md)
- [📈time plot](bm-20260228-blueberry-aarch64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22517769881)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260228-ripley-x86_64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38.json)

### vs. base

- Geometric mean: 1.050x faster (HPT: reliability of 98.08%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260228-ripley-x86_64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base-mem.svg)
- [📄table](bm-20260228-ripley-x86_64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.md)
- [📈time plot](bm-20260228-ripley-x86_64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22517769881)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260228-prometheus-amd64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38.json)

### vs. base

- Geometric mean: 1.181x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260228-prometheus-amd64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.md)
- [📈time plot](bm-20260228-prometheus-amd64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.svg)

