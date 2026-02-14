# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (fdbc135)](results/bm-20260213-3.15.0a6%2B-fdbc135/bm-20260213-ripley-x86_64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (fdbc135)](results/bm-20260213-3.15.0a6%2B-fdbc135-PYTHON_UOPS/bm-20260213-ripley-x86_64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT) | python/fdbc135f9cf57599cca8 | fdbc135 (JIT) |  |  |  | 1.020x ↑<br>[📄](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-blueberry-aarch64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base.md)[📈](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-blueberry-aarch64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base.svg)[🧠](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-blueberry-aarch64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base-mem.svg) |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135) | python/fdbc135f9cf57599cca8 | fdbc135 |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT) | python/945bf8ce1bf7ee388175 | 945bf8c (JIT) |  |  |  | 1.015x ↑<br>[📄](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-blueberry-aarch64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.md)[📈](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-blueberry-aarch64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.svg)[🧠](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-blueberry-aarch64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base-mem.svg) |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c) | python/945bf8ce1bf7ee388175 | 945bf8c |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106-JIT) | python/46d5106cfa903329821c | 46d5106 (JIT) |  |  |  | 1.010x ↑<br>[📄](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-blueberry-aarch64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.md)[📈](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-blueberry-aarch64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.svg)[🧠](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-blueberry-aarch64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base-mem.svg) |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106) | python/46d5106cfa903329821c | 46d5106 |  |  |  |  |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d-JIT) | python/936d60dbe1679f05d7ce | 936d60d (JIT) |  |  |  | 1.011x ↑<br>[📄](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-blueberry-aarch64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.md)[📈](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-blueberry-aarch64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.svg)[🧠](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-blueberry-aarch64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base-mem.svg) |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d) | python/936d60dbe1679f05d7ce | 936d60d |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT) | python/fdbc135f9cf57599cca8 | fdbc135 (JIT) |  |  |  | 1.036x ↑<br>[📄](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-ripley-x86_64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base.md)[📈](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-ripley-x86_64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base.svg)[🧠](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-ripley-x86_64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base-mem.svg) |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135) | python/fdbc135f9cf57599cca8 | fdbc135 |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT) | python/945bf8ce1bf7ee388175 | 945bf8c (JIT) |  |  |  | 1.026x ↑<br>[📄](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-ripley-x86_64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.md)[📈](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-ripley-x86_64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.svg)[🧠](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-ripley-x86_64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base-mem.svg) |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c) | python/945bf8ce1bf7ee388175 | 945bf8c |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106-JIT) | python/46d5106cfa903329821c | 46d5106 (JIT) |  |  |  | 1.039x ↑<br>[📄](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-ripley-x86_64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.md)[📈](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-ripley-x86_64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.svg)[🧠](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-ripley-x86_64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base-mem.svg) |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106) | python/46d5106cfa903329821c | 46d5106 |  |  |  |  |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d-JIT) | python/936d60dbe1679f05d7ce | 936d60d (JIT) |  |  |  | 1.033x ↑<br>[📄](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-ripley-x86_64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.md)[📈](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-ripley-x86_64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.svg)[🧠](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-ripley-x86_64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base-mem.svg) |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d) | python/936d60dbe1679f05d7ce | 936d60d |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT) | python/fdbc135f9cf57599cca8 | fdbc135 (JIT) |  |  |  | 1.173x ↑<br>[📄](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-prometheus-amd64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base.md)[📈](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT/bm-20260213-prometheus-amd64-python-fdbc135f9cf57599cca8-3.15.0a6%2B-fdbc135-vs-base.svg) |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135) | python/fdbc135f9cf57599cca8 | fdbc135 |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT) | python/945bf8ce1bf7ee388175 | 945bf8c (JIT) |  |  |  | 1.151x ↑<br>[📄](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-prometheus-amd64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.md)[📈](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT/bm-20260212-prometheus-amd64-python-945bf8ce1bf7ee388175-3.15.0a6%2B-945bf8c-vs-base.svg) |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c) | python/945bf8ce1bf7ee388175 | 945bf8c |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106-JIT) | python/46d5106cfa903329821c | 46d5106 (JIT) |  |  |  | 1.161x ↑<br>[📄](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-prometheus-amd64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.md)[📈](results/bm-20260212-3.15.0a6%2B-46d5106-JIT/bm-20260212-prometheus-amd64-python-46d5106cfa903329821c-3.15.0a6%2B-46d5106-vs-base.svg) |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106) | python/46d5106cfa903329821c | 46d5106 |  |  |  |  |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d-JIT) | python/936d60dbe1679f05d7ce | 936d60d (JIT) |  |  |  | 1.150x ↑<br>[📄](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-prometheus-amd64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.md)[📈](results/bm-20260211-3.15.0a5%2B-936d60d-JIT/bm-20260211-prometheus-amd64-python-936d60dbe1679f05d7ce-3.15.0a5%2B-936d60d-vs-base.svg) |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d) | python/936d60dbe1679f05d7ce | 936d60d |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135-TAILCALL) | python/fdbc135f9cf57599cca8 | fdbc135 (TAILCALL) |  |  |  |  |
| [2026-02-13](results/bm-20260213-3.15.0a6%2B-fdbc135-JIT%2CTAILCALL) | python/fdbc135f9cf57599cca8 | fdbc135 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c-TAILCALL) | python/945bf8ce1bf7ee388175 | 945bf8c (TAILCALL) |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-945bf8c-JIT%2CTAILCALL) | python/945bf8ce1bf7ee388175 | 945bf8c (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106-TAILCALL) | python/46d5106cfa903329821c | 46d5106 (TAILCALL) |  |  |  |  |
| [2026-02-12](results/bm-20260212-3.15.0a6%2B-46d5106-JIT%2CTAILCALL) | python/46d5106cfa903329821c | 46d5106 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d-TAILCALL) | python/936d60dbe1679f05d7ce | 936d60d (TAILCALL) |  |  |  |  |
| [2026-02-11](results/bm-20260211-3.15.0a5%2B-936d60d-JIT%2CTAILCALL) | python/936d60dbe1679f05d7ce | 936d60d (JIT) (TAILCALL) |  |  |  |  |


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
