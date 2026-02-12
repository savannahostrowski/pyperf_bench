# Results

- fork: python/936d60dbe1679f05d7ce
- version: 3.15.0a5+
- config: JIT
- commit hash: [936d60d](https://github.com/python/cpython/commit/936d60d)
- commit date: 2026-02-11T09:41:37+01:00
- commit merge base: [d5f96c86653de4dc8c5074ab0bf3027d0a3c1878](https://github.com/python/cpython/commit/d5f96c86653de4dc8c5074ab0bf3027d0a3c1878)
- ref: 936d60dbe1679f05d7ce

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21899424546)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260211-blueberry-aarch64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d.json)

### vs. base

- Geometric mean: 1.011x faster (HPT: reliability of 65.47%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260211-blueberry-aarch64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base-mem.svg)
- [📄table](bm-20260211-blueberry-aarch64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.md)
- [📈time plot](bm-20260211-blueberry-aarch64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21899424546)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260211-ripley-x86_64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d.json)

### vs. base

- Geometric mean: 1.033x faster (HPT: reliability of 85.46%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260211-ripley-x86_64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base-mem.svg)
- [📄table](bm-20260211-ripley-x86_64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.md)
- [📈time plot](bm-20260211-ripley-x86_64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21899424546)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260211-prometheus-amd64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d.json)

### vs. base

- Geometric mean: 1.150x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260211-prometheus-amd64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.md)
- [📈time plot](bm-20260211-prometheus-amd64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.svg)

