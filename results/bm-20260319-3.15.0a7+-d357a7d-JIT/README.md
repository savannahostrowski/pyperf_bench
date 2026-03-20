# Results

- fork: python/d357a7dbf38868844415
- version: 3.15.0a7+
- config: JIT
- commit hash: [d357a7d](https://github.com/python/cpython/commit/d357a7d)
- commit date: 2026-03-19T19:39:41-07:00
- commit merge base: [6b5511d66bab0754d1d959cfe98947c536bf4d82](https://github.com/python/cpython/commit/6b5511d66bab0754d1d959cfe98947c536bf4d82)
- ref: d357a7dbf38868844415

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23336497701)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260319-blueberry-aarch64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d.json)

### vs. base

- Geometric mean: 1.022x slower (HPT: reliability of 97.78%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260319-blueberry-aarch64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base-mem.svg)
- [📄table](bm-20260319-blueberry-aarch64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.md)
- [📈time plot](bm-20260319-blueberry-aarch64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23336497701)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260319-ripley-x86_64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d.json)

### vs. base

- Geometric mean: 1.049x faster (HPT: reliability of 99.83%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260319-ripley-x86_64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base-mem.svg)
- [📄table](bm-20260319-ripley-x86_64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.md)
- [📈time plot](bm-20260319-ripley-x86_64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23336497701)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260319-prometheus-amd64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d.json)

### vs. base

- Geometric mean: 1.218x faster (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260319-prometheus-amd64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.md)
- [📈time plot](bm-20260319-prometheus-amd64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.svg)

