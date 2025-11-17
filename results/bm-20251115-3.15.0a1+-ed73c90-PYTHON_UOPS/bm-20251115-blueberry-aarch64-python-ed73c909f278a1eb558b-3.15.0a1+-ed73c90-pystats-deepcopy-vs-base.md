## Execution counts

<details>
<summary> Execution counts for Tier 1 instructions. </summary>


The "miss ratio" column shows the percentage of times the instruction
executed that it deoptimized. When this happens, the base unspecialized
instruction is not counted.

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Base Count</th>
<th align="right">Head Count</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">30,899,710</td>
<td align="right">429,660</td>
<td align="right">-98.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">19,431,328</td>
<td align="right">1,537,111</td>
<td align="right">-92.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">1,540,023</td>
<td align="right">164,454</td>
<td align="right">-89.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">1,867,683</td>
<td align="right">216,189</td>
<td align="right">-88.4%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">48,298,855</td>
<td align="right">6,071,710</td>
<td align="right">-87.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">48,298,855</td>
<td align="right">6,071,710</td>
<td align="right">-87.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">23,330,218</td>
<td align="right">3,014,079</td>
<td align="right">-87.1%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">93,126,622</td>
<td align="right">12,326,113</td>
<td align="right">-86.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">64,420,203</td>
<td align="right">8,758,548</td>
<td align="right">-86.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">154,811,725</td>
<td align="right">23,862,449</td>
<td align="right">-84.6%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">1,867,683</td>
<td align="right">291,231</td>
<td align="right">-84.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">67,140,176</td>
<td align="right">10,988,134</td>
<td align="right">-83.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">53,246,989</td>
<td align="right">8,853,472</td>
<td align="right">-83.4%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,245,122</td>
<td align="right">208,266</td>
<td align="right">-83.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">622,561</td>
<td align="right">104,133</td>
<td align="right">-83.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">1,998,913</td>
<td align="right">358,574</td>
<td align="right">-82.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">11,046,848</td>
<td align="right">2,048,580</td>
<td align="right">-81.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">405,205,148</td>
<td align="right">76,660,390</td>
<td align="right">-81.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">78,347,465</td>
<td align="right">15,489,093</td>
<td align="right">-80.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">96,891,902</td>
<td align="right">19,303,766</td>
<td align="right">-80.1%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">2,031,492</td>
<td align="right">410,163</td>
<td align="right">-79.8%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">2,031,777</td>
<td align="right">410,446</td>
<td align="right">-79.8%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">2,031,919</td>
<td align="right">410,586</td>
<td align="right">-79.8%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">41,845,126</td>
<td align="right">8,556,380</td>
<td align="right">-79.6%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">5,832,883</td>
<td align="right">1,197,998</td>
<td align="right">-79.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">4,275,886</td>
<td align="right">972,130</td>
<td align="right">-77.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">1,605,784</td>
<td align="right">367,534</td>
<td align="right">-77.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">64,552,206</td>
<td align="right">14,873,257</td>
<td align="right">-77.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">30,932,297</td>
<td align="right">7,312,811</td>
<td align="right">-76.4%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">7,896,807</td>
<td align="right">1,901,611</td>
<td align="right">-75.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">7,896,975</td>
<td align="right">1,901,779</td>
<td align="right">-75.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">32,013,670</td>
<td align="right">7,717,593</td>
<td align="right">-75.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">69,958,201</td>
<td align="right">17,171,513</td>
<td align="right">-75.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">64,061,732</td>
<td align="right">16,185,151</td>
<td align="right">-74.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">7,700,115</td>
<td align="right">1,952,079</td>
<td align="right">-74.6%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">9,895,869</td>
<td align="right">2,512,852</td>
<td align="right">-74.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">4,128,954</td>
<td align="right">1,087,819</td>
<td align="right">-73.7%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">541,397</td>
<td align="right">159,397</td>
<td align="right">-70.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">2,228,102</td>
<td align="right">678,558</td>
<td align="right">-69.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">6,724,158</td>
<td align="right">2,143,093</td>
<td align="right">-68.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">36,966,037</td>
<td align="right">11,820,505</td>
<td align="right">-68.0%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">6,193,178</td>
<td align="right">2,037,718</td>
<td align="right">-67.1%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">4,816,958</td>
<td align="right">1,708,617</td>
<td align="right">-64.5%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">245,724</td>
<td align="right">91,773</td>
<td align="right">-62.7%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">6,062,397</td>
<td align="right">2,382,074</td>
<td align="right">-60.7%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">9,207,692</td>
<td align="right">3,633,760</td>
<td align="right">-60.5%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">5,963,732</td>
<td align="right">2,453,481</td>
<td align="right">-58.9%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">19,463,179</td>
<td align="right">8,422,491</td>
<td align="right">-56.7%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">3,407,685</td>
<td align="right">1,606,452</td>
<td align="right">-52.9%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">131,050</td>
<td align="right">65,514</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">982,938</td>
<td align="right">491,418</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">491,469</td>
<td align="right">245,709</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">491,490</td>
<td align="right">245,730</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">491,490</td>
<td align="right">245,730</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">983,047</td>
<td align="right">491,526</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">491,866</td>
<td align="right">246,104</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">492,020</td>
<td align="right">246,258</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">65,649</td>
<td align="right">32,879</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">5,625,280</td>
<td align="right">2,866,043</td>
<td align="right">-49.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">2,654,212</td>
<td align="right">1,397,860</td>
<td align="right">-47.3%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">4,129,113</td>
<td align="right">2,320,783</td>
<td align="right">-43.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">6,192,830</td>
<td align="right">3,523,245</td>
<td align="right">-43.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,092,173</td>
<td align="right">5,783,331</td>
<td align="right">-42.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">9,731,766</td>
<td align="right">5,751,826</td>
<td align="right">-40.9%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">3,949,238</td>
<td align="right">2,386,944</td>
<td align="right">-39.6%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">2,785,187</td>
<td align="right">1,916,835</td>
<td align="right">-31.2%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">2,785,187</td>
<td align="right">1,916,835</td>
<td align="right">-31.2%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">2,785,187</td>
<td align="right">1,916,835</td>
<td align="right">-31.2%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">3,572,064</td>
<td align="right">2,834,780</td>
<td align="right">-20.6%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">8,192,336</td>
<td align="right">6,717,772</td>
<td align="right">-18.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">3,080,305</td>
<td align="right">2,588,785</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">3,080,506</td>
<td align="right">2,588,984</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">1,540,364</td>
<td align="right">1,294,602</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">1,540,737</td>
<td align="right">1,294,972</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,541,912</td>
<td align="right">1,296,085</td>
<td align="right">-15.9%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">71</td>
<td align="right">70</td>
<td align="right">-1.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">636</td>
<td align="right">628</td>
<td align="right">-1.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">159</td>
<td align="right">157</td>
<td align="right">-1.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">159</td>
<td align="right">157</td>
<td align="right">-1.3%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">106</td>
<td align="right">105</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">376</td>
<td align="right">374</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">782</td>
<td align="right">780</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,048,924</td>
<td align="right">1,048,920</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">2,097,516</td>
<td align="right">2,097,513</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">42,253,610</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">5,334</td>
<td align="right">5,334</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">3,633</td>
<td align="right">3,633</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">945</td>
<td align="right">945</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">714</td>
<td align="right">714</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">616</td>
<td align="right">616</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">399</td>
<td align="right">399</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">336</td>
<td align="right">336</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">77</td>
<td align="right">77</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">77</td>
<td align="right">77</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">77</td>
<td align="right">77</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">56</td>
<td align="right">56</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">4,505,169</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">1,352,533</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 opcode pairs </summary>


