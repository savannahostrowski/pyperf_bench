# Results

- fork: python/832bc0b0ea20c2fade5d
- version: 3.16.0a0
- config: JIT
- commit hash: [832bc0b](https://github.com/python/cpython/commit/832bc0b)
- commit date: 2026-07-12T18:27:10+03:00
- commit merge base: [dd2faeb33d5fa0d2635b91ece6eaebd34c61408c](https://github.com/python/cpython/commit/dd2faeb33d5fa0d2635b91ece6eaebd34c61408c)
- ref: 832bc0b0ea20c2fade5d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29248776605)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260712-blueberry-aarch64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 88.50%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260712-blueberry-aarch64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b-vs-base-mem.svg)
- [📄table](bm-20260712-blueberry-aarch64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b-vs-base.md)
- [📈time plot](bm-20260712-blueberry-aarch64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29248776605)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260712-ripley-x86_64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b.json)

### vs. base

- Geometric mean: 1.073x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260712-ripley-x86_64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b-vs-base-mem.svg)
- [📄table](bm-20260712-ripley-x86_64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b-vs-base.md)
- [📈time plot](bm-20260712-ripley-x86_64-python-832bc0b0ea20c2fade5d-3.16.0a0-832bc0b-vs-base.svg)

