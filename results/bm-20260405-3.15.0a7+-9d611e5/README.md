# Results

- fork: pablogsal/frame_pointers
- version: 3.15.0a7+
- config: 
- commit hash: [9d611e5](https://github.com/pablogsal/cpython/commit/9d611e5)
- commit date: 2026-04-05T20:27:24+01:00
- commit merge base: [b07becb57371b733b9cc91233ab93b02a6b2f014](https://github.com/python/cpython/commit/b07becb57371b733b9cc91233ab93b02a6b2f014)
- ref: frame_pointers

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24044963381)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260405-blueberry-aarch64-pablogsal-frame_pointers-3.15.0a7%2B-9d611e5.json)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/24044991867)
- cpu model: missing
- platform: macOS-26.3.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20260405-jones-arm64-pablogsal-frame_pointers-3.15.0a7%2B-9d611e5.json)

### vs. base

- Geometric mean: 1.001x slower (HPT: reliability of 73.32%, 1.00x faster at 99th %ile)
- Memory usage: 1.00x
- [🧠memory plot](bm-20260405-jones-arm64-pablogsal-frame_pointers-3.15.0a7%2B-9d611e5-vs-base-mem.svg)
- [📄table](bm-20260405-jones-arm64-pablogsal-frame_pointers-3.15.0a7%2B-9d611e5-vs-base.md)
- [📈time plot](bm-20260405-jones-arm64-pablogsal-frame_pointers-3.15.0a7%2B-9d611e5-vs-base.svg)

