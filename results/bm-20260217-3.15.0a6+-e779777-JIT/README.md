# Results

- fork: python/e779777c66595acc5991
- version: 3.15.0a6+
- config: JIT
- commit hash: [e779777](https://github.com/python/cpython/commit/e779777)
- commit date: 2026-02-17T23:03:22+01:00
- commit merge base: [d1b541b047e15bb6bddea50a64d71ddb01935e33](https://github.com/python/cpython/commit/d1b541b047e15bb6bddea50a64d71ddb01935e33)
- ref: e779777c66595acc5991

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22133822860)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260217-blueberry-aarch64-python-e779777c66595acc5991-3.15.0a6%2B-e779777.json)

### vs. base

- Geometric mean: 1.004x faster (HPT: reliability of 72.98%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260217-blueberry-aarch64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base-mem.svg)
- [📄table](bm-20260217-blueberry-aarch64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.md)
- [📈time plot](bm-20260217-blueberry-aarch64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22133822860)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260217-ripley-x86_64-python-e779777c66595acc5991-3.15.0a6%2B-e779777.json)

### vs. base

- Geometric mean: 1.033x faster (HPT: reliability of 92.51%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260217-ripley-x86_64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base-mem.svg)
- [📄table](bm-20260217-ripley-x86_64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.md)
- [📈time plot](bm-20260217-ripley-x86_64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.svg)

