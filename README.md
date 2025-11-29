# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (d2d2e92)](results/bm-20251128-3.15.0a2%2B-d2d2e92/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (d2d2e92)](results/bm-20251128-3.15.0a2%2B-d2d2e92-PYTHON_UOPS/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-28](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT) | python/d2d2e92110751fff3cbb | d2d2e92 (JIT) |  |  |  | 1.087x ↓<br>[📄](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base.md)[📈](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base.svg)[🧠](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-blueberry-aarch64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base-mem.svg) |
| [2025-11-28](results/bm-20251128-3.15.0a2%2B-d2d2e92) | python/d2d2e92110751fff3cbb | d2d2e92 |  |  |  |  |
| [2025-11-27](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT) | python/5ec03cf3b086fd01614c | 5ec03cf (JIT) |  |  |  | 1.047x ↓<br>[📄](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-blueberry-aarch64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.md)[📈](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-blueberry-aarch64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.svg)[🧠](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-blueberry-aarch64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base-mem.svg) |
| [2025-11-27](results/bm-20251127-3.15.0a2%2B-5ec03cf) | python/5ec03cf3b086fd01614c | 5ec03cf |  |  |  |  |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT) | python/bc9e63dd9d2931771415 | bc9e63d (JIT) |  |  |  | 1.073x ↓<br>[📄](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base.md)[📈](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base.svg)[🧠](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-blueberry-aarch64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base-mem.svg) |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-bc9e63d) | python/bc9e63dd9d2931771415 | bc9e63d |  |  |  |  |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-33efd71-JIT) | python/33efd7178e269cbd0423 | 33efd71 (JIT) |  |  |  | 1.040x ↓<br>[📄](results/bm-20251126-3.15.0a2%2B-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.md)[📈](results/bm-20251126-3.15.0a2%2B-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.svg)[🧠](results/bm-20251126-3.15.0a2%2B-33efd71-JIT/bm-20251126-blueberry-aarch64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base-mem.svg) |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-33efd71) | python/33efd7178e269cbd0423 | 33efd71 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-28](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT) | python/d2d2e92110751fff3cbb | d2d2e92 (JIT) |  |  |  | 1.011x ↑<br>[📄](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-ripley-x86_64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base.md)[📈](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-ripley-x86_64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base.svg)[🧠](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-ripley-x86_64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base-mem.svg) |
| [2025-11-28](results/bm-20251128-3.15.0a2%2B-d2d2e92) | python/d2d2e92110751fff3cbb | d2d2e92 |  |  |  |  |
| [2025-11-27](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT) | python/5ec03cf3b086fd01614c | 5ec03cf (JIT) |  |  |  | 1.014x ↑<br>[📄](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-ripley-x86_64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.md)[📈](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-ripley-x86_64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.svg)[🧠](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-ripley-x86_64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base-mem.svg) |
| [2025-11-27](results/bm-20251127-3.15.0a2%2B-5ec03cf) | python/5ec03cf3b086fd01614c | 5ec03cf |  |  |  |  |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT) | python/bc9e63dd9d2931771415 | bc9e63d (JIT) |  |  |  | 1.007x ↑<br>[📄](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-ripley-x86_64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base.md)[📈](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-ripley-x86_64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base.svg)[🧠](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-ripley-x86_64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base-mem.svg) |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-bc9e63d) | python/bc9e63dd9d2931771415 | bc9e63d |  |  |  |  |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-33efd71-JIT) | python/33efd7178e269cbd0423 | 33efd71 (JIT) |  |  |  | 1.052x ↑<br>[📄](results/bm-20251126-3.15.0a2%2B-33efd71-JIT/bm-20251126-ripley-x86_64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.md)[📈](results/bm-20251126-3.15.0a2%2B-33efd71-JIT/bm-20251126-ripley-x86_64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base.svg)[🧠](results/bm-20251126-3.15.0a2%2B-33efd71-JIT/bm-20251126-ripley-x86_64-python-33efd7178e269cbd0423-3.15.0a2%2B-33efd71-vs-base-mem.svg) |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-33efd71) | python/33efd7178e269cbd0423 | 33efd71 |  |  |  |  |
| [2025-11-23](results/bm-20251123-3.15.0a2%2B-727f9a5) | brandtbucher/gc_double_count | 727f9a5 |  |  |  | 1.002x ↓<br>[📄](results/bm-20251123-3.15.0a2%2B-727f9a5/bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2%2B-727f9a5-vs-base.md)[📈](results/bm-20251123-3.15.0a2%2B-727f9a5/bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2%2B-727f9a5-vs-base.svg)[🧠](results/bm-20251123-3.15.0a2%2B-727f9a5/bm-20251123-ripley-x86_64-brandtbucher-gc_double_count-3.15.0a2%2B-727f9a5-vs-base-mem.svg) |
| [2025-11-23](results/bm-20251123-3.15.0a2%2B-e73fbba) | python/e73fbbacbba0dc65f852 | e73fbba |  |  |  | 1.002x ↓<br>[📄](results/bm-20251123-3.15.0a2%2B-e73fbba/bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2%2B-e73fbba-vs-base.md)[📈](results/bm-20251123-3.15.0a2%2B-e73fbba/bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2%2B-e73fbba-vs-base.svg)[🧠](results/bm-20251123-3.15.0a2%2B-e73fbba/bm-20251123-ripley-x86_64-python-e73fbbacbba0dc65f852-3.15.0a2%2B-e73fbba-vs-base-mem.svg) |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-28](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT) | python/d2d2e92110751fff3cbb | d2d2e92 (JIT) |  |  |  | 1.054x ↑<br>[📄](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base.md)[📈](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base.svg)[🧠](results/bm-20251128-3.15.0a2%2B-d2d2e92-JIT/bm-20251128-jones-arm64-python-d2d2e92110751fff3cbb-3.15.0a2%2B-d2d2e92-vs-base-mem.svg) |
| [2025-11-28](results/bm-20251128-3.15.0a2%2B-d2d2e92) | python/d2d2e92110751fff3cbb | d2d2e92 |  |  |  |  |
| [2025-11-27](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT) | python/5ec03cf3b086fd01614c | 5ec03cf (JIT) |  |  |  | 1.075x ↑<br>[📄](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.md)[📈](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base.svg)[🧠](results/bm-20251127-3.15.0a2%2B-5ec03cf-JIT/bm-20251127-jones-arm64-python-5ec03cf3b086fd01614c-3.15.0a2%2B-5ec03cf-vs-base-mem.svg) |
| [2025-11-27](results/bm-20251127-3.15.0a2%2B-5ec03cf) | python/5ec03cf3b086fd01614c | 5ec03cf |  |  |  |  |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT) | python/bc9e63dd9d2931771415 | bc9e63d (JIT) |  |  |  | 1.070x ↑<br>[📄](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-jones-arm64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base.md)[📈](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-jones-arm64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base.svg)[🧠](results/bm-20251126-3.15.0a2%2B-bc9e63d-JIT/bm-20251126-jones-arm64-python-bc9e63dd9d2931771415-3.15.0a2%2B-bc9e63d-vs-base-mem.svg) |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-bc9e63d) | python/bc9e63dd9d2931771415 | bc9e63d |  |  |  |  |


