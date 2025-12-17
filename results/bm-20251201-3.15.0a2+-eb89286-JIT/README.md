# Results

- fork: python/eb892868b31322d7cf27
- version: 3.15.0a2+
- config: JIT
- commit hash: [eb89286](https://github.com/python/cpython/commit/eb89286)
- commit date: 2025-12-01T19:04:47-05:00
- commit merge base: [e32c9756408a3b88394f687c4f55789a8bd21b73](https://github.com/python/cpython/commit/e32c9756408a3b88394f687c4f55789a8bd21b73)
- ref: eb892868b31322d7cf27

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19841958144)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251201-blueberry-aarch64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286.json)

### vs. base

- Geometric mean: 1.168x slower (HPT: reliability of 100.00%, 1.06x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251201-blueberry-aarch64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base-mem.svg)
- [📄table](bm-20251201-blueberry-aarch64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.md)
- [📈time plot](bm-20251201-blueberry-aarch64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19841958144)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251201-ripley-x86_64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286.json)

### vs. base

- Geometric mean: 1.014x faster (HPT: reliability of 64.82%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251201-ripley-x86_64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base-mem.svg)
- [📄table](bm-20251201-ripley-x86_64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.md)
- [📈time plot](bm-20251201-ripley-x86_64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19841958144)
- cpu model: missing
- platform: macOS-15.6.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251201-jones-arm64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286.json)

### vs. base

- Geometric mean: 1.067x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251201-jones-arm64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base-mem.svg)
- [📄table](bm-20251201-jones-arm64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.md)
- [📈time plot](bm-20251201-jones-arm64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.svg)

