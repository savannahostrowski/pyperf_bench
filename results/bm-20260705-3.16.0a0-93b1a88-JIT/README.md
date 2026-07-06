# Results

- fork: python/93b1a886343e44241145
- version: 3.16.0a0
- config: JIT
- commit hash: [93b1a88](https://github.com/python/cpython/commit/93b1a88)
- commit date: 2026-07-05T21:26:44+00:00
- commit merge base: [d733b104d53e96584a6881d2772df65ad82573a0](https://github.com/python/cpython/commit/d733b104d53e96584a6881d2772df65ad82573a0)
- ref: 93b1a886343e44241145

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28792880570)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260705-blueberry-aarch64-python-93b1a886343e44241145-3.16.0a0-93b1a88.json)

### vs. base

- Geometric mean: 1.015x slower (HPT: reliability of 90.90%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260705-blueberry-aarch64-python-93b1a886343e44241145-3.16.0a0-93b1a88-vs-base-mem.svg)
- [📄table](bm-20260705-blueberry-aarch64-python-93b1a886343e44241145-3.16.0a0-93b1a88-vs-base.md)
- [📈time plot](bm-20260705-blueberry-aarch64-python-93b1a886343e44241145-3.16.0a0-93b1a88-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28792880570)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260705-ripley-x86_64-python-93b1a886343e44241145-3.16.0a0-93b1a88.json)

### vs. base

- Geometric mean: 1.075x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260705-ripley-x86_64-python-93b1a886343e44241145-3.16.0a0-93b1a88-vs-base-mem.svg)
- [📄table](bm-20260705-ripley-x86_64-python-93b1a886343e44241145-3.16.0a0-93b1a88-vs-base.md)
- [📈time plot](bm-20260705-ripley-x86_64-python-93b1a886343e44241145-3.16.0a0-93b1a88-vs-base.svg)

