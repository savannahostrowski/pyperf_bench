# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (548526b)](results/bm-20260111-3.15.0a3%2B-548526b/bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (548526b)](results/bm-20260111-3.15.0a3%2B-548526b-PYTHON_UOPS/bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b-JIT) | python/548526bbbebd4e503470 | 548526b (JIT) |  |  |  | 1.015x ↓<br>[📄](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-blueberry-aarch64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.md)[📈](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-blueberry-aarch64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.svg)[🧠](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-blueberry-aarch64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base-mem.svg) |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b) | python/548526bbbebd4e503470 | 548526b |  |  |  |  |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT) | python/aa8578dc54df2af9daa3 | aa8578d (JIT) |  |  |  | 1.008x ↑<br>[📄](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-blueberry-aarch64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base.md)[📈](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-blueberry-aarch64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base.svg)[🧠](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-blueberry-aarch64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base-mem.svg) |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d) | python/aa8578dc54df2af9daa3 | aa8578d |  |  |  |  |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT) | python/95259116ecb4346b570b | 9525911 (JIT) |  |  |  | 1.030x ↑<br>[📄](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.md)[📈](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.svg)[🧠](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base-mem.svg) |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911) | python/95259116ecb4346b570b | 9525911 |  |  |  |  |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT) | python/dfeefbe8ead0e370cc70 | dfeefbe (JIT) |  |  |  | 1.031x ↑<br>[📄](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.md)[📈](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.svg)[🧠](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base-mem.svg) |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe) | python/dfeefbe8ead0e370cc70 | dfeefbe |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b-JIT) | python/548526bbbebd4e503470 | 548526b (JIT) |  |  |  | 1.043x ↑<br>[📄](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.md)[📈](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.svg)[🧠](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-ripley-x86_64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base-mem.svg) |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b) | python/548526bbbebd4e503470 | 548526b |  |  |  |  |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT) | python/aa8578dc54df2af9daa3 | aa8578d (JIT) |  |  |  | 1.045x ↑<br>[📄](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-ripley-x86_64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base.md)[📈](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-ripley-x86_64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base.svg)[🧠](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-ripley-x86_64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base-mem.svg) |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d) | python/aa8578dc54df2af9daa3 | aa8578d |  |  |  |  |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT) | python/95259116ecb4346b570b | 9525911 (JIT) |  |  |  | 1.037x ↑<br>[📄](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.md)[📈](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.svg)[🧠](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base-mem.svg) |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911) | python/95259116ecb4346b570b | 9525911 |  |  |  |  |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT) | python/dfeefbe8ead0e370cc70 | dfeefbe (JIT) |  |  |  | 1.030x ↑<br>[📄](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.md)[📈](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.svg)[🧠](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base-mem.svg) |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe) | python/dfeefbe8ead0e370cc70 | dfeefbe |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b-JIT) | python/548526bbbebd4e503470 | 548526b (JIT) |  |  |  | 1.154x ↑<br>[📄](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-prometheus-amd64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.md)[📈](results/bm-20260111-3.15.0a3%2B-548526b-JIT/bm-20260111-prometheus-amd64-python-548526bbbebd4e503470-3.15.0a3%2B-548526b-vs-base.svg) |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b) | python/548526bbbebd4e503470 | 548526b |  |  |  |  |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT) | python/aa8578dc54df2af9daa3 | aa8578d (JIT) |  |  |  | 1.161x ↑<br>[📄](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-prometheus-amd64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base.md)[📈](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT/bm-20260110-prometheus-amd64-python-aa8578dc54df2af9daa3-3.15.0a3%2B-aa8578d-vs-base.svg) |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d) | python/aa8578dc54df2af9daa3 | aa8578d |  |  |  |  |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT) | python/95259116ecb4346b570b | 9525911 (JIT) |  |  |  | 1.144x ↑<br>[📄](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-prometheus-amd64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.md)[📈](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-prometheus-amd64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.svg) |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911) | python/95259116ecb4346b570b | 9525911 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b-TAILCALL) | python/548526bbbebd4e503470 | 548526b (TAILCALL) |  |  |  |  |
| [2026-01-11](results/bm-20260111-3.15.0a3%2B-548526b-JIT%2CTAILCALL) | python/548526bbbebd4e503470 | 548526b (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d-TAILCALL) | python/aa8578dc54df2af9daa3 | aa8578d (TAILCALL) |  |  |  |  |
| [2026-01-10](results/bm-20260110-3.15.0a3%2B-aa8578d-JIT%2CTAILCALL) | python/aa8578dc54df2af9daa3 | aa8578d (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-TAILCALL) | python/95259116ecb4346b570b | 9525911 (TAILCALL) |  |  |  |  |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT%2CTAILCALL) | python/95259116ecb4346b570b | 9525911 (JIT) (TAILCALL) |  |  |  |  |


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
