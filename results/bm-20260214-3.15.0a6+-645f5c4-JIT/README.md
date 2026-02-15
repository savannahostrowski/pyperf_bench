# Results

- fork: python/645f5c4a737b3eab29d0
- version: 3.15.0a6+
- config: JIT
- commit hash: [645f5c4](https://github.com/python/cpython/commit/645f5c4)
- commit date: 2026-02-14T19:20:33+00:00
- commit merge base: [caac966b0051578b60b4b07fe341174f25d9f8b1](https://github.com/python/cpython/commit/caac966b0051578b60b4b07fe341174f25d9f8b1)
- ref: 645f5c4a737b3eab29d0

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22033082866)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260214-blueberry-aarch64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4.json)

### vs. base

- Geometric mean: 1.004x faster (HPT: reliability of 67.45%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260214-blueberry-aarch64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base-mem.svg)
- [📄table](bm-20260214-blueberry-aarch64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base.md)
- [📈time plot](bm-20260214-blueberry-aarch64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22033082866)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260214-ripley-x86_64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4.json)

### vs. base

- Geometric mean: 1.037x faster (HPT: reliability of 86.94%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260214-ripley-x86_64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base-mem.svg)
- [📄table](bm-20260214-ripley-x86_64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base.md)
- [📈time plot](bm-20260214-ripley-x86_64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22033082866)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260214-prometheus-amd64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4.json)

### vs. base

- Geometric mean: 1.141x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260214-prometheus-amd64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base.md)
- [📈time plot](bm-20260214-prometheus-amd64-python-645f5c4a737b3eab29d0-3.15.0a6%2B-645f5c4-vs-base.svg)

