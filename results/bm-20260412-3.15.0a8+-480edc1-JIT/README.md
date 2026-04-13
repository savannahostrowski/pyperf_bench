# Results

- fork: python/480edc1aae0f54e34d21
- version: 3.15.0a8+
- config: JIT
- commit hash: [480edc1](https://github.com/python/cpython/commit/480edc1)
- commit date: 2026-04-12T18:15:01-04:00
- commit merge base: [b29afe62f7236f7161c2670dccc24368217a7fb1](https://github.com/python/cpython/commit/b29afe62f7236f7161c2670dccc24368217a7fb1)
- ref: 480edc1aae0f54e34d21

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24336694551)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260412-blueberry-aarch64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1.json)

### vs. base

- Geometric mean: 1.018x faster (HPT: reliability of 82.74%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 docutils, fastapi_http
- [🧠memory plot](bm-20260412-blueberry-aarch64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1-vs-base-mem.svg)
- [📄table](bm-20260412-blueberry-aarch64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1-vs-base.md)
- [📈time plot](bm-20260412-blueberry-aarch64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24336694551)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260412-ripley-x86_64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1.json)

### vs. base

- Geometric mean: 1.082x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.01x
- new benchmarks: fastapi_http
- [🧠memory plot](bm-20260412-ripley-x86_64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1-vs-base-mem.svg)
- [📄table](bm-20260412-ripley-x86_64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1-vs-base.md)
- [📈time plot](bm-20260412-ripley-x86_64-python-480edc1aae0f54e34d21-3.15.0a8%2B-480edc1-vs-base.svg)

