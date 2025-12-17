# Results

- fork: python/c90863ac3dcbc5b0b8f9
- version: 3.15.0a2+
- config: JIT
- commit hash: [c90863a](https://github.com/python/cpython/commit/c90863a)
- commit date: 2025-12-12T21:23:18Z
- commit merge base: [0a97941245f1dda6d838f9aaf0512104e5253929](https://github.com/python/cpython/commit/0a97941245f1dda6d838f9aaf0512104e5253929)
- commit date: 2025-12-12T21:23:18+00:00
- ref: c90863ac3dcbc5b0b8f9

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20183519132)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251212-blueberry-aarch64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 96.14%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251212-blueberry-aarch64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base-mem.svg)
- [📄table](bm-20251212-blueberry-aarch64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.md)
- [📈time plot](bm-20251212-blueberry-aarch64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20183519132)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a.json)

### vs. base

- Geometric mean: 1.025x faster (HPT: reliability of 88.69%, 1.00x faster at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base-mem.svg)
- [📄table](bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.md)
- [📈time plot](bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20183519132)
- cpu model: missing
- platform: macOS-26.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a.json)

### vs. base

- Geometric mean: 1.088x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [🧠memory plot](bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base-mem.svg)
- [📄table](bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.md)
- [📈time plot](bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.svg)

