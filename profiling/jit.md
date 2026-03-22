
## 2to3

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.31% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.82% | `[JIT]` | `jit` | jit |
| 3.12% | `python` | `gc_collect_region` | gc |
| 2.90% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.52% | `python` | `_PyObject_Malloc` | memory |
| 1.80% | `python` | `sre_ucs1_match` | library |
| 1.80% | `python` | `_Py_dict_lookup` | lookup |
| 1.60% | `python` | `_Py_Dealloc` | memory |
| 1.58% | `python` | `_PyObject_Free` | memory |
| 1.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.40% | `python` | `visit_decref` | gc |
| 1.33% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.14% | `python` | `tuple_dealloc` | memory |
| 0.83% | `python` | `r_object` | import |
| 0.73% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.71% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.68% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.68% | `python` | `visit_reachable` | gc |
| 0.63% | `python` | `_PyGC_Collect` | gc |
| 0.61% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.61% | `python` | `tuple_alloc` | memory |
| 0.61% | `python` | `initialize_locals` | interpreter |
| 0.56% | `python` | `find_name_in_mro` | lookup |
| 0.55% | `python` | `_PyCode_Quicken` | interpreter |
| 0.54% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.53% | `python` | `PyDict_GetItemRef` | dict |
| 0.52% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.45% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.45% | `python` | `siphash13` | str |
| 0.44% | `python` | `gen_dealloc` | memory |
| 0.43% | `python` | `dict_traverse` | gc |
| 0.42% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.41% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.40% | `python` | `visit_add_to_container` | gc |
| 0.38% | `python` | `type_ready` | dynamic |
| 0.38% | `libc.so.6` | `_int_malloc` | libc |
| 0.37% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.35% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `insertdict` | dict |
| 0.32% | `python` | `PyObject_SetAttr` | dynamic |
| 0.31% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.31% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.31% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.31% | `python` | `_PyEval_Vector` | interpreter |
| 0.29% | `python` | `sre_ucs1_count` | library |
| 0.29% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.28% | `python` | `intern_constants` | str |
| 0.28% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.28% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.27% | `python` | `list_subscript` | list |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `dict_dealloc` | memory |
| 0.26% | `python` | `PySlice_AdjustIndices` | miscobj |

## argparse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.43% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.14% | `[JIT]` | `jit` | jit |
| 3.09% | `python` | `_PyObject_Malloc` | memory |
| 2.34% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.14% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.76% | `python` | `_PyObject_Free` | memory |
| 1.67% | `python` | `_Py_Dealloc` | memory |
| 1.57% | `python` | `_Py_dict_lookup` | lookup |
| 1.38% | `python` | `initialize_locals` | interpreter |
| 1.34% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.92% | `python` | `gc_collect_region` | gc |
| 0.87% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.83% | `python` | `PyDict_GetItemRef` | dict |
| 0.74% | `[unknown]` | `0xffffffffab6001c6` | unknown |
| 0.68% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.63% | `python` | `tuple_dealloc` | memory |
| 0.62% | `python` | `PyUnicode_Format` | str |
| 0.62% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.56% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.49% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.48% | `python` | `tuple_alloc` | memory |
| 0.44% | `python` | `list_dealloc` | memory |
| 0.43% | `python` | `PyList_New.constprop.0` | memory |
| 0.42% | `[unknown]` | `0xffffffffab600151` | unknown |
| 0.40% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.40% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.39% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.38% | `python` | `insertdict` | dict |
| 0.38% | `libc.so.6` | `malloc` | libc |
| 0.37% | `libc.so.6` | `__gconv_transform_utf8_internal` | libc |
| 0.36% | `python` | `PyUnicode_Contains` | str |
| 0.36% | `python` | `PyType_IsSubtype` | dynamic |
| 0.36% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.34% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.34% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.33% | `[unknown]` | `0xffffffffab60010f` | unknown |
| 0.33% | `python` | `PyUnicode_New.part.0` | memory |
| 0.32% | `python` | `dict_dealloc` | memory |
| 0.32% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.32% | `python` | `_PyGC_Collect` | gc |
| 0.31% | `python` | `new_dict` | dict |
| 0.31% | `python` | `_PyObject_Realloc` | memory |
| 0.30% | `python` | `sre_ucs1_match` | library |
| 0.29% | `python` | `replace` | str |
| 0.28% | `python` | `visit_decref` | gc |
| 0.28% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.27% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.26% | `[unknown]` | `0xffffffffab6001bd` | unknown |
| 0.26% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.25% | `python` | `insert_to_emptydict` | dict |
| 0.25% | `python` | `PyObject_Call` | dynamic |

## argparse_subparsers

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.68% | `[JIT]` | `jit` | jit |
| 7.41% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.56% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.20% | `python` | `_PyObject_Malloc` | memory |
| 3.03% | `python` | `_Py_dict_lookup` | lookup |
| 2.53% | `python` | `_PyObject_Free` | memory |
| 2.20% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.96% | `python` | `_Py_Dealloc` | memory |
| 1.84% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.76% | `python` | `initialize_locals` | interpreter |
| 1.15% | `python` | `gc_collect_region` | gc |
| 1.12% | `python` | `visit_add_to_container` | gc |
| 1.09% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.94% | `python` | `PyDict_GetItemRef` | dict |
| 0.93% | `libc.so.6` | `_int_malloc` | libc |
| 0.86% | `python` | `long_to_decimal_string_internal` | int |
| 0.82% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.74% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.74% | `python` | `insertdict` | dict |
| 0.65% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.61% | `python` | `tuple_dealloc` | memory |
| 0.58% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.57% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.56% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.56% | `python` | `find_name_in_mro` | lookup |
| 0.55% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.54% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.51% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.50% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.50% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.48% | `python` | `tuple_alloc` | memory |
| 0.48% | `python` | `_Py_BuildString_StackRefSteal` | unknown |
| 0.48% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.48% | `python` | `sre_ucs1_match` | library |
| 0.47% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.46% | `python` | `PyType_IsSubtype` | dynamic |
| 0.45% | `python` | `PyList_New.constprop.0` | memory |
| 0.44% | `libc.so.6` | `malloc` | libc |
| 0.44% | `python` | `visit_decref` | gc |
| 0.41% | `python` | `pattern_new_match` | memory |
| 0.40% | `python` | `PyUnicode_Contains` | str |
| 0.39% | `python` | `PyUnicode_Format` | str |
| 0.37% | `python` | `_Py_NewReference` | memory |
| 0.36% | `python` | `set_add_entry_takeref` | miscobj |
| 0.36% | `python` | `list_dealloc` | memory |
| 0.34% | `python` | `_PyGC_Collect` | gc |
| 0.34% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.34% | `python` | `dict_get` | dict |
| 0.34% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.32% | `python` | `PyObject_Str` | dynamic |
| 0.31% | `python` | `PyUnicode_New.part.0` | memory |
| 0.31% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.30% | `python` | `PyObject_Hash` | dynamic |
| 0.30% | `python` | `insert_to_emptydict` | dict |
| 0.29% | `python` | `clone_combined_dict_keys` | unknown |
| 0.29% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.28% | `python` | `siphash13` | str |
| 0.28% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.28% | `python` | `unicode_dealloc` | memory |
| 0.28% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.28% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.27% | `python` | `PyDict_Contains` | dict |
| 0.27% | `libc.so.6` | `_int_free` | libc |
| 0.27% | `python` | `PyMethod_New` | memory |
| 0.26% | `python` | `_PyEval_Vector` | interpreter |
| 0.26% | `python` | `_PyUnicode_XStrip` | str |
| 0.26% | `python` | `PyDict_Next` | dict |
| 0.26% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.26% | `python` | `PyObject_VisitManagedDict` | dynamic |

## async_generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.88% | `[JIT]` | `jit` | jit |
| 7.21% | `python` | `_Py_Dealloc` | memory |
| 3.63% | `python` | `_PyObject_Free` | memory |
| 3.30% | `python` | `_PyObject_Malloc` | memory |
| 3.28% | `python` | `async_gen_asend_iternext` | async |
| 2.56% | `python` | `async_gen_anext` | async |
| 2.24% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 2.17% | `python` | `async_gen_asend_dealloc` | memory |
| 2.14% | `python` | `_PyType_AllocNoTrack` | memory |
| 1.84% | `python` | `PyErr_ExceptionMatches` | exceptions |
| 1.78% | `python` | `PyType_GenericAlloc` | memory |
| 1.64% | `python` | `tuple_dealloc` | memory |
| 1.47% | `python` | `_PyGen_FetchStopIterationValue` | miscobj |
| 1.46% | `python` | `_PyAsyncGenValueWrapperNew` | memory |
| 1.45% | `python` | `_PyErr_ExceptionMatches` | exceptions |
| 1.44% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.44% | `python` | `StopIteration_dealloc` | memory |
| 1.37% | `python` | `type_call` | dynamic |
| 1.34% | `python` | `PyObject_CallOneArg` | dynamic |
| 1.32% | `python` | `async_gen_wrapped_val_dealloc` | memory |
| 1.24% | `python` | `_Py_NewReference` | memory |
| 1.23% | `python` | `PyTuple_FromArray` | tuple |
| 0.96% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.92% | `python` | `StopIteration_init` | dynamic |
| 0.85% | `python` | `PyType_IsSubtype` | dynamic |
| 0.83% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.82% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.81% | `python` | `BaseException_new` | memory |
| 0.76% | `python` | `tuple_alloc` | memory |
| 0.75% | `python` | `initialize_locals` | interpreter |
| 0.70% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.70% | `python` | `visit_add_to_container` | gc |
| 0.68% | `python` | `PyObject_GC_Del` | gc |
| 0.60% | `python` | `make_range_object` | unknown |
| 0.58% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.57% | `python` | `_PyEval_GetANext` | interpreter |
| 0.56% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.45% | `python` | `_PyLong_FromMedium` | int |
| 0.43% | `python` | `PyErr_SetRaisedException` | exceptions |
| 0.42% | `python` | `PyIter_Check` | dynamic |
| 0.40% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.40% | `python` | `_PyEval_Vector` | interpreter |
| 0.39% | `python` | `_PyEval_MonitorRaise` | interpreter |
| 0.39% | `python` | `range_subscript` | miscobj |
| 0.38% | `python` | `PyNumber_Add` | dynamic |
| 0.37% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.36% | `python` | `long_richcompare` | int |
| 0.36% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.35% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.35% | `python` | `set_add_entry_takeref` | miscobj |
| 0.34% | `python` | `PyObject_Malloc` | dynamic |
| 0.34% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.33% | `python` | `PySlice_New` | memory |
| 0.33% | `python` | `gen_dealloc` | memory |
| 0.31% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.26% | `python` | `PyErr_GetRaisedException` | exceptions |
| 0.26% | `python` | `PyObject_ClearManagedDict` | dynamic |

## async_tree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.55% | `[JIT]` | `jit` | jit |
| 6.93% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.24% | `python` | `visit_add_to_container` | gc |
| 3.59% | `python` | `_PyObject_Malloc` | memory |
| 3.40% | `python` | `_PyGC_Collect` | gc |
| 2.17% | `python` | `gc_collect_region` | gc |
| 2.10% | `python` | `_PyObject_Free` | memory |
| 2.06% | `python` | `initialize_locals` | interpreter |
| 2.04% | `python` | `_Py_Dealloc` | memory |
| 2.02% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.64% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.38% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.25% | `python` | `context_tp_dealloc` | memory |
| 1.20% | `python` | `mark_all_reachable` | unknown |
| 1.19% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.17% | `python` | `subtype_dealloc` | memory |
| 1.16% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.03% | `python` | `visit_reachable` | gc |
| 0.97% | `python` | `_PyEval_Vector` | interpreter |
| 0.73% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.72% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.68% | `python` | `gen_dealloc` | memory |
| 0.62% | `python` | `visit_decref` | gc |
| 0.59% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.54% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.53% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.50% | `python` | `tuple_dealloc` | memory |
| 0.49% | `python` | `_PyObject_Realloc` | memory |
| 0.48% | `python` | `subtype_traverse` | gc |
| 0.48% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.46% | `python` | `_Py_dict_lookup` | lookup |
| 0.46% | `python` | `_PyObject_GC_New` | gc |
| 0.45% | `python` | `insert_to_emptydict` | dict |
| 0.44% | `python` | `PyCMethod_New` | memory |
| 0.44% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.43% | `python` | `list_dealloc` | memory |
| 0.43% | `python` | `tuple_alloc` | memory |
| 0.42% | `python` | `_PyObject_Calloc` | memory |
| 0.42% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.40% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.40% | `python` | `PyIter_Send` | dynamic |
| 0.40% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.39% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.38% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.36% | `python` | `task_step_impl` | unknown |
| 0.35% | `python` | `_PyType_GetDict` | dynamic |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.35% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.35% | `python` | `_Py_NewReference` | memory |
| 0.34% | `python` | `PyTuple_FromArray` | tuple |
| 0.34% | `python` | `TaskObj_clear` | unknown |
| 0.33% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.33% | `python` | `_PyMember_GetOffset` | unknown |
| 0.33% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.33% | `python` | `PyUnicode_RichCompare` | str |
| 0.32% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.32% | `python` | `_asyncio_Task___init__` | unknown |
| 0.31% | `python` | `PyObject_Call` | dynamic |
| 0.30% | `python` | `TaskObj_traverse` | gc |
| 0.30% | `python` | `PyList_New` | memory |
| 0.30% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.29% | `python` | `PyContext_CopyCurrent` | unknown |
| 0.28% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.27% | `python` | `PyType_GenericAlloc` | memory |
| 0.27% | `python` | `list_extend_lock_held` | list |
| 0.27% | `python` | `dict_dealloc` | memory |
| 0.27% | `python` | `PyDict_GetItemRef` | dict |
| 0.26% | `[unknown]` | `0xffffffffab60128c` | unknown |

## async_tree_cpu_io_mixed

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.47% | `python` | `k_mul` | int |
| 10.14% | `[JIT]` | `jit` | jit |
| 5.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.18% | `python` | `_PyObject_Malloc` | memory |
| 2.98% | `python` | `_PyObject_Free` | memory |
| 2.70% | `python` | `PyErr_CheckSignals` | exceptions |
| 2.68% | `python` | `visit_add_to_container` | gc |
| 2.17% | `python` | `_Py_Dealloc` | memory |
| 2.09% | `python` | `_PyGC_Collect` | gc |
| 1.62% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.53% | `python` | `gc_collect_region` | gc |
| 1.43% | `_math_integer.cpython-315-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.41% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.10% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.08% | `python` | `initialize_locals` | interpreter |
| 1.00% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.84% | `python` | `PyThread_get_thread_ident` | threading |
| 0.83% | `python` | `_Py_IsMainThread` | unknown |
| 0.82% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.72% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.72% | `python` | `visit_reachable` | gc |
| 0.67% | `python` | `context_tp_dealloc` | memory |
| 0.63% | `python` | `_PyEval_Vector` | interpreter |
| 0.62% | `python` | `mark_all_reachable` | unknown |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.60% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.53% | `python` | `PyNumber_Multiply` | dynamic |
| 0.53% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.48% | `python` | `long_alloc` | memory |
| 0.47% | `python` | `gen_dealloc` | memory |
| 0.47% | `python` | `visit_decref` | gc |
| 0.46% | `python` | `subtype_dealloc` | memory |
| 0.43% | `python` | `long_lshift1` | int |
| 0.40% | `python` | `_Py_NewReference` | memory |
| 0.40% | `python` | `long_mul` | int |
| 0.38% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.35% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.33% | `python` | `long_dealloc` | memory |
| 0.32% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.32% | `python` | `_PyInterpreterState_Main` | unknown |
| 0.31% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.30% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.30% | `python` | `_Py_dict_lookup` | lookup |
| 0.29% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.29% | `python` | `subtype_traverse` | gc |
| 0.29% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.28% | `python` | `pthread_self@plt` | unknown |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.25% | `python` | `_PyThreadState_PopFrame` | threading |

## async_tree_cpu_io_mixed_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.41% | `python` | `k_mul` | int |
| 10.17% | `[JIT]` | `jit` | jit |
| 4.70% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.05% | `python` | `_PyObject_Malloc` | memory |
| 3.66% | `python` | `visit_add_to_container` | gc |
| 3.00% | `python` | `_PyObject_Free` | memory |
| 2.65% | `python` | `PyErr_CheckSignals` | exceptions |
| 2.43% | `python` | `_PyGC_Collect` | gc |
| 2.38% | `python` | `_Py_Dealloc` | memory |
| 1.53% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.40% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.38% | `_math_integer.cpython-315-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.11% | `python` | `gc_collect_region` | gc |
| 1.07% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.04% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.86% | `python` | `PyThread_get_thread_ident` | threading |
| 0.84% | `python` | `_Py_IsMainThread` | unknown |
| 0.83% | `python` | `initialize_locals` | interpreter |
| 0.82% | `python` | `mark_all_reachable` | unknown |
| 0.81% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.66% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.66% | `python` | `_PyEval_Vector` | interpreter |
| 0.61% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.58% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.57% | `python` | `visit_reachable` | gc |
| 0.54% | `python` | `PyNumber_Multiply` | dynamic |
| 0.51% | `python` | `long_alloc` | memory |
| 0.48% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.47% | `python` | `visit_decref` | gc |
| 0.46% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.46% | `python` | `long_lshift1` | int |
| 0.45% | `python` | `long_mul` | int |
| 0.44% | `python` | `subtype_dealloc` | memory |
| 0.41% | `python` | `_Py_NewReference` | memory |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.33% | `python` | `gen_dealloc` | memory |
| 0.33% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.33% | `python` | `long_dealloc` | memory |
| 0.32% | `python` | `_PyInterpreterState_Main` | unknown |
| 0.31% | `python` | `pthread_self@plt` | unknown |
| 0.30% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.29% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.28% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.28% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.27% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.27% | `python` | `subtype_traverse` | gc |
| 0.26% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.25% | `python` | `tuple_dealloc` | memory |

## async_tree_io

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.69% | `[JIT]` | `jit` | jit |
| 9.36% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.62% | `python` | `_PyGC_Collect` | gc |
| 5.14% | `python` | `visit_add_to_container` | gc |
| 3.31% | `python` | `gc_collect_region` | gc |
| 2.70% | `python` | `_PyObject_Malloc` | memory |
| 2.12% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.05% | `python` | `initialize_locals` | interpreter |
| 1.70% | `python` | `_Py_Dealloc` | memory |
| 1.66% | `python` | `_PyObject_Free` | memory |
| 1.59% | `python` | `visit_reachable` | gc |
| 1.51% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.50% | `python` | `_PyEval_Vector` | interpreter |
| 1.36% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.25% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.23% | `python` | `visit_decref` | gc |
| 1.07% | `_heapq.cpython-315-x86_64-linux-gnu.so` | `siftup` | library |
| 1.07% | `python` | `mark_all_reachable` | unknown |
| 1.07% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.83% | `python` | `subtype_dealloc` | memory |
| 0.83% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.64% | `python` | `subtype_traverse` | gc |
| 0.62% | `python` | `context_tp_dealloc` | memory |
| 0.60% | `python` | `slot_tp_richcompare` | dynamic |
| 0.60% | `python` | `gen_dealloc` | memory |
| 0.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.48% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.48% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.48% | `python` | `tuple_dealloc` | memory |
| 0.48% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.47% | `python` | `_PyObject_Realloc` | memory |
| 0.44% | `python` | `PyDict_GetItemRef` | dict |
| 0.43% | `python` | `tuple_alloc` | memory |
| 0.42% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.42% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.41% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.39% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.39% | `python` | `insert_to_emptydict` | dict |
| 0.39% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.37% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.37% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.37% | `python` | `_PyObject_Calloc` | memory |
| 0.35% | `python` | `_Py_dict_lookup` | lookup |
| 0.34% | `python` | `PyTuple_FromArray` | tuple |
| 0.34% | `python` | `PyCMethod_New` | memory |
| 0.33% | `python` | `_PyMember_GetOffset` | unknown |
| 0.33% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.32% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.31% | `python` | `PyIter_Send` | dynamic |
| 0.31% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.29% | `python` | `_Py_NewReference` | memory |
| 0.28% | `python` | `_PyObject_GC_New` | gc |
| 0.28% | `python` | `list_extend_lock_held` | list |
| 0.28% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.27% | `python` | `task_step_impl` | unknown |
| 0.27% | `python` | `PyObject_Call` | dynamic |
| 0.27% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.26% | `python` | `_PyType_GetDict` | dynamic |
| 0.26% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.26% | `python` | `allocate_from_new_pool` | memory |
| 0.25% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |

## async_tree_io_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.60% | `[JIT]` | `jit` | jit |
| 8.74% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.55% | `python` | `visit_add_to_container` | gc |
| 5.64% | `python` | `_PyGC_Collect` | gc |
| 2.82% | `python` | `_PyObject_Malloc` | memory |
| 2.63% | `python` | `gc_collect_region` | gc |
| 2.06% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.88% | `python` | `_PyEval_Vector` | interpreter |
| 1.87% | `python` | `initialize_locals` | interpreter |
| 1.83% | `python` | `_Py_Dealloc` | memory |
| 1.77% | `python` | `_PyObject_Free` | memory |
| 1.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.46% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.42% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.41% | `python` | `visit_reachable` | gc |
| 1.29% | `python` | `mark_all_reachable` | unknown |
| 1.21% | `python` | `visit_decref` | gc |
| 1.06% | `_heapq.cpython-315-x86_64-linux-gnu.so` | `siftup` | library |
| 0.93% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.84% | `python` | `subtype_dealloc` | memory |
| 0.81% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.61% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.58% | `python` | `subtype_traverse` | gc |
| 0.58% | `python` | `gen_dealloc` | memory |
| 0.57% | `python` | `slot_tp_richcompare` | dynamic |
| 0.52% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.51% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.51% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.51% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.46% | `python` | `tuple_dealloc` | memory |
| 0.45% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.45% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.44% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.40% | `python` | `_PyObject_Realloc` | memory |
| 0.39% | `python` | `PyDict_GetItemRef` | dict |
| 0.39% | `python` | `tuple_alloc` | memory |
| 0.38% | `python` | `PyObject_Call` | dynamic |
| 0.37% | `python` | `_PyObject_Calloc` | memory |
| 0.36% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.36% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.34% | `python` | `PyTuple_FromArray` | tuple |
| 0.34% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.33% | `python` | `_PyMember_GetOffset` | unknown |
| 0.32% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.32% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.32% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.31% | `python` | `PyIter_Send` | dynamic |
| 0.30% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.30% | `python` | `gen_traverse` | gc |
| 0.29% | `python` | `_Py_NewReference` | memory |
| 0.29% | `python` | `insert_to_emptydict` | dict |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.28% | `python` | `PyCMethod_New` | memory |
| 0.28% | `[unknown]` | `0xffffffffab44a16e` | unknown |
| 0.27% | `[unknown]` | `0xffffffffab601631` | unknown |
| 0.26% | `[unknown]` | `0xffffffffab6011a9` | unknown |
| 0.26% | `python` | `PyList_New` | memory |
| 0.26% | `python` | `allocate_from_new_pool` | memory |
| 0.25% | `python` | `_PyObject_GC_New` | gc |
| 0.25% | `python` | `_PyType_GetDict` | dynamic |

## async_tree_memoization

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.46% | `[JIT]` | `jit` | jit |
| 9.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.72% | `python` | `visit_add_to_container` | gc |
| 4.20% | `python` | `_PyGC_Collect` | gc |
| 3.49% | `python` | `_PyObject_Malloc` | memory |
| 3.25% | `python` | `gc_collect_region` | gc |
| 2.08% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.06% | `python` | `initialize_locals` | interpreter |
| 1.98% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.92% | `python` | `_Py_Dealloc` | memory |
| 1.88% | `python` | `_PyObject_Free` | memory |
| 1.46% | `python` | `visit_reachable` | gc |
| 1.36% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.35% | `python` | `context_tp_dealloc` | memory |
| 1.34% | `python` | `_PyEval_Vector` | interpreter |
| 1.11% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.05% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.04% | `python` | `mark_all_reachable` | unknown |
| 0.97% | `python` | `visit_decref` | gc |
| 0.91% | `python` | `subtype_dealloc` | memory |
| 0.67% | `python` | `gen_dealloc` | memory |
| 0.65% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.63% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.59% | `python` | `subtype_traverse` | gc |
| 0.56% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.52% | `python` | `_Py_dict_lookup` | lookup |
| 0.49% | `python` | `tuple_alloc` | memory |
| 0.48% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.47% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.46% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.46% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `PyIter_Send` | dynamic |
| 0.43% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.41% | `python` | `_PyObject_Realloc` | memory |
| 0.41% | `python` | `list_dealloc` | memory |
| 0.40% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.40% | `python` | `_PyObject_GC_New` | gc |
| 0.40% | `python` | `insert_to_emptydict` | dict |
| 0.39% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.38% | `python` | `list_extend_lock_held` | list |
| 0.37% | `python` | `_PyObject_Calloc` | memory |
| 0.37% | `python` | `PyCMethod_New` | memory |
| 0.35% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `python` | `PyUnicode_RichCompare` | str |
| 0.34% | `python` | `PyTuple_FromArray` | tuple |
| 0.33% | `python` | `task_step_impl` | unknown |
| 0.33% | `python` | `_PyType_GetDict` | dynamic |
| 0.32% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.32% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.32% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.32% | `python` | `TaskObj_clear` | unknown |
| 0.31% | `python` | `TaskObj_traverse` | gc |
| 0.31% | `python` | `PyDict_GetItemRef` | dict |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.29% | `python` | `_PyMember_GetOffset` | unknown |
| 0.28% | `python` | `PyObject_Call` | dynamic |
| 0.28% | `python` | `PyContext_CopyCurrent` | unknown |
| 0.27% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.27% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.26% | `python` | `_asyncio_Task___init__` | unknown |
| 0.25% | `python` | `context_run` | unknown |

## async_tree_memoization_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.82% | `[JIT]` | `jit` | jit |
| 8.35% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.20% | `python` | `visit_add_to_container` | gc |
| 5.15% | `python` | `_PyGC_Collect` | gc |
| 3.32% | `python` | `_PyObject_Malloc` | memory |
| 2.66% | `python` | `gc_collect_region` | gc |
| 2.13% | `python` | `_Py_Dealloc` | memory |
| 2.02% | `python` | `PyObject_GC_UnTrack` | gc |
| 2.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.98% | `python` | `_PyObject_Free` | memory |
| 1.57% | `python` | `initialize_locals` | interpreter |
| 1.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.39% | `python` | `_PyEval_Vector` | interpreter |
| 1.34% | `python` | `visit_reachable` | gc |
| 1.30% | `python` | `mark_all_reachable` | unknown |
| 1.15% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.13% | `python` | `visit_decref` | gc |
| 0.95% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.88% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.83% | `python` | `subtype_dealloc` | memory |
| 0.65% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.60% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.59% | `python` | `gen_dealloc` | memory |
| 0.58% | `python` | `subtype_traverse` | gc |
| 0.57% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.52% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.48% | `python` | `context_tp_dealloc` | memory |
| 0.43% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.42% | `python` | `tuple_dealloc` | memory |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.41% | `python` | `tuple_alloc` | memory |
| 0.38% | `python` | `PyIter_Send` | dynamic |
| 0.38% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.38% | `python` | `_PyObject_Calloc` | memory |
| 0.37% | `python` | `TaskObj_traverse` | gc |
| 0.37% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.36% | `python` | `set_lookkey` | miscobj |
| 0.35% | `python` | `PyObject_Call` | dynamic |
| 0.34% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.34% | `python` | `PyUnicode_RichCompare` | str |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.33% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.33% | `python` | `_Py_NewReference` | memory |
| 0.33% | `python` | `dict_dealloc` | memory |
| 0.32% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.32% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.32% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.32% | `python` | `_PyMember_GetOffset` | unknown |
| 0.32% | `python` | `_PyObject_GC_New` | gc |
| 0.31% | `python` | `TaskObj_clear` | unknown |
| 0.31% | `python` | `_asyncio_Task___init__` | unknown |
| 0.31% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `python` | `_Py_dict_lookup` | lookup |
| 0.29% | `python` | `_PyObject_VectorcallPrepend` | dynamic |
| 0.29% | `python` | `PyCMethod_New` | memory |
| 0.28% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `PyType_GenericAlloc` | memory |
| 0.28% | `python` | `PyDict_New` | memory |
| 0.27% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.27% | `python` | `set_traverse` | gc |
| 0.27% | `python` | `insert_to_emptydict` | dict |
| 0.26% | `python` | `allocate_from_new_pool` | memory |
| 0.25% | `python` | `task_step_impl` | unknown |

## async_tree_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.70% | `[JIT]` | `jit` | jit |
| 6.66% | `python` | `visit_add_to_container` | gc |
| 5.26% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.11% | `python` | `_PyGC_Collect` | gc |
| 3.72% | `python` | `_PyObject_Malloc` | memory |
| 2.52% | `python` | `gc_collect_region` | gc |
| 2.15% | `python` | `_PyObject_Free` | memory |
| 2.12% | `python` | `_Py_Dealloc` | memory |
| 1.91% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.65% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.58% | `python` | `initialize_locals` | interpreter |
| 1.46% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.21% | `python` | `visit_reachable` | gc |
| 1.18% | `python` | `mark_all_reachable` | unknown |
| 1.16% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.09% | `python` | `_PyEval_Vector` | interpreter |
| 0.97% | `python` | `visit_decref` | gc |
| 0.95% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.95% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.89% | `python` | `subtype_dealloc` | memory |
| 0.74% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.70% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.60% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.60% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.58% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.54% | `python` | `subtype_traverse` | gc |
| 0.54% | `python` | `gen_dealloc` | memory |
| 0.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.43% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.41% | `python` | `_PyObject_Calloc` | memory |
| 0.40% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.40% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.39% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.38% | `python` | `_PyObject_VectorcallPrepend` | dynamic |
| 0.38% | `python` | `PyObject_Call` | dynamic |
| 0.37% | `python` | `_Py_NewReference` | memory |
| 0.37% | `python` | `_asyncio_Task___init__` | unknown |
| 0.36% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.36% | `[unknown]` | `0xffffffffab44a16e` | unknown |
| 0.36% | `python` | `PyUnicode_RichCompare` | str |
| 0.36% | `python` | `TaskObj_traverse` | gc |
| 0.35% | `python` | `_PyObject_GC_New` | gc |
| 0.35% | `[unknown]` | `0xffffffffab601631` | unknown |
| 0.35% | `[unknown]` | `0xffffffffab6011a9` | unknown |
| 0.35% | `python` | `tuple_alloc` | memory |
| 0.35% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.34% | `python` | `dict_dealloc` | memory |
| 0.33% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.33% | `python` | `allocate_from_new_pool` | memory |
| 0.33% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.33% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.33% | `python` | `PyDict_New` | memory |
| 0.33% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.32% | `python` | `context_tp_dealloc` | memory |
| 0.32% | `python` | `PyIter_Send` | dynamic |
| 0.31% | `python` | `PyType_GenericAlloc` | memory |
| 0.31% | `python` | `PyCMethod_New` | memory |
| 0.29% | `python` | `_PyMember_GetOffset` | unknown |
| 0.28% | `python` | `set_traverse` | gc |
| 0.28% | `python` | `new_dict` | dict |
| 0.26% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.26% | `python` | `PyList_New` | memory |
| 0.26% | `python` | `insert_to_emptydict` | dict |
| 0.26% | `python` | `make_gen` | miscobj |
| 0.26% | `python` | `task_step_impl` | unknown |
| 0.25% | `python` | `PyTuple_FromArray` | tuple |

## asyncio_tcp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.36% | `[unknown]` | `0xffffffff939cb32a` | unknown |
| 8.00% | `[unknown]` | `0xffffffff939cac57` | unknown |
| 7.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.59% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.78% | `[unknown]` | `0xffffffff93c001c6` | unknown |
| 0.74% | `[JIT]` | `jit` | jit |
| 0.47% | `[unknown]` | `0xffffffff92ce5d2b` | unknown |
| 0.36% | `[unknown]` | `0xffffffff92c57dd9` | unknown |
| 0.35% | `[unknown]` | `0xffffffff92c532de` | unknown |
| 0.34% | `[unknown]` | `0xffffffff93c00151` | unknown |
| 0.32% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.31% | `[unknown]` | `0xffffffff93c0010f` | unknown |
| 0.31% | `python` | `_PyObject_Malloc` | memory |
| 0.29% | `python` | `_Py_Dealloc` | memory |

