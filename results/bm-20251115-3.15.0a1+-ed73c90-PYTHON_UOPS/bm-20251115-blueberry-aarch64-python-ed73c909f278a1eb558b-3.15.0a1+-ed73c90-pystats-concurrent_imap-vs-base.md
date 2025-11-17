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
<td align="right">69,150,212</td>
<td align="right">17,001</td>
<td align="right">-100.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">37,006,963</td>
<td align="right">683,355</td>
<td align="right">-98.2%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">29,167,883</td>
<td align="right">614,604</td>
<td align="right">-97.9%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">4,132,828</td>
<td align="right">89,017</td>
<td align="right">-97.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">29,221,291</td>
<td align="right">666,452</td>
<td align="right">-97.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">8,230,434</td>
<td align="right">194,365</td>
<td align="right">-97.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">12,398,459</td>
<td align="right">307,144</td>
<td align="right">-97.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">16,486,701</td>
<td align="right">412,113</td>
<td align="right">-97.5%</td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">8,249,361</td>
<td align="right">213,222</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">8,251,415</td>
<td align="right">215,280</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">50,555,177</td>
<td align="right">1,507,218</td>
<td align="right">-97.0%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">8,215,965</td>
<td align="right">276,299</td>
<td align="right">-96.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">17,264,522</td>
<td align="right">667,066</td>
<td align="right">-96.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">12,668,067</td>
<td align="right">586,891</td>
<td align="right">-95.4%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">4,179,119</td>
<td align="right">209,334</td>
<td align="right">-95.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">4,650,944</td>
<td align="right">273,609</td>
<td align="right">-94.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">4,651,251</td>
<td align="right">281,039</td>
<td align="right">-94.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">168,470,852</td>
<td align="right">11,016,512</td>
<td align="right">-93.5%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">4,326,362</td>
<td align="right">346,366</td>
<td align="right">-92.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">123,241,760</td>
<td align="right">10,249,731</td>
<td align="right">-91.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">5,040,374</td>
<td align="right">495,137</td>
<td align="right">-90.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">45,686,894</td>
<td align="right">4,728,700</td>
<td align="right">-89.6%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">86,606,284</td>
<td align="right">9,461,857</td>
<td align="right">-89.1%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">41,299,673</td>
<td align="right">4,760,346</td>
<td align="right">-88.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">4,745,625</td>
<td align="right">568,005</td>
<td align="right">-88.0%</td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">36,981,361</td>
<td align="right">4,677,444</td>
<td align="right">-87.4%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">28,815,800</td>
<td align="right">4,599,622</td>
<td align="right">-84.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">279,056,486</td>
<td align="right">47,742,445</td>
<td align="right">-82.9%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">123,383,702</td>
<td align="right">23,866,504</td>
<td align="right">-80.7%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">5,076,965</td>
<td align="right">982,642</td>
<td align="right">-80.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">25,103,286</td>
<td align="right">5,057,308</td>
<td align="right">-79.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">178,159,531</td>
<td align="right">37,029,103</td>
<td align="right">-79.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">353,148,969</td>
<td align="right">80,396,182</td>
<td align="right">-77.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">57,741,278</td>
<td align="right">13,367,639</td>
<td align="right">-76.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">228,284,762</td>
<td align="right">54,164,216</td>
<td align="right">-76.3%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">427,436</td>
<td align="right">102,060</td>
<td align="right">-76.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">857,856</td>
<td align="right">217,032</td>
<td align="right">-74.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">141,696,664</td>
<td align="right">36,884,902</td>
<td align="right">-74.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">83,605,608</td>
<td align="right">22,425,987</td>
<td align="right">-73.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">62,655,856</td>
<td align="right">18,104,195</td>
<td align="right">-71.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">319,773,885</td>
<td align="right">94,075,470</td>
<td align="right">-70.6%</td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">34,886,608</td>
<td align="right">10,344,274</td>
<td align="right">-70.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">1,385,951,357</td>
<td align="right">431,468,574</td>
<td align="right">-68.9%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">41,128,406</td>
<td align="right">12,842,929</td>
<td align="right">-68.8%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">477,161</td>
<td align="right">158,223</td>
<td align="right">-66.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">90,960,466</td>
<td align="right">30,335,238</td>
<td align="right">-66.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">68,592,836</td>
<td align="right">23,179,895</td>
<td align="right">-66.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">165,589,633</td>
<td align="right">56,602,005</td>
<td align="right">-65.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">79,371,789</td>
<td align="right">27,348,787</td>
<td align="right">-65.5%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">12,409,219</td>
<td align="right">4,427,283</td>
<td align="right">-64.3%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">244,698,868</td>
<td align="right">87,566,151</td>
<td align="right">-64.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">234,307,980</td>
<td align="right">88,272,635</td>
<td align="right">-62.3%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">58,751,845</td>
<td align="right">22,438,082</td>
<td align="right">-61.8%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">42,788,160</td>
<td align="right">16,563,924</td>
<td align="right">-61.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">537,948</td>
<td align="right">215,855</td>
<td align="right">-59.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">951,341</td>
<td align="right">384,711</td>
<td align="right">-59.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">71,110,388</td>
<td align="right">30,180,888</td>
<td align="right">-57.6%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">232,091,699</td>
<td align="right">99,103,255</td>
<td align="right">-57.3%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">45,191,430</td>
<td align="right">21,201,192</td>
<td align="right">-53.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">408,624,986</td>
<td align="right">191,774,377</td>
<td align="right">-53.1%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">45,688,407</td>
<td align="right">21,442,785</td>
<td align="right">-53.1%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">45,228,987</td>
<td align="right">21,238,862</td>
<td align="right">-53.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">45,268,545</td>
<td align="right">21,278,425</td>
<td align="right">-53.0%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">45,699,880</td>
<td align="right">21,652,475</td>
<td align="right">-52.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">650,626</td>
<td align="right">336,785</td>
<td align="right">-48.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">11,184,364</td>
<td align="right">5,998,353</td>
<td align="right">-46.4%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">9,128,809</td>
<td align="right">4,902,780</td>
<td align="right">-46.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">403,613,057</td>
<td align="right">220,850,568</td>
<td align="right">-45.3%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">133,564,724</td>
<td align="right">81,276,275</td>
<td align="right">-39.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">92,941,238</td>
<td align="right">56,782,466</td>
<td align="right">-38.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">861,812</td>
<td align="right">547,752</td>
<td align="right">-36.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">46,183,782</td>
<td align="right">30,191,076</td>
<td align="right">-34.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">12,358,503</td>
<td align="right">8,494,570</td>
<td align="right">-31.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">12,535,012</td>
<td align="right">16,325,486</td>
<td align="right">30.2%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">940,830</td>
<td align="right">702,610</td>
<td align="right">-25.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">246,044,167</td>
<td align="right">186,939,459</td>
<td align="right">-24.0%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">35,100,327</td>
<td align="right">30,651,889</td>
<td align="right">-12.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">4,169,790</td>
<td align="right">3,841,921</td>
<td align="right">-7.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">9,364</td>
<td align="right">9,177</td>
<td align="right">-2.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">17,418,266</td>
<td align="right">17,086,418</td>
<td align="right">-1.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">803</td>
<td align="right">815</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">12,314,676</td>
<td align="right">12,484,018</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">24,654,370</td>
<td align="right">24,993,223</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">4,132,163</td>
<td align="right">4,188,922</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">4,148,331</td>
<td align="right">4,205,092</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">12,750,835</td>
<td align="right">12,920,448</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">75,169,126</td>
<td align="right">76,129,704</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">83,712,796</td>
<td align="right">84,529,053</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">123,667</td>
<td align="right">124,854</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">250</td>
<td align="right">252</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">18,038,032</td>
<td align="right">17,942,460</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">36,995</td>
<td align="right">36,825</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">41,215</td>
<td align="right">41,046</td>
<td align="right">-0.4%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">41,215</td>
<td align="right">41,046</td>
<td align="right">-0.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">129,499</td>
<td align="right">129,984</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">59,067</td>
<td align="right">59,286</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">30,296</td>
<td align="right">30,408</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">1,498</td>
<td align="right">1,494</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">12,904</td>
<td align="right">12,936</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">280,410</td>
<td align="right">279,789</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">19,378</td>
<td align="right">19,403</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">140,638</td>
<td align="right">140,814</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">1,993</td>
<td align="right">1,995</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">18,590</td>
<td align="right">18,606</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">5,225</td>
<td align="right">5,229</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">26,608</td>
<td align="right">26,628</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">17,880</td>
<td align="right">17,892</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">43,562</td>
<td align="right">43,591</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">58,437</td>
<td align="right">58,471</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">57,214</td>
<td align="right">57,246</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">96,717</td>
<td align="right">96,768</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">60,726</td>
<td align="right">60,753</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">60,852</td>
<td align="right">60,879</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">71,767</td>
<td align="right">71,795</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">39,168</td>
<td align="right">39,183</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">10,727</td>
<td align="right">10,731</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">51,280</td>
<td align="right">51,299</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">31,641</td>
<td align="right">31,630</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">14,411</td>
<td align="right">14,416</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">196,215</td>
<td align="right">196,283</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">30,009</td>
<td align="right">30,018</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">37,326</td>
<td align="right">37,337</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">1,830,988</td>
<td align="right">1,831,514</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">35,987</td>
<td align="right">35,997</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">71,982</td>
<td align="right">71,962</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">56,121</td>
<td align="right">56,136</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">42,392</td>
<td align="right">42,381</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">81,348</td>
<td align="right">81,328</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">90,563</td>
<td align="right">90,585</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_ATTR</td>
<td align="right">63,300</td>
<td align="right">63,315</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">4,220</td>
<td align="right">4,221</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">12,723</td>
<td align="right">12,726</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">68,150</td>
<td align="right">68,166</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">8,608</td>
<td align="right">8,610</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">4,346</td>
<td align="right">4,347</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">9,793</td>
<td align="right">9,795</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">46,175</td>
<td align="right">46,182</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">105,496</td>
<td align="right">105,511</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">106,325</td>
<td align="right">106,340</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">22,047</td>
<td align="right">22,050</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">25,009</td>
<td align="right">25,011</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">104,187</td>
<td align="right">104,183</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">21,903</td>
<td align="right">21,903</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">11,991</td>
<td align="right">11,991</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">9,737</td>
<td align="right">9,737</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">3,171</td>
<td align="right">3,171</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">2,520</td>
<td align="right">2,520</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">2,043</td>
<td align="right">2,043</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">2,003</td>
<td align="right">2,003</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">1,806</td>
<td align="right">1,806</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">1,475</td>
<td align="right">1,475</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">1,134</td>
<td align="right">1,134</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">1,008</td>
<td align="right">1,008</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">924</td>
<td align="right">924</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">903</td>
<td align="right">903</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">882</td>
<td align="right">882</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">588</td>
<td align="right">588</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">525</td>
<td align="right">525</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">441</td>
<td align="right">441</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">336</td>
<td align="right">336</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">GET_YIELD_FROM_ITER</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_NAME</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">18,121,791</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">10,245,945</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">5,507,757</td>
<td align="right">2.7%</td>
<td align="right">76,787</td>
<td align="right">0.3%</td>
<td align="right">-98.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">197,254,547</td>
<td align="right">97.0%</td>
<td align="right">28,686,976</td>
<td align="right">99.0%</td>
<td align="right">-85.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">533,456</td>
<td align="right">0.3%</td>
<td align="right">211,293</td>
<td align="right">0.7%</td>
<td align="right">-60.4%</td>
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
<td align="right">105,711</td>
<td align="right">97.5%</td>
<td align="right">3,263</td>
<td align="right">54.1%</td>
<td align="right">-96.9%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">2,699</td>
<td align="right">2.5%</td>
<td align="right">2,768</td>
<td align="right">45.9%</td>
<td align="right">2.6%</td>
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
<td align="left">subscr</td>
<td align="right">463</td>
<td align="right">17.2%</td>
<td align="right">525</td>
<td align="right">19.0%</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">186</td>
<td align="right">6.9%</td>
<td align="right">189</td>
<td align="right">6.8%</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">838</td>
<td align="right">31.0%</td>
<td align="right">843</td>
<td align="right">30.5%</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">subscr deque</td>
<td align="right">310</td>
<td align="right">11.5%</td>
<td align="right">309</td>
<td align="right">11.2%</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">568</td>
<td align="right">21.0%</td>
<td align="right">568</td>
<td align="right">20.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr bytes</td>
<td align="right">164</td>
<td align="right">6.1%</td>
<td align="right">164</td>
<td align="right">5.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">and int</td>
<td align="right">87</td>
<td align="right">3.2%</td>
<td align="right">87</td>
<td align="right">3.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr string slice</td>
<td align="right">42</td>
<td align="right">1.6%</td>
<td align="right">42</td>
<td align="right">1.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr other slice</td>
<td align="right">41</td>
<td align="right">1.5%</td>
<td align="right">41</td>
<td align="right">1.5%</td>
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
<td align="right">19,378</td>
<td align="right">100.0%</td>
<td align="right">19,403</td>
<td align="right">100.0%</td>
<td align="right">0.1%</td>
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
<td align="right">386,055,905</td>
<td align="right">100.0%</td>
<td align="right">122,624,678</td>
<td align="right">100.0%</td>
<td align="right">-68.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">8,493</td>
<td align="right">0.0%</td>
<td align="right">8,505</td>
<td align="right">0.0%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">31,599</td>
<td align="right">0.0%</td>
<td align="right">31,601</td>
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
<td align="right">19,286</td>
<td align="right">100.0%</td>
<td align="right">19,285</td>
<td align="right">100.0%</td>
<td align="right">-0.0%</td>
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
<td align="right">1,075</td>
<td align="right">53.7%</td>
<td align="right">1,075</td>
<td align="right">53.7%</td>
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
<td align="right">928</td>
<td align="right">100.0%</td>
<td align="right">928</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">4,108,548</td>
<td align="right">6.0%</td>
<td align="right">60,213</td>
<td align="right">0.3%</td>
<td align="right">-98.5%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">51,487,906</td>
<td align="right">75.6%</td>
<td align="right">1,943,045</td>
<td align="right">10.6%</td>
<td align="right">-96.2%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">12,450,916</td>
<td align="right">18.3%</td>
<td align="right">16,316,636</td>
<td align="right">89.0%</td>
<td align="right">31.0%</td>
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
<td align="right">79,543</td>
<td align="right">49.2%</td>
<td align="right">3,156</td>
<td align="right">31.7%</td>
<td align="right">-96.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">82,033</td>
<td align="right">50.8%</td>
<td align="right">6,807</td>
<td align="right">68.3%</td>
<td align="right">-91.7%</td>
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
<td align="left">float long</td>
<td align="right">80,925</td>
<td align="right">98.6%</td>
<td align="right">5,694</td>
<td align="right">83.6%</td>
<td align="right">-93.0%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">165</td>
<td align="right">0.2%</td>
<td align="right">167</td>
<td align="right">2.5%</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">different types</td>
<td align="right">356</td>
<td align="right">0.4%</td>
<td align="right">359</td>
<td align="right">5.3%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">419</td>
<td align="right">0.5%</td>
<td align="right">419</td>
<td align="right">6.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">126</td>
<td align="right">0.2%</td>
<td align="right">126</td>
<td align="right">1.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">42</td>
<td align="right">0.1%</td>
<td align="right">42</td>
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
<td align="right">29,178,610</td>
<td align="right">100.0%</td>
<td align="right">625,335</td>
<td align="right">99.2%</td>
<td align="right">-97.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">4,931</td>
<td align="right">0.0%</td>
<td align="right">4,935</td>
<td align="right">0.8%</td>
<td align="right">0.1%</td>
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
<td align="right">189</td>
<td align="right">64.3%</td>
<td align="right">189</td>
<td align="right">64.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">105</td>
<td align="right">35.7%</td>
<td align="right">105</td>
<td align="right">35.7%</td>
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
<td align="right">63</td>
<td align="right">60.0%</td>
<td align="right">63</td>
<td align="right">60.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">str</td>
<td align="right">42</td>
<td align="right">40.0%</td>
<td align="right">42</td>
<td align="right">40.0%</td>
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
<td align="right">108,045,856</td>
<td align="right">99.1%</td>
<td align="right">30,951,988</td>
<td align="right">98.8%</td>
<td align="right">-71.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">948,706</td>
<td align="right">0.9%</td>
<td align="right">381,949</td>
<td align="right">1.2%</td>
<td align="right">-59.7%</td>
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
<td align="right">1,711</td>
<td align="right">64.9%</td>
<td align="right">1,838</td>
<td align="right">66.5%</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">924</td>
<td align="right">35.1%</td>
<td align="right">924</td>
<td align="right">33.5%</td>
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
<td align="left">enumerate</td>
<td align="right">464</td>
<td align="right">27.1%</td>
<td align="right">526</td>
<td align="right">28.6%</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">464</td>
<td align="right">27.1%</td>
<td align="right">525</td>
<td align="right">28.6%</td>
<td align="right">13.1%</td>
</tr>
<tr>
<td align="left">itertools</td>
<td align="right">358</td>
<td align="right">20.9%</td>
<td align="right">361</td>
<td align="right">19.6%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">callable</td>
<td align="right">210</td>
<td align="right">12.3%</td>
<td align="right">211</td>
<td align="right">11.5%</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">105</td>
<td align="right">6.1%</td>
<td align="right">105</td>
<td align="right">5.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">43</td>
<td align="right">2.5%</td>
<td align="right">43</td>
<td align="right">2.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">42</td>
<td align="right">2.5%</td>
<td align="right">42</td>
<td align="right">2.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ascii string</td>
<td align="right">22</td>
<td align="right">1.3%</td>
<td align="right">22</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">3</td>
<td align="right">0.2%</td>
<td align="right">3</td>
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
<td align="left">self</td>
<td align="right">4,120,659</td>
<td align="right">4,120,659 / 0 !!</td>
<td align="right">4,177,146</td>
<td align="right">4,177,146 / 0 !!</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">41,525,757</td>
<td align="right">41,525,757 / 0 !!</td>
<td align="right">42,090,958</td>
<td align="right">42,090,958 / 0 !!</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">24,669</td>
<td align="right">24,669 / 0 !!</td>
<td align="right">24,679</td>
<td align="right">24,679 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">14,655</td>
<td align="right">14,655 / 0 !!</td>
<td align="right">14,659</td>
<td align="right">14,659 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">4,220</td>
<td align="right">4,220 / 0 !!</td>
<td align="right">4,221</td>
<td align="right">4,221 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">generator</td>
<td align="right">8,608</td>
<td align="right">8,608 / 0 !!</td>
<td align="right">8,610</td>
<td align="right">8,610 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">934</td>
<td align="right">934 / 0 !!</td>
<td align="right">934</td>
<td align="right">934 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">294</td>
<td align="right">294 / 0 !!</td>
<td align="right">294</td>
<td align="right">294 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">84</td>
<td align="right">84 / 0 !!</td>
<td align="right">84</td>
<td align="right">84 / 0 !!</td>
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
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">178,076,497</td>
<td align="right">23.5%</td>
<td align="right">36,974,970</td>
<td align="right">19.4%</td>
<td align="right">-79.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">578,405,344</td>
<td align="right">76.4%</td>
<td align="right">152,936,032</td>
<td align="right">80.3%</td>
<td align="right">-73.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">438,370</td>
<td align="right">0.1%</td>
<td align="right">437,958</td>
<td align="right">0.2%</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
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
<td align="left">Failure</td>
<td align="right">60,214</td>
<td align="right">66.5%</td>
<td align="right">31,318</td>
<td align="right">50.8%</td>
<td align="right">-48.0%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">30,335</td>
<td align="right">33.5%</td>
<td align="right">30,319</td>
<td align="right">49.2%</td>
<td align="right">-0.1%</td>
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
<td align="right">25,784</td>
<td align="right">42.8%</td>
<td align="right">7,450</td>
<td align="right">23.8%</td>
<td align="right">-71.1%</td>
</tr>
<tr>
<td align="left">non overriding descriptor</td>
<td align="right">6,224</td>
<td align="right">10.3%</td>
<td align="right">2,681</td>
<td align="right">8.6%</td>
<td align="right">-56.9%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">8,490</td>
<td align="right">14.1%</td>
<td align="right">6,053</td>
<td align="right">19.3%</td>
<td align="right">-28.7%</td>
</tr>
<tr>
<td align="left">metaclass attribute</td>
<td align="right">83</td>
<td align="right">0.1%</td>
<td align="right">84</td>
<td align="right">0.3%</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">169</td>
<td align="right">0.3%</td>
<td align="right">171</td>
<td align="right">0.5%</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">2,273</td>
<td align="right">3.8%</td>
<td align="right">2,284</td>
<td align="right">7.3%</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">1,264</td>
<td align="right">2.1%</td>
<td align="right">1,264</td>
<td align="right">4.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">379</td>
<td align="right">0.6%</td>
<td align="right">379</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">232</td>
<td align="right">0.4%</td>
<td align="right">232</td>
<td align="right">0.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">169</td>
<td align="right">0.3%</td>
<td align="right">169</td>
<td align="right">0.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">42</td>
<td align="right">0.1%</td>
<td align="right">42</td>
<td align="right">0.1%</td>
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
<td align="right">461,464,270</td>
<td align="right">100.0%</td>
<td align="right">130,954,093</td>
<td align="right">100.0%</td>
<td align="right">-71.6%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">16,771</td>
<td align="right">0.0%</td>
<td align="right">16,763</td>
<td align="right">0.0%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">210</td>
<td align="right">0.0%</td>
<td align="right">210</td>
<td align="right">0.0%</td>
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
<td align="right">6,279</td>
<td align="right">0.0%</td>
<td align="right">6,279</td>
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
<td align="right">15,038</td>
<td align="right">100.0%</td>
<td align="right">15,035</td>
<td align="right">100.0%</td>
<td align="right">-0.0%</td>
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
<td align="right">45,221,726</td>
<td align="right">100.0%</td>
<td align="right">21,231,600</td>
<td align="right">100.0%</td>
<td align="right">-53.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">273</td>
<td align="right">0.0%</td>
<td align="right">273</td>
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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

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
<td align="right">294</td>
<td align="right">87.5%</td>
<td align="right">294</td>
<td align="right">87.5%</td>
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
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">42</td>
<td align="right">100.0%</td>
<td align="right">42</td>
<td align="right">100.0%</td>
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
<td align="right">42</td>
<td align="right">100.0%</td>
<td align="right">42</td>
<td align="right">100.0%</td>
<td align="right">0.0%</td>
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
<td align="right">83,568,858</td>
<td align="right">99.6%</td>
<td align="right">84,385,147</td>
<td align="right">99.6%</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">132,843</td>
<td align="right">0.2%</td>
<td align="right">133,014</td>
<td align="right">0.2%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">156,842</td>
<td align="right">0.2%</td>
<td align="right">156,842</td>
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
<td align="right">2,818</td>
<td align="right">26.8%</td>
<td align="right">2,823</td>
<td align="right">26.8%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">7,713</td>
<td align="right">73.2%</td>
<td align="right">7,713</td>
<td align="right">73.2%</td>
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
<td align="right">9,629</td>
<td align="right">341.7%</td>
<td align="right">4,981</td>
<td align="right">176.4%</td>
<td align="right">-48.3%</td>
</tr>
<tr>
<td align="left">split dict</td>
<td align="right">124</td>
<td align="right">4.4%</td>
<td align="right">126</td>
<td align="right">4.5%</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">927</td>
<td align="right">32.9%</td>
<td align="right">929</td>
<td align="right">32.9%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">1,074</td>
<td align="right">38.1%</td>
<td align="right">1,075</td>
<td align="right">38.1%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">231</td>
<td align="right">8.2%</td>
<td align="right">231</td>
<td align="right">8.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">42</td>
<td align="right">1.5%</td>
<td align="right">42</td>
<td align="right">1.5%</td>
<td align="right">0.0%</td>
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
<td align="right">42</td>
<td align="right">100.0%</td>
<td align="right">42</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">29,223,097</td>
<td align="right">99.8%</td>
<td align="right">668,258</td>
<td align="right">93.5%</td>
<td align="right">-97.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">45,143</td>
<td align="right">0.2%</td>
<td align="right">45,150</td>
<td align="right">6.3%</td>
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
<td align="right">30.5%</td>
<td align="right">315</td>
<td align="right">30.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">717</td>
<td align="right">69.5%</td>
<td align="right">717</td>
<td align="right">69.5%</td>
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
<td align="left">py simple</td>
<td align="right">422</td>
<td align="right">58.9%</td>
<td align="right">422</td>
<td align="right">58.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">169</td>
<td align="right">23.6%</td>
<td align="right">169</td>
<td align="right">23.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">bytearray int</td>
<td align="right">126</td>
<td align="right">17.6%</td>
<td align="right">126</td>
<td align="right">17.6%</td>
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
<td align="right">4,643,860</td>
<td align="right">2.0%</td>
<td align="right">274,506</td>
<td align="right">0.4%</td>
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
<td align="right">227,498,793</td>
<td align="right">98.0%</td>
<td align="right">62,822,694</td>
<td align="right">99.6%</td>
<td align="right">-72.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,730</td>
<td align="right">0.0%</td>
<td align="right">2,730</td>
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
<td align="right">3,477</td>
<td align="right">46.8%</td>
<td align="right">2,619</td>
<td align="right">39.8%</td>
<td align="right">-24.7%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">3,956</td>
<td align="right">53.2%</td>
<td align="right">3,956</td>
<td align="right">60.2%</td>
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
<td align="left">mapping</td>
<td align="right">2,046</td>
<td align="right">58.8%</td>
<td align="right">1,126</td>
<td align="right">43.0%</td>
<td align="right">-45.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">633</td>
<td align="right">18.2%</td>
<td align="right">694</td>
<td align="right">26.5%</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">62</td>
<td align="right">1.8%</td>
<td align="right">63</td>
<td align="right">2.4%</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">420</td>
<td align="right">12.1%</td>
<td align="right">420</td>
<td align="right">16.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">232</td>
<td align="right">6.7%</td>
<td align="right">232</td>
<td align="right">8.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">memory view</td>
<td align="right">84</td>
<td align="right">2.4%</td>
<td align="right">84</td>
<td align="right">3.2%</td>
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
<td align="right">9,986,665</td>
<td align="right">100.0%</td>
<td align="right">5,119,812</td>
<td align="right">100.0%</td>
<td align="right">-48.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">780</td>
<td align="right">0.0%</td>
<td align="right">780</td>
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
<td align="right">695</td>
<td align="right">100.0%</td>
<td align="right">695</td>
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
<td align="right">10,229,019</td>
<td align="right">0.1%</td>
<td align="right">749,314</td>
<td align="right">0.0%</td>
<td align="right">-92.7%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">242,824,856</td>
<td align="right">3.3%</td>
<td align="right">76,178,752</td>
<td align="right">2.9%</td>
<td align="right">-68.6%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">2,877,619,674</td>
<td align="right">38.9%</td>
<td align="right">952,960,557</td>
<td align="right">35.7%</td>
<td align="right">-66.9%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">4,264,628,920</td>
<td align="right">57.7%</td>
<td align="right">1,638,067,645</td>
<td align="right">61.4%</td>
<td align="right">-61.6%</td>
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
<td align="left">TO_BOOL</td>
<td align="right">4,643,860</td>
<td align="right">2.4%</td>
<td align="right">274,506</td>
<td align="right">0.5%</td>
<td align="right">-94.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">178,076,497</td>
<td align="right">90.4%</td>
<td align="right">36,974,970</td>
<td align="right">68.0%</td>
<td align="right">-79.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">533,456</td>
<td align="right">0.3%</td>
<td align="right">211,293</td>
<td align="right">0.4%</td>
<td align="right">-60.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">948,706</td>
<td align="right">0.5%</td>
<td align="right">381,949</td>
<td align="right">0.7%</td>
<td align="right">-59.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">12,450,916</td>
<td align="right">6.3%</td>
<td align="right">16,316,636</td>
<td align="right">30.0%</td>
<td align="right">31.0%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">19,378</td>
<td align="right">0.0%</td>
<td align="right">19,403</td>
<td align="right">0.0%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">132,843</td>
<td align="right">0.1%</td>
<td align="right">133,014</td>
<td align="right">0.2%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">16,771</td>
<td align="right">0.0%</td>
<td align="right">16,763</td>
<td align="right">0.0%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">45,143</td>
<td align="right">0.0%</td>
<td align="right">45,150</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">31,599</td>
<td align="right">0.0%</td>
<td align="right">31,601</td>
<td align="right">0.1%</td>
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
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">2,752,682</td>
<td align="right">26.9%</td>
<td align="right">36,708</td>
<td align="right">4.9%</td>
<td align="right">-98.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">2,753,311</td>
<td align="right">26.9%</td>
<td align="right">38,315</td>
<td align="right">5.1%</td>
<td align="right">-98.6%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">4,107,939</td>
<td align="right">40.2%</td>
<td align="right">59,604</td>
<td align="right">8.0%</td>
<td align="right">-98.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">373,036</td>
<td align="right">3.6%</td>
<td align="right">372,590</td>
<td align="right">49.7%</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">50,636</td>
<td align="right">0.5%</td>
<td align="right">50,670</td>
<td align="right">6.8%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">156,842</td>
<td align="right">1.5%</td>
<td align="right">156,842</td>
<td align="right">20.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">10,057</td>
<td align="right">0.1%</td>
<td align="right">10,057</td>
<td align="right">1.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">4,389</td>
<td align="right">0.0%</td>
<td align="right">4,389</td>
<td align="right">0.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">3,675</td>
<td align="right">0.0%</td>
<td align="right">3,675</td>
<td align="right">0.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,604</td>
<td align="right">0.0%</td>
<td align="right">2,604</td>
<td align="right">0.3%</td>
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
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">8,355,613</td>
<td align="right">2.0%</td>
<td align="right">8,468,530</td>
<td align="right">2.0%</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">403,618,484</td>
<td align="right">98.8%</td>
<td align="right">409,044,960</td>
<td align="right">98.8%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">333,474,710</td>
<td align="right">81.6%</td>
<td align="right">337,941,787</td>
<td align="right">81.6%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">74,732,480</td>
<td align="right">18.3%</td>
<td align="right">75,692,954</td>
<td align="right">18.3%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">74,733,992</td>
<td align="right">18.3%</td>
<td align="right">75,694,466</td>
<td align="right">18.3%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">75,174,424</td>
<td align="right">18.4%</td>
<td align="right">76,135,003</td>
<td align="right">18.4%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">75,174,424</td>
<td align="right">18.4%</td>
<td align="right">76,135,003</td>
<td align="right">18.4%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">43,472</td>
<td align="right">0.0%</td>
<td align="right">43,303</td>
<td align="right">0.0%</td>
<td align="right">-0.4%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">462,243</td>
<td align="right">0.1%</td>
<td align="right">462,357</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">440,432</td>
<td align="right">0.1%</td>
<td align="right">440,537</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">435,782</td>
<td align="right">0.1%</td>
<td align="right">435,792</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">504</td>
<td align="right">0.0%</td>
<td align="right">504</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">1,008</td>
<td align="right">0.0%</td>
<td align="right">1,008</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">273</td>
<td align="right">0.0%</td>
<td align="right">273</td>
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
<td align="left">Method cache collisions</td>
<td align="right">40,902</td>
<td align="right"></td>
<td align="right">34,422</td>
<td align="right"></td>
<td align="right">-15.8%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">35,733</td>
<td align="right"></td>
<td align="right">30,911</td>
<td align="right"></td>
<td align="right">-13.5%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">10,310</td>
<td align="right"></td>
<td align="right">8,944</td>
<td align="right"></td>
<td align="right">-13.2%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">1,597,895,389</td>
<td align="right">47.1%</td>
<td align="right">1,639,802,773</td>
<td align="right">47.4%</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">1,936,259,271</td>
<td align="right">51.0%</td>
<td align="right">1,979,970,331</td>
<td align="right">51.2%</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">976,370,467</td>
<td align="right">25.7%</td>
<td align="right">992,272,035</td>
<td align="right">25.6%</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">33,044,234</td>
<td align="right"></td>
<td align="right">33,496,384</td>
<td align="right"></td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">333,380,024</td>
<td align="right">70.9%</td>
<td align="right">337,913,199</td>
<td align="right">70.9%</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">333,395,419</td>
<td align="right"></td>
<td align="right">337,928,578</td>
<td align="right"></td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">219,666,763</td>
<td align="right"></td>
<td align="right">222,635,299</td>
<td align="right"></td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">899,919,437</td>
<td align="right">26.5%</td>
<td align="right">912,016,263</td>
<td align="right">26.4%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">792,385,944</td>
<td align="right">23.4%</td>
<td align="right">803,014,439</td>
<td align="right">23.2%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">160,368,432</td>
<td align="right"></td>
<td align="right">162,518,989</td>
<td align="right"></td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">165,489,920</td>
<td align="right"></td>
<td align="right">167,699,881</td>
<td align="right"></td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">869,533,166</td>
<td align="right">22.9%</td>
<td align="right">881,125,208</td>
<td align="right">22.8%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">136,597,618</td>
<td align="right">29.1%</td>
<td align="right">138,411,053</td>
<td align="right">29.0%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">136,754,808</td>
<td align="right">29.1%</td>
<td align="right">138,569,112</td>
<td align="right">29.1%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">17,067,938</td>
<td align="right">0.4%</td>
<td align="right">17,294,146</td>
<td align="right">0.4%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">100,307,392</td>
<td align="right">3.0%</td>
<td align="right">101,607,071</td>
<td align="right">2.9%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">1,250</td>
<td align="right">0.0%</td>
<td align="right">1,260</td>
<td align="right">0.0%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">57,971</td>
<td align="right">0.0%</td>
<td align="right">58,381</td>
<td align="right">0.0%</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">99,219</td>
<td align="right">0.0%</td>
<td align="right">99,678</td>
<td align="right">0.0%</td>
<td align="right">0.5%</td>
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
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2025-11-17
