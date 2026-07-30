# Results

- fork: python/49f96670d98c50eca769
- version: 3.16.0a0
- config: JIT
- commit hash: [49f9667](https://github.com/python/cpython/commit/49f9667)
- commit date: 2026-07-29T14:08:45-07:00
- commit merge base: [11d0da5b54b1a162e8f2566675007cfb2db797b5](https://github.com/python/cpython/commit/11d0da5b54b1a162e8f2566675007cfb2db797b5)
- ref: 49f96670d98c50eca769

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30537497780)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260729-blueberry-aarch64-python-49f96670d98c50eca769-3.16.0a0-49f9667.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 72.34%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260729-blueberry-aarch64-python-49f96670d98c50eca769-3.16.0a0-49f9667-vs-base-mem.svg)
- [📄table](bm-20260729-blueberry-aarch64-python-49f96670d98c50eca769-3.16.0a0-49f9667-vs-base.md)
- [📈time plot](bm-20260729-blueberry-aarch64-python-49f96670d98c50eca769-3.16.0a0-49f9667-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30537497780)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260729-ripley-x86_64-python-49f96670d98c50eca769-3.16.0a0-49f9667.json)

### vs. base

- Geometric mean: 1.076x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260729-ripley-x86_64-python-49f96670d98c50eca769-3.16.0a0-49f9667-vs-base-mem.svg)
- [📄table](bm-20260729-ripley-x86_64-python-49f96670d98c50eca769-3.16.0a0-49f9667-vs-base.md)
- [📈time plot](bm-20260729-ripley-x86_64-python-49f96670d98c50eca769-3.16.0a0-49f9667-vs-base.svg)

