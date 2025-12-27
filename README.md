# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (a1c6308)](results/bm-20251226-3.15.0a3%2B-a1c6308/bm-20251226-ripley-x86_64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (a1c6308)](results/bm-20251226-3.15.0a3%2B-a1c6308-PYTHON_UOPS/bm-20251226-ripley-x86_64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-26](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT) | python/a1c630834649d54ffbca | a1c6308 (JIT) |  |  |  | 1.003x ↑<br>[📄](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT/bm-20251226-blueberry-aarch64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-vs-base.md)[📈](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT/bm-20251226-blueberry-aarch64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-vs-base.svg)[🧠](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT/bm-20251226-blueberry-aarch64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-vs-base-mem.svg) |
| [2025-12-26](results/bm-20251226-3.15.0a3%2B-a1c6308) | python/a1c630834649d54ffbca | a1c6308 |  |  |  |  |
| [2025-12-25](results/bm-20251225-3.15.0a3%2B-888d101-JIT) | python/888d101445c72c7cf239 | 888d101 (JIT) |  |  |  | 1.038x ↑<br>[📄](results/bm-20251225-3.15.0a3%2B-888d101-JIT/bm-20251225-blueberry-aarch64-python-888d101445c72c7cf239-3.15.0a3%2B-888d101-vs-base.md)[📈](results/bm-20251225-3.15.0a3%2B-888d101-JIT/bm-20251225-blueberry-aarch64-python-888d101445c72c7cf239-3.15.0a3%2B-888d101-vs-base.svg)[🧠](results/bm-20251225-3.15.0a3%2B-888d101-JIT/bm-20251225-blueberry-aarch64-python-888d101445c72c7cf239-3.15.0a3%2B-888d101-vs-base-mem.svg) |
| [2025-12-25](results/bm-20251225-3.15.0a3%2B-888d101) | python/888d101445c72c7cf239 | 888d101 |  |  |  |  |
| [2025-12-24](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT) | python/cf6758ff9ebd6df8ac2a | cf6758f (JIT) |  |  |  | 1.015x ↑<br>[📄](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT/bm-20251224-blueberry-aarch64-python-cf6758ff9ebd6df8ac2a-3.15.0a3%2B-cf6758f-vs-base.md)[📈](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT/bm-20251224-blueberry-aarch64-python-cf6758ff9ebd6df8ac2a-3.15.0a3%2B-cf6758f-vs-base.svg)[🧠](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT/bm-20251224-blueberry-aarch64-python-cf6758ff9ebd6df8ac2a-3.15.0a3%2B-cf6758f-vs-base-mem.svg) |
| [2025-12-24](results/bm-20251224-3.15.0a3%2B-cf6758f) | python/cf6758ff9ebd6df8ac2a | cf6758f |  |  |  |  |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT) | python/cc48bf0fde8025d60a57 | cc48bf0 (JIT) |  |  |  | 1.013x ↑<br>[📄](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.md)[📈](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.svg)[🧠](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-blueberry-aarch64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base-mem.svg) |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0) | python/cc48bf0fde8025d60a57 | cc48bf0 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-26](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT) | python/a1c630834649d54ffbca | a1c6308 (JIT) |  |  |  | 1.031x ↑<br>[📄](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT/bm-20251226-ripley-x86_64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-vs-base.md)[📈](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT/bm-20251226-ripley-x86_64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-vs-base.svg)[🧠](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT/bm-20251226-ripley-x86_64-python-a1c630834649d54ffbca-3.15.0a3%2B-a1c6308-vs-base-mem.svg) |
| [2025-12-26](results/bm-20251226-3.15.0a3%2B-a1c6308) | python/a1c630834649d54ffbca | a1c6308 |  |  |  |  |
| [2025-12-25](results/bm-20251225-3.15.0a3%2B-888d101-JIT) | python/888d101445c72c7cf239 | 888d101 (JIT) |  |  |  | 1.031x ↑<br>[📄](results/bm-20251225-3.15.0a3%2B-888d101-JIT/bm-20251225-ripley-x86_64-python-888d101445c72c7cf239-3.15.0a3%2B-888d101-vs-base.md)[📈](results/bm-20251225-3.15.0a3%2B-888d101-JIT/bm-20251225-ripley-x86_64-python-888d101445c72c7cf239-3.15.0a3%2B-888d101-vs-base.svg)[🧠](results/bm-20251225-3.15.0a3%2B-888d101-JIT/bm-20251225-ripley-x86_64-python-888d101445c72c7cf239-3.15.0a3%2B-888d101-vs-base-mem.svg) |
| [2025-12-25](results/bm-20251225-3.15.0a3%2B-888d101) | python/888d101445c72c7cf239 | 888d101 |  |  |  |  |
| [2025-12-24](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT) | python/cf6758ff9ebd6df8ac2a | cf6758f (JIT) |  |  |  | 1.034x ↑<br>[📄](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3%2B-cf6758f-vs-base.md)[📈](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3%2B-cf6758f-vs-base.svg)[🧠](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT/bm-20251224-ripley-x86_64-python-cf6758ff9ebd6df8ac2a-3.15.0a3%2B-cf6758f-vs-base-mem.svg) |
| [2025-12-24](results/bm-20251224-3.15.0a3%2B-cf6758f) | python/cf6758ff9ebd6df8ac2a | cf6758f |  |  |  |  |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT) | python/cc48bf0fde8025d60a57 | cc48bf0 (JIT) |  |  |  | 1.034x ↑<br>[📄](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.md)[📈](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base.svg)[🧠](results/bm-20251223-3.15.0a3%2B-cc48bf0-JIT/bm-20251223-ripley-x86_64-python-cc48bf0fde8025d60a57-3.15.0a3%2B-cc48bf0-vs-base-mem.svg) |
| [2025-12-23](results/bm-20251223-3.15.0a3%2B-cc48bf0) | python/cc48bf0fde8025d60a57 | cc48bf0 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-26](results/bm-20251226-3.15.0a3%2B-a1c6308-TAILCALL) | python/a1c630834649d54ffbca | a1c6308 (TAILCALL) |  |  |  |  |
| [2025-12-26](results/bm-20251226-3.15.0a3%2B-a1c6308-JIT%2CTAILCALL) | python/a1c630834649d54ffbca | a1c6308 (JIT) (TAILCALL) |  |  |  |  |
| [2025-12-25](results/bm-20251225-3.15.0a3%2B-888d101-TAILCALL) | python/888d101445c72c7cf239 | 888d101 (TAILCALL) |  |  |  |  |
| [2025-12-25](results/bm-20251225-3.15.0a3%2B-888d101-JIT%2CTAILCALL) | python/888d101445c72c7cf239 | 888d101 (JIT) (TAILCALL) |  |  |  |  |
| [2025-12-24](results/bm-20251224-3.15.0a3%2B-cf6758f-TAILCALL) | python/cf6758ff9ebd6df8ac2a | cf6758f (TAILCALL) |  |  |  |  |
| [2025-12-24](results/bm-20251224-3.15.0a3%2B-cf6758f-JIT%2CTAILCALL) | python/cf6758ff9ebd6df8ac2a | cf6758f (JIT) (TAILCALL) |  |  |  |  |


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
