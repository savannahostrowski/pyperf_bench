# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (776573c)](results/bm-20260526-3.16.0a0-776573c/bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (776573c)](results/bm-20260526-3.16.0a0-776573c-PYTHON_UOPS/bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c-JIT) | python/776573c9f08f70ae9cb2 | 776573c (JIT) |  |  |  | 1.009x ↓<br>[📄](results/bm-20260526-3.16.0a0-776573c-JIT/bm-20260526-blueberry-aarch64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.md)[📈](results/bm-20260526-3.16.0a0-776573c-JIT/bm-20260526-blueberry-aarch64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.svg)[🧠](results/bm-20260526-3.16.0a0-776573c-JIT/bm-20260526-blueberry-aarch64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base-mem.svg) |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c) | python/776573c9f08f70ae9cb2 | 776573c |  |  |  |  |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d-JIT) | python/a5be25d3bdc1b3cbc963 | a5be25d (JIT) |  |  |  | 1.018x ↓<br>[📄](results/bm-20260525-3.16.0a0-a5be25d-JIT/bm-20260525-blueberry-aarch64-python-a5be25d3bdc1b3cbc963-3.16.0a0-a5be25d-vs-base.md)[📈](results/bm-20260525-3.16.0a0-a5be25d-JIT/bm-20260525-blueberry-aarch64-python-a5be25d3bdc1b3cbc963-3.16.0a0-a5be25d-vs-base.svg)[🧠](results/bm-20260525-3.16.0a0-a5be25d-JIT/bm-20260525-blueberry-aarch64-python-a5be25d3bdc1b3cbc963-3.16.0a0-a5be25d-vs-base-mem.svg) |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d) | python/a5be25d3bdc1b3cbc963 | a5be25d |  |  |  |  |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec-JIT) | python/43c60ec2fddd316a4a6b | 43c60ec (JIT) |  |  |  | 1.007x ↓<br>[📄](results/bm-20260524-3.16.0a0-43c60ec-JIT/bm-20260524-blueberry-aarch64-python-43c60ec2fddd316a4a6b-3.16.0a0-43c60ec-vs-base.md)[📈](results/bm-20260524-3.16.0a0-43c60ec-JIT/bm-20260524-blueberry-aarch64-python-43c60ec2fddd316a4a6b-3.16.0a0-43c60ec-vs-base.svg)[🧠](results/bm-20260524-3.16.0a0-43c60ec-JIT/bm-20260524-blueberry-aarch64-python-43c60ec2fddd316a4a6b-3.16.0a0-43c60ec-vs-base-mem.svg) |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec) | python/43c60ec2fddd316a4a6b | 43c60ec |  |  |  |  |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674-JIT) | python/fad06746051f6bd95a25 | fad0674 (JIT) |  |  |  | 1.015x ↓<br>[📄](results/bm-20260523-3.16.0a0-fad0674-JIT/bm-20260523-blueberry-aarch64-python-fad06746051f6bd95a25-3.16.0a0-fad0674-vs-base.md)[📈](results/bm-20260523-3.16.0a0-fad0674-JIT/bm-20260523-blueberry-aarch64-python-fad06746051f6bd95a25-3.16.0a0-fad0674-vs-base.svg)[🧠](results/bm-20260523-3.16.0a0-fad0674-JIT/bm-20260523-blueberry-aarch64-python-fad06746051f6bd95a25-3.16.0a0-fad0674-vs-base-mem.svg) |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674) | python/fad06746051f6bd95a25 | fad0674 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c-JIT) | python/776573c9f08f70ae9cb2 | 776573c (JIT) |  |  |  | 1.071x ↑<br>[📄](results/bm-20260526-3.16.0a0-776573c-JIT/bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.md)[📈](results/bm-20260526-3.16.0a0-776573c-JIT/bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base.svg)[🧠](results/bm-20260526-3.16.0a0-776573c-JIT/bm-20260526-ripley-x86_64-python-776573c9f08f70ae9cb2-3.16.0a0-776573c-vs-base-mem.svg) |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c) | python/776573c9f08f70ae9cb2 | 776573c |  |  |  |  |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d-JIT) | python/a5be25d3bdc1b3cbc963 | a5be25d (JIT) |  |  |  | 1.075x ↑<br>[📄](results/bm-20260525-3.16.0a0-a5be25d-JIT/bm-20260525-ripley-x86_64-python-a5be25d3bdc1b3cbc963-3.16.0a0-a5be25d-vs-base.md)[📈](results/bm-20260525-3.16.0a0-a5be25d-JIT/bm-20260525-ripley-x86_64-python-a5be25d3bdc1b3cbc963-3.16.0a0-a5be25d-vs-base.svg)[🧠](results/bm-20260525-3.16.0a0-a5be25d-JIT/bm-20260525-ripley-x86_64-python-a5be25d3bdc1b3cbc963-3.16.0a0-a5be25d-vs-base-mem.svg) |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d) | python/a5be25d3bdc1b3cbc963 | a5be25d |  |  |  |  |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec-JIT) | python/43c60ec2fddd316a4a6b | 43c60ec (JIT) |  |  |  | 1.066x ↑<br>[📄](results/bm-20260524-3.16.0a0-43c60ec-JIT/bm-20260524-ripley-x86_64-python-43c60ec2fddd316a4a6b-3.16.0a0-43c60ec-vs-base.md)[📈](results/bm-20260524-3.16.0a0-43c60ec-JIT/bm-20260524-ripley-x86_64-python-43c60ec2fddd316a4a6b-3.16.0a0-43c60ec-vs-base.svg)[🧠](results/bm-20260524-3.16.0a0-43c60ec-JIT/bm-20260524-ripley-x86_64-python-43c60ec2fddd316a4a6b-3.16.0a0-43c60ec-vs-base-mem.svg) |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec) | python/43c60ec2fddd316a4a6b | 43c60ec |  |  |  |  |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674-JIT) | python/fad06746051f6bd95a25 | fad0674 (JIT) |  |  |  | 1.068x ↑<br>[📄](results/bm-20260523-3.16.0a0-fad0674-JIT/bm-20260523-ripley-x86_64-python-fad06746051f6bd95a25-3.16.0a0-fad0674-vs-base.md)[📈](results/bm-20260523-3.16.0a0-fad0674-JIT/bm-20260523-ripley-x86_64-python-fad06746051f6bd95a25-3.16.0a0-fad0674-vs-base.svg)[🧠](results/bm-20260523-3.16.0a0-fad0674-JIT/bm-20260523-ripley-x86_64-python-fad06746051f6bd95a25-3.16.0a0-fad0674-vs-base-mem.svg) |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674) | python/fad06746051f6bd95a25 | fad0674 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c-TAILCALL) | python/776573c9f08f70ae9cb2 | 776573c (TAILCALL) |  |  |  |  |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c-JIT%2CTAILCALL) | python/776573c9f08f70ae9cb2 | 776573c (JIT) (TAILCALL) |  |  |  |  |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d-TAILCALL) | python/a5be25d3bdc1b3cbc963 | a5be25d (TAILCALL) |  |  |  |  |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d-JIT%2CTAILCALL) | python/a5be25d3bdc1b3cbc963 | a5be25d (JIT) (TAILCALL) |  |  |  |  |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec-TAILCALL) | python/43c60ec2fddd316a4a6b | 43c60ec (TAILCALL) |  |  |  |  |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec-JIT%2CTAILCALL) | python/43c60ec2fddd316a4a6b | 43c60ec (JIT) (TAILCALL) |  |  |  |  |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674-TAILCALL) | python/fad06746051f6bd95a25 | fad0674 (TAILCALL) |  |  |  |  |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674-JIT%2CTAILCALL) | python/fad06746051f6bd95a25 | fad0674 (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c-TAILCALL) | python/776573c9f08f70ae9cb2 | 776573c (TAILCALL) |  |  |  |  |
| [2026-05-26](results/bm-20260526-3.16.0a0-776573c-JIT%2CTAILCALL) | python/776573c9f08f70ae9cb2 | 776573c (JIT) (TAILCALL) |  |  |  |  |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d-TAILCALL) | python/a5be25d3bdc1b3cbc963 | a5be25d (TAILCALL) |  |  |  |  |
| [2026-05-25](results/bm-20260525-3.16.0a0-a5be25d-JIT%2CTAILCALL) | python/a5be25d3bdc1b3cbc963 | a5be25d (JIT) (TAILCALL) |  |  |  |  |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec-TAILCALL) | python/43c60ec2fddd316a4a6b | 43c60ec (TAILCALL) |  |  |  |  |
| [2026-05-24](results/bm-20260524-3.16.0a0-43c60ec-JIT%2CTAILCALL) | python/43c60ec2fddd316a4a6b | 43c60ec (JIT) (TAILCALL) |  |  |  |  |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674-TAILCALL) | python/fad06746051f6bd95a25 | fad0674 (TAILCALL) |  |  |  |  |
| [2026-05-23](results/bm-20260523-3.16.0a0-fad0674-JIT%2CTAILCALL) | python/fad06746051f6bd95a25 | fad0674 (JIT) (TAILCALL) |  |  |  |  |


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
