# Results

- fork: python/c75d220e257ef7fda8d5
- version: 3.15.0a7+
- config: JIT
- commit hash: [c75d220](https://github.com/python/cpython/commit/c75d220)
- commit date: 2026-03-26T23:40:32+01:00
- commit merge base: [ca6dfa0f31132c80aaad40855087c2d931dc2d0f](https://github.com/python/cpython/commit/ca6dfa0f31132c80aaad40855087c2d931dc2d0f)
- ref: c75d220e257ef7fda8d5

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23639608287)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260326-blueberry-aarch64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220.json)

### vs. base

- Geometric mean: 1.002x slower (HPT: reliability of 79.76%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260326-blueberry-aarch64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base-mem.svg)
- [📄table](bm-20260326-blueberry-aarch64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base.md)
- [📈time plot](bm-20260326-blueberry-aarch64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23639608287)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260326-ripley-x86_64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260326-ripley-x86_64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base-mem.svg)
- [📄table](bm-20260326-ripley-x86_64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base.md)
- [📈time plot](bm-20260326-ripley-x86_64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23639608287)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260326-prometheus-amd64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220.json)

### vs. base

- Geometric mean: 1.219x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260326-prometheus-amd64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base.md)
- [📈time plot](bm-20260326-prometheus-amd64-python-c75d220e257ef7fda8d5-3.15.0a7%2B-c75d220-vs-base.svg)

