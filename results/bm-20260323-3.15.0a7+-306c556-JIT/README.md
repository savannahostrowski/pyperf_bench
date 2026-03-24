# Results

- fork: python/306c556fdbe7034c9a6d
- version: 3.15.0a7+
- config: JIT
- commit hash: [306c556](https://github.com/python/cpython/commit/306c556)
- commit date: 2026-03-23T23:00:26+00:00
- commit merge base: [e017971eb9f98b2caa3cde6a74ee0acec41529c4](https://github.com/python/cpython/commit/e017971eb9f98b2caa3cde6a74ee0acec41529c4)
- ref: 306c556fdbe7034c9a6d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23482182034)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260323-blueberry-aarch64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556.json)

### vs. base

- Geometric mean: 1.009x slower (HPT: reliability of 62.91%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260323-blueberry-aarch64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base-mem.svg)
- [📄table](bm-20260323-blueberry-aarch64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base.md)
- [📈time plot](bm-20260323-blueberry-aarch64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23482182034)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260323-ripley-x86_64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556.json)

### vs. base

- Geometric mean: 1.062x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260323-ripley-x86_64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base-mem.svg)
- [📄table](bm-20260323-ripley-x86_64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base.md)
- [📈time plot](bm-20260323-ripley-x86_64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23482182034)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260323-prometheus-amd64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556.json)

### vs. base

- Geometric mean: 1.200x faster (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260323-prometheus-amd64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base.md)
- [📈time plot](bm-20260323-prometheus-amd64-python-306c556fdbe7034c9a6d-3.15.0a7%2B-306c556-vs-base.svg)

