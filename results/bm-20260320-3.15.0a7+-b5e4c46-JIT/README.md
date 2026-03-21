# Results

- fork: python/b5e4c46be24d1fade0de
- version: 3.15.0a7+
- config: JIT
- commit hash: [b5e4c46](https://github.com/python/cpython/commit/b5e4c46)
- commit date: 2026-03-20T20:10:50+00:00
- commit merge base: [1eff27f2c0452b3114bcf139062c87c025842c3e](https://github.com/python/cpython/commit/1eff27f2c0452b3114bcf139062c87c025842c3e)
- ref: b5e4c46be24d1fade0de

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23376451779)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260320-blueberry-aarch64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46.json)

### vs. base

- Geometric mean: 1.010x slower (HPT: reliability of 86.77%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260320-blueberry-aarch64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base-mem.svg)
- [📄table](bm-20260320-blueberry-aarch64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.md)
- [📈time plot](bm-20260320-blueberry-aarch64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23376451779)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46.json)

### vs. base

- Geometric mean: 1.057x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base-mem.svg)
- [📄table](bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.md)
- [📈time plot](bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23376451779)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260320-prometheus-amd64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46.json)

### vs. base

- Geometric mean: 1.220x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260320-prometheus-amd64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.md)
- [📈time plot](bm-20260320-prometheus-amd64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.svg)

