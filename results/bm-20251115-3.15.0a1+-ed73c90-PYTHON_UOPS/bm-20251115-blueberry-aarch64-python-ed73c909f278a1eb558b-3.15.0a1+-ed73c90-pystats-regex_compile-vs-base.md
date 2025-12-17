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
<td align="left">STORE_SUBSCR</td>
<td align="right">22,283,520</td>
<td align="right">478,149</td>
<td align="right">-97.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">25,631,592</td>
<td align="right">963,417</td>
<td align="right">-96.2%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">3,865,239</td>
<td align="right">585,627</td>
<td align="right">-84.8%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">6,715,653</td>
<td align="right">1,312,185</td>
<td align="right">-80.5%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">7,262,955</td>
<td align="right">1,606,794</td>
<td align="right">-77.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">7,404,873</td>
<td align="right">1,704,045</td>
<td align="right">-77.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">47,161,044</td>
<td align="right">12,006,393</td>
<td align="right">-74.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">11,038,923</td>
<td align="right">3,008,481</td>
<td align="right">-72.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">45,945,522</td>
<td align="right">12,627,867</td>
<td align="right">-72.5%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">8,888,418</td>
<td align="right">2,539,656</td>
<td align="right">-71.4%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">11,986,632</td>
<td align="right">3,491,376</td>
<td align="right">-70.9%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">12,357,786</td>
<td align="right">3,824,415</td>
<td align="right">-69.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">87,627,456</td>
<td align="right">27,598,221</td>
<td align="right">-68.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">19,934,208</td>
<td align="right">6,288,324</td>
<td align="right">-68.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">9,950,136</td>
<td align="right">3,204,810</td>
<td align="right">-67.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">10,383,219</td>
<td align="right">3,354,162</td>
<td align="right">-67.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">4,162,158</td>
<td align="right">1,374,534</td>
<td align="right">-67.0%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">4,556,160</td>
<td align="right">1,592,598</td>
<td align="right">-65.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">3,889,704</td>
<td align="right">1,363,677</td>
<td align="right">-64.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">6,398,490</td>
<td align="right">2,257,374</td>
<td align="right">-64.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">27,649,125</td>
<td align="right">9,984,009</td>
<td align="right">-63.9%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">1,761,732</td>
<td align="right">643,860</td>
<td align="right">-63.5%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">1,003,149</td>
<td align="right">371,112</td>
<td align="right">-63.0%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">3,345,993</td>
<td align="right">1,253,763</td>
<td align="right">-62.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">10,885,896</td>
<td align="right">4,090,527</td>
<td align="right">-62.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">6,107,157</td>
<td align="right">2,371,467</td>
<td align="right">-61.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">27,638,604</td>
<td align="right">10,804,122</td>
<td align="right">-60.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">15,635,970</td>
<td align="right">6,112,827</td>
<td align="right">-60.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">38,077,641</td>
<td align="right">15,246,210</td>
<td align="right">-60.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">15,009,057</td>
<td align="right">6,053,586</td>
<td align="right">-59.7%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">17,740,548</td>
<td align="right">7,230,951</td>
<td align="right">-59.2%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">220,752</td>
<td align="right">90,426</td>
<td align="right">-59.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">224,880,642</td>
<td align="right">93,518,733</td>
<td align="right">-58.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">1,932,000</td>
<td align="right">806,085</td>
<td align="right">-58.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">11,095,308</td>
<td align="right">4,776,618</td>
<td align="right">-56.9%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">983,472</td>
<td align="right">429,261</td>
<td align="right">-56.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">10,237,941</td>
<td align="right">4,494,126</td>
<td align="right">-56.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">1,380,372</td>
<td align="right">618,009</td>
<td align="right">-55.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">66,664,584</td>
<td align="right">30,003,456</td>
<td align="right">-55.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">39,468,597</td>
<td align="right">17,949,834</td>
<td align="right">-54.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">57,075,585</td>
<td align="right">26,230,491</td>
<td align="right">-54.0%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">560,196</td>
<td align="right">259,623</td>
<td align="right">-53.7%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">6,716,241</td>
<td align="right">3,130,260</td>
<td align="right">-53.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">2,176,146</td>
<td align="right">1,032,360</td>
<td align="right">-52.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">544,824</td>
<td align="right">266,994</td>
<td align="right">-51.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">1,137,591</td>
<td align="right">560,553</td>
<td align="right">-50.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">5,298,279</td>
<td align="right">2,648,268</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">2,400,048</td>
<td align="right">1,215,186</td>
<td align="right">-49.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">12,736,206</td>
<td align="right">6,555,948</td>
<td align="right">-48.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">33,379,668</td>
<td align="right">17,271,051</td>
<td align="right">-48.3%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">3,050,271</td>
<td align="right">1,580,418</td>
<td align="right">-48.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">230,202</td>
<td align="right">121,128</td>
<td align="right">-47.4%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">32,833,290</td>
<td align="right">17,462,823</td>
<td align="right">-46.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">7,875,252</td>
<td align="right">4,361,952</td>
<td align="right">-44.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">3,567,060</td>
<td align="right">2,027,382</td>
<td align="right">-43.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">7,776,573</td>
<td align="right">4,552,800</td>
<td align="right">-41.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,233,266</td>
<td align="right">1,334,109</td>
<td align="right">-40.3%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">1,532,223</td>
<td align="right">919,779</td>
<td align="right">-40.0%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">1,532,223</td>
<td align="right">919,779</td>
<td align="right">-40.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">34,842,507</td>
<td align="right">21,689,934</td>
<td align="right">-37.7%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">4,885,587</td>
<td align="right">3,086,118</td>
<td align="right">-36.8%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">3,929,940</td>
<td align="right">2,504,901</td>
<td align="right">-36.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">13,343,757</td>
<td align="right">8,537,739</td>
<td align="right">-36.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">730,548</td>
<td align="right">468,006</td>
<td align="right">-35.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">2,317,581</td>
<td align="right">1,496,649</td>
<td align="right">-35.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,846,761</td>
<td align="right">1,208,760</td>
<td align="right">-34.5%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">9,978,318</td>
<td align="right">6,582,639</td>
<td align="right">-34.0%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">9,621,297</td>
<td align="right">6,362,916</td>
<td align="right">-33.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">8,439,354</td>
<td align="right">5,606,475</td>
<td align="right">-33.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">1,765,512</td>
<td align="right">1,240,071</td>
<td align="right">-29.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">704,844</td>
<td align="right">511,035</td>
<td align="right">-27.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">628,509</td>
<td align="right">461,475</td>
<td align="right">-26.6%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">3,019,653</td>
<td align="right">2,280,495</td>
<td align="right">-24.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">557,550</td>
<td align="right">423,570</td>
<td align="right">-24.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">713,853</td>
<td align="right">549,717</td>
<td align="right">-23.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">5,726,826</td>
<td align="right">4,446,960</td>
<td align="right">-22.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">1,054,242</td>
<td align="right">834,666</td>
<td align="right">-20.8%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">980,154</td>
<td align="right">791,847</td>
<td align="right">-19.2%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">315,651</td>
<td align="right">260,757</td>
<td align="right">-17.4%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">2,361,177</td>
<td align="right">2,054,913</td>
<td align="right">-13.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">929,733</td>
<td align="right">843,885</td>
<td align="right">-9.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">1,959,342</td>
<td align="right">1,958,334</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">38,801,952</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">5,239,521</td>
<td align="right">5,239,521</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">874,923</td>
<td align="right">874,923</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">528,633</td>
<td align="right">528,633</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">471,240</td>
<td align="right">471,240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">445,851</td>
<td align="right">445,851</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">445,851</td>
<td align="right">445,851</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">445,851</td>
<td align="right">445,851</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">356,559</td>
<td align="right">356,559</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">355,194</td>
<td align="right">355,194</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">353,241</td>
<td align="right">353,241</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">345,177</td>
<td align="right">345,177</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">231,000</td>
<td align="right">231,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">176,211</td>
<td align="right">176,211</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">129,780</td>
<td align="right">129,780</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">128,142</td>
<td align="right">128,142</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">83,916</td>
<td align="right">83,916</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">62,874</td>
<td align="right">62,874</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">40,908</td>
<td align="right">40,908</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">35,532</td>
<td align="right">35,532</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">26,460</td>
<td align="right">26,460</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">25,641</td>
<td align="right">25,641</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">25,641</td>
<td align="right">25,641</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">4,284</td>
<td align="right">4,284</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">819</td>
<td align="right">819</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">546</td>
<td align="right">546</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">168</td>
<td align="right">168</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
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
<td align="left">MAKE_CELL</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">3,792,957</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">3,357,060</td>
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
<td align="right">52,254,405</td>
<td align="right">93.7%</td>
<td align="right">24,966,606</td>
<td align="right">90.5%</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,226,168</td>
<td align="right">4.0%</td>
<td align="right">1,325,121</td>
<td align="right">4.8%</td>
<td align="right">-40.5%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,287,699</td>
<td align="right">2.3%</td>
<td align="right">1,297,674</td>
<td align="right">4.7%</td>
<td align="right">0.8%</td>
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
<td align="right">7,035</td>
<td align="right">22.4%</td>
<td align="right">8,925</td>
<td align="right">26.5%</td>
<td align="right">26.9%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">24,360</td>
<td align="right">77.6%</td>
<td align="right">24,738</td>
<td align="right">73.5%</td>
<td align="right">1.6%</td>
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
<td align="left">subscr range</td>
<td align="right">273</td>
<td align="right">3.9%</td>
<td align="right">546</td>
<td align="right">6.1%</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">subscr string slice</td>
<td align="right">252</td>
<td align="right">3.6%</td>
<td align="right">441</td>
<td align="right">4.9%</td>
<td align="right">75.0%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">84</td>
<td align="right">1.2%</td>
<td align="right">147</td>
<td align="right">1.6%</td>
<td align="right">75.0%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">5,439</td>
<td align="right">77.3%</td>
<td align="right">6,804</td>
<td align="right">76.2%</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">multiply other</td>
<td align="right">336</td>
<td align="right">4.8%</td>
<td align="right">336</td>
<td align="right">3.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">252</td>
<td align="right">3.6%</td>
<td align="right">252</td>
<td align="right">2.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">105</td>
<td align="right">1.5%</td>
<td align="right">105</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">and different types</td>
<td align="right">105</td>
<td align="right">1.5%</td>
<td align="right">105</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr other slice</td>
<td align="right">105</td>
<td align="right">1.5%</td>
<td align="right">105</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">84</td>
<td align="right">1.2%</td>
<td align="right">84</td>
<td align="right">0.9%</td>
<td align="right">0.0%</td>
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
<td align="right">560,196</td>
<td align="right">100.0%</td>
<td align="right">259,623</td>
<td align="right">100.0%</td>
<td align="right">-53.7%</td>
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
<td align="right">75,732,678</td>
<td align="right">99.9%</td>
<td align="right">34,409,592</td>
<td align="right">99.9%</td>
<td align="right">-54.6%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">40,509</td>
<td align="right">0.1%</td>
<td align="right">40,509</td>
<td align="right">0.1%</td>
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
<td align="right">40,908</td>
<td align="right">0.1%</td>
<td align="right">40,908</td>
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
<td align="right">1,218</td>
<td align="right">100.0%</td>
<td align="right">1,218</td>
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
<td align="right">12,615,561</td>
<td align="right">92.3%</td>
<td align="right">5,344,731</td>
<td align="right">85.5%</td>
<td align="right">-57.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">128,835</td>
<td align="right">0.9%</td>
<td align="right">64,344</td>
<td align="right">1.0%</td>
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
<td align="right">923,811</td>
<td align="right">6.8%</td>
<td align="right">839,727</td>
<td align="right">13.4%</td>
<td align="right">-9.1%</td>
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
<td align="right">2,436</td>
<td align="right">29.1%</td>
<td align="right">1,260</td>
<td align="right">23.3%</td>
<td align="right">-48.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">5,922</td>
<td align="right">70.9%</td>
<td align="right">4,158</td>
<td align="right">76.7%</td>
<td align="right">-29.8%</td>
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
<td align="right">126</td>
<td align="right">2.1%</td>
<td align="right">315</td>
<td align="right">7.6%</td>
<td align="right">150.0%</td>
</tr>
<tr>
<td align="left">different types</td>
<td align="right">5,103</td>
<td align="right">86.2%</td>
<td align="right">3,150</td>
<td align="right">75.8%</td>
<td align="right">-38.3%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">273</td>
<td align="right">4.6%</td>
<td align="right">273</td>
<td align="right">6.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">210</td>
<td align="right">3.5%</td>
<td align="right">210</td>
<td align="right">5.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">210</td>
<td align="right">3.5%</td>
<td align="right">210</td>
<td align="right">5.1%</td>
<td align="right">0.0%</td>
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
<td align="right">6,713,721</td>
<td align="right">41.1%</td>
<td align="right">1,309,980</td>
<td align="right">30.3%</td>
<td align="right">-80.5%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">9,618,966</td>
<td align="right">58.9%</td>
<td align="right">3,007,662</td>
<td align="right">69.6%</td>
<td align="right">-68.7%</td>
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
<td align="right">1,932</td>
<td align="right">100.0%</td>
<td align="right">2,205</td>
<td align="right">100.0%</td>
<td align="right">14.1%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
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
<td align="left">str</td>
<td align="right">1,890</td>
<td align="right">97.8%</td>
<td align="right">2,163</td>
<td align="right">98.1%</td>
<td align="right">14.4%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">42</td>
<td align="right">2.2%</td>
<td align="right">42</td>
<td align="right">1.9%</td>
<td align="right">0.0%</td>
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
<td align="right">35,967,246</td>
<td align="right">89.9%</td>
<td align="right">4,284,798</td>
<td align="right">73.9%</td>
<td align="right">-88.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">3,877,545</td>
<td align="right">9.7%</td>
<td align="right">1,353,387</td>
<td align="right">23.3%</td>
<td align="right">-65.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">159,306</td>
<td align="right">0.4%</td>
<td align="right">150,423</td>
<td align="right">2.6%</td>
<td align="right">-5.6%</td>
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
<td align="right">12,096</td>
<td align="right">79.8%</td>
<td align="right">10,227</td>
<td align="right">77.9%</td>
<td align="right">-15.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">3,066</td>
<td align="right">20.2%</td>
<td align="right">2,898</td>
<td align="right">22.1%</td>
<td align="right">-5.5%</td>
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
<td align="left">dict keys</td>
<td align="right">105</td>
<td align="right">0.9%</td>
<td align="right">336</td>
<td align="right">3.3%</td>
<td align="right">220.0%</td>
</tr>
<tr>
<td align="left">seq iter</td>
<td align="right">11,802</td>
<td align="right">97.6%</td>
<td align="right">9,702</td>
<td align="right">94.9%</td>
<td align="right">-17.8%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">105</td>
<td align="right">0.9%</td>
<td align="right">105</td>
<td align="right">1.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">map</td>
<td align="right">63</td>
<td align="right">0.5%</td>
<td align="right">63</td>
<td align="right">0.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">21</td>
<td align="right">0.2%</td>
<td align="right">21</td>
<td align="right">0.2%</td>
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
<td align="right">2,283,939</td>
<td align="right">2,283,939 / 0 !!</td>
<td align="right">2,283,939</td>
<td align="right">2,283,939 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">2,242,233</td>
<td align="right">2,242,233 / 0 !!</td>
<td align="right">2,242,233</td>
<td align="right">2,242,233 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">182,196</td>
<td align="right">182,196 / 0 !!</td>
<td align="right">182,196</td>
<td align="right">182,196 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">176,211</td>
<td align="right">176,211 / 0 !!</td>
<td align="right">176,211</td>
<td align="right">176,211 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">1,008</td>
<td align="right">1,008 / 0 !!</td>
<td align="right">1,008</td>
<td align="right">1,008 / 0 !!</td>
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
<td align="right">53,831,316</td>
<td align="right">87.2%</td>
<td align="right">25,193,637</td>
<td align="right">85.2%</td>
<td align="right">-53.2%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">7,864,017</td>
<td align="right">12.7%</td>
<td align="right">4,349,856</td>
<td align="right">14.7%</td>
<td align="right">-44.7%</td>
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
<td align="right">3,612</td>
<td align="right">92.5%</td>
<td align="right">5,502</td>
<td align="right">94.9%</td>
<td align="right">52.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">294</td>
<td align="right">7.5%</td>
<td align="right">294</td>
<td align="right">5.1%</td>
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
<td align="right">294</td>
<td align="right">8.1%</td>
<td align="right">630</td>
<td align="right">11.5%</td>
<td align="right">114.3%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">2,016</td>
<td align="right">55.8%</td>
<td align="right">3,465</td>
<td align="right">63.0%</td>
<td align="right">71.9%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">546</td>
<td align="right">15.1%</td>
<td align="right">693</td>
<td align="right">12.6%</td>
<td align="right">26.9%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">546</td>
<td align="right">15.1%</td>
<td align="right">504</td>
<td align="right">9.2%</td>
<td align="right">-7.7%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">84</td>
<td align="right">2.3%</td>
<td align="right">84</td>
<td align="right">1.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">84</td>
<td align="right">2.3%</td>
<td align="right">84</td>
<td align="right">1.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">21</td>
<td align="right">0.6%</td>
<td align="right">21</td>
<td align="right">0.4%</td>
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
<td align="right">91,918,092</td>
<td align="right">100.0%</td>
<td align="right">47,920,425</td>
<td align="right">100.0%</td>
<td align="right">-47.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">231</td>
<td align="right">0.0%</td>
<td align="right">231</td>
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
<td align="right">315</td>
<td align="right">100.0%</td>
<td align="right">315</td>
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
<td align="right">15,009,057</td>
<td align="right">100.0%</td>
<td align="right">6,053,586</td>
<td align="right">100.0%</td>
<td align="right">-59.7%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

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
<td align="right">35,532</td>
<td align="right">100.0%</td>
<td align="right">35,532</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
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
<td align="right">22,277,619</td>
<td align="right">89.8%</td>
<td align="right">477,162</td>
<td align="right">25.6%</td>
<td align="right">-97.9%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">2,531,340</td>
<td align="right">10.2%</td>
<td align="right">1,387,554</td>
<td align="right">74.4%</td>
<td align="right">-45.2%</td>
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
<td align="right">5,901</td>
<td align="right">100.0%</td>
<td align="right">987</td>
<td align="right">100.0%</td>
<td align="right">-83.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
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
<td align="left">bytearray int</td>
<td align="right">5,607</td>
<td align="right">95.0%</td>
<td align="right">693</td>
<td align="right">70.2%</td>
<td align="right">-87.6%</td>
</tr>
<tr>
<td align="left">py simple</td>
<td align="right">147</td>
<td align="right">2.5%</td>
<td align="right">147</td>
<td align="right">14.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">84</td>
<td align="right">1.4%</td>
<td align="right">84</td>
<td align="right">8.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">63</td>
<td align="right">1.1%</td>
<td align="right">63</td>
<td align="right">6.4%</td>
<td align="right">0.0%</td>
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
<td align="right">28,637,448</td>
<td align="right">93.6%</td>
<td align="right">15,727,572</td>
<td align="right">92.3%</td>
<td align="right">-45.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,841,301</td>
<td align="right">6.0%</td>
<td align="right">1,203,909</td>
<td align="right">7.1%</td>
<td align="right">-34.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">127,638</td>
<td align="right">0.4%</td>
<td align="right">94,416</td>
<td align="right">0.6%</td>
<td align="right">-26.0%</td>
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
<td align="right">2,415</td>
<td align="right">30.6%</td>
<td align="right">1,848</td>
<td align="right">27.4%</td>
<td align="right">-23.5%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">5,481</td>
<td align="right">69.4%</td>
<td align="right">4,893</td>
<td align="right">72.6%</td>
<td align="right">-10.7%</td>
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
<td align="right">294</td>
<td align="right">5.4%</td>
<td align="right">630</td>
<td align="right">12.9%</td>
<td align="right">114.3%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">651</td>
<td align="right">11.9%</td>
<td align="right">1,113</td>
<td align="right">22.7%</td>
<td align="right">71.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">3,150</td>
<td align="right">57.5%</td>
<td align="right">1,806</td>
<td align="right">36.9%</td>
<td align="right">-42.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">1,260</td>
<td align="right">23.0%</td>
<td align="right">1,218</td>
<td align="right">24.9%</td>
<td align="right">-3.3%</td>
</tr>
<tr>
<td align="left">number</td>
<td align="right">105</td>
<td align="right">1.9%</td>
<td align="right">105</td>
<td align="right">2.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">21</td>
<td align="right">0.4%</td>
<td align="right">21</td>
<td align="right">0.4%</td>
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
<td align="right">12,829,026</td>
<td align="right">100.0%</td>
<td align="right">4,295,655</td>
<td align="right">100.0%</td>
<td align="right">-66.5%</td>
</tr>
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
<td align="right">51,256,653</td>
<td align="right">4.2%</td>
<td align="right">14,285,439</td>
<td align="right">2.9%</td>
<td align="right">-72.1%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">720,550,572</td>
<td align="right">59.0%</td>
<td align="right">288,914,724</td>
<td align="right">58.6%</td>
<td align="right">-59.9%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">448,555,254</td>
<td align="right">36.7%</td>
<td align="right">187,820,787</td>
<td align="right">38.1%</td>
<td align="right">-58.1%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">1,744,386</td>
<td align="right">0.1%</td>
<td align="right">1,647,765</td>
<td align="right">0.3%</td>
<td align="right">-5.5%</td>
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
<td align="right">22,277,619</td>
<td align="right">48.1%</td>
<td align="right">477,162</td>
<td align="right">4.3%</td>
<td align="right">-97.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">6,713,721</td>
<td align="right">14.5%</td>
<td align="right">1,309,980</td>
<td align="right">11.7%</td>
<td align="right">-80.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">3,877,545</td>
<td align="right">8.4%</td>
<td align="right">1,353,387</td>
<td align="right">12.1%</td>
<td align="right">-65.1%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">560,196</td>
<td align="right">1.2%</td>
<td align="right">259,623</td>
<td align="right">2.3%</td>
<td align="right">-53.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">7,864,017</td>
<td align="right">17.0%</td>
<td align="right">4,349,856</td>
<td align="right">38.9%</td>
<td align="right">-44.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,226,168</td>
<td align="right">4.8%</td>
<td align="right">1,325,121</td>
<td align="right">11.8%</td>
<td align="right">-40.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,841,301</td>
<td align="right">4.0%</td>
<td align="right">1,203,909</td>
<td align="right">10.8%</td>
<td align="right">-34.6%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">923,811</td>
<td align="right">2.0%</td>
<td align="right">839,727</td>
<td align="right">7.5%</td>
<td align="right">-9.1%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">40,509</td>
<td align="right">0.1%</td>
<td align="right">40,509</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">35,532</td>
<td align="right">0.1%</td>
<td align="right">35,532</td>
<td align="right">0.3%</td>
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
<td align="left">COMPARE_OP_STR</td>
<td align="right">128,835</td>
<td align="right">7.4%</td>
<td align="right">64,344</td>
<td align="right">3.9%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">101,220</td>
<td align="right">5.8%</td>
<td align="right">68,502</td>
<td align="right">4.2%</td>
<td align="right">-32.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">96,936</td>
<td align="right">5.6%</td>
<td align="right">106,722</td>
<td align="right">6.5%</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">6,384</td>
<td align="right">0.4%</td>
<td align="right">5,880</td>
<td align="right">0.4%</td>
<td align="right">-7.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">159,306</td>
<td align="right">9.1%</td>
<td align="right">150,423</td>
<td align="right">9.1%</td>
<td align="right">-5.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">182,805</td>
<td align="right">10.5%</td>
<td align="right">182,889</td>
<td align="right">11.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">1,004,976</td>
<td align="right">57.6%</td>
<td align="right">1,005,081</td>
<td align="right">61.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">40,908</td>
<td align="right">2.3%</td>
<td align="right">40,908</td>
<td align="right">2.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">20,034</td>
<td align="right">1.1%</td>
<td align="right">20,034</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">2,982</td>
<td align="right">0.2%</td>
<td align="right">2,982</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
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
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">26,607,861</td>
<td align="right">81.0%</td>
<td align="right">26,607,861</td>
<td align="right">81.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
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
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
<td align="right">6,225,597</td>
<td align="right">19.0%</td>
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
<td align="right">6,020,343</td>
<td align="right">18.3%</td>
<td align="right">6,020,343</td>
<td align="right">18.3%</td>
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
<td align="right">2,417,877</td>
<td align="right">7.4%</td>
<td align="right">2,417,877</td>
<td align="right">7.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">34,365,681</td>
<td align="right">104.7%</td>
<td align="right">34,365,681</td>
<td align="right">104.7%</td>
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
<td align="left">Method cache dunder misses</td>
<td align="right">3</td>
<td align="right"></td>
<td align="right">45</td>
<td align="right"></td>
<td align="right">1,400.0%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">335,850</td>
<td align="right"></td>
<td align="right">245</td>
<td align="right"></td>
<td align="right">-99.9%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">335,827</td>
<td align="right"></td>
<td align="right">252</td>
<td align="right"></td>
<td align="right">-99.9%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">1,638</td>
<td align="right">0.0%</td>
<td align="right">1,974</td>
<td align="right">0.0%</td>
<td align="right">20.5%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">7,578,987</td>
<td align="right"></td>
<td align="right">7,915,810</td>
<td align="right"></td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">222,401,697</td>
<td align="right">55.4%</td>
<td align="right">225,530,067</td>
<td align="right">55.8%</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">31,437</td>
<td align="right">0.1%</td>
<td align="right">31,878</td>
<td align="right">0.1%</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">257,549,019</td>
<td align="right">56.4%</td>
<td align="right">260,837,178</td>
<td align="right">56.8%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">84,085,922</td>
<td align="right">20.9%</td>
<td align="right">83,588,684</td>
<td align="right">20.7%</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">87,899,498</td>
<td align="right">19.2%</td>
<td align="right">87,401,440</td>
<td align="right">19.0%</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">12,758,067</td>
<td align="right">2.8%</td>
<td align="right">12,717,138</td>
<td align="right">2.8%</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">98,532,433</td>
<td align="right">21.6%</td>
<td align="right">98,372,385</td>
<td align="right">21.4%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">11,854,019</td>
<td align="right">21.1%</td>
<td align="right">11,854,817</td>
<td align="right">21.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">14,991,855</td>
<td align="right"></td>
<td align="right">14,992,548</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">78,817,947</td>
<td align="right">19.6%</td>
<td align="right">78,819,115</td>
<td align="right">19.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">16,451,064</td>
<td align="right">4.1%</td>
<td align="right">16,451,127</td>
<td align="right">4.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">11,820,944</td>
<td align="right">21.0%</td>
<td align="right">11,820,965</td>
<td align="right">21.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">13,874,490</td>
<td align="right"></td>
<td align="right">13,874,512</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">44,327,155</td>
<td align="right">78.9%</td>
<td align="right">44,327,155</td>
<td align="right">78.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">44,336,649</td>
<td align="right"></td>
<td align="right">44,336,649</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">1,532,223</td>
<td align="right"></td>
<td align="right">1,532,223</td>
<td align="right"></td>
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
