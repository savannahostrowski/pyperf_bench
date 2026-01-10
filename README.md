# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (9525911)](results/bm-20260109-3.15.0a3%2B-9525911/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (9525911)](results/bm-20260109-3.15.0a3%2B-9525911-PYTHON_UOPS/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT) | python/95259116ecb4346b570b | 9525911 (JIT) |  |  |  | 1.030x ↑<br>[📄](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.md)[📈](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.svg)[🧠](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-blueberry-aarch64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base-mem.svg) |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911) | python/95259116ecb4346b570b | 9525911 |  |  |  |  |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT) | python/dfeefbe8ead0e370cc70 | dfeefbe (JIT) |  |  |  | 1.031x ↑<br>[📄](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.md)[📈](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.svg)[🧠](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-blueberry-aarch64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base-mem.svg) |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe) | python/dfeefbe8ead0e370cc70 | dfeefbe |  |  |  |  |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT) | python/f11f5ebfe6614de23918 | f11f5eb (JIT) |  |  |  | 1.035x ↑<br>[📄](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base.md)[📈](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base.svg)[🧠](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-blueberry-aarch64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base-mem.svg) |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb) | python/f11f5ebfe6614de23918 | f11f5eb |  |  |  |  |
| [2026-01-06](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT) | python/b866a1c73f8160647545 | b866a1c (JIT) |  |  |  | 1.016x ↑<br>[📄](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT/bm-20260106-blueberry-aarch64-python-b866a1c73f8160647545-3.15.0a3%2B-b866a1c-vs-base.md)[📈](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT/bm-20260106-blueberry-aarch64-python-b866a1c73f8160647545-3.15.0a3%2B-b866a1c-vs-base.svg)[🧠](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT/bm-20260106-blueberry-aarch64-python-b866a1c73f8160647545-3.15.0a3%2B-b866a1c-vs-base-mem.svg) |
| [2026-01-06](results/bm-20260106-3.15.0a3%2B-b866a1c) | python/b866a1c73f8160647545 | b866a1c |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT) | python/95259116ecb4346b570b | 9525911 (JIT) |  |  |  | 1.037x ↑<br>[📄](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.md)[📈](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.svg)[🧠](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-ripley-x86_64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base-mem.svg) |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911) | python/95259116ecb4346b570b | 9525911 |  |  |  |  |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT) | python/dfeefbe8ead0e370cc70 | dfeefbe (JIT) |  |  |  | 1.030x ↑<br>[📄](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.md)[📈](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.svg)[🧠](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-ripley-x86_64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base-mem.svg) |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe) | python/dfeefbe8ead0e370cc70 | dfeefbe |  |  |  |  |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT) | python/f11f5ebfe6614de23918 | f11f5eb (JIT) |  |  |  | 1.037x ↑<br>[📄](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-ripley-x86_64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base.md)[📈](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-ripley-x86_64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base.svg)[🧠](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-ripley-x86_64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base-mem.svg) |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb) | python/f11f5ebfe6614de23918 | f11f5eb |  |  |  |  |
| [2026-01-06](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT) | python/b866a1c73f8160647545 | b866a1c (JIT) |  |  |  | 1.046x ↑<br>[📄](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT/bm-20260106-ripley-x86_64-python-b866a1c73f8160647545-3.15.0a3%2B-b866a1c-vs-base.md)[📈](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT/bm-20260106-ripley-x86_64-python-b866a1c73f8160647545-3.15.0a3%2B-b866a1c-vs-base.svg)[🧠](results/bm-20260106-3.15.0a3%2B-b866a1c-JIT/bm-20260106-ripley-x86_64-python-b866a1c73f8160647545-3.15.0a3%2B-b866a1c-vs-base-mem.svg) |
| [2026-01-06](results/bm-20260106-3.15.0a3%2B-b866a1c) | python/b866a1c73f8160647545 | b866a1c |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT) | python/95259116ecb4346b570b | 9525911 (JIT) |  |  |  | 1.144x ↑<br>[📄](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-prometheus-amd64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.md)[📈](results/bm-20260109-3.15.0a3%2B-9525911-JIT/bm-20260109-prometheus-amd64-python-95259116ecb4346b570b-3.15.0a3%2B-9525911-vs-base.svg) |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911) | python/95259116ecb4346b570b | 9525911 |  |  |  |  |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT) | python/dfeefbe8ead0e370cc70 | dfeefbe (JIT) |  |  |  | 1.158x ↑<br>[📄](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-prometheus-amd64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.md)[📈](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT/bm-20260108-prometheus-amd64-python-dfeefbe8ead0e370cc70-3.15.0a3%2B-dfeefbe-vs-base.svg) |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe) | python/dfeefbe8ead0e370cc70 | dfeefbe |  |  |  |  |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT) | python/f11f5ebfe6614de23918 | f11f5eb (JIT) |  |  |  | 1.169x ↑<br>[📄](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-prometheus-amd64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base.md)[📈](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT/bm-20260107-prometheus-amd64-python-f11f5ebfe6614de23918-3.15.0a3%2B-f11f5eb-vs-base.svg) |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb) | python/f11f5ebfe6614de23918 | f11f5eb |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-TAILCALL) | python/95259116ecb4346b570b | 9525911 (TAILCALL) |  |  |  |  |
| [2026-01-09](results/bm-20260109-3.15.0a3%2B-9525911-JIT%2CTAILCALL) | python/95259116ecb4346b570b | 9525911 (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe-TAILCALL) | python/dfeefbe8ead0e370cc70 | dfeefbe (TAILCALL) |  |  |  |  |
| [2026-01-08](results/bm-20260108-3.15.0a3%2B-dfeefbe-JIT%2CTAILCALL) | python/dfeefbe8ead0e370cc70 | dfeefbe (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb-TAILCALL) | python/f11f5ebfe6614de23918 | f11f5eb (TAILCALL) |  |  |  |  |
| [2026-01-07](results/bm-20260107-3.15.0a3%2B-f11f5eb-JIT%2CTAILCALL) | python/f11f5ebfe6614de23918 | f11f5eb (JIT) (TAILCALL) |  |  |  |  |


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
