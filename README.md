# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

[Currently failing benchmarks](failures.md).

**Key:** 📄: table, 📈: time plot, 🧠: memory plot

<!-- START table -->
- [Most recent  pystats on main (db3e990)](results/bm-20260417-3.15.0a8%2B-db3e990/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (db3e990)](results/bm-20260417-3.15.0a8%2B-db3e990-PYTHON_UOPS/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT) | python/db3e990b98fd12fee1bf | db3e990 (JIT) |  |  |  | 1.010x ↑<br>[📄](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.md)[📈](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.svg)[🧠](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-blueberry-aarch64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base-mem.svg) |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990) | python/db3e990b98fd12fee1bf | db3e990 |  |  |  |  |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee-JIT) | python/2faceeec5c0fb06498a9 | 2faceee (JIT) |  |  |  | 1.012x ↑<br>[📄](results/bm-20260416-3.15.0a8%2B-2faceee-JIT/bm-20260416-blueberry-aarch64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.md)[📈](results/bm-20260416-3.15.0a8%2B-2faceee-JIT/bm-20260416-blueberry-aarch64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.svg)[🧠](results/bm-20260416-3.15.0a8%2B-2faceee-JIT/bm-20260416-blueberry-aarch64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base-mem.svg) |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee) | python/2faceeec5c0fb06498a9 | 2faceee |  |  |  |  |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee-JIT) | python/54607eec34b42d377a12 | 54607ee (JIT) |  |  |  | 1.002x ↑<br>[📄](results/bm-20260415-3.15.0a8%2B-54607ee-JIT/bm-20260415-blueberry-aarch64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.md)[📈](results/bm-20260415-3.15.0a8%2B-54607ee-JIT/bm-20260415-blueberry-aarch64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.svg)[🧠](results/bm-20260415-3.15.0a8%2B-54607ee-JIT/bm-20260415-blueberry-aarch64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base-mem.svg) |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee) | python/54607eec34b42d377a12 | 54607ee |  |  |  |  |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT) | python/5c3decad66bdef425ea0 | 5c3deca (JIT) |  |  |  | 1.006x ↑<br>[📄](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT/bm-20260414-blueberry-aarch64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.md)[📈](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT/bm-20260414-blueberry-aarch64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.svg)[🧠](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT/bm-20260414-blueberry-aarch64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base-mem.svg) |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca) | python/5c3decad66bdef425ea0 | 5c3deca |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT) | python/db3e990b98fd12fee1bf | db3e990 (JIT) |  |  |  | 1.080x ↑<br>[📄](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.md)[📈](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base.svg)[🧠](results/bm-20260417-3.15.0a8%2B-db3e990-JIT/bm-20260417-ripley-x86_64-python-db3e990b98fd12fee1bf-3.15.0a8%2B-db3e990-vs-base-mem.svg) |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990) | python/db3e990b98fd12fee1bf | db3e990 |  |  |  |  |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee-JIT) | python/2faceeec5c0fb06498a9 | 2faceee (JIT) |  |  |  | 1.076x ↑<br>[📄](results/bm-20260416-3.15.0a8%2B-2faceee-JIT/bm-20260416-ripley-x86_64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.md)[📈](results/bm-20260416-3.15.0a8%2B-2faceee-JIT/bm-20260416-ripley-x86_64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base.svg)[🧠](results/bm-20260416-3.15.0a8%2B-2faceee-JIT/bm-20260416-ripley-x86_64-python-2faceeec5c0fb06498a9-3.15.0a8%2B-2faceee-vs-base-mem.svg) |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee) | python/2faceeec5c0fb06498a9 | 2faceee |  |  |  |  |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee-JIT) | python/54607eec34b42d377a12 | 54607ee (JIT) |  |  |  | 1.084x ↑<br>[📄](results/bm-20260415-3.15.0a8%2B-54607ee-JIT/bm-20260415-ripley-x86_64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.md)[📈](results/bm-20260415-3.15.0a8%2B-54607ee-JIT/bm-20260415-ripley-x86_64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base.svg)[🧠](results/bm-20260415-3.15.0a8%2B-54607ee-JIT/bm-20260415-ripley-x86_64-python-54607eec34b42d377a12-3.15.0a8%2B-54607ee-vs-base-mem.svg) |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee) | python/54607eec34b42d377a12 | 54607ee |  |  |  |  |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT) | python/5c3decad66bdef425ea0 | 5c3deca (JIT) |  |  |  | 1.084x ↑<br>[📄](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT/bm-20260414-ripley-x86_64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.md)[📈](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT/bm-20260414-ripley-x86_64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base.svg)[🧠](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT/bm-20260414-ripley-x86_64-python-5c3decad66bdef425ea0-3.15.0a8%2B-5c3deca-vs-base-mem.svg) |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca) | python/5c3decad66bdef425ea0 | 5c3deca |  |  |  |  |

## windows amd64 (prometheus)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-TAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (TAILCALL) |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT%2CTAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee-TAILCALL) | python/2faceeec5c0fb06498a9 | 2faceee (TAILCALL) |  |  |  |  |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee-JIT%2CTAILCALL) | python/2faceeec5c0fb06498a9 | 2faceee (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee-TAILCALL) | python/54607eec34b42d377a12 | 54607ee (TAILCALL) |  |  |  |  |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee-JIT%2CTAILCALL) | python/54607eec34b42d377a12 | 54607ee (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca-TAILCALL) | python/5c3decad66bdef425ea0 | 5c3deca (TAILCALL) |  |  |  |  |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT%2CTAILCALL) | python/5c3decad66bdef425ea0 | 5c3deca (JIT) (TAILCALL) |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-TAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (TAILCALL) |  |  |  |  |
| [2026-04-17](results/bm-20260417-3.15.0a8%2B-db3e990-JIT%2CTAILCALL) | python/db3e990b98fd12fee1bf | db3e990 (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee-TAILCALL) | python/2faceeec5c0fb06498a9 | 2faceee (TAILCALL) |  |  |  |  |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-2faceee-JIT%2CTAILCALL) | python/2faceeec5c0fb06498a9 | 2faceee (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-16](results/bm-20260416-3.15.0a8%2B-cecf564-JIT) | python/main | cecf564 (JIT) |  |  |  |  |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee-TAILCALL) | python/54607eec34b42d377a12 | 54607ee (TAILCALL) |  |  |  |  |
| [2026-04-15](results/bm-20260415-3.15.0a8%2B-54607ee-JIT%2CTAILCALL) | python/54607eec34b42d377a12 | 54607ee (JIT) (TAILCALL) |  |  |  |  |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca-TAILCALL) | python/5c3decad66bdef425ea0 | 5c3deca (TAILCALL) |  |  |  |  |
| [2026-04-14](results/bm-20260414-3.15.0a8%2B-5c3deca-JIT%2CTAILCALL) | python/5c3decad66bdef425ea0 | 5c3deca (JIT) (TAILCALL) |  |  |  |  |


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
