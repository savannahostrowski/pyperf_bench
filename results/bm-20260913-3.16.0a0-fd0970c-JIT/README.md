# Results

- fork: python/fd0970c0ab7eb8c685ef
- version: 3.16.0a0
- config: JIT
- commit hash: [fd0970c](https://github.com/python/cpython/commit/fd0970c)
- commit date: 2026-09-13T20:45:34+00:00
- commit merge base: [ae0d6cc79118114f70afe5f65e5ab3a8d33359cc](https://github.com/python/cpython/commit/ae0d6cc79118114f70afe5f65e5ab3a8d33359cc)
- ref: fd0970c0ab7eb8c685ef

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34864383177)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260913-blueberry-aarch64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c.json)

### vs. base

- Geometric mean: 1.004x slower (HPT: reliability of 79.11%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260913-blueberry-aarch64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c-vs-base-mem.svg)
- [📄table](bm-20260913-blueberry-aarch64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c-vs-base.md)
- [📈time plot](bm-20260913-blueberry-aarch64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34864383177)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260913-ripley-x86_64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c.json)

### vs. base

- Geometric mean: 1.074x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260913-ripley-x86_64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c-vs-base-mem.svg)
- [📄table](bm-20260913-ripley-x86_64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c-vs-base.md)
- [📈time plot](bm-20260913-ripley-x86_64-python-fd0970c0ab7eb8c685ef-3.16.0a0-fd0970c-vs-base.svg)

