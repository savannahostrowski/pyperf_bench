# Benchmark results

<!-- START table -->
- [Most recent  pystats on main (425f24e)](results/bm-20251123-3.15.0a2%2B-425f24e/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2%2B-425f24e-pystats.md)
- [Most recent PYTHON_UOPS pystats on main (425f24e)](results/bm-20251123-3.15.0a2%2B-425f24e-PYTHON_UOPS/bm-20251123-blueberry-aarch64-python-425f24e4fad672c21130-3.15.0a2%2B-425f24e-pystats.md)

## unknown x86_64 (linux)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python/v3.10.4 | 9d38120 |  |  |  |  |

## linux aarch64 (blueberry)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-23](results/bm-20251123-3.15.0a2%2B-425f24e) | python/425f24e4fad672c21130 | 425f24e |  |  |  |  |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT) | python/227b9d326ec7eba35942 | 227b9d3 (JIT) |  |  |  | 1.022x ↓<br>[📄](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT/bm-20251122-blueberry-aarch64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.md)[📈](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT/bm-20251122-blueberry-aarch64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.svg)[🧠](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT/bm-20251122-blueberry-aarch64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base-mem.svg) |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-227b9d3) | python/227b9d326ec7eba35942 | 227b9d3 |  |  |  |  |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT) | python/cde19e565cc9127fe5db | cde19e5 (JIT) |  |  |  | 1.047x ↑<br>[📄](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT/bm-20251122-blueberry-aarch64-python-cde19e565cc9127fe5db-3.15.0a2%2B-cde19e5-vs-base.md)[📈](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT/bm-20251122-blueberry-aarch64-python-cde19e565cc9127fe5db-3.15.0a2%2B-cde19e5-vs-base.svg)[🧠](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT/bm-20251122-blueberry-aarch64-python-cde19e565cc9127fe5db-3.15.0a2%2B-cde19e5-vs-base-mem.svg) |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-cde19e5) | python/cde19e565cc9127fe5db | cde19e5 |  |  |  |  |
| [2025-11-21](results/bm-20251121-3.15.0a2%2B-92972ae-JIT) | python/92972aea0f0e12dd21bf | 92972ae (JIT) |  |  |  | 1.035x ↓<br>[📄](results/bm-20251121-3.15.0a2%2B-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2%2B-92972ae-vs-base.md)[📈](results/bm-20251121-3.15.0a2%2B-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2%2B-92972ae-vs-base.svg)[🧠](results/bm-20251121-3.15.0a2%2B-92972ae-JIT/bm-20251121-blueberry-aarch64-python-92972aea0f0e12dd21bf-3.15.0a2%2B-92972ae-vs-base-mem.svg) |
| [2025-11-21](results/bm-20251121-3.15.0a2%2B-92972ae) | python/92972aea0f0e12dd21bf | 92972ae |  |  |  |  |
| [2025-11-20](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT) | python/77cb39e0c7ef606ef68a | 77cb39e (JIT) |  |  |  | 1.066x ↓<br>[📄](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.md)[📈](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.svg)[🧠](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT/bm-20251120-blueberry-aarch64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base-mem.svg) |
| [2025-11-20](results/bm-20251120-3.15.0a2%2B-77cb39e) | python/77cb39e0c7ef606ef68a | 77cb39e |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT) | python/ca1e86f9d963dc298d9a | ca1e86f (JIT) |  |  |  | 1.073x ↓<br>[📄](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-blueberry-aarch64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f) | python/ca1e86f9d963dc298d9a | ca1e86f |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT) | python/b3b63e8d6d296b879fdd | b3b63e8 (JIT) |  |  |  | 1.027x ↓<br>[📄](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-blueberry-aarch64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8) | python/b3b63e8d6d296b879fdd | b3b63e8 |  |  |  |  |
| [2025-11-20](results/bm-20251120-3.15.0a1%2B-66a12ad-JIT) | Fidget-Spinner/jit_lower_trace_limi | 66a12ad (JIT) |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT) | python/7b0b70867586ef7109de | 7b0b708 (JIT) |  |  |  | 1.103x ↓<br>[📄](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT/bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base.md)[📈](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT/bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base.svg)[🧠](results/bm-20251119-3.15.0a1%2B-7b0b708-JIT/bm-20251119-blueberry-aarch64-python-7b0b70867586ef7109de-3.15.0a1%2B-7b0b708-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a1%2B-7b0b708) | python/7b0b70867586ef7109de | 7b0b708 |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a1%2B-652c764-JIT) | python/652c764a59913327b28b | 652c764 (JIT) |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-1f50f61-TAILCALL) | Fidget-Spinner/jit_lower_trace_limi | 1f50f61 (TAILCALL) |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-1f50f61-JIT%2CTAILCALL) | Fidget-Spinner/jit_lower_trace_limi | 1f50f61 (JIT) (TAILCALL) |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-1f50f61-JIT) | Fidget-Spinner/jit_lower_trace_limi | 1f50f61 (JIT) |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-1f50f61) | Fidget-Spinner/jit_lower_trace_limi | 1f50f61 |  |  |  |  |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT) | python/4695ec109d07c9bfd9eb | 4695ec1 (JIT) |  |  |  | 1.053x ↓<br>[📄](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT/bm-20251118-blueberry-aarch64-python-4695ec109d07c9bfd9eb-3.15.0a1%2B-4695ec1-vs-base.md)[📈](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT/bm-20251118-blueberry-aarch64-python-4695ec109d07c9bfd9eb-3.15.0a1%2B-4695ec1-vs-base.svg)[🧠](results/bm-20251118-3.15.0a1%2B-4695ec1-JIT/bm-20251118-blueberry-aarch64-python-4695ec109d07c9bfd9eb-3.15.0a1%2B-4695ec1-vs-base-mem.svg) |
| [2025-11-18](results/bm-20251118-3.15.0a1%2B-4695ec1) | python/4695ec109d07c9bfd9eb | 4695ec1 |  |  |  |  |
| [2025-11-17](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT) | python/5d2eb98a91f2cd703d14 | 5d2eb98 (JIT) |  |  |  | 1.067x ↓<br>[📄](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT/bm-20251117-blueberry-aarch64-python-5d2eb98a91f2cd703d14-3.15.0a1%2B-5d2eb98-vs-base.md)[📈](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT/bm-20251117-blueberry-aarch64-python-5d2eb98a91f2cd703d14-3.15.0a1%2B-5d2eb98-vs-base.svg)[🧠](results/bm-20251117-3.15.0a1%2B-5d2eb98-JIT/bm-20251117-blueberry-aarch64-python-5d2eb98a91f2cd703d14-3.15.0a1%2B-5d2eb98-vs-base-mem.svg) |
| [2025-11-17](results/bm-20251117-3.15.0a1%2B-5d2eb98) | python/5d2eb98a91f2cd703d14 | 5d2eb98 |  |  |  |  |
| [2025-11-17](results/bm-20251117-3.15.0a1%2B-16ea950-JIT) | python/16ea9505ce690485bab3 | 16ea950 (JIT) |  |  |  |  |
| [2025-11-16](results/bm-20251116-3.15.0a1%2B-b748f45-JIT) | Fidget-Spinner/llvm_19 | b748f45 (JIT) |  |  |  |  |
| [2025-11-16](results/bm-20251116-3.15.0a1%2B-5348c20-JIT) | python/5348c200f5b26d6dd21d | 5348c20 (JIT) |  |  |  | 1.076x ↓<br>[📄](results/bm-20251116-3.15.0a1%2B-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1%2B-5348c20-vs-base.md)[📈](results/bm-20251116-3.15.0a1%2B-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1%2B-5348c20-vs-base.svg)[🧠](results/bm-20251116-3.15.0a1%2B-5348c20-JIT/bm-20251116-blueberry-aarch64-python-5348c200f5b26d6dd21d-3.15.0a1%2B-5348c20-vs-base-mem.svg) |
| [2025-11-16](results/bm-20251116-3.15.0a1%2B-5348c20) | python/5348c200f5b26d6dd21d | 5348c20 |  |  |  |  |
| [2025-11-15](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT) | python/ed73c909f278a1eb558b | ed73c90 (JIT) |  |  |  | 1.082x ↓<br>[📄](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-vs-base.md)[📈](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-vs-base.svg)[🧠](results/bm-20251115-3.15.0a1%2B-ed73c90-JIT/bm-20251115-blueberry-aarch64-python-ed73c909f278a1eb558b-3.15.0a1%2B-ed73c90-vs-base-mem.svg) |
| [2025-11-15](results/bm-20251115-3.15.0a1%2B-ed73c90) | python/ed73c909f278a1eb558b | ed73c90 |  |  |  |  |
| [2025-11-13](results/bm-20251113-3.15.0a1%2B-196f151-JIT) | python/196f1519cd2d8134d764 | 196f151 (JIT) |  |  |  | 1.009x ↑<br>[📄](results/bm-20251113-3.15.0a1%2B-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1%2B-196f151-vs-base.md)[📈](results/bm-20251113-3.15.0a1%2B-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1%2B-196f151-vs-base.svg)[🧠](results/bm-20251113-3.15.0a1%2B-196f151-JIT/bm-20251113-blueberry-aarch64-python-196f1519cd2d8134d764-3.15.0a1%2B-196f151-vs-base-mem.svg) |
| [2025-11-13](results/bm-20251113-3.15.0a1%2B-196f151) | python/196f1519cd2d8134d764 | 196f151 |  |  |  |  |
| [2025-10-25](results/bm-20251025-3.15.0a1%2B-421a475) | python/421a475c87771d46752c | 421a475 |  |  |  |  |
| [2025-10-19](results/bm-20251019-3.15.0a1%2B-bedaea0) | python/bedaea05987738c4c6b9 | bedaea0 |  |  |  |  |
| [2025-10-12](results/bm-20251012-3.15.0a0-d6dd64a) | python/d6dd64ac654898b4ce71 | d6dd64a |  |  |  |  |
| [2025-10-04](results/bm-20251004-3.15.0a0-880c952) | python/880c9526f91960b9cba5 | 880c952 |  |  |  |  |
| [2025-10-04](results/bm-20251004-3.15.0a0-9964320) | python/main | 9964320 |  |  |  |  |
| [2025-08-02](results/bm-20250802-3.15.0a0-801cf3f-JIT) | Fidget-Spinner/last_good_arm_commit | 801cf3f (JIT) |  |  |  |  |
| [2025-08-02](results/bm-20250802-3.15.0a0-801cf3f) | Fidget-Spinner/last_good_arm_commit | 801cf3f |  |  |  |  |
| [2025-10-05](results/bm-20251005-3.13.7%2B-ac853ec) | python/3.13 | ac853ec |  |  |  |  |
| [2025-08-14](results/bm-20250814-3.13.7-bcee1c3) | python/v3.13.7 | bcee1c3 |  |  |  |  |

