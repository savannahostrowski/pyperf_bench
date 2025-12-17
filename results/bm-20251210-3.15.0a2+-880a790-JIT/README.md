# Results

- fork: python/880a7905ca53d3c5c229
- version: 3.15.0a2+
- config: JIT
- commit hash: [880a790](https://github.com/python/cpython/commit/880a790)
- commit date: 2025-12-10T15:35:51-08:00
- commit merge base: [dc3ece2bc06d56c21ef81f86424b4598880ba1c8](https://github.com/python/cpython/commit/dc3ece2bc06d56c21ef81f86424b4598880ba1c8)
- ref: 880a7905ca53d3c5c229

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20117470366)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20251210-blueberry-aarch64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790.json)

### vs. base

- Geometric mean: 1.040x slower (HPT: reliability of 99.99%, 1.01x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20251210-blueberry-aarch64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base-mem.svg)
- [📄table](bm-20251210-blueberry-aarch64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.md)
- [📈time plot](bm-20251210-blueberry-aarch64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20117470366)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20251210-ripley-x86_64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790.json)

### vs. base

- Geometric mean: 1.027x faster (HPT: reliability of 90.08%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251210-ripley-x86_64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base-mem.svg)
- [📄table](bm-20251210-ripley-x86_64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.md)
- [📈time plot](bm-20251210-ripley-x86_64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20117470366)
- cpu model: missing
- platform: macOS-26.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20251210-jones-arm64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790.json)

### vs. base

- Geometric mean: 1.024x faster (HPT: reliability of 95.90%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20251210-jones-arm64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base-mem.svg)
- [📄table](bm-20251210-jones-arm64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.md)
- [📈time plot](bm-20251210-jones-arm64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.svg)

