# Results

- fork: python/87b120fdb58afd8f7cb7
- version: 3.16.0a0
- config: JIT
- commit hash: [87b120f](https://github.com/python/cpython/commit/87b120f)
- commit date: 2026-08-09T21:06:42+00:00
- commit merge base: [1286d4398e505f70f97e50edda6b0341f16ca267](https://github.com/python/cpython/commit/1286d4398e505f70f97e50edda6b0341f16ca267)
- ref: 87b120fdb58afd8f7cb7

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31378649075)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260809-blueberry-aarch64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f.json)

### vs. base

- Geometric mean: 1.020x slower (HPT: reliability of 99.21%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260809-blueberry-aarch64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f-vs-base-mem.svg)
- [📄table](bm-20260809-blueberry-aarch64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f-vs-base.md)
- [📈time plot](bm-20260809-blueberry-aarch64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31378649075)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260809-ripley-x86_64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f.json)

### vs. base

- Geometric mean: 1.080x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260809-ripley-x86_64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f-vs-base-mem.svg)
- [📄table](bm-20260809-ripley-x86_64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f-vs-base.md)
- [📈time plot](bm-20260809-ripley-x86_64-python-87b120fdb58afd8f7cb7-3.16.0a0-87b120f-vs-base.svg)

