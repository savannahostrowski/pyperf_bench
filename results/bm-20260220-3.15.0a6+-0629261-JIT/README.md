# Results

- fork: python/06292614ff7cef0ba28d
- version: 3.15.0a6+
- config: JIT
- commit hash: [0629261](https://github.com/python/cpython/commit/0629261)
- commit date: 2026-02-20T19:25:45-05:00
- commit merge base: [70da972f97ec799dc7d7ab069fe195455f2f81b2](https://github.com/python/cpython/commit/70da972f97ec799dc7d7ab069fe195455f2f81b2)
- ref: 06292614ff7cef0ba28d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22254178602)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261.json)

### vs. base

- Geometric mean: 1.014x faster (HPT: reliability of 71.91%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base-mem.svg)
- [📄table](bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)
- [📈time plot](bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22254178602)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261.json)

### vs. base

- Geometric mean: 1.052x faster (HPT: reliability of 99.64%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base-mem.svg)
- [📄table](bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)
- [📈time plot](bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22254178602)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260220-prometheus-amd64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261.json)

### vs. base

- Geometric mean: 1.169x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260220-prometheus-amd64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)
- [📈time plot](bm-20260220-prometheus-amd64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg)

