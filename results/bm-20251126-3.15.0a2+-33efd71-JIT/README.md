# Results

- fork: python/33efd7178e269cbd0423
- version: 3.15.0a2+
- config: JIT
- commit hash: [33efd71](https://github.com/python/cpython/commit/33efd71)
- commit date: 2025-11-26T00:00:00Z
- commit merge base: [9f2a34af747e2fc95f3de8a3bb5e1d7ac10d6d04](https://github.com/python/cpython/commit/9f2a34af747e2fc95f3de8a3bb5e1d7ac10d6d04)
- commit date: 2025-11-26T00:00:00+00:00
- ref: 33efd7178e269cbd0423

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19688076213)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71.json)

### vs. base

- Geometric mean: 1.040x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base-mem.svg)
- [📄table](bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.md)
- [📈time plot](bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19688076213)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251126-ripley-x86_64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71.json)

### vs. base

- Geometric mean: 1.052x faster (HPT: reliability of 52.64%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251126-ripley-x86_64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base-mem.svg)
- [📄table](bm-20251126-ripley-x86_64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.md)
- [📈time plot](bm-20251126-ripley-x86_64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19688076213)
- cpu model: missing
- platform: macOS-15.6.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251126-jones-arm64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71.json)

### vs. base

- Geometric mean: 1.142x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251126-jones-arm64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base-mem.svg)
- [📄table](bm-20251126-jones-arm64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.md)
- [📈time plot](bm-20251126-jones-arm64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.svg)

