# Results

- fork: python/1ac9d138ae0563f2829b
- version: 3.15.0a6+
- config: JIT
- commit hash: [1ac9d13](https://github.com/python/cpython/commit/1ac9d13)
- commit date: 2026-02-25T00:53:01+00:00
- commit merge base: [4e45c9c309abb12c622334c7a419503d169af380](https://github.com/python/cpython/commit/4e45c9c309abb12c622334c7a419503d169af380)
- ref: 1ac9d138ae0563f2829b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22390460617)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260225-blueberry-aarch64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13.json)

### vs. base

- Geometric mean: 1.005x faster (HPT: reliability of 93.25%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260225-blueberry-aarch64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base-mem.svg)
- [📄table](bm-20260225-blueberry-aarch64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base.md)
- [📈time plot](bm-20260225-blueberry-aarch64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22390460617)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260225-ripley-x86_64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13.json)

### vs. base

- Geometric mean: 1.048x faster (HPT: reliability of 91.26%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260225-ripley-x86_64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base-mem.svg)
- [📄table](bm-20260225-ripley-x86_64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base.md)
- [📈time plot](bm-20260225-ripley-x86_64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22390460617)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260225-prometheus-amd64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13.json)

### vs. base

- Geometric mean: 1.174x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260225-prometheus-amd64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base.md)
- [📈time plot](bm-20260225-prometheus-amd64-python-1ac9d138ae0563f2829b-3.15.0a6%2B-1ac9d13-vs-base.svg)

