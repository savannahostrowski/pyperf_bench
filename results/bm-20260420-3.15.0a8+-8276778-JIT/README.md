# Results

- fork: python/82767780f8de2fc49256
- version: 3.15.0a8+
- config: JIT
- commit hash: [8276778](https://github.com/python/cpython/commit/8276778)
- commit date: 2026-04-20T05:44:08+08:00
- commit merge base: [a8c9aa924b9795facc6bf1cafb37d2832289c9e6](https://github.com/python/cpython/commit/a8c9aa924b9795facc6bf1cafb37d2832289c9e6)
- ref: 82767780f8de2fc49256

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24659618805)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260420-blueberry-aarch64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778.json)

### vs. base

- Geometric mean: 1.000x faster (HPT: reliability of 86.94%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260420-blueberry-aarch64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base-mem.svg)
- [📄table](bm-20260420-blueberry-aarch64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.md)
- [📈time plot](bm-20260420-blueberry-aarch64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24659618805)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260420-ripley-x86_64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778.json)

### vs. base

- Geometric mean: 1.083x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260420-ripley-x86_64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base-mem.svg)
- [📄table](bm-20260420-ripley-x86_64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.md)
- [📈time plot](bm-20260420-ripley-x86_64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.svg)

