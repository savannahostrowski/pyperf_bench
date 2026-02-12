# Results

- fork: python/46d5106cfa903329821c
- version: 3.15.0a6+
- config: JIT
- commit hash: [46d5106](https://github.com/python/cpython/commit/46d5106)
- commit date: 2026-02-12T00:15:33+00:00
- commit merge base: [cac0c98450c27dbb6e185ab1c05e1d51d34135d9](https://github.com/python/cpython/commit/cac0c98450c27dbb6e185ab1c05e1d51d34135d9)
- ref: 46d5106cfa903329821c

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21935898584)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260212-blueberry-aarch64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106.json)

### vs. base

- Geometric mean: 1.010x faster (HPT: reliability of 51.98%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260212-blueberry-aarch64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base-mem.svg)
- [📄table](bm-20260212-blueberry-aarch64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.md)
- [📈time plot](bm-20260212-blueberry-aarch64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21935898584)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260212-ripley-x86_64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106.json)

### vs. base

- Geometric mean: 1.039x faster (HPT: reliability of 98.72%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260212-ripley-x86_64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base-mem.svg)
- [📄table](bm-20260212-ripley-x86_64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.md)
- [📈time plot](bm-20260212-ripley-x86_64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21935898584)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260212-prometheus-amd64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106.json)

### vs. base

- Geometric mean: 1.161x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260212-prometheus-amd64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.md)
- [📈time plot](bm-20260212-prometheus-amd64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.svg)

