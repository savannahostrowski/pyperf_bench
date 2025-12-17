# Results

- fork: python/b1c9582ebe1309819588
- version: 3.15.0a2+
- config: JIT
- commit hash: [b1c9582](https://github.com/python/cpython/commit/b1c9582)
- commit date: 2025-12-11T21:58:09Z
- commit merge base: [2eca80ffab5a5fd616a71757a4bf84908bce3a8d](https://github.com/python/cpython/commit/2eca80ffab5a5fd616a71757a4bf84908bce3a8d)
- commit date: 2025-12-11T21:58:09+00:00
- ref: b1c9582ebe1309819588

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20151670915)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251211-blueberry-aarch64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582.json)

### vs. base

- Geometric mean: 1.067x slower (HPT: reliability of 99.86%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251211-blueberry-aarch64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base-mem.svg)
- [📄table](bm-20251211-blueberry-aarch64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.md)
- [📈time plot](bm-20251211-blueberry-aarch64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20151670915)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251211-ripley-x86_64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582.json)

### vs. base

- Geometric mean: 1.032x faster (HPT: reliability of 91.27%, 1.00x faster at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251211-ripley-x86_64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base-mem.svg)
- [📄table](bm-20251211-ripley-x86_64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.md)
- [📈time plot](bm-20251211-ripley-x86_64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20151670915)
- cpu model: missing
- platform: macOS-26.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251211-jones-arm64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582.json)

### vs. base

- Geometric mean: 1.091x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251211-jones-arm64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base-mem.svg)
- [📄table](bm-20251211-jones-arm64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.md)
- [📈time plot](bm-20251211-jones-arm64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.svg)

