# Results

- fork: python/432ddd99e2b06a75a4f4
- version: 3.15.0a5+
- config: JIT
- commit hash: [432ddd9](https://github.com/python/cpython/commit/432ddd9)
- commit date: 2026-02-09T00:10:43+02:00
- commit merge base: [3dd7a3c65ad4ac330ad44a519efa017484530e1a](https://github.com/python/cpython/commit/3dd7a3c65ad4ac330ad44a519efa017484530e1a)
- ref: 432ddd99e2b06a75a4f4

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21819420648)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260209-blueberry-aarch64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9.json)

### vs. base

- Geometric mean: 1.006x faster (HPT: reliability of 78.84%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260209-blueberry-aarch64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base-mem.svg)
- [📄table](bm-20260209-blueberry-aarch64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.md)
- [📈time plot](bm-20260209-blueberry-aarch64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21819420648)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260209-ripley-x86_64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9.json)

### vs. base

- Geometric mean: 1.042x faster (HPT: reliability of 98.64%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260209-ripley-x86_64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base-mem.svg)
- [📄table](bm-20260209-ripley-x86_64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.md)
- [📈time plot](bm-20260209-ripley-x86_64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21819420648)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260209-prometheus-amd64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9.json)

### vs. base

- Geometric mean: 1.151x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260209-prometheus-amd64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.md)
- [📈time plot](bm-20260209-prometheus-amd64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.svg)

