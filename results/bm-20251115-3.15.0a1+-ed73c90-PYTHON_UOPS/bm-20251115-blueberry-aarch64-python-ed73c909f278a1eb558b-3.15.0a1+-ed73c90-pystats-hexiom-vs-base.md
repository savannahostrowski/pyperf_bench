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
<td align="left">JUMP_FORWARD</td>
<td align="right">3,323,610</td>
<td align="right">135,476</td>
<td align="right">-95.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">19,366,994</td>
<td align="right">1,136,503</td>
<td align="right">-94.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">20,144,263</td>
<td align="right">1,518,124</td>
<td align="right">-92.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">22,663,370</td>
<td align="right">2,282,481</td>
<td align="right">-89.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">16,443,574</td>
<td align="right">1,934,818</td>
<td align="right">-88.2%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">1,148,728</td>
<td align="right">138,792</td>
<td align="right">-87.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">1,154,168</td>
<td align="right">141,667</td>
<td align="right">-87.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">38,210,668</td>
<td align="right">5,420,161</td>
<td align="right">-85.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">52,747,630</td>
<td align="right">7,592,313</td>
<td align="right">-85.6%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">18,740,288</td>
<td align="right">2,832,365</td>
<td align="right">-84.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">1,254,442</td>
<td align="right">191,514</td>
<td align="right">-84.7%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">47,180,696</td>
<td align="right">7,471,256</td>
<td align="right">-84.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">17,439,502</td>
<td align="right">2,872,183</td>
<td align="right">-83.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">128,590,580</td>
<td align="right">21,310,280</td>
<td align="right">-83.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">18,344,787</td>
<td align="right">3,256,725</td>
<td align="right">-82.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">11,390,767</td>
<td align="right">2,054,626</td>
<td align="right">-82.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">39,891,586</td>
<td align="right">7,234,381</td>
<td align="right">-81.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">20,639,923</td>
<td align="right">3,769,376</td>
<td align="right">-81.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">19,302,858</td>
<td align="right">3,732,869</td>
<td align="right">-80.7%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">3,509,548</td>
<td align="right">680,616</td>
<td align="right">-80.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">1,762,677</td>
<td align="right">344,115</td>
<td align="right">-80.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">28,474,761</td>
<td align="right">5,665,196</td>
<td align="right">-80.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">37,065,264</td>
<td align="right">7,468,951</td>
<td align="right">-79.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">1,850,163</td>
<td align="right">387,825</td>
<td align="right">-79.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">3,823,813</td>
<td align="right">837,441</td>
<td align="right">-78.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">23,329,064</td>
<td align="right">5,122,140</td>
<td align="right">-78.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">13,632,854</td>
<td align="right">3,969,915</td>
<td align="right">-70.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">4,216,674</td>
<td align="right">1,248,111</td>
<td align="right">-70.4%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">37,727,659</td>
<td align="right">12,294,967</td>
<td align="right">-67.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">3,690,680</td>
<td align="right">1,207,053</td>
<td align="right">-67.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">5,497,817</td>
<td align="right">1,800,821</td>
<td align="right">-67.2%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">2,893,480</td>
<td align="right">973,923</td>
<td align="right">-66.3%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">883,074</td>
<td align="right">301,473</td>
<td align="right">-65.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,747,008</td>
<td align="right">1,297,011</td>
<td align="right">-65.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">1,800,253</td>
<td align="right">774,687</td>
<td align="right">-57.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,870,392</td>
<td align="right">878,515</td>
<td align="right">-53.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">490</td>
<td align="right">234</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">490</td>
<td align="right">234</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">2,958,311</td>
<td align="right">1,412,775</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">3,983</td>
<td align="right">1,935</td>
<td align="right">-51.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">1,114,417</td>
<td align="right">547,189</td>
<td align="right">-50.9%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">14,693</td>
<td align="right">7,269</td>
<td align="right">-50.5%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">6,090</td>
<td align="right">3,018</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">764,435</td>
<td align="right">379,535</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">764,522</td>
<td align="right">379,621</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">764,522</td>
<td align="right">379,621</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">764,522</td>
<td align="right">379,621</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">764,588</td>
<td align="right">379,686</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">19,334</td>
<td align="right">9,606</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">9,667</td>
<td align="right">4,803</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">948,548</td>
<td align="right">471,486</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">238,574</td>
<td align="right">118,597</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">19,379</td>
<td align="right">9,650</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">125,559</td>
<td align="right">62,583</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">125,559</td>
<td align="right">62,583</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">465,463</td>
<td align="right">232,067</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">376,824</td>
<td align="right">187,896</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">100,117</td>
<td align="right">49,940</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">58,233</td>
<td align="right">29,049</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">82,253</td>
<td align="right">41,036</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">83,293</td>
<td align="right">41,565</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">12,264</td>
<td align="right">6,120</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">511</td>
<td align="right">255</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">52,636</td>
<td align="right">26,267</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">14,524,994</td>
<td align="right">7,248,445</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">15,841,789</td>
<td align="right">7,905,778</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">15,289,936</td>
<td align="right">7,630,410</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">406,311</td>
<td align="right">202,790</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">109,378</td>
<td align="right">54,593</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">278,561</td>
<td align="right">139,040</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">222,865</td>
<td align="right">111,247</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">110,442</td>
<td align="right">55,145</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">66,478</td>
<td align="right">33,196</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">66,562</td>
<td align="right">33,280</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">535</td>
<td align="right">278</td>
<td align="right">-48.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">535</td>
<td align="right">278</td>
<td align="right">-48.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">3,444</td>
<td align="right">1,901</td>
<td align="right">-44.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">18,245</td>
<td align="right">11,503</td>
<td align="right">-37.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">715</td>
<td align="right">454</td>
<td align="right">-36.5%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">760</td>
<td align="right">498</td>
<td align="right">-34.5%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,171</td>
<td align="right">905</td>
<td align="right">-22.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">45</td>
<td align="right">44</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">132</td>
<td align="right">130</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">66</td>
<td align="right">65</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">66</td>
<td align="right">65</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">66</td>
<td align="right">65</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">66</td>
<td align="right">65</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">66</td>
<td align="right">65</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">1,726</td>
<td align="right">1,724</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,053</td>
<td align="right">1,052</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">5,443</td>
<td align="right">5,442</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">36,201,680</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">5,040</td>
<td align="right">5,040</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">4,452</td>
<td align="right">4,452</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">1,638</td>
<td align="right">1,638</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">1,512</td>
<td align="right">1,512</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">840</td>
<td align="right">840</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">588</td>
<td align="right">588</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">420</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">294</td>
<td align="right">294</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">168</td>
<td align="right">168</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">8,354,799</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">2,804,732</td>
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
<td align="right">90,893,021</td>
<td align="right">100.0%</td>
<td align="right">17,552,021</td>
<td align="right">99.9%</td>
<td align="right">-80.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">15,470</td>
<td align="right">0.0%</td>
<td align="right">8,814</td>
<td align="right">0.1%</td>
<td align="right">-43.0%</td>
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
<td align="right">591</td>
<td align="right">21.3%</td>
<td align="right">505</td>
<td align="right">18.8%</td>
<td align="right">-14.6%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">2,184</td>
<td align="right">78.7%</td>
<td align="right">2,184</td>
<td align="right">81.2%</td>
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
<td align="left">remainder</td>
<td align="right">273</td>
<td align="right">46.2%</td>
<td align="right">231</td>
<td align="right">45.7%</td>
<td align="right">-15.4%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">318</td>
<td align="right">53.8%</td>
<td align="right">274</td>
<td align="right">54.3%</td>
<td align="right">-13.8%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

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
<td align="right">12,264</td>
<td align="right">100.0%</td>
<td align="right">6,120</td>
<td align="right">100.0%</td>
<td align="right">-50.1%</td>
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
<td align="right">40,519,600</td>
<td align="right">100.0%</td>
<td align="right">7,789,860</td>
<td align="right">99.9%</td>
<td align="right">-80.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,520</td>
<td align="right">0.0%</td>
<td align="right">2,520</td>
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
<td align="right">2,520</td>
<td align="right">100.0%</td>
<td align="right">2,520</td>
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

