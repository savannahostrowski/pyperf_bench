# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (8851a06)](results/bm-20260429-3.15.0a8%2B-8851a06/bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (8851a06)](results/bm-20260429-3.15.0a8%2B-8851a06-PYTHON_UOPS/bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06-JIT) | python/8851a06e6e7ff23d91e5 | 8851a06 (JIT) |  |  |  | 1.004x ↑<br>[📄](results/bm-20260429-3.15.0a8%2B-8851a06-JIT/bm-20260429-blueberry-aarch64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.md)[📈](results/bm-20260429-3.15.0a8%2B-8851a06-JIT/bm-20260429-blueberry-aarch64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.svg)[🧠](results/bm-20260429-3.15.0a8%2B-8851a06-JIT/bm-20260429-blueberry-aarch64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base-mem.svg) |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06) | python/8851a06e6e7ff23d91e5 | 8851a06 |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT) | python/40dc61a0e0672810c393 | 40dc61a (JIT) |  |  |  | 1.008x ↑<br>[📄](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT/bm-20260428-blueberry-aarch64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.md)[📈](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT/bm-20260428-blueberry-aarch64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.svg)[🧠](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT/bm-20260428-blueberry-aarch64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base-mem.svg) |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-40dc61a) | python/40dc61a0e0672810c393 | 40dc61a |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679-JIT) | python/0efd679a6ce3b57ec3c5 | 0efd679 (JIT) |  |  |  | 1.014x ↑<br>[📄](results/bm-20260428-3.15.0a8%2B-0efd679-JIT/bm-20260428-blueberry-aarch64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.md)[📈](results/bm-20260428-3.15.0a8%2B-0efd679-JIT/bm-20260428-blueberry-aarch64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.svg)[🧠](results/bm-20260428-3.15.0a8%2B-0efd679-JIT/bm-20260428-blueberry-aarch64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base-mem.svg) |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679) | python/0efd679a6ce3b57ec3c5 | 0efd679 |  |  |  |  |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT) | python/1e7dfbce930d6abd4e54 | 1e7dfbc (JIT) |  |  |  | 1.029x ↑<br>[📄](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT/bm-20260426-blueberry-aarch64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.md)[📈](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT/bm-20260426-blueberry-aarch64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.svg)[🧠](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT/bm-20260426-blueberry-aarch64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base-mem.svg) |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc) | python/1e7dfbce930d6abd4e54 | 1e7dfbc |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06-JIT) | python/8851a06e6e7ff23d91e5 | 8851a06 (JIT) |  |  |  | 1.091x ↑<br>[📄](results/bm-20260429-3.15.0a8%2B-8851a06-JIT/bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.md)[📈](results/bm-20260429-3.15.0a8%2B-8851a06-JIT/bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base.svg)[🧠](results/bm-20260429-3.15.0a8%2B-8851a06-JIT/bm-20260429-ripley-x86_64-python-8851a06e6e7ff23d91e5-3.15.0a8%2B-8851a06-vs-base-mem.svg) |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06) | python/8851a06e6e7ff23d91e5 | 8851a06 |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT) | python/40dc61a0e0672810c393 | 40dc61a (JIT) |  |  |  | 1.081x ↑<br>[📄](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT/bm-20260428-ripley-x86_64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.md)[📈](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT/bm-20260428-ripley-x86_64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base.svg)[🧠](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT/bm-20260428-ripley-x86_64-python-40dc61a0e0672810c393-3.15.0a8%2B-40dc61a-vs-base-mem.svg) |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-40dc61a) | python/40dc61a0e0672810c393 | 40dc61a |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679-JIT) | python/0efd679a6ce3b57ec3c5 | 0efd679 (JIT) |  |  |  | 1.086x ↑<br>[📄](results/bm-20260428-3.15.0a8%2B-0efd679-JIT/bm-20260428-ripley-x86_64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.md)[📈](results/bm-20260428-3.15.0a8%2B-0efd679-JIT/bm-20260428-ripley-x86_64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base.svg)[🧠](results/bm-20260428-3.15.0a8%2B-0efd679-JIT/bm-20260428-ripley-x86_64-python-0efd679a6ce3b57ec3c5-3.15.0a8%2B-0efd679-vs-base-mem.svg) |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679) | python/0efd679a6ce3b57ec3c5 | 0efd679 |  |  |  |  |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT) | python/1e7dfbce930d6abd4e54 | 1e7dfbc (JIT) |  |  |  | 1.082x ↑<br>[📄](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT/bm-20260426-ripley-x86_64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.md)[📈](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT/bm-20260426-ripley-x86_64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base.svg)[🧠](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT/bm-20260426-ripley-x86_64-python-1e7dfbce930d6abd4e54-3.15.0a8%2B-1e7dfbc-vs-base-mem.svg) |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc) | python/1e7dfbce930d6abd4e54 | 1e7dfbc |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06-TAILCALL) | python/8851a06e6e7ff23d91e5 | 8851a06 (TAILCALL) |  |  |  |  |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06-JIT%2CTAILCALL) | python/8851a06e6e7ff23d91e5 | 8851a06 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-40dc61a-TAILCALL) | python/40dc61a0e0672810c393 | 40dc61a (TAILCALL) |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679-TAILCALL) | python/0efd679a6ce3b57ec3c5 | 0efd679 (TAILCALL) |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679-JIT%2CTAILCALL) | python/0efd679a6ce3b57ec3c5 | 0efd679 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc-TAILCALL) | python/1e7dfbce930d6abd4e54 | 1e7dfbc (TAILCALL) |  |  |  |  |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT%2CTAILCALL) | python/1e7dfbce930d6abd4e54 | 1e7dfbc (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06-TAILCALL) | python/8851a06e6e7ff23d91e5 | 8851a06 (TAILCALL) |  |  |  |  |
| [2026-04-29](results/bm-20260429-3.15.0a8%2B-8851a06-JIT%2CTAILCALL) | python/8851a06e6e7ff23d91e5 | 8851a06 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-40dc61a-TAILCALL) | python/40dc61a0e0672810c393 | 40dc61a (TAILCALL) |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-40dc61a-JIT%2CTAILCALL) | python/40dc61a0e0672810c393 | 40dc61a (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679-TAILCALL) | python/0efd679a6ce3b57ec3c5 | 0efd679 (TAILCALL) |  |  |  |  |
| [2026-04-28](results/bm-20260428-3.15.0a8%2B-0efd679-JIT%2CTAILCALL) | python/0efd679a6ce3b57ec3c5 | 0efd679 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc-TAILCALL) | python/1e7dfbce930d6abd4e54 | 1e7dfbc (TAILCALL) |  |  |  |  |
| [2026-04-26](results/bm-20260426-3.15.0a8%2B-1e7dfbc-JIT%2CTAILCALL) | python/1e7dfbce930d6abd4e54 | 1e7dfbc (JIT) (TAILCALL) |  |  |  |  |


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
