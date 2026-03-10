# Results

- fork: python/099943b122cda2548ad7
- version: 3.15.0a6+
- config: JIT
- commit hash: [099943b](https://github.com/python/cpython/commit/099943b)
- commit date: 2026-03-09T22:51:00+00:00
- commit merge base: [0b65c88c2af6e09530a9aa21800771aa687371db](https://github.com/python/cpython/commit/0b65c88c2af6e09530a9aa21800771aa687371db)
- ref: 099943b122cda2548ad7

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22895500268)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260309-blueberry-aarch64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b.json)

### vs. base

- Geometric mean: 1.020x faster (HPT: reliability of 57.17%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260309-blueberry-aarch64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base-mem.svg)
- [📄table](bm-20260309-blueberry-aarch64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base.md)
- [📈time plot](bm-20260309-blueberry-aarch64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22895500268)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260309-ripley-x86_64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b.json)

### vs. base

- Geometric mean: 1.058x faster (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260309-ripley-x86_64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base-mem.svg)
- [📄table](bm-20260309-ripley-x86_64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base.md)
- [📈time plot](bm-20260309-ripley-x86_64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22895500268)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260309-prometheus-amd64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b.json)

### vs. base

- Geometric mean: 1.176x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260309-prometheus-amd64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base.md)
- [📈time plot](bm-20260309-prometheus-amd64-python-099943b122cda2548ad7-3.15.0a6%2B-099943b-vs-base.svg)

