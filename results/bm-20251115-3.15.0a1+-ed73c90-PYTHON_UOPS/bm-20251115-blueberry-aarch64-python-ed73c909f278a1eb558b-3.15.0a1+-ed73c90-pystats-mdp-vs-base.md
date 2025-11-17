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
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">49,103,649</td>
<td align="right">580,503</td>
<td align="right">-98.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">24,558,849</td>
<td align="right">297,276</td>
<td align="right">-98.8%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">49,407,372</td>
<td align="right">780,339</td>
<td align="right">-98.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">35,443,422</td>
<td align="right">616,497</td>
<td align="right">-98.3%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">49,480,641</td>
<td align="right">957,495</td>
<td align="right">-98.1%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">49,638,078</td>
<td align="right">972,510</td>
<td align="right">-98.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">18,441,444</td>
<td align="right">366,933</td>
<td align="right">-98.0%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">17,980,641</td>
<td align="right">365,022</td>
<td align="right">-98.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">49,637,784</td>
<td align="right">1,083,453</td>
<td align="right">-97.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">49,893,774</td>
<td align="right">1,186,437</td>
<td align="right">-97.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">50,003,772</td>
<td align="right">1,314,369</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">56,192,136</td>
<td align="right">1,627,395</td>
<td align="right">-97.1%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">71,999,634</td>
<td align="right">2,111,949</td>
<td align="right">-97.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">26,121,627</td>
<td align="right">805,203</td>
<td align="right">-96.9%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">51,815,484</td>
<td align="right">1,858,332</td>
<td align="right">-96.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">19,392,723</td>
<td align="right">775,740</td>
<td align="right">-96.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">105,705,495</td>
<td align="right">4,644,444</td>
<td align="right">-95.6%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">46,025,973</td>
<td align="right">3,325,665</td>
<td align="right">-92.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">58,725,072</td>
<td align="right">4,413,276</td>
<td align="right">-92.5%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">48,589,632</td>
<td align="right">5,026,203</td>
<td align="right">-89.7%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">3,429,069</td>
<td align="right">423,864</td>
<td align="right">-87.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">3,430,581</td>
<td align="right">426,846</td>
<td align="right">-87.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">355,484,346</td>
<td align="right">50,223,642</td>
<td align="right">-85.9%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">1,716,267</td>
<td align="right">252,168</td>
<td align="right">-85.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">221,478,222</td>
<td align="right">32,987,346</td>
<td align="right">-85.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">231,185,577</td>
<td align="right">35,379,834</td>
<td align="right">-84.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">34,835,199</td>
<td align="right">5,985,231</td>
<td align="right">-82.8%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">3,890,103</td>
<td align="right">697,767</td>
<td align="right">-82.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">41,272,245</td>
<td align="right">7,796,355</td>
<td align="right">-81.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">393,782,445</td>
<td align="right">77,054,292</td>
<td align="right">-80.4%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">10,490,067</td>
<td align="right">2,344,125</td>
<td align="right">-77.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">129,907,575</td>
<td align="right">29,315,286</td>
<td align="right">-77.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">1,946,784</td>
<td align="right">444,129</td>
<td align="right">-77.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">8,888,649</td>
<td align="right">2,152,269</td>
<td align="right">-75.8%</td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">2,434,635</td>
<td align="right">625,884</td>
<td align="right">-74.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">431,879,574</td>
<td align="right">117,111,372</td>
<td align="right">-72.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">1,267,938</td>
<td align="right">366,723</td>
<td align="right">-71.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">661,835,097</td>
<td align="right">202,200,663</td>
<td align="right">-69.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">1,300,797,288</td>
<td align="right">450,111,837</td>
<td align="right">-65.4%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">4,548,600</td>
<td align="right">1,574,580</td>
<td align="right">-65.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">2,158,548</td>
<td align="right">778,071</td>
<td align="right">-64.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">9,200,100</td>
<td align="right">3,903,270</td>
<td align="right">-57.6%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">148,350,951</td>
<td align="right">66,717,693</td>
<td align="right">-55.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">8,452,605</td>
<td align="right">4,189,542</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">111,603,681</td>
<td align="right">57,070,125</td>
<td align="right">-48.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">154,955,367</td>
<td align="right">84,773,808</td>
<td align="right">-45.3%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">607,656</td>
<td align="right">350,280</td>
<td align="right">-42.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">136,136,784</td>
<td align="right">80,010,210</td>
<td align="right">-41.2%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">78,576,540</td>
<td align="right">47,949,489</td>
<td align="right">-39.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">51,841,629</td>
<td align="right">34,534,773</td>
<td align="right">-33.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">201,924,576</td>
<td align="right">143,532,018</td>
<td align="right">-28.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">300,500,130</td>
<td align="right">233,911,902</td>
<td align="right">-22.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">94,649,772</td>
<td align="right">75,794,061</td>
<td align="right">-19.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">962,514</td>
<td align="right">775,404</td>
<td align="right">-19.4%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">922,572</td>
<td align="right">744,345</td>
<td align="right">-19.3%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">230,496</td>
<td align="right">192,003</td>
<td align="right">-16.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">230,580</td>
<td align="right">192,087</td>
<td align="right">-16.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">690,963</td>
<td align="right">587,034</td>
<td align="right">-15.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">1,303,533</td>
<td align="right">1,125,306</td>
<td align="right">-13.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">28,034,601</td>
<td align="right">24,321,675</td>
<td align="right">-13.2%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">457,463,916</td>
<td align="right">399,280,434</td>
<td align="right">-12.7%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">303,702</td>
<td align="right">265,209</td>
<td align="right">-12.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">303,723</td>
<td align="right">265,230</td>
<td align="right">-12.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">59,252,004</td>
<td align="right">51,843,582</td>
<td align="right">-12.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">798,000</td>
<td align="right">704,445</td>
<td align="right">-11.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">79,062,984</td>
<td align="right">69,906,312</td>
<td align="right">-11.6%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">27,833,379</td>
<td align="right">24,724,245</td>
<td align="right">-11.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">1,272,264</td>
<td align="right">1,130,850</td>
<td align="right">-11.1%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">37,485,147</td>
<td align="right">34,281,891</td>
<td align="right">-8.5%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">567,630</td>
<td align="right">536,445</td>
<td align="right">-5.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">135,647,547</td>
<td align="right">131,934,075</td>
<td align="right">-2.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">27,210,519</td>
<td align="right">26,898,354</td>
<td align="right">-1.1%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">51,815,421</td>
<td align="right">51,345,777</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">52,012,737</td>
<td align="right">51,747,255</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">306,309,066</td>
<td align="right">306,202,302</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">343,263,228</td>
<td align="right">343,263,228</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">334,869,885</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">255,540,474</td>
<td align="right">255,540,474</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">102,387,684</td>
<td align="right">102,387,684</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">63,082,404</td>
<td align="right">63,082,404</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">46,328,016</td>
<td align="right">46,328,016</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">45,867,003</td>
<td align="right">45,867,003</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">31,541,223</td>
<td align="right">31,541,223</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">26,057,976</td>
<td align="right">26,057,976</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">7,964,082</td>
<td align="right">7,964,082</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">7,963,956</td>
<td align="right">7,963,956</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">7,440,741</td>
<td align="right">7,440,741</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">2,565,192</td>
<td align="right">2,565,192</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">303,723</td>
<td align="right">303,723</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">303,723</td>
<td align="right">303,723</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">303,723</td>
<td align="right">303,723</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">230,706</td>
<td align="right">230,706</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">230,496</td>
<td align="right">230,496</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">230,496</td>
<td align="right">230,496</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">83,307</td>
<td align="right">83,307</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">83,307</td>
<td align="right">83,307</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">7,119</td>
<td align="right">7,119</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">5,481</td>
<td align="right">5,481</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">4,599</td>
<td align="right">4,599</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">1,092</td>
<td align="right">1,092</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">756</td>
<td align="right">756</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">588</td>
<td align="right">588</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">504</td>
<td align="right">504</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">252</td>
<td align="right">252</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">231</td>
<td align="right">231</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">189</td>
<td align="right">189</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">189</td>
<td align="right">189</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">257,058,396</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">2,340,555</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">431,764,053</td>
<td align="right">50.1%</td>
<td align="right">117,062,631</td>
<td align="right">45.3%</td>
<td align="right">-72.9%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">429,500,799</td>
<td align="right">49.9%</td>
<td align="right">141,036,987</td>
<td align="right">54.6%</td>
<td align="right">-67.2%</td>
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
<td align="right">114,219</td>
<td align="right">98.9%</td>
<td align="right">47,439</td>
<td align="right">97.3%</td>
<td align="right">-58.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">1,302</td>
<td align="right">1.1%</td>
<td align="right">1,302</td>
<td align="right">2.7%</td>
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
<td align="left">multiply other</td>
<td align="right">378</td>
<td align="right">0.3%</td>
<td align="right">966</td>
<td align="right">2.0%</td>
<td align="right">155.6%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">546</td>
<td align="right">0.5%</td>
<td align="right">1,134</td>
<td align="right">2.4%</td>
<td align="right">107.7%</td>
</tr>
<tr>
<td align="left">subscr</td>
<td align="right">1,008</td>
<td align="right">0.9%</td>
<td align="right">1,848</td>
<td align="right">3.9%</td>
<td align="right">83.3%</td>
</tr>
<tr>
<td align="left">subscr defaultdict</td>
<td align="right">82,299</td>
<td align="right">72.1%</td>
<td align="right">19,236</td>
<td align="right">40.5%</td>
<td align="right">-76.6%</td>
</tr>
<tr>
<td align="left">true divide different types</td>
<td align="right">315</td>
<td align="right">0.3%</td>
<td align="right">483</td>
<td align="right">1.0%</td>
<td align="right">53.3%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">6,363</td>
<td align="right">5.6%</td>
<td align="right">3,024</td>
<td align="right">6.4%</td>
<td align="right">-52.5%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">22,554</td>
<td align="right">19.7%</td>
<td align="right">19,992</td>
<td align="right">42.1%</td>
<td align="right">-11.4%</td>
</tr>
<tr>
<td align="left">true divide other</td>
<td align="right">504</td>
<td align="right">0.4%</td>
<td align="right">504</td>
<td align="right">1.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subtract different types</td>
<td align="right">252</td>
<td align="right">0.2%</td>
<td align="right">252</td>
<td align="right">0.5%</td>
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
<td align="right">336,713,916</td>
<td align="right">99.4%</td>
<td align="right">165,916,401</td>
<td align="right">98.8%</td>
<td align="right">-50.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,996,890</td>
<td align="right">0.6%</td>
<td align="right">1,996,890</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,032,443</td>
<td align="right">0.6%</td>
<td align="right">2,032,443</td>
<td align="right">1.2%</td>
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
<td align="right">41,034</td>
<td align="right">100.0%</td>
<td align="right">41,034</td>
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
<td align="right">42</td>
<td align="right">50.0%</td>
<td align="right">42</td>
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
<td align="right">42</td>
<td align="right">100.0%</td>
<td align="right">42</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,266,573</td>
<td align="right">1.2%</td>
<td align="right">365,169</td>
<td align="right">0.7%</td>
<td align="right">-71.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">104,097,903</td>
<td align="right">98.8%</td>
<td align="right">49,022,211</td>
<td align="right">99.3%</td>
<td align="right">-52.9%</td>
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
<td align="right">714</td>
<td align="right">52.3%</td>
<td align="right">903</td>
<td align="right">58.1%</td>
<td align="right">26.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">651</td>
<td align="right">47.7%</td>
<td align="right">651</td>
<td align="right">41.9%</td>
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
<td align="left">different types</td>
<td align="right">714</td>
<td align="right">100.0%</td>
<td align="right">903</td>
<td align="right">100.0%</td>
<td align="right">26.5%</td>
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
<td align="right">35,443,422</td>
<td align="right">100.0%</td>
<td align="right">616,497</td>
<td align="right">100.0%</td>
<td align="right">-98.3%</td>
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
<td align="right">375,710,601</td>
<td align="right">97.6%</td>
<td align="right">51,177,063</td>
<td align="right">95.6%</td>
<td align="right">-86.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">8,884,764</td>
<td align="right">2.3%</td>
<td align="right">2,146,263</td>
<td align="right">4.0%</td>
<td align="right">-75.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">373,737</td>
<td align="right">0.1%</td>
<td align="right">191,583</td>
<td align="right">0.4%</td>
<td align="right">-48.7%</td>
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
<td align="right">3,633</td>
<td align="right">33.3%</td>
<td align="right">5,754</td>
<td align="right">59.7%</td>
<td align="right">58.4%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">7,287</td>
<td align="right">66.7%</td>
<td align="right">3,885</td>
<td align="right">40.3%</td>
<td align="right">-46.7%</td>
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
<td align="right">3,171</td>
<td align="right">87.3%</td>
<td align="right">5,166</td>
<td align="right">89.8%</td>
<td align="right">62.9%</td>
</tr>
<tr>
<td align="left">zip</td>
<td align="right">441</td>
<td align="right">12.1%</td>
<td align="right">567</td>
<td align="right">9.9%</td>
<td align="right">28.6%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">21</td>
<td align="right">0.6%</td>
<td align="right">21</td>
<td align="right">0.4%</td>
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
<td align="left">list</td>
<td align="right">49,645,008</td>
<td align="right">49,645,008 / 0 !!</td>
<td align="right">49,645,008</td>
<td align="right">49,645,008 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">1,489,698</td>
<td align="right">1,489,698 / 0 !!</td>
<td align="right">1,489,698</td>
<td align="right">1,489,698 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">450,135</td>
<td align="right">450,135 / 0 !!</td>
<td align="right">450,135</td>
<td align="right">450,135 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">230,580</td>
<td align="right">230,580 / 0 !!</td>
<td align="right">230,580</td>
<td align="right">230,580 / 0 !!</td>
<td align="right">0.0%</td>
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
<td align="right">259,848,687</td>
<td align="right">83.3%</td>
<td align="right">157,155,117</td>
<td align="right">82.0%</td>
<td align="right">-39.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">51,816,387</td>
<td align="right">16.6%</td>
<td align="right">34,503,399</td>
<td align="right">18.0%</td>
<td align="right">-33.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">68,838</td>
<td align="right">0.0%</td>
<td align="right">68,838</td>
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
<td align="right">23,394</td>
<td align="right">88.2%</td>
<td align="right">29,526</td>
<td align="right">90.4%</td>
<td align="right">26.2%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">3,129</td>
<td align="right">11.8%</td>
<td align="right">3,129</td>
<td align="right">9.6%</td>
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
<td align="left">overriding descriptor</td>
<td align="right">14,427</td>
<td align="right">61.7%</td>
<td align="right">20,349</td>
<td align="right">68.9%</td>
<td align="right">41.0%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">924</td>
<td align="right">3.9%</td>
<td align="right">1,029</td>
<td align="right">3.5%</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">7,119</td>
<td align="right">30.4%</td>
<td align="right">7,119</td>
<td align="right">24.1%</td>
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
<td align="right">271,784,331</td>
<td align="right">100.0%</td>
<td align="right">211,944,285</td>
<td align="right">100.0%</td>
<td align="right">-22.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,289</td>
<td align="right">0.0%</td>
<td align="right">2,289</td>
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
<td align="right">2,310</td>
<td align="right">100.0%</td>
<td align="right">2,310</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">31,541,223</td>
<td align="right">100.0%</td>
<td align="right">31,541,223</td>
<td align="right">100.0%</td>
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
<td align="right">42</td>
<td align="right">100.0%</td>
<td align="right">42</td>
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
<td align="right">252</td>
<td align="right">0.0%</td>
<td align="right">252</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">63,082,656</td>
<td align="right">100.0%</td>
<td align="right">63,082,656</td>
<td align="right">100.0%</td>
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
<td align="right">252</td>
<td align="right">100.0%</td>
<td align="right">252</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">71,979,978</td>
<td align="right">99.6%</td>
<td align="right">2,106,678</td>
<td align="right">88.6%</td>
<td align="right">-97.1%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">303,702</td>
<td align="right">0.4%</td>
<td align="right">265,209</td>
<td align="right">11.2%</td>
<td align="right">-12.7%</td>
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
<td align="right">19,635</td>
<td align="right">99.9%</td>
<td align="right">5,250</td>
<td align="right">99.6%</td>
<td align="right">-73.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
<td align="right">0.4%</td>
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
<td align="right">19,635</td>
<td align="right">100.0%</td>
<td align="right">5,250</td>
<td align="right">100.0%</td>
<td align="right">-73.3%</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">3,429,405</td>
<td align="right">10.5%</td>
<td align="right">425,565</td>
<td align="right">1.5%</td>
<td align="right">-87.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">29,157,534</td>
<td align="right">89.5%</td>
<td align="right">27,342,714</td>
<td align="right">98.5%</td>
<td align="right">-6.2%</td>
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
<td align="right">924</td>
<td align="right">78.6%</td>
<td align="right">1,029</td>
<td align="right">80.3%</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">252</td>
<td align="right">21.4%</td>
<td align="right">252</td>
<td align="right">19.7%</td>
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
<td align="left">dict</td>
<td align="right">903</td>
<td align="right">97.7%</td>
<td align="right">1,008</td>
<td align="right">98.0%</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">21</td>
<td align="right">2.3%</td>
<td align="right">21</td>
<td align="right">2.0%</td>
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
<td align="right">231,983,577</td>
<td align="right">100.0%</td>
<td align="right">36,084,279</td>
<td align="right">100.0%</td>
<td align="right">-84.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">378</td>
<td align="right">0.0%</td>
<td align="right">378</td>
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
<td align="right">378</td>
<td align="right">100.0%</td>
<td align="right">378</td>
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
<td align="right">621,135,060</td>
<td align="right">7.2%</td>
<td align="right">208,061,343</td>
<td align="right">4.9%</td>
<td align="right">-66.5%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">2,974,582,989</td>
<td align="right">34.5%</td>
<td align="right">1,346,748,585</td>
<td align="right">31.6%</td>
<td align="right">-54.7%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">5,019,798,924</td>
<td align="right">58.2%</td>
<td align="right">2,707,191,900</td>
<td align="right">63.5%</td>
<td align="right">-46.1%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">2,475,060</td>
<td align="right">0.0%</td>
<td align="right">2,292,927</td>
<td align="right">0.1%</td>
<td align="right">-7.4%</td>
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
<td align="left">STORE_SUBSCR</td>
<td align="right">71,979,978</td>
<td align="right">12.6%</td>
<td align="right">2,106,678</td>
<td align="right">1.3%</td>
<td align="right">-97.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">3,429,405</td>
<td align="right">0.6%</td>
<td align="right">425,565</td>
<td align="right">0.3%</td>
<td align="right">-87.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">8,884,764</td>
<td align="right">1.6%</td>
<td align="right">2,146,263</td>
<td align="right">1.4%</td>
<td align="right">-75.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">431,764,053</td>
<td align="right">75.6%</td>
<td align="right">117,062,631</td>
<td align="right">73.8%</td>
<td align="right">-72.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">1,266,573</td>
<td align="right">0.2%</td>
<td align="right">365,169</td>
<td align="right">0.2%</td>
<td align="right">-71.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">51,816,387</td>
<td align="right">9.1%</td>
<td align="right">34,503,399</td>
<td align="right">21.8%</td>
<td align="right">-33.4%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">1,996,890</td>
<td align="right">0.3%</td>
<td align="right">1,996,890</td>
<td align="right">1.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">2,289</td>
<td align="right">0.0%</td>
<td align="right">2,289</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">378</td>
<td align="right">0.0%</td>
<td align="right">378</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">252</td>
<td align="right">0.0%</td>
<td align="right">252</td>
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
<td align="left">RESUME</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">186,753</td>
<td align="right">7.5%</td>
<td align="right">95,403</td>
<td align="right">4.2%</td>
<td align="right">-48.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">186,984</td>
<td align="right">7.6%</td>
<td align="right">96,180</td>
<td align="right">4.2%</td>
<td align="right">-48.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">1,327,725</td>
<td align="right">53.6%</td>
<td align="right">1,327,725</td>
<td align="right">57.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">704,718</td>
<td align="right">28.5%</td>
<td align="right">704,718</td>
<td align="right">30.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">39,900</td>
<td align="right">1.6%</td>
<td align="right">39,900</td>
<td align="right">1.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">28,938</td>
<td align="right">1.2%</td>
<td align="right">28,938</td>
<td align="right">1.3%</td>
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
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">343,263,291</td>
<td align="right">67.7%</td>
<td align="right">343,263,291</td>
<td align="right">67.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">163,682,358</td>
<td align="right">32.3%</td>
<td align="right">163,682,358</td>
<td align="right">32.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">343,263,291</td>
<td align="right">67.7%</td>
<td align="right">343,263,291</td>
<td align="right">67.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">38,242,176</td>
<td align="right">7.5%</td>
<td align="right">38,242,176</td>
<td align="right">7.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">305,021,115</td>
<td align="right">60.2%</td>
<td align="right">305,021,115</td>
<td align="right">60.2%</td>
<td align="right">0.0%</td>
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
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">38,242,176</td>
<td align="right">7.5%</td>
<td align="right">38,242,176</td>
<td align="right">7.5%</td>
<td align="right">0.0%</td>
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
<td align="right">26,862,948</td>
<td align="right">5.3%</td>
<td align="right">26,862,948</td>
<td align="right">5.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">63</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">1,749,825</td>
<td align="right">0.3%</td>
<td align="right">1,749,825</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
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
<td align="right">303,723</td>
<td align="right">0.1%</td>
<td align="right">303,723</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">201,924,576</td>
<td align="right">39.8%</td>
<td align="right">201,924,576</td>
<td align="right">39.8%</td>
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
<td align="left">Method cache collisions</td>
<td align="right">1,174</td>
<td align="right"></td>
<td align="right">1,410</td>
<td align="right"></td>
<td align="right">20.1%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">1,512</td>
<td align="right">0.0%</td>
<td align="right">1,764</td>
<td align="right">0.0%</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">2,268,163,779</td>
<td align="right">50.5%</td>
<td align="right">2,580,464,166</td>
<td align="right">53.6%</td>
<td align="right">13.8%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">623</td>
<td align="right"></td>
<td align="right">544</td>
<td align="right"></td>
<td align="right">-12.7%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">2,720,054,799</td>
<td align="right">51.6%</td>
<td align="right">3,048,559,290</td>
<td align="right">54.0%</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">543,526,009</td>
<td align="right">78.3%</td>
<td align="right">593,165,494</td>
<td align="right">79.8%</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">543,655,308</td>
<td align="right"></td>
<td align="right">593,294,793</td>
<td align="right"></td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">1,843,677,462</td>
<td align="right">35.0%</td>
<td align="right">1,893,203,597</td>
<td align="right">33.5%</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">1,165</td>
<td align="right"></td>
<td align="right">1,192</td>
<td align="right"></td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">1,607,958,100</td>
<td align="right">35.8%</td>
<td align="right">1,624,050,157</td>
<td align="right">33.7%</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">52,798,837</td>
<td align="right"></td>
<td align="right">52,674,470</td>
<td align="right"></td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">476,595</td>
<td align="right">0.1%</td>
<td align="right">477,078</td>
<td align="right">0.1%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">80,623,841</td>
<td align="right"></td>
<td align="right">80,630,429</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">450,054,063</td>
<td align="right">10.0%</td>
<td align="right">450,058,133</td>
<td align="right">9.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">150,592,199</td>
<td align="right">21.7%</td>
<td align="right">150,593,102</td>
<td align="right">20.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">606,261,643</td>
<td align="right">11.5%</td>
<td align="right">606,264,878</td>
<td align="right">10.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">150,114,092</td>
<td align="right">21.6%</td>
<td align="right">150,114,260</td>
<td align="right">20.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">151,160,447</td>
<td align="right"></td>
<td align="right">151,160,461</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">63</td>
<td align="right"></td>
<td align="right">63</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">164,124,996</td>
<td align="right">3.7%</td>
<td align="right">164,124,996</td>
<td align="right">3.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">100,227,813</td>
<td align="right">1.9%</td>
<td align="right">100,227,813</td>
<td align="right">1.8%</td>
<td align="right">0.0%</td>
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
<td align="right">2,583</td>
<td align="right">5,880</td>
<td align="right">31,125,425</td>
<td align="right">4,148,550</td>
<td align="right">1,657,845</td>
<td align="right">2,583</td>
<td align="right">5,880</td>
<td align="right">31,141,214</td>
<td align="right">4,148,802</td>
<td align="right">1,659,105</td>
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
