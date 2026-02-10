# Results

- fork: python/d2d245942eccf108ac3c
- version: 3.15.0a5+
- config: JIT
- commit hash: [d2d2459](https://github.com/python/cpython/commit/d2d2459)
- commit date: 2026-02-10T08:29:55+00:00
- commit merge base: [704b915494521d6061c5377e90be6361ea2325b2](https://github.com/python/cpython/commit/704b915494521d6061c5377e90be6361ea2325b2)
- ref: d2d245942eccf108ac3c

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21859113198)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260210-blueberry-aarch64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459.json)

### vs. base

- Geometric mean: 1.011x faster (HPT: reliability of 56.92%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260210-blueberry-aarch64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base-mem.svg)
- [📄table](bm-20260210-blueberry-aarch64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.md)
- [📈time plot](bm-20260210-blueberry-aarch64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21859113198)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459.json)

### vs. base

- Geometric mean: 1.032x faster (HPT: reliability of 93.97%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base-mem.svg)
- [📄table](bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.md)
- [📈time plot](bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/21859113198)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260210-prometheus-amd64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459.json)

### vs. base

- Geometric mean: 1.151x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260210-prometheus-amd64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.md)
- [📈time plot](bm-20260210-prometheus-amd64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.svg)