Pairs of specialized operations that deoptimize and are then followed by
the corresponding unspecialized instruction are not counted as pairs.

Not included in comparative output.


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each Tier 1 opcode. </summary>


This does not include the unspecialized instructions that occur after a
specialized instruction deoptimizes.

Not included in comparative output.


</details>

## Specialization stats

<details>
<summary> Specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">8,158,924</td>
<td align="right">100.0%</td>
<td align="right">4,506,297</td>
<td align="right">100.0%</td>
<td align="right">-44.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">50</td>
<td align="right">0.0%</td>
<td align="right">49</td>
<td align="right">0.0%</td>
<td align="right">-2.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">442</td>
<td align="right">0.0%</td>
<td align="right">440</td>
<td align="right">0.0%</td>
<td align="right">-0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">294</td>
<td align="right">86.5%</td>
<td align="right">294</td>
<td align="right">86.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">46</td>
<td align="right">13.5%</td>
<td align="right">46</td>
<td align="right">13.5%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">multiply different types</td>
<td align="right">46</td>
<td align="right">100.0%</td>
<td align="right">46</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">205,286,754</td>
<td align="right">99.0%</td>
<td align="right">32,163,039</td>
<td align="right">98.9%</td>
<td align="right">-84.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,106,759</td>
<td align="right">1.0%</td>
<td align="right">359,001</td>
<td align="right">1.1%</td>
<td align="right">-83.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,069,726</td>
<td align="right">1.0%</td>
<td align="right">354,886</td>
<td align="right">1.1%</td>
<td align="right">-82.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">42,367</td>
<td align="right">100.0%</td>
<td align="right">9,449</td>
<td align="right">100.0%</td>
<td align="right">-77.7%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP

