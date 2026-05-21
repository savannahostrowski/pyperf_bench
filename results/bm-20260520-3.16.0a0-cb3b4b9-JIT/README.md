# Results

- fork: python/cb3b4b98d8d141c9de04
- version: 3.16.0a0
- config: JIT
- commit hash: [cb3b4b9](https://github.com/python/cpython/commit/cb3b4b9)
- commit date: 2026-05-20T12:40:15-07:00
- commit merge base: [87a879f4d0ec2e545e84c898c5ce452a6c87b09e](https://github.com/python/cpython/commit/87a879f4d0ec2e545e84c898c5ce452a6c87b09e)
- ref: cb3b4b98d8d141c9de04

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26220075455)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260520-blueberry-aarch64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9.json)

### vs. base

- Geometric mean: 1.014x slower (HPT: reliability of 92.93%, 1.00x slower at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260520-blueberry-aarch64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9-vs-base-mem.svg)
- [📄table](bm-20260520-blueberry-aarch64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9-vs-base.md)
- [📈time plot](bm-20260520-blueberry-aarch64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/26220075455)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260520-ripley-x86_64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260520-ripley-x86_64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9-vs-base-mem.svg)
- [📄table](bm-20260520-ripley-x86_64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9-vs-base.md)
- [📈time plot](bm-20260520-ripley-x86_64-python-cb3b4b98d8d141c9de04-3.16.0a0-cb3b4b9-vs-base.svg)

