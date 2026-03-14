# Results

- fork: python/3c38feb2a21aacdb009e
- version: 3.15.0a7+
- config: JIT
- commit hash: [3c38feb](https://github.com/python/cpython/commit/3c38feb)
- commit date: 2026-03-13T19:44:51+01:00
- commit merge base: [747ef70faa8637ccf6dd896323fa84aee8f14513](https://github.com/python/cpython/commit/747ef70faa8637ccf6dd896323fa84aee8f14513)
- ref: 3c38feb2a21aacdb009e

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23084995371)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260313-blueberry-aarch64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb.json)

### vs. base

- Geometric mean: 1.019x faster (HPT: reliability of 58.42%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260313-blueberry-aarch64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base-mem.svg)
- [📄table](bm-20260313-blueberry-aarch64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base.md)
- [📈time plot](bm-20260313-blueberry-aarch64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23084995371)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260313-ripley-x86_64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb.json)

### vs. base

- Geometric mean: 1.053x faster (HPT: reliability of 99.92%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260313-ripley-x86_64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base-mem.svg)
- [📄table](bm-20260313-ripley-x86_64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base.md)
- [📈time plot](bm-20260313-ripley-x86_64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23084995371)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260313-prometheus-amd64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb.json)

### vs. base

- Geometric mean: 1.176x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260313-prometheus-amd64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base.md)
- [📈time plot](bm-20260313-prometheus-amd64-python-3c38feb2a21aacdb009e-3.15.0a7%2B-3c38feb-vs-base.svg)

