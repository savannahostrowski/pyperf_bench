# Results

- fork: python/2f7634c0291c92cf1e04
- version: 3.15.0a6+
- config: JIT
- commit hash: [2f7634c](https://github.com/python/cpython/commit/2f7634c)
- commit date: 2026-02-16T18:28:21-08:00
- commit merge base: [18c04f2e2a7e47329e9eefc5f269afe2d68729b0](https://github.com/python/cpython/commit/18c04f2e2a7e47329e9eefc5f269afe2d68729b0)
- ref: 2f7634c0291c92cf1e04

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22092790032)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260216-blueberry-aarch64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c.json)

### vs. base

- Geometric mean: 1.009x faster (HPT: reliability of 57.42%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260216-blueberry-aarch64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base-mem.svg)
- [📄table](bm-20260216-blueberry-aarch64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base.md)
- [📈time plot](bm-20260216-blueberry-aarch64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22092790032)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260216-ripley-x86_64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c.json)

### vs. base

- Geometric mean: 1.036x faster (HPT: reliability of 93.77%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260216-ripley-x86_64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base-mem.svg)
- [📄table](bm-20260216-ripley-x86_64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base.md)
- [📈time plot](bm-20260216-ripley-x86_64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22092790032)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260216-prometheus-amd64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c.json)

### vs. base

- Geometric mean: 1.149x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260216-prometheus-amd64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base.md)
- [📈time plot](bm-20260216-prometheus-amd64-python-2f7634c0291c92cf1e04-3.15.0a6%2B-2f7634c-vs-base.svg)

