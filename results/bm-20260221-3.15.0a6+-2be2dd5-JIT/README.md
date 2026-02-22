# Results

- fork: python/2be2dd5fc219a5c252d7
- version: 3.15.0a6+
- config: JIT
- commit hash: [2be2dd5](https://github.com/python/cpython/commit/2be2dd5)
- commit date: 2026-02-21T22:06:59+01:00
- commit merge base: [fbd3b25e00fdfd5e0a30c64848624dc471987c30](https://github.com/python/cpython/commit/fbd3b25e00fdfd5e0a30c64848624dc471987c30)
- ref: 2be2dd5fc219a5c252d7

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22274262686)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260221-blueberry-aarch64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5.json)

### vs. base

- Geometric mean: 1.018x faster (HPT: reliability of 65.94%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260221-blueberry-aarch64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base-mem.svg)
- [📄table](bm-20260221-blueberry-aarch64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.md)
- [📈time plot](bm-20260221-blueberry-aarch64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22274262686)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260221-ripley-x86_64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5.json)

### vs. base

- Geometric mean: 1.040x faster (HPT: reliability of 89.11%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260221-ripley-x86_64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base-mem.svg)
- [📄table](bm-20260221-ripley-x86_64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.md)
- [📈time plot](bm-20260221-ripley-x86_64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22274262686)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260221-prometheus-amd64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5.json)

### vs. base

- Geometric mean: 1.179x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260221-prometheus-amd64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.md)
- [📈time plot](bm-20260221-prometheus-amd64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.svg)

