# Results

- fork: python/204febac457c39c6622c
- version: 3.16.0a0
- config: JIT
- commit hash: [204feba](https://github.com/python/cpython/commit/204feba)
- commit date: 2026-08-02T20:10:21+02:00
- commit merge base: [685ad027478d3c16e9843bb20ddec4711da3fcd0](https://github.com/python/cpython/commit/685ad027478d3c16e9843bb20ddec4711da3fcd0)
- ref: 204febac457c39c6622c

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30813731696)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260802-blueberry-aarch64-python-204febac457c39c6622c-3.16.0a0-204feba.json)

### vs. base

- Geometric mean: 1.007x slower (HPT: reliability of 81.34%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260802-blueberry-aarch64-python-204febac457c39c6622c-3.16.0a0-204feba-vs-base-mem.svg)
- [📄table](bm-20260802-blueberry-aarch64-python-204febac457c39c6622c-3.16.0a0-204feba-vs-base.md)
- [📈time plot](bm-20260802-blueberry-aarch64-python-204febac457c39c6622c-3.16.0a0-204feba-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/30813731696)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260802-ripley-x86_64-python-204febac457c39c6622c-3.16.0a0-204feba.json)

### vs. base

- Geometric mean: 1.075x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260802-ripley-x86_64-python-204febac457c39c6622c-3.16.0a0-204feba-vs-base-mem.svg)
- [📄table](bm-20260802-ripley-x86_64-python-204febac457c39c6622c-3.16.0a0-204feba-vs-base.md)
- [📈time plot](bm-20260802-ripley-x86_64-python-204febac457c39c6622c-3.16.0a0-204feba-vs-base.svg)

