# Results

- fork: python/5637f4e38a68cd015daa
- version: 3.16.0a0
- config: JIT
- commit hash: [5637f4e](https://github.com/python/cpython/commit/5637f4e)
- commit date: 2026-09-27T20:26:46-04:00
- commit merge base: [1c4fa4f98e64fbeda09ac0bcc9f4cba2f6d50349](https://github.com/python/cpython/commit/1c4fa4f98e64fbeda09ac0bcc9f4cba2f6d50349)
- ref: 5637f4e38a68cd015daa

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/36458438629)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260927-blueberry-aarch64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 97.86%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260927-blueberry-aarch64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e-vs-base-mem.svg)
- [📄table](bm-20260927-blueberry-aarch64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e-vs-base.md)
- [📈time plot](bm-20260927-blueberry-aarch64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/36458438629)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260927-ripley-x86_64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260927-ripley-x86_64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e-vs-base-mem.svg)
- [📄table](bm-20260927-ripley-x86_64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e-vs-base.md)
- [📈time plot](bm-20260927-ripley-x86_64-python-5637f4e38a68cd015daa-3.16.0a0-5637f4e-vs-base.svg)

