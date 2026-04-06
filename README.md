# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (bce96a1)](results/bm-20260405-3.15.0a7%2B-bce96a1/bm-20260405-ripley-x86_64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (bce96a1)](results/bm-20260405-3.15.0a7%2B-bce96a1-PYTHON_UOPS/bm-20260405-ripley-x86_64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT) | python/bce96a181350f348560f | bce96a1 (JIT) |  |  |  | 1.003x ↓<br>[📄](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT/bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-vs-base.md)[📈](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT/bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-vs-base.svg)[🧠](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT/bm-20260405-blueberry-aarch64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-vs-base-mem.svg) |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1) | python/bce96a181350f348560f | bce96a1 |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT) | python/1f36a510a2a16e8ff155 | 1f36a51 (JIT) |  |  |  | 1.002x ↑<br>[📄](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT/bm-20260405-blueberry-aarch64-python-1f36a510a2a16e8ff155-3.15.0a7%2B-1f36a51-vs-base.md)[📈](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT/bm-20260405-blueberry-aarch64-python-1f36a510a2a16e8ff155-3.15.0a7%2B-1f36a51-vs-base.svg)[🧠](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT/bm-20260405-blueberry-aarch64-python-1f36a510a2a16e8ff155-3.15.0a7%2B-1f36a51-vs-base-mem.svg) |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51) | python/1f36a510a2a16e8ff155 | 1f36a51 |  |  |  |  |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083-JIT) | python/dea4083aa952c955a7c3 | dea4083 (JIT) |  |  |  | 1.021x ↓<br>[📄](results/bm-20260403-3.15.0a7%2B-dea4083-JIT/bm-20260403-blueberry-aarch64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.md)[📈](results/bm-20260403-3.15.0a7%2B-dea4083-JIT/bm-20260403-blueberry-aarch64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.svg)[🧠](results/bm-20260403-3.15.0a7%2B-dea4083-JIT/bm-20260403-blueberry-aarch64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base-mem.svg) |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083) | python/dea4083aa952c955a7c3 | dea4083 |  |  |  |  |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT) | python/617f4cc1c2605b86b483 | 617f4cc (JIT) |  |  |  | 1.003x ↓<br>[📄](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-blueberry-aarch64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.md)[📈](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-blueberry-aarch64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.svg)[🧠](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-blueberry-aarch64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base-mem.svg) |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc) | python/617f4cc1c2605b86b483 | 617f4cc |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT) | python/bce96a181350f348560f | bce96a1 (JIT) |  |  |  | 1.071x ↑<br>[📄](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT/bm-20260405-ripley-x86_64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-vs-base.md)[📈](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT/bm-20260405-ripley-x86_64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-vs-base.svg)[🧠](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT/bm-20260405-ripley-x86_64-python-bce96a181350f348560f-3.15.0a7%2B-bce96a1-vs-base-mem.svg) |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1) | python/bce96a181350f348560f | bce96a1 |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT) | python/1f36a510a2a16e8ff155 | 1f36a51 (JIT) |  |  |  | 1.070x ↑<br>[📄](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT/bm-20260405-ripley-x86_64-python-1f36a510a2a16e8ff155-3.15.0a7%2B-1f36a51-vs-base.md)[📈](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT/bm-20260405-ripley-x86_64-python-1f36a510a2a16e8ff155-3.15.0a7%2B-1f36a51-vs-base.svg)[🧠](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT/bm-20260405-ripley-x86_64-python-1f36a510a2a16e8ff155-3.15.0a7%2B-1f36a51-vs-base-mem.svg) |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51) | python/1f36a510a2a16e8ff155 | 1f36a51 |  |  |  |  |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083-JIT) | python/dea4083aa952c955a7c3 | dea4083 (JIT) |  |  |  | 1.060x ↑<br>[📄](results/bm-20260403-3.15.0a7%2B-dea4083-JIT/bm-20260403-ripley-x86_64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.md)[📈](results/bm-20260403-3.15.0a7%2B-dea4083-JIT/bm-20260403-ripley-x86_64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.svg)[🧠](results/bm-20260403-3.15.0a7%2B-dea4083-JIT/bm-20260403-ripley-x86_64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base-mem.svg) |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083) | python/dea4083aa952c955a7c3 | dea4083 |  |  |  |  |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT) | python/617f4cc1c2605b86b483 | 617f4cc (JIT) |  |  |  | 1.063x ↑<br>[📄](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-ripley-x86_64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.md)[📈](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-ripley-x86_64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.svg)[🧠](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-ripley-x86_64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base-mem.svg) |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc) | python/617f4cc1c2605b86b483 | 617f4cc |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1-TAILCALL) | python/bce96a181350f348560f | bce96a1 (TAILCALL) |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT%2CTAILCALL) | python/bce96a181350f348560f | bce96a1 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51-TAILCALL) | python/1f36a510a2a16e8ff155 | 1f36a51 (TAILCALL) |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT%2CTAILCALL) | python/1f36a510a2a16e8ff155 | 1f36a51 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-80d0a85-JIT%2CTAILCALL) | python/main | 80d0a85 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083-TAILCALL) | python/dea4083aa952c955a7c3 | dea4083 (TAILCALL) |  |  |  |  |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083-JIT%2CTAILCALL) | python/dea4083aa952c955a7c3 | dea4083 (JIT) (TAILCALL) |  |  |  | 1.006x ↓<br>[📄](results/bm-20260403-3.15.0a7%2B-dea4083-JIT%2CTAILCALL/bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.md)[📈](results/bm-20260403-3.15.0a7%2B-dea4083-JIT%2CTAILCALL/bm-20260403-prometheus-amd64-python-dea4083aa952c955a7c3-3.15.0a7%2B-dea4083-vs-base.svg) |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT) | python/617f4cc1c2605b86b483 | 617f4cc (JIT) |  |  |  | 1.214x ↑<br>[📄](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-prometheus-amd64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.md)[📈](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT/bm-20260402-prometheus-amd64-python-617f4cc1c2605b86b483-3.15.0a7%2B-617f4cc-vs-base.svg) |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc) | python/617f4cc1c2605b86b483 | 617f4cc |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1-TAILCALL) | python/bce96a181350f348560f | bce96a1 (TAILCALL) |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-bce96a1-JIT%2CTAILCALL) | python/bce96a181350f348560f | bce96a1 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51-TAILCALL) | python/1f36a510a2a16e8ff155 | 1f36a51 (TAILCALL) |  |  |  |  |
| [2026-04-05](results/bm-20260405-3.15.0a7%2B-1f36a51-JIT%2CTAILCALL) | python/1f36a510a2a16e8ff155 | 1f36a51 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083-TAILCALL) | python/dea4083aa952c955a7c3 | dea4083 (TAILCALL) |  |  |  |  |
| [2026-04-03](results/bm-20260403-3.15.0a7%2B-dea4083-JIT%2CTAILCALL) | python/dea4083aa952c955a7c3 | dea4083 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc-TAILCALL) | python/617f4cc1c2605b86b483 | 617f4cc (TAILCALL) |  |  |  |  |
| [2026-04-02](results/bm-20260402-3.15.0a7%2B-617f4cc-JIT%2CTAILCALL) | python/617f4cc1c2605b86b483 | 617f4cc (JIT) (TAILCALL) |  |  |  |  |


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
