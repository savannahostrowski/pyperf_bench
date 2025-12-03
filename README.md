# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (8801c6d)](results/bm-20251202-3.15.0a2%2B-8801c6d/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (8801c6d)](results/bm-20251202-3.15.0a2%2B-8801c6d-PYTHON_UOPS/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-02](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT) | python/8801c6dec79275e9b588 | 8801c6d (JIT) |  |  |  | 1.040x ↓<br>[📄](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.md)[📈](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.svg)[🧠](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-blueberry-aarch64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base-mem.svg) |
| [2025-12-02](results/bm-20251202-3.15.0a2%2B-8801c6d) | python/8801c6dec79275e9b588 | 8801c6d |  |  |  |  |
| [2025-12-01](results/bm-20251201-3.15.0a2%2B-eb89286-JIT) | python/eb892868b31322d7cf27 | eb89286 (JIT) |  |  |  | 1.168x ↓<br>[📄](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-blueberry-aarch64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.md)[📈](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-blueberry-aarch64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.svg)[🧠](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-blueberry-aarch64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base-mem.svg) |
| [2025-12-01](results/bm-20251201-3.15.0a2%2B-eb89286) | python/eb892868b31322d7cf27 | eb89286 |  |  |  |  |
| [2025-11-30](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT) | python/229ed3dd1f97b2f87629 | 229ed3d (JIT) |  |  |  | 1.077x ↓<br>[📄](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base.md)[📈](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base.svg)[🧠](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-blueberry-aarch64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base-mem.svg) |
| [2025-11-30](results/bm-20251130-3.15.0a2%2B-229ed3d) | python/229ed3dd1f97b2f87629 | 229ed3d |  |  |  |  |
| [2025-11-29](results/bm-20251129-3.15.0a2%2B-db098a4-JIT) | python/db098a475a47b16d25c8 | db098a4 (JIT) |  |  |  | 1.058x ↓<br>[📄](results/bm-20251129-3.15.0a2%2B-db098a4-JIT/bm-20251129-blueberry-aarch64-python-db098a475a47b16d25c8-3.15.0a2%2B-db098a4-vs-base.md)[📈](results/bm-20251129-3.15.0a2%2B-db098a4-JIT/bm-20251129-blueberry-aarch64-python-db098a475a47b16d25c8-3.15.0a2%2B-db098a4-vs-base.svg)[🧠](results/bm-20251129-3.15.0a2%2B-db098a4-JIT/bm-20251129-blueberry-aarch64-python-db098a475a47b16d25c8-3.15.0a2%2B-db098a4-vs-base-mem.svg) |
| [2025-11-29](results/bm-20251129-3.15.0a2%2B-db098a4) | python/db098a475a47b16d25c8 | db098a4 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-02](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT) | python/8801c6dec79275e9b588 | 8801c6d (JIT) |  |  |  | 1.013x ↑<br>[📄](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-ripley-x86_64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.md)[📈](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-ripley-x86_64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.svg)[🧠](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-ripley-x86_64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base-mem.svg) |
| [2025-12-02](results/bm-20251202-3.15.0a2%2B-8801c6d) | python/8801c6dec79275e9b588 | 8801c6d |  |  |  |  |
| [2025-12-01](results/bm-20251201-3.15.0a2%2B-eb89286-JIT) | python/eb892868b31322d7cf27 | eb89286 (JIT) |  |  |  | 1.014x ↑<br>[📄](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-ripley-x86_64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.md)[📈](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-ripley-x86_64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.svg)[🧠](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-ripley-x86_64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base-mem.svg) |
| [2025-12-01](results/bm-20251201-3.15.0a2%2B-eb89286) | python/eb892868b31322d7cf27 | eb89286 |  |  |  |  |
| [2025-11-30](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT) | python/229ed3dd1f97b2f87629 | 229ed3d (JIT) |  |  |  | 1.011x ↑<br>[📄](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-ripley-x86_64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base.md)[📈](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-ripley-x86_64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base.svg)[🧠](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-ripley-x86_64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base-mem.svg) |
| [2025-11-30](results/bm-20251130-3.15.0a2%2B-229ed3d) | python/229ed3dd1f97b2f87629 | 229ed3d |  |  |  |  |
| [2025-11-29](results/bm-20251129-3.15.0a2%2B-db098a4-JIT) | python/db098a475a47b16d25c8 | db098a4 (JIT) |  |  |  | 1.012x ↑<br>[📄](results/bm-20251129-3.15.0a2%2B-db098a4-JIT/bm-20251129-ripley-x86_64-python-db098a475a47b16d25c8-3.15.0a2%2B-db098a4-vs-base.md)[📈](results/bm-20251129-3.15.0a2%2B-db098a4-JIT/bm-20251129-ripley-x86_64-python-db098a475a47b16d25c8-3.15.0a2%2B-db098a4-vs-base.svg)[🧠](results/bm-20251129-3.15.0a2%2B-db098a4-JIT/bm-20251129-ripley-x86_64-python-db098a475a47b16d25c8-3.15.0a2%2B-db098a4-vs-base-mem.svg) |
| [2025-11-29](results/bm-20251129-3.15.0a2%2B-db098a4) | python/db098a475a47b16d25c8 | db098a4 |  |  |  |  |
| [2025-11-28](results/bm-20251128-3.15.0a2%2B-8760c1b-JIT) | brandtbucher/jit_unwind | 8760c1b (JIT) |  |  |  | 1.005x ↑<br>[📄](results/bm-20251128-3.15.0a2%2B-8760c1b-JIT/bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2%2B-8760c1b-vs-base.md)[📈](results/bm-20251128-3.15.0a2%2B-8760c1b-JIT/bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2%2B-8760c1b-vs-base.svg)[🧠](results/bm-20251128-3.15.0a2%2B-8760c1b-JIT/bm-20251128-ripley-x86_64-brandtbucher-jit_unwind-3.15.0a2%2B-8760c1b-vs-base-mem.svg) |
| [2025-11-26](results/bm-20251126-3.15.0a2%2B-9ac1428-JIT) | python/9ac14288d7147dbbae08 | 9ac1428 (JIT) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-02](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT) | python/8801c6dec79275e9b588 | 8801c6d (JIT) |  |  |  | 1.066x ↑<br>[📄](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-jones-arm64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.md)[📈](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-jones-arm64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base.svg)[🧠](results/bm-20251202-3.15.0a2%2B-8801c6d-JIT/bm-20251202-jones-arm64-python-8801c6dec79275e9b588-3.15.0a2%2B-8801c6d-vs-base-mem.svg) |
| [2025-12-02](results/bm-20251202-3.15.0a2%2B-8801c6d) | python/8801c6dec79275e9b588 | 8801c6d |  |  |  |  |
| [2025-12-01](results/bm-20251201-3.15.0a2%2B-eb89286-JIT) | python/eb892868b31322d7cf27 | eb89286 (JIT) |  |  |  | 1.067x ↑<br>[📄](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-jones-arm64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.md)[📈](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-jones-arm64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base.svg)[🧠](results/bm-20251201-3.15.0a2%2B-eb89286-JIT/bm-20251201-jones-arm64-python-eb892868b31322d7cf27-3.15.0a2%2B-eb89286-vs-base-mem.svg) |
| [2025-12-01](results/bm-20251201-3.15.0a2%2B-eb89286) | python/eb892868b31322d7cf27 | eb89286 |  |  |  |  |
| [2025-11-30](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT) | python/229ed3dd1f97b2f87629 | 229ed3d (JIT) |  |  |  | 1.074x ↑<br>[📄](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-jones-arm64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base.md)[📈](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-jones-arm64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base.svg)[🧠](results/bm-20251130-3.15.0a2%2B-229ed3d-JIT/bm-20251130-jones-arm64-python-229ed3dd1f97b2f87629-3.15.0a2%2B-229ed3d-vs-base-mem.svg) |
| [2025-11-30](results/bm-20251130-3.15.0a2%2B-229ed3d) | python/229ed3dd1f97b2f87629 | 229ed3d |  |  |  |  |


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