### CALL_KW

<details>
<summary> specialization stats for CALL_KW family </summary>

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
<td align="right">147</td>
<td align="right">50.0%</td>
<td align="right">147</td>
<td align="right">50.0%</td>
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
<td align="right">147</td>
<td align="right">100.0%</td>
<td align="right">147</td>
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

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

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
<td align="right">28,494,140</td>
<td align="right">100.0%</td>
<td align="right">5,674,846</td>
<td align="right">100.0%</td>
<td align="right">-80.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">819</td>
<td align="right">0.0%</td>
<td align="right">819</td>
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
<td align="right">819</td>
<td align="right">100.0%</td>
<td align="right">819</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">19,361,300</td>
<td align="right">99.7%</td>
<td align="right">1,134,441</td>
<td align="right">97.3%</td>
<td align="right">-94.1%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">58,233</td>
<td align="right">0.3%</td>
<td align="right">29,049</td>
<td align="right">2.5%</td>
<td align="right">-50.1%</td>
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
<td align="right">5,673</td>
<td align="right">99.6%</td>
<td align="right">2,041</td>
<td align="right">99.0%</td>
<td align="right">-64.0%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">21</td>
<td align="right">0.4%</td>
<td align="right">21</td>
<td align="right">1.0%</td>
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
<td align="left">list</td>
<td align="right">5,673</td>
<td align="right">100.0%</td>
<td align="right">2,041</td>
<td align="right">100.0%</td>
<td align="right">-64.0%</td>
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
<td align="right">39,053,298</td>
<td align="right">99.9%</td>
<td align="right">4,193,895</td>
<td align="right">99.4%</td>
<td align="right">-89.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">53,646</td>
<td align="right">0.1%</td>
<td align="right">23,404</td>
<td align="right">0.6%</td>
<td align="right">-56.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">885</td>
<td align="right">0.0%</td>
<td align="right">884</td>
<td align="right">0.0%</td>
<td align="right">-0.1%</td>
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
<td align="right">1,801</td>
<td align="right">98.8%</td>
<td align="right">1,285</td>
<td align="right">98.4%</td>
<td align="right">-28.7%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">22</td>
<td align="right">1.2%</td>
<td align="right">21</td>
<td align="right">1.6%</td>
<td align="right">-4.5%</td>
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
<td align="left">dict values</td>
<td align="right">22</td>
<td align="right">100.0%</td>
<td align="right">21</td>
<td align="right">100.0%</td>
<td align="right">-4.5%</td>
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
<td align="left">list</td>
<td align="right">1,899,964</td>
<td align="right">1,899,964 / 0 !!</td>
<td align="right">948,155</td>
<td align="right">948,155 / 0 !!</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">1,058,347</td>
<td align="right">1,058,347 / 0 !!</td>
<td align="right">528,170</td>
<td align="right">528,170 / 0 !!</td>
<td align="right">-50.1%</td>
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
<td align="right">55,976,836</td>
<td align="right">100.0%</td>
<td align="right">11,008,371</td>
<td align="right">100.0%</td>
<td align="right">-80.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,754</td>
<td align="right">0.0%</td>
<td align="right">2,753</td>
<td align="right">0.0%</td>
<td align="right">-0.0%</td>
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
<td align="right">2,667</td>
<td align="right">99.2%</td>
<td align="right">2,667</td>
<td align="right">99.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">22</td>
<td align="right">0.8%</td>
<td align="right">22</td>
<td align="right">0.8%</td>
<td align="right">0.0%</td>
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
<td align="right">24,386,931</td>
<td align="right">100.0%</td>
<td align="right">5,066,387</td>
<td align="right">99.9%</td>
<td align="right">-79.2%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,226</td>
<td align="right">0.0%</td>
<td align="right">2,226</td>
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
<td align="right">2,226</td>
<td align="right">100.0%</td>
<td align="right">2,226</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">376,824</td>
<td align="right">99.8%</td>
<td align="right">187,896</td>
<td align="right">99.7%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">294</td>
<td align="right">0.1%</td>
<td align="right">294</td>
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
<td align="left">Success</td>
<td align="right">294</td>
<td align="right">100.0%</td>
<td align="right">294</td>
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
<td align="right">1,859,830</td>
<td align="right">100.0%</td>
<td align="right">392,628</td>
<td align="right">99.9%</td>
<td align="right">-78.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">210</td>
<td align="right">0.0%</td>
<td align="right">210</td>
<td align="right">0.1%</td>
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
<td align="right">210</td>
<td align="right">100.0%</td>
<td align="right">210</td>
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
<td align="right">17,439,502</td>
<td align="right">100.0%</td>
<td align="right">2,872,183</td>
<td align="right">100.0%</td>
<td align="right">-83.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">549</td>
<td align="right">0.0%</td>
<td align="right">548</td>
<td align="right">0.0%</td>
<td align="right">-0.2%</td>
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
<td align="right">483</td>
<td align="right">95.8%</td>
<td align="right">483</td>
<td align="right">95.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">21</td>
<td align="right">4.2%</td>
<td align="right">21</td>
<td align="right">4.2%</td>
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
<td align="left">sequence</td>
<td align="right">21</td>
<td align="right">100.0%</td>
<td align="right">21</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
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
<td align="right">66,478</td>
<td align="right">99.7%</td>
<td align="right">33,196</td>
<td align="right">99.5%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">84</td>
<td align="right">0.1%</td>
<td align="right">84</td>
<td align="right">0.3%</td>
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
<td align="right">84</td>
<td align="right">100.0%</td>
<td align="right">84</td>
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
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">22,376,636</td>
<td align="right">2.9%</td>
<td align="right">2,587,719</td>
<td align="right">1.6%</td>
<td align="right">-88.4%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">333,260,642</td>
<td align="right">43.4%</td>
<td align="right">62,714,666</td>
<td align="right">39.2%</td>
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
<td align="right">411,870,050</td>
<td align="right">53.7%</td>
<td align="right">94,790,063</td>
<td align="right">59.2%</td>
<td align="right">-77.0%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">53,646</td>
<td align="right">0.0%</td>
<td align="right">23,404</td>
<td align="right">0.0%</td>
<td align="right">-56.4%</td>
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
<td align="left">CONTAINS_OP</td>
<td align="right">19,361,300</td>
<td align="right">99.8%</td>
<td align="right">1,134,441</td>
<td align="right">97.8%</td>
<td align="right">-94.1%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">12,264</td>
<td align="right">0.1%</td>
<td align="right">6,120</td>
<td align="right">0.5%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">15,470</td>
<td align="right">0.1%</td>
<td align="right">8,814</td>
<td align="right">0.8%</td>
<td align="right">-43.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">549</td>
<td align="right">0.0%</td>
<td align="right">548</td>
<td align="right">0.0%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">885</td>
<td align="right">0.0%</td>
<td align="right">884</td>
<td align="right">0.1%</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">2,754</td>
<td align="right">0.0%</td>
<td align="right">2,753</td>
<td align="right">0.2%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">2,520</td>
<td align="right">0.0%</td>
<td align="right">2,520</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">2,226</td>
<td align="right">0.0%</td>
<td align="right">2,226</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">819</td>
<td align="right">0.0%</td>
<td align="right">819</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">294</td>
<td align="right">0.0%</td>
<td align="right">294</td>
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
<td align="left">FOR_ITER_LIST</td>
<td align="right">26,510</td>
<td align="right">49.4%</td>
<td align="right">11,034</td>
<td align="right">47.1%</td>
<td align="right">-58.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">27,136</td>
<td align="right">50.6%</td>
<td align="right">12,370</td>
<td align="right">52.9%</td>
<td align="right">-54.4%</td>
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
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_TOP</td>
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
<td align="left">Calls to Python functions inlined</td>
<td align="right">23,203,019</td>
<td align="right">60.3%</td>
<td align="right">11,578,820</td>
<td align="right">60.3%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">23,329,064</td>
<td align="right">60.6%</td>
<td align="right">11,641,888</td>
<td align="right">60.6%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">15,289,516</td>
<td align="right">39.7%</td>
<td align="right">7,629,990</td>
<td align="right">39.7%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">15,290,002</td>
<td align="right">39.7%</td>
<td align="right">7,630,475</td>
<td align="right">39.7%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">15,290,002</td>
<td align="right">39.7%</td>
<td align="right">7,630,475</td>
<td align="right">39.7%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">66</td>
<td align="right">0.0%</td>
<td align="right">65</td>
<td align="right">0.0%</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">486</td>
<td align="right">0.0%</td>
<td align="right">485</td>
<td align="right">0.0%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">486</td>
<td align="right">0.0%</td>
<td align="right">485</td>
<td align="right">0.0%</td>
<td align="right">-0.2%</td>
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
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">273</td>
<td align="right">0.0%</td>
<td align="right">273</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
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
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
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
<td align="left">Inline values</td>
<td align="right">125,706</td>
<td align="right"></td>
<td align="right">62,730</td>
<td align="right"></td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">39,212,189</td>
<td align="right">15.8%</td>
<td align="right">19,567,770</td>
<td align="right">15.8%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">65,788,476</td>
<td align="right">27.7%</td>
<td align="right">32,834,383</td>
<td align="right">27.6%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">4,126,065</td>
<td align="right">1.7%</td>
<td align="right">2,059,375</td>
<td align="right">1.7%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">47,364,982</td>
<td align="right">19.1%</td>
<td align="right">23,642,589</td>
<td align="right">19.1%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">3,819,177</td>
<td align="right"></td>
<td align="right">1,906,593</td>
<td align="right"></td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">154,952,852</td>
<td align="right">62.6%</td>
<td align="right">77,362,956</td>
<td align="right">62.6%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">159,390,537</td>
<td align="right">67.1%</td>
<td align="right">79,581,740</td>
<td align="right">66.9%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">3,648,796</td>
<td align="right">44.7%</td>
<td align="right">1,822,829</td>
<td align="right">40.9%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">3,649,307</td>
<td align="right">44.7%</td>
<td align="right">1,823,549</td>
<td align="right">40.9%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">5,956,876</td>
<td align="right">2.4%</td>
<td align="right">2,982,612</td>
<td align="right">2.4%</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">50,754</td>
<td align="right"></td>
<td align="right">25,686</td>
<td align="right"></td>
<td align="right">-49.4%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">8,198,948</td>
<td align="right">3.5%</td>
<td align="right">4,478,890</td>
<td align="right">3.8%</td>
<td align="right">-45.4%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">4,518,569</td>
<td align="right">55.3%</td>
<td align="right">2,635,782</td>
<td align="right">59.1%</td>
<td align="right">-41.7%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">4,520,797</td>
<td align="right"></td>
<td align="right">2,638,010</td>
<td align="right"></td>
<td align="right">-41.6%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">32,148</td>
<td align="right"></td>
<td align="right">18,887</td>
<td align="right"></td>
<td align="right">-41.2%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">511</td>
<td align="right">0.0%</td>
<td align="right">613</td>
<td align="right">0.0%</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">946</td>
<td align="right"></td>
<td align="right">851</td>
<td align="right"></td>
<td align="right">-10.0%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">230</td>
<td align="right"></td>
<td align="right">209</td>
<td align="right"></td>
<td align="right">-9.1%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">1,050</td>
<td align="right"></td>
<td align="right">1,082</td>
<td align="right"></td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">107</td>
<td align="right">0.0%</td>
<td align="right">107 / 0 !!</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
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
<td align="right">21</td>
<td align="right">21</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2025-11-17
