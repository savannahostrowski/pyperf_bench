# Results

- fork: python/43fdb7037e76c18d9545
- version: 3.15.0a6+
- config: JIT
- commit hash: [43fdb70](https://github.com/python/cpython/commit/43fdb70)
- commit date: 2026-02-26T06:21:05+08:00
- commit merge base: [7eb00ad23cf3795c42e9ac0a268387f8d6026ecd](https://github.com/python/cpython/commit/7eb00ad23cf3795c42e9ac0a268387f8d6026ecd)
- ref: 43fdb7037e76c18d9545

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22435781251)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260226-blueberry-aarch64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70.json)

### vs. base

- Geometric mean: 1.015x faster (HPT: reliability of 64.76%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260226-blueberry-aarch64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base-mem.svg)
- [📄table](bm-20260226-blueberry-aarch64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base.md)
- [📈time plot](bm-20260226-blueberry-aarch64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22435781251)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260226-ripley-x86_64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70.json)

### vs. base

- Geometric mean: 1.046x faster (HPT: reliability of 99.71%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260226-ripley-x86_64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base-mem.svg)
- [📄table](bm-20260226-ripley-x86_64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base.md)
- [📈time plot](bm-20260226-ripley-x86_64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22435781251)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260226-prometheus-amd64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70.json)

### vs. base

- Geometric mean: 1.164x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260226-prometheus-amd64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base.md)
- [📈time plot](bm-20260226-prometheus-amd64-python-43fdb7037e76c18d9545-3.15.0a6%2B-43fdb70-vs-base.svg)

