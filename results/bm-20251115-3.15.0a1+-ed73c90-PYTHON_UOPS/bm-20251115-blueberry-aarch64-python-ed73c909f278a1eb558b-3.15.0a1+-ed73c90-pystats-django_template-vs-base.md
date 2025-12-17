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
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">1,282,954</td>
<td align="right">34,167</td>
<td align="right">-97.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">1,295,485</td>
<td align="right">40,362</td>
<td align="right">-96.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">1,321,292</td>
<td align="right">52,815</td>
<td align="right">-96.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,322,451</td>
<td align="right">53,760</td>
<td align="right">-95.9%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">8,967,788</td>
<td align="right">365,484</td>
<td align="right">-95.9%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">2,578,227</td>
<td align="right">174,405</td>
<td align="right">-93.2%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">7,696,074</td>
<td align="right">537,264</td>
<td align="right">-93.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">5,130,716</td>
<td align="right">358,176</td>
<td align="right">-93.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">1,282,679</td>
<td align="right">89,544</td>
<td align="right">-93.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">2,603,946</td>
<td align="right">198,219</td>
<td align="right">-92.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">12,907,394</td>
<td align="right">1,216,929</td>
<td align="right">-90.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">10,278,907</td>
<td align="right">1,574,601</td>
<td align="right">-84.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">20,602,858</td>
<td align="right">4,441,206</td>
<td align="right">-78.4%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">3,861,372</td>
<td align="right">843,612</td>
<td align="right">-78.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">16,690,152</td>
<td align="right">3,739,071</td>
<td align="right">-77.6%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">6,505,831</td>
<td align="right">1,476,930</td>
<td align="right">-77.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">6,465,126</td>
<td align="right">1,478,337</td>
<td align="right">-77.1%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">10,262,236</td>
<td align="right">2,357,103</td>
<td align="right">-77.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">17,967,522</td>
<td align="right">4,344,732</td>
<td align="right">-75.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">2,565,739</td>
<td align="right">670,488</td>
<td align="right">-73.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">2,578,333</td>
<td align="right">676,704</td>
<td align="right">-73.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">2,578,566</td>
<td align="right">676,851</td>
<td align="right">-73.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,592,573</td>
<td align="right">684,306</td>
<td align="right">-73.6%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">7,722,679</td>
<td align="right">2,079,651</td>
<td align="right">-73.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">2,552,701</td>
<td align="right">719,565</td>
<td align="right">-71.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">2,552,764</td>
<td align="right">719,628</td>
<td align="right">-71.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">2,578,460</td>
<td align="right">733,026</td>
<td align="right">-71.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">2,592,530</td>
<td align="right">739,767</td>
<td align="right">-71.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">111,512,233</td>
<td align="right">33,080,481</td>
<td align="right">-70.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">32,046,746</td>
<td align="right">9,593,640</td>
<td align="right">-70.1%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">3,835,910</td>
<td align="right">1,300,530</td>
<td align="right">-66.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">30,764,104</td>
<td align="right">10,542,168</td>
<td align="right">-65.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">11,507,198</td>
<td align="right">3,944,913</td>
<td align="right">-65.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">3,822,637</td>
<td align="right">1,349,502</td>
<td align="right">-64.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">6,388,798</td>
<td align="right">2,566,956</td>
<td align="right">-59.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">42,258,748</td>
<td align="right">17,136,231</td>
<td align="right">-59.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">30,739,083</td>
<td align="right">12,502,770</td>
<td align="right">-59.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">30,633,929</td>
<td align="right">12,920,565</td>
<td align="right">-57.8%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">7,697,343</td>
<td align="right">3,294,081</td>
<td align="right">-57.2%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">10,173,061</td>
<td align="right">4,444,146</td>
<td align="right">-56.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">31,918,471</td>
<td align="right">14,026,404</td>
<td align="right">-56.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">233</td>
<td align="right">105</td>
<td align="right">-54.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">26,799,541</td>
<td align="right">12,145,329</td>
<td align="right">-54.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">21,642,097</td>
<td align="right">10,133,466</td>
<td align="right">-53.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">14,183</td>
<td align="right">6,951</td>
<td align="right">-51.0%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">38,545</td>
<td align="right">19,089</td>
<td align="right">-50.5%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">12,933</td>
<td align="right">6,405</td>
<td align="right">-50.5%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">12,933</td>
<td align="right">6,405</td>
<td align="right">-50.5%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">12,955</td>
<td align="right">6,426</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">1,270,212</td>
<td align="right">630,084</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">2,540,318</td>
<td align="right">1,260,126</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">2,552,764</td>
<td align="right">1,266,300</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">8,916,333</td>
<td align="right">4,422,957</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">6,349,895</td>
<td align="right">3,149,895</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">1,269,979</td>
<td align="right">629,979</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">3,861,245</td>
<td align="right">1,915,389</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">2,579,116</td>
<td align="right">1,279,404</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">2,578,862</td>
<td align="right">1,279,278</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">2,578,735</td>
<td align="right">1,279,215</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">2,566,162</td>
<td align="right">1,272,978</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">1,308,608</td>
<td align="right">649,152</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">1,283,081</td>
<td align="right">636,489</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">1,282,954</td>
<td align="right">636,426</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">1,282,954</td>
<td align="right">636,426</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">LOAD_COMMON_CONSTANT</td>
<td align="right">1,282,827</td>
<td align="right">636,363</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">1,270,127</td>
<td align="right">630,063</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">26,162</td>
<td align="right">12,978</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">12,827</td>
<td align="right">6,363</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">12,827</td>
<td align="right">6,363</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">DELETE_ATTR</td>
<td align="right">762</td>
<td align="right">378</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">254</td>
<td align="right">126</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">254</td>
<td align="right">126</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">254</td>
<td align="right">126</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">3,848,799</td>
<td align="right">1,909,278</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">3,836,226</td>
<td align="right">1,903,041</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">2,591,626</td>
<td align="right">1,285,641</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">2,566,099</td>
<td align="right">1,272,978</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">1,270,043</td>
<td align="right">630,042</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">2,540,108</td>
<td align="right">1,260,105</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">1,322,387</td>
<td align="right">656,019</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">1,282,891</td>
<td align="right">636,426</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">1,282,891</td>
<td align="right">636,426</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">8,916,610</td>
<td align="right">4,423,419</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">2,553,484</td>
<td align="right">1,266,762</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">13,526</td>
<td align="right">6,741</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">12,891</td>
<td align="right">6,426</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">12,891</td>
<td align="right">6,426</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">12,955</td>
<td align="right">6,489</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">39,467</td>
<td align="right">20,139</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">991</td>
<td align="right">672</td>
<td align="right">-32.2%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">210</td>
<td align="right">189</td>
<td align="right">-10.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">43</td>
<td align="right">42</td>
<td align="right">-2.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">2,478</td>
<td align="right">2,436</td>
<td align="right">-1.7%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">64</td>
<td align="right">63</td>
<td align="right">-1.6%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">3,657</td>
<td align="right">3,612</td>
<td align="right">-1.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,219</td>
<td align="right">1,218</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,046</td>
<td align="right">3,045</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">10,288,333</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">945</td>
<td align="right">945</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">252</td>
<td align="right">252</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">168</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">2,180,430</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">1,327,137</td>
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
<td align="right">15,354,239</td>
<td align="right">85.6%</td>
<td align="right">3,187,170</td>
<td align="right">82.3%</td>
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
<td align="right">2,591,307</td>
<td align="right">14.4%</td>
<td align="right">683,319</td>
<td align="right">17.7%</td>
<td align="right">-73.6%</td>
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
<td align="right">1,014</td>
<td align="right">80.1%</td>
<td align="right">735</td>
<td align="right">74.5%</td>
<td align="right">-27.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">252</td>
<td align="right">19.9%</td>
<td align="right">252</td>
<td align="right">25.5%</td>
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
<td align="left">out of range</td>
<td align="right">507</td>
<td align="right">50.0%</td>
<td align="right">357</td>
<td align="right">48.6%</td>
<td align="right">-29.6%</td>
</tr>
<tr>
<td align="left">subscr</td>
<td align="right">507</td>
<td align="right">50.0%</td>
<td align="right">378</td>
<td align="right">51.4%</td>
<td align="right">-25.4%</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,743,266</td>
<td align="right">3.0%</td>
<td align="right">45,318</td>
<td align="right">0.2%</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,712,224</td>
<td align="right">3.0%</td>
<td align="right">46,242</td>
<td align="right">0.2%</td>
<td align="right">-97.3%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">55,813,995</td>
<td align="right">97.0%</td>
<td align="right">21,059,388</td>
<td align="right">99.8%</td>
<td align="right">-62.3%</td>
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
<td align="right">34,699</td>
<td align="right">100.0%</td>
<td align="right">2,688</td>
<td align="right">100.0%</td>
<td align="right">-92.3%</td>
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
<td align="right">63</td>
<td align="right">50.0%</td>
<td align="right">63</td>
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
<td align="right">2,603,946</td>
<td align="right">100.0%</td>
<td align="right">198,219</td>
<td align="right">99.9%</td>
<td align="right">-92.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">126</td>
<td align="right">0.0%</td>
<td align="right">126</td>
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
<td align="right">126</td>
<td align="right">100.0%</td>
<td align="right">126</td>
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
<td align="right">1,320,322</td>
<td align="right">97.0%</td>
<td align="right">52,143</td>
<td align="right">71.5%</td>
<td align="right">-96.1%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">25,654</td>
<td align="right">1.9%</td>
<td align="right">12,726</td>
<td align="right">17.4%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">13,813</td>
<td align="right">1.0%</td>
<td align="right">7,413</td>
<td align="right">10.2%</td>
<td align="right">-46.3%</td>
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
<td align="right">275</td>
<td align="right">22.5%</td>
<td align="right">147</td>
<td align="right">18.4%</td>
<td align="right">-46.5%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">949</td>
<td align="right">77.5%</td>
<td align="right">651</td>
<td align="right">81.6%</td>
<td align="right">-31.4%</td>
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
<td align="right">949</td>
<td align="right">100.0%</td>
<td align="right">651</td>
<td align="right">100.0%</td>
<td align="right">-31.4%</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">10,275,400</td>
<td align="right">53.2%</td>
<td align="right">1,571,178</td>
<td align="right">32.1%</td>
<td align="right">-84.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">9,018,439</td>
<td align="right">46.7%</td>
<td align="right">3,325,266</td>
<td align="right">67.9%</td>
<td align="right">-63.1%</td>
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
<td align="right">4.2%</td>
<td align="right">126</td>
<td align="right">3.7%</td>
<td align="right">-14.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">3,360</td>
<td align="right">95.8%</td>
<td align="right">3,297</td>
<td align="right">96.3%</td>
<td align="right">-1.9%</td>
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
<td align="left">itertools</td>
<td align="right">782</td>
<td align="right">23.3%</td>
<td align="right">1,827</td>
<td align="right">55.4%</td>
<td align="right">133.6%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">1,523</td>
<td align="right">45.3%</td>
<td align="right">693</td>
<td align="right">21.0%</td>
<td align="right">-54.5%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">527</td>
<td align="right">15.7%</td>
<td align="right">378</td>
<td align="right">11.5%</td>
<td align="right">-28.3%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">507</td>
<td align="right">15.1%</td>
<td align="right">378</td>
<td align="right">11.5%</td>
<td align="right">-25.4%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">21</td>
<td align="right">0.6%</td>
<td align="right">21</td>
<td align="right">0.6%</td>
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
<td align="left">other</td>
<td align="right">1,282,890</td>
<td align="right">1,282,890 / 0 !!</td>
<td align="right">636,363</td>
<td align="right">636,363 / 0 !!</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">2,565,654</td>
<td align="right">2,565,654 / 0 !!</td>
<td align="right">1,272,726</td>
<td align="right">1,272,726 / 0 !!</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">2,565,527</td>
<td align="right">2,565,527 / 0 !!</td>
<td align="right">1,272,663</td>
<td align="right">1,272,663 / 0 !!</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">1,295,781</td>
<td align="right">1,295,781 / 0 !!</td>
<td align="right">642,789</td>
<td align="right">642,789 / 0 !!</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">12,827</td>
<td align="right">12,827 / 0 !!</td>
<td align="right">6,363</td>
<td align="right">6,363 / 0 !!</td>
<td align="right">-50.4%</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">3,488,490</td>
<td align="right">7.3%</td>
<td align="right">92,421</td>
<td align="right">0.9%</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">44,069,301</td>
<td align="right">92.7%</td>
<td align="right">10,770,837</td>
<td align="right">99.1%</td>
<td align="right">-75.6%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,555</td>
<td align="right">0.0%</td>
<td align="right">1,554</td>
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
<td align="right">67,255</td>
<td align="right">100.0%</td>
<td align="right">3,255</td>
<td align="right">99.4%</td>
<td align="right">-95.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">21</td>
<td align="right">0.0%</td>
<td align="right">21</td>
<td align="right">0.6%</td>
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
<td align="right">53,560,568</td>
<td align="right">100.0%</td>
<td align="right">24,159,870</td>
<td align="right">100.0%</td>
<td align="right">-54.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,239</td>
<td align="right">0.0%</td>
<td align="right">1,218</td>
<td align="right">0.0%</td>
<td align="right">-1.7%</td>
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
<td align="right">1,239</td>
<td align="right">100.0%</td>
<td align="right">1,218</td>
<td align="right">100.0%</td>
<td align="right">-1.7%</td>
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

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

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
<td align="right">12,933</td>
<td align="right">99.7%</td>
<td align="right">6,405</td>
<td align="right">99.3%</td>
<td align="right">-50.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">21</td>
<td align="right">0.2%</td>
<td align="right">21</td>
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
<td align="right">21</td>
<td align="right">100.0%</td>
<td align="right">21</td>
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
<td align="right">14,183</td>
<td align="right">93.5%</td>
<td align="right">6,951</td>
<td align="right">91.2%</td>
<td align="right">-51.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">676</td>
<td align="right">4.5%</td>
<td align="right">420</td>
<td align="right">5.5%</td>
<td align="right">-37.9%</td>
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
<td align="right">147</td>
<td align="right">46.7%</td>
<td align="right">84</td>
<td align="right">33.3%</td>
<td align="right">-42.9%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">168</td>
<td align="right">53.3%</td>
<td align="right">168</td>
<td align="right">66.7%</td>
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
<td align="left">class attr simple</td>
<td align="right">147</td>
<td align="right">100.0%</td>
<td align="right">84</td>
<td align="right">100.0%</td>
<td align="right">-42.9%</td>
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
<td align="right">8,966,053</td>
<td align="right">77.6%</td>
<td align="right">1,167,243</td>
<td align="right">61.2%</td>
<td align="right">-87.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,591,201</td>
<td align="right">22.4%</td>
<td align="right">738,738</td>
<td align="right">38.7%</td>
<td align="right">-71.5%</td>
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
<td align="right">1,182</td>
<td align="right">88.9%</td>
<td align="right">882</td>
<td align="right">85.7%</td>
<td align="right">-25.4%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">147</td>
<td align="right">11.1%</td>
<td align="right">147</td>
<td align="right">14.3%</td>
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
<td align="left">dict subclass no override</td>
<td align="right">507</td>
<td align="right">42.9%</td>
<td align="right">357</td>
<td align="right">40.5%</td>
<td align="right">-29.6%</td>
</tr>
<tr>
<td align="left">py simple</td>
<td align="right">675</td>
<td align="right">57.1%</td>
<td align="right">525</td>
<td align="right">59.5%</td>
<td align="right">-22.2%</td>
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
<td align="right">30,633,929</td>
<td align="right">100.0%</td>
<td align="right">12,920,565</td>
<td align="right">100.0%</td>
<td align="right">-57.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">631</td>
<td align="right">0.0%</td>
<td align="right">630</td>
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
<td align="right">567</td>
<td align="right">96.4%</td>
<td align="right">567</td>
<td align="right">96.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">21</td>
<td align="right">3.6%</td>
<td align="right">21</td>
<td align="right">3.6%</td>
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
<td align="right">2,552,701</td>
<td align="right">100.0%</td>
<td align="right">719,565</td>
<td align="right">100.0%</td>
<td align="right">-71.8%</td>
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
<td align="right">5,245,569</td>
<td align="right">0.8%</td>
<td align="right">145,152</td>
<td align="right">0.1%</td>
<td align="right">-97.2%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">24,519,918</td>
<td align="right">3.7%</td>
<td align="right">5,142,669</td>
<td align="right">2.3%</td>
<td align="right">-79.0%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">270,080,541</td>
<td align="right">41.1%</td>
<td align="right">91,792,365</td>
<td align="right">41.4%</td>
<td align="right">-66.0%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">356,555,156</td>
<td align="right">54.3%</td>
<td align="right">124,706,799</td>
<td align="right">56.2%</td>
<td align="right">-65.0%</td>
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
<td align="right">1,712,224</td>
<td align="right">9.3%</td>
<td align="right">46,242</td>
<td align="right">1.5%</td>
<td align="right">-97.3%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">1,320,322</td>
<td align="right">7.1%</td>
<td align="right">52,143</td>
<td align="right">1.7%</td>
<td align="right">-96.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">10,275,400</td>
<td align="right">55.6%</td>
<td align="right">1,571,178</td>
<td align="right">50.8%</td>
<td align="right">-84.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,591,307</td>
<td align="right">14.0%</td>
<td align="right">683,319</td>
<td align="right">22.1%</td>
<td align="right">-73.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">2,591,201</td>
<td align="right">14.0%</td>
<td align="right">738,738</td>
<td align="right">23.9%</td>
<td align="right">-71.5%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">676</td>
<td align="right">0.0%</td>
<td align="right">420</td>
<td align="right">0.0%</td>
<td align="right">-37.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">1,239</td>
<td align="right">0.0%</td>
<td align="right">1,218</td>
<td align="right">0.0%</td>
<td align="right">-1.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">631</td>
<td align="right">0.0%</td>
<td align="right">630</td>
<td align="right">0.0%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,555</td>
<td align="right">0.0%</td>
<td align="right">1,554</td>
<td align="right">0.1%</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">126</td>
<td align="right">0.0%</td>
<td align="right">126</td>
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
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">1,743,266</td>
<td align="right">33.2%</td>
<td align="right">45,318</td>
<td align="right">31.2%</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">3,488,130</td>
<td align="right">66.5%</td>
<td align="right">92,253</td>
<td align="right">63.6%</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">360</td>
<td align="right">0.0%</td>
<td align="right">168</td>
<td align="right">0.1%</td>
<td align="right">-53.3%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">13,813</td>
<td align="right">0.3%</td>
<td align="right">7,413</td>
<td align="right">5.1%</td>
<td align="right">-46.3%</td>
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
<td align="left">END_FOR</td>
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
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">3,810,254</td>
<td align="right">11.4%</td>
<td align="right">1,890,126</td>
<td align="right">11.4%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">254</td>
<td align="right">0.0%</td>
<td align="right">126</td>
<td align="right">0.0%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">32,008,321</td>
<td align="right">96.0%</td>
<td align="right">15,878,268</td>
<td align="right">96.0%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">30,751,783</td>
<td align="right">92.3%</td>
<td align="right">15,255,009</td>
<td align="right">92.3%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">1,308,523</td>
<td align="right">3.9%</td>
<td align="right">649,131</td>
<td align="right">3.9%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">1,321,922</td>
<td align="right">4.0%</td>
<td align="right">655,809</td>
<td align="right">4.0%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">1,321,922</td>
<td align="right">4.0%</td>
<td align="right">655,809</td>
<td align="right">4.0%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">1,322,451</td>
<td align="right">4.0%</td>
<td align="right">656,082</td>
<td align="right">4.0%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">1,322,451</td>
<td align="right">4.0%</td>
<td align="right">656,082</td>
<td align="right">4.0%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">529</td>
<td align="right">0.0%</td>
<td align="right">273</td>
<td align="right">0.0%</td>
<td align="right">-48.4%</td>
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
<td align="left">Method cache hits</td>
<td align="right">7,302,129</td>
<td align="right"></td>
<td align="right">1,985,682</td>
<td align="right"></td>
<td align="right">-72.8%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">75,352,687</td>
<td align="right">25.6%</td>
<td align="right">35,749,008</td>
<td align="right">24.4%</td>
<td align="right">-52.6%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">19,319,031</td>
<td align="right">6.6%</td>
<td align="right">9,583,350</td>
<td align="right">6.5%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">1,296,162</td>
<td align="right"></td>
<td align="right">642,978</td>
<td align="right"></td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">3,849,370</td>
<td align="right">1.2%</td>
<td align="right">1,909,530</td>
<td align="right">1.2%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">16,691,801</td>
<td align="right"></td>
<td align="right">8,280,187</td>
<td align="right"></td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">16,653,088</td>
<td align="right">43.2%</td>
<td align="right">8,261,064</td>
<td align="right">41.8%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">16,678,996</td>
<td align="right">43.3%</td>
<td align="right">8,274,021</td>
<td align="right">41.9%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">15,422,616</td>
<td align="right"></td>
<td align="right">7,651,019</td>
<td align="right"></td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">55,129,039</td>
<td align="right">17.2%</td>
<td align="right">27,349,085</td>
<td align="right">17.1%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">48,590,754</td>
<td align="right">16.5%</td>
<td align="right">24,106,430</td>
<td align="right">16.4%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">25,400</td>
<td align="right">0.1%</td>
<td align="right">12,663</td>
<td align="right">0.1%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">193,582,326</td>
<td align="right">60.4%</td>
<td align="right">96,577,173</td>
<td align="right">60.3%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">68,054,693</td>
<td align="right">21.2%</td>
<td align="right">34,370,796</td>
<td align="right">21.5%</td>
<td align="right">-49.5%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">151,617,974</td>
<td align="right">51.4%</td>
<td align="right">77,365,953</td>
<td align="right">52.7%</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">21,862,035</td>
<td align="right"></td>
<td align="right">11,481,498</td>
<td align="right"></td>
<td align="right">-47.5%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">21,862,036</td>
<td align="right">56.7%</td>
<td align="right">11,481,519</td>
<td align="right">58.1%</td>
<td align="right">-47.5%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">508</td>
<td align="right">0.0%</td>
<td align="right">294</td>
<td align="right">0.0%</td>
<td align="right">-42.1%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">997</td>
<td align="right"></td>
<td align="right">1,050</td>
<td align="right"></td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">447</td>
<td align="right"></td>
<td align="right">457</td>
<td align="right"></td>
<td align="right">2.2%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">675</td>
<td align="right"></td>
<td align="right">687</td>
<td align="right"></td>
<td align="right">1.8%</td>
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
