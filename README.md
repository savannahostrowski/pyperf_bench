# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (a7bb524)](results/bm-20260817-3.16.0a0-a7bb524/bm-20260817-ripley-x86_64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (a7bb524)](results/bm-20260817-3.16.0a0-a7bb524-PYTHON_UOPS/bm-20260817-ripley-x86_64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524-JIT) | python/a7bb524fef61f77ede01 | a7bb524 (JIT) |  |  |  | 1.017x ↓<br>[📄](results/bm-20260817-3.16.0a0-a7bb524-JIT/bm-20260817-blueberry-aarch64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-vs-base.md)[📈](results/bm-20260817-3.16.0a0-a7bb524-JIT/bm-20260817-blueberry-aarch64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-vs-base.svg)[🧠](results/bm-20260817-3.16.0a0-a7bb524-JIT/bm-20260817-blueberry-aarch64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-vs-base-mem.svg) |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524) | python/a7bb524fef61f77ede01 | a7bb524 |  |  |  |  |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce-JIT) | python/7a845ce16548bf94e777 | 7a845ce (JIT) |  |  |  | 1.011x ↑<br>[📄](results/bm-20260816-3.16.0a0-7a845ce-JIT/bm-20260816-blueberry-aarch64-python-7a845ce16548bf94e777-3.16.0a0-7a845ce-vs-base.md)[📈](results/bm-20260816-3.16.0a0-7a845ce-JIT/bm-20260816-blueberry-aarch64-python-7a845ce16548bf94e777-3.16.0a0-7a845ce-vs-base.svg)[🧠](results/bm-20260816-3.16.0a0-7a845ce-JIT/bm-20260816-blueberry-aarch64-python-7a845ce16548bf94e777-3.16.0a0-7a845ce-vs-base-mem.svg) |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce) | python/7a845ce16548bf94e777 | 7a845ce |  |  |  |  |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6-JIT) | python/e3287f631f3c88ed8019 | e3287f6 (JIT) |  |  |  | 1.006x ↓<br>[📄](results/bm-20260815-3.16.0a0-e3287f6-JIT/bm-20260815-blueberry-aarch64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.md)[📈](results/bm-20260815-3.16.0a0-e3287f6-JIT/bm-20260815-blueberry-aarch64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.svg)[🧠](results/bm-20260815-3.16.0a0-e3287f6-JIT/bm-20260815-blueberry-aarch64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base-mem.svg) |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6) | python/e3287f631f3c88ed8019 | e3287f6 |  |  |  |  |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61-JIT) | python/dffac6163e693cf80ed4 | dffac61 (JIT) |  |  |  | 1.005x ↓<br>[📄](results/bm-20260814-3.16.0a0-dffac61-JIT/bm-20260814-blueberry-aarch64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.md)[📈](results/bm-20260814-3.16.0a0-dffac61-JIT/bm-20260814-blueberry-aarch64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.svg)[🧠](results/bm-20260814-3.16.0a0-dffac61-JIT/bm-20260814-blueberry-aarch64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base-mem.svg) |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61) | python/dffac6163e693cf80ed4 | dffac61 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524-JIT) | python/a7bb524fef61f77ede01 | a7bb524 (JIT) |  |  |  | 1.076x ↑<br>[📄](results/bm-20260817-3.16.0a0-a7bb524-JIT/bm-20260817-ripley-x86_64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-vs-base.md)[📈](results/bm-20260817-3.16.0a0-a7bb524-JIT/bm-20260817-ripley-x86_64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-vs-base.svg)[🧠](results/bm-20260817-3.16.0a0-a7bb524-JIT/bm-20260817-ripley-x86_64-python-a7bb524fef61f77ede01-3.16.0a0-a7bb524-vs-base-mem.svg) |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524) | python/a7bb524fef61f77ede01 | a7bb524 |  |  |  |  |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce-JIT) | python/7a845ce16548bf94e777 | 7a845ce (JIT) |  |  |  | 1.073x ↑<br>[📄](results/bm-20260816-3.16.0a0-7a845ce-JIT/bm-20260816-ripley-x86_64-python-7a845ce16548bf94e777-3.16.0a0-7a845ce-vs-base.md)[📈](results/bm-20260816-3.16.0a0-7a845ce-JIT/bm-20260816-ripley-x86_64-python-7a845ce16548bf94e777-3.16.0a0-7a845ce-vs-base.svg)[🧠](results/bm-20260816-3.16.0a0-7a845ce-JIT/bm-20260816-ripley-x86_64-python-7a845ce16548bf94e777-3.16.0a0-7a845ce-vs-base-mem.svg) |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce) | python/7a845ce16548bf94e777 | 7a845ce |  |  |  |  |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6-JIT) | python/e3287f631f3c88ed8019 | e3287f6 (JIT) |  |  |  | 1.070x ↑<br>[📄](results/bm-20260815-3.16.0a0-e3287f6-JIT/bm-20260815-ripley-x86_64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.md)[📈](results/bm-20260815-3.16.0a0-e3287f6-JIT/bm-20260815-ripley-x86_64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base.svg)[🧠](results/bm-20260815-3.16.0a0-e3287f6-JIT/bm-20260815-ripley-x86_64-python-e3287f631f3c88ed8019-3.16.0a0-e3287f6-vs-base-mem.svg) |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6) | python/e3287f631f3c88ed8019 | e3287f6 |  |  |  |  |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61-JIT) | python/dffac6163e693cf80ed4 | dffac61 (JIT) |  |  |  | 1.074x ↑<br>[📄](results/bm-20260814-3.16.0a0-dffac61-JIT/bm-20260814-ripley-x86_64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.md)[📈](results/bm-20260814-3.16.0a0-dffac61-JIT/bm-20260814-ripley-x86_64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base.svg)[🧠](results/bm-20260814-3.16.0a0-dffac61-JIT/bm-20260814-ripley-x86_64-python-dffac6163e693cf80ed4-3.16.0a0-dffac61-vs-base-mem.svg) |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61) | python/dffac6163e693cf80ed4 | dffac61 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524-TAILCALL) | python/a7bb524fef61f77ede01 | a7bb524 (TAILCALL) |  |  |  |  |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524-JIT%2CTAILCALL) | python/a7bb524fef61f77ede01 | a7bb524 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce-TAILCALL) | python/7a845ce16548bf94e777 | 7a845ce (TAILCALL) |  |  |  |  |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce-JIT%2CTAILCALL) | python/7a845ce16548bf94e777 | 7a845ce (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6-TAILCALL) | python/e3287f631f3c88ed8019 | e3287f6 (TAILCALL) |  |  |  |  |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6-JIT%2CTAILCALL) | python/e3287f631f3c88ed8019 | e3287f6 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61-TAILCALL) | python/dffac6163e693cf80ed4 | dffac61 (TAILCALL) |  |  |  |  |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61-JIT%2CTAILCALL) | python/dffac6163e693cf80ed4 | dffac61 (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524-TAILCALL) | python/a7bb524fef61f77ede01 | a7bb524 (TAILCALL) |  |  |  |  |
| [2026-08-17](results/bm-20260817-3.16.0a0-a7bb524-JIT%2CTAILCALL) | python/a7bb524fef61f77ede01 | a7bb524 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce-TAILCALL) | python/7a845ce16548bf94e777 | 7a845ce (TAILCALL) |  |  |  |  |
| [2026-08-16](results/bm-20260816-3.16.0a0-7a845ce-JIT%2CTAILCALL) | python/7a845ce16548bf94e777 | 7a845ce (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6-TAILCALL) | python/e3287f631f3c88ed8019 | e3287f6 (TAILCALL) |  |  |  |  |
| [2026-08-15](results/bm-20260815-3.16.0a0-e3287f6-JIT%2CTAILCALL) | python/e3287f631f3c88ed8019 | e3287f6 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61-TAILCALL) | python/dffac6163e693cf80ed4 | dffac61 (TAILCALL) |  |  |  |  |
| [2026-08-14](results/bm-20260814-3.16.0a0-dffac61-JIT%2CTAILCALL) | python/dffac6163e693cf80ed4 | dffac61 (JIT) (TAILCALL) |  |  |  |  |


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
