# Results

- fork: python/89fe9857dd0832de9b59
- version: 3.16.0a0
- config: JIT
- commit hash: [89fe985](https://github.com/python/cpython/commit/89fe985)
- commit date: 2026-09-14T20:26:18-04:00
- commit merge base: [c6741161d30953d5c05d2ee11112ce6c97d9d3c1](https://github.com/python/cpython/commit/c6741161d30953d5c05d2ee11112ce6c97d9d3c1)
- ref: 89fe9857dd0832de9b59

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34980254216)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260914-blueberry-aarch64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 99.79%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260914-blueberry-aarch64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985-vs-base-mem.svg)
- [📄table](bm-20260914-blueberry-aarch64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985-vs-base.md)
- [📈time plot](bm-20260914-blueberry-aarch64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34980254216)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260914-ripley-x86_64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985.json)

### vs. base

- Geometric mean: 1.083x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260914-ripley-x86_64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985-vs-base-mem.svg)
- [📄table](bm-20260914-ripley-x86_64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985-vs-base.md)
- [📈time plot](bm-20260914-ripley-x86_64-python-89fe9857dd0832de9b59-3.16.0a0-89fe985-vs-base.svg)

