# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (e4058d7)](results/bm-20251218-3.15.0a3%2B-e4058d7/bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (e4058d7)](results/bm-20251218-3.15.0a3%2B-e4058d7-PYTHON_UOPS/bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-18](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT) | python/e4058d7cb115286c3c53 | e4058d7 (JIT) |  |  |  | 1.014x ↑<br>[📄](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.md)[📈](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.svg)[🧠](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT/bm-20251218-blueberry-aarch64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base-mem.svg) |
| [2025-12-18](results/bm-20251218-3.15.0a3%2B-e4058d7) | python/e4058d7cb115286c3c53 | e4058d7 |  |  |  |  |
| [2025-12-16](results/bm-20251216-3.15.0a3%2B-89729f2-JIT) | python/89729f2ef7f9473d9e4b | 89729f2 (JIT) |  |  |  | 1.008x ↑<br>[📄](results/bm-20251216-3.15.0a3%2B-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.md)[📈](results/bm-20251216-3.15.0a3%2B-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.svg)[🧠](results/bm-20251216-3.15.0a3%2B-89729f2-JIT/bm-20251216-blueberry-aarch64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base-mem.svg) |
| [2025-12-16](results/bm-20251216-3.15.0a3%2B-89729f2) | python/89729f2ef7f9473d9e4b | 89729f2 |  |  |  |  |
| [2025-12-15](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT) | python/bef63d2fb81ae2876004 | bef63d2 (JIT) |  |  |  | 1.028x ↑<br>[📄](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.md)[📈](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.svg)[🧠](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT/bm-20251215-blueberry-aarch64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base-mem.svg) |
| [2025-12-15](results/bm-20251215-3.15.0a2%2B-bef63d2) | python/bef63d2fb81ae2876004 | bef63d2 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-18](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT) | python/e4058d7cb115286c3c53 | e4058d7 (JIT) |  |  |  | 1.033x ↑<br>[📄](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT/bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.md)[📈](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT/bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base.svg)[🧠](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT/bm-20251218-ripley-x86_64-python-e4058d7cb115286c3c53-3.15.0a3%2B-e4058d7-vs-base-mem.svg) |
| [2025-12-18](results/bm-20251218-3.15.0a3%2B-e4058d7) | python/e4058d7cb115286c3c53 | e4058d7 |  |  |  |  |
| [2025-12-16](results/bm-20251216-3.15.0a3%2B-89729f2-JIT) | python/89729f2ef7f9473d9e4b | 89729f2 (JIT) |  |  |  | 1.029x ↑<br>[📄](results/bm-20251216-3.15.0a3%2B-89729f2-JIT/bm-20251216-ripley-x86_64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.md)[📈](results/bm-20251216-3.15.0a3%2B-89729f2-JIT/bm-20251216-ripley-x86_64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base.svg)[🧠](results/bm-20251216-3.15.0a3%2B-89729f2-JIT/bm-20251216-ripley-x86_64-python-89729f2ef7f9473d9e4b-3.15.0a3%2B-89729f2-vs-base-mem.svg) |
| [2025-12-16](results/bm-20251216-3.15.0a3%2B-89729f2) | python/89729f2ef7f9473d9e4b | 89729f2 |  |  |  |  |
| [2025-12-15](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT) | python/bef63d2fb81ae2876004 | bef63d2 (JIT) |  |  |  | 1.029x ↑<br>[📄](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT/bm-20251215-ripley-x86_64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.md)[📈](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT/bm-20251215-ripley-x86_64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base.svg)[🧠](results/bm-20251215-3.15.0a2%2B-bef63d2-JIT/bm-20251215-ripley-x86_64-python-bef63d2fb81ae2876004-3.15.0a2%2B-bef63d2-vs-base-mem.svg) |
| [2025-12-15](results/bm-20251215-3.15.0a2%2B-bef63d2) | python/bef63d2fb81ae2876004 | bef63d2 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-12-18](results/bm-20251218-3.15.0a3%2B-e4058d7-TAILCALL) | python/e4058d7cb115286c3c53 | e4058d7 (TAILCALL) |  |  |  |  |
| [2025-12-18](results/bm-20251218-3.15.0a3%2B-e4058d7-JIT%2CTAILCALL) | python/e4058d7cb115286c3c53 | e4058d7 (JIT) (TAILCALL) |  |  |  |  |
| [2025-12-16](results/bm-20251216-3.15.0a3%2B-89729f2-TAILCALL) | python/89729f2ef7f9473d9e4b | 89729f2 (TAILCALL) |  |  |  |  |
| [2025-12-16](results/bm-20251216-3.15.0a3%2B-89729f2-JIT%2CTAILCALL) | python/89729f2ef7f9473d9e4b | 89729f2 (JIT) (TAILCALL) |  |  |  |  |


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
