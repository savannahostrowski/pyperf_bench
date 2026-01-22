# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (6181b69)](results/bm-20260121-3.15.0a5%2B-6181b69/bm-20260121-ripley-x86_64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (6181b69)](results/bm-20260121-3.15.0a5%2B-6181b69-PYTHON_UOPS/bm-20260121-ripley-x86_64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69-JIT) | python/6181b69970b93fc74d74 | 6181b69 (JIT) |  |  |  | 1.015x ↑<br>[📄](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-blueberry-aarch64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base.md)[📈](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-blueberry-aarch64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base.svg)[🧠](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-blueberry-aarch64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base-mem.svg) |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69) | python/6181b69970b93fc74d74 | 6181b69 |  |  |  |  |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT) | python/9060b4abbe475591b623 | 9060b4a (JIT) |  |  |  | 1.022x ↑<br>[📄](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-blueberry-aarch64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base.md)[📈](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-blueberry-aarch64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base.svg)[🧠](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-blueberry-aarch64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base-mem.svg) |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a) | python/9060b4abbe475591b623 | 9060b4a |  |  |  |  |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT) | python/fa3abf5a51d42b2d62e1 | fa3abf5 (JIT) |  |  |  | 1.024x ↑<br>[📄](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-blueberry-aarch64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base.md)[📈](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-blueberry-aarch64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base.svg)[🧠](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-blueberry-aarch64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base-mem.svg) |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5) | python/fa3abf5a51d42b2d62e1 | fa3abf5 |  |  |  |  |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594-JIT) | python/59d3594ca12939dea0a5 | 59d3594 (JIT) |  |  |  | 1.020x ↑<br>[📄](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-blueberry-aarch64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base.md)[📈](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-blueberry-aarch64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base.svg)[🧠](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-blueberry-aarch64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base-mem.svg) |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594) | python/59d3594ca12939dea0a5 | 59d3594 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69-JIT) | python/6181b69970b93fc74d74 | 6181b69 (JIT) |  |  |  | 1.047x ↑<br>[📄](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-ripley-x86_64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base.md)[📈](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-ripley-x86_64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base.svg)[🧠](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-ripley-x86_64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base-mem.svg) |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69) | python/6181b69970b93fc74d74 | 6181b69 |  |  |  |  |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT) | python/9060b4abbe475591b623 | 9060b4a (JIT) |  |  |  | 1.048x ↑<br>[📄](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-ripley-x86_64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base.md)[📈](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-ripley-x86_64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base.svg)[🧠](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-ripley-x86_64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base-mem.svg) |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a) | python/9060b4abbe475591b623 | 9060b4a |  |  |  |  |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT) | python/fa3abf5a51d42b2d62e1 | fa3abf5 (JIT) |  |  |  | 1.050x ↑<br>[📄](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base.md)[📈](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base.svg)[🧠](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-ripley-x86_64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base-mem.svg) |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5) | python/fa3abf5a51d42b2d62e1 | fa3abf5 |  |  |  |  |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594-JIT) | python/59d3594ca12939dea0a5 | 59d3594 (JIT) |  |  |  | 1.049x ↑<br>[📄](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-ripley-x86_64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base.md)[📈](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-ripley-x86_64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base.svg)[🧠](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-ripley-x86_64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base-mem.svg) |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594) | python/59d3594ca12939dea0a5 | 59d3594 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69-JIT) | python/6181b69970b93fc74d74 | 6181b69 (JIT) |  |  |  | 1.171x ↑<br>[📄](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-prometheus-amd64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base.md)[📈](results/bm-20260121-3.15.0a5%2B-6181b69-JIT/bm-20260121-prometheus-amd64-python-6181b69970b93fc74d74-3.15.0a5%2B-6181b69-vs-base.svg) |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69) | python/6181b69970b93fc74d74 | 6181b69 |  |  |  |  |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT) | python/9060b4abbe475591b623 | 9060b4a (JIT) |  |  |  | 1.160x ↑<br>[📄](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base.md)[📈](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT/bm-20260121-prometheus-amd64-python-9060b4abbe475591b623-3.15.0a5%2B-9060b4a-vs-base.svg) |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a) | python/9060b4abbe475591b623 | 9060b4a |  |  |  |  |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT) | python/fa3abf5a51d42b2d62e1 | fa3abf5 (JIT) |  |  |  | 1.170x ↑<br>[📄](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-prometheus-amd64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base.md)[📈](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT/bm-20260120-prometheus-amd64-python-fa3abf5a51d42b2d62e1-3.15.0a5%2B-fa3abf5-vs-base.svg) |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5) | python/fa3abf5a51d42b2d62e1 | fa3abf5 |  |  |  |  |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594-JIT) | python/59d3594ca12939dea0a5 | 59d3594 (JIT) |  |  |  | 1.184x ↑<br>[📄](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-prometheus-amd64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base.md)[📈](results/bm-20260118-3.15.0a5%2B-59d3594-JIT/bm-20260118-prometheus-amd64-python-59d3594ca12939dea0a5-3.15.0a5%2B-59d3594-vs-base.svg) |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594) | python/59d3594ca12939dea0a5 | 59d3594 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69-TAILCALL) | python/6181b69970b93fc74d74 | 6181b69 (TAILCALL) |  |  |  |  |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-6181b69-JIT%2CTAILCALL) | python/6181b69970b93fc74d74 | 6181b69 (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a-TAILCALL) | python/9060b4abbe475591b623 | 9060b4a (TAILCALL) |  |  |  |  |
| [2026-01-21](results/bm-20260121-3.15.0a5%2B-9060b4a-JIT%2CTAILCALL) | python/9060b4abbe475591b623 | 9060b4a (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5-TAILCALL) | python/fa3abf5a51d42b2d62e1 | fa3abf5 (TAILCALL) |  |  |  |  |
| [2026-01-20](results/bm-20260120-3.15.0a5%2B-fa3abf5-JIT%2CTAILCALL) | python/fa3abf5a51d42b2d62e1 | fa3abf5 (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594-TAILCALL) | python/59d3594ca12939dea0a5 | 59d3594 (TAILCALL) |  |  |  |  |
| [2026-01-18](results/bm-20260118-3.15.0a5%2B-59d3594-JIT%2CTAILCALL) | python/59d3594ca12939dea0a5 | 59d3594 (JIT) (TAILCALL) |  |  |  |  |


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