## asyncio_tcp_ssl

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.66% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 11.14% | `[unknown]` | `0xffffffff939cb32a` | unknown |
| 3.29% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 2.89% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.44% | `[unknown]` | `0xffffffff939cac57` | unknown |
| 0.77% | `libcrypto.so.3` | `0x00000000002dcb4e` | libc |
| 0.54% | `[JIT]` | `jit` | jit |
| 0.53% | `libcrypto.so.3` | `0x00000000002dcb90` | libc |
| 0.53% | `libc.so.6` | `__strcmp_avx2` | libc |
| 0.44% | `libcrypto.so.3` | `0x00000000002dcb62` | libc |
| 0.43% | `libcrypto.so.3` | `0x00000000002dcb8b` | libc |
| 0.39% | `libcrypto.so.3` | `0x00000000002dcb9a` | libc |
| 0.38% | `libcrypto.so.3` | `0x00000000002dcb9f` | libc |
| 0.36% | `libcrypto.so.3` | `0x00000000002dcc92` | libc |
| 0.36% | `libcrypto.so.3` | `0x00000000002dcbae` | libc |
| 0.36% | `libcrypto.so.3` | `0x00000000002dcb95` | libc |
| 0.35% | `libcrypto.so.3` | `0x00000000002dc8cf` | libc |
| 0.35% | `libcrypto.so.3` | `0x00000000002dcabc` | libc |
| 0.34% | `libcrypto.so.3` | `0x00000000002dc8da` | libc |
| 0.34% | `libcrypto.so.3` | `0x00000000002dcd13` | libc |
| 0.34% | `libcrypto.so.3` | `0x00000000002dcac7` | libc |
| 0.34% | `libcrypto.so.3` | `0x00000000002dc9e6` | libc |
| 0.33% | `libc.so.6` | `_int_malloc` | libc |
| 0.33% | `libcrypto.so.3` | `0x00000000002dcba4` | libc |
| 0.32% | `libcrypto.so.3` | `0x00000000002dcd01` | libc |
| 0.31% | `libcrypto.so.3` | `0x00000000002dccd2` | libc |
| 0.31% | `libcrypto.so.3` | `0x00000000002dcc6a` | libc |
| 0.31% | `libcrypto.so.3` | `0x00000000002dcba9` | libc |
| 0.31% | `libcrypto.so.3` | `0x00000000002dccee` | libc |
| 0.30% | `libcrypto.so.3` | `0x00000000002dcc40` | libc |
| 0.30% | `libcrypto.so.3` | `0x00000000002dcc7e` | libc |
| 0.30% | `libcrypto.so.3` | `0x00000000002dcb44` | libc |
| 0.29% | `libcrypto.so.3` | `0x00000000002dcc74` | libc |
| 0.29% | `libcrypto.so.3` | `0x00000000002dcc9d` | libc |
| 0.29% | `libcrypto.so.3` | `0x00000000002dc899` | libc |
| 0.29% | `libcrypto.so.3` | `0x00000000002dcb5d` | libc |
| 0.28% | `libcrypto.so.3` | `0x00000000002dccaf` | libc |
| 0.28% | `libcrypto.so.3` | `0x00000000002dccc4` | libc |
| 0.28% | `libcrypto.so.3` | `0x00000000002dc96a` | libc |
| 0.28% | `libcrypto.so.3` | `0x00000000002dc861` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dcc51` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc994` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc979` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dcb6c` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dcbc7` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dca79` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dca12` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc9f0` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dcb18` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc9aa` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dca4e` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc825` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc84c` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc888` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dc92c` | libc |
| 0.27% | `libcrypto.so.3` | `0x00000000002dca8c` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc83b` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc876` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dccdb` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dca59` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc8c4` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc956` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dca25` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dcab3` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dcade` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dca68` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc812` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dcd25` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dca9f` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc904` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc989` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc8ef` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dcb2c` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc942` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dcb22` | libc |
| 0.26% | `libcrypto.so.3` | `0x00000000002dc8af` | libc |
| 0.25% | `libcrypto.so.3` | `0x00000000002dcaf1` | libc |
| 0.25% | `libcrypto.so.3` | `0x00000000002dc9be` | libc |
| 0.25% | `libcrypto.so.3` | `0x00000000002dca39` | libc |
| 0.25% | `libcrypto.so.3` | `0x00000000002dc9d2` | libc |
| 0.25% | `libcrypto.so.3` | `0x00000000002dca01` | libc |

## asyncio_websockets

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 4.96% | `libz.so.1.3` | `0x0000000000008c1c` | library |
| 3.76% | `libz.so.1.3` | `0x0000000000008c20` | library |
| 3.63% | `libz.so.1.3` | `0x0000000000002dba` | library |
| 3.59% | `libz.so.1.3` | `0x0000000000002db1` | library |
| 3.59% | `libz.so.1.3` | `0x0000000000002da3` | library |
| 3.52% | `libz.so.1.3` | `0x0000000000002db6` | library |
| 3.49% | `libz.so.1.3` | `0x0000000000002dc6` | library |
| 3.46% | `libz.so.1.3` | `0x0000000000008bf7` | library |
| 3.37% | `libz.so.1.3` | `0x0000000000002dae` | library |
| 2.38% | `libz.so.1.3` | `0x0000000000008c25` | library |
| 2.36% | `libz.so.1.3` | `0x0000000000008be6` | library |
| 2.27% | `libz.so.1.3` | `0x0000000000008192` | library |
| 2.22% | `libz.so.1.3` | `0x00000000000082aa` | library |
| 2.00% | `libz.so.1.3` | `0x0000000000008c2c` | library |
| 1.98% | `libz.so.1.3` | `0x0000000000008bd6` | library |
| 1.96% | `libz.so.1.3` | `0x0000000000008bed` | library |
| 1.85% | `libz.so.1.3` | `0x0000000000008c07` | library |
| 1.82% | `libz.so.1.3` | `0x00000000000082b7` | library |
| 1.79% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.77% | `libz.so.1.3` | `0x000000000000819f` | library |
| 1.72% | `libz.so.1.3` | `0x0000000000008c18` | library |
| 1.46% | `libz.so.1.3` | `0x0000000000008c2f` | library |
| 1.42% | `libz.so.1.3` | `0x0000000000008bf1` | library |
| 1.41% | `libz.so.1.3` | `0x0000000000008c0a` | library |
| 1.41% | `libz.so.1.3` | `0x0000000000008bdf` | library |
| 1.39% | `libz.so.1.3` | `0x0000000000008bfa` | library |
| 1.10% | `libz.so.1.3` | `0x0000000000008c01` | library |
| 1.03% | `libz.so.1.3` | `0x0000000000008bd0` | library |
| 0.98% | `libz.so.1.3` | `0x0000000000008c2a` | library |
| 0.97% | `libz.so.1.3` | `0x0000000000008c14` | library |
| 0.94% | `libz.so.1.3` | `0x0000000000008c0e` | library |
| 0.92% | `libz.so.1.3` | `0x0000000000008140` | library |
| 0.91% | `libz.so.1.3` | `0x000000000000829a` | library |
| 0.90% | `libz.so.1.3` | `0x0000000000008279` | library |
| 0.90% | `libz.so.1.3` | `0x0000000000008258` | library |
| 0.90% | `libz.so.1.3` | `0x0000000000008267` | library |
| 0.89% | `libz.so.1.3` | `0x0000000000008161` | library |
| 0.88% | `libz.so.1.3` | `0x000000000000828a` | library |
| 0.87% | `libz.so.1.3` | `0x0000000000008182` | library |
| 0.86% | `libz.so.1.3` | `0x0000000000008172` | library |
| 0.86% | `libz.so.1.3` | `0x000000000000814f` | library |
| 0.64% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.55% | `libz.so.1.3` | `0x0000000000002416` | library |
| 0.53% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.53% | `libz.so.1.3` | `0x0000000000002419` | library |
| 0.51% | `libz.so.1.3` | `0x000000000000242e` | library |
| 0.48% | `libz.so.1.3` | `0x00000000000082ae` | library |
| 0.48% | `libz.so.1.3` | `0x00000000000023f4` | library |
| 0.47% | `libz.so.1.3` | `0x0000000000008196` | library |
| 0.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.40% | `libz.so.1.3` | `0x0000000000008be3` | library |
| 0.40% | `libz.so.1.3` | `0x0000000000008c37` | library |
| 0.40% | `libz.so.1.3` | `0x0000000000008c28` | library |
| 0.39% | `libz.so.1.3` | `0x0000000000008bfe` | library |
| 0.37% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.36% | `libz.so.1.3` | `0x0000000000002403` | library |
| 0.36% | `[unknown]` | `0xffffffffab6011a9` | unknown |
| 0.34% | `libz.so.1.3` | `0x000000000000825c` | library |
| 0.34% | `libz.so.1.3` | `0x0000000000008165` | library |
| 0.33% | `libz.so.1.3` | `0x000000000000828e` | library |
| 0.33% | `libz.so.1.3` | `0x00000000000082bb` | library |
| 0.33% | `libz.so.1.3` | `0x0000000000008186` | library |
| 0.33% | `libz.so.1.3` | `0x00000000000081a3` | library |
| 0.32% | `libz.so.1.3` | `0x000000000000826c` | library |
| 0.32% | `[unknown]` | `0xffffffffab601631` | unknown |
| 0.32% | `libz.so.1.3` | `0x0000000000008144` | library |
| 0.31% | `libz.so.1.3` | `0x000000000000827d` | library |
| 0.31% | `libz.so.1.3` | `0x0000000000008176` | library |
| 0.31% | `libz.so.1.3` | `0x000000000000829e` | library |
| 0.31% | `libz.so.1.3` | `0x0000000000008154` | library |
| 0.27% | `[unknown]` | `0xffffffffab44a16e` | unknown |

## base64

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 11.93% | `[JIT]` | `jit` | jit |
| 7.56% | `binascii.cpython-315-x86_64-linux-gnu.so` | `binascii_a2b_ascii85` | library |
| 7.45% | `binascii.cpython-315-x86_64-linux-gnu.so` | `binascii_a2b_base85` | library |
| 5.70% | `binascii.cpython-315-x86_64-linux-gnu.so` | `binascii_a2b_base64` | library |
| 4.80% | `binascii.cpython-315-x86_64-linux-gnu.so` | `binascii_b2a_base64` | library |
| 3.75% | `python` | `bytes_translate_impl` | str |
| 3.69% | `binascii.cpython-315-x86_64-linux-gnu.so` | `binascii_b2a_ascii85` | library |
| 3.65% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.27% | `python` | `_PyObject_Malloc` | memory |
| 3.11% | `python` | `_PyObject_Free` | memory |
| 3.05% | `binascii.cpython-315-x86_64-linux-gnu.so` | `binascii_b2a_base85` | library |
| 2.68% | `python` | `_Py_Dealloc` | memory |
| 2.54% | `python` | `_Py_bytes_upper` | unknown |
| 2.23% | `binascii.cpython-315-x86_64-linux-gnu.so` | `binascii_a2b_hex` | library |
| 1.96% | `python` | `_PyArg_UnpackKeywords` | calls |
| 1.62% | `python` | `_Py_dict_lookup` | lookup |
| 1.15% | `python` | `initialize_locals` | interpreter |
| 1.14% | `python` | `PyDict_GetItemRef` | dict |
| 0.92% | `python` | `PyBytesWriter_Create` | unknown |
| 0.88% | `python` | `PyBuffer_Release` | miscobj |
| 0.86% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.83% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.82% | `python` | `PyBuffer_FillInfo` | miscobj |
| 0.78% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 0.75% | `python` | `long_lshift_method` | int |
| 0.75% | `python` | `long_lshift1` | int |
| 0.66% | `python` | `long_alloc` | memory |
| 0.64% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.63% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.61% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.58% | `python` | `_PyCompactLong_Add` | unknown |
| 0.57% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.53% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.50% | `python` | `_Py_NewReference` | memory |
| 0.48% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.44% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.44% | `python` | `PyNumber_Lshift` | dynamic |
| 0.43% | `python` | `_Py_strhex_impl` | unknown |
| 0.43% | `python` | `bytes_concat` | str |
| 0.43% | `python` | `_PyLong_FromMedium` | int |
| 0.43% | `python` | `PySlice_New` | memory |
| 0.39% | `python` | `long_rshift1` | int |
| 0.37% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.37% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.36% | `python` | `PyBytesWriter_FinishWithPointer` | unknown |
| 0.34% | `python` | `cfunction_vectorcall_FASTCALL_KEYWORDS` | calls |
| 0.31% | `python` | `PyObject_Malloc` | dynamic |
| 0.30% | `python` | `long_dealloc` | memory |
| 0.29% | `python` | `_PyLong_AsByteArray` | int |
| 0.29% | `python` | `_PyLong_FromByteArray.part.0` | int |
| 0.29% | `python` | `maybe_small_long` | unknown |
| 0.28% | `python` | `long_rshift` | int |
| 0.28% | `python` | `PyNumber_Add` | dynamic |

## bpe_tokeniser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.26% | `[JIT]` | `jit` | jit |
| 5.15% | `python` | `_Py_Dealloc` | memory |
| 4.99% | `python` | `_Py_dict_lookup` | lookup |
| 4.49% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.07% | `python` | `tuple_dealloc` | memory |
| 2.68% | `python` | `_PyObject_Free` | memory |
| 2.53% | `python` | `list_dealloc` | memory |
| 2.51% | `python` | `tuple_alloc` | memory |
| 2.49% | `python` | `_PyObject_Malloc` | memory |
| 2.31% | `python` | `PyObject_GC_UnTrack` | gc |
| 2.25% | `python` | `listiter_next` | list |
| 1.96% | `python` | `visit_add_to_container` | gc |
| 1.89% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.67% | `python` | `zip_next` | unknown |
| 1.43% | `python` | `PyTuple_New` | memory |
| 1.39% | `python` | `PyTuple_FromArray` | tuple |
| 1.37% | `python` | `PyList_New.constprop.0` | memory |
| 1.33% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.27% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.25% | `python` | `list_slice_lock_held` | list |
| 1.23% | `python` | `list_iter` | list |
| 1.21% | `python` | `tuple_richcompare` | tuple |
| 0.96% | `python` | `PyTuple_GetSlice` | tuple |
| 0.95% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.91% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.85% | `python` | `tuple_hash` | tuple |
| 0.84% | `python` | `_Py_NewReference` | memory |
| 0.82% | `python` | `insertdict` | dict |
| 0.79% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.79% | `python` | `listiter_dealloc` | memory |
| 0.76% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.63% | `python` | `zip_new` | memory |
| 0.62% | `python` | `slot_mp_ass_subscript` | unknown |
| 0.62% | `python` | `dict_subscript` | dict |
| 0.59% | `python` | `_PyCompactLong_Add` | unknown |
| 0.57% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.53% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.52% | `python` | `dictiter_iternextkey` | dict |
| 0.52% | `python` | `PyLong_FromSsize_t` | int |
| 0.52% | `python` | `mark_all_reachable` | unknown |
| 0.51% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.51% | `python` | `PyObject_Hash` | dynamic |
| 0.49% | `python` | `wrapperdescr_call` | unknown |
| 0.48% | `python` | `list_traverse` | gc |
| 0.47% | `python` | `PyObject_RichCompare` | dynamic |
| 0.47% | `python` | `PyArg_UnpackTuple` | calls |
| 0.47% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.45% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.45% | `python` | `_PyEval_Vector` | interpreter |
| 0.43% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.43% | `python` | `_PyGC_Collect` | gc |
| 0.43% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.42% | `python` | `PyType_GenericAlloc` | memory |
| 0.41% | `python` | `PyObject_GetItem` | dynamic |
| 0.40% | `python` | `initialize_locals` | interpreter |
| 0.38% | `python` | `_PyList_BinarySlice` | list |
| 0.36% | `python` | `bytes_richcompare` | str |
| 0.36% | `python` | `PyObject_GetIter` | dynamic |
| 0.36% | `python` | `dict_ass_sub` | dict |
| 0.34% | `python` | `_PyObject_Realloc` | memory |
| 0.34% | `python` | `type_call` | dynamic |
| 0.33% | `python` | `zip_dealloc` | memory |
| 0.32% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.31% | `python` | `wrap_objobjargproc` | unknown |
| 0.30% | `python` | `PyObject_Size` | dynamic |
| 0.29% | `python` | `PySlice_Unpack` | miscobj |
| 0.29% | `python` | `_PyObject_GC_New` | gc |
| 0.28% | `python` | `_PyList_SliceSubscript` | list |
| 0.28% | `python` | `dict_traverse` | gc |
| 0.28% | `python` | `_PyObject_RealIsSubclass` | dynamic |
| 0.28% | `python` | `gc_collect_region` | gc |
| 0.27% | `python` | `list_slice_wrap` | list |
| 0.27% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.25% | `python` | `PyObject_GC_Del` | gc |
| 0.25% | `python` | `PyObject_SetItem` | dynamic |

## chameleon

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.32% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.18% | `[JIT]` | `jit` | jit |
| 6.49% | `python` | `_PyObject_Malloc` | memory |
| 3.31% | `python` | `unicode_from_format` | str |
| 2.88% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.83% | `python` | `_PyObject_Free` | memory |
| 2.63% | `python` | `_PyUnicode_ResizeCompact` | str |
| 2.15% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.70% | `python` | `_PyObject_Realloc` | memory |
| 1.68% | `python` | `_Py_dict_lookup` | lookup |
| 1.63% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 1.62% | `python` | `do_super_lookup` | dynamic |
| 1.60% | `python` | `PyDict_GetItemRef` | dict |
| 1.43% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.30% | `python` | `_Py_Dealloc` | memory |
| 1.27% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.16% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 1.16% | `python` | `long_to_decimal_string_internal` | int |
| 0.98% | `python` | `PyUnicode_Format` | str |
| 0.97% | `python` | `PyUnicode_New` | memory |
| 0.96% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.84% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.83% | `python` | `list_append` | list |
| 0.82% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.80% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.75% | `python` | `dict_get` | dict |
| 0.71% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.67% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.66% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.64% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.62% | `python` | `_PySuper_Lookup` | dynamic |
| 0.61% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.57% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.56% | `python` | `_PyUnicodeWriter_WriteASCIIString` | str |
| 0.55% | `python` | `method_vectorcall_FASTCALL` | calls |
| 0.55% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 0.50% | `python` | `PyType_GenericAlloc` | memory |
| 0.50% | `python` | `PyType_IsSubtype` | dynamic |
| 0.48% | `libc.so.6` | `malloc` | libc |
| 0.48% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.47% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.45% | `python` | `PyObject_Str` | dynamic |
| 0.43% | `python` | `insertdict` | dict |
| 0.42% | `python` | `PyErr_ExceptionMatches` | exceptions |
| 0.40% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.40% | `python` | `_PyUnicodeWriter_Finish` | str |
| 0.39% | `python` | `delitem_common` | dynamic |
| 0.38% | `python` | `PyMember_GetOne` | lookup |
| 0.38% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.37% | `python` | `sre_search` | library |
| 0.37% | `python` | `unicode_dealloc` | memory |
| 0.37% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.34% | `python` | `PyTuple_FromArray` | tuple |
| 0.34% | `python` | `PyType_GetFullyQualifiedName` | unknown |
| 0.33% | `python` | `unicode_fromformat_write_str` | str |
| 0.32% | `python` | `listiter_next` | list |
| 0.31% | `python` | `PyArg_ParseTupleAndKeywords` | calls |
| 0.30% | `python` | `PyErr_Format` | exceptions |
| 0.30% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.30% | `python` | `tuple_dealloc` | memory |
| 0.29% | `python` | `tuple_alloc` | memory |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `_PyUnicode_DecodeUTF8Writer` | str |
| 0.26% | `python` | `AttributeError_init` | exceptions |
| 0.26% | `python` | `_Py_NewReference` | memory |
| 0.25% | `python` | `PyObject_Malloc` | dynamic |
| 0.25% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |

## chaos

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 39.97% | `[JIT]` | `jit` | jit |
| 8.54% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.56% | `python` | `_Py_Dealloc` | memory |
| 3.07% | `python` | `PyFloat_FromDouble` | float |
| 2.54% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.40% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.92% | `python` | `make_range_object` | unknown |
| 1.52% | `python` | `_PyCompactLong_Add` | unknown |
| 1.41% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 1.37% | `python` | `range_iter` | miscobj |
| 1.25% | `python` | `initialize_locals` | interpreter |
| 1.23% | `python` | `_Py_NewReference` | memory |
| 1.18% | `python` | `_PyObject_Free` | memory |
| 1.16% | `python` | `float_richcompare` | float |
| 1.15% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.03% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.01% | `python` | `PyType_IsSubtype` | dynamic |
| 0.98% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.97% | `python` | `float_pow` | float |
| 0.93% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.91% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.91% | `python` | `_PyObject_Malloc` | memory |
| 0.90% | `python` | `float_compactlong_true_div` | float |
| 0.84% | `python` | `subtype_dealloc` | memory |
| 0.80% | `python` | `float_dealloc` | memory |
| 0.78% | `python` | `PyLong_FromLong` | int |
| 0.78% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.76% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.73% | `python` | `PyLong_AsLong` | int |
| 0.64% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.60% | `python` | `PyObject_RichCompare` | dynamic |
| 0.56% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.49% | `python` | `PyType_GenericAlloc` | memory |
| 0.46% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.41% | `python` | `PyNumber_Index` | dynamic |
| 0.38% | `python` | `tuple_alloc` | memory |
| 0.37% | `python` | `range_vectorcall` | miscobj |
| 0.36% | `python` | `PyLong_AsDouble` | int |
| 0.31% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.31% | `python` | `PyObject_GetIter` | dynamic |
| 0.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.30% | `python` | `tuple_dealloc` | memory |
| 0.28% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.28% | `python` | `_PyEval_GetIter` | interpreter |
| 0.28% | `python` | `PyList_New.constprop.0` | memory |
| 0.27% | `python` | `PyNumber_TrueDivide` | dynamic |
| 0.27% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.26% | `python` | `list_dealloc` | memory |

## comprehensions

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 39.30% | `[JIT]` | `jit` | jit |
| 6.75% | `python` | `_Py_dict_lookup` | lookup |
| 4.06% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 3.02% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `python` | `dict_get` | dict |
| 2.32% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.23% | `python` | `_PyObject_Free` | memory |
| 1.84% | `python` | `PyDict_GetItemRef` | dict |
| 1.66% | `python` | `_Py_Dealloc` | memory |
| 1.61% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.58% | `python` | `_PyObject_Realloc` | memory |
| 1.40% | `python` | `insertdict` | dict |
| 1.34% | `python` | `PyObject_Hash` | dynamic |
| 1.34% | `python` | `long_richcompare` | int |
| 1.24% | `python` | `list_dealloc` | memory |
| 1.23% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.23% | `python` | `func_clear` | unknown |
| 1.19% | `python` | `long_hash` | int |
| 1.16% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 1.14% | `python` | `PyFunction_NewWithQualName` | memory |
| 1.10% | `python` | `gen_dealloc` | memory |
| 1.06% | `python` | `unsafe_tuple_compare` | unknown |
| 1.02% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.85% | `python` | `list_sort_impl` | list |
| 0.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.85% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.82% | `python` | `PyObject_RichCompare` | dynamic |
| 0.69% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.60% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.58% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.57% | `python` | `func_dealloc` | memory |
| 0.47% | `python` | `PyList_New.constprop.0` | memory |
| 0.46% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `make_gen` | miscobj |
| 0.42% | `python` | `tuple_alloc` | memory |
| 0.41% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.41% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.40% | `python` | `_PyEval_GetIter` | interpreter |
| 0.37% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.37% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.36% | `python` | `PyObject_IsTrue` | dynamic |
| 0.36% | `python` | `_Py_NewReference` | memory |
| 0.36% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.36% | `python` | `unsafe_object_compare` | unknown |
| 0.35% | `python` | `tuple_subscript` | tuple |
| 0.33% | `python` | `gen_close` | unknown |
| 0.32% | `python` | `_PyFunction_SetVersion` | unknown |
| 0.32% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.31% | `python` | `_PyObject_GC_New` | gc |
| 0.31% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.29% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.29% | `python` | `build_indices_generic` | unknown |
| 0.29% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.27% | `python` | `PyObject_GC_Del` | gc |
| 0.26% | `python` | `PyLong_FromSsize_t` | int |

## concurrent_imap

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 12.84% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.18% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.03% | `[unknown]` | `0xffffffff93c001c6` | unknown |
| 1.86% | `python` | `_PyObject_Malloc` | memory |
| 1.60% | `[JIT]` | `jit` | jit |
| 1.45% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.05% | `[unknown]` | `0xffffffff93c00151` | unknown |
| 1.02% | `python` | `_Py_dict_lookup` | lookup |
| 0.95% | `python` | `_PyObject_Free` | memory |
| 0.93% | `[unknown]` | `0xffffffff93c0010f` | unknown |
| 0.80% | `python` | `initialize_locals` | interpreter |
| 0.78% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.77% | `python` | `_Py_Dealloc` | memory |
| 0.66% | `[unknown]` | `0xffffffff93c0009d` | unknown |
| 0.64% | `[unknown]` | `0xffffffff93c001bd` | unknown |
| 0.57% | `python` | `r_object` | import |
| 0.56% | `[unknown]` | `0xffffffff939cb1a6` | unknown |
| 0.55% | `[unknown]` | `0xffffffff939cac57` | unknown |
| 0.50% | `[unknown]` | `0xffffffff93c011d3` | unknown |
| 0.50% | `python` | `PyDict_GetItemRef` | dict |
| 0.48% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.48% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.45% | `python` | `find_name_in_mro` | lookup |
| 0.42% | `python` | `tuple_dealloc` | memory |
| 0.39% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.37% | `libc.so.6` | `_int_malloc` | libc |
| 0.36% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.35% | `[unknown]` | `0xffffffff93c0128c` | unknown |
| 0.35% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.33% | `python` | `tuple_alloc` | memory |
| 0.33% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.32% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.31% | `libc.so.6` | `pthread_cond_timedwait@@GLIBC_2.3.2` | libc |
| 0.31% | `python` | `_PyCode_Quicken` | interpreter |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `[unknown]` | `0xffffffff93a5ab73` | unknown |
| 0.28% | `[unknown]` | `0xffffffff93c011a9` | unknown |
| 0.28% | `[unknown]` | `0xffffffff93c01631` | unknown |
| 0.27% | `python` | `siphash13` | str |
| 0.27% | `python` | `visit_add_to_container` | gc |
| 0.27% | `python` | `dict_dealloc` | memory |
| 0.27% | `python` | `PyObject_GetAttr` | dynamic |
| 0.27% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.26% | `libc.so.6` | `malloc` | libc |

## coroutines

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 54.36% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.57% | `python` | `gen_dealloc` | memory |
| 5.29% | `python` | `_PyObject_Free` | memory |
| 4.71% | `python` | `make_gen` | miscobj |
| 3.78% | `python` | `_PyObject_Malloc` | memory |
| 3.18% | `python` | `_PyObject_GC_NewVar` | gc |
| 2.92% | `python` | `_Py_Dealloc` | memory |
| 2.29% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.17% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.85% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.78% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.67% | `python` | `_PyCompactLong_Add` | unknown |
| 1.44% | `python` | `_PyCoro_GetAwaitableIter` | unknown |
| 1.22% | `python` | `_Py_MakeCoro` | unknown |
| 1.14% | `python` | `_PyEval_GetAwaitable` | interpreter |
| 1.10% | `python` | `PyObject_GC_Del` | gc |
| 0.76% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.51% | `python` | `gen_finalize` | unknown |
| 0.49% | `python` | `_Py_NewReference` | memory |
| 0.34% | `python` | `PyObject_Malloc` | dynamic |

## coverage

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.56% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.76% | `python` | `call_instrumentation_vector.part.0.isra.0` | interpreter |
| 7.60% | `tracer.cpython-315-x86_64-linux-gnu.so` | `CTracer_trace` | library |
| 6.26% | `python` | `_Py_call_instrumentation_line` | interpreter |
| 5.20% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.31% | `python` | `_PyObject_Free` | memory |
| 3.23% | `python` | `_Py_dict_lookup` | lookup |
| 3.06% | `python` | `_PyObject_Malloc` | memory |
| 2.39% | `python` | `PyDict_GetItem` | dict |
| 2.36% | `python` | `set_add_entry_takeref` | miscobj |
| 2.10% | `python` | `siphash13` | str |
| 1.81% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 1.54% | `python` | `_Py_Dealloc` | memory |
| 1.49% | `python` | `PyLong_FromLong` | int |
| 1.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.28% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 1.26% | `python` | `PyUnicode_InternFromString` | str |
| 1.18% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.10% | `python` | `unicode_decode_utf8.part.0` | str |
| 1.06% | `python` | `_PyCode_GetCode` | interpreter |
| 1.03% | `python` | `find_first_nonascii` | str |
| 1.00% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.96% | `python` | `PySet_Add` | miscobj |
| 0.93% | `python` | `PyFrame_GetCode` | exceptions |
| 0.87% | `python` | `PyUnicode_New.part.0` | memory |
| 0.82% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.80% | `python` | `sys_trace_return` | library |
| 0.78% | `python` | `PyObject_Hash` | dynamic |
| 0.77% | `python` | `_Py_call_instrumentation_arg` | unknown |
| 0.75% | `python` | `_PyDict_LoadGlobalStackRef` | dict |
| 0.73% | `python` | `sys_trace_start` | library |
| 0.67% | `tracer.cpython-315-x86_64-linux-gnu.so` | `CTracer_set_pdata_stack.constprop.0` | library |
| 0.67% | `python` | `PyObject_SetAttr` | dynamic |
| 0.65% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.64% | `python` | `PyEval_GetFrame` | interpreter |
| 0.63% | `python` | `long_hash` | int |
| 0.55% | `python` | `PyObject_SetAttrString` | dynamic |
| 0.54% | `python` | `_PyUnicode_InternMortal` | str |
| 0.53% | `python` | `frame_dealloc` | memory |
| 0.50% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.49% | `python` | `PyFrame_GetLasti` | exceptions |
| 0.47% | `python` | `_Py_call_instrumentation` | unknown |
| 0.47% | `python` | `PyObject_Free` | dynamic |
| 0.45% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.43% | `python` | `unicode_dealloc` | memory |
| 0.41% | `python` | `_PyFrame_MakeAndSetFrameObject` | interpreter |
| 0.40% | `python` | `_PyFrame_New_NoTrack` | interpreter |
| 0.40% | `python` | `_PyEval_LoadGlobalStackRef` | interpreter |
| 0.39% | `python` | `PyFrame_GetLineNumber` | exceptions |
| 0.39% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.39% | `python` | `_PyCompactLong_Add` | unknown |
| 0.38% | `python` | `_PyType_GetDict` | dynamic |
| 0.37% | `python` | `_Py_hashtable_get` | lookup |
| 0.36% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.35% | `python` | `hashtable_unicode_hash` | unknown |
| 0.34% | `tracer.cpython-315-x86_64-linux-gnu.so` | `DataStack_grow` | library |
| 0.33% | `python` | `getset_set` | unknown |
| 0.30% | `python` | `PyErr_SetRaisedException` | exceptions |
| 0.29% | `python` | `PyObject_GC_Del` | gc |
| 0.29% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.27% | `python` | `_Py_NewReference` | memory |
| 0.27% | `python` | `Py_HashBuffer` | unknown |
| 0.26% | `python` | `_PyErr_SetRaisedException` | exceptions |

## crypto_pyaes

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.53% | `[JIT]` | `jit` | jit |
| 7.14% | `python` | `long_bitwise` | int |
| 6.16% | `python` | `_PyObject_Free` | memory |
| 5.10% | `python` | `_PyObject_Malloc` | memory |
| 4.79% | `python` | `_Py_Dealloc` | memory |
| 3.47% | `python` | `l_mod` | int |
| 3.37% | `python` | `long_alloc` | memory |
| 3.25% | `python` | `long_rshift1` | int |
| 1.65% | `python` | `long_rshift` | int |
| 1.57% | `python` | `maybe_small_long` | unknown |
| 1.41% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.38% | `python` | `PyNumber_Xor` | dynamic |
| 1.26% | `python` | `long_dealloc` | memory |
| 1.20% | `python` | `PyLong_FromLong` | int |
| 1.15% | `python` | `PyNumber_Remainder` | dynamic |
| 1.13% | `python` | `PyLong_FromSsize_t` | int |
| 1.09% | `python` | `PyNumber_Rshift` | dynamic |
| 1.06% | `python` | `compactlongs_guard` | unknown |
| 1.04% | `python` | `_PyCompactLong_Add` | unknown |
| 0.92% | `python` | `_Py_NewReference` | memory |
| 0.83% | `python` | `make_range_object` | unknown |
| 0.77% | `python` | `long_mod` | int |
| 0.75% | `python` | `_PyLong_FromMedium` | int |
| 0.75% | `python` | `long_xor` | int |
| 0.64% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.61% | `python` | `range_iter` | miscobj |
| 0.57% | `python` | `compactlongs_and` | unknown |
| 0.47% | `python` | `list_dealloc` | memory |
| 0.45% | `python` | `PyObject_Malloc` | dynamic |
| 0.42% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.39% | `python` | `PyList_New.constprop.0` | memory |
| 0.34% | `python` | `PyLong_AsLong` | int |
| 0.33% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.31% | `python` | `PyNumber_And` | dynamic |
| 0.31% | `python` | `set_lookkey` | miscobj |
| 0.29% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.29% | `python` | `PyObject_Free` | dynamic |
| 0.27% | `python` | `_PyFrame_ClearExceptCode` | interpreter |

## deepcopy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.51% | `[JIT]` | `jit` | jit |
| 6.48% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.54% | `python` | `_Py_dict_lookup` | lookup |
| 4.27% | `python` | `_PyObject_Malloc` | memory |
| 3.56% | `python` | `_PyObject_Free` | memory |
| 3.20% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.63% | `python` | `_Py_Dealloc` | memory |
| 1.84% | `python` | `set_lookkey` | miscobj |
| 1.51% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 1.41% | `python` | `dict_get` | dict |
| 1.39% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.37% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.13% | `python` | `initialize_locals` | interpreter |
| 1.11% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.10% | `python` | `sys_audit_tstate` | unknown |
| 1.01% | `python` | `PyLong_FromVoidPtr` | int |
| 0.97% | `python` | `list_append` | list |
| 0.96% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.95% | `python` | `_PySet_Contains` | miscobj |
| 0.95% | `python` | `_PyObject_Realloc` | memory |
| 0.93% | `python` | `PyObject_Hash` | dynamic |
| 0.92% | `python` | `long_richcompare` | int |
| 0.90% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.88% | `python` | `insertdict` | dict |
| 0.79% | `python` | `list_dealloc` | memory |
| 0.78% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.71% | `python` | `long_hash` | int |
| 0.67% | `python` | `dictiter_iternextitem` | dict |
| 0.66% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.65% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.65% | `python` | `PySys_Audit` | unknown |
| 0.64% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.58% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.58% | `python` | `insert_to_emptydict` | dict |
| 0.57% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.56% | `python` | `tuple_dealloc` | memory |
| 0.56% | `python` | `PyDict_GetItemRef` | dict |
| 0.48% | `python` | `_Py_NewReference` | memory |
| 0.44% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.43% | `python` | `tuple_alloc` | memory |
| 0.42% | `python` | `PyTuple_FromArray` | tuple |
| 0.40% | `python` | `builtin_id` | unknown |
| 0.37% | `python` | `PyType_IsSubtype` | dynamic |
| 0.37% | `python` | `PyCMethod_New` | memory |
| 0.36% | `python` | `new_dict` | dict |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.34% | `python` | `_PyObject_Calloc` | memory |
| 0.33% | `python` | `dict_dealloc` | memory |
| 0.29% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.28% | `python` | `_PyDict_Next` | dict |
| 0.28% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.27% | `python` | `_PyObject_GC_New` | gc |
| 0.26% | `python` | `long_dealloc` | memory |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.25% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.25% | `python` | `PyObject_Malloc` | dynamic |

