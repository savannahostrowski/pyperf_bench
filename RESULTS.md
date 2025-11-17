# Benchmark results

<!-- START table -->
- [Most recent  pystats on main (ed73c90)](results/bm-20251115-3.15.0a1%2B-ed73c90/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (ed73c90)](results/bm-20251115-3.15.0a1%2B-ed73c90-PYTHON_UOPS/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-16](results/bm-20251116-3.15.0a1%2B-b748f45-JIT) | Fidget-Spinner/llvm_19 | b748f45 (JIT) |  |  |  |  |
| [2025-11-16](results/bm-20251116-3.15.0a1%2B-5348c20-JIT) | python/5348c200f5b26d6dd21d | 5348c20 (JIT) |  |  |  | 1.076x ↓<br>[📄](results/bm-20251116-3.15.0a1%2B-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1%2B-5348c20-vs-base.md)[📈](results/bm-20251116-3.15.0a1%2B-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1%2B-5348c20-vs-base.svg)[🧠](results/bm-20251116-3.15.0a1%2B-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1%2B-5348c20-vs-base-mem.svg) |
| [2025-11-16](results/bm-20251116-3.15.0a1%2B-5348c20) | python/5348c200f5b26d6dd21d | 5348c20 |  |  |  |  |
| [2025-11-15](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT) | python/ed73c909f278a1eb558b | ed73c90 (JIT) |  |  |  | 1.082x ↓<br>[📄](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-vs-base.md)[📈](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-vs-base.svg)[🧠](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-vs-base-mem.svg) |
| [2025-11-15](results/bm-20251115-3.15.0a1%2B-ed73c90) | python/ed73c909f278a1eb558b | ed73c90 |  |  |  |  |
| [2025-10-25](results/bm-20251025-3.15.0a1%2B-421a475) | python/421a475c87771d46752c | 421a475 |  |  |  |  |
| [2025-10-19](results/bm-20251019-3.15.0a1%2B-bedaea0) | python/bedaea05987738c4c6b9 | bedaea0 |  |  |  |  |
| [2025-10-12](results/bm-20251012-3.15.0a0-d6dd64a) | python/d6dd64ac654898b4ce71 | d6dd64a |  |  |  |  |
| [2025-10-04](results/bm-20251004-3.15.0a0-880c952) | python/880c9526f91960b9cba5 | 880c952 |  |  |  |  |
| [2025-10-04](results/bm-20251004-3.15.0a0-9964320) | python/main | 9964320 |  |  |  |  |
| [2025-08-02](results/bm-20250802-3.15.0a0-801cf3f-JIT) | Fidget-Spinner/last_good_arm_commit | 801cf3f (JIT) |  |  |  |  |
| [2025-08-02](results/bm-20250802-3.15.0a0-801cf3f) | Fidget-Spinner/last_good_arm_commit | 801cf3f |  |  |  |  |
| [2025-10-05](results/bm-20251005-3.13.7%2B-ac853ec) | python/3.13 | ac853ec |  |  |  |  |
| [2025-08-14](results/bm-20250814-3.13.7-bcee1c3) | python/v3.13.7 | bcee1c3 |  |  |  |  |


<!-- END table -->

`*` indicates that the exact same versions of pyperformance was not used.
