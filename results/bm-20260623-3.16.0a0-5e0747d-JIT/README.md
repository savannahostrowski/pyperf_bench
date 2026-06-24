# Results

- fork: python/5e0747db2f5a063657a1
- version: 3.16.0a0
- config: JIT
- commit hash: [5e0747d](https://github.com/python/cpython/commit/5e0747d)
- commit date: 2026-06-23T16:31:47-04:00
- commit merge base: [10d1b63ed8b0261e7a9b7ffc3231eafd89187a4b](https://github.com/python/cpython/commit/10d1b63ed8b0261e7a9b7ffc3231eafd89187a4b)
- ref: 5e0747db2f5a063657a1

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28091087575)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260623-blueberry-aarch64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d.json)

### vs. base

- Geometric mean: 1.005x slower (HPT: reliability of 64.04%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260623-blueberry-aarch64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d-vs-base-mem.svg)
- [📄table](bm-20260623-blueberry-aarch64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d-vs-base.md)
- [📈time plot](bm-20260623-blueberry-aarch64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28091087575)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260623-ripley-x86_64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260623-ripley-x86_64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d-vs-base-mem.svg)
- [📄table](bm-20260623-ripley-x86_64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d-vs-base.md)
- [📈time plot](bm-20260623-ripley-x86_64-python-5e0747db2f5a063657a1-3.16.0a0-5e0747d-vs-base.svg)

