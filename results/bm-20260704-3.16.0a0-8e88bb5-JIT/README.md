# Results

- fork: python/8e88bb56337a771f3af5
- version: 3.16.0a0
- config: JIT
- commit hash: [8e88bb5](https://github.com/python/cpython/commit/8e88bb5)
- commit date: 2026-07-04T19:39:11-04:00
- commit merge base: [8e580b068500feec5d6cc5e5a3e6072e8996fb25](https://github.com/python/cpython/commit/8e580b068500feec5d6cc5e5a3e6072e8996fb25)
- ref: 8e88bb56337a771f3af5

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28738679141)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260704-blueberry-aarch64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5.json)

### vs. base

- Geometric mean: 1.014x slower (HPT: reliability of 92.00%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260704-blueberry-aarch64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5-vs-base-mem.svg)
- [📄table](bm-20260704-blueberry-aarch64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5-vs-base.md)
- [📈time plot](bm-20260704-blueberry-aarch64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/28738679141)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260704-ripley-x86_64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260704-ripley-x86_64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5-vs-base-mem.svg)
- [📄table](bm-20260704-ripley-x86_64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5-vs-base.md)
- [📈time plot](bm-20260704-ripley-x86_64-python-8e88bb56337a771f3af5-3.16.0a0-8e88bb5-vs-base.svg)

