# Results

- fork: python/f62050d65743f0c895f7
- version: 3.16.0a0
- config: JIT
- commit hash: [f62050d](https://github.com/python/cpython/commit/f62050d)
- commit date: 2026-07-16T10:37:00-07:00
- commit merge base: [b090d06e7331c40b3c94e70b35a09f785b279e17](https://github.com/python/cpython/commit/b090d06e7331c40b3c94e70b35a09f785b279e17)
- ref: f62050d65743f0c895f7

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29574805251)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260716-blueberry-aarch64-python-f62050d65743f0c895f7-3.16.0a0-f62050d.json)

### vs. base

- Geometric mean: 1.006x slower (HPT: reliability of 92.73%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260716-blueberry-aarch64-python-f62050d65743f0c895f7-3.16.0a0-f62050d-vs-base-mem.svg)
- [📄table](bm-20260716-blueberry-aarch64-python-f62050d65743f0c895f7-3.16.0a0-f62050d-vs-base.md)
- [📈time plot](bm-20260716-blueberry-aarch64-python-f62050d65743f0c895f7-3.16.0a0-f62050d-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29574805251)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260716-ripley-x86_64-python-f62050d65743f0c895f7-3.16.0a0-f62050d.json)

### vs. base

- Geometric mean: 1.072x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260716-ripley-x86_64-python-f62050d65743f0c895f7-3.16.0a0-f62050d-vs-base-mem.svg)
- [📄table](bm-20260716-ripley-x86_64-python-f62050d65743f0c895f7-3.16.0a0-f62050d-vs-base.md)
- [📈time plot](bm-20260716-ripley-x86_64-python-f62050d65743f0c895f7-3.16.0a0-f62050d-vs-base.svg)

