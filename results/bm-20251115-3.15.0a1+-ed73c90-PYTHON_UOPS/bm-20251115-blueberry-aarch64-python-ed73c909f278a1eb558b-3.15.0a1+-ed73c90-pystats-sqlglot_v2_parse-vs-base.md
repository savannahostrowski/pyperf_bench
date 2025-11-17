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
<td align="left">TO_BOOL_INT</td>
<td align="right">3,579,009</td>
<td align="right">199,582</td>
<td align="right">-94.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">8,202,285</td>
<td align="right">714,653</td>
<td align="right">-91.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_STR_INT</td>
<td align="right">11,314,422</td>
<td align="right">1,118,688</td>
<td align="right">-90.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">12,170,340</td>
<td align="right">1,384,962</td>
<td align="right">-88.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">7,620,741</td>
<td align="right">949,099</td>
<td align="right">-87.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">12,817,350</td>
<td align="right">1,814,128</td>
<td align="right">-85.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">13,066,977</td>
<td align="right">1,938,827</td>
<td align="right">-85.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">6,936,720</td>
<td align="right">1,032,773</td>
<td align="right">-85.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">562,785</td>
<td align="right">87,248</td>
<td align="right">-84.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">13,607,391</td>
<td align="right">2,148,799</td>
<td align="right">-84.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">39,043,217</td>
<td align="right">6,383,743</td>
<td align="right">-83.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">7,026,873</td>
<td align="right">1,227,782</td>
<td align="right">-82.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">7,485,183</td>
<td align="right">1,456,715</td>
<td align="right">-80.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">114,919,087</td>
<td align="right">24,702,175</td>
<td align="right">-78.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">217,724,271</td>
<td align="right">53,150,702</td>
<td align="right">-75.6%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">10,242,024</td>
<td align="right">2,545,647</td>
<td align="right">-75.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">10,138,443</td>
<td align="right">2,538,624</td>
<td align="right">-75.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">12,702,828</td>
<td align="right">3,645,917</td>
<td align="right">-71.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">47,104,854</td>
<td align="right">13,858,580</td>
<td align="right">-70.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">11,064,383</td>
<td align="right">3,318,204</td>
<td align="right">-70.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">6,431,994</td>
<td align="right">1,971,432</td>
<td align="right">-69.3%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">4,570,089</td>
<td align="right">1,441,340</td>
<td align="right">-68.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">19,901,769</td>
<td align="right">6,299,261</td>
<td align="right">-68.3%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,191,561</td>
<td align="right">385,185</td>
<td align="right">-67.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">21,569,097</td>
<td align="right">7,040,483</td>
<td align="right">-67.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">31,686,198</td>
<td align="right">10,392,868</td>
<td align="right">-67.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,206,385</td>
<td align="right">1,058,265</td>
<td align="right">-67.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">9,370,277</td>
<td align="right">3,128,588</td>
<td align="right">-66.6%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">6,463,493</td>
<td align="right">2,159,122</td>
<td align="right">-66.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">3,804,219</td>
<td align="right">1,311,898</td>
<td align="right">-65.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">3,804,324</td>
<td align="right">1,312,003</td>
<td align="right">-65.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">10,547,080</td>
<td align="right">3,730,351</td>
<td align="right">-64.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">10,198,306</td>
<td align="right">3,749,666</td>
<td align="right">-63.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">15,333,147</td>
<td align="right">5,679,885</td>
<td align="right">-63.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">23,268,618</td>
<td align="right">8,706,629</td>
<td align="right">-62.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">2,956,428</td>
<td align="right">1,143,819</td>
<td align="right">-61.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">13,820,970</td>
<td align="right">5,363,692</td>
<td align="right">-61.2%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">2,653,350</td>
<td align="right">1,047,030</td>
<td align="right">-60.5%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">1,064,838</td>
<td align="right">426,616</td>
<td align="right">-59.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">1,265,166</td>
<td align="right">514,472</td>
<td align="right">-59.3%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">2,473,449</td>
<td align="right">1,007,717</td>
<td align="right">-59.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">30,931,866</td>
<td align="right">12,633,110</td>
<td align="right">-59.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">769,734</td>
<td align="right">315,653</td>
<td align="right">-59.0%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">1,355,514</td>
<td align="right">556,436</td>
<td align="right">-59.0%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">1,429,155</td>
<td align="right">593,753</td>
<td align="right">-58.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">31,499,202</td>
<td align="right">13,117,047</td>
<td align="right">-58.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">1,494,570</td>
<td align="right">626,400</td>
<td align="right">-58.1%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">1,912,503</td>
<td align="right">840,532</td>
<td align="right">-56.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">7,935,591</td>
<td align="right">3,559,102</td>
<td align="right">-55.2%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">565,089</td>
<td align="right">267,016</td>
<td align="right">-52.7%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">565,089</td>
<td align="right">267,016</td>
<td align="right">-52.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">565,089</td>
<td align="right">267,016</td>
<td align="right">-52.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">520,065</td>
<td align="right">246,431</td>
<td align="right">-52.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">16,579,370</td>
<td align="right">7,878,302</td>
<td align="right">-52.5%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">630,441</td>
<td align="right">299,600</td>
<td align="right">-52.5%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">552,894</td>
<td align="right">262,875</td>
<td align="right">-52.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">638,889</td>
<td align="right">303,951</td>
<td align="right">-52.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">23,889</td>
<td align="right">11,381</td>
<td align="right">-52.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">8,601,776</td>
<td align="right">4,111,866</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">1,197,598</td>
<td align="right">572,501</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">630,588</td>
<td align="right">306,396</td>
<td align="right">-51.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">1,128,323</td>
<td align="right">548,650</td>
<td align="right">-51.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">4,071</td>
<td align="right">2,023</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">4,074</td>
<td align="right">2,026</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">4,074</td>
<td align="right">2,026</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">20,391</td>
<td align="right">10,151</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_GETITEM</td>
<td align="right">8,169</td>
<td align="right">4,073</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">537,069</td>
<td align="right">268,065</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">28,623</td>
<td align="right">14,287</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">16,359</td>
<td align="right">8,167</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">384,531</td>
<td align="right">192,019</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">851,142</td>
<td align="right">425,156</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">24,555</td>
<td align="right">12,266</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">147,336</td>
<td align="right">73,608</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">257,859</td>
<td align="right">128,835</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">483,168</td>
<td align="right">241,504</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_LIST_INT</td>
<td align="right">1,732,335</td>
<td align="right">865,904</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">2,743,650</td>
<td align="right">1,371,490</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">421,785</td>
<td align="right">210,841</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">405,405</td>
<td align="right">202,653</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">24,570</td>
<td align="right">12,282</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">24,570</td>
<td align="right">12,282</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">12,285</td>
<td align="right">6,141</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">12,285</td>
<td align="right">6,141</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">12,285</td>
<td align="right">6,141</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">DICT_UPDATE</td>
<td align="right">4,095</td>
<td align="right">2,047</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">3,882,207</td>
<td align="right">1,940,703</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">1,973,928</td>
<td align="right">986,790</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">2,768,433</td>
<td align="right">1,383,981</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">685,988</td>
<td align="right">342,945</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">335,859</td>
<td align="right">167,922</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">241,674</td>
<td align="right">120,841</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,613,913</td>
<td align="right">806,994</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">405,543</td>
<td align="right">202,789</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">69,684</td>
<td align="right">34,867</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">32,829</td>
<td align="right">16,444</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">12,366</td>
<td align="right">6,219</td>
<td align="right">-49.7%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">8,259</td>
<td align="right">4,162</td>
<td align="right">-49.6%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">8,259</td>
<td align="right">4,162</td>
<td align="right">-49.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">4,143</td>
<td align="right">2,094</td>
<td align="right">-49.5%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">37,760</td>
<td align="right">19,286</td>
<td align="right">-48.9%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">7,355</td>
<td align="right">4,160</td>
<td align="right">-43.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">10,906</td>
<td align="right">8,836</td>
<td align="right">-19.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">48</td>
<td align="right">47</td>
<td align="right">-2.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">48</td>
<td align="right">47</td>
<td align="right">-2.1%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">69</td>
<td align="right">68</td>
<td align="right">-1.4%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">69</td>
<td align="right">68</td>
<td align="right">-1.4%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">10,131,099</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">11,844</td>
<td align="right">11,844</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">7,014</td>
<td align="right">7,014</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">2,247</td>
<td align="right">2,247</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">1,806</td>
<td align="right">1,806</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">1,050</td>
<td align="right">1,050</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">483</td>
<td align="right">483</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">210</td>
<td align="right">210</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">1,572,210</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">1,122,385</td>
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
<td align="right">561,732</td>
<td align="right">1.5%</td>
<td align="right">86,197</td>
<td align="right">1.3%</td>
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
<td align="right">36,264,542</td>
<td align="right">98.4%</td>
<td align="right">6,634,782</td>
<td align="right">98.6%</td>
<td align="right">-81.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">12,565</td>
<td align="right">0.0%</td>
<td align="right">6,293</td>
<td align="right">0.1%</td>
<td align="right">-49.9%</td>
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
<td align="right">948</td>
<td align="right">73.7%</td>
<td align="right">821</td>
<td align="right">70.9%</td>
<td align="right">-13.4%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">339</td>
<td align="right">26.3%</td>
<td align="right">337</td>
<td align="right">29.1%</td>
<td align="right">-0.6%</td>
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
<td align="right">338</td>
<td align="right">99.7%</td>
<td align="right">336</td>
<td align="right">99.7%</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">1</td>
<td align="right">0.3%</td>
<td align="right">1</td>
<td align="right">0.3%</td>
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
<td align="right">1,429,155</td>
<td align="right">100.0%</td>
<td align="right">593,753</td>
<td align="right">100.0%</td>
<td align="right">-58.5%</td>
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
<td align="right">35,666,387</td>
<td align="right">97.8%</td>
<td align="right">14,115,044</td>
<td align="right">97.3%</td>
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
<td align="right">774,740</td>
<td align="right">2.1%</td>
<td align="right">386,616</td>
<td align="right">2.7%</td>
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
<td align="right">766,075</td>
<td align="right">2.1%</td>
<td align="right">385,287</td>
<td align="right">2.7%</td>
<td align="right">-49.7%</td>
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
<td align="right">20,509</td>
<td align="right">100.0%</td>
<td align="right">13,173</td>
<td align="right">100.0%</td>
<td align="right">-35.8%</td>
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
<td align="right">525</td>
<td align="right">50.0%</td>
<td align="right">525</td>
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
<td align="right">525</td>
<td align="right">100.0%</td>
<td align="right">525</td>
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
<td align="right">14,872,557</td>
<td align="right">61.3%</td>
<td align="right">2,663,292</td>
<td align="right">46.0%</td>
<td align="right">-82.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">9,365,748</td>
<td align="right">38.6%</td>
<td align="right">3,124,506</td>
<td align="right">53.9%</td>
<td align="right">-66.6%</td>
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
<td align="right">4,046</td>
<td align="right">89.3%</td>
<td align="right">3,599</td>
<td align="right">88.2%</td>
<td align="right">-11.0%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">483</td>
<td align="right">10.7%</td>
<td align="right">483</td>
<td align="right">11.8%</td>
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
<td align="right">317</td>
<td align="right">7.8%</td>
<td align="right">831</td>
<td align="right">23.1%</td>
<td align="right">162.1%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">3,729</td>
<td align="right">92.2%</td>
<td align="right">2,747</td>
<td align="right">76.3%</td>
<td align="right">-26.3%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right"></td>
<td align="right"></td>
<td align="right">21</td>
<td align="right">0.6%</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">6,940,955</td>
<td align="right">91.0%</td>
<td align="right">2,382,543</td>
<td align="right">87.4%</td>
<td align="right">-65.7%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">650,861</td>
<td align="right">8.5%</td>
<td align="right">325,229</td>
<td align="right">11.9%</td>
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
<td align="right">37,149</td>
<td align="right">0.5%</td>
<td align="right">18,717</td>
<td align="right">0.7%</td>
<td align="right">-49.6%</td>
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
<td align="right">12,559</td>
<td align="right">97.5%</td>
<td align="right">6,415</td>
<td align="right">95.9%</td>
<td align="right">-48.9%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">317</td>
<td align="right">2.5%</td>
<td align="right">275</td>
<td align="right">4.1%</td>
<td align="right">-13.2%</td>
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
<td align="right">127</td>
<td align="right">40.1%</td>
<td align="right">106</td>
<td align="right">38.5%</td>
<td align="right">-16.5%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">190</td>
<td align="right">59.9%</td>
<td align="right">169</td>
<td align="right">61.5%</td>
<td align="right">-11.1%</td>
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
<td align="right">6,429,324</td>
<td align="right">97.7%</td>
<td align="right">1,966,543</td>
<td align="right">96.1%</td>
<td align="right">-69.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">151,479</td>
<td align="right">2.3%</td>
<td align="right">75,702</td>
<td align="right">3.7%</td>
<td align="right">-50.0%</td>
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
<td align="right">2,565</td>
<td align="right">96.1%</td>
<td align="right">4,784</td>
<td align="right">97.9%</td>
<td align="right">86.5%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">105</td>
<td align="right">3.9%</td>
<td align="right">105</td>
<td align="right">2.1%</td>
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
<td align="left">ascii string</td>
<td align="right">551</td>
<td align="right">21.5%</td>
<td align="right">1,822</td>
<td align="right">38.1%</td>
<td align="right">230.7%</td>
</tr>
<tr>
<td align="left">dict items</td>
<td align="right">1,167</td>
<td align="right">45.5%</td>
<td align="right">2,099</td>
<td align="right">43.9%</td>
<td align="right">79.9%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">338</td>
<td align="right">13.2%</td>
<td align="right">357</td>
<td align="right">7.5%</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">487</td>
<td align="right">19.0%</td>
<td align="right">484</td>
<td align="right">10.1%</td>
<td align="right">-0.6%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">22</td>
<td align="right">0.9%</td>
<td align="right">22</td>
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
<td align="left">string</td>
<td align="right">1,003,275</td>
<td align="right">1,003,275 / 0 !!</td>
<td align="right">501,515</td>
<td align="right">501,515 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">384,930</td>
<td align="right">384,930 / 0 !!</td>
<td align="right">192,418</td>
<td align="right">192,418 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">53,235</td>
<td align="right">53,235 / 0 !!</td>
<td align="right">26,611</td>
<td align="right">26,611 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">4,095</td>
<td align="right">4,095 / 0 !!</td>
<td align="right">2,047</td>
<td align="right">2,047 / 0 !!</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">1,027,914</td>
<td align="right">1,027,914 / 0 !!</td>
<td align="right">513,865</td>
<td align="right">513,865 / 0 !!</td>
<td align="right">-50.0%</td>
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
<td align="right">161,194,306</td>
<td align="right">92.5%</td>
<td align="right">39,735,119</td>
<td align="right">88.8%</td>
<td align="right">-75.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">10,517,268</td>
<td align="right">6.0%</td>
<td align="right">3,703,112</td>
<td align="right">8.3%</td>
<td align="right">-64.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,567,544</td>
<td align="right">1.5%</td>
<td align="right">1,259,682</td>
<td align="right">2.8%</td>
<td align="right">-50.9%</td>
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
<td align="right">57,802</td>
<td align="right">73.9%</td>
<td align="right">33,219</td>
<td align="right">65.1%</td>
<td align="right">-42.5%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">20,404</td>
<td align="right">26.1%</td>
<td align="right">17,831</td>
<td align="right">34.9%</td>
<td align="right">-12.6%</td>
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
<td align="left">class method obj</td>
<td align="right">443</td>
<td align="right">2.2%</td>
<td align="right">380</td>
<td align="right">2.1%</td>
<td align="right">-14.2%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">2,661</td>
<td align="right">13.0%</td>
<td align="right">2,325</td>
<td align="right">13.0%</td>
<td align="right">-12.6%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">17,278</td>
<td align="right">84.7%</td>
<td align="right">15,104</td>
<td align="right">84.7%</td>
<td align="right">-12.6%</td>
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
<td align="right">23,264,286</td>
<td align="right">100.0%</td>
<td align="right">9,234,535</td>
<td align="right">99.9%</td>
<td align="right">-60.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">3,507</td>
<td align="right">0.0%</td>
<td align="right">3,507</td>
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
<td align="right">4,452</td>
<td align="right">0.0%</td>
<td align="right">4,452</td>
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
<td align="right">3,591</td>
<td align="right">100.0%</td>
<td align="right">3,591</td>
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
<td align="right">36,308,970</td>
<td align="right">93.0%</td>
<td align="right">5,076,308</td>
<td align="right">79.5%</td>
<td align="right">-86.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,734,247</td>
<td align="right">7.0%</td>
<td align="right">1,307,435</td>
<td align="right">20.5%</td>
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
<td align="right">903</td>
<td align="right">0.0%</td>
<td align="right">903</td>
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
<td align="right">52,433</td>
<td align="right">100.0%</td>
<td align="right">25,632</td>
<td align="right">100.0%</td>
<td align="right">-51.1%</td>
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
<td align="right">4,074</td>
<td align="right">99.0%</td>
<td align="right">2,026</td>
<td align="right">98.0%</td>
<td align="right">-50.3%</td>
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
<td align="right">0.5%</td>
<td align="right">21</td>
<td align="right">1.0%</td>
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
<td align="right">29,668,568</td>
<td align="right">94.1%</td>
<td align="right">8,150,900</td>
<td align="right">93.1%</td>
<td align="right">-72.5%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,865,788</td>
<td align="right">5.9%</td>
<td align="right">595,633</td>
<td align="right">6.8%</td>
<td align="right">-68.1%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">7,461</td>
<td align="right">0.0%</td>
<td align="right">5,412</td>
<td align="right">0.1%</td>
<td align="right">-27.5%</td>
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
<td align="right">38,159</td>
<td align="right">99.6%</td>
<td align="right">14,264</td>
<td align="right">99.1%</td>
<td align="right">-62.6%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">148</td>
<td align="right">0.4%</td>
<td align="right">127</td>
<td align="right">0.9%</td>
<td align="right">-14.2%</td>
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
<td align="right">127</td>
<td align="right">85.8%</td>
<td align="right">106</td>
<td align="right">83.5%</td>
<td align="right">-16.5%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">21</td>
<td align="right">14.2%</td>
<td align="right">21</td>
<td align="right">16.5%</td>
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
<td align="right">3,804,219</td>
<td align="right">100.0%</td>
<td align="right">1,311,898</td>
<td align="right">100.0%</td>
<td align="right">-65.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">105</td>
<td align="right">0.0%</td>
<td align="right">105</td>
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
<td align="right">105</td>
<td align="right">100.0%</td>
<td align="right">105</td>
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
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">404,654,927</td>
<td align="right">44.8%</td>
<td align="right">107,843,912</td>
<td align="right">42.7%</td>
<td align="right">-73.3%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">458,706,501</td>
<td align="right">50.8%</td>
<td align="right">130,226,619</td>
<td align="right">51.6%</td>
<td align="right">-71.6%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">30,885,372</td>
<td align="right">3.4%</td>
<td align="right">10,569,177</td>
<td align="right">4.2%</td>
<td align="right">-65.8%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">8,610,197</td>
<td align="right">1.0%</td>
<td align="right">3,885,340</td>
<td align="right">1.5%</td>
<td align="right">-54.9%</td>
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
<td align="right">561,732</td>
<td align="right">1.9%</td>
<td align="right">86,197</td>
<td align="right">0.9%</td>
<td align="right">-84.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">6,429,324</td>
<td align="right">22.1%</td>
<td align="right">1,966,543</td>
<td align="right">19.9%</td>
<td align="right">-69.4%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">9,365,748</td>
<td align="right">32.2%</td>
<td align="right">3,124,506</td>
<td align="right">31.6%</td>
<td align="right">-66.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">10,517,268</td>
<td align="right">36.1%</td>
<td align="right">3,703,112</td>
<td align="right">37.4%</td>
<td align="right">-64.8%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">1,429,155</td>
<td align="right">4.9%</td>
<td align="right">593,753</td>
<td align="right">6.0%</td>
<td align="right">-58.5%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">766,075</td>
<td align="right">2.6%</td>
<td align="right">385,287</td>
<td align="right">3.9%</td>
<td align="right">-49.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">37,149</td>
<td align="right">0.1%</td>
<td align="right">18,717</td>
<td align="right">0.2%</td>
<td align="right">-49.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">7,461</td>
<td align="right">0.0%</td>
<td align="right">5,412</td>
<td align="right">0.1%</td>
<td align="right">-27.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">3,507</td>
<td align="right">0.0%</td>
<td align="right">3,507</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">903</td>
<td align="right">0.0%</td>
<td align="right">903</td>
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
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">644,558</td>
<td align="right">7.5%</td>
<td align="right">156,401</td>
<td align="right">4.0%</td>
<td align="right">-75.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">923,312</td>
<td align="right">10.7%</td>
<td align="right">293,880</td>
<td align="right">7.6%</td>
<td align="right">-68.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">2,734,247</td>
<td align="right">31.8%</td>
<td align="right">1,307,435</td>
<td align="right">33.7%</td>
<td align="right">-52.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">1,048,034</td>
<td align="right">12.2%</td>
<td align="right">503,363</td>
<td align="right">13.0%</td>
<td align="right">-52.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">975,416</td>
<td align="right">11.3%</td>
<td align="right">483,595</td>
<td align="right">12.4%</td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">390,547</td>
<td align="right">4.5%</td>
<td align="right">194,342</td>
<td align="right">5.0%</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">378,202</td>
<td align="right">4.4%</td>
<td align="right">188,882</td>
<td align="right">4.9%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">325,282</td>
<td align="right">3.8%</td>
<td align="right">162,466</td>
<td align="right">4.2%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">325,579</td>
<td align="right">3.8%</td>
<td align="right">162,763</td>
<td align="right">4.2%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">543,359</td>
<td align="right">6.3%</td>
<td align="right">271,989</td>
<td align="right">7.0%</td>
<td align="right">-49.9%</td>
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
<td align="right">12,285</td>
<td align="right">0.0%</td>
<td align="right">6,141</td>
<td align="right">0.0%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">27,051,837</td>
<td align="right">87.4%</td>
<td align="right">13,522,743</td>
<td align="right">87.4%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">31,499,202</td>
<td align="right">101.8%</td>
<td align="right">15,745,979</td>
<td align="right">101.8%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">2,743,755</td>
<td align="right">8.9%</td>
<td align="right">1,371,595</td>
<td align="right">8.9%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">450,471</td>
<td align="right">1.5%</td>
<td align="right">225,191</td>
<td align="right">1.5%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">3,882,276</td>
<td align="right">12.6%</td>
<td align="right">1,940,771</td>
<td align="right">12.6%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">3,882,276</td>
<td align="right">12.6%</td>
<td align="right">1,940,771</td>
<td align="right">12.6%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">3,882,276</td>
<td align="right">12.6%</td>
<td align="right">1,940,771</td>
<td align="right">12.6%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">3,882,276</td>
<td align="right">12.6%</td>
<td align="right">1,940,771</td>
<td align="right">12.6%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">69</td>
<td align="right">0.0%</td>
<td align="right">68</td>
<td align="right">0.0%</td>
<td align="right">-1.4%</td>
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
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
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
<td align="left">Method cache dunder misses</td>
<td align="right">18,073</td>
<td align="right"></td>
<td align="right">46,969</td>
<td align="right"></td>
<td align="right">159.9%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">7,513,117</td>
<td align="right"></td>
<td align="right">3,717,947</td>
<td align="right"></td>
<td align="right">-50.5%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">25,245,007</td>
<td align="right"></td>
<td align="right">12,529,628</td>
<td align="right"></td>
<td align="right">-50.4%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">73,247,823</td>
<td align="right">21.3%</td>
<td align="right">36,505,021</td>
<td align="right">21.2%</td>
<td align="right">-50.2%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">12,184,752</td>
<td align="right">49.5%</td>
<td align="right">6,078,458</td>
<td align="right">49.4%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">12,184,752</td>
<td align="right">49.5%</td>
<td align="right">6,078,798</td>
<td align="right">49.4%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">52,656,711</td>
<td align="right">15.3%</td>
<td align="right">26,304,697</td>
<td align="right">15.3%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">647,010</td>
<td align="right"></td>
<td align="right">323,426</td>
<td align="right"></td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">214,944,643</td>
<td align="right">60.9%</td>
<td align="right">107,479,261</td>
<td align="right">60.7%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">182,216,470</td>
<td align="right">53.0%</td>
<td align="right">91,152,176</td>
<td align="right">53.0%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">40,003,386</td>
<td align="right">11.3%</td>
<td align="right">20,030,324</td>
<td align="right">11.3%</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">35,935,368</td>
<td align="right">10.4%</td>
<td align="right">18,002,539</td>
<td align="right">10.5%</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">12,404,574</td>
<td align="right"></td>
<td align="right">6,218,984</td>
<td align="right"></td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">12,407,955</td>
<td align="right">50.5%</td>
<td align="right">6,220,965</td>
<td align="right">50.6%</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">57,166,187</td>
<td align="right">16.2%</td>
<td align="right">28,754,949</td>
<td align="right">16.2%</td>
<td align="right">-49.7%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">41,014,905</td>
<td align="right">11.6%</td>
<td align="right">20,846,442</td>
<td align="right">11.8%</td>
<td align="right">-49.2%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">11,394,542</td>
<td align="right"></td>
<td align="right">5,936,243</td>
<td align="right"></td>
<td align="right">-47.9%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">335,826</td>
<td align="right"></td>
<td align="right">199,204</td>
<td align="right"></td>
<td align="right">-40.7%</td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">352,305</td>
<td align="right"></td>
<td align="right">244,641</td>
<td align="right"></td>
<td align="right">-30.6%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">192</td>
<td align="right">0.0%</td>
<td align="right">192 / 0 !!</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">148</td>
<td align="right">0.0%</td>
<td align="right">148 / 0 !!</td>
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
<td align="right">639</td>
<td align="right">783,594</td>
<td align="right">10,412,114</td>
<td align="right">673,016</td>
<td align="right">928,956</td>
<td align="right">320</td>
<td align="right">541,548</td>
<td align="right">4,530,314</td>
<td align="right">83,334</td>
<td align="right">649,670</td>
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
