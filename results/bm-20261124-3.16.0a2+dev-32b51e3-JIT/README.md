# Results

- fork: python/32b51e34318e6dd355f3
- version: 3.16.0a2+dev
- config: JIT
- commit hash: [32b51e3](https://github.com/python/cpython/commit/32b51e3)
- commit date: 2026-11-24T12:52:33+08:00
- commit merge base: [187da85d248a884d47da2ae14573676a5af3240e](https://github.com/python/cpython/commit/187da85d248a884d47da2ae14573676a5af3240e)
- ref: 32b51e34318e6dd355f3

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/45476294269)
- cpu model: missing
- platform: Linux-6.12.115+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20261124-blueberry-aarch64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3.json)

### vs. base

- Geometric mean: 1.013x faster (HPT: reliability of 76.33%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20261124-blueberry-aarch64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3-vs-base-mem.svg)
- [📄table](bm-20261124-blueberry-aarch64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3-vs-base.md)
- [📈time plot](bm-20261124-blueberry-aarch64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/45476294269)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-149-generic-x86_64-with-glibc2.39
- [raw results](bm-20261124-ripley-x86_64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3.json)

### vs. base

- Geometric mean: 1.090x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20261124-ripley-x86_64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3-vs-base-mem.svg)
- [📄table](bm-20261124-ripley-x86_64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3-vs-base.md)
- [📈time plot](bm-20261124-ripley-x86_64-python-32b51e34318e6dd355f3-3.16.0a2%2Bdev-32b51e3-vs-base.svg)

