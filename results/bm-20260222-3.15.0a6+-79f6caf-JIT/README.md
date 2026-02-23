# Results

- fork: python/79f6caf8f1f52788e15c
- version: 3.15.0a6+
- config: JIT
- commit hash: [79f6caf](https://github.com/python/cpython/commit/79f6caf)
- commit date: 2026-02-22T19:59:40-06:00
- commit merge base: [fd01372d4e509b2cbec708adcf7cdf6f7c1c1298](https://github.com/python/cpython/commit/fd01372d4e509b2cbec708adcf7cdf6f7c1c1298)
- ref: 79f6caf8f1f52788e15c

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22300005714)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260222-blueberry-aarch64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf.json)

### vs. base

- Geometric mean: 1.020x faster (HPT: reliability of 56.66%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260222-blueberry-aarch64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base-mem.svg)
- [📄table](bm-20260222-blueberry-aarch64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.md)
- [📈time plot](bm-20260222-blueberry-aarch64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22300005714)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260222-ripley-x86_64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf.json)

### vs. base

- Geometric mean: 1.045x faster (HPT: reliability of 99.81%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260222-ripley-x86_64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base-mem.svg)
- [📄table](bm-20260222-ripley-x86_64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.md)
- [📈time plot](bm-20260222-ripley-x86_64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22300005714)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260222-prometheus-amd64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf.json)

### vs. base

- Geometric mean: 1.171x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260222-prometheus-amd64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.md)
- [📈time plot](bm-20260222-prometheus-amd64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.svg)

