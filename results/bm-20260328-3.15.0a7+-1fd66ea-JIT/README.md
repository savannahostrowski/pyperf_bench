# Results

- fork: python/1fd66eadd258223a0e34
- version: 3.15.0a7+
- config: JIT
- commit hash: [1fd66ea](https://github.com/python/cpython/commit/1fd66ea)
- commit date: 2026-03-28T20:21:19+00:00
- commit merge base: [5bf3a31bc23818907f8e5844d65d610835b4b672](https://github.com/python/cpython/commit/5bf3a31bc23818907f8e5844d65d610835b4b672)
- ref: 1fd66eadd258223a0e34

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23705866732)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260328-blueberry-aarch64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea.json)

### vs. base

- Geometric mean: 1.005x slower (HPT: reliability of 78.33%, 1.00x slower at 99th %ile)
- Memory usage: 1.04x
- [🧠memory plot](bm-20260328-blueberry-aarch64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base-mem.svg)
- [📄table](bm-20260328-blueberry-aarch64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base.md)
- [📈time plot](bm-20260328-blueberry-aarch64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23705866732)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260328-ripley-x86_64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea.json)

### vs. base

- Geometric mean: 1.060x faster (HPT: reliability of 99.07%, 1.00x faster at 99th %ile)
- Memory usage: 1.01x
- [🧠memory plot](bm-20260328-ripley-x86_64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base-mem.svg)
- [📄table](bm-20260328-ripley-x86_64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base.md)
- [📈time plot](bm-20260328-ripley-x86_64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23705866732)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260328-prometheus-amd64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea.json)

### vs. base

- Geometric mean: 1.225x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260328-prometheus-amd64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base.md)
- [📈time plot](bm-20260328-prometheus-amd64-python-1fd66eadd258223a0e34-3.15.0a7%2B-1fd66ea-vs-base.svg)

