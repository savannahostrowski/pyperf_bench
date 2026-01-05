# Results

- fork: python/c99f7667436d8978b407
- version: 3.15.0a3+
- config: JIT
- commit hash: [c99f766](https://github.com/python/cpython/commit/c99f766)
- commit date: 2026-01-04T21:44:47+01:00
- commit merge base: [e6bfe4d8869e046a91d091611d3c7b5dccdaf0d6](https://github.com/python/cpython/commit/e6bfe4d8869e046a91d091611d3c7b5dccdaf0d6)
- fork: python/main
- ref: c99f7667436d8978b407, main

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20701344245)
- cpu model: missing
- platform: Linux-6.12.25+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260104-blueberry-aarch64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766.json)

### vs. base

- Geometric mean: 1.007x faster (HPT: reliability of 79.76%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260104-blueberry-aarch64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766-vs-base-mem.svg)
- [📄table](bm-20260104-blueberry-aarch64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766-vs-base.md)
- [📈time plot](bm-20260104-blueberry-aarch64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20701344245)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-88-generic-x86_64-with-glibc2.39
- [raw results](bm-20260104-ripley-x86_64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766.json)

### vs. base

- Geometric mean: 1.038x faster (HPT: reliability of 96.88%, 1.00x faster at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260104-ripley-x86_64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766-vs-base-mem.svg)
- [📄table](bm-20260104-ripley-x86_64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766-vs-base.md)
- [📈time plot](bm-20260104-ripley-x86_64-python-c99f7667436d8978b407-3.15.0a3%2B-c99f766-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/20699706218)
- cpu model: missing
- platform: Windows-11-10.0.26100-SP0
- [raw results](bm-20260104-prometheus-amd64-python-main-3.15.0a3%2B-c99f766.json)

### vs. base

- Geometric mean: 1.142x slower (HPT: reliability of 100.00%, 1.08x slower at 99th %ile)
- Memory usage: unknown
- missing benchmarks: 🔴 asyncio_tcp, asyncio_tcp_ssl, bench_mp_pool, bench_thread_pool, pickle, pickle_dict, pickle_list, unpack_sequence, unpickle, unpickle_list
- [📄table](bm-20260104-prometheus-amd64-python-main-3.15.0a3%2B-c99f766-vs-base.md)
- [📈time plot](bm-20260104-prometheus-amd64-python-main-3.15.0a3%2B-c99f766-vs-base.svg)

