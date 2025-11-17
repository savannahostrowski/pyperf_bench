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
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">12,584,480</td>
<td align="right">966</td>
<td align="right">-100.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">2,609,817</td>
<td align="right">46,830</td>
<td align="right">-98.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">2,633,565</td>
<td align="right">58,086</td>
<td align="right">-97.8%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">3,937,920</td>
<td align="right">519,067</td>
<td align="right">-86.8%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">1,727,440</td>
<td align="right">307,685</td>
<td align="right">-82.2%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">3,399,039</td>
<td align="right">649,420</td>
<td align="right">-80.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">5,476,506</td>
<td align="right">1,064,280</td>
<td align="right">-80.6%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">3,485,538</td>
<td align="right">691,630</td>
<td align="right">-80.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">5,639,760</td>
<td align="right">1,154,496</td>
<td align="right">-79.5%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">2,261,784</td>
<td align="right">476,298</td>
<td align="right">-78.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">11,504,451</td>
<td align="right">2,454,649</td>
<td align="right">-78.7%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">11,500,253</td>
<td align="right">2,460,214</td>
<td align="right">-78.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">1,089,501</td>
<td align="right">251,979</td>
<td align="right">-76.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">2,741,739</td>
<td align="right">736,959</td>
<td align="right">-73.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">6,001,380</td>
<td align="right">1,625,990</td>
<td align="right">-72.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">87,181,210</td>
<td align="right">24,697,256</td>
<td align="right">-71.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">7,496,623</td>
<td align="right">2,172,412</td>
<td align="right">-71.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">51,705,572</td>
<td align="right">15,267,525</td>
<td align="right">-70.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">10,419,005</td>
<td align="right">3,108,141</td>
<td align="right">-70.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">177,938,438</td>
<td align="right">54,076,239</td>
<td align="right">-69.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">46,521,121</td>
<td align="right">14,152,139</td>
<td align="right">-69.6%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">6,930,903</td>
<td align="right">2,136,945</td>
<td align="right">-69.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">1,092,945</td>
<td align="right">339,103</td>
<td align="right">-69.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">23,764,887</td>
<td align="right">7,400,560</td>
<td align="right">-68.9%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">12,203,104</td>
<td align="right">3,816,551</td>
<td align="right">-68.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">14,708,800</td>
<td align="right">4,646,633</td>
<td align="right">-68.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">706,713</td>
<td align="right">228,270</td>
<td align="right">-67.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">16,589,203</td>
<td align="right">5,413,932</td>
<td align="right">-67.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">6,846,000</td>
<td align="right">2,238,423</td>
<td align="right">-67.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">13,525,344</td>
<td align="right">4,422,475</td>
<td align="right">-67.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">732,249</td>
<td align="right">242,088</td>
<td align="right">-66.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">13,752,901</td>
<td align="right">4,579,486</td>
<td align="right">-66.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">1,841,911</td>
<td align="right">613,942</td>
<td align="right">-66.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">14,224,648</td>
<td align="right">4,803,528</td>
<td align="right">-66.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">15,779,804</td>
<td align="right">5,405,265</td>
<td align="right">-65.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">2,412,879</td>
<td align="right">845,488</td>
<td align="right">-65.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">2,191,140</td>
<td align="right">772,020</td>
<td align="right">-64.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">407,925</td>
<td align="right">144,899</td>
<td align="right">-64.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">55,770,342</td>
<td align="right">19,835,336</td>
<td align="right">-64.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">23,033,415</td>
<td align="right">8,204,376</td>
<td align="right">-64.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">3,161,782</td>
<td align="right">1,138,730</td>
<td align="right">-64.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">15,791,748</td>
<td align="right">5,754,707</td>
<td align="right">-63.6%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">1,252,650</td>
<td align="right">457,432</td>
<td align="right">-63.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">6,113,858</td>
<td align="right">2,312,354</td>
<td align="right">-62.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">5,133,934</td>
<td align="right">1,944,665</td>
<td align="right">-62.1%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">1,607,005</td>
<td align="right">610,460</td>
<td align="right">-62.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">435,876</td>
<td align="right">166,676</td>
<td align="right">-61.8%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">6,606,286</td>
<td align="right">2,581,695</td>
<td align="right">-60.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">1,089,480</td>
<td align="right">427,352</td>
<td align="right">-60.8%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">2,931,180</td>
<td align="right">1,155,008</td>
<td align="right">-60.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">2,310,357</td>
<td align="right">916,969</td>
<td align="right">-60.3%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">210</td>
<td align="right">84</td>
<td align="right">-60.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,434,802</td>
<td align="right">994,501</td>
<td align="right">-59.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">10,399,601</td>
<td align="right">4,254,835</td>
<td align="right">-59.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">3,867,738</td>
<td align="right">1,637,289</td>
<td align="right">-57.7%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">1,846,111</td>
<td align="right">786,297</td>
<td align="right">-57.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">1,673,596</td>
<td align="right">719,462</td>
<td align="right">-57.0%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">8,200,694</td>
<td align="right">3,538,797</td>
<td align="right">-56.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">2,395,366</td>
<td align="right">1,054,573</td>
<td align="right">-56.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">726,663</td>
<td align="right">320,155</td>
<td align="right">-55.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">919,527</td>
<td align="right">406,707</td>
<td align="right">-55.8%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">1,592,726</td>
<td align="right">704,820</td>
<td align="right">-55.7%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">1,199,583</td>
<td align="right">537,023</td>
<td align="right">-55.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">1,143,156</td>
<td align="right">512,294</td>
<td align="right">-55.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">1,710,912</td>
<td align="right">766,784</td>
<td align="right">-55.2%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,789,830</td>
<td align="right">808,426</td>
<td align="right">-54.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">6,138,531</td>
<td align="right">2,802,796</td>
<td align="right">-54.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">6,715,316</td>
<td align="right">3,067,957</td>
<td align="right">-54.3%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">1,767,740</td>
<td align="right">815,464</td>
<td align="right">-53.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">406,329</td>
<td align="right">188,667</td>
<td align="right">-53.6%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">2,932,188</td>
<td align="right">1,376,232</td>
<td align="right">-53.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">1,197,083</td>
<td align="right">577,163</td>
<td align="right">-51.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">9,156</td>
<td align="right">4,494</td>
<td align="right">-50.9%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">786,898</td>
<td align="right">387,009</td>
<td align="right">-50.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">1,869</td>
<td align="right">924</td>
<td align="right">-50.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">12,033</td>
<td align="right">5,964</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">4,137</td>
<td align="right">2,058</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">500,997</td>
<td align="right">250,210</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">702,072</td>
<td align="right">351,036</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">126</td>
<td align="right">63</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">702,156</td>
<td align="right">351,120</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">351,078</td>
<td align="right">175,560</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">393,309</td>
<td align="right">196,686</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">599,949</td>
<td align="right">300,258</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">353,809</td>
<td align="right">177,282</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">97,104</td>
<td align="right">48,657</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">356,517</td>
<td align="right">178,836</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">353,766</td>
<td align="right">177,471</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">1,571,766</td>
<td align="right">788,582</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">354,502</td>
<td align="right">177,975</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">140,574</td>
<td align="right">70,581</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">1,800,056</td>
<td align="right">909,253</td>
<td align="right">-49.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">357,969</td>
<td align="right">180,936</td>
<td align="right">-49.5%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">401,709</td>
<td align="right">203,721</td>
<td align="right">-49.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">35,301</td>
<td align="right">17,990</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">974,526</td>
<td align="right">496,986</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,187,025</td>
<td align="right">609,063</td>
<td align="right">-48.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">6,363</td>
<td align="right">3,276</td>
<td align="right">-48.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">766,501</td>
<td align="right">398,407</td>
<td align="right">-48.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">769,210</td>
<td align="right">399,982</td>
<td align="right">-48.0%</td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">3,255</td>
<td align="right">1,806</td>
<td align="right">-44.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">12,222</td>
<td align="right">6,804</td>
<td align="right">-44.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">13,713</td>
<td align="right">7,665</td>
<td align="right">-44.1%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">147</td>
<td align="right">84</td>
<td align="right">-42.9%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">1,218</td>
<td align="right">714</td>
<td align="right">-41.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">9,912</td>
<td align="right">6,006</td>
<td align="right">-39.4%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">1,282</td>
<td align="right">777</td>
<td align="right">-39.4%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">189</td>
<td align="right">126</td>
<td align="right">-33.3%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">189</td>
<td align="right">126</td>
<td align="right">-33.3%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">189</td>
<td align="right">126</td>
<td align="right">-33.3%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">630</td>
<td align="right">441</td>
<td align="right">-30.0%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">210</td>
<td align="right">147</td>
<td align="right">-30.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">11,865</td>
<td align="right">8,652</td>
<td align="right">-27.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">9,282</td>
<td align="right">7,644</td>
<td align="right">-17.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">14,301</td>
<td align="right">11,844</td>
<td align="right">-17.2%</td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">399</td>
<td align="right">336</td>
<td align="right">-15.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">819</td>
<td align="right">693</td>
<td align="right">-15.4%</td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">420</td>
<td align="right">357</td>
<td align="right">-15.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">966</td>
<td align="right">903</td>
<td align="right">-6.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">924</td>
<td align="right">903</td>
<td align="right">-2.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">40,782</td>
<td align="right">39,900</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">59,893</td>
<td align="right">59,010</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">10,122</td>
<td align="right">10,080</td>
<td align="right">-0.4%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">18,360</td>
<td align="right">18,312</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">988</td>
<td align="right">987</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">1,009</td>
<td align="right">1,008</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">1,219</td>
<td align="right">1,218</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">7,498</td>
<td align="right">7,497</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">21,588</td>
<td align="right">21,588</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">12,243</td>
<td align="right">12,243</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">6,846</td>
<td align="right">6,846</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">4,599</td>
<td align="right">4,599</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">1,428</td>
<td align="right">1,428</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">1,008</td>
<td align="right">1,008</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">861</td>
<td align="right">861</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">861</td>
<td align="right">861</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">861</td>
<td align="right">861</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">819</td>
<td align="right">819</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">756</td>
<td align="right">756</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">693</td>
<td align="right">693</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">672</td>
<td align="right">672</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">651</td>
<td align="right">651</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">630</td>
<td align="right">630</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">462</td>
<td align="right">462</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">420</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FROM_DICT_OR_DEREF</td>
<td align="right">336</td>
<td align="right">336</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">210</td>
<td align="right">210</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">189</td>
<td align="right">189</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">168</td>
<td align="right">168</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
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
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DICT_UPDATE</td>
<td align="right">21</td>
<td align="right">21</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">1,807,654</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">1,161,841</td>
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
<td align="right">31,708,867</td>
<td align="right">83.8%</td>
<td align="right">9,459,910</td>
<td align="right">80.1%</td>
<td align="right">-70.2%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">6,101,656</td>
<td align="right">16.1%</td>
<td align="right">2,299,285</td>
<td align="right">19.5%</td>
<td align="right">-62.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">33,432</td>
<td align="right">0.1%</td>
<td align="right">33,327</td>
<td align="right">0.3%</td>
<td align="right">-0.3%</td>
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
<td align="right">8,085</td>
<td align="right">63.1%</td>
<td align="right">8,953</td>
<td align="right">65.4%</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">4,726</td>
<td align="right">36.9%</td>
<td align="right">4,746</td>
<td align="right">34.6%</td>
<td align="right">0.4%</td>
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
<td align="left">subscr bytes</td>
<td align="right">84</td>
<td align="right">1.0%</td>
<td align="right">42</td>
<td align="right">0.5%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">xor</td>
<td align="right">420</td>
<td align="right">5.2%</td>
<td align="right">622</td>
<td align="right">6.9%</td>
<td align="right">48.1%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">63</td>
<td align="right">0.8%</td>
<td align="right">42</td>
<td align="right">0.5%</td>
<td align="right">-33.3%</td>
</tr>
<tr>
<td align="left">subscr</td>
<td align="right">1,092</td>
<td align="right">13.5%</td>
<td align="right">1,324</td>
<td align="right">14.8%</td>
<td align="right">21.2%</td>
</tr>
<tr>
<td align="left">subscr other slice</td>
<td align="right">714</td>
<td align="right">8.8%</td>
<td align="right">840</td>
<td align="right">9.4%</td>
<td align="right">17.6%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">252</td>
<td align="right">3.1%</td>
<td align="right">210</td>
<td align="right">2.3%</td>
<td align="right">-16.7%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">147</td>
<td align="right">1.8%</td>
<td align="right">126</td>
<td align="right">1.4%</td>
<td align="right">-14.3%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">4,977</td>
<td align="right">61.6%</td>
<td align="right">5,411</td>
<td align="right">60.4%</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">subscr string slice</td>
<td align="right">147</td>
<td align="right">1.8%</td>
<td align="right">147</td>
<td align="right">1.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">84</td>
<td align="right">1.0%</td>
<td align="right">84</td>
<td align="right">0.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">84</td>
<td align="right">1.0%</td>
<td align="right">84</td>
<td align="right">0.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">21</td>
<td align="right">0.3%</td>
<td align="right">21</td>
<td align="right">0.2%</td>
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
<td align="right">1,252,650</td>
<td align="right">100.0%</td>
<td align="right">457,432</td>
<td align="right">100.0%</td>
<td align="right">-63.5%</td>
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
<td align="right">5,743,269</td>
<td align="right">16.4%</td>
<td align="right">1,213,053</td>
<td align="right">10.7%</td>
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
<td align="right">5,645,538</td>
<td align="right">16.1%</td>
<td align="right">1,200,578</td>
<td align="right">10.6%</td>
<td align="right">-78.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">29,288,117</td>
<td align="right">83.6%</td>
<td align="right">10,074,352</td>
<td align="right">89.1%</td>
<td align="right">-65.6%</td>
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
<td align="right">116,091</td>
<td align="right">100.0%</td>
<td align="right">30,787</td>
<td align="right">100.0%</td>
<td align="right">-73.5%</td>
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
<td align="right">210</td>
<td align="right">50.0%</td>
<td align="right">210</td>
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
<td align="right">26,197,816</td>
<td align="right">91.5%</td>
<td align="right">7,093,323</td>
<td align="right">89.3%</td>
<td align="right">-72.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,406,474</td>
<td align="right">8.4%</td>
<td align="right">839,028</td>
<td align="right">10.6%</td>
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
<td align="right">15,477</td>
<td align="right">0.1%</td>
<td align="right">8,001</td>
<td align="right">0.1%</td>
<td align="right">-48.3%</td>
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
<td align="right">2,961</td>
<td align="right">44.3%</td>
<td align="right">2,877</td>
<td align="right">43.3%</td>
<td align="right">-2.8%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">3,717</td>
<td align="right">55.7%</td>
<td align="right">3,772</td>
<td align="right">56.7%</td>
<td align="right">1.5%</td>
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
<td align="left">bytes</td>
<td align="right">399</td>
<td align="right">10.7%</td>
<td align="right">294</td>
<td align="right">7.8%</td>
<td align="right">-26.3%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">693</td>
<td align="right">18.6%</td>
<td align="right">852</td>
<td align="right">22.6%</td>
<td align="right">22.9%</td>
</tr>
<tr>
<td align="left">long float</td>
<td align="right">252</td>
<td align="right">6.8%</td>
<td align="right">210</td>
<td align="right">5.6%</td>
<td align="right">-16.7%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">735</td>
<td align="right">19.8%</td>
<td align="right">651</td>
<td align="right">17.3%</td>
<td align="right">-11.4%</td>
</tr>
<tr>
<td align="left">different types</td>
<td align="right">1,491</td>
<td align="right">40.1%</td>
<td align="right">1,618</td>
<td align="right">42.9%</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">126</td>
<td align="right">3.4%</td>
<td align="right">126</td>
<td align="right">3.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">21</td>
<td align="right">0.6%</td>
<td align="right">21</td>
<td align="right">0.6%</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">6,728,043</td>
<td align="right">88.0%</td>
<td align="right">1,946,145</td>
<td align="right">82.7%</td>
<td align="right">-71.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">916,125</td>
<td align="right">12.0%</td>
<td align="right">403,367</td>
<td align="right">17.1%</td>
<td align="right">-56.0%</td>
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
<td align="right">2,436</td>
<td align="right">71.6%</td>
<td align="right">2,374</td>
<td align="right">71.1%</td>
<td align="right">-2.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">966</td>
<td align="right">28.4%</td>
<td align="right">966</td>
<td align="right">28.9%</td>
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
<td align="right">987</td>
<td align="right">40.5%</td>
<td align="right">1,261</td>
<td align="right">53.1%</td>
<td align="right">27.8%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">168</td>
<td align="right">6.9%</td>
<td align="right">126</td>
<td align="right">5.3%</td>
<td align="right">-25.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">1,239</td>
<td align="right">50.9%</td>
<td align="right">945</td>
<td align="right">39.8%</td>
<td align="right">-23.7%</td>
</tr>
<tr>
<td align="left">str</td>
<td align="right">42</td>
<td align="right">1.7%</td>
<td align="right">42</td>
<td align="right">1.8%</td>
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
<td align="right">4,924,140</td>
<td align="right">72.8%</td>
<td align="right">930,720</td>
<td align="right">60.2%</td>
<td align="right">-81.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,840,021</td>
<td align="right">27.2%</td>
<td align="right">611,830</td>
<td align="right">39.6%</td>
<td align="right">-66.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">252</td>
<td align="right">0.0%</td>
<td align="right">252</td>
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
<td align="right">1,512</td>
<td align="right">80.0%</td>
<td align="right">1,755</td>
<td align="right">83.1%</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">378</td>
<td align="right">20.0%</td>
<td align="right">357</td>
<td align="right">16.9%</td>
<td align="right">-5.6%</td>
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
<td align="right">63</td>
<td align="right">4.2%</td>
<td align="right">42</td>
<td align="right">2.4%</td>
<td align="right">-33.3%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">735</td>
<td align="right">48.6%</td>
<td align="right">894</td>
<td align="right">50.9%</td>
<td align="right">21.6%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">525</td>
<td align="right">34.7%</td>
<td align="right">630</td>
<td align="right">35.9%</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">168</td>
<td align="right">11.1%</td>
<td align="right">168</td>
<td align="right">9.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">21</td>
<td align="right">1.4%</td>
<td align="right">21</td>
<td align="right">1.2%</td>
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
<td align="left">self</td>
<td align="right">593,460</td>
<td align="right">593,460 / 0 !!</td>
<td align="right">296,730</td>
<td align="right">296,730 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">962,052</td>
<td align="right">962,052 / 0 !!</td>
<td align="right">482,496</td>
<td align="right">482,496 / 0 !!</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">240,512</td>
<td align="right">240,512 / 0 !!</td>
<td align="right">127,680</td>
<td align="right">127,680 / 0 !!</td>
<td align="right">-46.9%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">3,654</td>
<td align="right">3,654 / 0 !!</td>
<td align="right">2,709</td>
<td align="right">2,709 / 0 !!</td>
<td align="right">-25.9%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">273</td>
<td align="right">273 / 0 !!</td>
<td align="right">273</td>
<td align="right">273 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">84</td>
<td align="right">84 / 0 !!</td>
<td align="right">84</td>
<td align="right">84 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">21</td>
<td align="right">21 / 0 !!</td>
<td align="right">21</td>
<td align="right">21 / 0 !!</td>
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
<td align="right">118,489,634</td>
<td align="right">95.8%</td>
<td align="right">36,733,333</td>
<td align="right">94.9%</td>
<td align="right">-69.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">5,109,448</td>
<td align="right">4.1%</td>
<td align="right">1,921,376</td>
<td align="right">5.0%</td>
<td align="right">-62.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">26,838</td>
<td align="right">0.0%</td>
<td align="right">24,738</td>
<td align="right">0.1%</td>
<td align="right">-7.8%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
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
<td align="left">Failure</td>
<td align="right">8,694</td>
<td align="right">35.5%</td>
<td align="right">7,665</td>
<td align="right">32.5%</td>
<td align="right">-11.8%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">15,771</td>
<td align="right">64.5%</td>
<td align="right">15,897</td>
<td align="right">67.5%</td>
<td align="right">0.8%</td>
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
<td align="left">metaclass attribute</td>
<td align="right">42</td>
<td align="right">0.5%</td>
<td align="right">21</td>
<td align="right">0.3%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">567</td>
<td align="right">6.5%</td>
<td align="right">420</td>
<td align="right">5.5%</td>
<td align="right">-25.9%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">84</td>
<td align="right">1.0%</td>
<td align="right">63</td>
<td align="right">0.8%</td>
<td align="right">-25.0%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">5,376</td>
<td align="right">61.8%</td>
<td align="right">4,507</td>
<td align="right">58.8%</td>
<td align="right">-16.2%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">483</td>
<td align="right">5.6%</td>
<td align="right">420</td>
<td align="right">5.5%</td>
<td align="right">-13.0%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">1,407</td>
<td align="right">16.2%</td>
<td align="right">1,436</td>
<td align="right">18.7%</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">42</td>
<td align="right">0.5%</td>
<td align="right">42</td>
<td align="right">0.5%</td>
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
<td align="right">20,938,830</td>
<td align="right">99.9%</td>
<td align="right">7,870,918</td>
<td align="right">99.9%</td>
<td align="right">-62.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,134</td>
<td align="right">0.0%</td>
<td align="right">567</td>
<td align="right">0.0%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">5,229</td>
<td align="right">0.0%</td>
<td align="right">5,208</td>
<td align="right">0.1%</td>
<td align="right">-0.4%</td>
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
<td align="right">4,893</td>
<td align="right">100.0%</td>
<td align="right">4,872</td>
<td align="right">100.0%</td>
<td align="right">-0.4%</td>
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
<td align="right">399</td>
<td align="right">76.0%</td>
<td align="right">210</td>
<td align="right">62.5%</td>
<td align="right">-47.4%</td>
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
<td align="right">12.0%</td>
<td align="right">63</td>
<td align="right">18.8%</td>
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
<td align="right">13,517,070</td>
<td align="right">92.1%</td>
<td align="right">4,407,691</td>
<td align="right">89.2%</td>
<td align="right">-67.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,137,423</td>
<td align="right">7.7%</td>
<td align="right">506,531</td>
<td align="right">10.3%</td>
<td align="right">-55.5%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">20,307</td>
<td align="right">0.1%</td>
<td align="right">20,748</td>
<td align="right">0.4%</td>
<td align="right">2.2%</td>
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
<td align="right">3,969</td>
<td align="right">65.9%</td>
<td align="right">4,179</td>
<td align="right">66.7%</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">2,058</td>
<td align="right">34.1%</td>
<td align="right">2,088</td>
<td align="right">33.3%</td>
<td align="right">1.5%</td>
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
<td align="left">no dict</td>
<td align="right">42</td>
<td align="right">2.0%</td>
<td align="right">21</td>
<td align="right">1.0%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">split dict</td>
<td align="right">378</td>
<td align="right">18.4%</td>
<td align="right">294</td>
<td align="right">14.1%</td>
<td align="right">-22.2%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">546</td>
<td align="right">26.5%</td>
<td align="right">609</td>
<td align="right">29.2%</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">1,092</td>
<td align="right">53.1%</td>
<td align="right">1,164</td>
<td align="right">55.7%</td>
<td align="right">6.6%</td>
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
<td align="right">2,608,578</td>
<td align="right">46.8%</td>
<td align="right">46,116</td>
<td align="right">6.1%</td>
<td align="right">-98.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">2,968,497</td>
<td align="right">53.2%</td>
<td align="right">704,568</td>
<td align="right">93.8%</td>
<td align="right">-76.3%</td>
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
<td align="right">756</td>
<td align="right">61.0%</td>
<td align="right">231</td>
<td align="right">32.4%</td>
<td align="right">-69.4%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">483</td>
<td align="right">39.0%</td>
<td align="right">483</td>
<td align="right">67.6%</td>
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
<td align="left">bytearray int</td>
<td align="right">735</td>
<td align="right">97.2%</td>
<td align="right">210</td>
<td align="right">90.9%</td>
<td align="right">-71.4%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">21</td>
<td align="right">2.8%</td>
<td align="right">21</td>
<td align="right">9.1%</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">7,491,730</td>
<td align="right">25.9%</td>
<td align="right">2,166,352</td>
<td align="right">23.2%</td>
<td align="right">-71.1%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">21,394,171</td>
<td align="right">73.9%</td>
<td align="right">7,139,279</td>
<td align="right">76.4%</td>
<td align="right">-66.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">54,705</td>
<td align="right">0.2%</td>
<td align="right">30,312</td>
<td align="right">0.3%</td>
<td align="right">-44.6%</td>
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
<td align="right">3,087</td>
<td align="right">52.3%</td>
<td align="right">4,254</td>
<td align="right">64.2%</td>
<td align="right">37.8%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">2,814</td>
<td align="right">47.7%</td>
<td align="right">2,374</td>
<td align="right">35.8%</td>
<td align="right">-15.6%</td>
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
<td align="left">mapping</td>
<td align="right">357</td>
<td align="right">11.6%</td>
<td align="right">693</td>
<td align="right">16.3%</td>
<td align="right">94.1%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">1,806</td>
<td align="right">58.5%</td>
<td align="right">2,805</td>
<td align="right">65.9%</td>
<td align="right">55.3%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">210</td>
<td align="right">6.8%</td>
<td align="right">168</td>
<td align="right">3.9%</td>
<td align="right">-20.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">105</td>
<td align="right">3.4%</td>
<td align="right">84</td>
<td align="right">2.0%</td>
<td align="right">-20.0%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">609</td>
<td align="right">19.7%</td>
<td align="right">504</td>
<td align="right">11.8%</td>
<td align="right">-17.2%</td>
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
<td align="right">771,331</td>
<td align="right">99.9%</td>
<td align="right">401,158</td>
<td align="right">99.9%</td>
<td align="right">-48.0%</td>
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
<td align="right">231</td>
<td align="right">100.0%</td>
<td align="right">231</td>
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
<td align="right">5,895,414</td>
<td align="right">0.7%</td>
<td align="right">1,331,020</td>
<td align="right">0.5%</td>
<td align="right">-77.4%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">314,509,594</td>
<td align="right">39.1%</td>
<td align="right">96,994,180</td>
<td align="right">38.0%</td>
<td align="right">-69.2%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">452,572,385</td>
<td align="right">56.3%</td>
<td align="right">146,906,719</td>
<td align="right">57.5%</td>
<td align="right">-67.5%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">30,753,901</td>
<td align="right">3.8%</td>
<td align="right">10,250,777</td>
<td align="right">4.0%</td>
<td align="right">-66.7%</td>
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
<td align="right">2,608,578</td>
<td align="right">7.6%</td>
<td align="right">46,116</td>
<td align="right">0.4%</td>
<td align="right">-98.2%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">5,645,538</td>
<td align="right">16.4%</td>
<td align="right">1,200,578</td>
<td align="right">11.5%</td>
<td align="right">-78.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">7,491,730</td>
<td align="right">21.7%</td>
<td align="right">2,166,352</td>
<td align="right">20.7%</td>
<td align="right">-71.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">1,840,021</td>
<td align="right">5.3%</td>
<td align="right">611,830</td>
<td align="right">5.9%</td>
<td align="right">-66.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">2,406,474</td>
<td align="right">7.0%</td>
<td align="right">839,028</td>
<td align="right">8.0%</td>
<td align="right">-65.1%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">1,252,650</td>
<td align="right">3.6%</td>
<td align="right">457,432</td>
<td align="right">4.4%</td>
<td align="right">-63.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">5,109,448</td>
<td align="right">14.8%</td>
<td align="right">1,921,376</td>
<td align="right">18.4%</td>
<td align="right">-62.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">6,101,656</td>
<td align="right">17.7%</td>
<td align="right">2,299,285</td>
<td align="right">22.0%</td>
<td align="right">-62.3%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">916,125</td>
<td align="right">2.7%</td>
<td align="right">403,367</td>
<td align="right">3.9%</td>
<td align="right">-56.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">1,137,423</td>
<td align="right">3.3%</td>
<td align="right">506,531</td>
<td align="right">4.8%</td>
<td align="right">-55.5%</td>
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
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">2,729,832</td>
<td align="right">46.3%</td>
<td align="right">174,713</td>
<td align="right">13.1%</td>
<td align="right">-93.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,730,840</td>
<td align="right">46.3%</td>
<td align="right">896,863</td>
<td align="right">67.4%</td>
<td align="right">-67.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">9,303</td>
<td align="right">0.2%</td>
<td align="right">15,288</td>
<td align="right">1.1%</td>
<td align="right">64.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">25,725</td>
<td align="right">0.4%</td>
<td align="right">12,349</td>
<td align="right">0.9%</td>
<td align="right">-52.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">271,236</td>
<td align="right">4.6%</td>
<td align="right">135,618</td>
<td align="right">10.2%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">15,477</td>
<td align="right">0.3%</td>
<td align="right">8,001</td>
<td align="right">0.6%</td>
<td align="right">-48.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">28,560</td>
<td align="right">0.5%</td>
<td align="right">17,837</td>
<td align="right">1.3%</td>
<td align="right">-37.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">12,978</td>
<td align="right">0.2%</td>
<td align="right">9,744</td>
<td align="right">0.7%</td>
<td align="right">-24.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">33,012</td>
<td align="right">0.6%</td>
<td align="right">32,907</td>
<td align="right">2.5%</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">11,004</td>
<td align="right">0.2%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">6,447</td>
<td align="right">0.5%</td>
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
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">353,514</td>
<td align="right">1.5%</td>
<td align="right">177,303</td>
<td align="right">1.5%</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">23,367,566</td>
<td align="right">98.3%</td>
<td align="right">11,725,644</td>
<td align="right">98.3%</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">23,033,772</td>
<td align="right">96.9%</td>
<td align="right">11,562,327</td>
<td align="right">96.9%</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">401,227</td>
<td align="right">1.7%</td>
<td align="right">203,238</td>
<td align="right">1.7%</td>
<td align="right">-49.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">401,941</td>
<td align="right">1.7%</td>
<td align="right">203,952</td>
<td align="right">1.7%</td>
<td align="right">-49.3%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">402,130</td>
<td align="right">1.7%</td>
<td align="right">204,141</td>
<td align="right">1.7%</td>
<td align="right">-49.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">402,130</td>
<td align="right">1.7%</td>
<td align="right">204,141</td>
<td align="right">1.7%</td>
<td align="right">-49.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">17,178</td>
<td align="right">0.1%</td>
<td align="right">9,933</td>
<td align="right">0.1%</td>
<td align="right">-42.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">336</td>
<td align="right">0.0%</td>
<td align="right">210</td>
<td align="right">0.0%</td>
<td align="right">-37.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">189</td>
<td align="right">0.0%</td>
<td align="right">189</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">672</td>
<td align="right">0.0%</td>
<td align="right">672</td>
<td align="right">0.0%</td>
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
<td align="right">1,596</td>
<td align="right">0.0%</td>
<td align="right">1,596</td>
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
<td align="left">Frees</td>
<td align="right">10,566,452</td>
<td align="right"></td>
<td align="right">4,664,164</td>
<td align="right"></td>
<td align="right">-55.9%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">181,410,540</td>
<td align="right">56.1%</td>
<td align="right">91,035,367</td>
<td align="right">55.5%</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">55,522,957</td>
<td align="right">16.8%</td>
<td align="right">27,923,533</td>
<td align="right">16.6%</td>
<td align="right">-49.7%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">367,836</td>
<td align="right"></td>
<td align="right">185,073</td>
<td align="right"></td>
<td align="right">-49.7%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">73,702,313</td>
<td align="right">22.8%</td>
<td align="right">37,228,664</td>
<td align="right">22.7%</td>
<td align="right">-49.5%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">220,668</td>
<td align="right">0.6%</td>
<td align="right">111,762</td>
<td align="right">0.6%</td>
<td align="right">-49.4%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">7,157,894</td>
<td align="right"></td>
<td align="right">3,627,139</td>
<td align="right"></td>
<td align="right">-49.3%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">4,985,296</td>
<td align="right">1.5%</td>
<td align="right">2,528,022</td>
<td align="right">1.5%</td>
<td align="right">-49.3%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">4,121,670</td>
<td align="right">1.2%</td>
<td align="right">2,092,272</td>
<td align="right">1.2%</td>
<td align="right">-49.2%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">219,344,234</td>
<td align="right">66.4%</td>
<td align="right">111,398,333</td>
<td align="right">66.4%</td>
<td align="right">-49.2%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">11,236,223</td>
<td align="right">32.8%</td>
<td align="right">5,731,489</td>
<td align="right">30.8%</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">11,006,210</td>
<td align="right">32.1%</td>
<td align="right">5,614,604</td>
<td align="right">30.2%</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">51,594,679</td>
<td align="right">15.6%</td>
<td align="right">26,430,793</td>
<td align="right">15.7%</td>
<td align="right">-48.8%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">908,161</td>
<td align="right"></td>
<td align="right">475,307</td>
<td align="right"></td>
<td align="right">-47.7%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">63,338,135</td>
<td align="right">19.6%</td>
<td align="right">33,242,362</td>
<td align="right">20.3%</td>
<td align="right">-47.5%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">9,345</td>
<td align="right">0.0%</td>
<td align="right">5,123</td>
<td align="right">0.0%</td>
<td align="right">-45.2%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">23,026,168</td>
<td align="right"></td>
<td align="right">12,880,392</td>
<td align="right"></td>
<td align="right">-44.1%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">23,030,178</td>
<td align="right">67.2%</td>
<td align="right">12,884,443</td>
<td align="right">69.2%</td>
<td align="right">-44.1%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">14,488</td>
<td align="right"></td>
<td align="right">11,461</td>
<td align="right"></td>
<td align="right">-20.9%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">2,966</td>
<td align="right"></td>
<td align="right">2,396</td>
<td align="right"></td>
<td align="right">-19.2%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">13,502</td>
<td align="right"></td>
<td align="right">10,992</td>
<td align="right"></td>
<td align="right">-18.6%</td>
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
<td align="right">882</td>
<td align="right">592,221</td>
<td align="right">10,897,732</td>
<td align="right">996,177</td>
<td align="right">793,044</td>
<td align="right">441</td>
<td align="right">483</td>
<td align="right">5,431,102</td>
<td align="right">733,488</td>
<td align="right">48,867</td>
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
