# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (c90863a)](results/bm-20251212-3.15.0a2%2B-c90863a/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (c90863a)](results/bm-20251212-3.15.0a2%2B-c90863a-PYTHON_UOPS/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-12](results/bm-20251212-3.15.0a2%2B-c90863a-JIT) | python/c90863ac3dcbc5b0b8f9 | c90863a (JIT) |  |  |  | 1.007x ↓<br>[📄](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-blueberry-aarch64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.md)[📈](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-blueberry-aarch64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.svg)[🧠](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-blueberry-aarch64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base-mem.svg) |
| [2025-12-12](results/bm-20251212-3.15.0a2%2B-c90863a) | python/c90863ac3dcbc5b0b8f9 | c90863a |  |  |  |  |
| [2025-12-11](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT) | python/b1c9582ebe1309819588 | b1c9582 (JIT) |  |  |  | 1.060x ↓<br>[📄](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-blueberry-aarch64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.md)[📈](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-blueberry-aarch64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.svg)[🧠](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-blueberry-aarch64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base-mem.svg) |
| [2025-12-11](results/bm-20251211-3.15.0a2%2B-b1c9582) | python/b1c9582ebe1309819588 | b1c9582 |  |  |  |  |
| [2025-12-10](results/bm-20251210-3.15.0a2%2B-880a790-JIT) | python/880a7905ca53d3c5c229 | 880a790 (JIT) |  |  |  | 1.049x ↓<br>[📄](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-blueberry-aarch64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.md)[📈](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-blueberry-aarch64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.svg)[🧠](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-blueberry-aarch64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base-mem.svg) |
| [2025-12-10](results/bm-20251210-3.15.0a2%2B-880a790) | python/880a7905ca53d3c5c229 | 880a790 |  |  |  |  |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT) | python/37fe9a90c5f99fd3830b | 37fe9a9 (JIT) |  |  |  | 1.022x ↓<br>[📄](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)[📈](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)[🧠](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-blueberry-aarch64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg) |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9) | python/37fe9a90c5f99fd3830b | 37fe9a9 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-12](results/bm-20251212-3.15.0a2%2B-c90863a-JIT) | python/c90863ac3dcbc5b0b8f9 | c90863a (JIT) |  |  |  | 1.025x ↑<br>[📄](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.md)[📈](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.svg)[🧠](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-ripley-x86_64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base-mem.svg) |
| [2025-12-12](results/bm-20251212-3.15.0a2%2B-c90863a) | python/c90863ac3dcbc5b0b8f9 | c90863a |  |  |  |  |
| [2025-12-11](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT) | python/b1c9582ebe1309819588 | b1c9582 (JIT) |  |  |  | 1.029x ↑<br>[📄](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-ripley-x86_64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.md)[📈](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-ripley-x86_64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.svg)[🧠](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-ripley-x86_64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base-mem.svg) |
| [2025-12-11](results/bm-20251211-3.15.0a2%2B-b1c9582) | python/b1c9582ebe1309819588 | b1c9582 |  |  |  |  |
| [2025-12-10](results/bm-20251210-3.15.0a2%2B-880a790-JIT) | python/880a7905ca53d3c5c229 | 880a790 (JIT) |  |  |  | 1.020x ↑<br>[📄](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-ripley-x86_64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.md)[📈](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-ripley-x86_64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.svg)[🧠](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-ripley-x86_64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base-mem.svg) |
| [2025-12-10](results/bm-20251210-3.15.0a2%2B-880a790) | python/880a7905ca53d3c5c229 | 880a790 |  |  |  |  |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT) | python/37fe9a90c5f99fd3830b | 37fe9a9 (JIT) |  |  |  | 1.017x ↑<br>[📄](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.md)[📈](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base.svg)[🧠](results/bm-20251209-3.15.0a2%2B-37fe9a9-JIT/bm-20251209-ripley-x86_64-python-37fe9a90c5f99fd3830b-3.15.0a2%2B-37fe9a9-vs-base-mem.svg) |
| [2025-12-09](results/bm-20251209-3.15.0a2%2B-37fe9a9) | python/37fe9a90c5f99fd3830b | 37fe9a9 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-12](results/bm-20251212-3.15.0a2%2B-c90863a-JIT) | python/c90863ac3dcbc5b0b8f9 | c90863a (JIT) |  |  |  | 1.088x ↑<br>[📄](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.md)[📈](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base.svg)[🧠](results/bm-20251212-3.15.0a2%2B-c90863a-JIT/bm-20251212-jones-arm64-python-c90863ac3dcbc5b0b8f9-3.15.0a2%2B-c90863a-vs-base-mem.svg) |
| [2025-12-12](results/bm-20251212-3.15.0a2%2B-c90863a) | python/c90863ac3dcbc5b0b8f9 | c90863a |  |  |  |  |
| [2025-12-11](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT) | python/b1c9582ebe1309819588 | b1c9582 (JIT) |  |  |  | 1.082x ↑<br>[📄](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-jones-arm64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.md)[📈](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-jones-arm64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base.svg)[🧠](results/bm-20251211-3.15.0a2%2B-b1c9582-JIT/bm-20251211-jones-arm64-python-b1c9582ebe1309819588-3.15.0a2%2B-b1c9582-vs-base-mem.svg) |
| [2025-12-11](results/bm-20251211-3.15.0a2%2B-b1c9582) | python/b1c9582ebe1309819588 | b1c9582 |  |  |  |  |
| [2025-12-10](results/bm-20251210-3.15.0a2%2B-880a790-JIT) | python/880a7905ca53d3c5c229 | 880a790 (JIT) |  |  |  | 1.023x ↑<br>[📄](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-jones-arm64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.md)[📈](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-jones-arm64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base.svg)[🧠](results/bm-20251210-3.15.0a2%2B-880a790-JIT/bm-20251210-jones-arm64-python-880a7905ca53d3c5c229-3.15.0a2%2B-880a790-vs-base-mem.svg) |
| [2025-12-10](results/bm-20251210-3.15.0a2%2B-880a790) | python/880a7905ca53d3c5c229 | 880a790 |  |  |  |  |


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
