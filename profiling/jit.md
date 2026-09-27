
## 2to3

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.80% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.96% | `[JIT]` | `jit` | jit |
| 3.96% | `python` | `gc_collect_main` | gc |
| 2.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.50% | `python` | `_PyObject_Malloc` | memory |
| 1.94% | `python` | `visit_decref` | gc |
| 1.86% | `python` | `sre_ucs1_match` | library |
| 1.73% | `python` | `_Py_dict_lookup` | lookup |
| 1.55% | `python` | `_PyObject_Free` | memory |
| 1.53% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.35% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.25% | `python` | `_Py_Dealloc` | memory |
| 1.21% | `python` | `visit_reachable` | gc |
| 1.11% | `python` | `tuple_dealloc` | memory |
| 0.78% | `python` | `r_object` | import |
| 0.76% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.66% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.65% | `python` | `tuple_alloc` | memory |
| 0.61% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.60% | `python` | `initialize_locals` | interpreter |
| 0.59% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.58% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.58% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.57% | `python` | `dict_traverse` | gc |
| 0.56% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.55% | `python` | `find_name_in_mro` | lookup |
| 0.53% | `python` | `_PyCode_Quicken` | interpreter |
| 0.46% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.43% | `python` | `siphash13` | str |
| 0.41% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.41% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.40% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.38% | `python` | `type_ready` | dynamic |
| 0.37% | `python` | `insertdict` | dict |
| 0.37% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.35% | `libc.so.6` | `_int_malloc` | libc |
| 0.35% | `python` | `PyDict_GetItemRef` | dict |
| 0.34% | `python` | `PyObject_SetAttr` | dynamic |
| 0.34% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.32% | `python` | `gen_dealloc` | memory |
| 0.30% | `python` | `update_one_slot` | lookup |
| 0.29% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.29% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.29% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.28% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.28% | `python` | `new_dict.constprop.0` | dict |
| 0.28% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.28% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.28% | `python` | `_PyEval_Vector` | interpreter |
| 0.27% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.26% | `python` | `list_subscript` | list |
| 0.26% | `python` | `dict_dealloc` | memory |
| 0.26% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.26% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.25% | `python` | `intern_constants` | str |
| 0.25% | `python` | `subtype_traverse` | gc |

## argparse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.12% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.54% | `[JIT]` | `jit` | jit |
| 2.65% | `python` | `_PyObject_Malloc` | memory |
| 2.24% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.13% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.66% | `python` | `_PyObject_Free` | memory |
| 1.63% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.63% | `python` | `_Py_dict_lookup` | lookup |
| 1.40% | `python` | `initialize_locals` | interpreter |
| 1.34% | `python` | `_Py_Dealloc` | memory |
| 0.89% | `python` | `gc_collect_main` | gc |
| 0.88% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.72% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.69% | `python` | `tuple_dealloc` | memory |
| 0.69% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.68% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.64% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.59% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.51% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.50% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.48% | `python` | `list_dealloc` | memory |
| 0.47% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.46% | `python` | `tuple_alloc` | memory |
| 0.46% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.43% | `python` | `PyDict_GetItemRef` | dict |
| 0.42% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 0.41% | `python` | `dict_dealloc` | memory |
| 0.38% | `python` | `PyList_New.constprop.0` | memory |
| 0.38% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.38% | `python` | `insertdict` | dict |
| 0.38% | `python` | `PyUnicode_Contains` | str |
| 0.38% | `python` | `PyType_IsSubtype` | dynamic |
| 0.37% | `python` | `PyUnicode_Format` | str |
| 0.37% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.37% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.37% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.37% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.36% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.35% | `libc.so.6` | `__gconv_transform_utf8_internal` | libc |
| 0.35% | `python` | `_PyJIT_Entry` | compiler |
| 0.34% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.33% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.33% | `python` | `_PyObject_Realloc` | memory |
| 0.32% | `python` | `visit_decref` | gc |
| 0.32% | `python` | `replace` | str |
| 0.31% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.31% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.30% | `python` | `new_dict.constprop.0` | dict |
| 0.30% | `libc.so.6` | `malloc` | libc |
| 0.30% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.29% | `python` | `PyUnicode_New.part.0` | memory |
| 0.29% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.27% | `python` | `frame_dealloc` | memory |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `PyUnicode_FromWideChar` | str |
| 0.26% | `python` | `_PyObject_GC_New` | gc |
| 0.26% | `libc.so.6` | `__dcigettext` | libc |
| 0.26% | `libc.so.6` | `_int_malloc` | libc |
| 0.25% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.25% | `python` | `sre_ucs1_match` | library |
| 0.25% | `python` | `siphash13` | str |

## argparse_subparsers

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.16% | `[JIT]` | `jit` | jit |
| 10.32% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.28% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.20% | `python` | `_PyObject_Malloc` | memory |
| 2.75% | `python` | `_PyObject_Free` | memory |
| 2.42% | `python` | `_Py_dict_lookup` | lookup |
| 2.33% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.20% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.02% | `python` | `gc_collect_main` | gc |
| 1.84% | `python` | `initialize_locals` | interpreter |
| 1.47% | `python` | `_Py_Dealloc` | memory |
| 1.10% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.95% | `python` | `visit_decref` | gc |
| 0.93% | `python` | `long_to_decimal_string_internal` | int |
| 0.92% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.86% | `libc.so.6` | `_int_malloc` | libc |
| 0.84% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.68% | `python` | `insertdict` | dict |
| 0.64% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.64% | `python` | `tuple_dealloc` | memory |
| 0.60% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.58% | `python` | `_PyDict_Subscript` | dict |
| 0.57% | `python` | `sre_ucs1_match` | library |
| 0.55% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.55% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.54% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.54% | `python` | `tuple_alloc` | memory |
| 0.53% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.53% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.51% | `python` | `PyUnicode_Format` | str |
| 0.51% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.50% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.50% | `python` | `pattern_new_match` | memory |
| 0.48% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.47% | `python` | `_PyJIT_Entry` | compiler |
| 0.47% | `python` | `PyUnicode_Contains` | str |
| 0.46% | `python` | `PyType_IsSubtype` | dynamic |
| 0.46% | `python` | `_Py_BuildString_StackRefSteal` | unknown |
| 0.45% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.43% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `PySequence_Contains` | dynamic |
| 0.40% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.39% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.39% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.36% | `python` | `PyObject_Str` | dynamic |
| 0.36% | `python` | `insert_to_emptydict` | dict |
| 0.36% | `python` | `set_add_entry_takeref` | miscobj |
| 0.35% | `python` | `subtype_traverse` | gc |
| 0.34% | `python` | `_Py_NewReference` | memory |
| 0.34% | `python` | `dict_get` | dict |
| 0.34% | `python` | `visit_reachable` | gc |
| 0.34% | `python` | `_PyEval_Vector` | interpreter |
| 0.33% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.33% | `python` | `clone_combined_dict_keys` | unknown |
| 0.31% | `libc.so.6` | `malloc` | libc |
| 0.31% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.30% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.30% | `python` | `_PyUnicode_XStrip` | str |
| 0.29% | `python` | `PyDict_Next` | dict |
| 0.29% | `python` | `PyList_New.constprop.0` | memory |
| 0.29% | `python` | `siphash13` | str |
| 0.28% | `python` | `PyUnicode_New` | memory |
| 0.28% | `python` | `PyObject_Hash` | dynamic |
| 0.28% | `python` | `PyUnicode_New.part.0` | memory |
| 0.28% | `python` | `PyObject_GetItem` | dynamic |
| 0.28% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.28% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.27% | `python` | `replace` | str |
| 0.27% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.27% | `python` | `PyDict_Contains` | dict |
| 0.26% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.26% | `python` | `find_name_in_mro` | lookup |

## async_generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.40% | `[JIT]` | `jit` | jit |
| 5.48% | `python` | `_Py_Dealloc` | memory |
| 3.78% | `python` | `_PyAsyncGenASend_Send` | unknown |
| 3.75% | `python` | `_PyObject_Free` | memory |
| 3.58% | `python` | `_PyObject_Malloc` | memory |
| 2.51% | `python` | `_PyType_AllocNoTrack` | memory |
| 2.26% | `python` | `async_gen_anext` | async |
| 2.16% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.98% | `python` | `gc_collect_main` | gc |
| 1.92% | `python` | `PyType_GenericAlloc` | memory |
| 1.90% | `python` | `PyErr_ExceptionMatches` | exceptions |
| 1.80% | `python` | `async_gen_asend_dealloc` | memory |
| 1.71% | `python` | `tuple_dealloc` | memory |
| 1.70% | `python` | `_PyAsyncGenValueWrapperNew` | memory |
| 1.65% | `python` | `_PyGen_FetchStopIterationValue` | miscobj |
| 1.65% | `python` | `StopIteration_dealloc` | memory |
| 1.60% | `python` | `PyObject_CallOneArg` | dynamic |
| 1.50% | `python` | `async_gen_wrapped_val_dealloc` | memory |
| 1.36% | `python` | `type_call` | dynamic |
| 1.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.22% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 1.20% | `python` | `tuple_alloc` | memory |
| 1.19% | `python` | `_Py_NewReference` | memory |
| 1.12% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.09% | `python` | `StopIteration_init` | dynamic |
| 0.96% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.90% | `python` | `_PyJIT_Entry` | compiler |
| 0.86% | `python` | `BaseException_new` | memory |
| 0.81% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.75% | `python` | `PyObject_GC_Del` | gc |
| 0.75% | `python` | `initialize_locals` | interpreter |
| 0.65% | `python` | `visit_decref` | gc |
| 0.64% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.64% | `python` | `make_range_object` | unknown |
| 0.62% | `python` | `_PyObject_GC_Link` | gc |
| 0.61% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.61% | `python` | `visit_reachable` | gc |
| 0.55% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.55% | `python` | `PyErr_SetRaisedException` | exceptions |
| 0.51% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.49% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.48% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.47% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.46% | `python` | `_PyLong_FromMedium` | int |
| 0.44% | `python` | `subtype_traverse` | gc |
| 0.44% | `python` | `_PyEval_GetANext` | interpreter |
| 0.44% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.42% | `python` | `range_subscript` | miscobj |
| 0.42% | `python` | `_PyEval_Vector` | interpreter |
| 0.41% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.40% | `python` | `PyNumber_Add` | dynamic |
| 0.39% | `python` | `long_richcompare` | int |
| 0.38% | `python` | `PyType_IsSubtype` | dynamic |
| 0.34% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.33% | `python` | `PySlice_New` | memory |
| 0.31% | `python` | `PyErr_GetRaisedException` | exceptions |
| 0.29% | `python` | `set_add_entry_takeref` | miscobj |
| 0.28% | `python` | `gen_dealloc` | memory |
| 0.27% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.26% | `python` | `long_add` | int |
| 0.25% | `python` | `weakref___new__` | memory |
| 0.25% | `python` | `PyObject_ClearManagedDict` | dynamic |

## async_tree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.11% | `python` | `gc_collect_main` | gc |
| 13.99% | `[JIT]` | `jit` | jit |
| 5.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.60% | `python` | `visit_reachable` | gc |
| 4.99% | `python` | `visit_decref` | gc |
| 3.13% | `python` | `_PyObject_Malloc` | memory |
| 1.88% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.86% | `python` | `_PyObject_Free` | memory |
| 1.71% | `python` | `initialize_locals` | interpreter |
| 1.44% | `python` | `_Py_Dealloc` | memory |
| 1.40% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.22% | `python` | `subtype_traverse` | gc |
| 1.16% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.11% | `python` | `context_tp_dealloc` | memory |
| 0.92% | `python` | `_PyEval_Vector` | interpreter |
| 0.90% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.89% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.76% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.62% | `python` | `TaskObj_traverse` | gc |
| 0.55% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.54% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.54% | `python` | `clear_slots` | unknown |
| 0.51% | `python` | `tuple_dealloc` | memory |
| 0.49% | `python` | `PyUnicode_RichCompare` | str |
| 0.49% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.48% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.45% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.44% | `python` | `_PyObject_Calloc` | memory |
| 0.44% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.43% | `python` | `_PyMember_GetOffset` | unknown |
| 0.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.42% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.41% | `python` | `_PyObject_GC_New` | gc |
| 0.40% | `python` | `_Py_dict_lookup` | lookup |
| 0.40% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.40% | `python` | `TaskObj_clear` | unknown |
| 0.40% | `python` | `_PyObject_Realloc` | memory |
| 0.39% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.39% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.38% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.38% | `python` | `tuple_alloc` | memory |
| 0.37% | `python` | `gen_dealloc` | memory |
| 0.36% | `python` | `PyCMethod_New` | memory |
| 0.34% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.34% | `python` | `PyIter_Send` | dynamic |
| 0.33% | `python` | `_PyJIT_Entry` | compiler |
| 0.32% | `python` | `_PyLong_FromMedium` | int |
| 0.32% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.31% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.31% | `python` | `insert_to_emptydict` | dict |
| 0.31% | `python` | `PyObject_Call` | dynamic |
| 0.30% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.30% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.29% | `python` | `subtype_dealloc` | memory |
| 0.28% | `python` | `PyObject_GC_Del` | gc |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `context_run` | unknown |
| 0.27% | `python` | `context_tp_traverse` | gc |
| 0.27% | `python` | `_Py_NewReference` | memory |
| 0.25% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |

## async_tree_cpu_io_mixed

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.60% | `python` | `k_mul` | int |
| 9.57% | `python` | `gc_collect_main` | gc |
| 8.63% | `[JIT]` | `jit` | jit |
| 4.67% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.82% | `python` | `visit_reachable` | gc |
| 3.77% | `python` | `_PyObject_Malloc` | memory |
| 3.42% | `python` | `visit_decref` | gc |
| 2.92% | `python` | `_PyObject_Free` | memory |
| 2.40% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.43% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.42% | `python` | `_Py_Dealloc` | memory |
| 1.37% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.21% | `_math_integer.cpython-316-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.10% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.99% | `python` | `PyThread_get_thread_ident` | threading |
| 0.98% | `python` | `initialize_locals` | interpreter |
| 0.89% | `python` | `subtype_traverse` | gc |
| 0.81% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.75% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.74% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.72% | `python` | `_Py_IsMainThread` | unknown |
| 0.64% | `python` | `_PyEval_Vector` | interpreter |
| 0.60% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.57% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.57% | `python` | `PyNumber_Multiply` | dynamic |
| 0.57% | `python` | `context_tp_dealloc` | memory |
| 0.51% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.43% | `python` | `long_alloc` | memory |
| 0.41% | `python` | `long_mul` | int |
| 0.37% | `python` | `long_lshift1` | int |
| 0.34% | `python` | `TaskObj_traverse` | gc |
| 0.31% | `python` | `_PyMember_GetOffset` | unknown |
| 0.31% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.31% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.29% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.29% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.27% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.26% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.26% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.26% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.25% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.25% | `python` | `clear_slots` | unknown |
| 0.25% | `python` | `_Py_dict_lookup` | lookup |

## async_tree_cpu_io_mixed_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.90% | `python` | `k_mul` | int |
| 8.80% | `python` | `gc_collect_main` | gc |
| 7.81% | `[JIT]` | `jit` | jit |
| 4.44% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.92% | `python` | `_PyObject_Malloc` | memory |
| 3.65% | `python` | `visit_reachable` | gc |
| 3.39% | `python` | `visit_decref` | gc |
| 2.97% | `python` | `_PyObject_Free` | memory |
| 2.56% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.50% | `python` | `_Py_Dealloc` | memory |
| 1.50% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.48% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.30% | `_math_integer.cpython-316-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.14% | `python` | `PyThread_get_thread_ident` | threading |
| 1.01% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.88% | `python` | `subtype_traverse` | gc |
| 0.87% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.80% | `python` | `initialize_locals` | interpreter |
| 0.79% | `python` | `_Py_IsMainThread` | unknown |
| 0.68% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.68% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.66% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.58% | `python` | `PyNumber_Multiply` | dynamic |
| 0.57% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.55% | `python` | `_PyEval_Vector` | interpreter |
| 0.51% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.49% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.45% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.44% | `python` | `long_alloc` | memory |
| 0.43% | `python` | `long_mul` | int |
| 0.43% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.43% | `python` | `TaskObj_traverse` | gc |
| 0.37% | `python` | `long_lshift1` | int |
| 0.35% | `python` | `_Py_NewReference` | memory |
| 0.32% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.32% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.32% | `python` | `_PyMember_GetOffset` | unknown |
| 0.31% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.31% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.31% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.30% | `python` | `set_traverse` | gc |
| 0.27% | `python` | `clear_slots` | unknown |
| 0.27% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.27% | `python` | `PyUnicode_RichCompare` | str |
| 0.26% | `python` | `_PyInterpreterState_Main` | unknown |
| 0.26% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.26% | `python` | `gen_dealloc` | memory |
| 0.26% | `python` | `gen_traverse` | gc |

## async_tree_io

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.04% | `python` | `gc_collect_main` | gc |
| 11.12% | `[JIT]` | `jit` | jit |
| 7.98% | `python` | `visit_reachable` | gc |
| 7.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.59% | `python` | `visit_decref` | gc |
| 2.08% | `python` | `_PyObject_Malloc` | memory |
| 1.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.52% | `python` | `subtype_traverse` | gc |
| 1.48% | `python` | `initialize_locals` | interpreter |
| 1.19% | `python` | `_PyEval_Vector` | interpreter |
| 1.18% | `python` | `_PyObject_Free` | memory |
| 1.17% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.09% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.08% | `python` | `_Py_Dealloc` | memory |
| 0.86% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.82% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.75% | `_heapq.cpython-316-x86_64-linux-gnu.so` | `siftup` | library |
| 0.72% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.66% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.57% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.51% | `python` | `_PyMember_GetOffset` | unknown |
| 0.50% | `python` | `slot_tp_richcompare` | dynamic |
| 0.47% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.46% | `python` | `gen_traverse` | gc |
| 0.45% | `python` | `_PyJIT_Entry` | compiler |
| 0.44% | `python` | `TaskObj_traverse` | gc |
| 0.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.39% | `python` | `PyObject_IS_GC` | gc |
| 0.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.37% | `python` | `clear_slots` | unknown |
| 0.36% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.35% | `python` | `_PyObject_Calloc` | memory |
| 0.35% | `python` | `context_tp_dealloc` | memory |
| 0.34% | `python` | `tuple_dealloc` | memory |
| 0.34% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.32% | `python` | `_PyObject_Realloc` | memory |
| 0.31% | `python` | `gen_dealloc` | memory |
| 0.31% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.30% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.29% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.28% | `python` | `PyIter_Send` | dynamic |
| 0.28% | `python` | `tuple_alloc` | memory |
| 0.28% | `python` | `tuple_traverse` | gc |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.27% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.27% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.27% | `python` | `context_tp_traverse` | gc |
| 0.26% | `python` | `_Py_dict_lookup` | lookup |

## async_tree_io_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.75% | `python` | `gc_collect_main` | gc |
| 10.73% | `[JIT]` | `jit` | jit |
| 8.20% | `python` | `visit_reachable` | gc |
| 7.44% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.76% | `python` | `visit_decref` | gc |
| 2.09% | `python` | `_PyObject_Malloc` | memory |
| 1.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `subtype_traverse` | gc |
| 1.36% | `python` | `_PyEval_Vector` | interpreter |
| 1.34% | `python` | `initialize_locals` | interpreter |
| 1.19% | `python` | `_PyObject_Free` | memory |
| 1.19% | `python` | `_Py_Dealloc` | memory |
| 1.11% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.11% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.10% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.85% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.82% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.76% | `_heapq.cpython-316-x86_64-linux-gnu.so` | `siftup` | library |
| 0.70% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.58% | `python` | `gen_traverse` | gc |
| 0.58% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.53% | `python` | `_PyMember_GetOffset` | unknown |
| 0.52% | `python` | `slot_tp_richcompare` | dynamic |
| 0.50% | `python` | `TaskObj_traverse` | gc |
| 0.46% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.44% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.43% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.42% | `python` | `clear_slots` | unknown |
| 0.42% | `python` | `_PyJIT_Entry` | compiler |
| 0.41% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.36% | `python` | `set_traverse` | gc |
| 0.35% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.35% | `python` | `gen_dealloc` | memory |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.35% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.35% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.35% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.32% | `python` | `tuple_dealloc` | memory |
| 0.31% | `python` | `_PyObject_Calloc` | memory |
| 0.30% | `python` | `PyObject_Call` | dynamic |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.27% | `python` | `_PyObject_Realloc` | memory |
| 0.26% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.26% | `python` | `tuple_alloc` | memory |
| 0.25% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.25% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |

## async_tree_memoization

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.36% | `python` | `gc_collect_main` | gc |
| 13.65% | `[JIT]` | `jit` | jit |
| 7.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.25% | `python` | `visit_reachable` | gc |
| 5.70% | `python` | `visit_decref` | gc |
| 2.82% | `python` | `_PyObject_Malloc` | memory |
| 1.83% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.67% | `python` | `initialize_locals` | interpreter |
| 1.56% | `python` | `_PyObject_Free` | memory |
| 1.55% | `python` | `subtype_traverse` | gc |
| 1.30% | `python` | `_Py_Dealloc` | memory |
| 1.27% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.23% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.20% | `python` | `_PyEval_Vector` | interpreter |
| 0.95% | `python` | `context_tp_dealloc` | memory |
| 0.95% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.84% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.53% | `python` | `_PyMember_GetOffset` | unknown |
| 0.52% | `python` | `TaskObj_traverse` | gc |
| 0.51% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.50% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.49% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.44% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.44% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.43% | `python` | `clear_slots` | unknown |
| 0.42% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.42% | `python` | `tuple_alloc` | memory |
| 0.42% | `python` | `PyIter_Send` | dynamic |
| 0.41% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.41% | `python` | `_PyJIT_Entry` | compiler |
| 0.41% | `python` | `tuple_dealloc` | memory |
| 0.40% | `python` | `PyUnicode_RichCompare` | str |
| 0.40% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.38% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.38% | `python` | `_Py_dict_lookup` | lookup |
| 0.35% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.35% | `python` | `_PyObject_Realloc` | memory |
| 0.34% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.34% | `python` | `_PyObject_GC_New` | gc |
| 0.34% | `python` | `TaskObj_clear` | unknown |
| 0.34% | `python` | `gen_dealloc` | memory |
| 0.33% | `python` | `_PyObject_Calloc` | memory |
| 0.33% | `python` | `context_run` | unknown |
| 0.32% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.31% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.30% | `python` | `list_traverse` | gc |
| 0.30% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.30% | `python` | `context_tp_traverse` | gc |
| 0.30% | `python` | `PyCMethod_New` | memory |
| 0.29% | `python` | `gen_traverse` | gc |
| 0.28% | `python` | `insert_to_emptydict` | dict |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.28% | `python` | `_PyLong_FromMedium` | int |
| 0.28% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.28% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.27% | `python` | `PyObject_GC_Del` | gc |
| 0.27% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `PyObject_IS_GC` | gc |
| 0.26% | `python` | `list_extend_lock_held` | list |
| 0.26% | `python` | `_asyncio_future_discard_from_awaited_by` | unknown |
| 0.26% | `python` | `tuple_traverse` | gc |
| 0.25% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.25% | `python` | `subtype_dealloc` | memory |

## async_tree_memoization_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.48% | `python` | `gc_collect_main` | gc |
| 13.26% | `[JIT]` | `jit` | jit |
| 6.87% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.85% | `python` | `visit_reachable` | gc |
| 6.12% | `python` | `visit_decref` | gc |
| 2.71% | `python` | `_PyObject_Malloc` | memory |
| 1.77% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.62% | `python` | `subtype_traverse` | gc |
| 1.49% | `python` | `_PyObject_Free` | memory |
| 1.45% | `python` | `_Py_Dealloc` | memory |
| 1.27% | `python` | `initialize_locals` | interpreter |
| 1.12% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.06% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.02% | `python` | `_PyEval_Vector` | interpreter |
| 0.91% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.81% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.79% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.78% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.68% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.62% | `python` | `TaskObj_traverse` | gc |
| 0.58% | `python` | `_PyMember_GetOffset` | unknown |
| 0.55% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.51% | `python` | `set_traverse` | gc |
| 0.48% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.47% | `python` | `gen_traverse` | gc |
| 0.46% | `python` | `PyUnicode_RichCompare` | str |
| 0.45% | `python` | `clear_slots` | unknown |
| 0.44% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.44% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.44% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.41% | `python` | `_PyJIT_Entry` | compiler |
| 0.40% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.40% | `python` | `gen_dealloc` | memory |
| 0.38% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.37% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.36% | `python` | `PyObject_Call` | dynamic |
| 0.35% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.34% | `python` | `tuple_dealloc` | memory |
| 0.33% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.33% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `PyIter_Send` | dynamic |
| 0.31% | `python` | `_PyObject_Calloc` | memory |
| 0.30% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.30% | `python` | `context_tp_dealloc` | memory |
| 0.29% | `python` | `context_tp_traverse` | gc |
| 0.29% | `python` | `tuple_alloc` | memory |
| 0.29% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.28% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.28% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.28% | `python` | `PyObject_GC_Del` | gc |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.26% | `python` | `set_lookkey` | miscobj |
| 0.26% | `python` | `PyCMethod_New` | memory |
| 0.26% | `python` | `TaskObj_clear` | unknown |
| 0.25% | `python` | `dict_dealloc` | memory |

## async_tree_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.44% | `python` | `gc_collect_main` | gc |
| 14.04% | `[JIT]` | `jit` | jit |
| 6.00% | `python` | `visit_reachable` | gc |
| 5.37% | `python` | `visit_decref` | gc |
| 5.03% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.25% | `python` | `_PyObject_Malloc` | memory |
| 1.94% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.74% | `python` | `_PyObject_Free` | memory |
| 1.65% | `python` | `_Py_Dealloc` | memory |
| 1.46% | `python` | `initialize_locals` | interpreter |
| 1.22% | `python` | `subtype_traverse` | gc |
| 1.21% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.18% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.10% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.99% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.86% | `python` | `_PyEval_Vector` | interpreter |
| 0.82% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.77% | `python` | `TaskObj_traverse` | gc |
| 0.76% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.76% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.64% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.61% | `python` | `clear_slots` | unknown |
| 0.60% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.58% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.57% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.56% | `python` | `set_traverse` | gc |
| 0.55% | `python` | `PyUnicode_RichCompare` | str |
| 0.51% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.49% | `python` | `_PyMember_GetOffset` | unknown |
| 0.49% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.45% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.45% | `python` | `gen_traverse` | gc |
| 0.44% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.44% | `python` | `PyObject_Call` | dynamic |
| 0.44% | `python` | `_PyObject_Calloc` | memory |
| 0.43% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.42% | `python` | `gen_dealloc` | memory |
| 0.39% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.38% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.36% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.36% | `python` | `_PyObject_GC_New` | gc |
| 0.35% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.35% | `python` | `PyObject_GC_Del` | gc |
| 0.32% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.31% | `python` | `_PyJIT_Entry` | compiler |
| 0.31% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.31% | `python` | `PyDict_New` | memory |
| 0.31% | `python` | `dict_dealloc` | memory |
| 0.31% | `python` | `PyCMethod_New` | memory |
| 0.30% | `python` | `PyIter_Send` | dynamic |
| 0.30% | `python` | `tuple_alloc` | memory |
| 0.29% | `python` | `_Py_NewReference` | memory |
| 0.29% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.29% | `python` | `context_tp_traverse` | gc |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.28% | `python` | `allocate_from_new_pool` | memory |
| 0.28% | `python` | `_PyObject_VectorcallPrepend` | dynamic |
| 0.27% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `_PyObject_GC_Link` | gc |
| 0.26% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.25% | `python` | `insert_to_emptydict` | dict |
| 0.25% | `python` | `context_tp_dealloc` | memory |
| 0.25% | `python` | `_PyLong_FromMedium` | int |

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
| 5.18% | `libz.so.1.3` | `0x0000000000008c1c` | library |
| 3.78% | `libz.so.1.3` | `0x0000000000008c20` | library |
| 3.58% | `libz.so.1.3` | `0x0000000000002dda` | library |
| 3.55% | `libz.so.1.3` | `0x0000000000002dd1` | library |
| 3.52% | `libz.so.1.3` | `0x0000000000002dce` | library |
| 3.49% | `libz.so.1.3` | `0x0000000000002dc3` | library |
| 3.47% | `libz.so.1.3` | `0x0000000000002dd6` | library |
| 3.47% | `libz.so.1.3` | `0x0000000000002de6` | library |
| 3.47% | `libz.so.1.3` | `0x0000000000008bf7` | library |
| 2.35% | `libz.so.1.3` | `0x0000000000008be6` | library |
| 2.31% | `libz.so.1.3` | `0x0000000000008c25` | library |
| 2.31% | `libz.so.1.3` | `0x0000000000008192` | library |
| 2.19% | `libz.so.1.3` | `0x00000000000082aa` | library |
| 2.00% | `libz.so.1.3` | `0x0000000000008bed` | library |
| 1.97% | `libz.so.1.3` | `0x0000000000008bd6` | library |
| 1.95% | `libz.so.1.3` | `0x0000000000008c2c` | library |
| 1.92% | `libz.so.1.3` | `0x0000000000008c07` | library |
| 1.77% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.77% | `libz.so.1.3` | `0x00000000000082b7` | library |
| 1.69% | `libz.so.1.3` | `0x000000000000819f` | library |
| 1.69% | `libz.so.1.3` | `0x0000000000008c18` | library |
| 1.46% | `libz.so.1.3` | `0x0000000000008c2f` | library |
| 1.45% | `libz.so.1.3` | `0x0000000000008bf1` | library |
| 1.45% | `libz.so.1.3` | `0x0000000000008c0a` | library |
| 1.45% | `libz.so.1.3` | `0x0000000000008bfa` | library |
| 1.35% | `libz.so.1.3` | `0x0000000000008bdf` | library |
| 1.33% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.14% | `libz.so.1.3` | `0x0000000000008c01` | library |
| 1.01% | `libz.so.1.3` | `0x0000000000008c2a` | library |
| 0.98% | `libz.so.1.3` | `0x0000000000008bd0` | library |
| 0.97% | `libz.so.1.3` | `0x0000000000008c0e` | library |
| 0.96% | `libz.so.1.3` | `0x0000000000008c14` | library |
| 0.94% | `libz.so.1.3` | `0x0000000000008172` | library |
| 0.93% | `libz.so.1.3` | `0x000000000000814f` | library |
| 0.92% | `libz.so.1.3` | `0x0000000000008182` | library |
| 0.89% | `libz.so.1.3` | `0x0000000000008279` | library |
| 0.89% | `libz.so.1.3` | `0x0000000000008140` | library |
| 0.88% | `libz.so.1.3` | `0x000000000000829a` | library |
| 0.88% | `libz.so.1.3` | `0x0000000000008267` | library |
| 0.87% | `libz.so.1.3` | `0x0000000000008258` | library |
| 0.87% | `libz.so.1.3` | `0x0000000000008161` | library |
| 0.87% | `libz.so.1.3` | `0x000000000000828a` | library |
| 0.64% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.56% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.52% | `libz.so.1.3` | `0x0000000000002419` | library |
| 0.52% | `libz.so.1.3` | `0x00000000000082ae` | library |
| 0.51% | `libz.so.1.3` | `0x0000000000002416` | library |
| 0.50% | `libz.so.1.3` | `0x000000000000242e` | library |
| 0.47% | `libz.so.1.3` | `0x00000000000023f4` | library |
| 0.46% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.46% | `libz.so.1.3` | `0x0000000000008196` | library |
| 0.42% | `libz.so.1.3` | `0x0000000000008bfe` | library |
| 0.40% | `libz.so.1.3` | `0x0000000000008c28` | library |
| 0.40% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.39% | `libz.so.1.3` | `0x0000000000002403` | library |
| 0.37% | `libz.so.1.3` | `0x0000000000008c37` | library |
| 0.35% | `libz.so.1.3` | `0x0000000000008be3` | library |
| 0.34% | `libz.so.1.3` | `0x0000000000008154` | library |
| 0.33% | `libz.so.1.3` | `0x000000000000825c` | library |
| 0.33% | `libz.so.1.3` | `0x000000000000828e` | library |
| 0.32% | `libz.so.1.3` | `0x0000000000008176` | library |
| 0.32% | `libz.so.1.3` | `0x000000000000829e` | library |
| 0.32% | `libz.so.1.3` | `0x000000000000827d` | library |
| 0.32% | `libz.so.1.3` | `0x0000000000008165` | library |
| 0.32% | `libz.so.1.3` | `0x00000000000082bb` | library |
| 0.31% | `libz.so.1.3` | `0x000000000000826c` | library |
| 0.31% | `libz.so.1.3` | `0x0000000000008186` | library |
| 0.31% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.30% | `libz.so.1.3` | `0x00000000000081a3` | library |
| 0.29% | `libz.so.1.3` | `0x0000000000008144` | library |

