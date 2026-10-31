# Results

- fork: python/4a9b98115fec4d93c32c
- version: 3.16.0a1+dev
- config: JIT
- commit hash: [4a9b981](https://github.com/python/cpython/commit/4a9b981)
- commit date: 2026-10-30T14:29:45+00:00
- commit merge base: [32fe0cca23d9e9677107abe4d701cb20768c7926](https://github.com/python/cpython/commit/32fe0cca23d9e9677107abe4d701cb20768c7926)
- ref: 4a9b98115fec4d93c32c

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/41213628872)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261030-blueberry-aarch64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981.json)

### vs. base

- Geometric mean: 1.001x slower (HPT: reliability of 78.88%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20261030-blueberry-aarch64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981-vs-base-mem.svg)
- [📄table](bm-20261030-blueberry-aarch64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981-vs-base.md)
- [📈time plot](bm-20261030-blueberry-aarch64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/41213628872)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-142-generic-x86_64-with-glibc2.39
- [raw results](bm-20261030-ripley-x86_64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981.json)

### vs. base

- Geometric mean: 1.085x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20261030-ripley-x86_64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981-vs-base-mem.svg)
- [📄table](bm-20261030-ripley-x86_64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981-vs-base.md)
- [📈time plot](bm-20261030-ripley-x86_64-python-4a9b98115fec4d93c32c-3.16.0a1%2Bdev-4a9b981-vs-base.svg)

