# Results

- fork: python/d844d22cb00e4a8a224a
- version: 3.15.0a2+
- config: JIT
- commit hash: [d844d22](https://github.com/python/cpython/commit/d844d22)
- commit date: 2025-12-14T21:23:38Z
- commit merge base: [3f56186a2d0e22f4f279b0cd071e871a312e2c67](https://github.com/python/cpython/commit/3f56186a2d0e22f4f279b0cd071e871a312e2c67)
- commit date: 2025-12-14T21:23:38+00:00
- ref: d844d22cb00e4a8a224a

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20216417387)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22.json)

### vs. base

- Geometric mean: 1.021x faster (HPT: reliability of 76.61%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base-mem.svg)
- [📄table](bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base.md)
- [📈time plot](bm-20251214-blueberry-aarch64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20216417387)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251214-ripley-x86_64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22.json)

### vs. base

- Geometric mean: 1.032x faster (HPT: reliability of 80.50%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251214-ripley-x86_64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base-mem.svg)
- [📄table](bm-20251214-ripley-x86_64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base.md)
- [📈time plot](bm-20251214-ripley-x86_64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20216417387)
- cpu model: missing
- platform: macOS-26.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22.json)

### vs. base

- Geometric mean: 1.082x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base-mem.svg)
- [📄table](bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base.md)
- [📈time plot](bm-20251214-jones-arm64-python-d844d22cb00e4a8a224a-3.15.0a2%2B-d844d22-vs-base.svg)

