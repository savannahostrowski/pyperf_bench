# Results

- fork: python/ce916dc50644bb1de940
- version: 3.16.0a0
- config: JIT
- commit hash: [ce916dc](https://github.com/python/cpython/commit/ce916dc)
- commit date: 2026-06-09T15:22:13-07:00
- commit merge base: [580499177ca91477b53b4a40afcec7d3370265b0](https://github.com/python/cpython/commit/580499177ca91477b53b4a40afcec7d3370265b0)
- ref: ce916dc50644bb1de940

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27270066714)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260609-blueberry-aarch64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc.json)

### vs. base

- Geometric mean: 1.004x slower (HPT: reliability of 68.64%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260609-blueberry-aarch64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc-vs-base-mem.svg)
- [📄table](bm-20260609-blueberry-aarch64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc-vs-base.md)
- [📈time plot](bm-20260609-blueberry-aarch64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/27270066714)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260609-ripley-x86_64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc.json)

### vs. base

- Geometric mean: 1.073x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260609-ripley-x86_64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc-vs-base-mem.svg)
- [📄table](bm-20260609-ripley-x86_64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc-vs-base.md)
- [📈time plot](bm-20260609-ripley-x86_64-python-ce916dc50644bb1de940-3.16.0a0-ce916dc-vs-base.svg)

