# Results

- fork: python/1dfe99ae3bed6cac0173
- version: 3.15.0a7+
- config: JIT
- commit hash: [1dfe99a](https://github.com/python/cpython/commit/1dfe99a)
- commit date: 2026-03-14T22:58:35-04:00
- commit merge base: [788c3291172b55efa7cf8b33a315e4b0fe63540c](https://github.com/python/cpython/commit/788c3291172b55efa7cf8b33a315e4b0fe63540c)
- ref: 1dfe99ae3bed6cac0173

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23107397815)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260314-blueberry-aarch64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a.json)

### vs. base

- Geometric mean: 1.022x faster (HPT: reliability of 59.16%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260314-blueberry-aarch64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base-mem.svg)
- [📄table](bm-20260314-blueberry-aarch64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base.md)
- [📈time plot](bm-20260314-blueberry-aarch64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23107397815)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260314-ripley-x86_64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a.json)

### vs. base

- Geometric mean: 1.059x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260314-ripley-x86_64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base-mem.svg)
- [📄table](bm-20260314-ripley-x86_64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base.md)
- [📈time plot](bm-20260314-ripley-x86_64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23107397815)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260314-prometheus-amd64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a.json)

### vs. base

- Geometric mean: 1.182x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260314-prometheus-amd64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base.md)
- [📈time plot](bm-20260314-prometheus-amd64-python-1dfe99ae3bed6cac0173-3.15.0a7%2B-1dfe99a-vs-base.svg)

