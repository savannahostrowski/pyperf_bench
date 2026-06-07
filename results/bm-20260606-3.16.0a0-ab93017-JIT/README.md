# Results

- fork: python/ab930175e7e909aaa3ec
- version: 3.16.0a0
- config: JIT
- commit hash: [ab93017](https://github.com/python/cpython/commit/ab93017)
- commit date: 2026-06-06T21:38:15+00:00
- commit merge base: [69851a64076cc240513b834d87d654064f7ac597](https://github.com/python/cpython/commit/69851a64076cc240513b834d87d654064f7ac597)
- ref: ab930175e7e909aaa3ec

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27089388310)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260606-blueberry-aarch64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 78.90%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260606-blueberry-aarch64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017-vs-base-mem.svg)
- [📄table](bm-20260606-blueberry-aarch64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017-vs-base.md)
- [📈time plot](bm-20260606-blueberry-aarch64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27089388310)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260606-ripley-x86_64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017.json)

### vs. base

- Geometric mean: 1.068x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20260606-ripley-x86_64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017-vs-base-mem.svg)
- [📄table](bm-20260606-ripley-x86_64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017-vs-base.md)
- [📈time plot](bm-20260606-ripley-x86_64-python-ab930175e7e909aaa3ec-3.16.0a0-ab93017-vs-base.svg)

