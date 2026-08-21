# Results

- fork: python/04242c027feeff726acb
- version: 3.16.0a0
- config: JIT
- commit hash: [04242c0](https://github.com/python/cpython/commit/04242c0)
- commit date: 2026-08-20T12:24:45-07:00
- commit merge base: [83531fd39f24f873671c38b981061afe1730613f](https://github.com/python/cpython/commit/83531fd39f24f873671c38b981061afe1730613f)
- ref: 04242c027feeff726acb

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32468990373)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260820-blueberry-aarch64-python-04242c027feeff726acb-3.16.0a0-04242c0.json)

### vs. base

- Geometric mean: 1.014x slower (HPT: reliability of 97.09%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260820-blueberry-aarch64-python-04242c027feeff726acb-3.16.0a0-04242c0-vs-base-mem.svg)
- [📄table](bm-20260820-blueberry-aarch64-python-04242c027feeff726acb-3.16.0a0-04242c0-vs-base.md)
- [📈time plot](bm-20260820-blueberry-aarch64-python-04242c027feeff726acb-3.16.0a0-04242c0-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32468990373)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260820-ripley-x86_64-python-04242c027feeff726acb-3.16.0a0-04242c0.json)

### vs. base

- Geometric mean: 1.075x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260820-ripley-x86_64-python-04242c027feeff726acb-3.16.0a0-04242c0-vs-base-mem.svg)
- [📄table](bm-20260820-ripley-x86_64-python-04242c027feeff726acb-3.16.0a0-04242c0-vs-base.md)
- [📈time plot](bm-20260820-ripley-x86_64-python-04242c027feeff726acb-3.16.0a0-04242c0-vs-base.svg)

