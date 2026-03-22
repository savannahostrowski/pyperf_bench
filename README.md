# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (b5e4c46)](results/bm-20260320-3.15.0a7%2B-b5e4c46/bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (b5e4c46)](results/bm-20260320-3.15.0a7%2B-b5e4c46-PYTHON_UOPS/bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT) | python/b5e4c46be24d1fade0de | b5e4c46 (JIT) |  |  |  | 1.010x ↓<br>[📄](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-blueberry-aarch64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.md)[📈](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-blueberry-aarch64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.svg)[🧠](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-blueberry-aarch64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base-mem.svg) |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46) | python/b5e4c46be24d1fade0de | b5e4c46 |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT) | python/d357a7dbf38868844415 | d357a7d (JIT) |  |  |  | 1.022x ↓<br>[📄](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-blueberry-aarch64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.md)[📈](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-blueberry-aarch64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.svg)[🧠](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-blueberry-aarch64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base-mem.svg) |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d) | python/d357a7dbf38868844415 | d357a7d |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246-JIT) | python/abd5246305655fc09e4e | abd5246 (JIT) |  |  |  | 1.018x ↓<br>[📄](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-blueberry-aarch64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base.md)[📈](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-blueberry-aarch64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base.svg)[🧠](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-blueberry-aarch64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base-mem.svg) |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246) | python/abd5246305655fc09e4e | abd5246 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT) | python/b5e4c46be24d1fade0de | b5e4c46 (JIT) |  |  |  | 1.057x ↑<br>[📄](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.md)[📈](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.svg)[🧠](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-ripley-x86_64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base-mem.svg) |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46) | python/b5e4c46be24d1fade0de | b5e4c46 |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT) | python/d357a7dbf38868844415 | d357a7d (JIT) |  |  |  | 1.049x ↑<br>[📄](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-ripley-x86_64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.md)[📈](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-ripley-x86_64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.svg)[🧠](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-ripley-x86_64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base-mem.svg) |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d) | python/d357a7dbf38868844415 | d357a7d |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246-JIT) | python/abd5246305655fc09e4e | abd5246 (JIT) |  |  |  | 1.052x ↑<br>[📄](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-ripley-x86_64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base.md)[📈](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-ripley-x86_64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base.svg)[🧠](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-ripley-x86_64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base-mem.svg) |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246) | python/abd5246305655fc09e4e | abd5246 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT) | python/b5e4c46be24d1fade0de | b5e4c46 (JIT) |  |  |  | 1.220x ↑<br>[📄](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-prometheus-amd64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.md)[📈](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT/bm-20260320-prometheus-amd64-python-b5e4c46be24d1fade0de-3.15.0a7%2B-b5e4c46-vs-base.svg) |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46) | python/b5e4c46be24d1fade0de | b5e4c46 |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT) | python/d357a7dbf38868844415 | d357a7d (JIT) |  |  |  | 1.218x ↑<br>[📄](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-prometheus-amd64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.md)[📈](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT/bm-20260319-prometheus-amd64-python-d357a7dbf38868844415-3.15.0a7%2B-d357a7d-vs-base.svg) |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d) | python/d357a7dbf38868844415 | d357a7d |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246-JIT) | python/abd5246305655fc09e4e | abd5246 (JIT) |  |  |  | 1.204x ↑<br>[📄](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-prometheus-amd64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base.md)[📈](results/bm-20260319-3.15.0a7%2B-abd5246-JIT/bm-20260319-prometheus-amd64-python-abd5246305655fc09e4e-3.15.0a7%2B-abd5246-vs-base.svg) |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246) | python/abd5246305655fc09e4e | abd5246 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46-TAILCALL) | python/b5e4c46be24d1fade0de | b5e4c46 (TAILCALL) |  |  |  |  |
| [2026-03-20](results/bm-20260320-3.15.0a7%2B-b5e4c46-JIT%2CTAILCALL) | python/b5e4c46be24d1fade0de | b5e4c46 (JIT) (TAILCALL) |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d-TAILCALL) | python/d357a7dbf38868844415 | d357a7d (TAILCALL) |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-d357a7d-JIT%2CTAILCALL) | python/d357a7dbf38868844415 | d357a7d (JIT) (TAILCALL) |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246-TAILCALL) | python/abd5246305655fc09e4e | abd5246 (TAILCALL) |  |  |  |  |
| [2026-03-19](results/bm-20260319-3.15.0a7%2B-abd5246-JIT%2CTAILCALL) | python/abd5246305655fc09e4e | abd5246 (JIT) (TAILCALL) |  |  |  |  |


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
