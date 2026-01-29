# Results

- fork: python/6543720b63a62363de54
- version: 3.15.0a5+
- config: JIT
- commit hash: [6543720](https://github.com/python/cpython/commit/6543720)
- commit date: 2026-01-29T07:48:26+08:00
- commit merge base: [9b154aba7d08c0b5c72d1e415097852388e6d87b](https://github.com/python/cpython/commit/9b154aba7d08c0b5c72d1e415097852388e6d87b)
- ref: 6543720b63a62363de54

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21472450250)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260129-blueberry-aarch64-python-6543720b63a62363de54-3.15.0a5%2B-6543720.json)

### vs. base

- Geometric mean: 1.023x faster (HPT: reliability of 93.80%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260129-blueberry-aarch64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base-mem.svg)
- [📄table](bm-20260129-blueberry-aarch64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base.md)
- [📈time plot](bm-20260129-blueberry-aarch64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21472450250)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260129-ripley-x86_64-python-6543720b63a62363de54-3.15.0a5%2B-6543720.json)

### vs. base

- Geometric mean: 1.036x faster (HPT: reliability of 71.82%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260129-ripley-x86_64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base-mem.svg)
- [📄table](bm-20260129-ripley-x86_64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base.md)
- [📈time plot](bm-20260129-ripley-x86_64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21472450250)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260129-prometheus-amd64-python-6543720b63a62363de54-3.15.0a5%2B-6543720.json)

### vs. base

- Geometric mean: 1.148x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260129-prometheus-amd64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base.md)
- [📈time plot](bm-20260129-prometheus-amd64-python-6543720b63a62363de54-3.15.0a5%2B-6543720-vs-base.svg)

