# Results

- fork: python/40095d526bd8ddbabee0
- version: 3.15.0a7+
- config: JIT
- commit hash: [40095d5](https://github.com/python/cpython/commit/40095d5)
- commit date: 2026-03-15T18:54:20-05:00
- commit merge base: [83edae33a5591c52fa45df38da2616af470f290a](https://github.com/python/cpython/commit/83edae33a5591c52fa45df38da2616af470f290a)
- ref: 40095d526bd8ddbabee0

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23136839714)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260315-blueberry-aarch64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5.json)

### vs. base

- Geometric mean: 1.020x faster (HPT: reliability of 61.51%, 1.00x faster at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260315-blueberry-aarch64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base-mem.svg)
- [📄table](bm-20260315-blueberry-aarch64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base.md)
- [📈time plot](bm-20260315-blueberry-aarch64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23136839714)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260315-ripley-x86_64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5.json)

### vs. base

- Geometric mean: 1.065x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260315-ripley-x86_64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base-mem.svg)
- [📄table](bm-20260315-ripley-x86_64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base.md)
- [📈time plot](bm-20260315-ripley-x86_64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23136839714)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260315-prometheus-amd64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5.json)

### vs. base

- Geometric mean: 1.189x faster (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260315-prometheus-amd64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base.md)
- [📈time plot](bm-20260315-prometheus-amd64-python-40095d526bd8ddbabee0-3.15.0a7%2B-40095d5-vs-base.svg)

