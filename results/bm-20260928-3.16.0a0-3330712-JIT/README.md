# Results

- fork: python/333071231d3a46cccc32
- version: 3.16.0a0
- config: JIT
- commit hash: [3330712](https://github.com/python/cpython/commit/3330712)
- commit date: 2026-09-28T19:18:28+00:00
- commit merge base: [6e32490d922cc0b9376f06da0325e79fb6fb8ef8](https://github.com/python/cpython/commit/6e32490d922cc0b9376f06da0325e79fb6fb8ef8)
- ref: 333071231d3a46cccc32

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/36590911882)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260928-blueberry-aarch64-python-333071231d3a46cccc32-3.16.0a0-3330712.json)

### vs. base

- Geometric mean: 1.004x faster (HPT: reliability of 79.02%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260928-blueberry-aarch64-python-333071231d3a46cccc32-3.16.0a0-3330712-vs-base-mem.svg)
- [📄table](bm-20260928-blueberry-aarch64-python-333071231d3a46cccc32-3.16.0a0-3330712-vs-base.md)
- [📈time plot](bm-20260928-blueberry-aarch64-python-333071231d3a46cccc32-3.16.0a0-3330712-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/36590911882)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260928-ripley-x86_64-python-333071231d3a46cccc32-3.16.0a0-3330712.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260928-ripley-x86_64-python-333071231d3a46cccc32-3.16.0a0-3330712-vs-base-mem.svg)
- [📄table](bm-20260928-ripley-x86_64-python-333071231d3a46cccc32-3.16.0a0-3330712-vs-base.md)
- [📈time plot](bm-20260928-ripley-x86_64-python-333071231d3a46cccc32-3.16.0a0-3330712-vs-base.svg)

