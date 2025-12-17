# Results

- fork: python/37fe9a90c5f99fd3830b
- version: 3.15.0a2+
- config: JIT
- commit hash: [37fe9a9](https://github.com/python/cpython/commit/37fe9a9)
- commit date: 2025-12-09T23:07:50Z
- commit merge base: [91884838bc3c47e02ab6099e6f9b12d80a0abae2](https://github.com/python/cpython/commit/91884838bc3c47e02ab6099e6f9b12d80a0abae2)
- commit date: 2025-12-09T23:07:50+00:00
- ref: 37fe9a90c5f99fd3830b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20082736483)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9.json)

### vs. base

- Geometric mean: 1.022x slower (HPT: reliability of 98.05%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg)
- [📄table](bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)
- [📈time plot](bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20082736483)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9.json)

### vs. base

- Geometric mean: 1.017x faster (HPT: reliability of 91.37%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg)
- [📄table](bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)
- [📈time plot](bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20082736483)
- cpu model: missing
- platform: macOS-26.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9.json)

### vs. base

- Geometric mean: 1.021x faster (HPT: reliability of 96.46%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg)
- [📄table](bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)
- [📈time plot](bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)

