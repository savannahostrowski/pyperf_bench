# Results

- fork: python/83360b5869a4981c87dc
- version: 3.15.0a7+
- config: JIT
- commit hash: [83360b5](https://github.com/python/cpython/commit/83360b5)
- commit date: 2026-03-21T18:02:06+02:00
- commit merge base: [f6b5eed47de2de13da94332231eb9c3f4769c78d](https://github.com/python/cpython/commit/f6b5eed47de2de13da94332231eb9c3f4769c78d)
- ref: 83360b5869a4981c87dc

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23399903437)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260321-blueberry-aarch64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 91.18%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260321-blueberry-aarch64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base-mem.svg)
- [📄table](bm-20260321-blueberry-aarch64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base.md)
- [📈time plot](bm-20260321-blueberry-aarch64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23399903437)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260321-ripley-x86_64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5.json)

### vs. base

- Geometric mean: 1.061x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260321-ripley-x86_64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base-mem.svg)
- [📄table](bm-20260321-ripley-x86_64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base.md)
- [📈time plot](bm-20260321-ripley-x86_64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23399903437)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260321-prometheus-amd64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5.json)

### vs. base

- Geometric mean: 1.213x faster (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260321-prometheus-amd64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base.md)
- [📈time plot](bm-20260321-prometheus-amd64-python-83360b5869a4981c87dc-3.15.0a7%2B-83360b5-vs-base.svg)

