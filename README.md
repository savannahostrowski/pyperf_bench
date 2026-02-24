# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (fd04005)](results/bm-20260223-3.15.0a6%2B-fd04005/bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (fd04005)](results/bm-20260223-3.15.0a6%2B-fd04005-PYTHON_UOPS/bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005-JIT) | python/fd0400585eb957c7d108 | fd04005 (JIT) |  |  |  | 1.018x ↑<br>[📄](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-blueberry-aarch64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.md)[📈](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-blueberry-aarch64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.svg)[🧠](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-blueberry-aarch64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base-mem.svg) |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005) | python/fd0400585eb957c7d108 | fd04005 |  |  |  |  |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT) | python/79f6caf8f1f52788e15c | 79f6caf (JIT) |  |  |  | 1.020x ↑<br>[📄](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-blueberry-aarch64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.md)[📈](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-blueberry-aarch64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.svg)[🧠](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-blueberry-aarch64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base-mem.svg) |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf) | python/79f6caf8f1f52788e15c | 79f6caf |  |  |  |  |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT) | python/2be2dd5fc219a5c252d7 | 2be2dd5 (JIT) |  |  |  | 1.018x ↑<br>[📄](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-blueberry-aarch64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.md)[📈](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-blueberry-aarch64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.svg)[🧠](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-blueberry-aarch64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base-mem.svg) |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5) | python/2be2dd5fc219a5c252d7 | 2be2dd5 |  |  |  |  |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT) | python/06292614ff7cef0ba28d | 0629261 (JIT) |  |  |  | 1.014x ↑<br>[📄](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)[📈](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg)[🧠](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base-mem.svg) |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261) | python/06292614ff7cef0ba28d | 0629261 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005-JIT) | python/fd0400585eb957c7d108 | fd04005 (JIT) |  |  |  | 1.045x ↑<br>[📄](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.md)[📈](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.svg)[🧠](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-ripley-x86_64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base-mem.svg) |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005) | python/fd0400585eb957c7d108 | fd04005 |  |  |  |  |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT) | python/79f6caf8f1f52788e15c | 79f6caf (JIT) |  |  |  | 1.045x ↑<br>[📄](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-ripley-x86_64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.md)[📈](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-ripley-x86_64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.svg)[🧠](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-ripley-x86_64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base-mem.svg) |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf) | python/79f6caf8f1f52788e15c | 79f6caf |  |  |  |  |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT) | python/2be2dd5fc219a5c252d7 | 2be2dd5 (JIT) |  |  |  | 1.040x ↑<br>[📄](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-ripley-x86_64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.md)[📈](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-ripley-x86_64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.svg)[🧠](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-ripley-x86_64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base-mem.svg) |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5) | python/2be2dd5fc219a5c252d7 | 2be2dd5 |  |  |  |  |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT) | python/06292614ff7cef0ba28d | 0629261 (JIT) |  |  |  | 1.052x ↑<br>[📄](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)[📈](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg)[🧠](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base-mem.svg) |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261) | python/06292614ff7cef0ba28d | 0629261 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005-JIT) | python/fd0400585eb957c7d108 | fd04005 (JIT) |  |  |  | 1.185x ↑<br>[📄](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-prometheus-amd64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.md)[📈](results/bm-20260223-3.15.0a6%2B-fd04005-JIT/bm-20260223-prometheus-amd64-python-fd0400585eb957c7d108-3.15.0a6%2B-fd04005-vs-base.svg) |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005) | python/fd0400585eb957c7d108 | fd04005 |  |  |  |  |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT) | python/79f6caf8f1f52788e15c | 79f6caf (JIT) |  |  |  | 1.171x ↑<br>[📄](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-prometheus-amd64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.md)[📈](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT/bm-20260222-prometheus-amd64-python-79f6caf8f1f52788e15c-3.15.0a6%2B-79f6caf-vs-base.svg) |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf) | python/79f6caf8f1f52788e15c | 79f6caf |  |  |  |  |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT) | python/2be2dd5fc219a5c252d7 | 2be2dd5 (JIT) |  |  |  | 1.179x ↑<br>[📄](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-prometheus-amd64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.md)[📈](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT/bm-20260221-prometheus-amd64-python-2be2dd5fc219a5c252d7-3.15.0a6%2B-2be2dd5-vs-base.svg) |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5) | python/2be2dd5fc219a5c252d7 | 2be2dd5 |  |  |  |  |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT) | python/06292614ff7cef0ba28d | 0629261 (JIT) |  |  |  | 1.169x ↑<br>[📄](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-prometheus-amd64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)[📈](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-prometheus-amd64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg) |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261) | python/06292614ff7cef0ba28d | 0629261 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005-TAILCALL) | python/fd0400585eb957c7d108 | fd04005 (TAILCALL) |  |  |  |  |
| [2026-02-23](results/bm-20260223-3.15.0a6%2B-fd04005-JIT%2CTAILCALL) | python/fd0400585eb957c7d108 | fd04005 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf-TAILCALL) | python/79f6caf8f1f52788e15c | 79f6caf (TAILCALL) |  |  |  |  |
| [2026-02-22](results/bm-20260222-3.15.0a6%2B-79f6caf-JIT%2CTAILCALL) | python/79f6caf8f1f52788e15c | 79f6caf (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5-TAILCALL) | python/2be2dd5fc219a5c252d7 | 2be2dd5 (TAILCALL) |  |  |  |  |
| [2026-02-21](results/bm-20260221-3.15.0a6%2B-2be2dd5-JIT%2CTAILCALL) | python/2be2dd5fc219a5c252d7 | 2be2dd5 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-TAILCALL) | python/06292614ff7cef0ba28d | 0629261 (TAILCALL) |  |  |  |  |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT%2CTAILCALL) | python/06292614ff7cef0ba28d | 0629261 (JIT) (TAILCALL) |  |  |  |  |


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
