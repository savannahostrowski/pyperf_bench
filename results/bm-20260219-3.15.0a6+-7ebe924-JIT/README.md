# Results

- fork: python/7ebe9243950e9038dbbd
- version: 3.15.0a6+
- config: JIT
- commit hash: [7ebe924](https://github.com/python/cpython/commit/7ebe924)
- commit date: 2026-02-19T01:49:09+01:00
- commit merge base: [0bbdb4e897ae909af39cd93f7a25de89b724ab47](https://github.com/python/cpython/commit/0bbdb4e897ae909af39cd93f7a25de89b724ab47)
- ref: 7ebe9243950e9038dbbd

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22175822255)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260219-blueberry-aarch64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924.json)

### vs. base

- Geometric mean: 1.007x faster (HPT: reliability of 56.54%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260219-blueberry-aarch64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base-mem.svg)
- [📄table](bm-20260219-blueberry-aarch64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.md)
- [📈time plot](bm-20260219-blueberry-aarch64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22175822255)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260219-ripley-x86_64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924.json)

### vs. base

- Geometric mean: 1.038x faster (HPT: reliability of 98.22%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260219-ripley-x86_64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base-mem.svg)
- [📄table](bm-20260219-ripley-x86_64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.md)
- [📈time plot](bm-20260219-ripley-x86_64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22175822255)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260219-prometheus-amd64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924.json)

### vs. base

- Geometric mean: 1.162x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260219-prometheus-amd64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.md)
- [📈time plot](bm-20260219-prometheus-amd64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.svg)