## deltablue

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 48.95% | `[JIT]` | `jit` | jit |
| 11.19% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.85% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.11% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.82% | `python` | `gc_collect_region` | gc |
| 1.59% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.48% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.48% | `python` | `listiter_next` | list |
| 1.39% | `python` | `_PyObject_Malloc` | memory |
| 1.10% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.08% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.95% | `python` | `_Py_Dealloc` | memory |
| 0.89% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.75% | `python` | `_PyObject_Free` | memory |
| 0.63% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.62% | `python` | `_Py_type_getattro` | lookup |
| 0.56% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.52% | `python` | `PyMethod_New` | memory |
| 0.50% | `python` | `PyType_IsSubtype` | dynamic |
| 0.50% | `python` | `visit_decref` | gc |
| 0.48% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.46% | `python` | `_PyGC_Collect` | gc |
| 0.43% | `python` | `do_super_lookup` | dynamic |
| 0.43% | `python` | `PyDict_GetItemRef` | dict |
| 0.42% | `python` | `subtype_dealloc` | memory |
| 0.41% | `python` | `list_iter` | list |
| 0.40% | `python` | `_PyCompactLong_Add` | unknown |
| 0.39% | `python` | `_PyType_GetDict` | dynamic |
| 0.37% | `python` | `subtype_traverse` | gc |
| 0.36% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.35% | `python` | `method_dealloc` | memory |
| 0.33% | `python` | `long_to_decimal_string_internal` | int |
| 0.33% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.32% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.32% | `python` | `PyObject_RichCompare` | dynamic |
| 0.30% | `python` | `object_richcompare` | dynamic |
| 0.28% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.27% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.26% | `python` | `visit_add_to_container` | gc |
| 0.25% | `python` | `list_append` | list |
| 0.25% | `python` | `method_vectorcall_O` | calls |

## django_template

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.55% | `[JIT]` | `jit` | jit |
| 8.98% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.40% | `python` | `_PyObject_Malloc` | memory |
| 2.85% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.69% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.38% | `python` | `_PyObject_Free` | memory |
| 2.22% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.04% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.94% | `python` | `_Py_Dealloc` | memory |
| 1.75% | `python` | `initialize_locals` | interpreter |
| 1.47% | `python` | `replace` | str |
| 1.29% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 1.27% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.26% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.26% | `python` | `_Py_dict_lookup` | lookup |
| 1.22% | `python` | `PyType_IsSubtype` | dynamic |
| 1.14% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.94% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.90% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRefSteal` | unknown |
| 0.87% | `python` | `unicode_replace` | str |
| 0.79% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.74% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.74% | `python` | `listiter_next` | list |
| 0.74% | `python` | `long_to_decimal_string_internal` | int |
| 0.73% | `python` | `insertdict` | dict |
| 0.60% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.59% | `python` | `object_isinstance` | dynamic |
| 0.57% | `python` | `_PyEvalFramePushAndInit_Ex` | interpreter |
| 0.54% | `python` | `tuple_dealloc` | memory |
| 0.51% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.50% | `python` | `_PyType_GetDict` | dynamic |
| 0.48% | `python` | `tuple_alloc` | memory |
| 0.45% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.44% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.44% | `python` | `new_dict` | dict |
| 0.44% | `python` | `PyTuple_FromArray` | tuple |
| 0.43% | `python` | `PyDict_GetItemRef` | dict |
| 0.43% | `python` | `dict_dealloc` | memory |
| 0.42% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.41% | `python` | `PyMethod_New` | memory |
| 0.41% | `python` | `_Py_NewReference` | memory |
| 0.40% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.40% | `python` | `_PyEval_GetIter` | interpreter |
| 0.39% | `python` | `PyDict_New` | memory |
| 0.38% | `python` | `enum_next` | miscobj |
| 0.37% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.37% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.35% | `python` | `PyList_New` | memory |
| 0.35% | `python` | `PyObject_SetItem` | dynamic |
| 0.35% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.35% | `python` | `func_clear` | unknown |
| 0.35% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.35% | `python` | `PyObject_IsInstance` | dynamic |
| 0.34% | `python` | `list_dealloc` | memory |
| 0.34% | `python` | `unicode_new` | memory |
| 0.32% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.31% | `python` | `list_iter` | list |
| 0.31% | `python` | `_PyObject_GC_New` | gc |
| 0.31% | `python` | `slot_sq_contains` | unknown |
| 0.31% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.30% | `python` | `chain_new` | memory |
| 0.28% | `python` | `gen_dealloc` | memory |
| 0.28% | `python` | `PyObject_Str` | dynamic |
| 0.28% | `python` | `func_dealloc` | memory |
| 0.27% | `python` | `chain_next` | unknown |
| 0.27% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.27% | `python` | `list_subscript` | list |
| 0.27% | `python` | `PyType_GenericAlloc` | memory |
| 0.27% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.26% | `python` | `_PyObject_Calloc` | memory |

## docutils

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.72% | `[JIT]` | `jit` | jit |
| 9.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.13% | `python` | `sre_ucs1_match` | library |
| 4.76% | `python` | `gc_collect_region` | gc |
| 3.05% | `python` | `_PyObject_Malloc` | memory |
| 2.99% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.74% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.77% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.65% | `python` | `visit_add_to_container` | gc |
| 1.63% | `python` | `sre_ucs1_charset.isra.0` | library |
| 1.62% | `python` | `_PyGC_Collect` | gc |
| 1.60% | `python` | `_PyObject_Free` | memory |
| 1.60% | `python` | `_Py_dict_lookup` | lookup |
| 1.54% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.29% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.25% | `python` | `_Py_Dealloc` | memory |
| 1.18% | `python` | `list_dealloc` | memory |
| 0.98% | `python` | `visit_decref` | gc |
| 0.96% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.84% | `python` | `initialize_locals` | interpreter |
| 0.80% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.67% | `python` | `PyType_IsSubtype` | dynamic |
| 0.65% | `python` | `PyDict_GetItemRef` | dict |
| 0.59% | `python` | `list_slice_lock_held` | list |
| 0.57% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.56% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.55% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.50% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.48% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.48% | `python` | `dict_traverse` | gc |
| 0.42% | `python` | `list_extend_lock_held` | list |
| 0.42% | `python` | `tuple_dealloc` | memory |
| 0.42% | `python` | `sre_ucs1_count` | library |
| 0.42% | `python` | `PyUnicode_Format` | str |
| 0.38% | `python` | `tuple_alloc` | memory |
| 0.36% | `libc.so.6` | `_int_malloc` | libc |
| 0.36% | `python` | `split` | str |
| 0.35% | `python` | `list_traverse` | gc |
| 0.33% | `python` | `PyObject_SetAttr` | dynamic |
| 0.33% | `python` | `PyList_New.constprop.0` | memory |
| 0.33% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.33% | `python` | `find_name_in_mro` | lookup |
| 0.32% | `python` | `_PyObject_Realloc` | memory |
| 0.32% | `python` | `insertdict` | dict |
| 0.31% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.27% | `python` | `_PyType_GetDict` | dynamic |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.26% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.25% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |

## dulwich_log

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.29% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.47% | `[JIT]` | `jit` | jit |
| 2.78% | `python` | `_PyObject_Malloc` | memory |
| 1.84% | `libz.so.1.3` | `inflate` | library |
| 1.84% | `python` | `_Py_Dealloc` | memory |
| 1.82% | `python` | `_PyObject_Free` | memory |
| 1.35% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.83% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.77% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.69% | `libc.so.6` | `_int_malloc` | libc |
| 0.66% | `libz.so.1.3` | `0x000000000000381f` | library |
| 0.64% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.63% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.61% | `python` | `subtype_dealloc` | memory |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.54% | `python` | `_Py_dict_lookup` | lookup |
| 0.50% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.49% | `[unknown]` | `0xffffffffaa71b26f` | unknown |
| 0.49% | `python` | `PyObject_RichCompare` | dynamic |
| 0.49% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.46% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRefSteal` | unknown |
| 0.44% | `python` | `PyLong_FromString` | int |
| 0.44% | `python` | `PyObject_IsTrue` | dynamic |
| 0.41% | `python` | `initialize_locals` | interpreter |
| 0.38% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.36% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.36% | `python` | `bytes_richcompare` | str |
| 0.36% | `python` | `_PyCompactLong_Add` | unknown |
| 0.35% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.35% | `python` | `_io_open` | unknown |
| 0.34% | `[unknown]` | `0xffffffffab6001c6` | unknown |
| 0.34% | `python` | `do_mkvalue` | unknown |
| 0.34% | `libz.so.1.3` | `adler32_z` | library |
| 0.33% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.33% | `python` | `unicode_from_format` | str |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.32% | `libz.so.1.3` | `0x00000000000025b7` | library |
| 0.31% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.30% | `python` | `PySlice_New` | memory |
| 0.30% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.30% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.30% | `python` | `PyList_New.constprop.0` | memory |
| 0.29% | `python` | `_io_FileIO___init__` | unknown |
| 0.28% | `python` | `bytes_subscript` | str |
| 0.28% | `python` | `PyType_IsSubtype` | dynamic |
| 0.28% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.27% | `python` | `PyUnicode_Decode` | str |
| 0.27% | `python` | `siphash13` | str |
| 0.26% | `python` | `_PyObject_CallFunctionVa` | dynamic |
| 0.26% | `python` | `convertitem.constprop.0` | unknown |
| 0.26% | `python` | `PyObject_GetItem` | dynamic |

## fannkuch

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.33% | `[JIT]` | `jit` | jit |
| 11.74% | `python` | `PySlice_AdjustIndices` | miscobj |
| 6.23% | `python` | `list_ass_slice_lock_held` | list |
| 5.39% | `python` | `_Py_Dealloc` | memory |
| 4.56% | `python` | `list_slice_wrap` | list |
| 3.73% | `python` | `_PyObject_Free` | memory |
| 3.42% | `python` | `_PyObject_Malloc` | memory |
| 3.06% | `python` | `PyObject_GC_UnTrack` | gc |
| 3.00% | `python` | `PySlice_New` | memory |
| 2.79% | `python` | `PySlice_Unpack` | miscobj |
| 2.71% | `python` | `_PyEval_SliceIndex` | interpreter |
| 2.70% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 2.63% | `python` | `list_dealloc` | memory |
| 2.56% | `python` | `list_ass_subscript` | list |
| 2.13% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 2.09% | `python` | `_PyCompactLong_Add` | unknown |
| 1.79% | `python` | `slice_dealloc` | memory |
| 1.79% | `python` | `PyList_New.constprop.0` | memory |
| 1.42% | `python` | `_PyList_SliceSubscript` | list |
| 1.36% | `python` | `list_insert` | list |
| 1.22% | `python` | `PySequence_Fast` | dynamic |
| 0.84% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.81% | `python` | `_Py_NewReference` | memory |
| 0.78% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.74% | `python` | `PyObject_SetItem` | dynamic |
| 0.70% | `python` | `list_pop` | list |
| 0.57% | `python` | `_PyNumber_Index` | dynamic |
| 0.51% | `python` | `list_slice_lock_held` | list |
| 0.51% | `python` | `PyLong_AsSsize_t` | int |

## float

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 34.93% | `[JIT]` | `jit` | jit |
| 5.96% | `python` | `_Py_Dealloc` | memory |
| 3.87% | `libm.so.6` | `__sin_fma` | library |
| 3.67% | `libm.so.6` | `__cos_fma` | library |
| 3.37% | `python` | `PyFloat_FromDouble` | float |
| 3.05% | `python` | `_PyObject_Malloc` | memory |
| 2.50% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.49% | `python` | `subtype_dealloc` | memory |
| 2.39% | `python` | `visit_add_to_container` | gc |
| 2.08% | `python` | `_PyObject_Free` | memory |
| 1.78% | `python` | `_Py_NewReference` | memory |
| 1.71% | `python` | `subtype_traverse` | gc |
| 1.51% | `python` | `float_div` | float |
| 1.32% | `python` | `float_dealloc` | memory |
| 1.30% | `python` | `PyType_IsSubtype` | dynamic |
| 1.29% | `python` | `PyNumber_InPlaceTrueDivide` | dynamic |
| 1.21% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.12% | `python` | `_PyGC_Collect` | gc |
| 1.06% | `python` | `PyFloat_AsDouble` | float |
| 1.03% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.98% | `python` | `list_dealloc` | memory |
| 0.94% | `math.cpython-315-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.89% | `python` | `list_slice_lock_held` | list |
| 0.77% | `python` | `initialize_locals` | interpreter |
| 0.70% | `python` | `visit_decref` | gc |
| 0.68% | `python` | `gc_collect_region` | gc |
| 0.68% | `python` | `PyType_GenericAlloc` | memory |
| 0.68% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.63% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.60% | `python` | `_PyMember_GetOffset` | unknown |
| 0.60% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.58% | `python` | `long_float` | int |
| 0.57% | `python` | `visit_reachable` | gc |
| 0.54% | `python` | `PyLong_FromLong` | int |
| 0.53% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.53% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.50% | `math.cpython-315-x86_64-linux-gnu.so` | `math_sin` | library |
| 0.47% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.36% | `python` | `mark_all_reachable` | unknown |
| 0.36% | `math.cpython-315-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.34% | `[unknown]` | `0xffffffffab6011a9` | unknown |
| 0.33% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.32% | `[unknown]` | `0xffffffffab601631` | unknown |
| 0.31% | `python` | `float_compactlong_true_div` | float |

## gc_collect

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.80% | `python` | `gc_collect_region` | gc |
| 16.96% | `python` | `visit_reachable` | gc |
| 16.83% | `python` | `visit_decref` | gc |
| 9.51% | `python` | `visit_add_to_container` | gc |
| 8.63% | `python` | `dict_traverse` | gc |
| 3.99% | `python` | `_PyGC_Collect` | gc |
| 2.93% | `[JIT]` | `jit` | jit |
| 2.68% | `python` | `func_traverse` | gc |
| 2.08% | `python` | `mark_all_reachable` | unknown |
| 1.77% | `python` | `subtype_traverse` | gc |
| 1.65% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 1.14% | `python` | `type_traverse` | gc |
| 1.07% | `python` | `tuple_traverse` | gc |
| 0.98% | `python` | `set_traverse` | gc |
| 0.95% | `python` | `type_is_gc` | gc |
| 0.83% | `python` | `PyObject_IS_GC` | gc |
| 0.81% | `python` | `list_traverse` | gc |
| 0.54% | `python` | `_PyObject_Malloc` | memory |
| 0.48% | `python` | `meth_traverse` | gc |
| 0.34% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.30% | `python` | `_PyTuple_MaybeUntrack` | gc |
| 0.28% | `python` | `_PyFrame_ClearExceptCode` | interpreter |

## gc_traversal

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.32% | `python` | `visit_reachable` | gc |
| 26.08% | `python` | `visit_decref` | gc |
| 13.96% | `python` | `list_traverse` | gc |
| 9.87% | `python` | `gc_collect_region` | gc |
| 4.46% | `python` | `dict_traverse` | gc |
| 3.99% | `python` | `_PyGC_Collect` | gc |
| 1.71% | `[JIT]` | `jit` | jit |
| 1.27% | `python` | `func_traverse` | gc |
| 0.64% | `python` | `subtype_traverse` | gc |
| 0.62% | `python` | `type_traverse` | gc |
| 0.58% | `python` | `tuple_traverse` | gc |
| 0.51% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.45% | `python` | `type_is_gc` | gc |
| 0.43% | `python` | `PyObject_IS_GC` | gc |
| 0.41% | `python` | `set_traverse` | gc |
| 0.27% | `python` | `PyLong_FromLong` | int |
| 0.26% | `python` | `list_dealloc` | memory |

## generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 49.76% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.41% | `[JIT]` | `jit` | jit |
| 2.64% | `python` | `_Py_Dealloc` | memory |
| 2.22% | `python` | `_PyObject_Malloc` | memory |
| 1.95% | `python` | `_PyObject_Free` | memory |
| 1.89% | `python` | `gen_dealloc` | memory |
| 1.58% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.56% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.44% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.37% | `python` | `visit_add_to_container` | gc |
| 1.36% | `python` | `initialize_locals` | interpreter |
| 1.30% | `python` | `make_range_object` | unknown |
| 1.03% | `python` | `_PyEval_Vector` | interpreter |
| 1.03% | `python` | `_PyLong_FromMedium` | int |
| 0.93% | `python` | `make_gen` | miscobj |
| 0.88% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.87% | `python` | `range_subscript` | miscobj |
| 0.85% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.82% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.82% | `python` | `PyNumber_Add` | dynamic |
| 0.76% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.72% | `python` | `slot_tp_iter` | unknown |
| 0.70% | `python` | `long_richcompare` | int |
| 0.63% | `python` | `PySlice_New` | memory |
| 0.63% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.52% | `python` | `_PyEval_GetIter` | interpreter |
| 0.52% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.51% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.50% | `python` | `range_dealloc` | memory |
| 0.49% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.47% | `python` | `long_add` | int |
| 0.47% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.47% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.45% | `python` | `_Py_NewReference` | memory |
| 0.45% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.40% | `python` | `long_dealloc` | memory |
| 0.38% | `python` | `long_mul` | int |
| 0.35% | `python` | `PyObject_GetItem` | dynamic |
| 0.35% | `python` | `PyNumber_Multiply` | dynamic |
| 0.34% | `python` | `subtype_dealloc` | memory |
| 0.33% | `python` | `PyObject_GC_Del` | gc |
| 0.32% | `python` | `PyObject_IsTrue` | dynamic |
| 0.32% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.31% | `python` | `PyObject_GetIter` | dynamic |
| 0.30% | `python` | `PyLong_FromLong` | int |
| 0.30% | `python` | `_PyGC_Collect` | gc |
| 0.30% | `python` | `mark_all_reachable` | unknown |
| 0.29% | `python` | `long_div` | int |

## genshi

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.68% | `[JIT]` | `jit` | jit |
| 7.24% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.54% | `python` | `_PyObject_Malloc` | memory |
| 2.13% | `python` | `_PyObject_Free` | memory |
| 2.12% | `python` | `_Py_dict_lookup` | lookup |
| 2.04% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.91% | `python` | `_Py_Dealloc` | memory |
| 1.59% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.41% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.40% | `python` | `insertdict` | dict |
| 1.38% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.27% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.03% | `python` | `_PyDict_FromItems` | dict |
| 1.01% | `python` | `PyDict_GetItemRef` | dict |
| 0.96% | `python` | `tuple_dealloc` | memory |
| 0.85% | `python` | `insert_to_emptydict` | dict |
| 0.83% | `python` | `initialize_locals` | interpreter |
| 0.81% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.81% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.78% | `python` | `long_to_decimal_string_internal` | int |
| 0.76% | `python` | `_Py_BuildMap_StackRefSteal` | unknown |
| 0.75% | `python` | `PyType_IsSubtype` | dynamic |
| 0.74% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.71% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.65% | `python` | `tuple_alloc` | memory |
| 0.64% | `python` | `PyMethod_New` | memory |
| 0.64% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.56% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.54% | `python` | `gen_iternext` | miscobj |
| 0.53% | `python` | `dictiter_iternextvalue` | dict |
| 0.51% | `python` | `pattern_subx` | library |
| 0.50% | `python` | `PyObject_IsTrue` | dynamic |
| 0.49% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.48% | `python` | `_PyObject_GC_New` | gc |
| 0.48% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.48% | `python` | `object_recursive_isinstance` | dynamic |
| 0.44% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.42% | `python` | `PyEval_EvalCode` | interpreter |
| 0.42% | `python` | `deque_iter` | miscobj |
| 0.42% | `python` | `_list_extend` | list |
| 0.42% | `python` | `method_dealloc` | memory |
| 0.40% | `python` | `build_indices_unicode` | dict |
| 0.38% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRefSteal` | unknown |
| 0.37% | `python` | `dict_dealloc` | memory |
| 0.37% | `python` | `new_dict` | dict |
| 0.36% | `python` | `_PyFunction_FromConstructor` | unknown |
| 0.36% | `python` | `PyObject_Str` | dynamic |
| 0.36% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.34% | `python` | `_Py_NewReference` | memory |
| 0.34% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.33% | `python` | `_PyEval_EnsureBuiltins` | interpreter |
| 0.32% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.32% | `python` | `func_dealloc` | memory |
| 0.31% | `python` | `builtin_eval` | unknown |
| 0.31% | `python` | `PyObject_IsInstance` | dynamic |
| 0.30% | `python` | `object_isinstance` | dynamic |
| 0.30% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.29% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.28% | `libc.so.6` | `_int_malloc` | libc |
| 0.28% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.27% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.27% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.27% | `python` | `func_clear` | unknown |
| 0.26% | `libc.so.6` | `malloc` | libc |
| 0.26% | `python` | `_PyEval_GetIter` | interpreter |
| 0.26% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.25% | `python` | `dictresize` | dict |

## go

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 56.75% | `[JIT]` | `jit` | jit |
| 14.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.29% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.18% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.68% | `python` | `initialize_locals` | interpreter |
| 1.32% | `python` | `long_bitwise` | int |
| 1.15% | `python` | `_Py_Dealloc` | memory |
| 1.12% | `python` | `insertdict` | dict |
| 1.10% | `python` | `_PyObject_Malloc` | memory |
| 1.03% | `python` | `_PyObject_Free` | memory |
| 1.02% | `python` | `_PyCompactLong_Add` | unknown |
| 0.99% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.73% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.67% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.53% | `python` | `set_lookkey` | miscobj |
| 0.51% | `python` | `PyNumber_InPlaceXor` | dynamic |
| 0.40% | `python` | `PyDict_SetItem` | dict |
| 0.37% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.35% | `python` | `long_alloc` | memory |
| 0.32% | `python` | `PyFloat_FromDouble` | float |
| 0.31% | `python` | `_Py_dict_lookup` | lookup |
| 0.30% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.29% | `python` | `long_dealloc` | memory |
| 0.28% | `python` | `set_add_entry_takeref` | miscobj |
| 0.27% | `_random.cpython-315-x86_64-linux-gnu.so` | `genrand_uint32` | library |
| 0.26% | `python` | `_Py_NewReference` | memory |

## hexiom

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 49.13% | `[JIT]` | `jit` | jit |
| 14.06% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.97% | `python` | `PyObject_RichCompareBool` | dynamic |
| 3.14% | `python` | `long_richcompare` | int |
| 3.09% | `python` | `list_contains` | list |
| 2.45% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.26% | `python` | `gen_iternext` | miscobj |
| 1.64% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.12% | `python` | `PyLong_FromSsize_t` | int |
| 0.96% | `python` | `_PyObject_Malloc` | memory |
| 0.92% | `python` | `PyObject_Size` | dynamic |
| 0.88% | `python` | `builtin_sum` | unknown |
| 0.83% | `python` | `PyLong_FromLong` | int |
| 0.81% | `python` | `_Py_Dealloc` | memory |
| 0.79% | `python` | `_PyObject_Free` | memory |
| 0.74% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.63% | `python` | `PyIter_Next` | dynamic |
| 0.56% | `python` | `make_range_object` | unknown |
| 0.45% | `python` | `PySequence_Contains` | dynamic |
| 0.44% | `python` | `range_iter` | miscobj |
| 0.40% | `python` | `_PyCompactLong_Add` | unknown |
| 0.37% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.34% | `python` | `list_dealloc` | memory |
| 0.34% | `python` | `PyList_New.constprop.0` | memory |
| 0.33% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.32% | `python` | `func_clear` | unknown |
| 0.31% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.31% | `python` | `_PyEval_GetIter` | interpreter |
| 0.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.28% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.27% | `python` | `gen_dealloc` | memory |
| 0.25% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |

## html5lib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.99% | `[JIT]` | `jit` | jit |
| 12.23% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.83% | `python` | `sre_ucs1_charset.isra.0` | library |
| 2.00% | `python` | `_PyObject_Malloc` | memory |
| 1.69% | `python` | `_Py_dict_lookup` | lookup |
| 1.67% | `python` | `PyDict_GetItemRef` | dict |
| 1.50% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.41% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.31% | `python` | `_Py_Dealloc` | memory |
| 1.13% | `python` | `_PyObject_Free` | memory |
| 0.94% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.94% | `python` | `PyObject_IsTrue` | dynamic |
| 0.90% | `python` | `gc_collect_region` | gc |
| 0.85% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.85% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.83% | `python` | `sre_ucs1_count` | library |
| 0.70% | `python` | `set_lookkey` | miscobj |
| 0.66% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.63% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.57% | `python` | `initialize_locals` | interpreter |
| 0.56% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `python` | `list_subscript` | list |
| 0.53% | `python` | `insertdict` | dict |
| 0.51% | `python` | `_PyGC_Collect` | gc |
| 0.51% | `python` | `_PyUnicode_Equal` | str |
| 0.50% | `libc.so.6` | `__strcmp_avx2` | libc |
| 0.48% | `python` | `sre_ucs1_match` | library |
| 0.47% | `python` | `visit_add_to_container` | gc |
| 0.41% | `libc.so.6` | `_int_malloc` | libc |
| 0.41% | `python` | `PyObject_GetItem` | dynamic |
| 0.41% | `python` | `list_contains` | list |
| 0.41% | `python` | `_PyDict_FromItems` | dict |
| 0.40% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.39% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.38% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.37% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.36% | `python` | `PyList_New.constprop.0` | memory |
| 0.34% | `libc.so.6` | `malloc` | libc |
| 0.34% | `python` | `insert_to_emptydict` | dict |
| 0.33% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.33% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.32% | `python` | `_PyCompactLong_Add` | unknown |
| 0.32% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.32% | `python` | `PyObject_RichCompare` | dynamic |
| 0.31% | `python` | `PyUnicode_Concat` | str |
| 0.28% | `python` | `object_richcompare` | dynamic |
| 0.27% | `python` | `_Py_BuildMap_StackRefSteal` | unknown |
| 0.26% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.26% | `python` | `visit_decref` | gc |
| 0.26% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.26% | `python` | `PySlice_AdjustIndices` | miscobj |

## json

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.66% | `_json.cpython-315-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 7.73% | `python` | `_PyObject_Malloc` | memory |
| 7.41% | `_json.cpython-315-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 5.38% | `python` | `_PyObject_Free` | memory |
| 5.21% | `python` | `siphash13` | str |
| 4.72% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.85% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.41% | `[JIT]` | `jit` | jit |
| 2.98% | `python` | `_Py_Dealloc` | memory |
| 2.66% | `python` | `PyLong_FromString` | int |
| 2.54% | `python` | `PyUnicode_Substring` | str |
| 2.51% | `python` | `_Py_dict_lookup` | lookup |
| 2.43% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 2.41% | `python` | `insertdict` | dict |
| 2.29% | `python` | `PyUnicode_New.part.0` | memory |
| 1.68% | `python` | `build_indices_unicode` | dict |
| 1.60% | `python` | `find_empty_slot.constprop.0` | dict |
| 1.25% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.09% | `libc.so.6` | `_int_malloc` | libc |
| 1.03% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 1.03% | `python` | `PyDict_SetItem` | dict |
| 0.86% | `python` | `initialize_locals` | interpreter |
| 0.84% | `python` | `unicode_dealloc` | memory |
| 0.65% | `python` | `dictresize` | dict |
| 0.64% | `python` | `insert_to_emptydict` | dict |
| 0.60% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.59% | `python` | `sre_ucs1_match` | library |
| 0.57% | `libc.so.6` | `malloc` | libc |
| 0.57% | `python` | `pattern_new_match` | memory |
| 0.49% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.48% | `python` | `new_keys_object` | dict |
| 0.47% | `python` | `_Py_NewReference` | memory |
| 0.47% | `python` | `PyDict_GetItemRef` | dict |
| 0.46% | `python` | `unicode_hash` | str |
| 0.41% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.39% | `python` | `PyObject_Malloc` | dynamic |
| 0.39% | `python` | `maybe_small_long` | unknown |
| 0.37% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.37% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.35% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.35% | `python` | `PyDict_New` | memory |
| 0.35% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.34% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.34% | `python` | `_PyObject_Realloc` | memory |
| 0.33% | `libc.so.6` | `_int_free` | libc |
| 0.33% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.31% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.31% | `python` | `long_alloc` | memory |
| 0.31% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.30% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.28% | `python` | `convertitem.constprop.0` | unknown |
| 0.27% | `python` | `PyObject_Hash` | dynamic |
| 0.27% | `python` | `Py_HashBuffer` | unknown |
| 0.26% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 0.26% | `python` | `long_dealloc` | memory |
| 0.26% | `python` | `tuple_dealloc` | memory |
| 0.26% | `libc.so.6` | `cfree@GLIBC_2.2.5` | libc |

## json_dumps

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 5.78% | `[JIT]` | `jit` | jit |
| 5.65% | `_json.cpython-315-x86_64-linux-gnu.so` | `ascii_escape_size` | library |
| 4.86% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 4.50% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 4.45% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 4.41% | `python` | `_PyUnicode_ResizeCompact` | str |
| 4.00% | `_json.cpython-315-x86_64-linux-gnu.so` | `encoder_listencode_obj` | library |
| 3.86% | `python` | `_PyObject_Malloc` | memory |
| 3.16% | `python` | `_Py_dict_lookup` | lookup |
| 2.76% | `python` | `PyDict_Next` | dict |
| 2.67% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 2.44% | `_json.cpython-315-x86_64-linux-gnu.so` | `write_escaped_ascii` | library |
| 2.37% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.22% | `_json.cpython-315-x86_64-linux-gnu.so` | `encoder_encode_key_value` | library |
| 2.13% | `python` | `_Py_Dealloc` | memory |
| 2.12% | `python` | `convertitem.constprop.0` | unknown |
| 2.02% | `python` | `_PyObject_Free` | memory |
| 1.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.92% | `python` | `PyUnicodeWriter_WriteStr` | str |
| 1.75% | `python` | `PyDict_GetItemRef` | dict |
| 1.69% | `python` | `_PyObject_Realloc` | memory |
| 1.52% | `python` | `initialize_locals` | interpreter |
| 1.35% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.32% | `python` | `long_to_decimal_string_internal` | int |
| 1.19% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 1.14% | `python` | `tuple_dealloc` | memory |
| 1.04% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.87% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.83% | `python` | `tuple_alloc` | memory |
| 0.76% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.75% | `python` | `PyTuple_FromArray` | tuple |
| 0.68% | `python` | `PyType_IsSubtype` | dynamic |
| 0.66% | `_json.cpython-315-x86_64-linux-gnu.so` | `encoder_write_string` | library |
| 0.61% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.58% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.58% | `python` | `delitem_common` | dynamic |
| 0.52% | `python` | `long_hash` | int |
| 0.48% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.48% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.48% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.46% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.45% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.43% | `python` | `memcpy@plt` | memory |
| 0.42% | `python` | `_Py_NewReference` | memory |
| 0.39% | `_json.cpython-315-x86_64-linux-gnu.so` | `PyUnicodeWriter_WriteStr@plt` | library |
| 0.39% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.38% | `python` | `insertdict` | dict |
| 0.37% | `python` | `_PyUnicode_FastCopyCharacters` | str |
| 0.37% | `python` | `PyDict_DelItem` | dict |
| 0.37% | `_json.cpython-315-x86_64-linux-gnu.so` | `ascii_escape_unicode_and_size` | library |
| 0.37% | `_json.cpython-315-x86_64-linux-gnu.so` | `PyUnicodeWriter_WriteChar@plt` | library |
| 0.34% | `python` | `func_clear` | unknown |
| 0.33% | `python` | `new_dict` | dict |
| 0.32% | `python` | `long_alloc` | memory |
| 0.32% | `_json.cpython-315-x86_64-linux-gnu.so` | `encoder_new` | library |
| 0.31% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.31% | `python` | `func_dealloc` | memory |
| 0.30% | `python` | `dict_dealloc` | memory |
| 0.30% | `python` | `PyObject_IsTrue` | dynamic |
| 0.29% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.29% | `python` | `PyUnicodeWriter_Create` | str |
| 0.28% | `python` | `PyUnicodeWriter_Finish` | str |
| 0.28% | `python` | `insert_to_emptydict` | dict |
| 0.26% | `python` | `PyLong_FromVoidPtr` | int |
| 0.25% | `python` | `object_recursive_isinstance` | dynamic |
| 0.25% | `python` | `PyDict_New` | memory |

## json_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.17% | `_json.cpython-315-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 8.39% | `python` | `_PyObject_Malloc` | memory |
| 8.31% | `_json.cpython-315-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.82% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 6.01% | `python` | `siphash13` | str |
| 5.37% | `python` | `_PyObject_Free` | memory |
| 4.14% | `python` | `PyUnicode_Substring` | str |
| 3.42% | `python` | `PyUnicode_New.part.0` | memory |
| 3.40% | `python` | `PyLong_FromString` | int |
| 3.38% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.23% | `python` | `_Py_Dealloc` | memory |
| 3.13% | `python` | `_Py_dict_lookup` | lookup |
| 3.11% | `python` | `insertdict` | dict |
| 1.48% | `python` | `find_empty_slot.constprop.0` | dict |
| 1.38% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 1.37% | `[JIT]` | `jit` | jit |
| 1.29% | `python` | `PyDict_SetItem` | dict |
| 1.25% | `python` | `unicode_dealloc` | memory |
| 1.19% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.06% | `python` | `build_indices_unicode` | dict |
| 0.69% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.64% | `python` | `_Py_NewReference` | memory |
| 0.62% | `python` | `unicode_hash` | str |
| 0.58% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.57% | `python` | `PyObject_Malloc` | dynamic |
| 0.56% | `libc.so.6` | `_int_malloc` | libc |
| 0.42% | `python` | `dictresize` | dict |
| 0.42% | `libc.so.6` | `malloc` | libc |
| 0.41% | `python` | `initialize_locals` | interpreter |
| 0.40% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.39% | `python` | `PyList_Append` | list |
| 0.36% | `python` | `sre_ucs1_match` | library |
| 0.35% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.34% | `python` | `maybe_small_long` | unknown |
| 0.34% | `python` | `long_alloc` | memory |
| 0.33% | `python` | `insert_to_emptydict` | dict |
| 0.32% | `python` | `Py_HashBuffer` | unknown |
| 0.31% | `python` | `PyObject_Hash` | dynamic |
| 0.30% | `python` | `new_keys_object` | dict |
| 0.29% | `_json.cpython-315-x86_64-linux-gnu.so` | `PyUnicode_Substring@plt` | library |
| 0.28% | `python` | `PyDict_GetItemRef` | dict |
| 0.28% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.28% | `python` | `list_dealloc` | memory |
| 0.27% | `python` | `PyObject_Free` | dynamic |

## logging

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.34% | `[JIT]` | `jit` | jit |
| 6.30% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.44% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.60% | `python` | `_Py_dict_lookup` | lookup |
| 2.54% | `python` | `initialize_locals` | interpreter |
| 2.52% | `python` | `PyCode_Addr2Line` | exceptions |
| 2.51% | `python` | `_Py_Dealloc` | memory |
| 2.34% | `python` | `_PyObject_Malloc` | memory |
| 2.10% | `python` | `PyDict_New` | memory |
| 2.04% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 2.01% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.83% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.69% | `[unknown]` | `0xffffffffab6001c6` | unknown |
| 1.60% | `python` | `dict_dealloc` | memory |
| 1.36% | `python` | `PyDict_GetItemRef` | dict |
| 1.35% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.25% | `python` | `_PyObject_Free` | memory |
| 1.08% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.89% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.76% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.76% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.71% | `[unknown]` | `0xffffffffab600151` | unknown |
| 0.68% | `[unknown]` | `0xffffffffab60010f` | unknown |
| 0.67% | `python` | `PyUnicode_Format` | str |
| 0.62% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.61% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.53% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.50% | `python` | `PyUnicode_Contains` | str |
| 0.47% | `[unknown]` | `0xffffffffab6001bd` | unknown |
| 0.46% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.46% | `python` | `PyObject_Hash` | dynamic |
| 0.45% | `python` | `PyLong_FromLong` | int |
| 0.43% | `python` | `any_find_slice` | unknown |
| 0.43% | `[unknown]` | `0xffffffffab60009d` | unknown |
| 0.42% | `python` | `_Py_NewReference` | memory |
| 0.37% | `python` | `_PyLong_Frexp` | int |
| 0.37% | `python` | `PyUnicode_AsUCS4` | str |
| 0.34% | `python` | `long_hash` | int |
| 0.32% | `python` | `_PyObject_VectorcallPrepend` | dynamic |
| 0.32% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.31% | `python` | `tuple_alloc` | memory |
| 0.30% | `python` | `PyType_IsSubtype` | dynamic |
| 0.29% | `python` | `l_mod` | int |
| 0.29% | `python` | `_PyUnicode_BinarySlice` | str |
| 0.28% | `python` | `sys_audit_tstate` | unknown |
| 0.28% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.27% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.27% | `python` | `tuple_dealloc` | memory |
| 0.26% | `python` | `PyNumber_TrueDivide` | dynamic |
| 0.26% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRefSteal` | unknown |
| 0.25% | `python` | `PyUnicode_Splitlines` | str |
| 0.25% | `python` | `_PyType_GetDict` | dynamic |

