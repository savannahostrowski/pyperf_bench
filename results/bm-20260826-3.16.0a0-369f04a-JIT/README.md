# Results

- fork: python/369f04a1bcc26ddd05e2
- version: 3.16.0a0
- config: JIT
- commit hash: [369f04a](https://github.com/python/cpython/commit/369f04a)
- commit date: 2026-08-26T07:51:59+09:00
- commit merge base: [cf7e9108bdb18f52507909f2f9d659f951a4a1fe](https://github.com/python/cpython/commit/cf7e9108bdb18f52507909f2f9d659f951a4a1fe)
- ref: 369f04a1bcc26ddd05e2

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32954820046)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260826-blueberry-aarch64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 78.18%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260826-blueberry-aarch64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a-vs-base-mem.svg)
- [📄table](bm-20260826-blueberry-aarch64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a-vs-base.md)
- [📈time plot](bm-20260826-blueberry-aarch64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32954820046)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260826-ripley-x86_64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260826-ripley-x86_64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a-vs-base-mem.svg)
- [📄table](bm-20260826-ripley-x86_64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a-vs-base.md)
- [📈time plot](bm-20260826-ripley-x86_64-python-369f04a1bcc26ddd05e2-3.16.0a0-369f04a-vs-base.svg)

