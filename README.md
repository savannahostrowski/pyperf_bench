# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (c5fcdb4)](results/bm-20260425-3.15.0a8%2B-c5fcdb4/bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (c5fcdb4)](results/bm-20260425-3.15.0a8%2B-c5fcdb4-PYTHON_UOPS/bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 (JIT) |  |  |  | 1.010x ↑<br>[📄](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT/bm-20260425-blueberry-aarch64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.md)[📈](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT/bm-20260425-blueberry-aarch64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.svg)[🧠](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT/bm-20260425-blueberry-aarch64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base-mem.svg) |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 |  |  |  |  |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2-JIT) | python/95559d2a7e0071342dff | 95559d2 (JIT) |  |  |  | 1.011x ↑<br>[📄](results/bm-20260424-3.15.0a8%2B-95559d2-JIT/bm-20260424-blueberry-aarch64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.md)[📈](results/bm-20260424-3.15.0a8%2B-95559d2-JIT/bm-20260424-blueberry-aarch64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.svg)[🧠](results/bm-20260424-3.15.0a8%2B-95559d2-JIT/bm-20260424-blueberry-aarch64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base-mem.svg) |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2) | python/95559d2a7e0071342dff | 95559d2 |  |  |  |  |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT) | python/448d7b96c181d13ca7f8 | 448d7b9 (JIT) |  |  |  | 1.006x ↑<br>[📄](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT/bm-20260423-blueberry-aarch64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.md)[📈](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT/bm-20260423-blueberry-aarch64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.svg)[🧠](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT/bm-20260423-blueberry-aarch64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base-mem.svg) |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9) | python/448d7b96c181d13ca7f8 | 448d7b9 |  |  |  |  |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd-JIT) | python/79321fdce3227cf09bb8 | 79321fd (JIT) |  |  |  | 1.010x ↑<br>[📄](results/bm-20260422-3.15.0a8%2B-79321fd-JIT/bm-20260422-blueberry-aarch64-python-79321fdce3227cf09bb8-3.15.0a8%2B-79321fd-vs-base.md)[📈](results/bm-20260422-3.15.0a8%2B-79321fd-JIT/bm-20260422-blueberry-aarch64-python-79321fdce3227cf09bb8-3.15.0a8%2B-79321fd-vs-base.svg)[🧠](results/bm-20260422-3.15.0a8%2B-79321fd-JIT/bm-20260422-blueberry-aarch64-python-79321fdce3227cf09bb8-3.15.0a8%2B-79321fd-vs-base-mem.svg) |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd) | python/79321fdce3227cf09bb8 | 79321fd |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 (JIT) |  |  |  | 1.082x ↑<br>[📄](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT/bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.md)[📈](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT/bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base.svg)[🧠](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT/bm-20260425-ripley-x86_64-python-c5fcdb4a9bd04b88f363-3.15.0a8%2B-c5fcdb4-vs-base-mem.svg) |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 |  |  |  |  |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2-JIT) | python/95559d2a7e0071342dff | 95559d2 (JIT) |  |  |  | 1.084x ↑<br>[📄](results/bm-20260424-3.15.0a8%2B-95559d2-JIT/bm-20260424-ripley-x86_64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.md)[📈](results/bm-20260424-3.15.0a8%2B-95559d2-JIT/bm-20260424-ripley-x86_64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base.svg)[🧠](results/bm-20260424-3.15.0a8%2B-95559d2-JIT/bm-20260424-ripley-x86_64-python-95559d2a7e0071342dff-3.15.0a8%2B-95559d2-vs-base-mem.svg) |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2) | python/95559d2a7e0071342dff | 95559d2 |  |  |  |  |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT) | python/448d7b96c181d13ca7f8 | 448d7b9 (JIT) |  |  |  | 1.089x ↑<br>[📄](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT/bm-20260423-ripley-x86_64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.md)[📈](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT/bm-20260423-ripley-x86_64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base.svg)[🧠](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT/bm-20260423-ripley-x86_64-python-448d7b96c181d13ca7f8-3.15.0a8%2B-448d7b9-vs-base-mem.svg) |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9) | python/448d7b96c181d13ca7f8 | 448d7b9 |  |  |  |  |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd-JIT) | python/79321fdce3227cf09bb8 | 79321fd (JIT) |  |  |  | 1.077x ↑<br>[📄](results/bm-20260422-3.15.0a8%2B-79321fd-JIT/bm-20260422-ripley-x86_64-python-79321fdce3227cf09bb8-3.15.0a8%2B-79321fd-vs-base.md)[📈](results/bm-20260422-3.15.0a8%2B-79321fd-JIT/bm-20260422-ripley-x86_64-python-79321fdce3227cf09bb8-3.15.0a8%2B-79321fd-vs-base.svg)[🧠](results/bm-20260422-3.15.0a8%2B-79321fd-JIT/bm-20260422-ripley-x86_64-python-79321fdce3227cf09bb8-3.15.0a8%2B-79321fd-vs-base-mem.svg) |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd) | python/79321fdce3227cf09bb8 | 79321fd |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4-TAILCALL) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 (TAILCALL) |  |  |  |  |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT%2CTAILCALL) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2-TAILCALL) | python/95559d2a7e0071342dff | 95559d2 (TAILCALL) |  |  |  |  |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2-JIT%2CTAILCALL) | python/95559d2a7e0071342dff | 95559d2 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9-TAILCALL) | python/448d7b96c181d13ca7f8 | 448d7b9 (TAILCALL) |  |  |  |  |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT%2CTAILCALL) | python/448d7b96c181d13ca7f8 | 448d7b9 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd-TAILCALL) | python/79321fdce3227cf09bb8 | 79321fd (TAILCALL) |  |  |  |  |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd-JIT%2CTAILCALL) | python/79321fdce3227cf09bb8 | 79321fd (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4-TAILCALL) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 (TAILCALL) |  |  |  |  |
| [2026-04-25](results/bm-20260425-3.15.0a8%2B-c5fcdb4-JIT%2CTAILCALL) | python/c5fcdb4a9bd04b88f363 | c5fcdb4 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2-TAILCALL) | python/95559d2a7e0071342dff | 95559d2 (TAILCALL) |  |  |  |  |
| [2026-04-24](results/bm-20260424-3.15.0a8%2B-95559d2-JIT%2CTAILCALL) | python/95559d2a7e0071342dff | 95559d2 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9-TAILCALL) | python/448d7b96c181d13ca7f8 | 448d7b9 (TAILCALL) |  |  |  |  |
| [2026-04-23](results/bm-20260423-3.15.0a8%2B-448d7b9-JIT%2CTAILCALL) | python/448d7b96c181d13ca7f8 | 448d7b9 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd-TAILCALL) | python/79321fdce3227cf09bb8 | 79321fd (TAILCALL) |  |  |  |  |
| [2026-04-22](results/bm-20260422-3.15.0a8%2B-79321fd-JIT%2CTAILCALL) | python/79321fdce3227cf09bb8 | 79321fd (JIT) (TAILCALL) |  |  |  |  |


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
