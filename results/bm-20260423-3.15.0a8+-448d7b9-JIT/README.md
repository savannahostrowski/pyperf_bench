# Results

- fork: python/448d7b96c181d13ca7f8
- version: 3.15.0a8+
- config: JIT
- commit hash: [448d7b9](https://github.com/python/cpython/commit/448d7b9)
- commit date: 2026-04-23T22:07:28+03:00
- commit merge base: [4629c2215a9a4b3d1ec4a306cd4dd7d11dcfebb4](https://github.com/python/cpython/commit/4629c2215a9a4b3d1ec4a306cd4dd7d11dcfebb4)
- ref: 448d7b96c181d13ca7f8

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24882936202)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260423-blueberry-aarch64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9.json)

### vs. base

- Geometric mean: 1.006x faster (HPT: reliability of 72.27%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260423-blueberry-aarch64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base-mem.svg)
- [📄table](bm-20260423-blueberry-aarch64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.md)
- [📈time plot](bm-20260423-blueberry-aarch64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24882936202)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260423-ripley-x86_64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9.json)

### vs. base

- Geometric mean: 1.089x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260423-ripley-x86_64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base-mem.svg)
- [📄table](bm-20260423-ripley-x86_64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.md)
- [📈time plot](bm-20260423-ripley-x86_64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.svg)

