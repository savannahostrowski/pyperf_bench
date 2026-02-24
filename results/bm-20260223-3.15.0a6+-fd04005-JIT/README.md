# Results

- fork: python/fd0400585eb957c7d108
- version: 3.15.0a6+
- config: JIT
- commit hash: [fd04005](https://github.com/python/cpython/commit/fd04005)
- commit date: 2026-02-23T16:53:17-08:00
- commit merge base: [ae7fc4a4f6b711173bb70d23755ec15b8ac958a6](https://github.com/python/cpython/commit/ae7fc4a4f6b711173bb70d23755ec15b8ac958a6)
- ref: fd0400585eb957c7d108

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22344541541)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260223-blueberry-aarch64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005.json)

### vs. base

- Geometric mean: 1.018x faster (HPT: reliability of 58.17%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260223-blueberry-aarch64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base-mem.svg)
- [📄table](bm-20260223-blueberry-aarch64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.md)
- [📈time plot](bm-20260223-blueberry-aarch64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22344541541)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005.json)

### vs. base

- Geometric mean: 1.045x faster (HPT: reliability of 98.75%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base-mem.svg)
- [📄table](bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.md)
- [📈time plot](bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22344541541)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260223-prometheus-amd64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005.json)

### vs. base

- Geometric mean: 1.185x faster (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260223-prometheus-amd64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.md)
- [📈time plot](bm-20260223-prometheus-amd64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.svg)

