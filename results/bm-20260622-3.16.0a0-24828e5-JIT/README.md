# Results

- fork: python/24828e57e17621fff166
- version: 3.16.0a0
- config: JIT
- commit hash: [24828e5](https://github.com/python/cpython/commit/24828e5)
- commit date: 2026-06-22T06:49:54+08:00
- commit merge base: [7782794850f1ba7f100ca65daf4caa083a3b5101](https://github.com/python/cpython/commit/7782794850f1ba7f100ca65daf4caa083a3b5101)
- ref: 24828e57e17621fff166

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27948060438)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260622-blueberry-aarch64-python-24828e57e17621fff166-3.16.0a0-24828e5.json)

### vs. base

- Geometric mean: 1.009x slower (HPT: reliability of 81.16%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260622-blueberry-aarch64-python-24828e57e17621fff166-3.16.0a0-24828e5-vs-base-mem.svg)
- [📄table](bm-20260622-blueberry-aarch64-python-24828e57e17621fff166-3.16.0a0-24828e5-vs-base.md)
- [📈time plot](bm-20260622-blueberry-aarch64-python-24828e57e17621fff166-3.16.0a0-24828e5-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27948060438)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260622-ripley-x86_64-python-24828e57e17621fff166-3.16.0a0-24828e5.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260622-ripley-x86_64-python-24828e57e17621fff166-3.16.0a0-24828e5-vs-base-mem.svg)
- [📄table](bm-20260622-ripley-x86_64-python-24828e57e17621fff166-3.16.0a0-24828e5-vs-base.md)
- [📈time plot](bm-20260622-ripley-x86_64-python-24828e57e17621fff166-3.16.0a0-24828e5-vs-base.svg)

