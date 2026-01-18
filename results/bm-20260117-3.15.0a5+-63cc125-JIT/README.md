# Results

- fork: python/63cc1257db468a368d64
- version: 3.15.0a5+
- config: JIT
- commit hash: [63cc125](https://github.com/python/cpython/commit/63cc125)
- commit date: 2026-01-17T19:16:12-05:00
- commit merge base: [7ca9e7ad053c24ae40fc68bc931ca1ff8abbc956](https://github.com/python/cpython/commit/7ca9e7ad053c24ae40fc68bc931ca1ff8abbc956)
- ref: 63cc1257db468a368d64

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21109228167)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125.json)

### vs. base

- Geometric mean: 1.018x faster (HPT: reliability of 84.08%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base-mem.svg)
- [📄table](bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base.md)
- [📈time plot](bm-20260117-blueberry-aarch64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21109228167)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260117-ripley-x86_64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125.json)

### vs. base

- Geometric mean: 1.055x faster (HPT: reliability of 99.94%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260117-ripley-x86_64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base-mem.svg)
- [📄table](bm-20260117-ripley-x86_64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base.md)
- [📈time plot](bm-20260117-ripley-x86_64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21109228167)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260117-prometheus-amd64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125.json)

### vs. base

- Geometric mean: 1.168x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260117-prometheus-amd64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base.md)
- [📈time plot](bm-20260117-prometheus-amd64-python-63cc1257db468a368d64-3.15.0a5%2B-63cc125-vs-base.svg)

