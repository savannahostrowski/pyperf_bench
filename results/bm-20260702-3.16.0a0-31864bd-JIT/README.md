# Results

- fork: python/31864bd9a683c93bd9b2
- version: 3.16.0a0
- config: JIT
- commit hash: [31864bd](https://github.com/python/cpython/commit/31864bd)
- commit date: 2026-07-02T20:04:53+02:00
- commit merge base: [8b430d6f740541f1b9045a89dde43abee2c54bc5](https://github.com/python/cpython/commit/8b430d6f740541f1b9045a89dde43abee2c54bc5)
- ref: 31864bd9a683c93bd9b2

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28657957854)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260702-blueberry-aarch64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd.json)

### vs. base

- Geometric mean: 1.008x slower (HPT: reliability of 83.80%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260702-blueberry-aarch64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd-vs-base-mem.svg)
- [📄table](bm-20260702-blueberry-aarch64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd-vs-base.md)
- [📈time plot](bm-20260702-blueberry-aarch64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28657957854)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260702-ripley-x86_64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260702-ripley-x86_64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd-vs-base-mem.svg)
- [📄table](bm-20260702-ripley-x86_64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd-vs-base.md)
- [📈time plot](bm-20260702-ripley-x86_64-python-31864bd9a683c93bd9b2-3.16.0a0-31864bd-vs-base.svg)

