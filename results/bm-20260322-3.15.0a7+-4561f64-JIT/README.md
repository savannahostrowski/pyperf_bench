# Results

- fork: python/4561f6418a691b3e89ae
- version: 3.15.0a7+
- config: JIT
- commit hash: [4561f64](https://github.com/python/cpython/commit/4561f64)
- commit date: 2026-03-22T23:12:58+02:00
- commit merge base: [ae6adc907907562e4ffbb5355f12e77e9085c506](https://github.com/python/cpython/commit/ae6adc907907562e4ffbb5355f12e77e9085c506)
- ref: 4561f6418a691b3e89ae

## linux aarch64 (blueberry)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23430370650)
- cpu model: missing
- platform: Linux-6.12.47+rpt-rpi-2712-aarch64-with-glibc2.36
- [raw results](bm-20260322-blueberry-aarch64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64.json)

### vs. base

- Geometric mean: 1.011x slower (HPT: reliability of 82.20%, 1.00x slower at 99th %ile)
- Memory usage: 1.03x
- [🧠memory plot](bm-20260322-blueberry-aarch64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base-mem.svg)
- [📄table](bm-20260322-blueberry-aarch64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base.md)
- [📈time plot](bm-20260322-blueberry-aarch64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base.svg)

## linux x86_64 (ripley)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23430370650)
- cpu model: Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
- platform: Linux-6.8.0-100-generic-x86_64-with-glibc2.39
- [raw results](bm-20260322-ripley-x86_64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64.json)

### vs. base

- Geometric mean: 1.053x faster (HPT: reliability of 99.93%, 1.00x faster at 99th %ile)
- Memory usage: 1.02x
- [🧠memory plot](bm-20260322-ripley-x86_64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base-mem.svg)
- [📄table](bm-20260322-ripley-x86_64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base.md)
- [📈time plot](bm-20260322-ripley-x86_64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base.svg)

## windows amd64 (prometheus)

- [GitHub Action run](https://github.com/savannahostrowski/pyperf_bench/actions/runs/23430370650)
- cpu model: missing
- platform: Windows-11-10.0.26200-SP0
- [raw results](bm-20260322-prometheus-amd64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64.json)

### vs. base

- Geometric mean: 1.226x faster (HPT: reliability of 100.00%, 1.10x faster at 99th %ile)
- Memory usage: unknown
- [📄table](bm-20260322-prometheus-amd64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base.md)
- [📈time plot](bm-20260322-prometheus-amd64-python-4561f6418a691b3e89ae-3.15.0a7%2B-4561f64-vs-base.svg)

