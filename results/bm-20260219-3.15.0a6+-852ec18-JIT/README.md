# Results

- fork: python/852ec189784d6f11e6c2
- version: 3.15.0a6+
- config: JIT
- commit hash: [852ec18](https://github.com/python/cpython/commit/852ec18)
- commit date: 2026-02-19T18:45:28-05:00
- commit merge base: [4141f0a1ee6a6e9d5b4ba24f15a9d17df6933321](https://github.com/python/cpython/commit/4141f0a1ee6a6e9d5b4ba24f15a9d17df6933321)
- ref: 852ec189784d6f11e6c2

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22218379254)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260219-blueberry-aarch64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18.json)

### vs. base

- Geometric mean: 1.021x faster (HPT: reliability of 73.09%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260219-blueberry-aarch64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base-mem.svg)
- [📄table](bm-20260219-blueberry-aarch64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.md)
- [📈time plot](bm-20260219-blueberry-aarch64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22218379254)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260219-ripley-x86_64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18.json)

### vs. base

- Geometric mean: 1.053x faster (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260219-ripley-x86_64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base-mem.svg)
- [📄table](bm-20260219-ripley-x86_64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.md)
- [📈time plot](bm-20260219-ripley-x86_64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22218379254)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260219-prometheus-amd64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18.json)

### vs. base

- Geometric mean: 1.172x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260219-prometheus-amd64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.md)
- [📈time plot](bm-20260219-prometheus-amd64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.svg)

