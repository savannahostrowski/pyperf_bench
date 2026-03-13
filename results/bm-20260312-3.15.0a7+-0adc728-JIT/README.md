# Results

- fork: python/0adc7289c3ab097b5608
- version: 3.15.0a7+
- config: JIT
- commit hash: [0adc728](https://github.com/python/cpython/commit/0adc728)
- commit date: 2026-03-12T21:53:29-04:00
- commit merge base: [08a018ebe0d673e9c352f790d2e4604d69604188](https://github.com/python/cpython/commit/08a018ebe0d673e9c352f790d2e4604d69604188)
- ref: 0adc7289c3ab097b5608

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23044233488)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260312-blueberry-aarch64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728.json)

### vs. base

- Geometric mean: 1.020x faster (HPT: reliability of 65.82%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260312-blueberry-aarch64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base-mem.svg)
- [📄table](bm-20260312-blueberry-aarch64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base.md)
- [📈time plot](bm-20260312-blueberry-aarch64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23044233488)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260312-ripley-x86_64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728.json)

### vs. base

- Geometric mean: 1.055x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260312-ripley-x86_64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base-mem.svg)
- [📄table](bm-20260312-ripley-x86_64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base.md)
- [📈time plot](bm-20260312-ripley-x86_64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23044233488)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260312-prometheus-amd64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728.json)

### vs. base

- Geometric mean: 1.174x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260312-prometheus-amd64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base.md)
- [📈time plot](bm-20260312-prometheus-amd64-python-0adc7289c3ab097b5608-3.15.0a7%2B-0adc728-vs-base.svg)

