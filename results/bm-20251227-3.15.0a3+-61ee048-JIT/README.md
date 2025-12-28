# Results

- fork: python/61ee04834b096be00678
- version: 3.15.0a3+
- config: JIT
- commit hash: [61ee048](https://github.com/python/cpython/commit/61ee048)
- commit date: 2025-12-27T14:57:13+00:00
- commit merge base: [84fcdbd86ecd81f7cc793e22268a029ac6cf29c2](https://github.com/python/cpython/commit/84fcdbd86ecd81f7cc793e22268a029ac6cf29c2)
- ref: 61ee04834b096be00678

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20546232992)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251227-blueberry-aarch64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048.json)

### vs. base

- Geometric mean: 1.004x slower (HPT: reliability of 93.25%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251227-blueberry-aarch64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048-vs-base-mem.svg)
- [📄table](bm-20251227-blueberry-aarch64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048-vs-base.md)
- [📈time plot](bm-20251227-blueberry-aarch64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20546232992)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251227-ripley-x86_64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048.json)

### vs. base

- Geometric mean: 1.034x faster (HPT: reliability of 95.97%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251227-ripley-x86_64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048-vs-base-mem.svg)
- [📄table](bm-20251227-ripley-x86_64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048-vs-base.md)
- [📈time plot](bm-20251227-ripley-x86_64-python-61ee04834b096be00678-3.15.0a3%2B-61ee048-vs-base.svg)