## mako

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.69% | `[JIT]` | `jit` | jit |
| 9.67% | `python` | `replace` | str |
| 6.49% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRefSteal` | unknown |
| 5.84% | `python` | `long_to_decimal_string_internal` | int |
| 5.42% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 4.58% | `python` | `_PyObject_Malloc` | memory |
| 3.86% | `python` | `unicode_replace` | str |
| 3.38% | `python` | `_PyObject_Free` | memory |
| 3.11% | `python` | `deque_append` | miscobj |
| 2.63% | `python` | `dequeiter_next` | miscobj |
| 2.16% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.50% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.47% | `python` | `PyObject_Str` | dynamic |
| 1.44% | `python` | `_list_extend` | list |
| 1.43% | `python` | `PyUnicode_New` | memory |
| 1.03% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.01% | `python` | `list_dealloc` | memory |
| 0.98% | `python` | `_Py_Dealloc` | memory |
| 0.98% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.97% | `python` | `deque_clear.part.0` | miscobj |
| 0.90% | `python` | `long_alloc` | memory |
| 0.82% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.68% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.62% | `python` | `unicode_dealloc` | memory |
| 0.59% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.57% | `python` | `PyThread_get_thread_ident` | threading |
| 0.56% | `python` | `_Py_IsMainThread` | unknown |
| 0.54% | `python` | `PyLong_FromLong` | int |
| 0.41% | `python` | `long_to_decimal_string` | int |
| 0.41% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.38% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.37% | `[unknown]` | `0xffffffffab601631` | unknown |
| 0.34% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.34% | `[unknown]` | `0xffffffffab6011a9` | unknown |
| 0.31% | `python` | `memcpy@plt` | memory |
| 0.29% | `[unknown]` | `0xffffffffab44a16e` | unknown |
| 0.29% | `python` | `PyObject_Malloc` | dynamic |

## mdp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.52% | `[JIT]` | `jit` | jit |
| 11.12% | `python` | `_Py_dict_lookup` | lookup |
| 11.04% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.17% | `python` | `PyObject_RichCompareBool` | dynamic |
| 4.50% | `python` | `tuple_richcompare` | tuple |
| 2.51% | `python` | `_PyLong_GCD` | int |
| 2.33% | `python` | `dict_subscript` | dict |
| 1.77% | `python` | `_Py_Dealloc` | memory |
| 1.63% | `python` | `_PyObject_Malloc` | memory |
| 1.59% | `python` | `PyDict_GetItemRef` | dict |
| 1.49% | `python` | `gen_iternext` | miscobj |
| 1.42% | `python` | `_PyObject_Free` | memory |
| 1.37% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.33% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.32% | `python` | `builtin_sum` | unknown |
| 1.03% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.91% | `python` | `PyObject_GetItem` | dynamic |
| 0.91% | `python` | `tuple_hash` | tuple |
| 0.77% | `python` | `subtype_dealloc` | memory |
| 0.70% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRefSteal` | unknown |
| 0.70% | `python` | `insertdict` | dict |
| 0.61% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.60% | `python` | `PyObject_Hash` | dynamic |
| 0.59% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.59% | `python` | `gen_dealloc` | memory |
| 0.58% | `python` | `set_lookkey` | miscobj |
| 0.52% | `python` | `func_clear` | unknown |
| 0.51% | `python` | `PyFloat_FromDouble` | float |
| 0.49% | `python` | `long_div` | int |
| 0.47% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.46% | `python` | `do_super_lookup` | dynamic |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.43% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.43% | `python` | `_PyCompactLong_Multiply` | unknown |
| 0.41% | `python` | `_Py_NewReference` | memory |
| 0.41% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.40% | `python` | `PyIter_Next` | dynamic |
| 0.40% | `python` | `PyLong_FromLong` | int |
| 0.36% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.36% | `python` | `initialize_locals` | interpreter |
| 0.34% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.34% | `python` | `func_dealloc` | memory |
| 0.32% | `python` | `make_gen` | miscobj |
| 0.30% | `python` | `PyType_IsSubtype` | dynamic |
| 0.30% | `python` | `PyObject_SetItem` | dynamic |
| 0.30% | `python` | `tp_new_wrapper` | memory |
| 0.29% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.28% | `python` | `tuple_alloc` | memory |
| 0.27% | `python` | `_Py_type_getattro` | lookup |
| 0.26% | `python` | `min_max` | unknown |

## meteor_contest

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.91% | `[JIT]` | `jit` | jit |
| 12.34% | `python` | `set_issubset_impl` | miscobj |
| 11.40% | `python` | `set_lookkey` | miscobj |
| 9.33% | `python` | `setiter_iternext` | miscobj |
| 4.64% | `python` | `set_difference` | miscobj |
| 4.05% | `python` | `set_dealloc` | memory |
| 3.35% | `python` | `PyObject_RichCompareBool` | dynamic |
| 3.17% | `python` | `set_add_entry_takeref` | miscobj |
| 2.44% | `python` | `_PyObject_Malloc` | memory |
| 2.26% | `python` | `_PyObject_Free` | memory |
| 2.19% | `python` | `list_slice_lock_held` | list |
| 1.71% | `python` | `long_richcompare` | int |
| 1.70% | `python` | `list_dealloc` | memory |
| 1.53% | `python` | `min_max` | unknown |
| 1.38% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.24% | `python` | `PyObject_RichCompare` | dynamic |
| 1.22% | `python` | `set_table_resize` | miscobj |
| 1.18% | `python` | `set_intersection` | miscobj |
| 1.17% | `python` | `set_merge_lock_held` | miscobj |
| 1.10% | `python` | `PyIter_Next` | dynamic |
| 1.02% | `python` | `_Py_Dealloc` | memory |
| 0.84% | `python` | `set_richcompare` | miscobj |
| 0.78% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.65% | `python` | `set_difference_update_internal` | miscobj |
| 0.57% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.46% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.46% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.42% | `python` | `PyList_New.constprop.0` | memory |
| 0.39% | `python` | `initialize_locals` | interpreter |
| 0.39% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.37% | `python` | `set_iter` | miscobj |
| 0.34% | `python` | `PyObject_Size` | dynamic |
| 0.32% | `python` | `_PyEval_GetIter` | interpreter |
| 0.29% | `python` | `PyLong_FromSsize_t` | int |
| 0.29% | `python` | `list_ass_slice_lock_held` | list |
| 0.28% | `python` | `PyObject_IsTrue` | dynamic |
| 0.27% | `python` | `_PyObject_GC_New` | gc |
| 0.25% | `python` | `PyObject_GC_Del` | gc |
| 0.25% | `python` | `PyType_GenericAlloc` | memory |

## nbody

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 60.89% | `[JIT]` | `jit` | jit |
| 10.60% | `python` | `PyFloat_FromDouble` | float |
| 9.34% | `python` | `_Py_Dealloc` | memory |
| 5.61% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 4.29% | `python` | `_Py_NewReference` | memory |
| 2.76% | `python` | `_PyFloat_ExactDealloc` | memory |
| 2.64% | `python` | `float_dealloc` | memory |
| 1.60% | `python` | `float_pow` | float |
| 0.83% | `python` | `_PyNumber_PowerNoMod` | dynamic |
| 0.54% | `libm.so.6` | `pow@@GLIBC_2.29` | library |
| 0.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |

## networkx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.45% | `python` | `set_lookkey` | miscobj |
| 21.10% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 15.46% | `python` | `dictiter_iternextkey` | dict |
| 9.96% | `[JIT]` | `jit` | jit |
| 5.98% | `python` | `build_indices_unicode` | dict |
| 2.55% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.35% | `python` | `PyDict_GetItemRef` | dict |
| 1.17% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.16% | `python` | `set_dealloc` | memory |
| 1.15% | `python` | `_PySet_Contains` | miscobj |
| 0.92% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.85% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.83% | `python` | `list_dealloc` | memory |
| 0.78% | `python` | `deque_clear.part.0` | miscobj |
| 0.55% | `python` | `set_table_resize` | miscobj |
| 0.53% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.49% | `python` | `_Py_dict_lookup` | lookup |
| 0.45% | `python` | `_PyObject_Free` | memory |
| 0.45% | `python` | `_Py_Dealloc` | memory |
| 0.40% | `python` | `insertdict` | dict |
| 0.38% | `python` | `set_add_entry_takeref` | miscobj |
| 0.29% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `merge_from_seq2_lock_held` | unknown |
| 0.26% | `python` | `gen_iternext` | miscobj |

## networkx_connected_components

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.87% | `python` | `set_lookkey` | miscobj |
| 16.18% | `python` | `dictiter_iternextkey` | dict |
| 15.42% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 11.63% | `[JIT]` | `jit` | jit |
| 3.30% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.68% | `python` | `PyDict_GetItemRef` | dict |
| 2.52% | `python` | `set_dealloc` | memory |
| 1.59% | `python` | `set_merge_lock_held` | miscobj |
| 1.46% | `python` | `_PySet_Contains` | miscobj |
| 1.11% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.94% | `python` | `list_dealloc` | memory |
| 0.70% | `python` | `set_table_resize` | miscobj |
| 0.59% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.47% | `python` | `_PyObject_Free` | memory |
| 0.39% | `python` | `set_add_entry_takeref` | miscobj |
| 0.31% | `python` | `_Py_dict_lookup` | lookup |
| 0.26% | `python` | `dict_iter` | dict |

## networkx_k_core

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.42% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 14.68% | `[JIT]` | `jit` | jit |
| 7.59% | `python` | `list_remove` | list |
| 6.53% | `python` | `PyDict_GetItemRef` | dict |
| 4.13% | `python` | `dictiter_iternextkey` | dict |
| 3.42% | `python` | `_Py_dict_lookup` | lookup |
| 1.80% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.74% | `python` | `build_indices_unicode` | dict |
| 1.59% | `python` | `visit_add_to_container` | gc |
| 1.46% | `python` | `list_dealloc` | memory |
| 1.33% | `python` | `PyUnicode_RichCompare` | str |
| 1.26% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.07% | `python` | `listiter_next` | list |
| 0.99% | `python` | `insertdict` | dict |
| 0.83% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.72% | `python` | `mark_all_reachable` | unknown |
| 0.58% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.45% | `python` | `_PyObject_Malloc` | memory |
| 0.40% | `python` | `list_sort_impl` | list |
| 0.36% | `python` | `_Py_Dealloc` | memory |
| 0.35% | `python` | `list_ass_slice_lock_held` | list |
| 0.32% | `python` | `dict_traverse` | gc |
| 0.30% | `python` | `dictiter_iternextitem` | dict |
| 0.29% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.27% | `python` | `_PyDict_Next` | dict |

## nqueens

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 41.84% | `[JIT]` | `jit` | jit |
| 4.17% | `python` | `_PyObject_Malloc` | memory |
| 3.60% | `python` | `_Py_Dealloc` | memory |
| 3.56% | `python` | `_PyObject_Free` | memory |
| 3.27% | `python` | `set_add_entry_takeref` | miscobj |
| 2.82% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.78% | `python` | `set_dealloc` | memory |
| 1.42% | `python` | `list_dealloc` | memory |
| 1.41% | `python` | `PyList_New.constprop.0` | memory |
| 1.29% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.24% | `python` | `_PyCompactLong_Add` | unknown |
| 1.18% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.07% | `python` | `PyFunction_NewWithQualName` | memory |
| 1.04% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.03% | `python` | `func_clear` | unknown |
| 0.92% | `python` | `set_table_resize` | miscobj |
| 0.91% | `python` | `gen_dealloc` | memory |
| 0.85% | `python` | `PyLong_FromLong` | int |
| 0.83% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.80% | `python` | `list_slice_lock_held` | list |
| 0.79% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.75% | `python` | `list_ass_slice_lock_held` | list |
| 0.73% | `python` | `_PyList_BinarySlice` | list |
| 0.73% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.73% | `python` | `list_ass_subscript` | list |
| 0.72% | `python` | `make_range_object` | unknown |
| 0.69% | `python` | `_PyObject_Realloc` | memory |
| 0.67% | `python` | `tuple_dealloc` | memory |
| 0.66% | `python` | `range_iter` | miscobj |
| 0.66% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.65% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.62% | `python` | `_Py_NewReference` | memory |
| 0.58% | `python` | `PyTuple_FromArray` | tuple |
| 0.56% | `python` | `PyLong_AsLong` | int |
| 0.55% | `python` | `_PySet_AddTakeRef` | miscobj |
| 0.55% | `python` | `func_dealloc` | memory |
| 0.53% | `python` | `range_reverse` | miscobj |
| 0.51% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.51% | `python` | `make_gen` | miscobj |
| 0.48% | `python` | `tuple_alloc` | memory |
| 0.48% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.45% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 0.44% | `python` | `PyCMethod_New` | memory |
| 0.41% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.40% | `python` | `long_hash` | int |
| 0.40% | `python` | `_Py_dict_lookup` | lookup |
| 0.39% | `python` | `PyDict_GetItemRef` | dict |
| 0.37% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.33% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.33% | `python` | `list_concat` | list |
| 0.31% | `python` | `_PyEval_GetIter` | interpreter |
| 0.31% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.31% | `python` | `PyObject_Hash` | dynamic |
| 0.31% | `python` | `_PyObject_GC_New` | gc |
| 0.28% | `python` | `long_neg_method` | int |
| 0.27% | `python` | `PyObject_GC_Del` | gc |
| 0.26% | `python` | `_PyObject_LookupSpecial` | dynamic |
| 0.25% | `python` | `reversed_new_impl` | memory |

## pathlib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.63% | `[JIT]` | `jit` | jit |
| 3.68% | `python` | `_PyObject_Malloc` | memory |
| 3.49% | `[unknown]` | `0xffffffffab6001c6` | unknown |
| 3.28% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.87% | `python` | `_PyObject_Free` | memory |
| 2.53% | `python` | `_Py_Dealloc` | memory |
| 1.83% | `[unknown]` | `0xffffffffab600151` | unknown |
| 1.61% | `[unknown]` | `0xffffffffab60010f` | unknown |
| 1.22% | `[unknown]` | `0xffffffffab60009d` | unknown |
| 1.22% | `python` | `subtype_dealloc` | memory |
| 1.20% | `[unknown]` | `0xffffffffab6001bd` | unknown |
| 1.13% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.98% | `python` | `initialize_locals` | interpreter |
| 0.98% | `python` | `take_gil` | gil |
| 0.96% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.89% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.86% | `python` | `PyLong_FromLongLong` | int |
| 0.77% | `[unknown]` | `0xffffffffab450653` | unknown |
| 0.75% | `python` | `_pystat_fromstructstat` | unknown |
| 0.70% | `python` | `sre_ucs1_match` | library |
| 0.67% | `python` | `structseq_dealloc` | memory |
| 0.65% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.61% | `[unknown]` | `0xffffffffab45065a` | unknown |
| 0.60% | `[unknown]` | `0xffffffffaa71b26f` | unknown |
| 0.60% | `libc.so.6` | `__GI___readdir64` | libc |
| 0.56% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.54% | `[unknown]` | `0xffffffffab450662` | unknown |
| 0.50% | `[unknown]` | `0xffffffffab45065e` | unknown |
| 0.50% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.48% | `python` | `drop_gil` | gil |
| 0.45% | `python` | `_PyEval_Vector` | interpreter |
| 0.45% | `[unknown]` | `0xffffffffab450656` | unknown |
| 0.44% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.43% | `python` | `find_first_nonascii` | str |
| 0.42% | `libc.so.6` | `_int_malloc` | libc |
| 0.41% | `python` | `ScandirIterator_iternext` | unknown |
| 0.40% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.39% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.38% | `[unknown]` | `0xffffffffaa7dff36` | unknown |
| 0.38% | `[unknown]` | `0xffffffffaa71b24e` | unknown |
| 0.38% | `[unknown]` | `0xffffffffaa8f2e8d` | unknown |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.37% | `libc.so.6` | `__GI___fstatat64` | libc |
| 0.37% | `python` | `long_dealloc` | memory |
| 0.36% | `python` | `fill_time` | unknown |
| 0.36% | `[unknown]` | `0xffffffffab450666` | unknown |
| 0.36% | `[unknown]` | `0xffffffffaa96832a` | unknown |
| 0.35% | `python` | `os_stat` | unknown |
| 0.35% | `[unknown]` | `0xffffffffab45066a` | unknown |
| 0.35% | `python` | `path_converter` | unknown |
| 0.34% | `python` | `tuple_dealloc` | memory |
| 0.33% | `python` | `PyUnicode_New.part.0` | memory |
| 0.33% | `python` | `tp_new_wrapper` | memory |
| 0.32% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.31% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.30% | `[unknown]` | `0xffffffffab45066e` | unknown |
| 0.30% | `python` | `_Py_dict_lookup` | lookup |
| 0.30% | `python` | `PyDict_New` | memory |
| 0.29% | `python` | `PyStructSequence_SetItem` | unknown |
| 0.29% | `python` | `PyDict_GetItemWithError` | dict |
| 0.29% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.28% | `[unknown]` | `0xffffffffaa806049` | unknown |
| 0.28% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.27% | `python` | `_PyType_GetDict` | dynamic |
| 0.27% | `libc.so.6` | `pthread_cond_signal@@GLIBC_2.3.2` | libc |
| 0.27% | `[unknown]` | `0xffffffffaa6fba44` | unknown |
| 0.27% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.27% | `[unknown]` | `0xffffffffab6001cd` | unknown |
| 0.26% | `libc.so.6` | `malloc` | libc |
| 0.26% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRefSteal` | unknown |
| 0.26% | `[unknown]` | `0xffffffffaa667246` | unknown |
| 0.26% | `python` | `_PyThreadState_PushFrame` | threading |

## pickle

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.59% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save.constprop.0` | library |
| 9.67% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 9.39% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 6.81% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_dict` | library |
| 5.91% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_unicode` | library |
| 3.97% | `python` | `PyDict_Next` | dict |
| 3.87% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `memo_put` | library |
| 3.09% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 2.99% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 2.70% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 2.53% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.0` | library |
| 2.02% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `memo_get` | library |
| 1.75% | `python` | `_PyObject_Malloc` | memory |
| 1.69% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.20% | `python` | `_PyObject_Free` | memory |
| 1.17% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_list` | library |
| 1.13% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.07% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_long` | library |
| 0.77% | `libc.so.6` | `_int_malloc` | libc |
| 0.73% | `python` | `_Py_Dealloc` | memory |
| 0.61% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.57% | `python` | `unicode_from_format` | str |
| 0.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.49% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.49% | `python` | `_Py_dict_lookup` | lookup |
| 0.42% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.40% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.39% | `python` | `PyCMethod_New` | memory |
| 0.35% | `python` | `_PyObject_Realloc` | memory |
| 0.34% | `python` | `do_mkvalue` | unknown |
| 0.33% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.33% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.31% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyUnicode_AsUTF8AndSize@plt` | library |
| 0.30% | `python` | `unicode_fromformat_write_utf8` | str |
| 0.27% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.26% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.25% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.25% | `python` | `PyDict_GetItemRef` | dict |
| 0.25% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Pickler_New` | library |
| 0.25% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `memcpy@plt` | library |
| 0.25% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRefSteal` | unknown |
| 0.25% | `python` | `PyObject_GC_UnTrack` | gc |

## pickle_dict

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.40% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save.constprop.0` | library |
| 18.35% | `python` | `PyDict_Next` | dict |
| 15.90% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_dict` | library |
| 11.22% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_long` | library |
| 7.89% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 7.53% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.0` | library |
| 3.82% | `python` | `PyLong_AsLongAndOverflow` | int |
| 2.38% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 1.05% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `memo_put` | library |
| 1.02% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 0.88% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.81% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyDict_Next@plt` | library |
| 0.72% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyLong_AsLongAndOverflow@plt` | library |

## pickle_list

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.90% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save.constprop.0` | library |
| 20.20% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_list` | library |
| 14.19% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_long` | library |
| 11.78% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 4.89% | `python` | `PyLong_AsLongAndOverflow` | int |
| 4.41% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 3.81% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.0` | library |
| 2.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.49% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 1.36% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `memo_put` | library |
| 1.11% | `python` | `_PyObject_Malloc` | memory |
| 0.91% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyLong_AsLongAndOverflow@plt` | library |
| 0.73% | `python` | `_PyObject_Free` | memory |
| 0.63% | `python` | `PyList_Size` | list |
| 0.54% | `libc.so.6` | `_int_malloc` | libc |
| 0.52% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.48% | `python` | `unicode_from_format` | str |
| 0.39% | `python` | `_Py_Dealloc` | memory |
| 0.36% | `python` | `_PyThreadState_GetCurrent` | threading |
| 0.31% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.28% | `python` | `_PyObject_Realloc` | memory |
| 0.27% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.25% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_PyThreadState_GetCurrent@plt` | library |

## pickle_pure_python

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.39% | `[JIT]` | `jit` | jit |
| 5.03% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.33% | `python` | `_Py_dict_lookup` | lookup |
| 3.91% | `python` | `_PyObject_Malloc` | memory |
| 3.25% | `python` | `_PyObject_Free` | memory |
| 2.71% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.90% | `python` | `initialize_locals` | interpreter |
| 1.83% | `python` | `_Py_Dealloc` | memory |
| 1.36% | `python` | `tuple_dealloc` | memory |
| 1.26% | `libc.so.6` | `__strlen_avx2` | libc |
| 1.23% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 1.20% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 1.12% | `python` | `PyBuffer_FillInfo` | miscobj |
| 1.05% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.01% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.98% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.97% | `python` | `write_bytes_lock_held` | unknown |
| 0.97% | `python` | `PyBuffer_Release` | miscobj |
| 0.95% | `python` | `dict_get` | dict |
| 0.91% | `python` | `PyDict_GetItemRef` | dict |
| 0.88% | `python` | `bytes_concat` | str |
| 0.79% | `python` | `PyLong_FromSsize_t` | int |
| 0.79% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.68% | `python` | `tuple_alloc` | memory |
| 0.61% | `python` | `_PyTuple_Resize` | tuple |
| 0.59% | `python` | `PyLong_FromVoidPtr` | int |
| 0.58% | `_struct.cpython-315-x86_64-linux-gnu.so` | `pack` | library |
| 0.57% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.57% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.55% | `python` | `sys_audit_tstate` | unknown |
| 0.55% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.54% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.54% | `python` | `unicode_encode` | str |
| 0.50% | `python` | `PyNumber_Add` | dynamic |
| 0.50% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.48% | `python` | `insertdict` | dict |
| 0.47% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.45% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.43% | `_struct.cpython-315-x86_64-linux-gnu.so` | `s_pack_internal` | library |
| 0.41% | `python` | `PySys_Audit` | unknown |
| 0.41% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.40% | `python` | `PyObject_Malloc` | dynamic |
| 0.38% | `python` | `dictiter_iternextitem` | dict |
| 0.38% | `python` | `long_hash` | int |
| 0.38% | `python` | `PyObject_Size` | dynamic |
| 0.36% | `python` | `_PyObject_Realloc` | memory |
| 0.35% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRefSteal` | unknown |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.31% | `python` | `PyBytes_FromStringAndSize.constprop.0` | str |
| 0.30% | `python` | `bytes_buffer_getbuffer` | str |
| 0.30% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `long_dealloc` | memory |
| 0.28% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `PyObject_Hash` | dynamic |
| 0.27% | `libc.so.6` | `_int_malloc` | libc |
| 0.26% | `python` | `builtin_id` | unknown |

## pidigits

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.60% | `python` | `x_divrem` | int |
| 30.21% | `python` | `k_mul` | int |
| 14.51% | `python` | `x_add` | int |
| 6.63% | `python` | `x_sub` | int |
| 2.88% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.83% | `libc.so.6` | `_int_malloc` | libc |
| 1.00% | `[JIT]` | `jit` | jit |
| 0.47% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.43% | `python` | `_Py_Dealloc` | memory |
| 0.40% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.30% | `python` | `_PyObject_Free` | memory |
| 0.30% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.26% | `python` | `long_alloc` | memory |
| 0.26% | `python` | `_PyObject_Malloc` | memory |

## pprint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 30.36% | `[JIT]` | `jit` | jit |
| 5.05% | `python` | `_PyObject_Malloc` | memory |
| 3.89% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.64% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 3.55% | `python` | `_PyObject_Free` | memory |
| 2.78% | `python` | `_Py_Dealloc` | memory |
| 2.17% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.02% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.84% | `python` | `_Py_type_getattro_impl` | dynamic |
| 1.83% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.68% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.62% | `python` | `long_to_decimal_string_internal` | int |
| 1.43% | `python` | `PyUnicode_Format` | str |
| 1.27% | `python` | `_Py_dict_lookup` | lookup |
| 1.25% | `python` | `tuple_dealloc` | memory |
| 1.13% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.97% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.95% | `python` | `set_lookkey` | miscobj |
| 0.92% | `python` | `PyObject_IsSubclass` | dynamic |
| 0.88% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.86% | `python` | `tuple_alloc` | memory |
| 0.68% | `python` | `list_sort_impl` | list |
| 0.67% | `python` | `PyType_IsSubtype` | dynamic |
| 0.67% | `python` | `_PyObject_Realloc` | memory |
| 0.67% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.66% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.66% | `python` | `PyUnicode_New` | memory |
| 0.66% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.65% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.59% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.55% | `python` | `recursive_issubclass` | unknown |
| 0.55% | `python` | `initialize_locals` | interpreter |
| 0.51% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.49% | `python` | `list_append` | list |
| 0.47% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.47% | `python` | `_Py_NewReference` | memory |
| 0.47% | `python` | `subtype_dealloc` | memory |
| 0.46% | `python` | `PyObject_Repr` | dynamic |
| 0.45% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.45% | `python` | `list_dealloc` | memory |
| 0.42% | `python` | `PyCMethod_New` | memory |
| 0.42% | `python` | `_PyUnicodeWriter_WriteSubstring` | str |
| 0.40% | `python` | `PyObject_Hash` | dynamic |
| 0.40% | `python` | `unicode_repr` | str |
| 0.40% | `python` | `_PySet_Contains` | miscobj |
| 0.39% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.39% | `python` | `PyList_New.constprop.0` | memory |
| 0.38% | `python` | `unicode_dealloc` | memory |
| 0.34% | `python` | `PyObject_DelItem` | dynamic |
| 0.34% | `python` | `PyUnicode_New.part.0` | memory |
| 0.34% | `python` | `insertdict` | dict |
| 0.32% | `python` | `delitem_common` | dynamic |
| 0.32% | `python` | `_Py_BuildString_StackRefSteal` | unknown |
| 0.30% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.30% | `python` | `builtin_getattr` | lookup |
| 0.30% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.28% | `python` | `_PyEval_Vector` | interpreter |
| 0.28% | `python` | `PyTuple_FromArray` | tuple |
| 0.28% | `python` | `builtin_issubclass` | unknown |
| 0.28% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.27% | `python` | `long_hash` | int |
| 0.27% | `python` | `PyObject_Malloc` | dynamic |
| 0.25% | `python` | `PyType_GenericAlloc` | memory |
| 0.25% | `python` | `_Py_IsMainThread` | unknown |

## pycparser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.75% | `[JIT]` | `jit` | jit |
| 11.17% | `python` | `sre_ucs1_match` | library |
| 8.42% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.50% | `python` | `_Py_dict_lookup` | lookup |
| 2.29% | `python` | `gc_collect_region` | gc |
| 2.22% | `python` | `_PyObject_Malloc` | memory |
| 2.00% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.60% | `python` | `PyDict_GetItemRef` | dict |
| 1.58% | `python` | `_PyObject_Free` | memory |
| 1.52% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.28% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.28% | `python` | `_Py_Dealloc` | memory |
| 1.17% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.03% | `libc.so.6` | `_int_malloc` | libc |
| 0.88% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.86% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.83% | `python` | `visit_add_to_container` | gc |
| 0.82% | `python` | `pattern_new_match` | memory |
| 0.81% | `python` | `list_ass_slice_lock_held` | list |
| 0.79% | `python` | `initialize_locals` | interpreter |
| 0.76% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.75% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.70% | `python` | `PySlice_New` | memory |
| 0.69% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.65% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.65% | `python` | `sre_ucs1_count` | library |
| 0.64% | `python` | `subtype_dealloc` | memory |
| 0.64% | `python` | `dict_get` | dict |
| 0.59% | `libc.so.6` | `malloc` | libc |
| 0.56% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.54% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.54% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.53% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.51% | `python` | `subtype_traverse` | gc |
| 0.51% | `python` | `visit_decref` | gc |
| 0.47% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.46% | `python` | `PyType_IsSubtype` | dynamic |
| 0.45% | `python` | `PyList_New.constprop.0` | memory |
| 0.39% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.39% | `python` | `list_ass_subscript` | list |
| 0.38% | `python` | `_PyEval_Vector` | interpreter |
| 0.37% | `python` | `PyNumber_Negative` | dynamic |
| 0.37% | `python` | `long_neg_method` | int |
| 0.37% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.35% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.35% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.35% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.35% | `python` | `object_isinstance` | dynamic |
| 0.34% | `python` | `PyUnicode_Contains` | str |
| 0.34% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.33% | `python` | `_PyGC_Collect` | gc |
| 0.33% | `python` | `PyObject_DelItem` | dynamic |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.31% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.31% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.29% | `python` | `list_subscript` | list |
| 0.29% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.29% | `python` | `PyObject_SetItem` | dynamic |
| 0.28% | `libc.so.6` | `_int_free` | libc |
| 0.27% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.26% | `python` | `PyType_GenericAlloc` | memory |
| 0.26% | `python` | `PyObject_IsInstance` | dynamic |

## pyflate

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.03% | `[JIT]` | `jit` | jit |
| 5.81% | `python` | `list_ass_slice_lock_held` | list |
| 5.06% | `python` | `list_dealloc` | memory |
| 3.04% | `python` | `list_concat` | list |
| 2.68% | `python` | `list_slice_lock_held` | list |
| 2.12% | `python` | `_Py_Dealloc` | memory |
| 2.09% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.81% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.74% | `python` | `_PyCompactLong_Add` | unknown |
| 1.73% | `libc.so.6` | `_int_malloc` | libc |
| 1.60% | `python` | `stringlib_bytes_join` | str |
| 1.58% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.56% | `python` | `_PyObject_Malloc` | memory |
| 1.50% | `python` | `_PyObject_Free` | memory |
| 1.38% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.25% | `python` | `bytes_subscript` | str |
| 1.18% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.16% | `python` | `list_sort_impl` | list |
| 1.13% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.06% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.04% | `python` | `PyLong_FromSsize_t` | int |
| 0.99% | `python` | `long_lshift_method` | int |
| 0.87% | `python` | `PyBuffer_Release` | miscobj |
| 0.83% | `python` | `unsafe_long_compare` | unknown |
| 0.81% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.77% | `python` | `long_lshift1` | int |
| 0.69% | `python` | `PyLong_AsSsize_t` | int |
| 0.61% | `python` | `PySlice_New` | memory |
| 0.61% | `python` | `PyList_New.constprop.0` | memory |
| 0.60% | `python` | `_Py_NewReference` | memory |
| 0.59% | `python` | `PyObject_GetItem` | dynamic |
| 0.58% | `python` | `long_dealloc` | memory |
| 0.58% | `python` | `long_rshift` | int |
| 0.56% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.56% | `python` | `PyNumber_Lshift` | dynamic |
| 0.55% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.54% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.53% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.50% | `python` | `PyBytes_FromObject` | str |
| 0.47% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.38% | `python` | `long_rshift1` | int |
| 0.36% | `python` | `PyNumber_Rshift` | dynamic |
| 0.32% | `libc.so.6` | `malloc` | libc |
| 0.29% | `python` | `enum_next` | miscobj |
| 0.28% | `python` | `gallop_right` | unknown |
| 0.27% | `python` | `gallop_left` | unknown |
| 0.27% | `python` | `_PyList_BinarySlice` | list |
| 0.26% | `python` | `PySlice_Unpack` | miscobj |

## pylint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.99% | `[JIT]` | `jit` | jit |
| 3.18% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.95% | `python` | `_PyObject_Malloc` | memory |
| 2.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.14% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.12% | `python` | `_Py_dict_lookup` | lookup |
| 1.74% | `python` | `_PyObject_Free` | memory |
| 1.69% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.47% | `python` | `initialize_locals` | interpreter |
| 1.37% | `python` | `visit_add_to_container` | gc |
| 1.32% | `python` | `_Py_Dealloc` | memory |
| 1.14% | `python` | `PyDict_GetItemRef` | dict |
| 0.83% | `python` | `PyType_IsSubtype` | dynamic |
| 0.79% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.78% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.78% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.64% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.60% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `gc_collect_region` | gc |
| 0.59% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.55% | `python` | `tuple_dealloc` | memory |
| 0.51% | `python` | `gen_dealloc` | memory |
| 0.51% | `python` | `_PyGC_Collect` | gc |
| 0.51% | `python` | `mark_all_reachable` | unknown |
| 0.50% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.40% | `python` | `unicode_repr` | str |
| 0.40% | `python` | `_PyPegen_is_memoized` | interpreter |
| 0.40% | `python` | `tuple_alloc` | memory |
| 0.38% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.38% | `python` | `insertdict` | dict |
| 0.37% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.34% | `python` | `_PyEval_Vector` | interpreter |
| 0.34% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.33% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.32% | `python` | `listiter_next` | list |
| 0.32% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.32% | `python` | `find_name_in_mro` | lookup |
| 0.30% | `python` | `visit_decref` | gc |
| 0.30% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.29% | `python` | `PyObject_IsTrue` | dynamic |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.27% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.27% | `python` | `object_isinstance` | dynamic |
| 0.27% | `python` | `PyObject_SetAttr` | dynamic |
| 0.27% | `python` | `PyObject_IsInstance` | dynamic |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.26% | `python` | `visit_reachable` | gc |
| 0.25% | `python` | `dict_dealloc` | memory |

## python_startup

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 8.06% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.03% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.25% | `python` | `gc_collect_region` | gc |
| 3.00% | `python` | `_PyObject_Malloc` | memory |
| 2.07% | `python` | `_Py_dict_lookup` | lookup |
| 2.03% | `python` | `visit_decref` | gc |
| 1.95% | `python` | `r_object` | import |
| 1.49% | `python` | `visit_reachable` | gc |
| 1.49% | `python` | `_PyObject_Free` | memory |
| 1.33% | `python` | `_PyCode_Quicken` | interpreter |
| 1.31% | `python` | `find_name_in_mro` | lookup |
| 1.26% | `python` | `type_ready` | dynamic |
| 1.14% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.10% | `python` | `_Py_Dealloc` | memory |
| 1.07% | `python` | `siphash13` | str |
| 0.99% | `python` | `_PyGC_Collect` | gc |
| 0.95% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.88% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.87% | `python` | `dict_traverse` | gc |
| 0.84% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.82% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.76% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.68% | `python` | `intern_constants` | str |
| 0.66% | `python` | `tuple_dealloc` | memory |
| 0.64% | `libc.so.6` | `_int_malloc` | libc |
| 0.64% | `python` | `insertdict` | dict |
| 0.59% | `python` | `update_one_slot` | lookup |
| 0.57% | `python` | `visit_add_to_container` | gc |
| 0.56% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.55% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.54% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.53% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.52% | `[unknown]` | `0xffffffffab6011a9` | unknown |
| 0.51% | `[unknown]` | `0xffffffffab601631` | unknown |
| 0.51% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.50% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.50% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.46% | `python` | `find_first_nonascii` | str |
| 0.45% | `python` | `PyUnicode_New.part.0` | memory |
| 0.44% | `[unknown]` | `0xffffffffab44a16e` | unknown |
| 0.44% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.44% | `python` | `PyDict_GetItemRef` | dict |
| 0.44% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.43% | `python` | `build_indices_unicode` | dict |
| 0.41% | `[unknown]` | `0xffffffffab6001c6` | unknown |
| 0.41% | `python` | `_PyCode_New` | interpreter |
| 0.35% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.34% | `[unknown]` | `0xffffffffab3d0187` | unknown |
| 0.34% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.33% | `[unknown]` | `0xffffffffab60125b` | unknown |
| 0.33% | `python` | `initialize_locals` | interpreter |
| 0.33% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `code_dealloc` | memory |
| 0.32% | `python` | `r_long` | import |
| 0.32% | `python` | `PyObject_IS_GC` | gc |
| 0.31% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.29% | `[unknown]` | `0xffffffffab601618` | unknown |
| 0.29% | `python` | `tuple_alloc` | memory |
| 0.27% | `[unknown]` | `0xffffffffab3d02da` | unknown |
| 0.26% | `python` | `PyFunction_NewWithQualName` | memory |

## python_startup_no_site

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.84% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.56% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.57% | `python` | `gc_collect_region` | gc |
| 3.02% | `python` | `_PyObject_Malloc` | memory |
| 2.16% | `python` | `visit_decref` | gc |
| 1.77% | `python` | `visit_reachable` | gc |
| 1.77% | `python` | `_Py_dict_lookup` | lookup |
| 1.69% | `python` | `r_object` | import |
| 1.54% | `python` | `type_ready` | dynamic |
| 1.39% | `python` | `_PyObject_Free` | memory |
| 1.23% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.16% | `python` | `_PyCode_Quicken` | interpreter |
| 1.13% | `python` | `siphash13` | str |
| 1.12% | `python` | `_PyGC_Collect` | gc |
| 1.12% | `python` | `find_name_in_mro` | lookup |
| 1.09% | `python` | `dict_traverse` | gc |
| 1.09% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 1.00% | `python` | `_Py_Dealloc` | memory |
| 0.80% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.80% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.79% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.76% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.71% | `libc.so.6` | `_int_malloc` | libc |
| 0.70% | `python` | `visit_add_to_container` | gc |
| 0.70% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.69% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.66% | `python` | `insertdict` | dict |
| 0.62% | `python` | `tuple_dealloc` | memory |
| 0.61% | `python` | `intern_constants` | str |
| 0.60% | `[unknown]` | `0xffffffffab6011a9` | unknown |
| 0.59% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.56% | `[unknown]` | `0xffffffffab601631` | unknown |
| 0.55% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.53% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.53% | `python` | `find_first_nonascii` | str |
| 0.53% | `python` | `build_indices_unicode` | dict |
| 0.51% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.51% | `python` | `update_one_slot` | lookup |
| 0.49% | `[unknown]` | `0xffffffffab44a16e` | unknown |
| 0.48% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.46% | `python` | `PyUnicode_New.part.0` | memory |
| 0.43% | `[unknown]` | `0xffffffffab3d0187` | unknown |
| 0.43% | `[unknown]` | `0xffffffffab6001c6` | unknown |
| 0.40% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.40% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.39% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.38% | `[unknown]` | `0xffffffffab601618` | unknown |
| 0.37% | `[unknown]` | `0xffffffffab60125b` | unknown |
| 0.35% | `python` | `PyDict_GetItemRef` | dict |
| 0.33% | `python` | `_PyCode_New` | interpreter |
| 0.30% | `ld-linux-x86-64.so.2` | `do_lookup_x` | library |
| 0.30% | `python` | `PyObject_IS_GC` | gc |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.28% | `python` | `r_long` | import |
| 0.28% | `python` | `initialize_locals` | interpreter |
| 0.27% | `libc.so.6` | `malloc` | libc |
| 0.26% | `python` | `code_dealloc` | memory |
| 0.26% | `python` | `PyDict_Next` | dict |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.25% | `python` | `tuple_alloc` | memory |

## raytrace

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.93% | `[JIT]` | `jit` | jit |
| 5.36% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.15% | `python` | `PyFloat_FromDouble` | float |
| 4.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.78% | `python` | `_Py_Dealloc` | memory |
| 2.92% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.74% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.66% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.63% | `python` | `_PyObject_Free` | memory |
| 1.46% | `python` | `initialize_locals` | interpreter |
| 1.28% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 1.23% | `python` | `subtype_dealloc` | memory |
| 1.15% | `python` | `_Py_NewReference` | memory |
| 1.04% | `python` | `_PyObject_Malloc` | memory |
| 0.99% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.89% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.88% | `python` | `PyType_IsSubtype` | dynamic |
| 0.76% | `python` | `float_dealloc` | memory |
| 0.76% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.74% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.72% | `python` | `PyType_GenericAlloc` | memory |
| 0.68% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.67% | `python` | `PyNumber_Subtract` | dynamic |
| 0.62% | `python` | `_PyEval_Vector` | interpreter |
| 0.59% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.47% | `python` | `vectorcall_maybe` | unknown |
| 0.47% | `python` | `float_richcompare` | float |
| 0.45% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.41% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.39% | `python` | `slot_nb_subtract` | unknown |
| 0.35% | `python` | `PyObject_RichCompare` | dynamic |
| 0.34% | `python` | `tuple_alloc` | memory |
| 0.34% | `python` | `compactlong_float_guard` | unknown |
| 0.33% | `python` | `PyNumber_TrueDivide` | dynamic |
| 0.31% | `python` | `tuple_dealloc` | memory |
| 0.30% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.28% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.27% | `math.cpython-315-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.27% | `python` | `memset@plt` | memory |
| 0.25% | `python` | `PyObject_IsTrue` | dynamic |

