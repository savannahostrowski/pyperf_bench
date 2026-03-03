# Results

- fork: python/6908372fb8182be5849a
- version: 3.15.0a6+
- config: JIT
- commit hash: [6908372](https://github.com/python/cpython/commit/6908372)
- commit date: 2026-03-03T09:58:38+09:00
- commit merge base: [ea90b032a016122e7871e91c5210f3b4e68768b4](https://github.com/python/cpython/commit/ea90b032a016122e7871e91c5210f3b4e68768b4)
- ref: 6908372fb8182be5849a

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22616329189)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260303-blueberry-aarch64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372.json)

### vs. base

- Geometric mean: 1.002x faster (HPT: reliability of 89.40%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260303-blueberry-aarch64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base-mem.svg)
- [📄table](bm-20260303-blueberry-aarch64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.md)
- [📈time plot](bm-20260303-blueberry-aarch64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22616329189)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260303-ripley-x86_64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372.json)

### vs. base

- Geometric mean: 1.059x faster (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260303-ripley-x86_64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base-mem.svg)
- [📄table](bm-20260303-ripley-x86_64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.md)
- [📈time plot](bm-20260303-ripley-x86_64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22616329189)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260303-prometheus-amd64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372.json)

### vs. base

- Geometric mean: 1.161x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260303-prometheus-amd64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.md)
- [📈time plot](bm-20260303-prometheus-amd64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.svg)

