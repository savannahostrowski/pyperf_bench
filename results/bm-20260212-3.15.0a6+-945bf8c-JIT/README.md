# Results

- fork: python/945bf8ce1bf7ee388175
- version: 3.15.0a6+
- config: JIT
- commit hash: [945bf8c](https://github.com/python/cpython/commit/945bf8c)
- commit date: 2026-02-12T18:15:23-05:00
- commit merge base: [66da7bf6fe7b81e3ecc9c0a25bd47d4616c8d1a6](https://github.com/python/cpython/commit/66da7bf6fe7b81e3ecc9c0a25bd47d4616c8d1a6)
- ref: 945bf8ce1bf7ee388175

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21981455816)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260212-blueberry-aarch64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c.json)

### vs. base

- Geometric mean: 1.015x faster (HPT: reliability of 72.87%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260212-blueberry-aarch64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base-mem.svg)
- [📄table](bm-20260212-blueberry-aarch64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.md)
- [📈time plot](bm-20260212-blueberry-aarch64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21981455816)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260212-ripley-x86_64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c.json)

### vs. base

- Geometric mean: 1.026x faster (HPT: reliability of 83.24%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260212-ripley-x86_64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base-mem.svg)
- [📄table](bm-20260212-ripley-x86_64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.md)
- [📈time plot](bm-20260212-ripley-x86_64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21981455816)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260212-prometheus-amd64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c.json)

### vs. base

- Geometric mean: 1.151x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260212-prometheus-amd64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.md)
- [📈time plot](bm-20260212-prometheus-amd64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.svg)

