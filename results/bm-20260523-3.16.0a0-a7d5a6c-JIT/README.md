# Results

- fork: python/a7d5a6cc179e2eabd780
- version: 3.16.0a0
- config: JIT
- commit hash: [a7d5a6c](https://github.com/python/cpython/commit/a7d5a6c)
- commit date: 2026-05-23T00:04:51+02:00
- commit merge base: [9df2b6ccc719b0bc0167da65b72b57f9da39398b](https://github.com/python/cpython/commit/9df2b6ccc719b0bc0167da65b72b57f9da39398b)
- ref: a7d5a6cc179e2eabd780

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26329468858)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260523-blueberry-aarch64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c.json)

### vs. base

- Geometric mean: 1.005x slower (HPT: reliability of 56.82%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260523-blueberry-aarch64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c-vs-base-mem.svg)
- [📄table](bm-20260523-blueberry-aarch64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c-vs-base.md)
- [📈time plot](bm-20260523-blueberry-aarch64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26329468858)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260523-ripley-x86_64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260523-ripley-x86_64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c-vs-base-mem.svg)
- [📄table](bm-20260523-ripley-x86_64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c-vs-base.md)
- [📈time plot](bm-20260523-ripley-x86_64-python-a7d5a6cc179e2eabd780-3.16.0a0-a7d5a6c-vs-base.svg)

