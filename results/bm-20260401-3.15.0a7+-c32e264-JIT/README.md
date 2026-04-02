# Results

- fork: python/c32e264227b1fee3a643
- version: 3.15.0a7+
- config: JIT
- commit hash: [c32e264](https://github.com/python/cpython/commit/c32e264)
- commit date: 2026-04-01T22:54:06+00:00
- commit merge base: [b456cb25a98985bdbce6987a37f01da4e2ed478e](https://github.com/python/cpython/commit/b456cb25a98985bdbce6987a37f01da4e2ed478e)
- ref: c32e264227b1fee3a643

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23893765575)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260401-blueberry-aarch64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264.json)

### vs. base

- Geometric mean: 1.003x slower (HPT: reliability of 88.61%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260401-blueberry-aarch64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base-mem.svg)
- [📄table](bm-20260401-blueberry-aarch64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base.md)
- [📈time plot](bm-20260401-blueberry-aarch64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23893765575)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260401-ripley-x86_64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264.json)

### vs. base

- Geometric mean: 1.061x faster (HPT: reliability of 99.97%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260401-ripley-x86_64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base-mem.svg)
- [📄table](bm-20260401-ripley-x86_64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base.md)
- [📈time plot](bm-20260401-ripley-x86_64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23893765575)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260401-prometheus-amd64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264.json)

### vs. base

- Geometric mean: 1.215x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260401-prometheus-amd64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base.md)
- [📈time plot](bm-20260401-prometheus-amd64-python-c32e264227b1fee3a643-3.15.0a7%2B-c32e264-vs-base.svg)

