# Results

- fork: python/871047dbb82ab9a89f36
- version: 3.16.0a0
- config: JIT
- commit hash: [871047d](https://github.com/python/cpython/commit/871047d)
- commit date: 2026-06-10T13:43:09-07:00
- commit merge base: [e60c42dc3f5a8dd9b10bc9a8a028ef2765469650](https://github.com/python/cpython/commit/e60c42dc3f5a8dd9b10bc9a8a028ef2765469650)
- ref: 871047dbb82ab9a89f36

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27340946371)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260610-blueberry-aarch64-python-871047dbb82ab9a89f36-3.16.0a0-871047d.json)

### vs. base

- Geometric mean: 1.004x slower (HPT: reliability of 57.35%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260610-blueberry-aarch64-python-871047dbb82ab9a89f36-3.16.0a0-871047d-vs-base-mem.svg)
- [📄table](bm-20260610-blueberry-aarch64-python-871047dbb82ab9a89f36-3.16.0a0-871047d-vs-base.md)
- [📈time plot](bm-20260610-blueberry-aarch64-python-871047dbb82ab9a89f36-3.16.0a0-871047d-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27340946371)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260610-ripley-x86_64-python-871047dbb82ab9a89f36-3.16.0a0-871047d.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260610-ripley-x86_64-python-871047dbb82ab9a89f36-3.16.0a0-871047d-vs-base-mem.svg)
- [📄table](bm-20260610-ripley-x86_64-python-871047dbb82ab9a89f36-3.16.0a0-871047d-vs-base.md)
- [📈time plot](bm-20260610-ripley-x86_64-python-871047dbb82ab9a89f36-3.16.0a0-871047d-vs-base.svg)

