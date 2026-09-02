# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (3daa7f8)](results/bm-20260902-3.16.0a0-3daa7f8/bm-20260902-ripley-x86_64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (3daa7f8)](results/bm-20260902-3.16.0a0-3daa7f8-PYTHON_UOPS/bm-20260902-ripley-x86_64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8-JIT) | python/3daa7f8258fa21931e76 | 3daa7f8 (JIT) |  |  |  | 1.026x ↑<br>[📄](results/bm-20260902-3.16.0a0-3daa7f8-JIT/bm-20260902-blueberry-aarch64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-vs-base.md)[📈](results/bm-20260902-3.16.0a0-3daa7f8-JIT/bm-20260902-blueberry-aarch64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-vs-base.svg)[🧠](results/bm-20260902-3.16.0a0-3daa7f8-JIT/bm-20260902-blueberry-aarch64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-vs-base-mem.svg) |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8) | python/3daa7f8258fa21931e76 | 3daa7f8 |  |  |  |  |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073-JIT) | python/b38e073f1be8fe40af99 | b38e073 (JIT) |  |  |  | 1.005x ↑<br>[📄](results/bm-20260831-3.16.0a0-b38e073-JIT/bm-20260831-blueberry-aarch64-python-b38e073f1be8fe40af99-3.16.0a0-b38e073-vs-base.md)[📈](results/bm-20260831-3.16.0a0-b38e073-JIT/bm-20260831-blueberry-aarch64-python-b38e073f1be8fe40af99-3.16.0a0-b38e073-vs-base.svg)[🧠](results/bm-20260831-3.16.0a0-b38e073-JIT/bm-20260831-blueberry-aarch64-python-b38e073f1be8fe40af99-3.16.0a0-b38e073-vs-base-mem.svg) |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073) | python/b38e073f1be8fe40af99 | b38e073 |  |  |  |  |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc-JIT) | python/03503dccd0aa6d889561 | 03503dc (JIT) |  |  |  | 1.016x ↓<br>[📄](results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.md)[📈](results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.svg)[🧠](results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-blueberry-aarch64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base-mem.svg) |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc) | python/03503dccd0aa6d889561 | 03503dc |  |  |  |  |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a-JIT) | python/41b3f0af266b408438ca | 41b3f0a (JIT) |  |  |  | 1.014x ↓<br>[📄](results/bm-20260829-3.16.0a0-41b3f0a-JIT/bm-20260829-blueberry-aarch64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.md)[📈](results/bm-20260829-3.16.0a0-41b3f0a-JIT/bm-20260829-blueberry-aarch64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.svg)[🧠](results/bm-20260829-3.16.0a0-41b3f0a-JIT/bm-20260829-blueberry-aarch64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base-mem.svg) |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a) | python/41b3f0af266b408438ca | 41b3f0a |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8-JIT) | python/3daa7f8258fa21931e76 | 3daa7f8 (JIT) |  |  |  | 1.079x ↑<br>[📄](results/bm-20260902-3.16.0a0-3daa7f8-JIT/bm-20260902-ripley-x86_64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-vs-base.md)[📈](results/bm-20260902-3.16.0a0-3daa7f8-JIT/bm-20260902-ripley-x86_64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-vs-base.svg)[🧠](results/bm-20260902-3.16.0a0-3daa7f8-JIT/bm-20260902-ripley-x86_64-python-3daa7f8258fa21931e76-3.16.0a0-3daa7f8-vs-base-mem.svg) |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8) | python/3daa7f8258fa21931e76 | 3daa7f8 |  |  |  |  |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073-JIT) | python/b38e073f1be8fe40af99 | b38e073 (JIT) |  |  |  | 1.077x ↑<br>[📄](results/bm-20260831-3.16.0a0-b38e073-JIT/bm-20260831-ripley-x86_64-python-b38e073f1be8fe40af99-3.16.0a0-b38e073-vs-base.md)[📈](results/bm-20260831-3.16.0a0-b38e073-JIT/bm-20260831-ripley-x86_64-python-b38e073f1be8fe40af99-3.16.0a0-b38e073-vs-base.svg)[🧠](results/bm-20260831-3.16.0a0-b38e073-JIT/bm-20260831-ripley-x86_64-python-b38e073f1be8fe40af99-3.16.0a0-b38e073-vs-base-mem.svg) |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073) | python/b38e073f1be8fe40af99 | b38e073 |  |  |  |  |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc-JIT) | python/03503dccd0aa6d889561 | 03503dc (JIT) |  |  |  | 1.079x ↑<br>[📄](results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-ripley-x86_64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.md)[📈](results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-ripley-x86_64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base.svg)[🧠](results/bm-20260830-3.16.0a0-03503dc-JIT/bm-20260830-ripley-x86_64-python-03503dccd0aa6d889561-3.16.0a0-03503dc-vs-base-mem.svg) |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc) | python/03503dccd0aa6d889561 | 03503dc |  |  |  |  |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a-JIT) | python/41b3f0af266b408438ca | 41b3f0a (JIT) |  |  |  | 1.071x ↑<br>[📄](results/bm-20260829-3.16.0a0-41b3f0a-JIT/bm-20260829-ripley-x86_64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.md)[📈](results/bm-20260829-3.16.0a0-41b3f0a-JIT/bm-20260829-ripley-x86_64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base.svg)[🧠](results/bm-20260829-3.16.0a0-41b3f0a-JIT/bm-20260829-ripley-x86_64-python-41b3f0af266b408438ca-3.16.0a0-41b3f0a-vs-base-mem.svg) |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a) | python/41b3f0af266b408438ca | 41b3f0a |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8-TAILCALL) | python/3daa7f8258fa21931e76 | 3daa7f8 (TAILCALL) |  |  |  |  |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8-JIT%2CTAILCALL) | python/3daa7f8258fa21931e76 | 3daa7f8 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073-TAILCALL) | python/b38e073f1be8fe40af99 | b38e073 (TAILCALL) |  |  |  |  |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073-JIT%2CTAILCALL) | python/b38e073f1be8fe40af99 | b38e073 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc-TAILCALL) | python/03503dccd0aa6d889561 | 03503dc (TAILCALL) |  |  |  |  |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc-JIT%2CTAILCALL) | python/03503dccd0aa6d889561 | 03503dc (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a-TAILCALL) | python/41b3f0af266b408438ca | 41b3f0a (TAILCALL) |  |  |  |  |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a-JIT%2CTAILCALL) | python/41b3f0af266b408438ca | 41b3f0a (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8-TAILCALL) | python/3daa7f8258fa21931e76 | 3daa7f8 (TAILCALL) |  |  |  |  |
| [2026-09-02](results/bm-20260902-3.16.0a0-3daa7f8-JIT%2CTAILCALL) | python/3daa7f8258fa21931e76 | 3daa7f8 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073-TAILCALL) | python/b38e073f1be8fe40af99 | b38e073 (TAILCALL) |  |  |  |  |
| [2026-08-31](results/bm-20260831-3.16.0a0-b38e073-JIT%2CTAILCALL) | python/b38e073f1be8fe40af99 | b38e073 (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc-TAILCALL) | python/03503dccd0aa6d889561 | 03503dc (TAILCALL) |  |  |  |  |
| [2026-08-30](results/bm-20260830-3.16.0a0-03503dc-JIT%2CTAILCALL) | python/03503dccd0aa6d889561 | 03503dc (JIT) (TAILCALL) |  |  |  |  |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a-TAILCALL) | python/41b3f0af266b408438ca | 41b3f0a (TAILCALL) |  |  |  |  |
| [2026-08-29](results/bm-20260829-3.16.0a0-41b3f0a-JIT%2CTAILCALL) | python/41b3f0af266b408438ca | 41b3f0a (JIT) (TAILCALL) |  |  |  |  |


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
