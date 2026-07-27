# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (993a0c6)](results/bm-20260727-3.16.0a0-993a0c6/bm-20260727-ripley-x86_64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (993a0c6)](results/bm-20260727-3.16.0a0-993a0c6-PYTHON_UOPS/bm-20260727-ripley-x86_64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6-JIT) | python/993a0c65a7b1836aa208 | 993a0c6 (JIT) |  |  |  | 1.028x ↑<br>[📄](results/bm-20260727-3.16.0a0-993a0c6-JIT/bm-20260727-blueberry-aarch64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-vs-base.md)[📈](results/bm-20260727-3.16.0a0-993a0c6-JIT/bm-20260727-blueberry-aarch64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-vs-base.svg)[🧠](results/bm-20260727-3.16.0a0-993a0c6-JIT/bm-20260727-blueberry-aarch64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-vs-base-mem.svg) |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6) | python/993a0c65a7b1836aa208 | 993a0c6 |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c-JIT) | python/b86a41cbf631c959d274 | b86a41c (JIT) |  |  |  | 1.003x ↓<br>[📄](results/bm-20260725-3.16.0a0-b86a41c-JIT/bm-20260725-blueberry-aarch64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.md)[📈](results/bm-20260725-3.16.0a0-b86a41c-JIT/bm-20260725-blueberry-aarch64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.svg)[🧠](results/bm-20260725-3.16.0a0-b86a41c-JIT/bm-20260725-blueberry-aarch64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base-mem.svg) |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c) | python/b86a41cbf631c959d274 | b86a41c |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2-JIT) | python/59e67c284d3e8dcb708e | 59e67c2 (JIT) |  |  |  | 1.005x ↓<br>[📄](results/bm-20260725-3.16.0a0-59e67c2-JIT/bm-20260725-blueberry-aarch64-python-59e67c284d3e8dcb708e-3.16.0a0-59e67c2-vs-base.md)[📈](results/bm-20260725-3.16.0a0-59e67c2-JIT/bm-20260725-blueberry-aarch64-python-59e67c284d3e8dcb708e-3.16.0a0-59e67c2-vs-base.svg)[🧠](results/bm-20260725-3.16.0a0-59e67c2-JIT/bm-20260725-blueberry-aarch64-python-59e67c284d3e8dcb708e-3.16.0a0-59e67c2-vs-base-mem.svg) |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2) | python/59e67c284d3e8dcb708e | 59e67c2 |  |  |  |  |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f-JIT) | python/66e313f471516bfa04c5 | 66e313f (JIT) |  |  |  | 1.010x ↓<br>[📄](results/bm-20260723-3.16.0a0-66e313f-JIT/bm-20260723-blueberry-aarch64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.md)[📈](results/bm-20260723-3.16.0a0-66e313f-JIT/bm-20260723-blueberry-aarch64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.svg)[🧠](results/bm-20260723-3.16.0a0-66e313f-JIT/bm-20260723-blueberry-aarch64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base-mem.svg) |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f) | python/66e313f471516bfa04c5 | 66e313f |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6-JIT) | python/993a0c65a7b1836aa208 | 993a0c6 (JIT) |  |  |  | 1.076x ↑<br>[📄](results/bm-20260727-3.16.0a0-993a0c6-JIT/bm-20260727-ripley-x86_64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-vs-base.md)[📈](results/bm-20260727-3.16.0a0-993a0c6-JIT/bm-20260727-ripley-x86_64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-vs-base.svg)[🧠](results/bm-20260727-3.16.0a0-993a0c6-JIT/bm-20260727-ripley-x86_64-python-993a0c65a7b1836aa208-3.16.0a0-993a0c6-vs-base-mem.svg) |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6) | python/993a0c65a7b1836aa208 | 993a0c6 |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c-JIT) | python/b86a41cbf631c959d274 | b86a41c (JIT) |  |  |  | 1.068x ↑<br>[📄](results/bm-20260725-3.16.0a0-b86a41c-JIT/bm-20260725-ripley-x86_64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.md)[📈](results/bm-20260725-3.16.0a0-b86a41c-JIT/bm-20260725-ripley-x86_64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base.svg)[🧠](results/bm-20260725-3.16.0a0-b86a41c-JIT/bm-20260725-ripley-x86_64-python-b86a41cbf631c959d274-3.16.0a0-b86a41c-vs-base-mem.svg) |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c) | python/b86a41cbf631c959d274 | b86a41c |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2-JIT) | python/59e67c284d3e8dcb708e | 59e67c2 (JIT) |  |  |  | 1.069x ↑<br>[📄](results/bm-20260725-3.16.0a0-59e67c2-JIT/bm-20260725-ripley-x86_64-python-59e67c284d3e8dcb708e-3.16.0a0-59e67c2-vs-base.md)[📈](results/bm-20260725-3.16.0a0-59e67c2-JIT/bm-20260725-ripley-x86_64-python-59e67c284d3e8dcb708e-3.16.0a0-59e67c2-vs-base.svg)[🧠](results/bm-20260725-3.16.0a0-59e67c2-JIT/bm-20260725-ripley-x86_64-python-59e67c284d3e8dcb708e-3.16.0a0-59e67c2-vs-base-mem.svg) |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2) | python/59e67c284d3e8dcb708e | 59e67c2 |  |  |  |  |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f-JIT) | python/66e313f471516bfa04c5 | 66e313f (JIT) |  |  |  | 1.070x ↑<br>[📄](results/bm-20260723-3.16.0a0-66e313f-JIT/bm-20260723-ripley-x86_64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.md)[📈](results/bm-20260723-3.16.0a0-66e313f-JIT/bm-20260723-ripley-x86_64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base.svg)[🧠](results/bm-20260723-3.16.0a0-66e313f-JIT/bm-20260723-ripley-x86_64-python-66e313f471516bfa04c5-3.16.0a0-66e313f-vs-base-mem.svg) |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f) | python/66e313f471516bfa04c5 | 66e313f |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6-TAILCALL) | python/993a0c65a7b1836aa208 | 993a0c6 (TAILCALL) |  |  |  |  |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6-JIT%2CTAILCALL) | python/993a0c65a7b1836aa208 | 993a0c6 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c-TAILCALL) | python/b86a41cbf631c959d274 | b86a41c (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c-JIT%2CTAILCALL) | python/b86a41cbf631c959d274 | b86a41c (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2-TAILCALL) | python/59e67c284d3e8dcb708e | 59e67c2 (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2-JIT%2CTAILCALL) | python/59e67c284d3e8dcb708e | 59e67c2 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f-TAILCALL) | python/66e313f471516bfa04c5 | 66e313f (TAILCALL) |  |  |  |  |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f-JIT%2CTAILCALL) | python/66e313f471516bfa04c5 | 66e313f (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6-TAILCALL) | python/993a0c65a7b1836aa208 | 993a0c6 (TAILCALL) |  |  |  |  |
| [2026-07-27](results/bm-20260727-3.16.0a0-993a0c6-JIT%2CTAILCALL) | python/993a0c65a7b1836aa208 | 993a0c6 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c-TAILCALL) | python/b86a41cbf631c959d274 | b86a41c (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-b86a41c-JIT%2CTAILCALL) | python/b86a41cbf631c959d274 | b86a41c (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2-TAILCALL) | python/59e67c284d3e8dcb708e | 59e67c2 (TAILCALL) |  |  |  |  |
| [2026-07-25](results/bm-20260725-3.16.0a0-59e67c2-JIT%2CTAILCALL) | python/59e67c284d3e8dcb708e | 59e67c2 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f-TAILCALL) | python/66e313f471516bfa04c5 | 66e313f (TAILCALL) |  |  |  |  |
| [2026-07-23](results/bm-20260723-3.16.0a0-66e313f-JIT%2CTAILCALL) | python/66e313f471516bfa04c5 | 66e313f (JIT) (TAILCALL) |  |  |  |  |


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
