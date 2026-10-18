# Results

- fork: python/2188f9b60abb7965548b
- version: 3.16.0a1+dev
- config: JIT
- commit hash: [2188f9b](https://github.com/python/cpython/commit/2188f9b)
- commit date: 2026-10-17T23:07:03+00:00
- commit merge base: [0fedf7852c24727b5a9fa7f2014c18cbaa50cdb9](https://github.com/python/cpython/commit/0fedf7852c24727b5a9fa7f2014c18cbaa50cdb9)
- ref: 2188f9b60abb7965548b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/39129991741)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261017-blueberry-aarch64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 90.21%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20261017-blueberry-aarch64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b-vs-base-mem.svg)
- [📄table](bm-20261017-blueberry-aarch64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b-vs-base.md)
- [📈time plot](bm-20261017-blueberry-aarch64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/39129991741)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-142-generic-x86_64-with-glibc2.39
- [raw results](bm-20261017-ripley-x86_64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b.json)

### vs. base

- Geometric mean: 1.094x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20261017-ripley-x86_64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b-vs-base-mem.svg)
- [📄table](bm-20261017-ripley-x86_64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b-vs-base.md)
- [📈time plot](bm-20261017-ripley-x86_64-python-2188f9b60abb7965548b-3.16.0a1%2Bdev-2188f9b-vs-base.svg)

