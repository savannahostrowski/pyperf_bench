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
<td align="right">138,788,170</td>
<td align="right">3,369,527</td>
<td align="right">-97.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">15,938,145</td>
<td align="right">2,858,532</td>
<td align="right">-82.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">23,309,584</td>
<td align="right">4,618,078</td>
<td align="right">-80.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">19,461,419</td>
<td align="right">4,032,404</td>
<td align="right">-79.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">9,882,010</td>
<td align="right">2,105,918</td>
<td align="right">-78.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">17,979,493</td>
<td align="right">5,083,603</td>
<td align="right">-71.7%</td>
</tr>
<tr>
<td align="left">LOAD_COMMON_CONSTANT</td>
<td align="right">8,138,646</td>
<td align="right">2,463,934</td>
<td align="right">-69.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">50,218,624</td>
<td align="right">15,245,383</td>
<td align="right">-69.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">10,374,418</td>
<td align="right">3,160,568</td>
<td align="right">-69.5%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">8,303,830</td>
<td align="right">2,655,551</td>
<td align="right">-68.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">36,597,790</td>
<td align="right">11,881,411</td>
<td align="right">-67.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">24,209,930</td>
<td align="right">8,483,546</td>
<td align="right">-65.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">82,290,317</td>
<td align="right">29,022,180</td>
<td align="right">-64.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">82,594,784</td>
<td align="right">30,095,617</td>
<td align="right">-63.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">16,258,341</td>
<td align="right">6,008,503</td>
<td align="right">-63.0%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">11,420,013</td>
<td align="right">4,290,266</td>
<td align="right">-62.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">83,850,814</td>
<td align="right">32,023,183</td>
<td align="right">-61.8%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">11,446,241</td>
<td align="right">4,434,024</td>
<td align="right">-61.3%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">2,763,018</td>
<td align="right">1,079,675</td>
<td align="right">-60.9%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">3,087,815</td>
<td align="right">1,307,833</td>
<td align="right">-57.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">231</td>
<td align="right">103</td>
<td align="right">-55.4%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">5,228,777</td>
<td align="right">2,437,572</td>
<td align="right">-53.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">37,367,459</td>
<td align="right">17,716,988</td>
<td align="right">-52.6%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">12,126,807</td>
<td align="right">5,825,764</td>
<td align="right">-52.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">4,553,755</td>
<td align="right">2,235,403</td>
<td align="right">-50.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">27,717,812</td>
<td align="right">14,300,286</td>
<td align="right">-48.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">10,001,088</td>
<td align="right">5,269,392</td>
<td align="right">-47.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">18,565,988</td>
<td align="right">9,808,871</td>
<td align="right">-47.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">1,249,623</td>
<td align="right">660,733</td>
<td align="right">-47.1%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">48,253,973</td>
<td align="right">25,786,052</td>
<td align="right">-46.6%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">63,100,842</td>
<td align="right">33,759,372</td>
<td align="right">-46.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">2,136,445</td>
<td align="right">1,156,062</td>
<td align="right">-45.9%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">54,826,063</td>
<td align="right">30,020,501</td>
<td align="right">-45.2%</td>
</tr>
<tr>
<td align="left">SET_ADD</td>
<td align="right">15,684</td>
<td align="right">8,644</td>
<td align="right">-44.9%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">23,601,420</td>
<td align="right">13,148,818</td>
<td align="right">-44.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">202,530,918</td>
<td align="right">117,680,163</td>
<td align="right">-41.9%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">18,783,072</td>
<td align="right">11,073,462</td>
<td align="right">-41.0%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">848,530</td>
<td align="right">507,877</td>
<td align="right">-40.1%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">45,192,405</td>
<td align="right">27,218,971</td>
<td align="right">-39.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">82,929,143</td>
<td align="right">50,472,977</td>
<td align="right">-39.1%</td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">6,242,877</td>
<td align="right">3,825,061</td>
<td align="right">-38.7%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">1,653</td>
<td align="right">1,013</td>
<td align="right">-38.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">360</td>
<td align="right">232</td>
<td align="right">-35.6%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">6,913,616</td>
<td align="right">4,489,645</td>
<td align="right">-35.1%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">18,958,115</td>
<td align="right">12,328,335</td>
<td align="right">-35.0%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">45,281,439</td>
<td align="right">29,869,583</td>
<td align="right">-34.0%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">18,443,280</td>
<td align="right">12,179,863</td>
<td align="right">-34.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">73,054,399</td>
<td align="right">48,375,989</td>
<td align="right">-33.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">47,053,074</td>
<td align="right">31,211,273</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">54,437,818</td>
<td align="right">36,840,317</td>
<td align="right">-32.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">116,500,680</td>
<td align="right">78,960,560</td>
<td align="right">-32.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">33,690,777</td>
<td align="right">22,885,134</td>
<td align="right">-32.1%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">743,819</td>
<td align="right">506,543</td>
<td align="right">-31.9%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">25,316,414</td>
<td align="right">17,433,457</td>
<td align="right">-31.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">278,965,410</td>
<td align="right">193,019,859</td>
<td align="right">-30.8%</td>
</tr>
<tr>
<td align="left">BUILD_SET</td>
<td align="right">58,674</td>
<td align="right">40,750</td>
<td align="right">-30.5%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">26,902,920</td>
<td align="right">18,822,711</td>
<td align="right">-30.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">738,675,764</td>
<td align="right">528,048,326</td>
<td align="right">-28.5%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">46,305,845</td>
<td align="right">33,147,751</td>
<td align="right">-28.4%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">945,873</td>
<td align="right">677,136</td>
<td align="right">-28.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">238,735,469</td>
<td align="right">172,621,495</td>
<td align="right">-27.7%</td>
</tr>
<tr>
<td align="left">GET_YIELD_FROM_ITER</td>
<td align="right">444,261</td>
<td align="right">321,742</td>
<td align="right">-27.6%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">427,533</td>
<td align="right">313,101</td>
<td align="right">-26.8%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">17,171,405</td>
<td align="right">12,700,119</td>
<td align="right">-26.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">36,272,992</td>
<td align="right">26,886,436</td>
<td align="right">-25.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">46,227,688</td>
<td align="right">34,446,025</td>
<td align="right">-25.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">7,254,496</td>
<td align="right">5,410,796</td>
<td align="right">-25.4%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">51,138,487</td>
<td align="right">38,315,124</td>
<td align="right">-25.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">71,476,363</td>
<td align="right">53,580,682</td>
<td align="right">-25.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">932,371</td>
<td align="right">704,017</td>
<td align="right">-24.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">154,000,272</td>
<td align="right">117,099,305</td>
<td align="right">-24.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">13,400,383</td>
<td align="right">10,199,334</td>
<td align="right">-23.9%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">47,759,566</td>
<td align="right">36,726,722</td>
<td align="right">-23.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">30,668,845</td>
<td align="right">23,761,827</td>
<td align="right">-22.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">2,257,382</td>
<td align="right">1,755,012</td>
<td align="right">-22.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">41,013,141</td>
<td align="right">32,010,618</td>
<td align="right">-22.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">15,713,051</td>
<td align="right">12,275,406</td>
<td align="right">-21.9%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">1,082,493</td>
<td align="right">845,939</td>
<td align="right">-21.9%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">1,080,675</td>
<td align="right">844,633</td>
<td align="right">-21.8%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">18,501,339</td>
<td align="right">14,508,701</td>
<td align="right">-21.6%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">54,078,299</td>
<td align="right">42,566,375</td>
<td align="right">-21.3%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">4,661,385</td>
<td align="right">3,680,327</td>
<td align="right">-21.0%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">12,613,177</td>
<td align="right">10,057,090</td>
<td align="right">-20.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">205,875,853</td>
<td align="right">164,636,899</td>
<td align="right">-20.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">5,096,239</td>
<td align="right">4,118,053</td>
<td align="right">-19.2%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">743,437</td>
<td align="right">601,023</td>
<td align="right">-19.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">1,291,141</td>
<td align="right">1,054,057</td>
<td align="right">-18.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">22,339,515</td>
<td align="right">18,277,264</td>
<td align="right">-18.2%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">4,595,576</td>
<td align="right">3,764,236</td>
<td align="right">-18.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">2,668,085</td>
<td align="right">2,185,968</td>
<td align="right">-18.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">156,314,874</td>
<td align="right">128,400,753</td>
<td align="right">-17.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">1,455,965</td>
<td align="right">1,197,302</td>
<td align="right">-17.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">187,384,479</td>
<td align="right">154,543,036</td>
<td align="right">-17.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">13,379,627</td>
<td align="right">11,219,689</td>
<td align="right">-16.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">18,495,447</td>
<td align="right">15,555,514</td>
<td align="right">-15.9%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">17,878,351</td>
<td align="right">15,128,270</td>
<td align="right">-15.4%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">4,885,822</td>
<td align="right">4,143,461</td>
<td align="right">-15.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">187,798,990</td>
<td align="right">159,596,284</td>
<td align="right">-15.0%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">22,506,002</td>
<td align="right">19,171,031</td>
<td align="right">-14.8%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">743,437</td>
<td align="right">639,187</td>
<td align="right">-14.0%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">743,437</td>
<td align="right">639,187</td>
<td align="right">-14.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">34,865,984</td>
<td align="right">30,069,787</td>
<td align="right">-13.8%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">27,205,968</td>
<td align="right">23,524,374</td>
<td align="right">-13.5%</td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">6,276,573</td>
<td align="right">5,532,525</td>
<td align="right">-11.9%</td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">7,261,119</td>
<td align="right">6,471,829</td>
<td align="right">-10.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">7,400,481</td>
<td align="right">6,617,648</td>
<td align="right">-10.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">76,218,272</td>
<td align="right">68,408,695</td>
<td align="right">-10.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">15,666,874</td>
<td align="right">14,272,794</td>
<td align="right">-8.9%</td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">98,403</td>
<td align="right">89,657</td>
<td align="right">-8.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">2,020,959</td>
<td align="right">1,845,326</td>
<td align="right">-8.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">7,867,141</td>
<td align="right">7,222,899</td>
<td align="right">-8.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">143,100</td>
<td align="right">131,834</td>
<td align="right">-7.9%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">4,203,689</td>
<td align="right">3,886,522</td>
<td align="right">-7.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">464,739</td>
<td align="right">431,035</td>
<td align="right">-7.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">431,883</td>
<td align="right">402,007</td>
<td align="right">-6.9%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">493,977</td>
<td align="right">461,447</td>
<td align="right">-6.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">13,527</td>
<td align="right">12,637</td>
<td align="right">-6.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">440,463</td>
<td align="right">413,031</td>
<td align="right">-6.2%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">2,103</td>
<td align="right">1,975</td>
<td align="right">-6.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">184,044</td>
<td align="right">174,285</td>
<td align="right">-5.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">5,466</td>
<td align="right">5,210</td>
<td align="right">-4.7%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">386,554</td>
<td align="right">370,919</td>
<td align="right">-4.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">164,991</td>
<td align="right">158,581</td>
<td align="right">-3.9%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">2,987,171</td>
<td align="right">2,876,372</td>
<td align="right">-3.7%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">736,366</td>
<td align="right">710,039</td>
<td align="right">-3.6%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">736,706</td>
<td align="right">710,391</td>
<td align="right">-3.6%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">378,841</td>
<td align="right">366,020</td>
<td align="right">-3.4%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">7,795,936</td>
<td align="right">7,552,285</td>
<td align="right">-3.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">40,024</td>
<td align="right">38,810</td>
<td align="right">-3.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">81,371,400</td>
<td align="right">79,042,259</td>
<td align="right">-2.9%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">7,361,281</td>
<td align="right">7,175,404</td>
<td align="right">-2.5%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">166,840</td>
<td align="right">162,758</td>
<td align="right">-2.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">11,740,148</td>
<td align="right">11,470,858</td>
<td align="right">-2.3%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">1,477,380</td>
<td align="right">1,443,996</td>
<td align="right">-2.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">1,737,405</td>
<td align="right">1,699,268</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">770,445</td>
<td align="right">754,007</td>
<td align="right">-2.1%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">90,471</td>
<td align="right">88,551</td>
<td align="right">-2.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">214,776</td>
<td align="right">210,654</td>
<td align="right">-1.9%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">22,225,191</td>
<td align="right">21,849,929</td>
<td align="right">-1.7%</td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">1,028,007</td>
<td align="right">1,012,135</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">1,825,627</td>
<td align="right">1,799,760</td>
<td align="right">-1.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">2,168,441</td>
<td align="right">2,142,574</td>
<td align="right">-1.2%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">11,862,178</td>
<td align="right">11,730,018</td>
<td align="right">-1.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">89,523</td>
<td align="right">88,637</td>
<td align="right">-1.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">1,236,011</td>
<td align="right">1,226,995</td>
<td align="right">-0.7%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">202,050</td>
<td align="right">200,770</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">120,429</td>
<td align="right">119,789</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">241,299</td>
<td align="right">240,019</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">241,341</td>
<td align="right">240,061</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">10,025,490</td>
<td align="right">9,986,455</td>
<td align="right">-0.4%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">1,263</td>
<td align="right">1,266</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">191,224</td>
<td align="right">191,457</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">272,830</td>
<td align="right">272,995</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">20,741</td>
<td align="right">20,753</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">50,134</td>
<td align="right">50,161</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">13,446</td>
<td align="right">13,452</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">187,761</td>
<td align="right">187,761</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">184,485</td>
<td align="right">184,485</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">87,150</td>
<td align="right">87,150</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">25,599</td>
<td align="right">25,599</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_BOUND_METHOD</td>
<td align="right">6,993</td>
<td align="right">6,993</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">4,200</td>
<td align="right">4,200</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">2,940</td>
<td align="right">2,940</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">2,793</td>
<td align="right">2,793</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">2,667</td>
<td align="right">2,667</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">2,142</td>
<td align="right">2,142</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">1,932</td>
<td align="right">1,932</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_NAME</td>
<td align="right">126</td>
<td align="right">126</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">63</td>
<td align="right">63</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">21</td>
<td align="right">21</td>
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
<td align="right">39,301,637</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">23,663,964</td>
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
<td align="right">74,023,347</td>
<td align="right">60.9%</td>
<td align="right">32,773,790</td>
<td align="right">50.9%</td>
<td align="right">-55.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">46,959,523</td>
<td align="right">38.7%</td>
<td align="right">31,114,772</td>
<td align="right">48.3%</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">396,160</td>
<td align="right">0.3%</td>
<td align="right">396,874</td>
<td align="right">0.6%</td>
<td align="right">0.2%</td>
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
<td align="right">77,476</td>
<td align="right">76.9%</td>
<td align="right">80,353</td>
<td align="right">77.4%</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">23,336</td>
<td align="right">23.1%</td>
<td align="right">23,472</td>
<td align="right">22.6%</td>
<td align="right">0.6%</td>
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
<td align="left">true divide float</td>
<td align="right">2</td>
<td align="right">0.0%</td>
<td align="right">4</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">subscr</td>
<td align="right">7,922</td>
<td align="right">10.2%</td>
<td align="right">11,328</td>
<td align="right">14.1%</td>
<td align="right">43.0%</td>
</tr>
<tr>
<td align="left">subtract other</td>
<td align="right">6,282</td>
<td align="right">8.1%</td>
<td align="right">7,058</td>
<td align="right">8.8%</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">2,157</td>
<td align="right">2.8%</td>
<td align="right">1,923</td>
<td align="right">2.4%</td>
<td align="right">-10.8%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">1,925</td>
<td align="right">2.5%</td>
<td align="right">1,736</td>
<td align="right">2.2%</td>
<td align="right">-9.8%</td>
</tr>
<tr>
<td align="left">subtract different types</td>
<td align="right">1,176</td>
<td align="right">1.5%</td>
<td align="right">1,071</td>
<td align="right">1.3%</td>
<td align="right">-8.9%</td>
</tr>
<tr>
<td align="left">true divide other</td>
<td align="right">294</td>
<td align="right">0.4%</td>
<td align="right">273</td>
<td align="right">0.3%</td>
<td align="right">-7.1%</td>
</tr>
<tr>
<td align="left">true divide different types</td>
<td align="right">2,355</td>
<td align="right">3.0%</td>
<td align="right">2,191</td>
<td align="right">2.7%</td>
<td align="right">-7.0%</td>
</tr>
<tr>
<td align="left">power</td>
<td align="right">2,933</td>
<td align="right">3.8%</td>
<td align="right">2,740</td>
<td align="right">3.4%</td>
<td align="right">-6.6%</td>
</tr>
<tr>
<td align="left">and other</td>
<td align="right">359</td>
<td align="right">0.5%</td>
<td align="right">337</td>
<td align="right">0.4%</td>
<td align="right">-6.1%</td>
</tr>
<tr>
<td align="left">rshift</td>
<td align="right">3,735</td>
<td align="right">4.8%</td>
<td align="right">3,614</td>
<td align="right">4.5%</td>
<td align="right">-3.2%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">1,249</td>
<td align="right">1.6%</td>
<td align="right">1,215</td>
<td align="right">1.5%</td>
<td align="right">-2.7%</td>
</tr>
<tr>
<td align="left">subscr tuple slice</td>
<td align="right">2,062</td>
<td align="right">2.7%</td>
<td align="right">2,019</td>
<td align="right">2.5%</td>
<td align="right">-2.1%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">3,173</td>
<td align="right">4.1%</td>
<td align="right">3,235</td>
<td align="right">4.0%</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">3,822</td>
<td align="right">4.9%</td>
<td align="right">3,759</td>
<td align="right">4.7%</td>
<td align="right">-1.6%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">6,159</td>
<td align="right">7.9%</td>
<td align="right">6,073</td>
<td align="right">7.6%</td>
<td align="right">-1.4%</td>
</tr>
<tr>
<td align="left">lshift</td>
<td align="right">195</td>
<td align="right">0.3%</td>
<td align="right">197</td>
<td align="right">0.2%</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">multiply other</td>
<td align="right">8,968</td>
<td align="right">11.6%</td>
<td align="right">8,906</td>
<td align="right">11.1%</td>
<td align="right">-0.7%</td>
</tr>
<tr>
<td align="left">subscr defaultdict</td>
<td align="right">4,875</td>
<td align="right">6.3%</td>
<td align="right">4,851</td>
<td align="right">6.0%</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">and int</td>
<td align="right">4,049</td>
<td align="right">5.2%</td>
<td align="right">4,036</td>
<td align="right">5.0%</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">13,763</td>
<td align="right">17.8%</td>
<td align="right">13,766</td>
<td align="right">17.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr array</td>
<td align="right">21</td>
<td align="right">0.0%</td>
<td align="right">21</td>
<td align="right">0.0%</td>
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
<td align="right">90,471</td>
<td align="right">100.0%</td>
<td align="right">88,551</td>
<td align="right">100.0%</td>
<td align="right">-2.1%</td>
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
<td align="right">286,053,667</td>
<td align="right">88.5%</td>
<td align="right">208,506,348</td>
<td align="right">86.5%</td>
<td align="right">-27.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">37,010,507</td>
<td align="right">11.4%</td>
<td align="right">32,331,271</td>
<td align="right">13.4%</td>
<td align="right">-12.6%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">36,488,241</td>
<td align="right">11.3%</td>
<td align="right">31,895,335</td>
<td align="right">13.2%</td>
<td align="right">-12.6%</td>
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
<td align="right">795,096</td>
<td align="right">100.0%</td>
<td align="right">708,931</td>
<td align="right">100.0%</td>
<td align="right">-10.8%</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,988</td>
<td align="right">18.2%</td>
<td align="right">2,484</td>
<td align="right">15.6%</td>
<td align="right">-16.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">11,350</td>
<td align="right">69.1%</td>
<td align="right">10,871</td>
<td align="right">68.2%</td>
<td align="right">-4.2%</td>
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
<td align="right">5,084</td>
<td align="right">100.0%</td>
<td align="right">5,065</td>
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
<td align="right">30,595,278</td>
<td align="right">36.4%</td>
<td align="right">23,687,434</td>
<td align="right">34.9%</td>
<td align="right">-22.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">52,873,950</td>
<td align="right">63.0%</td>
<td align="right">43,730,405</td>
<td align="right">64.4%</td>
<td align="right">-17.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">433,252</td>
<td align="right">0.5%</td>
<td align="right">412,280</td>
<td align="right">0.6%</td>
<td align="right">-4.8%</td>
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
<td align="right">17,905</td>
<td align="right">21.9%</td>
<td align="right">17,521</td>
<td align="right">21.4%</td>
<td align="right">-2.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">63,680</td>
<td align="right">78.1%</td>
<td align="right">64,471</td>
<td align="right">78.6%</td>
<td align="right">1.2%</td>
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
<td align="left">bool</td>
<td align="right">1,767</td>
<td align="right">2.8%</td>
<td align="right">2,442</td>
<td align="right">3.8%</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">292</td>
<td align="right">0.5%</td>
<td align="right">251</td>
<td align="right">0.4%</td>
<td align="right">-14.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">231</td>
<td align="right">0.4%</td>
<td align="right">210</td>
<td align="right">0.3%</td>
<td align="right">-9.1%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">273</td>
<td align="right">0.4%</td>
<td align="right">252</td>
<td align="right">0.4%</td>
<td align="right">-7.7%</td>
</tr>
<tr>
<td align="left">float long</td>
<td align="right">315</td>
<td align="right">0.5%</td>
<td align="right">294</td>
<td align="right">0.5%</td>
<td align="right">-6.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">14,410</td>
<td align="right">22.6%</td>
<td align="right">15,301</td>
<td align="right">23.7%</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">different types</td>
<td align="right">12,100</td>
<td align="right">19.0%</td>
<td align="right">11,444</td>
<td align="right">17.8%</td>
<td align="right">-5.4%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">8,316</td>
<td align="right">13.1%</td>
<td align="right">7,980</td>
<td align="right">12.4%</td>
<td align="right">-4.0%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">15,917</td>
<td align="right">25.0%</td>
<td align="right">16,204</td>
<td align="right">25.1%</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">9,996</td>
<td align="right">15.7%</td>
<td align="right">10,030</td>
<td align="right">15.6%</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">long float</td>
<td align="right">63</td>
<td align="right">0.1%</td>
<td align="right">63</td>
<td align="right">0.1%</td>
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
<td align="right">23,523,436</td>
<td align="right">56.7%</td>
<td align="right">4,827,808</td>
<td align="right">48.7%</td>
<td align="right">-79.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">17,963,901</td>
<td align="right">43.3%</td>
<td align="right">5,066,289</td>
<td align="right">51.1%</td>
<td align="right">-71.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">924</td>
<td align="right">0.0%</td>
<td align="right">924</td>
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
<td align="right">14,227</td>
<td align="right">91.2%</td>
<td align="right">15,949</td>
<td align="right">92.1%</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">1,365</td>
<td align="right">8.8%</td>
<td align="right">1,365</td>
<td align="right">7.9%</td>
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
<td align="right">7,148</td>
<td align="right">50.2%</td>
<td align="right">8,407</td>
<td align="right">52.7%</td>
<td align="right">17.6%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">5,525</td>
<td align="right">38.8%</td>
<td align="right">6,030</td>
<td align="right">37.8%</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">1,197</td>
<td align="right">8.4%</td>
<td align="right">1,155</td>
<td align="right">7.2%</td>
<td align="right">-3.5%</td>
</tr>
<tr>
<td align="left">str</td>
<td align="right">357</td>
<td align="right">2.5%</td>
<td align="right">357</td>
<td align="right">2.2%</td>
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
<td align="right">106,026,754</td>
<td align="right">55.8%</td>
<td align="right">35,059,538</td>
<td align="right">53.3%</td>
<td align="right">-66.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">82,493,472</td>
<td align="right">43.4%</td>
<td align="right">29,990,031</td>
<td align="right">45.6%</td>
<td align="right">-63.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,253,111</td>
<td align="right">0.7%</td>
<td align="right">624,453</td>
<td align="right">0.9%</td>
<td align="right">-50.2%</td>
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
<td align="right">37,605</td>
<td align="right">30.1%</td>
<td align="right">25,857</td>
<td align="right">22.0%</td>
<td align="right">-31.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">87,234</td>
<td align="right">69.9%</td>
<td align="right">91,489</td>
<td align="right">78.0%</td>
<td align="right">4.9%</td>
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
<td align="right">1,828</td>
<td align="right">2.1%</td>
<td align="right">3,318</td>
<td align="right">3.6%</td>
<td align="right">81.5%</td>
</tr>
<tr>
<td align="left">zip</td>
<td align="right">6,637</td>
<td align="right">7.6%</td>
<td align="right">8,475</td>
<td align="right">9.3%</td>
<td align="right">27.7%</td>
</tr>
<tr>
<td align="left">ascii string</td>
<td align="right">84</td>
<td align="right">0.1%</td>
<td align="right">63</td>
<td align="right">0.1%</td>
<td align="right">-25.0%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">903</td>
<td align="right">1.0%</td>
<td align="right">840</td>
<td align="right">0.9%</td>
<td align="right">-7.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">2,773</td>
<td align="right">3.2%</td>
<td align="right">2,626</td>
<td align="right">2.9%</td>
<td align="right">-5.3%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">7,559</td>
<td align="right">8.7%</td>
<td align="right">7,237</td>
<td align="right">7.9%</td>
<td align="right">-4.3%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">714</td>
<td align="right">0.8%</td>
<td align="right">693</td>
<td align="right">0.8%</td>
<td align="right">-2.9%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">59,301</td>
<td align="right">68.0%</td>
<td align="right">60,744</td>
<td align="right">66.4%</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">4,305</td>
<td align="right">4.9%</td>
<td align="right">4,384</td>
<td align="right">4.8%</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">1,618</td>
<td align="right">1.9%</td>
<td align="right">1,597</td>
<td align="right">1.7%</td>
<td align="right">-1.3%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">1,344</td>
<td align="right">1.5%</td>
<td align="right">1,344</td>
<td align="right">1.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">168</td>
<td align="right">0.2%</td>
<td align="right">168</td>
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
<td align="left">generator</td>
<td align="right">72,763</td>
<td align="right">72,763 / 0 !!</td>
<td align="right">51,937</td>
<td align="right">51,937 / 0 !!</td>
<td align="right">-28.6%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">8,946,540</td>
<td align="right">8,946,540 / 0 !!</td>
<td align="right">8,508,631</td>
<td align="right">8,508,631 / 0 !!</td>
<td align="right">-4.9%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">7,365,579</td>
<td align="right">7,365,579 / 0 !!</td>
<td align="right">7,089,710</td>
<td align="right">7,089,710 / 0 !!</td>
<td align="right">-3.7%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">166,062</td>
<td align="right">166,062 / 0 !!</td>
<td align="right">159,978</td>
<td align="right">159,978 / 0 !!</td>
<td align="right">-3.7%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">9,563,496</td>
<td align="right">9,563,496 / 0 !!</td>
<td align="right">9,255,539</td>
<td align="right">9,255,539 / 0 !!</td>
<td align="right">-3.2%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">4,119</td>
<td align="right">4,119 / 0 !!</td>
<td align="right">3,991</td>
<td align="right">3,991 / 0 !!</td>
<td align="right">-3.1%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">9,175,857</td>
<td align="right">9,175,857 / 0 !!</td>
<td align="right">8,991,255</td>
<td align="right">8,991,255 / 0 !!</td>
<td align="right">-2.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">12,458,976</td>
<td align="right">12,458,976 / 0 !!</td>
<td align="right">12,319,499</td>
<td align="right">12,319,499 / 0 !!</td>
<td align="right">-1.1%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">6,174</td>
<td align="right">6,174 / 0 !!</td>
<td align="right">6,174</td>
<td align="right">6,174 / 0 !!</td>
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
<td align="right">229,222,853</td>
<td align="right">64.7%</td>
<td align="right">152,348,765</td>
<td align="right">61.1%</td>
<td align="right">-33.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">71,249,699</td>
<td align="right">20.1%</td>
<td align="right">53,355,474</td>
<td align="right">21.4%</td>
<td align="right">-25.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">53,451,410</td>
<td align="right">15.1%</td>
<td align="right">43,247,547</td>
<td align="right">17.4%</td>
<td align="right">-19.1%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">21</td>
<td align="right">0.0%</td>
<td align="right">21</td>
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
<td align="right">1,095,212</td>
<td align="right">89.6%</td>
<td align="right">904,405</td>
<td align="right">87.7%</td>
<td align="right">-17.4%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">127,801</td>
<td align="right">10.4%</td>
<td align="right">126,583</td>
<td align="right">12.3%</td>
<td align="right">-1.0%</td>
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
<td align="left">non overriding descriptor</td>
<td align="right">10,736</td>
<td align="right">8.4%</td>
<td align="right">9,496</td>
<td align="right">7.5%</td>
<td align="right">-11.5%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">1,218</td>
<td align="right">1.0%</td>
<td align="right">1,323</td>
<td align="right">1.0%</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">8,882</td>
<td align="right">6.9%</td>
<td align="right">8,377</td>
<td align="right">6.6%</td>
<td align="right">-5.7%</td>
</tr>
<tr>
<td align="left">metaclass attribute</td>
<td align="right">15,445</td>
<td align="right">12.1%</td>
<td align="right">16,239</td>
<td align="right">12.8%</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">7,569</td>
<td align="right">5.9%</td>
<td align="right">7,240</td>
<td align="right">5.7%</td>
<td align="right">-4.3%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">12,347</td>
<td align="right">9.7%</td>
<td align="right">11,902</td>
<td align="right">9.4%</td>
<td align="right">-3.6%</td>
</tr>
<tr>
<td align="left">expected error</td>
<td align="right">4,706</td>
<td align="right">3.7%</td>
<td align="right">4,769</td>
<td align="right">3.8%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">106</td>
<td align="right">0.1%</td>
<td align="right">105</td>
<td align="right">0.1%</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">61,719</td>
<td align="right">48.3%</td>
<td align="right">62,227</td>
<td align="right">49.2%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">588</td>
<td align="right">0.5%</td>
<td align="right">588</td>
<td align="right">0.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">147</td>
<td align="right">0.1%</td>
<td align="right">147</td>
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
<td align="right">303,862,920</td>
<td align="right">99.9%</td>
<td align="right">233,481,357</td>
<td align="right">99.9%</td>
<td align="right">-23.2%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">94,741</td>
<td align="right">0.0%</td>
<td align="right">94,864</td>
<td align="right">0.0%</td>
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
<td align="right">22,239</td>
<td align="right">0.0%</td>
<td align="right">22,239</td>
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
<td align="right">96,651</td>
<td align="right">100.0%</td>
<td align="right">96,761</td>
<td align="right">100.0%</td>
<td align="right">0.1%</td>
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
<td align="right">2,409,751</td>
<td align="right">99.9%</td>
<td align="right">2,148,013</td>
<td align="right">99.9%</td>
<td align="right">-10.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">633</td>
<td align="right">0.0%</td>
<td align="right">636</td>
<td align="right">0.0%</td>
<td align="right">0.5%</td>
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
<td align="right">630</td>
<td align="right">100.0%</td>
<td align="right">630</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">821,109</td>
<td align="right">66.9%</td>
<td align="right">483,961</td>
<td align="right">55.4%</td>
<td align="right">-41.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">27,421</td>
<td align="right">2.2%</td>
<td align="right">23,916</td>
<td align="right">2.7%</td>
<td align="right">-12.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">375,973</td>
<td align="right">30.6%</td>
<td align="right">363,515</td>
<td align="right">41.6%</td>
<td align="right">-3.3%</td>
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
<td align="right">2,805</td>
<td align="right">83.1%</td>
<td align="right">2,443</td>
<td align="right">82.9%</td>
<td align="right">-12.9%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">569</td>
<td align="right">16.9%</td>
<td align="right">504</td>
<td align="right">17.1%</td>
<td align="right">-11.4%</td>
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
<td align="right">2,805</td>
<td align="right">100.0%</td>
<td align="right">2,443</td>
<td align="right">100.0%</td>
<td align="right">-12.9%</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,823,061</td>
<td align="right">17.0%</td>
<td align="right">1,707,696</td>
<td align="right">16.4%</td>
<td align="right">-6.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">377,533</td>
<td align="right">3.5%</td>
<td align="right">361,960</td>
<td align="right">3.5%</td>
<td align="right">-4.1%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">8,525,391</td>
<td align="right">79.4%</td>
<td align="right">8,344,080</td>
<td align="right">80.1%</td>
<td align="right">-2.1%</td>
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
<td align="right">39,688</td>
<td align="right">91.6%</td>
<td align="right">37,520</td>
<td align="right">91.3%</td>
<td align="right">-5.5%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">3,645</td>
<td align="right">8.4%</td>
<td align="right">3,583</td>
<td align="right">8.7%</td>
<td align="right">-1.7%</td>
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
<td align="right">462</td>
<td align="right">12.7%</td>
<td align="right">441</td>
<td align="right">12.3%</td>
<td align="right">-4.5%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">1,398</td>
<td align="right">38.4%</td>
<td align="right">1,356</td>
<td align="right">37.8%</td>
<td align="right">-3.0%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">1,953</td>
<td align="right">53.6%</td>
<td align="right">1,953</td>
<td align="right">54.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">63</td>
<td align="right">1.7%</td>
<td align="right">63</td>
<td align="right">1.8%</td>
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
<td align="right">2,103</td>
<td align="right">100.0%</td>
<td align="right">1,975</td>
<td align="right">100.0%</td>
<td align="right">-6.1%</td>
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
<td align="right">2,756,650</td>
<td align="right">13.2%</td>
<td align="right">1,073,304</td>
<td align="right">12.1%</td>
<td align="right">-61.1%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">18,083,968</td>
<td align="right">86.7%</td>
<td align="right">7,808,263</td>
<td align="right">87.9%</td>
<td align="right">-56.8%</td>
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
<td align="right">2,858</td>
<td align="right">44.9%</td>
<td align="right">2,860</td>
<td align="right">44.9%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">3,510</td>
<td align="right">55.1%</td>
<td align="right">3,511</td>
<td align="right">55.1%</td>
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
<td align="right">3,510</td>
<td align="right">100.0%</td>
<td align="right">3,511</td>
<td align="right">100.0%</td>
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
<td align="right">668,560</td>
<td align="right">0.4%</td>
<td align="right">443,151</td>
<td align="right">0.3%</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">173,899,901</td>
<td align="right">94.2%</td>
<td align="right">134,314,259</td>
<td align="right">92.8%</td>
<td align="right">-22.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">9,941,129</td>
<td align="right">5.4%</td>
<td align="right">9,905,591</td>
<td align="right">6.8%</td>
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
<td align="left">Failure</td>
<td align="right">27,182</td>
<td align="right">28.4%</td>
<td align="right">23,682</td>
<td align="right">26.9%</td>
<td align="right">-12.9%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">68,637</td>
<td align="right">71.6%</td>
<td align="right">64,363</td>
<td align="right">73.1%</td>
<td align="right">-6.2%</td>
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
<td align="right">3,071</td>
<td align="right">11.3%</td>
<td align="right">2,339</td>
<td align="right">9.9%</td>
<td align="right">-23.8%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">13,534</td>
<td align="right">49.8%</td>
<td align="right">11,210</td>
<td align="right">47.3%</td>
<td align="right">-17.2%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">1,392</td>
<td align="right">5.1%</td>
<td align="right">1,266</td>
<td align="right">5.3%</td>
<td align="right">-9.1%</td>
</tr>
<tr>
<td align="left">number</td>
<td align="right">3,368</td>
<td align="right">12.4%</td>
<td align="right">3,176</td>
<td align="right">13.4%</td>
<td align="right">-5.7%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">2,352</td>
<td align="right">8.7%</td>
<td align="right">2,226</td>
<td align="right">9.4%</td>
<td align="right">-5.4%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">3,339</td>
<td align="right">12.3%</td>
<td align="right">3,339</td>
<td align="right">14.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">84</td>
<td align="right">0.3%</td>
<td align="right">84</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">float</td>
<td align="right">42</td>
<td align="right">0.2%</td>
<td align="right">42</td>
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
<td align="right">83,724,558</td>
<td align="right">100.0%</td>
<td align="right">30,208,071</td>
<td align="right">99.9%</td>
<td align="right">-63.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">27,354</td>
<td align="right">0.0%</td>
<td align="right">26,127</td>
<td align="right">0.1%</td>
<td align="right">-4.5%</td>
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
<td align="right">743</td>
<td align="right">5.9%</td>
<td align="right">736</td>
<td align="right">5.8%</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">11,927</td>
<td align="right">94.1%</td>
<td align="right">11,947</td>
<td align="right">94.2%</td>
<td align="right">0.2%</td>
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
<td align="right">680</td>
<td align="right">91.5%</td>
<td align="right">673</td>
<td align="right">91.4%</td>
<td align="right">-1.0%</td>
</tr>
<tr>
<td align="left">iterator</td>
<td align="right">63</td>
<td align="right">8.5%</td>
<td align="right">63</td>
<td align="right">8.6%</td>
<td align="right">0.0%</td>
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
<td align="right">311,697,389</td>
<td align="right">6.3%</td>
<td align="right">192,871,299</td>
<td align="right">5.7%</td>
<td align="right">-38.1%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">1,696,429,981</td>
<td align="right">34.4%</td>
<td align="right">1,093,649,216</td>
<td align="right">32.4%</td>
<td align="right">-35.5%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">2,834,072,209</td>
<td align="right">57.4%</td>
<td align="right">2,006,208,384</td>
<td align="right">59.5%</td>
<td align="right">-29.2%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">95,089,633</td>
<td align="right">1.9%</td>
<td align="right">79,212,835</td>
<td align="right">2.3%</td>
<td align="right">-16.7%</td>
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
<td align="right">17,963,901</td>
<td align="right">6.0%</td>
<td align="right">5,066,289</td>
<td align="right">2.7%</td>
<td align="right">-71.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">82,493,472</td>
<td align="right">27.6%</td>
<td align="right">29,990,031</td>
<td align="right">16.0%</td>
<td align="right">-63.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">2,756,650</td>
<td align="right">0.9%</td>
<td align="right">1,073,304</td>
<td align="right">0.6%</td>
<td align="right">-61.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">46,959,523</td>
<td align="right">15.7%</td>
<td align="right">31,114,772</td>
<td align="right">16.6%</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">71,249,699</td>
<td align="right">23.8%</td>
<td align="right">53,355,474</td>
<td align="right">28.5%</td>
<td align="right">-25.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">30,595,278</td>
<td align="right">10.2%</td>
<td align="right">23,687,434</td>
<td align="right">12.7%</td>
<td align="right">-22.6%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">36,488,241</td>
<td align="right">12.2%</td>
<td align="right">31,895,335</td>
<td align="right">17.1%</td>
<td align="right">-12.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">377,533</td>
<td align="right">0.1%</td>
<td align="right">361,960</td>
<td align="right">0.2%</td>
<td align="right">-4.1%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">375,973</td>
<td align="right">0.1%</td>
<td align="right">363,515</td>
<td align="right">0.2%</td>
<td align="right">-3.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">9,941,129</td>
<td align="right">3.3%</td>
<td align="right">9,905,591</td>
<td align="right">5.3%</td>
<td align="right">-0.4%</td>
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
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">13,378,089</td>
<td align="right">14.1%</td>
<td align="right">9,128,403</td>
<td align="right">11.5%</td>
<td align="right">-31.8%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">11,914,815</td>
<td align="right">12.5%</td>
<td align="right">8,563,512</td>
<td align="right">10.8%</td>
<td align="right">-28.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">7,314,563</td>
<td align="right">7.7%</td>
<td align="right">5,561,484</td>
<td align="right">7.0%</td>
<td align="right">-24.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">3,288,417</td>
<td align="right">3.5%</td>
<td align="right">2,714,679</td>
<td align="right">3.4%</td>
<td align="right">-17.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">28,952,985</td>
<td align="right">30.4%</td>
<td align="right">25,484,674</td>
<td align="right">32.2%</td>
<td align="right">-12.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">6,185,290</td>
<td align="right">6.5%</td>
<td align="right">5,578,588</td>
<td align="right">7.0%</td>
<td align="right">-9.8%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">1,822,275</td>
<td align="right">1.9%</td>
<td align="right">1,707,294</td>
<td align="right">2.2%</td>
<td align="right">-6.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">11,495,156</td>
<td align="right">12.1%</td>
<td align="right">10,863,026</td>
<td align="right">13.7%</td>
<td align="right">-5.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">2,105,468</td>
<td align="right">2.2%</td>
<td align="right">2,077,033</td>
<td align="right">2.6%</td>
<td align="right">-1.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">5,164,085</td>
<td align="right">5.4%</td>
<td align="right">5,125,388</td>
<td align="right">6.5%</td>
<td align="right">-0.7%</td>
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
<td align="left">Frame objects created</td>
<td align="right">1,047,845</td>
<td align="right">0.5%</td>
<td align="right">906,855</td>
<td align="right">0.4%</td>
<td align="right">-13.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">4,046,377</td>
<td align="right">1.9%</td>
<td align="right">3,815,029</td>
<td align="right">1.8%</td>
<td align="right">-5.7%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">135,836,421</td>
<td align="right">62.5%</td>
<td align="right">129,411,625</td>
<td align="right">62.0%</td>
<td align="right">-4.7%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">193,767,833</td>
<td align="right">89.1%</td>
<td align="right">186,401,353</td>
<td align="right">89.4%</td>
<td align="right">-3.8%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">42,030,175</td>
<td align="right">19.3%</td>
<td align="right">40,597,882</td>
<td align="right">19.5%</td>
<td align="right">-3.4%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">81,535,807</td>
<td align="right">37.5%</td>
<td align="right">79,184,531</td>
<td align="right">38.0%</td>
<td align="right">-2.9%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">81,535,807</td>
<td align="right">37.5%</td>
<td align="right">79,184,531</td>
<td align="right">38.0%</td>
<td align="right">-2.9%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">77,481,912</td>
<td align="right">35.6%</td>
<td align="right">75,361,984</td>
<td align="right">36.1%</td>
<td align="right">-2.7%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">77,489,430</td>
<td align="right">35.6%</td>
<td align="right">75,369,502</td>
<td align="right">36.1%</td>
<td align="right">-2.7%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">18,923,852</td>
<td align="right">8.7%</td>
<td align="right">18,515,919</td>
<td align="right">8.9%</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">9,359,253</td>
<td align="right">4.3%</td>
<td align="right">9,272,785</td>
<td align="right">4.4%</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">4,725</td>
<td align="right">0.0%</td>
<td align="right">4,725</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">2,793</td>
<td align="right">0.0%</td>
<td align="right">2,793</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">8,736</td>
<td align="right">0.0%</td>
<td align="right">8,736</td>
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
<td align="left">Method cache dunder misses</td>
<td align="right">2,227,021</td>
<td align="right"></td>
<td align="right">1,892,644</td>
<td align="right"></td>
<td align="right">-15.0%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">153,721,210</td>
<td align="right"></td>
<td align="right">141,661,187</td>
<td align="right"></td>
<td align="right">-7.8%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">1,270,509,905</td>
<td align="right">36.3%</td>
<td align="right">1,216,272,465</td>
<td align="right">36.0%</td>
<td align="right">-4.3%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">4,366,864</td>
<td align="right"></td>
<td align="right">4,550,964</td>
<td align="right"></td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">1,596,075,369</td>
<td align="right">42.4%</td>
<td align="right">1,531,447,130</td>
<td align="right">42.0%</td>
<td align="right">-4.0%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">1,186,650</td>
<td align="right"></td>
<td align="right">1,140,152</td>
<td align="right"></td>
<td align="right">-3.9%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">53,727,112</td>
<td align="right">1.4%</td>
<td align="right">51,938,204</td>
<td align="right">1.4%</td>
<td align="right">-3.3%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">851,452</td>
<td align="right">0.2%</td>
<td align="right">824,851</td>
<td align="right">0.2%</td>
<td align="right">-3.1%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">1,137,682,363</td>
<td align="right">32.5%</td>
<td align="right">1,103,079,020</td>
<td align="right">32.6%</td>
<td align="right">-3.0%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">254,909,785</td>
<td align="right"></td>
<td align="right">247,333,483</td>
<td align="right"></td>
<td align="right">-3.0%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">1,007,780,127</td>
<td align="right">28.8%</td>
<td align="right">978,043,039</td>
<td align="right">28.9%</td>
<td align="right">-3.0%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">871,911,765</td>
<td align="right">23.2%</td>
<td align="right">847,335,473</td>
<td align="right">23.2%</td>
<td align="right">-2.8%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">83,563,910</td>
<td align="right">2.4%</td>
<td align="right">81,297,517</td>
<td align="right">2.4%</td>
<td align="right">-2.7%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">146,058,933</td>
<td align="right"></td>
<td align="right">142,481,420</td>
<td align="right"></td>
<td align="right">-2.4%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">135,527,400</td>
<td align="right">27.3%</td>
<td align="right">132,224,109</td>
<td align="right">26.5%</td>
<td align="right">-2.4%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">134,652,485</td>
<td align="right">27.1%</td>
<td align="right">131,375,252</td>
<td align="right">26.4%</td>
<td align="right">-2.4%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">23,463</td>
<td align="right">0.0%</td>
<td align="right">24,006</td>
<td align="right">0.0%</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">6,590,374</td>
<td align="right"></td>
<td align="right">6,440,422</td>
<td align="right"></td>
<td align="right">-2.3%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">1,241,559,780</td>
<td align="right">33.0%</td>
<td align="right">1,219,903,992</td>
<td align="right">33.4%</td>
<td align="right">-1.7%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">360,981,103</td>
<td align="right">72.7%</td>
<td align="right">366,041,116</td>
<td align="right">73.5%</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">361,235,752</td>
<td align="right"></td>
<td align="right">366,295,769</td>
<td align="right"></td>
<td align="right">1.4%</td>
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
<td align="right">1,680</td>
<td align="right">1,680</td>
<td align="right">0.0%</td>
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
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2025-11-17