<!-- END table -->

`*` indicates that the exact same versions of pyperformance was not used.

For the results above, the "faster/slower" result is a geometric mean of each of the benchmarks. The "reliability (rel)" number is the likelihood that the change is faster or slower based on the [Hierarchical Performance Testing (HPT)](#hpt) method. For more details, visit each individual result's README.md.

## Longitudinal results

Below are longitudinal timing results. There are also [🧠 longitudinal memory results](memory.md).
![Longitudinal speed improvement](/longitudinal.svg)

Improvement of the geometric mean of key merged benchmarks, computed with `pyperf compare`.
The results have a resolution of 0.01 (1%).

![Configuration speed improvement](/configs.svg)

There is also a [longitudinal plot by benchmark](/benchmarks.svg).

## Documentation

### Running benchmarks from the GitHub web UI

Visit the 🔒 [benchmark action](../../actions/workflows/benchmark.yml) and click the "Run Workflow" button.

The available parameters are:

- `fork`: The fork of CPython to benchmark.
  If benchmarking a pull request, this would normally be your GitHub username.
- `ref`: The branch, tag or commit SHA to benchmark.
  If a SHA, it must be the full SHA, since finding it by a prefix is not supported.
- `machine`: The machine to run on.
  One of `linux-amd64` (default), `windows-amd64`, `darwin-arm64` or `all`.
- `benchmark_base`: If checked, the base of the selected branch will also be benchmarked.
  The base is determined by running `git merge-base upstream/main $ref`.
- `pystats`: If checked, collect the pystats from running the benchmarks.

To watch the progress of the benchmark, select it from the 🔒 [benchmark action page](../../actions/workflows/benchmark.yml).
It may be canceled from there as well.
To show only your benchmark workflows, select your GitHub ID from the "Actor" dropdown.

When the benchmarking is complete, the results are published to this repository and will appear in the [complete table](RESULTS.md).
Each set of benchmarks will have:

- The raw `.json` results from pyperformance.
- Comparisons against important reference releases, as well as the merge base of the branch if `benchmark_base` was selected. These include
  - A markdown table produced by `pyperf compare_to`.
  - A set of "violin" plots showing the distribution of results for each benchmark.
  - A set of plots showing the memory change for each benchmark (for immediate bases only, on non-Windows platforms).

The most convenient way to get results locally is to clone this repo and `git pull` from it.

### Running benchmarks from the GitHub CLI

To automate benchmarking runs, it may be more convenient to use the [GitHub CLI](https://cli.github.com/).
Once you have `gh` installed and configured, you can run benchmarks by cloning this repository and then from inside it:

```bash
$ gh workflow run benchmark.yml -f fork=me -f ref=my_branch
```

Any of the parameters described above are available at the commandline using the `-f key=value` syntax.

### Collecting Linux perf profiling data

To collect Linux perf sampling profile data for a benchmarking run, run the `_benchmark` action and check the `perf` checkbox.
Follow this by a run of the `_generate` action to regenerate the plots.
