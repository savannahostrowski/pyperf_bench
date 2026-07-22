# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (1f649fe)](results/bm-20260720-3.16.0a0-1f649fe/bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (1f649fe)](results/bm-20260720-3.16.0a0-1f649fe-PYTHON_UOPS/bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f649fe-JIT) | python/1f649fecb645d70b9c48 | 1f649fe (JIT) |  |  |  | 1.010x ↓<br>[📄](results/bm-20260720-3.16.0a0-1f649fe-JIT/bm-20260720-blueberry-aarch64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.md)[📈](results/bm-20260720-3.16.0a0-1f649fe-JIT/bm-20260720-blueberry-aarch64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.svg)[🧠](results/bm-20260720-3.16.0a0-1f649fe-JIT/bm-20260720-blueberry-aarch64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base-mem.svg) |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f649fe) | python/1f649fecb645d70b9c48 | 1f649fe |  |  |  |  |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f9d20b-JIT) | python/1f9d20bbd4fed601e7ca | 1f9d20b (JIT) |  |  |  | 1.001x ↓<br>[📄](results/bm-20260720-3.16.0a0-1f9d20b-JIT/bm-20260720-blueberry-aarch64-python-1f9d20bbd4fed601e7ca-3.16.0a0-1f9d20b-vs-base.md)[📈](results/bm-20260720-3.16.0a0-1f9d20b-JIT/bm-20260720-blueberry-aarch64-python-1f9d20bbd4fed601e7ca-3.16.0a0-1f9d20b-vs-base.svg)[🧠](results/bm-20260720-3.16.0a0-1f9d20b-JIT/bm-20260720-blueberry-aarch64-python-1f9d20bbd4fed601e7ca-3.16.0a0-1f9d20b-vs-base-mem.svg) |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f9d20b) | python/1f9d20bbd4fed601e7ca | 1f9d20b |  |  |  |  |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804-JIT) | python/a1d580430c81c298d267 | a1d5804 (JIT) |  |  |  | 1.001x ↓<br>[📄](results/bm-20260718-3.16.0a0-a1d5804-JIT/bm-20260718-blueberry-aarch64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.md)[📈](results/bm-20260718-3.16.0a0-a1d5804-JIT/bm-20260718-blueberry-aarch64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.svg)[🧠](results/bm-20260718-3.16.0a0-a1d5804-JIT/bm-20260718-blueberry-aarch64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base-mem.svg) |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804) | python/a1d580430c81c298d267 | a1d5804 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f649fe-JIT) | python/1f649fecb645d70b9c48 | 1f649fe (JIT) |  |  |  | 1.070x ↑<br>[📄](results/bm-20260720-3.16.0a0-1f649fe-JIT/bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.md)[📈](results/bm-20260720-3.16.0a0-1f649fe-JIT/bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base.svg)[🧠](results/bm-20260720-3.16.0a0-1f649fe-JIT/bm-20260720-ripley-x86_64-python-1f649fecb645d70b9c48-3.16.0a0-1f649fe-vs-base-mem.svg) |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f649fe) | python/1f649fecb645d70b9c48 | 1f649fe |  |  |  |  |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f9d20b-JIT) | python/1f9d20bbd4fed601e7ca | 1f9d20b (JIT) |  |  |  | 1.079x ↑<br>[📄](results/bm-20260720-3.16.0a0-1f9d20b-JIT/bm-20260720-ripley-x86_64-python-1f9d20bbd4fed601e7ca-3.16.0a0-1f9d20b-vs-base.md)[📈](results/bm-20260720-3.16.0a0-1f9d20b-JIT/bm-20260720-ripley-x86_64-python-1f9d20bbd4fed601e7ca-3.16.0a0-1f9d20b-vs-base.svg)[🧠](results/bm-20260720-3.16.0a0-1f9d20b-JIT/bm-20260720-ripley-x86_64-python-1f9d20bbd4fed601e7ca-3.16.0a0-1f9d20b-vs-base-mem.svg) |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f9d20b) | python/1f9d20bbd4fed601e7ca | 1f9d20b |  |  |  |  |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804-JIT) | python/a1d580430c81c298d267 | a1d5804 (JIT) |  |  |  | 1.065x ↑<br>[📄](results/bm-20260718-3.16.0a0-a1d5804-JIT/bm-20260718-ripley-x86_64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.md)[📈](results/bm-20260718-3.16.0a0-a1d5804-JIT/bm-20260718-ripley-x86_64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base.svg)[🧠](results/bm-20260718-3.16.0a0-a1d5804-JIT/bm-20260718-ripley-x86_64-python-a1d580430c81c298d267-3.16.0a0-a1d5804-vs-base-mem.svg) |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804) | python/a1d580430c81c298d267 | a1d5804 |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f649fe-TAILCALL) | python/1f649fecb645d70b9c48 | 1f649fe (TAILCALL) |  |  |  |  |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f649fe-JIT%2CTAILCALL) | python/1f649fecb645d70b9c48 | 1f649fe (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f9d20b-TAILCALL) | python/1f9d20bbd4fed601e7ca | 1f9d20b (TAILCALL) |  |  |  |  |
| [2026-07-20](results/bm-20260720-3.16.0a0-1f9d20b-JIT%2CTAILCALL) | python/1f9d20bbd4fed601e7ca | 1f9d20b (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804-TAILCALL) | python/a1d580430c81c298d267 | a1d5804 (TAILCALL) |  |  |  |  |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804-JIT%2CTAILCALL) | python/a1d580430c81c298d267 | a1d5804 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-09](results/bm-20260709-3.16.0a0-b2d8db1-TAILCALL) | python/b2d8db1ac818e74ffe66 | b2d8db1 (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804-TAILCALL) | python/a1d580430c81c298d267 | a1d5804 (TAILCALL) |  |  |  |  |
| [2026-07-18](results/bm-20260718-3.16.0a0-a1d5804-JIT%2CTAILCALL) | python/a1d580430c81c298d267 | a1d5804 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-18](results/bm-20260718-3.16.0a0-16d0c89-TAILCALL) | python/16d0c89b875c520cf5af | 16d0c89 (TAILCALL) |  |  |  |  |
| [2026-07-18](results/bm-20260718-3.16.0a0-16d0c89-JIT%2CTAILCALL) | python/16d0c89b875c520cf5af | 16d0c89 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-16](results/bm-20260716-3.16.0a0-f62050d-TAILCALL) | python/f62050d65743f0c895f7 | f62050d (TAILCALL) |  |  |  |  |
| [2026-07-16](results/bm-20260716-3.16.0a0-f62050d-JIT%2CTAILCALL) | python/f62050d65743f0c895f7 | f62050d (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-15](results/bm-20260715-3.16.0a0-b4662e8-TAILCALL) | python/b4662e8e3b60a2644861 | b4662e8 (TAILCALL) |  |  |  |  |
| [2026-07-15](results/bm-20260715-3.16.0a0-b4662e8-JIT%2CTAILCALL) | python/b4662e8e3b60a2644861 | b4662e8 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-14](results/bm-20260714-3.16.0a0-b704b64-TAILCALL) | python/b704b647b2295924ebaf | b704b64 (TAILCALL) |  |  |  |  |
| [2026-07-14](results/bm-20260714-3.16.0a0-b704b64-JIT%2CTAILCALL) | python/b704b647b2295924ebaf | b704b64 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-14](results/bm-20260714-3.16.0a0-2dc1a91-TAILCALL) | python/2dc1a91af801ea896e21 | 2dc1a91 (TAILCALL) |  |  |  |  |
| [2026-07-14](results/bm-20260714-3.16.0a0-2dc1a91-JIT%2CTAILCALL) | python/2dc1a91af801ea896e21 | 2dc1a91 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-12](results/bm-20260712-3.16.0a0-832bc0b-TAILCALL) | python/832bc0b0ea20c2fade5d | 832bc0b (TAILCALL) |  |  |  |  |
| [2026-07-12](results/bm-20260712-3.16.0a0-832bc0b-JIT%2CTAILCALL) | python/832bc0b0ea20c2fade5d | 832bc0b (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-11](results/bm-20260711-3.16.0a0-0023d5b-TAILCALL) | python/0023d5b23df09f18425f | 0023d5b (TAILCALL) |  |  |  |  |
| [2026-07-11](results/bm-20260711-3.16.0a0-0023d5b-JIT%2CTAILCALL) | python/0023d5b23df09f18425f | 0023d5b (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-10](results/bm-20260710-3.16.0a0-c22e9c9-TAILCALL) | python/c22e9c9daef4d97a3fdf | c22e9c9 (TAILCALL) |  |  |  |  |
| [2026-07-10](results/bm-20260710-3.16.0a0-c22e9c9-JIT%2CTAILCALL) | python/c22e9c9daef4d97a3fdf | c22e9c9 (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-10](results/bm-20260710-3.16.0a0-1b41c7b-TAILCALL) | python/1b41c7b722b77d9c02c6 | 1b41c7b (TAILCALL) |  |  |  |  |
| [2026-07-10](results/bm-20260710-3.16.0a0-1b41c7b-JIT%2CTAILCALL) | python/1b41c7b722b77d9c02c6 | 1b41c7b (JIT) (TAILCALL) |  |  |  |  |
| [2026-07-09](results/bm-20260709-3.16.0a0-b2d8db1-TAILCALL) | python/b2d8db1ac818e74ffe66 | b2d8db1 (TAILCALL) |  |  |  |  |
| [2026-07-09](results/bm-20260709-3.16.0a0-b2d8db1-JIT%2CTAILCALL) | python/b2d8db1ac818e74ffe66 | b2d8db1 (JIT) (TAILCALL) |  |  |  |  |


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
