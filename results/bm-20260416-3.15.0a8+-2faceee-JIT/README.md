# Results

- fork: python/2faceeec5c0fb06498a9
- version: 3.15.0a8+
- config: JIT
- commit hash: [2faceee](https://github.com/python/cpython/commit/2faceee)
- commit date: 2026-04-16T19:13:25+02:00
- commit merge base: [c0af5c024b57d216fc3db41cb0e39a683c327bbd](https://github.com/python/cpython/commit/c0af5c024b57d216fc3db41cb0e39a683c327bbd)
- ref: 2faceeec5c0fb06498a9

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24558457117)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260416-blueberry-aarch64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee.json)

### vs. base

- Geometric mean: 1.012x faster (HPT: reliability of 76.04%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260416-blueberry-aarch64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base-mem.svg)
- [📄table](bm-20260416-blueberry-aarch64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.md)
- [📈time plot](bm-20260416-blueberry-aarch64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24558457117)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260416-ripley-x86_64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee.json)

### vs. base

- Geometric mean: 1.076x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 logging_format, logging_silent, logging_simple
- [🧠memory plot](bm-20260416-ripley-x86_64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base-mem.svg)
- [📄table](bm-20260416-ripley-x86_64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.md)
- [📈time plot](bm-20260416-ripley-x86_64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.svg)

