# Results

- fork: python/09233bd19879284395af
- version: 3.15.0a8+
- config: JIT
- commit hash: [09233bd](https://github.com/python/cpython/commit/09233bd)
- commit date: 2026-04-21T12:49:44-07:00
- commit merge base: [0b9146e90b4969af8cd6ed39c3d97bb71bfc6a7a](https://github.com/python/cpython/commit/0b9146e90b4969af8cd6ed39c3d97bb71bfc6a7a)
- ref: 09233bd19879284395af

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24771358605)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260421-blueberry-aarch64-python-09233bd19879284395af-3.15.0a8%2B-09233bd.json)

### vs. base

- Geometric mean: 1.005x slower (HPT: reliability of 98.60%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260421-blueberry-aarch64-python-09233bd19879284395af-3.15.0a8%2B-09233bd-vs-base-mem.svg)
- [📄table](bm-20260421-blueberry-aarch64-python-09233bd19879284395af-3.15.0a8%2B-09233bd-vs-base.md)
- [📈time plot](bm-20260421-blueberry-aarch64-python-09233bd19879284395af-3.15.0a8%2B-09233bd-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24771358605)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260421-ripley-x86_64-python-09233bd19879284395af-3.15.0a8%2B-09233bd.json)

### vs. base

- Geometric mean: 1.084x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260421-ripley-x86_64-python-09233bd19879284395af-3.15.0a8%2B-09233bd-vs-base-mem.svg)
- [📄table](bm-20260421-ripley-x86_64-python-09233bd19879284395af-3.15.0a8%2B-09233bd-vs-base.md)
- [📈time plot](bm-20260421-ripley-x86_64-python-09233bd19879284395af-3.15.0a8%2B-09233bd-vs-base.svg)

