# Results

- fork: python/cf60e0c4527b910c93c8
- version: 3.15.0a5+
- config: JIT
- commit hash: [cf60e0c](https://github.com/python/cpython/commit/cf60e0c)
- commit date: 2026-02-06T09:54:34+01:00
- commit merge base: [56590f820e94987edf532f7b47772452a25d9c8f](https://github.com/python/cpython/commit/56590f820e94987edf532f7b47772452a25d9c8f)
- ref: cf60e0c4527b910c93c8

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21745327759)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c.json)

### vs. base

- Geometric mean: 1.008x faster (HPT: reliability of 63.03%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base-mem.svg)
- [📄table](bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.md)
- [📈time plot](bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21745327759)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260206-ripley-x86_64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c.json)

### vs. base

- Geometric mean: 1.033x faster (HPT: reliability of 90.95%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260206-ripley-x86_64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base-mem.svg)
- [📄table](bm-20260206-ripley-x86_64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.md)
- [📈time plot](bm-20260206-ripley-x86_64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21745327759)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260206-prometheus-amd64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c.json)

### vs. base

- Geometric mean: 1.144x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260206-prometheus-amd64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.md)
- [📈time plot](bm-20260206-prometheus-amd64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.svg)

