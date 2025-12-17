# Results

- fork: python/5ec03cf3b086fd01614c
- version: 3.15.0a2+
- config: JIT
- commit hash: [5ec03cf](https://github.com/python/cpython/commit/5ec03cf)
- commit date: 2025-11-27T22:22:21Z
- commit merge base: [656a64b37f817cc8fe36ee17f332100482185cce](https://github.com/python/cpython/commit/656a64b37f817cc8fe36ee17f332100482185cce)
- commit date: 2025-11-27T22:22:21+00:00
- ref: 5ec03cf3b086fd01614c

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19750440568)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251127-blueberry-aarch64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf.json)

### vs. base

- Geometric mean: 1.045x slower (HPT: reliability of 99.73%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils
- [🧠memory plot](bm-20251127-blueberry-aarch64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base-mem.svg)
- [📄table](bm-20251127-blueberry-aarch64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.md)
- [📈time plot](bm-20251127-blueberry-aarch64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19750440568)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-87-generic-x86_64-with-glibc2.39
- [raw results](bm-20251127-ripley-x86_64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf.json)

### vs. base

- Geometric mean: 1.019x faster (HPT: reliability of 54.80%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251127-ripley-x86_64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base-mem.svg)
- [📄table](bm-20251127-ripley-x86_64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.md)
- [📈time plot](bm-20251127-ripley-x86_64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/19750440568)
- cpu model: missing
- platform: macOS-15.6.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf.json)

### vs. base

- Geometric mean: 1.082x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 dulwich_log
- [🧠memory plot](bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base-mem.svg)
- [📄table](bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.md)
- [📈time plot](bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.svg)

