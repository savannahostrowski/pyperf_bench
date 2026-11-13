# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (eb21dea)](results/bm-20261112-3.16.0a2%2Bdev-eb21dea/bm-20261112-ripley-x86_64-python-eb21dea301df801352ac-3.16.0a2%2Bdev-eb21dea-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (eb21dea)](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-PYTHON_UOPS/bm-20261112-ripley-x86_64-python-eb21dea301df801352ac-3.16.0a2%2Bdev-eb21dea-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-c07d1f4-JIT) | python/c07d1f4f32ed37d86110 | c07d1f4 (JIT) |  |  |  | 1.025x ↑<br>[📄](results/bm-20261109-3.16.0a1%2Bdev-c07d1f4-JIT/bm-20261109-blueberry-aarch64-python-c07d1f4f32ed37d86110-3.16.0a1%2Bdev-c07d1f4-vs-base.md)[📈](results/bm-20261109-3.16.0a1%2Bdev-c07d1f4-JIT/bm-20261109-blueberry-aarch64-python-c07d1f4f32ed37d86110-3.16.0a1%2Bdev-c07d1f4-vs-base.svg)[🧠](results/bm-20261109-3.16.0a1%2Bdev-c07d1f4-JIT/bm-20261109-blueberry-aarch64-python-c07d1f4f32ed37d86110-3.16.0a1%2Bdev-c07d1f4-vs-base-mem.svg) |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-c07d1f4) | python/c07d1f4f32ed37d86110 | c07d1f4 |  |  |  |  |
| [2026-11-07](results/bm-20261107-3.16.0a1%2Bdev-1955eb3-JIT) | python/1955eb3ec065bda56ed7 | 1955eb3 (JIT) |  |  |  | 1.001x ↑<br>[📄](results/bm-20261107-3.16.0a1%2Bdev-1955eb3-JIT/bm-20261107-blueberry-aarch64-python-1955eb3ec065bda56ed7-3.16.0a1%2Bdev-1955eb3-vs-base.md)[📈](results/bm-20261107-3.16.0a1%2Bdev-1955eb3-JIT/bm-20261107-blueberry-aarch64-python-1955eb3ec065bda56ed7-3.16.0a1%2Bdev-1955eb3-vs-base.svg)[🧠](results/bm-20261107-3.16.0a1%2Bdev-1955eb3-JIT/bm-20261107-blueberry-aarch64-python-1955eb3ec065bda56ed7-3.16.0a1%2Bdev-1955eb3-vs-base-mem.svg) |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-11-12](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-JIT) | python/eb21dea301df801352ac | eb21dea (JIT) |  |  |  | 1.090x ↑<br>[📄](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-JIT/bm-20261112-ripley-x86_64-python-eb21dea301df801352ac-3.16.0a2%2Bdev-eb21dea-vs-base.md)[📈](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-JIT/bm-20261112-ripley-x86_64-python-eb21dea301df801352ac-3.16.0a2%2Bdev-eb21dea-vs-base.svg)[🧠](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-JIT/bm-20261112-ripley-x86_64-python-eb21dea301df801352ac-3.16.0a2%2Bdev-eb21dea-vs-base-mem.svg) |
| [2026-11-12](results/bm-20261112-3.16.0a2%2Bdev-eb21dea) | python/eb21dea301df801352ac | eb21dea |  |  |  |  |
| [2026-11-10](results/bm-20261110-3.16.0a2%2Bdev-acab532-JIT) | python/acab53212d89b298ba0d | acab532 (JIT) |  |  |  | 1.091x ↑<br>[📄](results/bm-20261110-3.16.0a2%2Bdev-acab532-JIT/bm-20261110-ripley-x86_64-python-acab53212d89b298ba0d-3.16.0a2%2Bdev-acab532-vs-base.md)[📈](results/bm-20261110-3.16.0a2%2Bdev-acab532-JIT/bm-20261110-ripley-x86_64-python-acab53212d89b298ba0d-3.16.0a2%2Bdev-acab532-vs-base.svg)[🧠](results/bm-20261110-3.16.0a2%2Bdev-acab532-JIT/bm-20261110-ripley-x86_64-python-acab53212d89b298ba0d-3.16.0a2%2Bdev-acab532-vs-base-mem.svg) |
| [2026-11-10](results/bm-20261110-3.16.0a2%2Bdev-acab532) | python/acab53212d89b298ba0d | acab532 |  |  |  |  |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-e891a91-JIT) | python/e891a9117985888df3e5 | e891a91 (JIT) |  |  |  | 1.087x ↑<br>[📄](results/bm-20261109-3.16.0a1%2Bdev-e891a91-JIT/bm-20261109-ripley-x86_64-python-e891a9117985888df3e5-3.16.0a1%2Bdev-e891a91-vs-base.md)[📈](results/bm-20261109-3.16.0a1%2Bdev-e891a91-JIT/bm-20261109-ripley-x86_64-python-e891a9117985888df3e5-3.16.0a1%2Bdev-e891a91-vs-base.svg)[🧠](results/bm-20261109-3.16.0a1%2Bdev-e891a91-JIT/bm-20261109-ripley-x86_64-python-e891a9117985888df3e5-3.16.0a1%2Bdev-e891a91-vs-base-mem.svg) |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-e891a91) | python/e891a9117985888df3e5 | e891a91 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-11-12](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-TAILCALL) | python/eb21dea301df801352ac | eb21dea (TAILCALL) |  |  |  |  |
| [2026-11-12](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-JIT%2CTAILCALL) | python/eb21dea301df801352ac | eb21dea (JIT) (TAILCALL) |  |  |  |  |
| [2026-11-10](results/bm-20261110-3.16.0a2%2Bdev-acab532-TAILCALL) | python/acab53212d89b298ba0d | acab532 (TAILCALL) |  |  |  |  |
| [2026-11-10](results/bm-20261110-3.16.0a2%2Bdev-acab532-JIT%2CTAILCALL) | python/acab53212d89b298ba0d | acab532 (JIT) (TAILCALL) |  |  |  |  |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-e891a91-TAILCALL) | python/e891a9117985888df3e5 | e891a91 (TAILCALL) |  |  |  |  |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-e891a91-JIT%2CTAILCALL) | python/e891a9117985888df3e5 | e891a91 (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-11-12](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-TAILCALL) | python/eb21dea301df801352ac | eb21dea (TAILCALL) |  |  |  |  |
| [2026-11-12](results/bm-20261112-3.16.0a2%2Bdev-eb21dea-JIT%2CTAILCALL) | python/eb21dea301df801352ac | eb21dea (JIT) (TAILCALL) |  |  |  |  |
| [2026-11-10](results/bm-20261110-3.16.0a2%2Bdev-acab532-TAILCALL) | python/acab53212d89b298ba0d | acab532 (TAILCALL) |  |  |  |  |
| [2026-11-10](results/bm-20261110-3.16.0a2%2Bdev-acab532-JIT%2CTAILCALL) | python/acab53212d89b298ba0d | acab532 (JIT) (TAILCALL) |  |  |  |  |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-e891a91-TAILCALL) | python/e891a9117985888df3e5 | e891a91 (TAILCALL) |  |  |  |  |
| [2026-11-09](results/bm-20261109-3.16.0a1%2Bdev-e891a91-JIT%2CTAILCALL) | python/e891a9117985888df3e5 | e891a91 (JIT) (TAILCALL) |  |  |  |  |


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
