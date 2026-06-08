# Results

- fork: python/4084141073127669a779
- version: 3.16.0a0
- config: JIT
- commit hash: [4084141](https://github.com/python/cpython/commit/4084141)
- commit date: 2026-06-07T19:25:50+01:00
- commit merge base: [81965c1683d7129a70e3fde22ea8a02b9398e227](https://github.com/python/cpython/commit/81965c1683d7129a70e3fde22ea8a02b9398e227)
- ref: 4084141073127669a779

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27132221432)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260607-blueberry-aarch64-python-4084141073127669a779-3.16.0a0-4084141.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 90.21%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260607-blueberry-aarch64-python-4084141073127669a779-3.16.0a0-4084141-vs-base-mem.svg)
- [📄table](bm-20260607-blueberry-aarch64-python-4084141073127669a779-3.16.0a0-4084141-vs-base.md)
- [📈time plot](bm-20260607-blueberry-aarch64-python-4084141073127669a779-3.16.0a0-4084141-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27132221432)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260607-ripley-x86_64-python-4084141073127669a779-3.16.0a0-4084141.json)

### vs. base

- Geometric mean: 1.067x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260607-ripley-x86_64-python-4084141073127669a779-3.16.0a0-4084141-vs-base-mem.svg)
- [📄table](bm-20260607-ripley-x86_64-python-4084141073127669a779-3.16.0a0-4084141-vs-base.md)
- [📈time plot](bm-20260607-ripley-x86_64-python-4084141073127669a779-3.16.0a0-4084141-vs-base.svg)

