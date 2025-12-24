# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (cc48bf0)](results/bm-20251223-3.15.0a3%2B-cc48bf0/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (cc48bf0)](results/bm-20251223-3.15.0a3%2B-cc48bf0-PYTHON_UOPS/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT) | python/cc48bf0fde8025d60a57 | cc48bf0 (JIT) |  |  |  | 1.013x ↑<br>[📄](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.md)[📈](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.svg)[🧠](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base-mem.svg) |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0) | python/cc48bf0fde8025d60a57 | cc48bf0 |  |  |  |  |
| [2025-12-22](results/bm-20251222-3.15.0a3%2B-9e51301-JIT) | python/9e513012341607458196 | 9e51301 (JIT) |  |  |  | 1.024x ↓<br>[📄](results/bm-20251222-3.15.0a3%2B-9e51301-JIT/bm-20251222-blueberry-aarch64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.md)[📈](results/bm-20251222-3.15.0a3%2B-9e51301-JIT/bm-20251222-blueberry-aarch64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.svg)[🧠](results/bm-20251222-3.15.0a3%2B-9e51301-JIT/bm-20251222-blueberry-aarch64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base-mem.svg) |
| [2025-12-22](results/bm-20251222-3.15.0a3%2B-9e51301) | python/9e513012341607458196 | 9e51301 |  |  |  |  |
| [2025-12-21](results/bm-20251221-3.15.0a3%2B-09044dd-JIT) | python/09044dd42b50e628b197 | 09044dd (JIT) |  |  |  | 1.014x ↓<br>[📄](results/bm-20251221-3.15.0a3%2B-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3%2B-09044dd-vs-base.md)[📈](results/bm-20251221-3.15.0a3%2B-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3%2B-09044dd-vs-base.svg)[🧠](results/bm-20251221-3.15.0a3%2B-09044dd-JIT/bm-20251221-blueberry-aarch64-python-09044dd42b50e628b197-3.15.0a3%2B-09044dd-vs-base-mem.svg) |
| [2025-12-21](results/bm-20251221-3.15.0a3%2B-09044dd) | python/09044dd42b50e628b197 | 09044dd |  |  |  |  |
| [2025-12-20](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT) | python/8d2d7bb2e754f8649a68 | 8d2d7bb (JIT) |  |  |  | 1.014x ↓<br>[📄](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT/bm-20251220-blueberry-aarch64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.md)[📈](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT/bm-20251220-blueberry-aarch64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.svg)[🧠](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT/bm-20251220-blueberry-aarch64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base-mem.svg) |
| [2025-12-20](results/bm-20251220-3.15.0a3%2B-8d2d7bb) | python/8d2d7bb2e754f8649a68 | 8d2d7bb |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT) | python/cc48bf0fde8025d60a57 | cc48bf0 (JIT) |  |  |  | 1.034x ↑<br>[📄](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.md)[📈](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.svg)[🧠](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base-mem.svg) |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0) | python/cc48bf0fde8025d60a57 | cc48bf0 |  |  |  |  |
| [2025-12-22](results/bm-20251222-3.15.0a3%2B-9e51301-JIT) | python/9e513012341607458196 | 9e51301 (JIT) |  |  |  | 1.038x ↑<br>[📄](results/bm-20251222-3.15.0a3%2B-9e51301-JIT/bm-20251222-ripley-x86_64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.md)[📈](results/bm-20251222-3.15.0a3%2B-9e51301-JIT/bm-20251222-ripley-x86_64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base.svg)[🧠](results/bm-20251222-3.15.0a3%2B-9e51301-JIT/bm-20251222-ripley-x86_64-python-9e513012341607458196-3.15.0a3%2B-9e51301-vs-base-mem.svg) |
| [2025-12-22](results/bm-20251222-3.15.0a3%2B-9e51301) | python/9e513012341607458196 | 9e51301 |  |  |  |  |
| [2025-12-21](results/bm-20251221-3.15.0a3%2B-09044dd-JIT) | python/09044dd42b50e628b197 | 09044dd (JIT) |  |  |  | 1.031x ↑<br>[📄](results/bm-20251221-3.15.0a3%2B-09044dd-JIT/bm-20251221-ripley-x86_64-python-09044dd42b50e628b197-3.15.0a3%2B-09044dd-vs-base.md)[📈](results/bm-20251221-3.15.0a3%2B-09044dd-JIT/bm-20251221-ripley-x86_64-python-09044dd42b50e628b197-3.15.0a3%2B-09044dd-vs-base.svg)[🧠](results/bm-20251221-3.15.0a3%2B-09044dd-JIT/bm-20251221-ripley-x86_64-python-09044dd42b50e628b197-3.15.0a3%2B-09044dd-vs-base-mem.svg) |
| [2025-12-21](results/bm-20251221-3.15.0a3%2B-09044dd) | python/09044dd42b50e628b197 | 09044dd |  |  |  |  |
| [2025-12-20](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT) | python/8d2d7bb2e754f8649a68 | 8d2d7bb (JIT) |  |  |  | 1.035x ↑<br>[📄](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT/bm-20251220-ripley-x86_64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.md)[📈](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT/bm-20251220-ripley-x86_64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base.svg)[🧠](results/bm-20251220-3.15.0a3%2B-8d2d7bb-JIT/bm-20251220-ripley-x86_64-python-8d2d7bb2e754f8649a68-3.15.0a3%2B-8d2d7bb-vs-base-mem.svg) |
| [2025-12-20](results/bm-20251220-3.15.0a3%2B-8d2d7bb) | python/8d2d7bb2e754f8649a68 | 8d2d7bb |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0-TAILCALL) | python/cc48bf0fde8025d60a57 | cc48bf0 (TAILCALL) |  |  |  |  |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT%2CTAILCALL) | python/cc48bf0fde8025d60a57 | cc48bf0 (JIT) (TAILCALL) |  |  |  |  |
| [2025-12-22](results/bm-20251222-3.15.0a3%2B-9e51301-TAILCALL) | python/9e513012341607458196 | 9e51301 (TAILCALL) |  |  |  |  |
| [2025-12-22](results/bm-20251222-3.15.0a3%2B-9e51301-JIT%2CTAILCALL) | python/9e513012341607458196 | 9e51301 (JIT) (TAILCALL) |  |  |  |  |
| [2025-12-21](results/bm-20251221-3.15.0a3%2B-09044dd-TAILCALL) | python/09044dd42b50e628b197 | 09044dd (TAILCALL) |  |  |  |  |
| [2025-12-21](results/bm-20251221-3.15.0a3%2B-09044dd-JIT%2CTAILCALL) | python/09044dd42b50e628b197 | 09044dd (JIT) (TAILCALL) |  |  |  |  |


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