## base64

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 10.13% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_ascii85` | library |
| 9.99% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base85` | library |
| 8.38% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base64` | library |
| 7.13% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base32` | library |
| 6.24% | `[JIT]` | `jit` | jit |
| 5.74% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base32` | library |
| 5.60% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base64` | library |
| 4.75% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_hex_impl.isra.0` | library |
| 4.21% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_ascii85` | library |
| 3.18% | `python` | `_PyArg_UnpackKeywords` | calls |
| 3.06% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base85` | library |
| 2.03% | `python` | `initialize_locals` | interpreter |
| 1.96% | `python` | `_Py_bytes_upper` | unknown |
| 1.59% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.52% | `python` | `PyDict_GetItemRef` | dict |
| 1.41% | `python` | `_PyObject_Malloc` | memory |
| 1.36% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 1.32% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.25% | `python` | `_Py_dict_lookup` | lookup |
| 1.21% | `python` | `_PyObject_Free` | memory |
| 1.05% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.93% | `python` | `PyBytesWriter_Create` | unknown |
| 0.91% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.79% | `python` | `bytes_translate_impl` | str |
| 0.66% | `python` | `PyBytesWriter_FinishWithPointer` | unknown |
| 0.63% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.61% | `libc.so.6` | `__memchr_avx2` | libc |
| 0.61% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.60% | `python` | `PyBuffer_FillInfo` | miscobj |
| 0.55% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.54% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.54% | `python` | `PyBuffer_Release` | miscobj |
| 0.45% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.40% | `python` | `_Py_strhex_impl` | unknown |
| 0.38% | `python` | `PyObject_IsInstance` | dynamic |
| 0.37% | `python` | `_Py_Dealloc` | memory |
| 0.35% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.33% | `python` | `cfunction_vectorcall_FASTCALL_KEYWORDS` | calls |
| 0.32% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.29% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.28% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.25% | `python` | `PyNumber_AsSsize_t` | dynamic |

## bpe_tokeniser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.67% | `[JIT]` | `jit` | jit |
| 4.93% | `python` | `_Py_dict_lookup` | lookup |
| 3.96% | `python` | `tuple_dealloc` | memory |
| 3.70% | `python` | `_Py_Dealloc` | memory |
| 3.51% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.93% | `python` | `gc_collect_main` | gc |
| 2.86% | `python` | `_PyObject_Free` | memory |
| 2.78% | `python` | `list_dealloc` | memory |
| 2.41% | `python` | `tuple_alloc` | memory |
| 2.26% | `python` | `_PyObject_Malloc` | memory |
| 2.17% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 2.15% | `python` | `listiter_next` | list |
| 2.00% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.97% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.46% | `python` | `zip_next` | unknown |
| 1.39% | `python` | `visit_decref` | gc |
| 1.35% | `python` | `PyList_New.constprop.0` | memory |
| 1.33% | `python` | `visit_reachable` | gc |
| 1.32% | `python` | `list_traverse` | gc |
| 1.31% | `python` | `PyTuple_New` | memory |
| 1.31% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.27% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.24% | `python` | `list_slice_lock_held` | list |
| 1.20% | `python` | `tuple_richcompare` | tuple |
| 1.07% | `python` | `list_iter` | list |
| 1.04% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.98% | `python` | `tuple_hash` | tuple |
| 0.95% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.94% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.92% | `python` | `_PyCompactLong_Add` | unknown |
| 0.83% | `python` | `_Py_NewReference` | memory |
| 0.79% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.79% | `python` | `insertdict` | dict |
| 0.73% | `python` | `listiter_dealloc` | memory |
| 0.73% | `python` | `zip_new` | memory |
| 0.71% | `python` | `slot_mp_ass_subscript` | unknown |
| 0.64% | `python` | `PyObject_Hash` | dynamic |
| 0.61% | `python` | `_PyDict_Subscript` | dict |
| 0.58% | `python` | `PyLong_FromSsize_t` | int |
| 0.56% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.56% | `python` | `wrapperdescr_call` | unknown |
| 0.54% | `python` | `_PyList_BinarySlice` | list |
| 0.52% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.51% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.47% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.46% | `python` | `dictiter_iternextkey` | dict |
| 0.45% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.45% | `python` | `PyArg_UnpackTuple` | calls |
| 0.44% | `python` | `_PyEval_Vector` | interpreter |
| 0.44% | `python` | `bytes_richcompare` | str |
| 0.44% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.41% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.41% | `python` | `PyObject_RichCompare` | dynamic |
| 0.39% | `python` | `wrap_objobjargproc` | unknown |
| 0.39% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.39% | `python` | `initialize_locals` | interpreter |
| 0.38% | `python` | `PyObject_GC_Del` | gc |
| 0.37% | `python` | `PySlice_Unpack` | miscobj |
| 0.36% | `python` | `_PyObject_GC_New` | gc |
| 0.36% | `python` | `PyType_GenericAlloc` | memory |
| 0.35% | `python` | `_PyObject_Realloc` | memory |
| 0.35% | `python` | `zip_dealloc` | memory |
| 0.35% | `python` | `_PyJIT_Entry` | compiler |
| 0.34% | `python` | `PyObject_GetIter` | dynamic |
| 0.32% | `python` | `list_slice_wrap` | list |
| 0.32% | `python` | `PyObject_Size` | dynamic |
| 0.31% | `python` | `_PyList_SliceSubscript` | list |
| 0.31% | `python` | `type_call` | dynamic |
| 0.29% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.29% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.28% | `python` | `PyObject_GetItem` | dynamic |
| 0.25% | `python` | `PyObject_SetItem` | dynamic |

## chameleon

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 16.64% | `[JIT]` | `jit` | jit |
| 3.75% | `python` | `_PyObject_Malloc` | memory |
| 3.34% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.94% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 2.41% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.05% | `python` | `_Py_dict_lookup` | lookup |
| 1.90% | `python` | `_PyObject_Free` | memory |
| 1.84% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.73% | `python` | `long_to_decimal_string_internal` | int |
| 1.47% | `python` | `sre_search` | library |
| 1.42% | `python` | `PyUnicode_Format` | str |
| 1.35% | `python` | `list_append` | list |
| 1.25% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.19% | `python` | `dict_get` | dict |
| 1.07% | `python` | `_sre_SRE_Pattern_search` | library |
| 1.01% | `python` | `insertdict` | dict |
| 0.95% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.88% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.87% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.83% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.83% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.82% | `python` | `method_vectorcall_FASTCALL` | calls |
| 0.81% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.74% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.73% | `python` | `PyDict_GetItemRef` | dict |
| 0.71% | `python` | `_PyJIT_Entry` | compiler |
| 0.67% | `python` | `PyUnicode_New` | memory |
| 0.57% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.54% | `python` | `listiter_next` | list |
| 0.50% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.50% | `python` | `_PyObject_Realloc` | memory |
| 0.50% | `python` | `PyType_IsSubtype` | dynamic |
| 0.50% | `python` | `_PySuper_Lookup` | dynamic |
| 0.49% | `python` | `PyNumber_Remainder` | dynamic |
| 0.48% | `python` | `_Py_Dealloc` | memory |
| 0.46% | `python` | `delitem_common` | dynamic |
| 0.46% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.44% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.44% | `python` | `PyObject_DelItem` | dynamic |
| 0.43% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.42% | `python` | `PyUnicode_New.part.0` | memory |
| 0.41% | `python` | `PyObject_Str` | dynamic |
| 0.41% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `supercheck` | unknown |
| 0.40% | `python` | `cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD` | calls |
| 0.37% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.37% | `python` | `_PyUnicodeWriter_WriteSubstring` | str |
| 0.33% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.32% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.32% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.31% | `python` | `PyThread_get_thread_ident` | threading |
| 0.26% | `python` | `_PyDict_Next` | dict |

## chaos

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.05% | `[JIT]` | `jit` | jit |
| 9.17% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.09% | `python` | `_PyCompactLong_Subtract` | unknown |
| 2.52% | `python` | `_Py_Dealloc` | memory |
| 2.50% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.26% | `python` | `PyFloat_FromDouble` | float |
| 1.96% | `python` | `make_range_object` | unknown |
| 1.91% | `python` | `_PyCompactLong_Add` | unknown |
| 1.55% | `python` | `range_iter` | miscobj |
| 1.37% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.36% | `python` | `initialize_locals` | interpreter |
| 1.33% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 1.29% | `python` | `float_pow` | float |
| 1.19% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.12% | `python` | `_PyObject_Free` | memory |
| 1.12% | `python` | `float_richcompare` | float |
| 1.08% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 1.03% | `python` | `float_dealloc` | memory |
| 1.03% | `python` | `_Py_NewReference` | memory |
| 1.02% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.98% | `python` | `_PyObject_Malloc` | memory |
| 0.94% | `python` | `subtype_dealloc` | memory |
| 0.93% | `python` | `float_compactlong_true_div` | float |
| 0.91% | `python` | `PyLong_FromLong` | int |
| 0.87% | `python` | `PyType_IsSubtype` | dynamic |
| 0.77% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.72% | `python` | `PyLong_AsLong` | int |
| 0.71% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.68% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.63% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.57% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.57% | `python` | `PyObject_RichCompare` | dynamic |
| 0.56% | `python` | `PyNumber_Index` | dynamic |
| 0.54% | `python` | `_PyJIT_Entry` | compiler |
| 0.48% | `python` | `range_vectorcall` | miscobj |
| 0.47% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.46% | `python` | `PyType_GenericAlloc` | memory |
| 0.44% | `python` | `PyLong_AsDouble` | int |
| 0.41% | `python` | `PyObject_IsTrue` | dynamic |
| 0.40% | `python` | `tuple_alloc` | memory |
| 0.37% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.36% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.35% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.33% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.32% | `python` | `tuple_dealloc` | memory |
| 0.32% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.30% | `python` | `PyObject_GC_Del` | gc |
| 0.26% | `python` | `float_compactlong_subtract` | float |
| 0.26% | `python` | `range_dealloc` | memory |
| 0.26% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.25% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |

## comprehensions

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.15% | `[JIT]` | `jit` | jit |
| 7.10% | `python` | `_Py_dict_lookup` | lookup |
| 3.62% | `python` | `_PyObject_Malloc` | memory |
| 3.40% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 3.13% | `python` | `dict_get` | dict |
| 2.59% | `python` | `_PyObject_Free` | memory |
| 2.27% | `python` | `_PyObject_Realloc` | memory |
| 2.22% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.67% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.56% | `python` | `insertdict` | dict |
| 1.50% | `python` | `long_richcompare` | int |
| 1.43% | `python` | `_PyDict_Subscript` | dict |
| 1.37% | `python` | `PyObject_Hash` | dynamic |
| 1.34% | `python` | `_Py_Dealloc` | memory |
| 1.24% | `python` | `long_hash` | int |
| 1.20% | `python` | `list_dealloc` | memory |
| 1.16% | `python` | `PyFunction_NewWithQualName` | memory |
| 1.12% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.10% | `python` | `unsafe_tuple_compare` | unknown |
| 1.10% | `python` | `PyObject_GetItem` | dynamic |
| 1.08% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.94% | `python` | `list_sort_impl` | list |
| 0.91% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.87% | `python` | `func_clear` | unknown |
| 0.84% | `python` | `gen_dealloc` | memory |
| 0.83% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.71% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.71% | `python` | `tuple_dealloc` | memory |
| 0.70% | `python` | `func_dealloc` | memory |
| 0.70% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.66% | `python` | `PyObject_RichCompare` | dynamic |
| 0.65% | `python` | `PyDict_GetItemRef` | dict |
| 0.53% | `python` | `tuple_alloc` | memory |
| 0.49% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.47% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.45% | `python` | `PyList_New.constprop.0` | memory |
| 0.43% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.43% | `python` | `gen_close` | unknown |
| 0.43% | `python` | `PyObject_GC_Del` | gc |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.41% | `python` | `tuple_subscript` | tuple |
| 0.40% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.40% | `python` | `_PyObject_GC_New` | gc |
| 0.36% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.34% | `python` | `find_empty_slot` | dict |
| 0.32% | `python` | `make_gen` | miscobj |
| 0.32% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `_Py_NewReference` | memory |
| 0.29% | `python` | `unsafe_object_compare` | unknown |
| 0.29% | `python` | `PyLong_FromSsize_t` | int |
| 0.28% | `python` | `_PyEval_NoToolsForUnwind` | interpreter |

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
| 54.73% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.24% | `python` | `gen_dealloc` | memory |
| 4.23% | `python` | `_PyObject_Free` | memory |
| 4.10% | `python` | `_PyObject_Malloc` | memory |
| 3.83% | `python` | `make_gen` | miscobj |
| 3.38% | `python` | `_PyObject_GC_NewVar` | gc |
| 2.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.49% | `python` | `_PyCompactLong_Subtract` | unknown |
| 2.05% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.96% | `python` | `_PyEval_GetAwaitable` | interpreter |
| 1.95% | `python` | `_Py_Dealloc` | memory |
| 1.85% | `python` | `_Py_MakeCoro` | unknown |
| 1.83% | `python` | `_PyCompactLong_Add` | unknown |
| 1.70% | `python` | `_PyObject_GC_Link` | gc |
| 1.63% | `python` | `_PyCoro_GetAwaitableIter` | unknown |
| 1.61% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.16% | `python` | `PyObject_GC_Del` | gc |
| 0.89% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.51% | `python` | `gen_finalize` | unknown |
| 0.48% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `PyObject_Malloc` | dynamic |
| 0.25% | `python` | `PyObject_Free` | dynamic |

## coverage

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.09% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.51% | `python` | `call_instrumentation_vector.part.0.isra.0` | interpreter |
| 6.99% | `tracer.cpython-316-x86_64-linux-gnu.so` | `CTracer_trace` | library |
| 5.19% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.90% | `python` | `_Py_call_instrumentation_line` | interpreter |
| 3.37% | `python` | `_Py_dict_lookup` | lookup |
| 3.13% | `python` | `_PyObject_Free` | memory |
| 2.84% | `python` | `_PyObject_Malloc` | memory |
| 2.36% | `python` | `PyDict_GetItem` | dict |
| 2.27% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 2.06% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.04% | `python` | `siphash13` | str |
| 1.97% | `python` | `set_add_entry_takeref` | miscobj |
| 1.63% | `python` | `PyLong_FromLong` | int |
| 1.35% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 1.19% | `python` | `find_first_nonascii` | str |
| 1.19% | `python` | `PyUnicode_InternFromString` | str |
| 1.11% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 1.04% | `python` | `PySet_Add` | miscobj |
| 0.98% | `python` | `_Py_Dealloc` | memory |
| 0.96% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.93% | `python` | `PyObject_SetAttr` | dynamic |
| 0.93% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.91% | `python` | `_PyDict_LoadGlobalStackRef` | dict |
| 0.90% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.85% | `tracer.cpython-316-x86_64-linux-gnu.so` | `CTracer_set_pdata_stack.constprop.0` | library |
| 0.84% | `python` | `PyUnicode_New.part.0` | memory |
| 0.82% | `python` | `_PyCode_GetCode` | interpreter |
| 0.80% | `python` | `sys_trace_start` | library |
| 0.77% | `python` | `PyObject_GC_Del` | gc |
| 0.75% | `python` | `_Py_call_instrumentation_arg` | unknown |
| 0.72% | `python` | `PyFrame_GetCode` | exceptions |
| 0.69% | `python` | `sys_trace_return` | library |
| 0.67% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.66% | `python` | `PyEval_GetFrame` | interpreter |
| 0.66% | `python` | `PyObject_Hash` | dynamic |
| 0.66% | `python` | `frame_dealloc` | memory |
| 0.65% | `python` | `_PyType_GetDict` | dynamic |
| 0.65% | `python` | `pysiphash` | unknown |
| 0.61% | `python` | `_Py_call_instrumentation` | unknown |
| 0.60% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.60% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.59% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.56% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.55% | `python` | `_PyFrame_MakeAndSetFrameObject` | interpreter |
| 0.54% | `python` | `_PyUnicode_InternMortal` | str |
| 0.50% | `python` | `unicode_dealloc` | memory |
| 0.50% | `python` | `getset_set` | unknown |
| 0.50% | `python` | `hashtable_unicode_hash` | unknown |
| 0.49% | `python` | `PyObject_SetAttrString` | dynamic |
| 0.46% | `python` | `_PyCompactLong_Add` | unknown |
| 0.46% | `python` | `long_hash` | int |
| 0.42% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.42% | `python` | `_PyEval_LoadGlobalStackRef` | interpreter |
| 0.42% | `python` | `PyFrame_GetLineNumber` | exceptions |
| 0.41% | `python` | `frame_trace_set` | unknown |
| 0.34% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.31% | `python` | `_Py_hashtable_get` | lookup |
| 0.30% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `PyFrame_GetLasti` | exceptions |
| 0.27% | `python` | `_PyObject_GC_Link` | gc |
| 0.26% | `python` | `_PyErr_SetRaisedException` | exceptions |
| 0.26% | `python` | `_Py_NewReference` | memory |
| 0.26% | `python` | `_PyFrame_New_NoTrack` | interpreter |

## crypto_pyaes

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.34% | `[JIT]` | `jit` | jit |
| 7.50% | `python` | `_PyObject_Free` | memory |
| 7.45% | `python` | `long_bitwise` | int |
| 4.71% | `python` | `_PyObject_Malloc` | memory |
| 3.71% | `python` | `long_rshift1` | int |
| 3.59% | `python` | `l_mod` | int |
| 3.30% | `python` | `long_alloc` | memory |
| 2.78% | `python` | `_Py_Dealloc` | memory |
| 1.89% | `python` | `maybe_small_long` | unknown |
| 1.86% | `python` | `long_rshift` | int |
| 1.82% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.56% | `python` | `PyNumber_Xor` | dynamic |
| 1.47% | `python` | `long_dealloc` | memory |
| 1.46% | `python` | `PyLong_FromLong` | int |
| 1.42% | `python` | `PyNumber_Rshift` | dynamic |
| 1.41% | `python` | `PyLong_FromSsize_t` | int |
| 1.24% | `python` | `compactlongs_guard` | unknown |
| 1.22% | `python` | `_PyCompactLong_Add` | unknown |
| 1.22% | `python` | `PyNumber_Remainder` | dynamic |
| 1.01% | `python` | `long_mod` | int |
| 0.94% | `python` | `make_range_object` | unknown |
| 0.86% | `python` | `long_xor` | int |
| 0.82% | `python` | `_Py_NewReference` | memory |
| 0.81% | `python` | `_PyLong_FromMedium` | int |
| 0.73% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.67% | `python` | `range_iter` | miscobj |
| 0.60% | `python` | `compactlongs_and` | unknown |
| 0.59% | `python` | `list_dealloc` | memory |
| 0.44% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.41% | `python` | `PyObject_Malloc` | dynamic |
| 0.38% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.36% | `python` | `PyNumber_And` | dynamic |
| 0.34% | `python` | `PyObject_Free` | dynamic |
| 0.34% | `python` | `set_lookkey` | miscobj |
| 0.32% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.32% | `python` | `PyLong_AsLong` | int |
| 0.29% | `python` | `PyList_New.constprop.0` | memory |
| 0.29% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.29% | `python` | `list_slice_lock_held` | list |

## deepcopy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.28% | `[JIT]` | `jit` | jit |
| 6.38% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.14% | `python` | `_Py_dict_lookup` | lookup |
| 3.87% | `python` | `_PyObject_Malloc` | memory |
| 3.25% | `python` | `_PyObject_Free` | memory |
| 2.97% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.14% | `python` | `set_lookkey` | miscobj |
| 1.97% | `python` | `_Py_Dealloc` | memory |
| 1.72% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.43% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.11% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.08% | `python` | `long_richcompare` | int |
| 1.05% | `python` | `PyObject_Hash` | dynamic |
| 1.05% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.04% | `python` | `PyLong_FromVoidPtr` | int |
| 1.01% | `python` | `insertdict` | dict |
| 0.99% | `python` | `initialize_locals` | interpreter |
| 0.97% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.85% | `python` | `dictiter_iternextitem` | dict |
| 0.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.84% | `python` | `_PyDict_Subscript` | dict |
| 0.83% | `python` | `_PyObject_Realloc` | memory |
| 0.82% | `python` | `_PySet_Contains` | miscobj |
| 0.81% | `python` | `list_append` | list |
| 0.76% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.75% | `python` | `long_hash` | int |
| 0.67% | `python` | `sys_audit_tstate` | unknown |
| 0.66% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.65% | `python` | `PySys_Audit` | unknown |
| 0.62% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.61% | `python` | `insert_to_emptydict` | dict |
| 0.58% | `python` | `tuple_dealloc` | memory |
| 0.55% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.53% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.48% | `python` | `builtin_id` | unknown |
| 0.47% | `python` | `PyDict_Contains` | dict |
| 0.46% | `python` | `PyObject_SetItem` | dynamic |
| 0.45% | `python` | `tuple_alloc` | memory |
| 0.44% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.44% | `python` | `_Py_NewReference` | memory |
| 0.42% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `dict_get` | dict |
| 0.41% | `python` | `PyType_IsSubtype` | dynamic |
| 0.41% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.40% | `python` | `dict_dealloc` | memory |
| 0.40% | `python` | `_PyJIT_Entry` | compiler |
| 0.39% | `python` | `PyObject_GetItem` | dynamic |
| 0.39% | `python` | `_PyObject_Calloc` | memory |
| 0.38% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.37% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.37% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.36% | `python` | `_PyDict_Next` | dict |
| 0.35% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.35% | `python` | `_PyObject_GC_New` | gc |
| 0.34% | `python` | `PyCMethod_New` | memory |
| 0.33% | `python` | `new_dict.constprop.0` | dict |
| 0.32% | `python` | `PyDict_GetItemRef` | dict |
| 0.32% | `python` | `PyObject_GC_Del` | gc |
| 0.29% | `python` | `PyList_New` | memory |
| 0.28% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |

## deltablue

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.36% | `[JIT]` | `jit` | jit |
| 10.23% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.43% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.43% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.62% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.45% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 2.15% | `python` | `listiter_next` | list |
| 1.99% | `python` | `gc_collect_main` | gc |
| 1.52% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.38% | `python` | `_PyObject_Malloc` | memory |
| 1.16% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.04% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.84% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.79% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.77% | `python` | `visit_decref` | gc |
| 0.73% | `python` | `_Py_Dealloc` | memory |
| 0.72% | `python` | `_PyObject_Free` | memory |
| 0.70% | `python` | `_PyJIT_Entry` | compiler |
| 0.55% | `python` | `_Py_type_getattro` | lookup |
| 0.55% | `python` | `_PyType_GetDict` | dynamic |
| 0.50% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.49% | `python` | `PyType_IsSubtype` | dynamic |
| 0.43% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.40% | `python` | `PyMethod_New` | memory |
| 0.39% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.39% | `python` | `PyDict_GetItemRef` | dict |
| 0.39% | `python` | `subtype_dealloc` | memory |
| 0.36% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.34% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.32% | `python` | `subtype_traverse` | gc |
| 0.31% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.31% | `python` | `_PyCompactLong_Add` | unknown |
| 0.31% | `python` | `list_pop` | list |
| 0.31% | `python` | `PyObject_RichCompare` | dynamic |
| 0.30% | `python` | `list_iter` | list |
| 0.29% | `python` | `long_to_decimal_string_internal` | int |
| 0.29% | `python` | `method_dealloc` | memory |
| 0.28% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.26% | `python` | `_PyObject_Realloc` | memory |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.25% | `python` | `_PyCompactLong_Multiply` | unknown |

## django_template

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.06% | `[JIT]` | `jit` | jit |
| 8.48% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.35% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.10% | `python` | `_PyObject_Malloc` | memory |
| 2.30% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.96% | `python` | `_PyObject_Free` | memory |
| 1.68% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.66% | `python` | `_Py_Dealloc` | memory |
| 1.62% | `python` | `initialize_locals` | interpreter |
| 1.61% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.40% | `python` | `replace` | str |
| 1.15% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.12% | `python` | `_Py_dict_lookup` | lookup |
| 1.07% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.05% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.01% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.95% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.88% | `python` | `unicode_replace` | str |
| 0.85% | `python` | `PyType_IsSubtype` | dynamic |
| 0.85% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.77% | `python` | `PyObject_SetItem` | dynamic |
| 0.74% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.69% | `python` | `long_to_decimal_string_internal` | int |
| 0.67% | `python` | `dict_dealloc` | memory |
| 0.65% | `python` | `insertdict` | dict |
| 0.64% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.62% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.56% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.55% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.54% | `python` | `object_isinstance` | dynamic |
| 0.52% | `python` | `tuple_dealloc` | memory |
| 0.52% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.48% | `python` | `_PyJIT_Entry` | compiler |
| 0.45% | `python` | `list_subscript` | list |
| 0.44% | `python` | `_PyEvalFramePushAndInit_Ex` | interpreter |
| 0.44% | `python` | `_PyType_GetDict` | dynamic |
| 0.40% | `python` | `PyDict_GetItemRef` | dict |
| 0.39% | `python` | `PyDict_New` | memory |
| 0.37% | `python` | `PyObject_IsInstance` | dynamic |
| 0.37% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.37% | `python` | `func_dealloc` | memory |
| 0.36% | `python` | `_PyObject_GC_New` | gc |
| 0.36% | `python` | `enum_next` | miscobj |
| 0.36% | `python` | `_PyObject_Calloc` | memory |
| 0.35% | `python` | `_Py_NewReference` | memory |
| 0.35% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.35% | `python` | `tuple_iter` | tuple |
| 0.34% | `python` | `listiter_next` | list |
| 0.34% | `python` | `unicode_new` | memory |
| 0.34% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.33% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.32% | `python` | `make_gen` | miscobj |
| 0.30% | `python` | `PySequence_Fast` | dynamic |
| 0.30% | `python` | `PyMethod_New` | memory |
| 0.29% | `python` | `new_dict.constprop.0` | dict |
| 0.29% | `python` | `_PyCompactLong_Add` | unknown |
| 0.28% | `python` | `list_extend_lock_held` | list |
| 0.27% | `python` | `getset_get` | dynamic |
| 0.27% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.27% | `python` | `PyObject_GetIter` | dynamic |
| 0.26% | `python` | `gen_dealloc` | memory |
| 0.26% | `python` | `func_clear` | unknown |
| 0.26% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.26% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.26% | `python` | `PyType_GenericAlloc` | memory |

## docutils

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.59% | `[JIT]` | `jit` | jit |
| 9.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.16% | `python` | `sre_ucs1_match` | library |
| 5.68% | `python` | `gc_collect_main` | gc |
| 3.41% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.62% | `python` | `_PyObject_Malloc` | memory |
| 2.29% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.91% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.72% | `python` | `visit_decref` | gc |
| 1.67% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.52% | `python` | `_PyObject_Free` | memory |
| 1.35% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.26% | `python` | `list_dealloc` | memory |
| 1.21% | `python` | `_Py_dict_lookup` | lookup |
| 1.10% | `python` | `_Py_Dealloc` | memory |
| 1.07% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.98% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.86% | `python` | `initialize_locals` | interpreter |
| 0.80% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.75% | `python` | `visit_reachable` | gc |
| 0.70% | `python` | `PyType_IsSubtype` | dynamic |
| 0.64% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.60% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.53% | `python` | `_PyJIT_Entry` | compiler |
| 0.52% | `python` | `list_slice_lock_held` | list |
| 0.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.50% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.50% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `PyUnicode_Format` | str |
| 0.43% | `python` | `list_extend_lock_held` | list |
| 0.43% | `python` | `sre_ucs1_count` | library |
| 0.42% | `python` | `sre_search` | library |
| 0.37% | `python` | `split` | str |
| 0.37% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.37% | `python` | `PyObject_SetAttr` | dynamic |
| 0.36% | `python` | `tuple_alloc` | memory |
| 0.36% | `python` | `_PyObject_Realloc` | memory |
| 0.36% | `python` | `list_traverse` | gc |
| 0.35% | `python` | `dict_traverse` | gc |
| 0.34% | `python` | `PyList_New.constprop.0` | memory |
| 0.33% | `libc.so.6` | `_int_malloc` | libc |
| 0.32% | `python` | `PyDict_GetItemRef` | dict |
| 0.32% | `python` | `insertdict` | dict |
| 0.32% | `python` | `_PyDict_Subscript` | dict |
| 0.32% | `python` | `dict_dealloc` | memory |
| 0.32% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.31% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.31% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.29% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `_PyType_GetDict` | dynamic |
| 0.27% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.26% | `python` | `subtype_traverse` | gc |

## dulwich_log

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 13.44% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.32% | `[JIT]` | `jit` | jit |
| 2.72% | `python` | `_PyObject_Malloc` | memory |
| 1.90% | `libz.so.1.3` | `inflate` | library |
| 1.82% | `python` | `_PyObject_Free` | memory |
| 1.46% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.45% | `python` | `_Py_Dealloc` | memory |
| 0.98% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.91% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.78% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.75% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.69% | `libz.so.1.3` | `0x000000000000381f` | library |
| 0.65% | `libc.so.6` | `_int_malloc` | libc |
| 0.56% | `python` | `initialize_locals` | interpreter |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.52% | `python` | `PyLong_FromString` | int |
| 0.51% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.50% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.48% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.48% | `python` | `PyObject_RichCompare` | dynamic |
| 0.46% | `python` | `_Py_dict_lookup` | lookup |
| 0.46% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.41% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.39% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.38% | `python` | `PyObject_IsTrue` | dynamic |
| 0.37% | `python` | `clear_slots` | unknown |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.36% | `python` | `PyList_New.constprop.0` | memory |
| 0.36% | `python` | `_io_open` | unknown |
| 0.36% | `python` | `PySlice_New` | memory |
| 0.36% | `python` | `bytes_subscript` | str |
| 0.36% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.35% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.35% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.34% | `libz.so.1.3` | `0x00000000000025b7` | library |
| 0.33% | `python` | `bytes_richcompare` | str |
| 0.33% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.32% | `python` | `convertitem.constprop.0` | unknown |
| 0.32% | `python` | `_PyJIT_Entry` | compiler |
| 0.32% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 0.32% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.30% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.30% | `python` | `set_lookkey` | miscobj |
| 0.30% | `libz.so.1.3` | `adler32_z` | library |
| 0.30% | `python` | `siphash13` | str |
| 0.30% | `python` | `list_dealloc` | memory |
| 0.30% | `python` | `subtype_dealloc` | memory |
| 0.29% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.29% | `[kernel.kallsyms]` | `kmem_cache_alloc` | kernel |
| 0.29% | `python` | `_PyCompactLong_Multiply` | unknown |
| 0.29% | `python` | `_PyCompactLong_Add` | unknown |
| 0.29% | `python` | `unicode_from_format` | str |
| 0.29% | `python` | `PyUnicode_Decode` | str |
| 0.28% | `python` | `do_mkvalue` | unknown |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_hex_impl.isra.0` | library |
| 0.26% | `libc.so.6` | `__gconv_transform_utf8_internal` | libc |
| 0.26% | `python` | `bytes_decode` | str |
| 0.26% | `python` | `PyObject_GetItem` | dynamic |

