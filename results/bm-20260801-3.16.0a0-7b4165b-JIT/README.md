# Results

- fork: python/7b4165b3b07638d8aeab
- version: 3.16.0a0
- config: JIT
- commit hash: [7b4165b](https://github.com/python/cpython/commit/7b4165b)
- commit date: 2026-08-01T21:54:04+02:00
- commit merge base: [7ce7f0bd8511410bf7c42cc5fc88dfafe07874b6](https://github.com/python/cpython/commit/7ce7f0bd8511410bf7c42cc5fc88dfafe07874b6)
- ref: 7b4165b3b07638d8aeab

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30744280955)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260801-blueberry-aarch64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 83.95%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260801-blueberry-aarch64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b-vs-base-mem.svg)
- [📄table](bm-20260801-blueberry-aarch64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b-vs-base.md)
- [📈time plot](bm-20260801-blueberry-aarch64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30744280955)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260801-ripley-x86_64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b.json)

### vs. base

- Geometric mean: 1.075x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260801-ripley-x86_64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b-vs-base-mem.svg)
- [📄table](bm-20260801-ripley-x86_64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b-vs-base.md)
- [📈time plot](bm-20260801-ripley-x86_64-python-7b4165b3b07638d8aeab-3.16.0a0-7b4165b-vs-base.svg)

