# Results

- fork: python/d19de375a204c74ab5f3
- version: 3.15.0a7+
- config: JIT
- commit hash: [d19de37](https://github.com/python/cpython/commit/d19de37)
- commit date: 2026-03-11T21:08:18+00:00
- commit merge base: [f062014d3876f1f81c0e60bf861c3460429ac3b4](https://github.com/python/cpython/commit/f062014d3876f1f81c0e60bf861c3460429ac3b4)
- ref: d19de375a204c74ab5f3

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22994888478)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260311-blueberry-aarch64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37.json)

### vs. base

- Geometric mean: 1.020x faster (HPT: reliability of 61.26%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260311-blueberry-aarch64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base-mem.svg)
- [📄table](bm-20260311-blueberry-aarch64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base.md)
- [📈time plot](bm-20260311-blueberry-aarch64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22994888478)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260311-ripley-x86_64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37.json)

### vs. base

- Geometric mean: 1.062x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260311-ripley-x86_64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base-mem.svg)
- [📄table](bm-20260311-ripley-x86_64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base.md)
- [📈time plot](bm-20260311-ripley-x86_64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22994888478)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260311-prometheus-amd64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37.json)

### vs. base

- Geometric mean: 1.189x faster (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260311-prometheus-amd64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base.md)
- [📈time plot](bm-20260311-prometheus-amd64-python-d19de375a204c74ab5f3-3.15.0a7%2B-d19de37-vs-base.svg)

