# Results

- fork: python/89729f2ef7f9473d9e4b
- version: 3.15.0a3+
- config: JIT
- commit hash: [89729f2](https://github.com/python/cpython/commit/89729f2)
- commit date: 2025-12-17T00:12:32+00:00
- commit merge base: [434525398196db692196661d15e678b3d514aa54](https://github.com/python/cpython/commit/434525398196db692196661d15e678b3d514aa54)
- ref: 89729f2ef7f9473d9e4b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20287012605)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2.json)

### vs. base

- Geometric mean: 1.009x faster (HPT: reliability of 65.29%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base-mem.svg)
- [📄table](bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.md)
- [📈time plot](bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20287012605)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251216-ripley-x86_64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2.json)

### vs. base

- Geometric mean: 1.028x faster (HPT: reliability of 70.18%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251216-ripley-x86_64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base-mem.svg)
- [📄table](bm-20251216-ripley-x86_64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.md)
- [📈time plot](bm-20251216-ripley-x86_64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.svg)

