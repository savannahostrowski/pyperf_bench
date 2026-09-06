# Results

- fork: python/7a918411a300ddeef06d
- version: 3.16.0a0
- config: JIT
- commit hash: [7a91841](https://github.com/python/cpython/commit/7a91841)
- commit date: 2026-09-05T17:00:22+00:00
- commit merge base: [e208bf0dda73b8e5a32af154f448e68ad11b26b7](https://github.com/python/cpython/commit/e208bf0dda73b8e5a32af154f448e68ad11b26b7)
- ref: 7a918411a300ddeef06d

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34033955865)
- cpu model: missing
- platform: Linux-6.12.75+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260905-blueberry-aarch64-python-7a918411a300ddeef06d-3.16.0a0-7a91841.json)

### vs. base

- Geometric mean: 1.017x slower (HPT: reliability of 99.12%, 1.00x slower at 99th %ile)
- Memory usage: 1.05x
- [🧠memory plot](bm-20260905-blueberry-aarch64-python-7a918411a300ddeef06d-3.16.0a0-7a91841-vs-base-mem.svg)
- [📄table](bm-20260905-blueberry-aarch64-python-7a918411a300ddeef06d-3.16.0a0-7a91841-vs-base.md)
- [📈time plot](bm-20260905-blueberry-aarch64-python-7a918411a300ddeef06d-3.16.0a0-7a91841-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/34033955865)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-137-generic-x86_64-with-glibc2.39
- [raw results](bm-20260905-ripley-x86_64-python-7a918411a300ddeef06d-3.16.0a0-7a91841.json)

### vs. base

- Geometric mean: 1.077x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260905-ripley-x86_64-python-7a918411a300ddeef06d-3.16.0a0-7a91841-vs-base-mem.svg)
- [📄table](bm-20260905-ripley-x86_64-python-7a918411a300ddeef06d-3.16.0a0-7a91841-vs-base.md)
- [📈time plot](bm-20260905-ripley-x86_64-python-7a918411a300ddeef06d-3.16.0a0-7a91841-vs-base.svg)

