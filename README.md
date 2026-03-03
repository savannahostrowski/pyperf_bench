# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (6908372)](results/bm-20260303-3.15.0a6%2B-6908372/bm-20260303-ripley-x86_64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (6908372)](results/bm-20260303-3.15.0a6%2B-6908372-PYTHON_UOPS/bm-20260303-ripley-x86_64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-03](results/bm-20260303-3.15.0a6%2B-6908372-JIT) | python/6908372fb8182be5849a | 6908372 (JIT) |  |  |  | 1.002x ↑<br>[📄](results/bm-20260303-3.15.0a6%2B-6908372-JIT/bm-20260303-blueberry-aarch64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.md)[📈](results/bm-20260303-3.15.0a6%2B-6908372-JIT/bm-20260303-blueberry-aarch64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.svg)[🧠](results/bm-20260303-3.15.0a6%2B-6908372-JIT/bm-20260303-blueberry-aarch64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base-mem.svg) |
| [2026-03-03](results/bm-20260303-3.15.0a6%2B-6908372) | python/6908372fb8182be5849a | 6908372 |  |  |  |  |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT) | python/c9a5d9aae48a9faa553a | c9a5d9a (JIT) |  |  |  | 1.018x ↑<br>[📄](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-blueberry-aarch64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.md)[📈](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-blueberry-aarch64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.svg)[🧠](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-blueberry-aarch64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base-mem.svg) |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a) | python/c9a5d9aae48a9faa553a | c9a5d9a |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT) | python/a1ec7467874207957519 | a1ec746 (JIT) |  |  |  | 1.008x ↑<br>[📄](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-blueberry-aarch64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.md)[📈](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-blueberry-aarch64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.svg)[🧠](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-blueberry-aarch64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base-mem.svg) |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746) | python/a1ec7467874207957519 | a1ec746 |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT) | python/09e8c382312b145b710d | 09e8c38 (JIT) |  |  |  | 1.013x ↑<br>[📄](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-blueberry-aarch64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.md)[📈](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-blueberry-aarch64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.svg)[🧠](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-blueberry-aarch64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base-mem.svg) |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38) | python/09e8c382312b145b710d | 09e8c38 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-03](results/bm-20260303-3.15.0a6%2B-6908372-JIT) | python/6908372fb8182be5849a | 6908372 (JIT) |  |  |  |  |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT) | python/c9a5d9aae48a9faa553a | c9a5d9a (JIT) |  |  |  | 1.044x ↑<br>[📄](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-ripley-x86_64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.md)[📈](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-ripley-x86_64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.svg)[🧠](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-ripley-x86_64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base-mem.svg) |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a) | python/c9a5d9aae48a9faa553a | c9a5d9a |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT) | python/a1ec7467874207957519 | a1ec746 (JIT) |  |  |  | 1.044x ↑<br>[📄](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-ripley-x86_64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.md)[📈](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-ripley-x86_64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.svg)[🧠](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-ripley-x86_64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base-mem.svg) |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746) | python/a1ec7467874207957519 | a1ec746 |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT) | python/09e8c382312b145b710d | 09e8c38 (JIT) |  |  |  | 1.050x ↑<br>[📄](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-ripley-x86_64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.md)[📈](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-ripley-x86_64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.svg)[🧠](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-ripley-x86_64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base-mem.svg) |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38) | python/09e8c382312b145b710d | 09e8c38 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-03](results/bm-20260303-3.15.0a6%2B-6908372-JIT) | python/6908372fb8182be5849a | 6908372 (JIT) |  |  |  | 1.161x ↑<br>[📄](results/bm-20260303-3.15.0a6%2B-6908372-JIT/bm-20260303-prometheus-amd64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.md)[📈](results/bm-20260303-3.15.0a6%2B-6908372-JIT/bm-20260303-prometheus-amd64-python-6908372fb8182be5849a-3.15.0a6%2B-6908372-vs-base.svg) |
| [2026-03-03](results/bm-20260303-3.15.0a6%2B-6908372) | python/6908372fb8182be5849a | 6908372 |  |  |  |  |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT) | python/c9a5d9aae48a9faa553a | c9a5d9a (JIT) |  |  |  | 1.180x ↑<br>[📄](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-prometheus-amd64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.md)[📈](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT/bm-20260301-prometheus-amd64-python-c9a5d9aae48a9faa553a-3.15.0a6%2B-c9a5d9a-vs-base.svg) |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a) | python/c9a5d9aae48a9faa553a | c9a5d9a |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT) | python/a1ec7467874207957519 | a1ec746 (JIT) |  |  |  | 1.191x ↑<br>[📄](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-prometheus-amd64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.md)[📈](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT/bm-20260228-prometheus-amd64-python-a1ec7467874207957519-3.15.0a6%2B-a1ec746-vs-base.svg) |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746) | python/a1ec7467874207957519 | a1ec746 |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT) | python/09e8c382312b145b710d | 09e8c38 (JIT) |  |  |  | 1.181x ↑<br>[📄](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-prometheus-amd64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.md)[📈](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT/bm-20260228-prometheus-amd64-python-09e8c382312b145b710d-3.15.0a6%2B-09e8c38-vs-base.svg) |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38) | python/09e8c382312b145b710d | 09e8c38 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-03-03](results/bm-20260303-3.15.0a6%2B-6908372-TAILCALL) | python/6908372fb8182be5849a | 6908372 (TAILCALL) |  |  |  |  |
| [2026-03-03](results/bm-20260303-3.15.0a6%2B-6908372-JIT%2CTAILCALL) | python/6908372fb8182be5849a | 6908372 (JIT) (TAILCALL) |  |  |  |  |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a-TAILCALL) | python/c9a5d9aae48a9faa553a | c9a5d9a (TAILCALL) |  |  |  |  |
| [2026-03-01](results/bm-20260301-3.15.0a6%2B-c9a5d9a-JIT%2CTAILCALL) | python/c9a5d9aae48a9faa553a | c9a5d9a (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746-TAILCALL) | python/a1ec7467874207957519 | a1ec746 (TAILCALL) |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-a1ec746-JIT%2CTAILCALL) | python/a1ec7467874207957519 | a1ec746 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38-TAILCALL) | python/09e8c382312b145b710d | 09e8c38 (TAILCALL) |  |  |  |  |
| [2026-02-28](results/bm-20260228-3.15.0a6%2B-09e8c38-JIT%2CTAILCALL) | python/09e8c382312b145b710d | 09e8c38 (JIT) (TAILCALL) |  |  |  |  |


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
