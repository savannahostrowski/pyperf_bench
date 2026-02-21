# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (0629261)](results/bm-20260220-3.15.0a6%2B-0629261/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (0629261)](results/bm-20260220-3.15.0a6%2B-0629261-PYTHON_UOPS/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT) | python/06292614ff7cef0ba28d | 0629261 (JIT) |  |  |  | 1.014x ↑<br>[📄](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)[📈](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg)[🧠](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-blueberry-aarch64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base-mem.svg) |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261) | python/06292614ff7cef0ba28d | 0629261 |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18-JIT) | python/852ec189784d6f11e6c2 | 852ec18 (JIT) |  |  |  | 1.021x ↑<br>[📄](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-blueberry-aarch64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.md)[📈](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-blueberry-aarch64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.svg)[🧠](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-blueberry-aarch64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base-mem.svg) |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18) | python/852ec189784d6f11e6c2 | 852ec18 |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT) | python/7ebe9243950e9038dbbd | 7ebe924 (JIT) |  |  |  | 1.007x ↑<br>[📄](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-blueberry-aarch64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.md)[📈](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-blueberry-aarch64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.svg)[🧠](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-blueberry-aarch64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base-mem.svg) |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924) | python/7ebe9243950e9038dbbd | 7ebe924 |  |  |  |  |
| [2026-02-17](results/bm-20260217-3.15.0a6%2B-e779777-JIT) | python/e779777c66595acc5991 | e779777 (JIT) |  |  |  | 1.004x ↑<br>[📄](results/bm-20260217-3.15.0a6%2B-e779777-JIT/bm-20260217-blueberry-aarch64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.md)[📈](results/bm-20260217-3.15.0a6%2B-e779777-JIT/bm-20260217-blueberry-aarch64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.svg)[🧠](results/bm-20260217-3.15.0a6%2B-e779777-JIT/bm-20260217-blueberry-aarch64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base-mem.svg) |
| [2026-02-17](results/bm-20260217-3.15.0a6%2B-e779777) | python/e779777c66595acc5991 | e779777 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT) | python/06292614ff7cef0ba28d | 0629261 (JIT) |  |  |  | 1.052x ↑<br>[📄](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)[📈](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg)[🧠](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-ripley-x86_64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base-mem.svg) |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261) | python/06292614ff7cef0ba28d | 0629261 |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18-JIT) | python/852ec189784d6f11e6c2 | 852ec18 (JIT) |  |  |  | 1.053x ↑<br>[📄](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-ripley-x86_64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.md)[📈](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-ripley-x86_64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.svg)[🧠](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-ripley-x86_64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base-mem.svg) |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18) | python/852ec189784d6f11e6c2 | 852ec18 |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT) | python/7ebe9243950e9038dbbd | 7ebe924 (JIT) |  |  |  | 1.038x ↑<br>[📄](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-ripley-x86_64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.md)[📈](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-ripley-x86_64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.svg)[🧠](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-ripley-x86_64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base-mem.svg) |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924) | python/7ebe9243950e9038dbbd | 7ebe924 |  |  |  |  |
| [2026-02-17](results/bm-20260217-3.15.0a6%2B-e779777-JIT) | python/e779777c66595acc5991 | e779777 (JIT) |  |  |  | 1.033x ↑<br>[📄](results/bm-20260217-3.15.0a6%2B-e779777-JIT/bm-20260217-ripley-x86_64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.md)[📈](results/bm-20260217-3.15.0a6%2B-e779777-JIT/bm-20260217-ripley-x86_64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base.svg)[🧠](results/bm-20260217-3.15.0a6%2B-e779777-JIT/bm-20260217-ripley-x86_64-python-e779777c66595acc5991-3.15.0a6%2B-e779777-vs-base-mem.svg) |
| [2026-02-17](results/bm-20260217-3.15.0a6%2B-e779777) | python/e779777c66595acc5991 | e779777 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT) | python/06292614ff7cef0ba28d | 0629261 (JIT) |  |  |  | 1.169x ↑<br>[📄](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-prometheus-amd64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.md)[📈](results/bm-20260220-3.15.0a6%2B-0629261-JIT/bm-20260220-prometheus-amd64-python-06292614ff7cef0ba28d-3.15.0a6%2B-0629261-vs-base.svg) |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261) | python/06292614ff7cef0ba28d | 0629261 |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18-JIT) | python/852ec189784d6f11e6c2 | 852ec18 (JIT) |  |  |  | 1.172x ↑<br>[📄](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-prometheus-amd64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.md)[📈](results/bm-20260219-3.15.0a6%2B-852ec18-JIT/bm-20260219-prometheus-amd64-python-852ec189784d6f11e6c2-3.15.0a6%2B-852ec18-vs-base.svg) |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18) | python/852ec189784d6f11e6c2 | 852ec18 |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT) | python/7ebe9243950e9038dbbd | 7ebe924 (JIT) |  |  |  | 1.162x ↑<br>[📄](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-prometheus-amd64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.md)[📈](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT/bm-20260219-prometheus-amd64-python-7ebe9243950e9038dbbd-3.15.0a6%2B-7ebe924-vs-base.svg) |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924) | python/7ebe9243950e9038dbbd | 7ebe924 |  |  |  |  |
| [2026-02-17](results/bm-20260217-3.15.0a6%2B-e779777) | python/e779777c66595acc5991 | e779777 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-TAILCALL) | python/06292614ff7cef0ba28d | 0629261 (TAILCALL) |  |  |  |  |
| [2026-02-20](results/bm-20260220-3.15.0a6%2B-0629261-JIT%2CTAILCALL) | python/06292614ff7cef0ba28d | 0629261 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18-TAILCALL) | python/852ec189784d6f11e6c2 | 852ec18 (TAILCALL) |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-852ec18-JIT%2CTAILCALL) | python/852ec189784d6f11e6c2 | 852ec18 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924-TAILCALL) | python/7ebe9243950e9038dbbd | 7ebe924 (TAILCALL) |  |  |  |  |
| [2026-02-19](results/bm-20260219-3.15.0a6%2B-7ebe924-JIT%2CTAILCALL) | python/7ebe9243950e9038dbbd | 7ebe924 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-17](results/bm-20260217-3.15.0a6%2B-e779777-TAILCALL) | python/e779777c66595acc5991 | e779777 (TAILCALL) |  |  |  |  |
| [2026-02-17](results/bm-20260217-3.15.0a6%2B-e779777-JIT%2CTAILCALL) | python/e779777c66595acc5991 | e779777 (JIT) (TAILCALL) |  |  |  |  |


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
