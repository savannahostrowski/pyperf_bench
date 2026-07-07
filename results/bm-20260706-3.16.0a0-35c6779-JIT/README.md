# Results

- fork: python/35c6779c7b5c4c2e2d97
- version: 3.16.0a0
- config: JIT
- commit hash: [35c6779](https://github.com/python/cpython/commit/35c6779)
- commit date: 2026-07-06T23:54:16+00:00
- commit merge base: [d7275d356916f839dc96aaa43a75e0bbde25732e](https://github.com/python/cpython/commit/d7275d356916f839dc96aaa43a75e0bbde25732e)
- ref: 35c6779c7b5c4c2e2d97

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28864160037)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260706-blueberry-aarch64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779.json)

### vs. base

- Geometric mean: 1.015x slower (HPT: reliability of 96.78%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260706-blueberry-aarch64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779-vs-base-mem.svg)
- [📄table](bm-20260706-blueberry-aarch64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779-vs-base.md)
- [📈time plot](bm-20260706-blueberry-aarch64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28864160037)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260706-ripley-x86_64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779.json)

### vs. base

- Geometric mean: 1.075x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260706-ripley-x86_64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779-vs-base-mem.svg)
- [📄table](bm-20260706-ripley-x86_64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779-vs-base.md)
- [📈time plot](bm-20260706-ripley-x86_64-python-35c6779c7b5c4c2e2d97-3.16.0a0-35c6779-vs-base.svg)

