# Results

- fork: python/6757482c25d4fa308d3f
- version: 3.16.0a0
- config: JIT
- commit hash: [6757482](https://github.com/python/cpython/commit/6757482)
- commit date: 2026-09-22T22:45:00+02:00
- commit merge base: [6f64920479e37d30c8a5c59f07c7b47712a8ccc7](https://github.com/python/cpython/commit/6f64920479e37d30c8a5c59f07c7b47712a8ccc7)
- ref: 6757482c25d4fa308d3f

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35871991227)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260922-blueberry-aarch64-python-6757482c25d4fa308d3f-3.16.0a0-6757482.json)

### vs. base

- Geometric mean: 1.029x slower (HPT: reliability of 99.99%, 1.01x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260922-blueberry-aarch64-python-6757482c25d4fa308d3f-3.16.0a0-6757482-vs-base-mem.svg)
- [📄table](bm-20260922-blueberry-aarch64-python-6757482c25d4fa308d3f-3.16.0a0-6757482-vs-base.md)
- [📈time plot](bm-20260922-blueberry-aarch64-python-6757482c25d4fa308d3f-3.16.0a0-6757482-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35871991227)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260922-ripley-x86_64-python-6757482c25d4fa308d3f-3.16.0a0-6757482.json)

### vs. base

- Geometric mean: 1.079x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260922-ripley-x86_64-python-6757482c25d4fa308d3f-3.16.0a0-6757482-vs-base-mem.svg)
- [📄table](bm-20260922-ripley-x86_64-python-6757482c25d4fa308d3f-3.16.0a0-6757482-vs-base.md)
- [📈time plot](bm-20260922-ripley-x86_64-python-6757482c25d4fa308d3f-3.16.0a0-6757482-vs-base.svg)

