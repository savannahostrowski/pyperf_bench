# Results

- fork: python/1b118353bb0a9d816de6
- version: 3.15.0a7+
- config: JIT
- commit hash: [1b11835](https://github.com/python/cpython/commit/1b11835)
- commit date: 2026-03-17T09:39:45+08:00
- commit merge base: [104cae039ac428709c7bcf9b1a00102f97be0a5c](https://github.com/python/cpython/commit/104cae039ac428709c7bcf9b1a00102f97be0a5c)
- ref: 1b118353bb0a9d816de6

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23187204932)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260317-blueberry-aarch64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835.json)

### vs. base

- Geometric mean: 1.017x slower (HPT: reliability of 93.85%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260317-blueberry-aarch64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base-mem.svg)
- [📄table](bm-20260317-blueberry-aarch64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base.md)
- [📈time plot](bm-20260317-blueberry-aarch64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23187204932)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260317-ripley-x86_64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835.json)

### vs. base

- Geometric mean: 1.053x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260317-ripley-x86_64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base-mem.svg)
- [📄table](bm-20260317-ripley-x86_64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base.md)
- [📈time plot](bm-20260317-ripley-x86_64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23187204932)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260317-prometheus-amd64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835.json)

### vs. base

- Geometric mean: 1.219x faster (HPT: reliability of 100.00%, 1.10x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260317-prometheus-amd64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base.md)
- [📈time plot](bm-20260317-prometheus-amd64-python-1b118353bb0a9d816de6-3.15.0a7%2B-1b11835-vs-base.svg)