## linux x86_64 (ripley)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-23](results/bm-20251123-3.15.0a2%2B-425f24e-JIT) | python/425f24e4fad672c21130 | 425f24e (JIT) |  |  |  | 1.048x ↑<br>[📄](results/bm-20251123-3.15.0a2%2B-425f24e-JIT/bm-20251123-ripley-x86_64-python-425f24e4fad672c21130-3.15.0a2%2B-425f24e-vs-base.md)[📈](results/bm-20251123-3.15.0a2%2B-425f24e-JIT/bm-20251123-ripley-x86_64-python-425f24e4fad672c21130-3.15.0a2%2B-425f24e-vs-base.svg)[🧠](results/bm-20251123-3.15.0a2%2B-425f24e-JIT/bm-20251123-ripley-x86_64-python-425f24e4fad672c21130-3.15.0a2%2B-425f24e-vs-base-mem.svg) |
| [2025-11-23](results/bm-20251123-3.15.0a2%2B-425f24e) | python/425f24e4fad672c21130 | 425f24e |  |  |  |  |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT) | python/227b9d326ec7eba35942 | 227b9d3 (JIT) |  |  |  | 1.052x ↑<br>[📄](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT/bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.md)[📈](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT/bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base.svg)[🧠](results/bm-20251122-3.15.0a2%2B-227b9d3-JIT/bm-20251122-ripley-x86_64-python-227b9d326ec7eba35942-3.15.0a2%2B-227b9d3-vs-base-mem.svg) |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-227b9d3) | python/227b9d326ec7eba35942 | 227b9d3 |  |  |  |  |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT) | python/cde19e565cc9127fe5db | cde19e5 (JIT) |  |  |  | 1.064x ↑<br>[📄](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2%2B-cde19e5-vs-base.md)[📈](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2%2B-cde19e5-vs-base.svg)[🧠](results/bm-20251122-3.15.0a2%2B-cde19e5-JIT/bm-20251122-ripley-x86_64-python-cde19e565cc9127fe5db-3.15.0a2%2B-cde19e5-vs-base-mem.svg) |
| [2025-11-22](results/bm-20251122-3.15.0a2%2B-cde19e5) | python/cde19e565cc9127fe5db | cde19e5 |  |  |  |  |
| [2025-11-21](results/bm-20251121-3.15.0a2%2B-92972ae-JIT) | python/92972aea0f0e12dd21bf | 92972ae (JIT) |  |  |  | 1.049x ↑<br>[📄](results/bm-20251121-3.15.0a2%2B-92972ae-JIT/bm-20251121-ripley-x86_64-python-92972aea0f0e12dd21bf-3.15.0a2%2B-92972ae-vs-base.md)[📈](results/bm-20251121-3.15.0a2%2B-92972ae-JIT/bm-20251121-ripley-x86_64-python-92972aea0f0e12dd21bf-3.15.0a2%2B-92972ae-vs-base.svg)[🧠](results/bm-20251121-3.15.0a2%2B-92972ae-JIT/bm-20251121-ripley-x86_64-python-92972aea0f0e12dd21bf-3.15.0a2%2B-92972ae-vs-base-mem.svg) |
| [2025-11-21](results/bm-20251121-3.15.0a2%2B-92972ae) | python/92972aea0f0e12dd21bf | 92972ae |  |  |  |  |
| [2025-11-20](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT) | python/77cb39e0c7ef606ef68a | 77cb39e (JIT) |  |  |  | 1.010x ↑<br>[📄](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT/bm-20251120-ripley-x86_64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.md)[📈](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT/bm-20251120-ripley-x86_64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base.svg)[🧠](results/bm-20251120-3.15.0a2%2B-77cb39e-JIT/bm-20251120-ripley-x86_64-python-77cb39e0c7ef606ef68a-3.15.0a2%2B-77cb39e-vs-base-mem.svg) |
| [2025-11-20](results/bm-20251120-3.15.0a2%2B-77cb39e) | python/77cb39e0c7ef606ef68a | 77cb39e |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT) | python/ca1e86f9d963dc298d9a | ca1e86f (JIT) |  |  |  | 1.013x ↑<br>[📄](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-ca1e86f-JIT/bm-20251119-ripley-x86_64-python-ca1e86f9d963dc298d9a-3.15.0a2%2B-ca1e86f-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-ca1e86f) | python/ca1e86f9d963dc298d9a | ca1e86f |  |  |  |  |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT) | python/b3b63e8d6d296b879fdd | b3b63e8 (JIT) |  |  |  | 1.005x ↑<br>[📄](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.md)[📈](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base.svg)[🧠](results/bm-20251119-3.15.0a2%2B-b3b63e8-JIT/bm-20251119-ripley-x86_64-python-b3b63e8d6d296b879fdd-3.15.0a2%2B-b3b63e8-vs-base-mem.svg) |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-b3b63e8) | python/b3b63e8d6d296b879fdd | b3b63e8 |  |  |  |  |

## darwin arm64 (jones)
| date | fork/ref | hash/flags | vs. 3.11.0: | vs. 3.12.0: | vs. 3.13.0: | vs. base: |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| [2025-11-19](results/bm-20251119-3.15.0a2%2B-bc9b9d4) | python/main | bc9b9d4 |  |  |  |  |


<!-- END table -->

`*` indicates that the exact same versions of pyperformance was not used.
