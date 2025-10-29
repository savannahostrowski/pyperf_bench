# Benchmark results

<!-- START table -->

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-10-25](results/bm-20251025-3.15.0a1%2B-421a475-JIT) | python/421a475c87771d46752c | 421a475 (JIT) |  |  |  | 1.025x ↓<br>[📄](results/bm-20251025-3.15.0a1%2B-421a475-JIT/bm-20251025-blueberry-aarch64-python-421a475c87771d46752c-3.15.0a1%2B-421a475-vs-base.md)[📈](results/bm-20251025-3.15.0a1%2B-421a475-JIT/bm-20251025-blueberry-aarch64-python-421a475c87771d46752c-3.15.0a1%2B-421a475-vs-base.svg)[🧠](results/bm-20251025-3.15.0a1%2B-421a475-JIT/bm-20251025-blueberry-aarch64-python-421a475c87771d46752c-3.15.0a1%2B-421a475-vs-base-mem.svg) |
| [2025-10-25](results/bm-20251025-3.15.0a1%2B-421a475) | python/421a475c87771d46752c | 421a475 |  |  |  |  |
| [2025-10-19](results/bm-20251019-3.15.0a1%2B-bedaea0) | python/bedaea05987738c4c6b9 | bedaea0 |  |  |  |  |
| [2025-10-12](results/bm-20251012-3.15.0a0-d6dd64a) | python/d6dd64ac654898b4ce71 | d6dd64a |  |  |  |  |
| [2025-10-04](results/bm-20251004-3.15.0a0-880c952) | python/880c9526f91960b9cba5 | 880c952 |  |  |  |  |
| [2025-10-04](results/bm-20251004-3.15.0a0-9964320) | python/main | 9964320 |  |  |  |  |
| [2025-10-05](results/bm-20251005-3.13.7%2B-ac853ec) | python/3.13 | ac853ec |  |  |  |  |
| [2025-08-14](results/bm-20250814-3.13.7-bcee1c3) | python/v3.13.7 | bcee1c3 |  |  |  |  |


<!-- END table -->

`*` indicates that the exact same versions of pyperformance was not used.
