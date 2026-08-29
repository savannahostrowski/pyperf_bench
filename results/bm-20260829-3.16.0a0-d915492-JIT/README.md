# Results

- fork: python/d915492413869d616e26
- version: 3.16.0a0
- config: JIT
- commit hash: [d915492](https://github.com/python/cpython/commit/d915492)
- commit date: 2026-08-29T03:37:45+00:00
- commit merge base: [3e245faf34efc41c39bbe76071e6edb7a62692a8](https://github.com/python/cpython/commit/3e245faf34efc41c39bbe76071e6edb7a62692a8)
- ref: d915492413869d616e26

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33257117206)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260829-blueberry-aarch64-python-d915492413869d616e26-3.16.0a0-d915492.json)

### vs. base

- Geometric mean: 1.013x slower (HPT: reliability of 95.62%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260829-blueberry-aarch64-python-d915492413869d616e26-3.16.0a0-d915492-vs-base-mem.svg)
- [📄table](bm-20260829-blueberry-aarch64-python-d915492413869d616e26-3.16.0a0-d915492-vs-base.md)
- [📈time plot](bm-20260829-blueberry-aarch64-python-d915492413869d616e26-3.16.0a0-d915492-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/33257117206)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260829-ripley-x86_64-python-d915492413869d616e26-3.16.0a0-d915492.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260829-ripley-x86_64-python-d915492413869d616e26-3.16.0a0-d915492-vs-base-mem.svg)
- [📄table](bm-20260829-ripley-x86_64-python-d915492413869d616e26-3.16.0a0-d915492-vs-base.md)
- [📈time plot](bm-20260829-ripley-x86_64-python-d915492413869d616e26-3.16.0a0-d915492-vs-base.svg)

