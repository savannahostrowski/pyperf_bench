# Results

- fork: python/565685f6e88fd333326b
- version: 3.15.0a5+
- config: JIT
- commit hash: [565685f](https://github.com/python/cpython/commit/565685f)
- commit date: 2026-01-15T10:41:08+02:00
- commit merge base: [421bd1770a87d141f66754ae29e407589e44ce83](https://github.com/python/cpython/commit/421bd1770a87d141f66754ae29e407589e44ce83)
- ref: 565685f6e88fd333326b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21025765521)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f.json)

### vs. base

- Geometric mean: 1.016x faster (HPT: reliability of 63.03%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base-mem.svg)
- [📄table](bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base.md)
- [📈time plot](bm-20260115-blueberry-aarch64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21025765521)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260115-ripley-x86_64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f.json)

### vs. base

- Geometric mean: 1.049x faster (HPT: reliability of 99.74%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260115-ripley-x86_64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base-mem.svg)
- [📄table](bm-20260115-ripley-x86_64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base.md)
- [📈time plot](bm-20260115-ripley-x86_64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21025765521)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260115-prometheus-amd64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f.json)

### vs. base

- Geometric mean: 1.162x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260115-prometheus-amd64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base.md)
- [📈time plot](bm-20260115-prometheus-amd64-python-565685f6e88fd333326b-3.15.0a5%2B-565685f-vs-base.svg)

