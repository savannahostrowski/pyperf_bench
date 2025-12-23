# Results

- fork: python/9e513012341607458196
- version: 3.15.0a3+
- config: JIT
- commit hash: [9e51301](https://github.com/python/cpython/commit/9e51301)
- commit date: 2025-12-22T23:57:20+00:00
- commit merge base: [714037ba845a5a5168a7a8648befce203e2f0c24](https://github.com/python/cpython/commit/714037ba845a5a5168a7a8648befce203e2f0c24)
- ref: 9e513012341607458196

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20447458014)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251222-blueberry-aarch64-python-9e513012341607458196-3.15.0a3%2B-9e51301.json)

### vs. base

- Geometric mean: 1.024x slower (HPT: reliability of 99.92%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251222-blueberry-aarch64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base-mem.svg)
- [📄table](bm-20251222-blueberry-aarch64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.md)
- [📈time plot](bm-20251222-blueberry-aarch64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20447458014)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251222-ripley-x86_64-python-9e513012341607458196-3.15.0a3%2B-9e51301.json)

### vs. base

- Geometric mean: 1.038x faster (HPT: reliability of 94.45%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251222-ripley-x86_64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base-mem.svg)
- [📄table](bm-20251222-ripley-x86_64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.md)
- [📈time plot](bm-20251222-ripley-x86_64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.svg)