## regex_compile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.17% | `[JIT]` | `jit` | jit |
| 20.65% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.52% | `python` | `_Py_Dealloc` | memory |
| 2.09% | `python` | `_PyObject_Malloc` | memory |
| 1.69% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.17% | `python` | `_PyObject_Free` | memory |
| 1.12% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.04% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.92% | `python` | `PyType_IsSubtype` | dynamic |
| 0.91% | `python` | `PyLong_FromLong` | int |
| 0.86% | `python` | `bytearray_ass_subscript_lock_held` | miscobj |
| 0.80% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.77% | `python` | `PyUnicode_Contains` | str |
| 0.71% | `python` | `tuple_alloc` | memory |
| 0.69% | `python` | `list_append` | list |
| 0.69% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.65% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.59% | `python` | `initialize_locals` | interpreter |
| 0.56% | `python` | `set_lookkey` | miscobj |
| 0.55% | `python` | `tuple_dealloc` | memory |
| 0.53% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.51% | `python` | `list_dealloc` | memory |
| 0.51% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.49% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRefSteal` | unknown |
| 0.48% | `python` | `_Py_dict_lookup` | lookup |
| 0.45% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.45% | `python` | `PyObject_SetItem` | dynamic |
| 0.45% | `python` | `PyList_New.constprop.0` | memory |
| 0.44% | `python` | `PyLong_FromSsize_t` | int |
| 0.43% | `python` | `_PyObject_Realloc` | memory |
| 0.42% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.42% | `python` | `min_max` | unknown |
| 0.42% | `python` | `_PyUnicode_Equal` | str |
| 0.41% | `python` | `_PyEval_Vector` | interpreter |
| 0.38% | `python` | `PyObject_IsInstance` | dynamic |
| 0.38% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.37% | `python` | `make_range_object` | unknown |
| 0.34% | `python` | `_PyCompactLong_Add` | unknown |
| 0.33% | `python` | `_Py_NewReference` | memory |
| 0.33% | `python` | `PyMethod_New` | memory |
| 0.32% | `python` | `PyCMethod_New` | memory |
| 0.32% | `python` | `long_richcompare` | int |
| 0.31% | `python` | `PyObject_Size` | dynamic |
| 0.31% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.30% | `python` | `bytearray_ass_subscript` | miscobj |
| 0.30% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.30% | `python` | `PyDict_GetItemRef` | dict |
| 0.30% | `python` | `PyLong_AsSsize_t` | int |
| 0.29% | `python` | `long_dealloc` | memory |
| 0.28% | `python` | `_validate_inner` | unknown |
| 0.28% | `python` | `_PyEval_GetIter` | interpreter |
| 0.26% | `python` | `PyObject_GetItem` | dynamic |
| 0.26% | `python` | `_PySet_Contains` | miscobj |
| 0.26% | `python` | `range_iter` | miscobj |

## regex_dna

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 48.65% | `python` | `sre_ucs1_match` | library |
| 34.87% | `python` | `sre_ucs1_charset.isra.0` | library |
| 10.38% | `python` | `sre_search` | library |
| 1.08% | `python` | `pattern_subx` | library |
| 0.94% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.58% | `python` | `stringlib_bytes_join` | str |
| 0.39% | `python` | `_PyObject_Malloc` | memory |
| 0.26% | `python` | `PyBuffer_Release` | miscobj |

## regex_effbot

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 64.73% | `python` | `sre_ucs1_match` | library |
| 16.32% | `python` | `sre_ucs1_charset.isra.0` | library |
| 8.98% | `python` | `sre_search` | library |
| 5.25% | `python` | `sre_ucs1_count` | library |
| 1.04% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.38% | `python` | `siphash13` | str |
| 0.29% | `python` | `_PyObject_Malloc` | memory |

## regex_v8

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 54.36% | `python` | `sre_ucs1_match` | library |
| 5.84% | `python` | `sre_search` | library |
| 5.66% | `python` | `sre_ucs1_count` | library |
| 2.80% | `libc.so.6` | `_int_malloc` | libc |
| 2.56% | `python` | `pattern_subx` | library |
| 2.40% | `python` | `_PyObject_Malloc` | memory |
| 2.31% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.07% | `python` | `_PyObject_Free` | memory |
| 1.85% | `[JIT]` | `jit` | jit |
| 1.67% | `python` | `pattern_new_match` | memory |
| 1.66% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.90% | `libc.so.6` | `malloc` | libc |
| 0.87% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.76% | `python` | `_PyUnicode_ToLowercase` | str |
| 0.74% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.73% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.65% | `python` | `_PyUnicode_IsAlpha` | str |
| 0.63% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.60% | `libc.so.6` | `_int_free` | libc |
| 0.59% | `python` | `_Py_Dealloc` | memory |
| 0.58% | `python` | `PyList_Append` | list |
| 0.53% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.45% | `libc.so.6` | `cfree@GLIBC_2.2.5` | libc |
| 0.37% | `python` | `PyUnicode_Substring` | str |
| 0.33% | `python` | `_PyObject_Realloc` | memory |
| 0.31% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.30% | `python` | `_PyUnicode_IsDecimalDigit` | str |
| 0.30% | `python` | `_Py_dict_lookup` | lookup |
| 0.29% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.28% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.28% | `python` | `PyErr_Occurred` | exceptions |
| 0.26% | `python` | `method_vectorcall_FASTCALL_KEYWORDS_METHOD` | calls |

## richards

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 70.63% | `[JIT]` | `jit` | jit |
| 8.20% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 5.25% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.63% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.24% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.98% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.42% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.11% | `python` | `_PyCompactLong_Add` | unknown |
| 1.08% | `python` | `_Py_Dealloc` | memory |
| 0.75% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.71% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.39% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.36% | `python` | `long_div` | int |
| 0.34% | `python` | `long_dealloc` | memory |
| 0.32% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.32% | `python` | `_PyType_GetDict` | dynamic |

## richards_super

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 67.76% | `[JIT]` | `jit` | jit |
| 8.19% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 4.80% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.05% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.82% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.74% | `python` | `do_super_lookup` | dynamic |
| 1.37% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.35% | `python` | `PyDict_GetItemRef` | dict |
| 1.09% | `python` | `_PySuper_Lookup` | dynamic |
| 1.07% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.05% | `python` | `_Py_dict_lookup` | lookup |
| 0.98% | `python` | `_Py_Dealloc` | memory |
| 0.88% | `python` | `_PyCompactLong_Add` | unknown |
| 0.53% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.32% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.29% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.25% | `python` | `long_div` | int |

## scimark

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.53% | `[JIT]` | `jit` | jit |
| 5.50% | `python` | `PyFloat_FromDouble` | float |
| 4.97% | `array.cpython-315-x86_64-linux-gnu.so` | `array_subscr` | library |
| 4.53% | `python` | `_Py_Dealloc` | memory |
| 3.91% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 2.93% | `python` | `convertitem.constprop.0` | unknown |
| 2.90% | `python` | `vgetargs1_impl.constprop.0` | calls |
| 2.52% | `python` | `_Py_NewReference` | memory |
| 2.18% | `python` | `PyObject_GetItem` | dynamic |
| 1.94% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.90% | `python` | `PyLong_AsSsize_t` | int |
| 1.84% | `python` | `_PyCompactLong_Add` | unknown |
| 1.62% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.60% | `array.cpython-315-x86_64-linux-gnu.so` | `array_ass_subscr` | library |
| 1.52% | `array.cpython-315-x86_64-linux-gnu.so` | `d_setitem` | library |
| 1.48% | `python` | `PyIndex_Check` | unknown |
| 1.28% | `python` | `PyType_GetModuleByDef` | dynamic |
| 1.21% | `python` | `PyLong_FromLong` | int |
| 1.17% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.13% | `array.cpython-315-x86_64-linux-gnu.so` | `d_getitem` | library |
| 1.11% | `python` | `_PyCompactLong_Multiply` | unknown |
| 1.06% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.01% | `python` | `PyArg_Parse` | calls |
| 0.93% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.83% | `python` | `PyObject_SetItem` | dynamic |
| 0.80% | `python` | `PyType_IsSubtype` | dynamic |
| 0.74% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.58% | `python` | `float_dealloc` | memory |
| 0.55% | `python` | `PyFloat_AsDouble` | float |
| 0.54% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.49% | `python` | `tuple_dealloc` | memory |
| 0.46% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.44% | `array.cpython-315-x86_64-linux-gnu.so` | `PyType_GetModuleByDef@plt` | library |
| 0.43% | `array.cpython-315-x86_64-linux-gnu.so` | `PyNumber_AsSsize_t@plt` | library |
| 0.43% | `python` | `object_isinstance` | dynamic |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.40% | `array.cpython-315-x86_64-linux-gnu.so` | `PyIndex_Check@plt` | library |
| 0.39% | `python` | `long_dealloc` | memory |
| 0.38% | `python` | `tuple_alloc` | memory |
| 0.36% | `python` | `float_richcompare` | float |
| 0.36% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.35% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.34% | `python` | `_PyLong_Frexp` | int |
| 0.33% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.27% | `python` | `PyObject_IsInstance` | dynamic |
| 0.27% | `python` | `make_range_object` | unknown |
| 0.27% | `array.cpython-315-x86_64-linux-gnu.so` | `PyFloat_FromDouble@plt` | library |

## spectral_norm

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.85% | `[JIT]` | `jit` | jit |
| 11.43% | `python` | `_PyCompactLong_Add` | unknown |
| 4.56% | `python` | `PyFloat_FromDouble` | float |
| 3.89% | `python` | `long_div` | int |
| 3.64% | `python` | `_PyCompactLong_Multiply` | unknown |
| 3.38% | `python` | `_Py_NewReference` | memory |
| 3.26% | `python` | `_PyLong_ExactDealloc` | memory |
| 3.16% | `python` | `float_compactlong_true_div` | float |
| 3.12% | `python` | `enum_next` | miscobj |
| 2.70% | `python` | `listiter_next` | list |
| 2.22% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.86% | `python` | `PyLong_FromLong` | int |
| 1.86% | `python` | `PyNumber_FloorDivide` | dynamic |
| 1.60% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.32% | `python` | `_Py_Dealloc` | memory |
| 1.26% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 1.25% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.01% | `python` | `PyLong_FromSsize_t` | int |
| 0.85% | `python` | `nonzero_float_compactlong_guard` | unknown |
| 0.59% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.34% | `python` | `float_dealloc` | memory |
| 0.28% | `python` | `float_compactlong_guard` | float |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |

## sphinx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 13.17% | `[JIT]` | `jit` | jit |
| 12.32% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.17% | `python` | `sre_ucs1_match` | library |
| 3.14% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.66% | `python` | `_PyObject_Malloc` | memory |
| 2.50% | `python` | `gc_collect_region` | gc |
| 2.40% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.22% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.98% | `python` | `sre_ucs1_charset.isra.0` | library |
| 1.71% | `python` | `_PyObject_Free` | memory |
| 1.49% | `python` | `_Py_dict_lookup` | lookup |
| 1.49% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.43% | `python` | `visit_add_to_container` | gc |
| 1.16% | `python` | `_Py_Dealloc` | memory |
| 1.07% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.06% | `python` | `PyType_IsSubtype` | dynamic |
| 0.97% | `python` | `initialize_locals` | interpreter |
| 0.95% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.92% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.90% | `python` | `_PyGC_Collect` | gc |
| 0.86% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save.constprop.0` | library |
| 0.74% | `python` | `PyDict_GetItemRef` | dict |
| 0.70% | `python` | `siphash13` | str |
| 0.65% | `python` | `PyUnicode_Format` | str |
| 0.64% | `python` | `visit_decref` | gc |
| 0.59% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.57% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `python` | `gen_dealloc` | memory |
| 0.52% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `save_dict` | library |
| 0.48% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.48% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.47% | `python` | `tuple_dealloc` | memory |
| 0.45% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.43% | `python` | `list_dealloc` | memory |
| 0.42% | `python` | `sre_search` | library |
| 0.42% | `python` | `object_isinstance` | dynamic |
| 0.40% | `python` | `dict_traverse` | gc |
| 0.40% | `python` | `tuple_alloc` | memory |
| 0.39% | `python` | `PyObject_IsInstance` | dynamic |
| 0.36% | `python` | `sre_ucs2_match` | library |
| 0.35% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.34% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 0.33% | `python` | `_PyEval_Vector` | interpreter |
| 0.33% | `libc.so.6` | `_int_malloc` | libc |
| 0.31% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.31% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.30% | `python` | `visit_reachable` | gc |
| 0.30% | `python` | `pattern_subx` | library |
| 0.29% | `python` | `getset_get` | dynamic |
| 0.29% | `python` | `replace` | str |
| 0.29% | `python` | `_PyType_GetDict` | dynamic |
| 0.27% | `python` | `unicode_repr` | str |
| 0.27% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 0.26% | `python` | `find_name_in_mro` | lookup |
| 0.26% | `python` | `_PyEval_GetIter` | interpreter |
| 0.26% | `python` | `sre_ucs1_count` | library |
| 0.25% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |

## sqlalchemy_declarative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.55% | `[JIT]` | `jit` | jit |
| 3.92% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.78% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.56% | `python` | `_PyObject_Malloc` | memory |
| 2.34% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.92% | `python` | `_Py_dict_lookup` | lookup |
| 1.78% | `python` | `_Py_Dealloc` | memory |
| 1.59% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.48% | `python` | `initialize_locals` | interpreter |
| 1.46% | `python` | `tuple_dealloc` | memory |
| 1.45% | `python` | `_PyObject_Free` | memory |
| 1.15% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 1.00% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.81% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.77% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.76% | `python` | `tuple_alloc` | memory |
| 0.75% | `python` | `PyDict_GetItemRef` | dict |
| 0.75% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.74% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.74% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.69% | `python` | `PyObject_SetAttr` | dynamic |
| 0.69% | `python` | `subtype_dealloc` | memory |
| 0.62% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.59% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.58% | `python` | `PyObject_IsTrue` | dynamic |
| 0.55% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.55% | `python` | `PyType_IsSubtype` | dynamic |
| 0.55% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.51% | `python` | `set_lookkey` | miscobj |
| 0.50% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.48% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.48% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.47% | `python` | `dict_dealloc` | memory |
| 0.45% | `python` | `take_gil` | gil |
| 0.44% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.43% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `_PyEval_Vector` | interpreter |
| 0.41% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.39% | `python` | `PyTuple_FromArray` | tuple |
| 0.36% | `python` | `find_name_in_mro` | lookup |
| 0.35% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.35% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.34% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.33% | `python` | `set_dealloc` | memory |
| 0.31% | `python` | `PyType_GenericAlloc` | memory |
| 0.29% | `python` | `insertdict` | dict |
| 0.28% | `python` | `tuple_hash` | tuple |
| 0.28% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.28% | `python` | `set_add_entry_takeref` | miscobj |
| 0.27% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.27% | `python` | `PyObject_Hash` | dynamic |
| 0.26% | `python` | `_PyType_GetDict` | dynamic |
| 0.26% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.25% | `python` | `PyMethod_New` | memory |

## sqlalchemy_imperative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.81% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.12% | `[JIT]` | `jit` | jit |
| 4.03% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.28% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.13% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 1.92% | `python` | `_PyObject_Malloc` | memory |
| 1.75% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.61% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `_Py_dict_lookup` | lookup |
| 1.44% | `python` | `initialize_locals` | interpreter |
| 1.44% | `python` | `_Py_Dealloc` | memory |
| 1.26% | `python` | `_PyObject_Free` | memory |
| 0.90% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.85% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.80% | `python` | `tuple_dealloc` | memory |
| 0.75% | `python` | `gc_collect_region` | gc |
| 0.72% | `python` | `subtype_dealloc` | memory |
| 0.72% | `python` | `PyObject_SetAttr` | dynamic |
| 0.66% | `python` | `PyObject_IsTrue` | dynamic |
| 0.66% | `python` | `tuple_alloc` | memory |
| 0.65% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.64% | `python` | `PyType_IsSubtype` | dynamic |
| 0.63% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.61% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.60% | `python` | `PyDict_GetItemRef` | dict |
| 0.58% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.55% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.50% | `python` | `dict_dealloc` | memory |
| 0.43% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.39% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.39% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.38% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.38% | `python` | `insertdict` | dict |
| 0.38% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.37% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.36% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.31% | `python` | `_PyType_GetDict` | dynamic |
| 0.30% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.29% | `python` | `_PyGC_Collect` | gc |
| 0.29% | `libsqlite3.so.0.8.6` | `sqlite3Parser` | library |
| 0.28% | `python` | `new_dict` | dict |
| 0.28% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.27% | `python` | `long_to_decimal_string_internal` | int |
| 0.27% | `python` | `list_dealloc` | memory |
| 0.27% | `python` | `PyObject_Call` | dynamic |
| 0.25% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.25% | `python` | `insert_to_emptydict` | dict |

## sqlglot_v2

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.45% | `[JIT]` | `jit` | jit |
| 15.83% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.74% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.58% | `python` | `_PyObject_Malloc` | memory |
| 3.58% | `python` | `_Py_Dealloc` | memory |
| 2.99% | `python` | `_PyObject_Free` | memory |
| 2.72% | `python` | `PyType_IsSubtype` | dynamic |
| 2.72% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.05% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.94% | `python` | `dictiter_iternextitem` | dict |
| 1.65% | `python` | `tuple_dealloc` | memory |
| 1.44% | `python` | `PyObject_IsInstance` | dynamic |
| 1.24% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.15% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.13% | `python` | `PyCMethod_New` | memory |
| 1.09% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.08% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.95% | `python` | `object_isinstance` | dynamic |
| 0.90% | `python` | `initialize_locals` | interpreter |
| 0.84% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.79% | `python` | `gen_dealloc` | memory |
| 0.78% | `python` | `tuple_alloc` | memory |
| 0.78% | `python` | `_PyObject_GC_New` | gc |
| 0.73% | `python` | `_PyObject_LookupSpecial` | dynamic |
| 0.70% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.67% | `python` | `getset_get` | dynamic |
| 0.67% | `python` | `meth_dealloc` | memory |
| 0.67% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.67% | `python` | `insert_to_emptydict` | dict |
| 0.60% | `python` | `_Py_NewReference` | memory |
| 0.58% | `python` | `_Py_dict_lookup` | lookup |
| 0.54% | `python` | `PyTuple_Pack` | tuple |
| 0.54% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.53% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.50% | `python` | `_PyObject_Calloc` | memory |
| 0.47% | `python` | `_PyEval_GetIter` | interpreter |
| 0.47% | `python` | `tuple_hash` | tuple |
| 0.44% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.42% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `dictitems_iter` | unknown |
| 0.41% | `python` | `dict_get` | dict |
| 0.37% | `python` | `PyObject_IsTrue` | dynamic |
| 0.37% | `python` | `func_dealloc` | memory |
| 0.37% | `python` | `make_gen` | miscobj |
| 0.36% | `python` | `unicode_lower` | str |
| 0.36% | `python` | `PyList_New` | memory |
| 0.36% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.35% | `python` | `_PyEval_Vector` | interpreter |
| 0.35% | `python` | `func_clear` | unknown |
| 0.34% | `python` | `cfunction_vectorcall_O` | calls |
| 0.33% | `python` | `PyMem_Calloc` | memory |
| 0.33% | `python` | `PyObject_GC_Del` | gc |
| 0.32% | `python` | `method_get` | dynamic |
| 0.32% | `python` | `object_recursive_isinstance` | dynamic |
| 0.32% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.31% | `python` | `dictiter_dealloc` | memory |
| 0.29% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.28% | `python` | `dict_items` | dict |
| 0.27% | `python` | `set_add_entry_takeref` | miscobj |
| 0.26% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.26% | `python` | `new_dict` | dict |
| 0.26% | `python` | `PyObject_Hash` | dynamic |
| 0.26% | `python` | `dictview_dealloc` | memory |

## sqlglot_v2_optimize

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.33% | `[JIT]` | `jit` | jit |
| 16.18% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.47% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.35% | `python` | `_Py_Dealloc` | memory |
| 3.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 3.04% | `python` | `_PyObject_Malloc` | memory |
| 2.98% | `python` | `PyType_IsSubtype` | dynamic |
| 2.85% | `python` | `_PyObject_Free` | memory |
| 2.13% | `python` | `dictiter_iternextitem` | dict |
| 1.67% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.64% | `python` | `PyObject_IsInstance` | dynamic |
| 1.54% | `python` | `tuple_dealloc` | memory |
| 1.32% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.21% | `python` | `PyCMethod_New` | memory |
| 1.12% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.07% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.04% | `python` | `object_isinstance` | dynamic |
| 0.96% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.85% | `python` | `getset_get` | dynamic |
| 0.83% | `python` | `tuple_alloc` | memory |
| 0.77% | `python` | `_PyObject_LookupSpecial` | dynamic |
| 0.74% | `python` | `_Py_dict_lookup` | lookup |
| 0.65% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.64% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.64% | `python` | `initialize_locals` | interpreter |
| 0.64% | `python` | `_PyObject_GC_New` | gc |
| 0.63% | `python` | `meth_dealloc` | memory |
| 0.60% | `python` | `_PyObject_Calloc` | memory |
| 0.54% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `python` | `dict_get` | dict |
| 0.53% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.51% | `python` | `tuple_hash` | tuple |
| 0.50% | `python` | `_Py_NewReference` | memory |
| 0.48% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.47% | `python` | `PyList_New` | memory |
| 0.47% | `python` | `insert_to_emptydict` | dict |
| 0.47% | `python` | `PyObject_IsTrue` | dynamic |
| 0.46% | `python` | `PyTuple_Pack` | tuple |
| 0.42% | `python` | `list_dealloc` | memory |
| 0.42% | `python` | `PyObject_Hash` | dynamic |
| 0.39% | `python` | `cfunction_vectorcall_O` | calls |
| 0.39% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.39% | `python` | `_PyEval_GetIter` | interpreter |
| 0.36% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.36% | `python` | `method_get` | dynamic |
| 0.35% | `python` | `insertdict` | dict |
| 0.33% | `python` | `dictitems_iter` | unknown |
| 0.33% | `python` | `_PyType_GetDict` | dynamic |
| 0.32% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.32% | `python` | `gen_dealloc` | memory |
| 0.32% | `python` | `PyMember_GetOne` | lookup |
| 0.31% | `python` | `siphash13` | str |
| 0.31% | `python` | `object_recursive_isinstance` | dynamic |
| 0.30% | `python` | `object_get_class` | dynamic |
| 0.27% | `python` | `PyDict_GetItemRef` | dict |
| 0.27% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.27% | `python` | `func_clear` | unknown |
| 0.27% | `python` | `func_dealloc` | memory |
| 0.27% | `python` | `PyMem_Calloc` | memory |
| 0.26% | `python` | `dict_items` | dict |

## sqlglot_v2_parse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 30.69% | `[JIT]` | `jit` | jit |
| 12.52% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.10% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.10% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.48% | `python` | `initialize_locals` | interpreter |
| 2.39% | `python` | `_PyObject_Malloc` | memory |
| 1.96% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.76% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.73% | `python` | `_Py_dict_lookup` | lookup |
| 1.70% | `python` | `_PyObject_Free` | memory |
| 1.58% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.52% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 1.51% | `python` | `gc_collect_region` | gc |
| 1.49% | `python` | `_Py_Dealloc` | memory |
| 1.13% | `python` | `PyObject_RichCompare` | dynamic |
| 0.87% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.83% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.81% | `python` | `PyType_IsSubtype` | dynamic |
| 0.65% | `python` | `_PyCompactLong_Add` | unknown |
| 0.63% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.62% | `python` | `dictiter_iternextitem` | dict |
| 0.56% | `python` | `PyDict_Contains` | dict |
| 0.51% | `python` | `dict_get` | dict |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.48% | `python` | `_PyEval_Vector` | interpreter |
| 0.43% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.43% | `python` | `PyObject_SetAttr` | dynamic |
| 0.43% | `python` | `PyObject_IsTrue` | dynamic |
| 0.42% | `python` | `_PyGC_Collect` | gc |
| 0.42% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.42% | `python` | `subtype_dealloc` | memory |
| 0.40% | `python` | `visit_decref` | gc |
| 0.39% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.39% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.38% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.37% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.35% | `python` | `_PyObject_GC_New` | gc |
| 0.34% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.34% | `python` | `object_richcompare` | dynamic |
| 0.34% | `python` | `insert_to_emptydict` | dict |
| 0.33% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.33% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.32% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.31% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.31% | `python` | `PyLong_FromSsize_t` | int |
| 0.28% | `python` | `set_lookkey` | miscobj |
| 0.28% | `python` | `PyMember_SetOne` | lookup |
| 0.27% | `python` | `PyCMethod_New` | memory |
| 0.26% | `python` | `PyObject_IsInstance` | dynamic |
| 0.26% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.25% | `python` | `_Py_NewReference` | memory |

