# Results

- fork: python/8b5431367042672d5c6f
- version: 3.15.0a6+
- config: JIT
- commit hash: [8b54313](https://github.com/python/cpython/commit/8b54313)
- commit date: 2026-03-05T09:07:47+09:00
- commit merge base: [72b3e374a32989a07bbab057695942b2cc23a294](https://github.com/python/cpython/commit/72b3e374a32989a07bbab057695942b2cc23a294)
- ref: 8b5431367042672d5c6f

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22710952847)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260305-blueberry-aarch64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313.json)

### vs. base

- Geometric mean: 1.026x faster (HPT: reliability of 75.46%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260305-blueberry-aarch64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base-mem.svg)
- [📄table](bm-20260305-blueberry-aarch64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base.md)
- [📈time plot](bm-20260305-blueberry-aarch64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22710952847)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260305-ripley-x86_64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313.json)

### vs. base

- Geometric mean: 1.046x faster (HPT: reliability of 99.05%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260305-ripley-x86_64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base-mem.svg)
- [📄table](bm-20260305-ripley-x86_64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base.md)
- [📈time plot](bm-20260305-ripley-x86_64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22710952847)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260305-prometheus-amd64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313.json)

### vs. base

- Geometric mean: 1.159x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260305-prometheus-amd64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base.md)
- [📈time plot](bm-20260305-prometheus-amd64-python-8b5431367042672d5c6f-3.15.0a6%2B-8b54313-vs-base.svg)

