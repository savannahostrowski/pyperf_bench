# Results

- fork: python/8801c6dec79275e9b588
- version: 3.15.0a2+
- config: JIT
- commit hash: [8801c6d](https://github.com/python/cpython/commit/8801c6d)
- commit date: 2025-12-02T20:33:40Z
- commit merge base: [d3c888b4ec15dbd7d6b6ef4f15b558af77c228af](https://github.com/python/cpython/commit/d3c888b4ec15dbd7d6b6ef4f15b558af77c228af)
- commit date: 2025-12-02T20:33:40+00:00
- ref: 8801c6dec79275e9b588

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19877760598)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d.json)

### vs. base

- Geometric mean: 1.042x slower (HPT: reliability of 99.97%, 1.01x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base-mem.svg)
- [📄table](bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.md)
- [📈time plot](bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19877760598)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251202-ripley-x86_64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d.json)

### vs. base

- Geometric mean: 1.018x faster (HPT: reliability of 57.75%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251202-ripley-x86_64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base-mem.svg)
- [📄table](bm-20251202-ripley-x86_64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.md)
- [📈time plot](bm-20251202-ripley-x86_64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19877760598)
- cpu model: missing
- platform: macOS-15.6.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251202-jones-arm64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d.json)

### vs. base

- Geometric mean: 1.072x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 dulwich_log
- [🧠memory plot](bm-20251202-jones-arm64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base-mem.svg)
- [📄table](bm-20251202-jones-arm64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.md)
- [📈time plot](bm-20251202-jones-arm64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.svg)