## fannkuch

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.25% | `[JIT]` | `jit` | jit |
| 11.91% | `python` | `PySlice_AdjustIndices` | miscobj |
| 6.51% | `python` | `list_ass_slice_lock_held` | list |
| 4.94% | `python` | `list_slice_wrap` | list |
| 3.90% | `python` | `_Py_Dealloc` | memory |
| 3.78% | `python` | `_PyObject_Free` | memory |
| 3.47% | `python` | `PySlice_New` | memory |
| 3.08% | `python` | `PySlice_Unpack` | miscobj |
| 2.98% | `python` | `PyObject_GC_UnTrack` | gc |
| 2.80% | `python` | `list_dealloc` | memory |
| 2.69% | `python` | `_PyEval_SliceIndex` | interpreter |
| 2.59% | `python` | `list_ass_subscript` | list |
| 2.57% | `python` | `_PyObject_Malloc` | memory |
| 2.54% | `python` | `_PyCompactLong_Add` | unknown |
| 2.51% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 2.14% | `python` | `slice_dealloc` | memory |
| 1.62% | `python` | `PyList_New.constprop.0` | memory |
| 1.61% | `python` | `PySequence_Fast` | dynamic |
| 1.58% | `python` | `list_insert` | list |
| 1.56% | `python` | `_PyList_SliceSubscript` | list |
| 1.50% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.49% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.92% | `python` | `PyObject_SetItem` | dynamic |
| 0.90% | `python` | `_Py_NewReference` | memory |
| 0.88% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.76% | `python` | `list_pop` | list |
| 0.55% | `python` | `list_slice_lock_held` | list |
| 0.53% | `python` | `_PyNumber_Index` | dynamic |
| 0.45% | `python` | `PyLong_AsSsize_t` | int |
| 0.29% | `python` | `list_resize` | list |

## fastapi

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.06% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 16.03% | `[JIT]` | `jit` | jit |
| 3.11% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.04% | `python` | `_PyObject_Malloc` | memory |
| 1.47% | `python` | `initialize_locals` | interpreter |
| 1.44% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.30% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.27% | `python` | `_PyObject_Free` | memory |
| 1.17% | `python` | `PyObject_RichCompare` | dynamic |
| 1.03% | `python` | `_Py_Dealloc` | memory |
| 0.96% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.95% | `libc.so.6` | `pthread_rwlock_unlock@@GLIBC_2.34` | libc |
| 0.86% | `libc.so.6` | `pthread_rwlock_rdlock@GLIBC_2.2.5` | libc |
| 0.70% | `python` | `bytes_richcompare` | str |
| 0.69% | `python` | `_PyEval_Vector` | interpreter |
| 0.69% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.68% | `python` | `_Py_dict_lookup` | lookup |
| 0.65% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.64% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.60% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.57% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.56% | `python` | `tuple_dealloc` | memory |
| 0.53% | `python` | `gc_collect_main` | gc |
| 0.53% | `python` | `slot_tp_richcompare` | dynamic |
| 0.51% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.43% | `python` | `PyDict_GetItemRef` | dict |
| 0.39% | `libc.so.6` | `malloc` | libc |
| 0.36% | `python` | `_PyJIT_Entry` | compiler |
| 0.35% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.35% | `python` | `tuple_alloc` | memory |
| 0.33% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.32% | `python` | `subtype_dealloc` | memory |
| 0.32% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.31% | `python` | `sre_ucs1_match` | library |
| 0.31% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.30% | `libc.so.6` | `_int_malloc` | libc |
| 0.30% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.29% | `python` | `long_richcompare` | int |
| 0.29% | `python` | `set_lookkey` | miscobj |
| 0.29% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.28% | `python` | `visit_decref` | gc |
| 0.28% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `libc.so.6` | `_int_free` | libc |
| 0.26% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.26% | `python` | `list_dealloc` | memory |
| 0.26% | `python` | `_PyDict_FromItems` | dict |
| 0.25% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.25% | `python` | `_PyThreadState_PushFrame` | threading |

## float

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.17% | `[JIT]` | `jit` | jit |
| 5.23% | `python` | `subtype_traverse` | gc |
| 4.02% | `python` | `gc_collect_main` | gc |
| 3.96% | `libm.so.6` | `__sin_fma` | library |
| 3.84% | `python` | `PyFloat_FromDouble` | float |
| 3.55% | `libm.so.6` | `__cos_fma` | library |
| 3.45% | `python` | `visit_reachable` | gc |
| 3.42% | `python` | `_Py_Dealloc` | memory |
| 3.31% | `python` | `_PyObject_Malloc` | memory |
| 3.25% | `python` | `visit_decref` | gc |
| 2.95% | `python` | `_PyObject_Free` | memory |
| 2.61% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.63% | `python` | `float_dealloc` | memory |
| 1.52% | `python` | `clear_slots` | unknown |
| 1.46% | `python` | `_Py_NewReference` | memory |
| 1.34% | `python` | `PyFloat_AsDouble` | float |
| 1.32% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.16% | `python` | `_PyMember_GetOffset` | unknown |
| 1.11% | `python` | `list_dealloc` | memory |
| 1.09% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.00% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.94% | `python` | `long_float` | int |
| 0.88% | `python` | `list_slice_lock_held` | list |
| 0.88% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.85% | `python` | `subtype_dealloc` | memory |
| 0.80% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.80% | `python` | `initialize_locals` | interpreter |
| 0.72% | `python` | `PyType_IsSubtype` | dynamic |
| 0.60% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.60% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.59% | `python` | `PyType_GenericAlloc` | memory |
| 0.52% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.51% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.50% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sin` | library |
| 0.43% | `python` | `list_traverse` | gc |
| 0.41% | `math.cpython-316-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.40% | `python` | `_PyLong_FromMedium` | int |
| 0.34% | `python` | `float_compactlong_true_div` | float |
| 0.33% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.28% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.28% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.27% | `[kernel.kallsyms]` | `zap_pte_range` | kernel |
| 0.27% | `python` | `long_dealloc` | memory |
| 0.27% | `python` | `_PyObject_GC_Link` | gc |
| 0.26% | `python` | `PyObject_GC_UnTrack` | gc |

## gc_collect

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.08% | `python` | `gc_collect_main` | gc |
| 20.30% | `python` | `visit_reachable` | gc |
| 20.24% | `python` | `visit_decref` | gc |
| 8.42% | `python` | `dict_traverse` | gc |
| 2.97% | `python` | `func_traverse` | gc |
| 2.84% | `[JIT]` | `jit` | jit |
| 2.01% | `python` | `subtype_traverse` | gc |
| 1.83% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 1.26% | `python` | `tuple_traverse` | gc |
| 1.16% | `python` | `type_traverse` | gc |
| 1.13% | `python` | `type_is_gc` | gc |
| 0.94% | `python` | `set_traverse` | gc |
| 0.92% | `python` | `list_traverse` | gc |
| 0.85% | `python` | `PyObject_IS_GC` | gc |
| 0.54% | `python` | `meth_traverse` | gc |
| 0.53% | `python` | `_PyObject_Malloc` | memory |
| 0.44% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.43% | `python` | `_PyTuple_MaybeUntrack` | gc |
| 0.34% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.31% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.29% | `python` | `gc_traverse` | gc |
| 0.29% | `python` | `subtype_dealloc` | memory |
| 0.26% | `python` | `_PyEvalFramePushAndInit` | interpreter |

## gc_traversal

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.90% | `python` | `visit_reachable` | gc |
| 30.53% | `python` | `visit_decref` | gc |
| 13.41% | `python` | `list_traverse` | gc |
| 11.07% | `python` | `gc_collect_main` | gc |
| 3.99% | `python` | `dict_traverse` | gc |
| 1.42% | `python` | `func_traverse` | gc |
| 1.34% | `[JIT]` | `jit` | jit |
| 0.63% | `python` | `type_traverse` | gc |
| 0.57% | `python` | `tuple_traverse` | gc |
| 0.54% | `python` | `subtype_traverse` | gc |
| 0.50% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.48% | `python` | `type_is_gc` | gc |
| 0.43% | `python` | `set_traverse` | gc |
| 0.41% | `python` | `PyObject_IS_GC` | gc |
| 0.27% | `python` | `PyLong_FromLong` | int |
| 0.25% | `python` | `list_dealloc` | memory |
| 0.25% | `python` | `meth_traverse` | gc |

## generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 46.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.79% | `[JIT]` | `jit` | jit |
| 3.25% | `python` | `gc_collect_main` | gc |
| 2.02% | `python` | `_PyObject_Malloc` | memory |
| 1.72% | `python` | `_Py_Dealloc` | memory |
| 1.65% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.60% | `python` | `_PyObject_Free` | memory |
| 1.46% | `python` | `initialize_locals` | interpreter |
| 1.44% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.40% | `python` | `gen_dealloc` | memory |
| 1.24% | `python` | `make_range_object` | unknown |
| 1.18% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.15% | `python` | `visit_reachable` | gc |
| 1.14% | `python` | `visit_decref` | gc |
| 1.07% | `python` | `make_gen` | miscobj |
| 1.00% | `python` | `_PyEval_Vector` | interpreter |
| 0.92% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.90% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.90% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.90% | `python` | `range_subscript` | miscobj |
| 0.87% | `python` | `_PyLong_FromMedium` | int |
| 0.86% | `python` | `PyNumber_Add` | dynamic |
| 0.82% | `python` | `long_richcompare` | int |
| 0.78% | `python` | `slot_tp_iter` | unknown |
| 0.78% | `python` | `subtype_traverse` | gc |
| 0.72% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.70% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.69% | `python` | `PySlice_New` | memory |
| 0.62% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.58% | `python` | `long_add` | int |
| 0.57% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.54% | `python` | `_PyEval_GetIter` | interpreter |
| 0.49% | `python` | `range_dealloc` | memory |
| 0.49% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.48% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.46% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.45% | `python` | `long_dealloc` | memory |
| 0.44% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.42% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.42% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.40% | `python` | `_Py_NewReference` | memory |
| 0.38% | `python` | `PyObject_GC_Del` | gc |
| 0.37% | `python` | `_PyJIT_Entry` | compiler |
| 0.35% | `python` | `long_mul` | int |
| 0.34% | `python` | `PyObject_GetItem` | dynamic |
| 0.33% | `python` | `long_div` | int |
| 0.29% | `python` | `PyObject_GetIter` | dynamic |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `python` | `PyNumber_Index` | dynamic |
| 0.26% | `python` | `_PyObject_GC_Link` | gc |
| 0.26% | `python` | `PyLong_FromLong` | int |

## genshi

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.67% | `[JIT]` | `jit` | jit |
| 7.50% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.35% | `python` | `_PyObject_Malloc` | memory |
| 2.35% | `python` | `_Py_dict_lookup` | lookup |
| 2.13% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.06% | `python` | `_Py_Dealloc` | memory |
| 2.04% | `python` | `_PyObject_Free` | memory |
| 1.81% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.74% | `python` | `insertdict` | dict |
| 1.49% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.44% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.32% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.30% | `python` | `insert_to_emptydict` | dict |
| 1.09% | `python` | `_PyDict_FromItems` | dict |
| 0.97% | `python` | `PyDict_GetItemRef` | dict |
| 0.94% | `python` | `tuple_dealloc` | memory |
| 0.92% | `python` | `_PyJIT` | unknown |
| 0.89% | `python` | `initialize_locals` | interpreter |
| 0.87% | `python` | `_Py_BuildMap_StackRefSteal` | unknown |
| 0.87% | `python` | `long_to_decimal_string_internal` | int |
| 0.77% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.76% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.73% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.73% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.71% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.65% | `python` | `tuple_alloc` | memory |
| 0.62% | `python` | `pattern_subx` | library |
| 0.59% | `python` | `dictiter_iternextvalue` | dict |
| 0.58% | `python` | `PyType_IsSubtype` | dynamic |
| 0.56% | `python` | `_PyEval_EnsureBuiltins` | interpreter |
| 0.54% | `python` | `gen_iternext` | miscobj |
| 0.54% | `python` | `PyObject_IsTrue` | dynamic |
| 0.54% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.54% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.53% | `python` | `PyMethod_New` | memory |
| 0.52% | `python` | `_PyObject_GC_New` | gc |
| 0.51% | `python` | `new_dict` | dict |
| 0.50% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.48% | `python` | `method_dealloc` | memory |
| 0.40% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.40% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.40% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.40% | `python` | `_PyFunction_FromConstructor` | unknown |
| 0.40% | `python` | `PyObject_Str` | dynamic |
| 0.39% | `python` | `PyEval_EvalCode` | interpreter |
| 0.39% | `python` | `_Py_NewReference` | memory |
| 0.39% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.39% | `python` | `_list_extend` | list |
| 0.38% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.38% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.36% | `python` | `dict_dealloc` | memory |
| 0.35% | `python` | `func_dealloc` | memory |
| 0.35% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.32% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.31% | `python` | `PyObject_IsInstance` | dynamic |
| 0.31% | `python` | `build_indices_unicode` | dict |
| 0.30% | `python` | `deque_iter` | miscobj |
| 0.30% | `libc.so.6` | `_int_malloc` | libc |
| 0.28% | `python` | `func_clear` | unknown |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.26% | `python` | `PyUnicode_New` | memory |

## go

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 53.89% | `[JIT]` | `jit` | jit |
| 15.78% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.26% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.28% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.58% | `python` | `initialize_locals` | interpreter |
| 1.44% | `python` | `long_bitwise` | int |
| 1.28% | `python` | `_PyObject_Free` | memory |
| 1.18% | `python` | `insertdict` | dict |
| 1.14% | `python` | `_PyObject_Malloc` | memory |
| 1.00% | `python` | `_PyCompactLong_Add` | unknown |
| 1.00% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.86% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.77% | `python` | `_Py_Dealloc` | memory |
| 0.69% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.66% | `python` | `_PyJIT_Entry` | compiler |
| 0.55% | `python` | `PyNumber_InPlaceXor` | dynamic |
| 0.51% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.43% | `python` | `set_lookkey` | miscobj |
| 0.42% | `python` | `PyFloat_FromDouble` | float |
| 0.41% | `python` | `_Py_dict_lookup` | lookup |
| 0.40% | `python` | `PyDict_SetItem` | dict |
| 0.35% | `python` | `long_dealloc` | memory |
| 0.34% | `python` | `long_alloc` | memory |
| 0.33% | `python` | `set_add_entry_takeref` | miscobj |

## hexiom

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.03% | `[JIT]` | `jit` | jit |
| 14.69% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.66% | `python` | `PyObject_RichCompareBool` | dynamic |
| 3.77% | `python` | `list_contains` | list |
| 3.39% | `python` | `long_richcompare` | int |
| 2.80% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.37% | `python` | `gen_iternext` | miscobj |
| 1.96% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.23% | `python` | `_PyJIT_Entry` | compiler |
| 1.12% | `python` | `PyLong_FromLong` | int |
| 1.08% | `python` | `PyLong_FromSsize_t` | int |
| 1.00% | `python` | `_PyObject_Malloc` | memory |
| 0.98% | `python` | `builtin_sum` | unknown |
| 0.92% | `python` | `PyObject_Size` | dynamic |
| 0.90% | `python` | `_PyObject_Free` | memory |
| 0.84% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.71% | `python` | `PyIter_Next` | dynamic |
| 0.71% | `python` | `_Py_Dealloc` | memory |
| 0.65% | `python` | `make_range_object` | unknown |
| 0.54% | `python` | `PySequence_Contains` | dynamic |
| 0.41% | `python` | `range_iter` | miscobj |
| 0.39% | `python` | `_PyCompactLong_Add` | unknown |
| 0.37% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.32% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.30% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.29% | `python` | `PyList_New.constprop.0` | memory |
| 0.29% | `python` | `func_clear` | unknown |
| 0.28% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.27% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.26% | `python` | `PyFunction_NewWithQualName` | memory |

## html5lib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.78% | `[JIT]` | `jit` | jit |
| 18.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.02% | `python` | `sre_search` | library |
| 2.57% | `python` | `gc_collect_main` | gc |
| 1.99% | `python` | `_PyObject_Malloc` | memory |
| 1.47% | `python` | `_Py_dict_lookup` | lookup |
| 1.43% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.36% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.24% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.05% | `python` | `_PyObject_Free` | memory |
| 0.91% | `python` | `_PyDict_Subscript` | dict |
| 0.90% | `python` | `set_lookkey` | miscobj |
| 0.85% | `python` | `_Py_Dealloc` | memory |
| 0.85% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.80% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.76% | `python` | `_PyJIT_Entry` | compiler |
| 0.75% | `python` | `sre_ucs1_count` | library |
| 0.73% | `python` | `PyObject_IsTrue` | dynamic |
| 0.71% | `python` | `visit_decref` | gc |
| 0.61% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.56% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.51% | `python` | `_PyUnicode_Equal` | str |
| 0.51% | `libc.so.6` | `__strcmp_avx2` | libc |
| 0.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.49% | `python` | `initialize_locals` | interpreter |
| 0.49% | `python` | `PyObject_GetItem` | dynamic |
| 0.47% | `python` | `insertdict` | dict |
| 0.45% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.44% | `python` | `sre_ucs1_match` | library |
| 0.42% | `python` | `list_subscript` | list |
| 0.42% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.42% | `python` | `list_contains` | list |
| 0.42% | `python` | `_PyDict_FromItems` | dict |
| 0.41% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.38% | `libc.so.6` | `_int_malloc` | libc |
| 0.35% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.34% | `python` | `_PyCompactLong_Add` | unknown |
| 0.34% | `python` | `visit_reachable` | gc |
| 0.33% | `python` | `insert_to_emptydict` | dict |
| 0.32% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.31% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.31% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.31% | `python` | `PyObject_Hash` | dynamic |
| 0.31% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.31% | `python` | `_Py_BuildMap_StackRefSteal` | unknown |
| 0.30% | `python` | `PyList_New.constprop.0` | memory |
| 0.30% | `python` | `PyUnicode_Concat` | str |
| 0.30% | `python` | `dict_dealloc` | memory |
| 0.29% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.28% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.26% | `python` | `PyType_IsSubtype` | dynamic |
| 0.26% | `python` | `PySlice_AdjustIndices` | miscobj |

## json

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.09% | `_json.cpython-316-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 6.73% | `_json.cpython-316-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.29% | `python` | `_PyObject_Malloc` | memory |
| 5.66% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 5.45% | `python` | `_PyObject_Free` | memory |
| 5.26% | `python` | `siphash13` | str |
| 3.90% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.12% | `[JIT]` | `jit` | jit |
| 3.01% | `python` | `_Py_dict_lookup` | lookup |
| 2.90% | `python` | `PyLong_FromString` | int |
| 2.90% | `python` | `PyUnicode_Substring` | str |
| 2.81% | `python` | `insertdict` | dict |
| 2.34% | `python` | `PyUnicode_New.part.0` | memory |
| 2.03% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 1.82% | `python` | `_Py_Dealloc` | memory |
| 1.81% | `python` | `find_empty_slot` | dict |
| 1.50% | `python` | `build_indices_unicode` | dict |
| 1.35% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.13% | `libc.so.6` | `_int_malloc` | libc |
| 1.12% | `python` | `unicode_dealloc` | memory |
| 1.01% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.99% | `python` | `initialize_locals` | interpreter |
| 0.76% | `python` | `unicode_hash` | str |
| 0.69% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.64% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.63% | `python` | `dictresize` | dict |
| 0.62% | `python` | `insert_to_emptydict` | dict |
| 0.58% | `python` | `pattern_new_match` | memory |
| 0.53% | `python` | `PyDict_GetItemRef` | dict |
| 0.52% | `python` | `new_keys_object` | dict |
| 0.52% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.48% | `python` | `_Py_NewReference` | memory |
| 0.48% | `python` | `sre_ucs1_match` | library |
| 0.47% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.47% | `python` | `maybe_small_long` | unknown |
| 0.46% | `python` | `_PyObject_Realloc` | memory |
| 0.44% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.39% | `python` | `PyDict_New` | memory |
| 0.39% | `_json.cpython-316-x86_64-linux-gnu.so` | `PyUnicode_Substring@plt` | library |
| 0.39% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.38% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.37% | `python` | `PyObject_Hash` | dynamic |
| 0.35% | `python` | `Py_HashBuffer` | unknown |
| 0.31% | `python` | `PyUnicode_Splitlines` | str |
| 0.31% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.31% | `python` | `PyObject_Malloc` | dynamic |
| 0.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.30% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.29% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 0.29% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.29% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.27% | `python` | `long_alloc` | memory |
| 0.27% | `libc.so.6` | `malloc` | libc |
| 0.27% | `python` | `dict_dealloc` | memory |
| 0.26% | `_json.cpython-316-x86_64-linux-gnu.so` | `scanner_call` | library |
| 0.25% | `python` | `convertitem.constprop.0` | unknown |

## json_dumps

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.18% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_listencode_obj` | library |
| 5.78% | `[JIT]` | `jit` | jit |
| 5.28% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 4.59% | `python` | `_PyUnicode_ResizeCompact` | str |
| 4.15% | `_json.cpython-316-x86_64-linux-gnu.so` | `ascii_escape_size` | library |
| 3.95% | `python` | `_PyObject_Malloc` | memory |
| 3.32% | `python` | `_Py_dict_lookup` | lookup |
| 3.15% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 3.03% | `python` | `PyUnicodeWriter_WriteASCII` | str |
| 2.96% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 2.78% | `python` | `PyDict_Next` | dict |
| 2.76% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 2.74% | `_json.cpython-316-x86_64-linux-gnu.so` | `write_escaped_ascii` | library |
| 2.35% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.23% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_encode_key_value` | library |
| 2.14% | `python` | `convertitem.constprop.0` | unknown |
| 1.97% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.83% | `python` | `_PyObject_Free` | memory |
| 1.71% | `python` | `initialize_locals` | interpreter |
| 1.65% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.64% | `python` | `_PyObject_Realloc` | memory |
| 1.47% | `python` | `PyDict_GetItemRef` | dict |
| 1.45% | `python` | `long_to_decimal_string_internal` | int |
| 1.39% | `python` | `PyUnicodeWriter_WriteStr` | str |
| 1.33% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 1.30% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.20% | `python` | `_Py_Dealloc` | memory |
| 1.05% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.99% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.88% | `python` | `tuple_dealloc` | memory |
| 0.83% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.80% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_write_string` | library |
| 0.69% | `python` | `delitem_common` | dynamic |
| 0.65% | `python` | `tuple_alloc` | memory |
| 0.60% | `python` | `long_hash` | int |
| 0.54% | `python` | `PyType_IsSubtype` | dynamic |
| 0.53% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.53% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.50% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.49% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.47% | `python` | `memcpy@plt` | memory |
| 0.46% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.44% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_new` | library |
| 0.44% | `python` | `PyDict_DelItem` | dict |
| 0.43% | `_json.cpython-316-x86_64-linux-gnu.so` | `PyUnicodeWriter_WriteChar@plt` | library |
| 0.42% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.40% | `python` | `dict_dealloc` | memory |
| 0.38% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.37% | `_json.cpython-316-x86_64-linux-gnu.so` | `ascii_escape_unicode_and_size` | library |
| 0.37% | `python` | `insertdict` | dict |
| 0.36% | `python` | `PyUnicode_New` | memory |
| 0.36% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.36% | `python` | `PyUnicodeWriter_Create` | str |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.32% | `python` | `new_dict.constprop.0` | dict |
| 0.32% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.31% | `python` | `PyObject_Hash` | dynamic |
| 0.31% | `python` | `_Py_NewReference` | memory |
| 0.31% | `python` | `PyLong_FromVoidPtr` | int |
| 0.28% | `python` | `PyArg_ParseTupleAndKeywords` | calls |
| 0.26% | `python` | `PyDict_SetItem` | dict |
| 0.26% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.25% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |

## json_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.17% | `_json.cpython-316-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 7.81% | `_json.cpython-316-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 7.28% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 6.74% | `python` | `_PyObject_Malloc` | memory |
| 6.23% | `python` | `siphash13` | str |
| 6.13% | `python` | `_PyObject_Free` | memory |
| 4.93% | `python` | `PyUnicode_Substring` | str |
| 3.76% | `python` | `PyUnicode_New.part.0` | memory |
| 3.39% | `python` | `PyLong_FromString` | int |
| 3.36% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.30% | `python` | `_Py_dict_lookup` | lookup |
| 3.26% | `python` | `insertdict` | dict |
| 2.05% | `python` | `_Py_Dealloc` | memory |
| 1.51% | `python` | `find_empty_slot` | dict |
| 1.46% | `python` | `unicode_dealloc` | memory |
| 1.30% | `[JIT]` | `jit` | jit |
| 1.20% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.97% | `python` | `build_indices_unicode` | dict |
| 0.90% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.82% | `python` | `unicode_hash` | str |
| 0.72% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.62% | `python` | `_Py_NewReference` | memory |
| 0.60% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.58% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.52% | `libc.so.6` | `_int_malloc` | libc |
| 0.51% | `python` | `initialize_locals` | interpreter |
| 0.49% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.44% | `python` | `dictresize` | dict |
| 0.43% | `python` | `PyObject_Malloc` | dynamic |
| 0.41% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.39% | `libc.so.6` | `malloc` | libc |
| 0.38% | `python` | `PyObject_Hash` | dynamic |
| 0.37% | `python` | `Py_HashBuffer` | unknown |
| 0.37% | `python` | `new_keys_object` | dict |
| 0.37% | `python` | `maybe_small_long` | unknown |
| 0.37% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.32% | `python` | `PyDict_GetItemRef` | dict |
| 0.32% | `python` | `sre_ucs1_match` | library |
| 0.31% | `python` | `pattern_new_match` | memory |
| 0.30% | `python` | `PyObject_Free` | dynamic |
| 0.30% | `python` | `long_alloc` | memory |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `python` | `insert_to_emptydict` | dict |
| 0.28% | `_json.cpython-316-x86_64-linux-gnu.so` | `PyUnicode_Substring@plt` | library |
| 0.26% | `python` | `_PyFrame_ClearExceptCode` | interpreter |

## logging

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.27% | `[JIT]` | `jit` | jit |
| 10.15% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.13% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.84% | `python` | `_Py_dict_lookup` | lookup |
| 2.37% | `python` | `initialize_locals` | interpreter |
| 2.26% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.03% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.99% | `python` | `dict_dealloc` | memory |
| 1.96% | `python` | `_PyObject_Malloc` | memory |
| 1.89% | `python` | `PyDict_New` | memory |
| 1.82% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.71% | `python` | `_PyCode_CheckLineNumber` | interpreter |
| 1.69% | `python` | `_Py_Dealloc` | memory |
| 1.68% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 1.41% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 1.39% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.19% | `python` | `_PyDict_Subscript` | dict |
| 1.17% | `python` | `_PyObject_Free` | memory |
| 1.04% | `python` | `_PyJIT_Entry` | compiler |
| 0.94% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.86% | `python` | `PyUnicode_Format` | str |
| 0.81% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.79% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.75% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.74% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.74% | `python` | `PyObject_GetItem` | dynamic |
| 0.67% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.60% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.57% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.56% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.51% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.49% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.47% | `python` | `_PyLong_Frexp` | int |
| 0.45% | `python` | `asciilib_default_find` | unknown |
| 0.42% | `python` | `PyObject_Hash` | dynamic |
| 0.41% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.39% | `python` | `_Py_NewReference` | memory |
| 0.38% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.34% | `python` | `getset_get` | dynamic |
| 0.33% | `python` | `PyUnicode_Splitlines` | str |
| 0.32% | `python` | `any_find_slice` | unknown |
| 0.32% | `python` | `long_hash` | int |
| 0.32% | `python` | `l_mod` | int |
| 0.32% | `python` | `unicode_rfind` | str |
| 0.31% | `python` | `PyUnicode_AsUCS4` | str |
| 0.31% | `python` | `tuple_alloc` | memory |
| 0.29% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `dict_get` | dict |
| 0.27% | `[kernel.kallsyms]` | `__task_pid_nr_ns` | kernel |
| 0.26% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.26% | `python` | `_PyLong_FromMedium` | int |
| 0.26% | `python` | `PyType_IsSubtype` | dynamic |
| 0.26% | `python` | `PyLong_FromLong` | int |
| 0.25% | `python` | `PyObject_GetOptionalAttr` | dynamic |

## mako

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.74% | `[JIT]` | `jit` | jit |
| 8.61% | `python` | `replace` | str |
| 6.18% | `python` | `long_to_decimal_string_internal` | int |
| 5.41% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 5.15% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 4.79% | `python` | `_PyObject_Malloc` | memory |
| 4.21% | `python` | `unicode_replace` | str |
| 3.53% | `python` | `deque_append` | miscobj |
| 3.37% | `python` | `_PyObject_Free` | memory |
| 2.78% | `python` | `dequeiter_next` | miscobj |
| 2.00% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.99% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.57% | `python` | `PyUnicode_New` | memory |
| 1.40% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.31% | `python` | `_list_extend` | list |
| 1.25% | `python` | `PyObject_Str` | dynamic |
| 1.17% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.08% | `python` | `deque_clear.part.0` | miscobj |
| 1.04% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.02% | `python` | `list_dealloc` | memory |
| 0.86% | `python` | `long_alloc` | memory |
| 0.83% | `python` | `PyThread_get_thread_ident` | threading |
| 0.82% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.72% | `python` | `unicode_dealloc` | memory |
| 0.69% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.66% | `python` | `_Py_Dealloc` | memory |
| 0.65% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.65% | `python` | `PyLong_FromLong` | int |
| 0.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.58% | `python` | `_Py_IsMainThread` | unknown |
| 0.57% | `python` | `long_to_decimal_string` | int |
| 0.53% | `python` | `sre_search` | library |
| 0.42% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.41% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.37% | `python` | `_Py_NewReference` | memory |
| 0.32% | `python` | `memcpy@plt` | memory |
| 0.32% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.31% | `python` | `PyObject_Malloc` | dynamic |

## mdp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.83% | `[JIT]` | `jit` | jit |
| 13.67% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.12% | `python` | `_Py_dict_lookup` | lookup |
| 6.81% | `python` | `PyObject_RichCompareBool` | dynamic |
| 4.32% | `python` | `tuple_richcompare` | tuple |
| 3.03% | `python` | `_PyDict_Subscript` | dict |
| 2.29% | `python` | `_PyLong_GCD` | int |
| 1.56% | `python` | `_PyObject_Free` | memory |
| 1.48% | `python` | `_PyObject_Malloc` | memory |
| 1.36% | `python` | `_Py_Dealloc` | memory |
| 1.32% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.29% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.27% | `python` | `builtin_sum` | unknown |
| 1.21% | `python` | `gen_iternext` | miscobj |
| 1.17% | `python` | `PyDict_GetItemRef` | dict |
| 1.10% | `python` | `_PyJIT_Entry` | compiler |
| 1.00% | `python` | `tuple_hash` | tuple |
| 0.98% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.91% | `python` | `PyObject_GetItem` | dynamic |
| 0.66% | `python` | `insertdict` | dict |
| 0.62% | `python` | `set_lookkey` | miscobj |
| 0.62% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.59% | `python` | `subtype_dealloc` | memory |
| 0.57% | `python` | `PyObject_Hash` | dynamic |
| 0.54% | `python` | `func_clear` | unknown |
| 0.53% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.51% | `python` | `long_div` | int |
| 0.49% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.47% | `python` | `PyFloat_FromDouble` | float |
| 0.46% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.46% | `python` | `_PyCompactLong_Multiply` | unknown |
| 0.44% | `python` | `PyLong_FromLong` | int |
| 0.44% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.42% | `python` | `tuple_dealloc` | memory |
| 0.41% | `python` | `func_dealloc` | memory |
| 0.41% | `python` | `gen_dealloc` | memory |
| 0.41% | `python` | `PyIter_Next` | dynamic |
| 0.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.40% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.39% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.39% | `python` | `_Py_NewReference` | memory |
| 0.36% | `python` | `initialize_locals` | interpreter |
| 0.33% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.31% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.27% | `python` | `tuple_alloc` | memory |
| 0.27% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.27% | `python` | `PyNumber_Add` | dynamic |
| 0.27% | `python` | `_PyEval_Vector` | interpreter |
| 0.26% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.26% | `python` | `min_max` | unknown |

