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
<td align="right">56,413,889</td>
<td align="right">210,987</td>
<td align="right">-99.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">25,480,977</td>
<td align="right">3,954,315</td>
<td align="right">-84.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">26,855,616</td>
<td align="right">4,440,519</td>
<td align="right">-83.5%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">22,446,661</td>
<td align="right">4,673,127</td>
<td align="right">-79.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">29,272,530</td>
<td align="right">7,848,489</td>
<td align="right">-73.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">1,228,038</td>
<td align="right">339,910</td>
<td align="right">-72.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">40,847,322</td>
<td align="right">14,831,860</td>
<td align="right">-63.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">34,943,242</td>
<td align="right">13,463,404</td>
<td align="right">-61.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">2,548,980</td>
<td align="right">1,027,593</td>
<td align="right">-59.7%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">1,196,559</td>
<td align="right">486,801</td>
<td align="right">-59.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">1,489,719</td>
<td align="right">678,090</td>
<td align="right">-54.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">3,509,331</td>
<td align="right">1,984,853</td>
<td align="right">-43.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">50,106,133</td>
<td align="right">28,659,057</td>
<td align="right">-42.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">2,160,648</td>
<td align="right">1,319,957</td>
<td align="right">-38.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">6,089,205</td>
<td align="right">3,793,345</td>
<td align="right">-37.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">5,443,723</td>
<td align="right">3,425,722</td>
<td align="right">-37.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">4,902,219</td>
<td align="right">3,131,663</td>
<td align="right">-36.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">6,788,292</td>
<td align="right">4,407,408</td>
<td align="right">-35.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">16,475,403</td>
<td align="right">10,729,207</td>
<td align="right">-34.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">8,523,541</td>
<td align="right">5,750,524</td>
<td align="right">-32.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">9,086,934</td>
<td align="right">6,142,175</td>
<td align="right">-32.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">4,742,819</td>
<td align="right">3,216,131</td>
<td align="right">-32.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">3,964,989</td>
<td align="right">2,787,061</td>
<td align="right">-29.7%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">7,827,664</td>
<td align="right">5,505,365</td>
<td align="right">-29.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">7,284,743</td>
<td align="right">5,327,352</td>
<td align="right">-26.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">87,482,041</td>
<td align="right">64,010,891</td>
<td align="right">-26.8%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">15,922,248</td>
<td align="right">11,754,349</td>
<td align="right">-26.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">1,630,629</td>
<td align="right">1,210,552</td>
<td align="right">-25.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">12,984,069</td>
<td align="right">9,837,114</td>
<td align="right">-24.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">429,801,264</td>
<td align="right">326,064,873</td>
<td align="right">-24.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">87,544,562</td>
<td align="right">68,642,164</td>
<td align="right">-21.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">973,476</td>
<td align="right">769,734</td>
<td align="right">-20.9%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">4,656,990</td>
<td align="right">3,698,125</td>
<td align="right">-20.6%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">20,475,983</td>
<td align="right">16,476,177</td>
<td align="right">-19.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">4,699,269</td>
<td align="right">3,802,539</td>
<td align="right">-19.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">66,055,047</td>
<td align="right">53,580,357</td>
<td align="right">-18.9%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">8,934,471</td>
<td align="right">7,292,538</td>
<td align="right">-18.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">10,082,728</td>
<td align="right">8,344,626</td>
<td align="right">-17.2%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">2,328,486</td>
<td align="right">1,928,440</td>
<td align="right">-17.2%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">34,423,340</td>
<td align="right">28,891,076</td>
<td align="right">-16.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">15,113,545</td>
<td align="right">12,837,717</td>
<td align="right">-15.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">71,959,100</td>
<td align="right">61,393,593</td>
<td align="right">-14.7%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">13,432,776</td>
<td align="right">11,529,281</td>
<td align="right">-14.2%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">6,083,430</td>
<td align="right">5,230,814</td>
<td align="right">-14.0%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">8,883,273</td>
<td align="right">7,653,247</td>
<td align="right">-13.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">101,372,338</td>
<td align="right">87,634,515</td>
<td align="right">-13.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">67,618,564</td>
<td align="right">58,667,345</td>
<td align="right">-13.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,500,815</td>
<td align="right">12,773,917</td>
<td align="right">-11.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">868,161</td>
<td align="right">765,807</td>
<td align="right">-11.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">31,685,113</td>
<td align="right">27,976,280</td>
<td align="right">-11.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">50,714,771</td>
<td align="right">44,815,694</td>
<td align="right">-11.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">13,078,080</td>
<td align="right">11,581,702</td>
<td align="right">-11.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">42,264,111</td>
<td align="right">38,013,207</td>
<td align="right">-10.1%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">20,635,163</td>
<td align="right">18,592,514</td>
<td align="right">-9.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">99,370,594</td>
<td align="right">89,723,809</td>
<td align="right">-9.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">701,337</td>
<td align="right">633,276</td>
<td align="right">-9.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">24,979,998</td>
<td align="right">22,624,924</td>
<td align="right">-9.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">2,228,940</td>
<td align="right">2,026,707</td>
<td align="right">-9.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">111,855,056</td>
<td align="right">102,131,121</td>
<td align="right">-8.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">3,380,979</td>
<td align="right">3,101,019</td>
<td align="right">-8.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">3,077,655</td>
<td align="right">2,848,138</td>
<td align="right">-7.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">70,310,440</td>
<td align="right">65,481,093</td>
<td align="right">-6.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">28,235,991</td>
<td align="right">26,305,085</td>
<td align="right">-6.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">9,206,399</td>
<td align="right">8,581,205</td>
<td align="right">-6.8%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">6,357,620</td>
<td align="right">5,956,463</td>
<td align="right">-6.3%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">53,858,085</td>
<td align="right">50,528,688</td>
<td align="right">-6.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">7,426,524</td>
<td align="right">7,048,174</td>
<td align="right">-5.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">6,754,354</td>
<td align="right">6,465,635</td>
<td align="right">-4.3%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">4,038,930</td>
<td align="right">3,881,997</td>
<td align="right">-3.9%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">774,081</td>
<td align="right">746,382</td>
<td align="right">-3.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">32,765,964</td>
<td align="right">31,624,268</td>
<td align="right">-3.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">15,187,363</td>
<td align="right">14,703,002</td>
<td align="right">-3.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">4,429,381</td>
<td align="right">4,288,315</td>
<td align="right">-3.2%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">2,293,579</td>
<td align="right">2,229,622</td>
<td align="right">-2.8%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">3,886,846</td>
<td align="right">3,779,898</td>
<td align="right">-2.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">2,934,456</td>
<td align="right">2,857,197</td>
<td align="right">-2.6%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">66,570</td>
<td align="right">68,182</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">102,159,138</td>
<td align="right">99,897,279</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">4,214,973</td>
<td align="right">4,125,104</td>
<td align="right">-2.1%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">1,235,027</td>
<td align="right">1,211,044</td>
<td align="right">-1.9%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">1,239,903</td>
<td align="right">1,215,920</td>
<td align="right">-1.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">7,564,870</td>
<td align="right">7,423,321</td>
<td align="right">-1.9%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">6,072,906</td>
<td align="right">5,961,900</td>
<td align="right">-1.8%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">25,438,098</td>
<td align="right">24,978,461</td>
<td align="right">-1.8%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">1,431,213</td>
<td align="right">1,407,702</td>
<td align="right">-1.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">32,181,077</td>
<td align="right">31,654,800</td>
<td align="right">-1.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">2,646,819</td>
<td align="right">2,613,266</td>
<td align="right">-1.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">16,464,565</td>
<td align="right">16,262,556</td>
<td align="right">-1.2%</td>
</tr>
<tr>
<td align="left">GET_YIELD_FROM_ITER</td>
<td align="right">8,629,299</td>
<td align="right">8,536,008</td>
<td align="right">-1.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">4,130,026</td>
<td align="right">4,093,805</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,143,933</td>
<td align="right">1,134,164</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">5,570,250</td>
<td align="right">5,523,652</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">33,083,130</td>
<td align="right">32,811,347</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">4,673,025</td>
<td align="right">4,637,007</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">3,698,394</td>
<td align="right">3,670,262</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">6,861,963</td>
<td align="right">6,821,590</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">8,529,633</td>
<td align="right">8,479,611</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">2,438,289</td>
<td align="right">2,425,794</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">243,852</td>
<td align="right">242,673</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">12,663,231</td>
<td align="right">12,605,074</td>
<td align="right">-0.5%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">3,340,260</td>
<td align="right">3,327,765</td>
<td align="right">-0.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">466,410</td>
<td align="right">465,027</td>
<td align="right">-0.3%</td>
</tr>
<tr>
<td align="left">CALL_KW_BOUND_METHOD</td>
<td align="right">734,788</td>
<td align="right">733,740</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">78,225</td>
<td align="right">78,141</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">165,588</td>
<td align="right">165,452</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">141,078</td>
<td align="right">140,994</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">1,996,449</td>
<td align="right">1,995,385</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">8,498,952</td>
<td align="right">8,494,479</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">2,331,462</td>
<td align="right">2,330,268</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LOAD_COMMON_CONSTANT</td>
<td align="right">1,696,107</td>
<td align="right">1,695,609</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">6,829,158</td>
<td align="right">6,830,691</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">5,645,010</td>
<td align="right">5,646,110</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_ATTR</td>
<td align="right">288,624</td>
<td align="right">288,606</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">5,476,800</td>
<td align="right">5,476,716</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">BUILD_SET</td>
<td align="right">453,600</td>
<td align="right">453,594</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">1,289,442</td>
<td align="right">1,289,430</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">27,569,408</td>
<td align="right">27,569,597</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">2,572,143</td>
<td align="right">2,572,131</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">1,351,980</td>
<td align="right">1,351,974</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">2,847,138</td>
<td align="right">2,847,132</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">3,381,563</td>
<td align="right">3,381,563</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">1,486,086</td>
<td align="right">1,486,086</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">1,333,017</td>
<td align="right">1,333,017</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">1,326,633</td>
<td align="right">1,326,633</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">1,285,746</td>
<td align="right">1,285,746</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">1,201,158</td>
<td align="right">1,201,158</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">1,201,158</td>
<td align="right">1,201,158</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">905,289</td>
<td align="right">905,289</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">534,261</td>
<td align="right">534,261</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">533,967</td>
<td align="right">533,967</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">507,759</td>
<td align="right">507,759</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">493,521</td>
<td align="right">493,521</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">456,540</td>
<td align="right">456,540</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">454,062</td>
<td align="right">454,062</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_SLICE</td>
<td align="right">447,552</td>
<td align="right">447,552</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">444,654</td>
<td align="right">444,654</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">424,536</td>
<td align="right">424,536</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">334,299</td>
<td align="right">334,299</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">328,272</td>
<td align="right">328,272</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_EXTEND</td>
<td align="right">256,725</td>
<td align="right">256,725</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">248,073</td>
<td align="right">248,073</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">244,167</td>
<td align="right">244,167</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">212,772</td>
<td align="right">212,772</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">204,477</td>
<td align="right">204,477</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">197,694</td>
<td align="right">197,694</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">154,497</td>
<td align="right">154,497</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">128,940</td>
<td align="right">128,940</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">128,352</td>
<td align="right">128,352</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CLEANUP_THROW</td>
<td align="right">120,309</td>
<td align="right">120,309</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">111,384</td>
<td align="right">111,384</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">82,068</td>
<td align="right">82,068</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">81,333</td>
<td align="right">81,333</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_GETATTRIBUTE_OVERRIDDEN</td>
<td align="right">73,668</td>
<td align="right">73,668</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SET_UPDATE</td>
<td align="right">72,135</td>
<td align="right">72,135</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">61,278</td>
<td align="right">61,278</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">56,994</td>
<td align="right">56,994</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SET_ADD</td>
<td align="right">52,311</td>
<td align="right">52,311</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">30,198</td>
<td align="right">30,198</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">28,056</td>
<td align="right">28,056</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">21,441</td>
<td align="right">21,441</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">20,706</td>
<td align="right">20,706</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">20,622</td>
<td align="right">20,622</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_WITH_HINT</td>
<td align="right">18,207</td>
<td align="right">18,207</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">14,322</td>
<td align="right">14,322</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">13,902</td>
<td align="right">13,902</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">10,479</td>
<td align="right">10,479</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">7,707</td>
<td align="right">7,707</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">7,014</td>
<td align="right">7,014</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">5,544</td>
<td align="right">5,544</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">4,284</td>
<td align="right">4,284</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">4,074</td>
<td align="right">4,074</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">3,843</td>
<td align="right">3,843</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DICT_UPDATE</td>
<td align="right">1,596</td>
<td align="right">1,596</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SETUP_ANNOTATIONS</td>
<td align="right">1,239</td>
<td align="right">1,239</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">609</td>
<td align="right">609</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">315</td>
<td align="right">315</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_NAME</td>
<td align="right">294</td>
<td align="right">294</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FORMAT_WITH_SPEC</td>
<td align="right">189</td>
<td align="right">189</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">84</td>
<td align="right">84</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">16,812,787</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">16,716,408</td>
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
<td align="right">190,197</td>
<td align="right">0.5%</td>
<td align="right">61,299</td>
<td align="right">0.2%</td>
<td align="right">-67.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">5,408,527</td>
<td align="right">15.1%</td>
<td align="right">3,390,795</td>
<td align="right">13.5%</td>
<td align="right">-37.3%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">30,237,340</td>
<td align="right">84.3%</td>
<td align="right">21,603,393</td>
<td align="right">86.1%</td>
<td align="right">-28.6%</td>
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
<td align="right">16,926</td>
<td align="right">43.7%</td>
<td align="right">14,532</td>
<td align="right">40.3%</td>
<td align="right">-14.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">21,798</td>
<td align="right">56.3%</td>
<td align="right">21,571</td>
<td align="right">59.7%</td>
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
<td align="left">subscr defaultdict</td>
<td align="right">2,961</td>
<td align="right">13.6%</td>
<td align="right">3,756</td>
<td align="right">17.4%</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">6,048</td>
<td align="right">27.7%</td>
<td align="right">4,427</td>
<td align="right">20.5%</td>
<td align="right">-26.8%</td>
</tr>
<tr>
<td align="left">subscr</td>
<td align="right">2,310</td>
<td align="right">10.6%</td>
<td align="right">2,720</td>
<td align="right">12.6%</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">subscr string slice</td>
<td align="right">2,310</td>
<td align="right">10.6%</td>
<td align="right">2,457</td>
<td align="right">11.4%</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">882</td>
<td align="right">4.0%</td>
<td align="right">924</td>
<td align="right">4.3%</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">3,675</td>
<td align="right">16.9%</td>
<td align="right">3,675</td>
<td align="right">17.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">756</td>
<td align="right">3.5%</td>
<td align="right">756</td>
<td align="right">3.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">546</td>
<td align="right">2.5%</td>
<td align="right">546</td>
<td align="right">2.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">and other</td>
<td align="right">336</td>
<td align="right">1.5%</td>
<td align="right">336</td>
<td align="right">1.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">xor</td>
<td align="right">315</td>
<td align="right">1.4%</td>
<td align="right">315</td>
<td align="right">1.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">lshift</td>
<td align="right">210</td>
<td align="right">1.0%</td>
<td align="right">210</td>
<td align="right">1.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">true divide different types</td>
<td align="right">210</td>
<td align="right">1.0%</td>
<td align="right">210</td>
<td align="right">1.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">and int</td>
<td align="right">189</td>
<td align="right">0.9%</td>
<td align="right">189</td>
<td align="right">0.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr tuple slice</td>
<td align="right">147</td>
<td align="right">0.7%</td>
<td align="right">147</td>
<td align="right">0.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">126</td>
<td align="right">0.6%</td>
<td align="right">126</td>
<td align="right">0.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr ordereddict</td>
<td align="right">126</td>
<td align="right">0.6%</td>
<td align="right">126</td>
<td align="right">0.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">84</td>
<td align="right">0.4%</td>
<td align="right">84</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subtract other</td>
<td align="right">84</td>
<td align="right">0.4%</td>
<td align="right">84</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr bytes</td>
<td align="right">84</td>
<td align="right">0.4%</td>
<td align="right">84</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">rshift</td>
<td align="right">63</td>
<td align="right">0.3%</td>
<td align="right">63</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">xor int</td>
<td align="right">63</td>
<td align="right">0.3%</td>
<td align="right">63</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr other slice</td>
<td align="right">63</td>
<td align="right">0.3%</td>
<td align="right">63</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">and different types</td>
<td align="right">42</td>
<td align="right">0.2%</td>
<td align="right">42</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr range</td>
<td align="right">42</td>
<td align="right">0.2%</td>
<td align="right">42</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">code complex parameters</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">multiply other</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">power</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">true divide other</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">or different types</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">subscr enumdict</td>
<td align="right">21</td>
<td align="right">0.1%</td>
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
<td align="right">774,081</td>
<td align="right">100.0%</td>
<td align="right">746,382</td>
<td align="right">100.0%</td>
<td align="right">-3.6%</td>
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
<td align="right">14,472,260</td>
<td align="right">11.2%</td>
<td align="right">11,623,443</td>
<td align="right">10.6%</td>
<td align="right">-19.7%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">14,341,467</td>
<td align="right">11.1%</td>
<td align="right">11,545,455</td>
<td align="right">10.6%</td>
<td align="right">-19.5%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">114,078,054</td>
<td align="right">88.6%</td>
<td align="right">97,514,496</td>
<td align="right">89.2%</td>
<td align="right">-14.5%</td>
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
<td align="right">374,960</td>
<td align="right">100.0%</td>
<td align="right">322,155</td>
<td align="right">100.0%</td>
<td align="right">-14.1%</td>
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
<td align="left">init not simple</td>
<td align="right">483</td>
<td align="right">483 / 0 !!</td>
<td align="right">483</td>
<td align="right">483 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">init not python</td>
<td align="right">21</td>
<td align="right">21 / 0 !!</td>
<td align="right">21</td>
<td align="right">21 / 0 !!</td>
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
<td align="right">639,051</td>
<td align="right">96.7%</td>
<td align="right">638,114</td>
<td align="right">96.6%</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">639,723</td>
<td align="right">96.8%</td>
<td align="right">638,844</td>
<td align="right">96.8%</td>
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
<td align="right">22,113</td>
<td align="right">100.0%</td>
<td align="right">22,171</td>
<td align="right">100.0%</td>
<td align="right">0.3%</td>
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
<td align="right">4,879,266</td>
<td align="right">11.6%</td>
<td align="right">3,107,542</td>
<td align="right">8.7%</td>
<td align="right">-36.3%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">37,299,237</td>
<td align="right">88.3%</td>
<td align="right">32,422,606</td>
<td align="right">91.1%</td>
<td align="right">-13.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">30,702</td>
<td align="right">0.1%</td>
<td align="right">31,668</td>
<td align="right">0.1%</td>
<td align="right">3.1%</td>
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
<td align="right">11,130</td>
<td align="right">47.3%</td>
<td align="right">12,298</td>
<td align="right">49.8%</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">12,390</td>
<td align="right">52.7%</td>
<td align="right">12,411</td>
<td align="right">50.2%</td>
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
<td align="left">list</td>
<td align="right">945</td>
<td align="right">8.5%</td>
<td align="right">1,310</td>
<td align="right">10.7%</td>
<td align="right">38.6%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">756</td>
<td align="right">6.8%</td>
<td align="right">986</td>
<td align="right">8.0%</td>
<td align="right">30.4%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">4,368</td>
<td align="right">39.2%</td>
<td align="right">4,919</td>
<td align="right">40.0%</td>
<td align="right">12.6%</td>
</tr>
<tr>
<td align="left">different types</td>
<td align="right">3,696</td>
<td align="right">33.2%</td>
<td align="right">3,718</td>
<td align="right">30.2%</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">420</td>
<td align="right">3.8%</td>
<td align="right">420</td>
<td align="right">3.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">378</td>
<td align="right">3.4%</td>
<td align="right">378</td>
<td align="right">3.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">bool</td>
<td align="right">210</td>
<td align="right">1.9%</td>
<td align="right">210</td>
<td align="right">1.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">168</td>
<td align="right">1.5%</td>
<td align="right">168</td>
<td align="right">1.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">147</td>
<td align="right">1.3%</td>
<td align="right">147</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">21</td>
<td align="right">0.2%</td>
<td align="right">21</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">float long</td>
<td align="right">21</td>
<td align="right">0.2%</td>
<td align="right">21</td>
<td align="right">0.2%</td>
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
<td align="right">4,719,734</td>
<td align="right">38.5%</td>
<td align="right">3,191,872</td>
<td align="right">30.7%</td>
<td align="right">-32.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">7,484,566</td>
<td align="right">61.1%</td>
<td align="right">7,168,385</td>
<td align="right">68.9%</td>
<td align="right">-4.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">26,439</td>
<td align="right">0.2%</td>
<td align="right">26,439</td>
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
<td align="left">Failure</td>
<td align="right">18,717</td>
<td align="right">79.4%</td>
<td align="right">19,891</td>
<td align="right">80.4%</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">4,851</td>
<td align="right">20.6%</td>
<td align="right">4,851</td>
<td align="right">19.6%</td>
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
<td align="right">4,263</td>
<td align="right">22.8%</td>
<td align="right">4,760</td>
<td align="right">23.9%</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">3,759</td>
<td align="right">20.1%</td>
<td align="right">3,969</td>
<td align="right">20.0%</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">8,238</td>
<td align="right">44.0%</td>
<td align="right">8,663</td>
<td align="right">43.6%</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">2,457</td>
<td align="right">13.1%</td>
<td align="right">2,499</td>
<td align="right">12.6%</td>
<td align="right">1.7%</td>
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
<td align="right">66,081,592</td>
<td align="right">90.4%</td>
<td align="right">31,544,935</td>
<td align="right">87.2%</td>
<td align="right">-52.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">6,750,492</td>
<td align="right">9.2%</td>
<td align="right">4,367,927</td>
<td align="right">12.1%</td>
<td align="right">-35.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">231,084</td>
<td align="right">0.3%</td>
<td align="right">231,683</td>
<td align="right">0.6%</td>
<td align="right">0.3%</td>
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
<td align="right">22,533</td>
<td align="right">53.5%</td>
<td align="right">24,214</td>
<td align="right">55.2%</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">19,593</td>
<td align="right">46.5%</td>
<td align="right">19,615</td>
<td align="right">44.8%</td>
<td align="right">0.1%</td>
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
<td align="right">4,893</td>
<td align="right">21.7%</td>
<td align="right">6,103</td>
<td align="right">25.2%</td>
<td align="right">24.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">651</td>
<td align="right">2.9%</td>
<td align="right">777</td>
<td align="right">3.2%</td>
<td align="right">19.4%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">4,998</td>
<td align="right">22.2%</td>
<td align="right">5,334</td>
<td align="right">22.0%</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">6,174</td>
<td align="right">27.4%</td>
<td align="right">6,183</td>
<td align="right">25.5%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">itertools</td>
<td align="right">1,995</td>
<td align="right">8.9%</td>
<td align="right">1,995</td>
<td align="right">8.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">zip</td>
<td align="right">1,176</td>
<td align="right">5.2%</td>
<td align="right">1,176</td>
<td align="right">4.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">924</td>
<td align="right">4.1%</td>
<td align="right">924</td>
<td align="right">3.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">630</td>
<td align="right">2.8%</td>
<td align="right">630</td>
<td align="right">2.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">546</td>
<td align="right">2.4%</td>
<td align="right">546</td>
<td align="right">2.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">231</td>
<td align="right">1.0%</td>
<td align="right">231</td>
<td align="right">1.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">map</td>
<td align="right">189</td>
<td align="right">0.8%</td>
<td align="right">189</td>
<td align="right">0.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">ascii string</td>
<td align="right">105</td>
<td align="right">0.5%</td>
<td align="right">105</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">seq iter</td>
<td align="right">21</td>
<td align="right">0.1%</td>
<td align="right">21</td>
<td align="right">0.1%</td>
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
<td align="right">9,183,739</td>
<td align="right">9,183,739 / 0 !!</td>
<td align="right">9,183,739</td>
<td align="right">9,183,739 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">generator</td>
<td align="right">5,557,377</td>
<td align="right">5,557,377 / 0 !!</td>
<td align="right">5,557,377</td>
<td align="right">5,557,377 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">3,672,856</td>
<td align="right">3,672,856 / 0 !!</td>
<td align="right">3,672,856</td>
<td align="right">3,672,856 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">859,068</td>
<td align="right">859,068 / 0 !!</td>
<td align="right">859,068</td>
<td align="right">859,068 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">730,002</td>
<td align="right">730,002 / 0 !!</td>
<td align="right">730,002</td>
<td align="right">730,002 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">363,909</td>
<td align="right">363,909 / 0 !!</td>
<td align="right">363,909</td>
<td align="right">363,909 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">self</td>
<td align="right">247,716</td>
<td align="right">247,716 / 0 !!</td>
<td align="right">247,716</td>
<td align="right">247,716 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">13,734</td>
<td align="right">13,734 / 0 !!</td>
<td align="right">13,734</td>
<td align="right">13,734 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">6,699</td>
<td align="right">6,699 / 0 !!</td>
<td align="right">6,699</td>
<td align="right">6,699 / 0 !!</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">63</td>
<td align="right">63 / 0 !!</td>
<td align="right">63</td>
<td align="right">63 / 0 !!</td>
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
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">48,525,506</td>
<td align="right">19.7%</td>
<td align="right">43,885,723</td>
<td align="right">19.3%</td>
<td align="right">-9.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">165,019,773</td>
<td align="right">67.0%</td>
<td align="right">152,015,005</td>
<td align="right">66.8%</td>
<td align="right">-7.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">32,264,610</td>
<td align="right">13.1%</td>
<td align="right">31,123,556</td>
<td align="right">13.7%</td>
<td align="right">-3.5%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">345,807</td>
<td align="right">0.1%</td>
<td align="right">346,299</td>
<td align="right">0.2%</td>
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
<td align="right">1,035,657</td>
<td align="right">84.3%</td>
<td align="right">950,397</td>
<td align="right">83.1%</td>
<td align="right">-8.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">192,948</td>
<td align="right">15.7%</td>
<td align="right">192,647</td>
<td align="right">16.9%</td>
<td align="right">-0.2%</td>
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
<td align="left">overridden</td>
<td align="right">630</td>
<td align="right">0.3%</td>
<td align="right">707</td>
<td align="right">0.4%</td>
<td align="right">12.2%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">18,942</td>
<td align="right">9.8%</td>
<td align="right">20,971</td>
<td align="right">10.9%</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">15,519</td>
<td align="right">8.0%</td>
<td align="right">17,152</td>
<td align="right">8.9%</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">21,147</td>
<td align="right">11.0%</td>
<td align="right">22,911</td>
<td align="right">11.9%</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">1,764</td>
<td align="right">0.9%</td>
<td align="right">1,905</td>
<td align="right">1.0%</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">metaclass attribute</td>
<td align="right">4,557</td>
<td align="right">2.4%</td>
<td align="right">4,885</td>
<td align="right">2.5%</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">3,675</td>
<td align="right">1.9%</td>
<td align="right">3,931</td>
<td align="right">2.0%</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">non overriding descriptor</td>
<td align="right">1,869</td>
<td align="right">1.0%</td>
<td align="right">1,917</td>
<td align="right">1.0%</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">1,617</td>
<td align="right">0.8%</td>
<td align="right">1,617</td>
<td align="right">0.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">wrong number arguments</td>
<td align="right">1,092</td>
<td align="right">0.6%</td>
<td align="right">1,092</td>
<td align="right">0.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">840</td>
<td align="right">0.4%</td>
<td align="right">840</td>
<td align="right">0.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">567</td>
<td align="right">0.3%</td>
<td align="right">567</td>
<td align="right">0.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">expected error</td>
<td align="right">105</td>
<td align="right">0.1%</td>
<td align="right">105</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">not in dict</td>
<td align="right">42</td>
<td align="right">0.0%</td>
<td align="right">42</td>
<td align="right">0.0%</td>
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
<td align="right">133,630,162</td>
<td align="right">99.8%</td>
<td align="right">112,204,253</td>
<td align="right">99.8%</td>
<td align="right">-16.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">103,719</td>
<td align="right">0.1%</td>
<td align="right">103,719</td>
<td align="right">0.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">525</td>
<td align="right">0.0%</td>
<td align="right">525</td>
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
<td align="right">43,449</td>
<td align="right">0.0%</td>
<td align="right">43,449</td>
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
<td align="right">101,283</td>
<td align="right">100.0%</td>
<td align="right">101,283</td>
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
<td align="right">2,142</td>
<td align="right">0.1%</td>
<td align="right">2,142</td>
<td align="right">0.1%</td>
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
<td align="right">3,594,335</td>
<td align="right">99.9%</td>
<td align="right">3,594,335</td>
<td align="right">99.9%</td>
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
<td align="right">2,142</td>
<td align="right">100.0%</td>
<td align="right">2,142</td>
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
<td align="right">5,476,800</td>
<td align="right">44.5%</td>
<td align="right">5,476,716</td>
<td align="right">44.5%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">6,819,330</td>
<td align="right">55.4%</td>
<td align="right">6,819,330</td>
<td align="right">55.4%</td>
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
<td align="right">8,925</td>
<td align="right">90.8%</td>
<td align="right">10,458</td>
<td align="right">92.1%</td>
<td align="right">17.2%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">903</td>
<td align="right">9.2%</td>
<td align="right">903</td>
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
<td align="left">tuple</td>
<td align="right">2,121</td>
<td align="right">23.8%</td>
<td align="right">2,751</td>
<td align="right">26.3%</td>
<td align="right">29.7%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">6,594</td>
<td align="right">73.9%</td>
<td align="right">7,497</td>
<td align="right">71.7%</td>
<td align="right">13.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">210</td>
<td align="right">2.4%</td>
<td align="right">210</td>
<td align="right">2.0%</td>
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
<td align="right">27,877,839</td>
<td align="right">61.5%</td>
<td align="right">27,564,602</td>
<td align="right">61.3%</td>
<td align="right">-1.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">3,668,154</td>
<td align="right">8.1%</td>
<td align="right">3,639,811</td>
<td align="right">8.1%</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">13,753,131</td>
<td align="right">30.3%</td>
<td align="right">13,744,563</td>
<td align="right">30.6%</td>
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
<td align="left">Failure</td>
<td align="right">16,611</td>
<td align="right">5.7%</td>
<td align="right">16,822</td>
<td align="right">5.8%</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">272,706</td>
<td align="right">94.3%</td>
<td align="right">272,559</td>
<td align="right">94.2%</td>
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
<td align="left">property</td>
<td align="right">630</td>
<td align="right">3.8%</td>
<td align="right">735</td>
<td align="right">4.4%</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">116,676</td>
<td align="right">702.4%</td>
<td align="right">110,076</td>
<td align="right">654.4%</td>
<td align="right">-5.7%</td>
</tr>
<tr>
<td align="left">split dict</td>
<td align="right">1,911</td>
<td align="right">11.5%</td>
<td align="right">2,017</td>
<td align="right">12.0%</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">7,539</td>
<td align="right">45.4%</td>
<td align="right">7,539</td>
<td align="right">44.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">3,360</td>
<td align="right">20.2%</td>
<td align="right">3,360</td>
<td align="right">20.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">1,092</td>
<td align="right">6.6%</td>
<td align="right">1,092</td>
<td align="right">6.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">735</td>
<td align="right">4.4%</td>
<td align="right">735</td>
<td align="right">4.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">not in dict</td>
<td align="right">441</td>
<td align="right">2.7%</td>
<td align="right">441</td>
<td align="right">2.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">210</td>
<td align="right">1.3%</td>
<td align="right">210</td>
<td align="right">1.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">no dict</td>
<td align="right">168</td>
<td align="right">1.0%</td>
<td align="right">168</td>
<td align="right">1.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">42</td>
<td align="right">0.3%</td>
<td align="right">42</td>
<td align="right">0.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">42</td>
<td align="right">0.3%</td>
<td align="right">42</td>
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
<td align="right">609</td>
<td align="right">100.0%</td>
<td align="right">609</td>
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
<td align="right">3,634,848</td>
<td align="right">93.7%</td>
<td align="right">2,912,595</td>
<td align="right">92.3%</td>
<td align="right">-19.9%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">239,841</td>
<td align="right">6.2%</td>
<td align="right">238,619</td>
<td align="right">7.6%</td>
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
<td align="left">Failure</td>
<td align="right">1,869</td>
<td align="right">46.6%</td>
<td align="right">1,912</td>
<td align="right">47.2%</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">2,142</td>
<td align="right">53.4%</td>
<td align="right">2,142</td>
<td align="right">52.8%</td>
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
<td align="right">420</td>
<td align="right">22.5%</td>
<td align="right">462</td>
<td align="right">24.2%</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">147</td>
<td align="right">7.9%</td>
<td align="right">148</td>
<td align="right">7.7%</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">dict subclass no override</td>
<td align="right">819</td>
<td align="right">43.8%</td>
<td align="right">819</td>
<td align="right">42.8%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">252</td>
<td align="right">13.5%</td>
<td align="right">252</td>
<td align="right">13.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">py simple</td>
<td align="right">126</td>
<td align="right">6.7%</td>
<td align="right">126</td>
<td align="right">6.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">105</td>
<td align="right">5.6%</td>
<td align="right">105</td>
<td align="right">5.5%</td>
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
<td align="right">97,760,202</td>
<td align="right">91.0%</td>
<td align="right">73,142,310</td>
<td align="right">90.6%</td>
<td align="right">-25.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">8,484,462</td>
<td align="right">7.9%</td>
<td align="right">6,412,777</td>
<td align="right">7.9%</td>
<td align="right">-24.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,081,878</td>
<td align="right">1.0%</td>
<td align="right">1,071,493</td>
<td align="right">1.3%</td>
<td align="right">-1.0%</td>
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
<td align="right">208,614</td>
<td align="right">94.5%</td>
<td align="right">170,166</td>
<td align="right">93.0%</td>
<td align="right">-18.4%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">12,201</td>
<td align="right">5.5%</td>
<td align="right">12,817</td>
<td align="right">7.0%</td>
<td align="right">5.0%</td>
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
<td align="left">set</td>
<td align="right">6,090</td>
<td align="right">49.9%</td>
<td align="right">6,610</td>
<td align="right">51.6%</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">1,008</td>
<td align="right">8.3%</td>
<td align="right">1,066</td>
<td align="right">8.3%</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">number</td>
<td align="right">756</td>
<td align="right">6.2%</td>
<td align="right">794</td>
<td align="right">6.2%</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">1,680</td>
<td align="right">13.8%</td>
<td align="right">1,680</td>
<td align="right">13.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">1,176</td>
<td align="right">9.6%</td>
<td align="right">1,176</td>
<td align="right">9.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">1,113</td>
<td align="right">9.1%</td>
<td align="right">1,113</td>
<td align="right">8.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">210</td>
<td align="right">1.7%</td>
<td align="right">210</td>
<td align="right">1.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">168</td>
<td align="right">1.4%</td>
<td align="right">168</td>
<td align="right">1.3%</td>
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
<td align="right">25,617,036</td>
<td align="right">95.4%</td>
<td align="right">4,090,374</td>
<td align="right">92.3%</td>
<td align="right">-84.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,222,641</td>
<td align="right">4.6%</td>
<td align="right">334,091</td>
<td align="right">7.5%</td>
<td align="right">-72.7%</td>
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
<td align="right">966</td>
<td align="right">17.9%</td>
<td align="right">1,388</td>
<td align="right">23.9%</td>
<td align="right">43.7%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">4,431</td>
<td align="right">82.1%</td>
<td align="right">4,431</td>
<td align="right">76.1%</td>
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
<td align="right">882</td>
<td align="right">91.3%</td>
<td align="right">1,304</td>
<td align="right">93.9%</td>
<td align="right">47.8%</td>
</tr>
<tr>
<td align="left">iterator</td>
<td align="right">84</td>
<td align="right">8.7%</td>
<td align="right">84</td>
<td align="right">6.1%</td>
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
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">914,744,280</td>
<td align="right">36.5%</td>
<td align="right">706,322,042</td>
<td align="right">35.0%</td>
<td align="right">-22.8%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">1,415,007,081</td>
<td align="right">56.5%</td>
<td align="right">1,155,472,817</td>
<td align="right">57.3%</td>
<td align="right">-18.3%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">89,670,614</td>
<td align="right">3.6%</td>
<td align="right">77,836,766</td>
<td align="right">3.9%</td>
<td align="right">-13.2%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">86,400,440</td>
<td align="right">3.4%</td>
<td align="right">76,703,071</td>
<td align="right">3.8%</td>
<td align="right">-11.2%</td>
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
<td align="left">BINARY_OP</td>
<td align="right">5,408,527</td>
<td align="right">6.5%</td>
<td align="right">3,390,795</td>
<td align="right">4.8%</td>
<td align="right">-37.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">4,879,266</td>
<td align="right">5.9%</td>
<td align="right">3,107,542</td>
<td align="right">4.4%</td>
<td align="right">-36.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">6,750,492</td>
<td align="right">8.1%</td>
<td align="right">4,367,927</td>
<td align="right">6.2%</td>
<td align="right">-35.3%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">4,719,734</td>
<td align="right">5.7%</td>
<td align="right">3,191,872</td>
<td align="right">4.5%</td>
<td align="right">-32.4%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">14,341,467</td>
<td align="right">17.3%</td>
<td align="right">11,545,455</td>
<td align="right">16.4%</td>
<td align="right">-19.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">32,264,610</td>
<td align="right">38.9%</td>
<td align="right">31,123,556</td>
<td align="right">44.3%</td>
<td align="right">-3.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,081,878</td>
<td align="right">1.3%</td>
<td align="right">1,071,493</td>
<td align="right">1.5%</td>
<td align="right">-1.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">3,668,154</td>
<td align="right">4.4%</td>
<td align="right">3,639,811</td>
<td align="right">5.2%</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">6,819,330</td>
<td align="right">8.2%</td>
<td align="right">6,819,330</td>
<td align="right">9.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">1,222,641</td>
<td align="right">1.5%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">746,382</td>
<td align="right">1.1%</td>
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
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">3,697,680</td>
<td align="right">4.3%</td>
<td align="right">2,744,843</td>
<td align="right">3.6%</td>
<td align="right">-25.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">7,126,130</td>
<td align="right">8.2%</td>
<td align="right">5,656,260</td>
<td align="right">7.4%</td>
<td align="right">-20.6%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">2,315,611</td>
<td align="right">2.7%</td>
<td align="right">1,874,509</td>
<td align="right">2.4%</td>
<td align="right">-19.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">10,453,443</td>
<td align="right">12.1%</td>
<td align="right">8,591,037</td>
<td align="right">11.2%</td>
<td align="right">-17.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">10,606,215</td>
<td align="right">12.3%</td>
<td align="right">8,990,406</td>
<td align="right">11.7%</td>
<td align="right">-15.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">5,289,018</td>
<td align="right">6.1%</td>
<td align="right">5,082,192</td>
<td align="right">6.6%</td>
<td align="right">-3.9%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">8,668,124</td>
<td align="right">10.0%</td>
<td align="right">8,418,507</td>
<td align="right">11.0%</td>
<td align="right">-2.9%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">13,753,089</td>
<td align="right">15.9%</td>
<td align="right">13,744,521</td>
<td align="right">17.9%</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">18,369,498</td>
<td align="right">21.3%</td>
<td align="right">18,367,835</td>
<td align="right">23.9%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">2,349,585</td>
<td align="right">2.7%</td>
<td align="right"></td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">593,629</td>
<td align="right">0.8%</td>
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
<td align="right">2,980,446</td>
<td align="right">2.4%</td>
<td align="right">2,980,656</td>
<td align="right">2.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">565,323</td>
<td align="right">0.5%</td>
<td align="right">565,302</td>
<td align="right">0.5%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">27,936,971</td>
<td align="right">22.4%</td>
<td align="right">27,937,160</td>
<td align="right">22.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">27,936,971</td>
<td align="right">22.4%</td>
<td align="right">27,937,160</td>
<td align="right">22.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">96,933,885</td>
<td align="right">77.6%</td>
<td align="right">96,933,654</td>
<td align="right">77.6%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">24,942,329</td>
<td align="right">20.0%</td>
<td align="right">24,942,308</td>
<td align="right">20.0%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">24,956,525</td>
<td align="right">20.0%</td>
<td align="right">24,956,504</td>
<td align="right">20.0%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">101,201,899</td>
<td align="right">81.0%</td>
<td align="right">101,201,857</td>
<td align="right">81.0%</td>
<td align="right">-0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">3,717</td>
<td align="right">0.0%</td>
<td align="right">3,717</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">10,479</td>
<td align="right">0.0%</td>
<td align="right">10,479</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">684,747</td>
<td align="right">0.5%</td>
<td align="right">684,747</td>
<td align="right">0.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">923,685</td>
<td align="right">0.7%</td>
<td align="right">923,685</td>
<td align="right">0.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">1,449</td>
<td align="right">0.0%</td>
<td align="right">1,449</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">1,685,313</td>
<td align="right">1.3%</td>
<td align="right">1,685,313</td>
<td align="right">1.3%</td>
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
<td align="left">Method cache misses</td>
<td align="right">3,499,007</td>
<td align="right"></td>
<td align="right">3,145,447</td>
<td align="right"></td>
<td align="right">-10.1%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">4,001,091</td>
<td align="right"></td>
<td align="right">3,642,161</td>
<td align="right"></td>
<td align="right">-9.0%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">66,846,139</td>
<td align="right">42.6%</td>
<td align="right">69,002,720</td>
<td align="right">43.4%</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">66,884,781</td>
<td align="right"></td>
<td align="right">69,041,362</td>
<td align="right"></td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">585,547,880</td>
<td align="right">38.7%</td>
<td align="right">599,859,562</td>
<td align="right">39.5%</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">727,516,514</td>
<td align="right">48.3%</td>
<td align="right">740,414,170</td>
<td align="right">48.8%</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">113,207,240</td>
<td align="right"></td>
<td align="right">111,782,638</td>
<td align="right"></td>
<td align="right">-1.3%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">55,260,139</td>
<td align="right"></td>
<td align="right">54,719,613</td>
<td align="right"></td>
<td align="right">-1.0%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">419,057,260</td>
<td align="right">27.7%</td>
<td align="right">415,115,600</td>
<td align="right">27.3%</td>
<td align="right">-0.9%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">337,400,037</td>
<td align="right">22.4%</td>
<td align="right">334,572,478</td>
<td align="right">22.0%</td>
<td align="right">-0.8%</td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">527,330</td>
<td align="right"></td>
<td align="right">523,745</td>
<td align="right"></td>
<td align="right">-0.7%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">437,043,907</td>
<td align="right">28.9%</td>
<td align="right">434,209,725</td>
<td align="right">28.6%</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">36,410,113</td>
<td align="right">2.4%</td>
<td align="right">36,175,483</td>
<td align="right">2.4%</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">490,581</td>
<td align="right">0.3%</td>
<td align="right">492,639</td>
<td align="right">0.3%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">405,636,100</td>
<td align="right">26.9%</td>
<td align="right">406,368,919</td>
<td align="right">26.8%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">228,648</td>
<td align="right">0.1%</td>
<td align="right">229,054</td>
<td align="right">0.1%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">80,600,446</td>
<td align="right"></td>
<td align="right">80,608,178</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">89,929,384</td>
<td align="right">57.4%</td>
<td align="right">89,935,920</td>
<td align="right">56.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">89,210,155</td>
<td align="right">56.9%</td>
<td align="right">89,214,227</td>
<td align="right">56.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">71,154,136</td>
<td align="right">4.7%</td>
<td align="right">71,154,252</td>
<td align="right">4.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">3,998,650</td>
<td align="right"></td>
<td align="right">3,998,650</td>
<td align="right"></td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">367,500</td>
<td align="right">9.2%</td>
<td align="right">367,500</td>
<td align="right">9.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Materialize dict (new key)</td>
<td align="right">38,010</td>
<td align="right">1.0%</td>
<td align="right">38,010</td>
<td align="right">1.0%</td>
<td align="right">0.0%</td>
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
<td align="right">5,208</td>
<td align="right">395,472</td>
<td align="right">125,936,251</td>
<td align="right">11,049,395</td>
<td align="right">7,852,176</td>
<td align="right">5,208</td>
<td align="right">395,472</td>
<td align="right">126,062,414</td>
<td align="right">11,031,193</td>
<td align="right">7,873,301</td>
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
<td align="right">252</td>
<td align="right">252</td>
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
func modification
<details>
<summary>ⓘ</summary>

Modifying a function, e.g. `func.__defaults__ = ...`, etc.
</details>
</td>
<td align="right">3,465</td>
<td align="right">3,465</td>
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
<td align="right">21</td>
<td align="right">21</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2025-11-17
