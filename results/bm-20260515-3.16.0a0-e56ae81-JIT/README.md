# Results

- fork: python/e56ae817e5f3df37a603
- version: 3.16.0a0
- config: JIT
- commit hash: [e56ae81](https://github.com/python/cpython/commit/e56ae81)
- commit date: 2026-05-15T23:09:36+00:00
- commit merge base: [1441f2f7351f030ba07c6c6b11be513ad1c9104f](https://github.com/python/cpython/commit/1441f2f7351f030ba07c6c6b11be513ad1c9104f)
- ref: e56ae817e5f3df37a603

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25958618658)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260515-blueberry-aarch64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81.json)

### vs. base

- Geometric mean: 1.018x slower (HPT: reliability of 98.55%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260515-blueberry-aarch64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81-vs-base-mem.svg)
- [📄table](bm-20260515-blueberry-aarch64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81-vs-base.md)
- [📈time plot](bm-20260515-blueberry-aarch64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25958618658)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260515-ripley-x86_64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81.json)

### vs. base

- Geometric mean: 1.070x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260515-ripley-x86_64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81-vs-base-mem.svg)
- [📄table](bm-20260515-ripley-x86_64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81-vs-base.md)
- [📈time plot](bm-20260515-ripley-x86_64-python-e56ae817e5f3df37a603-3.16.0a0-e56ae81-vs-base.svg)

