# Results

- fork: python/1f649fecb645d70b9c48
- version: 3.16.0a0
- config: JIT
- commit hash: [1f649fe](https://github.com/python/cpython/commit/1f649fe)
- commit date: 2026-07-20T22:47:43+00:00
- commit merge base: [1c1088b1da5a7484b7b04e90ccc47aa362e709eb](https://github.com/python/cpython/commit/1c1088b1da5a7484b7b04e90ccc47aa362e709eb)
- ref: 1f649fecb645d70b9c48

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29825104779)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260720-blueberry-aarch64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe.json)

### vs. base

- Geometric mean: 1.010x slower (HPT: reliability of 86.11%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260720-blueberry-aarch64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base-mem.svg)
- [📄table](bm-20260720-blueberry-aarch64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.md)
- [📈time plot](bm-20260720-blueberry-aarch64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29825104779)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe.json)

### vs. base

- Geometric mean: 1.070x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base-mem.svg)
- [📄table](bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.md)
- [📈time plot](bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.svg)

