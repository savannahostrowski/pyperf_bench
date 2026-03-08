# Results

- fork: python/149c4657507d17f78dd0
- version: 3.15.0a6+
- config: JIT
- commit hash: [149c465](https://github.com/python/cpython/commit/149c465)
- commit date: 2026-03-07T16:53:13+02:00
- commit merge base: [2cf6b2caade94e75f10363df6f432a3e6515be6c](https://github.com/python/cpython/commit/2cf6b2caade94e75f10363df6f432a3e6515be6c)
- ref: 149c4657507d17f78dd0

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22818029078)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260307-blueberry-aarch64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465.json)

### vs. base

- Geometric mean: 1.017x faster (HPT: reliability of 57.67%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260307-blueberry-aarch64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base-mem.svg)
- [📄table](bm-20260307-blueberry-aarch64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base.md)
- [📈time plot](bm-20260307-blueberry-aarch64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22818029078)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260307-ripley-x86_64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465.json)

### vs. base

- Geometric mean: 1.044x faster (HPT: reliability of 99.79%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260307-ripley-x86_64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base-mem.svg)
- [📄table](bm-20260307-ripley-x86_64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base.md)
- [📈time plot](bm-20260307-ripley-x86_64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22818029078)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260307-prometheus-amd64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465.json)

### vs. base

- Geometric mean: 1.157x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260307-prometheus-amd64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base.md)
- [📈time plot](bm-20260307-prometheus-amd64-python-149c4657507d17f78dd0-3.15.0a6%2B-149c465-vs-base.svg)

