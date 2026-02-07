# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (a2495ff)](results/bm-20260206-3.15.0a5%2B-a2495ff/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (a2495ff)](results/bm-20260206-3.15.0a5%2B-a2495ff-PYTHON_UOPS/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT) | python/a2495ff1e7b370c26128 | a2495ff (JIT) |  |  |  | 1.012x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.svg)[🧠](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-blueberry-aarch64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base-mem.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff) | python/a2495ff1e7b370c26128 | a2495ff |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT) | python/cf60e0c4527b910c93c8 | cf60e0c (JIT) |  |  |  | 1.008x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.svg)[🧠](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-blueberry-aarch64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base-mem.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c) | python/cf60e0c4527b910c93c8 | cf60e0c |  |  |  |  |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT) | python/b53fc7caa6f41bf3bd7d | b53fc7c (JIT) |  |  |  | 1.018x ↑<br>[📄](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-blueberry-aarch64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base.md)[📈](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-blueberry-aarch64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base.svg)[🧠](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-blueberry-aarch64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base-mem.svg) |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c) | python/b53fc7caa6f41bf3bd7d | b53fc7c |  |  |  |  |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT) | python/34e5a63f145585cbeb09 | 34e5a63 (JIT) |  |  |  | 1.024x ↑<br>[📄](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-blueberry-aarch64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base.md)[📈](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-blueberry-aarch64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base.svg)[🧠](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-blueberry-aarch64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base-mem.svg) |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63) | python/34e5a63f145585cbeb09 | 34e5a63 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT) | python/a2495ff1e7b370c26128 | a2495ff (JIT) |  |  |  | 1.038x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.svg)[🧠](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-ripley-x86_64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base-mem.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff) | python/a2495ff1e7b370c26128 | a2495ff |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT) | python/cf60e0c4527b910c93c8 | cf60e0c (JIT) |  |  |  | 1.033x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-ripley-x86_64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-ripley-x86_64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.svg)[🧠](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-ripley-x86_64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base-mem.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c) | python/cf60e0c4527b910c93c8 | cf60e0c |  |  |  |  |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT) | python/b53fc7caa6f41bf3bd7d | b53fc7c (JIT) |  |  |  | 1.037x ↑<br>[📄](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base.md)[📈](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base.svg)[🧠](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-ripley-x86_64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base-mem.svg) |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c) | python/b53fc7caa6f41bf3bd7d | b53fc7c |  |  |  |  |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT) | python/34e5a63f145585cbeb09 | 34e5a63 (JIT) |  |  |  | 1.038x ↑<br>[📄](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-ripley-x86_64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base.md)[📈](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-ripley-x86_64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base.svg)[🧠](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-ripley-x86_64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base-mem.svg) |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63) | python/34e5a63f145585cbeb09 | 34e5a63 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT) | python/a2495ff1e7b370c26128 | a2495ff (JIT) |  |  |  | 1.173x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-prometheus-amd64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT/bm-20260206-prometheus-amd64-python-a2495ff1e7b370c26128-3.15.0a5%2B-a2495ff-vs-base.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff) | python/a2495ff1e7b370c26128 | a2495ff |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT) | python/cf60e0c4527b910c93c8 | cf60e0c (JIT) |  |  |  | 1.144x ↑<br>[📄](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-prometheus-amd64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.md)[📈](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT/bm-20260206-prometheus-amd64-python-cf60e0c4527b910c93c8-3.15.0a5%2B-cf60e0c-vs-base.svg) |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c) | python/cf60e0c4527b910c93c8 | cf60e0c |  |  |  |  |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT) | python/b53fc7caa6f41bf3bd7d | b53fc7c (JIT) |  |  |  | 1.147x ↑<br>[📄](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-prometheus-amd64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base.md)[📈](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT/bm-20260205-prometheus-amd64-python-b53fc7caa6f41bf3bd7d-3.15.0a5%2B-b53fc7c-vs-base.svg) |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c) | python/b53fc7caa6f41bf3bd7d | b53fc7c |  |  |  |  |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT) | python/34e5a63f145585cbeb09 | 34e5a63 (JIT) |  |  |  | 1.145x ↑<br>[📄](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-prometheus-amd64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base.md)[📈](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT/bm-20260204-prometheus-amd64-python-34e5a63f145585cbeb09-3.15.0a5%2B-34e5a63-vs-base.svg) |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63) | python/34e5a63f145585cbeb09 | 34e5a63 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-TAILCALL) | python/a2495ff1e7b370c26128 | a2495ff (TAILCALL) |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-a2495ff-JIT%2CTAILCALL) | python/a2495ff1e7b370c26128 | a2495ff (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c-TAILCALL) | python/cf60e0c4527b910c93c8 | cf60e0c (TAILCALL) |  |  |  |  |
| [2026-02-06](results/bm-20260206-3.15.0a5%2B-cf60e0c-JIT%2CTAILCALL) | python/cf60e0c4527b910c93c8 | cf60e0c (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c-TAILCALL) | python/b53fc7caa6f41bf3bd7d | b53fc7c (TAILCALL) |  |  |  |  |
| [2026-02-05](results/bm-20260205-3.15.0a5%2B-b53fc7c-JIT%2CTAILCALL) | python/b53fc7caa6f41bf3bd7d | b53fc7c (JIT) (TAILCALL) |  |  |  |  |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63-TAILCALL) | python/34e5a63f145585cbeb09 | 34e5a63 (TAILCALL) |  |  |  |  |
| [2026-02-04](results/bm-20260204-3.15.0a5%2B-34e5a63-JIT%2CTAILCALL) | python/34e5a63f145585cbeb09 | 34e5a63 (JIT) (TAILCALL) |  |  |  |  |


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