## sqlglot_v2_transpile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.43% | `[JIT]` | `jit` | jit |
| 17.12% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.82% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.26% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.42% | `python` | `_PyObject_Malloc` | memory |
| 2.35% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.30% | `python` | `initialize_locals` | interpreter |
| 1.83% | `python` | `_Py_dict_lookup` | lookup |
| 1.63% | `python` | `_Py_Dealloc` | memory |
| 1.59% | `python` | `_PyObject_Free` | memory |
| 1.38% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.32% | `python` | `gc_collect_region` | gc |
| 1.29% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.28% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 1.15% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.02% | `python` | `PyType_IsSubtype` | dynamic |
| 0.94% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.85% | `python` | `PyObject_RichCompare` | dynamic |
| 0.62% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.62% | `python` | `dict_get` | dict |
| 0.61% | `python` | `dictiter_iternextitem` | dict |
| 0.54% | `python` | `_PyCompactLong_Add` | unknown |
| 0.51% | `python` | `PyObject_IsTrue` | dynamic |
| 0.47% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.42% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.42% | `python` | `subtype_dealloc` | memory |
| 0.40% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.40% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.39% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.39% | `python` | `PyDict_Contains` | dict |
| 0.39% | `python` | `_PyObject_GC_New` | gc |
| 0.38% | `python` | `PyObject_IsInstance` | dynamic |
| 0.36% | `python` | `_PyGC_Collect` | gc |
| 0.36% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.34% | `python` | `_PyEval_Vector` | interpreter |
| 0.34% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.34% | `python` | `tuple_dealloc` | memory |
| 0.33% | `python` | `insert_to_emptydict` | dict |
| 0.33% | `python` | `set_lookkey` | miscobj |
| 0.33% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.32% | `python` | `PyMethod_New` | memory |
| 0.31% | `python` | `visit_decref` | gc |
| 0.30% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.30% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.27% | `python` | `PyCMethod_New` | memory |
| 0.27% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.26% | `python` | `PyObject_SetAttr` | dynamic |
| 0.25% | `python` | `object_richcompare` | dynamic |

## sqlite_synth

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 8.02% | `python` | `take_gil` | gil |
| 6.17% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 5.74% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 4.43% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 4.29% | `[JIT]` | `jit` | jit |
| 3.52% | `python` | `_Py_Dealloc` | memory |
| 2.95% | `libm.so.6` | `__cos_fma` | library |
| 2.16% | `python` | `drop_gil` | gil |
| 2.12% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 2.09% | `_sqlite3.cpython-315-x86_64-linux-gnu.so` | `_pysqlite_query_execute` | library |
| 2.06% | `libc.so.6` | `pthread_cond_signal@@GLIBC_2.3.2` | libc |
| 1.90% | `python` | `_PyObject_Free` | memory |
| 1.40% | `python` | `_PyObject_Malloc` | memory |
| 1.12% | `python` | `long_to_decimal_string_internal` | int |
| 1.07% | `_sqlite3.cpython-315-x86_64-linux-gnu.so` | `_pysqlite_fetch_one_row.constprop.0` | library |
| 0.97% | `libsqlite3.so.0.8.6` | `sqlite3BtreeInsert` | library |
| 0.86% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.86% | `python` | `_PyThreadState_Attach` | threading |
| 0.85% | `python` | `_PyThreadState_Detach` | threading |
| 0.78% | `python` | `tuple_dealloc` | memory |
| 0.75% | `python` | `PyFloat_FromDouble` | float |
| 0.74% | `python` | `PyLong_FromLongLong` | int |
| 0.72% | `python` | `PyThread_get_thread_ident` | threading |
| 0.71% | `libsqlite3.so.0.8.6` | `sqlite3_step` | library |
| 0.66% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.63% | `python` | `_Py_NewReference` | memory |
| 0.59% | `python` | `PyTuple_New` | memory |
| 0.58% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.55% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.55% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.52% | `libsqlite3.so.0.8.6` | `sqlite3VdbeHalt` | library |
| 0.51% | `libsqlite3.so.0.8.6` | `sqlite3_column_type` | library |
| 0.48% | `python` | `PyType_IsSubtype` | dynamic |
| 0.47% | `python` | `PyList_New` | memory |
| 0.43% | `libsqlite3.so.0.8.6` | `sqlite3BtreeBeginTrans` | library |
| 0.43% | `python` | `_PyThreadState_MustExit` | threading |
| 0.42% | `python` | `list_dealloc` | memory |
| 0.42% | `libsqlite3.so.0.8.6` | `0x00000000000bd72a` | library |
| 0.41% | `python` | `_Py_IsMainThread` | unknown |
| 0.41% | `python` | `PyFloat_AsDouble` | float |
| 0.41% | `python` | `pthread_mutex_unlock@plt` | unknown |
| 0.39% | `_sqlite3.cpython-315-x86_64-linux-gnu.so` | `bind_param` | library |
| 0.38% | `python` | `pthread_mutex_lock@plt` | unknown |
| 0.37% | `libsqlite3.so.0.8.6` | `sqlite3_mutex_enter` | library |
| 0.36% | `libsqlite3.so.0.8.6` | `sqlite3_reset` | library |
| 0.36% | `libsqlite3.so.0.8.6` | `sqlite3BtreeNext` | library |
| 0.36% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.36% | `python` | `_Py_dict_lookup` | lookup |
| 0.36% | `_sqlite3.cpython-315-x86_64-linux-gnu.so` | `pysqlite_cursor_init` | library |
| 0.35% | `python` | `PyObject_CallObject` | dynamic |
| 0.35% | `python` | `PyEval_SaveThread` | interpreter |
| 0.35% | `math.cpython-315-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.35% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemGrow` | library |
| 0.34% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.31% | `_sqlite3.cpython-315-x86_64-linux-gnu.so` | `_pysqlite_build_py_params` | library |
| 0.31% | `libsqlite3.so.0.8.6` | `sqlite3_column_double` | library |
| 0.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.31% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.31% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemSetStr` | library |
| 0.30% | `python` | `_PyEval_Vector` | interpreter |
| 0.30% | `_sqlite3.cpython-315-x86_64-linux-gnu.so` | `step_callback` | library |
| 0.30% | `python` | `PyTuple_FromArray` | tuple |
| 0.29% | `python` | `pthread_cond_signal@plt` | unknown |
| 0.29% | `python` | `_PyCompactLong_Add` | unknown |
| 0.29% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemRelease` | library |
| 0.29% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.28% | `python` | `listiter_dealloc` | memory |
| 0.28% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.27% | `python` | `PyMethod_New` | memory |
| 0.26% | `python` | `_PyDict_GetItemRef_KnownHash_LockHeld` | dict |
| 0.26% | `python` | `float_dealloc` | memory |
| 0.25% | `python` | `long_dealloc` | memory |
| 0.25% | `python` | `lru_cache_make_key` | unknown |

## sympy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.38% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 15.13% | `[JIT]` | `jit` | jit |
| 4.26% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.70% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.30% | `python` | `_Py_Dealloc` | memory |
| 2.23% | `python` | `_PyObject_Malloc` | memory |
| 2.17% | `python` | `_Py_dict_lookup` | lookup |
| 1.90% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.65% | `python` | `initialize_locals` | interpreter |
| 1.60% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.51% | `python` | `_PyObject_Free` | memory |
| 1.45% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.41% | `python` | `tuple_dealloc` | memory |
| 1.21% | `python` | `PyType_IsSubtype` | dynamic |
| 1.15% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.07% | `python` | `tuple_alloc` | memory |
| 0.91% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.87% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.85% | `python` | `PyDict_GetItemRef` | dict |
| 0.66% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.65% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.65% | `python` | `insertdict` | dict |
| 0.62% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.58% | `python` | `dictiter_iternextitem` | dict |
| 0.58% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.58% | `python` | `_PyEval_Vector` | interpreter |
| 0.53% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.50% | `python` | `PyUnicode_RichCompare` | str |
| 0.48% | `python` | `setiter_iternext` | miscobj |
| 0.47% | `python` | `PyTuple_FromArray` | tuple |
| 0.46% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.44% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.41% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 0.41% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.41% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.40% | `python` | `slot_tp_richcompare` | dynamic |
| 0.39% | `python` | `PyObject_IsInstance` | dynamic |
| 0.38% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.37% | `python` | `PyCMethod_New` | memory |
| 0.37% | `python` | `insert_to_emptydict` | dict |
| 0.36% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.36% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.36% | `python` | `PyObject_IsTrue` | dynamic |
| 0.35% | `python` | `dict_dealloc` | memory |
| 0.34% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.34% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.34% | `python` | `_Py_NewReference` | memory |
| 0.33% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `PyDict_Next` | dict |
| 0.32% | `python` | `_Py_TriggerGC` | unknown |
| 0.31% | `python` | `new_dict` | dict |
| 0.30% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.29% | `python` | `PyObject_Hash` | dynamic |
| 0.29% | `python` | `_PyObject_GC_New` | gc |
| 0.29% | `python` | `PyTuple_GetSlice` | tuple |
| 0.28% | `python` | `PyObject_RichCompare` | dynamic |
| 0.28% | `python` | `PyList_New.constprop.0` | memory |
| 0.28% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.28% | `python` | `list_sort_impl` | list |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.27% | `python` | `_PyEval_GetIter` | interpreter |
| 0.26% | `python` | `_PyType_GetDict` | dynamic |

## telco

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 30.53% | `[JIT]` | `jit` | jit |
| 8.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.55% | `python` | `initialize_locals` | interpreter |
| 2.46% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.31% | `python` | `_PyObject_Malloc` | memory |
| 1.90% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.84% | `python` | `_PyObject_Free` | memory |
| 1.78% | `python` | `subtype_dealloc` | memory |
| 1.76% | `python` | `_Py_Dealloc` | memory |
| 1.65% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.09% | `python` | `_PyEval_Vector` | interpreter |
| 1.04% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.02% | `python` | `_PyCompactLong_Add` | unknown |
| 0.97% | `python` | `PyLong_FromString` | int |
| 0.96% | `python` | `long_to_decimal_string_internal` | int |
| 0.90% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.85% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.84% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.71% | `python` | `PyObject_IsTrue` | dynamic |
| 0.66% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.59% | `python` | `_Py_dict_lookup` | lookup |
| 0.56% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRefSteal` | unknown |
| 0.54% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.50% | `python` | `sre_ucs1_match` | library |
| 0.50% | `python` | `tuple_alloc` | memory |
| 0.48% | `python` | `PyObject_Size` | dynamic |
| 0.48% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.46% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.46% | `python` | `tp_new_wrapper` | memory |
| 0.46% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.45% | `python` | `slot_nb_bool` | unknown |
| 0.44% | `python` | `PyType_IsSubtype` | dynamic |
| 0.44% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.42% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.42% | `python` | `PyType_GenericAlloc` | memory |
| 0.41% | `python` | `PyLong_FromSsize_t` | int |
| 0.40% | `python` | `PyNumber_Long` | dynamic |
| 0.39% | `python` | `tuple_dealloc` | memory |
| 0.39% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.39% | `python` | `PyNumber_Multiply` | dynamic |
| 0.37% | `python` | `PyTuple_FromArray` | tuple |
| 0.37% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.37% | `python` | `PyObject_IsInstance` | dynamic |
| 0.37% | `python` | `PyObject_Str` | dynamic |
| 0.35% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.35% | `libc.so.6` | `_int_malloc` | libc |
| 0.34% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.34% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.32% | `python` | `PyUnicode_Concat` | str |
| 0.32% | `python` | `_PyUnicode_Equal` | str |
| 0.32% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.31% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.31% | `python` | `_Py_NewReference` | memory |
| 0.29% | `python` | `PyUnicode_New` | memory |
| 0.29% | `python` | `min_max` | unknown |
| 0.29% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.28% | `libc.so.6` | `malloc` | libc |
| 0.27% | `python` | `PyDict_GetItemRef` | dict |
| 0.27% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.26% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.26% | `python` | `long_pow` | int |
| 0.26% | `python` | `object_isinstance` | dynamic |

## thrift

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.59% | `[JIT]` | `jit` | jit |
| 5.77% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.04% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.04% | `python` | `_PyObject_Malloc` | memory |
| 2.99% | `python` | `initialize_locals` | interpreter |
| 2.48% | `python` | `_Py_Dealloc` | memory |
| 2.37% | `apache::thrift::py::TType,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*,` | unknown |
| 2.32% | `python` | `_PyObject_Free` | memory |
| 1.78% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.69% | `python` | `_Py_dict_lookup` | lookup |
| 1.59% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.54% | `python` | `insert_to_emptydict` | dict |
| 1.45% | `python` | `PyDict_GetItemRef` | dict |
| 1.39% | `python` | `insertdict` | dict |
| 1.19% | `_object*)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType,` | unknown |
| 1.12% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.11% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.08% | `python` | `subtype_dealloc` | memory |
| 1.05% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.98% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.96% | `python` | `PyLong_AsLong` | int |
| 0.84% | `python` | `PyTuple_Size` | tuple |
| 0.84% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.82% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.81% | `python` | `unicode_from_format` | str |
| 0.79% | `python` | `PyDict_Next` | dict |
| 0.78% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.77% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.71% | `python` | `_PyEval_Vector` | interpreter |
| 0.71% | `python` | `PyObject_Call` | dynamic |
| 0.69% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.69% | `python` | `tuple_dealloc` | memory |
| 0.66% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.62% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.58% | `_object*,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readStruct(_object*,` | unknown |
| 0.57% | `python` | `dict_dealloc` | memory |
| 0.57% | `short&)` | `apache::thrift::py::BinaryProtocol::readFieldBegin(apache::thrift::py::TType&,` | unknown |
| 0.53% | `python` | `PyDict_SetItem` | dict |
| 0.53% | `python` | `_PyDict_FromItems` | dict |
| 0.51% | `python` | `PyObject_GetAttr` | dynamic |
| 0.50% | `python` | `PyType_GenericAlloc` | memory |
| 0.48% | `python` | `tuple_alloc` | memory |
| 0.47% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.47% | `python` | `_PyObject_VectorcallDictTstate` | dynamic |
| 0.46% | `python` | `vgetargs1_impl` | calls |
| 0.46% | `python` | `convertitem.constprop.0` | unknown |
| 0.45% | `int)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readBytes(char**,` | unknown |
| 0.44% | `python` | `PyDict_New` | memory |
| 0.44% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.44% | `python` | `find_first_nonascii` | str |
| 0.43% | `python` | `dict_merge` | dict |
| 0.42% | `python` | `_Py_NewReference` | memory |
| 0.40% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.40% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.40% | `python` | `new_dict` | dict |
| 0.40% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.39% | `python` | `PyUnicode_RichCompare` | str |
| 0.39% | `python` | `_PyType_GetDict` | dynamic |
| 0.38% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.38% | `python` | `PyTuple_FromArray` | tuple |
| 0.38% | `libc.so.6` | `malloc` | libc |
| 0.37% | `_object*)` | `apache::thrift::py::parse_struct_item_spec(apache::thrift::py::StructItemSpec*,` | unknown |
| 0.37% | `python` | `_Py_module_getattro_impl` | unknown |
| 0.37% | `python` | `_PyObject_Calloc` | memory |
| 0.36% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.36% | `python` | `_PyDict_Next` | dict |
| 0.34% | `fastbinary.cpython-315-x86_64-linux-gnu.so` | `decode_binary` | library |
| 0.33% | `python` | `_PyObject_Realloc` | memory |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.33% | `python` | `PyList_New` | memory |
| 0.32% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.31% | `python` | `listiter_next` | list |
| 0.31% | `python` | `list_dealloc` | memory |
| 0.31% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.30% | `python` | `type_call` | dynamic |
| 0.29% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.28% | `python` | `do_super_lookup` | dynamic |
| 0.27% | `python` | `delitem_common` | dynamic |
| 0.27% | `python` | `slot_tp_init` | unknown |
| 0.27% | `python` | `object_vacall` | dynamic |
| 0.26% | `python` | `PyObject_Vectorcall` | dynamic |

## tomli_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 30.22% | `[JIT]` | `jit` | jit |
| 7.66% | `python` | `set_lookkey` | miscobj |
| 4.98% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.15% | `python` | `_PyCompactLong_Add` | unknown |
| 4.05% | `python` | `_PyUnicode_Equal` | str |
| 3.05% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.24% | `python` | `_PySet_Contains` | miscobj |
| 2.04% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.76% | `python` | `_Py_dict_lookup` | lookup |
| 1.69% | `python` | `_PyObject_Malloc` | memory |
| 1.64% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.60% | `python` | `PyDict_GetItemRef` | dict |
| 1.57% | `python` | `_Py_Dealloc` | memory |
| 1.07% | `python` | `_PyObject_Free` | memory |
| 1.01% | `python` | `_PyIncrementalNewlineDecoder_decode` | memory |
| 1.01% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.83% | `python` | `_PyUnicode_FromUCS4.part.0` | str |
| 0.82% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.81% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.78% | `python` | `sre_ucs4_match` | library |
| 0.75% | `python` | `tuple_dealloc` | memory |
| 0.73% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.71% | `python` | `_Py_NewReference` | memory |
| 0.69% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.69% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.63% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.59% | `python` | `tuple_alloc` | memory |
| 0.45% | `python` | `PyDict_Contains` | dict |
| 0.44% | `[unknown]` | `0xffffffffab6011d3` | unknown |
| 0.43% | `python` | `PyType_IsSubtype` | dynamic |
| 0.42% | `[unknown]` | `0xffffffffab3cfc07` | unknown |
| 0.40% | `python` | `initialize_locals` | interpreter |
| 0.40% | `python` | `unicode_decode_utf8_impl` | str |
| 0.39% | `python` | `siphash13` | str |
| 0.37% | `python` | `replace` | str |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `python` | `memcmp@plt` | unknown |
| 0.32% | `python` | `make_range_object` | unknown |
| 0.29% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `[unknown]` | `0xffffffffab60128c` | unknown |
| 0.27% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.27% | `python` | `_PyEval_UnpackIndices` | interpreter |

## tornado_http

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.26% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.08% | `[JIT]` | `jit` | jit |
| 1.92% | `python` | `_PyObject_Malloc` | memory |
| 1.87% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.82% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.54% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.34% | `python` | `_Py_Dealloc` | memory |
| 1.19% | `python` | `_PyObject_Free` | memory |
| 1.18% | `python` | `sre_ucs1_match` | library |
| 1.09% | `python` | `initialize_locals` | interpreter |
| 0.94% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.87% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.68% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.68% | `[unknown]` | `0xffffffffab6001c6` | unknown |
| 0.67% | `python` | `_Py_dict_lookup` | lookup |
| 0.59% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.57% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.56% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.55% | `python` | `tuple_dealloc` | memory |
| 0.55% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.49% | `python` | `PyType_IsSubtype` | dynamic |
| 0.45% | `[unknown]` | `0xffffffffab3d02da` | unknown |
| 0.44% | `python` | `PyDict_GetItemRef` | dict |
| 0.44% | `python` | `tuple_alloc` | memory |
| 0.43% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.43% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.40% | `libc.so.6` | `_int_malloc` | libc |
| 0.40% | `libc.so.6` | `malloc` | libc |
| 0.37% | `python` | `_PyEval_Vector` | interpreter |
| 0.34% | `python` | `subtype_dealloc` | memory |
| 0.34% | `python` | `sre_ucs1_count` | library |
| 0.32% | `[unknown]` | `0xffffffffab600151` | unknown |
| 0.29% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.29% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.28% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.28% | `[unknown]` | `0xffffffffab60010f` | unknown |

## typing_runtime_protocols

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.67% | `[JIT]` | `jit` | jit |
| 5.62% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.90% | `python` | `weakref___new__` | memory |
| 3.40% | `python` | `PyTuple_FromArray` | tuple |
| 3.31% | `python` | `_Py_Dealloc` | memory |
| 3.15% | `python` | `_PyObject_Malloc` | memory |
| 2.89% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.87% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 2.86% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 2.70% | `python` | `_Py_dict_lookup` | lookup |
| 2.36% | `python` | `tuple_dealloc` | memory |
| 2.35% | `python` | `PyArg_UnpackTuple` | calls |
| 2.32% | `python` | `_PyObject_Free` | memory |
| 1.96% | `python` | `tuple_alloc` | memory |
| 1.78% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.40% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.20% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.18% | `python` | `PyObject_Vectorcall` | dynamic |
| 1.14% | `python` | `_Py_BuiltinCallFast_StackRefSteal` | unknown |
| 1.08% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.04% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 1.01% | `python` | `type_call` | dynamic |
| 0.98% | `python` | `set_lookkey` | miscobj |
| 0.92% | `python` | `PyList_New.constprop.0` | memory |
| 0.86% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.69% | `python` | `tuple_hash` | tuple |
| 0.66% | `python` | `getset_get` | dynamic |
| 0.65% | `python` | `_Py_NewReference` | memory |
| 0.63% | `python` | `initialize_locals` | interpreter |
| 0.61% | `python` | `_Py_type_getattro_impl` | dynamic |
| 0.57% | `python` | `list_dealloc` | memory |
| 0.55% | `python` | `PyObject_Hash` | dynamic |
| 0.55% | `python` | `wrap_descr_get` | unknown |
| 0.55% | `python` | `tuple_richcompare` | tuple |
| 0.54% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.54% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.49% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.48% | `python` | `weakref___init__` | miscobj |
| 0.47% | `python` | `_PyObject_GC_New` | gc |
| 0.46% | `python` | `PyType_IsSubtype` | dynamic |
| 0.46% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.45% | `python` | `frame_dealloc` | memory |
| 0.45% | `python` | `PyMapping_Check` | dynamic |
| 0.45% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.45% | `python` | `_PyDict_GetItemRef_KnownHash_LockHeld` | dict |
| 0.44% | `python` | `wrapper_call` | unknown |
| 0.42% | `python` | `PyObject_Call` | dynamic |
| 0.40% | `python` | `setiter_iternext` | miscobj |
| 0.39% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.39% | `python` | `_PyStaticType_GetState` | unknown |
| 0.37% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.37% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.37% | `python` | `lru_cache_make_key` | unknown |
| 0.36% | `python` | `PySequence_Contains` | dynamic |
| 0.35% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.34% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.34% | `python` | `weakref_hash` | miscobj |
| 0.33% | `python` | `new_dict` | dict |
| 0.29% | `python` | `_Py_type_getattro` | lookup |
| 0.28% | `python` | `PyWeakref_NewRef` | memory |
| 0.28% | `python` | `PyDictProxy_New` | memory |
| 0.28% | `python` | `_PyObject_Realloc` | memory |
| 0.26% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 0.26% | `python` | `_PyEval_Vector` | interpreter |
| 0.26% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.26% | `python` | `type_get_mro` | dynamic |
| 0.26% | `python` | `PyObject_GC_Del` | gc |
| 0.25% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.25% | `python` | `object_richcompare` | dynamic |

## unpack_sequence

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 71.97% | `[JIT]` | `jit` | jit |
| 26.97% | `python` | `_PyEval_EvalFrameDefault` | interpreter |

## unpickle

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 9.40% | `python` | `_PyObject_Malloc` | memory |
| 9.18% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `load` | library |
| 6.30% | `python` | `_PyObject_Free` | memory |
| 6.14% | `python` | `find_first_nonascii` | str |
| 4.95% | `python` | `siphash13` | str |
| 4.68% | `python` | `insertdict.isra.0` | dict |
| 4.30% | `python` | `unicode_decode_utf8.part.0` | str |
| 4.13% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.95% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `load_counted_binunicode` | library |
| 3.83% | `python` | `_Py_Dealloc` | memory |
| 3.61% | `python` | `PyUnicode_New.part.0` | memory |
| 2.52% | `python` | `_Py_dict_lookup` | lookup |
| 2.37% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Unpickler_MemoPut` | library |
| 2.25% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `do_setitems` | library |
| 2.10% | `python` | `dict_ass_sub` | dict |
| 1.93% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.66% | `python` | `unicode_dealloc` | memory |
| 1.63% | `python` | `dict_dealloc` | memory |
| 1.59% | `python` | `find_empty_slot.constprop.0` | dict |
| 1.32% | `python` | `PyObject_SetItem` | dynamic |
| 1.31% | `python` | `build_indices_unicode` | dict |
| 1.19% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Unpickler_clear` | library |
| 1.05% | `python` | `_PyObject_Realloc` | memory |
| 0.81% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Pdata_push` | library |
| 0.79% | `python` | `_Py_NewReference` | memory |
| 0.68% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.66% | `python` | `PyLong_FromLong` | int |
| 0.65% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Unpickler_MemoGet` | library |
| 0.61% | `python` | `PyUnicode_DecodeUTF8` | str |
| 0.55% | `python` | `list_dealloc` | memory |
| 0.51% | `python` | `unicode_hash` | str |
| 0.51% | `python` | `dictresize` | dict |
| 0.46% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.42% | `libc.so.6` | `malloc` | libc |
| 0.40% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.36% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.36% | `python` | `PyList_New` | memory |
| 0.35% | `python` | `PyObject_Hash` | dynamic |
| 0.35% | `python` | `PyObject_Malloc` | dynamic |
| 0.33% | `python` | `memcpy@plt` | memory |
| 0.32% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Unpickler_New` | library |
| 0.32% | `python` | `insert_to_emptydict.isra.0` | dict |
| 0.31% | `python` | `Py_HashBuffer` | unknown |
| 0.30% | `python` | `new_keys_object` | dict |
| 0.30% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.29% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyUnicode_DecodeUTF8@plt` | library |
| 0.29% | `python` | `PyObject_Free` | dynamic |
| 0.29% | `python` | `list_ass_slice_lock_held` | list |

## unpickle_list

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.36% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `load` | library |
| 7.85% | `python` | `list_ass_slice_lock_held` | list |
| 7.08% | `python` | `PyList_New` | memory |
| 6.95% | `python` | `_PyObject_Free` | memory |
| 6.94% | `python` | `list_dealloc` | memory |
| 5.69% | `python` | `PyLong_FromLong` | int |
| 5.46% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `do_append` | library |
| 5.44% | `python` | `_PyObject_Malloc` | memory |
| 5.08% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Pdata_push` | library |
| 4.23% | `python` | `PyMem_Calloc` | memory |
| 3.68% | `python` | `_Py_Dealloc` | memory |
| 3.31% | `python` | `_PyObject_Calloc` | memory |
| 2.84% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.69% | `python` | `_PyObject_Realloc` | memory |
| 1.41% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `marker` | library |
| 1.23% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Unpickler_MemoPut` | library |
| 1.05% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyLong_FromLong@plt` | library |
| 0.87% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.78% | `python` | `PySequence_Fast` | dynamic |
| 0.72% | `python` | `_Py_NewReference` | memory |
| 0.68% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `Unpickler_clear` | library |
| 0.61% | `python` | `PyList_SetSlice` | list |
| 0.59% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.38% | `python` | `PyMem_Free` | memory |
| 0.37% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `_Unpickler_New` | library |
| 0.35% | `_pickle.cpython-315-x86_64-linux-gnu.so` | `PyList_New@plt` | library |
| 0.32% | `python` | `PyMem_Realloc` | memory |

## unpickle_pure_python

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 48.64% | `[JIT]` | `jit` | jit |
| 3.19% | `python` | `_PyCallMethodDescriptorFast_StackRefSteal` | unknown |
| 3.18% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.83% | `python` | `_PyObject_Malloc` | memory |
| 2.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.53% | `python` | `_Py_dict_lookup` | lookup |
| 2.30% | `python` | `_Py_convert_optional_to_ssize_t` | unknown |
| 2.02% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.81% | `python` | `PyDict_GetItemRef` | dict |
| 1.72% | `python` | `PyObject_IsTrue` | dynamic |
| 1.33% | `python` | `_PyObject_Free` | memory |
| 1.31% | `python` | `_io_BytesIO_read` | unknown |
| 1.30% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.12% | `python` | `bytes_subscript` | str |
| 1.06% | `python` | `insertdict` | dict |
| 1.05% | `python` | `PyUnicode_Decode` | str |
| 0.98% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.94% | `python` | `PyObject_IsInstance` | dynamic |
| 0.93% | `python` | `PyLong_AsSsize_t` | int |
| 0.84% | `python` | `_Py_Dealloc` | memory |
| 0.79% | `python` | `PyLong_FromSsize_t` | int |
| 0.79% | `python` | `PyObject_GetItem` | dynamic |
| 0.67% | `python` | `find_first_nonascii` | str |
| 0.66% | `python` | `unicode_vectorcall` | str |
| 0.56% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.56% | `python` | `_Py_CallBuiltinClass_StackRefSteal` | unknown |
| 0.52% | `python` | `list_append` | list |
| 0.49% | `python` | `PyObject_Size` | dynamic |
| 0.48% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.43% | `python` | `list_subscript` | list |
| 0.43% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.42% | `python` | `long_hash` | int |
| 0.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.38% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.34% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.33% | `python` | `siphash13` | str |
| 0.32% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.32% | `python` | `PyObject_Hash` | dynamic |
| 0.31% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.29% | `python` | `PyUnicode_New.part.0` | memory |
| 0.28% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.27% | `python` | `initialize_locals` | interpreter |
| 0.26% | `python` | `_PyObject_Realloc` | memory |
| 0.26% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |

## xdsl

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.95% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 12.71% | `[JIT]` | `jit` | jit |
| 4.30% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.20% | `python` | `_PyObject_Malloc` | memory |
| 2.52% | `python` | `_Py_Dealloc` | memory |
| 1.91% | `python` | `_PyObject_Free` | memory |
| 1.78% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.75% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.48% | `python` | `_Py_dict_lookup` | lookup |
| 1.15% | `python` | `initialize_locals` | interpreter |
| 1.02% | `python` | `tuple_dealloc` | memory |
| 1.00% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.98% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.98% | `python` | `PyObject_SetAttr` | dynamic |
| 0.96% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.90% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.90% | `python` | `gc_collect_region` | gc |
| 0.87% | `python` | `PyDict_GetItemRef` | dict |
| 0.83% | `python` | `tuple_alloc` | memory |
| 0.81% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.76% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.73% | `python` | `unicode_from_format` | str |
| 0.73% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.70% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.65% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.56% | `python` | `visit_add_to_container` | gc |
| 0.51% | `python` | `set_lookkey` | miscobj |
| 0.50% | `python` | `_PyEval_Vector` | interpreter |
| 0.50% | `python` | `PyTuple_FromArray` | tuple |
| 0.49% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.47% | `python` | `PyType_IsSubtype` | dynamic |
| 0.46% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.45% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.43% | `python` | `PyType_GenericAlloc` | memory |
| 0.43% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.40% | `python` | `subtype_dealloc` | memory |
| 0.40% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.37% | `python` | `_Py_NewReference` | memory |
| 0.36% | `python` | `_PyGC_Collect` | gc |
| 0.35% | `python` | `tuple_iter` | tuple |
| 0.35% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.34% | `python` | `_PyUnicode_InternMortal` | str |
| 0.34% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.33% | `python` | `do_super_lookup` | dynamic |
| 0.33% | `python` | `PyObject_IsInstance` | dynamic |
| 0.32% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.32% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.31% | `python` | `_PyType_GetDict` | dynamic |
| 0.31% | `python` | `_Py_type_getattro` | lookup |
| 0.31% | `python` | `dict_traverse` | gc |
| 0.29% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.28% | `python` | `_PySuper_Lookup` | dynamic |
| 0.28% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.28% | `python` | `type_call` | dynamic |
| 0.28% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.26% | `python` | `_PyEval_GetIter` | interpreter |
| 0.26% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.26% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.26% | `python` | `PyObject_Hash` | dynamic |
| 0.26% | `python` | `subtype_traverse` | gc |
| 0.25% | `python` | `method_dealloc` | memory |

## xml_etree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 11.11% | `[JIT]` | `jit` | jit |
| 6.02% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.03% | `python` | `_PyObject_Malloc` | memory |
| 3.15% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.02% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 3.00% | `python` | `_PyObject_Free` | memory |
| 2.98% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `normal_contentTok` | library |
| 2.79% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `normal_updatePosition` | library |
| 2.20% | `python` | `_Py_Dealloc` | memory |
| 2.19% | `python` | `visit_add_to_container` | gc |
| 1.60% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `accountingDiffTolerated.part.0` | library |
| 1.52% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `sip24_update.isra.0` | library |
| 1.46% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `doContent` | library |
| 1.23% | `python` | `_io_TextIOWrapper_write` | unknown |
| 1.21% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `normal_nameLength` | library |
| 1.20% | `python` | `_Py_dict_lookup` | lookup |
| 1.04% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `lookup.constprop.0` | library |
| 1.00% | `python` | `PyUnicode_Contains` | str |
| 0.97% | `python` | `initialize_locals` | interpreter |
| 0.94% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.93% | `python` | `find_first_nonascii` | str |
| 0.83% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.77% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `elementiter_next` | library |
| 0.77% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `expat_end_handler` | library |
| 0.77% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.77% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.76% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `normal_getAtts` | library |
| 0.76% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `treebuilder_handle_start` | library |
| 0.73% | `python` | `tuple_dealloc` | memory |
| 0.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.71% | `python` | `getset_get` | dynamic |
| 0.71% | `python` | `PyUnicode_New.part.0` | memory |
| 0.69% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `sip24_final` | library |
| 0.69% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.66% | `python` | `PyUnicode_Format` | str |
| 0.66% | `python` | `_PyEval_Vector` | interpreter |
| 0.64% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.60% | `python` | `siphash13` | str |
| 0.59% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.58% | `python` | `long_to_decimal_string_internal` | int |
| 0.52% | `python` | `_PyGC_Collect` | gc |
| 0.51% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `element_dealloc` | library |
| 0.51% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.50% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `storeAtts` | library |
| 0.49% | `python` | `PyList_New` | memory |
| 0.47% | `python` | `PyType_IsSubtype` | dynamic |
| 0.47% | `python` | `vgetargs1_impl` | calls |
| 0.46% | `python` | `list_dealloc` | memory |
| 0.45% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.44% | `python` | `mark_all_reachable` | unknown |
| 0.43% | `python` | `PyUnicode_Concat` | str |
| 0.43% | `python` | `_Py_NewReference` | memory |
| 0.43% | `python` | `PyTuple_Pack` | tuple |
| 0.42% | `python` | `_PyObject_GC_New` | gc |
| 0.42% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.41% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.41% | `python` | `_PyType_GetDict` | dynamic |
| 0.40% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `makeuniversal` | library |
| 0.39% | `python` | `tuple_alloc` | memory |
| 0.37% | `python` | `object_isinstance` | dynamic |
| 0.37% | `python` | `PyList_Append` | list |
| 0.37% | `python` | `stringlib__two_way` | str |
| 0.36% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.34% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.34% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.33% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.32% | `python` | `_PyObject_Realloc` | memory |
| 0.31% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `element_getitem` | library |
| 0.31% | `python` | `_textiowrapper_writeflush` | unknown |
| 0.31% | `python` | `PyTuple_FromArray` | tuple |
| 0.30% | `python` | `PyObject_Malloc` | dynamic |
| 0.30% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `expat_start_handler` | library |
| 0.29% | `python` | `convertitem.constprop.0` | unknown |
| 0.29% | `python` | `visit_decref` | gc |
| 0.28% | `python` | `gen_iternext` | miscobj |
| 0.28% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.28% | `python` | `unicode_dealloc` | memory |
| 0.28% | `python` | `slot_tp_iternext` | unknown |
| 0.28% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.28% | `python` | `PyObject_IsTrue` | dynamic |
| 0.28% | `python` | `PyObject_IsInstance` | dynamic |
| 0.27% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `element_gc_traverse` | library |
| 0.27% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.27% | `_elementtree.cpython-315-x86_64-linux-gnu.so` | `create_new_element.isra.0` | library |
| 0.27% | `pyexpat.cpython-315-x86_64-linux-gnu.so` | `utf8_toUtf8` | library |
| 0.26% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.26% | `python` | `PyObject_GC_Track` | gc |
| 0.25% | `python` | `visit_reachable` | gc |
| 0.25% | `python` | `PyDict_GetItemWithError` | dict |


## Categories

### jit

18.64% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 18.64% | [JIT] | jit |

### memory

13.28% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.44% | python | _PyObject_Malloc |
| 2.21% | python | _Py_Dealloc |
| 1.86% | python | _PyObject_Free |
| 0.85% | python | tuple_dealloc |
| 0.69% | python | list_dealloc |
| 0.58% | python | tuple_alloc |
| 0.46% | python | _Py_NewReference |
| 0.29% | python | PyList_New.constprop.0 |
| 0.23% | python | _PyObject_Realloc |
| 0.22% | python | subtype_dealloc |
| 0.21% | python | _PyType_AllocNoTrack |
| 0.19% | python | PyTuple_New |
| 0.16% | python | gen_dealloc |
| 0.16% | python | PyType_GenericAlloc |
| 0.12% | python | PyUnicode_New.part.0 |
| 0.12% | python | PyCMethod_New |
| 0.11% | python | dict_dealloc |
| 0.10% | python | long_dealloc |
| 0.09% | python | listiter_dealloc |
| 0.09% | python | PyList_New |
| 0.09% | python | long_alloc |
| 0.09% | python | PyMethod_New |
| 0.09% | python | PySlice_New |
| 0.08% | python | unicode_dealloc |
| 0.08% | python | _PyLong_ExactDealloc |
| 0.08% | python | _PyFloat_ExactDealloc |
| 0.08% | python | zip_new |
| 0.07% | python | _PyObject_Calloc |
| 0.07% | python | PyFunction_NewWithQualName |
| 0.07% | python | method_dealloc |
| 0.07% | python | PyDict_New |
| 0.06% | python | PyUnicode_New |
| 0.06% | python | set_dealloc |
| 0.05% | python | meth_dealloc |
| 0.05% | python | pattern_new_match |
| 0.05% | python | PyMem_Free |
| 0.05% | python | PyObject_CallFinalizerFromDealloc |
| 0.05% | python | memcpy@plt |
| 0.05% | python | float_dealloc |
| 0.05% | python | context_tp_dealloc |
| 0.05% | python | memset@plt |
| 0.04% | python | func_dealloc |
| 0.04% | python | PyMem_Calloc |
| 0.04% | python | _PyIncrementalNewlineDecoder_decode |
| 0.04% | python | zip_dealloc |
| 0.03% | python | slice_dealloc |
| 0.03% | python | allocate_from_new_pool |
| 0.02% | python | tp_new_wrapper |
| 0.02% | python | PyMem_Realloc |
| 0.02% | python | PyMem_Malloc |
| 0.02% | python | weakref___new__ |
| 0.02% | python | frame_dealloc |
| 0.02% | python | object_new |
| 0.02% | python | async_gen_asend_dealloc |
| 0.02% | python | object_dealloc |
| 0.02% | python | cell_dealloc |
| 0.02% | python | dictiter_dealloc |
| 0.01% | python | StopIteration_dealloc |
| 0.01% | python | PyCell_New |
| 0.01% | python | _PyAsyncGenValueWrapperNew |
| 0.01% | python | BaseException_new |
| 0.01% | python | async_gen_wrapped_val_dealloc |
| 0.01% | python | BaseException_dealloc |
| 0.01% | python | dictview_dealloc |
| 0.01% | python | range_dealloc |
| 0.01% | python | match_dealloc |
| 0.01% | python | tupleiter_dealloc |
| 0.01% | python | tb_dealloc |
| 0.01% | python | slot_tp_new |
| 0.01% | python | unicode_new |
| 0.01% | python | _PyMem_RawMalloc |
| 0.01% | python | _PyUnicode_ExactDealloc |
| 0.01% | python | PyFunction_New |
| 0.00% | python | striter_dealloc |
| 0.00% | python | _Py_NewReferenceNoTotal |
| 0.00% | python | code_dealloc |
| 0.00% | python | future_new_iter |
| 0.00% | python | TaskObj_dealloc |
| 0.00% | python | _PyMem_RawFree |
| 0.00% | python | PyObject_Realloc |
| 0.00% | python | PyWeakref_NewRef |
| 0.00% | python | rangeiter_dealloc |
| 0.00% | python | reversed_new_impl |
| 0.00% | python | AttributeError_dealloc |
| 0.00% | python | structseq_dealloc |
| 0.00% | python | type_new |
| 0.00% | python | TaskStepMethWrapper_dealloc |
| 0.00% | python | FutureObj_dealloc |
| 0.00% | python | setiter_dealloc |

### interpreter

10.74% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 6.78% | python | _PyEval_EvalFrameDefault |
| 1.38% | python | _PyFrame_ClearExceptCode |
| 0.69% | python | initialize_locals |
| 0.61% | python | _PyEval_FrameClearAndPop |
| 0.47% | python | _PyEvalFramePushAndInit |
| 0.29% | python | _PyEval_Vector |
| 0.12% | python | _PyEval_SliceIndex |
| 0.12% | python | _PyEval_GetIter |
| 0.05% | python | call_instrumentation_vector.part.0.isra.0 |
| 0.03% | python | _PyStack_UnpackDict |
| 0.03% | python | _Py_call_instrumentation_line |
| 0.02% | python | _PyCode_Quicken |
| 0.02% | python | _PyEval_UnpackIndices |
| 0.01% | python | _PyFrame_Traverse |
| 0.01% | python | _PyEvalFramePushAndInit_Ex |
| 0.01% | python | _PyEval_MonitorRaise |
| 0.01% | python | _PyEval_SliceIndexNotNone |
| 0.01% | python | _PyFrame_New_NoTrack |
| 0.01% | python | _PyPegen_is_memoized |
| 0.01% | python | _PyEval_GetAwaitable |
| 0.01% | python | _PyCode_New |
| 0.01% | python | _PyFrame_MakeAndSetFrameObject |
| 0.00% | python | _PyCode_GetCode |
| 0.00% | python | _PyEval_GetANext |
| 0.00% | python | PyEval_SaveThread |
| 0.00% | python | _PyPegen_expect_token |
| 0.00% | python | _PyEval_ImportName |
| 0.00% | python | PyEval_EvalCode |
| 0.00% | python | _PyEval_CheckExceptTypeValid |
| 0.00% | python | PyEval_GetFrame |
| 0.00% | python | _PyEval_ImportFrom |
| 0.00% | python | _PyEval_LoadGlobalStackRef |
| 0.00% | python | _PyEval_EnsureBuiltins |

### unknown

10.42% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.26% | python | _PyType_LookupStackRefAndVersion |
| 0.92% | [unknown] | 0xffffffff939cb32a |
| 0.47% | python | _PyCompactLong_Add |
| 0.34% | python | _Py_BuiltinCallFast_StackRefSteal |
| 0.33% | python | _Py_VectorCall_StackRefSteal |
| 0.23% | python | mark_all_reachable |
| 0.20% | python | _PyForIter_VirtualIteratorNext |
| 0.20% | [unknown] | 0xffffffff939cac57 |
| 0.20% | python | zip_next |
| 0.16% | python | _PyCompactLong_Subtract |
| 0.13% | python | _Py_bytes_upper |
| 0.13% | python | _PyCallMethodDescriptorFast_StackRefSteal |
| 0.13% | python | lookup_method_ex.constprop.0 |
| 0.10% | [unknown] | 0xffffffffab6011d3 |
| 0.09% | python | convertitem.constprop.0 |
| 0.08% | [unknown] | 0xffffffffab3cfc07 |
| 0.08% | python | slot_mp_ass_subscript |
| 0.08% | python | _PyRunRemoteDebugger |
| 0.08% | python | wrapperdescr_call |
| 0.07% | python | _Py_type_getattro_stackref |
| 0.06% | [unknown] | 0xffffffffab60128c |
| 0.06% | python | _Py_BuiltinCallFastWithKeywords_StackRefSteal |
| 0.06% | python | _PyCallMethodDescriptorFastWithKeywords_StackRefSteal |
| 0.06% | python | _PyCompactLong_Multiply |
| 0.06% | python | func_clear |
| 0.06% | python | _Py_CallBuiltinClass_StackRefSteal |
| 0.06% | [unknown] | 0xffffffffab6011a9 |
| 0.06% | python | make_range_object |
| 0.05% | [unknown] | 0xffffffffab601631 |
| 0.05% | [unknown] | 0xffffffffab44a16e |
| 0.05% | python | PyBytesWriter_Create |
| 0.05% | python | builtin_sum |
| 0.05% | python | _Py_IsMainThread |
| 0.05% | python | _Py_VectorCallInstrumentation_StackRefSteal |
| 0.05% | [unknown] | 0xffffffffab6001c6 |
| 0.04% | python | PyIndex_Check |
| 0.04% | python | _Py_BuildMap_StackRefSteal |
| 0.04% | [unknown] | 0xffffffffab601618 |
| 0.04% | [unknown] | 0xffffffffab60125b |
| 0.04% | python | sys_audit_tstate |
| 0.04% | python | _PyMember_GetOffset |
| 0.04% | python | wrap_objobjargproc |
| 0.03% | python | recursive_issubclass |
| 0.03% | python | memcmp@plt |
| 0.03% | python | _Py_BuildString_StackRefSteal |
| 0.03% | python | min_max |
| 0.03% | python | maybe_small_long |
| 0.03% | python | vgetargskeywords_impl.constprop.0 |
| 0.03% | python | get_exception_handler.isra.0 |
| 0.03% | python | store_instance_attr_lock_held |
| 0.02% | python | build_indices_generic |
| 0.02% | [unknown] | 0xffffffff93c001c6 |
| 0.02% | python | _Py_strhex_impl |
| 0.02% | [unknown] | 0xffffffffab600151 |
| 0.02% | python | _Py_LoadAttr_StackRefSteal |
| 0.02% | python | TaskStepMethWrapper_call |
| 0.02% | python | _io_TextIOWrapper_write |
| 0.02% | [unknown] | 0xffffffffaa627923 |
| 0.02% | python | task_step_impl |
| 0.02% | [unknown] | 0xffffffffab60010f |
| 0.02% | python | PySys_Audit |
| 0.02% | python | PyBytesWriter_FinishWithPointer |
| 0.02% | python | _Py_MakeCoro |
| 0.02% | python | pthread_self@plt |
| 0.02% | python | _PyInterpreterState_GetConfig |
| 0.02% | python | clone_combined_dict_keys |
| 0.02% | python | unsafe_long_compare |
| 0.02% | python | context_run |
| 0.02% | python | _asyncio_Task___init__ |
| 0.02% | python | builtin_issubclass |
| 0.02% | python | _PyInterpreterState_Main |
| 0.02% | python | Py_HashBuffer |
| 0.02% | python | PyContext_CopyCurrent |
| 0.02% | python | bounded_lru_cache_wrapper |
| 0.02% | [unknown] | 0xffffffffab3d02da |
| 0.02% | python | TaskObj_clear |
| 0.02% | python | striter_next |
| 0.01% | [unknown] | 0xffffffffab6001bd |
| 0.01% | python | compactlongs_guard |
| 0.01% | [unknown] | 0xffffffffab60009d |
| 0.01% | python | gen_finalize |
| 0.01% | python | vectorcall_maybe |
| 0.01% | [unknown] | 0xffffffff92ce5d2b |
| 0.01% | python | any_find_slice |
| 0.01% | python | _PyFunction_SetVersion |
| 0.01% | python | binary_op1 |
| 0.01% | python | map_next |
| 0.01% | python | builtin_hasattr |
| 0.01% | python | pysiphash |
| 0.01% | python | slot_tp_init |
| 0.01% | python | unsafe_tuple_compare |
| 0.01% | python | _PyContext_Exit |
| 0.01% | python | future_schedule_callbacks |
| 0.01% | python | _PyBytes_Resize |
| 0.01% | [unknown] | 0xffffffffaa3e110e |
| 0.01% | python | _Py_TriggerGC |
| 0.01% | python | malloc@plt |
| 0.01% | python | task_wakeup |
| 0.01% | python | dictitems_iter |
| 0.01% | [unknown] | 0xffffffff93c00151 |
| 0.01% | python | lru_cache_make_key |
| 0.01% | python | builtin_id |
| 0.01% | [unknown] | 0xffffffffab4600b3 |
| 0.01% | python | compactlongs_and |
| 0.01% | [unknown] | 0xffffffff93c0010f |
| 0.01% | python | _PyCoro_GetAwaitableIter |
| 0.01% | python | wrapperdescr_get |
| 0.01% | python | tailmatch |
| 0.01% | python | do_mkvalue |
| 0.01% | python | _Py_convert_optional_to_ssize_t |
| 0.01% | [unknown] | 0xffffffff93c011d3 |
| 0.01% | [unknown] | 0xffffffff92c57dd9 |
| 0.01% | python | _PyContext_Enter |
| 0.01% | [unknown] | 0xffffffff92c532de |
| 0.01% | python | slot_nb_add |
| 0.01% | python | slot_tp_hash |
| 0.01% | [unknown] | 0xffffffffaa71b26f |
| 0.01% | python | func_descr_get |
| 0.01% | python | slot_sq_contains |
| 0.01% | [unknown] | 0xffffffffaa5a46fd |
| 0.01% | [unknown] | 0xffffffffab60125e |
| 0.01% | python | _asyncio_future_discard_from_awaited_by |
| 0.01% | python | FutureObj_clear |
| 0.01% | python | insert_split_key |
| 0.01% | python | builtin_sorted |
| 0.01% | [unknown] | 0xffffffff93c0009d |
| 0.01% | python | charmaptranslate_lookup |
| 0.01% | apache::thrift::py::TType, | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*, |
| 0.01% | [unknown] | 0xffffffffaa6591b8 |
| 0.01% | [unknown] | 0xffffffff93c001bd |
| 0.01% | python | strlen@plt |
| 0.01% | python | PyBytesWriter_Finish |
| 0.01% | python | _Py_module_getattro_impl |
| 0.01% | [unknown] | 0xffffffffaa6cdbde |
| 0.01% | python | _PyOptimizer_Optimize |
| 0.01% | python | int_to_bytes |
| 0.01% | python | slot_sq_length |
| 0.01% | python | slot_nb_bool |
| 0.01% | [unknown] | 0xffffffffaa5d8736 |
| 0.01% | python | PyType_GetModule |
| 0.01% | python | mro_implementation_unlocked |
| 0.01% | python | slot_tp_iternext |
| 0.01% | python | _Py_slot_tp_getattr_hook |
| 0.01% | [unknown] | 0xffffffffaa2c7c44 |
| 0.01% | [unknown] | 0xffffffffaa3db49f |
| 0.01% | python | listreviter_next |
| 0.01% | python | _abc__abc_instancecheck |
| 0.01% | python | int_from_bytes |
| 0.01% | python | task_call_step_soon |
| 0.01% | [unknown] | 0xffffffff93c0128c |
| 0.01% | python | match_group |
| 0.01% | python | PyBytesWriter_GetData |
| 0.01% | python | _textiowrapper_writeflush |
| 0.01% | python | _Py_Specialize_LoadAttr |
| 0.01% | python | _asyncio_future_add_to_awaited_by |
| 0.01% | [vdso] | 0x0000000000000b00 |
| 0.01% | python | merge_from_seq2_lock_held |
| 0.01% | [unknown] | 0xffffffffaa64837f |
| 0.01% | python | unsafe_object_compare |
| 0.01% | [unknown] | 0xffffffffab601622 |
| 0.01% | python | gallop_right |
| 0.01% | python | merge_at |
| 0.00% | [unknown] | 0xffffffffaa9feda0 |
| 0.00% | [unknown] | 0xffffffffaa6ca7f6 |
| 0.00% | python | PyTime_AsSecondsDouble |
| 0.00% | [unknown] | 0xffffffffab45f8c7 |
| 0.00% | [unknown] | 0xffffffff93c01631 |
| 0.00% | [unknown] | 0xffffffffab450653 |
| 0.00% | python | gallop_left |
| 0.00% | python | nonzero_float_compactlong_guard |
| 0.00% | python | match_getslice_by_index |
| 0.00% | python | _Py_ReachedRecursionLimitWithMargin |
| 0.00% | [unknown] | 0xffffffff92866fc0 |
| 0.00% | python | TaskObj_finalize |
| 0.00% | python | match_getindex |
| 0.00% | python | free@plt |
| 0.00% | python | future_add_done_callback |
| 0.00% | python | _io_BytesIO_read |
| 0.00% | [unknown] | 0xffffffffaa6cdb17 |
| 0.00% | python | memmove@plt |
| 0.00% | python | subtype_clear |
| 0.00% | [unknown] | 0xffffffff93c011a9 |
| 0.00% | [unknown] | 0xffffffffaa6ca7cc |
| 0.00% | [unknown] | 0xffffffff92c57678 |
| 0.00% | [unknown] | 0xffffffffaa6480f3 |
| 0.00% | python | _asyncio_Future_add_done_callback |
| 0.00% | [unknown] | 0xffffffffaa3db4ab |
| 0.00% | [unknown] | 0xffffffffaa6cdc1d |
| 0.00% | python | slot_sq_item |
| 0.00% | [unknown] | 0xffffffffab3d0187 |
| 0.00% | [unknown] | 0xffffffff93a44c0e |
| 0.00% | python | _Py_bytes_contains |
| 0.00% | [unknown] | 0xffffffffaa71b24e |
| 0.00% | python | property_descr_get |
| 0.00% | [unknown] | 0xffffffffaa267d50 |
| 0.00% | python | compactlong_float_guard |
| 0.00% | [unknown] | 0xffffffffaa5d8c32 |
| 0.00% | [unknown] | 0xffffffffaa5d6738 |
| 0.00% | [unknown] | 0xffffffffaa5d7cbc |
| 0.00% | [unknown] | 0xffffffffaa62f9dd |
| 0.00% | [unknown] | 0xffffffffab60122a |
| 0.00% | python | slot_nb_subtract |
| 0.00% | python | slot_tp_iter |
| 0.00% | [unknown] | 0xffffffffaa6ca7c3 |
| 0.00% | python | iter_iternext |
| 0.00% | [unknown] | 0xffffffff929df75e |
| 0.00% | [unknown] | 0xffffffffaa62f942 |
| 0.00% | [unknown] | 0xffffffffaab39b08 |
| 0.00% | python | strchr@plt |
| 0.00% | [unknown] | 0xffffffffaa3a5c27 |
| 0.00% | [unknown] | 0xffffffffaa5d8d2f |
| 0.00% | [unknown] | 0xffffffff936e9148 |
| 0.00% | python | getset_set |
| 0.00% | python | richcmp_eq |
| 0.00% | [unknown] | 0xffffffffaa3a56b5 |
| 0.00% | python | _pystat_fromstructstat |
| 0.00% | [unknown] | 0xffffffff929a4ca7 |
| 0.00% | python | _Py_call_instrumentation_arg |
| 0.00% | [unknown] | 0xffffffffaa5d8dc9 |
| 0.00% | python | setitem_take2_lock_held |
| 0.00% | [unknown] | 0xffffffffaa65d944 |
| 0.00% | [unknown] | 0xffffffff92c54aac |
| 0.00% | python | va_build_value |
| 0.00% | python | wrapper_call |
| 0.00% | python | _PyJit_translate_single_bytecode_to_trace |
| 0.00% | [unknown] | 0xffffffffaa5d6d1b |
| 0.00% | [unknown] | 0xffffffffab45065a |
| 0.00% | _object*) | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType, |
| 0.00% | python | slot_nb_multiply |
| 0.00% | [unknown] | 0xffffffffab44a153 |
| 0.00% | [unknown] | 0xffffffffab6000a0 |
| 0.00% | python | chain_next |
| 0.00% | [unknown] | 0xffffffff92c54d84 |
| 0.00% | python | call_soon |
| 0.00% | python | PyCallable_Check |
| 0.00% | python | _Py_bytes_lower |
| 0.00% | python | _asyncio_Future___init__ |
| 0.00% | [unknown] | 0xffffffffab6001cd |
| 0.00% | [unknown] | 0xffffffff936f3c9e |
| 0.00% | [unknown] | 0xffffffffaa3f8125 |
| 0.00% | [unknown] | 0xffffffffaa62e9cc |
| 0.00% | python | hashtable_unicode_hash |
| 0.00% | [unknown] | 0xffffffffab450662 |
| 0.00% | [unknown] | 0xffffffffab45065e |
| 0.00% | python | _Py_uop_analyze_and_optimize |
| 0.00% | python | __errno_location@plt |
| 0.00% | python | slot_tp_call |
| 0.00% | python | write_str |
| 0.00% | python | copy_values |
| 0.00% | python | write_bytes_lock_held |
| 0.00% | [unknown] | 0xffffffffab601633 |
| 0.00% | python | PyBytesWriter_FinishWithSize |
| 0.00% | python | vgetargskeywords.constprop.0 |
| 0.00% | [unknown] | 0xffffffff93c01618 |
| 0.00% | python | pthread_mutex_unlock@plt |
| 0.00% | python | analyze_descriptor_load.constprop.0 |
| 0.00% | [unknown] | 0xffffffffaa2d6a89 |
| 0.00% | [unknown] | 0xffffffff93c0125b |
| 0.00% | [unknown] | 0xffffffff92ce5d79 |
| 0.00% | python | _Py_Specialize_Call |
| 0.00% | [unknown] | 0xffffffffaa62fa7f |
| 0.00% | [unknown] | 0xffffffffaa6ca7af |
| 0.00% | [unknown] | 0xffffffff92c25c73 |
| 0.00% | python | cm_descr_get |
| 0.00% | python | hashtable_unicode_compare |
| 0.00% | [unknown] | 0xffffffffaa6ca7bc |
| 0.00% | [unknown] | 0xffffffffaa26ca45 |
| 0.00% | [unknown] | 0xffffffffaa5ff2e2 |
| 0.00% | python | task_step |
| 0.00% | [unknown] | 0xffffffffab601700 |
| 0.00% | python | gen_close |
| 0.00% | python | pthread_mutex_lock@plt |
| 0.00% | python | _PyFunction_FromConstructor |
| 0.00% | [unknown] | 0xffffffffab450656 |
| 0.00% | python | do_raise |
| 0.00% | [unknown] | 0xffffffffaa3a6537 |
| 0.00% | python | FutureIter_iternext |
| 0.00% | [unknown] | 0xffffffffaa627cc3 |
| 0.00% | [unknown] | 0xffffffffaa5d7cc2 |
| 0.00% | python | subtype_dict |
| 0.00% | [unknown] | 0xffffffffaa696de5 |
| 0.00% | [unknown] | 0xffffffffaa5d6d29 |
| 0.00% | [unknown] | 0xffffffffab6011ab |
| 0.00% | [unknown] | 0xffffffffaa6cdbb9 |
| 0.00% | [unknown] | 0xffffffff939cb1a6 |
| 0.00% | [unknown] | 0xffffffffab3ae196 |
| 0.00% | python | wrap_descr_get |
| 0.00% | [unknown] | 0xffffffffaa65d964 |
| 0.00% | python | defdict_missing |
| 0.00% | [unknown] | 0xffffffffaa3e1105 |
| 0.00% | python | partial_vectorcall |
| 0.00% | [unknown] | 0xffffffff936f5163 |

