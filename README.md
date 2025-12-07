# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (eba449a)](results/bm-20251205-3.15.0a2%2B-eba449a/bm-20251205-ripley-x86_64-python-main-3.15.0a2%2B-eba449a-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (eba449a)](results/bm-20251205-3.15.0a2%2B-eba449a-PYTHON_UOPS/bm-20251205-blueberry-aarch64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-05](results/bm-20251205-3.15.0a2%2B-eba449a-JIT) | python/eba449a1989265a92317 | eba449a (JIT) |  |  |  | 1.058x ↓<br>[📄](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-blueberry-aarch64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base.md)[📈](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-blueberry-aarch64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base.svg)[🧠](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-blueberry-aarch64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base-mem.svg) |
| [2025-12-05](results/bm-20251205-3.15.0a2%2B-eba449a) | python/eba449a1989265a92317 | eba449a |  |  |  |  |
| [2025-12-04](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT) | python/b3bf2128989e550a7a02 | b3bf212 (JIT) |  |  |  | 1.078x ↓<br>[📄](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-blueberry-aarch64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base.md)[📈](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-blueberry-aarch64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base.svg)[🧠](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-blueberry-aarch64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base-mem.svg) |
| [2025-12-04](results/bm-20251204-3.15.0a2%2B-b3bf212) | python/b3bf2128989e550a7a02 | b3bf212 |  |  |  |  |
| [2025-12-03](results/bm-20251203-3.15.0a2%2B-c525204-JIT) | python/c5252045d3a7164f1829 | c525204 (JIT) |  |  |  | 1.063x ↓<br>[📄](results/bm-20251203-3.15.0a2%2B-c525204-JIT/bm-20251203-blueberry-aarch64-python-c5252045d3a7164f1829-3.15.0a2%2B-c525204-vs-base.md)[📈](results/bm-20251203-3.15.0a2%2B-c525204-JIT/bm-20251203-blueberry-aarch64-python-c5252045d3a7164f1829-3.15.0a2%2B-c525204-vs-base.svg)[🧠](results/bm-20251203-3.15.0a2%2B-c525204-JIT/bm-20251203-blueberry-aarch64-python-c5252045d3a7164f1829-3.15.0a2%2B-c525204-vs-base-mem.svg) |
| [2025-12-03](results/bm-20251203-3.15.0a2%2B-c525204) | python/c5252045d3a7164f1829 | c525204 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-05](results/bm-20251205-3.15.0a2%2B-eba449a-JIT) | python/eba449a1989265a92317 | eba449a (JIT) |  |  |  | 1.014x ↑<br>[📄](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-ripley-x86_64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base.md)[📈](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-ripley-x86_64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base.svg)[🧠](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-ripley-x86_64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base-mem.svg) |
| [2025-12-05](results/bm-20251205-3.15.0a2%2B-eba449a) | python/eba449a1989265a92317 | eba449a |  |  |  |  |
| [2025-12-04](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT) | python/b3bf2128989e550a7a02 | b3bf212 (JIT) |  |  |  | 1.024x ↑<br>[📄](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-ripley-x86_64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base.md)[📈](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-ripley-x86_64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base.svg)[🧠](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-ripley-x86_64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base-mem.svg) |
| [2025-12-04](results/bm-20251204-3.15.0a2%2B-b3bf212) | python/b3bf2128989e550a7a02 | b3bf212 |  |  |  |  |
| [2025-12-03](results/bm-20251203-3.15.0a2%2B-c525204-JIT) | python/c5252045d3a7164f1829 | c525204 (JIT) |  |  |  | 1.024x ↑<br>[📄](results/bm-20251203-3.15.0a2%2B-c525204-JIT/bm-20251203-ripley-x86_64-python-c5252045d3a7164f1829-3.15.0a2%2B-c525204-vs-base.md)[📈](results/bm-20251203-3.15.0a2%2B-c525204-JIT/bm-20251203-ripley-x86_64-python-c5252045d3a7164f1829-3.15.0a2%2B-c525204-vs-base.svg)[🧠](results/bm-20251203-3.15.0a2%2B-c525204-JIT/bm-20251203-ripley-x86_64-python-c5252045d3a7164f1829-3.15.0a2%2B-c525204-vs-base-mem.svg) |
| [2025-12-03](results/bm-20251203-3.15.0a2%2B-c525204) | python/c5252045d3a7164f1829 | c525204 |  |  |  |  |
| [2025-12-06](results/bm-20251206-3.14.2-00bf18d) | Fidget-Spinner/paper_3.14.2_noopt | 00bf18d |  |  |  |  |
| [2025-12-05](results/bm-20251205-3.14.2-df79316-JIT) | Fidget-Spinner/paper_3.14.2 | df79316 (JIT) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-05](results/bm-20251205-3.15.0a2%2B-eba449a-JIT) | python/eba449a1989265a92317 | eba449a (JIT) |  |  |  | 1.025x ↑<br>[📄](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-jones-arm64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base.md)[📈](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-jones-arm64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base.svg)[🧠](results/bm-20251205-3.15.0a2%2B-eba449a-JIT/bm-20251205-jones-arm64-python-eba449a1989265a92317-3.15.0a2%2B-eba449a-vs-base-mem.svg) |
| [2025-12-05](results/bm-20251205-3.15.0a2%2B-eba449a) | python/eba449a1989265a92317 | eba449a |  |  |  |  |
| [2025-12-04](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT) | python/b3bf2128989e550a7a02 | b3bf212 (JIT) |  |  |  | 1.023x ↑<br>[📄](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-jones-arm64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base.md)[📈](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-jones-arm64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base.svg)[🧠](results/bm-20251204-3.15.0a2%2B-b3bf212-JIT/bm-20251204-jones-arm64-python-b3bf2128989e550a7a02-3.15.0a2%2B-b3bf212-vs-base-mem.svg) |
| [2025-12-04](results/bm-20251204-3.15.0a2%2B-b3bf212) | python/b3bf2128989e550a7a02 | b3bf212 |  |  |  |  |
| [2025-12-06](results/bm-20251206-3.14.2-00bf18d) | Fidget-Spinner/paper_3.14.2_noopt | 00bf18d |  |  |  |  |
| [2025-12-05](results/bm-20251205-3.14.2-df79316-JIT) | Fidget-Spinner/paper_3.14.2 | df79316 (JIT) |  |  |  |  |
| [2025-12-05](results/bm-20251205-3.14.2-df79316) | Fidget-Spinner/paper_3.14.2 | df79316 |  |  |  |  |


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
