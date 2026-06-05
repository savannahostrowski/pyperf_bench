# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (e28a2f4)](results/bm-20260604-3.16.0a0-e28a2f4/bm-20260604-ripley-x86_64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (e28a2f4)](results/bm-20260604-3.16.0a0-e28a2f4-PYTHON_UOPS/bm-20260604-ripley-x86_64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4-JIT) | python/e28a2f493044ecfc0f76 | e28a2f4 (JIT) |  |  |  | 1.010x ↓<br>[📄](results/bm-20260604-3.16.0a0-e28a2f4-JIT/bm-20260604-blueberry-aarch64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-vs-base.md)[📈](results/bm-20260604-3.16.0a0-e28a2f4-JIT/bm-20260604-blueberry-aarch64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-vs-base.svg)[🧠](results/bm-20260604-3.16.0a0-e28a2f4-JIT/bm-20260604-blueberry-aarch64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-vs-base-mem.svg) |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4) | python/e28a2f493044ecfc0f76 | e28a2f4 |  |  |  |  |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1-JIT) | python/7a468a101268d2b13105 | 7a468a1 (JIT) |  |  |  | 1.213x ↓<br>[📄](results/bm-20260603-3.16.0a0-7a468a1-JIT/bm-20260603-blueberry-aarch64-python-7a468a101268d2b13105-3.16.0a0-7a468a1-vs-base.md)[📈](results/bm-20260603-3.16.0a0-7a468a1-JIT/bm-20260603-blueberry-aarch64-python-7a468a101268d2b13105-3.16.0a0-7a468a1-vs-base.svg)[🧠](results/bm-20260603-3.16.0a0-7a468a1-JIT/bm-20260603-blueberry-aarch64-python-7a468a101268d2b13105-3.16.0a0-7a468a1-vs-base-mem.svg) |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1) | python/7a468a101268d2b13105 | 7a468a1 |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0-JIT) | python/29805f00a1b65163230d | 29805f0 (JIT) |  |  |  | 1.206x ↓<br>[📄](results/bm-20260602-3.16.0a0-29805f0-JIT/bm-20260602-blueberry-aarch64-python-29805f00a1b65163230d-3.16.0a0-29805f0-vs-base.md)[📈](results/bm-20260602-3.16.0a0-29805f0-JIT/bm-20260602-blueberry-aarch64-python-29805f00a1b65163230d-3.16.0a0-29805f0-vs-base.svg)[🧠](results/bm-20260602-3.16.0a0-29805f0-JIT/bm-20260602-blueberry-aarch64-python-29805f00a1b65163230d-3.16.0a0-29805f0-vs-base-mem.svg) |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0) | python/29805f00a1b65163230d | 29805f0 |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6-JIT) | python/71fc4c66d3e675a5481b | 71fc4c6 (JIT) |  |  |  | 1.207x ↓<br>[📄](results/bm-20260602-3.16.0a0-71fc4c6-JIT/bm-20260602-blueberry-aarch64-python-71fc4c66d3e675a5481b-3.16.0a0-71fc4c6-vs-base.md)[📈](results/bm-20260602-3.16.0a0-71fc4c6-JIT/bm-20260602-blueberry-aarch64-python-71fc4c66d3e675a5481b-3.16.0a0-71fc4c6-vs-base.svg)[🧠](results/bm-20260602-3.16.0a0-71fc4c6-JIT/bm-20260602-blueberry-aarch64-python-71fc4c66d3e675a5481b-3.16.0a0-71fc4c6-vs-base-mem.svg) |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6) | python/71fc4c66d3e675a5481b | 71fc4c6 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4-JIT) | python/e28a2f493044ecfc0f76 | e28a2f4 (JIT) |  |  |  | 1.068x ↑<br>[📄](results/bm-20260604-3.16.0a0-e28a2f4-JIT/bm-20260604-ripley-x86_64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-vs-base.md)[📈](results/bm-20260604-3.16.0a0-e28a2f4-JIT/bm-20260604-ripley-x86_64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-vs-base.svg)[🧠](results/bm-20260604-3.16.0a0-e28a2f4-JIT/bm-20260604-ripley-x86_64-python-e28a2f493044ecfc0f76-3.16.0a0-e28a2f4-vs-base-mem.svg) |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4) | python/e28a2f493044ecfc0f76 | e28a2f4 |  |  |  |  |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1-JIT) | python/7a468a101268d2b13105 | 7a468a1 (JIT) |  |  |  | 1.091x ↓<br>[📄](results/bm-20260603-3.16.0a0-7a468a1-JIT/bm-20260603-ripley-x86_64-python-7a468a101268d2b13105-3.16.0a0-7a468a1-vs-base.md)[📈](results/bm-20260603-3.16.0a0-7a468a1-JIT/bm-20260603-ripley-x86_64-python-7a468a101268d2b13105-3.16.0a0-7a468a1-vs-base.svg)[🧠](results/bm-20260603-3.16.0a0-7a468a1-JIT/bm-20260603-ripley-x86_64-python-7a468a101268d2b13105-3.16.0a0-7a468a1-vs-base-mem.svg) |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1) | python/7a468a101268d2b13105 | 7a468a1 |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0-JIT) | python/29805f00a1b65163230d | 29805f0 (JIT) |  |  |  | 1.096x ↓<br>[📄](results/bm-20260602-3.16.0a0-29805f0-JIT/bm-20260602-ripley-x86_64-python-29805f00a1b65163230d-3.16.0a0-29805f0-vs-base.md)[📈](results/bm-20260602-3.16.0a0-29805f0-JIT/bm-20260602-ripley-x86_64-python-29805f00a1b65163230d-3.16.0a0-29805f0-vs-base.svg)[🧠](results/bm-20260602-3.16.0a0-29805f0-JIT/bm-20260602-ripley-x86_64-python-29805f00a1b65163230d-3.16.0a0-29805f0-vs-base-mem.svg) |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0) | python/29805f00a1b65163230d | 29805f0 |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6-JIT) | python/71fc4c66d3e675a5481b | 71fc4c6 (JIT) |  |  |  | 1.088x ↓<br>[📄](results/bm-20260602-3.16.0a0-71fc4c6-JIT/bm-20260602-ripley-x86_64-python-71fc4c66d3e675a5481b-3.16.0a0-71fc4c6-vs-base.md)[📈](results/bm-20260602-3.16.0a0-71fc4c6-JIT/bm-20260602-ripley-x86_64-python-71fc4c66d3e675a5481b-3.16.0a0-71fc4c6-vs-base.svg)[🧠](results/bm-20260602-3.16.0a0-71fc4c6-JIT/bm-20260602-ripley-x86_64-python-71fc4c66d3e675a5481b-3.16.0a0-71fc4c6-vs-base-mem.svg) |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6) | python/71fc4c66d3e675a5481b | 71fc4c6 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4-TAILCALL) | python/e28a2f493044ecfc0f76 | e28a2f4 (TAILCALL) |  |  |  |  |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4-JIT%2CTAILCALL) | python/e28a2f493044ecfc0f76 | e28a2f4 (JIT) (TAILCALL) |  |  |  |  |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1-TAILCALL) | python/7a468a101268d2b13105 | 7a468a1 (TAILCALL) |  |  |  |  |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1-JIT%2CTAILCALL) | python/7a468a101268d2b13105 | 7a468a1 (JIT) (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0-TAILCALL) | python/29805f00a1b65163230d | 29805f0 (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0-JIT%2CTAILCALL) | python/29805f00a1b65163230d | 29805f0 (JIT) (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6-TAILCALL) | python/71fc4c66d3e675a5481b | 71fc4c6 (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6-JIT%2CTAILCALL) | python/71fc4c66d3e675a5481b | 71fc4c6 (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4-TAILCALL) | python/e28a2f493044ecfc0f76 | e28a2f4 (TAILCALL) |  |  |  |  |
| [2026-06-04](results/bm-20260604-3.16.0a0-e28a2f4-JIT%2CTAILCALL) | python/e28a2f493044ecfc0f76 | e28a2f4 (JIT) (TAILCALL) |  |  |  |  |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1-TAILCALL) | python/7a468a101268d2b13105 | 7a468a1 (TAILCALL) |  |  |  |  |
| [2026-06-03](results/bm-20260603-3.16.0a0-7a468a1-JIT%2CTAILCALL) | python/7a468a101268d2b13105 | 7a468a1 (JIT) (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0-TAILCALL) | python/29805f00a1b65163230d | 29805f0 (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-29805f0-JIT%2CTAILCALL) | python/29805f00a1b65163230d | 29805f0 (JIT) (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6-TAILCALL) | python/71fc4c66d3e675a5481b | 71fc4c6 (TAILCALL) |  |  |  |  |
| [2026-06-02](results/bm-20260602-3.16.0a0-71fc4c6-JIT%2CTAILCALL) | python/71fc4c66d3e675a5481b | 71fc4c6 (JIT) (TAILCALL) |  |  |  |  |


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
