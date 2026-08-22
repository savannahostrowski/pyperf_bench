# Results

- fork: python/999a046b24cff4ba0e72
- version: 3.16.0a0
- config: JIT
- commit hash: [999a046](https://github.com/python/cpython/commit/999a046)
- commit date: 2026-08-21T10:02:24-07:00
- commit merge base: [862befdb99c8268f570c28adaa342eb6586fa0dc](https://github.com/python/cpython/commit/862befdb99c8268f570c28adaa342eb6586fa0dc)
- ref: 999a046b24cff4ba0e72

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32565097486)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260821-blueberry-aarch64-python-999a046b24cff4ba0e72-3.16.0a0-999a046.json)

### vs. base

- Geometric mean: 1.010x slower (HPT: reliability of 92.95%, 1.00x slower at 99th %ile)
- Memory usage: 1.06x
- [🧠memory plot](bm-20260821-blueberry-aarch64-python-999a046b24cff4ba0e72-3.16.0a0-999a046-vs-base-mem.svg)
- [📄table](bm-20260821-blueberry-aarch64-python-999a046b24cff4ba0e72-3.16.0a0-999a046-vs-base.md)
- [📈time plot](bm-20260821-blueberry-aarch64-python-999a046b24cff4ba0e72-3.16.0a0-999a046-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/32565097486)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260821-ripley-x86_64-python-999a046b24cff4ba0e72-3.16.0a0-999a046.json)

### vs. base

- Geometric mean: 1.079x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260821-ripley-x86_64-python-999a046b24cff4ba0e72-3.16.0a0-999a046-vs-base-mem.svg)
- [📄table](bm-20260821-ripley-x86_64-python-999a046b24cff4ba0e72-3.16.0a0-999a046-vs-base.md)
- [📈time plot](bm-20260821-ripley-x86_64-python-999a046b24cff4ba0e72-3.16.0a0-999a046-vs-base.svg)

