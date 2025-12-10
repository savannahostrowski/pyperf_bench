# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (37fe9a9)](results/bm-20251209-3.15.0a2%2B-37fe9a9/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (37fe9a9)](results/bm-20251209-3.15.0a2%2B-37fe9a9-PYTHON_UOPS/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT) | python/37fe9a90c5f99fd3830b | 37fe9a9 (JIT) |  |  |  | 1.022x ↓<br>[📄](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)[📈](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)[🧠](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg) |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9) | python/37fe9a90c5f99fd3830b | 37fe9a9 |  |  |  |  |
| [2025-12-08](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT) | python/726e8e8defc487c55ade | 726e8e8 (JIT) |  |  |  | 1.063x ↓<br>[📄](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-blueberry-aarch64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base.md)[📈](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-blueberry-aarch64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base.svg)[🧠](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-blueberry-aarch64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base-mem.svg) |
| [2025-12-08](results/bm-20251208-3.15.0a2%2B-726e8e8) | python/726e8e8defc487c55ade | 726e8e8 |  |  |  |  |
| [2025-12-07](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT) | python/ef51a7c8f3f4511ad18e | ef51a7c (JIT) |  |  |  | 1.100x ↓<br>[📄](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base.md)[📈](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base.svg)[🧠](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-blueberry-aarch64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base-mem.svg) |
| [2025-12-07](results/bm-20251207-3.15.0a2%2B-ef51a7c) | python/ef51a7c8f3f4511ad18e | ef51a7c |  |  |  |  |
| [2025-12-06](results/bm-20251206-3.15.0a2%2B-572c780-JIT) | python/572c780aa875e4eb0096 | 572c780 (JIT) |  |  |  | 1.052x ↓<br>[📄](results/bm-20251206-3.15.0a2%2B-572c780-JIT/bm-20251206-blueberry-aarch64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.md)[📈](results/bm-20251206-3.15.0a2%2B-572c780-JIT/bm-20251206-blueberry-aarch64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.svg)[🧠](results/bm-20251206-3.15.0a2%2B-572c780-JIT/bm-20251206-blueberry-aarch64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base-mem.svg) |
| [2025-12-06](results/bm-20251206-3.15.0a2%2B-572c780) | python/572c780aa875e4eb0096 | 572c780 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT) | python/37fe9a90c5f99fd3830b | 37fe9a9 (JIT) |  |  |  | 1.017x ↑<br>[📄](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)[📈](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)[🧠](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg) |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9) | python/37fe9a90c5f99fd3830b | 37fe9a9 |  |  |  |  |
| [2025-12-08](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT) | python/726e8e8defc487c55ade | 726e8e8 (JIT) |  |  |  | 1.012x ↑<br>[📄](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base.md)[📈](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base.svg)[🧠](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-ripley-x86_64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base-mem.svg) |
| [2025-12-08](results/bm-20251208-3.15.0a2%2B-726e8e8) | python/726e8e8defc487c55ade | 726e8e8 |  |  |  |  |
| [2025-12-07](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT) | python/ef51a7c8f3f4511ad18e | ef51a7c (JIT) |  |  |  | 1.023x ↑<br>[📄](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-ripley-x86_64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base.md)[📈](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-ripley-x86_64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base.svg)[🧠](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-ripley-x86_64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base-mem.svg) |
| [2025-12-07](results/bm-20251207-3.15.0a2%2B-ef51a7c) | python/ef51a7c8f3f4511ad18e | ef51a7c |  |  |  |  |
| [2025-12-06](results/bm-20251206-3.15.0a2%2B-572c780-JIT) | python/572c780aa875e4eb0096 | 572c780 (JIT) |  |  |  | 1.021x ↑<br>[📄](results/bm-20251206-3.15.0a2%2B-572c780-JIT/bm-20251206-ripley-x86_64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.md)[📈](results/bm-20251206-3.15.0a2%2B-572c780-JIT/bm-20251206-ripley-x86_64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base.svg)[🧠](results/bm-20251206-3.15.0a2%2B-572c780-JIT/bm-20251206-ripley-x86_64-python-572c780aa875e4eb0096-3.15.0a2%2B-572c780-vs-base-mem.svg) |
| [2025-12-06](results/bm-20251206-3.15.0a2%2B-572c780) | python/572c780aa875e4eb0096 | 572c780 |  |  |  |  |
| [2025-12-05](results/bm-20251205-3.14.2-df79316-JIT) | Fidget-Spinner/paper_3.14.2 | df79316 (JIT) |  |  |  |  |
| [2025-12-05](results/bm-20251205-3.14.2-df79316) | Fidget-Spinner/paper_3.14.2 | df79316 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT) | python/37fe9a90c5f99fd3830b | 37fe9a9 (JIT) |  |  |  | 1.021x ↑<br>[📄](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)[📈](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)[🧠](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-jones-arm64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg) |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9) | python/37fe9a90c5f99fd3830b | 37fe9a9 |  |  |  |  |
| [2025-12-08](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT) | python/726e8e8defc487c55ade | 726e8e8 (JIT) |  |  |  | 1.018x ↑<br>[📄](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base.md)[📈](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base.svg)[🧠](results/bm-20251208-3.15.0a2%2B-726e8e8-JIT/bm-20251208-jones-arm64-python-726e8e8defc487c55ade-3.15.0a2%2B-726e8e8-vs-base-mem.svg) |
| [2025-12-08](results/bm-20251208-3.15.0a2%2B-726e8e8) | python/726e8e8defc487c55ade | 726e8e8 |  |  |  |  |
| [2025-12-07](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT) | python/ef51a7c8f3f4511ad18e | ef51a7c (JIT) |  |  |  | 1.013x ↑<br>[📄](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base.md)[📈](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base.svg)[🧠](results/bm-20251207-3.15.0a2%2B-ef51a7c-JIT/bm-20251207-jones-arm64-python-ef51a7c8f3f4511ad18e-3.15.0a2%2B-ef51a7c-vs-base-mem.svg) |
| [2025-12-07](results/bm-20251207-3.15.0a2%2B-ef51a7c) | python/ef51a7c8f3f4511ad18e | ef51a7c |  |  |  |  |


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