## meteor_contest

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.11% | `[JIT]` | `jit` | jit |
| 12.61% | `python` | `set_lookkey` | miscobj |
| 11.16% | `python` | `set_issubset_impl` | miscobj |
| 9.07% | `python` | `setiter_iternext` | miscobj |
| 4.23% | `python` | `set_difference_untracked` | miscobj |
| 4.12% | `python` | `set_dealloc` | memory |
| 3.37% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.95% | `python` | `set_add_entry_takeref` | miscobj |
| 2.38% | `python` | `long_richcompare` | int |
| 2.34% | `python` | `_PyObject_Malloc` | memory |
| 2.22% | `python` | `_PyObject_Free` | memory |
| 1.93% | `python` | `list_dealloc` | memory |
| 1.93% | `python` | `list_slice_lock_held` | list |
| 1.91% | `python` | `min_max` | unknown |
| 1.52% | `python` | `PyIter_Next` | dynamic |
| 1.42% | `python` | `set_intersection` | miscobj |
| 1.32% | `python` | `PyObject_RichCompare` | dynamic |
| 1.32% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.18% | `python` | `set_table_resize` | miscobj |
| 1.09% | `python` | `set_merge_lock_held` | miscobj |
| 0.92% | `python` | `_Py_Dealloc` | memory |
| 0.87% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.81% | `python` | `set_richcompare` | miscobj |
| 0.58% | `python` | `set_difference_update_internal` | miscobj |
| 0.57% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.49% | `python` | `initialize_locals` | interpreter |
| 0.47% | `python` | `PyList_New.constprop.0` | memory |
| 0.42% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.41% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.37% | `python` | `list_ass_slice_lock_held` | list |
| 0.36% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.35% | `python` | `set_sub` | miscobj |
| 0.34% | `python` | `_PyObject_GC_New` | gc |
| 0.34% | `python` | `PyObject_GC_Del` | gc |
| 0.33% | `python` | `PyLong_FromSsize_t` | int |
| 0.33% | `python` | `PyObject_IsTrue` | dynamic |
| 0.31% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `set_iter` | miscobj |
| 0.27% | `python` | `_PyList_SliceSubscript` | list |
| 0.26% | `python` | `PyObject_Size` | dynamic |
| 0.26% | `python` | `PyObject_GetIter` | dynamic |
| 0.25% | `python` | `list_slice_wrap` | list |

## nbody

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 63.89% | `[JIT]` | `jit` | jit |
| 8.54% | `python` | `PyFloat_FromDouble` | float |
| 7.39% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 6.87% | `python` | `_Py_Dealloc` | memory |
| 4.13% | `python` | `float_dealloc` | memory |
| 2.82% | `python` | `_Py_NewReference` | memory |
| 2.40% | `python` | `float_pow` | float |
| 1.10% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.03% | `python` | `_PyNumber_PowerNoMod` | dynamic |
| 0.70% | `libm.so.6` | `pow@@GLIBC_2.29` | library |
| 0.27% | `python` | `_PyEval_EvalFrameDefault` | interpreter |

## networkx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.19% | `python` | `set_lookkey` | miscobj |
| 21.41% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 15.57% | `python` | `dictiter_iternextkey` | dict |
| 9.59% | `[JIT]` | `jit` | jit |
| 5.85% | `python` | `build_indices_unicode` | dict |
| 2.50% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.27% | `python` | `_PyDict_Subscript` | dict |
| 1.16% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.13% | `python` | `set_dealloc` | memory |
| 0.93% | `python` | `_PySet_Contains` | miscobj |
| 0.92% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.84% | `python` | `list_dealloc` | memory |
| 0.77% | `python` | `deque_clear.part.0` | miscobj |
| 0.77% | `python` | `unicode_hash` | str |
| 0.58% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.55% | `python` | `set_table_resize` | miscobj |
| 0.53% | `python` | `_Py_dict_lookup` | lookup |
| 0.52% | `python` | `PyObject_Hash` | dynamic |
| 0.45% | `python` | `_PyObject_Free` | memory |
| 0.45% | `python` | `set_add_entry_takeref` | miscobj |
| 0.41% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.39% | `python` | `insertdict` | dict |
| 0.32% | `python` | `_Py_Dealloc` | memory |
| 0.29% | `python` | `merge_from_seq2_lock_held` | unknown |
| 0.26% | `python` | `tuple_alloc` | memory |
| 0.25% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |

## networkx_connected_components

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.37% | `python` | `set_lookkey` | miscobj |
| 16.13% | `python` | `dictiter_iternextkey` | dict |
| 15.96% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 11.36% | `[JIT]` | `jit` | jit |
| 3.33% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.66% | `python` | `_PyDict_Subscript` | dict |
| 2.48% | `python` | `set_dealloc` | memory |
| 1.58% | `python` | `set_merge_lock_held` | miscobj |
| 1.20% | `python` | `_PySet_Contains` | miscobj |
| 0.95% | `python` | `unicode_hash` | str |
| 0.91% | `python` | `list_dealloc` | memory |
| 0.67% | `python` | `PyObject_Hash` | dynamic |
| 0.66% | `python` | `set_table_resize` | miscobj |
| 0.58% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.48% | `python` | `_PyObject_Free` | memory |
| 0.46% | `python` | `set_add_entry_takeref` | miscobj |
| 0.44% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.29% | `python` | `_Py_dict_lookup` | lookup |

## networkx_k_core

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 34.65% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 19.63% | `[JIT]` | `jit` | jit |
| 6.63% | `python` | `list_remove` | list |
| 5.09% | `python` | `_PyDict_Subscript` | dict |
| 3.36% | `python` | `dictiter_iternextkey` | dict |
| 3.26% | `python` | `visit_decref` | gc |
| 3.01% | `python` | `_Py_dict_lookup` | lookup |
| 2.94% | `python` | `visit_reachable` | gc |
| 1.52% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.44% | `python` | `gc_collect_main` | gc |
| 1.40% | `python` | `build_indices_unicode` | dict |
| 1.24% | `python` | `dict_traverse` | gc |
| 1.19% | `python` | `PyUnicode_RichCompare` | str |
| 1.16% | `python` | `list_dealloc` | memory |
| 1.05% | `python` | `insertdict` | dict |
| 1.04% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.88% | `python` | `listiter_next` | list |
| 0.82% | `python` | `PyObject_GetItem` | dynamic |
| 0.58% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.47% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.42% | `python` | `_PyObject_Malloc` | memory |
| 0.38% | `python` | `list_traverse` | gc |
| 0.35% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.33% | `python` | `PyObject_SetItem` | dynamic |
| 0.31% | `python` | `list_sort_impl` | list |
| 0.29% | `python` | `list_ass_slice_lock_held` | list |

## nqueens

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.77% | `[JIT]` | `jit` | jit |
| 3.84% | `python` | `_PyObject_Free` | memory |
| 3.83% | `python` | `_PyObject_Malloc` | memory |
| 3.40% | `python` | `set_add_entry_takeref` | miscobj |
| 3.03% | `python` | `_Py_Dealloc` | memory |
| 2.78% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.70% | `python` | `set_dealloc` | memory |
| 1.55% | `python` | `_PyCompactLong_Add` | unknown |
| 1.50% | `python` | `PyList_New.constprop.0` | memory |
| 1.33% | `python` | `PyFunction_NewWithQualName` | memory |
| 1.25% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.22% | `python` | `list_dealloc` | memory |
| 1.20% | `python` | `PyLong_FromLong` | int |
| 1.18% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.18% | `python` | `func_clear` | unknown |
| 1.17% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.06% | `python` | `set_table_resize` | miscobj |
| 1.00% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.85% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.85% | `python` | `list_ass_slice_lock_held` | list |
| 0.82% | `python` | `make_range_object` | unknown |
| 0.81% | `python` | `_PyList_BinarySlice` | list |
| 0.79% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.78% | `python` | `gen_dealloc` | memory |
| 0.78% | `python` | `list_slice_lock_held` | list |
| 0.77% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 0.77% | `python` | `list_ass_subscript` | list |
| 0.77% | `python` | `tuple_dealloc` | memory |
| 0.70% | `python` | `_PyObject_Realloc` | memory |
| 0.68% | `python` | `_Py_NewReference` | memory |
| 0.63% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.61% | `python` | `tuple_alloc` | memory |
| 0.60% | `python` | `_PyFunction_SetVersion` | unknown |
| 0.59% | `python` | `PyLong_AsLong` | int |
| 0.58% | `python` | `range_reverse` | miscobj |
| 0.57% | `python` | `func_dealloc` | memory |
| 0.56% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.55% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.54% | `python` | `range_iter` | miscobj |
| 0.53% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.53% | `python` | `PyDict_GetItemRef` | dict |
| 0.47% | `python` | `long_hash` | int |
| 0.47% | `python` | `make_gen` | miscobj |
| 0.46% | `python` | `PyObject_Hash` | dynamic |
| 0.46% | `python` | `_PySet_AddTakeRef` | miscobj |
| 0.45% | `python` | `_Py_dict_lookup` | lookup |
| 0.45% | `python` | `PyCMethod_New` | memory |
| 0.44% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.43% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.39% | `python` | `PyObject_GC_Del` | gc |
| 0.38% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.37% | `python` | `_PyList_Concat` | list |
| 0.36% | `python` | `_PyObject_GC_New` | gc |
| 0.35% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.33% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.32% | `python` | `PyObject_SetItem` | dynamic |
| 0.31% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.29% | `python` | `range_vectorcall` | miscobj |
| 0.27% | `python` | `list_subscript` | list |
| 0.27% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.26% | `python` | `reversed_new_impl` | memory |
| 0.26% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.26% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.26% | `python` | `PySequence_Fast` | dynamic |
| 0.26% | `python` | `PySet_New` | memory |

## pathlib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 5.88% | `[JIT]` | `jit` | jit |
| 4.22% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 3.96% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 3.71% | `python` | `_PyObject_Malloc` | memory |
| 3.68% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 3.34% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.88% | `python` | `_PyObject_Free` | memory |
| 1.95% | `python` | `_Py_Dealloc` | memory |
| 1.87% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 1.65% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 1.59% | `[kernel.kallsyms]` | `ext4_htree_store_dirent` | kernel |
| 1.51% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 1.36% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 1.32% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.19% | `[kernel.kallsyms]` | `half_md4_transform.isra.0` | kernel |
| 1.11% | `[kernel.kallsyms]` | `filldir64` | kernel |
| 1.08% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.01% | `python` | `take_gil` | gil |
| 1.01% | `python` | `ScandirIterator_iternext` | unknown |
| 0.98% | `python` | `initialize_locals` | interpreter |
| 0.89% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.79% | `[kernel.kallsyms]` | `str2hashbuf_signed` | kernel |
| 0.75% | `[kernel.kallsyms]` | `__kmalloc` | kernel |
| 0.70% | `python` | `PyLong_FromLongLong` | int |
| 0.63% | `[kernel.kallsyms]` | `filename_lookup` | kernel |
| 0.62% | `[kernel.kallsyms]` | `apparmor_inode_getattr` | kernel |
| 0.62% | `libc.so.6` | `__GI___readdir64` | libc |
| 0.62% | `python` | `clear_slots` | unknown |
| 0.61% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.61% | `[kernel.kallsyms]` | `inode_permission` | kernel |
| 0.60% | `python` | `structseq_dealloc` | memory |
| 0.58% | `python` | `sre_ucs1_match` | library |
| 0.57% | `[kernel.kallsyms]` | `cp_new_stat` | kernel |
| 0.57% | `[kernel.kallsyms]` | `strncpy_from_user` | kernel |
| 0.56% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.55% | `[kernel.kallsyms]` | `generic_permission` | kernel |
| 0.51% | `libc.so.6` | `_int_malloc` | libc |
| 0.51% | `[kernel.kallsyms]` | `rb_insert_color` | kernel |
| 0.50% | `[kernel.kallsyms]` | `kmem_cache_alloc` | kernel |
| 0.48% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.47% | `python` | `tuple_alloc` | memory |
| 0.47% | `[kernel.kallsyms]` | `ext4_file_getattr` | kernel |
| 0.46% | `python` | `_PyLong_FromMedium` | int |
| 0.46% | `[kernel.kallsyms]` | `__virt_addr_valid` | kernel |
| 0.45% | `[kernel.kallsyms]` | `kfree` | kernel |
| 0.45% | `python` | `_pystat_fromstructstat` | unknown |
| 0.44% | `[kernel.kallsyms]` | `rb_next` | kernel |
| 0.44% | `python` | `find_first_nonascii` | str |
| 0.43% | `python` | `_PyEval_Vector` | interpreter |
| 0.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.42% | `[kernel.kallsyms]` | `security_inode_getattr` | kernel |
| 0.42% | `python` | `_PyJIT_Entry` | compiler |
| 0.42% | `python` | `_Py_NewReference` | memory |
| 0.41% | `python` | `_PyType_GetDict` | dynamic |
| 0.41% | `[kernel.kallsyms]` | `ext4_getattr` | kernel |
| 0.41% | `[kernel.kallsyms]` | `__slab_free` | kernel |
| 0.40% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.40% | `[kernel.kallsyms]` | `slab_update_freelist.isra.0` | kernel |
| 0.40% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.40% | `[kernel.kallsyms]` | `vfs_getattr_nosec` | kernel |
| 0.39% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.39% | `[kernel.kallsyms]` | `do_syscall_64` | kernel |
| 0.39% | `[kernel.kallsyms]` | `vfs_statx` | kernel |
| 0.39% | `python` | `PyFloat_FromDouble` | float |
| 0.38% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.38% | `python` | `PyDict_GetItemRef` | dict |
| 0.38% | `[kernel.kallsyms]` | `map_id_up` | kernel |
| 0.37% | `[kernel.kallsyms]` | `common_perm_cond` | kernel |
| 0.37% | `python` | `path_converter` | unknown |
| 0.36% | `[kernel.kallsyms]` | `set_root` | kernel |
| 0.36% | `[kernel.kallsyms]` | `__ext4fs_dirhash` | kernel |
| 0.36% | `python` | `fill_time` | unknown |
| 0.35% | `python` | `subtype_dealloc` | memory |
| 0.35% | `python` | `PyDict_GetItemWithError` | dict |
| 0.35% | `python` | `long_dealloc` | memory |
| 0.34% | `[kernel.kallsyms]` | `__ext4_check_dir_entry` | kernel |
| 0.33% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.33% | `[kernel.kallsyms]` | `security_inode_permission` | kernel |
| 0.32% | `python` | `PyLong_AsSsize_t` | int |
| 0.32% | `[kernel.kallsyms]` | `step_into` | kernel |
| 0.32% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.31% | `[kernel.kallsyms]` | `__check_heap_object` | kernel |
| 0.31% | `python` | `PyLong_FromLong` | int |
| 0.31% | `[kernel.kallsyms]` | `memchr` | kernel |
| 0.31% | `[kernel.kallsyms]` | `kmem_cache_free` | kernel |
| 0.31% | `python` | `float_dealloc` | memory |
| 0.31% | `[kernel.kallsyms]` | `htree_dirblock_to_tree` | kernel |
| 0.31% | `libc.so.6` | `__GI___fstatat64` | libc |
| 0.30% | `[kernel.kallsyms]` | `from_kuid_munged` | kernel |
| 0.30% | `python` | `PyObject_GC_Del` | gc |
| 0.30% | `python` | `_Py_dict_lookup` | lookup |
| 0.30% | `python` | `tuple_dealloc` | memory |
| 0.30% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.30% | `[kernel.kallsyms]` | `path_lookupat` | kernel |
| 0.29% | `[kernel.kallsyms]` | `_copy_to_user` | kernel |
| 0.29% | `[kernel.kallsyms]` | `lockref_put_return` | kernel |
| 0.29% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.28% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.28% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.28% | `[kernel.kallsyms]` | `dput` | kernel |
| 0.28% | `python` | `drop_gil` | gil |
| 0.28% | `python` | `os_stat` | unknown |
| 0.28% | `[kernel.kallsyms]` | `__do_sys_newfstatat` | kernel |
| 0.28% | `python` | `PyUnicode_New.part.0` | memory |
| 0.27% | `[kernel.kallsyms]` | `call_filldir` | kernel |
| 0.27% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.27% | `python` | `posix_do_stat.isra.0` | unknown |
| 0.26% | `python` | `PyDict_New` | memory |
| 0.26% | `python` | `tp_new_wrapper` | memory |
| 0.26% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.26% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.26% | `python` | `PyStructSequence_SetItem` | unknown |

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
| 29.08% | `[JIT]` | `jit` | jit |
| 6.08% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.21% | `python` | `_Py_dict_lookup` | lookup |
| 3.69% | `python` | `_PyObject_Malloc` | memory |
| 3.59% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.30% | `python` | `_PyObject_Free` | memory |
| 2.25% | `python` | `initialize_locals` | interpreter |
| 2.01% | `python` | `tuple_dealloc` | memory |
| 1.63% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.46% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.43% | `libc.so.6` | `__strlen_avx2` | libc |
| 1.33% | `python` | `PyBuffer_Release` | miscobj |
| 1.28% | `python` | `_Py_Dealloc` | memory |
| 1.26% | `python` | `dict_get` | dict |
| 1.25% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.20% | `python` | `PyBuffer_FillInfo` | miscobj |
| 1.17% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.11% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.04% | `python` | `write_bytes_lock_held` | unknown |
| 0.98% | `python` | `_PyBytes_Concat` | unknown |
| 0.94% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.90% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.84% | `_struct.cpython-316-x86_64-linux-gnu.so` | `pack` | library |
| 0.76% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.75% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.73% | `python` | `PyLong_FromVoidPtr` | int |
| 0.72% | `python` | `_PyTuple_Resize` | tuple |
| 0.71% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.70% | `python` | `unicode_encode` | str |
| 0.68% | `python` | `PyLong_FromSsize_t` | int |
| 0.62% | `python` | `PyDict_GetItemRef` | dict |
| 0.60% | `_struct.cpython-316-x86_64-linux-gnu.so` | `s_pack_internal` | library |
| 0.57% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.57% | `python` | `PySys_Audit` | unknown |
| 0.56% | `python` | `tuple_alloc` | memory |
| 0.55% | `python` | `PyBytes_FromStringAndSize.constprop.0` | str |
| 0.55% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.55% | `python` | `sys_audit_tstate` | unknown |
| 0.53% | `python` | `insertdict` | dict |
| 0.51% | `python` | `builtin_id` | unknown |
| 0.51% | `python` | `long_hash` | int |
| 0.48% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.47% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.44% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.41% | `python` | `dictiter_iternextitem` | dict |
| 0.41% | `python` | `PyObject_Hash` | dynamic |
| 0.38% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.36% | `python` | `PyObject_Size` | dynamic |
| 0.35% | `python` | `_Py_NewReference` | memory |
| 0.35% | `libc.so.6` | `_int_malloc` | libc |
| 0.33% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.33% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.32% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.32% | `python` | `PyDict_Contains` | dict |
| 0.31% | `python` | `PyObject_Malloc` | dynamic |
| 0.30% | `python` | `bytes_buffer_getbuffer` | str |
| 0.30% | `python` | `unicode_encode_utf8` | str |
| 0.30% | `_struct.cpython-316-x86_64-linux-gnu.so` | `np_ubyte` | library |
| 0.29% | `python` | `PyBytesWriter_FinishWithSize` | unknown |
| 0.28% | `python` | `_PyObject_Realloc` | memory |
| 0.28% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.28% | `python` | `find_empty_slot` | dict |
| 0.27% | `python` | `_PyJIT_Entry` | compiler |
| 0.27% | `python` | `long_richcompare` | int |
| 0.26% | `python` | `_PyLong_FromMedium` | int |

## pidigits

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.52% | `python` | `x_divrem` | int |
| 28.16% | `python` | `k_mul` | int |
| 13.54% | `python` | `x_add` | int |
| 6.88% | `python` | `x_sub` | int |
| 2.87% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.66% | `libc.so.6` | `_int_malloc` | libc |
| 0.88% | `[JIT]` | `jit` | jit |
| 0.52% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.41% | `python` | `_PyObject_Free` | memory |
| 0.36% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.26% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.25% | `python` | `long_alloc` | memory |
| 0.25% | `libc.so.6` | `malloc` | libc |

## pprint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.99% | `[JIT]` | `jit` | jit |
| 4.45% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 4.43% | `python` | `_PyObject_Malloc` | memory |
| 3.22% | `python` | `_PyObject_Free` | memory |
| 3.17% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.11% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 2.46% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.22% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.88% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.77% | `python` | `long_to_decimal_string_internal` | int |
| 1.44% | `python` | `_Py_type_getattro_stackref` | unknown |
| 1.42% | `python` | `_Py_Dealloc` | memory |
| 1.42% | `python` | `set_lookkey` | miscobj |
| 1.31% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.23% | `python` | `PyUnicode_Format` | str |
| 1.20% | `python` | `_Py_dict_lookup` | lookup |
| 1.12% | `python` | `PyObject_IsSubclass` | dynamic |
| 0.96% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.94% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.86% | `python` | `tuple_alloc` | memory |
| 0.83% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.72% | `python` | `PyUnicode_New` | memory |
| 0.68% | `python` | `list_sort_impl` | list |
| 0.68% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.67% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.67% | `python` | `_PyObject_Realloc` | memory |
| 0.66% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.64% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.62% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.61% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.60% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.58% | `python` | `_PyStaticType_GetState` | unknown |
| 0.54% | `python` | `PyType_IsSubtype` | dynamic |
| 0.53% | `python` | `initialize_locals` | interpreter |
| 0.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.52% | `python` | `delitem_common` | dynamic |
| 0.52% | `python` | `list_append` | list |
| 0.50% | `python` | `subtype_dealloc` | memory |
| 0.48% | `python` | `tuple_dealloc` | memory |
| 0.46% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.45% | `python` | `builtin_issubclass` | unknown |
| 0.44% | `python` | `_Py_NewReference` | memory |
| 0.44% | `python` | `unicode_dealloc` | memory |
| 0.43% | `python` | `_PyUnicodeWriter_WriteSubstring` | str |
| 0.39% | `python` | `PyList_New.constprop.0` | memory |
| 0.38% | `python` | `recursive_issubclass` | unknown |
| 0.38% | `python` | `insertdict` | dict |
| 0.37% | `python` | `PyUnicode_New.part.0` | memory |
| 0.37% | `python` | `slot_tp_richcompare` | dynamic |
| 0.36% | `python` | `PyCMethod_New` | memory |
| 0.36% | `python` | `_PySet_Contains` | miscobj |
| 0.36% | `python` | `PyObject_Hash` | dynamic |
| 0.35% | `python` | `unicode_repr` | str |
| 0.35% | `python` | `PyThread_get_thread_ident` | threading |
| 0.34% | `python` | `PyObject_Repr` | dynamic |
| 0.32% | `python` | `_PyStolenTuple_Free` | unknown |
| 0.32% | `python` | `_Py_BuildString_StackRefSteal` | unknown |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.31% | `python` | `builtin_getattr` | lookup |
| 0.31% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.30% | `python` | `PyNumber_Remainder` | dynamic |
| 0.29% | `python` | `_PyEval_Vector` | interpreter |
| 0.27% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.27% | `python` | `long_hash` | int |
| 0.26% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.26% | `python` | `clear_slots` | unknown |

## pycparser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.72% | `[JIT]` | `jit` | jit |
| 12.91% | `python` | `sre_ucs1_match` | library |
| 9.04% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.23% | `python` | `gc_collect_main` | gc |
| 2.31% | `python` | `_Py_dict_lookup` | lookup |
| 2.12% | `python` | `_PyObject_Malloc` | memory |
| 2.01% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.55% | `python` | `_PyObject_Free` | memory |
| 1.32% | `python` | `_PyDict_Subscript` | dict |
| 1.27% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.18% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.06% | `python` | `visit_decref` | gc |
| 0.98% | `python` | `_Py_Dealloc` | memory |
| 0.98% | `libc.so.6` | `_int_malloc` | libc |
| 0.83% | `python` | `subtype_traverse` | gc |
| 0.83% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.81% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.81% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.80% | `python` | `pattern_new_match` | memory |
| 0.75% | `python` | `initialize_locals` | interpreter |
| 0.72% | `python` | `list_ass_slice_lock_held` | list |
| 0.72% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.71% | `python` | `_PyJIT_Entry` | compiler |
| 0.70% | `python` | `dict_get` | dict |
| 0.65% | `python` | `visit_reachable` | gc |
| 0.64% | `python` | `sre_ucs1_count` | library |
| 0.63% | `python` | `PySlice_New` | memory |
| 0.59% | `python` | `PyObject_GetItem` | dynamic |
| 0.58% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.58% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.57% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.52% | `libc.so.6` | `malloc` | libc |
| 0.52% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.50% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.50% | `python` | `subtype_dealloc` | memory |
| 0.49% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.47% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.41% | `python` | `list_ass_subscript` | list |
| 0.39% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.39% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.38% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.38% | `python` | `list_subscript` | list |
| 0.37% | `python` | `long_neg_method` | int |
| 0.37% | `python` | `_PyEval_Vector` | interpreter |
| 0.37% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.36% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.34% | `python` | `PyType_IsSubtype` | dynamic |
| 0.32% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.31% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.30% | `python` | `PyNumber_Negative` | dynamic |
| 0.28% | `python` | `PyObject_SetItem` | dynamic |
| 0.28% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.27% | `python` | `list_dealloc` | memory |
| 0.27% | `libc.so.6` | `_int_free` | libc |
| 0.27% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.26% | `python` | `PyObject_IsInstance` | dynamic |
| 0.26% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.26% | `python` | `PyUnicode_Contains` | str |
| 0.26% | `python` | `slot_mp_ass_subscript` | unknown |
| 0.25% | `python` | `PySlice_Unpack` | miscobj |

## pyflate

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.77% | `[JIT]` | `jit` | jit |
| 5.39% | `python` | `list_ass_slice_lock_held` | list |
| 5.18% | `python` | `list_dealloc` | memory |
| 3.21% | `python` | `_PyList_Concat` | list |
| 2.22% | `python` | `list_slice_lock_held` | list |
| 2.16% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.98% | `python` | `_PyCompactLong_Add` | unknown |
| 1.83% | `libc.so.6` | `_int_malloc` | libc |
| 1.79% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.76% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.73% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.71% | `python` | `stringlib_bytes_join` | str |
| 1.69% | `python` | `_PyObject_Free` | memory |
| 1.67% | `python` | `_PyObject_Malloc` | memory |
| 1.38% | `python` | `_Py_Dealloc` | memory |
| 1.38% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.32% | `python` | `bytes_subscript` | str |
| 1.25% | `python` | `long_lshift_method` | int |
| 1.23% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.15% | `python` | `list_sort_impl` | list |
| 1.07% | `python` | `_PyLong_FromMedium` | int |
| 1.03% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.97% | `python` | `PyLong_AsSsize_t` | int |
| 0.89% | `python` | `PyBuffer_Release` | miscobj |
| 0.81% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.78% | `python` | `long_lshift1` | int |
| 0.77% | `python` | `unsafe_long_compare` | unknown |
| 0.75% | `python` | `PyLong_FromSsize_t` | int |
| 0.70% | `python` | `long_rshift` | int |
| 0.68% | `python` | `PyNumber_Lshift` | dynamic |
| 0.66% | `python` | `PySlice_New` | memory |
| 0.60% | `python` | `PyObject_GetItem` | dynamic |
| 0.59% | `python` | `long_dealloc` | memory |
| 0.58% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.56% | `python` | `_Py_NewReference` | memory |
| 0.54% | `python` | `PyList_New.constprop.0` | memory |
| 0.54% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.50% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.49% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.39% | `python` | `PyNumber_Rshift` | dynamic |
| 0.39% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.37% | `libc.so.6` | `malloc` | libc |
| 0.37% | `python` | `long_rshift1` | int |
| 0.36% | `python` | `_PyList_BinarySlice` | list |
| 0.34% | `python` | `enum_next` | miscobj |
| 0.32% | `python` | `gallop_right` | unknown |
| 0.32% | `python` | `gallop_left` | unknown |
| 0.29% | `python` | `PyObject_Size` | dynamic |
| 0.27% | `python` | `PySlice_Unpack` | miscobj |

## pylint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.82% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.86% | `[JIT]` | `jit` | jit |
| 4.05% | `python` | `gc_collect_main` | gc |
| 2.89% | `python` | `_PyObject_Malloc` | memory |
| 2.76% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.75% | `python` | `_PyObject_Free` | memory |
| 1.71% | `python` | `visit_decref` | gc |
| 1.69% | `python` | `visit_reachable` | gc |
| 1.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.58% | `python` | `_Py_dict_lookup` | lookup |
| 1.50% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.27% | `python` | `initialize_locals` | interpreter |
| 0.98% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.97% | `python` | `_Py_Dealloc` | memory |
| 0.85% | `python` | `PyDict_GetItemRef` | dict |
| 0.72% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.71% | `python` | `unicode_repr` | str |
| 0.64% | `python` | `listiter_next` | list |
| 0.62% | `python` | `subtype_traverse` | gc |
| 0.61% | `python` | `tuple_dealloc` | memory |
| 0.58% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.56% | `python` | `dict_traverse` | gc |
| 0.54% | `python` | `insertdict` | dict |
| 0.53% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.52% | `python` | `PyType_IsSubtype` | dynamic |
| 0.51% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.48% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.46% | `python` | `_PyLexer_get_normal` | unknown |
| 0.46% | `python` | `PyObject_SetAttr` | dynamic |
| 0.46% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.45% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.45% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.44% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.44% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.43% | `python` | `partial_vectorcall` | unknown |
| 0.42% | `python` | `_PyPegen_is_memoized` | interpreter |
| 0.41% | `python` | `islice_next` | unknown |
| 0.40% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.39% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.38% | `python` | `tuple_alloc` | memory |
| 0.38% | `python` | `_PyPegen_expect_token` | interpreter |
| 0.37% | `python` | `_PyJIT_Entry` | compiler |
| 0.37% | `python` | `list_traverse` | gc |
| 0.36% | `python` | `sre_ucs1_match` | library |
| 0.35% | `python` | `_PyEval_Vector` | interpreter |
| 0.34% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.31% | `python` | `PyDict_Next` | dict |
| 0.30% | `python` | `_PyObject_GC_New` | gc |
| 0.28% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 0.28% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.27% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.27% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.26% | `python` | `list_dealloc` | memory |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |

## python_startup

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 8.26% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.03% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.39% | `python` | `gc_collect_main` | gc |
| 2.83% | `python` | `_PyObject_Malloc` | memory |
| 2.78% | `python` | `visit_decref` | gc |
| 2.13% | `python` | `visit_reachable` | gc |
| 2.05% | `python` | `_Py_dict_lookup` | lookup |
| 1.83% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.81% | `python` | `r_object` | import |
| 1.50% | `python` | `_PyObject_Free` | memory |
| 1.23% | `python` | `type_ready` | dynamic |
| 1.20% | `python` | `_PyCode_Quicken` | interpreter |
| 1.16% | `python` | `find_name_in_mro` | lookup |
| 1.12% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.01% | `python` | `dict_traverse` | gc |
| 1.00% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.98% | `python` | `siphash13` | str |
| 0.94% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.91% | `python` | `_Py_Dealloc` | memory |
| 0.85% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.73% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.70% | `python` | `tuple_dealloc` | memory |
| 0.70% | `python` | `update_one_slot` | lookup |
| 0.68% | `python` | `insertdict` | dict |
| 0.66% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.62% | `libc.so.6` | `_int_malloc` | libc |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.59% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.58% | `python` | `intern_constants` | str |
| 0.54% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.51% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.49% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.48% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.48% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.47% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.45% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.43% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.43% | `python` | `build_indices_unicode` | dict |
| 0.41% | `python` | `PyUnicode_New.part.0` | memory |
| 0.40% | `python` | `find_first_nonascii` | str |
| 0.39% | `python` | `PyDict_GetItemRef` | dict |
| 0.36% | `python` | `find_empty_slot` | dict |
| 0.35% | `python` | `_PyCode_New` | interpreter |
| 0.35% | `python` | `initialize_locals` | interpreter |
| 0.35% | `python` | `r_long` | import |
| 0.34% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.33% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.33% | `[kernel.kallsyms]` | `__handle_mm_fault` | kernel |
| 0.32% | `python` | `tuple_traverse` | gc |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.32% | `python` | `code_dealloc` | memory |
| 0.32% | `[kernel.kallsyms]` | `next_uptodate_folio` | kernel |
| 0.31% | `python` | `_PyTypeCache_Insert` | unknown |
| 0.31% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.30% | `[kernel.kallsyms]` | `copy_page` | kernel |
| 0.30% | `python` | `tuple_alloc` | memory |
| 0.28% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.28% | `python` | `func_traverse` | gc |
| 0.27% | `libc.so.6` | `malloc` | libc |
| 0.27% | `ld-linux-x86-64.so.2` | `do_lookup_x` | library |
| 0.27% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.27% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.26% | `python` | `PyObject_IS_GC` | gc |
| 0.25% | `python` | `PyDict_Next` | dict |

