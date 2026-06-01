# Results

- fork: python/f4bda4d6cb13d4c57fba
- version: 3.16.0a0
- config: JIT
- commit hash: [f4bda4d](https://github.com/python/cpython/commit/f4bda4d)
- commit date: 2026-05-31T20:28:02+01:00
- commit merge base: [2f8f569ba911ab3cff1356a15a3e688adc4ae917](https://github.com/python/cpython/commit/2f8f569ba911ab3cff1356a15a3e688adc4ae917)
- ref: f4bda4d6cb13d4c57fba

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26750411581)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260531-blueberry-aarch64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d.json)

### vs. base

- Geometric mean: 1.013x slower (HPT: reliability of 94.03%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260531-blueberry-aarch64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d-vs-base-mem.svg)
- [📄table](bm-20260531-blueberry-aarch64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d-vs-base.md)
- [📈time plot](bm-20260531-blueberry-aarch64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26750411581)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260531-ripley-x86_64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260531-ripley-x86_64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d-vs-base-mem.svg)
- [📄table](bm-20260531-ripley-x86_64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d-vs-base.md)
- [📈time plot](bm-20260531-ripley-x86_64-python-f4bda4d6cb13d4c57fba-3.16.0a0-f4bda4d-vs-base.svg)

