# Results

- fork: python/a1ec7467874207957519
- version: 3.15.0a6+
- config: JIT
- commit hash: [a1ec746](https://github.com/python/cpython/commit/a1ec746)
- commit date: 2026-02-28T22:26:47+00:00
- commit merge base: [50c2e23f69943a6f70d98c4d0bcf1ac37bcaf0d3](https://github.com/python/cpython/commit/50c2e23f69943a6f70d98c4d0bcf1ac37bcaf0d3)
- ref: a1ec7467874207957519

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22540197578)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260228-blueberry-aarch64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746.json)

### vs. base

- Geometric mean: 1.008x faster (HPT: reliability of 99.39%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260228-blueberry-aarch64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base-mem.svg)
- [📄table](bm-20260228-blueberry-aarch64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.md)
- [📈time plot](bm-20260228-blueberry-aarch64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22540197578)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260228-ripley-x86_64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746.json)

### vs. base

- Geometric mean: 1.044x faster (HPT: reliability of 94.27%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260228-ripley-x86_64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base-mem.svg)
- [📄table](bm-20260228-ripley-x86_64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.md)
- [📈time plot](bm-20260228-ripley-x86_64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22540197578)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260228-prometheus-amd64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746.json)

### vs. base

- Geometric mean: 1.191x faster (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260228-prometheus-amd64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.md)
- [📈time plot](bm-20260228-prometheus-amd64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.svg)

