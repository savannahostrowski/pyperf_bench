# Results

- fork: python/e4058d7cb115286c3c53
- version: 3.15.0a3+
- config: JIT
- commit hash: [e4058d7](https://github.com/python/cpython/commit/e4058d7)
- commit date: 2025-12-18T16:43:44+00:00
- commit merge base: [14f0b5191ad1d749d2ba5810f4f4495ee5581ce9](https://github.com/python/cpython/commit/14f0b5191ad1d749d2ba5810f4f4495ee5581ce9)
- ref: e4058d7cb115286c3c53

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20344368709)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7.json)

### vs. base

- Geometric mean: 1.014x faster (HPT: reliability of 65.87%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base-mem.svg)
- [📄table](bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.md)
- [📈time plot](bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20344368709)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7.json)

### vs. base

- Geometric mean: 1.033x faster (HPT: reliability of 89.29%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base-mem.svg)
- [📄table](bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.md)
- [📈time plot](bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.svg)

