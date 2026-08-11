# Results

- fork: python/219768ff531fc0686de6
- version: 3.16.0a0
- config: JIT
- commit hash: [219768f](https://github.com/python/cpython/commit/219768f)
- commit date: 2026-08-10T21:44:50+02:00
- commit merge base: [7571c41da7505e6b551dae305b285af2a9139771](https://github.com/python/cpython/commit/7571c41da7505e6b551dae305b285af2a9139771)
- ref: 219768ff531fc0686de6

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31480398468)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260810-blueberry-aarch64-python-219768ff531fc0686de6-3.16.0a0-219768f.json)

### vs. base

- Geometric mean: 1.006x slower (HPT: reliability of 74.44%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260810-blueberry-aarch64-python-219768ff531fc0686de6-3.16.0a0-219768f-vs-base-mem.svg)
- [📄table](bm-20260810-blueberry-aarch64-python-219768ff531fc0686de6-3.16.0a0-219768f-vs-base.md)
- [📈time plot](bm-20260810-blueberry-aarch64-python-219768ff531fc0686de6-3.16.0a0-219768f-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31480398468)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260810-ripley-x86_64-python-219768ff531fc0686de6-3.16.0a0-219768f.json)

### vs. base

- Geometric mean: 1.076x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260810-ripley-x86_64-python-219768ff531fc0686de6-3.16.0a0-219768f-vs-base-mem.svg)
- [📄table](bm-20260810-ripley-x86_64-python-219768ff531fc0686de6-3.16.0a0-219768f-vs-base.md)
- [📈time plot](bm-20260810-ripley-x86_64-python-219768ff531fc0686de6-3.16.0a0-219768f-vs-base.svg)

