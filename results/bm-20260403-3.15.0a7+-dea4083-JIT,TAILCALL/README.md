# Results

- fork: python/dea4083aa952c955a7c3
- version: 3.15.0a7+
- config: JIT,TAILCALL
- commit hash: [dea4083](https://github.com/python/cpython/commit/dea4083)
- commit date: 2026-04-03T12:42:13-07:00
- commit merge base: [80d0a85d969d305c7436dc54f8939d7b6f441b5f](https://github.com/python/cpython/commit/80d0a85d969d305c7436dc54f8939d7b6f441b5f)
- ref: dea4083aa952c955a7c3

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23975989936)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083.json)

### vs. base

- Geometric mean: 1.006x slower (HPT: reliability of 99.15%, 1.00x slower at 99th %ile)
- Memory usage: unknown
- new benchmarks: asyncio_tcp, asyncio_tcp_ssl, bench_mp_pool, bench_thread_pool, pickle, pickle_dict, pickle_list, unpack_sequence, unpickle, unpickle_list
- [📄table](bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.md)
- [📈time plot](bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.svg)

## darwin arm64 (jones)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23975989936)
- cpu model: missing
- platform: macOS-26.3.1-arm64-arm-64bit-Mach-O
- [raw results](bm-20260403-jones-arm64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083.json)

