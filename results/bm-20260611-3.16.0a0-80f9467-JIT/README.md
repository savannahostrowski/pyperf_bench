# Results

- fork: python/80f9467434cecbc4e97b
- version: 3.16.0a0
- config: JIT
- commit hash: [80f9467](https://github.com/python/cpython/commit/80f9467)
- commit date: 2026-06-11T18:11:52-04:00
- commit merge base: [71805db4294de9495954571c82a835d94ba67594](https://github.com/python/cpython/commit/71805db4294de9495954571c82a835d94ba67594)
- ref: 80f9467434cecbc4e97b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27410387664)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260611-blueberry-aarch64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467.json)

### vs. base

- Geometric mean: 1.012x slower (HPT: reliability of 90.55%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260611-blueberry-aarch64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467-vs-base-mem.svg)
- [📄table](bm-20260611-blueberry-aarch64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467-vs-base.md)
- [📈time plot](bm-20260611-blueberry-aarch64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27410387664)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260611-ripley-x86_64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260611-ripley-x86_64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467-vs-base-mem.svg)
- [📄table](bm-20260611-ripley-x86_64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467-vs-base.md)
- [📈time plot](bm-20260611-ripley-x86_64-python-80f9467434cecbc4e97b-3.16.0a0-80f9467-vs-base.svg)

