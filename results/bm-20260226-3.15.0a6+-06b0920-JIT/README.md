# Results

- fork: python/06b0920f1292690a22ab
- version: 3.15.0a6+
- config: JIT
- commit hash: [06b0920](https://github.com/python/cpython/commit/06b0920)
- commit date: 2026-02-26T23:40:25+00:00
- commit merge base: [3fc945df22a169e039c3f21b44c0d08390a00c0c](https://github.com/python/cpython/commit/3fc945df22a169e039c3f21b44c0d08390a00c0c)
- ref: 06b0920f1292690a22ab

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22480277150)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260226-blueberry-aarch64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920.json)

### vs. base

- Geometric mean: 1.018x faster (HPT: reliability of 62.84%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260226-blueberry-aarch64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base-mem.svg)
- [📄table](bm-20260226-blueberry-aarch64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base.md)
- [📈time plot](bm-20260226-blueberry-aarch64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22480277150)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260226-ripley-x86_64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920.json)

### vs. base

- Geometric mean: 1.049x faster (HPT: reliability of 99.84%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260226-ripley-x86_64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base-mem.svg)
- [📄table](bm-20260226-ripley-x86_64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base.md)
- [📈time plot](bm-20260226-ripley-x86_64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22480277150)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260226-prometheus-amd64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920.json)

### vs. base

- Geometric mean: 1.181x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [📄table](bm-20260226-prometheus-amd64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base.md)
- [📈time plot](bm-20260226-prometheus-amd64-python-06b0920f1292690a22ab-3.15.0a6%2B-06b0920-vs-base.svg)

