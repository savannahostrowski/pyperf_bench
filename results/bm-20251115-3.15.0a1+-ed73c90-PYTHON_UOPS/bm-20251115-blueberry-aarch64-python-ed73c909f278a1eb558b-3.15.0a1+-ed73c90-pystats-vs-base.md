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
<td align="right">5,108,751,107</td>
<td align="right">4,747,356</td>
<td align="right">-99.9%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">113,968,040</td>
<td align="right">601,758</td>
<td align="right">-99.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">459,447,851</td>
<td align="right">3,902,439</td>
<td align="right">-99.2%</td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">115,502,168</td>
<td align="right">6,635,057</td>
<td align="right">-94.3%</td>
</tr>
<tr>
<td align="left">GET_ANEXT</td>
<td align="right">105,143,598</td>
<td align="right">6,552,168</td>
<td align="right">-93.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">335,716,504</td>
<td align="right">22,541,204</td>
<td align="right">-93.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">1,065,404,087</td>
<td align="right">81,597,015</td>
<td align="right">-92.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">1,460,584,146</td>
<td align="right">120,814,130</td>
<td align="right">-91.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">2,264,394,972</td>
<td align="right">191,110,650</td>
<td align="right">-91.6%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">1,874,534,212</td>
<td align="right">160,711,847</td>
<td align="right">-91.4%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,229,687,374</td>
<td align="right">110,036,972</td>
<td align="right">-91.1%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">1,305,782,269</td>
<td align="right">118,630,690</td>
<td align="right">-90.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">536,088,207</td>
<td align="right">49,720,760</td>
<td align="right">-90.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">3,358,112,330</td>
<td align="right">313,231,956</td>
<td align="right">-90.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,995,685,168</td>
<td align="right">187,360,374</td>
<td align="right">-90.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">700,997,014</td>
<td align="right">67,534,627</td>
<td align="right">-90.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">1,573,858,007</td>
<td align="right">154,511,722</td>
<td align="right">-90.2%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">121,830,258</td>
<td align="right">12,643,930</td>
<td align="right">-89.6%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">61,552,035</td>
<td align="right">6,803,140</td>
<td align="right">-88.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">127,350,341</td>
<td align="right">14,114,962</td>
<td align="right">-88.9%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">577,170,678</td>
<td align="right">64,366,814</td>
<td align="right">-88.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">744,423,063</td>
<td align="right">84,240,294</td>
<td align="right">-88.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">433,008,433</td>
<td align="right">49,942,866</td>
<td align="right">-88.5%</td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">47,813,983</td>
<td align="right">5,950,831</td>
<td align="right">-87.6%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">366,174,859</td>
<td align="right">46,828,416</td>
<td align="right">-87.2%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">540,175,642</td>
<td align="right">71,327,724</td>
<td align="right">-86.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,745,315,838</td>
<td align="right">233,250,885</td>
<td align="right">-86.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">262,182,617</td>
<td align="right">35,058,709</td>
<td align="right">-86.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">380,103,707</td>
<td align="right">52,273,612</td>
<td align="right">-86.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">869,768,361</td>
<td align="right">122,242,326</td>
<td align="right">-85.9%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">102,654,329</td>
<td align="right">14,584,994</td>
<td align="right">-85.8%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">692,941,596</td>
<td align="right">101,281,737</td>
<td align="right">-85.4%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">1,702,602,135</td>
<td align="right">250,156,295</td>
<td align="right">-85.3%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">202,215,822</td>
<td align="right">30,434,762</td>
<td align="right">-84.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">411,502,926</td>
<td align="right">62,347,340</td>
<td align="right">-84.8%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">6,786,907,907</td>
<td align="right">1,062,395,516</td>
<td align="right">-84.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">510,261,740</td>
<td align="right">81,024,047</td>
<td align="right">-84.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">506,576,325</td>
<td align="right">82,081,253</td>
<td align="right">-83.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">244,691,827</td>
<td align="right">40,415,973</td>
<td align="right">-83.5%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">166,853,738</td>
<td align="right">28,408,651</td>
<td align="right">-83.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">1,307,872,785</td>
<td align="right">227,605,615</td>
<td align="right">-82.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">76,697,910</td>
<td align="right">13,399,727</td>
<td align="right">-82.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">345,874,873</td>
<td align="right">60,442,807</td>
<td align="right">-82.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">2,453,613,351</td>
<td align="right">439,562,327</td>
<td align="right">-82.1%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">1,008,664,149</td>
<td align="right">182,150,359</td>
<td align="right">-81.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">1,089,492,635</td>
<td align="right">200,109,875</td>
<td align="right">-81.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">2,751,232,395</td>
<td align="right">512,928,651</td>
<td align="right">-81.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">5,673,471,147</td>
<td align="right">1,078,252,806</td>
<td align="right">-81.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">96,003,440</td>
<td align="right">18,348,972</td>
<td align="right">-80.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">227,928,663</td>
<td align="right">43,749,937</td>
<td align="right">-80.8%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_WITH_HINT</td>
<td align="right">9,872,436</td>
<td align="right">1,899,129</td>
<td align="right">-80.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">12,683,767,461</td>
<td align="right">2,449,552,833</td>
<td align="right">-80.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">399,697,184</td>
<td align="right">77,198,030</td>
<td align="right">-80.7%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">743,519,072</td>
<td align="right">147,094,002</td>
<td align="right">-80.2%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">1,184,107,702</td>
<td align="right">237,374,899</td>
<td align="right">-80.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,194,425,194</td>
<td align="right">442,828,828</td>
<td align="right">-79.8%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">133,489,992</td>
<td align="right">28,461,912</td>
<td align="right">-78.7%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">107,690,464</td>
<td align="right">23,054,941</td>
<td align="right">-78.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">2,352,513,912</td>
<td align="right">508,907,498</td>
<td align="right">-78.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">10,663,374,679</td>
<td align="right">2,352,903,734</td>
<td align="right">-77.9%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">133,809,892</td>
<td align="right">30,591,396</td>
<td align="right">-77.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">71,693,397</td>
<td align="right">16,428,603</td>
<td align="right">-77.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">281,161,046</td>
<td align="right">66,616,180</td>
<td align="right">-76.3%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">448,629,727</td>
<td align="right">108,163,700</td>
<td align="right">-75.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">10,016,503,605</td>
<td align="right">2,453,335,067</td>
<td align="right">-75.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">452,657,625</td>
<td align="right">111,185,656</td>
<td align="right">-75.4%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">6,459,568</td>
<td align="right">1,598,865</td>
<td align="right">-75.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">1,637,104,647</td>
<td align="right">417,185,924</td>
<td align="right">-74.5%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">34,262,953</td>
<td align="right">8,741,895</td>
<td align="right">-74.5%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">127,450,867</td>
<td align="right">33,104,068</td>
<td align="right">-74.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">35,196,605,597</td>
<td align="right">9,295,697,747</td>
<td align="right">-73.6%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">1,045,063,806</td>
<td align="right">287,390,111</td>
<td align="right">-72.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">15,386,278</td>
<td align="right">4,327,320</td>
<td align="right">-71.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">601,335,894</td>
<td align="right">173,472,005</td>
<td align="right">-71.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">43,906,705</td>
<td align="right">12,975,889</td>
<td align="right">-70.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">67,337,388</td>
<td align="right">20,022,779</td>
<td align="right">-70.3%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">113,603,807</td>
<td align="right">33,950,047</td>
<td align="right">-70.1%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">395,966,458</td>
<td align="right">118,628,989</td>
<td align="right">-70.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">8,370,207,500</td>
<td align="right">2,608,315,015</td>
<td align="right">-68.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">105,671,578</td>
<td align="right">33,354,501</td>
<td align="right">-68.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">322,816,810</td>
<td align="right">103,215,088</td>
<td align="right">-68.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">3,747,625,077</td>
<td align="right">1,200,369,119</td>
<td align="right">-68.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">21,152,359</td>
<td align="right">7,153,659</td>
<td align="right">-66.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">349,083,152</td>
<td align="right">118,522,215</td>
<td align="right">-66.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">1,313,496,863</td>
<td align="right">447,562,106</td>
<td align="right">-65.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">2,463,258,780</td>
<td align="right">848,159,584</td>
<td align="right">-65.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">88,887,456</td>
<td align="right">30,617,561</td>
<td align="right">-65.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">4,555,345,995</td>
<td align="right">1,636,857,943</td>
<td align="right">-64.1%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,437,314,819</td>
<td align="right">517,350,055</td>
<td align="right">-64.0%</td>
</tr>
<tr>
<td align="left">LOAD_COMMON_CONSTANT</td>
<td align="right">20,872,022</td>
<td align="right">7,581,981</td>
<td align="right">-63.7%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">898,223,784</td>
<td align="right">328,290,231</td>
<td align="right">-63.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">6,916,501</td>
<td align="right">2,538,631</td>
<td align="right">-63.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">834,201,455</td>
<td align="right">310,282,952</td>
<td align="right">-62.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">271,418,425</td>
<td align="right">101,845,046</td>
<td align="right">-62.5%</td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">24,156,116</td>
<td align="right">9,165,835</td>
<td align="right">-62.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">110,454,178</td>
<td align="right">41,937,144</td>
<td align="right">-62.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">169,561,746</td>
<td align="right">64,464,286</td>
<td align="right">-62.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">999,289,097</td>
<td align="right">379,933,039</td>
<td align="right">-62.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">1,719,644</td>
<td align="right">663,425</td>
<td align="right">-61.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">3,097,847,448</td>
<td align="right">1,203,975,253</td>
<td align="right">-61.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">158,215,440</td>
<td align="right">61,858,359</td>
<td align="right">-60.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">246,057,506</td>
<td align="right">97,618,406</td>
<td align="right">-60.3%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">317,304,840</td>
<td align="right">132,818,095</td>
<td align="right">-58.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">155,346,864</td>
<td align="right">66,581,312</td>
<td align="right">-57.1%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">152,374,239</td>
<td align="right">65,813,406</td>
<td align="right">-56.8%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">335,997,449</td>
<td align="right">145,893,374</td>
<td align="right">-56.6%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">32,958,410</td>
<td align="right">14,788,807</td>
<td align="right">-55.1%</td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">16,253,690</td>
<td align="right">7,429,978</td>
<td align="right">-54.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">333,764,399</td>
<td align="right">155,918,489</td>
<td align="right">-53.3%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">861,091,761</td>
<td align="right">408,429,281</td>
<td align="right">-52.6%</td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">47,073,200</td>
<td align="right">22,477,734</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">67,885,028</td>
<td align="right">32,849,123</td>
<td align="right">-51.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">932,881,841</td>
<td align="right">454,338,715</td>
<td align="right">-51.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">229,488,567</td>
<td align="right">113,029,627</td>
<td align="right">-50.7%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">53,573,077</td>
<td align="right">27,133,586</td>
<td align="right">-49.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">510,129,961</td>
<td align="right">260,010,073</td>
<td align="right">-49.0%</td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">18,099,192</td>
<td align="right">9,261,826</td>
<td align="right">-48.8%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">73,084,583</td>
<td align="right">38,786,693</td>
<td align="right">-46.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,224,954,186</td>
<td align="right">1,726,990,650</td>
<td align="right">-46.4%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">85,221,075</td>
<td align="right">45,717,739</td>
<td align="right">-46.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">478,199,419</td>
<td align="right">264,598,298</td>
<td align="right">-44.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">2,960,427,653</td>
<td align="right">1,647,592,049</td>
<td align="right">-44.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">5,392,352,307</td>
<td align="right">3,019,432,329</td>
<td align="right">-44.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">283,837,790</td>
<td align="right">160,369,539</td>
<td align="right">-43.5%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">154,119,102</td>
<td align="right">88,734,060</td>
<td align="right">-42.4%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">198,255,914</td>
<td align="right">115,583,041</td>
<td align="right">-41.7%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">5,992,168,767</td>
<td align="right">3,506,681,374</td>
<td align="right">-41.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">1,740,401,231</td>
<td align="right">1,035,776,200</td>
<td align="right">-40.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">1,559,813,166</td>
<td align="right">935,207,948</td>
<td align="right">-40.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">87,444,718</td>
<td align="right">52,932,765</td>
<td align="right">-39.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">137,954,890</td>
<td align="right">85,573,595</td>
<td align="right">-38.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_BOUND_METHOD</td>
<td align="right">1,534,154</td>
<td align="right">952,666</td>
<td align="right">-37.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">67,149,298</td>
<td align="right">43,500,507</td>
<td align="right">-35.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">63,521,213</td>
<td align="right">41,379,556</td>
<td align="right">-34.9%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">8,205,425</td>
<td align="right">5,366,503</td>
<td align="right">-34.6%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">25,373,211</td>
<td align="right">17,136,213</td>
<td align="right">-32.5%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">71,754,240</td>
<td align="right">48,504,524</td>
<td align="right">-32.4%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">25,373,217</td>
<td align="right">17,174,383</td>
<td align="right">-32.3%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">25,050,552</td>
<td align="right">17,224,924</td>
<td align="right">-31.2%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">169,232,991</td>
<td align="right">116,759,984</td>
<td align="right">-31.0%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">384,771,502</td>
<td align="right">266,892,177</td>
<td align="right">-30.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">571,226,616</td>
<td align="right">408,013,248</td>
<td align="right">-28.6%</td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">7,395,594</td>
<td align="right">5,386,514</td>
<td align="right">-27.2%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">104,649,180</td>
<td align="right">76,295,296</td>
<td align="right">-27.1%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">6,113,780</td>
<td align="right">4,515,276</td>
<td align="right">-26.1%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">1,614,166</td>
<td align="right">1,214,992</td>
<td align="right">-24.7%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">6,741,387</td>
<td align="right">5,258,911</td>
<td align="right">-22.0%</td>
</tr>
<tr>
<td align="left">DELETE_NAME</td>
<td align="right">882</td>
<td align="right">722</td>
<td align="right">-18.1%</td>
</tr>
<tr>
<td align="left">DICT_UPDATE</td>
<td align="right">20,012</td>
<td align="right">16,524</td>
<td align="right">-17.4%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">1,429,333</td>
<td align="right">1,194,057</td>
<td align="right">-16.5%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">24,797</td>
<td align="right">20,775</td>
<td align="right">-16.2%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">819,566,472</td>
<td align="right">711,150,149</td>
<td align="right">-13.2%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">7,320,213</td>
<td align="right">6,365,256</td>
<td align="right">-13.0%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">235,624,038</td>
<td align="right">207,255,566</td>
<td align="right">-12.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">949,589,539</td>
<td align="right">837,853,312</td>
<td align="right">-11.8%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">233,486,996</td>
<td align="right">206,941,498</td>
<td align="right">-11.4%</td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">52,013</td>
<td align="right">46,156</td>
<td align="right">-11.3%</td>
</tr>
<tr>
<td align="left">LOAD_FROM_DICT_OR_DEREF</td>
<td align="right">1,785</td>
<td align="right">1,596</td>
<td align="right">-10.6%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">189,524,099</td>
<td align="right">170,680,667</td>
<td align="right">-9.9%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">345,702</td>
<td align="right">314,561</td>
<td align="right">-9.0%</td>
</tr>
<tr>
<td align="left">SET_ADD</td>
<td align="right">78,726</td>
<td align="right">71,686</td>
<td align="right">-8.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">97,887</td>
<td align="right">89,492</td>
<td align="right">-8.6%</td>
</tr>
<tr>
<td align="left">GET_AWAITABLE</td>
<td align="right">91,029,777</td>
<td align="right">83,740,758</td>
<td align="right">-8.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">1,672,620</td>
<td align="right">1,541,249</td>
<td align="right">-7.9%</td>
</tr>
<tr>
<td align="left">GET_YIELD_FROM_ITER</td>
<td align="right">24,628,360</td>
<td align="right">22,917,525</td>
<td align="right">-6.9%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">334,218,807</td>
<td align="right">311,844,759</td>
<td align="right">-6.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">20,314,038</td>
<td align="right">18,997,866</td>
<td align="right">-6.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">255,909,599</td>
<td align="right">239,785,208</td>
<td align="right">-6.3%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">112,741</td>
<td align="right">105,773</td>
<td align="right">-6.2%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">71,780,160</td>
<td align="right">67,773,544</td>
<td align="right">-5.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">1,114,039</td>
<td align="right">1,052,219</td>
<td align="right">-5.5%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">214,354,156</td>
<td align="right">204,459,946</td>
<td align="right">-4.6%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">1,566,228,728</td>
<td align="right">1,511,952,923</td>
<td align="right">-3.5%</td>
</tr>
<tr>
<td align="left">BUILD_SET</td>
<td align="right">562,653</td>
<td align="right">544,583</td>
<td align="right">-3.2%</td>
</tr>
<tr>
<td align="left">DELETE_ATTR</td>
<td align="right">395,499</td>
<td align="right">391,597</td>
<td align="right">-1.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">16,767</td>
<td align="right">16,608</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">22,830</td>
<td align="right">22,713</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">136,399,413</td>
<td align="right">136,657,377</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">43,484,604</td>
<td align="right">43,437,198</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">SET_UPDATE</td>
<td align="right">73,794</td>
<td align="right">73,754</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">CLEANUP_THROW</td>
<td align="right">120,813</td>
<td align="right">120,815</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">NOT_TAKEN</td>
<td align="right">98,843,598</td>
<td align="right">98,843,598</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">GET_AITER</td>
<td align="right">6,300,000</td>
<td align="right">6,300,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">6,300,000</td>
<td align="right">6,300,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_EX</td>
<td align="right">114,723</td>
<td align="right">114,723</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_GETATTRIBUTE_OVERRIDDEN</td>
<td align="right">73,668</td>
<td align="right">73,668</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SETUP_ANNOTATIONS</td>
<td align="right">3,696</td>
<td align="right">3,696</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FORMAT_WITH_SPEC</td>
<td align="right">2,709</td>
<td align="right">2,709</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FROM_DICT_OR_GLOBALS</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">942,179,095</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">144,261,689</td>
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
<td align="right">14,341,351,300</td>
<td align="right">86.4%</td>
<td align="right">1,804,870,437</td>
<td align="right">78.9%</td>
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
<td align="right">2,193,250,847</td>
<td align="right">13.2%</td>
<td align="right">442,227,271</td>
<td align="right">19.3%</td>
<td align="right">-79.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">70,897,540</td>
<td align="right">0.4%</td>
<td align="right">38,709,855</td>
<td align="right">1.7%</td>
<td align="right">-45.4%</td>
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
<td align="right">1,008,141</td>
<td align="right">40.2%</td>
<td align="right">454,688</td>
<td align="right">34.1%</td>
<td align="right">-54.9%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">1,502,110</td>
<td align="right">59.8%</td>
<td align="right">878,314</td>
<td align="right">65.9%</td>
<td align="right">-41.5%</td>
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
<td align="left">subscr array</td>
<td align="right">126,579</td>
<td align="right">12.6%</td>
<td align="right">22,708</td>
<td align="right">5.0%</td>
<td align="right">-82.1%</td>
</tr>
<tr>
<td align="left">subscr tuple slice</td>
<td align="right">109,437</td>
<td align="right">10.9%</td>
<td align="right">23,846</td>
<td align="right">5.2%</td>
<td align="right">-78.2%</td>
</tr>
<tr>
<td align="left">subscr bytes</td>
<td align="right">23,181</td>
<td align="right">2.3%</td>
<td align="right">5,853</td>
<td align="right">1.3%</td>
<td align="right">-74.8%</td>
</tr>
<tr>
<td align="left">subscr counter</td>
<td align="right">114,030</td>
<td align="right">11.3%</td>
<td align="right">29,011</td>
<td align="right">6.4%</td>
<td align="right">-74.6%</td>
</tr>
<tr>
<td align="left">subscr defaultdict</td>
<td align="right">91,122</td>
<td align="right">9.0%</td>
<td align="right">28,830</td>
<td align="right">6.3%</td>
<td align="right">-68.4%</td>
</tr>
<tr>
<td align="left">and int</td>
<td align="right">38,119</td>
<td align="right">3.8%</td>
<td align="right">12,150</td>
<td align="right">2.7%</td>
<td align="right">-68.1%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">53,720</td>
<td align="right">5.3%</td>
<td align="right">21,225</td>
<td align="right">4.7%</td>
<td align="right">-60.5%</td>
</tr>
<tr>
<td align="left">xor int</td>
<td align="right">48,300</td>
<td align="right">4.8%</td>
<td align="right">19,656</td>
<td align="right">4.3%</td>
<td align="right">-59.3%</td>
</tr>
<tr>
<td align="left">lshift</td>
<td align="right">23,463</td>
<td align="right">2.3%</td>
<td align="right">9,584</td>
<td align="right">2.1%</td>
<td align="right">-59.2%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">59,172</td>
<td align="right">5.9%</td>
<td align="right">31,079</td>
<td align="right">6.8%</td>
<td align="right">-47.5%</td>
</tr>
<tr>
<td align="left">rshift</td>
<td align="right">25,031</td>
<td align="right">2.5%</td>
<td align="right">13,422</td>
<td align="right">3.0%</td>
<td align="right">-46.4%</td>
</tr>
<tr>
<td align="left">true divide float</td>
<td align="right">9,599</td>
<td align="right">1.0%</td>
<td align="right">5,529</td>
<td align="right">1.2%</td>
<td align="right">-42.4%</td>
</tr>
<tr>
<td align="left">and other</td>
<td align="right">1,787</td>
<td align="right">0.2%</td>
<td align="right">1,030</td>
<td align="right">0.2%</td>
<td align="right">-42.4%</td>
</tr>
<tr>
<td align="left">subscr mappingproxy</td>
<td align="right">924</td>
<td align="right">0.1%</td>
<td align="right">567</td>
<td align="right">0.1%</td>
<td align="right">-38.6%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">63,720</td>
<td align="right">6.3%</td>
<td align="right">40,555</td>
<td align="right">8.9%</td>
<td align="right">-36.4%</td>
</tr>
<tr>
<td align="left">power</td>
<td align="right">9,044</td>
<td align="right">0.9%</td>
<td align="right">6,038</td>
<td align="right">1.3%</td>
<td align="right">-33.2%</td>
</tr>
<tr>
<td align="left">xor</td>
<td align="right">735</td>
<td align="right">0.1%</td>
<td align="right">937</td>
<td align="right">0.2%</td>
<td align="right">27.5%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">43,615</td>
<td align="right">4.3%</td>
<td align="right">31,968</td>
<td align="right">7.0%</td>
<td align="right">-26.7%</td>
</tr>
<tr>
<td align="left">subscr</td>
<td align="right">16,431</td>
<td align="right">1.6%</td>
<td align="right">20,370</td>
<td align="right">4.5%</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">69,454</td>
<td align="right">6.9%</td>
<td align="right">53,982</td>
<td align="right">11.9%</td>
<td align="right">-22.3%</td>
</tr>
<tr>
<td align="left">subscr string slice</td>
<td align="right">8,678</td>
<td align="right">0.9%</td>
<td align="right">7,257</td>
<td align="right">1.6%</td>
<td align="right">-16.4%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">5,672</td>
<td align="right">0.6%</td>
<td align="right">4,975</td>
<td align="right">1.1%</td>
<td align="right">-12.3%</td>
</tr>
<tr>
<td align="left">true divide other</td>
<td align="right">2,732</td>
<td align="right">0.3%</td>
<td align="right">3,067</td>
<td align="right">0.7%</td>
<td align="right">12.3%</td>
</tr>
<tr>
<td align="left">and different types</td>
<td align="right">357</td>
<td align="right">0.0%</td>
<td align="right">317</td>
<td align="right">0.1%</td>
<td align="right">-11.2%</td>
</tr>
<tr>
<td align="left">multiply other</td>
<td align="right">19,006</td>
<td align="right">1.9%</td>
<td align="right">17,495</td>
<td align="right">3.8%</td>
<td align="right">-8.0%</td>
</tr>
<tr>
<td align="left">subtract different types</td>
<td align="right">1,428</td>
<td align="right">0.1%</td>
<td align="right">1,323</td>
<td align="right">0.3%</td>
<td align="right">-7.4%</td>
</tr>
<tr>
<td align="left">subscr other slice</td>
<td align="right">1,259</td>
<td align="right">0.1%</td>
<td align="right">1,345</td>
<td align="right">0.3%</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">subscr range</td>
<td align="right">3,972</td>
<td align="right">0.4%</td>
<td align="right">4,205</td>
<td align="right">0.9%</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">subtract other</td>
<td align="right">14,436</td>
<td align="right">1.4%</td>
<td align="right">13,678</td>
<td align="right">3.0%</td>
<td align="right">-5.3%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">17,335</td>
<td align="right">1.7%</td>
<td align="right">16,880</td>
<td align="right">3.7%</td>
<td align="right">-2.6%</td>
</tr>
<tr>
<td align="left">subscr deque</td>
<td align="right">478</td>
<td align="right">0.0%</td>
<td align="right">477</td>
<td align="right">0.1%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">true divide different types</td>
<td align="right">4,272</td>
<td align="right">0.4%</td>
<td align="right">4,276</td>
<td align="right">0.9%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">or different types</td>
<td align="right">609</td>
<td align="right">0.1%</td>
<td align="right">609</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr structtime</td>
<td align="right">147</td>
<td align="right">0.0%</td>
<td align="right">147</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr ordereddict</td>
<td align="right">129</td>
<td align="right">0.0%</td>
<td align="right">129</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">code complex parameters</td>
<td align="right">84</td>
<td align="right">0.0%</td>
<td align="right">84</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">or int</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr enumdict</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">42</td>
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
<td align="right">540,175,642</td>
<td align="right">100.0%</td>
<td align="right">71,327,724</td>
<td align="right">100.0%</td>
<td align="right">-86.8%</td>
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
<td align="right">10,428,529,338</td>
<td align="right">98.4%</td>
<td align="right">2,953,058,111</td>
<td align="right">96.3%</td>
<td align="right">-71.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">167,156,343</td>
<td align="right">1.6%</td>
<td align="right">110,536,851</td>
<td align="right">3.6%</td>
<td align="right">-33.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">165,034,334</td>
<td align="right">1.6%</td>
<td align="right">109,402,152</td>
<td align="right">3.6%</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">6,720</td>
<td align="right">0.0%</td>
<td align="right">6,720</td>
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
<td align="right">3,794,502</td>
<td align="right">100.0%</td>
<td align="right">2,675,821</td>
<td align="right">100.0%</td>
<td align="right">-29.5%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">127</td>
<td align="right">0.0%</td>
<td align="right">127</td>
<td align="right">0.0%</td>
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
<td align="left">init not python</td>
<td align="right">1,008</td>
<td align="right">793.7%</td>
<td align="right">484</td>
<td align="right">381.1%</td>
<td align="right">-52.0%</td>
</tr>
<tr>
<td align="left">init not simple</td>
<td align="right">3,444</td>
<td align="right">2,711.8%</td>
<td align="right">2,030</td>
<td align="right">1,598.4%</td>
<td align="right">-41.1%</td>
</tr>
<tr>
<td align="left">out of versions</td>
<td align="right">127</td>
<td align="right">100.0%</td>
<td align="right">127</td>
<td align="right">100.0%</td>
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
<td align="right">690,800</td>
<td align="right">91.4%</td>
<td align="right">685,754</td>
<td align="right">91.8%</td>
<td align="right">-0.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">642,774</td>
<td align="right">85.1%</td>
<td align="right">641,391</td>
<td align="right">85.8%</td>
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
<td align="right">64,715</td>
<td align="right">100.0%</td>
<td align="right">61,410</td>
<td align="right">100.0%</td>
<td align="right">-5.1%</td>
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
<td align="right">5,239,849</td>
<td align="right">0.1%</td>
<td align="right">793,339</td>
<td align="right">0.1%</td>
<td align="right">-84.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">506,158,144</td>
<td align="right">10.5%</td>
<td align="right">81,850,763</td>
<td align="right">9.2%</td>
<td align="right">-83.8%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">4,320,208,628</td>
<td align="right">89.4%</td>
<td align="right">805,685,565</td>
<td align="right">90.7%</td>
<td align="right">-81.4%</td>
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
<td align="right">342,194</td>
<td align="right">66.3%</td>
<td align="right">159,880</td>
<td align="right">65.2%</td>
<td align="right">-53.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">174,319</td>
<td align="right">33.7%</td>
<td align="right">85,284</td>
<td align="right">34.8%</td>
<td align="right">-51.1%</td>
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
<td align="right">97,546</td>
<td align="right">28.5%</td>
<td align="right">12,826</td>
<td align="right">8.0%</td>
<td align="right">-86.9%</td>
</tr>
<tr>
<td align="left">float long</td>
<td align="right">94,828</td>
<td align="right">27.7%</td>
<td align="right">18,036</td>
<td align="right">11.3%</td>
<td align="right">-81.0%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">7,957</td>
<td align="right">2.3%</td>
<td align="right">2,057</td>
<td align="right">1.3%</td>
<td align="right">-74.1%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">3,874</td>
<td align="right">1.1%</td>
<td align="right">4,967</td>
<td align="right">3.1%</td>
<td align="right">28.2%</td>
</tr>
<tr>
<td align="left">different types</td>
<td align="right">58,063</td>
<td align="right">17.0%</td>
<td align="right">43,112</td>
<td align="right">27.0%</td>
<td align="right">-25.7%</td>
</tr>
<tr>
<td align="left">bool</td>
<td align="right">2,881</td>
<td align="right">0.8%</td>
<td align="right">3,556</td>
<td align="right">2.2%</td>
<td align="right">23.4%</td>
</tr>
<tr>
<td align="left">long float</td>
<td align="right">525</td>
<td align="right">0.2%</td>
<td align="right">441</td>
<td align="right">0.3%</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">3,465</td>
<td align="right">1.0%</td>
<td align="right">3,216</td>
<td align="right">2.0%</td>
<td align="right">-7.2%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">24,564</td>
<td align="right">7.2%</td>
<td align="right">23,245</td>
<td align="right">14.5%</td>
<td align="right">-5.4%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">19,618</td>
<td align="right">5.7%</td>
<td align="right">20,650</td>
<td align="right">12.9%</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">19,654</td>
<td align="right">5.7%</td>
<td align="right">18,891</td>
<td align="right">11.8%</td>
<td align="right">-3.9%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">9,219</td>
<td align="right">2.7%</td>
<td align="right">8,883</td>
<td align="right">5.6%</td>
<td align="right">-3.6%</td>
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
<td align="right">2,005,833,886</td>
<td align="right">93.7%</td>
<td align="right">203,754,066</td>
<td align="right">86.7%</td>
<td align="right">-89.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">133,679,007</td>
<td align="right">6.2%</td>
<td align="right">30,484,903</td>
<td align="right">13.0%</td>
<td align="right">-77.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,032,554</td>
<td align="right">0.0%</td>
<td align="right">700,522</td>
<td align="right">0.3%</td>
<td align="right">-32.2%</td>
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
<td align="right">35,276</td>
<td align="right">23.5%</td>
<td align="right">27,265</td>
<td align="right">22.8%</td>
<td align="right">-22.7%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">114,984</td>
<td align="right">76.5%</td>
<td align="right">92,331</td>
<td align="right">77.2%</td>
<td align="right">-19.7%</td>
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
<td align="right">22,753</td>
<td align="right">19.8%</td>
<td align="right">13,816</td>
<td align="right">15.0%</td>
<td align="right">-39.3%</td>
</tr>
<tr>
<td align="left">str</td>
<td align="right">42,557</td>
<td align="right">37.0%</td>
<td align="right">33,473</td>
<td align="right">36.3%</td>
<td align="right">-21.3%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">18,265</td>
<td align="right">15.9%</td>
<td align="right">15,963</td>
<td align="right">17.3%</td>
<td align="right">-12.6%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">31,409</td>
<td align="right">27.3%</td>
<td align="right">29,079</td>
<td align="right">31.5%</td>
<td align="right">-7.4%</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">163,899,130</td>
<td align="right">3.8%</td>
<td align="right">5,281,496</td>
<td align="right">1.2%</td>
<td align="right">-96.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,064,921,456</td>
<td align="right">24.4%</td>
<td align="right">81,301,831</td>
<td align="right">18.7%</td>
<td align="right">-92.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">3,140,318,602</td>
<td align="right">71.9%</td>
<td align="right">347,882,394</td>
<td align="right">80.0%</td>
<td align="right">-88.9%</td>
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
<td align="right">3,154,931</td>
<td align="right">88.3%</td>
<td align="right">158,454</td>
<td align="right">40.1%</td>
<td align="right">-95.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">419,784</td>
<td align="right">11.7%</td>
<td align="right">237,063</td>
<td align="right">59.9%</td>
<td align="right">-43.5%</td>
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
<td align="right">174,123</td>
<td align="right">41.5%</td>
<td align="right">14,741</td>
<td align="right">6.2%</td>
<td align="right">-91.5%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">1,911</td>
<td align="right">0.5%</td>
<td align="right">3,486</td>
<td align="right">1.5%</td>
<td align="right">82.4%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">39,418</td>
<td align="right">9.4%</td>
<td align="right">19,880</td>
<td align="right">8.4%</td>
<td align="right">-49.6%</td>
</tr>
<tr>
<td align="left">itertools</td>
<td align="right">7,949</td>
<td align="right">1.9%</td>
<td align="right">10,508</td>
<td align="right">4.4%</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">16,164</td>
<td align="right">3.9%</td>
<td align="right">11,484</td>
<td align="right">4.8%</td>
<td align="right">-29.0%</td>
</tr>
<tr>
<td align="left">seq iter</td>
<td align="right">23,751</td>
<td align="right">5.7%</td>
<td align="right">17,390</td>
<td align="right">7.3%</td>
<td align="right">-26.8%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">23,035</td>
<td align="right">5.5%</td>
<td align="right">17,414</td>
<td align="right">7.3%</td>
<td align="right">-24.4%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">2,079</td>
<td align="right">0.5%</td>
<td align="right">1,586</td>
<td align="right">0.7%</td>
<td align="right">-23.7%</td>
</tr>
<tr>
<td align="left">ascii string</td>
<td align="right">5,143</td>
<td align="right">1.2%</td>
<td align="right">5,833</td>
<td align="right">2.5%</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">91,951</td>
<td align="right">21.9%</td>
<td align="right">102,066</td>
<td align="right">43.1%</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">map</td>
<td align="right">1,155</td>
<td align="right">0.3%</td>
<td align="right">1,036</td>
<td align="right">0.4%</td>
<td align="right">-10.3%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">11,716</td>
<td align="right">2.8%</td>
<td align="right">10,855</td>
<td align="right">4.6%</td>
<td align="right">-7.3%</td>
</tr>
<tr>
<td align="left">callable</td>
<td align="right">504</td>
<td align="right">0.1%</td>
<td align="right">526</td>
<td align="right">0.2%</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">7,721</td>
<td align="right">1.8%</td>
<td align="right">7,407</td>
<td align="right">3.1%</td>
<td align="right">-4.1%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">7,717</td>
<td align="right">1.8%</td>
<td align="right">7,499</td>
<td align="right">3.2%</td>
<td align="right">-2.8%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">5,447</td>
<td align="right">1.3%</td>
<td align="right">5,352</td>
<td align="right">2.3%</td>
<td align="right">-1.7%</td>
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
<td align="left">enumerate</td>
<td align="right">5,664,032</td>
<td align="right">5,664,032 / 0 !!</td>
<td align="right">3,379,559</td>
<td align="right">3,379,559 / 0 !!</td>
<td align="right">-40.3%</td>
</tr>
<tr>
<td align="left">generator</td>
<td align="right">104,106,345</td>
<td align="right">104,106,345 / 0 !!</td>
<td align="right">65,378,529</td>
<td align="right">65,378,529 / 0 !!</td>
<td align="right">-37.2%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">2,217,528</td>
<td align="right">2,217,528 / 0 !!</td>
<td align="right">1,506,584</td>
<td align="right">1,506,584 / 0 !!</td>
<td align="right">-32.1%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">164,551,655</td>
<td align="right">164,551,655 / 0 !!</td>
<td align="right">127,886,775</td>
<td align="right">127,886,775 / 0 !!</td>
<td align="right">-22.3%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">316,623,300</td>
<td align="right">316,623,300 / 0 !!</td>
<td align="right">257,205,667</td>
<td align="right">257,205,667 / 0 !!</td>
<td align="right">-18.8%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">1,060,476</td>
<td align="right">1,060,476 / 0 !!</td>
<td align="right">862,065</td>
<td align="right">862,065 / 0 !!</td>
<td align="right">-18.7%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">11,025,200</td>
<td align="right">11,025,200 / 0 !!</td>
<td align="right">9,722,467</td>
<td align="right">9,722,467 / 0 !!</td>
<td align="right">-11.8%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">102,956,000</td>
<td align="right">102,956,000 / 0 !!</td>
<td align="right">92,465,661</td>
<td align="right">92,465,661 / 0 !!</td>
<td align="right">-10.2%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">336,044,932</td>
<td align="right">336,044,932 / 0 !!</td>
<td align="right">333,957,716</td>
<td align="right">333,957,716 / 0 !!</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">814,338</td>
<td align="right">814,338 / 0 !!</td>
<td align="right">814,278</td>
<td align="right">814,278 / 0 !!</td>
<td align="right">-0.0%</td>
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
<td align="right">729,535,577</td>
<td align="right">5.5%</td>
<td align="right">217,293,753</td>
<td align="right">4.4%</td>
<td align="right">-70.2%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">11,651,412,547</td>
<td align="right">87.1%</td>
<td align="right">4,369,178,310</td>
<td align="right">88.0%</td>
<td align="right">-62.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">996,173,861</td>
<td align="right">7.4%</td>
<td align="right">377,946,649</td>
<td align="right">7.6%</td>
<td align="right">-62.1%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,139,341</td>
<td align="right">0.0%</td>
<td align="right">1,140,882</td>
<td align="right">0.0%</td>
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
<td align="right">14,427,746</td>
<td align="right">93.8%</td>
<td align="right">4,761,914</td>
<td align="right">86.6%</td>
<td align="right">-67.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">950,004</td>
<td align="right">6.2%</td>
<td align="right">734,551</td>
<td align="right">13.4%</td>
<td align="right">-22.7%</td>
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
<td align="left">not in dict</td>
<td align="right">987</td>
<td align="right">0.1%</td>
<td align="right">364</td>
<td align="right">0.0%</td>
<td align="right">-63.1%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">125,109</td>
<td align="right">13.2%</td>
<td align="right">81,435</td>
<td align="right">11.1%</td>
<td align="right">-34.9%</td>
</tr>
<tr>
<td align="left">non overriding descriptor</td>
<td align="right">19,501</td>
<td align="right">2.1%</td>
<td align="right">14,686</td>
<td align="right">2.0%</td>
<td align="right">-24.7%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">4,860</td>
<td align="right">0.5%</td>
<td align="right">3,756</td>
<td align="right">0.5%</td>
<td align="right">-22.7%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">125,241</td>
<td align="right">13.2%</td>
<td align="right">100,728</td>
<td align="right">13.7%</td>
<td align="right">-19.6%</td>
</tr>
<tr>
<td align="left">metaclass attribute</td>
<td align="right">42,808</td>
<td align="right">4.5%</td>
<td align="right">38,015</td>
<td align="right">5.2%</td>
<td align="right">-11.2%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">22,029</td>
<td align="right">2.3%</td>
<td align="right">24,049</td>
<td align="right">3.3%</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">59,492</td>
<td align="right">6.3%</td>
<td align="right">54,695</td>
<td align="right">7.4%</td>
<td align="right">-8.1%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">17,330</td>
<td align="right">1.8%</td>
<td align="right">16,575</td>
<td align="right">2.3%</td>
<td align="right">-4.4%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">139,063</td>
<td align="right">14.6%</td>
<td align="right">135,722</td>
<td align="right">18.5%</td>
<td align="right">-2.4%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">29,338</td>
<td align="right">3.1%</td>
<td align="right">29,976</td>
<td align="right">4.1%</td>
<td align="right">2.2%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">106</td>
<td align="right">0.0%</td>
<td align="right">105</td>
<td align="right">0.0%</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">3,235</td>
<td align="right">0.3%</td>
<td align="right">3,259</td>
<td align="right">0.4%</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">expected error</td>
<td align="right">5,043</td>
<td align="right">0.5%</td>
<td align="right">5,046</td>
<td align="right">0.7%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">2,986</td>
<td align="right">0.3%</td>
<td align="right">2,986</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">wrong number arguments</td>
<td align="right">1,092</td>
<td align="right">0.1%</td>
<td align="right">1,092</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">out of versions</td>
<td align="right">336</td>
<td align="right">0.0%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
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
<td align="right">8,898,112,480</td>
<td align="right">100.0%</td>
<td align="right">2,804,959,776</td>
<td align="right">100.0%</td>
<td align="right">-68.5%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,597</td>
<td align="right">0.0%</td>
<td align="right">1,177</td>
<td align="right">0.0%</td>
<td align="right">-26.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">312,853</td>
<td align="right">0.0%</td>
<td align="right">283,680</td>
<td align="right">0.0%</td>
<td align="right">-9.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">563,563</td>
<td align="right">0.0%</td>
<td align="right">532,226</td>
<td align="right">0.0%</td>
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
<td align="left">Success</td>
<td align="right">555,833</td>
<td align="right">100.0%</td>
<td align="right">524,816</td>
<td align="right">100.0%</td>
<td align="right">-5.6%</td>
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
<td align="right">106,078,513</td>
<td align="right">100.0%</td>
<td align="right">77,489,353</td>
<td align="right">100.0%</td>
<td align="right">-27.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">8,273</td>
<td align="right">0.0%</td>
<td align="right">8,195</td>
<td align="right">0.0%</td>
<td align="right">-0.9%</td>
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
<td align="right">8,494</td>
<td align="right">100.0%</td>
<td align="right">8,413</td>
<td align="right">100.0%</td>
<td align="right">-1.0%</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">27,421</td>
<td align="right">0.0%</td>
<td align="right">23,916</td>
<td align="right">0.0%</td>
<td align="right">-12.8%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">334,191,386</td>
<td align="right">71.0%</td>
<td align="right">311,820,843</td>
<td align="right">69.5%</td>
<td align="right">-6.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">136,345,179</td>
<td align="right">29.0%</td>
<td align="right">136,332,539</td>
<td align="right">30.4%</td>
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
<td align="left">Failure</td>
<td align="right">49,089</td>
<td align="right">89.7%</td>
<td align="right">319,754</td>
<td align="right">98.3%</td>
<td align="right">551.4%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">5,651</td>
<td align="right">10.3%</td>
<td align="right">5,526</td>
<td align="right">1.7%</td>
<td align="right">-2.2%</td>
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
<td align="left">async generator send</td>
<td align="right">26,292</td>
<td align="right">53.6%</td>
<td align="right">289,590</td>
<td align="right">90.6%</td>
<td align="right">1,001.4%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">10,920</td>
<td align="right">22.2%</td>
<td align="right">17,136</td>
<td align="right">5.4%</td>
<td align="right">56.9%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">2,121</td>
<td align="right">4.3%</td>
<td align="right">2,751</td>
<td align="right">0.9%</td>
<td align="right">29.7%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">9,756</td>
<td align="right">19.9%</td>
<td align="right">10,277</td>
<td align="right">3.2%</td>
<td align="right">5.3%</td>
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
<td align="right">110,535,564</td>
<td align="right">5.6%</td>
<td align="right">42,673,661</td>
<td align="right">3.2%</td>
<td align="right">-61.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">67,656,265</td>
<td align="right">3.5%</td>
<td align="right">32,657,355</td>
<td align="right">2.5%</td>
<td align="right">-51.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,781,808,252</td>
<td align="right">90.9%</td>
<td align="right">1,251,417,495</td>
<td align="right">94.3%</td>
<td align="right">-29.8%</td>
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
<td align="right">2,204,170</td>
<td align="right">95.4%</td>
<td align="right">916,791</td>
<td align="right">92.1%</td>
<td align="right">-58.4%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">105,819</td>
<td align="right">4.6%</td>
<td align="right">78,818</td>
<td align="right">7.9%</td>
<td align="right">-25.5%</td>
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
<td align="left">not in dict</td>
<td align="right">13,545</td>
<td align="right">12.8%</td>
<td align="right">7,318</td>
<td align="right">9.3%</td>
<td align="right">-46.0%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">45,715</td>
<td align="right">43.2%</td>
<td align="right">25,704</td>
<td align="right">32.6%</td>
<td align="right">-43.8%</td>
</tr>
<tr>
<td align="left">no dict</td>
<td align="right">462</td>
<td align="right">0.4%</td>
<td align="right">281</td>
<td align="right">0.4%</td>
<td align="right">-39.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">329,310</td>
<td align="right">311.2%</td>
<td align="right">200,431</td>
<td align="right">254.3%</td>
<td align="right">-39.1%</td>
</tr>
<tr>
<td align="left">split dict</td>
<td align="right">8,001</td>
<td align="right">7.6%</td>
<td align="right">10,508</td>
<td align="right">13.3%</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">7,581</td>
<td align="right">7.2%</td>
<td align="right">5,206</td>
<td align="right">6.6%</td>
<td align="right">-31.3%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">4,077</td>
<td align="right">3.9%</td>
<td align="right">4,268</td>
<td align="right">5.4%</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">1,911</td>
<td align="right">1.8%</td>
<td align="right">1,828</td>
<td align="right">2.3%</td>
<td align="right">-4.3%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">9,618</td>
<td align="right">9.1%</td>
<td align="right">9,208</td>
<td align="right">11.7%</td>
<td align="right">-4.3%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">10,793</td>
<td align="right">10.2%</td>
<td align="right">10,710</td>
<td align="right">13.6%</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">294</td>
<td align="right">0.3%</td>
<td align="right">294</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">273</td>
<td align="right">0.3%</td>
<td align="right">273</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">126</td>
<td align="right">0.1%</td>
<td align="right">126</td>
<td align="right">0.2%</td>
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
<td align="right">113,968,040</td>
<td align="right">100.0%</td>
<td align="right">601,758</td>
<td align="right">100.0%</td>
<td align="right">-99.5%</td>
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
<td align="right">700,752,565</td>
<td align="right">54.7%</td>
<td align="right">67,440,341</td>
<td align="right">51.7%</td>
<td align="right">-90.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">580,406,063</td>
<td align="right">45.3%</td>
<td align="right">62,957,177</td>
<td align="right">48.2%</td>
<td align="right">-89.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,268</td>
<td align="right">0.0%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
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
<td align="right">227,739</td>
<td align="right">93.1%</td>
<td align="right">79,796</td>
<td align="right">84.6%</td>
<td align="right">-65.0%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">16,752</td>
<td align="right">6.9%</td>
<td align="right">14,490</td>
<td align="right">15.4%</td>
<td align="right">-13.5%</td>
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
<td align="right">85,895</td>
<td align="right">37.7%</td>
<td align="right">1,102</td>
<td align="right">1.4%</td>
<td align="right">-98.7%</td>
</tr>
<tr>
<td align="left">bytearray int</td>
<td align="right">9,366</td>
<td align="right">4.1%</td>
<td align="right">2,918</td>
<td align="right">3.7%</td>
<td align="right">-68.8%</td>
</tr>
<tr>
<td align="left">array int</td>
<td align="right">53,689</td>
<td align="right">23.6%</td>
<td align="right">17,863</td>
<td align="right">22.4%</td>
<td align="right">-66.7%</td>
</tr>
<tr>
<td align="left">dict subclass no override</td>
<td align="right">24,513</td>
<td align="right">10.8%</td>
<td align="right">9,979</td>
<td align="right">12.5%</td>
<td align="right">-59.3%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">2,396</td>
<td align="right">1.1%</td>
<td align="right">1,047</td>
<td align="right">1.3%</td>
<td align="right">-56.3%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">4,600</td>
<td align="right">2.0%</td>
<td align="right">3,180</td>
<td align="right">4.0%</td>
<td align="right">-30.9%</td>
</tr>
<tr>
<td align="left">py simple</td>
<td align="right">47,112</td>
<td align="right">20.7%</td>
<td align="right">43,539</td>
<td align="right">54.6%</td>
<td align="right">-7.6%</td>
</tr>
<tr>
<td align="left">array slice</td>
<td align="right">168</td>
<td align="right">0.1%</td>
<td align="right">168</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">4,731,142,577</td>
<td align="right">93.3%</td>
<td align="right">1,559,660,368</td>
<td align="right">92.0%</td>
<td align="right">-67.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">245,198,187</td>
<td align="right">4.8%</td>
<td align="right">97,123,319</td>
<td align="right">5.7%</td>
<td align="right">-60.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">96,185,420</td>
<td align="right">1.9%</td>
<td align="right">38,864,087</td>
<td align="right">2.3%</td>
<td align="right">-59.6%</td>
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
<td align="right">621,106</td>
<td align="right">23.3%</td>
<td align="right">273,436</td>
<td align="right">22.3%</td>
<td align="right">-56.0%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">2,047,358</td>
<td align="right">76.7%</td>
<td align="right">952,957</td>
<td align="right">77.7%</td>
<td align="right">-53.5%</td>
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
<td align="right">130,336</td>
<td align="right">21.0%</td>
<td align="right">16,966</td>
<td align="right">6.2%</td>
<td align="right">-87.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">99,004</td>
<td align="right">15.9%</td>
<td align="right">43,004</td>
<td align="right">15.7%</td>
<td align="right">-56.6%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">52,341</td>
<td align="right">8.4%</td>
<td align="right">22,948</td>
<td align="right">8.4%</td>
<td align="right">-56.2%</td>
</tr>
<tr>
<td align="left">number</td>
<td align="right">270,593</td>
<td align="right">43.6%</td>
<td align="right">137,301</td>
<td align="right">50.2%</td>
<td align="right">-49.3%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">14,939</td>
<td align="right">2.4%</td>
<td align="right">8,065</td>
<td align="right">2.9%</td>
<td align="right">-46.0%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">22,029</td>
<td align="right">3.5%</td>
<td align="right">14,856</td>
<td align="right">5.4%</td>
<td align="right">-32.6%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">14,512</td>
<td align="right">2.3%</td>
<td align="right">12,949</td>
<td align="right">4.7%</td>
<td align="right">-10.8%</td>
</tr>
<tr>
<td align="left">float</td>
<td align="right">693</td>
<td align="right">0.1%</td>
<td align="right">714</td>
<td align="right">0.3%</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">15,630</td>
<td align="right">2.5%</td>
<td align="right">15,604</td>
<td align="right">5.7%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">memory view</td>
<td align="right">525</td>
<td align="right">0.1%</td>
<td align="right">525</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">bytearray</td>
<td align="right">504</td>
<td align="right">0.1%</td>
<td align="right">504</td>
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
<td align="right">1,331,627,194</td>
<td align="right">99.7%</td>
<td align="right">342,077,100</td>
<td align="right">99.3%</td>
<td align="right">-74.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,669,283</td>
<td align="right">0.1%</td>
<td align="right">616,320</td>
<td align="right">0.2%</td>
<td align="right">-63.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,504,393</td>
<td align="right">0.2%</td>
<td align="right">1,776,153</td>
<td align="right">0.5%</td>
<td align="right">-29.1%</td>
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
<td align="right">2,528</td>
<td align="right">2.6%</td>
<td align="right">3,039</td>
<td align="right">3.5%</td>
<td align="right">20.2%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">95,075</td>
<td align="right">97.4%</td>
<td align="right">83,434</td>
<td align="right">96.5%</td>
<td align="right">-12.2%</td>
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
<td align="right">1,835</td>
<td align="right">72.6%</td>
<td align="right">2,346</td>
<td align="right">77.2%</td>
<td align="right">27.8%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">378</td>
<td align="right">15.0%</td>
<td align="right">378</td>
<td align="right">12.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">iterator</td>
<td align="right">315</td>
<td align="right">12.5%</td>
<td align="right">315</td>
<td align="right">10.4%</td>
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
<td align="right">7,754,686,855</td>
<td align="right">3.9%</td>
<td align="right">1,714,389,931</td>
<td align="right">2.9%</td>
<td align="right">-77.9%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">73,819,835,710</td>
<td align="right">36.9%</td>
<td align="right">20,849,279,232</td>
<td align="right">35.8%</td>
<td align="right">-71.8%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">117,374,513,168</td>
<td align="right">58.6%</td>
<td align="right">35,233,725,202</td>
<td align="right">60.5%</td>
<td align="right">-70.0%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">1,348,146,151</td>
<td align="right">0.7%</td>
<td align="right">457,739,068</td>
<td align="right">0.8%</td>
<td align="right">-66.0%</td>
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
<td align="left">FOR_ITER</td>
<td align="right">1,064,921,456</td>
<td align="right">15.5%</td>
<td align="right">81,301,831</td>
<td align="right">5.3%</td>
<td align="right">-92.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">700,752,565</td>
<td align="right">10.2%</td>
<td align="right">67,440,341</td>
<td align="right">4.4%</td>
<td align="right">-90.4%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">540,175,642</td>
<td align="right">7.9%</td>
<td align="right">71,327,724</td>
<td align="right">4.7%</td>
<td align="right">-86.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">506,158,144</td>
<td align="right">7.4%</td>
<td align="right">81,850,763</td>
<td align="right">5.3%</td>
<td align="right">-83.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,193,250,847</td>
<td align="right">31.9%</td>
<td align="right">442,227,271</td>
<td align="right">28.9%</td>
<td align="right">-79.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">996,173,861</td>
<td align="right">14.5%</td>
<td align="right">377,946,649</td>
<td align="right">24.7%</td>
<td align="right">-62.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">245,198,187</td>
<td align="right">3.6%</td>
<td align="right">97,123,319</td>
<td align="right">6.3%</td>
<td align="right">-60.4%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">165,034,334</td>
<td align="right">2.4%</td>
<td align="right">109,402,152</td>
<td align="right">7.1%</td>
<td align="right">-33.7%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">136,345,179</td>
<td align="right">2.0%</td>
<td align="right">136,332,539</td>
<td align="right">8.9%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">133,679,007</td>
<td align="right">1.9%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">32,657,355</td>
<td align="right">2.1%</td>
<td align="right"></td>
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
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">212,745,714</td>
<td align="right">15.8%</td>
<td align="right">43,192,238</td>
<td align="right">9.4%</td>
<td align="right">-79.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">276,000,958</td>
<td align="right">20.5%</td>
<td align="right">68,998,283</td>
<td align="right">15.1%</td>
<td align="right">-75.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">90,763,438</td>
<td align="right">6.7%</td>
<td align="right">23,395,727</td>
<td align="right">5.1%</td>
<td align="right">-74.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">91,530,473</td>
<td align="right">6.8%</td>
<td align="right">25,478,508</td>
<td align="right">5.6%</td>
<td align="right">-72.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">43,608,228</td>
<td align="right">3.2%</td>
<td align="right">19,323,503</td>
<td align="right">4.2%</td>
<td align="right">-55.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">90,070,623</td>
<td align="right">6.7%</td>
<td align="right">43,991,794</td>
<td align="right">9.6%</td>
<td align="right">-51.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">66,684,532</td>
<td align="right">4.9%</td>
<td align="right">45,523,533</td>
<td align="right">9.9%</td>
<td align="right">-31.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">81,974,059</td>
<td align="right">6.1%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">81,867,458</td>
<td align="right">6.1%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">46,329,279</td>
<td align="right">3.4%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">22,577,743</td>
<td align="right">4.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">21,603,558</td>
<td align="right">4.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">17,164,493</td>
<td align="right">3.7%</td>
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
<td align="left">Frame objects created</td>
<td align="right">46,444,373</td>
<td align="right">0.7%</td>
<td align="right">33,787,829</td>
<td align="right">0.6%</td>
<td align="right">-27.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">21,213,641</td>
<td align="right">0.3%</td>
<td align="right">16,797,610</td>
<td align="right">0.3%</td>
<td align="right">-20.8%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">52,013</td>
<td align="right">0.0%</td>
<td align="right">46,156</td>
<td align="right">0.0%</td>
<td align="right">-11.3%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">4,739,064,490</td>
<td align="right">75.1%</td>
<td align="right">4,224,361,818</td>
<td align="right">73.6%</td>
<td align="right">-10.9%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">5,418,630,368</td>
<td align="right">85.9%</td>
<td align="right">4,905,765,189</td>
<td align="right">85.5%</td>
<td align="right">-9.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">268,314,678</td>
<td align="right">4.3%</td>
<td align="right">252,643,705</td>
<td align="right">4.4%</td>
<td align="right">-5.8%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">1,040,273,895</td>
<td align="right">16.5%</td>
<td align="right">993,630,087</td>
<td align="right">17.3%</td>
<td align="right">-4.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">1,042,438,401</td>
<td align="right">16.5%</td>
<td align="right">995,783,982</td>
<td align="right">17.3%</td>
<td align="right">-4.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">278,950,811</td>
<td align="right">4.4%</td>
<td align="right">267,088,882</td>
<td align="right">4.7%</td>
<td align="right">-4.3%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">1,571,047,937</td>
<td align="right">24.9%</td>
<td align="right">1,515,644,553</td>
<td align="right">26.4%</td>
<td align="right">-3.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">1,571,047,937</td>
<td align="right">24.9%</td>
<td align="right">1,515,644,553</td>
<td align="right">26.4%</td>
<td align="right">-3.5%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">528,609,536</td>
<td align="right">8.4%</td>
<td align="right">519,860,571</td>
<td align="right">9.1%</td>
<td align="right">-1.7%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">2,112,493</td>
<td align="right">0.0%</td>
<td align="right">2,107,739</td>
<td align="right">0.0%</td>
<td align="right">-0.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">137,519,784</td>
<td align="right">2.2%</td>
<td align="right">137,519,371</td>
<td align="right">2.4%</td>
<td align="right">-0.0%</td>
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
<td align="left">Method cache misses</td>
<td align="right">69,970,610</td>
<td align="right"></td>
<td align="right">21,480,210</td>
<td align="right"></td>
<td align="right">-69.3%</td>
</tr>
<tr>
<td align="left">Materialize dict (too big)</td>
<td align="right">4,536</td>
<td align="right">0.0%</td>
<td align="right">1,463</td>
<td align="right">0.0%</td>
<td align="right">-67.7%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">74,905,996</td>
<td align="right"></td>
<td align="right">26,563,086</td>
<td align="right"></td>
<td align="right">-64.5%</td>
</tr>
<tr>
<td align="left">Materialize dict (new key)</td>
<td align="right">301,310</td>
<td align="right">0.2%</td>
<td align="right">176,887</td>
<td align="right">0.1%</td>
<td align="right">-41.3%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">2,248,642,034</td>
<td align="right"></td>
<td align="right">1,610,399,972</td>
<td align="right"></td>
<td align="right">-28.4%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">22,874,355,617</td>
<td align="right">26.8%</td>
<td align="right">20,398,121,572</td>
<td align="right">25.9%</td>
<td align="right">-10.8%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">2,518,479,191</td>
<td align="right"></td>
<td align="right">2,276,740,442</td>
<td align="right"></td>
<td align="right">-9.6%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">1,613,222,385</td>
<td align="right">1.6%</td>
<td align="right">1,479,034,244</td>
<td align="right">1.6%</td>
<td align="right">-8.3%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">23,015,804,173</td>
<td align="right">27.0%</td>
<td align="right">21,165,740,961</td>
<td align="right">26.9%</td>
<td align="right">-8.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">5,070,975,381</td>
<td align="right">28.3%</td>
<td align="right">4,694,886,206</td>
<td align="right">27.4%</td>
<td align="right">-7.4%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">5,158,903,783</td>
<td align="right">28.8%</td>
<td align="right">4,783,342,146</td>
<td align="right">27.9%</td>
<td align="right">-7.3%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">5,756,789,486</td>
<td align="right"></td>
<td align="right">5,344,943,311</td>
<td align="right"></td>
<td align="right">-7.2%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">29,341,137,874</td>
<td align="right">29.6%</td>
<td align="right">27,246,804,943</td>
<td align="right">29.6%</td>
<td align="right">-7.1%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">5,664,724</td>
<td align="right"></td>
<td align="right">5,262,131</td>
<td align="right"></td>
<td align="right">-7.1%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">4,360,207,973</td>
<td align="right">5.1%</td>
<td align="right">4,053,120,813</td>
<td align="right">5.2%</td>
<td align="right">-7.0%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">22,904,995,681</td>
<td align="right">23.1%</td>
<td align="right">21,318,260,898</td>
<td align="right">23.1%</td>
<td align="right">-6.9%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">45,166,513,912</td>
<td align="right">45.6%</td>
<td align="right">42,132,062,448</td>
<td align="right">45.7%</td>
<td align="right">-6.7%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">198,384,210</td>
<td align="right"></td>
<td align="right">185,297,051</td>
<td align="right"></td>
<td align="right">-6.6%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">4,230,846</td>
<td align="right">2.1%</td>
<td align="right">3,957,305</td>
<td align="right">2.1%</td>
<td align="right">-6.5%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">34,984,013,150</td>
<td align="right">41.0%</td>
<td align="right">33,026,481,077</td>
<td align="right">42.0%</td>
<td align="right">-5.6%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">12,771,312,965</td>
<td align="right">71.2%</td>
<td align="right">12,339,591,024</td>
<td align="right">72.1%</td>
<td align="right">-3.4%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">12,772,919,475</td>
<td align="right"></td>
<td align="right">12,341,197,950</td>
<td align="right"></td>
<td align="right">-3.4%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">14,827,832</td>
<td align="right">0.1%</td>
<td align="right">15,112,981</td>
<td align="right">0.1%</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">73,100,570</td>
<td align="right">0.4%</td>
<td align="right">73,342,959</td>
<td align="right">0.4%</td>
<td align="right">0.3%</td>
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
<td align="right">420,111</td>
<td align="right">93,936,096</td>
<td align="right">6,682,493,430</td>
<td align="right">664,673,384</td>
<td align="right">417,515,209</td>
<td align="right">380,532</td>
<td align="right">20,663,667</td>
<td align="right">5,690,548,735</td>
<td align="right">631,063,977</td>
<td align="right">318,423,925</td>
</tr>
<tr>
<td align="right">2</td>
<td align="right">3,068</td>
<td align="right">2,160,060</td>
<td align="right">1,748,534,984</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">3,068</td>
<td align="right">2,160,060</td>
<td align="right">1,748,686,124</td>
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
func modification
<details>
<summary>ⓘ</summary>

Modifying a function, e.g. `func.__defaults__ = ...`, etc.
</details>
</td>
<td align="right">11,109</td>
<td align="right">10,869</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">
set class
<details>
<summary>ⓘ</summary>

Setting an object's class, `obj.__class__ = ...`
</details>
</td>
<td align="right">22,239</td>
<td align="right">22,239</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
set bases
<details>
<summary>ⓘ</summary>

Setting the bases of a class, `cls.__bases__ = ...`
</details>
</td>
<td align="right">714</td>
<td align="right">714</td>
<td align="right">0.0%</td>
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
watched dict modification
<details>
<summary>ⓘ</summary>

A watched dict has been modified
</details>
</td>
<td align="right">0</td>
<td align="right">504</td>
<td align="right">504 / 0 !!</td>
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
<td align="right">504</td>
<td align="right">504 / 0 !!</td>
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
<td align="right">2,529</td>
<td align="right">2,509</td>
<td align="right">-0.8%</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2025-11-17
