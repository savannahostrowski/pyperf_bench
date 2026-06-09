# Results

- fork: python/29a920e80e21490b5bdb
- version: 3.16.0a0
- config: JIT
- commit hash: [29a920e](https://github.com/python/cpython/commit/29a920e)
- commit date: 2026-06-08T22:38:14+03:00
- commit merge base: [fccf67a35449920484ea11d8a16566b58b0c4519](https://github.com/python/cpython/commit/fccf67a35449920484ea11d8a16566b58b0c4519)
- ref: 29a920e80e21490b5bdb

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27199563047)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260608-blueberry-aarch64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e.json)

### vs. base

- Geometric mean: 1.012x slower (HPT: reliability of 89.98%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260608-blueberry-aarch64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e-vs-base-mem.svg)
- [📄table](bm-20260608-blueberry-aarch64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e-vs-base.md)
- [📈time plot](bm-20260608-blueberry-aarch64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27199563047)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260608-ripley-x86_64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e.json)

### vs. base

- Geometric mean: 1.072x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260608-ripley-x86_64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e-vs-base-mem.svg)
- [📄table](bm-20260608-ripley-x86_64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e-vs-base.md)
- [📈time plot](bm-20260608-ripley-x86_64-python-29a920e80e21490b5bdb-3.16.0a0-29a920e-vs-base.svg)

