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
<td align="left">FOR_ITER</td>
<td align="right">16,670,238</td>
<td align="right">2,339,154</td>
<td align="right">-86.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">31,467,228</td>
<td align="right">5,065,883</td>
<td align="right">-83.9%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">49,217,511</td>
<td align="right">8,946,367</td>
<td align="right">-81.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">53,233,959</td>
<td align="right">10,390,297</td>
<td align="right">-80.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">52,155,518</td>
<td align="right">10,207,155</td>
<td align="right">-80.4%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">35,087,503</td>
<td align="right">6,886,864</td>
<td align="right">-80.4%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">52,602,720</td>
<td align="right">10,536,427</td>
<td align="right">-80.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">36,587,729</td>
<td align="right">7,425,779</td>
<td align="right">-79.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">37,750,357</td>
<td align="right">7,921,964</td>
<td align="right">-79.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">107,257,066</td>
<td align="right">23,171,086</td>
<td align="right">-78.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">21,913,464</td>
<td align="right">4,865,492</td>
<td align="right">-77.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">2,544,138</td>
<td align="right">568,834</td>
<td align="right">-77.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">22,013,385</td>
<td align="right">4,992,364</td>
<td align="right">-77.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW</td>
<td align="right">155,288,781</td>
<td align="right">36,967,517</td>
<td align="right">-76.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">23,617,313</td>
<td align="right">5,908,079</td>
<td align="right">-75.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">24,080,310</td>
<td align="right">6,092,654</td>
<td align="right">-74.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">2,863,272</td>
<td align="right">728,224</td>
<td align="right">-74.6%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">1,776,888</td>
<td align="right">539,682</td>
<td align="right">-69.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">1,776,888</td>
<td align="right">539,682</td>
<td align="right">-69.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">3,145,350</td>
<td align="right">1,081,327</td>
<td align="right">-65.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">1,146,783</td>
<td align="right">434,946</td>
<td align="right">-62.1%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">1,359,336</td>
<td align="right">537,128</td>
<td align="right">-60.5%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">1,359,634</td>
<td align="right">537,425</td>
<td align="right">-60.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">5,623,498</td>
<td align="right">2,239,877</td>
<td align="right">-60.2%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">2,203,882</td>
<td align="right">904,850</td>
<td align="right">-58.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_BORROW_LOAD_FAST_BORROW</td>
<td align="right">8,121,932</td>
<td align="right">3,348,543</td>
<td align="right">-58.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">7,273,051</td>
<td align="right">3,156,508</td>
<td align="right">-56.6%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">629,874</td>
<td align="right">279,042</td>
<td align="right">-55.7%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">629,874</td>
<td align="right">279,042</td>
<td align="right">-55.7%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">205,690</td>
<td align="right">92,613</td>
<td align="right">-55.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">2,222,090</td>
<td align="right">1,013,252</td>
<td align="right">-54.4%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">1,484,306</td>
<td align="right">695,897</td>
<td align="right">-53.1%</td>
</tr>
<tr>
<td align="left">POP_ITER</td>
<td align="right">1,621,588</td>
<td align="right">763,058</td>
<td align="right">-52.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,455,512</td>
<td align="right">1,631,099</td>
<td align="right">-52.8%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">2,779,302</td>
<td align="right">1,320,522</td>
<td align="right">-52.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">1,860,837</td>
<td align="right">892,325</td>
<td align="right">-52.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">9,126</td>
<td align="right">4,517</td>
<td align="right">-50.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">24,426</td>
<td align="right">12,138</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_DICT</td>
<td align="right">4,071</td>
<td align="right">2,023</td>
<td align="right">-50.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">35,742</td>
<td align="right">17,822</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">561,545</td>
<td align="right">280,456</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">1,273,017</td>
<td align="right">635,856</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">2,446,792</td>
<td align="right">1,222,191</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">318,153</td>
<td align="right">158,921</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">108,438</td>
<td align="right">54,166</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">4,092</td>
<td align="right">2,044</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">2,046</td>
<td align="right">1,022</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">1,023</td>
<td align="right">511</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">1,621,521</td>
<td align="right">810,000</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,158,102</td>
<td align="right">578,517</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">546,170</td>
<td align="right">273,660</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">1,090</td>
<td align="right">577</td>
<td align="right">-47.1%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">1,317</td>
<td align="right">805</td>
<td align="right">-38.9%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,492</td>
<td align="right">973</td>
<td align="right">-34.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">45</td>
<td align="right">44</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">138</td>
<td align="right">135</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">92</td>
<td align="right">90</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBSCR_TUPLE_INT</td>
<td align="right">46</td>
<td align="right">45</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">46</td>
<td align="right">45</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">46</td>
<td align="right">45</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">46</td>
<td align="right">45</td>
<td align="right">-2.2%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">134</td>
<td align="right">132</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">67</td>
<td align="right">66</td>
<td align="right">-1.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">1,306</td>
<td align="right">1,305</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_JIT</td>
<td align="right">17,065,752</td>
<td align="right"></td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">6,303</td>
<td align="right">6,303</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">4,242</td>
<td align="right">4,242</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">2,310</td>
<td align="right">2,310</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">1,365</td>
<td align="right">1,365</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">504</td>
<td align="right">504</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">462</td>
<td align="right">462</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">42</td>
<td align="right">42</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_JIT</td>
<td align="right"></td>
<td align="right">2,165,904</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">ENTER_EXECUTOR</td>
<td align="right"></td>
<td align="right">837,118</td>
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
<td align="right">5,447,314</td>
<td align="right">90.9%</td>
<td align="right">1,316,992</td>
<td align="right">82.8%</td>
<td align="right">-75.8%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">544,531</td>
<td align="right">9.1%</td>
<td align="right">272,147</td>
<td align="right">17.1%</td>
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
<td align="right">1,345</td>
<td align="right">82.1%</td>
<td align="right">1,219</td>
<td align="right">80.6%</td>
<td align="right">-9.4%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">294</td>
<td align="right">17.9%</td>
<td align="right">294</td>
<td align="right">19.4%</td>
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
<td align="left">true divide other</td>
<td align="right">190</td>
<td align="right">14.1%</td>
<td align="right">169</td>
<td align="right">13.9%</td>
<td align="right">-11.1%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">693</td>
<td align="right">51.5%</td>
<td align="right">630</td>
<td align="right">51.7%</td>
<td align="right">-9.1%</td>
</tr>
<tr>
<td align="left">subscr</td>
<td align="right">462</td>
<td align="right">34.3%</td>
<td align="right">420</td>
<td align="right">34.5%</td>
<td align="right">-9.1%</td>
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
<td align="right">55,805,754</td>
<td align="right">91.6%</td>
<td align="right">11,842,878</td>
<td align="right">83.0%</td>
<td align="right">-78.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">5,106,104</td>
<td align="right">8.4%</td>
<td align="right">2,425,866</td>
<td align="right">17.0%</td>
<td align="right">-52.5%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">5,013,321</td>
<td align="right">8.2%</td>
<td align="right">2,383,005</td>
<td align="right">16.7%</td>
<td align="right">-52.5%</td>
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
<td align="right">99,086</td>
<td align="right">100.0%</td>
<td align="right">49,164</td>
<td align="right">100.0%</td>
<td align="right">-50.4%</td>
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
<td align="right">35,087,503</td>
<td align="right">94.1%</td>
<td align="right">6,886,864</td>
<td align="right">88.4%</td>
<td align="right">-80.4%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,201,937</td>
<td align="right">5.9%</td>
<td align="right">902,062</td>
<td align="right">11.6%</td>
<td align="right">-59.0%</td>
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
<td align="right">1,504</td>
<td align="right">77.3%</td>
<td align="right">2,347</td>
<td align="right">84.2%</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">441</td>
<td align="right">22.7%</td>
<td align="right">441</td>
<td align="right">15.8%</td>
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
<td align="left">baseobject</td>
<td align="right">1,038</td>
<td align="right">69.0%</td>
<td align="right">1,925</td>
<td align="right">82.0%</td>
<td align="right">85.5%</td>
</tr>
<tr>
<td align="left">float long</td>
<td align="right">85</td>
<td align="right">5.7%</td>
<td align="right">64</td>
<td align="right">2.7%</td>
<td align="right">-24.7%</td>
</tr>
<tr>
<td align="left">different types</td>
<td align="right">381</td>
<td align="right">25.3%</td>
<td align="right">358</td>
<td align="right">15.3%</td>
<td align="right">-6.0%</td>
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
<td align="right">16,664,884</td>
<td align="right">96.7%</td>
<td align="right">2,333,314</td>
<td align="right">89.1%</td>
<td align="right">-86.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">561,545</td>
<td align="right">3.3%</td>
<td align="right">280,456</td>
<td align="right">10.7%</td>
<td align="right">-50.1%</td>
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
<td align="right">5,207</td>
<td align="right">97.3%</td>
<td align="right">5,693</td>
<td align="right">97.5%</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">Success</td>
<td align="right">147</td>
<td align="right">2.7%</td>
<td align="right">147</td>
<td align="right">2.5%</td>
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
<td align="right">5,185</td>
<td align="right">99.6%</td>
<td align="right">5,671</td>
<td align="right">99.6%</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">22</td>
<td align="right">0.4%</td>
<td align="right">22</td>
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
<td align="left">other</td>
<td align="right">1,621,521</td>
<td align="right">1,621,521 / 0 !!</td>
<td align="right">810,000</td>
<td align="right">810,000 / 0 !!</td>
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
<td align="right">186,652,608</td>
<td align="right">96.0%</td>
<td align="right">36,660,644</td>
<td align="right">91.5%</td>
<td align="right">-80.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">4,251,860</td>
<td align="right">2.2%</td>
<td align="right">1,795,843</td>
<td align="right">4.5%</td>
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
<td align="right">3,445,975</td>
<td align="right">1.8%</td>
<td align="right">1,620,490</td>
<td align="right">4.0%</td>
<td align="right">-53.0%</td>
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
<td align="right">84,408</td>
<td align="right">94.4%</td>
<td align="right">40,262</td>
<td align="right">86.9%</td>
<td align="right">-52.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">5,022</td>
<td align="right">5.6%</td>
<td align="right">6,094</td>
<td align="right">13.1%</td>
<td align="right">21.3%</td>
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
<td align="right">2,487</td>
<td align="right">49.5%</td>
<td align="right">3,904</td>
<td align="right">64.1%</td>
<td align="right">57.0%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">2,513</td>
<td align="right">50.0%</td>
<td align="right">2,168</td>
<td align="right">35.6%</td>
<td align="right">-13.7%</td>
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
<td align="right">40,895,707</td>
<td align="right">100.0%</td>
<td align="right">9,003,291</td>
<td align="right">100.0%</td>
<td align="right">-78.0%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">2,121</td>
<td align="right">0.0%</td>
<td align="right">2,121</td>
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
<td align="right">2,121</td>
<td align="right">100.0%</td>
<td align="right">2,121</td>
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
<td align="right">1,359,336</td>
<td align="right">100.0%</td>
<td align="right">537,128</td>
<td align="right">99.9%</td>
<td align="right">-60.5%</td>
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
<td align="right">21,268,563</td>
<td align="right">96.6%</td>
<td align="right">4,755,927</td>
<td align="right">95.2%</td>
<td align="right">-77.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">744,822</td>
<td align="right">3.4%</td>
<td align="right">236,437</td>
<td align="right">4.7%</td>
<td align="right">-68.3%</td>
</tr>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,197</td>
<td align="right">0.0%</td>
<td align="right">1,197</td>
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
<td align="right">15,015</td>
<td align="right">99.7%</td>
<td align="right">5,676</td>
<td align="right">99.3%</td>
<td align="right">-62.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">42</td>
<td align="right">0.3%</td>
<td align="right">42</td>
<td align="right">0.7%</td>
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
<td align="left">not in keys</td>
<td align="right">42</td>
<td align="right">100.0%</td>
<td align="right">42</td>
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
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">9,049,939</td>
<td align="right">100.0%</td>
<td align="right">3,696,190</td>
<td align="right">100.0%</td>
<td align="right">-59.2%</td>
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
<td align="right">0.0%</td>
<td align="right">675</td>
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
<td align="right">609</td>
<td align="right">96.7%</td>
<td align="right">609</td>
<td align="right">96.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">21</td>
<td align="right">3.3%</td>
<td align="right">21</td>
<td align="right">3.3%</td>
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
<td align="right">46</td>
<td align="right">52.3%</td>
<td align="right">45</td>
<td align="right">51.7%</td>
<td align="right">-2.2%</td>
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
<td align="right">23.9%</td>
<td align="right">21</td>
<td align="right">24.1%</td>
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
<td align="right">424,501,602</td>
<td align="right">53.2%</td>
<td align="right">87,058,059</td>
<td align="right">48.3%</td>
<td align="right">-79.5%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">24,511,988</td>
<td align="right">3.1%</td>
<td align="right">5,973,427</td>
<td align="right">3.3%</td>
<td align="right">-75.6%</td>
</tr>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">339,111,841</td>
<td align="right">42.5%</td>
<td align="right">82,888,148</td>
<td align="right">46.0%</td>
<td align="right">-75.6%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">10,103,021</td>
<td align="right">1.3%</td>
<td align="right">4,458,253</td>
<td align="right">2.5%</td>
<td align="right">-55.9%</td>
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
<td align="right">16,664,884</td>
<td align="right">59.8%</td>
<td align="right">2,333,314</td>
<td align="right">31.0%</td>
<td align="right">-86.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">2,201,937</td>
<td align="right">7.9%</td>
<td align="right">902,062</td>
<td align="right">12.0%</td>
<td align="right">-59.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,445,975</td>
<td align="right">12.4%</td>
<td align="right">1,620,490</td>
<td align="right">21.6%</td>
<td align="right">-53.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">5,013,321</td>
<td align="right">18.0%</td>
<td align="right">2,383,005</td>
<td align="right">31.7%</td>
<td align="right">-52.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">544,531</td>
<td align="right">2.0%</td>
<td align="right">272,147</td>
<td align="right">3.6%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">676</td>
<td align="right">0.0%</td>
<td align="right">675</td>
<td align="right">0.0%</td>
<td align="right">-0.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">2,121</td>
<td align="right">0.0%</td>
<td align="right">2,121</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">1,197</td>
<td align="right">0.0%</td>
<td align="right">1,197</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">231</td>
<td align="right">0.0%</td>
<td align="right">231</td>
<td align="right">0.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">21</td>
<td align="right">0.0%</td>
<td align="right">21</td>
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
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">744,822</td>
<td align="right">7.4%</td>
<td align="right">236,437</td>
<td align="right">5.3%</td>
<td align="right">-68.3%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">1,386,341</td>
<td align="right">13.7%</td>
<td align="right">567,864</td>
<td align="right">12.7%</td>
<td align="right">-59.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">2,634,579</td>
<td align="right">26.1%</td>
<td align="right">1,103,022</td>
<td align="right">24.7%</td>
<td align="right">-58.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">1,617,281</td>
<td align="right">16.0%</td>
<td align="right">692,821</td>
<td align="right">15.5%</td>
<td align="right">-57.2%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">235</td>
<td align="right">0.0%</td>
<td align="right">107</td>
<td align="right">0.0%</td>
<td align="right">-54.5%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">235</td>
<td align="right">0.0%</td>
<td align="right">107</td>
<td align="right">0.0%</td>
<td align="right">-54.5%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">1,273,017</td>
<td align="right">12.6%</td>
<td align="right">635,856</td>
<td align="right">14.3%</td>
<td align="right">-50.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">2,446,746</td>
<td align="right">24.2%</td>
<td align="right">1,222,146</td>
<td align="right">27.4%</td>
<td align="right">-50.1%</td>
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
<td align="left">Calls to Python functions inlined</td>
<td align="right">52,602,701</td>
<td align="right">100.0%</td>
<td align="right">26,275,656</td>
<td align="right">100.0%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">53,233,959</td>
<td align="right">101.2%</td>
<td align="right">26,591,009</td>
<td align="right">101.2%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">1,384</td>
<td align="right">0.0%</td>
<td align="right">871</td>
<td align="right">0.0%</td>
<td align="right">-37.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">1,384</td>
<td align="right">0.0%</td>
<td align="right">871</td>
<td align="right">0.0%</td>
<td align="right">-37.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">1,384</td>
<td align="right">0.0%</td>
<td align="right">871</td>
<td align="right">0.0%</td>
<td align="right">-37.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">1,384</td>
<td align="right">0.0%</td>
<td align="right">871</td>
<td align="right">0.0%</td>
<td align="right">-37.1%</td>
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
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
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
<tr>
<td align="left">Frame objects created</td>
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
<td align="left">Method cache collisions</td>
<td align="right">10,032</td>
<td align="right"></td>
<td align="right">2,868</td>
<td align="right"></td>
<td align="right">-71.4%</td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">10,566</td>
<td align="right"></td>
<td align="right">3,517</td>
<td align="right"></td>
<td align="right">-66.7%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">10,969,749</td>
<td align="right">3.9%</td>
<td align="right">5,049,878</td>
<td align="right">3.7%</td>
<td align="right">-54.0%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">11,890,499</td>
<td align="right"></td>
<td align="right">5,493,419</td>
<td align="right"></td>
<td align="right">-53.8%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">11,915,199</td>
<td align="right">4.4%</td>
<td align="right">5,507,147</td>
<td align="right">4.1%</td>
<td align="right">-53.8%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">2,994,522</td>
<td align="right"></td>
<td align="right">1,434,413</td>
<td align="right"></td>
<td align="right">-52.1%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">20,826,644</td>
<td align="right">7.4%</td>
<td align="right">10,116,436</td>
<td align="right">7.4%</td>
<td align="right">-51.4%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">40,638,161</td>
<td align="right">15.0%</td>
<td align="right">19,781,708</td>
<td align="right">14.9%</td>
<td align="right">-51.3%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">231,609,662</td>
<td align="right">82.6%</td>
<td align="right">113,747,095</td>
<td align="right">82.8%</td>
<td align="right">-50.9%</td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">202,514,493</td>
<td align="right">74.7%</td>
<td align="right">99,594,286</td>
<td align="right">75.0%</td>
<td align="right">-50.8%</td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">1,483,350</td>
<td align="right"></td>
<td align="right">740,950</td>
<td align="right"></td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">7,490,235</td>
<td align="right"></td>
<td align="right">3,741,719</td>
<td align="right"></td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">7,489,405</td>
<td align="right">77.4%</td>
<td align="right">3,741,660</td>
<td align="right">77.3%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">2,189,543</td>
<td align="right">22.6%</td>
<td align="right">1,095,415</td>
<td align="right">22.6%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">2,189,543</td>
<td align="right">22.6%</td>
<td align="right">1,095,804</td>
<td align="right">22.7%</td>
<td align="right">-50.0%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">17,002,970</td>
<td align="right">6.1%</td>
<td align="right">8,514,125</td>
<td align="right">6.2%</td>
<td align="right">-49.9%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">15,890,780</td>
<td align="right">5.9%</td>
<td align="right">7,977,509</td>
<td align="right">6.0%</td>
<td align="right">-49.8%</td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">1,554</td>
<td align="right"></td>
<td align="right">1,470</td>
<td align="right"></td>
<td align="right">-5.4%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">149</td>
<td align="right">0.0%</td>
<td align="right">149 / 0 !!</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">0</td>
<td align="right">0.0%</td>
<td align="right">240</td>
<td align="right">0.0%</td>
<td align="right">240 / 0 !!</td>
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
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">336</td>
<td align="right"></td>
<td align="right">336</td>
<td align="right"></td>
<td align="right">0.0%</td>
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
<td align="right">469</td>
<td align="right">842,484</td>
<td align="right">10,501,115</td>
<td align="right">43,285</td>
<td align="right">926,383</td>
<td align="right">234</td>
<td align="right">386,304</td>
<td align="right">5,003,846</td>
<td align="right">15,063</td>
<td align="right">442,332</td>
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
<td align="right">126</td>
<td align="right">126 / 0 !!</td>
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
<td align="right">126</td>
<td align="right">126 / 0 !!</td>
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
