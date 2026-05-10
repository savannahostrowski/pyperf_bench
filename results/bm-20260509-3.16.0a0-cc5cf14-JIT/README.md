# Results

- fork: python/cc5cf14ae0a3665ba9d1
- version: 3.16.0a0
- config: JIT
- commit hash: [cc5cf14](https://github.com/python/cpython/commit/cc5cf14)
- commit date: 2026-05-09T14:39:01-07:00
- commit merge base: [4e97ff3351f381a61b238bd8e805e4e8dd3ea5cf](https://github.com/python/cpython/commit/4e97ff3351f381a61b238bd8e805e4e8dd3ea5cf)
- ref: cc5cf14ae0a3665ba9d1

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25625361352)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260509-blueberry-aarch64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14.json)

### vs. base

- Geometric mean: 1.013x slower (HPT: reliability of 93.91%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260509-blueberry-aarch64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14-vs-base-mem.svg)
- [📄table](bm-20260509-blueberry-aarch64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14-vs-base.md)
- [📈time plot](bm-20260509-blueberry-aarch64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25625361352)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260509-ripley-x86_64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14.json)

### vs. base

- Geometric mean: 1.067x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260509-ripley-x86_64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14-vs-base-mem.svg)
- [📄table](bm-20260509-ripley-x86_64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14-vs-base.md)
- [📈time plot](bm-20260509-ripley-x86_64-python-cc5cf14ae0a3665ba9d1-3.16.0a0-cc5cf14-vs-base.svg)

