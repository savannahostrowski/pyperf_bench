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
<td align="right">75,116,349</td>
<td align="right">1,113</td>
<td align="right">-100.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">36,679,650</td>
<td align="right">527,254</td>
<td align="right">-98.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">18,529,581</td>
<td align="right">448,350</td>
<td align="right">-97.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">29,087,478</td>
<td align="right">705,894</td>
<td align="right">-97.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">64,543,416</td>
<td align="right">1,695,229</td>
<td align="right">-97.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">27,502,083</td>
<td align="right">916,687</td>
<td align="right">-96.7%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">27,940,101</td>
<td align="right">1,354,705</td>
<td align="right">-95.2%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">143,587,584</td>
<td align="right">7,273,766</td>
<td align="right">-94.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">36,328,761</td>
<td align="right">1,932,674</td>
<td align="right">-94.7%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">76,246,653</td>
<td align="right">4,523,211</td>
<td align="right">-94.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">39,017,055</td>
<td align="right">2,393,630</td>
<td align="right">-93.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">36,931,986</td>
<td align="right">3,260,426</td>
<td align="right">-91.2%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">20,408,514</td>
<td align="right">1,928,796</td>
<td align="right">-90.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">10,157,637</td>
<td align="right">1,002,057</td>
<td align="right">-90.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">36,968,505</td>
<td align="right">3,800,252</td>
<td align="right">-89.7%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">29,640,387</td>
<td align="right">3,242,864</td>
<td align="right">-89.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">9,238,446</td>
<td align="right">1,080,452</td>
<td align="right">-88.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">34,314,693</td>
<td align="right">4,575,228</td>
<td align="right">-86.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">50,057,259</td>
<td align="right">6,965,181</td>
<td align="right">-86.1%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">45,124,254</td>
<td align="right">6,824,607</td>
<td align="right">-84.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">31,676,001</td>
<td align="right">4,842,799</td>
<td align="right">-84.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">107,756,964</td>
<td align="right">17,872,630</td>
<td align="right">-83.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">7,664,601</td>
<td align="right">1,323,670</td>
<td align="right">-82.7%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">14,993,139</td>
<td align="right">2,608,156</td>
<td align="right">-82.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">405,350,799</td>
<td align="right">75,282,606</td>
<td align="right">-81.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">4,362,603</td>
<td align="right">829,104</td>
<td align="right">-81.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">62,435,646</td>
<td align="right">13,268,714</td>
<td align="right">-78.7%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">205,880,682</td>
<td align="right">46,706,532</td>
<td align="right">-77.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">11,114,166</td>
<td align="right">2,661,737</td>
<td align="right">-76.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">2,678,403</td>
<td align="right">651,073</td>
<td align="right">-75.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">3,595,263</td>
<td align="right">926,915</td>
<td align="right">-74.2%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">110,557,608</td>
<td align="right">28,597,103</td>
<td align="right">-74.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">7,582,764</td>
<td align="right">2,358,029</td>
<td align="right">-68.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">56,962,143</td>
<td align="right">18,275,673</td>
<td align="right">-67.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">12,422,256</td>
<td align="right">4,171,436</td>
<td align="right">-66.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">278,918,493</td>
<td align="right">97,920,691</td>
<td align="right">-64.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">1,933,103,046</td>
<td align="right">694,314,604</td>
<td align="right">-64.1%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">8,447,187</td>
<td align="right">3,130,446</td>
<td align="right">-62.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">877,275</td>
<td align="right">330,365</td>
<td align="right">-62.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">134,129,331</td>
<td align="right">52,670,118</td>
<td align="right">-60.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">175,326,522</td>
<td align="right">71,421,634</td>
<td align="right">-59.3%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">22,366,512</td>
<td align="right">9,254,168</td>
<td align="right">-58.6%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">12,819,282</td>
<td align="right">5,496,306</td>
<td align="right">-57.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">54,336,198</td>
<td align="right">23,306,367</td>
<td align="right">-57.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">3,689,049</td>
<td align="right">1,584,547</td>
<td align="right">-57.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">330,469,629</td>
<td align="right">146,099,276</td>
<td align="right">-55.8%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">559,083</td>
<td align="right">252,399</td>
<td align="right">-54.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">170,410,737</td>
<td align="right">77,067,040</td>
<td align="right">-54.8%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">1,691,781</td>
<td align="right">779,877</td>
<td align="right">-53.9%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">54,966,534</td>
<td align="right">26,757,516</td>
<td align="right">-51.3%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">54,974,955</td>
<td align="right">26,765,937</td>
<td align="right">-51.3%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">271,620,468</td>
<td align="right">141,301,174</td>
<td align="right">-48.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">276,163,629</td>
<td align="right">169,990,063</td>
<td align="right">-38.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">100,136,547</td>
<td align="right">61,690,271</td>
<td align="right">-38.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">119,064,603</td>
<td align="right">80,994,090</td>
<td align="right">-32.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">29,823,381</td>
<td align="right">20,608,063</td>
<td align="right">-30.9%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">3,914,022</td>
<td align="right">2,726,674</td>
<td align="right">-30.3%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">55,263,285</td>
<td align="right">39,266,054</td>
<td align="right">-28.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">1,317,057</td>
<td align="right">953,127</td>
<td align="right">-27.6%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">1,146,537</td>
<td align="right">852,678</td>
<td align="right">-25.6%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">1,146,768</td>
<td align="right">853,006</td>
<td align="right">-25.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">9,423,603</td>
<td align="right">7,024,791</td>
<td align="right">-25.5%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">74,044,614</td>
<td align="right">55,783,691</td>
<td align="right">-24.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">14,501,130</td>
<td align="right">11,317,400</td>
<td align="right">-22.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">689,808</td>
<td align="right">538,503</td>
<td align="right">-21.9%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">2,776,620</td>
<td align="right">2,189,128</td>
<td align="right">-21.2%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">166,794,705</td>
<td align="right">137,745,305</td>
<td align="right">-17.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">51,847,530</td>
<td align="right">43,998,289</td>
<td align="right">-15.1%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">1,302,462</td>
<td align="right">1,120,497</td>
<td align="right">-14.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">171,013,836</td>
<td align="right">148,927,199</td>
<td align="right">-12.9%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">1,287,321</td>
<td align="right">1,159,902</td>
<td align="right">-9.9%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">42,987,105</td>
<td align="right">38,913,525</td>
<td align="right">-9.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">30,343,194</td>
<td align="right">27,914,418</td>
<td align="right">-8.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">115,219,566</td>
<td align="right">106,063,912</td>
<td align="right">-7.9%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">7,275,576</td>
<td align="right">6,717,377</td>
<td align="right">-7.7%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">28,175,952</td>
<td align="right">26,293,195</td>
<td align="right">-6.7%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">8,388,387</td>
<td align="right">7,855,145</td>
<td align="right">-6.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">12,980,184</td>
<td align="right">12,236,766</td>
<td align="right">-5.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">37,307,760</td>
<td align="right">35,287,647</td>
<td align="right">-5.4%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">37,887,633</td>
<td align="right">36,526,999</td>
<td align="right">-3.6%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">4,223,751</td>
<td align="right">4,117,971</td>
<td align="right">-2.5%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">4,223,898</td>
<td align="right">4,118,118</td>
<td align="right">-2.5%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">897,687</td>
<td align="right">882,046</td>
<td align="right">-1.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">103,782</td>
<td align="right">102,207</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">17,538,927</td>
<td align="right">17,283,804</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">50,501,472</td>
<td align="right">49,906,080</td>
<td align="right">-1.2%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">44,048,613</td>
<td align="right">44,048,613</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">708,918</td>
<td align="right">708,918</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">439,656</td>
<td align="right">439,656</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">279,825</td>
<td align="right">279,825</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">191,394</td>
<td align="right">191,394</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">124,005</td>
<td align="right">124,005</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">115,122</td>
<td align="right">115,122</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">103,656</td>
<td align="right">103,656</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">69,174</td>
<td align="right">69,174</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">69,174</td>
<td align="right">69,174</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">59,031</td>
<td align="right">59,031</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">54,537</td>
<td align="right">54,537</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">52,773</td>
<td align="right">52,773</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">41,160</td>
<td align="right">41,160</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">39,375</td>
<td align="right">39,375</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">34,587</td>
<td align="right">34,587</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">33,348</td>
<td align="right">33,348</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">32,046</td>
<td align="right">32,046</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">30,240</td>
<td align="right">30,240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">17,577</td>
<td align="right">17,577</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">16,401</td>
<td align="right">16,401</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">16,275</td>
<td align="right">16,275</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">15,540</td>
<td align="right">15,540</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">15,393</td>
<td align="right">15,393</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">14,805</td>
<td align="right">14,805</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">13,461</td>
<td align="right">13,461</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">11,340</td>
<td align="right">11,340</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">11,256</td>
<td align="right">11,256</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">8,988</td>
<td align="right">8,988</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">5,838</td>
<td align="right">5,838</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">4,368</td>
<td align="right">4,368</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">4,158</td>
<td align="right">4,158</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">3,570</td>
<td align="right">3,570</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">2,751</td>
<td align="right">2,751</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">2,268</td>
<td align="right">2,268</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">2,100</td>
<td align="right">2,100</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">1,890</td>
<td align="right">1,890</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">1,344</td>
<td align="right">1,344</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">1,134</td>
<td align="right">1,134</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">756</td>
<td align="right">756</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">714</td>
<td align="right">714</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">504</td>
<td align="right">504</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">420</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">420</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">420</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">378</td>
<td align="right">378</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">315</td>
<td align="right">315</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">273</td>
<td align="right">273</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DICT_UPDATE</td>
<td align="right">210</td>
<td align="right">210</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">189</td>
<td align="right">189</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">189</td>
<td align="right">189</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">147</td>
<td align="right">147</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">147</td>
<td align="right">147</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">105</td>
<td align="right">105</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_NAME</td>
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
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">31,922,781</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">4,046,014</td>
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
<td align="right">437,155,026</td>
<td align="right">93.5%</td>
<td align="right">265,930,688</td>
<td align="right">90.5%</td>
<td align="right">-39.2%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">30,324,525</td>
<td align="right">6.5%</td>
<td align="right">27,890,284</td>
<td align="right">9.5%</td>
<td align="right">-8.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">13,167</td>
<td align="right">0.0%</td>
<td align="right">13,167</td>
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
<td align="right">11,277</td>
<td align="right">59.7%</td>
<td align="right">16,742</td>
<td align="right">68.7%</td>
<td align="right">48.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">7,623</td>
<td align="right">40.3%</td>
<td align="right">7,623</td>
<td align="right">31.3%</td>
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
<td align="right">8,904</td>
<td align="right">79.0%</td>
<td align="right">14,305</td>
<td align="right">85.4%</td>
<td align="right">60.7%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">588</td>
<td align="right">5.2%</td>
<td align="right">652</td>
<td align="right">3.9%</td>
<td align="right">10.9%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">1,008</td>
<td align="right">8.9%</td>
<td align="right">1,008</td>
<td align="right">6.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr string slice</td>
<td align="right">420</td>
<td align="right">3.7%</td>
<td align="right">420</td>
<td align="right">2.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">210</td>
<td align="right">1.9%</td>
<td align="right">210</td>
<td align="right">1.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">42</td>
<td align="right">0.4%</td>
<td align="right">42</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr other slice</td>
<td align="right">42</td>
<td align="right">0.4%</td>
<td align="right">42</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr range</td>
<td align="right">42</td>
<td align="right">0.4%</td>
<td align="right">42</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">21</td>
<td align="right">0.2%</td>
<td align="right">21</td>
<td align="right">0.1%</td>
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
<td align="right">27,940,101</td>
<td align="right">100.0%</td>
<td align="right">1,354,705</td>
<td align="right">100.0%</td>
<td align="right">-95.2%</td>
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
<td align="right">296,268,105</td>
<td align="right">90.6%</td>
<td align="right">172,704,133</td>
<td align="right">86.8%</td>
<td align="right">-41.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">30,309,069</td>
<td align="right">9.3%</td>
<td align="right">25,721,866</td>
<td align="right">12.9%</td>
<td align="right">-15.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">30,883,587</td>
<td align="right">9.4%</td>
<td align="right">26,211,564</td>
<td align="right">13.2%</td>
<td align="right">-15.1%</td>
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
<td align="right">590,793</td>
<td align="right">100.0%</td>
<td align="right">505,973</td>
<td align="right">100.0%</td>
<td align="right">-14.4%</td>
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
<td align="left">init not python</td>
<td align="right">84</td>
<td align="right">84 / 0 !!</td>
<td align="right">84</td>
<td align="right">84 / 0 !!</td>
<td align="right">0.0%</td>
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
<td align="right">1,050</td>
<td align="right">50.0%</td>
<td align="right">1,050</td>
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
<td align="right">1,050</td>
<td align="right">100.0%</td>
<td align="right">1,050</td>
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
<td align="right">137,724,468</td>
<td align="right">99.7%</td>
<td align="right">53,596,907</td>
<td align="right">99.2%</td>
<td align="right">-61.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">437,913</td>
<td align="right">0.3%</td>
<td align="right">437,913</td>
<td align="right">0.8%</td>
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
<td align="right">1,302</td>
<td align="right">74.7%</td>
<td align="right">1,302</td>
<td align="right">74.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">441</td>
<td align="right">25.3%</td>
<td align="right">441</td>
<td align="right">25.3%</td>
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
<td align="right">336</td>
<td align="right">76.2%</td>
<td align="right">336</td>
<td align="right">76.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">84</td>
<td align="right">19.0%</td>
<td align="right">84</td>
<td align="right">19.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">21</td>
<td align="right">4.8%</td>
<td align="right">21</td>
<td align="right">4.8%</td>
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
<td align="right">36,732,423</td>
<td align="right">64.3%</td>
<td align="right">580,027</td>
<td align="right">23.1%</td>
<td align="right">-98.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">20,401,563</td>
<td align="right">35.7%</td>
<td align="right">1,925,169</td>
<td align="right">76.7%</td>
<td align="right">-90.6%</td>
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
<td align="right">6,783</td>
<td align="right">97.6%</td>
<td align="right">3,459</td>
<td align="right">95.4%</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">168</td>
<td align="right">2.4%</td>
<td align="right">168</td>
<td align="right">4.6%</td>
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
<td align="left">str</td>
<td align="right">4,998</td>
<td align="right">73.7%</td>
<td align="right">1,218</td>
<td align="right">35.2%</td>
<td align="right">-75.6%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">1,050</td>
<td align="right">15.5%</td>
<td align="right">1,386</td>
<td align="right">40.1%</td>
<td align="right">32.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">735</td>
<td align="right">10.8%</td>
<td align="right">855</td>
<td align="right">24.7%</td>
<td align="right">16.3%</td>
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
<td align="right">34,402,578</td>
<td align="right">81.8%</td>
<td align="right">4,663,113</td>
<td align="right">77.9%</td>
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
<td align="right">7,659,981</td>
<td align="right">18.2%</td>
<td align="right">1,318,588</td>
<td align="right">22.0%</td>
<td align="right">-82.8%</td>
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
<td align="right">4,095</td>
<td align="right">88.6%</td>
<td align="right">4,557</td>
<td align="right">89.7%</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">525</td>
<td align="right">11.4%</td>
<td align="right">525</td>
<td align="right">10.3%</td>
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
<td align="left">zip</td>
<td align="right">441</td>
<td align="right">10.8%</td>
<td align="right">525</td>
<td align="right">11.5%</td>
<td align="right">19.0%</td>
</tr>
<tr>
<td align="left">ascii string</td>
<td align="right">462</td>
<td align="right">11.3%</td>
<td align="right">546</td>
<td align="right">12.0%</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">861</td>
<td align="right">21.0%</td>
<td align="right">987</td>
<td align="right">21.7%</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">1,680</td>
<td align="right">41.0%</td>
<td align="right">1,848</td>
<td align="right">40.6%</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">273</td>
<td align="right">6.7%</td>
<td align="right">273</td>
<td align="right">6.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">189</td>
<td align="right">4.6%</td>
<td align="right">189</td>
<td align="right">4.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">168</td>
<td align="right">4.1%</td>
<td align="right">168</td>
<td align="right">3.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">seq iter</td>
<td align="right">21</td>
<td align="right">0.5%</td>
<td align="right">21</td>
<td align="right">0.5%</td>
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
<td align="right">12,190,080</td>
<td align="right">12,190,080 / 0 !!</td>
<td align="right">12,190,080</td>
<td align="right">12,190,080 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">2,324,469</td>
<td align="right">2,324,469 / 0 !!</td>
<td align="right">2,324,469</td>
<td align="right">2,324,469 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">425,838</td>
<td align="right">425,838 / 0 !!</td>
<td align="right">425,838</td>
<td align="right">425,838 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">22,113</td>
<td align="right">22,113 / 0 !!</td>
<td align="right">22,113</td>
<td align="right">22,113 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">15,540</td>
<td align="right">15,540 / 0 !!</td>
<td align="right">15,540</td>
<td align="right">15,540 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">14,553</td>
<td align="right">14,553 / 0 !!</td>
<td align="right">14,553</td>
<td align="right">14,553 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">546</td>
<td align="right">546 / 0 !!</td>
<td align="right">546</td>
<td align="right">546 / 0 !!</td>
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
<td align="right">54,299,028</td>
<td align="right">8.8%</td>
<td align="right">23,256,071</td>
<td align="right">8.3%</td>
<td align="right">-57.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">548,149,287</td>
<td align="right">89.3%</td>
<td align="right">246,592,793</td>
<td align="right">88.1%</td>
<td align="right">-55.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">11,436,873</td>
<td align="right">1.9%</td>
<td align="right">9,920,266</td>
<td align="right">3.5%</td>
<td align="right">-13.3%</td>
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
<td align="right">27,069</td>
<td align="right">10.7%</td>
<td align="right">40,195</td>
<td align="right">16.9%</td>
<td align="right">48.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">225,498</td>
<td align="right">89.3%</td>
<td align="right">197,722</td>
<td align="right">83.1%</td>
<td align="right">-12.3%</td>
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
<td align="right">2,688</td>
<td align="right">9.9%</td>
<td align="right">4,143</td>
<td align="right">10.3%</td>
<td align="right">54.1%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">693</td>
<td align="right">2.6%</td>
<td align="right">693</td>
<td align="right">1.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">399</td>
<td align="right">1.5%</td>
<td align="right">399</td>
<td align="right">1.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">315</td>
<td align="right">1.2%</td>
<td align="right">315</td>
<td align="right">0.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">168</td>
<td align="right">0.6%</td>
<td align="right">168</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">42</td>
<td align="right">0.2%</td>
<td align="right">42</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
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
<td align="right">172,157,685</td>
<td align="right">100.0%</td>
<td align="right">124,315,561</td>
<td align="right">100.0%</td>
<td align="right">-27.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">5,607</td>
<td align="right">0.0%</td>
<td align="right">5,607</td>
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
<td align="right">24,024</td>
<td align="right">0.0%</td>
<td align="right">24,024</td>
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
<td align="right">6,027</td>
<td align="right">100.0%</td>
<td align="right">6,027</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">84</td>
<td align="right">100.0%</td>
<td align="right">84</td>
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
<td align="right">243,360,495</td>
<td align="right">96.5%</td>
<td align="right">83,016,517</td>
<td align="right">96.1%</td>
<td align="right">-65.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">8,437,506</td>
<td align="right">3.3%</td>
<td align="right">3,117,830</td>
<td align="right">3.6%</td>
<td align="right">-63.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">407,820</td>
<td align="right">0.2%</td>
<td align="right">217,014</td>
<td align="right">0.3%</td>
<td align="right">-46.8%</td>
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
<td align="right">3,675</td>
<td align="right">21.2%</td>
<td align="right">6,610</td>
<td align="right">39.6%</td>
<td align="right">79.9%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">13,650</td>
<td align="right">78.8%</td>
<td align="right">10,080</td>
<td align="right">60.4%</td>
<td align="right">-26.2%</td>
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
<td align="left">split dict</td>
<td align="right">3,549</td>
<td align="right">96.6%</td>
<td align="right">6,484</td>
<td align="right">98.1%</td>
<td align="right">82.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">22,722</td>
<td align="right">618.3%</td>
<td align="right">34,393</td>
<td align="right">520.3%</td>
<td align="right">51.4%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">126</td>
<td align="right">3.4%</td>
<td align="right">126</td>
<td align="right">1.9%</td>
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
<td align="right">28,191,891</td>
<td align="right">50.0%</td>
<td align="right">1,455,190</td>
<td align="right">5.2%</td>
<td align="right">-94.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">28,147,434</td>
<td align="right">49.9%</td>
<td align="right">26,260,103</td>
<td align="right">94.6%</td>
<td align="right">-6.7%</td>
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
<td align="right">28,098</td>
<td align="right">98.5%</td>
<td align="right">32,672</td>
<td align="right">98.7%</td>
<td align="right">16.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">420</td>
<td align="right">1.5%</td>
<td align="right">420</td>
<td align="right">1.3%</td>
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
<td align="right">28,035</td>
<td align="right">99.8%</td>
<td align="right">32,609</td>
<td align="right">99.8%</td>
<td align="right">16.3%</td>
</tr>
<tr>
<td align="left">bytearray int</td>
<td align="right">63</td>
<td align="right">0.2%</td>
<td align="right">63</td>
<td align="right">0.2%</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">31,084,725</td>
<td align="right">19.9%</td>
<td align="right">1,736,410</td>
<td align="right">3.3%</td>
<td align="right">-94.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">121,429,812</td>
<td align="right">77.7%</td>
<td align="right">50,097,735</td>
<td align="right">93.8%</td>
<td align="right">-58.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">3,562,188</td>
<td align="right">2.3%</td>
<td align="right">1,570,450</td>
<td align="right">2.9%</td>
<td align="right">-55.9%</td>
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
<td align="right">588,294</td>
<td align="right">82.5%</td>
<td align="right">35,198</td>
<td align="right">74.3%</td>
<td align="right">-94.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">124,950</td>
<td align="right">17.5%</td>
<td align="right">12,166</td>
<td align="right">25.7%</td>
<td align="right">-90.3%</td>
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
<td align="right">120,918</td>
<td align="right">96.8%</td>
<td align="right">8,189</td>
<td align="right">67.3%</td>
<td align="right">-93.2%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">2,877</td>
<td align="right">2.3%</td>
<td align="right">2,822</td>
<td align="right">23.2%</td>
<td align="right">-1.9%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">1,092</td>
<td align="right">0.9%</td>
<td align="right">1,092</td>
<td align="right">9.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">42</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">21</td>
<td align="right">0.0%</td>
<td align="right">21</td>
<td align="right">0.2%</td>
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
<td align="right">39,026,043</td>
<td align="right">100.0%</td>
<td align="right">2,402,618</td>
<td align="right">100.0%</td>
<td align="right">-93.8%</td>
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
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">4,346,948,193</td>
<td align="right">62.7%</td>
<td align="right">1,686,540,102</td>
<td align="right">58.2%</td>
<td align="right">-61.2%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">196,467,936</td>
<td align="right">2.8%</td>
<td align="right">89,914,301</td>
<td align="right">3.1%</td>
<td align="right">-54.2%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">2,310,302,484</td>
<td align="right">33.3%</td>
<td align="right">1,083,327,722</td>
<td align="right">37.4%</td>
<td align="right">-53.1%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">73,855,908</td>
<td align="right">1.1%</td>
<td align="right">38,128,306</td>
<td align="right">1.3%</td>
<td align="right">-48.4%</td>
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
<td align="left">BINARY_SLICE</td>
<td align="right">27,940,101</td>
<td align="right">13.2%</td>
<td align="right">1,354,705</td>
<td align="right">1.2%</td>
<td align="right">-95.2%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">20,401,563</td>
<td align="right">9.6%</td>
<td align="right">1,925,169</td>
<td align="right">1.7%</td>
<td align="right">-90.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">7,659,981</td>
<td align="right">3.6%</td>
<td align="right">1,318,588</td>
<td align="right">1.2%</td>
<td align="right">-82.8%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">8,437,506</td>
<td align="right">4.0%</td>
<td align="right">3,117,830</td>
<td align="right">2.8%</td>
<td align="right">-63.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">54,299,028</td>
<td align="right">25.7%</td>
<td align="right">23,256,071</td>
<td align="right">20.6%</td>
<td align="right">-57.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">3,562,188</td>
<td align="right">1.7%</td>
<td align="right">1,570,450</td>
<td align="right">1.4%</td>
<td align="right">-55.9%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">30,309,069</td>
<td align="right">14.3%</td>
<td align="right">25,721,866</td>
<td align="right">22.8%</td>
<td align="right">-15.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">30,324,525</td>
<td align="right">14.3%</td>
<td align="right">27,890,284</td>
<td align="right">24.7%</td>
<td align="right">-8.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">28,147,434</td>
<td align="right">13.3%</td>
<td align="right">26,260,103</td>
<td align="right">23.3%</td>
<td align="right">-6.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">437,913</td>
<td align="right">0.2%</td>
<td align="right">437,913</td>
<td align="right">0.4%</td>
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
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">13,805,211</td>
<td align="right">18.7%</td>
<td align="right">733,200</td>
<td align="right">1.9%</td>
<td align="right">-94.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">17,271,849</td>
<td align="right">23.4%</td>
<td align="right">995,280</td>
<td align="right">2.6%</td>
<td align="right">-94.2%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">15,049,062</td>
<td align="right">20.4%</td>
<td align="right">1,357,386</td>
<td align="right">3.6%</td>
<td align="right">-91.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">15,831,060</td>
<td align="right">21.4%</td>
<td align="right">24,850,713</td>
<td align="right">65.2%</td>
<td align="right">57.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">407,526</td>
<td align="right">0.6%</td>
<td align="right">216,720</td>
<td align="right">0.6%</td>
<td align="right">-46.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">2,340,555</td>
<td align="right">3.2%</td>
<td align="right">1,605,189</td>
<td align="right">4.2%</td>
<td align="right">-31.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">8,886,339</td>
<td align="right">12.0%</td>
<td align="right">8,116,342</td>
<td align="right">21.3%</td>
<td align="right">-8.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">209,643</td>
<td align="right">0.3%</td>
<td align="right">198,399</td>
<td align="right">0.5%</td>
<td align="right">-5.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">14,784</td>
<td align="right">0.0%</td>
<td align="right">14,784</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">10,374</td>
<td align="right">0.0%</td>
<td align="right">10,374</td>
<td align="right">0.0%</td>
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
<td align="right">44,058,861</td>
<td align="right">26.4%</td>
<td align="right">44,058,861</td>
<td align="right">26.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">122,741,829</td>
<td align="right">73.6%</td>
<td align="right">122,741,829</td>
<td align="right">73.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">44,058,861</td>
<td align="right">26.4%</td>
<td align="right">44,058,861</td>
<td align="right">26.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">44,058,441</td>
<td align="right">26.4%</td>
<td align="right">44,058,441</td>
<td align="right">26.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">420</td>
<td align="right">0.0%</td>
<td align="right">420</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">420</td>
<td align="right">0.0%</td>
<td align="right">420</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">44,058,021</td>
<td align="right">26.4%</td>
<td align="right">44,058,021</td>
<td align="right">26.4%</td>
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
<td align="right">36,647,037</td>
<td align="right">22.0%</td>
<td align="right">36,647,037</td>
<td align="right">22.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">294</td>
<td align="right">0.0%</td>
<td align="right">294</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">77,637</td>
<td align="right">0.0%</td>
<td align="right">77,637</td>
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
<td align="right">21,168</td>
<td align="right">0.0%</td>
<td align="right">21,168</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">171,024,021</td>
<td align="right">102.5%</td>
<td align="right">171,024,021</td>
<td align="right">102.5%</td>
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
<td align="right">15,523</td>
<td align="right"></td>
<td align="right">41,268</td>
<td align="right"></td>
<td align="right">165.9%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">231,622</td>
<td align="right"></td>
<td align="right">118,559</td>
<td align="right"></td>
<td align="right">-48.8%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">3,087</td>
<td align="right">0.0%</td>
<td align="right">4,526</td>
<td align="right">0.0%</td>
<td align="right">46.6%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">235,436</td>
<td align="right"></td>
<td align="right">147,060</td>
<td align="right"></td>
<td align="right">-37.5%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">87,283,001</td>
<td align="right"></td>
<td align="right">85,705,087</td>
<td align="right"></td>
<td align="right">-1.8%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">559,921,777</td>
<td align="right">19.3%</td>
<td align="right">557,369,936</td>
<td align="right">19.2%</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">669,360,178</td>
<td align="right">23.1%</td>
<td align="right">667,152,278</td>
<td align="right">23.0%</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">63,008,589</td>
<td align="right">2.0%</td>
<td align="right">63,195,890</td>
<td align="right">2.1%</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">822,164,916</td>
<td align="right">26.7%</td>
<td align="right">820,061,754</td>
<td align="right">26.7%</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">514,843,728</td>
<td align="right">16.7%</td>
<td align="right">513,693,573</td>
<td align="right">16.7%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">1,415,563,548</td>
<td align="right">48.8%</td>
<td align="right">1,416,386,874</td>
<td align="right">48.9%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">256,719,267</td>
<td align="right">8.8%</td>
<td align="right">256,809,926</td>
<td align="right">8.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">1,676,584,686</td>
<td align="right">54.5%</td>
<td align="right">1,676,009,212</td>
<td align="right">54.5%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">89,274,083</td>
<td align="right"></td>
<td align="right">89,258,313</td>
<td align="right"></td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">165,664,863</td>
<td align="right"></td>
<td align="right">165,673,243</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">165,640,524</td>
<td align="right">54.1%</td>
<td align="right">165,645,397</td>
<td align="right">54.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">165,076,481</td>
<td align="right"></td>
<td align="right">165,072,935</td>
<td align="right"></td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">28,870,527</td>
<td align="right">9.4%</td>
<td align="right">28,871,062</td>
<td align="right">9.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">140,683,872</td>
<td align="right">45.9%</td>
<td align="right">140,686,449</td>
<td align="right">45.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">111,810,258</td>
<td align="right">36.5%</td>
<td align="right">111,810,861</td>
<td align="right">36.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">37,825,557</td>
<td align="right"></td>
<td align="right">37,825,557</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">378</td>
<td align="right">0.0%</td>
<td align="right">378</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
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
<td align="right">7,014</td>
<td align="right">7,934,556</td>
<td align="right">169,798,911</td>
<td align="right">8,148,609</td>
<td align="right">16,522,716</td>
<td align="right">7,035</td>
<td align="right">7,934,556</td>
<td align="right">174,466,798</td>
<td align="right">8,581,649</td>
<td align="right">16,941,245</td>
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
<td align="right">252</td>
<td align="right">252 / 0 !!</td>
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
<td align="right">252</td>
<td align="right">252 / 0 !!</td>
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
