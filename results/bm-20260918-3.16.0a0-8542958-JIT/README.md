# Results

- fork: python/854295809ad5a42c9461
- version: 3.16.0a0
- config: JIT
- commit hash: [8542958](https://github.com/python/cpython/commit/8542958)
- commit date: 2026-09-18T00:32:50+00:00
- commit merge base: [5539c2a5437acc4f4719aabac375368e0d310bd9](https://github.com/python/cpython/commit/5539c2a5437acc4f4719aabac375368e0d310bd9)
- ref: 854295809ad5a42c9461

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35350550841)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260918-blueberry-aarch64-python-854295809ad5a42c9461-3.16.0a0-8542958.json)

### vs. base

- Geometric mean: 1.028x slower (HPT: reliability of 99.95%, 1.00x slower at 99th %ile)
- Memory usage: 1.07x
- [🧠memory plot](bm-20260918-blueberry-aarch64-python-854295809ad5a42c9461-3.16.0a0-8542958-vs-base-mem.svg)
- [📄table](bm-20260918-blueberry-aarch64-python-854295809ad5a42c9461-3.16.0a0-8542958-vs-base.md)
- [📈time plot](bm-20260918-blueberry-aarch64-python-854295809ad5a42c9461-3.16.0a0-8542958-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/35350550841)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260918-ripley-x86_64-python-854295809ad5a42c9461-3.16.0a0-8542958.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260918-ripley-x86_64-python-854295809ad5a42c9461-3.16.0a0-8542958-vs-base-mem.svg)
- [📄table](bm-20260918-ripley-x86_64-python-854295809ad5a42c9461-3.16.0a0-8542958-vs-base.md)
- [📈time plot](bm-20260918-ripley-x86_64-python-854295809ad5a42c9461-3.16.0a0-8542958-vs-base.svg)

