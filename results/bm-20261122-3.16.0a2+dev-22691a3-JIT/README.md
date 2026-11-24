# Results

- fork: python/22691a32b122cff3ad17
- version: 3.16.0a2+dev
- config: JIT
- commit hash: [22691a3](https://github.com/python/cpython/commit/22691a3)
- commit date: 2026-11-22T16:21:06-08:00
- commit merge base: [e8bc97b55d1ba76b2593608919e4300e525310fd](https://github.com/python/cpython/commit/e8bc97b55d1ba76b2593608919e4300e525310fd)
- ref: 22691a32b122cff3ad17

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/45265030430)
- cpu model: missing
- platform: Linux-6.12.115+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261122-blueberry-aarch64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3.json)

### vs. base

- Geometric mean: 1.002x slower (HPT: reliability of 96.00%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20261122-blueberry-aarch64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3-vs-base-mem.svg)
- [📄table](bm-20261122-blueberry-aarch64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3-vs-base.md)
- [📈time plot](bm-20261122-blueberry-aarch64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/45265030430)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-149-generic-x86_64-with-glibc2.39
- [raw results](bm-20261122-ripley-x86_64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3.json)

### vs. base

- Geometric mean: 1.086x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20261122-ripley-x86_64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3-vs-base-mem.svg)
- [📄table](bm-20261122-ripley-x86_64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3-vs-base.md)
- [📈time plot](bm-20261122-ripley-x86_64-python-22691a32b122cff3ad17-3.16.0a2%2Bdev-22691a3-vs-base.svg)

