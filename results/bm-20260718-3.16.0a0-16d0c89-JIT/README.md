# Results

- fork: python/16d0c89b875c520cf5af
- version: 3.16.0a0
- config: JIT
- commit hash: [16d0c89](https://github.com/python/cpython/commit/16d0c89)
- commit date: 2026-07-18T01:43:38+02:00
- commit merge base: [d478cf81f770168e3fb512ce110a88774f04f549](https://github.com/python/cpython/commit/d478cf81f770168e3fb512ce110a88774f04f549)
- ref: 16d0c89b875c520cf5af

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29640688366)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260718-blueberry-aarch64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89.json)

### vs. base

- Geometric mean: 1.004x slower (HPT: reliability of 88.69%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260718-blueberry-aarch64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89-vs-base-mem.svg)
- [📄table](bm-20260718-blueberry-aarch64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89-vs-base.md)
- [📈time plot](bm-20260718-blueberry-aarch64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29640688366)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260718-ripley-x86_64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89.json)

### vs. base

- Geometric mean: 1.080x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260718-ripley-x86_64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89-vs-base-mem.svg)
- [📄table](bm-20260718-ripley-x86_64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89-vs-base.md)
- [📈time plot](bm-20260718-ripley-x86_64-python-16d0c89b875c520cf5af-3.16.0a0-16d0c89-vs-base.svg)