## python_startup_no_site

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.98% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.51% | `python` | `gc_collect_main` | gc |
| 4.50% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.84% | `python` | `visit_decref` | gc |
| 2.73% | `python` | `_PyObject_Malloc` | memory |
| 2.30% | `python` | `visit_reachable` | gc |
| 2.11% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.79% | `python` | `_Py_dict_lookup` | lookup |
| 1.62% | `python` | `r_object` | import |
| 1.51% | `python` | `_PyObject_Free` | memory |
| 1.50% | `python` | `type_ready` | dynamic |
| 1.18% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.18% | `python` | `siphash13` | str |
| 1.09% | `python` | `find_name_in_mro` | lookup |
| 1.09% | `python` | `_PyCode_Quicken` | interpreter |
| 1.04% | `python` | `dict_traverse` | gc |
| 1.03% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.91% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.85% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.80% | `python` | `_Py_Dealloc` | memory |
| 0.79% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.78% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.77% | `python` | `insertdict` | dict |
| 0.70% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.66% | `libc.so.6` | `_int_malloc` | libc |
| 0.63% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.60% | `python` | `tuple_dealloc` | memory |
| 0.60% | `python` | `build_indices_unicode` | dict |
| 0.59% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.58% | `python` | `intern_constants` | str |
| 0.56% | `python` | `find_first_nonascii` | str |
| 0.55% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.55% | `python` | `update_one_slot` | lookup |
| 0.51% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.50% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.50% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.49% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.46% | `[kernel.kallsyms]` | `next_uptodate_folio` | kernel |
| 0.45% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.45% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.45% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.43% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.43% | `python` | `PyUnicode_New.part.0` | memory |
| 0.39% | `ld-linux-x86-64.so.2` | `do_lookup_x` | library |
| 0.38% | `python` | `find_empty_slot` | dict |
| 0.37% | `[kernel.kallsyms]` | `filemap_map_pages` | kernel |
| 0.35% | `[kernel.kallsyms]` | `__handle_mm_fault` | kernel |
| 0.35% | `[kernel.kallsyms]` | `copy_page` | kernel |
| 0.32% | `python` | `_PyCode_New` | interpreter |
| 0.31% | `python` | `PyDict_GetItemRef` | dict |
| 0.30% | `python` | `r_long` | import |
| 0.30% | `python` | `tuple_traverse` | gc |
| 0.30% | `python` | `code_dealloc` | memory |
| 0.29% | `[kernel.kallsyms]` | `mas_walk` | kernel |
| 0.29% | `python` | `_PyTypeCache_Insert` | unknown |
| 0.28% | `python` | `initialize_locals` | interpreter |
| 0.27% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.27% | `libc.so.6` | `malloc` | libc |
| 0.27% | `python` | `func_traverse` | gc |
| 0.26% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.25% | `python` | `tuple_alloc` | memory |
| 0.25% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |

## raytrace

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 41.22% | `[JIT]` | `jit` | jit |
| 6.78% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.93% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.56% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.89% | `python` | `PyFloat_FromDouble` | float |
| 2.51% | `python` | `_Py_Dealloc` | memory |
| 2.21% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.98% | `python` | `initialize_locals` | interpreter |
| 1.74% | `python` | `_PyObject_Free` | memory |
| 1.68% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 1.51% | `python` | `subtype_dealloc` | memory |
| 1.33% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.20% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.10% | `python` | `_PyType_AllocNoTrack` | memory |
| 1.07% | `python` | `_PyObject_Malloc` | memory |
| 0.96% | `python` | `float_dealloc` | memory |
| 0.86% | `python` | `_Py_NewReference` | memory |
| 0.85% | `python` | `PyType_GenericAlloc` | memory |
| 0.79% | `python` | `PyType_IsSubtype` | dynamic |
| 0.77% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.69% | `python` | `_PyEval_Vector` | interpreter |
| 0.66% | `python` | `PyNumber_Subtract` | dynamic |
| 0.66% | `python` | `float_richcompare` | float |
| 0.62% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.58% | `python` | `_PyJIT_Entry` | compiler |
| 0.57% | `python` | `vectorcall_maybe` | unknown |
| 0.56% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.52% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.44% | `python` | `tuple_dealloc` | memory |
| 0.43% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.40% | `python` | `slot_nb_subtract` | unknown |
| 0.37% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.37% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.35% | `python` | `_PyObject_GC_Link` | gc |
| 0.35% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.35% | `python` | `PyObject_GC_Del` | gc |
| 0.32% | `python` | `compactlong_float_subtract` | unknown |
| 0.32% | `python` | `compactlong_float_guard` | unknown |
| 0.31% | `python` | `tuple_alloc` | memory |
| 0.31% | `python` | `PyObject_RichCompare` | dynamic |
| 0.30% | `python` | `min_max` | unknown |
| 0.27% | `python` | `PyObject_IsTrue` | dynamic |
| 0.26% | `python` | `PyNumber_Multiply` | dynamic |

## regex_compile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.33% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 21.96% | `[JIT]` | `jit` | jit |
| 2.58% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.35% | `python` | `_PyObject_Malloc` | memory |
| 2.14% | `python` | `_Py_Dealloc` | memory |
| 1.70% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.35% | `python` | `_PyObject_Free` | memory |
| 1.12% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.11% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.94% | `python` | `bytearray_ass_subscript_lock_held` | miscobj |
| 0.93% | `python` | `tuple_dealloc` | memory |
| 0.92% | `python` | `tuple_alloc` | memory |
| 0.91% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.80% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.77% | `python` | `_PyJIT_Entry` | compiler |
| 0.72% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.71% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.67% | `python` | `set_lookkey` | miscobj |
| 0.65% | `python` | `long_richcompare` | int |
| 0.65% | `python` | `PyUnicode_Contains` | str |
| 0.64% | `python` | `PyType_IsSubtype` | dynamic |
| 0.61% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.59% | `python` | `PyObject_SetItem` | dynamic |
| 0.58% | `python` | `list_append` | list |
| 0.57% | `python` | `initialize_locals` | interpreter |
| 0.57% | `python` | `_PyLong_FromMedium` | int |
| 0.56% | `python` | `list_dealloc` | memory |
| 0.55% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.53% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.51% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.48% | `python` | `PyLong_FromSsize_t` | int |
| 0.45% | `python` | `_PyUnicode_Equal` | str |
| 0.44% | `python` | `min_max` | unknown |
| 0.44% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.43% | `python` | `PyLong_FromLong` | int |
| 0.42% | `python` | `_Py_NewReference` | memory |
| 0.42% | `python` | `_PyEval_Vector` | interpreter |
| 0.41% | `python` | `make_range_object` | unknown |
| 0.40% | `python` | `_PyCompactLong_Add` | unknown |
| 0.40% | `python` | `_Py_dict_lookup` | lookup |
| 0.40% | `python` | `_PyObject_Realloc` | memory |
| 0.38% | `python` | `PyLong_AsSsize_t` | int |
| 0.37% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.36% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.34% | `python` | `PyList_New.constprop.0` | memory |
| 0.34% | `python` | `bytearray_ass_subscript` | miscobj |
| 0.32% | `python` | `listiter_next` | list |
| 0.32% | `python` | `PySequence_Contains` | dynamic |
| 0.31% | `python` | `PyObject_Size` | dynamic |
| 0.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.31% | `python` | `_validate_inner` | unknown |
| 0.31% | `python` | `long_dealloc` | memory |
| 0.30% | `python` | `enum_next` | miscobj |
| 0.30% | `python` | `gen_dealloc` | memory |
| 0.30% | `python` | `_PySet_Contains` | miscobj |
| 0.29% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.27% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.26% | `python` | `slot_sq_item` | unknown |

## regex_dna

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 59.45% | `python` | `sre_ucs1_match` | library |
| 34.77% | `python` | `sre_search` | library |
| 1.30% | `python` | `pattern_subx` | library |
| 0.99% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.58% | `python` | `stringlib_bytes_join` | str |
| 0.37% | `python` | `_PyObject_Malloc` | memory |
| 0.27% | `python` | `PyBuffer_Release` | miscobj |

## regex_effbot

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 73.67% | `python` | `sre_ucs1_match` | library |
| 17.70% | `python` | `sre_search` | library |
| 3.53% | `python` | `sre_ucs1_count` | library |
| 1.09% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.44% | `python` | `siphash13` | str |
| 0.34% | `python` | `_PyObject_Malloc` | memory |

## regex_v8

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 54.67% | `python` | `sre_ucs1_match` | library |
| 6.87% | `python` | `sre_search` | library |
| 3.95% | `python` | `sre_ucs1_count` | library |
| 2.72% | `python` | `pattern_subx` | library |
| 2.34% | `python` | `_PyObject_Malloc` | memory |
| 2.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.14% | `libc.so.6` | `_int_malloc` | libc |
| 2.03% | `python` | `_PyObject_Free` | memory |
| 1.82% | `[JIT]` | `jit` | jit |
| 1.81% | `python` | `pattern_new_match` | memory |
| 1.61% | `python` | `_sre_SRE_Pattern_search` | library |
| 1.23% | `python` | `sre_category` | library |
| 1.08% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.85% | `python` | `_PyUnicode_IsAlpha` | str |
| 0.83% | `python` | `_PyUnicode_ToLowercase` | str |
| 0.72% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.68% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.59% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.57% | `python` | `PyUnicode_Substring` | str |
| 0.48% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.44% | `python` | `_Py_Dealloc` | memory |
| 0.43% | `libc.so.6` | `malloc` | libc |
| 0.36% | `python` | `_PyObject_Realloc` | memory |
| 0.34% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.32% | `libc.so.6` | `_int_free` | libc |
| 0.31% | `python` | `PyErr_Occurred` | exceptions |
| 0.30% | `python` | `method_vectorcall_FASTCALL_KEYWORDS_METHOD` | calls |
| 0.30% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.30% | `python` | `_Py_dict_lookup` | lookup |
| 0.29% | `libc.so.6` | `cfree@GLIBC_2.2.5` | libc |
| 0.29% | `python` | `_PyUnicode_IsDecimalDigit` | str |
| 0.28% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.27% | `libc.so.6` | `_int_free_maybe_consolidate` | libc |
| 0.26% | `python` | `list_dealloc` | memory |
| 0.26% | `python` | `PyList_New` | memory |

## richards

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 68.16% | `[JIT]` | `jit` | jit |
| 9.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 5.84% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.49% | `python` | `_PyThreadState_PopFrame` | threading |
| 2.18% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.72% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.24% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.05% | `python` | `_PyCompactLong_Add` | unknown |
| 0.98% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.76% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.69% | `python` | `PyObject_IsInstance` | dynamic |
| 0.64% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.61% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.52% | `python` | `_Py_Dealloc` | memory |
| 0.37% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.33% | `python` | `long_div` | int |
| 0.28% | `python` | `long_dealloc` | memory |

## richards_super

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 68.25% | `[JIT]` | `jit` | jit |
| 10.03% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 5.75% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.53% | `python` | `_PyThreadState_PopFrame` | threading |
| 2.41% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.72% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.07% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.90% | `python` | `_PyCompactLong_Add` | unknown |
| 0.64% | `python` | `PyObject_IsInstance` | dynamic |
| 0.62% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.59% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.52% | `python` | `_Py_Dealloc` | memory |
| 0.49% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.34% | `python` | `long_div` | int |
| 0.34% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.34% | `python` | `long_dealloc` | memory |

## scimark

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 33.45% | `[JIT]` | `jit` | jit |
| 5.26% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 5.14% | `array.cpython-316-x86_64-linux-gnu.so` | `array_subscr` | library |
| 4.16% | `python` | `PyFloat_FromDouble` | float |
| 3.12% | `python` | `vgetargs1_impl.constprop.0` | calls |
| 2.54% | `python` | `PyObject_GetItem` | dynamic |
| 2.46% | `python` | `convertitem.constprop.0` | unknown |
| 2.26% | `python` | `_Py_Dealloc` | memory |
| 2.26% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.14% | `python` | `PyLong_AsSsize_t` | int |
| 2.06% | `python` | `PyIndex_Check` | unknown |
| 1.76% | `array.cpython-316-x86_64-linux-gnu.so` | `array_ass_subscr` | library |
| 1.70% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.59% | `python` | `_PyCompactLong_Add` | unknown |
| 1.46% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.44% | `python` | `PyArg_Parse` | calls |
| 1.42% | `python` | `_Py_NewReference` | memory |
| 1.31% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.26% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.25% | `array.cpython-316-x86_64-linux-gnu.so` | `d_getitem` | library |
| 1.23% | `python` | `PyType_GetModuleByDef` | dynamic |
| 1.21% | `array.cpython-316-x86_64-linux-gnu.so` | `d_setitem` | library |
| 1.03% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.01% | `python` | `_PyCompactLong_Multiply` | unknown |
| 0.99% | `python` | `PyLong_FromLong` | int |
| 0.98% | `python` | `float_dealloc` | memory |
| 0.96% | `python` | `PyObject_SetItem` | dynamic |
| 0.69% | `python` | `PyType_IsSubtype` | dynamic |
| 0.66% | `array.cpython-316-x86_64-linux-gnu.so` | `PyNumber_AsSsize_t@plt` | library |
| 0.56% | `python` | `PyFloat_AsDouble` | float |
| 0.56% | `python` | `_PyLong_FromMedium` | int |
| 0.54% | `python` | `tuple_dealloc` | memory |
| 0.52% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.50% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.49% | `python` | `long_dealloc` | memory |
| 0.49% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.48% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.47% | `python` | `object_isinstance` | dynamic |
| 0.45% | `python` | `float_richcompare` | float |
| 0.43% | `array.cpython-316-x86_64-linux-gnu.so` | `PyIndex_Check@plt` | library |
| 0.41% | `python` | `_PyLong_Frexp` | int |
| 0.41% | `array.cpython-316-x86_64-linux-gnu.so` | `PyType_GetModuleByDef@plt` | library |
| 0.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.39% | `python` | `PyObject_IsInstance` | dynamic |
| 0.33% | `python` | `tuple_alloc` | memory |
| 0.33% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.29% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.28% | `array.cpython-316-x86_64-linux-gnu.so` | `PyFloat_FromDouble@plt` | library |
| 0.26% | `python` | `make_range_object` | unknown |

## spectral_norm

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.21% | `[JIT]` | `jit` | jit |
| 10.43% | `python` | `_PyCompactLong_Add` | unknown |
| 4.93% | `python` | `long_div` | int |
| 4.20% | `python` | `_PyCompactLong_Multiply` | unknown |
| 4.01% | `python` | `float_compactlong_true_div` | float |
| 4.00% | `python` | `enum_next` | miscobj |
| 3.04% | `python` | `listiter_next` | list |
| 2.93% | `python` | `_PyLong_ExactDealloc` | memory |
| 2.64% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.40% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.23% | `python` | `PyNumber_FloorDivide` | dynamic |
| 2.01% | `python` | `_Py_NewReference` | memory |
| 1.97% | `python` | `PyFloat_FromDouble` | float |
| 1.51% | `python` | `_PyLong_FromMedium` | int |
| 1.39% | `python` | `PyLong_FromSsize_t` | int |
| 1.15% | `python` | `PyLong_FromLong` | int |
| 0.97% | `python` | `nonzero_float_compactlong_guard` | unknown |
| 0.91% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.81% | `python` | `_Py_Dealloc` | memory |
| 0.78% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.54% | `python` | `float_dealloc` | memory |
| 0.37% | `python` | `float_compactlong_guard` | float |
| 0.29% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |

## sphinx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 11.94% | `[JIT]` | `jit` | jit |
| 11.71% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.14% | `python` | `sre_ucs1_match` | library |
| 4.76% | `python` | `gc_collect_main` | gc |
| 3.71% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.50% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.40% | `python` | `_PyObject_Malloc` | memory |
| 2.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.67% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.56% | `python` | `_PyObject_Free` | memory |
| 1.37% | `python` | `visit_decref` | gc |
| 1.25% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.16% | `python` | `_Py_dict_lookup` | lookup |
| 1.08% | `python` | `PyType_IsSubtype` | dynamic |
| 1.06% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.99% | `python` | `initialize_locals` | interpreter |
| 0.99% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.97% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.94% | `python` | `_Py_Dealloc` | memory |
| 0.91% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `save.constprop.0` | library |
| 0.83% | `python` | `visit_reachable` | gc |
| 0.70% | `python` | `siphash13` | str |
| 0.66% | `python` | `sre_search` | library |
| 0.61% | `python` | `PyUnicode_Format` | str |
| 0.59% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.57% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.55% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.53% | `python` | `_PyJIT_Entry` | compiler |
| 0.48% | `python` | `object_isinstance` | dynamic |
| 0.46% | `python` | `PyDict_GetItemRef` | dict |
| 0.46% | `python` | `gen_dealloc` | memory |
| 0.45% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `PyObject_IsInstance` | dynamic |
| 0.43% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `save_dict` | library |
| 0.43% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.41% | `python` | `tuple_alloc` | memory |
| 0.40% | `python` | `sre_ucs2_match` | library |
| 0.37% | `python` | `dict_traverse` | gc |
| 0.36% | `python` | `_PyEval_Vector` | interpreter |
| 0.33% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 0.32% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.31% | `python` | `getset_get` | dynamic |
| 0.31% | `python` | `pattern_subx` | library |
| 0.31% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.30% | `libc.so.6` | `_int_malloc` | libc |
| 0.30% | `python` | `replace` | str |
| 0.30% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.29% | `python` | `sre_category` | library |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `_PyDict_Subscript` | dict |
| 0.27% | `python` | `_PyObject_Realloc` | memory |
| 0.26% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.26% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.26% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 0.26% | `python` | `PyObject_SetAttr` | dynamic |
| 0.25% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.25% | `python` | `unicode_repr` | str |

## sqlalchemy_declarative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.30% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.95% | `[JIT]` | `jit` | jit |
| 4.26% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.87% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.57% | `python` | `_PyObject_Malloc` | memory |
| 2.38% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.64% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.55% | `python` | `initialize_locals` | interpreter |
| 1.55% | `python` | `_PyObject_Free` | memory |
| 1.54% | `python` | `_Py_Dealloc` | memory |
| 1.48% | `python` | `tuple_dealloc` | memory |
| 1.35% | `python` | `_Py_dict_lookup` | lookup |
| 1.18% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.15% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.90% | `python` | `PyObject_SetAttr` | dynamic |
| 0.89% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.82% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.80% | `python` | `tuple_alloc` | memory |
| 0.75% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.74% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.71% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.63% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.58% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.58% | `python` | `PyType_IsSubtype` | dynamic |
| 0.56% | `python` | `subtype_dealloc` | memory |
| 0.55% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.53% | `python` | `PyObject_IsTrue` | dynamic |
| 0.51% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.48% | `python` | `dict_dealloc` | memory |
| 0.48% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.47% | `python` | `set_lookkey` | miscobj |
| 0.47% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.46% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.45% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.43% | `python` | `list_dealloc` | memory |
| 0.42% | `python` | `take_gil` | gil |
| 0.40% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.40% | `python` | `_PyEval_Vector` | interpreter |
| 0.40% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.38% | `python` | `_PyDict_Subscript` | dict |
| 0.37% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.36% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.34% | `python` | `PyDict_GetItemRef` | dict |
| 0.33% | `python` | `set_dealloc` | memory |
| 0.32% | `python` | `insertdict` | dict |
| 0.31% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.30% | `python` | `PyObject_Hash` | dynamic |
| 0.30% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.29% | `python` | `set_add_entry_takeref` | miscobj |
| 0.28% | `python` | `_PyObject_GC_New` | gc |
| 0.28% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.28% | `python` | `tuple_hash` | tuple |
| 0.27% | `python` | `_PyUnicode_InternMortal` | str |
| 0.27% | `python` | `PyObject_GC_Del` | gc |
| 0.26% | `python` | `_PyObject_Realloc` | memory |

## sqlalchemy_imperative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.36% | `[JIT]` | `jit` | jit |
| 4.61% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.10% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 2.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.83% | `python` | `_PyObject_Malloc` | memory |
| 1.82% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.51% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.41% | `python` | `initialize_locals` | interpreter |
| 1.20% | `python` | `_Py_Dealloc` | memory |
| 1.15% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.13% | `python` | `_PyObject_Free` | memory |
| 1.11% | `python` | `_Py_dict_lookup` | lookup |
| 0.85% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.84% | `python` | `tuple_dealloc` | memory |
| 0.81% | `python` | `PyObject_SetAttr` | dynamic |
| 0.79% | `python` | `gc_collect_main` | gc |
| 0.77% | `python` | `tuple_alloc` | memory |
| 0.66% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.63% | `python` | `PyObject_IsTrue` | dynamic |
| 0.62% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.60% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.57% | `python` | `subtype_dealloc` | memory |
| 0.57% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.56% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.56% | `python` | `PyType_IsSubtype` | dynamic |
| 0.56% | `python` | `dict_dealloc` | memory |
| 0.55% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.55% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.44% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.44% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.43% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.41% | `python` | `_PyJIT_Entry` | compiler |
| 0.41% | `python` | `PyDict_GetItemRef` | dict |
| 0.39% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.37% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.37% | `python` | `insertdict` | dict |
| 0.33% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.31% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.30% | `libsqlite3.so.0.8.6` | `sqlite3Parser` | library |
| 0.30% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.29% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.29% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `long_to_decimal_string_internal` | int |
| 0.27% | `python` | `subtype_dict` | unknown |
| 0.27% | `python` | `list_dealloc` | memory |
| 0.27% | `python` | `PyObject_Hash` | dynamic |
| 0.26% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.26% | `python` | `insert_to_emptydict` | dict |
| 0.25% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |

## sqlglot_v2

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.45% | `[JIT]` | `jit` | jit |
| 15.66% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.11% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.51% | `python` | `_PyObject_Malloc` | memory |
| 3.27% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.94% | `python` | `_PyObject_Free` | memory |
| 2.67% | `python` | `PyType_IsSubtype` | dynamic |
| 2.31% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.28% | `python` | `_Py_Dealloc` | memory |
| 2.12% | `python` | `dictiter_iternextitem` | dict |
| 1.74% | `python` | `PyObject_IsInstance` | dynamic |
| 1.74% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.34% | `python` | `tuple_dealloc` | memory |
| 1.32% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.23% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.10% | `python` | `_PyJIT_Entry` | compiler |
| 1.10% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.06% | `python` | `object_isinstance` | dynamic |
| 0.96% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.92% | `python` | `initialize_locals` | interpreter |
| 0.90% | `python` | `call_special_method` | unknown |
| 0.90% | `python` | `tuple_alloc` | memory |
| 0.86% | `python` | `_PyObject_GC_New` | gc |
| 0.85% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.77% | `python` | `getset_get` | dynamic |
| 0.70% | `python` | `gen_dealloc` | memory |
| 0.68% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.66% | `python` | `_Py_dict_lookup` | lookup |
| 0.64% | `python` | `insert_to_emptydict` | dict |
| 0.59% | `python` | `_PyObject_Calloc` | memory |
| 0.59% | `python` | `_PyObject_LookupSpecialMethod` | dynamic |
| 0.54% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.52% | `python` | `PyObject_GC_Del` | gc |
| 0.49% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.49% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.49% | `python` | `method_vectorcall_O` | calls |
| 0.48% | `python` | `PyList_New` | memory |
| 0.46% | `python` | `_Py_NewReference` | memory |
| 0.42% | `python` | `func_clear` | unknown |
| 0.40% | `python` | `tuple_hash` | tuple |
| 0.39% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.39% | `python` | `object_recursive_isinstance` | dynamic |
| 0.39% | `python` | `list_dealloc` | memory |
| 0.36% | `python` | `PyObject_IsTrue` | dynamic |
| 0.35% | `python` | `_PyEval_Vector` | interpreter |
| 0.35% | `python` | `PyObject_Hash` | dynamic |
| 0.35% | `python` | `make_gen` | miscobj |
| 0.34% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.34% | `python` | `dictitems_iter` | unknown |
| 0.33% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.32% | `python` | `dictiter_dealloc` | memory |
| 0.31% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.30% | `python` | `dict_get` | dict |
| 0.30% | `python` | `new_dict.constprop.0` | dict |
| 0.30% | `python` | `dict_items` | dict |
| 0.30% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.28% | `python` | `dictview_dealloc` | memory |
| 0.27% | `python` | `set_add_entry_takeref` | miscobj |
| 0.27% | `python` | `_PyObject_GC_Link` | gc |
| 0.27% | `python` | `PyMem_Calloc` | memory |
| 0.26% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.26% | `python` | `_PyList_FromStackRefStealOnSuccess` | list |
| 0.26% | `python` | `PyDict_GetItemRef` | dict |
| 0.26% | `python` | `siphash13` | str |
| 0.25% | `python` | `type___instancecheck__` | dynamic |

## sqlglot_v2_optimize

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.93% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 15.91% | `[JIT]` | `jit` | jit |
| 5.22% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.47% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 3.12% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `python` | `PyType_IsSubtype` | dynamic |
| 2.64% | `python` | `_PyObject_Free` | memory |
| 2.20% | `python` | `dictiter_iternextitem` | dict |
| 2.16% | `python` | `_Py_Dealloc` | memory |
| 2.05% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.86% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.75% | `python` | `PyObject_IsInstance` | dynamic |
| 1.33% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.29% | `python` | `tuple_dealloc` | memory |
| 1.24% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.08% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.98% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.98% | `python` | `call_special_method` | unknown |
| 0.95% | `python` | `object_isinstance` | dynamic |
| 0.83% | `python` | `tuple_alloc` | memory |
| 0.82% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.78% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.77% | `python` | `_PyObject_GC_New` | gc |
| 0.74% | `python` | `getset_get` | dynamic |
| 0.72% | `python` | `_Py_dict_lookup` | lookup |
| 0.67% | `python` | `initialize_locals` | interpreter |
| 0.65% | `python` | `_PyObject_LookupSpecialMethod` | dynamic |
| 0.59% | `python` | `_PyObject_Calloc` | memory |
| 0.58% | `python` | `_PyJIT_Entry` | compiler |
| 0.57% | `python` | `method_vectorcall_O` | calls |
| 0.53% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.53% | `python` | `dict_get` | dict |
| 0.51% | `python` | `object_recursive_isinstance` | dynamic |
| 0.50% | `python` | `tuple_hash` | tuple |
| 0.48% | `python` | `insert_to_emptydict` | dict |
| 0.46% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.46% | `python` | `list_dealloc` | memory |
| 0.46% | `python` | `PyMember_GetOne` | lookup |
| 0.44% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.43% | `python` | `insertdict` | dict |
| 0.42% | `python` | `_Py_NewReference` | memory |
| 0.41% | `python` | `PyList_New` | memory |
| 0.40% | `python` | `PyObject_Hash` | dynamic |
| 0.37% | `python` | `gen_dealloc` | memory |
| 0.36% | `python` | `func_clear` | unknown |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `python` | `_PyType_GetDict` | dynamic |
| 0.34% | `python` | `PyObject_IsTrue` | dynamic |
| 0.34% | `python` | `PyObject_GC_Del` | gc |
| 0.34% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.32% | `python` | `gc_collect_main` | gc |
| 0.30% | `python` | `type___instancecheck__` | dynamic |
| 0.30% | `python` | `siphash13` | str |
| 0.29% | `python` | `PyMem_Calloc` | memory |
| 0.29% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.28% | `python` | `dictiter_dealloc` | memory |
| 0.28% | `python` | `_PyEval_Vector` | interpreter |
| 0.27% | `python` | `object_get_class` | dynamic |
| 0.27% | `python` | `dict_items` | dict |
| 0.26% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.26% | `python` | `_PyTuple_FromPairSteal` | tuple |
| 0.26% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.26% | `python` | `dictitems_iter` | unknown |
| 0.25% | `python` | `func_dealloc` | memory |
| 0.25% | `python` | `_PyList_FromStackRefStealOnSuccess` | list |

## sqlglot_v2_parse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.83% | `[JIT]` | `jit` | jit |
| 14.32% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.62% | `python` | `initialize_locals` | interpreter |
| 2.28% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.22% | `python` | `_PyObject_Malloc` | memory |
| 2.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.94% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.88% | `python` | `gc_collect_main` | gc |
| 1.86% | `python` | `_Py_dict_lookup` | lookup |
| 1.59% | `python` | `_PyObject_Free` | memory |
| 1.55% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.27% | `python` | `PyObject_RichCompare` | dynamic |
| 1.05% | `python` | `_Py_Dealloc` | memory |
| 0.98% | `python` | `_PyCompactLong_Add` | unknown |
| 0.86% | `python` | `PyType_IsSubtype` | dynamic |
| 0.81% | `python` | `dictiter_iternextitem` | dict |
| 0.77% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.76% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.75% | `python` | `_PyJIT_Entry` | compiler |
| 0.75% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.71% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.69% | `python` | `dict_get` | dict |
| 0.66% | `python` | `visit_decref` | gc |
| 0.60% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.50% | `python` | `_PyEval_Vector` | interpreter |
| 0.49% | `python` | `PyDict_Contains` | dict |
| 0.46% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.45% | `python` | `clear_slots` | unknown |
| 0.42% | `python` | `insert_to_emptydict` | dict |
| 0.41% | `python` | `subtype_traverse` | gc |
| 0.40% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.39% | `python` | `object_richcompare` | dynamic |
| 0.36% | `python` | `PyObject_SetAttr` | dynamic |
| 0.36% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.36% | `python` | `PyObject_IsTrue` | dynamic |
| 0.36% | `python` | `set_lookkey` | miscobj |
| 0.35% | `python` | `insertdict` | dict |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.34% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.34% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.33% | `python` | `PyLong_FromSsize_t` | int |
| 0.32% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.32% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `tuple_dealloc` | memory |
| 0.30% | `python` | `slot_tp_hash` | unknown |
| 0.27% | `python` | `dict_traverse` | gc |
| 0.26% | `python` | `dictiter_iternextkey` | dict |
| 0.26% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.25% | `python` | `unicode_strip` | str |

## sqlglot_v2_transpile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.20% | `[JIT]` | `jit` | jit |
| 15.23% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.52% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.71% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.52% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.51% | `python` | `initialize_locals` | interpreter |
| 2.40% | `python` | `_PyObject_Malloc` | memory |
| 2.10% | `python` | `_Py_dict_lookup` | lookup |
| 1.74% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.66% | `python` | `_PyObject_Free` | memory |
| 1.63% | `python` | `gc_collect_main` | gc |
| 1.40% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.19% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.12% | `python` | `_Py_Dealloc` | memory |
| 1.00% | `python` | `PyType_IsSubtype` | dynamic |
| 0.97% | `python` | `PyObject_RichCompare` | dynamic |
| 0.89% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.86% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.83% | `python` | `dict_get` | dict |
| 0.73% | `python` | `_PyCompactLong_Add` | unknown |
| 0.71% | `python` | `_PyJIT_Entry` | compiler |
| 0.66% | `python` | `dictiter_iternextitem` | dict |
| 0.59% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.49% | `python` | `PyObject_IsTrue` | dynamic |
| 0.49% | `python` | `visit_decref` | gc |
| 0.44% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.43% | `python` | `_PyEval_Vector` | interpreter |
| 0.42% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.41% | `python` | `PyObject_SetAttr` | dynamic |
| 0.41% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.41% | `python` | `PyDict_Contains` | dict |
| 0.40% | `python` | `PyObject_IsInstance` | dynamic |
| 0.40% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.38% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.38% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.37% | `python` | `clear_slots` | unknown |
| 0.36% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.36% | `python` | `insert_to_emptydict` | dict |
| 0.34% | `python` | `_PyObject_GC_New` | gc |
| 0.33% | `python` | `subtype_traverse` | gc |
| 0.32% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.31% | `python` | `tuple_dealloc` | memory |
| 0.31% | `python` | `set_lookkey` | miscobj |
| 0.30% | `python` | `object_richcompare` | dynamic |
| 0.30% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.29% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.29% | `python` | `slot_tp_hash` | unknown |
| 0.29% | `python` | `insertdict` | dict |
| 0.28% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.27% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.27% | `python` | `PyLong_FromSsize_t` | int |
| 0.26% | `python` | `PyObject_GC_UnTrack` | gc |

