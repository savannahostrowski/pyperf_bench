# Results

- fork: python/c5fcdb4a9bd04b88f363
- version: 3.15.0a8+
- config: JIT
- commit hash: [c5fcdb4](https://github.com/python/cpython/commit/c5fcdb4)
- commit date: 2026-04-25T16:02:51-07:00
- commit merge base: [b2f126c4a0bad66d4b51028e8754a18e59ad84bb](https://github.com/python/cpython/commit/b2f126c4a0bad66d4b51028e8754a18e59ad84bb)
- ref: c5fcdb4a9bd04b88f363

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24953272613)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260425-blueberry-aarch64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4.json)

### vs. base

- Geometric mean: 1.010x faster (HPT: reliability of 52.95%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260425-blueberry-aarch64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base-mem.svg)
- [📄table](bm-20260425-blueberry-aarch64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.md)
- [📈time plot](bm-20260425-blueberry-aarch64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24953272613)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4.json)

### vs. base

- Geometric mean: 1.082x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base-mem.svg)
- [📄table](bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.md)
- [📈time plot](bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.svg)

