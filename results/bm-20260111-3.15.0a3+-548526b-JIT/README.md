# Results

- fork: python/548526bbbebd4e503470
- version: 3.15.0a3+
- config: JIT
- commit hash: [548526b](https://github.com/python/cpython/commit/548526b)
- commit date: 2026-01-11T20:42:55+00:00
- commit merge base: [9d13ca97c1a83ed649a16fb0512b5f1c5f9ad108](https://github.com/python/cpython/commit/9d13ca97c1a83ed649a16fb0512b5f1c5f9ad108)
- ref: 548526bbbebd4e503470

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20904264288)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260111-blueberry-aarch64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b.json)

### vs. base

- Geometric mean: 1.015x slower (HPT: reliability of 99.48%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260111-blueberry-aarch64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base-mem.svg)
- [📄table](bm-20260111-blueberry-aarch64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.md)
- [📈time plot](bm-20260111-blueberry-aarch64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20904264288)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b.json)

### vs. base

- Geometric mean: 1.043x faster (HPT: reliability of 99.23%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base-mem.svg)
- [📄table](bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.md)
- [📈time plot](bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20904264288)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260111-prometheus-amd64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b.json)

### vs. base

- Geometric mean: 1.154x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260111-prometheus-amd64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.md)
- [📈time plot](bm-20260111-prometheus-amd64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.svg)

