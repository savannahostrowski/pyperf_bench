# Results

- fork: python/e12ee02a164c87865b78
- version: 3.16.0a0
- config: JIT
- commit hash: [e12ee02](https://github.com/python/cpython/commit/e12ee02)
- commit date: 2026-08-05T19:57:06+00:00
- commit merge base: [4bbc20bd6dc9418a89d77f0b268aaec8843bf9d0](https://github.com/python/cpython/commit/4bbc20bd6dc9418a89d77f0b268aaec8843bf9d0)
- ref: e12ee02a164c87865b78

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31097258968)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260805-blueberry-aarch64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02.json)

### vs. base

- Geometric mean: 1.019x slower (HPT: reliability of 97.92%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260805-blueberry-aarch64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02-vs-base-mem.svg)
- [📄table](bm-20260805-blueberry-aarch64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02-vs-base.md)
- [📈time plot](bm-20260805-blueberry-aarch64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/31097258968)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260805-ripley-x86_64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02.json)

### vs. base

- Geometric mean: 1.069x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260805-ripley-x86_64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02-vs-base-mem.svg)
- [📄table](bm-20260805-ripley-x86_64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02-vs-base.md)
- [📈time plot](bm-20260805-ripley-x86_64-python-e12ee02a164c87865b78-3.16.0a0-e12ee02-vs-base.svg)