### library

8.10% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.61% | python | sre_ucs1_match |
| 0.40% | python | sre_ucs1_charset.isra.0 |
| 0.40% | binascii.cpython-315-x86_64-linux-gnu.so | binascii_a2b_ascii85 |
| 0.39% | binascii.cpython-315-x86_64-linux-gnu.so | binascii_a2b_base85 |
| 0.30% | binascii.cpython-315-x86_64-linux-gnu.so | binascii_a2b_base64 |
| 0.29% | _pickle.cpython-315-x86_64-linux-gnu.so | save.constprop.0 |
| 0.25% | binascii.cpython-315-x86_64-linux-gnu.so | binascii_b2a_base64 |
| 0.19% | binascii.cpython-315-x86_64-linux-gnu.so | binascii_b2a_ascii85 |
| 0.16% | binascii.cpython-315-x86_64-linux-gnu.so | binascii_b2a_base85 |
| 0.12% | _pickle.cpython-315-x86_64-linux-gnu.so | save_dict |
| 0.12% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write |
| 0.12% | binascii.cpython-315-x86_64-linux-gnu.so | binascii_a2b_hex |
| 0.12% | python | sre_search |
| 0.11% | array.cpython-315-x86_64-linux-gnu.so | array_subscr |
| 0.11% | _pickle.cpython-315-x86_64-linux-gnu.so | save_long |
| 0.11% | _json.cpython-315-x86_64-linux-gnu.so | scanstring_unicode |
| 0.10% | _pickle.cpython-315-x86_64-linux-gnu.so | load |
| 0.10% | python | sre_ucs1_count |
| 0.08% | _pickle.cpython-315-x86_64-linux-gnu.so | save_list |
| 0.07% | _pickle.cpython-315-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.07% | libz.so.1.3 | 0x0000000000008c1c |
| 0.06% | python | _sre_SRE_Pattern_prefixmatch |
| 0.06% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write.constprop.0 |
| 0.05% | _json.cpython-315-x86_64-linux-gnu.so | scan_once_unicode |
| 0.05% | pyexpat.cpython-315-x86_64-linux-gnu.so | normal_contentTok |
| 0.05% | libz.so.1.3 | 0x0000000000008c20 |
| 0.05% | libz.so.1.3 | 0x0000000000002dba |
| 0.05% | pyexpat.cpython-315-x86_64-linux-gnu.so | normal_updatePosition |
| 0.05% | libz.so.1.3 | 0x0000000000002da3 |
| 0.05% | libz.so.1.3 | 0x0000000000002db1 |
| 0.05% | libz.so.1.3 | 0x0000000000002db6 |
| 0.05% | libz.so.1.3 | 0x0000000000002dc6 |
| 0.05% | libz.so.1.3 | 0x0000000000008bf7 |
| 0.05% | libz.so.1.3 | 0x0000000000002dae |
| 0.04% | array.cpython-315-x86_64-linux-gnu.so | array_ass_subscr |
| 0.04% | tracer.cpython-315-x86_64-linux-gnu.so | CTracer_trace |
| 0.03% | array.cpython-315-x86_64-linux-gnu.so | d_setitem |
| 0.03% | _heapq.cpython-315-x86_64-linux-gnu.so | siftup |
| 0.03% | _math_integer.cpython-315-x86_64-linux-gnu.so | factorial_partial_product |
| 0.03% | libz.so.1.3 | 0x0000000000008c25 |
| 0.03% | libz.so.1.3 | 0x0000000000008be6 |
| 0.03% | libsqlite3.so.0.8.6 | sqlite3VdbeExec |
| 0.03% | python | sre_ucs4_match |
| 0.03% | libz.so.1.3 | 0x0000000000008192 |
| 0.03% | python | pattern_subx |
| 0.03% | _pickle.cpython-315-x86_64-linux-gnu.so | Pickler_clear |
| 0.03% | libz.so.1.3 | 0x00000000000082aa |
| 0.03% | pyexpat.cpython-315-x86_64-linux-gnu.so | accountingDiffTolerated.part.0 |
| 0.03% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_put |
| 0.03% | libz.so.1.3 | 0x0000000000008c2c |
| 0.03% | libz.so.1.3 | 0x0000000000008bd6 |
| 0.03% | libz.so.1.3 | 0x0000000000008bed |
| 0.03% | pyexpat.cpython-315-x86_64-linux-gnu.so | sip24_update.isra.0 |
| 0.03% | array.cpython-315-x86_64-linux-gnu.so | d_getitem |
| 0.03% | pyexpat.cpython-315-x86_64-linux-gnu.so | doContent |
| 0.02% | libz.so.1.3 | 0x0000000000008c07 |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | save_unicode |
| 0.02% | libz.so.1.3 | 0x00000000000082b7 |
| 0.02% | libm.so.6 | __ieee754_pow_fma |
| 0.02% | libz.so.1.3 | 0x000000000000819f |
| 0.02% | _json.cpython-315-x86_64-linux-gnu.so | ascii_escape_size |
| 0.02% | libz.so.1.3 | 0x0000000000008c18 |
| 0.02% | libm.so.6 | __cos_fma |
| 0.02% | pyexpat.cpython-315-x86_64-linux-gnu.so | normal_nameLength |
| 0.02% | libz.so.1.3 | 0x0000000000008c2f |
| 0.02% | libz.so.1.3 | 0x0000000000008bf1 |
| 0.02% | libz.so.1.3 | 0x0000000000008c0a |
| 0.02% | libz.so.1.3 | 0x0000000000008bdf |
| 0.02% | libz.so.1.3 | 0x0000000000008bfa |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | load_counted_binunicode |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | Pdata_push |
| 0.02% | pyexpat.cpython-315-x86_64-linux-gnu.so | lookup.constprop.0 |
| 0.02% | _json.cpython-315-x86_64-linux-gnu.so | encoder_listencode_obj |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | do_append |
| 0.02% | python | _sre_SRE_Pattern_search |
| 0.01% | libz.so.1.3 | 0x0000000000008c01 |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoPut |
| 0.01% | libz.so.1.3 | 0x0000000000008bd0 |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | elementiter_next |
| 0.01% | python | sre_ucs2_match |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | expat_end_handler |
| 0.01% | pyexpat.cpython-315-x86_64-linux-gnu.so | normal_getAtts |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | treebuilder_handle_start |
| 0.01% | libz.so.1.3 | 0x0000000000008c2a |
| 0.01% | libz.so.1.3 | 0x0000000000008c14 |
| 0.01% | libz.so.1.3 | 0x0000000000008c0e |
| 0.01% | libz.so.1.3 | 0x0000000000008140 |
| 0.01% | libz.so.1.3 | 0x000000000000829a |
| 0.01% | libz.so.1.3 | 0x0000000000008279 |
| 0.01% | libz.so.1.3 | 0x0000000000008258 |
| 0.01% | libz.so.1.3 | 0x0000000000008267 |
| 0.01% | libz.so.1.3 | 0x0000000000008161 |
| 0.01% | pyexpat.cpython-315-x86_64-linux-gnu.so | sip24_final |
| 0.01% | libz.so.1.3 | 0x000000000000828a |
| 0.01% | libz.so.1.3 | 0x0000000000008182 |
| 0.01% | libz.so.1.3 | 0x0000000000008172 |
| 0.01% | libz.so.1.3 | 0x000000000000814f |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_get |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | do_setitems |
| 0.01% | libm.so.6 | __sin_fma |
| 0.01% | array.cpython-315-x86_64-linux-gnu.so | PyType_GetModuleByDef@plt |
| 0.01% | _json.cpython-315-x86_64-linux-gnu.so | write_escaped_ascii |
| 0.01% | _sqlite3.cpython-315-x86_64-linux-gnu.so | _pysqlite_query_execute |
| 0.01% | array.cpython-315-x86_64-linux-gnu.so | PyNumber_AsSsize_t@plt |
| 0.01% | array.cpython-315-x86_64-linux-gnu.so | PyIndex_Check@plt |
| 0.01% | _json.cpython-315-x86_64-linux-gnu.so | encoder_encode_key_value |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | element_dealloc |
| 0.01% | pyexpat.cpython-315-x86_64-linux-gnu.so | storeAtts |
| 0.01% | _heapq.cpython-315-x86_64-linux-gnu.so | siftdown |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | Unpickler_clear |
| 0.01% | binascii.cpython-315-x86_64-linux-gnu.so | ascii_buffer_converter |
| 0.01% | libz.so.1.3 | 0x0000000000002416 |
| 0.01% | libz.so.1.3 | 0x0000000000002419 |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | makeuniversal |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_AsLongAndOverflow@plt |
| 0.01% | libz.so.1.3 | 0x000000000000242e |
| 0.01% | libz.so.1.3 | inflate |
| 0.01% | ld-linux-x86-64.so.2 | _dl_relocate_object |
| 0.01% | libz.so.1.3 | 0x00000000000082ae |
| 0.01% | libz.so.1.3 | 0x00000000000023f4 |
| 0.01% | libz.so.1.3 | 0x0000000000008196 |
| 0.01% | array.cpython-315-x86_64-linux-gnu.so | PyFloat_FromDouble@plt |
| 0.01% | _random.cpython-315-x86_64-linux-gnu.so | genrand_uint32 |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | element_getitem |
| 0.01% | libz.so.1.3 | 0x0000000000008be3 |
| 0.01% | _math_integer.cpython-315-x86_64-linux-gnu.so | math_integer_factorial |
| 0.01% | libz.so.1.3 | 0x0000000000008c37 |
| 0.01% | libssl.so.3 | 0x0000000000055398 |
| 0.01% | _math_integer.cpython-315-x86_64-linux-gnu.so | math_integer_gcd |
| 0.01% | libz.so.1.3 | 0x0000000000008c28 |
| 0.01% | math.cpython-315-x86_64-linux-gnu.so | math_sqrt |
| 0.01% | libz.so.1.3 | 0x0000000000008bfe |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | expat_start_handler |
| 0.01% | _sqlite3.cpython-315-x86_64-linux-gnu.so | _pysqlite_fetch_one_row.constprop.0 |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | PyDict_Next@plt |
| 0.01% | _elementtree.cpython-315-x86_64-linux-gnu.so | element_gc_traverse |
| 0.00% | libz.so.1.3 | 0x0000000000002403 |
| 0.00% | _elementtree.cpython-315-x86_64-linux-gnu.so | create_new_element.isra.0 |
| 0.00% | python | sre_ucs4_count |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | marker |
| 0.00% | pyexpat.cpython-315-x86_64-linux-gnu.so | utf8_toUtf8 |
| 0.00% | libz.so.1.3 | 0x000000000000825c |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3BtreeInsert |
| 0.00% | libz.so.1.3 | 0x0000000000008165 |
| 0.00% | libz.so.1.3 | 0x000000000000828e |
| 0.00% | libz.so.1.3 | 0x00000000000082bb |
| 0.00% | libz.so.1.3 | 0x0000000000008186 |
| 0.00% | libz.so.1.3 | 0x00000000000081a3 |
| 0.00% | libz.so.1.3 | 0x000000000000826c |
| 0.00% | libz.so.1.3 | 0x0000000000008144 |
| 0.00% | libz.so.1.3 | 0x000000000000827d |
| 0.00% | _random.cpython-315-x86_64-linux-gnu.so | _random_Random_getrandbits |
| 0.00% | libz.so.1.3 | 0x0000000000008176 |
| 0.00% | libz.so.1.3 | 0x000000000000829e |
| 0.00% | libz.so.1.3 | 0x0000000000008154 |
| 0.00% | _elementtree.cpython-315-x86_64-linux-gnu.so | expat_data_handler |
| 0.00% | _elementtree.cpython-315-x86_64-linux-gnu.so | element_resize |
| 0.00% | array.cpython-315-x86_64-linux-gnu.so | i_getitem |
| 0.00% | _elementtree.cpython-315-x86_64-linux-gnu.so | treebuilder_extend_element_text_or_tail.isra.0 |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3_step |
| 0.00% | python | sys_trace_return |
| 0.00% | _ssl.cpython-315-x86_64-linux-gnu.so | _ssl__SSLSocket_read |
| 0.00% | unicodedata.cpython-315-x86_64-linux-gnu.so | unicodedata_UCD_combining |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3VdbeHalt |
| 0.00% | python | sys_trace_start |
| 0.00% | ld-linux-x86-64.so.2 | do_lookup_x |
| 0.00% | python | _sre_SRE_Pattern_sub |
| 0.00% | libz.so.1.3 | 0x00000000000023f0 |
| 0.00% | python | _sre_SRE_Match_end |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_FromLong@plt |
| 0.00% | _heapq.cpython-315-x86_64-linux-gnu.so | _heapq_heappop |
| 0.00% | tracer.cpython-315-x86_64-linux-gnu.so | CTracer_set_pdata_stack.constprop.0 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoGet |
| 0.00% | binascii.cpython-315-x86_64-linux-gnu.so | PyObject_GetBuffer@plt |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | save_reduce |
| 0.00% | _json.cpython-315-x86_64-linux-gnu.so | encoder_write_string |
| 0.00% | _heapq.cpython-315-x86_64-linux-gnu.so | _heapq_heappush |
| 0.00% | _math_integer.cpython-315-x86_64-linux-gnu.so | _Py_Dealloc@plt |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_New |
| 0.00% | _elementtree.cpython-315-x86_64-linux-gnu.so | subelement |
| 0.00% | binascii.cpython-315-x86_64-linux-gnu.so | PyBuffer_Release@plt |
| 0.00% | ld-linux-x86-64.so.2 | strcmp |
| 0.00% | _elementtree.cpython-315-x86_64-linux-gnu.so | element_text_getter |

