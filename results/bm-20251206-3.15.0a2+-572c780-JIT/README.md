# Results

- fork: python/572c780aa875e4eb0096
- version: 3.15.0a2+
- config: JIT
- commit hash: [572c780](https://github.com/python/cpython/commit/572c780)
- commit date: 2025-12-06T22:37:34Z
- commit merge base: [332da6295f365b09cabf30a9222323b056ab1410](https://github.com/python/cpython/commit/332da6295f365b09cabf30a9222323b056ab1410)
- commit date: 2025-12-06T22:37:34+00:00
- ref: 572c780aa875e4eb0096

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19996243161)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251206-blueberry-aarch64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780.json)

### vs. base

- Geometric mean: 1.052x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251206-blueberry-aarch64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base-mem.svg)
- [📄table](bm-20251206-blueberry-aarch64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.md)
- [📈time plot](bm-20251206-blueberry-aarch64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19996243161)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251206-ripley-x86_64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780.json)

### vs. base

- Geometric mean: 1.021x faster (HPT: reliability of 51.40%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251206-ripley-x86_64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base-mem.svg)
- [📄table](bm-20251206-ripley-x86_64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.md)
- [📈time plot](bm-20251206-ripley-x86_64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19996243161)
- cpu model: missing
- platform: macOS-26.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251206-jones-arm64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780.json)

### vs. base

- Geometric mean: 1.026x faster (HPT: reliability of 87.04%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251206-jones-arm64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base-mem.svg)
- [📄table](bm-20251206-jones-arm64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.md)
- [📈time plot](bm-20251206-jones-arm64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.svg)

