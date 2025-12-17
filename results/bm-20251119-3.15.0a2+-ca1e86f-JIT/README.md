# Results

- fork: python/ca1e86f9d963dc298d9a
- version: 3.15.0a2+
- config: JIT
- commit hash: [ca1e86f](https://github.com/python/cpython/commit/ca1e86f)
- commit date: 2025-11-19T15:57:44-08:00
- commit merge base: [b4344f7020f066e83a113e0d4f9343cec4e56a1e](https://github.com/python/cpython/commit/b4344f7020f066e83a113e0d4f9343cec4e56a1e)
- ref: ca1e86f9d963dc298d9a

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19520656326)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f.json)

### vs. base

- Geometric mean: 1.089x slower (HPT: reliability of 99.95%, 1.01x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base-mem.svg)
- [📄table](bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.md)
- [📈time plot](bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19520656326)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f.json)

### vs. base

- Geometric mean: 1.017x faster (HPT: reliability of 90.22%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base-mem.svg)
- [📄table](bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.md)
- [📈time plot](bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.svg)

