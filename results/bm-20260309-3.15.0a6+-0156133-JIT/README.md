# Results

- fork: python/015613384fea7a00bb20
- version: 3.15.0a6+
- config: JIT
- commit hash: [0156133](https://github.com/python/cpython/commit/0156133)
- commit date: 2026-03-09T02:25:21+00:00
- commit merge base: [5a15a52dd1dee37af4f2b3a6b15a9f5735f75c6e](https://github.com/python/cpython/commit/5a15a52dd1dee37af4f2b3a6b15a9f5735f75c6e)
- ref: 015613384fea7a00bb20

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22846658955)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260309-blueberry-aarch64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133.json)

### vs. base

- Geometric mean: 1.015x faster (HPT: reliability of 54.39%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260309-blueberry-aarch64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base-mem.svg)
- [📄table](bm-20260309-blueberry-aarch64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base.md)
- [📈time plot](bm-20260309-blueberry-aarch64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22846658955)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260309-ripley-x86_64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133.json)

### vs. base

- Geometric mean: 1.054x faster (HPT: reliability of 99.94%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260309-ripley-x86_64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base-mem.svg)
- [📄table](bm-20260309-ripley-x86_64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base.md)
- [📈time plot](bm-20260309-ripley-x86_64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22846658955)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260309-prometheus-amd64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133.json)

### vs. base

- Geometric mean: 1.193x faster (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260309-prometheus-amd64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base.md)
- [📈time plot](bm-20260309-prometheus-amd64-python-015613384fea7a00bb20-3.15.0a6%2B-0156133-vs-base.svg)

