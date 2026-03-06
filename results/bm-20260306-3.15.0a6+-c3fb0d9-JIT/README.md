# Results

- fork: python/c3fb0d9d96902774c08b
- version: 3.15.0a6+
- config: JIT
- commit hash: [c3fb0d9](https://github.com/python/cpython/commit/c3fb0d9)
- commit date: 2026-03-06T08:42:41+08:00
- commit merge base: [7232883adfc28f94a62d2e79c897db59711702d7](https://github.com/python/cpython/commit/7232883adfc28f94a62d2e79c897db59711702d7)
- ref: c3fb0d9d96902774c08b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22756997896)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260306-blueberry-aarch64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9.json)

### vs. base

- Geometric mean: 1.015x faster (HPT: reliability of 74.03%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260306-blueberry-aarch64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base-mem.svg)
- [📄table](bm-20260306-blueberry-aarch64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base.md)
- [📈time plot](bm-20260306-blueberry-aarch64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22756997896)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260306-ripley-x86_64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9.json)

### vs. base

- Geometric mean: 1.052x faster (HPT: reliability of 99.83%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260306-ripley-x86_64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base-mem.svg)
- [📄table](bm-20260306-ripley-x86_64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base.md)
- [📈time plot](bm-20260306-ripley-x86_64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22756997896)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260306-prometheus-amd64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9.json)

### vs. base

- Geometric mean: 1.174x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260306-prometheus-amd64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base.md)
- [📈time plot](bm-20260306-prometheus-amd64-python-c3fb0d9d96902774c08b-3.15.0a6%2B-c3fb0d9-vs-base.svg)

