# Results

- fork: python/03503dccd0aa6d889561
- version: 3.16.0a0
- config: JIT
- commit hash: [03503dc](https://github.com/python/cpython/commit/03503dc)
- commit date: 2026-08-30T21:43:38+00:00
- commit merge base: [e50e41f7d6f944d224aedf29064cba9c04ecdc3f](https://github.com/python/cpython/commit/e50e41f7d6f944d224aedf29064cba9c04ecdc3f)
- ref: 03503dccd0aa6d889561

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33416582922)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json)

### vs. base

- Geometric mean: 1.016x slower (HPT: reliability of 99.21%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base-mem.svg)
- [📄table](bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.md)
- [📈time plot](bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33416582922)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260830-ripley-x86_64-python-03503dccd0aa6d889561-3.16.0a0-03503dc.json)

### vs. base

- Geometric mean: 1.079x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260830-ripley-x86_64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base-mem.svg)
- [📄table](bm-20260830-ripley-x86_64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.md)
- [📈time plot](bm-20260830-ripley-x86_64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.svg)

