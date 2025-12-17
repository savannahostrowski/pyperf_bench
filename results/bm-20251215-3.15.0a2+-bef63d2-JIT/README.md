# Results

- fork: python/bef63d2fb81ae2876004
- version: 3.15.0a2+
- config: JIT
- commit hash: [bef63d2](https://github.com/python/cpython/commit/bef63d2)
- commit date: 2025-12-15T15:18:44-08:00
- commit merge base: [f277781bba684322dffffe45cd878f4652ccf7e4](https://github.com/python/cpython/commit/f277781bba684322dffffe45cd878f4652ccf7e4)
- ref: bef63d2fb81ae2876004

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20251908402)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2.json)

### vs. base

- Geometric mean: 1.024x faster (HPT: reliability of 96.91%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base-mem.svg)
- [📄table](bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.md)
- [📈time plot](bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20251908402)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251215-ripley-x86_64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2.json)

### vs. base

- Geometric mean: 1.035x faster (HPT: reliability of 99.02%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251215-ripley-x86_64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base-mem.svg)
- [📄table](bm-20251215-ripley-x86_64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.md)
- [📈time plot](bm-20251215-ripley-x86_64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.svg)

