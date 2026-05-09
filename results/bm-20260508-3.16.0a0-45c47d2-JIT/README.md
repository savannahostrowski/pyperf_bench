# Results

- fork: python/45c47d26c230086163ac
- version: 3.16.0a0
- config: JIT
- commit hash: [45c47d2](https://github.com/python/cpython/commit/45c47d2)
- commit date: 2026-05-08T20:33:05+00:00
- commit merge base: [57ef2199503387617b8af3d719c74089fb70dbd4](https://github.com/python/cpython/commit/57ef2199503387617b8af3d719c74089fb70dbd4)
- ref: 45c47d26c230086163ac

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25597856897)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260508-blueberry-aarch64-python-45c47d26c230086163ac-3.16.0a0-45c47d2.json)

### vs. base

- Geometric mean: 1.017x slower (HPT: reliability of 92.65%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260508-blueberry-aarch64-python-45c47d26c230086163ac-3.16.0a0-45c47d2-vs-base-mem.svg)
- [📄table](bm-20260508-blueberry-aarch64-python-45c47d26c230086163ac-3.16.0a0-45c47d2-vs-base.md)
- [📈time plot](bm-20260508-blueberry-aarch64-python-45c47d26c230086163ac-3.16.0a0-45c47d2-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/25597856897)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-110-generic-x86_64-with-glibc2.39
- [raw results](bm-20260508-ripley-x86_64-python-45c47d26c230086163ac-3.16.0a0-45c47d2.json)

### vs. base

- Geometric mean: 1.081x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20260508-ripley-x86_64-python-45c47d26c230086163ac-3.16.0a0-45c47d2-vs-base-mem.svg)
- [📄table](bm-20260508-ripley-x86_64-python-45c47d26c230086163ac-3.16.0a0-45c47d2-vs-base.md)
- [📈time plot](bm-20260508-ripley-x86_64-python-45c47d26c230086163ac-3.16.0a0-45c47d2-vs-base.svg)

