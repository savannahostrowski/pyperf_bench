# Results

- fork: python/9e1f1644cd7b7661f074
- version: 3.15.0a7+
- config: JIT
- commit hash: [9e1f164](https://github.com/python/cpython/commit/9e1f164)
- commit date: 2026-03-31T17:52:11-04:00
- commit merge base: [62a6e898e017c9878490544f6a227b8a187a949c](https://github.com/python/cpython/commit/62a6e898e017c9878490544f6a227b8a187a949c)
- ref: 9e1f1644cd7b7661f074

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23841970985)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260331-blueberry-aarch64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164.json)

### vs. base

- Geometric mean: 1.004x slower (HPT: reliability of 91.67%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260331-blueberry-aarch64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base-mem.svg)
- [📄table](bm-20260331-blueberry-aarch64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base.md)
- [📈time plot](bm-20260331-blueberry-aarch64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23841970985)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260331-ripley-x86_64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164.json)

### vs. base

- Geometric mean: 1.063x faster (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260331-ripley-x86_64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base-mem.svg)
- [📄table](bm-20260331-ripley-x86_64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base.md)
- [📈time plot](bm-20260331-ripley-x86_64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23841970985)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260331-prometheus-amd64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164.json)

### vs. base

- Geometric mean: 1.225x faster (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260331-prometheus-amd64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base.md)
- [📈time plot](bm-20260331-prometheus-amd64-python-9e1f1644cd7b7661f074-3.15.0a7%2B-9e1f164-vs-base.svg)