### dynamic

6.59% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.75% | python | PyObject_RichCompareBool |
| 0.60% | python | _PyObject_GenericGetAttrWithDict |
| 0.36% | python | PyType_IsSubtype |
| 0.28% | python | _PyObject_GetAttrStackRef |
| 0.28% | python | _PyObject_MakeTpCall |
| 0.19% | python | PyObject_Hash |
| 0.18% | python | PyObject_GetItem |
| 0.17% | python | PyObject_Vectorcall |
| 0.16% | python | PyObject_GetOptionalAttr |
| 0.15% | python | _PyObject_GetMethodStackRef |
| 0.14% | python | _PyObject_TryGetInstanceAttribute |
| 0.14% | python | PyNumber_AsSsize_t |
| 0.12% | python | _PyType_GetDict |
| 0.12% | python | PyObject_IsTrue |
| 0.12% | python | PyObject_Malloc |
| 0.11% | python | _Py_type_getattro_impl |
| 0.11% | python | PyObject_IsInstance |
| 0.10% | python | type_call |
| 0.10% | python | PyObject_RichCompare |
| 0.10% | python | PyObject_CallOneArg |
| 0.09% | python | PyObject_Size |
| 0.09% | python | PyObject_SetItem |
| 0.09% | python | PyObject_GetIter |
| 0.09% | python | object_isinstance |
| 0.08% | python | getset_get |
| 0.08% | python | PyObject_Free |
| 0.07% | python | PyObject_ClearManagedDict |
| 0.07% | python | PyObject_SetAttr |
| 0.06% | python | PyObject_GenericSetAttr |
| 0.06% | python | PyObject_VisitManagedDict |
| 0.06% | python | PyType_GetModuleByDef |
| 0.06% | python | PyObject_IsSubclass |
| 0.05% | python | PyNumber_Add |
| 0.05% | python | PyObject_Call |
| 0.05% | python | PyObject_ClearWeakRefs |
| 0.05% | python | _PyObject_LookupSpecial |
| 0.05% | python | _PyObject_VectorcallPrepend |
| 0.05% | python | slot_tp_richcompare |
| 0.05% | python | do_super_lookup |
| 0.04% | python | _PyObject_RealIsSubclass |
| 0.04% | python | PySequence_Fast |
| 0.04% | python | PyObject_Str |
| 0.03% | python | PyDescr_IsData |
| 0.03% | python | PyIter_Next |
| 0.03% | python | PyObject_VectorcallMethod |
| 0.03% | python | PyObject_GetBuffer |
| 0.03% | python | PyObject_DelItem |
| 0.03% | python | delitem_common |
| 0.03% | python | method_get |
| 0.03% | python | PyObject_GetAttr |
| 0.03% | python | PyNumber_Lshift |
| 0.03% | python | _PyObject_VectorcallDictTstate |
| 0.03% | python | PySequence_Contains |
| 0.03% | python | PyObject_Repr |
| 0.03% | python | PyNumber_Remainder |
| 0.03% | python | PyNumber_Multiply |
| 0.03% | python | PyIter_Send |
| 0.03% | python | PyNumber_InPlaceAdd |
| 0.02% | python | _PySuper_Lookup |
| 0.02% | python | _PyObject_InitInlineValues |
| 0.02% | python | type_ready |
| 0.02% | python | PyNumber_FloorDivide |
| 0.02% | python | PyNumber_Rshift |
| 0.02% | python | object_get_class |
| 0.02% | python | _PyNumber_Index |
| 0.02% | python | object_richcompare |
| 0.02% | python | object_recursive_isinstance |
| 0.02% | python | PyNumber_Negative |
| 0.02% | python | _PyObject_Call_Prepend |
| 0.01% | python | object_init |
| 0.01% | python | PyNumber_Index |
| 0.01% | python | PyObject_GenericGetAttr |
| 0.01% | python | PyMapping_Check |
| 0.01% | python | PyObject_GenericHash |
| 0.01% | python | _PyObject_RealIsInstance |
| 0.01% | python | _PyObject_StoreInstanceAttribute |
| 0.01% | python | StopIteration_init |
| 0.01% | python | PyNumber_Subtract |
| 0.01% | python | PyMapping_GetOptionalItem |
| 0.01% | python | PyObject_LengthHint |
| 0.01% | python | PyNumber_TrueDivide |
| 0.01% | python | PySequence_Tuple |
| 0.01% | python | PyIter_Check |
| 0.01% | python | type_name |
| 0.01% | python | PyNumber_And |
| 0.01% | python | PyNumber_Long |
| 0.01% | python | PyNumber_Xor |
| 0.00% | python | _PyNumber_PowerNoMod |
| 0.00% | python | object___reduce_ex__ |
| 0.00% | python | PyObject_GenericGetDict |
| 0.00% | python | PySequence_GetItem |
| 0.00% | python | PyNumber_InPlaceTrueDivide |
| 0.00% | python | PyObject_SelfIter |
| 0.00% | python | PyObject_HasAttrWithError |
| 0.00% | python | _PyObject_SetAttributeErrorContext |
| 0.00% | python | PySequence_List |
| 0.00% | python | _PyObject_CallFunctionVa |
| 0.00% | python | _PyObject_LookupSpecialMethod |
| 0.00% | python | PyNumber_Check |
| 0.00% | python | object_vacall |
| 0.00% | python | PyObject_SetAttrString |
| 0.00% | python | type___instancecheck__ |
| 0.00% | python | PyObject_CallObject |

### gc

5.83% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.04% | python | visit_add_to_container |
| 1.02% | python | gc_collect_region |
| 0.74% | python | PyObject_GC_UnTrack |
| 0.64% | python | _PyGC_Collect |
| 0.57% | python | visit_decref |
| 0.55% | python | visit_reachable |
| 0.22% | python | dict_traverse |
| 0.20% | python | list_traverse |
| 0.16% | python | _PyObject_GC_New |
| 0.12% | python | PyObject_GC_Del |
| 0.11% | python | subtype_traverse |
| 0.11% | python | _PyObject_GC_NewVar |
| 0.05% | python | func_traverse |
| 0.03% | python | PyObject_IS_GC |
| 0.03% | python | tuple_traverse |
| 0.03% | python | _PyGC_VisitFrameStack |
| 0.02% | python | _PyTuple_MaybeUntrack |
| 0.02% | python | type_traverse |
| 0.02% | python | set_traverse |
| 0.02% | python | type_is_gc |
| 0.02% | python | PyObject_GC_Track |
| 0.02% | python | TaskObj_traverse |
| 0.02% | python | gen_traverse |
| 0.01% | python | _PyObject_GC_Link |
| 0.01% | python | meth_traverse |
| 0.01% | python | context_tp_traverse |
| 0.00% | python | method_traverse |
| 0.00% | python | FutureObj_traverse |
| 0.00% | python | _PyGC_VisitStackRef |
| 0.00% | python | TaskStepMethWrapper_traverse |
| 0.00% | python | gc_traverse |
| 0.00% | python | descr_traverse |

### lookup

5.23% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.99% | python | unicodekeys_lookup_unicode |
| 2.01% | python | _Py_dict_lookup |
| 0.06% | python | find_name_in_mro |
| 0.03% | python | builtin_getattr |
| 0.03% | python | _Py_type_getattro |
| 0.03% | python | _Py_dict_lookup_threadsafe_stackref |
| 0.03% | python | _Py_hashtable_get_entry_generic |
| 0.01% | python | PyMember_GetOne |
| 0.01% | python | update_one_slot |
| 0.01% | python | PyMember_SetOne |
| 0.01% | python | member_get |
| 0.00% | python | _Py_hashtable_get |

### libc

4.84% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.78% | libc.so.6 | __memmove_avx_unaligned_erms |
| 0.53% | libc.so.6 | __memset_avx2_unaligned_erms |
| 0.32% | libc.so.6 | __memcmp_avx2_movbe |
| 0.18% | libc.so.6 | _int_malloc |
| 0.10% | libc.so.6 | malloc |
| 0.06% | libc.so.6 | __strlen_avx2 |
| 0.06% | libc.so.6 | _int_free_merge_chunk |
| 0.05% | libc.so.6 | _int_free |
| 0.04% | libc.so.6 | unlink_chunk.isra.0 |
| 0.04% | libc.so.6 | cfree@GLIBC_2.2.5 |
| 0.04% | libc.so.6 | pthread_mutex_lock@@GLIBC_2.2.5 |
| 0.03% | libcrypto.so.3 | 0x00000000002dcb4e |
| 0.03% | libc.so.6 | __strcmp_avx2 |
| 0.03% | libc.so.6 | pthread_mutex_unlock@@GLIBC_2.2.5 |
| 0.02% | libc.so.6 | __GI___pthread_self |
| 0.02% | libc.so.6 | __strchr_avx2 |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb90 |
| 0.02% | libc.so.6 | _int_free_maybe_consolidate |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb62 |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb8b |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb9a |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb9f |
| 0.02% | libcrypto.so.3 | 0x00000000002dcc92 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbae |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb95 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8cf |
| 0.01% | libcrypto.so.3 | 0x00000000002dcabc |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8da |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd13 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcac7 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc9e6 |
| 0.01% | libc.so.6 | pthread_cond_signal@@GLIBC_2.3.2 |
| 0.01% | libc.so.6 | __memchr_avx2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba4 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd01 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccd2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc6a |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba9 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccee |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc40 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc7e |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb44 |
| 0.01% | libc.so.6 | realloc |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc74 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc9d |
| 0.01% | libcrypto.so.3 | 0x00000000002dc899 |
| 0.01% | libc.so.6 | _int_realloc |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb5d |
| 0.01% | libcrypto.so.3 | 0x00000000002dccaf |
| 0.01% | libcrypto.so.3 | 0x00000000002dccc4 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc96a |
| 0.01% | libcrypto.so.3 | 0x00000000002dc861 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc51 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc994 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc979 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb6c |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbc7 |
| 0.01% | libcrypto.so.3 | 0x00000000002dca79 |
| 0.01% | libcrypto.so.3 | 0x00000000002dca12 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc9f0 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb18 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc9aa |
| 0.01% | libcrypto.so.3 | 0x00000000002dca4e |
| 0.01% | libcrypto.so.3 | 0x00000000002dc825 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc84c |
| 0.01% | libcrypto.so.3 | 0x00000000002dc888 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc92c |
| 0.01% | libcrypto.so.3 | 0x00000000002dca8c |
| 0.01% | libcrypto.so.3 | 0x00000000002dc83b |
| 0.01% | libcrypto.so.3 | 0x00000000002dc876 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccdb |
| 0.01% | libcrypto.so.3 | 0x00000000002dca59 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8c4 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc956 |
| 0.01% | libcrypto.so.3 | 0x00000000002dca25 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcab3 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcade |
| 0.01% | libcrypto.so.3 | 0x00000000002dca68 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc812 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd25 |
| 0.01% | libcrypto.so.3 | 0x00000000002dca9f |
| 0.01% | libcrypto.so.3 | 0x00000000002dc904 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc989 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8ef |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb2c |
| 0.01% | libcrypto.so.3 | 0x00000000002dc942 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb22 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8af |
| 0.01% | libcrypto.so.3 | 0x00000000002dcaf1 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc9be |
| 0.01% | libcrypto.so.3 | 0x00000000002dca39 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc9d2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dca01 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb05 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc917 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbb8 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb71 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb7b |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc60 |
| 0.01% | libcrypto.so.3 | OPENSSL_cleanse |
| 0.01% | libcrypto.so.3 | OSSL_PARAM_locate |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb49 |
| 0.01% | libcrypto.so.3 | BIO_ctrl |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbbd |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb58 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbb3 |
| 0.01% | libc.so.6 | __memrchr_avx2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb67 |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_ctrl |
| 0.01% | libc.so.6 | __errno_location |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_get_iv_length |
| 0.01% | libcrypto.so.3 | 0x00000000000c0ddb |
| 0.00% | libc.so.6 | clock_gettime@@GLIBC_2.17 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb53 |
| 0.00% | libc.so.6 | malloc_consolidate |
| 0.00% | libcrypto.so.3 | 0x00000000002dcd0a |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb27 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc9db |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb0f |
| 0.00% | libcrypto.so.3 | 0x00000000002dc8fa |
| 0.00% | libcrypto.so.3 | 0x00000000002dca53 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcae8 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc98e |
| 0.00% | libcrypto.so.3 | 0x00000000002dcad3 |
| 0.00% | libcrypto.so.3 | 0x00000000002dccf8 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc90e |
| 0.00% | libcrypto.so.3 | 0x00000000002dca30 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc974 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcafb |
| 0.00% | libcrypto.so.3 | 0x00000000002dc9fc |
| 0.00% | libcrypto.so.3 | 0x00000000002dca44 |
| 0.00% | libcrypto.so.3 | 0x00000000000c0dc4 |
| 0.00% | libcrypto.so.3 | 0x00000000002dca07 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcd1c |
| 0.00% | libcrypto.so.3 | 0x00000000002dc95f |
| 0.00% | libcrypto.so.3 | 0x00000000002dc9c8 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc922 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc937 |
| 0.00% | libc.so.6 | __GI___readdir64 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb1c |
| 0.00% | libcrypto.so.3 | 0x00000000002dca63 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc9a0 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcaa9 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc97f |
| 0.00% | libcrypto.so.3 | 0x00000000002dca1c |
| 0.00% | libcrypto.so.3 | 0x00000000002dc86b |
| 0.00% | libcrypto.so.3 | 0x00000000002dc857 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc891 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc841 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc800 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc8a4 |
| 0.00% | libcrypto.so.3 | 0x00000000002dca6e |
| 0.00% | libcrypto.so.3 | 0x00000000002dc8b8 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc94b |
| 0.00% | libcrypto.so.3 | 0x00000000002dca95 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc830 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc9b4 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc87e |
| 0.00% | libcrypto.so.3 | 0x00000000002dcce4 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc81b |
| 0.00% | libcrypto.so.3 | 0x00000000002dca83 |
| 0.00% | libc.so.6 | __printf_buffer |
| 0.00% | libc.so.6 | __gconv_transform_utf8_internal |
| 0.00% | libcrypto.so.3 | 0x00000000002dc8e5 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb36 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcc65 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb85 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcca6 |

### dict

3.39% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.78% | python | PyDict_GetItemRef |
| 0.52% | python | dictiter_iternextkey |
| 0.33% | python | insertdict |
| 0.17% | python | dictkeys_decref.part.0.constprop.0 |
| 0.17% | python | build_indices_unicode |
| 0.16% | python | PyDict_Next |
| 0.16% | python | dict_subscript |
| 0.10% | python | insert_to_emptydict |
| 0.10% | python | find_empty_slot.constprop.0 |
| 0.10% | python | dict_get |
| 0.07% | python | new_dict |
| 0.07% | python | dictiter_iternextitem |
| 0.07% | python | PyDict_Contains |
| 0.06% | python | dict_ass_sub |
| 0.06% | python | _PyDict_FromItems |
| 0.05% | python | _PyDict_LoadBuiltinsFromGlobals |
| 0.05% | python | dict_setdefault_ref_lock_held |
| 0.04% | python | _PyDict_Next |
| 0.04% | python | _PyDict_SetItem_Take2 |
| 0.03% | python | dict_merge |
| 0.03% | python | dictresize |
| 0.03% | python | PyDict_SetItem |
| 0.02% | python | insertdict.isra.0 |
| 0.02% | python | new_keys_object |
| 0.02% | python | dictiter_iternextvalue |
| 0.02% | python | dict_items |
| 0.01% | python | PyDict_GetItem |
| 0.01% | python | _PyDict_MergeEx |
| 0.01% | python | _PyDict_DelItem_KnownHash_LockHeld |
| 0.01% | python | PyDict_GetItemWithError |
| 0.01% | python | dict_iter |
| 0.01% | python | _PyDict_GetItemRef_KnownHash_LockHeld |
| 0.01% | python | dict_pop |
| 0.01% | python | _PyDict_LoadGlobalStackRef |
| 0.01% | python | _PyDict_GetMethodStackRef |
| 0.01% | python | dict_vectorcall |
| 0.00% | python | dict_update |
| 0.00% | python | insert_to_emptydict.isra.0 |
| 0.00% | python | dict_length |

### int

2.61% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.79% | python | k_mul |
| 0.18% | python | x_divrem |
| 0.17% | python | long_to_decimal_string_internal |
| 0.16% | python | PyLong_FromLong |
| 0.15% | python | PyLong_FromSsize_t |
| 0.09% | python | PyLong_AsSsize_t |
| 0.08% | python | _PyLong_GCD |
| 0.08% | python | x_add |
| 0.08% | python | long_richcompare |
| 0.07% | python | long_hash |
| 0.07% | python | PyLong_AsLongAndOverflow |
| 0.06% | python | PyLong_AsNativeBytes.constprop.0 |
| 0.06% | python | long_lshift1 |
| 0.05% | python | long_lshift_method |
| 0.04% | python | _PyLong_FromMedium |
| 0.04% | python | long_div |
| 0.04% | python | long_bitwise |
| 0.04% | python | long_rshift1 |
| 0.03% | python | PyLong_FromString |
| 0.03% | python | x_sub |
| 0.03% | python | long_rshift |
| 0.03% | python | PyLong_FromVoidPtr |
| 0.03% | python | PyLong_AsLong |
| 0.02% | python | l_mod |
| 0.02% | python | _PyLong_FromByteArray.part.0 |
| 0.02% | python | PyLong_FromUnsignedLong |
| 0.02% | python | _PyLong_AsByteArray |
| 0.02% | python | long_mul |
| 0.02% | python | long_neg_method |
| 0.01% | python | _PyLong_Frexp |
| 0.01% | python | long_to_decimal_string |
| 0.01% | python | long_add |
| 0.01% | python | long_mul_method |
| 0.01% | python | PyLong_FromLongLong |
| 0.01% | python | PyLong_FromUnsignedLongLong |
| 0.01% | python | long_add_method |
| 0.01% | python | _PyLong_Size_t_Converter |
| 0.01% | python | PyLong_AsDouble |
| 0.00% | python | PyLong_AsInt |
| 0.00% | python | long_mod |
| 0.00% | python | long_xor |
| 0.00% | python | long_float |
| 0.00% | python | long_vectorcall |

### str

2.50% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.20% | python | bytes_translate_impl |
| 0.19% | python | _PyUnicode_JoinArray.part.0 |
| 0.19% | python | _PyUnicode_Equal |
| 0.16% | python | siphash13 |
| 0.16% | python | PyUnicode_Format |
| 0.11% | python | _PyUnicode_ResizeCompact |
| 0.11% | python | PyUnicode_RichCompare |
| 0.10% | python | _copy_characters.constprop.0.isra.0 |
| 0.08% | python | replace |
| 0.07% | python | find_first_nonascii |
| 0.05% | python | PyBytes_FromStringAndSize |
| 0.05% | python | bytes_richcompare |
| 0.04% | python | unicode_from_format |
| 0.04% | python | unicode_decode_utf8.part.0 |
| 0.04% | python | PyUnicode_Contains |
| 0.04% | python | PyUnicode_Substring |
| 0.04% | python | _PyUnicodeWriter_PrepareInternal |
| 0.04% | python | _PyUnicodeWriter_WriteStr |
| 0.04% | python | _PyUnicode_FromUCS4.part.0 |
| 0.03% | python | unicode_repr |
| 0.03% | python | split |
| 0.03% | python | _PyUnicodeWriter_WriteSubstring |
| 0.03% | python | bytes_concat |
| 0.03% | python | PyUnicode_Concat |
| 0.03% | python | bytes_subscript |
| 0.03% | python | _PyUnicode_InternMortal |
| 0.03% | python | unicode_replace |
| 0.02% | python | PyUnicodeWriter_WriteChar |
| 0.02% | python | _PyUnicode_BinarySlice |
| 0.02% | python | _PyUnicodeWriter_Finish |
| 0.02% | python | unicode_hash |
| 0.02% | python | stringlib_bytes_join |
| 0.02% | python | PyUnicode_AsUTF8AndSize |
| 0.02% | python | unicode_decode_utf8_impl |
| 0.02% | python | _PyUnicode_TranslateCharmap |
| 0.01% | python | unicode_join |
| 0.01% | python | PyBytes_FromStringAndSize.constprop.0 |
| 0.01% | python | bytes_buffer_getbuffer |
| 0.01% | python | _PyUnicode_FromUCS1.part.0 |
| 0.01% | python | _PyUnicode_IsAlpha |
| 0.01% | python | intern_constants |
| 0.01% | python | bytes_hash |
| 0.01% | python | unicode_startswith |
| 0.01% | python | _PyUnicodeWriter_WriteASCIIString |
| 0.01% | python | unicode_fromformat_write_utf8 |
| 0.01% | python | PyUnicodeWriter_WriteStr |
| 0.01% | python | bytes_iter |
| 0.01% | python | _PyUnicode_FindMaxChar |
| 0.01% | python | _PyUnicodeWriter_Init |
| 0.01% | python | PyUnicode_InternFromString |
| 0.01% | python | _PyUnicode_InternImmortal |
| 0.01% | python | PyUnicode_Splitlines |
| 0.01% | python | unicode_lower |
| 0.01% | python | stringlib__two_way |
| 0.01% | python | _PyUnicode_IsDecimalDigit |
| 0.01% | python | PyBytes_FromObject |
| 0.01% | python | _PyUnicode_FastCopyCharacters |
| 0.01% | python | PyUnicode_Decode |
| 0.01% | python | unicode_expandtabs |
| 0.00% | python | unicode_rfind |
| 0.00% | python | _PyUnicode_Result |
| 0.00% | python | PyUnicode_AsEncodedString |
| 0.00% | python | _PyUnicode_DecodeUTF8Writer |
| 0.00% | python | unicode_strip |
| 0.00% | python | PyUnicode_AsUCS4 |
| 0.00% | python | unicode_split |
| 0.00% | python | PyUnicode_DecodeUTF8 |
| 0.00% | python | PyUnicode_Append |
| 0.00% | python | PyUnicode_FindChar |
| 0.00% | python | PyUnicode_FromWideChar |
| 0.00% | python | _PyUnicode_XStrip |
| 0.00% | python | unicode_encode |
| 0.00% | python | unicode_fromformat_write_str |
| 0.00% | python | _PyUnicode_ToLowercase |
| 0.00% | python | bytes_translate |
| 0.00% | python | _PyUnicode_IsDigit |
| 0.00% | python | bytes_length |
| 0.00% | python | unicode_count_impl |
| 0.00% | python | unicode_mod |
| 0.00% | python | ascii_decode |
| 0.00% | python | PyUnicode_FromFormatV |
| 0.00% | python | unicode_find |

### miscobj

2.46% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.03% | python | set_lookkey |
| 0.39% | python | PySlice_AdjustIndices |
| 0.16% | python | _PySet_Contains |
| 0.08% | python | gen_iternext |
| 0.08% | python | PySlice_Unpack |
| 0.07% | python | make_gen |
| 0.06% | python | PyBuffer_Release |
| 0.06% | python | set_add_entry_takeref |
| 0.05% | python | PyBuffer_FillInfo |
| 0.05% | python | setiter_iternext |
| 0.03% | python | range_iter |
| 0.03% | python | set_issubset_impl |
| 0.03% | python | PyBool_FromLong |
| 0.03% | python | enum_next |
| 0.03% | python | deque_append |
| 0.02% | python | _PyBuildSlice_ConsumeRefs |
| 0.02% | python | set_table_resize |
| 0.02% | python | set_merge_lock_held |
| 0.02% | python | deque_popleft |
| 0.01% | python | _PyGen_FetchStopIterationValue |
| 0.01% | python | dequeiter_next |
| 0.01% | python | PyGen_am_send |
| 0.01% | python | range_vectorcall |
| 0.01% | python | set_difference |
| 0.01% | python | deque_clear.part.0 |
| 0.01% | python | bytearray_resize_lock_held |
| 0.01% | python | bytearray_iconcat |
| 0.01% | python | _PySlice_GetLongIndices |
| 0.01% | python | range_subscript |
| 0.01% | python | set_add |
| 0.00% | python | _PySet_NextEntryRef |
| 0.00% | python | PySet_Add |
| 0.00% | python | set_iter |
| 0.00% | python | deque_iter |
| 0.00% | python | bytearray_ass_subscript_lock_held |
| 0.00% | python | weakref_hash |
| 0.00% | python | set_intersection |
| 0.00% | python | set_vectorcall |
| 0.00% | python | weakref_richcompare |
| 0.00% | python | weakref___init__ |
| 0.00% | python | set_discard |

### list

2.02% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.34% | python | listiter_next |
| 0.31% | python | list_remove |
| 0.23% | python | list_slice_lock_held |
| 0.18% | python | list_ass_slice_lock_held |
| 0.15% | python | list_iter |
| 0.09% | python | list_sort_impl |
| 0.08% | python | _PyList_AppendTakeRefListResize |
| 0.07% | python | list_slice_wrap |
| 0.06% | python | _list_extend |
| 0.06% | python | list_extend_lock_held |
| 0.06% | python | _PyList_BinarySlice |
| 0.05% | python | list_append |
| 0.04% | python | _PyList_SliceSubscript |
| 0.04% | python | list_ass_subscript |
| 0.04% | python | _PyList_FromStackRefStealOnSuccess |
| 0.04% | python | list_concat |
| 0.03% | python | list_subscript |
| 0.02% | python | PyList_Append |
| 0.02% | python | list_contains |
| 0.01% | python | list_length |
| 0.01% | python | list_insert |
| 0.01% | python | list_resize |
| 0.01% | python | list_pop |
| 0.01% | python | _PyList_GetItemRef |
| 0.01% | python | list_sort |
| 0.01% | python | list_vectorcall |
| 0.01% | python | list_index |
| 0.01% | python | _PyList_Extend |
| 0.00% | python | list_to_tuple |
| 0.00% | python | list_richcompare |
| 0.00% | python | PyList_Size |
| 0.00% | python | PyList_SetItem |

### tuple

1.29% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.30% | python | tuple_richcompare |
| 0.30% | python | PyTuple_FromArray |
| 0.29% | python | _PyTuple_FromStackRefStealOnSuccess |
| 0.15% | python | tuple_hash |
| 0.13% | python | PyTuple_GetSlice |
| 0.03% | python | PyTuple_Pack |
| 0.02% | python | tuple_subscript |
| 0.02% | python | tupleiter_next |
| 0.01% | python | tuple_iter |
| 0.01% | python | _PyTuple_BinarySlice |
| 0.01% | python | tuplegetter_descr_get |
| 0.01% | python | tuple_concat |
| 0.01% | python | tuple_length |
| 0.01% | python | tuple_contains |
| 0.00% | python | PyTuple_Size |

### calls

0.64% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.15% | python | _PyArg_UnpackKeywords |
| 0.08% | python | _PyFunction_Vectorcall |
| 0.07% | python | PyArg_UnpackTuple |
| 0.07% | python | vgetargs1_impl.constprop.0 |
| 0.06% | python | _Py_CheckFunctionResult |
| 0.03% | python | cfunction_vectorcall_FASTCALL_KEYWORDS |
| 0.02% | python | PyArg_Parse |
| 0.02% | python | method_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.02% | python | vgetargs1_impl |
| 0.02% | python | cfunction_vectorcall_NOARGS |
| 0.01% | python | cfunction_vectorcall_O |
| 0.01% | python | method_vectorcall |
| 0.01% | python | method_vectorcall_VARARGS |
| 0.01% | python | method_vectorcall_O |
| 0.01% | python | PyArg_ParseTupleAndKeywords |
| 0.01% | python | method_vectorcall_FASTCALL |
| 0.01% | python | vectorcall_method |
| 0.00% | python | method_vectorcall_VARARGS_KEYWORDS |
| 0.00% | python | cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.00% | python | method_vectorcall_NOARGS |
| 0.00% | python | _PyArg_UnpackStack |
| 0.00% | python | method_vectorcall_FASTCALL_KEYWORDS |
| 0.00% | python | cfunction_vectorcall_FASTCALL |
| 0.00% | python | PyArg_ParseTuple |

### threading

0.45% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.24% | python | _PyThreadState_PopFrame |
| 0.13% | python | _PyThreadState_PushFrame |
| 0.06% | python | PyThread_get_thread_ident |
| 0.01% | python | _PyThreadState_Attach |
| 0.01% | python | _PyThreadState_Detach |
| 0.00% | python | _PyThreadState_MustExit |
| 0.00% | python | _PyThreadState_GetCurrent |

### exceptions

0.44% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.13% | python | PyErr_CheckSignals |
| 0.08% | python | _PyErr_CheckSignalsTstate |
| 0.03% | python | _PyErr_SetObject.part.0 |
| 0.03% | python | PyErr_ExceptionMatches |
| 0.03% | python | PyErr_Occurred |
| 0.03% | python | PyCode_Addr2Line |
| 0.01% | python | _PyErr_ExceptionMatches |
| 0.01% | python | PyErr_SetRaisedException |
| 0.01% | python | PyErr_GetRaisedException |
| 0.01% | python | PyErr_GivenExceptionMatches |
| 0.01% | python | PyTraceBack_Here |
| 0.01% | python | BaseException_vectorcall |
| 0.01% | python | _PyErr_Restore |
| 0.01% | python | PyErr_Format |
| 0.00% | python | AttributeError_init |
| 0.00% | python | PyFrame_GetCode |
| 0.00% | python | PyException_GetTraceback |
| 0.00% | python | _PyErr_CreateException |
| 0.00% | python | BaseException_clear |
| 0.00% | python | _PyErr_SetKeyError |

### float

0.35% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.26% | python | PyFloat_FromDouble |
| 0.02% | python | float_richcompare |
| 0.02% | python | PyFloat_AsDouble |
| 0.02% | python | float_compactlong_true_div |
| 0.01% | python | float_pow |
| 0.01% | python | float_add |
| 0.01% | python | float_div |
| 0.00% | python | float_compactlong_guard |

### gil

0.07% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.05% | python | take_gil |
| 0.02% | python | drop_gil |

### async

0.05% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.03% | python | async_gen_asend_iternext |
| 0.02% | python | async_gen_anext |

### import

0.05% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.03% | python | r_object |
| 0.01% | python | PyImport_ImportModuleLevelObject |
| 0.00% | python | r_long |

### compiler

0.01% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.00% | python | optimize_uops.isra.0 |
| 0.00% | python | tok_get_normal_mode |