## sqlite_synth

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.59% | `python` | `take_gil` | gil |
| 7.00% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 5.75% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 4.18% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 4.13% | `[JIT]` | `jit` | jit |
| 2.97% | `libm.so.6` | `__cos_fma` | library |
| 2.25% | `python` | `_Py_Dealloc` | memory |
| 2.21% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_query_execute` | library |
| 2.02% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.84% | `python` | `drop_gil` | gil |
| 1.74% | `python` | `_PyObject_Free` | memory |
| 1.71% | `libc.so.6` | `pthread_cond_signal@@GLIBC_2.3.2` | libc |
| 1.41% | `python` | `_PyObject_Malloc` | memory |
| 1.25% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_fetch_one_row.constprop.0` | library |
| 1.09% | `libsqlite3.so.0.8.6` | `sqlite3BtreeInsert` | library |
| 1.04% | `python` | `_PyThreadState_Detach` | threading |
| 0.99% | `python` | `_PyThreadState_Attach` | threading |
| 0.99% | `python` | `_PyThreadState_MustExit` | threading |
| 0.98% | `python` | `long_to_decimal_string_internal` | int |
| 0.94% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.93% | `python` | `PyEval_SaveThread` | interpreter |
| 0.83% | `python` | `tuple_dealloc` | memory |
| 0.71% | `python` | `PyFloat_FromDouble` | float |
| 0.64% | `python` | `PyFloat_AsDouble` | float |
| 0.63% | `libsqlite3.so.0.8.6` | `sqlite3_step` | library |
| 0.63% | `python` | `_Py_IsMainThread` | unknown |
| 0.62% | `python` | `_Py_NewReference` | memory |
| 0.60% | `python` | `PyList_New` | memory |
| 0.60% | `python` | `tuple_alloc` | memory |
| 0.60% | `python` | `PyThread_get_thread_ident` | threading |
| 0.56% | `libsqlite3.so.0.8.6` | `sqlite3VdbeHalt` | library |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.53% | `python` | `PyTuple_New` | memory |
| 0.49% | `libsqlite3.so.0.8.6` | `sqlite3_column_type` | library |
| 0.48% | `python` | `_PyLong_FromMedium` | int |
| 0.47% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.47% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.45% | `python` | `pthread_mutex_unlock@plt` | unknown |
| 0.45% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.44% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `bind_param` | library |
| 0.43% | `math.cpython-316-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.43% | `python` | `_Py_dict_lookup` | lookup |
| 0.42% | `python` | `float_dealloc` | memory |
| 0.40% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `pysqlite_cursor_init` | library |
| 0.39% | `libsqlite3.so.0.8.6` | `sqlite3_mutex_enter` | library |
| 0.38% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `cursor_clear` | library |
| 0.37% | `libsqlite3.so.0.8.6` | `0x00000000000bd72a` | library |
| 0.36% | `python` | `long_float` | int |
| 0.36% | `python` | `pthread_mutex_lock@plt` | unknown |
| 0.35% | `python` | `long_dealloc` | memory |
| 0.35% | `python` | `PyType_IsSubtype` | dynamic |
| 0.35% | `python` | `list_dealloc` | memory |
| 0.35% | `libsqlite3.so.0.8.6` | `sqlite3BtreeNext` | library |
| 0.34% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.34% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `func_callback` | library |
| 0.34% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_build_py_params` | library |
| 0.34% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.33% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `step_callback` | library |
| 0.33% | `libsqlite3.so.0.8.6` | `sqlite3BtreeBeginTrans` | library |
| 0.33% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.33% | `python` | `PyObject_CallObject` | dynamic |
| 0.33% | `libsqlite3.so.0.8.6` | `sqlite3DbMallocRawNN` | library |
| 0.32% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.31% | `python` | `_PyDict_GetItemRef_KnownHash_LockHeld` | dict |
| 0.31% | `python` | `_PyCompactLong_Add` | unknown |
| 0.31% | `python` | `_PyEval_Vector` | interpreter |
| 0.31% | `libsqlite3.so.0.8.6` | `sqlite3_reset` | library |
| 0.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.29% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.29% | `python` | `PyUnicode_New` | memory |
| 0.28% | `python` | `list_iter` | list |
| 0.27% | `libsqlite3.so.0.8.6` | `sqlite3_column_double` | library |
| 0.27% | `libc.so.6` | `__errno_location` | libc |
| 0.27% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.26% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemGrow` | library |
| 0.25% | `libsqlite3.so.0.8.6` | `sqlite3BtreeCloseCursor` | library |
| 0.25% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `pysqlite_check_thread` | library |
| 0.25% | `python` | `unicode_decode_utf8.part.0` | str |

## sympy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.15% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 13.03% | `[JIT]` | `jit` | jit |
| 4.54% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.02% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.41% | `python` | `_Py_dict_lookup` | lookup |
| 2.07% | `python` | `_PyObject_Malloc` | memory |
| 2.01% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.77% | `python` | `initialize_locals` | interpreter |
| 1.68% | `python` | `_Py_Dealloc` | memory |
| 1.51% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.47% | `python` | `_PyObject_Free` | memory |
| 1.45% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.44% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.43% | `python` | `tuple_dealloc` | memory |
| 1.20% | `python` | `PyType_IsSubtype` | dynamic |
| 0.97% | `python` | `tuple_alloc` | memory |
| 0.91% | `python` | `PyDict_GetItemRef` | dict |
| 0.90% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.87% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.84% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.79% | `python` | `_PyJIT_Entry` | compiler |
| 0.73% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.66% | `python` | `insertdict` | dict |
| 0.65% | `python` | `PyUnicode_RichCompare` | str |
| 0.60% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.59% | `python` | `_PyEval_Vector` | interpreter |
| 0.58% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.57% | `python` | `dictiter_iternextitem` | dict |
| 0.57% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.56% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.55% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.52% | `python` | `setiter_iternext` | miscobj |
| 0.47% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.46% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.45% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.41% | `python` | `slot_tp_richcompare` | dynamic |
| 0.39% | `python` | `dict_merge` | dict |
| 0.38% | `python` | `dict_dealloc` | memory |
| 0.37% | `python` | `PyObject_IsInstance` | dynamic |
| 0.36% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.35% | `python` | `insert_to_emptydict` | dict |
| 0.34% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.34% | `python` | `PyObject_IsTrue` | dynamic |
| 0.33% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.33% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.32% | `python` | `PyObject_Hash` | dynamic |
| 0.32% | `python` | `PyDict_Next` | dict |
| 0.32% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.30% | `python` | `new_dict.constprop.0` | dict |
| 0.29% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.28% | `python` | `list_sort_impl` | list |
| 0.26% | `python` | `method_vectorcall_O` | calls |
| 0.26% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.25% | `python` | `PyList_New.constprop.0` | memory |

## telco

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.40% | `[JIT]` | `jit` | jit |
| 13.70% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.00% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.92% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.77% | `python` | `initialize_locals` | interpreter |
| 1.99% | `python` | `_PyObject_Malloc` | memory |
| 1.95% | `python` | `_PyObject_Free` | memory |
| 1.93% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.72% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.24% | `python` | `_Py_Dealloc` | memory |
| 1.14% | `python` | `PyLong_FromString` | int |
| 1.12% | `python` | `_PyEval_Vector` | interpreter |
| 1.09% | `python` | `long_to_decimal_string_internal` | int |
| 1.06% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.06% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.03% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.97% | `python` | `subtype_dealloc` | memory |
| 0.91% | `python` | `clear_slots` | unknown |
| 0.90% | `python` | `_PyJIT_Entry` | compiler |
| 0.86% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.69% | `python` | `PyObject_IsTrue` | dynamic |
| 0.69% | `python` | `_Py_dict_lookup` | lookup |
| 0.67% | `python` | `_PyCompactLong_Add` | unknown |
| 0.64% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.61% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.60% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.60% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.59% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.59% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.58% | `python` | `slot_nb_bool` | unknown |
| 0.53% | `python` | `PyObject_IsInstance` | dynamic |
| 0.52% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.52% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.51% | `python` | `PyNumber_Long` | dynamic |
| 0.49% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.46% | `python` | `tuple_alloc` | memory |
| 0.43% | `python` | `sre_ucs1_match` | library |
| 0.42% | `python` | `PyObject_Size` | dynamic |
| 0.41% | `python` | `object_isinstance` | dynamic |
| 0.40% | `libc.so.6` | `_int_malloc` | libc |
| 0.40% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.40% | `python` | `PyType_IsSubtype` | dynamic |
| 0.39% | `python` | `_PyUnicode_Equal` | str |
| 0.38% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.38% | `python` | `tp_new_wrapper` | memory |
| 0.37% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.36% | `python` | `PyLong_FromSsize_t` | int |
| 0.36% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.35% | `python` | `min_max` | unknown |
| 0.33% | `python` | `tuple_dealloc` | memory |
| 0.33% | `python` | `long_pow` | int |
| 0.33% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.32% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.32% | `python` | `PyUnicode_New` | memory |
| 0.32% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.32% | `python` | `PyType_GenericAlloc` | memory |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.28% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.28% | `python` | `PyObject_GC_Del` | gc |
| 0.27% | `python` | `long_dealloc` | memory |
| 0.26% | `python` | `PyUnicode_Concat` | str |
| 0.26% | `python` | `PyObject_Str` | dynamic |

## thrift

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.93% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.57% | `[JIT]` | `jit` | jit |
| 3.03% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.92% | `python` | `initialize_locals` | interpreter |
| 2.68% | `python` | `_PyObject_Malloc` | memory |
| 2.49% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.42% | `apache::thrift::py::TType,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*,` | unknown |
| 2.35% | `python` | `_PyObject_Free` | memory |
| 2.06% | `python` | `_Py_Dealloc` | memory |
| 1.64% | `python` | `_Py_dict_lookup` | lookup |
| 1.58% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.57% | `python` | `insert_to_emptydict` | dict |
| 1.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.51% | `python` | `PyDict_GetItemRef` | dict |
| 1.28% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.28% | `python` | `insertdict` | dict |
| 1.19% | `python` | `PyLong_AsLong` | int |
| 1.17% | `python` | `subtype_dealloc` | memory |
| 1.12% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.09% | `_object*)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType,` | unknown |
| 1.08% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.95% | `python` | `PyDict_Next` | dict |
| 0.92% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.88% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.83% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.82% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.80% | `python` | `PyTuple_Size` | tuple |
| 0.79% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.76% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.75% | `_object*,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readStruct(_object*,` | unknown |
| 0.70% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `python` | `tuple_dealloc` | memory |
| 0.67% | `python` | `unicode_from_format` | str |
| 0.66% | `python` | `dict_dealloc` | memory |
| 0.66% | `python` | `_PyEval_Vector` | interpreter |
| 0.65% | `python` | `PyDict_New` | memory |
| 0.64% | `python` | `PyObject_Call` | dynamic |
| 0.62% | `python` | `PyUnicode_RichCompare` | str |
| 0.61% | `python` | `PyDict_SetItem` | dict |
| 0.61% | `int)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readBytes(char**,` | unknown |
| 0.61% | `python` | `_PyJIT_Entry` | compiler |
| 0.57% | `python` | `slot_tp_init` | unknown |
| 0.55% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.53% | `short&)` | `apache::thrift::py::BinaryProtocol::readFieldBegin(apache::thrift::py::TType&,` | unknown |
| 0.52% | `python` | `dict_merge` | dict |
| 0.52% | `python` | `_PyDict_Next` | dict |
| 0.49% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.48% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.48% | `python` | `_PyDict_FromItems` | dict |
| 0.48% | `python` | `PyObject_GetAttr` | dynamic |
| 0.47% | `python` | `PyType_GenericAlloc` | memory |
| 0.47% | `python` | `vgetargs1_impl` | calls |
| 0.47% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.46% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.44% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.43% | `python` | `_PyObject_Calloc` | memory |
| 0.43% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.42% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.42% | `python` | `find_first_nonascii` | str |
| 0.41% | `libc.so.6` | `malloc` | libc |
| 0.40% | `python` | `_PyObject_VectorcallDictTstate` | dynamic |
| 0.39% | `python` | `tuple_alloc` | memory |
| 0.38% | `python` | `PyList_New` | memory |
| 0.36% | `python` | `_Py_NewReference` | memory |
| 0.36% | `python` | `convertitem.constprop.0` | unknown |
| 0.36% | `python` | `find_empty_slot` | dict |
| 0.35% | `_object*)` | `apache::thrift::py::parse_struct_item_spec(apache::thrift::py::StructItemSpec*,` | unknown |
| 0.34% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.34% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.32% | `python` | `_PyType_GetDict` | dynamic |
| 0.31% | `python` | `object_vacall` | dynamic |
| 0.30% | `python` | `PyImport_ImportModuleLevelObject` | import |
| 0.29% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.29% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.29% | `fastbinary.cpython-316-x86_64-linux-gnu.so` | `decode_binary` | library |
| 0.28% | `_object*)` | `apache::thrift::py::parse_struct_args(apache::thrift::py::StructTypeArgs*,` | unknown |
| 0.27% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.27% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.26% | `python` | `new_dict.constprop.0` | dict |
| 0.26% | `python` | `_Py_module_getattro_impl` | unknown |
| 0.26% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.26% | `python` | `_PyObject_VectorcallPrepend` | dynamic |
| 0.25% | `python` | `unicode_fromformat_write_utf8` | str |
| 0.25% | `python` | `_PyObject_Realloc` | memory |
| 0.25% | `python` | `PyObject_GC_Del` | gc |

## tomli_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 34.04% | `[JIT]` | `jit` | jit |
| 5.37% | `python` | `set_lookkey` | miscobj |
| 4.90% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.40% | `python` | `_PyUnicode_Equal` | str |
| 3.31% | `python` | `_PyCompactLong_Add` | unknown |
| 3.18% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.95% | `python` | `_PySet_Contains` | miscobj |
| 1.84% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.80% | `python` | `_Py_dict_lookup` | lookup |
| 1.64% | `python` | `_PyObject_Malloc` | memory |
| 1.61% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.27% | `python` | `_PyIncrementalNewlineDecoder_decode` | memory |
| 1.24% | `python` | `PyObject_Hash` | dynamic |
| 1.24% | `python` | `_PyDict_Subscript` | dict |
| 1.10% | `python` | `_PyObject_Free` | memory |
| 0.94% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.90% | `python` | `_Py_Dealloc` | memory |
| 0.82% | `python` | `_PyUnicode_FromUCS4.part.0` | str |
| 0.77% | `python` | `PyObject_GetItem` | dynamic |
| 0.77% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.73% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.72% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.71% | `python` | `sre_ucs4_match` | library |
| 0.70% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.69% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.65% | `python` | `_Py_NewReference` | memory |
| 0.61% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.59% | `python` | `tuple_alloc` | memory |
| 0.56% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.49% | `python` | `unicode_hash` | str |
| 0.45% | `python` | `replace` | str |
| 0.44% | `python` | `PyType_IsSubtype` | dynamic |
| 0.41% | `python` | `initialize_locals` | interpreter |
| 0.41% | `python` | `PyDict_GetItemRef` | dict |
| 0.40% | `python` | `tuple_dealloc` | memory |
| 0.40% | `python` | `PyDict_Contains` | dict |
| 0.38% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.36% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.36% | `python` | `unicode_decode_utf8_impl` | str |
| 0.34% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `func_clear` | unknown |
| 0.33% | `python` | `make_range_object` | unknown |
| 0.33% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.31% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.31% | `python` | `insertdict` | dict |
| 0.30% | `python` | `memcmp@plt` | unknown |
| 0.29% | `python` | `siphash13` | str |
| 0.29% | `python` | `_PyEval_UnpackIndices` | interpreter |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.27% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.26% | `python` | `tuple_subscript` | tuple |

## tornado_http

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.07% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.89% | `[JIT]` | `jit` | jit |
| 2.12% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.94% | `python` | `_PyObject_Malloc` | memory |
| 1.85% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.64% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.20% | `python` | `_Py_Dealloc` | memory |
| 1.18% | `python` | `initialize_locals` | interpreter |
| 1.16% | `python` | `_PyObject_Free` | memory |
| 0.95% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.95% | `python` | `sre_ucs1_match` | library |
| 0.73% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.72% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.69% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.68% | `python` | `_Py_dict_lookup` | lookup |
| 0.62% | `python` | `tuple_dealloc` | memory |
| 0.57% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.52% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.52% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.52% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.51% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.49% | `[nf_tables]` | `nft_do_chain` | unknown |
| 0.47% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.42% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.41% | `python` | `tuple_alloc` | memory |
| 0.40% | `python` | `_PyJIT_Entry` | compiler |
| 0.40% | `python` | `PyType_IsSubtype` | dynamic |
| 0.39% | `libc.so.6` | `_int_malloc` | libc |
| 0.37% | `python` | `_PyEval_Vector` | interpreter |
| 0.34% | `python` | `sre_ucs1_count` | library |
| 0.32% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.32% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.32% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.32% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.29% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.29% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.28% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `PyObject_IsTrue` | dynamic |
| 0.26% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.26% | `libc.so.6` | `malloc` | libc |
| 0.25% | `python` | `PyDict_GetItemRef` | dict |

## typing_runtime_protocols

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.67% | `[JIT]` | `jit` | jit |
| 5.80% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.49% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.40% | `python` | `_PyObject_Malloc` | memory |
| 2.54% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 2.49% | `python` | `_Py_dict_lookup` | lookup |
| 2.48% | `python` | `_PyObject_Free` | memory |
| 2.33% | `python` | `weakref___new__` | memory |
| 2.31% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 2.24% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.18% | `python` | `_Py_Dealloc` | memory |
| 2.14% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.78% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.69% | `python` | `tuple_dealloc` | memory |
| 1.60% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.57% | `python` | `_Py_type_getattro_stackref` | unknown |
| 1.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.50% | `python` | `tuple_alloc` | memory |
| 1.44% | `python` | `PyArg_UnpackTuple` | calls |
| 1.41% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.17% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.15% | `python` | `PyObject_Vectorcall` | dynamic |
| 1.12% | `python` | `set_lookkey` | miscobj |
| 0.93% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.92% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.79% | `python` | `_PyObject_GC_New` | gc |
| 0.77% | `python` | `initialize_locals` | interpreter |
| 0.72% | `python` | `getset_get` | dynamic |
| 0.67% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.64% | `python` | `PyType_IsSubtype` | dynamic |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.61% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.60% | `python` | `frame_dealloc` | memory |
| 0.58% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.56% | `python` | `setiter_iternext` | miscobj |
| 0.53% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.53% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.52% | `python` | `PyObject_Hash` | dynamic |
| 0.52% | `python` | `PyList_New.constprop.0` | memory |
| 0.51% | `python` | `PyWeakref_NewRef` | memory |
| 0.51% | `python` | `type_call` | dynamic |
| 0.50% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.48% | `python` | `PyObject_GC_Del` | gc |
| 0.47% | `python` | `wrap_descr_get` | unknown |
| 0.47% | `python` | `_Py_NewReference` | memory |
| 0.45% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.45% | `python` | `PyMapping_Check` | dynamic |
| 0.44% | `python` | `wrapperdescr_call` | unknown |
| 0.43% | `python` | `object_richcompare` | dynamic |
| 0.42% | `python` | `weakref_richcompare` | miscobj |
| 0.41% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.39% | `python` | `builtin_getattr` | lookup |
| 0.39% | `python` | `PyDictProxy_New` | memory |
| 0.38% | `python` | `PyTraceBack_Here` | exceptions |
| 0.38% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.37% | `python` | `_Py_type_getattro` | lookup |
| 0.35% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.33% | `python` | `mappingproxy_dealloc` | memory |
| 0.32% | `python` | `AttributeError_dealloc` | memory |
| 0.32% | `python` | `tuple_hash` | tuple |
| 0.32% | `python` | `dict_dealloc` | memory |
| 0.32% | `python` | `_PyEval_Vector` | interpreter |
| 0.31% | `python` | `_PyObject_GC_Link` | gc |
| 0.31% | `python` | `_PyStaticType_GetState` | unknown |
| 0.30% | `python` | `weakref___init__` | miscobj |
| 0.30% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.29% | `python` | `infinite_lru_cache_wrapper` | unknown |
| 0.29% | `python` | `tuple_richcompare` | tuple |
| 0.29% | `python` | `PyDict_Contains` | dict |
| 0.28% | `python` | `_PyDict_GetItemRef_KnownHash` | dict |
| 0.27% | `python` | `_PyObject_Realloc` | memory |
| 0.26% | `python` | `weakref_hash` | miscobj |
| 0.26% | `python` | `new_dict.constprop.0` | dict |
| 0.25% | `python` | `_PyJIT_Entry` | compiler |

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
| 41.30% | `[JIT]` | `jit` | jit |
| 3.57% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.32% | `python` | `_Py_dict_lookup` | lookup |
| 3.04% | `python` | `PyObject_IsTrue` | dynamic |
| 2.98% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.82% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 2.60% | `python` | `_PyObject_Malloc` | memory |
| 2.59% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 1.89% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.75% | `python` | `_io_BytesIO_read` | unknown |
| 1.62% | `python` | `_Py_convert_optional_to_ssize_t` | unknown |
| 1.52% | `python` | `PyObject_GetItem` | dynamic |
| 1.51% | `python` | `_PyObject_Free` | memory |
| 1.46% | `python` | `_PyDict_Subscript` | dict |
| 1.28% | `python` | `bytes_subscript` | str |
| 1.21% | `python` | `insertdict` | dict |
| 1.05% | `python` | `PyObject_IsInstance` | dynamic |
| 1.03% | `python` | `PyUnicode_Decode` | str |
| 1.02% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.96% | `python` | `find_first_nonascii` | str |
| 0.94% | `python` | `PyLong_FromSsize_t` | int |
| 0.89% | `python` | `PyLong_AsSsize_t` | int |
| 0.83% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.67% | `python` | `unicode_vectorcall` | str |
| 0.60% | `python` | `object_recursive_isinstance` | dynamic |
| 0.56% | `python` | `_Py_Dealloc` | memory |
| 0.55% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.55% | `python` | `list_append` | list |
| 0.53% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.51% | `python` | `PyObject_Size` | dynamic |
| 0.51% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.49% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.48% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.47% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.45% | `python` | `list_subscript` | list |
| 0.44% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.43% | `python` | `PyObject_Hash` | dynamic |
| 0.41% | `python` | `long_hash` | int |
| 0.39% | `python` | `siphash13` | str |
| 0.34% | `python` | `PyObject_SetItem` | dynamic |
| 0.32% | `python` | `_PyObject_Realloc` | memory |
| 0.30% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.30% | `python` | `PyUnicode_New.part.0` | memory |
| 0.28% | `python` | `find_empty_slot` | dict |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.27% | `python` | `bytes_length` | str |
| 0.26% | `python` | `initialize_locals` | interpreter |
| 0.26% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.26% | `python` | `_PyEvalFramePushAndInit` | interpreter |

## xdsl

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.12% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 10.06% | `[JIT]` | `jit` | jit |
| 4.17% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.34% | `python` | `_PyObject_Malloc` | memory |
| 2.44% | `python` | `gc_collect_main` | gc |
| 2.01% | `python` | `_PyObject_Free` | memory |
| 1.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.79% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.79% | `python` | `_Py_Dealloc` | memory |
| 1.39% | `python` | `_Py_dict_lookup` | lookup |
| 1.32% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.14% | `python` | `tuple_dealloc` | memory |
| 1.09% | `python` | `initialize_locals` | interpreter |
| 1.05% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.01% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.98% | `python` | `PyDict_GetItemRef` | dict |
| 0.98% | `python` | `PyObject_SetAttr` | dynamic |
| 0.94% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.84% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.80% | `python` | `_PyJIT_Entry` | compiler |
| 0.79% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.75% | `python` | `visit_decref` | gc |
| 0.74% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.73% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.70% | `python` | `unicode_from_format` | str |
| 0.70% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.69% | `python` | `tuple_alloc` | memory |
| 0.63% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.62% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.55% | `python` | `set_lookkey` | miscobj |
| 0.54% | `python` | `_PyEval_Vector` | interpreter |
| 0.54% | `python` | `visit_reachable` | gc |
| 0.53% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.53% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.53% | `python` | `PyType_IsSubtype` | dynamic |
| 0.50% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.45% | `python` | `dict_traverse` | gc |
| 0.43% | `python` | `subtype_traverse` | gc |
| 0.42% | `python` | `subtype_dealloc` | memory |
| 0.39% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.36% | `python` | `PyType_GenericAlloc` | memory |
| 0.36% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.35% | `python` | `PyObject_GC_Del` | gc |
| 0.32% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.32% | `python` | `_Py_NewReference` | memory |
| 0.31% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.31% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.30% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.30% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.29% | `python` | `PyObject_GetIter` | dynamic |
| 0.29% | `python` | `PyWeakref_NewRef` | memory |
| 0.28% | `python` | `_PyObject_Realloc` | memory |
| 0.28% | `python` | `_PyUnicode_InternMortal` | str |
| 0.28% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.28% | `python` | `zip_next` | unknown |
| 0.27% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.25% | `python` | `tuple_iter` | tuple |
| 0.25% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.25% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.25% | `python` | `PyObject_GetOptionalAttr` | dynamic |

## xml_etree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 9.11% | `[JIT]` | `jit` | jit |
| 6.63% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.40% | `python` | `_PyObject_Malloc` | memory |
| 3.07% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.91% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_contentTok` | library |
| 2.83% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_updatePosition` | library |
| 2.82% | `python` | `_PyObject_Free` | memory |
| 2.56% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.39% | `python` | `gc_collect_main` | gc |
| 1.72% | `python` | `visit_decref` | gc |
| 1.69% | `python` | `visit_reachable` | gc |
| 1.63% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `doContent` | library |
| 1.61% | `python` | `_Py_Dealloc` | memory |
| 1.56% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `accountingDiffTolerated.part.0` | library |
| 1.45% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `sip24_update.isra.0` | library |
| 1.34% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.33% | `python` | `_Py_dict_lookup` | lookup |
| 1.30% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_nameLength` | library |
| 1.10% | `python` | `find_first_nonascii` | str |
| 1.05% | `python` | `_io_TextIOWrapper_write` | unknown |
| 0.91% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.88% | `python` | `PyUnicode_Contains` | str |
| 0.85% | `python` | `initialize_locals` | interpreter |
| 0.84% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.79% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_end_handler` | library |
| 0.78% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_getAtts` | library |
| 0.78% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `treebuilder_handle_start` | library |
| 0.76% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_gc_traverse` | library |
| 0.76% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `lookupWithLength` | library |
| 0.74% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.74% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `sip24_final` | library |
| 0.74% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `elementiter_next` | library |
| 0.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.71% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.67% | `python` | `PyUnicode_New.part.0` | memory |
| 0.67% | `python` | `getset_get` | dynamic |
| 0.66% | `python` | `tuple_dealloc` | memory |
| 0.66% | `python` | `siphash13` | str |
| 0.64% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.61% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.61% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `storeAtts` | library |
| 0.56% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.55% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.53% | `python` | `_PyEval_Vector` | interpreter |
| 0.50% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.47% | `python` | `_PyJIT_Entry` | compiler |
| 0.47% | `python` | `_PyObject_GC_New` | gc |
| 0.47% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_dealloc` | library |
| 0.45% | `python` | `_PyType_GetDict` | dynamic |
| 0.45% | `python` | `PyType_IsSubtype` | dynamic |
| 0.44% | `libc.so.6` | `__strncmp_avx2` | libc |
| 0.43% | `python` | `_Py_NewReference` | memory |
| 0.43% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.41% | `python` | `PyObject_IsTrue` | dynamic |
| 0.41% | `python` | `list_dealloc` | memory |
| 0.41% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `makeuniversal` | library |
| 0.40% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.40% | `python` | `PyList_Append` | list |
| 0.39% | `python` | `PyUnicode_Concat` | str |
| 0.38% | `python` | `long_to_decimal_string_internal` | int |
| 0.38% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.35% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `utf8_toUtf8` | library |
| 0.35% | `python` | `PyUnicode_Format` | str |
| 0.35% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.35% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.35% | `python` | `object_isinstance` | dynamic |
| 0.34% | `python` | `vgetargs1_impl` | calls |
| 0.34% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.34% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_start_handler` | library |
| 0.32% | `python` | `unicode_dealloc` | memory |
| 0.32% | `python` | `slot_tp_iternext` | unknown |
| 0.31% | `python` | `tuple_alloc` | memory |
| 0.31% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_getitem` | library |
| 0.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.30% | `python` | `PyObject_IsInstance` | dynamic |
| 0.29% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_data_handler` | library |
| 0.29% | `python` | `PyObject_GC_Del` | gc |
| 0.29% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `create_new_element.isra.0` | library |
| 0.29% | `python` | `_PyTuple_FromPair` | tuple |
| 0.29% | `python` | `PyList_New` | memory |
| 0.28% | `python` | `PyObject_GetAttr` | dynamic |
| 0.28% | `python` | `_PyObject_GC_Link` | gc |
| 0.27% | `python` | `stringlib__two_way` | str |
| 0.27% | `python` | `PyObject_Malloc` | dynamic |
| 0.26% | `python` | `_PyObject_Realloc` | memory |


## Categories

### jit

17.12% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 17.12% | [JIT] | jit |

### memory

11.31% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.14% | python | _PyObject_Malloc |
| 1.69% | python | _PyObject_Free |
| 1.42% | python | _Py_Dealloc |
| 0.73% | python | tuple_dealloc |
| 0.66% | python | list_dealloc |
| 0.53% | python | tuple_alloc |
| 0.37% | python | _Py_NewReference |
| 0.25% | python | PyList_New.constprop.0 |
| 0.22% | python | _PyObject_Realloc |
| 0.22% | python | _PyType_AllocNoTrack |
| 0.15% | python | subtype_dealloc |
| 0.15% | python | PyTuple_New |
| 0.13% | python | dict_dealloc |
| 0.13% | python | PyType_GenericAlloc |
| 0.13% | python | gen_dealloc |
| 0.12% | python | PyUnicode_New.part.0 |
| 0.09% | python | PyList_New |
| 0.09% | python | unicode_dealloc |
| 0.09% | python | PyCMethod_New |
| 0.08% | python | long_dealloc |
| 0.08% | python | _PyObject_Calloc |
| 0.08% | python | listiter_dealloc |
| 0.08% | python | zip_new |
| 0.08% | python | PyDict_New |
| 0.07% | python | PyMethod_New |
| 0.07% | python | PyUnicode_New |
| 0.07% | python | PyFunction_NewWithQualName |
| 0.06% | python | PySlice_New |
| 0.06% | python | _PyLong_ExactDealloc |
| 0.06% | python | float_dealloc |
| 0.06% | python | _PyIncrementalNewlineDecoder_decode |
| 0.06% | python | _PyFloat_ExactDealloc |
| 0.05% | python | set_dealloc |
| 0.05% | python | method_dealloc |
| 0.05% | python | pattern_new_match |
| 0.05% | python | PyObject_CallFinalizerFromDealloc |
| 0.05% | python | long_alloc |
| 0.04% | python | func_dealloc |
| 0.04% | python | PyMem_Calloc |
| 0.04% | python | meth_dealloc |
| 0.04% | python | context_tp_dealloc |
| 0.04% | python | memcpy@plt |
| 0.04% | python | zip_dealloc |
| 0.04% | python | PyMem_Free |
| 0.03% | python | allocate_from_new_pool |
| 0.03% | python | slice_dealloc |
| 0.03% | python | memset@plt |
| 0.03% | python | PyMem_Realloc |
| 0.02% | python | frame_dealloc |
| 0.02% | python | PyMem_Malloc |
| 0.02% | python | object_new |
| 0.02% | python | tp_new_wrapper |
| 0.02% | python | object_dealloc |
| 0.02% | python | cell_dealloc |
| 0.02% | python | async_gen_asend_dealloc |
| 0.02% | python | StopIteration_dealloc |
| 0.02% | python | dictiter_dealloc |
| 0.02% | python | _PyAsyncGenValueWrapperNew |
| 0.01% | python | async_gen_wrapped_val_dealloc |
| 0.01% | python | weakref___new__ |
| 0.01% | python | range_dealloc |
| 0.01% | python | dictview_dealloc |
| 0.01% | python | BaseException_dealloc |
| 0.01% | python | PyCell_New |
| 0.01% | python | BaseException_new |
| 0.01% | python | _PyUnicode_ExactDealloc |
| 0.01% | python | match_dealloc |
| 0.01% | python | tb_dealloc |
| 0.01% | python | _PyMem_RawMalloc |
| 0.01% | python | tupleiter_dealloc |
| 0.01% | python | slot_tp_new |
| 0.01% | python | unicode_new |
| 0.01% | python | PyWeakref_NewRef |
| 0.00% | python | code_dealloc |
| 0.00% | python | AttributeError_dealloc |
| 0.00% | python | _Py_NewReferenceNoTotal |
| 0.00% | python | future_new_iter |
| 0.00% | python | PyObject_Realloc |
| 0.00% | python | structseq_dealloc |
| 0.00% | python | _PyMem_RawFree |
| 0.00% | python | rangeiter_dealloc |
| 0.00% | python | PyFunction_New |
| 0.00% | python | type_new |
| 0.00% | python | reversed_new_impl |
| 0.00% | python | setiter_dealloc |
| 0.00% | python | partial_new |
| 0.00% | python | TaskStepMethWrapper_dealloc |
| 0.00% | python | TaskObj_dealloc |

### interpreter

10.90% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 6.82% | python | _PyEval_EvalFrameDefault |
| 1.47% | python | _PyFrame_ClearExceptCode |
| 0.73% | python | initialize_locals |
| 0.66% | python | _PyEval_FrameClearAndPop |
| 0.50% | python | _PyEvalFramePushAndInit |
| 0.29% | python | _PyEval_Vector |
| 0.10% | python | _PyEval_SliceIndex |
| 0.04% | python | _PyFrame_Traverse |
| 0.04% | python | call_instrumentation_vector.part.0.isra.0 |
| 0.04% | python | _PyStack_UnpackDict |
| 0.02% | python | _PyEval_UnpackIndices |
| 0.02% | python | _Py_call_instrumentation_line |
| 0.02% | python | _PyCode_Quicken |
| 0.02% | python | _PyCode_CheckLineNumber |
| 0.02% | python | _PyEval_GetIter |
| 0.01% | python | _PyEvalFramePushAndInit_Ex |
| 0.01% | python | _PyEval_MonitorRaise |
| 0.01% | python | _PyEval_GetAwaitable |
| 0.01% | python | _PyEval_SliceIndexNotNone |
| 0.01% | python | _PyFrame_New_NoTrack |
| 0.01% | python | _PyFrame_MakeAndSetFrameObject |
| 0.01% | python | PyEval_SaveThread |
| 0.01% | python | _PyCode_New |
| 0.00% | python | _PyPegen_is_memoized |
| 0.00% | python | _PyEval_GetANext |
| 0.00% | python | _PyEval_EnsureBuiltins |
| 0.00% | python | _PyPegen_expect_token |
| 0.00% | python | _PyCode_GetCode |
| 0.00% | python | _PyEval_ImportName |
| 0.00% | python | PyEval_EvalCode |
| 0.00% | python | PyEval_GetFrame |
| 0.00% | python | _PyEval_LoadGlobalStackRef |

### unknown

8.80% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.39% | python | _PyTypeCache_Lookup |
| 0.90% | [unknown] | 0xffffffff939cb32a |
| 0.51% | python | _PyType_LookupStackRefAndVersion |
| 0.45% | python | _PyCompactLong_Add |
| 0.34% | python | _Py_VectorCall_StackRefSteal |
| 0.29% | python | _Py_BuiltinCallFast_StackRef |
| 0.19% | [unknown] | 0xffffffff939cac57 |
| 0.19% | python | _PyCompactLong_Subtract |
| 0.15% | python | zip_next |
| 0.14% | python | _Py_type_getattro_stackref |
| 0.10% | python | lookup_method_ex.constprop.0 |
| 0.09% | python | _PyCallMethodDescriptorFast_StackRef |
| 0.09% | python | _PyRunRemoteDebugger |
| 0.09% | python | _Py_bytes_upper |
| 0.09% | python | clear_slots |
| 0.08% | python | slot_mp_ass_subscript |
| 0.08% | python | convertitem.constprop.0 |
| 0.08% | python | _PyStaticType_GetState |
| 0.07% | python | wrapperdescr_call |
| 0.06% | python | _PyMember_GetOffset |
| 0.06% | python | func_clear |
| 0.06% | python | _PyCompactLong_Multiply |
| 0.06% | python | make_range_object |
| 0.05% | python | PyIndex_Check |
| 0.05% | python | _PyForIter_VirtualIteratorNext |
| 0.05% | python | builtin_sum |
| 0.05% | python | _Py_BuildMap_StackRefSteal |
| 0.05% | python | _Py_IsMainThread |
| 0.05% | python | _Py_CallBuiltinClass_StackRef |
| 0.04% | python | PyBytesWriter_Create |
| 0.04% | python | _Py_BuiltinCallFastWithKeywords_StackRef |
| 0.04% | python | _Py_VectorCallInstrumentation_StackRefSteal |
| 0.04% | python | wrap_objobjargproc |
| 0.04% | python | _PyCallMethodDescriptorFastWithKeywords_StackRef |
| 0.03% | python | _PyAsyncGenASend_Send |
| 0.03% | python | memcmp@plt |
| 0.03% | python | _Py_BuildString_StackRefSteal |
| 0.03% | python | _PyStolenTuple_Free |
| 0.03% | python | min_max |
| 0.03% | python | PyBytesWriter_FinishWithPointer |
| 0.03% | python | _PySuper_LookupDescr |
| 0.03% | python | store_instance_attr_lock_held |
| 0.03% | python | _Py_LoadAttr_StackRefSteal |
| 0.03% | python | get_exception_handler.isra.0 |
| 0.03% | python | builtin_issubclass |
| 0.02% | python | vgetargskeywords_impl.constprop.0 |
| 0.02% | python | _Py_MakeCoro |
| 0.02% | python | _PyInterpreterState_GetConfig |
| 0.02% | python | recursive_issubclass |
| 0.02% | [unknown] | 0xffffffff93c001c6 |
| 0.02% | python | context_run |
| 0.02% | python | build_indices_generic |
| 0.02% | python | Py_HashBuffer |
| 0.02% | python | sys_audit_tstate |
| 0.02% | python | TaskObj_clear |
| 0.02% | python | TaskStepMethWrapper_call |
| 0.02% | python | pthread_self@plt |
| 0.02% | python | slot_tp_init |
| 0.02% | python | task_step_impl |
| 0.02% | python | _Py_strhex_impl |
| 0.02% | python | _io_TextIOWrapper_write |
| 0.02% | python | PySys_Audit |
| 0.02% | python | call_special_method |
| 0.02% | python | _PyInterpreterState_Main |
| 0.02% | python | unsafe_long_compare |
| 0.02% | python | pysiphash |
| 0.01% | python | gen_finalize |
| 0.01% | python | clone_combined_dict_keys |
| 0.01% | python | _asyncio_Task___init__ |
| 0.01% | python | PyContext_CopyCurrent |
| 0.01% | python | builtin_id |
| 0.01% | [unknown] | 0xffffffff92ce5d2b |
| 0.01% | python | _asyncio_future_discard_from_awaited_by |
| 0.01% | python | map_next |
| 0.01% | python | vectorcall_maybe |
| 0.01% | python | wrapperdescr_get |
| 0.01% | python | maybe_small_long |
| 0.01% | python | supercheck |
| 0.01% | python | future_schedule_callbacks |
| 0.01% | python | _PyCoro_GetAwaitableIter |
| 0.01% | python | builtin_hasattr |
| 0.01% | python | bounded_lru_cache_wrapper |
| 0.01% | python | _PyContext_Exit |
| 0.01% | python | unsafe_tuple_compare |
| 0.01% | [unknown] | 0xffffffff93c00151 |
| 0.01% | python | _Py_bytes_contains |
| 0.01% | python | _PyFunction_SetVersion |
| 0.01% | python | task_wakeup |
| 0.01% | python | any_find_slice |
| 0.01% | python | insert_split_key |
| 0.01% | python | compactlongs_guard |
| 0.01% | [unknown] | 0xffffffff93c0010f |
| 0.01% | python | slot_tp_hash |
| 0.01% | python | do_mkvalue |
| 0.01% | python | _PyContext_Enter |
| 0.01% | python | PyType_GetModule |
| 0.01% | python | charmaptranslate_lookup |
| 0.01% | [unknown] | 0xffffffff93c011d3 |
| 0.01% | python | findchar |
| 0.01% | [unknown] | 0xffffffff92c57dd9 |
| 0.01% | python | tailmatch |
| 0.01% | [unknown] | 0xffffffff92c532de |
| 0.01% | python | _PyIter_Send |
| 0.01% | python | slot_sq_contains |
| 0.01% | python | FutureObj_clear |
| 0.01% | python | slot_nb_bool |
| 0.01% | python | _Py_module_getattro_impl |
| 0.01% | python | dictitems_iter |
| 0.01% | apache::thrift::py::TType, | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*, |
| 0.01% | python | lru_cache_make_key |
| 0.01% | python | unsafe_object_compare |
| 0.01% | python | partial_vectorcall |
| 0.01% | python | binary_op1 |
| 0.01% | python | strlen@plt |
| 0.01% | python | _PyOptimizer_Optimize |
| 0.01% | [unknown] | 0xffffffff93c0009d |
| 0.01% | python | builtin_sorted |
| 0.01% | python | slot_sq_length |
| 0.01% | [unknown] | 0xffffffff93c001bd |
| 0.01% | python | task_call_step_soon |
| 0.01% | python | PyBytesWriter_FinishWithSize |
| 0.01% | python | _PyJIT |
| 0.01% | python | malloc@plt |
| 0.01% | python | merge_from_seq2_lock_held |
| 0.01% | python | _Py_convert_optional_to_ssize_t |
| 0.01% | python | slot_tp_iternext |
| 0.01% | python | compactlongs_and |
| 0.01% | python | _abc__abc_instancecheck |
| 0.01% | python | _Py_Specialize_LoadAttr |
| 0.01% | python | asciilib_default_find |
| 0.01% | python | mro_implementation_unlocked |
| 0.01% | python | _asyncio_Future_add_done_callback |
| 0.01% | python | call_soon |
| 0.01% | [unknown] | 0xffffffff93c0128c |
| 0.01% | python | PyTime_AsSecondsDouble |
| 0.01% | python | _io_BytesIO_read |
| 0.01% | [vdso] | 0x0000000000000b00 |
| 0.01% | python | match_getslice_by_index |
| 0.01% | python | PyBytesWriter_GetData |
| 0.01% | python | merge_at |
| 0.01% | python | gallop_right |
| 0.01% | python | make_dict_from_instance_attributes |
| 0.01% | python | func_descr_get |
| 0.01% | python | _Py_slot_tp_getattr_hook |
| 0.01% | python | listreviter_next |
| 0.00% | python | gallop_left |
| 0.00% | python | _PyJit_translate_single_bytecode_to_trace |
| 0.00% | python | slot_sq_item |
| 0.00% | python | _PyBytes_Resize |
| 0.00% | python | setitem_take2_lock_held |
| 0.00% | [unknown] | 0xffffffff93c01631 |
| 0.00% | [unknown] | 0xffffffff92866fc0 |
| 0.00% | python | _PyTypeCache_Insert |
| 0.00% | python | getset_set |
| 0.00% | python | subtype_clear |
| 0.00% | python | nonzero_float_compactlong_guard |
| 0.00% | python | byteswriter_create |
| 0.00% | python | _asyncio_future_add_to_awaited_by |
| 0.00% | [unknown] | 0xffffffff93c011a9 |
| 0.00% | python | hashtable_unicode_hash |
| 0.00% | python | _PyLexer_get_normal |
| 0.00% | [unknown] | 0xffffffff92c57678 |
| 0.00% | python | property_descr_get |
| 0.00% | python | slot_nb_add |
| 0.00% | python | memmove@plt |
| 0.00% | [unknown] | 0xffffffff93a44c0e |
| 0.00% | python | iter_iternext |
| 0.00% | python | PyCallable_Check |
| 0.00% | python | ScandirIterator_iternext |
| 0.00% | python | slot_tp_iter |
| 0.00% | python | _Py_bytes_lower |
| 0.00% | python | future_add_done_callback |
| 0.00% | python | free@plt |
| 0.00% | python | va_build_value |
| 0.00% | python | copy_lock_held_untracked |
| 0.00% | python | match_group |
| 0.00% | python | _PyBytes_Concat |
| 0.00% | [unknown] | 0xffffffff929df75e |
| 0.00% | python | builtin_repr |
| 0.00% | python | do_raise |
| 0.00% | [unknown] | 0xffffffff936e9148 |
| 0.00% | [unknown] | 0xffffffff929a4ca7 |
| 0.00% | python | _Py_BuiltinCallFastWithKeywords_StackRefSteal |
| 0.00% | python | match_getindex |
| 0.00% | python | richcmp_eq |
| 0.00% | [unknown] | 0xffffffff92c54aac |
| 0.00% | python | member_set |
| 0.00% | _object*) | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType, |
| 0.00% | python | subtype_dict |
| 0.00% | python | strchr@plt |
| 0.00% | python | _asyncio_Future___init__ |
| 0.00% | python | __errno_location@plt |
| 0.00% | [unknown] | 0xffffffff92c54d84 |
| 0.00% | python | _Py_call_instrumentation_arg |
| 0.00% | python | pthread_mutex_unlock@plt |
| 0.00% | python | memchr@plt |
| 0.00% | python | _textiowrapper_writeflush |
| 0.00% | [unknown] | 0xffffffff936f3c9e |
| 0.00% | python | memrchr@plt |
| 0.00% | python | vgetargskeywords.constprop.0 |
| 0.00% | python | _Py_Specialize_Call |
| 0.00% | python | task_step |
| 0.00% | [unknown] | 0xffffffff93c01618 |
| 0.00% | python | write_str |
| 0.00% | python | int_bit_length |
| 0.00% | [unknown] | 0xffffffff93c0125b |
| 0.00% | [unknown] | 0xffffffff92ce5d79 |
| 0.00% | [kvm] | pvclock_gtod_notify |
| 0.00% | python | _PyFunction_FromConstructor |
| 0.00% | python | chain_next |
| 0.00% | python | write_bytes_lock_held |
| 0.00% | [unknown] | 0xffffffff92c25c73 |
| 0.00% | python | import_ensure_initialized |
| 0.00% | python | slot_tp_call |
| 0.00% | python | gen_close |
| 0.00% | python | _Py_uop_analyze_and_optimize |
| 0.00% | python | hashtable_unicode_compare |
| 0.00% | python | compactlong_float_guard |
| 0.00% | python | slot_nb_subtract |
| 0.00% | python | countformat |
| 0.00% | python | _Py_call_instrumentation |
| 0.00% | python | pthread_mutex_lock@plt |
| 0.00% | [unknown] | 0xffffffff939cb1a6 |
| 0.00% | python | analyze_descriptor_load.constprop.0 |
| 0.00% | python | slot_nb_multiply |

### library

8.64% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.78% | python | sre_ucs1_match |
| 0.45% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_ascii85 |
| 0.44% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base85 |
| 0.37% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base64 |
| 0.31% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base32 |
| 0.28% | python | sre_search |
| 0.26% | _pickle.cpython-315-x86_64-linux-gnu.so | save.constprop.0 |
| 0.25% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base32 |
| 0.25% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base64 |
| 0.21% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_hex_impl.isra.0 |
| 0.19% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_ascii85 |
| 0.14% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base85 |
| 0.12% | array.cpython-316-x86_64-linux-gnu.so | array_subscr |
| 0.12% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write |
| 0.11% | _json.cpython-316-x86_64-linux-gnu.so | scanstring_unicode |
| 0.11% | _pickle.cpython-315-x86_64-linux-gnu.so | save_dict |
| 0.11% | _pickle.cpython-315-x86_64-linux-gnu.so | save_long |
| 0.10% | _pickle.cpython-315-x86_64-linux-gnu.so | load |
| 0.09% | python | sre_ucs1_count |
| 0.07% | _pickle.cpython-315-x86_64-linux-gnu.so | save_list |
| 0.06% | _pickle.cpython-315-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.06% | python | _sre_SRE_Pattern_prefixmatch |
| 0.06% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write.constprop.0 |
| 0.06% | libz.so.1.3 | 0x0000000000008c1c |
| 0.05% | _json.cpython-316-x86_64-linux-gnu.so | scan_once_unicode |
| 0.05% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_contentTok |
| 0.05% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_updatePosition |
| 0.04% | libz.so.1.3 | 0x0000000000008c20 |
| 0.04% | libz.so.1.3 | 0x0000000000002dda |
| 0.04% | array.cpython-316-x86_64-linux-gnu.so | array_ass_subscr |
| 0.04% | libz.so.1.3 | 0x0000000000002dd1 |
| 0.04% | libz.so.1.3 | 0x0000000000002dce |
| 0.04% | libz.so.1.3 | 0x0000000000002dc3 |
| 0.04% | libz.so.1.3 | 0x0000000000002dd6 |
| 0.04% | libz.so.1.3 | 0x0000000000002de6 |
| 0.04% | libz.so.1.3 | 0x0000000000008bf7 |
| 0.04% | _math_integer.cpython-316-x86_64-linux-gnu.so | factorial_partial_product |
| 0.03% | python | pattern_subx |
| 0.03% | libsqlite3.so.0.8.6 | sqlite3VdbeExec |
| 0.03% | _heapq.cpython-316-x86_64-linux-gnu.so | siftup |
| 0.03% | python | sre_ucs4_match |
| 0.03% | tracer.cpython-316-x86_64-linux-gnu.so | CTracer_trace |
| 0.03% | array.cpython-316-x86_64-linux-gnu.so | d_getitem |
| 0.03% | python | sre_category |
| 0.03% | array.cpython-316-x86_64-linux-gnu.so | d_setitem |
| 0.03% | libz.so.1.3 | 0x0000000000008be6 |
| 0.03% | libz.so.1.3 | 0x0000000000008c25 |
| 0.03% | libz.so.1.3 | 0x0000000000008192 |
| 0.03% | libm.so.6 | __ieee754_pow_fma |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | doContent |
| 0.03% | libz.so.1.3 | 0x00000000000082aa |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | accountingDiffTolerated.part.0 |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_put |
| 0.02% | _pickle.cpython-316-x86_64-linux-gnu.so | save.constprop.0 |
| 0.02% | _json.cpython-316-x86_64-linux-gnu.so | encoder_listencode_obj |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | save_unicode |
| 0.02% | pyexpat.cpython-316-x86_64-linux-gnu.so | sip24_update.isra.0 |
| 0.02% | libz.so.1.3 | 0x0000000000008bed |
| 0.02% | libz.so.1.3 | 0x0000000000008bd6 |
| 0.02% | libz.so.1.3 | 0x0000000000008c2c |
| 0.02% | libz.so.1.3 | 0x0000000000008c07 |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | Pickler_clear |
| 0.02% | libm.so.6 | __cos_fma |
| 0.02% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_nameLength |
| 0.02% | libz.so.1.3 | 0x00000000000082b7 |
| 0.02% | libz.so.1.3 | 0x000000000000819f |
| 0.02% | libz.so.1.3 | 0x0000000000008c18 |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | load_counted_binunicode |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | Pdata_push |
| 0.02% | python | _sre_SRE_Pattern_search |
| 0.02% | libz.so.1.3 | 0x0000000000008c2f |
| 0.02% | libz.so.1.3 | 0x0000000000008bf1 |
| 0.02% | libz.so.1.3 | 0x0000000000008c0a |
| 0.02% | libz.so.1.3 | 0x0000000000008bfa |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | do_append |
| 0.02% | _json.cpython-316-x86_64-linux-gnu.so | ascii_escape_size |
| 0.02% | libz.so.1.3 | 0x0000000000008bdf |
| 0.02% | array.cpython-316-x86_64-linux-gnu.so | PyNumber_AsSsize_t@plt |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoPut |
| 0.01% | python | sre_ucs2_match |
| 0.01% | libz.so.1.3 | 0x0000000000008c01 |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_end_handler |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_gc_traverse |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_getAtts |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | treebuilder_handle_start |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | lookupWithLength |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | sip24_final |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | elementiter_next |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | save_dict |
| 0.01% | libz.so.1.3 | 0x0000000000008c2a |
| 0.01% | libz.so.1.3 | 0x0000000000008bd0 |
| 0.01% | libz.so.1.3 | 0x0000000000008c0e |
| 0.01% | libz.so.1.3 | 0x0000000000008c14 |
| 0.01% | libz.so.1.3 | 0x0000000000008172 |
| 0.01% | libz.so.1.3 | 0x000000000000814f |
| 0.01% | libz.so.1.3 | 0x0000000000008182 |
| 0.01% | libm.so.6 | __sin_fma |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | write_escaped_ascii |
| 0.01% | libz.so.1.3 | 0x0000000000008279 |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | do_setitems |
| 0.01% | libz.so.1.3 | 0x0000000000008140 |
| 0.01% | libz.so.1.3 | 0x000000000000829a |
| 0.01% | libz.so.1.3 | 0x0000000000008267 |
| 0.01% | libz.so.1.3 | 0x0000000000008258 |
| 0.01% | libz.so.1.3 | 0x0000000000008161 |
| 0.01% | libz.so.1.3 | 0x000000000000828a |
| 0.01% | _sqlite3.cpython-316-x86_64-linux-gnu.so | _pysqlite_query_execute |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyIndex_Check@plt |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | storeAtts |
| 0.01% | binascii.cpython-316-x86_64-linux-gnu.so | ascii_buffer_converter |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyType_GetModuleByDef@plt |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | encoder_encode_key_value |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_get |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_dealloc |
| 0.01% | libz.so.1.3 | inflate |
| 0.01% | _heapq.cpython-316-x86_64-linux-gnu.so | siftdown |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | Unpickler_clear |
| 0.01% | ld-linux-x86-64.so.2 | _dl_relocate_object |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | Pickler_clear |
| 0.01% | _math_integer.cpython-316-x86_64-linux-gnu.so | math_integer_factorial |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_AsLongAndOverflow@plt |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | makeuniversal |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyFloat_FromDouble@plt |
| 0.01% | libz.so.1.3 | 0x0000000000002419 |
| 0.01% | libz.so.1.3 | 0x00000000000082ae |
| 0.01% | libz.so.1.3 | 0x0000000000002416 |
| 0.01% | libz.so.1.3 | 0x000000000000242e |
| 0.01% | _sqlite3.cpython-316-x86_64-linux-gnu.so | _pysqlite_fetch_one_row.constprop.0 |
| 0.01% | _math_integer.cpython-316-x86_64-linux-gnu.so | math_integer_gcd |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | utf8_toUtf8 |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | _Pickler_Write |
| 0.01% | libz.so.1.3 | 0x00000000000023f4 |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_start_handler |
| 0.01% | libz.so.1.3 | 0x0000000000008196 |
| 0.01% | libssl.so.3 | 0x0000000000055398 |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_getitem |
| 0.00% | math.cpython-316-x86_64-linux-gnu.so | math_sqrt |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3BtreeInsert |
| 0.00% | _random.cpython-316-x86_64-linux-gnu.so | genrand_uint32 |
| 0.00% | libz.so.1.3 | 0x0000000000008bfe |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | PyDict_Next@plt |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_data_handler |
| 0.00% | libz.so.1.3 | 0x0000000000008c28 |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | create_new_element.isra.0 |
| 0.00% | libz.so.1.3 | 0x0000000000002403 |
| 0.00% | ld-linux-x86-64.so.2 | do_lookup_x |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | marker |
| 0.00% | python | sre_ucs4_count |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyObject_IsTrue@plt |
| 0.00% | _random.cpython-316-x86_64-linux-gnu.so | _random_Random_getrandbits |
| 0.00% | libz.so.1.3 | 0x0000000000008c37 |
| 0.00% | libz.so.1.3 | 0x0000000000008be3 |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | treebuilder_extend_element_text_or_tail.isra.0 |
| 0.00% | libz.so.1.3 | 0x0000000000008154 |
| 0.00% | array.cpython-316-x86_64-linux-gnu.so | i_getitem |
| 0.00% | python | _sre_SRE_Pattern_sub |
| 0.00% | libz.so.1.3 | 0x000000000000825c |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | memo_get |
| 0.00% | libz.so.1.3 | 0x000000000000828e |
| 0.00% | libz.so.1.3 | 0x0000000000008176 |
| 0.00% | libz.so.1.3 | 0x000000000000829e |
| 0.00% | libz.so.1.3 | 0x000000000000827d |
| 0.00% | libz.so.1.3 | 0x0000000000008165 |
| 0.00% | libz.so.1.3 | 0x00000000000082bb |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | Pickler_traverse |
| 0.00% | tracer.cpython-316-x86_64-linux-gnu.so | CTracer_set_pdata_stack.constprop.0 |
| 0.00% | _ssl.cpython-315-x86_64-linux-gnu.so | _ssl__SSLSocket_read |
| 0.00% | libz.so.1.3 | 0x000000000000826c |
| 0.00% | libz.so.1.3 | 0x0000000000008186 |
| 0.00% | unicodedata.cpython-316-x86_64-linux-gnu.so | unicodedata_UCD_combining |
| 0.00% | _heapq.cpython-316-x86_64-linux-gnu.so | _heapq_heappop |
| 0.00% | python | _sre_SRE_Match_end |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3_step |
| 0.00% | libz.so.1.3 | 0x00000000000081a3 |
| 0.00% | python | sys_trace_start |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_resize |
| 0.00% | libz.so.1.3 | 0x0000000000008144 |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyObject_GetBuffer@plt |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3VdbeHalt |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | xmlparser_append_event.isra.0 |
| 0.00% | _json.cpython-316-x86_64-linux-gnu.so | encoder_write_string |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_FromLong@plt |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | _Pickler_Write.constprop.0 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoGet |
| 0.00% | python | sys_trace_return |
| 0.00% | ld-linux-x86-64.so.2 | strcmp |
| 0.00% | math.cpython-316-x86_64-linux-gnu.so | math_cos |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyBuffer_Release@plt |
| 0.00% | libz.so.1.3 | 0x00000000000023f0 |
| 0.00% | libz.so.1.3 | 0x000000000000381f |
| 0.00% | array.cpython-316-x86_64-linux-gnu.so | PyArg_Parse@plt |
| 0.00% | libm.so.6 | pow@@GLIBC_2.29 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_New |

### gc

8.58% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 3.06% | python | gc_collect_main |
| 1.52% | python | visit_decref |
| 1.48% | python | visit_reachable |
| 0.59% | python | PyObject_GC_UnTrack |
| 0.30% | python | list_traverse |
| 0.25% | python | dict_traverse |
| 0.24% | python | subtype_traverse |
| 0.17% | python | PyObject_GC_Del |
| 0.16% | python | _PyObject_GC_New |
| 0.11% | python | _PyObject_GC_Link |
| 0.11% | python | _PyObject_GC_NewVar |
| 0.07% | python | _PyGC_VisitFrameStack |
| 0.07% | python | tuple_traverse |
| 0.05% | python | TaskObj_traverse |
| 0.05% | python | PyObject_IS_GC |
| 0.05% | python | func_traverse |
| 0.04% | python | _PyTuple_MaybeUntrack |
| 0.04% | python | gen_traverse |
| 0.03% | python | set_traverse |
| 0.03% | python | type_is_gc |
| 0.02% | python | context_tp_traverse |
| 0.02% | python | type_traverse |
| 0.02% | python | meth_traverse |
| 0.01% | python | PyObject_GC_Track |
| 0.01% | python | FutureObj_traverse |
| 0.01% | python | TaskStepMethWrapper_traverse |
| 0.01% | python | _PyGC_VisitStackRef |
| 0.01% | python | method_traverse |
| 0.01% | python | FutureIter_traverse |
| 0.00% | python | gc_traverse |
| 0.00% | python | descr_traverse |
| 0.00% | python | cell_traverse |

### dynamic

6.49% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.71% | python | PyObject_RichCompareBool |
| 0.61% | python | _PyObject_GenericGetAttrWithDict |
| 0.33% | python | PyType_IsSubtype |
| 0.27% | python | PyObject_GetItem |
| 0.27% | python | _PyObject_GetAttrStackRef |
| 0.25% | python | PyObject_Hash |
| 0.24% | python | _PyObject_MakeTpCall |
| 0.18% | python | PyNumber_AsSsize_t |
| 0.18% | python | PyObject_Vectorcall |
| 0.18% | python | PyObject_GetOptionalAttr |
| 0.15% | python | _PyObject_GetMethodStackRef |
| 0.14% | python | _PyObject_TryGetInstanceAttribute |
| 0.14% | python | PyObject_SetItem |
| 0.14% | python | PyObject_IsInstance |
| 0.13% | python | PyObject_IsTrue |
| 0.12% | python | _PyType_GetDict |
| 0.10% | python | PyObject_Malloc |
| 0.09% | python | PyObject_RichCompare |
| 0.09% | python | getset_get |
| 0.09% | python | object_isinstance |
| 0.09% | python | PyObject_CallOneArg |
| 0.08% | python | PyObject_VisitManagedDict |
| 0.08% | python | type_call |
| 0.08% | python | PyObject_GetIter |
| 0.08% | python | PyObject_SetAttr |
| 0.07% | python | PyObject_Size |
| 0.07% | python | PyObject_ClearManagedDict |
| 0.07% | python | PyObject_IsSubclass |
| 0.07% | python | PyObject_Free |
| 0.07% | python | PyObject_GenericSetAttr |
| 0.06% | python | slot_tp_richcompare |
| 0.06% | python | PySequence_Fast |
| 0.05% | python | PyObject_Call |
| 0.05% | python | PyType_GetModuleByDef |
| 0.04% | python | PyObject_ClearWeakRefs |
| 0.04% | python | _PyObject_VectorcallPrepend |
| 0.04% | python | delitem_common |
| 0.04% | python | method_get |
| 0.04% | python | PyObject_VectorcallMethod |
| 0.03% | python | PyIter_Next |
| 0.03% | python | PyObject_Str |
| 0.03% | python | PyObject_GetAttr |
| 0.03% | python | PyNumber_Remainder |
| 0.03% | python | _PyObject_LookupSpecial |
| 0.03% | python | PyObject_GetBuffer |
| 0.03% | python | PyDescr_IsData |
| 0.03% | python | _PyObject_RealIsSubclass |
| 0.03% | python | PySequence_Contains |
| 0.03% | python | PyIter_Send |
| 0.03% | python | _PyObject_VectorcallDictTstate |
| 0.02% | python | PyNumber_Multiply |
| 0.02% | python | PyNumber_Add |
| 0.02% | python | _PyObject_InitInlineValues |
| 0.02% | python | PyObject_Repr |
| 0.02% | python | object_recursive_isinstance |
| 0.02% | python | type_ready |
| 0.02% | python | PyObject_DelItem |
| 0.02% | python | PyNumber_FloorDivide |
| 0.02% | python | object_get_class |
| 0.02% | python | PyNumber_Index |
| 0.02% | python | PyObject_GenericGetAttr |
| 0.02% | python | object_init |
| 0.01% | python | _PyObject_LookupSpecialMethod |
| 0.01% | python | _PyNumber_Index |
| 0.01% | python | _PySuper_Lookup |
| 0.01% | python | _PyObject_Call_Prepend |
| 0.01% | python | object_richcompare |
| 0.01% | python | _PyObject_StoreInstanceAttribute |
| 0.01% | python | PyObject_GenericHash |
| 0.01% | python | PyNumber_Negative |
| 0.01% | python | PyNumber_InPlaceAdd |
| 0.01% | python | StopIteration_init |
| 0.01% | python | PyMapping_GetOptionalItem |
| 0.01% | python | PyMapping_Check |
| 0.01% | python | _Py_type_getattro_impl |
| 0.01% | python | _PyObject_RealIsInstance |
| 0.01% | python | PyNumber_Rshift |
| 0.01% | python | PyNumber_Lshift |
| 0.01% | python | PyObject_LengthHint |
| 0.01% | python | PySequence_Tuple |
| 0.01% | python | PyNumber_Subtract |
| 0.01% | python | type_name |
| 0.01% | python | type___instancecheck__ |
| 0.01% | python | PyNumber_Long |
| 0.01% | python | PyNumber_Xor |
| 0.00% | python | PySequence_List |
| 0.00% | python | _PyNumber_PowerNoMod |
| 0.00% | python | PyNumber_TrueDivide |
| 0.00% | python | PyObject_HasAttrWithError |
| 0.00% | python | PySequence_GetItem |
| 0.00% | python | PyObject_GenericGetDict |
| 0.00% | python | _PyObject_SetAttributeErrorContext |
| 0.00% | python | PyIter_Check |
| 0.00% | python | object_vacall |
| 0.00% | python | _PyObject_CallFunctionVa |
| 0.00% | python | PyNumber_Float |
| 0.00% | python | object___reduce_ex__ |
| 0.00% | python | PyObject_SelfIter |

### lookup

5.38% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 3.31% | python | unicodekeys_lookup_unicode |
| 1.90% | python | _Py_dict_lookup |
| 0.03% | python | find_name_in_mro |
| 0.03% | python | builtin_getattr |
| 0.03% | python | _Py_hashtable_get_entry_generic |
| 0.02% | python | _Py_type_getattro |
| 0.02% | python | _Py_dict_lookup_threadsafe_stackref |
| 0.01% | python | PyMember_GetOne |
| 0.01% | python | update_one_slot |
| 0.01% | python | PyMember_SetOne |
| 0.01% | python | member_get |
| 0.00% | python | _Py_hashtable_get |

### libc

4.76% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.74% | libc.so.6 | __memmove_avx_unaligned_erms |
| 0.50% | libc.so.6 | __memset_avx2_unaligned_erms |
| 0.33% | libc.so.6 | __memcmp_avx2_movbe |
| 0.17% | libc.so.6 | _int_malloc |
| 0.08% | libc.so.6 | malloc |
| 0.06% | libc.so.6 | __strlen_avx2 |
| 0.05% | libc.so.6 | _int_free_merge_chunk |
| 0.04% | libc.so.6 | _int_free |
| 0.04% | libc.so.6 | unlink_chunk.isra.0 |
| 0.04% | libc.so.6 | __memchr_avx2 |
| 0.04% | libc.so.6 | pthread_mutex_lock@@GLIBC_2.2.5 |
| 0.04% | libc.so.6 | cfree@GLIBC_2.2.5 |
| 0.03% | libcrypto.so.3 | 0x00000000002dcb4e |
| 0.03% | libc.so.6 | __strcmp_avx2 |
| 0.03% | libc.so.6 | __GI___pthread_self |
| 0.02% | libc.so.6 | pthread_mutex_unlock@@GLIBC_2.2.5 |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb90 |
| 0.02% | libc.so.6 | _int_free_maybe_consolidate |
| 0.02% | libc.so.6 | __strchr_avx2 |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb62 |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb8b |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb9a |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb9f |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc92 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbae |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb95 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8cf |
| 0.01% | libcrypto.so.3 | 0x00000000002dcabc |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8da |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd13 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcac7 |
| 0.01% | libc.so.6 | realloc |
| 0.01% | libcrypto.so.3 | 0x00000000002dc9e6 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba4 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd01 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccd2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc6a |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba9 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccee |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc40 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc7e |
| 0.01% | libc.so.6 | pthread_cond_signal@@GLIBC_2.3.2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb44 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc74 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc9d |
| 0.01% | libcrypto.so.3 | 0x00000000002dc899 |
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
| 0.01% | libc.so.6 | _int_realloc |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb71 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb7b |
| 0.01% | libcrypto.so.3 | OPENSSL_cleanse |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc60 |
| 0.01% | libcrypto.so.3 | OSSL_PARAM_locate |
| 0.01% | libcrypto.so.3 | BIO_ctrl |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb49 |
| 0.01% | libc.so.6 | pthread_rwlock_unlock@@GLIBC_2.34 |
| 0.01% | libc.so.6 | __strncmp_avx2 |
| 0.01% | libc.so.6 | pthread_rwlock_rdlock@GLIBC_2.2.5 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbbd |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb58 |
| 0.01% | libc.so.6 | __errno_location |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbb3 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb67 |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_ctrl |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_get_iv_length |
| 0.01% | libc.so.6 | clock_gettime@@GLIBC_2.17 |
| 0.01% | libcrypto.so.3 | 0x00000000000c0ddb |
| 0.01% | libc.so.6 | __memrchr_avx2 |
| 0.00% | libc.so.6 | malloc_consolidate |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb53 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcd0a |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb27 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc9db |
| 0.00% | libc.so.6 | __printf_buffer |
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
| 0.00% | libc.so.6 | __gconv_transform_utf8_internal |
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
| 0.00% | libcrypto.so.3 | 0x00000000002dc8e5 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb36 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcc65 |

### dict

3.40% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.67% | python | _PyDict_Subscript |
| 0.52% | python | dictiter_iternextkey |
| 0.35% | python | insertdict |
| 0.28% | python | PyDict_GetItemRef |
| 0.18% | python | build_indices_unicode |
| 0.17% | python | dictkeys_decref.part.0.constprop.0 |
| 0.16% | python | PyDict_Next |
| 0.10% | python | insert_to_emptydict |
| 0.09% | python | _PyDict_StoreSubscript |
| 0.09% | python | dict_get |
| 0.07% | python | find_empty_slot |
| 0.07% | python | dictiter_iternextitem |
| 0.07% | python | PyDict_Contains |
| 0.06% | python | _PyDict_FromItems |
| 0.06% | python | new_dict.constprop.0 |
| 0.05% | python | _PyDict_LoadBuiltinsFromGlobals |
| 0.05% | python | dict_setdefault_ref_lock_held |
| 0.04% | python | _PyDict_Next |
| 0.04% | python | dict_merge |
| 0.03% | python | dictresize |
| 0.02% | python | insertdict.isra.0 |
| 0.02% | python | _PyDict_SetItem_Take2 |
| 0.02% | python | new_keys_object |
| 0.02% | python | dictiter_iternextvalue |
| 0.02% | python | PyDict_SetItem |
| 0.01% | python | dict_items |
| 0.01% | python | find_empty_slot.constprop.0 |
| 0.01% | python | _PyDict_DelItem_KnownHash_LockHeld |
| 0.01% | python | PyDict_GetItem |
| 0.01% | python | dict_ass_sub |
| 0.01% | python | PyDict_GetItemWithError |
| 0.01% | python | dict_pop |
| 0.01% | python | _PyDict_MergeUniq |
| 0.01% | python | _PyDict_LoadGlobalStackRef |
| 0.01% | python | _PyDict_GetMethodStackRef |
| 0.01% | python | dict_iter |
| 0.01% | python | _PyDict_GetItemRef_KnownHash_LockHeld |
| 0.01% | python | new_dict |
| 0.00% | python | dict_vectorcall |
| 0.00% | python | dict___contains__ |
| 0.00% | python | dict_update |
| 0.00% | python | insert_to_emptydict.isra.0 |
| 0.00% | python | _PyDict_GetItemRef_KnownHash |

### int

2.39% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.75% | python | k_mul |
| 0.19% | python | x_divrem |
| 0.17% | python | long_to_decimal_string_internal |
| 0.15% | python | PyLong_FromSsize_t |
| 0.14% | python | PyLong_FromLong |
| 0.10% | python | PyLong_AsSsize_t |
| 0.09% | python | _PyLong_FromMedium |
| 0.08% | python | _PyLong_GCD |
| 0.07% | python | long_richcompare |
| 0.07% | python | PyLong_AsLongAndOverflow |
| 0.06% | python | x_add |
| 0.06% | python | long_hash |
| 0.04% | python | long_div |
| 0.03% | python | PyLong_FromString |
| 0.03% | python | x_sub |
| 0.03% | python | long_bitwise |
| 0.02% | python | PyLong_FromVoidPtr |
| 0.02% | python | PyLong_AsLong |
| 0.02% | python | PyLong_FromUnsignedLong |
| 0.02% | python | PyLong_AsNativeBytes.constprop.0 |
| 0.02% | python | long_lshift1 |
| 0.02% | python | long_mul |
| 0.02% | python | long_rshift1 |
| 0.02% | python | l_mod |
| 0.01% | python | _PyLong_Frexp |
| 0.01% | python | long_rshift |
| 0.01% | python | long_to_decimal_string |
| 0.01% | python | long_neg_method |
| 0.01% | python | long_lshift_method |
| 0.01% | python | _PyLong_Size_t_Converter |
| 0.01% | python | PyLong_FromUnsignedLongLong |
| 0.01% | python | long_add |
| 0.01% | python | PyLong_AsDouble |
| 0.01% | python | long_mul_method |
| 0.00% | python | PyLong_FromLongLong |
| 0.00% | python | PyLong_GetSign |
| 0.00% | python | long_mod |
| 0.00% | python | PyLong_AsInt |
| 0.00% | python | long_float |
| 0.00% | python | long_add_method |
| 0.00% | python | long_xor |
| 0.00% | python | long_vectorcall |
| 0.00% | python | _PyLong_UInt64_Converter |

### str

2.36% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.21% | python | _PyUnicode_JoinArray.part.0 |
| 0.19% | python | _PyUnicode_Equal |
| 0.16% | python | siphash13 |
| 0.14% | python | PyUnicode_Format |
| 0.14% | python | PyUnicode_RichCompare |
| 0.10% | python | _PyUnicode_ResizeCompact |
| 0.10% | python | _copy_characters.constprop.0.isra.0 |
| 0.08% | python | replace |
| 0.07% | python | find_first_nonascii |
| 0.06% | python | unicode_hash |
| 0.05% | python | bytes_richcompare |
| 0.05% | python | PyUnicode_Substring |
| 0.05% | python | PyBytes_FromStringAndSize |
| 0.04% | python | unicode_decode_utf8.part.0 |
| 0.04% | python | _PyUnicode_FromUCS4.part.0 |
| 0.03% | python | bytes_translate_impl |
| 0.03% | python | split |
| 0.03% | python | _PyUnicodeWriter_WriteStr |
| 0.03% | python | PyUnicode_Contains |
| 0.03% | python | _PyUnicodeWriter_WriteSubstring |
| 0.03% | python | _PyUnicodeWriter_PrepareInternal |
| 0.03% | python | unicode_from_format |
| 0.03% | python | unicode_repr |
| 0.03% | python | _PyUnicode_InternMortal |
| 0.02% | python | unicode_replace |
| 0.02% | python | _PyUnicode_TranslateCharmap |
| 0.02% | python | unicode_join |
| 0.02% | python | PyUnicode_Concat |
| 0.02% | python | PyUnicodeWriter_WriteChar |
| 0.02% | python | _PyUnicodeWriter_Finish |
| 0.02% | python | PyUnicode_AsUTF8AndSize |
| 0.02% | python | _PyUnicode_BinarySlice |
| 0.02% | python | unicode_decode_utf8_impl |
| 0.02% | python | stringlib_bytes_join |
| 0.02% | python | bytes_subscript |
| 0.01% | python | _PyUnicode_FromUCS1.part.0 |
| 0.01% | python | unicode_startswith |
| 0.01% | python | _PyUnicode_IsAlpha |
| 0.01% | python | PyUnicodeWriter_WriteASCII |
| 0.01% | python | _PyUnicodeWriter_Init |
| 0.01% | python | bytes_hash |
| 0.01% | python | intern_constants |
| 0.01% | python | PyUnicode_Splitlines |
| 0.01% | python | unicode_fromformat_write_utf8 |
| 0.01% | python | _PyUnicodeWriter_WriteASCIIString |
| 0.01% | python | _PyUnicode_InternImmortal |
| 0.01% | python | _PyUnicode_FromASCII |
| 0.01% | python | bytes_buffer_getbuffer |
| 0.01% | python | unicode_expandtabs |
| 0.01% | python | PyUnicode_InternFromString |
| 0.01% | python | unicode_rfind |
| 0.01% | python | _PyUnicode_IsDecimalDigit |
| 0.01% | python | PyUnicode_Decode |
| 0.01% | python | unicode_strip |
| 0.01% | python | PyUnicodeWriter_WriteStr |
| 0.01% | python | unicode_lower |
| 0.01% | python | _PyUnicode_FindMaxChar |
| 0.01% | python | _PyUnicode_JoinArray |
| 0.00% | python | bytes_iteritem |
| 0.00% | python | _PyUnicode_XStrip |
| 0.00% | python | PyUnicode_AsEncodedString |
| 0.00% | python | _PyUnicode_FastCopyCharacters |
| 0.00% | python | _PyUnicode_DecodeUTF8Writer |
| 0.00% | python | unicode_split |
| 0.00% | python | PyUnicode_Append |
| 0.00% | python | stringlib__two_way |
| 0.00% | python | ascii_decode |
| 0.00% | python | PyUnicode_FromWideChar |
| 0.00% | python | unicode_encode |
| 0.00% | python | PyUnicode_FromString |
| 0.00% | python | _PyUnicode_IsDigit |
| 0.00% | python | PyUnicode_DecodeUTF8 |
| 0.00% | python | _PyUnicode_ToLowercase |
| 0.00% | python | PyUnicode_AsUCS4 |
| 0.00% | python | PyUnicode_FindChar |
| 0.00% | python | PyBytes_FromStringAndSize.constprop.0 |
| 0.00% | python | PyUnicode_Join |
| 0.00% | python | bytes_length |
| 0.00% | python | unicode_find |
| 0.00% | python | unicode_rstrip |
| 0.00% | python | PyUnicode_FromFormatV |
| 0.00% | python | unicode_mod |
| 0.00% | python | PyUnicodeWriter_Create |

### miscobj

2.26% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.98% | python | set_lookkey |
| 0.35% | python | PySlice_AdjustIndices |
| 0.15% | python | _PySet_Contains |
| 0.08% | python | PySlice_Unpack |
| 0.07% | python | gen_iternext |
| 0.06% | python | make_gen |
| 0.05% | python | set_add_entry_takeref |
| 0.04% | python | setiter_iternext |
| 0.04% | python | PyBuffer_Release |
| 0.04% | python | PyBool_FromLong |
| 0.03% | python | PyBuffer_FillInfo |
| 0.03% | python | enum_next |
| 0.03% | python | range_iter |
| 0.03% | python | deque_append |
| 0.03% | python | _PyBuildSlice_ConsumeRefs |
| 0.02% | python | set_issubset_impl |
| 0.02% | python | set_table_resize |
| 0.02% | python | deque_popleft |
| 0.02% | python | set_merge_lock_held |
| 0.02% | python | _PyGen_FetchStopIterationValue |
| 0.01% | python | PyGen_am_send |
| 0.01% | python | range_vectorcall |
| 0.01% | python | dequeiter_next |
| 0.01% | python | deque_clear.part.0 |
| 0.01% | python | set_difference_untracked |
| 0.01% | python | _PySlice_GetLongIndices |
| 0.01% | python | range_subscript |
| 0.01% | python | set_add |
| 0.01% | python | _PySet_NextEntryRef |
| 0.00% | python | PySet_Add |
| 0.00% | python | weakref_richcompare |
| 0.00% | python | bytearray_ass_subscript_lock_held |
| 0.00% | python | set_intersection |
| 0.00% | python | set_vectorcall |
| 0.00% | python | weakref_hash |
| 0.00% | python | set_iter |
| 0.00% | python | deque_iter |

### kernel

2.00% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.21% | [kernel.kallsyms] | __irqentry_text_end |
| 0.11% | [kernel.kallsyms] | error_entry |
| 0.08% | [kernel.kallsyms] | clear_page_erms |
| 0.06% | [kernel.kallsyms] | native_irq_return_iret |
| 0.06% | [kernel.kallsyms] | sync_regs |
| 0.05% | [kernel.kallsyms] | entry_SYSRETQ_unsafe_stack |
| 0.05% | [kernel.kallsyms] | syscall_return_via_sysret |
| 0.03% | [kernel.kallsyms] | __handle_mm_fault |
| 0.03% | [kernel.kallsyms] | zap_pte_range |
| 0.03% | [kernel.kallsyms] | memset_orig |
| 0.03% | [kernel.kallsyms] | entry_SYSCALL_64_after_hwframe |
| 0.03% | [kernel.kallsyms] | get_mem_cgroup_from_mm |
| 0.03% | [kernel.kallsyms] | mas_walk |
| 0.02% | [kernel.kallsyms] | entry_SYSCALL_64 |
| 0.02% | [kernel.kallsyms] | __alloc_pages |
| 0.02% | [kernel.kallsyms] | do_anonymous_page |
| 0.02% | [kernel.kallsyms] | __count_memcg_events |
| 0.02% | [kernel.kallsyms] | __d_lookup_rcu |
| 0.02% | [kernel.kallsyms] | handle_mm_fault |
| 0.02% | [kernel.kallsyms] | lru_gen_add_folio |
| 0.02% | [kernel.kallsyms] | __rcu_read_lock |
| 0.02% | [kernel.kallsyms] | perf_adjust_freq_unthr_context |
| 0.02% | [kernel.kallsyms] | __rcu_read_unlock |
| 0.02% | [kernel.kallsyms] | rep_movs_alternative |
| 0.02% | [kernel.kallsyms] | __mod_memcg_lruvec_state |
| 0.02% | [kernel.kallsyms] | __lruvec_stat_mod_folio |
| 0.01% | [kernel.kallsyms] | _raw_spin_lock |
| 0.01% | [kernel.kallsyms] | link_path_walk.part.0.constprop.0 |
| 0.01% | [kernel.kallsyms] | arch_exit_to_user_mode_prepare.isra.0 |
| 0.01% | [kernel.kallsyms] | __mod_node_page_state |
| 0.01% | [kernel.kallsyms] | release_pages |
| 0.01% | [kernel.kallsyms] | percpu_counter_add_batch |
| 0.01% | [kernel.kallsyms] | get_page_from_freelist |
| 0.01% | [kernel.kallsyms] | cgroup_rstat_updated |
| 0.01% | [kernel.kallsyms] | lru_gen_del_folio.constprop.0 |
| 0.01% | [kernel.kallsyms] | lru_add_fn |
| 0.01% | [kernel.kallsyms] | folio_add_lru |
| 0.01% | [kernel.kallsyms] | do_user_addr_fault |
| 0.01% | [kernel.kallsyms] | blk_cgroup_congested |
| 0.01% | [kernel.kallsyms] | rmqueue_bulk |
| 0.01% | [kernel.kallsyms] | __pte_offset_map |
| 0.01% | [kernel.kallsyms] | alloc_anon_folio |
| 0.01% | [kernel.kallsyms] | rmqueue |
| 0.01% | [kernel.kallsyms] | get_vma_policy |
| 0.01% | [kernel.kallsyms] | handle_pte_fault |
| 0.01% | [kernel.kallsyms] | __pte_offset_map_lock |
| 0.01% | [kernel.kallsyms] | kmem_cache_alloc |
| 0.01% | [kernel.kallsyms] | native_write_msr |
| 0.01% | [kernel.kallsyms] | lock_vma_under_rcu |
| 0.01% | [kernel.kallsyms] | folio_batch_move_lru |
| 0.01% | [kernel.kallsyms] | ext4_htree_store_dirent |
| 0.01% | [kernel.kallsyms] | fpregs_assert_state_consistent |
| 0.01% | [kernel.kallsyms] | exc_page_fault |
| 0.01% | [kernel.kallsyms] | _raw_spin_trylock |
| 0.01% | [kernel.kallsyms] | folio_remove_rmap_ptes |
| 0.01% | [kernel.kallsyms] | inode_permission |
| 0.01% | [kernel.kallsyms] | __rmqueue_pcplist |
| 0.01% | [kernel.kallsyms] | do_syscall_64 |
| 0.01% | [kernel.kallsyms] | pte_offset_map_nolock |
| 0.01% | [kernel.kallsyms] | down_read_trylock |
| 0.01% | [kernel.kallsyms] | __mod_zone_page_state |
| 0.01% | [kernel.kallsyms] | folio_add_new_anon_rmap |
| 0.01% | [kernel.kallsyms] | asm_exc_page_fault |
| 0.01% | [kernel.kallsyms] | __update_load_avg_se |
| 0.01% | [kernel.kallsyms] | up_read |
| 0.01% | [kernel.kallsyms] | half_md4_transform.isra.0 |
| 0.01% | [kernel.kallsyms] | filldir64 |
| 0.01% | [kernel.kallsyms] | post_alloc_hook |
| 0.01% | [kernel.kallsyms] | free_unref_page_prepare |
| 0.01% | [kernel.kallsyms] | mem_cgroup_commit_charge |
| 0.01% | [kernel.kallsyms] | alloc_pages_mpol |
| 0.01% | [kernel.kallsyms] | generic_permission |
| 0.00% | [kernel.kallsyms] | uncharge_folio |
| 0.00% | [kernel.kallsyms] | kmem_cache_free |
| 0.00% | [kernel.kallsyms] | free_unref_page_list |
| 0.00% | [kernel.kallsyms] | update_load_avg |
| 0.00% | [kernel.kallsyms] | free_unref_page_commit |
| 0.00% | [kernel.kallsyms] | __update_load_avg_cfs_rq |
| 0.00% | [kernel.kallsyms] | next_uptodate_folio |
| 0.00% | [kernel.kallsyms] | strncpy_from_user |
| 0.00% | [kernel.kallsyms] | __virt_addr_valid |
| 0.00% | [kernel.kallsyms] | __raw_spin_lock_irqsave |
| 0.00% | [kernel.kallsyms] | str2hashbuf_signed |
| 0.00% | [kernel.kallsyms] | read_tsc |
| 0.00% | [kernel.kallsyms] | __kmalloc |
| 0.00% | [kernel.kallsyms] | count_memcg_events.constprop.0 |
| 0.00% | [kernel.kallsyms] | update_curr |
| 0.00% | [kernel.kallsyms] | __mem_cgroup_charge |
| 0.00% | [kernel.kallsyms] | hrtimer_interrupt |
| 0.00% | [kernel.kallsyms] | native_read_msr |
| 0.00% | [kernel.kallsyms] | __mod_lruvec_state |
| 0.00% | [kernel.kallsyms] | get_pfnblock_flags_mask |
| 0.00% | [kernel.kallsyms] | apparmor_inode_getattr |
| 0.00% | [kernel.kallsyms] | filename_lookup |
| 0.00% | [kernel.kallsyms] | rb_next |
| 0.00% | [kernel.kallsyms] | __free_one_page |
| 0.00% | [kernel.kallsyms] | account_user_time |
| 0.00% | [kernel.kallsyms] | __hrtimer_run_queues |
| 0.00% | [kernel.kallsyms] | cond_accept_memory |
| 0.00% | [kernel.kallsyms] | irqentry_exit_to_user_mode |
| 0.00% | [kernel.kallsyms] | copy_page |
| 0.00% | [kernel.kallsyms] | step_into |
| 0.00% | [kernel.kallsyms] | vma_alloc_folio |
| 0.00% | [kernel.kallsyms] | irqentry_exit |
| 0.00% | [kernel.kallsyms] | filemap_map_pages |
| 0.00% | [kernel.kallsyms] | timekeeping_advance |
| 0.00% | [kernel.kallsyms] | __task_pid_nr_ns |
| 0.00% | [kernel.kallsyms] | consume_stock |
| 0.00% | [kernel.kallsyms] | try_charge_memcg |
| 0.00% | [kernel.kallsyms] | __folio_throttle_swaprate |
| 0.00% | [kernel.kallsyms] | _raw_spin_unlock |
| 0.00% | [kernel.kallsyms] | update_cfs_group |
| 0.00% | [kernel.kallsyms] | rb_insert_color |
| 0.00% | [kernel.kallsyms] | cp_new_stat |
| 0.00% | [kernel.kallsyms] | security_inode_permission |
| 0.00% | [kernel.kallsyms] | lapic_next_deadline |
| 0.00% | [kernel.kallsyms] | scheduler_tick |
| 0.00% | [kernel.kallsyms] | kfree |
| 0.00% | [kernel.kallsyms] | set_root |
| 0.00% | [kernel.kallsyms] | free_pcppages_bulk |
| 0.00% | [kernel.kallsyms] | __sysvec_apic_timer_interrupt |
| 0.00% | [kernel.kallsyms] | walk_component |
| 0.00% | [kernel.kallsyms] | pfn_pte |
| 0.00% | [kernel.kallsyms] | x64_sys_call |
| 0.00% | [kernel.kallsyms] | error_return |
| 0.00% | [kernel.kallsyms] | policy_nodemask |
| 0.00% | [kernel.kallsyms] | ext4_getattr |
| 0.00% | [kernel.kallsyms] | ktime_get_update_offsets_now |
| 0.00% | [kernel.kallsyms] | free_swap_cache |
| 0.00% | [kernel.kallsyms] | arch_scale_freq_tick |
| 0.00% | [kernel.kallsyms] | __slab_free |
| 0.00% | [kernel.kallsyms] | native_apic_msr_eoi |

### list

1.98% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.37% | python | list_remove |
| 0.30% | python | listiter_next |
| 0.20% | python | list_slice_lock_held |
| 0.17% | python | list_ass_slice_lock_held |
| 0.11% | python | list_iter |
| 0.09% | python | list_sort_impl |
| 0.08% | python | list_slice_wrap |
| 0.08% | python | _PyList_AppendTakeRefListResize |
| 0.07% | python | list_extend_lock_held |
| 0.07% | python | _list_extend |
| 0.06% | python | _PyList_BinarySlice |
| 0.05% | python | list_append |
| 0.05% | python | _PyList_SliceSubscript |
| 0.04% | python | list_ass_subscript |
| 0.04% | python | _PyList_FromStackRefStealOnSuccess |
| 0.03% | python | _PyList_Concat |
| 0.03% | python | list_subscript |
| 0.02% | python | list_contains |
| 0.02% | python | list_insert |
| 0.01% | python | list_length |
| 0.01% | python | list_resize |
| 0.01% | python | PyList_Append |
| 0.01% | python | list_pop |
| 0.01% | python | list_vectorcall |
| 0.01% | python | list_sort |
| 0.01% | python | _PyList_Extend |
| 0.01% | python | list_index |
| 0.00% | python | list_to_tuple |
| 0.00% | python | list_richcompare |
| 0.00% | python | PyList_SetItem |
| 0.00% | python | _PyList_AsTupleAndClear |
| 0.00% | python | PyList_Size |
| 0.00% | python | PyList_GetItemRef |

### tuple

1.23% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.31% | python | PyTuple_FromArray.part.0 |
| 0.29% | python | _PyTuple_FromStackRefStealOnSuccess |
| 0.29% | python | tuple_richcompare |
| 0.15% | python | tuple_hash |
| 0.03% | python | PyTuple_GetSlice |
| 0.02% | python | PyTuple_FromArray |
| 0.02% | python | _PyTuple_FromArraySteal |
| 0.02% | python | tuple_subscript |
| 0.02% | python | _PyTuple_FromPair |
| 0.01% | python | tuple_iter |
| 0.01% | python | tupleiter_next |
| 0.01% | python | _PyTuple_FromPairSteal |
| 0.01% | python | tuplegetter_descr_get |
| 0.01% | python | _PyTuple_BinarySlice |
| 0.01% | python | _PyTuple_Concat |
| 0.01% | python | tuple_iteritem |
| 0.01% | python | tuple_contains |
| 0.00% | python | tuple_length |
| 0.00% | python | PyTuple_Pack |
| 0.00% | python | PyTuple_Size |

### calls

0.69% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.20% | python | _PyArg_UnpackKeywords |
| 0.08% | python | _PyFunction_Vectorcall |
| 0.08% | python | _Py_CheckFunctionResult |
| 0.07% | python | vgetargs1_impl.constprop.0 |
| 0.06% | python | PyArg_UnpackTuple |
| 0.03% | python | PyArg_Parse |
| 0.03% | python | cfunction_vectorcall_FASTCALL_KEYWORDS |
| 0.03% | python | method_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.02% | python | method_vectorcall_O |
| 0.01% | python | cfunction_vectorcall_NOARGS |
| 0.01% | python | vgetargs1_impl |
| 0.01% | python | method_vectorcall_VARARGS |
| 0.01% | python | method_vectorcall |
| 0.01% | python | cfunction_vectorcall_O |
| 0.01% | python | PyArg_ParseTupleAndKeywords |
| 0.01% | python | cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.01% | python | vectorcall_method |
| 0.01% | python | method_vectorcall_FASTCALL |
| 0.00% | python | method_vectorcall_VARARGS_KEYWORDS |
| 0.00% | python | _PyArg_UnpackStack |
| 0.00% | python | method_vectorcall_NOARGS |
| 0.00% | python | cfunction_vectorcall_FASTCALL |

### threading

0.52% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.28% | python | _PyThreadState_PopFrame |
| 0.14% | python | _PyThreadState_PushFrame |
| 0.07% | python | PyThread_get_thread_ident |
| 0.01% | python | _PyThreadState_Attach |
| 0.01% | python | _PyThreadState_Detach |
| 0.01% | python | _PyThreadState_MustExit |

### exceptions

0.42% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.13% | python | PyErr_CheckSignals |
| 0.10% | python | _PyErr_CheckSignalsTstate |
| 0.03% | python | _PyErr_SetObject.part.0 |
| 0.03% | python | PyErr_Occurred |
| 0.03% | python | PyErr_ExceptionMatches |
| 0.01% | python | PyErr_SetRaisedException |
| 0.01% | python | PyTraceBack_Here |
| 0.01% | python | PyErr_GetRaisedException |
| 0.01% | python | _PyErr_Restore |
| 0.01% | python | PyErr_GivenExceptionMatches |
| 0.01% | python | BaseException_vectorcall |
| 0.01% | python | PyErr_Format |
| 0.00% | python | PyException_GetTraceback |
| 0.00% | python | AttributeError_init |
| 0.00% | python | _PyErr_SetKeyError |
| 0.00% | python | PyException_SetTraceback |
| 0.00% | python | PyFrame_GetCode |
| 0.00% | python | _PyErr_CreateException |
| 0.00% | python | _PyErr_GetRaisedException |

### compiler

0.34% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.33% | python | _PyJIT_Entry |
| 0.00% | python | optimize_uops.isra.0 |

### float

0.28% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.19% | python | PyFloat_FromDouble |
| 0.02% | python | float_richcompare |
| 0.02% | python | PyFloat_AsDouble |
| 0.02% | python | float_compactlong_true_div |
| 0.01% | python | float_pow |
| 0.01% | python | float_add |
| 0.00% | python | float_vectorcall |
| 0.00% | python | float_compactlong_guard |

### gil

0.06% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.05% | python | take_gil |
| 0.01% | python | drop_gil |

### import

0.05% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.03% | python | r_object |
| 0.01% | python | PyImport_ImportModuleLevelObject |
| 0.01% | python | r_long |

### async

0.02% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.02% | python | async_gen_anext |
