# Results

- fork: python/61ec3c2065deeea935f1
- version: 3.16.0a0
- config: JIT
- commit hash: [61ec3c2](https://github.com/python/cpython/commit/61ec3c2)
- commit date: 2026-05-30T13:49:11-07:00
- commit merge base: [56bd9ea676d5ab4d5f6c68aefc3125ef5a216157](https://github.com/python/cpython/commit/56bd9ea676d5ab4d5f6c68aefc3125ef5a216157)
- ref: 61ec3c2065deeea935f1

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26709466147)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260530-blueberry-aarch64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2.json)

### vs. base

- Geometric mean: 1.013x slower (HPT: reliability of 69.46%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260530-blueberry-aarch64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2-vs-base-mem.svg)
- [📄table](bm-20260530-blueberry-aarch64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2-vs-base.md)
- [📈time plot](bm-20260530-blueberry-aarch64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26709466147)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260530-ripley-x86_64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2.json)

### vs. base

- Geometric mean: 1.072x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260530-ripley-x86_64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2-vs-base-mem.svg)
- [📄table](bm-20260530-ripley-x86_64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2-vs-base.md)
- [📈time plot](bm-20260530-ripley-x86_64-python-61ec3c2065deeea935f1-3.16.0a0-61ec3c2-vs-base.svg)

