# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (9d22a53)](results/bm-20261003-3.16.0a0-9d22a53/bm-20261003-ripley-x86_64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (9d22a53)](results/bm-20261003-3.16.0a0-9d22a53-PYTHON_UOPS/bm-20261003-ripley-x86_64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53-JIT) | python/9d22a5334bd5273962ad | 9d22a53 (JIT) |  |  |  | 1.020x ↑<br>[📄](results/bm-20261003-3.16.0a0-9d22a53-JIT/bm-20261003-blueberry-aarch64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-vs-base.md)[📈](results/bm-20261003-3.16.0a0-9d22a53-JIT/bm-20261003-blueberry-aarch64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-vs-base.svg)[🧠](results/bm-20261003-3.16.0a0-9d22a53-JIT/bm-20261003-blueberry-aarch64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-vs-base-mem.svg) |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53) | python/9d22a5334bd5273962ad | 9d22a53 |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213-JIT) | python/1a85213940896f180cbc | 1a85213 (JIT) |  |  |  | 1.007x ↑<br>[📄](results/bm-20261003-3.16.0a0-1a85213-JIT/bm-20261003-blueberry-aarch64-python-1a85213940896f180cbc-3.16.0a0-1a85213-vs-base.md)[📈](results/bm-20261003-3.16.0a0-1a85213-JIT/bm-20261003-blueberry-aarch64-python-1a85213940896f180cbc-3.16.0a0-1a85213-vs-base.svg)[🧠](results/bm-20261003-3.16.0a0-1a85213-JIT/bm-20261003-blueberry-aarch64-python-1a85213940896f180cbc-3.16.0a0-1a85213-vs-base-mem.svg) |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213) | python/1a85213940896f180cbc | 1a85213 |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5-JIT) | python/a4f28a52b4b54c34100e | a4f28a5 (JIT) |  |  |  | 1.043x ↑<br>[📄](results/bm-20261001-3.16.0a0-a4f28a5-JIT/bm-20261001-blueberry-aarch64-python-a4f28a52b4b54c34100e-3.16.0a0-a4f28a5-vs-base.md)[📈](results/bm-20261001-3.16.0a0-a4f28a5-JIT/bm-20261001-blueberry-aarch64-python-a4f28a52b4b54c34100e-3.16.0a0-a4f28a5-vs-base.svg)[🧠](results/bm-20261001-3.16.0a0-a4f28a5-JIT/bm-20261001-blueberry-aarch64-python-a4f28a52b4b54c34100e-3.16.0a0-a4f28a5-vs-base-mem.svg) |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5) | python/a4f28a52b4b54c34100e | a4f28a5 |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed-JIT) | python/763b6edb0ec959bdfb78 | 763b6ed (JIT) |  |  |  | 1.018x ↑<br>[📄](results/bm-20261001-3.16.0a0-763b6ed-JIT/bm-20261001-blueberry-aarch64-python-763b6edb0ec959bdfb78-3.16.0a0-763b6ed-vs-base.md)[📈](results/bm-20261001-3.16.0a0-763b6ed-JIT/bm-20261001-blueberry-aarch64-python-763b6edb0ec959bdfb78-3.16.0a0-763b6ed-vs-base.svg)[🧠](results/bm-20261001-3.16.0a0-763b6ed-JIT/bm-20261001-blueberry-aarch64-python-763b6edb0ec959bdfb78-3.16.0a0-763b6ed-vs-base-mem.svg) |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed) | python/763b6edb0ec959bdfb78 | 763b6ed |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53-JIT) | python/9d22a5334bd5273962ad | 9d22a53 (JIT) |  |  |  | 1.089x ↑<br>[📄](results/bm-20261003-3.16.0a0-9d22a53-JIT/bm-20261003-ripley-x86_64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-vs-base.md)[📈](results/bm-20261003-3.16.0a0-9d22a53-JIT/bm-20261003-ripley-x86_64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-vs-base.svg)[🧠](results/bm-20261003-3.16.0a0-9d22a53-JIT/bm-20261003-ripley-x86_64-python-9d22a5334bd5273962ad-3.16.0a0-9d22a53-vs-base-mem.svg) |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53) | python/9d22a5334bd5273962ad | 9d22a53 |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213-JIT) | python/1a85213940896f180cbc | 1a85213 (JIT) |  |  |  | 1.089x ↑<br>[📄](results/bm-20261003-3.16.0a0-1a85213-JIT/bm-20261003-ripley-x86_64-python-1a85213940896f180cbc-3.16.0a0-1a85213-vs-base.md)[📈](results/bm-20261003-3.16.0a0-1a85213-JIT/bm-20261003-ripley-x86_64-python-1a85213940896f180cbc-3.16.0a0-1a85213-vs-base.svg)[🧠](results/bm-20261003-3.16.0a0-1a85213-JIT/bm-20261003-ripley-x86_64-python-1a85213940896f180cbc-3.16.0a0-1a85213-vs-base-mem.svg) |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213) | python/1a85213940896f180cbc | 1a85213 |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5-JIT) | python/a4f28a52b4b54c34100e | a4f28a5 (JIT) |  |  |  | 1.094x ↑<br>[📄](results/bm-20261001-3.16.0a0-a4f28a5-JIT/bm-20261001-ripley-x86_64-python-a4f28a52b4b54c34100e-3.16.0a0-a4f28a5-vs-base.md)[📈](results/bm-20261001-3.16.0a0-a4f28a5-JIT/bm-20261001-ripley-x86_64-python-a4f28a52b4b54c34100e-3.16.0a0-a4f28a5-vs-base.svg)[🧠](results/bm-20261001-3.16.0a0-a4f28a5-JIT/bm-20261001-ripley-x86_64-python-a4f28a52b4b54c34100e-3.16.0a0-a4f28a5-vs-base-mem.svg) |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5) | python/a4f28a52b4b54c34100e | a4f28a5 |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed-JIT) | python/763b6edb0ec959bdfb78 | 763b6ed (JIT) |  |  |  | 1.094x ↑<br>[📄](results/bm-20261001-3.16.0a0-763b6ed-JIT/bm-20261001-ripley-x86_64-python-763b6edb0ec959bdfb78-3.16.0a0-763b6ed-vs-base.md)[📈](results/bm-20261001-3.16.0a0-763b6ed-JIT/bm-20261001-ripley-x86_64-python-763b6edb0ec959bdfb78-3.16.0a0-763b6ed-vs-base.svg)[🧠](results/bm-20261001-3.16.0a0-763b6ed-JIT/bm-20261001-ripley-x86_64-python-763b6edb0ec959bdfb78-3.16.0a0-763b6ed-vs-base-mem.svg) |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed) | python/763b6edb0ec959bdfb78 | 763b6ed |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53-TAILCALL) | python/9d22a5334bd5273962ad | 9d22a53 (TAILCALL) |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53-JIT%2CTAILCALL) | python/9d22a5334bd5273962ad | 9d22a53 (JIT) (TAILCALL) |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213-TAILCALL) | python/1a85213940896f180cbc | 1a85213 (TAILCALL) |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213-JIT%2CTAILCALL) | python/1a85213940896f180cbc | 1a85213 (JIT) (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5-TAILCALL) | python/a4f28a52b4b54c34100e | a4f28a5 (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5-JIT%2CTAILCALL) | python/a4f28a52b4b54c34100e | a4f28a5 (JIT) (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed-TAILCALL) | python/763b6edb0ec959bdfb78 | 763b6ed (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed-JIT%2CTAILCALL) | python/763b6edb0ec959bdfb78 | 763b6ed (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53-TAILCALL) | python/9d22a5334bd5273962ad | 9d22a53 (TAILCALL) |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-9d22a53-JIT%2CTAILCALL) | python/9d22a5334bd5273962ad | 9d22a53 (JIT) (TAILCALL) |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213-TAILCALL) | python/1a85213940896f180cbc | 1a85213 (TAILCALL) |  |  |  |  |
| [2026-10-03](results/bm-20261003-3.16.0a0-1a85213-JIT%2CTAILCALL) | python/1a85213940896f180cbc | 1a85213 (JIT) (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5-TAILCALL) | python/a4f28a52b4b54c34100e | a4f28a5 (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-a4f28a5-JIT%2CTAILCALL) | python/a4f28a52b4b54c34100e | a4f28a5 (JIT) (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed-TAILCALL) | python/763b6edb0ec959bdfb78 | 763b6ed (TAILCALL) |  |  |  |  |
| [2026-10-01](results/bm-20261001-3.16.0a0-763b6ed-JIT%2CTAILCALL) | python/763b6edb0ec959bdfb78 | 763b6ed (JIT) (TAILCALL) |  |  |  |  |


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
