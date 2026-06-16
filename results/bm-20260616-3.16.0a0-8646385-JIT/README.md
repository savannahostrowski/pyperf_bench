# Results

- fork: python/8646385076ea4f6ef086
- version: 3.16.0a0
- config: JIT
- commit hash: [8646385](https://github.com/python/cpython/commit/8646385)
- commit date: 2026-06-16T06:16:16+08:00
- commit merge base: [5ea1e907d1928c1e08cf4246e8935d62a95ca8a1](https://github.com/python/cpython/commit/5ea1e907d1928c1e08cf4246e8935d62a95ca8a1)
- ref: 8646385076ea4f6ef086

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27611936675)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260616-blueberry-aarch64-python-8646385076ea4f6ef086-3.16.0a0-8646385.json)

### vs. base

- Geometric mean: 1.012x slower (HPT: reliability of 83.95%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260616-blueberry-aarch64-python-8646385076ea4f6ef086-3.16.0a0-8646385-vs-base-mem.svg)
- [📄table](bm-20260616-blueberry-aarch64-python-8646385076ea4f6ef086-3.16.0a0-8646385-vs-base.md)
- [📈time plot](bm-20260616-blueberry-aarch64-python-8646385076ea4f6ef086-3.16.0a0-8646385-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27611936675)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260616-ripley-x86_64-python-8646385076ea4f6ef086-3.16.0a0-8646385.json)

### vs. base

- Geometric mean: 1.076x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260616-ripley-x86_64-python-8646385076ea4f6ef086-3.16.0a0-8646385-vs-base-mem.svg)
- [📄table](bm-20260616-ripley-x86_64-python-8646385076ea4f6ef086-3.16.0a0-8646385-vs-base.md)
- [📈time plot](bm-20260616-ripley-x86_64-python-8646385076ea4f6ef086-3.16.0a0-8646385-vs-base.svg)

