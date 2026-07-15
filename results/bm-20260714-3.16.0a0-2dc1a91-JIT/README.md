# Results

- fork: python/2dc1a91af801ea896e21
- version: 3.16.0a0
- config: JIT
- commit hash: [2dc1a91](https://github.com/python/cpython/commit/2dc1a91)
- commit date: 2026-07-14T06:38:43+08:00
- commit merge base: [701a7c5408f689b26c46ed7ed13879375fa82959](https://github.com/python/cpython/commit/701a7c5408f689b26c46ed7ed13879375fa82959)
- ref: 2dc1a91af801ea896e21

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29326768322)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260714-blueberry-aarch64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91.json)

### vs. base

- Geometric mean: 1.008x slower (HPT: reliability of 82.92%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260714-blueberry-aarch64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91-vs-base-mem.svg)
- [📄table](bm-20260714-blueberry-aarch64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91-vs-base.md)
- [📈time plot](bm-20260714-blueberry-aarch64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/29326768322)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260714-ripley-x86_64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91.json)

### vs. base

- Geometric mean: 1.071x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260714-ripley-x86_64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91-vs-base-mem.svg)
- [📄table](bm-20260714-ripley-x86_64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91-vs-base.md)
- [📈time plot](bm-20260714-ripley-x86_64-python-2dc1a91af801ea896e21-3.16.0a0-2dc1a91-vs-base.svg)

