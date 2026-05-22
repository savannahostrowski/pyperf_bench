# Results

- fork: python/3c298e2e385fc6f462ab
- version: 3.16.0a0
- config: JIT
- commit hash: [3c298e2](https://github.com/python/cpython/commit/3c298e2)
- commit date: 2026-05-21T21:44:13+00:00
- commit merge base: [65f99329edf5d0df3ee14d9a242e1a4c8b842211](https://github.com/python/cpython/commit/65f99329edf5d0df3ee14d9a242e1a4c8b842211)
- ref: 3c298e2e385fc6f462ab

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26281716208)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260521-blueberry-aarch64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 88.30%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260521-blueberry-aarch64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2-vs-base-mem.svg)
- [📄table](bm-20260521-blueberry-aarch64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2-vs-base.md)
- [📈time plot](bm-20260521-blueberry-aarch64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26281716208)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260521-ripley-x86_64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260521-ripley-x86_64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2-vs-base-mem.svg)
- [📄table](bm-20260521-ripley-x86_64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2-vs-base.md)
- [📈time plot](bm-20260521-ripley-x86_64-python-3c298e2e385fc6f462ab-3.16.0a0-3c298e2-vs-base.svg)

