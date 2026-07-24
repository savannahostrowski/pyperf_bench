# Results

- fork: python/66e313f471516bfa04c5
- version: 3.16.0a0
- config: JIT
- commit hash: [66e313f](https://github.com/python/cpython/commit/66e313f)
- commit date: 2026-07-23T17:28:39+00:00
- commit merge base: [2b4e062a277f888c0139ac7196c2b6dcaed795dc](https://github.com/python/cpython/commit/2b4e062a277f888c0139ac7196c2b6dcaed795dc)
- ref: 66e313f471516bfa04c5

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30088353556)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260723-blueberry-aarch64-python-66e313f471516bfa04c5-3.16.0a0-66e313f.json)

### vs. base

- Geometric mean: 1.010x slower (HPT: reliability of 85.32%, 1.00x slower at 99th %ile)
- Memory usage: 1.06x
- [🧠memory plot](bm-20260723-blueberry-aarch64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base-mem.svg)
- [📄table](bm-20260723-blueberry-aarch64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.md)
- [📈time plot](bm-20260723-blueberry-aarch64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30088353556)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260723-ripley-x86_64-python-66e313f471516bfa04c5-3.16.0a0-66e313f.json)

### vs. base

- Geometric mean: 1.070x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260723-ripley-x86_64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base-mem.svg)
- [📄table](bm-20260723-ripley-x86_64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.md)
- [📈time plot](bm-20260723-ripley-x86_64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.svg)

