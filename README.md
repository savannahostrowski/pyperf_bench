# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (ca1e86f)](results/bm-20251119-3.15.0a2%2B-ca1e86f/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (ca1e86f)](results/bm-20251119-3.15.0a2%2B-ca1e86f-PYTHON_UOPS/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT) | python/ca1e86f9d963dc298d9a | ca1e86f (JIT) |  |  |  | 1.073x ↓<br>[📄](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f) | python/ca1e86f9d963dc298d9a | ca1e86f |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT) | python/b3b63e8d6d296b879fdd | b3b63e8 (JIT) |  |  |  | 1.027x ↓<br>[📄](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8) | python/b3b63e8d6d296b879fdd | b3b63e8 |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT) | python/7b0b70867586ef7109de | 7b0b708 (JIT) |  |  |  | 1.103x ↓<br>[📄](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT/bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base.md)[📈](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT/bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base.svg)[🧠](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT/bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a1%2B-7b0b708) | python/7b0b70867586ef7109de | 7b0b708 |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a1%2B-652c764-JIT) | python/652c764a59913327b28b | 652c764 (JIT) |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-1f50f61-JIT) | Fidget-Spinner/jit_lower_trace_limi | 1f50f61 (JIT) |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-1f50f61) | Fidget-Spinner/jit_lower_trace_limi | 1f50f61 |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT) | python/4695ec109d07c9bfd9eb | 4695ec1 (JIT) |  |  |  | 1.053x ↓<br>[📄](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT/bm-20251118-blueberry-aarch64-python-4695ec109d07c9bfd9eb-3.15.0a1%2B-4695ec1-vs-base.md)[📈](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT/bm-20251118-blueberry-aarch64-python-4695ec109d07c9bfd9eb-3.15.0a1%2B-4695ec1-vs-base.svg)[🧠](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT/bm-20251118-blueberry-aarch64-python-4695ec109d07c9bfd9eb-3.15.0a1%2B-4695ec1-vs-base-mem.svg) |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-4695ec1) | python/4695ec109d07c9bfd9eb | 4695ec1 |  |  |  |  |
| [2025-11-17](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT) | python/5d2eb98a91f2cd703d14 | 5d2eb98 (JIT) |  |  |  | 1.067x ↓<br>[📄](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT/bm-20251117-blueberry-aarch64-python-5d2eb98a91f2cd703d14-3.15.0a1%2B-5d2eb98-vs-base.md)[📈](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT/bm-20251117-blueberry-aarch64-python-5d2eb98a91f2cd703d14-3.15.0a1%2B-5d2eb98-vs-base.svg)[🧠](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT/bm-20251117-blueberry-aarch64-python-5d2eb98a91f2cd703d14-3.15.0a1%2B-5d2eb98-vs-base-mem.svg) |
| [2025-11-17](results/bm-20251117-3.15.0a1%2B-5d2eb98) | python/5d2eb98a91f2cd703d14 | 5d2eb98 |  |  |  |  |
| [2025-11-17](results/bm-20251117-3.15.0a1%2B-16ea950-JIT) | python/16ea9505ce690485bab3 | 16ea950 (JIT) |  |  |  |  |
| [2025-11-16](results/bm-20251116-3.15.0a1%2B-5348c20) | python/5348c200f5b26d6dd21d | 5348c20 |  |  |  |  |
| [2025-11-13](results/bm-20251113-3.15.0a1%2B-196f151-JIT) | python/196f1519cd2d8134d764 | 196f151 (JIT) |  |  |  | 1.009x ↑<br>[📄](results/bm-20251113-3.15.0a1%2B-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1%2B-196f151-vs-base.md)[📈](results/bm-20251113-3.15.0a1%2B-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1%2B-196f151-vs-base.svg)[🧠](results/bm-20251113-3.15.0a1%2B-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1%2B-196f151-vs-base-mem.svg) |
| [2025-11-13](results/bm-20251113-3.15.0a1%2B-196f151) | python/196f1519cd2d8134d764 | 196f151 |  |  |  |  |
| [2025-08-02](results/bm-20250802-3.15.0a0-801cf3f-JIT) | Fidget-Spinner/last_good_arm_commit | 801cf3f (JIT) |  |  |  |  |
| [2025-08-02](results/bm-20250802-3.15.0a0-801cf3f) | Fidget-Spinner/last_good_arm_commit | 801cf3f |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT) | python/ca1e86f9d963dc298d9a | ca1e86f (JIT) |  |  |  | 1.013x ↑<br>[📄](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f) | python/ca1e86f9d963dc298d9a | ca1e86f |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT) | python/b3b63e8d6d296b879fdd | b3b63e8 (JIT) |  |  |  | 1.005x ↑<br>[📄](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8) | python/b3b63e8d6d296b879fdd | b3b63e8 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-bc9b9d4) | python/main | bc9b9d4 |  |  |  |  |


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