<details>
<summary> specialization stats for CONTAINS_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">48,298,855</td>
<td align="right">100.0%</td>
<td align="right">6,071,710</td>
<td align="right">100.0%</td>
<td align="right">-87.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">63</td>
<td align="right">100.0%</td>
<td align="right">63</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">37,174,509</td>
<td align="right">77.1%</td>
<td align="right">1,760,364</td>
<td align="right">46.2%</td>
<td align="right">-95.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">11,042,833</td>
<td align="right">22.9%</td>
<td align="right">2,045,650</td>
<td align="right">53.7%</td>
<td align="right">-81.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Failure</td>
<td align="right">3,763</td>
<td align="right">93.7%</td>
<td align="right">2,678</td>
<td align="right">91.4%</td>
<td align="right">-28.8%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">252</td>
<td align="right">6.3%</td>
<td align="right">252</td>
<td align="right">8.6%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dict items</td>
<td align="right">2,786</td>
<td align="right">74.0%</td>
<td align="right">1,896</td>
<td align="right">70.8%</td>
<td align="right">-31.9%</td>
</tr>
<tr>
<td align="left">zip</td>
<td align="right">911</td>
<td align="right">24.2%</td>
<td align="right">716</td>
<td align="right">26.7%</td>
<td align="right">-21.4%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">66</td>
<td align="right">1.8%</td>
<td align="right">66</td>
<td align="right">2.5%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### GET_ITER

