# Results

- fork: python/dc12d1999b88e84d5a6b
- version: 3.15.0a6+
- config: JIT
- commit hash: [dc12d19](https://github.com/python/cpython/commit/dc12d19)
- commit date: 2026-03-03T21:41:26+00:00
- commit merge base: [15f6479c415cc6cd219cd25c1d94bab17d720cbc](https://github.com/python/cpython/commit/15f6479c415cc6cd219cd25c1d94bab17d720cbc)
- ref: dc12d1999b88e84d5a6b

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22662859812)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260303-blueberry-aarch64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19.json)

### vs. base

- Geometric mean: 1.011x faster (HPT: reliability of 65.11%, 1.00x slower at 99th %ile)
- Memory usage: 1.02x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260303-blueberry-aarch64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19-vs-base-mem.svg)
- [📄table](bm-20260303-blueberry-aarch64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19-vs-base.md)
- [📈time plot](bm-20260303-blueberry-aarch64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/22662859812)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260303-ripley-x86_64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19.json)

### vs. base

- Geometric mean: 1.059x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- missing benchmarks: 🔴 genshi_text, genshi_xml
- [🧠memory plot](bm-20260303-ripley-x86_64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19-vs-base-mem.svg)
- [📄table](bm-20260303-ripley-x86_64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19-vs-base.md)
- [📈time plot](bm-20260303-ripley-x86_64-python-dc12d1999b88e84d5a6b-3.15.0a6%2B-dc12d19-vs-base.svg)

