# Results

- fork: python/c1df6843d36233ec1da7
- version: 3.16.0a0
- config: JIT
- commit hash: [c1df684](https://github.com/python/cpython/commit/c1df684)
- commit date: 2026-09-19T22:04:42+00:00
- commit merge base: [a1669c95d980f6cabceaaf61e3c49873b5e03efa](https://github.com/python/cpython/commit/a1669c95d980f6cabceaaf61e3c49873b5e03efa)
- ref: c1df6843d36233ec1da7

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35513697616)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260919-blueberry-aarch64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 98.26%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260919-blueberry-aarch64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684-vs-base-mem.svg)
- [📄table](bm-20260919-blueberry-aarch64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684-vs-base.md)
- [📈time plot](bm-20260919-blueberry-aarch64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35513697616)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260919-ripley-x86_64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684.json)

### vs. base

- Geometric mean: 1.079x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260919-ripley-x86_64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684-vs-base-mem.svg)
- [📄table](bm-20260919-ripley-x86_64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684-vs-base.md)
- [📈time plot](bm-20260919-ripley-x86_64-python-c1df6843d36233ec1da7-3.16.0a0-c1df684-vs-base.svg)