<details>
<summary> specialization stats for GET_ITER family </summary>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tuple</td>
<td align="right">1,376,179</td>
<td align="right">1,376,179 / 0 !!</td>
<td align="right">688,051</td>
<td align="right">688,051 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">1,245,122</td>
<td align="right">1,245,122 / 0 !!</td>
<td align="right">622,530</td>
<td align="right">622,530 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">622,561</td>
<td align="right">622,561 / 0 !!</td>
<td align="right">311,265</td>
<td align="right">311,265 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">2,719,870</td>
<td align="right">2,719,870 / 0 !!</td>
<td align="right">1,884,284</td>
<td align="right">1,884,284 / 0 !!</td>
<td align="right">-30.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">36,599,524</td>
<td align="right">86.7%</td>
<td align="right">9,693,131</td>
<td align="right">77.2%</td>
<td align="right">-73.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">5,621,054</td>
<td align="right">13.3%</td>
<td align="right">2,862,268</td>
<td align="right">22.8%</td>
<td align="right">-49.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,756</td>
<td align="right">0.0%</td>
<td align="right">2,756</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Failure</td>
<td align="right">3,071</td>
<td align="right">71.8%</td>
<td align="right">2,620</td>
<td align="right">68.5%</td>
<td align="right">-14.7%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">1,207</td>
<td align="right">28.2%</td>
<td align="right">1,207</td>
<td align="right">31.5%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">method</td>
<td align="right">1,501</td>
<td align="right">48.9%</td>
<td align="right">988</td>
<td align="right">37.7%</td>
<td align="right">-34.2%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">1,249</td>
<td align="right">40.7%</td>
<td align="right">1,185</td>
<td align="right">45.2%</td>
<td align="right">-5.1%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">164,032,078</td>
<td align="right">100.0%</td>
<td align="right">30,291,900</td>
<td align="right">100.0%</td>
<td align="right">-81.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,827</td>
<td align="right">0.0%</td>
<td align="right">1,827</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,806</td>
<td align="right">100.0%</td>
<td align="right">1,806</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">540,765</td>
<td align="right">20.5%</td>
<td align="right">158,514</td>
<td align="right">7.0%</td>
<td align="right">-70.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">2,092,004</td>
<td align="right">79.3%</td>
<td align="right">2,092,001</td>
<td align="right">92.7%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">5,512</td>
<td align="right">0.2%</td>
<td align="right">5,512</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Failure</td>
<td align="right">527</td>
<td align="right">71.6%</td>
<td align="right">778</td>
<td align="right">78.8%</td>
<td align="right">47.6%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">209</td>
<td align="right">28.4%</td>
<td align="right">209</td>
<td align="right">21.2%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">other</td>
<td align="right">253</td>
<td align="right">48.0%</td>
<td align="right">379</td>
<td align="right">48.7%</td>
<td align="right">49.8%</td>
</tr>
<tr>
<td align="left">split dict</td>
<td align="right">527</td>
<td align="right">100.0%</td>
<td align="right">778</td>
<td align="right">100.0%</td>
<td align="right">47.6%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">19,708,903</td>
<td align="right">100.0%</td>
<td align="right">8,514,264</td>
<td align="right">100.0%</td>
<td align="right">-56.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">357</td>
<td align="right">0.0%</td>
<td align="right">357</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">357</td>
<td align="right">100.0%</td>
<td align="right">357</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">11,271,789</td>
<td align="right">88.0%</td>
<td align="right">5,916,280</td>
<td align="right">82.0%</td>
<td align="right">-47.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,540,686</td>
<td align="right">12.0%</td>
<td align="right">1,294,924</td>
<td align="right">18.0%</td>
<td align="right">-16.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Failure</td>
<td align="right">848</td>
<td align="right">69.2%</td>
<td align="right">783</td>
<td align="right">67.4%</td>
<td align="right">-7.7%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">378</td>
<td align="right">30.8%</td>
<td align="right">378</td>
<td align="right">32.6%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tuple</td>
<td align="right">783</td>
<td align="right">92.3%</td>
<td align="right">719</td>
<td align="right">91.8%</td>
<td align="right">-8.2%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">65</td>
<td align="right">7.7%</td>
<td align="right">64</td>
<td align="right">8.2%</td>
<td align="right">-1.5%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">7,896,807</td>
<td align="right">100.0%</td>
<td align="right">1,901,611</td>
<td align="right">100.0%</td>
<td align="right">-75.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">168</td>
<td align="right">0.0%</td>
<td align="right">168</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">168</td>
<td align="right">100.0%</td>
<td align="right">168</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>


All entries are execution counts. Should add up to the total number of
Tier 1 instructions executed.

<table>
<thead>
<tr>
<th align="left">Instructions</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">2,115,077</td>
<td align="right">0.1%</td>
<td align="right">367,318</td>
<td align="right">0.1%</td>
<td align="right">-82.6%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">656,072,510</td>
<td align="right">36.7%</td>
<td align="right">123,241,297</td>
<td align="right">32.6%</td>
<td align="right">-81.2%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">1,104,546,425</td>
<td align="right">61.8%</td>
<td align="right">246,120,340</td>
<td align="right">65.0%</td>
<td align="right">-77.7%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">24,730,094</td>
<td align="right">1.4%</td>
<td align="right">8,834,509</td>
<td align="right">2.3%</td>
<td align="right">-64.3%</td>
</tr>
</tbody>
</table>

### Deferred by instruction

<details>
<summary> Breakdown of deferred (not specialized) instruction counts by family </summary>

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL</td>
<td align="right">2,069,726</td>
<td align="right">9.9%</td>
<td align="right">354,886</td>
<td align="right">5.3%</td>
<td align="right">-82.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">11,042,833</td>
<td align="right">53.0%</td>
<td align="right">2,045,650</td>
<td align="right">30.4%</td>
<td align="right">-81.5%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">540,765</td>
<td align="right">2.6%</td>
<td align="right">158,514</td>
<td align="right">2.4%</td>
<td align="right">-70.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">5,621,054</td>
<td align="right">27.0%</td>
<td align="right">2,862,268</td>
<td align="right">42.6%</td>
<td align="right">-49.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,540,686</td>
<td align="right">7.4%</td>
<td align="right">1,294,924</td>
<td align="right">19.3%</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">442</td>
<td align="right">0.0%</td>
<td align="right">440</td>
<td align="right">0.0%</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">1,827</td>
<td align="right">0.0%</td>
<td align="right">1,827</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">357</td>
<td align="right">0.0%</td>
<td align="right">357</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">168</td>
<td align="right">0.0%</td>
<td align="right">168</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### Misses by instruction

