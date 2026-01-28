# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (6ea3f8c)](results/bm-20260127-3.15.0a5%2B-6ea3f8c/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (6ea3f8c)](results/bm-20260127-3.15.0a5%2B-6ea3f8c-PYTHON_UOPS/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c (JIT) |  |  |  | 1.024x ↑<br>[📄](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base.md)[📈](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base.svg)[🧠](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-blueberry-aarch64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base-mem.svg) |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c |  |  |  |  |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT) | python/3e9a5b022f01fa95b448 | 3e9a5b0 (JIT) |  |  |  | 1.021x ↑<br>[📄](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-blueberry-aarch64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base.md)[📈](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-blueberry-aarch64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base.svg)[🧠](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-blueberry-aarch64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base-mem.svg) |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-3e9a5b0) | python/3e9a5b022f01fa95b448 | 3e9a5b0 |  |  |  |  |
| [2026-01-26](results/bm-20260126-3.15.0a5%2B-9982147-JIT) | python/99821474336187eaf657 | 9982147 (JIT) |  |  |  | 1.021x ↑<br>[📄](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-blueberry-aarch64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base.md)[📈](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-blueberry-aarch64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base.svg)[🧠](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-blueberry-aarch64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base-mem.svg) |
| [2026-01-26](results/bm-20260126-3.15.0a5%2B-9982147) | python/99821474336187eaf657 | 9982147 |  |  |  |  |
| [2026-01-24](results/bm-20260124-3.15.0a5%2B-979d92f-JIT) | python/979d92fefc0b6863c978 | 979d92f (JIT) |  |  |  | 1.025x ↑<br>[📄](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base.md)[📈](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base.svg)[🧠](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-blueberry-aarch64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base-mem.svg) |
| [2026-01-24](results/bm-20260124-3.15.0a5%2B-979d92f) | python/979d92fefc0b6863c978 | 979d92f |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c (JIT) |  |  |  | 1.039x ↑<br>[📄](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base.md)[📈](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base.svg)[🧠](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-ripley-x86_64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base-mem.svg) |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c |  |  |  |  |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT) | python/3e9a5b022f01fa95b448 | 3e9a5b0 (JIT) |  |  |  | 1.042x ↑<br>[📄](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-ripley-x86_64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base.md)[📈](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-ripley-x86_64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base.svg)[🧠](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-ripley-x86_64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base-mem.svg) |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-3e9a5b0) | python/3e9a5b022f01fa95b448 | 3e9a5b0 |  |  |  |  |
| [2026-01-26](results/bm-20260126-3.15.0a5%2B-9982147-JIT) | python/99821474336187eaf657 | 9982147 (JIT) |  |  |  | 1.041x ↑<br>[📄](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-ripley-x86_64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base.md)[📈](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-ripley-x86_64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base.svg)[🧠](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-ripley-x86_64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base-mem.svg) |
| [2026-01-26](results/bm-20260126-3.15.0a5%2B-9982147) | python/99821474336187eaf657 | 9982147 |  |  |  |  |
| [2026-01-24](results/bm-20260124-3.15.0a5%2B-979d92f-JIT) | python/979d92fefc0b6863c978 | 979d92f (JIT) |  |  |  | 1.042x ↑<br>[📄](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-ripley-x86_64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base.md)[📈](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-ripley-x86_64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base.svg)[🧠](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-ripley-x86_64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base-mem.svg) |
| [2026-01-24](results/bm-20260124-3.15.0a5%2B-979d92f) | python/979d92fefc0b6863c978 | 979d92f |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c (JIT) |  |  |  | 1.163x ↑<br>[📄](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-prometheus-amd64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base.md)[📈](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT/bm-20260127-prometheus-amd64-python-6ea3f8cd7ff4ff9769ae-3.15.0a5%2B-6ea3f8c-vs-base.svg) |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c |  |  |  |  |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT) | python/3e9a5b022f01fa95b448 | 3e9a5b0 (JIT) |  |  |  | 1.155x ↑<br>[📄](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-prometheus-amd64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base.md)[📈](results/bm-20260127-3.15.0a5%2B-3e9a5b0-JIT/bm-20260127-prometheus-amd64-python-3e9a5b022f01fa95b448-3.15.0a5%2B-3e9a5b0-vs-base.svg) |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-3e9a5b0) | python/3e9a5b022f01fa95b448 | 3e9a5b0 |  |  |  |  |
| [2026-01-26](results/bm-20260126-3.15.0a5%2B-9982147-JIT) | python/99821474336187eaf657 | 9982147 (JIT) |  |  |  | 1.137x ↑<br>[📄](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-prometheus-amd64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base.md)[📈](results/bm-20260126-3.15.0a5%2B-9982147-JIT/bm-20260126-prometheus-amd64-python-99821474336187eaf657-3.15.0a5%2B-9982147-vs-base.svg) |
| [2026-01-26](results/bm-20260126-3.15.0a5%2B-9982147) | python/99821474336187eaf657 | 9982147 |  |  |  |  |
| [2026-01-24](results/bm-20260124-3.15.0a5%2B-979d92f-JIT) | python/979d92fefc0b6863c978 | 979d92f (JIT) |  |  |  | 1.162x ↑<br>[📄](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base.md)[📈](results/bm-20260124-3.15.0a5%2B-979d92f-JIT/bm-20260124-prometheus-amd64-python-979d92fefc0b6863c978-3.15.0a5%2B-979d92f-vs-base.svg) |
| [2026-01-24](results/bm-20260124-3.15.0a5%2B-979d92f) | python/979d92fefc0b6863c978 | 979d92f |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c-TAILCALL) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c (TAILCALL) |  |  |  |  |
| [2026-01-27](results/bm-20260127-3.15.0a5%2B-6ea3f8c-JIT%2CTAILCALL) | python/6ea3f8cd7ff4ff9769ae | 6ea3f8c (JIT) (TAILCALL) |  |  |  |  |
| [2026-01-23](results/bm-20260123-3.15.0a5%2B-f3dd0ca-TAILCALL) | python/f3dd0cae6cea38b15b42 | f3dd0ca (TAILCALL) |  |  |  |  |


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
