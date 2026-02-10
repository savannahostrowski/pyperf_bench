# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (d2d2459)](results/bm-20260210-3.15.0a5%2B-d2d2459/bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (d2d2459)](results/bm-20260210-3.15.0a5%2B-d2d2459-PYTHON_UOPS/bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT) | python/d2d245942eccf108ac3c | d2d2459 (JIT) |  |  |  | 1.011x ↑<br>[📄](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-blueberry-aarch64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.md)[📈](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-blueberry-aarch64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.svg)[🧠](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-blueberry-aarch64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base-mem.svg) |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459) | python/d2d245942eccf108ac3c | d2d2459 |  |  |  |  |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT) | python/432ddd99e2b06a75a4f4 | 432ddd9 (JIT) |  |  |  | 1.006x ↑<br>[📄](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-blueberry-aarch64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.md)[📈](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-blueberry-aarch64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.svg)[🧠](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-blueberry-aarch64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base-mem.svg) |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9) | python/432ddd99e2b06a75a4f4 | 432ddd9 |  |  |  |  |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349-JIT) | python/d73634935cb9ce00a57d | d736349 (JIT) |  |  |  | 1.012x ↑<br>[📄](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-blueberry-aarch64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.md)[📈](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-blueberry-aarch64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.svg)[🧠](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-blueberry-aarch64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base-mem.svg) |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349) | python/d73634935cb9ce00a57d | d736349 |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT) | python/a2495ff1e7b370c26128 | a2495ff (JIT) |  |  |  | 1.012x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.svg)[🧠](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base-mem.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff) | python/a2495ff1e7b370c26128 | a2495ff |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT) | python/d2d245942eccf108ac3c | d2d2459 (JIT) |  |  |  | 1.032x ↑<br>[📄](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.md)[📈](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.svg)[🧠](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-ripley-x86_64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base-mem.svg) |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459) | python/d2d245942eccf108ac3c | d2d2459 |  |  |  |  |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT) | python/432ddd99e2b06a75a4f4 | 432ddd9 (JIT) |  |  |  | 1.042x ↑<br>[📄](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-ripley-x86_64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.md)[📈](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-ripley-x86_64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.svg)[🧠](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-ripley-x86_64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base-mem.svg) |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9) | python/432ddd99e2b06a75a4f4 | 432ddd9 |  |  |  |  |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349-JIT) | python/d73634935cb9ce00a57d | d736349 (JIT) |  |  |  | 1.036x ↑<br>[📄](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-ripley-x86_64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.md)[📈](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-ripley-x86_64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.svg)[🧠](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-ripley-x86_64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base-mem.svg) |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349) | python/d73634935cb9ce00a57d | d736349 |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT) | python/a2495ff1e7b370c26128 | a2495ff (JIT) |  |  |  | 1.038x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.svg)[🧠](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base-mem.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff) | python/a2495ff1e7b370c26128 | a2495ff |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT) | python/d2d245942eccf108ac3c | d2d2459 (JIT) |  |  |  | 1.151x ↑<br>[📄](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-prometheus-amd64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.md)[📈](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT/bm-20260210-prometheus-amd64-python-d2d245942eccf108ac3c-3.15.0a5%2B-d2d2459-vs-base.svg) |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459) | python/d2d245942eccf108ac3c | d2d2459 |  |  |  |  |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT) | python/432ddd99e2b06a75a4f4 | 432ddd9 (JIT) |  |  |  | 1.151x ↑<br>[📄](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-prometheus-amd64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.md)[📈](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT/bm-20260209-prometheus-amd64-python-432ddd99e2b06a75a4f4-3.15.0a5%2B-432ddd9-vs-base.svg) |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9) | python/432ddd99e2b06a75a4f4 | 432ddd9 |  |  |  |  |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349-JIT) | python/d73634935cb9ce00a57d | d736349 (JIT) |  |  |  | 1.143x ↑<br>[📄](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-prometheus-amd64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.md)[📈](results/bm-20260207-3.15.0a5%2B-d736349-JIT/bm-20260207-prometheus-amd64-python-d73634935cb9ce00a57d-3.15.0a5%2B-d736349-vs-base.svg) |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349) | python/d73634935cb9ce00a57d | d736349 |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT) | python/a2495ff1e7b370c26128 | a2495ff (JIT) |  |  |  | 1.173x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-prometheus-amd64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-prometheus-amd64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff) | python/a2495ff1e7b370c26128 | a2495ff |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459-TAILCALL) | python/d2d245942eccf108ac3c | d2d2459 (TAILCALL) |  |  |  |  |
| [2026-02-10](results/bm-20260210-3.15.0a5%2B-d2d2459-JIT%2CTAILCALL) | python/d2d245942eccf108ac3c | d2d2459 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9-TAILCALL) | python/432ddd99e2b06a75a4f4 | 432ddd9 (TAILCALL) |  |  |  |  |
| [2026-02-09](results/bm-20260209-3.15.0a5%2B-432ddd9-JIT%2CTAILCALL) | python/432ddd99e2b06a75a4f4 | 432ddd9 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349-TAILCALL) | python/d73634935cb9ce00a57d | d736349 (TAILCALL) |  |  |  |  |
| [2026-02-07](results/bm-20260207-3.15.0a5%2B-d736349-JIT%2CTAILCALL) | python/d73634935cb9ce00a57d | d736349 (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-TAILCALL) | python/a2495ff1e7b370c26128 | a2495ff (TAILCALL) |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT%2CTAILCALL) | python/a2495ff1e7b370c26128 | a2495ff (JIT) (TAILCALL) |  |  |  |  |


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