<details>
<summary> Breakdown of misses (specialized deopts) instruction counts by family </summary>

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">2,106,724</td>
<td align="right">99.6%</td>
<td align="right">358,966</td>
<td align="right">97.7%</td>
<td align="right">-83.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">50</td>
<td align="right">0.0%</td>
<td align="right">49</td>
<td align="right">0.0%</td>
<td align="right">-2.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">5,512</td>
<td align="right">0.3%</td>
<td align="right">5,512</td>
<td align="right">1.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">2,756</td>
<td align="right">0.1%</td>
<td align="right">2,756</td>
<td align="right">0.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">35</td>
<td align="right">0.0%</td>
<td align="right">35</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>


This shows what fraction of calls to Python functions are inlined (i.e.
not having a call at the C level) and for those that are not, where the
call comes from.  The various categories overlap.

Also includes the count of frame objects created.

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">982,980</td>
<td align="right">1.5%</td>
<td align="right">491,460</td>
<td align="right">1.2%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">61,964,114</td>
<td align="right">95.3%</td>
<td align="right">36,749,125</td>
<td align="right">93.4%</td>
<td align="right">-40.7%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">64,061,732</td>
<td align="right">98.5%</td>
<td align="right">38,846,740</td>
<td align="right">98.8%</td>
<td align="right">-39.4%</td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">2,785,187</td>
<td align="right">4.3%</td>
<td align="right">1,916,835</td>
<td align="right">4.9%</td>
<td align="right">-31.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">2,031,777</td>
<td align="right">3.1%</td>
<td align="right">1,540,255</td>
<td align="right">3.9%</td>
<td align="right">-24.2%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">3,080,527</td>
<td align="right">4.7%</td>
<td align="right">2,589,005</td>
<td align="right">6.6%</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">3,080,527</td>
<td align="right">4.7%</td>
<td align="right">2,589,005</td>
<td align="right">6.6%</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">2,097,470</td>
<td align="right">3.2%</td>
<td align="right">2,097,468</td>
<td align="right">5.3%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">2,097,547</td>
<td align="right">3.2%</td>
<td align="right">2,097,545</td>
<td align="right">5.3%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">77</td>
<td align="right">0.0%</td>
<td align="right">77</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">21</td>
<td align="right">0.0%</td>
<td align="right">21</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

## Object stats

<details>
<summary> Allocations, frees and dict materializatons </summary>


Below, "allocations" means "allocations that are not from a freelist".
Total allocations = "Allocations from freelist" + "Allocations".

"Inline values" is the number of values arrays inlined into objects.

