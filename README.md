# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (d206d42)](results/bm-20260421-3.15.0a8%2B-d206d42/bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (d206d42)](results/bm-20260421-3.15.0a8%2B-d206d42-PYTHON_UOPS/bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42-JIT) | python/d206d42834b2a34aee11 | d206d42 (JIT) |  |  |  | 1.001x ↓<br>[📄](results/bm-20260421-3.15.0a8%2B-d206d42-JIT/bm-20260421-blueberry-aarch64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.md)[📈](results/bm-20260421-3.15.0a8%2B-d206d42-JIT/bm-20260421-blueberry-aarch64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.svg)[🧠](results/bm-20260421-3.15.0a8%2B-d206d42-JIT/bm-20260421-blueberry-aarch64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base-mem.svg) |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42) | python/d206d42834b2a34aee11 | d206d42 |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-3fd61b7-JIT) | python/main | 3fd61b7 (JIT) |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778-JIT) | python/82767780f8de2fc49256 | 8276778 (JIT) |  |  |  | 1.000x ↑<br>[📄](results/bm-20260420-3.15.0a8%2B-8276778-JIT/bm-20260420-blueberry-aarch64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.md)[📈](results/bm-20260420-3.15.0a8%2B-8276778-JIT/bm-20260420-blueberry-aarch64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.svg)[🧠](results/bm-20260420-3.15.0a8%2B-8276778-JIT/bm-20260420-blueberry-aarch64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base-mem.svg) |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778) | python/82767780f8de2fc49256 | 8276778 |  |  |  |  |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308-JIT) | python/4b3330813760a3e3c75c | 4b33308 (JIT) |  |  |  | 1.005x ↑<br>[📄](results/bm-20260418-3.15.0a8%2B-4b33308-JIT/bm-20260418-blueberry-aarch64-python-4b3330813760a3e3c75c-3.15.0a8%2B-4b33308-vs-base.md)[📈](results/bm-20260418-3.15.0a8%2B-4b33308-JIT/bm-20260418-blueberry-aarch64-python-4b3330813760a3e3c75c-3.15.0a8%2B-4b33308-vs-base.svg)[🧠](results/bm-20260418-3.15.0a8%2B-4b33308-JIT/bm-20260418-blueberry-aarch64-python-4b3330813760a3e3c75c-3.15.0a8%2B-4b33308-vs-base-mem.svg) |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308) | python/4b3330813760a3e3c75c | 4b33308 |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT) | python/db3e990b98fd12fee1bf | db3e990 (JIT) |  |  |  | 1.010x ↑<br>[📄](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.md)[📈](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.svg)[🧠](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base-mem.svg) |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990) | python/db3e990b98fd12fee1bf | db3e990 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42-JIT) | python/d206d42834b2a34aee11 | d206d42 (JIT) |  |  |  | 1.082x ↑<br>[📄](results/bm-20260421-3.15.0a8%2B-d206d42-JIT/bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.md)[📈](results/bm-20260421-3.15.0a8%2B-d206d42-JIT/bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base.svg)[🧠](results/bm-20260421-3.15.0a8%2B-d206d42-JIT/bm-20260421-ripley-x86_64-python-d206d42834b2a34aee11-3.15.0a8%2B-d206d42-vs-base-mem.svg) |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42) | python/d206d42834b2a34aee11 | d206d42 |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-983c746-JIT) | python/main | 983c746 (JIT) |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778-JIT) | python/82767780f8de2fc49256 | 8276778 (JIT) |  |  |  | 1.083x ↑<br>[📄](results/bm-20260420-3.15.0a8%2B-8276778-JIT/bm-20260420-ripley-x86_64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.md)[📈](results/bm-20260420-3.15.0a8%2B-8276778-JIT/bm-20260420-ripley-x86_64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base.svg)[🧠](results/bm-20260420-3.15.0a8%2B-8276778-JIT/bm-20260420-ripley-x86_64-python-82767780f8de2fc49256-3.15.0a8%2B-8276778-vs-base-mem.svg) |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778) | python/82767780f8de2fc49256 | 8276778 |  |  |  |  |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308-JIT) | python/4b3330813760a3e3c75c | 4b33308 (JIT) |  |  |  | 1.088x ↑<br>[📄](results/bm-20260418-3.15.0a8%2B-4b33308-JIT/bm-20260418-ripley-x86_64-python-4b3330813760a3e3c75c-3.15.0a8%2B-4b33308-vs-base.md)[📈](results/bm-20260418-3.15.0a8%2B-4b33308-JIT/bm-20260418-ripley-x86_64-python-4b3330813760a3e3c75c-3.15.0a8%2B-4b33308-vs-base.svg)[🧠](results/bm-20260418-3.15.0a8%2B-4b33308-JIT/bm-20260418-ripley-x86_64-python-4b3330813760a3e3c75c-3.15.0a8%2B-4b33308-vs-base-mem.svg) |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308) | python/4b3330813760a3e3c75c | 4b33308 |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT) | python/db3e990b98fd12fee1bf | db3e990 (JIT) |  |  |  | 1.080x ↑<br>[📄](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.md)[📈](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.svg)[🧠](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base-mem.svg) |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990) | python/db3e990b98fd12fee1bf | db3e990 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42-TAILCALL) | python/d206d42834b2a34aee11 | d206d42 (TAILCALL) |  |  |  |  |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42-JIT%2CTAILCALL) | python/d206d42834b2a34aee11 | d206d42 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778-TAILCALL) | python/82767780f8de2fc49256 | 8276778 (TAILCALL) |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778-JIT%2CTAILCALL) | python/82767780f8de2fc49256 | 8276778 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308-TAILCALL) | python/4b3330813760a3e3c75c | 4b33308 (TAILCALL) |  |  |  |  |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308-JIT%2CTAILCALL) | python/4b3330813760a3e3c75c | 4b33308 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-TAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (TAILCALL) |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT%2CTAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42-TAILCALL) | python/d206d42834b2a34aee11 | d206d42 (TAILCALL) |  |  |  |  |
| [2026-04-21](results/bm-20260421-3.15.0a8%2B-d206d42-JIT%2CTAILCALL) | python/d206d42834b2a34aee11 | d206d42 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778-TAILCALL) | python/82767780f8de2fc49256 | 8276778 (TAILCALL) |  |  |  |  |
| [2026-04-20](results/bm-20260420-3.15.0a8%2B-8276778-JIT%2CTAILCALL) | python/82767780f8de2fc49256 | 8276778 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308-TAILCALL) | python/4b3330813760a3e3c75c | 4b33308 (TAILCALL) |  |  |  |  |
| [2026-04-18](results/bm-20260418-3.15.0a8%2B-4b33308-JIT%2CTAILCALL) | python/4b3330813760a3e3c75c | 4b33308 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-TAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (TAILCALL) |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT%2CTAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (JIT) (TAILCALL) |  |  |  |  |


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
