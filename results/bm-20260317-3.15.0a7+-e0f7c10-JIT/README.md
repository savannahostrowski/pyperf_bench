# Results

- fork: python/e0f7c1097e19b6f5c239
- version: 3.15.0a7+
- config: JIT
- commit hash: [e0f7c10](https://github.com/python/cpython/commit/e0f7c10)
- commit date: 2026-03-17T14:24:44-04:00
- commit merge base: [966fc8153141ef41885dc36ab3522487657c06fe](https://github.com/python/cpython/commit/966fc8153141ef41885dc36ab3522487657c06fe)
- ref: e0f7c1097e19b6f5c239

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23237748732)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260317-blueberry-aarch64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10.json)

### vs. base

- Geometric mean: 1.017x slower (HPT: reliability of 85.33%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260317-blueberry-aarch64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base-mem.svg)
- [📄table](bm-20260317-blueberry-aarch64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base.md)
- [📈time plot](bm-20260317-blueberry-aarch64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23237748732)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260317-ripley-x86_64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10.json)

### vs. base

- Geometric mean: 1.042x faster (HPT: reliability of 99.75%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260317-ripley-x86_64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base-mem.svg)
- [📄table](bm-20260317-ripley-x86_64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base.md)
- [📈time plot](bm-20260317-ripley-x86_64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23237748732)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260317-prometheus-amd64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10.json)

### vs. base

- Geometric mean: 1.205x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260317-prometheus-amd64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base.md)
- [📈time plot](bm-20260317-prometheus-amd64-python-e0f7c1097e19b6f5c239-3.15.0a7%2B-e0f7c10-vs-base.svg)