The cache hit/miss numbers are for the MRO cache, split into dunder and
other names.

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Base Count</th>
<th align="right">Base Ratio</th>
<th align="right">Head Count</th>
<th align="right">Head Ratio</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">302</td>
<td align="right">0.0%</td>
<td align="right">658</td>
<td align="right">0.0%</td>
<td align="right">117.9%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">1,720,194</td>
<td align="right">0.3%</td>
<td align="right">860,034</td>
<td align="right">0.2%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">307,915,037</td>
<td align="right">49.4%</td>
<td align="right">183,954,012</td>
<td align="right">45.7%</td>
<td align="right">-40.3%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">379,041,328</td>
<td align="right">57.6%</td>
<td align="right">236,629,518</td>
<td align="right">55.4%</td>
<td align="right">-37.6%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">4,072,417</td>
<td align="right"></td>
<td align="right">2,565,084</td>
<td align="right"></td>
<td align="right">-37.0%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">62,881,735</td>
<td align="right"></td>
<td align="right">41,402,324</td>
<td align="right"></td>
<td align="right">-34.2%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">61,014,914</td>
<td align="right">58.7%</td>
<td align="right">40,469,490</td>
<td align="right">57.4%</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">61,015,216</td>
<td align="right">58.7%</td>
<td align="right">40,470,317</td>
<td align="right">57.4%</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">144,237,645</td>
<td align="right">23.1%</td>
<td align="right">96,775,667</td>
<td align="right">24.0%</td>
<td align="right">-32.9%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">177,746,679</td>
<td align="right">27.0%</td>
<td align="right">120,594,176</td>
<td align="right">28.3%</td>
<td align="right">-32.2%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">99,803,661</td>
<td align="right">15.2%</td>
<td align="right">68,790,445</td>
<td align="right">16.1%</td>
<td align="right">-31.1%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">42,857,707</td>
<td align="right"></td>
<td align="right">29,997,307</td>
<td align="right"></td>
<td align="right">-30.0%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">42,858,274</td>
<td align="right">41.3%</td>
<td align="right">29,997,873</td>
<td align="right">42.6%</td>
<td align="right">-30.0%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">155,548,151</td>
<td align="right">25.0%</td>
<td align="right">110,697,336</td>
<td align="right">27.5%</td>
<td align="right">-28.8%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">15,706,999</td>
<td align="right">2.5%</td>
<td align="right">11,520,882</td>
<td align="right">2.9%</td>
<td align="right">-26.7%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">17,370,723</td>
<td align="right"></td>
<td align="right">13,930,013</td>
<td align="right"></td>
<td align="right">-19.8%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">1,540,213</td>
<td align="right"></td>
<td align="right">1,294,452</td>
<td align="right"></td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">1,540,213</td>
<td align="right">100.0%</td>
<td align="right">1,294,452</td>
<td align="right">100.0%</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">932</td>
<td align="right"></td>
<td align="right">884</td>
<td align="right"></td>
<td align="right">-5.2%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">1,554</td>
<td align="right"></td>
<td align="right">1,515</td>
<td align="right"></td>
<td align="right">-2.5%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">1,089</td>
<td align="right"></td>
<td align="right">1,095</td>
<td align="right"></td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">169</td>
<td align="right">0.0%</td>
<td align="right">169 / 0 !!</td>
</tr>
<tr>
<td align="left">Materialize dict (new key)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Materialize dict (too big)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Materialize dict (str subclass)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>


Collected/visits gives some measure of efficiency.

<table>
<thead>
<tr>
<th align="right">Generation</th>
<th align="right">Base Collections</th>
<th align="right">Base Objects collected</th>
<th align="right">Base Object visits</th>
<th align="right">Base Reachable from roots</th>
<th align="right">Base Not reachable from roots</th>
<th align="right">Head Collections</th>
<th align="right">Head Objects collected</th>
<th align="right">Head Object visits</th>
<th align="right">Head Reachable from roots</th>
<th align="right">Head Not reachable from roots</th>
</tr>
</thead>
<tbody>
<tr>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
</tr>
<tr>
<td align="right">1</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
</tr>
<tr>
<td align="right">2</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
</tr>
</tbody>
</table>


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>


</details>

## Rare events

<details>
<summary> Counts of rare/unlikely events </summary>

<table>
<thead>
<tr>
<th align="left">Event</th>
<th align="right">Base Count</th>
<th align="right">Head Count</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
set class
<details>
<summary>ⓘ</summary>

Setting an object's class, `obj.__class__ = ...`
</details>
</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
set bases
<details>
<summary>ⓘ</summary>

Setting the bases of a class, `cls.__bases__ = ...`
</details>
</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
set eval frame func
<details>
<summary>ⓘ</summary>

Setting the PEP 523 frame eval function `_PyInterpreterState_SetFrameEvalFunc()`
</details>
</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
builtin dict
<details>
<summary>ⓘ</summary>

Modifying the builtins, `__builtins__.__dict__[var] = ...`
</details>
</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
func modification
<details>
<summary>ⓘ</summary>

Modifying a function, e.g. `func.__defaults__ = ...`, etc.
</details>
</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
watched dict modification
<details>
<summary>ⓘ</summary>

A watched dict has been modified
</details>
</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">
watched globals modification
<details>
<summary>ⓘ</summary>

A watched `globals()` dict has been modified
</details>
</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Base Count</th>
<th align="right">Head Count</th>
<th align="right">Change</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Number of data files</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2025-11-17
