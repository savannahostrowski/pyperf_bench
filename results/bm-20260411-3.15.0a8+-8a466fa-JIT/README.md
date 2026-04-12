# Results

- fork: python/8a466fa3d90a9e1f04d2
- version: 3.15.0a8+
- config: JIT
- commit hash: [8a466fa](https://github.com/python/cpython/commit/8a466fa)
- commit date: 2026-04-11T22:26:36+00:00
- commit merge base: [daa2578dc04cce99545e72acc8431929519c04fc](https://github.com/python/cpython/commit/daa2578dc04cce99545e72acc8431929519c04fc)
- ref: 8a466fa3d90a9e1f04d2

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24303402925)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260411-blueberry-aarch64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa.json)

### vs. base

- Geometric mean: 1.001x faster (HPT: reliability of 61.71%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20260411-blueberry-aarch64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa-vs-base-mem.svg)
- [📄table](bm-20260411-blueberry-aarch64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa-vs-base.md)
- [📈time plot](bm-20260411-blueberry-aarch64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24303402925)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260411-ripley-x86_64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa.json)

### vs. base

- Geometric mean: 1.088x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20260411-ripley-x86_64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa-vs-base-mem.svg)
- [📄table](bm-20260411-ripley-x86_64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa-vs-base.md)
- [📈time plot](bm-20260411-ripley-x86_64-python-8a466fa3d90a9e1f04d2-3.15.0a8%2B-8a466fa-vs-base.svg)

