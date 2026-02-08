# Results

- fork: python/d73634935cb9ce00a57d
- version: 3.15.0a5+
- config: JIT
- commit hash: [d736349](https://github.com/python/cpython/commit/d736349)
- commit date: 2026-02-07T23:35:02-08:00
- commit merge base: [e682141c495c2e52368c4341ae54eea041070356](https://github.com/python/cpython/commit/e682141c495c2e52368c4341ae54eea041070356)
- ref: d73634935cb9ce00a57d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21795657005)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260207-blueberry-aarch64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349.json)

### vs. base

- Geometric mean: 1.012x faster (HPT: reliability of 71.15%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260207-blueberry-aarch64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base-mem.svg)
- [📄table](bm-20260207-blueberry-aarch64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.md)
- [📈time plot](bm-20260207-blueberry-aarch64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21795657005)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260207-ripley-x86_64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349.json)

### vs. base

- Geometric mean: 1.036x faster (HPT: reliability of 97.00%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260207-ripley-x86_64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base-mem.svg)
- [📄table](bm-20260207-ripley-x86_64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.md)
- [📈time plot](bm-20260207-ripley-x86_64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21795657005)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260207-prometheus-amd64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349.json)

### vs. base

- Geometric mean: 1.143x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260207-prometheus-amd64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.md)
- [📈time plot](bm-20260207-prometheus-amd64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.svg)

