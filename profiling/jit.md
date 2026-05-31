
## 2to3

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.05% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.03% | `[JIT]` | `jit` | jit |
| 3.90% | `python` | `gc_collect_main` | gc |
| 2.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.47% | `python` | `_PyObject_Malloc` | memory |
| 1.97% | `python` | `visit_decref` | gc |
| 1.70% | `python` | `_Py_dict_lookup` | lookup |
| 1.66% | `python` | `sre_ucs1_match` | library |
| 1.56% | `python` | `_PyObject_Free` | memory |
| 1.48% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.43% | `python` | `_Py_Dealloc` | memory |
| 1.32% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.23% | `python` | `visit_reachable` | gc |
| 1.10% | `python` | `tuple_dealloc` | memory |
| 0.78% | `python` | `r_object` | import |
| 0.74% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.67% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.64% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.62% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.61% | `python` | `initialize_locals` | interpreter |
| 0.61% | `python` | `tuple_alloc` | memory |
| 0.59% | `python` | `_PyCode_Quicken` | interpreter |
| 0.58% | `python` | `find_name_in_mro` | lookup |
| 0.56% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.54% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.50% | `python` | `dict_traverse` | gc |
| 0.48% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.44% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.44% | `python` | `siphash13` | str |
| 0.41% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.39% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.38% | `libc.so.6` | `_int_malloc` | libc |
| 0.37% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.36% | `python` | `list_dealloc` | memory |
| 0.34% | `python` | `type_ready` | dynamic |
| 0.34% | `python` | `PyDict_GetItemRef` | dict |
| 0.32% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.32% | `python` | `insertdict` | dict |
| 0.31% | `python` | `PyObject_SetAttr` | dynamic |
| 0.31% | `python` | `gen_dealloc` | memory |
| 0.31% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.29% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.29% | `python` | `update_one_slot` | lookup |
| 0.29% | `python` | `_PyPegen_is_memoized` | interpreter |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `python` | `sre_ucs1_count` | library |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.28% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.28% | `python` | `dict_dealloc` | memory |
| 0.28% | `python` | `list_subscript` | list |
| 0.28% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.27% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.27% | `python` | `_PyEval_Vector` | interpreter |
| 0.27% | `python` | `new_dict` | dict |
| 0.27% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.26% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.25% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |

## argparse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.24% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.95% | `[JIT]` | `jit` | jit |
| 2.95% | `python` | `_PyObject_Malloc` | memory |
| 2.27% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.11% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.81% | `python` | `_PyObject_Free` | memory |
| 1.58% | `python` | `_Py_dict_lookup` | lookup |
| 1.51% | `python` | `_Py_Dealloc` | memory |
| 1.41% | `python` | `initialize_locals` | interpreter |
| 1.37% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.01% | `python` | `gc_collect_main` | gc |
| 0.82% | `python` | `tuple_dealloc` | memory |
| 0.81% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.78% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.70% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.67% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.60% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.55% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.50% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.49% | `python` | `PyUnicode_Format` | str |
| 0.48% | `python` | `list_dealloc` | memory |
| 0.47% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.46% | `python` | `PyDict_GetItemRef` | dict |
| 0.46% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.45% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.43% | `python` | `insertdict` | dict |
| 0.42% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.42% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 0.39% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.38% | `libc.so.6` | `__gconv_transform_utf8_internal` | libc |
| 0.37% | `python` | `PyList_New.constprop.0` | memory |
| 0.37% | `python` | `dict_dealloc` | memory |
| 0.36% | `python` | `visit_decref` | gc |
| 0.36% | `python` | `tuple_alloc` | memory |
| 0.36% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.35% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.35% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.34% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.33% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `PyUnicode_Contains` | str |
| 0.33% | `libc.so.6` | `malloc` | libc |
| 0.33% | `python` | `replace` | str |
| 0.33% | `python` | `new_dict` | dict |
| 0.32% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.32% | `python` | `PyType_IsSubtype` | dynamic |
| 0.32% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.31% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.30% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.30% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.30% | `python` | `PyUnicode_Append` | str |
| 0.30% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.29% | `python` | `_PyObject_Realloc` | memory |
| 0.29% | `python` | `sre_ucs1_match` | library |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.28% | `python` | `siphash13` | str |
| 0.27% | `python` | `split` | str |
| 0.27% | `python` | `_PyObject_GC_New` | gc |
| 0.27% | `python` | `insert_to_emptydict` | dict |
| 0.27% | `python` | `PyUnicode_New.part.0` | memory |
| 0.26% | `libc.so.6` | `__dcigettext` | libc |
| 0.26% | `python` | `get_exception_handler.isra.0` | unknown |

## argparse_subparsers

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.04% | `[JIT]` | `jit` | jit |
| 10.13% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.33% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.05% | `python` | `_PyObject_Malloc` | memory |
| 2.81% | `python` | `_Py_dict_lookup` | lookup |
| 2.47% | `python` | `_PyObject_Free` | memory |
| 2.16% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.05% | `python` | `gc_collect_main` | gc |
| 1.94% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.75% | `python` | `_Py_Dealloc` | memory |
| 1.75% | `python` | `initialize_locals` | interpreter |
| 0.93% | `python` | `long_to_decimal_string_internal` | int |
| 0.90% | `python` | `visit_decref` | gc |
| 0.90% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.85% | `libc.so.6` | `_int_malloc` | libc |
| 0.84% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.75% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.73% | `python` | `insertdict` | dict |
| 0.68% | `python` | `sre_ucs1_match` | library |
| 0.66% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.65% | `python` | `tuple_dealloc` | memory |
| 0.61% | `python` | `find_name_in_mro` | lookup |
| 0.59% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.56% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.56% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.56% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.53% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.51% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.51% | `python` | `_PyDict_Subscript` | dict |
| 0.48% | `python` | `tuple_alloc` | memory |
| 0.48% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.47% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.45% | `libc.so.6` | `malloc` | libc |
| 0.45% | `python` | `PyUnicode_Contains` | str |
| 0.44% | `python` | `PyType_IsSubtype` | dynamic |
| 0.43% | `python` | `_PyJIT_Entry` | compiler |
| 0.43% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.41% | `python` | `_Py_BuildString_StackRefSteal` | unknown |
| 0.41% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.41% | `python` | `PyUnicode_Format` | str |
| 0.40% | `python` | `list_dealloc` | memory |
| 0.40% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.39% | `python` | `PyObject_Hash` | dynamic |
| 0.39% | `python` | `replace` | str |
| 0.37% | `python` | `pattern_new_match` | memory |
| 0.34% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.33% | `python` | `siphash13` | str |
| 0.31% | `python` | `_PyEval_Vector` | interpreter |
| 0.30% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.30% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.30% | `python` | `dict_get` | dict |
| 0.30% | `python` | `subtype_traverse` | gc |
| 0.29% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.29% | `python` | `PyMethod_New` | memory |
| 0.29% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.29% | `python` | `visit_reachable` | gc |
| 0.28% | `python` | `set_add_entry_takeref` | miscobj |
| 0.28% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.28% | `python` | `unicode_dealloc` | memory |
| 0.27% | `python` | `_Py_NewReference` | memory |
| 0.27% | `python` | `PyUnicode_New.part.0` | memory |
| 0.27% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.26% | `python` | `clone_combined_dict_keys` | unknown |
| 0.26% | `python` | `dict_dealloc` | memory |
| 0.26% | `python` | `PyObject_Str` | dynamic |
| 0.25% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.25% | `python` | `PyList_New.constprop.0` | memory |
| 0.25% | `python` | `PyDict_Next` | dict |

## async_generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.35% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.51% | `[JIT]` | `jit` | jit |
| 6.55% | `python` | `_Py_Dealloc` | memory |
| 3.60% | `python` | `_PyObject_Free` | memory |
| 3.43% | `python` | `_PyAsyncGenASend_Send` | unknown |
| 3.10% | `python` | `_PyObject_Malloc` | memory |
| 2.42% | `python` | `async_gen_anext` | async |
| 2.30% | `python` | `_PyType_AllocNoTrack` | memory |
| 2.01% | `python` | `PyErr_ExceptionMatches` | exceptions |
| 1.96% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.84% | `python` | `gc_collect_main` | gc |
| 1.83% | `python` | `tuple_dealloc` | memory |
| 1.75% | `python` | `PyType_GenericAlloc` | memory |
| 1.67% | `python` | `_PyGen_FetchStopIterationValue` | miscobj |
| 1.62% | `python` | `_PyAsyncGenValueWrapperNew` | memory |
| 1.53% | `python` | `PyObject_CallOneArg` | dynamic |
| 1.51% | `python` | `async_gen_asend_dealloc` | memory |
| 1.49% | `python` | `async_gen_wrapped_val_dealloc` | memory |
| 1.48% | `python` | `StopIteration_dealloc` | memory |
| 1.45% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.21% | `python` | `_Py_NewReference` | memory |
| 1.18% | `python` | `type_call` | dynamic |
| 1.12% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 1.08% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.05% | `python` | `StopIteration_init` | dynamic |
| 1.04% | `python` | `tuple_alloc` | memory |
| 1.02% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.90% | `python` | `_PyJIT_Entry` | compiler |
| 0.84% | `python` | `BaseException_new` | memory |
| 0.78% | `python` | `PyObject_GC_Del` | gc |
| 0.71% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.71% | `python` | `_PyObject_GC_Link` | gc |
| 0.71% | `python` | `initialize_locals` | interpreter |
| 0.66% | `python` | `visit_decref` | gc |
| 0.64% | `python` | `_PyEval_GetANext` | interpreter |
| 0.64% | `python` | `visit_reachable` | gc |
| 0.64% | `python` | `make_range_object` | unknown |
| 0.63% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.58% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.58% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.50% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.49% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.48% | `python` | `PyType_IsSubtype` | dynamic |
| 0.46% | `python` | `range_subscript` | miscobj |
| 0.46% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.45% | `python` | `set_add_entry_takeref` | miscobj |
| 0.44% | `python` | `_PyLong_FromMedium` | int |
| 0.43% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.43% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.42% | `python` | `PyNumber_Add` | dynamic |
| 0.40% | `python` | `subtype_traverse` | gc |
| 0.40% | `python` | `_PyEval_Vector` | interpreter |
| 0.36% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.35% | `python` | `PyErr_SetRaisedException` | exceptions |
| 0.35% | `python` | `long_add_method` | int |
| 0.35% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.33% | `python` | `long_richcompare` | int |
| 0.30% | `python` | `set_lookkey` | miscobj |
| 0.30% | `python` | `PySlice_New` | memory |
| 0.29% | `python` | `PyErr_GetRaisedException` | exceptions |
| 0.29% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.27% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.27% | `python` | `range_dealloc` | memory |

## async_tree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.79% | `[JIT]` | `jit` | jit |
| 12.84% | `python` | `gc_collect_main` | gc |
| 6.08% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.20% | `python` | `visit_reachable` | gc |
| 4.71% | `python` | `visit_decref` | gc |
| 3.11% | `python` | `_PyObject_Malloc` | memory |
| 1.86% | `python` | `_PyObject_Free` | memory |
| 1.84% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.80% | `python` | `initialize_locals` | interpreter |
| 1.74% | `python` | `_Py_Dealloc` | memory |
| 1.40% | `python` | `subtype_traverse` | gc |
| 1.28% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.07% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.02% | `python` | `context_tp_dealloc` | memory |
| 0.98% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.97% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.88% | `python` | `_PyEval_Vector` | interpreter |
| 0.76% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.62% | `python` | `TaskObj_traverse` | gc |
| 0.59% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.55% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.55% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.53% | `python` | `_PyMember_GetOffset` | unknown |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.49% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.46% | `python` | `clear_slots` | unknown |
| 0.45% | `python` | `_Py_dict_lookup` | lookup |
| 0.44% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.44% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.42% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.42% | `python` | `tuple_dealloc` | memory |
| 0.41% | `python` | `_PyObject_Realloc` | memory |
| 0.40% | `python` | `_PyObject_GC_New` | gc |
| 0.38% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.36% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.36% | `python` | `_PyObject_Calloc` | memory |
| 0.36% | `python` | `gen_dealloc` | memory |
| 0.36% | `python` | `PyObject_Call` | dynamic |
| 0.36% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.35% | `python` | `tuple_alloc` | memory |
| 0.35% | `python` | `PyCMethod_New` | memory |
| 0.35% | `python` | `TaskObj_clear` | unknown |
| 0.34% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.33% | `python` | `PyUnicode_RichCompare` | str |
| 0.33% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.32% | `python` | `insert_to_emptydict` | dict |
| 0.32% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.32% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.31% | `python` | `PyIter_Send` | dynamic |
| 0.31% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.31% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.30% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `_PyType_GetDict` | dynamic |
| 0.30% | `python` | `context_tp_traverse` | gc |
| 0.30% | `python` | `PyObject_GC_Del` | gc |
| 0.30% | `python` | `subtype_dealloc` | memory |
| 0.30% | `python` | `context_run` | unknown |
| 0.28% | `python` | `gen_traverse` | gc |
| 0.28% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.26% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.25% | `python` | `task_step_impl` | unknown |

## async_tree_cpu_io_mixed

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.95% | `python` | `k_mul` | int |
| 8.39% | `[JIT]` | `jit` | jit |
| 7.75% | `python` | `gc_collect_main` | gc |
| 4.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.81% | `python` | `_PyObject_Malloc` | memory |
| 3.19% | `python` | `visit_reachable` | gc |
| 3.03% | `python` | `_PyObject_Free` | memory |
| 3.01% | `python` | `visit_decref` | gc |
| 2.68% | `python` | `PyErr_CheckSignals` | exceptions |
| 2.11% | `python` | `_Py_Dealloc` | memory |
| 1.67% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.41% | `_math_integer.cpython-316-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.38% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.09% | `python` | `PyThread_get_thread_ident` | threading |
| 1.05% | `python` | `initialize_locals` | interpreter |
| 1.05% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.96% | `python` | `subtype_traverse` | gc |
| 0.81% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.79% | `python` | `_Py_IsMainThread` | unknown |
| 0.71% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.64% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.62% | `python` | `PyNumber_Multiply` | dynamic |
| 0.61% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `context_tp_dealloc` | memory |
| 0.59% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.59% | `python` | `_PyEval_Vector` | interpreter |
| 0.54% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.48% | `python` | `long_mul` | int |
| 0.42% | `python` | `long_alloc` | memory |
| 0.40% | `python` | `long_lshift1` | int |
| 0.36% | `python` | `_Py_NewReference` | memory |
| 0.34% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.33% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.33% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.32% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.32% | `python` | `TaskObj_traverse` | gc |
| 0.32% | `python` | `_PyMember_GetOffset` | unknown |
| 0.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.29% | `python` | `pthread_self@plt` | unknown |
| 0.28% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.27% | `python` | `_PyInterpreterState_Main` | unknown |
| 0.26% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.25% | `python` | `_Py_dict_lookup` | lookup |

## async_tree_cpu_io_mixed_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.99% | `python` | `k_mul` | int |
| 8.94% | `python` | `gc_collect_main` | gc |
| 8.19% | `[JIT]` | `jit` | jit |
| 4.15% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.83% | `python` | `_PyObject_Malloc` | memory |
| 3.63% | `python` | `visit_reachable` | gc |
| 3.41% | `python` | `visit_decref` | gc |
| 2.98% | `python` | `_PyObject_Free` | memory |
| 2.62% | `python` | `PyErr_CheckSignals` | exceptions |
| 2.17% | `python` | `_Py_Dealloc` | memory |
| 1.43% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.38% | `_math_integer.cpython-316-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.34% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.13% | `python` | `PyThread_get_thread_ident` | threading |
| 1.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.85% | `python` | `subtype_traverse` | gc |
| 0.81% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.77% | `python` | `_Py_IsMainThread` | unknown |
| 0.75% | `python` | `initialize_locals` | interpreter |
| 0.67% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.66% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.60% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.59% | `python` | `_PyEval_Vector` | interpreter |
| 0.58% | `python` | `PyNumber_Multiply` | dynamic |
| 0.53% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.51% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.49% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.46% | `python` | `long_mul` | int |
| 0.43% | `python` | `long_alloc` | memory |
| 0.42% | `python` | `long_lshift1` | int |
| 0.42% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.41% | `python` | `TaskObj_traverse` | gc |
| 0.39% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.36% | `python` | `_PyMember_GetOffset` | unknown |
| 0.35% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.34% | `python` | `_Py_NewReference` | memory |
| 0.32% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.31% | `python` | `set_traverse` | gc |
| 0.30% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.29% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.27% | `python` | `gen_dealloc` | memory |
| 0.27% | `python` | `pthread_self@plt` | unknown |
| 0.27% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.27% | `python` | `long_dealloc` | memory |
| 0.26% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.26% | `python` | `_PyInterpreterState_Main` | unknown |

## async_tree_io

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.80% | `python` | `gc_collect_main` | gc |
| 12.35% | `[JIT]` | `jit` | jit |
| 7.72% | `python` | `visit_reachable` | gc |
| 7.42% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.31% | `python` | `visit_decref` | gc |
| 2.14% | `python` | `_PyObject_Malloc` | memory |
| 1.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.62% | `python` | `subtype_traverse` | gc |
| 1.58% | `python` | `initialize_locals` | interpreter |
| 1.26% | `python` | `_Py_Dealloc` | memory |
| 1.25% | `python` | `_PyObject_Free` | memory |
| 1.19% | `python` | `_PyEval_Vector` | interpreter |
| 1.19% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.06% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.91% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.90% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.72% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.69% | `_heapq.cpython-316-x86_64-linux-gnu.so` | `siftup` | library |
| 0.60% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.59% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.58% | `python` | `_PyMember_GetOffset` | unknown |
| 0.57% | `python` | `slot_tp_richcompare` | dynamic |
| 0.56% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.50% | `python` | `gen_traverse` | gc |
| 0.47% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.46% | `python` | `TaskObj_traverse` | gc |
| 0.43% | `python` | `_PyJIT_Entry` | compiler |
| 0.40% | `python` | `clear_slots` | unknown |
| 0.39% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.39% | `python` | `_PyObject_Realloc` | memory |
| 0.38% | `python` | `PyObject_IS_GC` | gc |
| 0.38% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.37% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.34% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.33% | `python` | `gen_dealloc` | memory |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.33% | `python` | `context_tp_dealloc` | memory |
| 0.30% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.30% | `python` | `_PyObject_Calloc` | memory |
| 0.30% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.30% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.29% | `python` | `list_traverse` | gc |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.27% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.27% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.26% | `python` | `insert_to_emptydict` | dict |
| 0.26% | `python` | `_Py_dict_lookup` | lookup |
| 0.26% | `python` | `tuple_alloc` | memory |
| 0.25% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.25% | `python` | `FutureObj_traverse` | gc |

## async_tree_io_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.26% | `python` | `gc_collect_main` | gc |
| 11.26% | `[JIT]` | `jit` | jit |
| 8.25% | `python` | `visit_reachable` | gc |
| 7.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.70% | `python` | `visit_decref` | gc |
| 2.13% | `python` | `_PyObject_Malloc` | memory |
| 1.62% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.50% | `python` | `subtype_traverse` | gc |
| 1.38% | `python` | `_PyEval_Vector` | interpreter |
| 1.34% | `python` | `initialize_locals` | interpreter |
| 1.28% | `python` | `_Py_Dealloc` | memory |
| 1.13% | `python` | `_PyObject_Free` | memory |
| 1.13% | `python` | `_PyGC_VisitFrameStack` | gc |
| 1.11% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.00% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.86% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.81% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `_heapq.cpython-316-x86_64-linux-gnu.so` | `siftup` | library |
| 0.66% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.58% | `python` | `gen_traverse` | gc |
| 0.57% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.57% | `python` | `_PyMember_GetOffset` | unknown |
| 0.56% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.53% | `python` | `slot_tp_richcompare` | dynamic |
| 0.49% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.48% | `python` | `TaskObj_traverse` | gc |
| 0.46% | `python` | `_PyJIT_Entry` | compiler |
| 0.43% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.40% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.38% | `python` | `clear_slots` | unknown |
| 0.38% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.38% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.36% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.36% | `python` | `gen_dealloc` | memory |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.34% | `python` | `set_traverse` | gc |
| 0.32% | `python` | `tuple_dealloc` | memory |
| 0.30% | `python` | `PyObject_Call` | dynamic |
| 0.28% | `python` | `_PyObject_Calloc` | memory |
| 0.28% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.28% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.26% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.25% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |

## async_tree_memoization

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.03% | `[JIT]` | `jit` | jit |
| 13.83% | `python` | `gc_collect_main` | gc |
| 8.22% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.74% | `python` | `visit_reachable` | gc |
| 5.40% | `python` | `visit_decref` | gc |
| 2.83% | `python` | `_PyObject_Malloc` | memory |
| 1.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.71% | `python` | `initialize_locals` | interpreter |
| 1.68% | `python` | `subtype_traverse` | gc |
| 1.56% | `python` | `_PyObject_Free` | memory |
| 1.52% | `python` | `_Py_Dealloc` | memory |
| 1.20% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.12% | `python` | `_PyEval_Vector` | interpreter |
| 1.06% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.98% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.96% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.93% | `python` | `context_tp_dealloc` | memory |
| 0.62% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.62% | `python` | `TaskObj_traverse` | gc |
| 0.57% | `python` | `_PyMember_GetOffset` | unknown |
| 0.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.50% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.49% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.48% | `python` | `_Py_dict_lookup` | lookup |
| 0.45% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.43% | `python` | `clear_slots` | unknown |
| 0.42% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.40% | `python` | `tuple_dealloc` | memory |
| 0.40% | `python` | `_PyJIT_Entry` | compiler |
| 0.37% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.36% | `python` | `_PyObject_Realloc` | memory |
| 0.36% | `python` | `TaskObj_clear` | unknown |
| 0.35% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.35% | `python` | `_PyObject_GC_New` | gc |
| 0.35% | `python` | `tuple_alloc` | memory |
| 0.35% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.34% | `python` | `gen_dealloc` | memory |
| 0.34% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.33% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.32% | `python` | `PyIter_Send` | dynamic |
| 0.32% | `python` | `_PyObject_Calloc` | memory |
| 0.31% | `python` | `list_dealloc` | memory |
| 0.31% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.31% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.31% | `python` | `PyObject_Call` | dynamic |
| 0.31% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.31% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.30% | `python` | `context_tp_traverse` | gc |
| 0.29% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.29% | `python` | `PyUnicode_RichCompare` | str |
| 0.29% | `python` | `gen_traverse` | gc |
| 0.29% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.28% | `python` | `PyCMethod_New` | memory |
| 0.28% | `python` | `list_extend_lock_held` | list |
| 0.28% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.27% | `python` | `insert_to_emptydict` | dict |
| 0.27% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.26% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.26% | `python` | `subtype_dealloc` | memory |
| 0.26% | `python` | `_Py_NewReference` | memory |
| 0.25% | `python` | `PyObject_GC_Del` | gc |

## async_tree_memoization_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.51% | `python` | `gc_collect_main` | gc |
| 14.04% | `[JIT]` | `jit` | jit |
| 7.01% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.70% | `python` | `visit_reachable` | gc |
| 6.11% | `python` | `visit_decref` | gc |
| 2.58% | `python` | `_PyObject_Malloc` | memory |
| 1.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.61% | `python` | `subtype_traverse` | gc |
| 1.59% | `python` | `_Py_Dealloc` | memory |
| 1.51% | `python` | `_PyObject_Free` | memory |
| 1.22% | `python` | `initialize_locals` | interpreter |
| 1.15% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.02% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.99% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.95% | `python` | `_PyEval_Vector` | interpreter |
| 0.85% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.84% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.73% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.64% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.63% | `python` | `TaskObj_traverse` | gc |
| 0.62% | `python` | `_PyMember_GetOffset` | unknown |
| 0.54% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.50% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.48% | `python` | `set_traverse` | gc |
| 0.45% | `python` | `_PyJIT_Entry` | compiler |
| 0.44% | `python` | `gen_traverse` | gc |
| 0.44% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.44% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `python` | `clear_slots` | unknown |
| 0.42% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.39% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.39% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.39% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.38% | `python` | `gen_dealloc` | memory |
| 0.37% | `python` | `PyObject_Call` | dynamic |
| 0.33% | `python` | `tuple_dealloc` | memory |
| 0.32% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.32% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.32% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.32% | `python` | `context_tp_traverse` | gc |
| 0.31% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.30% | `python` | `context_tp_dealloc` | memory |
| 0.29% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.29% | `python` | `_PyObject_GC_New` | gc |
| 0.29% | `python` | `_PyObject_Calloc` | memory |
| 0.29% | `python` | `dict_dealloc` | memory |
| 0.28% | `python` | `set_lookkey` | miscobj |
| 0.28% | `python` | `TaskObj_clear` | unknown |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.28% | `python` | `PyUnicode_RichCompare` | str |
| 0.27% | `python` | `tuple_alloc` | memory |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `PyCMethod_New` | memory |
| 0.26% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.26% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.26% | `python` | `_Py_NewReference` | memory |
| 0.25% | `python` | `_PyObject_VectorcallPrepend` | dynamic |

## async_tree_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.31% | `[JIT]` | `jit` | jit |
| 14.76% | `python` | `gc_collect_main` | gc |
| 6.05% | `python` | `visit_reachable` | gc |
| 5.22% | `python` | `visit_decref` | gc |
| 5.05% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.11% | `python` | `_PyObject_Malloc` | memory |
| 1.89% | `python` | `_Py_Dealloc` | memory |
| 1.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.70% | `python` | `_PyObject_Free` | memory |
| 1.41% | `python` | `initialize_locals` | interpreter |
| 1.23% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.20% | `python` | `subtype_traverse` | gc |
| 1.12% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.09% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.99% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.92% | `python` | `_PyEval_Vector` | interpreter |
| 0.85% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.76% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.76% | `python` | `TaskObj_traverse` | gc |
| 0.75% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.61% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.58% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.57% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.56% | `python` | `set_traverse` | gc |
| 0.55% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.51% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.49% | `python` | `clear_slots` | unknown |
| 0.48% | `python` | `_PyMember_GetOffset` | unknown |
| 0.47% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.47% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.45% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `python` | `gen_traverse` | gc |
| 0.41% | `python` | `PyObject_Call` | dynamic |
| 0.40% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.40% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.39% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.37% | `python` | `gen_dealloc` | memory |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.36% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.36% | `python` | `_PyObject_GC_New` | gc |
| 0.36% | `python` | `PyUnicode_RichCompare` | str |
| 0.35% | `python` | `_PyObject_Calloc` | memory |
| 0.34% | `python` | `PyObject_GC_Del` | gc |
| 0.34% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.33% | `python` | `context_tp_traverse` | gc |
| 0.32% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.31% | `python` | `_PyJIT_Entry` | compiler |
| 0.30% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `python` | `dict_dealloc` | memory |
| 0.28% | `python` | `context_tp_dealloc` | memory |
| 0.28% | `python` | `PyCMethod_New` | memory |
| 0.28% | `python` | `tuple_alloc` | memory |
| 0.27% | `python` | `_PyObject_VectorcallPrepend` | dynamic |
| 0.27% | `python` | `_asyncio_Task___init__` | unknown |
| 0.27% | `python` | `PyDict_New` | memory |
| 0.26% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.25% | `python` | `allocate_from_new_pool` | memory |
| 0.25% | `python` | `method_traverse` | gc |
| 0.25% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |

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
| 4.97% | `libz.so.1.3` | `0x0000000000008c1c` | library |
| 3.79% | `libz.so.1.3` | `0x0000000000008c20` | library |
| 3.62% | `libz.so.1.3` | `0x0000000000002dba` | library |
| 3.57% | `libz.so.1.3` | `0x0000000000002da3` | library |
| 3.55% | `libz.so.1.3` | `0x0000000000008bf7` | library |
| 3.55% | `libz.so.1.3` | `0x0000000000002db1` | library |
| 3.53% | `libz.so.1.3` | `0x0000000000002dc6` | library |
| 3.46% | `libz.so.1.3` | `0x0000000000002db6` | library |
| 3.42% | `libz.so.1.3` | `0x0000000000002dae` | library |
| 2.31% | `libz.so.1.3` | `0x0000000000008192` | library |
| 2.31% | `libz.so.1.3` | `0x0000000000008be6` | library |
| 2.23% | `libz.so.1.3` | `0x0000000000008c25` | library |
| 2.22% | `libz.so.1.3` | `0x00000000000082aa` | library |
| 1.97% | `libz.so.1.3` | `0x0000000000008c2c` | library |
| 1.96% | `libz.so.1.3` | `0x0000000000008bed` | library |
| 1.91% | `libz.so.1.3` | `0x0000000000008bd6` | library |
| 1.86% | `libz.so.1.3` | `0x0000000000008c07` | library |
| 1.83% | `libz.so.1.3` | `0x00000000000082b7` | library |
| 1.81% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.77% | `libz.so.1.3` | `0x000000000000819f` | library |
| 1.72% | `libz.so.1.3` | `0x0000000000008c18` | library |
| 1.46% | `libz.so.1.3` | `0x0000000000008c2f` | library |
| 1.41% | `libz.so.1.3` | `0x0000000000008bdf` | library |
| 1.40% | `libz.so.1.3` | `0x0000000000008bf1` | library |
| 1.38% | `libz.so.1.3` | `0x0000000000008c0a` | library |
| 1.37% | `libz.so.1.3` | `0x0000000000008bfa` | library |
| 1.33% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.16% | `libz.so.1.3` | `0x0000000000008c01` | library |
| 1.00% | `libz.so.1.3` | `0x0000000000008bd0` | library |
| 0.97% | `libz.so.1.3` | `0x0000000000008c14` | library |
| 0.97% | `libz.so.1.3` | `0x0000000000008c2a` | library |
| 0.94% | `libz.so.1.3` | `0x0000000000008c0e` | library |
| 0.92% | `libz.so.1.3` | `0x0000000000008140` | library |
| 0.90% | `libz.so.1.3` | `0x0000000000008279` | library |
| 0.90% | `libz.so.1.3` | `0x000000000000828a` | library |
| 0.89% | `libz.so.1.3` | `0x000000000000814f` | library |
| 0.89% | `libz.so.1.3` | `0x0000000000008267` | library |
| 0.89% | `libz.so.1.3` | `0x0000000000008182` | library |
| 0.89% | `libz.so.1.3` | `0x0000000000008258` | library |
| 0.88% | `libz.so.1.3` | `0x0000000000008172` | library |
| 0.88% | `libz.so.1.3` | `0x0000000000008161` | library |
| 0.85% | `libz.so.1.3` | `0x000000000000829a` | library |
| 0.63% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.57% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.54% | `libz.so.1.3` | `0x000000000000242e` | library |
| 0.54% | `libz.so.1.3` | `0x0000000000002419` | library |
| 0.53% | `libz.so.1.3` | `0x0000000000002416` | library |
| 0.49% | `libz.so.1.3` | `0x00000000000023f4` | library |
| 0.47% | `libz.so.1.3` | `0x00000000000082ae` | library |
| 0.45% | `libz.so.1.3` | `0x0000000000008196` | library |
| 0.43% | `libz.so.1.3` | `0x0000000000008c28` | library |
| 0.42% | `libz.so.1.3` | `0x0000000000008c37` | library |
| 0.41% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.41% | `libz.so.1.3` | `0x0000000000008bfe` | library |
| 0.41% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.41% | `libz.so.1.3` | `0x0000000000008be3` | library |
| 0.37% | `libz.so.1.3` | `0x0000000000002403` | library |
| 0.35% | `libz.so.1.3` | `0x000000000000827d` | library |
| 0.34% | `libz.so.1.3` | `0x0000000000008144` | library |
| 0.34% | `libz.so.1.3` | `0x00000000000082bb` | library |
| 0.33% | `libz.so.1.3` | `0x000000000000829e` | library |
| 0.33% | `libz.so.1.3` | `0x000000000000828e` | library |
| 0.32% | `libz.so.1.3` | `0x0000000000008165` | library |
| 0.32% | `libz.so.1.3` | `0x0000000000008154` | library |
| 0.32% | `libz.so.1.3` | `0x0000000000008186` | library |
| 0.31% | `libz.so.1.3` | `0x000000000000825c` | library |
| 0.31% | `libz.so.1.3` | `0x000000000000826c` | library |
| 0.31% | `libz.so.1.3` | `0x00000000000081a3` | library |
| 0.31% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.31% | `libz.so.1.3` | `0x0000000000008176` | library |
| 0.26% | `libz.so.1.3` | `0x00000000000023f0` | library |

## base64

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 9.76% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_ascii85` | library |
| 8.60% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base85` | library |
| 8.11% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base64` | library |
| 6.85% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base32` | library |
| 6.44% | `[JIT]` | `jit` | jit |
| 5.59% | `python` | `bytes_translate_impl` | str |
| 5.46% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base32` | library |
| 5.41% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base64` | library |
| 4.47% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_hex_impl.isra.0` | library |
| 4.08% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_ascii85` | library |
| 3.06% | `python` | `_PyArg_UnpackKeywords` | calls |
| 2.63% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base85` | library |
| 2.04% | `python` | `initialize_locals` | interpreter |
| 1.81% | `python` | `_Py_bytes_upper` | unknown |
| 1.70% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.59% | `python` | `PyDict_GetItemRef` | dict |
| 1.50% | `python` | `_PyObject_Malloc` | memory |
| 1.37% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 1.27% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.27% | `python` | `_PyObject_Free` | memory |
| 1.21% | `python` | `_Py_dict_lookup` | lookup |
| 1.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.97% | `python` | `PyBytesWriter_Create` | unknown |
| 0.91% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.60% | `python` | `_Py_Dealloc` | memory |
| 0.56% | `libc.so.6` | `__memchr_avx2` | libc |
| 0.56% | `python` | `PyBuffer_FillInfo` | miscobj |
| 0.56% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.54% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.51% | `python` | `PyBytesWriter_FinishWithPointer` | unknown |
| 0.51% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.50% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.44% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.43% | `python` | `PyBuffer_Release` | miscobj |
| 0.35% | `python` | `cfunction_vectorcall_FASTCALL_KEYWORDS` | calls |
| 0.33% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.31% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.30% | `python` | `_Py_strhex_impl` | unknown |
| 0.25% | `python` | `_PyThreadState_PushFrame` | threading |

## bpe_tokeniser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.60% | `[JIT]` | `jit` | jit |
| 4.89% | `python` | `_Py_dict_lookup` | lookup |
| 4.41% | `python` | `_Py_Dealloc` | memory |
| 3.98% | `python` | `tuple_dealloc` | memory |
| 3.76% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.98% | `python` | `gc_collect_main` | gc |
| 2.75% | `python` | `list_dealloc` | memory |
| 2.70% | `python` | `_PyObject_Free` | memory |
| 2.24% | `python` | `tuple_alloc` | memory |
| 2.13% | `python` | `_PyObject_Malloc` | memory |
| 2.13% | `python` | `listiter_next` | list |
| 1.94% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 1.84% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.83% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.59% | `python` | `zip_next` | unknown |
| 1.42% | `python` | `visit_decref` | gc |
| 1.35% | `python` | `visit_reachable` | gc |
| 1.30% | `python` | `list_traverse` | gc |
| 1.25% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.25% | `python` | `list_slice_lock_held` | list |
| 1.25% | `python` | `PyTuple_New` | memory |
| 1.24% | `python` | `PyList_New.constprop.0` | memory |
| 1.23% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.20% | `python` | `tuple_richcompare` | tuple |
| 1.04% | `python` | `list_iter` | list |
| 1.01% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.97% | `python` | `_PyCompactLong_Add` | unknown |
| 0.97% | `python` | `tuple_hash` | tuple |
| 0.91% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.89% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.83% | `python` | `_Py_NewReference` | memory |
| 0.81% | `python` | `insertdict` | dict |
| 0.80% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.74% | `python` | `listiter_dealloc` | memory |
| 0.72% | `python` | `zip_new` | memory |
| 0.67% | `python` | `PyObject_Hash` | dynamic |
| 0.65% | `python` | `slot_mp_ass_subscript` | unknown |
| 0.59% | `python` | `_PyDict_Subscript` | dict |
| 0.55% | `python` | `wrapperdescr_call` | unknown |
| 0.52% | `python` | `PyLong_FromSsize_t` | int |
| 0.51% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.48% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.48% | `python` | `dictiter_iternextkey` | dict |
| 0.47% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.46% | `python` | `_PyEval_Vector` | interpreter |
| 0.46% | `python` | `bytes_richcompare` | str |
| 0.46% | `python` | `_PyList_BinarySlice` | list |
| 0.44% | `python` | `PyArg_UnpackTuple` | calls |
| 0.43% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.43% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.42% | `python` | `PyObject_RichCompare` | dynamic |
| 0.41% | `python` | `_PyJIT_Entry` | compiler |
| 0.40% | `python` | `initialize_locals` | interpreter |
| 0.39% | `python` | `PyType_GenericAlloc` | memory |
| 0.38% | `python` | `wrap_objobjargproc` | unknown |
| 0.38% | `python` | `PyObject_Size` | dynamic |
| 0.37% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.37% | `python` | `PySlice_Unpack` | miscobj |
| 0.37% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.36% | `python` | `_PyObject_Realloc` | memory |
| 0.35% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.34% | `python` | `_PyObject_GC_New` | gc |
| 0.34% | `python` | `PyObject_GetIter` | dynamic |
| 0.34% | `python` | `zip_dealloc` | memory |
| 0.33% | `python` | `PyObject_GetItem` | dynamic |
| 0.33% | `python` | `list_slice_wrap` | list |
| 0.29% | `python` | `PyObject_GC_Del` | gc |
| 0.29% | `python` | `_PyList_SliceSubscript` | list |
| 0.29% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.28% | `python` | `type_call` | dynamic |
| 0.26% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.26% | `python` | `_PyObject_RealIsSubclass` | dynamic |
| 0.25% | `python` | `PyObject_SetItem` | dynamic |

## chameleon

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.70% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.79% | `[JIT]` | `jit` | jit |
| 5.95% | `python` | `_PyObject_Malloc` | memory |
| 3.86% | `python` | `unicode_from_format` | str |
| 2.69% | `python` | `_PyObject_Free` | memory |
| 2.61% | `python` | `_PyUnicode_ResizeCompact` | str |
| 2.33% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.09% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.68% | `python` | `_PyObject_Realloc` | memory |
| 1.64% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 1.52% | `python` | `_Py_dict_lookup` | lookup |
| 1.41% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 1.27% | `python` | `_Py_Dealloc` | memory |
| 1.27% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.17% | `python` | `long_to_decimal_string_internal` | int |
| 1.04% | `python` | `list_append` | list |
| 1.00% | `python` | `PyUnicode_New` | memory |
| 0.99% | `python` | `PyDict_GetItemRef` | dict |
| 0.98% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.96% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.94% | `python` | `PyUnicode_Format` | str |
| 0.88% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.88% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.82% | `python` | `dict_get` | dict |
| 0.82% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.79% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 0.78% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.78% | `python` | `AttributeError_dealloc` | memory |
| 0.74% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.74% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.71% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.65% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.63% | `python` | `_PyUnicodeWriter_WriteASCIIString` | str |
| 0.56% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.55% | `python` | `_PyJIT_Entry` | compiler |
| 0.52% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.49% | `python` | `_PyUnicodeWriter_Finish` | str |
| 0.47% | `python` | `PyType_IsSubtype` | dynamic |
| 0.45% | `python` | `unicode_fromformat_write_str` | str |
| 0.44% | `python` | `PyType_GetFullyQualifiedName` | unknown |
| 0.44% | `python` | `insertdict` | dict |
| 0.43% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.42% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.42% | `python` | `unicode_dealloc` | memory |
| 0.41% | `python` | `method_vectorcall_FASTCALL` | calls |
| 0.41% | `python` | `_PyUnicode_DecodeUTF8Writer` | str |
| 0.41% | `libc.so.6` | `malloc` | libc |
| 0.40% | `python` | `listiter_next` | list |
| 0.40% | `python` | `PyErr_Format` | exceptions |
| 0.38% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.37% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.36% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.36% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.35% | `python` | `_PySuper_Lookup` | dynamic |
| 0.34% | `python` | `PyErr_ExceptionMatches` | exceptions |
| 0.33% | `python` | `sre_search` | library |
| 0.33% | `python` | `unicode_fromformat_write_utf8` | str |
| 0.33% | `python` | `tuple_dealloc` | memory |
| 0.33% | `python` | `PyNumber_Remainder` | dynamic |
| 0.33% | `python` | `PyArg_ParseTupleAndKeywords` | calls |
| 0.33% | `python` | `tuple_alloc` | memory |
| 0.32% | `python` | `delitem_common` | dynamic |
| 0.32% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.32% | `python` | `_PyUnicode_Result` | str |
| 0.32% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.31% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.31% | `python` | `builtin_getattr` | lookup |
| 0.30% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.30% | `python` | `list_dealloc` | memory |
| 0.29% | `python` | `PyObject_Str` | dynamic |
| 0.29% | `python` | `memcpy@plt` | memory |
| 0.29% | `python` | `AttributeError_init` | exceptions |
| 0.28% | `python` | `PyMember_GetOne` | lookup |
| 0.28% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.28% | `python` | `PyType_GenericAlloc` | memory |
| 0.28% | `python` | `_PyUnicodeWriter_WriteSubstring` | str |
| 0.25% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.25% | `python` | `find_first_nonascii` | str |
| 0.25% | `python` | `_Py_NewReference` | memory |

## chaos

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.87% | `[JIT]` | `jit` | jit |
| 9.18% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.68% | `python` | `_Py_Dealloc` | memory |
| 2.84% | `python` | `_PyCompactLong_Subtract` | unknown |
| 2.68% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.01% | `python` | `make_range_object` | unknown |
| 1.99% | `python` | `PyFloat_FromDouble` | float |
| 1.86% | `python` | `_PyCompactLong_Add` | unknown |
| 1.38% | `python` | `range_iter` | miscobj |
| 1.34% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 1.34% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.31% | `python` | `initialize_locals` | interpreter |
| 1.23% | `python` | `float_richcompare` | float |
| 1.22% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.16% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 1.16% | `python` | `_PyObject_Free` | memory |
| 1.15% | `python` | `_Py_NewReference` | memory |
| 1.10% | `python` | `float_pow` | float |
| 1.02% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.99% | `python` | `PyLong_FromLong` | int |
| 0.88% | `python` | `PyType_IsSubtype` | dynamic |
| 0.84% | `python` | `float_compactlong_true_div` | float |
| 0.82% | `python` | `float_dealloc` | memory |
| 0.80% | `python` | `subtype_dealloc` | memory |
| 0.79% | `python` | `_PyObject_Malloc` | memory |
| 0.69% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.69% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.67% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.65% | `python` | `PyLong_AsLong` | int |
| 0.59% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.55% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.53% | `python` | `_PyJIT_Entry` | compiler |
| 0.51% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.47% | `python` | `PyObject_RichCompare` | dynamic |
| 0.46% | `python` | `PyType_GenericAlloc` | memory |
| 0.46% | `python` | `range_vectorcall` | miscobj |
| 0.41% | `python` | `PyNumber_Index` | dynamic |
| 0.37% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.37% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.36% | `python` | `PyLong_AsDouble` | int |
| 0.36% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.36% | `python` | `tuple_alloc` | memory |
| 0.35% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.35% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.32% | `python` | `PyObject_GetIter` | dynamic |
| 0.31% | `python` | `_PyEval_Vector` | interpreter |
| 0.25% | `python` | `range_dealloc` | memory |
| 0.25% | `python` | `list_dealloc` | memory |

## comprehensions

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 39.55% | `[JIT]` | `jit` | jit |
| 7.26% | `python` | `_Py_dict_lookup` | lookup |
| 3.68% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 3.22% | `python` | `_PyObject_Malloc` | memory |
| 2.98% | `python` | `dict_get` | dict |
| 2.90% | `python` | `_PyObject_Free` | memory |
| 2.34% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.05% | `python` | `_PyObject_Realloc` | memory |
| 1.54% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.53% | `python` | `long_richcompare` | int |
| 1.49% | `python` | `_PyDict_Subscript` | dict |
| 1.47% | `python` | `_Py_Dealloc` | memory |
| 1.46% | `python` | `insertdict` | dict |
| 1.25% | `python` | `PyObject_Hash` | dynamic |
| 1.25% | `python` | `PyFunction_NewWithQualName` | memory |
| 1.21% | `python` | `long_hash` | int |
| 1.19% | `python` | `unsafe_tuple_compare` | unknown |
| 1.12% | `python` | `list_dealloc` | memory |
| 1.11% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.03% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.00% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.83% | `python` | `PyObject_GetItem` | dynamic |
| 0.83% | `python` | `list_sort_impl` | list |
| 0.81% | `python` | `func_clear` | unknown |
| 0.80% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.80% | `python` | `gen_dealloc` | memory |
| 0.74% | `python` | `PyObject_RichCompare` | dynamic |
| 0.63% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.61% | `python` | `func_dealloc` | memory |
| 0.59% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.55% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.54% | `python` | `PyDict_GetItemRef` | dict |
| 0.51% | `python` | `tuple_dealloc` | memory |
| 0.50% | `python` | `PyObject_IsTrue` | dynamic |
| 0.49% | `python` | `PyList_New.constprop.0` | memory |
| 0.44% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.41% | `python` | `_PyObject_GC_New` | gc |
| 0.40% | `python` | `tuple_alloc` | memory |
| 0.38% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.36% | `python` | `make_gen` | miscobj |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.35% | `python` | `unsafe_object_compare` | unknown |
| 0.35% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.35% | `python` | `tuple_subscript` | tuple |
| 0.35% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.32% | `python` | `gen_close` | unknown |
| 0.32% | `python` | `PyObject_GC_Del` | gc |
| 0.31% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.30% | `python` | `_PyEval_NoToolsForUnwind` | interpreter |
| 0.29% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `build_indices_generic` | unknown |
| 0.25% | `python` | `_Py_NewReference` | memory |

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
| 55.08% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.39% | `python` | `gen_dealloc` | memory |
| 4.69% | `python` | `_PyObject_Malloc` | memory |
| 3.89% | `python` | `make_gen` | miscobj |
| 3.66% | `python` | `_PyObject_Free` | memory |
| 3.42% | `python` | `_PyObject_GC_NewVar` | gc |
| 2.81% | `python` | `_PyCompactLong_Subtract` | unknown |
| 2.73% | `python` | `_Py_Dealloc` | memory |
| 2.39% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.03% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.96% | `python` | `_PyEval_GetAwaitable` | interpreter |
| 1.93% | `python` | `_PyCompactLong_Add` | unknown |
| 1.92% | `python` | `_PyCoro_GetAwaitableIter` | unknown |
| 1.87% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.79% | `python` | `_Py_MakeCoro` | unknown |
| 1.12% | `python` | `PyObject_GC_Del` | gc |
| 0.88% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.80% | `python` | `_PyObject_GC_Link` | gc |
| 0.50% | `python` | `_Py_NewReference` | memory |
| 0.43% | `python` | `gen_finalize` | unknown |
| 0.35% | `python` | `PyObject_Malloc` | dynamic |
| 0.26% | `python` | `PyObject_Free` | dynamic |

## coverage

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.15% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.84% | `python` | `call_instrumentation_vector.part.0.isra.0` | interpreter |
| 7.33% | `tracer.cpython-316-x86_64-linux-gnu.so` | `CTracer_trace` | library |
| 6.27% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 5.52% | `python` | `_Py_call_instrumentation_line` | interpreter |
| 3.50% | `python` | `_Py_dict_lookup` | lookup |
| 3.47% | `python` | `_PyObject_Free` | memory |
| 2.93% | `python` | `_PyObject_Malloc` | memory |
| 2.36% | `python` | `PyDict_GetItem` | dict |
| 2.12% | `python` | `set_add_entry_takeref` | miscobj |
| 2.00% | `python` | `siphash13` | str |
| 1.72% | `python` | `PyLong_FromLong` | int |
| 1.49% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 1.41% | `python` | `_Py_Dealloc` | memory |
| 1.34% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.26% | `python` | `PyUnicode_InternFromString` | str |
| 1.23% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 1.10% | `python` | `PySet_Add` | miscobj |
| 1.09% | `python` | `_PyCode_GetCode` | interpreter |
| 1.09% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.98% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.98% | `python` | `find_first_nonascii` | str |
| 0.93% | `tracer.cpython-316-x86_64-linux-gnu.so` | `CTracer_set_pdata_stack.constprop.0` | library |
| 0.87% | `python` | `PyFrame_GetCode` | exceptions |
| 0.85% | `python` | `PyUnicode_New.part.0` | memory |
| 0.83% | `python` | `PyObject_SetAttr` | dynamic |
| 0.83% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.82% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.81% | `python` | `PyEval_GetFrame` | interpreter |
| 0.78% | `python` | `_Py_call_instrumentation_arg` | unknown |
| 0.76% | `python` | `sys_trace_return` | library |
| 0.76% | `python` | `PyObject_GC_Del` | gc |
| 0.72% | `python` | `sys_trace_start` | library |
| 0.69% | `python` | `PyObject_Hash` | dynamic |
| 0.67% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.63% | `python` | `_PyDict_LoadGlobalStackRef` | dict |
| 0.62% | `python` | `frame_dealloc` | memory |
| 0.61% | `python` | `_PyUnicode_InternMortal` | str |
| 0.59% | `python` | `_Py_call_instrumentation` | unknown |
| 0.58% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.56% | `python` | `_PyFrame_MakeAndSetFrameObject` | interpreter |
| 0.54% | `python` | `PyObject_SetAttrString` | dynamic |
| 0.53% | `python` | `long_hash` | int |
| 0.52% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.50% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.48% | `python` | `_PyEval_LoadGlobalStackRef` | interpreter |
| 0.48% | `python` | `unicode_dealloc` | memory |
| 0.47% | `python` | `_PyCompactLong_Add` | unknown |
| 0.47% | `python` | `hashtable_unicode_hash` | unknown |
| 0.42% | `python` | `frame_trace_set` | unknown |
| 0.42% | `python` | `getset_set` | unknown |
| 0.40% | `python` | `PyFrame_GetLineNumber` | exceptions |
| 0.40% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.36% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `_Py_NewReference` | memory |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.27% | `python` | `_PyObject_GC_Link` | gc |
| 0.26% | `python` | `_Py_hashtable_get` | lookup |
| 0.26% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.26% | `python` | `_PyErr_GetRaisedException` | exceptions |
| 0.25% | `python` | `PyFrame_GetLasti` | exceptions |

## crypto_pyaes

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.10% | `[JIT]` | `jit` | jit |
| 7.00% | `python` | `long_bitwise` | int |
| 6.28% | `python` | `_PyObject_Free` | memory |
| 4.79% | `python` | `_PyObject_Malloc` | memory |
| 4.58% | `python` | `_Py_Dealloc` | memory |
| 3.74% | `python` | `long_rshift1` | int |
| 3.33% | `python` | `long_alloc` | memory |
| 3.03% | `python` | `l_mod` | int |
| 2.01% | `python` | `long_rshift` | int |
| 1.79% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.72% | `python` | `maybe_small_long` | unknown |
| 1.61% | `python` | `PyNumber_Xor` | dynamic |
| 1.39% | `python` | `PyLong_FromLong` | int |
| 1.30% | `python` | `PyNumber_Rshift` | dynamic |
| 1.28% | `python` | `long_dealloc` | memory |
| 1.17% | `python` | `_PyCompactLong_Add` | unknown |
| 1.16% | `python` | `PyLong_FromSsize_t` | int |
| 1.12% | `python` | `compactlongs_guard` | unknown |
| 1.07% | `python` | `PyNumber_Remainder` | dynamic |
| 1.03% | `python` | `long_mod` | int |
| 0.93% | `python` | `_Py_NewReference` | memory |
| 0.92% | `python` | `long_xor` | int |
| 0.90% | `python` | `make_range_object` | unknown |
| 0.72% | `python` | `_PyLong_FromMedium` | int |
| 0.61% | `python` | `compactlongs_and` | unknown |
| 0.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.55% | `python` | `range_iter` | miscobj |
| 0.52% | `python` | `list_dealloc` | memory |
| 0.37% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.36% | `python` | `PyObject_Malloc` | dynamic |
| 0.33% | `python` | `set_lookkey` | miscobj |
| 0.33% | `python` | `PyNumber_And` | dynamic |
| 0.32% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.29% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.28% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.28% | `python` | `PyObject_Free` | dynamic |
| 0.25% | `python` | `PyList_New.constprop.0` | memory |

## deepcopy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.54% | `[JIT]` | `jit` | jit |
| 5.41% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.37% | `python` | `_Py_dict_lookup` | lookup |
| 3.87% | `python` | `_PyObject_Malloc` | memory |
| 3.52% | `python` | `_PyObject_Free` | memory |
| 3.38% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.42% | `python` | `set_lookkey` | miscobj |
| 2.29% | `python` | `_Py_Dealloc` | memory |
| 1.54% | `python` | `dict_get` | dict |
| 1.38% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.34% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 1.23% | `python` | `list_append` | list |
| 1.14% | `python` | `PyLong_FromVoidPtr` | int |
| 1.08% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.07% | `python` | `_PySet_Contains` | miscobj |
| 1.06% | `python` | `PyObject_Hash` | dynamic |
| 1.00% | `python` | `long_richcompare` | int |
| 0.98% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.97% | `python` | `initialize_locals` | interpreter |
| 0.96% | `python` | `sys_audit_tstate` | unknown |
| 0.90% | `python` | `_PyObject_Realloc` | memory |
| 0.83% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.82% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.75% | `python` | `long_hash` | int |
| 0.74% | `python` | `insertdict` | dict |
| 0.73% | `python` | `PySys_Audit` | unknown |
| 0.71% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.69% | `python` | `dictiter_iternextitem` | dict |
| 0.66% | `python` | `builtin_id` | unknown |
| 0.65% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.64% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.62% | `python` | `list_dealloc` | memory |
| 0.53% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.52% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.47% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `insert_to_emptydict` | dict |
| 0.42% | `python` | `_Py_NewReference` | memory |
| 0.41% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.40% | `python` | `dict_dealloc` | memory |
| 0.36% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.35% | `python` | `PyObject_SetItem` | dynamic |
| 0.34% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.34% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.33% | `python` | `PyType_IsSubtype` | dynamic |
| 0.33% | `python` | `tuple_alloc` | memory |
| 0.32% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.31% | `python` | `_PyObject_Calloc` | memory |
| 0.30% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.29% | `python` | `PyCMethod_New` | memory |
| 0.28% | `python` | `new_dict` | dict |
| 0.25% | `python` | `_PyDict_Subscript` | dict |

## deltablue

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.39% | `[JIT]` | `jit` | jit |
| 10.26% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.25% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.70% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 2.28% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.08% | `python` | `gc_collect_main` | gc |
| 1.97% | `python` | `listiter_next` | list |
| 1.73% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.27% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.22% | `python` | `_PyObject_Malloc` | memory |
| 1.18% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.96% | `python` | `_Py_Dealloc` | memory |
| 0.84% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.77% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.76% | `python` | `visit_decref` | gc |
| 0.71% | `python` | `_PyObject_Free` | memory |
| 0.62% | `python` | `_PyJIT_Entry` | compiler |
| 0.57% | `python` | `_Py_type_getattro` | lookup |
| 0.51% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.45% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.43% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.43% | `python` | `PyMethod_New` | memory |
| 0.42% | `python` | `PyType_IsSubtype` | dynamic |
| 0.39% | `python` | `long_to_decimal_string_internal` | int |
| 0.38% | `python` | `_PyType_GetDict` | dynamic |
| 0.38% | `python` | `subtype_dealloc` | memory |
| 0.37% | `python` | `_PyCompactLong_Add` | unknown |
| 0.37% | `python` | `PyDict_GetItemRef` | dict |
| 0.36% | `python` | `subtype_traverse` | gc |
| 0.36% | `python` | `PyObject_RichCompare` | dynamic |
| 0.33% | `python` | `list_iter` | list |
| 0.33% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.32% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.30% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.30% | `python` | `list_pop` | list |
| 0.29% | `python` | `object_richcompare` | dynamic |
| 0.29% | `python` | `method_dealloc` | memory |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `list_append` | list |
| 0.25% | `python` | `_Py_dict_lookup` | lookup |

## django_template

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.09% | `[JIT]` | `jit` | jit |
| 9.39% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.36% | `python` | `_PyObject_Malloc` | memory |
| 2.66% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.37% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.93% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.89% | `python` | `_PyObject_Free` | memory |
| 1.80% | `python` | `_Py_Dealloc` | memory |
| 1.67% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.58% | `python` | `replace` | str |
| 1.53% | `python` | `initialize_locals` | interpreter |
| 1.17% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.10% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.08% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.01% | `python` | `_Py_dict_lookup` | lookup |
| 0.99% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.92% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.86% | `python` | `unicode_replace` | str |
| 0.78% | `python` | `long_to_decimal_string_internal` | int |
| 0.76% | `python` | `PyType_IsSubtype` | dynamic |
| 0.75% | `python` | `PyObject_SetItem` | dynamic |
| 0.71% | `python` | `insertdict` | dict |
| 0.69% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.67% | `python` | `listiter_next` | list |
| 0.65% | `python` | `_PyEvalFramePushAndInit_Ex` | interpreter |
| 0.64% | `python` | `tuple_alloc` | memory |
| 0.61% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.58% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.55% | `python` | `enum_next` | miscobj |
| 0.52% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.50% | `python` | `object_isinstance` | dynamic |
| 0.49% | `python` | `_PyJIT_Entry` | compiler |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `func_clear` | unknown |
| 0.42% | `python` | `_PyObject_GC_New` | gc |
| 0.41% | `python` | `_PyType_GetDict` | dynamic |
| 0.39% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.39% | `python` | `PyDict_New` | memory |
| 0.38% | `python` | `dict_dealloc` | memory |
| 0.37% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.35% | `python` | `_PyObject_Calloc` | memory |
| 0.33% | `python` | `PyDict_GetItemRef` | dict |
| 0.33% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.32% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.31% | `python` | `list_subscript` | list |
| 0.31% | `python` | `tuple_iter` | tuple |
| 0.30% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.30% | `python` | `PyObject_GetItem` | dynamic |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.29% | `python` | `PyObject_IsInstance` | dynamic |
| 0.28% | `python` | `slot_sq_contains` | unknown |
| 0.27% | `python` | `new_dict` | dict |
| 0.26% | `python` | `PyObject_Str` | dynamic |
| 0.25% | `python` | `chain_next` | unknown |

## docutils

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.62% | `[JIT]` | `jit` | jit |
| 9.80% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.23% | `python` | `sre_ucs1_match` | library |
| 5.79% | `python` | `gc_collect_main` | gc |
| 3.04% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.90% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.47% | `python` | `_PyObject_Malloc` | memory |
| 1.81% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.69% | `python` | `visit_decref` | gc |
| 1.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.58% | `python` | `sre_ucs1_charset.isra.0` | library |
| 1.58% | `python` | `_Py_dict_lookup` | lookup |
| 1.51% | `python` | `_PyObject_Free` | memory |
| 1.33% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.27% | `python` | `list_dealloc` | memory |
| 1.19% | `python` | `_Py_Dealloc` | memory |
| 0.97% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.85% | `python` | `initialize_locals` | interpreter |
| 0.77% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.75% | `python` | `visit_reachable` | gc |
| 0.65% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.65% | `python` | `PyType_IsSubtype` | dynamic |
| 0.58% | `python` | `_PyJIT_Entry` | compiler |
| 0.53% | `python` | `list_slice_lock_held` | list |
| 0.52% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.49% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.48% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.46% | `python` | `sre_ucs1_count` | library |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.44% | `python` | `PyUnicode_Format` | str |
| 0.43% | `python` | `list_extend_lock_held` | list |
| 0.39% | `python` | `PyObject_SetAttr` | dynamic |
| 0.38% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.36% | `python` | `find_name_in_mro` | lookup |
| 0.36% | `python` | `list_traverse` | gc |
| 0.36% | `python` | `tuple_alloc` | memory |
| 0.35% | `libc.so.6` | `_int_malloc` | libc |
| 0.33% | `python` | `dict_traverse` | gc |
| 0.33% | `python` | `split` | str |
| 0.33% | `python` | `PyList_New.constprop.0` | memory |
| 0.32% | `python` | `_PyObject_Realloc` | memory |
| 0.32% | `python` | `PyDict_GetItemRef` | dict |
| 0.32% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.31% | `python` | `dict_dealloc` | memory |
| 0.31% | `python` | `_PyDict_Subscript` | dict |
| 0.30% | `python` | `insertdict` | dict |
| 0.29% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.28% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.27% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.27% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.26% | `python` | `_PyObject_GC_New` | gc |
| 0.26% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |

## dulwich_log

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 13.97% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 10.90% | `[JIT]` | `jit` | jit |
| 3.03% | `python` | `_PyObject_Malloc` | memory |
| 1.91% | `python` | `_PyObject_Free` | memory |
| 1.80% | `libz.so.1.3` | `inflate` | library |
| 1.64% | `python` | `_Py_Dealloc` | memory |
| 1.41% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.00% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.82% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.72% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.71% | `libz.so.1.3` | `0x000000000000381f` | library |
| 0.70% | `libc.so.6` | `_int_malloc` | libc |
| 0.61% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.55% | `python` | `PyLong_FromString` | int |
| 0.54% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.54% | `python` | `initialize_locals` | interpreter |
| 0.53% | `python` | `tuple_alloc` | memory |
| 0.51% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.49% | `python` | `_Py_dict_lookup` | lookup |
| 0.47% | `python` | `tuple_dealloc` | memory |
| 0.45% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 0.45% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.43% | `python` | `PyObject_RichCompare` | dynamic |
| 0.39% | `python` | `list_dealloc` | memory |
| 0.38% | `python` | `PyList_New.constprop.0` | memory |
| 0.36% | `python` | `_io_open` | unknown |
| 0.36% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.35% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.35% | `python` | `PySlice_New` | memory |
| 0.34% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.34% | `libz.so.1.3` | `0x00000000000025b7` | library |
| 0.33% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.33% | `python` | `clear_slots` | unknown |
| 0.33% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.33% | `python` | `PyObject_IsTrue` | dynamic |
| 0.33% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.32% | `libz.so.1.3` | `adler32_z` | library |
| 0.32% | `python` | `bytes_richcompare` | str |
| 0.32% | `python` | `unicode_from_format` | str |
| 0.31% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.31% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.30% | `python` | `bytes_subscript` | str |
| 0.29% | `python` | `_PyObject_CallFunctionVa` | dynamic |
| 0.29% | `python` | `_PyJIT_Entry` | compiler |
| 0.29% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.28% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.28% | `[kernel.kallsyms]` | `kmem_cache_alloc` | kernel |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.27% | `python` | `do_mkvalue` | unknown |
| 0.27% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.27% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.27% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_hex_impl.isra.0` | library |
| 0.27% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.27% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.27% | `python` | `siphash13` | str |
| 0.26% | `python` | `PyObject_GC_Del` | gc |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.25% | `python` | `convertitem.constprop.0` | unknown |
| 0.25% | `python` | `PyUnicode_Decode` | str |

## fannkuch

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.85% | `[JIT]` | `jit` | jit |
| 11.77% | `python` | `PySlice_AdjustIndices` | miscobj |
| 6.37% | `python` | `list_ass_slice_lock_held` | list |
| 4.87% | `python` | `list_slice_wrap` | list |
| 4.81% | `python` | `_Py_Dealloc` | memory |
| 3.51% | `python` | `PySlice_New` | memory |
| 3.35% | `python` | `_PyObject_Free` | memory |
| 3.15% | `python` | `PySlice_Unpack` | miscobj |
| 2.92% | `python` | `PyObject_GC_UnTrack` | gc |
| 2.86% | `python` | `_PyObject_Malloc` | memory |
| 2.76% | `python` | `list_dealloc` | memory |
| 2.74% | `python` | `_PyEval_SliceIndex` | interpreter |
| 2.73% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 2.66% | `python` | `list_ass_subscript` | list |
| 2.49% | `python` | `_PyCompactLong_Add` | unknown |
| 1.95% | `python` | `slice_dealloc` | memory |
| 1.64% | `python` | `PyList_New.constprop.0` | memory |
| 1.59% | `python` | `PySequence_Fast` | dynamic |
| 1.50% | `python` | `_PyList_SliceSubscript` | list |
| 1.40% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.11% | `python` | `list_insert` | list |
| 0.99% | `python` | `_Py_NewReference` | memory |
| 0.96% | `python` | `PyObject_SetItem` | dynamic |
| 0.88% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.84% | `python` | `list_pop` | list |
| 0.82% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.58% | `python` | `list_slice_lock_held` | list |
| 0.50% | `python` | `_PyNumber_Index` | dynamic |
| 0.42% | `python` | `PyLong_AsSsize_t` | int |
| 0.30% | `python` | `list_resize` | list |

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
| 28.99% | `[JIT]` | `jit` | jit |
| 5.53% | `python` | `_Py_Dealloc` | memory |
| 4.66% | `python` | `subtype_traverse` | gc |
| 3.74% | `python` | `gc_collect_main` | gc |
| 3.73% | `libm.so.6` | `__sin_fma` | library |
| 3.64% | `python` | `PyFloat_FromDouble` | float |
| 3.52% | `libm.so.6` | `__cos_fma` | library |
| 3.33% | `python` | `visit_decref` | gc |
| 3.28% | `python` | `visit_reachable` | gc |
| 2.92% | `python` | `_PyObject_Malloc` | memory |
| 2.88% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.18% | `python` | `_PyObject_Free` | memory |
| 1.66% | `python` | `clear_slots` | unknown |
| 1.57% | `python` | `_Py_NewReference` | memory |
| 1.49% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.31% | `python` | `float_dealloc` | memory |
| 1.29% | `python` | `PyFloat_AsDouble` | float |
| 1.27% | `python` | `_PyMember_GetOffset` | unknown |
| 1.19% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.15% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.08% | `python` | `list_dealloc` | memory |
| 0.97% | `python` | `long_float` | int |
| 0.87% | `python` | `list_slice_lock_held` | list |
| 0.83% | `python` | `initialize_locals` | interpreter |
| 0.81% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.79% | `python` | `subtype_dealloc` | memory |
| 0.75% | `python` | `PyType_IsSubtype` | dynamic |
| 0.71% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.68% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.63% | `python` | `PyType_GenericAlloc` | memory |
| 0.59% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.51% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.50% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.46% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sin` | library |
| 0.42% | `python` | `list_traverse` | gc |
| 0.42% | `math.cpython-316-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.42% | `python` | `float_compactlong_true_div` | float |
| 0.36% | `python` | `_PyLong_FromMedium` | int |
| 0.34% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.29% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `[kernel.kallsyms]` | `zap_pte_range` | kernel |
| 0.27% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.27% | `[kernel.kallsyms]` | `sync_regs` | kernel |

## gc_collect

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.18% | `python` | `gc_collect_main` | gc |
| 20.06% | `python` | `visit_reachable` | gc |
| 19.92% | `python` | `visit_decref` | gc |
| 8.77% | `python` | `dict_traverse` | gc |
| 3.02% | `[JIT]` | `jit` | jit |
| 2.99% | `python` | `func_traverse` | gc |
| 2.07% | `python` | `subtype_traverse` | gc |
| 1.90% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 1.21% | `python` | `tuple_traverse` | gc |
| 1.16% | `python` | `type_traverse` | gc |
| 1.11% | `python` | `type_is_gc` | gc |
| 0.99% | `python` | `set_traverse` | gc |
| 0.98% | `python` | `list_traverse` | gc |
| 0.82% | `python` | `PyObject_IS_GC` | gc |
| 0.53% | `python` | `_PyObject_Malloc` | memory |
| 0.51% | `python` | `meth_traverse` | gc |
| 0.41% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.40% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.39% | `python` | `_PyTuple_MaybeUntrack` | gc |
| 0.31% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.30% | `python` | `subtype_dealloc` | memory |
| 0.28% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.27% | `python` | `gc_traverse` | gc |

## gc_traversal

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.07% | `python` | `visit_reachable` | gc |
| 30.59% | `python` | `visit_decref` | gc |
| 13.61% | `python` | `list_traverse` | gc |
| 11.14% | `python` | `gc_collect_main` | gc |
| 4.01% | `python` | `dict_traverse` | gc |
| 1.40% | `[JIT]` | `jit` | jit |
| 1.31% | `python` | `func_traverse` | gc |
| 0.61% | `python` | `type_traverse` | gc |
| 0.53% | `python` | `subtype_traverse` | gc |
| 0.52% | `python` | `tuple_traverse` | gc |
| 0.49% | `python` | `type_is_gc` | gc |
| 0.44% | `python` | `set_traverse` | gc |
| 0.43% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.38% | `python` | `PyObject_IS_GC` | gc |
| 0.25% | `python` | `list_dealloc` | memory |
| 0.25% | `python` | `PyLong_FromLong` | int |

## generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 46.42% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.51% | `[JIT]` | `jit` | jit |
| 3.28% | `python` | `gc_collect_main` | gc |
| 2.54% | `python` | `_Py_Dealloc` | memory |
| 1.95% | `python` | `_PyObject_Malloc` | memory |
| 1.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.72% | `python` | `_PyObject_Free` | memory |
| 1.53% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.39% | `python` | `gen_dealloc` | memory |
| 1.27% | `python` | `make_range_object` | unknown |
| 1.23% | `python` | `initialize_locals` | interpreter |
| 1.21% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.11% | `python` | `visit_decref` | gc |
| 1.09% | `python` | `visit_reachable` | gc |
| 1.03% | `python` | `_PyEval_Vector` | interpreter |
| 0.99% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.93% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.93% | `python` | `range_subscript` | miscobj |
| 0.91% | `python` | `make_gen` | miscobj |
| 0.91% | `python` | `PyNumber_Add` | dynamic |
| 0.85% | `python` | `long_add_method` | int |
| 0.79% | `python` | `subtype_traverse` | gc |
| 0.77% | `python` | `_PyLong_FromMedium` | int |
| 0.75% | `python` | `long_richcompare` | int |
| 0.75% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.72% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.72% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.68% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.67% | `python` | `PySlice_New` | memory |
| 0.65% | `python` | `slot_tp_iter` | unknown |
| 0.57% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.55% | `python` | `_PyEval_GetIter` | interpreter |
| 0.54% | `python` | `range_dealloc` | memory |
| 0.52% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.52% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.49% | `python` | `_PyJIT_Entry` | compiler |
| 0.48% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.46% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.45% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.43% | `python` | `_Py_NewReference` | memory |
| 0.40% | `python` | `PyObject_GetItem` | dynamic |
| 0.39% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.38% | `python` | `long_dealloc` | memory |
| 0.34% | `python` | `subtype_dealloc` | memory |
| 0.33% | `python` | `PyObject_GC_Del` | gc |
| 0.31% | `python` | `PyNumber_Multiply` | dynamic |
| 0.29% | `python` | `long_div` | int |
| 0.29% | `python` | `long_mul` | int |
| 0.29% | `python` | `PyObject_GetIter` | dynamic |
| 0.28% | `python` | `PyNumber_Index` | dynamic |
| 0.27% | `python` | `slice_dealloc` | memory |
| 0.27% | `python` | `PyLong_FromLong` | int |
| 0.25% | `python` | `_PyObject_GC_Link` | gc |

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
| 55.33% | `[JIT]` | `jit` | jit |
| 14.98% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.39% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.37% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.63% | `python` | `initialize_locals` | interpreter |
| 1.36% | `python` | `long_bitwise` | int |
| 1.11% | `python` | `_PyCompactLong_Add` | unknown |
| 1.08% | `python` | `_Py_Dealloc` | memory |
| 1.05% | `python` | `insertdict` | dict |
| 1.04% | `python` | `_PyObject_Malloc` | memory |
| 0.99% | `python` | `_PyObject_Free` | memory |
| 0.94% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.91% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.67% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.61% | `python` | `_PyJIT_Entry` | compiler |
| 0.56% | `python` | `PyNumber_InPlaceXor` | dynamic |
| 0.48% | `python` | `PyDict_SetItem` | dict |
| 0.44% | `python` | `set_lookkey` | miscobj |
| 0.44% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.39% | `python` | `PyFloat_FromDouble` | float |
| 0.35% | `python` | `_Py_dict_lookup` | lookup |
| 0.34% | `python` | `set_add_entry_takeref` | miscobj |
| 0.30% | `python` | `long_dealloc` | memory |
| 0.27% | `python` | `long_alloc` | memory |
| 0.27% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.27% | `python` | `set_dealloc` | memory |
| 0.26% | `python` | `_PyThreadState_PushFrame` | threading |

## hexiom

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.06% | `[JIT]` | `jit` | jit |
| 15.48% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.68% | `python` | `PyObject_RichCompareBool` | dynamic |
| 4.12% | `python` | `list_contains` | list |
| 3.19% | `python` | `long_richcompare` | int |
| 2.42% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.21% | `python` | `gen_iternext` | miscobj |
| 1.75% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.29% | `python` | `_PyJIT_Entry` | compiler |
| 1.14% | `python` | `PyObject_Size` | dynamic |
| 1.10% | `python` | `PyLong_FromSsize_t` | int |
| 1.04% | `python` | `builtin_sum` | unknown |
| 0.90% | `python` | `_PyObject_Malloc` | memory |
| 0.88% | `python` | `_Py_Dealloc` | memory |
| 0.87% | `python` | `_PyObject_Free` | memory |
| 0.86% | `python` | `PyLong_FromLong` | int |
| 0.70% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.62% | `python` | `PyIter_Next` | dynamic |
| 0.56% | `python` | `make_range_object` | unknown |
| 0.45% | `python` | `PySequence_Contains` | dynamic |
| 0.42% | `python` | `range_iter` | miscobj |
| 0.37% | `python` | `_PyCompactLong_Add` | unknown |
| 0.36% | `python` | `list_dealloc` | memory |
| 0.36% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.30% | `python` | `func_clear` | unknown |
| 0.29% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.29% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.28% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.28% | `python` | `PyList_New.constprop.0` | memory |
| 0.26% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |

## html5lib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.01% | `[JIT]` | `jit` | jit |
| 18.03% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.53% | `python` | `sre_ucs1_charset.isra.0` | library |
| 2.70% | `python` | `gc_collect_main` | gc |
| 2.00% | `python` | `_PyObject_Malloc` | memory |
| 1.50% | `python` | `_Py_dict_lookup` | lookup |
| 1.45% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.36% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.29% | `python` | `_Py_Dealloc` | memory |
| 1.08% | `python` | `_PyObject_Free` | memory |
| 0.99% | `python` | `_PyDict_Subscript` | dict |
| 0.97% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.84% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.84% | `python` | `sre_ucs1_count` | library |
| 0.79% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.73% | `python` | `visit_decref` | gc |
| 0.71% | `python` | `set_lookkey` | miscobj |
| 0.70% | `python` | `_PyJIT_Entry` | compiler |
| 0.63% | `python` | `initialize_locals` | interpreter |
| 0.60% | `python` | `PyObject_IsTrue` | dynamic |
| 0.59% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.58% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.57% | `libc.so.6` | `__strcmp_avx2` | libc |
| 0.54% | `python` | `PyObject_GetItem` | dynamic |
| 0.47% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.46% | `python` | `list_subscript` | list |
| 0.45% | `python` | `_PyUnicode_Equal` | str |
| 0.42% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.42% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.42% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.42% | `python` | `sre_ucs1_match` | library |
| 0.41% | `python` | `list_contains` | list |
| 0.41% | `python` | `_PyCompactLong_Add` | unknown |
| 0.40% | `libc.so.6` | `malloc` | libc |
| 0.37% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.36% | `libc.so.6` | `_int_malloc` | libc |
| 0.35% | `python` | `_PyDict_FromItems` | dict |
| 0.35% | `python` | `PyUnicode_Concat` | str |
| 0.35% | `python` | `insertdict` | dict |
| 0.33% | `python` | `insert_to_emptydict` | dict |
| 0.32% | `python` | `visit_reachable` | gc |
| 0.31% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.30% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.30% | `python` | `list_dealloc` | memory |
| 0.30% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.29% | `python` | `PyType_IsSubtype` | dynamic |
| 0.29% | `python` | `PyList_New.constprop.0` | memory |
| 0.28% | `python` | `_Py_BuildMap_StackRefSteal` | unknown |
| 0.28% | `python` | `PyObject_Hash` | dynamic |
| 0.27% | `python` | `PyObject_RichCompare` | dynamic |
| 0.26% | `python` | `object_richcompare` | dynamic |
| 0.26% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.25% | `python` | `_PyThreadState_PopFrame` | threading |

## json

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.70% | `_json.cpython-316-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 7.30% | `_json.cpython-316-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.84% | `python` | `_PyObject_Malloc` | memory |
| 5.83% | `python` | `_PyObject_Free` | memory |
| 5.11% | `python` | `siphash13` | str |
| 4.96% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.92% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.22% | `[JIT]` | `jit` | jit |
| 2.88% | `python` | `PyLong_FromString` | int |
| 2.87% | `python` | `_Py_dict_lookup` | lookup |
| 2.72% | `python` | `insertdict` | dict |
| 2.62% | `python` | `PyUnicode_Substring` | str |
| 2.59% | `python` | `_Py_Dealloc` | memory |
| 2.20% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 2.00% | `python` | `PyUnicode_New.part.0` | memory |
| 1.69% | `python` | `find_empty_slot.constprop.0` | dict |
| 1.45% | `python` | `build_indices_unicode` | dict |
| 1.29% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.12% | `libc.so.6` | `_int_malloc` | libc |
| 0.97% | `python` | `initialize_locals` | interpreter |
| 0.96% | `python` | `PyDict_SetItem` | dict |
| 0.93% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.91% | `python` | `unicode_dealloc` | memory |
| 0.70% | `python` | `sre_ucs1_match` | library |
| 0.68% | `python` | `unicode_hash` | str |
| 0.67% | `python` | `pattern_new_match` | memory |
| 0.62% | `python` | `PyDict_GetItemRef` | dict |
| 0.59% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.58% | `python` | `dictresize` | dict |
| 0.54% | `python` | `insert_to_emptydict` | dict |
| 0.52% | `libc.so.6` | `malloc` | libc |
| 0.51% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.48% | `python` | `new_keys_object` | dict |
| 0.48% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.44% | `python` | `maybe_small_long` | unknown |
| 0.43% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.43% | `python` | `_Py_NewReference` | memory |
| 0.39% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.39% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.39% | `python` | `sre_ucs1_count` | library |
| 0.36% | `python` | `_PyObject_Realloc` | memory |
| 0.34% | `libc.so.6` | `_int_free` | libc |
| 0.33% | `python` | `Py_HashBuffer` | unknown |
| 0.32% | `python` | `PyObject_Hash` | dynamic |
| 0.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.30% | `python` | `PyObject_Malloc` | dynamic |
| 0.30% | `python` | `PyDict_New` | memory |
| 0.29% | `python` | `long_alloc` | memory |
| 0.28% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.27% | `python` | `dict_dealloc` | memory |
| 0.27% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.26% | `python` | `PyObject_Free` | dynamic |
| 0.26% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 0.26% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.26% | `python` | `convertitem.constprop.0` | unknown |

## json_dumps

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.48% | `[JIT]` | `jit` | jit |
| 5.99% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_listencode_obj` | library |
| 4.93% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 4.33% | `python` | `_PyUnicode_ResizeCompact` | str |
| 4.14% | `python` | `_PyObject_Malloc` | memory |
| 4.04% | `_json.cpython-316-x86_64-linux-gnu.so` | `ascii_escape_size` | library |
| 3.32% | `python` | `_Py_dict_lookup` | lookup |
| 2.93% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 2.80% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 2.80% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 2.79% | `python` | `PyUnicodeWriter_WriteASCII` | str |
| 2.69% | `_json.cpython-316-x86_64-linux-gnu.so` | `write_escaped_ascii` | library |
| 2.62% | `python` | `PyDict_Next` | dict |
| 2.15% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.09% | `python` | `convertitem.constprop.0` | unknown |
| 2.06% | `python` | `_PyObject_Free` | memory |
| 2.01% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_encode_key_value` | library |
| 2.00% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.85% | `python` | `PyDict_GetItemRef` | dict |
| 1.85% | `python` | `_Py_Dealloc` | memory |
| 1.83% | `python` | `_PyObject_Realloc` | memory |
| 1.51% | `python` | `initialize_locals` | interpreter |
| 1.36% | `python` | `long_to_decimal_string_internal` | int |
| 1.33% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 1.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.12% | `python` | `PyUnicodeWriter_WriteStr` | str |
| 1.05% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.01% | `python` | `tuple_dealloc` | memory |
| 0.99% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.80% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.76% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_write_string` | library |
| 0.73% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.72% | `python` | `tuple_alloc` | memory |
| 0.69% | `python` | `PyType_IsSubtype` | dynamic |
| 0.64% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.58% | `python` | `delitem_common` | dynamic |
| 0.54% | `python` | `long_hash` | int |
| 0.54% | `python` | `memcpy@plt` | memory |
| 0.49% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.47% | `python` | `insertdict` | dict |
| 0.46% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.45% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.44% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.41% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.40% | `python` | `func_clear` | unknown |
| 0.40% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_new` | library |
| 0.40% | `python` | `PyUnicodeWriter_Create` | str |
| 0.40% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.38% | `python` | `dict_dealloc` | memory |
| 0.37% | `python` | `PyDict_DelItem` | dict |
| 0.37% | `python` | `PyLong_FromVoidPtr` | int |
| 0.37% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.36% | `_json.cpython-316-x86_64-linux-gnu.so` | `PyUnicodeWriter_WriteChar@plt` | library |
| 0.36% | `python` | `new_dict` | dict |
| 0.35% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.34% | `_json.cpython-316-x86_64-linux-gnu.so` | `ascii_escape_unicode_and_size` | library |
| 0.32% | `python` | `func_dealloc` | memory |
| 0.30% | `python` | `PyObject_Hash` | dynamic |
| 0.27% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_dealloc` | library |
| 0.26% | `python` | `PyArg_ParseTupleAndKeywords` | calls |
| 0.26% | `python` | `PyDict_SetItem` | dict |
| 0.25% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.25% | `python` | `PyObject_Vectorcall` | dynamic |

## json_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.98% | `_json.cpython-316-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 8.17% | `_json.cpython-316-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.80% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 6.60% | `python` | `_PyObject_Malloc` | memory |
| 6.06% | `python` | `siphash13` | str |
| 5.45% | `python` | `_PyObject_Free` | memory |
| 4.46% | `python` | `PyUnicode_Substring` | str |
| 3.42% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.31% | `python` | `_Py_Dealloc` | memory |
| 3.23% | `python` | `_Py_dict_lookup` | lookup |
| 3.13% | `python` | `PyLong_FromString` | int |
| 2.99% | `python` | `PyUnicode_New.part.0` | memory |
| 2.97% | `python` | `insertdict` | dict |
| 1.65% | `python` | `find_empty_slot.constprop.0` | dict |
| 1.43% | `[JIT]` | `jit` | jit |
| 1.36% | `python` | `unicode_dealloc` | memory |
| 1.29% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.26% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 1.17% | `python` | `PyDict_SetItem` | dict |
| 1.00% | `python` | `build_indices_unicode` | dict |
| 0.90% | `python` | `unicode_hash` | str |
| 0.71% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.62% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.57% | `python` | `_Py_NewReference` | memory |
| 0.55% | `libc.so.6` | `_int_malloc` | libc |
| 0.53% | `libc.so.6` | `malloc` | libc |
| 0.52% | `python` | `PyList_Append` | list |
| 0.48% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.48% | `python` | `PyObject_Malloc` | dynamic |
| 0.46% | `python` | `initialize_locals` | interpreter |
| 0.44% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.44% | `python` | `dictresize` | dict |
| 0.43% | `python` | `new_keys_object` | dict |
| 0.38% | `python` | `Py_HashBuffer` | unknown |
| 0.38% | `python` | `maybe_small_long` | unknown |
| 0.37% | `python` | `PyObject_Hash` | dynamic |
| 0.33% | `python` | `insert_to_emptydict` | dict |
| 0.32% | `python` | `sre_ucs1_match` | library |
| 0.31% | `python` | `long_alloc` | memory |
| 0.29% | `python` | `list_dealloc` | memory |
| 0.28% | `python` | `PyDict_GetItemRef` | dict |
| 0.27% | `python` | `_PyObject_Realloc` | memory |
| 0.27% | `python` | `pattern_new_match` | memory |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `_json.cpython-316-x86_64-linux-gnu.so` | `PyUnicode_Substring@plt` | library |
| 0.25% | `python` | `PyObject_Free` | dynamic |

## logging

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.85% | `[JIT]` | `jit` | jit |
| 10.56% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.07% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.77% | `python` | `_Py_dict_lookup` | lookup |
| 2.37% | `python` | `initialize_locals` | interpreter |
| 2.06% | `python` | `_Py_Dealloc` | memory |
| 2.05% | `python` | `_PyObject_Malloc` | memory |
| 1.99% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.89% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.88% | `python` | `PyDict_New` | memory |
| 1.76% | `python` | `dict_dealloc` | memory |
| 1.70% | `python` | `_PyCode_CheckLineNumber` | interpreter |
| 1.65% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 1.57% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.31% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 1.30% | `python` | `_PyDict_Subscript` | dict |
| 1.27% | `python` | `_PyObject_Free` | memory |
| 1.23% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.19% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.11% | `python` | `PyObject_GetItem` | dynamic |
| 0.94% | `python` | `_PyJIT_Entry` | compiler |
| 0.93% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.83% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.79% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.71% | `python` | `PyUnicode_Format` | str |
| 0.70% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.67% | `python` | `PyUnicode_Contains` | str |
| 0.61% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.54% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.48% | `python` | `any_find_slice` | unknown |
| 0.48% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.47% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.45% | `python` | `PyObject_Hash` | dynamic |
| 0.44% | `python` | `_PyLong_Frexp` | int |
| 0.41% | `python` | `PyUnicode_AsUCS4` | str |
| 0.37% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.36% | `python` | `_Py_NewReference` | memory |
| 0.36% | `python` | `long_hash` | int |
| 0.34% | `python` | `l_mod` | int |
| 0.33% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.32% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.29% | `python` | `PyType_IsSubtype` | dynamic |
| 0.28% | `python` | `dict_get` | dict |
| 0.27% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.27% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.27% | `python` | `_PyType_GetDict` | dynamic |
| 0.26% | `[kernel.kallsyms]` | `__task_pid_nr_ns` | kernel |
| 0.25% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |

## mako

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.42% | `[JIT]` | `jit` | jit |
| 8.49% | `python` | `replace` | str |
| 7.12% | `python` | `long_to_decimal_string_internal` | int |
| 5.38% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 4.39% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 4.14% | `python` | `_PyObject_Malloc` | memory |
| 3.77% | `python` | `unicode_replace` | str |
| 3.30% | `python` | `_PyObject_Free` | memory |
| 3.02% | `python` | `deque_append` | miscobj |
| 2.83% | `python` | `dequeiter_next` | miscobj |
| 1.88% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.81% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.57% | `python` | `PyUnicode_New` | memory |
| 1.42% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.29% | `python` | `_list_extend` | list |
| 1.28% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.26% | `python` | `PyObject_Str` | dynamic |
| 1.20% | `python` | `_Py_Dealloc` | memory |
| 1.09% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.04% | `python` | `list_dealloc` | memory |
| 1.01% | `python` | `deque_clear.part.0` | miscobj |
| 0.85% | `python` | `PyThread_get_thread_ident` | threading |
| 0.83% | `python` | `long_alloc` | memory |
| 0.72% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.69% | `python` | `PyLong_FromLong` | int |
| 0.66% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.65% | `python` | `unicode_dealloc` | memory |
| 0.62% | `python` | `_Py_IsMainThread` | unknown |
| 0.59% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.58% | `python` | `long_to_decimal_string` | int |
| 0.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.39% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.37% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.37% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.37% | `python` | `_Py_NewReference` | memory |
| 0.37% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.29% | `python` | `memcpy@plt` | memory |
| 0.27% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.25% | `libc.so.6` | `_int_malloc` | libc |

## mdp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.45% | `[JIT]` | `jit` | jit |
| 13.55% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.49% | `python` | `_Py_dict_lookup` | lookup |
| 6.74% | `python` | `PyObject_RichCompareBool` | dynamic |
| 4.41% | `python` | `tuple_richcompare` | tuple |
| 2.92% | `python` | `_PyDict_Subscript` | dict |
| 2.25% | `python` | `_PyLong_GCD` | int |
| 1.65% | `python` | `_Py_Dealloc` | memory |
| 1.58% | `python` | `_PyObject_Free` | memory |
| 1.43% | `python` | `_PyObject_Malloc` | memory |
| 1.37% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.35% | `python` | `gen_iternext` | miscobj |
| 1.34% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.24% | `python` | `builtin_sum` | unknown |
| 1.07% | `python` | `PyDict_GetItemRef` | dict |
| 1.01% | `python` | `_PyJIT_Entry` | compiler |
| 0.96% | `python` | `tuple_hash` | tuple |
| 0.92% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.74% | `python` | `PyObject_GetItem` | dynamic |
| 0.66% | `python` | `PyObject_Hash` | dynamic |
| 0.64% | `python` | `insertdict` | dict |
| 0.62% | `python` | `set_lookkey` | miscobj |
| 0.59% | `python` | `func_clear` | unknown |
| 0.55% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.53% | `python` | `gen_dealloc` | memory |
| 0.52% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.52% | `python` | `subtype_dealloc` | memory |
| 0.49% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.48% | `python` | `long_div` | int |
| 0.48% | `python` | `PyFloat_FromDouble` | float |
| 0.45% | `python` | `_PyCompactLong_Multiply` | unknown |
| 0.44% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.43% | `python` | `tuple_dealloc` | memory |
| 0.42% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.42% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.40% | `python` | `_Py_NewReference` | memory |
| 0.37% | `python` | `PyIter_Next` | dynamic |
| 0.37% | `python` | `PyLong_FromLong` | int |
| 0.34% | `python` | `func_dealloc` | memory |
| 0.34% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.33% | `python` | `initialize_locals` | interpreter |
| 0.32% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.31% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.29% | `python` | `PyType_IsSubtype` | dynamic |
| 0.27% | `python` | `min_max` | unknown |
| 0.25% | `python` | `tuple_alloc` | memory |

## meteor_contest

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.55% | `[JIT]` | `jit` | jit |
| 12.88% | `python` | `set_lookkey` | miscobj |
| 10.54% | `python` | `set_issubset_impl` | miscobj |
| 8.93% | `python` | `setiter_iternext` | miscobj |
| 4.85% | `python` | `set_difference` | miscobj |
| 4.24% | `python` | `set_dealloc` | memory |
| 3.33% | `python` | `PyObject_RichCompareBool` | dynamic |
| 3.08% | `python` | `set_add_entry_takeref` | miscobj |
| 2.58% | `python` | `_PyObject_Free` | memory |
| 2.33% | `python` | `long_richcompare` | int |
| 2.29% | `python` | `_PyObject_Malloc` | memory |
| 1.85% | `python` | `min_max` | unknown |
| 1.82% | `python` | `list_dealloc` | memory |
| 1.74% | `python` | `list_slice_lock_held` | list |
| 1.38% | `python` | `PyIter_Next` | dynamic |
| 1.38% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.30% | `python` | `set_table_resize` | miscobj |
| 1.27% | `python` | `PyObject_RichCompare` | dynamic |
| 1.19% | `python` | `set_intersection` | miscobj |
| 1.08% | `python` | `_Py_Dealloc` | memory |
| 0.94% | `python` | `set_merge_lock_held` | miscobj |
| 0.80% | `python` | `set_richcompare` | miscobj |
| 0.78% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.63% | `python` | `set_difference_update_internal` | miscobj |
| 0.57% | `python` | `PyList_New.constprop.0` | memory |
| 0.49% | `python` | `initialize_locals` | interpreter |
| 0.49% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.44% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.36% | `python` | `PyObject_Size` | dynamic |
| 0.35% | `python` | `PyLong_FromSsize_t` | int |
| 0.33% | `python` | `list_ass_slice_lock_held` | list |
| 0.33% | `python` | `set_iter` | miscobj |
| 0.32% | `python` | `PyObject_GC_Del` | gc |
| 0.32% | `python` | `PyObject_IsTrue` | dynamic |
| 0.32% | `python` | `PyType_GenericAlloc` | memory |
| 0.30% | `python` | `list_slice_wrap` | list |
| 0.30% | `python` | `setiter_dealloc` | memory |
| 0.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.28% | `python` | `_PyObject_GC_New` | gc |

## nbody

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 61.96% | `[JIT]` | `jit` | jit |
| 12.22% | `python` | `_Py_Dealloc` | memory |
| 7.43% | `python` | `PyFloat_FromDouble` | float |
| 6.82% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 3.34% | `python` | `float_dealloc` | memory |
| 2.91% | `python` | `_Py_NewReference` | memory |
| 1.94% | `python` | `float_pow` | float |
| 1.01% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.93% | `python` | `_PyNumber_PowerNoMod` | dynamic |
| 0.66% | `libm.so.6` | `pow@@GLIBC_2.29` | library |

## networkx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.54% | `python` | `set_lookkey` | miscobj |
| 21.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 15.62% | `python` | `dictiter_iternextkey` | dict |
| 10.00% | `[JIT]` | `jit` | jit |
| 5.93% | `python` | `build_indices_unicode` | dict |
| 2.49% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.33% | `python` | `_PyDict_Subscript` | dict |
| 1.25% | `python` | `_PySet_Contains` | miscobj |
| 1.15% | `python` | `set_dealloc` | memory |
| 1.09% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.92% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.82% | `python` | `list_dealloc` | memory |
| 0.80% | `python` | `deque_clear.part.0` | miscobj |
| 0.58% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.55% | `python` | `set_table_resize` | miscobj |
| 0.54% | `python` | `_Py_dict_lookup` | lookup |
| 0.46% | `python` | `set_add_entry_takeref` | miscobj |
| 0.45% | `python` | `_PyObject_Free` | memory |
| 0.42% | `python` | `_Py_Dealloc` | memory |
| 0.39% | `python` | `insertdict` | dict |
| 0.38% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.29% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.28% | `python` | `merge_from_seq2_lock_held` | unknown |

## networkx_connected_components

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.16% | `python` | `set_lookkey` | miscobj |
| 16.35% | `python` | `dictiter_iternextkey` | dict |
| 16.04% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 11.75% | `[JIT]` | `jit` | jit |
| 3.19% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.58% | `python` | `_PyDict_Subscript` | dict |
| 2.51% | `python` | `set_dealloc` | memory |
| 1.58% | `python` | `set_merge_lock_held` | miscobj |
| 1.55% | `python` | `_PySet_Contains` | miscobj |
| 0.92% | `python` | `list_dealloc` | memory |
| 0.70% | `python` | `set_table_resize` | miscobj |
| 0.54% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.51% | `python` | `set_add_entry_takeref` | miscobj |
| 0.43% | `python` | `_PyObject_Free` | memory |
| 0.42% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.29% | `python` | `_Py_dict_lookup` | lookup |
| 0.25% | `python` | `_PyObject_GC_New` | gc |

## networkx_k_core

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 34.57% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 19.47% | `[JIT]` | `jit` | jit |
| 6.46% | `python` | `list_remove` | list |
| 5.15% | `python` | `_PyDict_Subscript` | dict |
| 3.28% | `python` | `visit_decref` | gc |
| 3.27% | `python` | `dictiter_iternextkey` | dict |
| 2.97% | `python` | `visit_reachable` | gc |
| 2.95% | `python` | `_Py_dict_lookup` | lookup |
| 1.54% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.47% | `python` | `gc_collect_main` | gc |
| 1.36% | `python` | `build_indices_unicode` | dict |
| 1.27% | `python` | `dict_traverse` | gc |
| 1.21% | `python` | `PyUnicode_RichCompare` | str |
| 1.17% | `python` | `list_dealloc` | memory |
| 1.06% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.03% | `python` | `insertdict` | dict |
| 0.96% | `python` | `PyObject_GetItem` | dynamic |
| 0.92% | `python` | `listiter_next` | list |
| 0.68% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.46% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.42% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.39% | `python` | `_PyObject_Malloc` | memory |
| 0.38% | `python` | `list_traverse` | gc |
| 0.31% | `python` | `list_ass_slice_lock_held` | list |
| 0.31% | `python` | `PyObject_SetItem` | dynamic |
| 0.31% | `python` | `list_sort_impl` | list |
| 0.31% | `python` | `_Py_Dealloc` | memory |

## nqueens

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.05% | `[JIT]` | `jit` | jit |
| 4.13% | `python` | `_PyObject_Malloc` | memory |
| 3.83% | `python` | `_PyObject_Free` | memory |
| 3.80% | `python` | `set_add_entry_takeref` | miscobj |
| 3.42% | `python` | `_Py_Dealloc` | memory |
| 3.16% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.81% | `python` | `set_dealloc` | memory |
| 1.61% | `python` | `_PyCompactLong_Add` | unknown |
| 1.46% | `python` | `PyList_New.constprop.0` | memory |
| 1.33% | `python` | `list_dealloc` | memory |
| 1.23% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.17% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.16% | `python` | `PyLong_FromLong` | int |
| 1.11% | `python` | `func_clear` | unknown |
| 1.09% | `python` | `set_table_resize` | miscobj |
| 1.06% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.03% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.96% | `python` | `list_ass_slice_lock_held` | list |
| 0.93% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.90% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.89% | `python` | `make_range_object` | unknown |
| 0.85% | `python` | `list_ass_subscript` | list |
| 0.83% | `python` | `tuple_dealloc` | memory |
| 0.82% | `python` | `_PyList_BinarySlice` | list |
| 0.81% | `python` | `list_slice_lock_held` | list |
| 0.77% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.76% | `python` | `gen_dealloc` | memory |
| 0.75% | `python` | `_PyObject_Realloc` | memory |
| 0.73% | `python` | `_Py_NewReference` | memory |
| 0.70% | `python` | `range_iter` | miscobj |
| 0.67% | `python` | `func_dealloc` | memory |
| 0.67% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.63% | `python` | `PyLong_AsLong` | int |
| 0.58% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 0.58% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.57% | `python` | `range_reverse` | miscobj |
| 0.52% | `python` | `_PySet_AddTakeRef` | miscobj |
| 0.52% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.52% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.52% | `python` | `PyObject_Hash` | dynamic |
| 0.50% | `python` | `_PyList_Concat` | list |
| 0.46% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.45% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.45% | `python` | `PyDict_GetItemRef` | dict |
| 0.43% | `python` | `PyCMethod_New` | memory |
| 0.43% | `python` | `PyObject_GC_Del` | gc |
| 0.42% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.41% | `python` | `make_gen` | miscobj |
| 0.38% | `python` | `tuple_alloc` | memory |
| 0.37% | `python` | `PySequence_Fast` | dynamic |
| 0.37% | `python` | `_Py_dict_lookup` | lookup |
| 0.37% | `python` | `long_hash` | int |
| 0.36% | `python` | `PyObject_SetItem` | dynamic |
| 0.34% | `python` | `_PyObject_GC_New` | gc |
| 0.33% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.32% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.30% | `python` | `reversed_new_impl` | memory |
| 0.29% | `python` | `_PyObject_GC_Link` | gc |
| 0.27% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.27% | `python` | `list_subscript` | list |
| 0.26% | `python` | `PyNumber_Negative` | dynamic |
| 0.26% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.25% | `python` | `_PyType_AllocNoTrack` | memory |

## pathlib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.06% | `[JIT]` | `jit` | jit |
| 4.06% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 3.78% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 3.65% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 3.59% | `python` | `_PyObject_Malloc` | memory |
| 3.59% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.78% | `python` | `_PyObject_Free` | memory |
| 2.49% | `python` | `_Py_Dealloc` | memory |
| 2.09% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 2.04% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 1.73% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 1.64% | `[kernel.kallsyms]` | `ext4_htree_store_dirent` | kernel |
| 1.32% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 1.22% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.17% | `[kernel.kallsyms]` | `filldir64` | kernel |
| 1.13% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.12% | `[kernel.kallsyms]` | `half_md4_transform.isra.0` | kernel |
| 1.07% | `python` | `initialize_locals` | interpreter |
| 1.03% | `[kernel.kallsyms]` | `str2hashbuf_signed` | kernel |
| 0.94% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.89% | `python` | `take_gil` | gil |
| 0.81% | `[kernel.kallsyms]` | `__kmalloc` | kernel |
| 0.79% | `python` | `PyLong_FromLongLong` | int |
| 0.71% | `python` | `structseq_dealloc` | memory |
| 0.67% | `python` | `clear_slots` | unknown |
| 0.65% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.64% | `libc.so.6` | `_int_malloc` | libc |
| 0.62% | `[kernel.kallsyms]` | `apparmor_inode_getattr` | kernel |
| 0.61% | `[kernel.kallsyms]` | `cp_new_stat` | kernel |
| 0.60% | `[kernel.kallsyms]` | `filename_lookup` | kernel |
| 0.58% | `python` | `sre_ucs1_match` | library |
| 0.58% | `libc.so.6` | `__GI___readdir64` | libc |
| 0.57% | `[kernel.kallsyms]` | `ext4_file_getattr` | kernel |
| 0.57% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.56% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.54% | `[kernel.kallsyms]` | `strncpy_from_user` | kernel |
| 0.52% | `python` | `dict_dealloc` | memory |
| 0.51% | `[kernel.kallsyms]` | `kmem_cache_alloc` | kernel |
| 0.50% | `[kernel.kallsyms]` | `__slab_free` | kernel |
| 0.50% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.49% | `[kernel.kallsyms]` | `security_inode_getattr` | kernel |
| 0.49% | `[kernel.kallsyms]` | `rb_insert_color` | kernel |
| 0.49% | `[kernel.kallsyms]` | `inode_permission` | kernel |
| 0.48% | `[kernel.kallsyms]` | `rb_next` | kernel |
| 0.48% | `python` | `find_first_nonascii` | str |
| 0.47% | `python` | `_PyEval_Vector` | interpreter |
| 0.46% | `[kernel.kallsyms]` | `__virt_addr_valid` | kernel |
| 0.45% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.45% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.44% | `python` | `_pystat_fromstructstat` | unknown |
| 0.44% | `python` | `ScandirIterator_iternext` | unknown |
| 0.44% | `python` | `_PyJIT_Entry` | compiler |
| 0.41% | `[kernel.kallsyms]` | `do_syscall_64` | kernel |
| 0.40% | `[kernel.kallsyms]` | `generic_permission` | kernel |
| 0.40% | `[kernel.kallsyms]` | `common_perm_cond` | kernel |
| 0.40% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.40% | `[kernel.kallsyms]` | `kfree` | kernel |
| 0.39% | `[kernel.kallsyms]` | `set_root` | kernel |
| 0.39% | `[kernel.kallsyms]` | `vfs_getattr_nosec` | kernel |
| 0.39% | `python` | `path_converter` | unknown |
| 0.38% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.38% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.38% | `python` | `PyFloat_FromDouble` | float |
| 0.38% | `[kernel.kallsyms]` | `memchr` | kernel |
| 0.37% | `python` | `_PyLong_FromMedium` | int |
| 0.37% | `python` | `_Py_NewReference` | memory |
| 0.36% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.35% | `[kernel.kallsyms]` | `__ext4_check_dir_entry` | kernel |
| 0.35% | `python` | `tuple_dealloc` | memory |
| 0.35% | `[kernel.kallsyms]` | `slab_update_freelist.isra.0` | kernel |
| 0.35% | `python` | `PyDict_GetItemWithError` | dict |
| 0.35% | `libc.so.6` | `__GI___fstatat64` | libc |
| 0.34% | `python` | `fill_time` | unknown |
| 0.34% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.34% | `python` | `_Py_dict_lookup` | lookup |
| 0.34% | `python` | `float_dealloc` | memory |
| 0.33% | `python` | `subtype_dealloc` | memory |
| 0.33% | `[kernel.kallsyms]` | `ext4_getattr` | kernel |
| 0.33% | `[kernel.kallsyms]` | `map_id_up` | kernel |
| 0.33% | `[kernel.kallsyms]` | `__do_sys_newfstatat` | kernel |
| 0.33% | `[kernel.kallsyms]` | `vfs_statx` | kernel |
| 0.32% | `libc.so.6` | `pthread_cond_signal@@GLIBC_2.3.2` | libc |
| 0.30% | `python` | `tuple_alloc` | memory |
| 0.30% | `[kernel.kallsyms]` | `kmem_cache_free` | kernel |
| 0.30% | `[kernel.kallsyms]` | `_copy_to_user` | kernel |
| 0.30% | `[kernel.kallsyms]` | `htree_dirblock_to_tree` | kernel |
| 0.30% | `[kernel.kallsyms]` | `security_inode_permission` | kernel |
| 0.30% | `[kernel.kallsyms]` | `__check_heap_object` | kernel |
| 0.29% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.29% | `python` | `PyUnicode_New.part.0` | memory |
| 0.29% | `[kernel.kallsyms]` | `path_lookupat` | kernel |
| 0.29% | `python` | `os_stat` | unknown |
| 0.28% | `python` | `drop_gil` | gil |
| 0.28% | `[kernel.kallsyms]` | `step_into` | kernel |
| 0.28% | `python` | `PyStructSequence_SetItem` | unknown |
| 0.28% | `python` | `PyDict_GetItemRef` | dict |
| 0.27% | `python` | `long_dealloc` | memory |
| 0.27% | `python` | `tp_new_wrapper` | memory |
| 0.27% | `python` | `_PyMember_GetOffset` | unknown |
| 0.26% | `[kernel.kallsyms]` | `from_kuid_munged` | kernel |
| 0.26% | `[kernel.kallsyms]` | `__ext4fs_dirhash` | kernel |
| 0.26% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.26% | `libc.so.6` | `malloc` | libc |
| 0.26% | `[kernel.kallsyms]` | `call_filldir` | kernel |
| 0.25% | `[kernel.kallsyms]` | `__legitimize_mnt` | kernel |
| 0.25% | `[kernel.kallsyms]` | `terminate_walk` | kernel |

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
| 30.90% | `[JIT]` | `jit` | jit |
| 4.80% | `python` | `_Py_dict_lookup` | lookup |
| 4.74% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.41% | `python` | `_PyObject_Malloc` | memory |
| 3.41% | `python` | `_PyObject_Free` | memory |
| 3.21% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.43% | `python` | `initialize_locals` | interpreter |
| 1.93% | `python` | `_Py_Dealloc` | memory |
| 1.76% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.55% | `libc.so.6` | `__strlen_avx2` | libc |
| 1.49% | `python` | `tuple_dealloc` | memory |
| 1.29% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.28% | `python` | `PyBuffer_Release` | miscobj |
| 1.18% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.16% | `python` | `PyBuffer_FillInfo` | miscobj |
| 1.12% | `python` | `_PyTuple_Resize` | tuple |
| 1.00% | `python` | `PyDict_GetItemRef` | dict |
| 0.98% | `python` | `dict_get` | dict |
| 0.97% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.94% | `python` | `write_bytes_lock_held` | unknown |
| 0.90% | `python` | `_PyBytes_Concat` | unknown |
| 0.86% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.84% | `python` | `PyLong_FromVoidPtr` | int |
| 0.79% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.77% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.73% | `python` | `PyLong_FromSsize_t` | int |
| 0.70% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.66% | `python` | `sys_audit_tstate` | unknown |
| 0.59% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.58% | `_struct.cpython-316-x86_64-linux-gnu.so` | `pack` | library |
| 0.56% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.56% | `_struct.cpython-316-x86_64-linux-gnu.so` | `s_pack_internal` | library |
| 0.54% | `python` | `unicode_encode` | str |
| 0.53% | `python` | `tuple_alloc` | memory |
| 0.53% | `python` | `PyObject_Hash` | dynamic |
| 0.51% | `python` | `PySys_Audit` | unknown |
| 0.50% | `python` | `insertdict` | dict |
| 0.50% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.49% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.46% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.43% | `python` | `long_hash` | int |
| 0.42% | `python` | `builtin_id` | unknown |
| 0.42% | `python` | `dictiter_iternextitem` | dict |
| 0.40% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.39% | `python` | `PyBytes_FromStringAndSize.constprop.0` | str |
| 0.38% | `python` | `PyObject_Malloc` | dynamic |
| 0.38% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.37% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.36% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.35% | `python` | `_Py_NewReference` | memory |
| 0.35% | `python` | `_PyObject_Realloc` | memory |
| 0.34% | `python` | `PyObject_Size` | dynamic |
| 0.33% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.32% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.31% | `python` | `PyBytesWriter_FinishWithSize` | unknown |
| 0.31% | `python` | `bytes_buffer_getbuffer` | str |
| 0.30% | `libc.so.6` | `_int_malloc` | libc |
| 0.26% | `python` | `_PyJIT_Entry` | compiler |
| 0.26% | `python` | `_PyLong_FromMedium` | int |
| 0.26% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.26% | `python` | `unicode_encode_utf8` | str |

## pidigits

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.27% | `python` | `x_divrem` | int |
| 28.11% | `python` | `k_mul` | int |
| 13.67% | `python` | `x_add` | int |
| 6.69% | `python` | `x_sub` | int |
| 2.79% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.72% | `libc.so.6` | `_int_malloc` | libc |
| 0.94% | `[JIT]` | `jit` | jit |
| 0.45% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.43% | `python` | `_PyObject_Free` | memory |
| 0.43% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.40% | `python` | `_Py_Dealloc` | memory |
| 0.29% | `libc.so.6` | `malloc` | libc |
| 0.28% | `libc.so.6` | `unlink_chunk.isra.0` | libc |

## pprint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.55% | `[JIT]` | `jit` | jit |
| 4.96% | `python` | `_PyObject_Malloc` | memory |
| 4.36% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.38% | `python` | `_PyObject_Free` | memory |
| 3.14% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 2.28% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.24% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.01% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.98% | `python` | `_Py_Dealloc` | memory |
| 1.78% | `python` | `long_to_decimal_string_internal` | int |
| 1.66% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.52% | `python` | `set_lookkey` | miscobj |
| 1.46% | `python` | `_Py_type_getattro_impl` | dynamic |
| 1.34% | `python` | `_Py_dict_lookup` | lookup |
| 1.31% | `python` | `PyUnicode_Format` | str |
| 1.26% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.95% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.87% | `python` | `PyObject_IsSubclass` | dynamic |
| 0.85% | `python` | `list_sort_impl` | list |
| 0.84% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.80% | `python` | `tuple_alloc` | memory |
| 0.75% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.71% | `python` | `PyUnicode_New` | memory |
| 0.71% | `python` | `_PyObject_Realloc` | memory |
| 0.67% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.62% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.62% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.60% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.55% | `python` | `list_append` | list |
| 0.54% | `python` | `initialize_locals` | interpreter |
| 0.53% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.52% | `python` | `PyType_IsSubtype` | dynamic |
| 0.52% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.47% | `python` | `unicode_dealloc` | memory |
| 0.47% | `python` | `_Py_NewReference` | memory |
| 0.47% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.46% | `python` | `tuple_dealloc` | memory |
| 0.45% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.45% | `python` | `builtin_issubclass` | unknown |
| 0.44% | `python` | `PyObject_Repr` | dynamic |
| 0.44% | `python` | `unicode_repr` | str |
| 0.44% | `python` | `recursive_issubclass` | unknown |
| 0.44% | `python` | `delitem_common` | dynamic |
| 0.43% | `python` | `PyThread_get_thread_ident` | threading |
| 0.41% | `python` | `_PyUnicodeWriter_WriteSubstring` | str |
| 0.40% | `python` | `PyObject_Hash` | dynamic |
| 0.40% | `python` | `insertdict` | dict |
| 0.40% | `python` | `list_dealloc` | memory |
| 0.38% | `python` | `_PySet_Contains` | miscobj |
| 0.37% | `python` | `PyCMethod_New` | memory |
| 0.34% | `python` | `PyList_New.constprop.0` | memory |
| 0.34% | `python` | `_PyStolenTuple_Free` | unknown |
| 0.34% | `python` | `PyUnicode_New.part.0` | memory |
| 0.34% | `python` | `slot_tp_richcompare` | dynamic |
| 0.33% | `python` | `_PyDict_DelItem_KnownHash_LockHeld` | dict |
| 0.32% | `python` | `PyNumber_Remainder` | dynamic |
| 0.31% | `python` | `subtype_dealloc` | memory |
| 0.29% | `python` | `long_hash` | int |
| 0.29% | `python` | `builtin_getattr` | lookup |
| 0.27% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.27% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.27% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.27% | `python` | `_PyEval_Vector` | interpreter |
| 0.26% | `python` | `_Py_BuildString_StackRefSteal` | unknown |

## pycparser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.49% | `[JIT]` | `jit` | jit |
| 11.30% | `python` | `sre_ucs1_match` | library |
| 8.53% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.43% | `python` | `gc_collect_main` | gc |
| 2.41% | `python` | `_Py_dict_lookup` | lookup |
| 2.37% | `python` | `_PyObject_Malloc` | memory |
| 2.08% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.59% | `python` | `_PyObject_Free` | memory |
| 1.58% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.34% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.31% | `python` | `_PyDict_Subscript` | dict |
| 1.20% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.11% | `python` | `_Py_Dealloc` | memory |
| 1.11% | `python` | `visit_decref` | gc |
| 1.07% | `libc.so.6` | `_int_malloc` | libc |
| 0.89% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.88% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.84% | `python` | `subtype_traverse` | gc |
| 0.83% | `python` | `initialize_locals` | interpreter |
| 0.81% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.80% | `python` | `pattern_new_match` | memory |
| 0.79% | `python` | `list_ass_slice_lock_held` | list |
| 0.77% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.77% | `python` | `_PyJIT_Entry` | compiler |
| 0.71% | `python` | `dict_get` | dict |
| 0.70% | `python` | `sre_ucs1_count` | library |
| 0.67% | `python` | `visit_reachable` | gc |
| 0.67% | `python` | `PySlice_New` | memory |
| 0.61% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.59% | `python` | `PyObject_GetItem` | dynamic |
| 0.58% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.58% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.52% | `libc.so.6` | `malloc` | libc |
| 0.50% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.50% | `python` | `subtype_dealloc` | memory |
| 0.48% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.45% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.43% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.43% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.38% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.38% | `python` | `long_neg_method` | int |
| 0.38% | `python` | `list_ass_subscript` | list |
| 0.38% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.37% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.36% | `python` | `list_subscript` | list |
| 0.35% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.34% | `python` | `PyNumber_Negative` | dynamic |
| 0.34% | `python` | `_PyEval_Vector` | interpreter |
| 0.33% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.31% | `python` | `PyType_IsSubtype` | dynamic |
| 0.30% | `python` | `PyUnicode_Contains` | str |
| 0.30% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.30% | `python` | `PyObject_DelItem` | dynamic |
| 0.29% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.29% | `python` | `PyObject_SetItem` | dynamic |
| 0.29% | `python` | `list_dealloc` | memory |
| 0.28% | `libc.so.6` | `_int_free` | libc |
| 0.27% | `python` | `slot_mp_ass_subscript` | unknown |

## pyflate

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.16% | `[JIT]` | `jit` | jit |
| 5.22% | `python` | `list_dealloc` | memory |
| 4.97% | `python` | `list_ass_slice_lock_held` | list |
| 3.18% | `python` | `_PyList_Concat` | list |
| 2.19% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.18% | `python` | `list_slice_lock_held` | list |
| 1.96% | `python` | `_Py_Dealloc` | memory |
| 1.83% | `python` | `_PyCompactLong_Add` | unknown |
| 1.80% | `libc.so.6` | `_int_malloc` | libc |
| 1.74% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.68% | `python` | `stringlib_bytes_join` | str |
| 1.67% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.58% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.53% | `python` | `_PyObject_Malloc` | memory |
| 1.48% | `python` | `_PyObject_Free` | memory |
| 1.38% | `python` | `bytes_subscript` | str |
| 1.38% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.28% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.28% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.27% | `python` | `long_lshift_method` | int |
| 1.12% | `python` | `list_sort_impl` | list |
| 1.09% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.94% | `python` | `_PyLong_FromMedium` | int |
| 0.87% | `python` | `PyBuffer_Release` | miscobj |
| 0.85% | `python` | `long_lshift1` | int |
| 0.74% | `python` | `PyLong_AsSsize_t` | int |
| 0.71% | `python` | `unsafe_long_compare` | unknown |
| 0.69% | `python` | `PyLong_FromSsize_t` | int |
| 0.67% | `python` | `PyNumber_Lshift` | dynamic |
| 0.65% | `python` | `long_rshift` | int |
| 0.59% | `python` | `PyObject_GetItem` | dynamic |
| 0.58% | `python` | `PySlice_New` | memory |
| 0.58% | `python` | `long_dealloc` | memory |
| 0.57% | `python` | `_Py_NewReference` | memory |
| 0.56% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.51% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.50% | `python` | `PyList_New.constprop.0` | memory |
| 0.50% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.48% | `python` | `PyNumber_Rshift` | dynamic |
| 0.41% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.41% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.39% | `python` | `_PyList_GetItemRef` | list |
| 0.38% | `python` | `long_rshift1` | int |
| 0.37% | `python` | `enum_next` | miscobj |
| 0.34% | `python` | `_PyList_BinarySlice` | list |
| 0.34% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.33% | `libc.so.6` | `malloc` | libc |
| 0.31% | `python` | `gallop_left` | unknown |
| 0.30% | `python` | `gallop_right` | unknown |
| 0.26% | `python` | `compactlongs_guard` | unknown |
| 0.26% | `python` | `PyBytes_FromObject` | str |
| 0.26% | `python` | `PySlice_Unpack` | miscobj |

## pylint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.02% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.06% | `[JIT]` | `jit` | jit |
| 4.11% | `python` | `gc_collect_main` | gc |
| 2.74% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.66% | `python` | `_PyObject_Malloc` | memory |
| 2.45% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.91% | `python` | `_Py_dict_lookup` | lookup |
| 1.84% | `python` | `_PyObject_Free` | memory |
| 1.69% | `python` | `visit_decref` | gc |
| 1.60% | `python` | `visit_reachable` | gc |
| 1.55% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.27% | `python` | `initialize_locals` | interpreter |
| 1.15% | `python` | `_Py_Dealloc` | memory |
| 0.92% | `python` | `_PyPegen_is_memoized` | interpreter |
| 0.72% | `python` | `PyDict_GetItemRef` | dict |
| 0.63% | `python` | `unicode_repr` | str |
| 0.63% | `python` | `listiter_next` | list |
| 0.63% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.62% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.61% | `python` | `tuple_dealloc` | memory |
| 0.61% | `python` | `PyType_IsSubtype` | dynamic |
| 0.59% | `python` | `subtype_traverse` | gc |
| 0.57% | `python` | `insertdict` | dict |
| 0.55% | `python` | `dict_traverse` | gc |
| 0.53% | `python` | `_Py_ReachedRecursionLimitWithMargin` | unknown |
| 0.51% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.50% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.50% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.44% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.44% | `python` | `_PyPegen_expect_token` | interpreter |
| 0.42% | `python` | `PyObject_SetAttr` | dynamic |
| 0.42% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.42% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.42% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.42% | `python` | `tok_get_normal_mode` | compiler |
| 0.39% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.38% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.37% | `python` | `islice_next` | unknown |
| 0.37% | `python` | `_PyEval_Vector` | interpreter |
| 0.36% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.36% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.33% | `python` | `tok_nextc` | compiler |
| 0.33% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.33% | `python` | `_PyPegen_update_memo` | interpreter |
| 0.32% | `python` | `_PyJIT_Entry` | compiler |
| 0.31% | `python` | `partial_vectorcall` | unknown |
| 0.31% | `python` | `list_traverse` | gc |
| 0.31% | `python` | `tuple_alloc` | memory |
| 0.31% | `python` | `_PyObject_GC_New` | gc |
| 0.29% | `python` | `sre_ucs1_match` | library |
| 0.28% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.27% | `python` | `list_dealloc` | memory |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.26% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |

## python_startup

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 8.05% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.29% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.44% | `python` | `gc_collect_main` | gc |
| 2.97% | `python` | `visit_decref` | gc |
| 2.87% | `python` | `_PyObject_Malloc` | memory |
| 2.19% | `python` | `visit_reachable` | gc |
| 1.99% | `python` | `_Py_dict_lookup` | lookup |
| 1.83% | `python` | `r_object` | import |
| 1.81% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.45% | `python` | `_PyCode_Quicken` | interpreter |
| 1.37% | `python` | `_PyObject_Free` | memory |
| 1.36% | `python` | `find_name_in_mro` | lookup |
| 1.26% | `python` | `type_ready` | dynamic |
| 1.08% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.07% | `python` | `siphash13` | str |
| 1.04% | `python` | `dict_traverse` | gc |
| 0.99% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.96% | `python` | `_Py_Dealloc` | memory |
| 0.92% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.88% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.88% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.75% | `python` | `update_one_slot` | lookup |
| 0.73% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.71% | `python` | `tuple_dealloc` | memory |
| 0.68% | `python` | `insertdict` | dict |
| 0.67% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.65% | `libc.so.6` | `_int_malloc` | libc |
| 0.62% | `python` | `intern_constants` | str |
| 0.55% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.54% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.53% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.52% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.49% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.48% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.47% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.46% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.44% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.44% | `python` | `find_first_nonascii` | str |
| 0.42% | `python` | `PyUnicode_New.part.0` | memory |
| 0.39% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.39% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.38% | `python` | `PyDict_GetItemRef` | dict |
| 0.35% | `python` | `build_indices_unicode` | dict |
| 0.34% | `python` | `r_long` | import |
| 0.34% | `python` | `_PyCode_New` | interpreter |
| 0.34% | `[kernel.kallsyms]` | `copy_page` | kernel |
| 0.33% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.32% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.32% | `python` | `tuple_alloc` | memory |
| 0.32% | `[kernel.kallsyms]` | `next_uptodate_folio` | kernel |
| 0.31% | `python` | `code_dealloc` | memory |
| 0.31% | `python` | `initialize_locals` | interpreter |
| 0.31% | `python` | `tuple_traverse` | gc |
| 0.29% | `python` | `func_traverse` | gc |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.29% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.28% | `[kernel.kallsyms]` | `__handle_mm_fault` | kernel |
| 0.28% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.27% | `python` | `list_dealloc` | memory |
| 0.26% | `ld-linux-x86-64.so.2` | `do_lookup_x` | library |
| 0.25% | `libc.so.6` | `malloc` | libc |

## python_startup_no_site

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.84% | `python` | `gc_collect_main` | gc |
| 4.74% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.07% | `python` | `visit_decref` | gc |
| 2.99% | `python` | `_PyObject_Malloc` | memory |
| 2.45% | `python` | `visit_reachable` | gc |
| 2.29% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.92% | `python` | `_Py_dict_lookup` | lookup |
| 1.66% | `python` | `r_object` | import |
| 1.50% | `python` | `type_ready` | dynamic |
| 1.46% | `python` | `_PyObject_Free` | memory |
| 1.30% | `python` | `_PyCode_Quicken` | interpreter |
| 1.20% | `python` | `siphash13` | str |
| 1.20% | `python` | `dict_traverse` | gc |
| 1.20% | `python` | `find_name_in_mro` | lookup |
| 1.16% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.13% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.91% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.90% | `python` | `_Py_Dealloc` | memory |
| 0.85% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.83% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.83% | `python` | `insertdict` | dict |
| 0.81% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.73% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.65% | `python` | `update_one_slot` | lookup |
| 0.65% | `libc.so.6` | `_int_malloc` | libc |
| 0.64% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.60% | `python` | `intern_constants` | str |
| 0.59% | `python` | `find_first_nonascii` | str |
| 0.58% | `python` | `tuple_dealloc` | memory |
| 0.58% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.56% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.55% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.55% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.53% | `python` | `build_indices_unicode` | dict |
| 0.49% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.48% | `[kernel.kallsyms]` | `next_uptodate_folio` | kernel |
| 0.47% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.46% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.44% | `python` | `PyUnicode_New.part.0` | memory |
| 0.44% | `[kernel.kallsyms]` | `copy_page` | kernel |
| 0.42% | `ld-linux-x86-64.so.2` | `do_lookup_x` | library |
| 0.42% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.42% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.41% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.41% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.38% | `[kernel.kallsyms]` | `__handle_mm_fault` | kernel |
| 0.37% | `[kernel.kallsyms]` | `filemap_map_pages` | kernel |
| 0.35% | `python` | `_PyCode_New` | interpreter |
| 0.34% | `python` | `PyDict_GetItemRef` | dict |
| 0.30% | `python` | `PyObject_IS_GC` | gc |
| 0.29% | `[kernel.kallsyms]` | `mas_walk` | kernel |
| 0.29% | `python` | `tuple_traverse` | gc |
| 0.28% | `python` | `r_long` | import |
| 0.27% | `python` | `PyDict_Next` | dict |
| 0.27% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.26% | `python` | `code_dealloc` | memory |
| 0.26% | `python` | `initialize_locals` | interpreter |
| 0.25% | `[kernel.kallsyms]` | `__count_memcg_events` | kernel |

## raytrace

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 42.37% | `[JIT]` | `jit` | jit |
| 6.44% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.04% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.32% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 3.32% | `python` | `_Py_Dealloc` | memory |
| 2.94% | `python` | `PyFloat_FromDouble` | float |
| 2.07% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.81% | `python` | `initialize_locals` | interpreter |
| 1.74% | `python` | `_PyObject_Free` | memory |
| 1.71% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 1.50% | `python` | `subtype_dealloc` | memory |
| 1.33% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.15% | `python` | `_PyObject_Malloc` | memory |
| 1.12% | `python` | `_PyType_AllocNoTrack` | memory |
| 1.05% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.05% | `python` | `float_dealloc` | memory |
| 0.91% | `python` | `_Py_NewReference` | memory |
| 0.81% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.76% | `python` | `PyNumber_Subtract` | dynamic |
| 0.73% | `python` | `PyType_IsSubtype` | dynamic |
| 0.73% | `python` | `PyType_GenericAlloc` | memory |
| 0.66% | `python` | `_PyEval_Vector` | interpreter |
| 0.66% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.63% | `python` | `float_richcompare` | float |
| 0.58% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.57% | `python` | `vectorcall_maybe` | unknown |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.54% | `python` | `_PyJIT_Entry` | compiler |
| 0.53% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.49% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.37% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.36% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.36% | `python` | `min_max` | unknown |
| 0.34% | `python` | `PyObject_RichCompare` | dynamic |
| 0.34% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.32% | `python` | `PyObject_GC_Del` | gc |
| 0.32% | `python` | `tuple_alloc` | memory |
| 0.31% | `python` | `float_sub` | float |
| 0.31% | `python` | `compactlong_float_guard` | unknown |
| 0.31% | `python` | `slot_nb_subtract` | unknown |
| 0.30% | `python` | `compactlong_float_subtract` | unknown |
| 0.25% | `python` | `PyLong_AsDouble` | int |

## regex_compile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.73% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 21.99% | `[JIT]` | `jit` | jit |
| 2.46% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.34% | `python` | `_Py_Dealloc` | memory |
| 2.20% | `python` | `_PyObject_Malloc` | memory |
| 1.67% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.20% | `python` | `_PyObject_Free` | memory |
| 1.15% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.97% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.91% | `python` | `_PyLong_FromMedium` | int |
| 0.91% | `python` | `bytearray_ass_subscript_lock_held` | miscobj |
| 0.90% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.82% | `python` | `_PyJIT_Entry` | compiler |
| 0.76% | `python` | `PyUnicode_Contains` | str |
| 0.71% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.70% | `python` | `PyType_IsSubtype` | dynamic |
| 0.70% | `python` | `initialize_locals` | interpreter |
| 0.68% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.67% | `python` | `PyObject_SetItem` | dynamic |
| 0.65% | `python` | `tuple_alloc` | memory |
| 0.64% | `python` | `set_lookkey` | miscobj |
| 0.64% | `python` | `list_append` | list |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.61% | `python` | `PyLong_FromLong` | int |
| 0.61% | `python` | `tuple_dealloc` | memory |
| 0.57% | `python` | `min_max` | unknown |
| 0.57% | `python` | `list_dealloc` | memory |
| 0.56% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.56% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.55% | `python` | `make_range_object` | unknown |
| 0.52% | `python` | `_PyUnicode_Equal` | str |
| 0.50% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.50% | `python` | `_PyEval_Vector` | interpreter |
| 0.50% | `python` | `_Py_dict_lookup` | lookup |
| 0.48% | `python` | `PyLong_FromSsize_t` | int |
| 0.45% | `python` | `_PyCompactLong_Add` | unknown |
| 0.41% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.41% | `python` | `_Py_NewReference` | memory |
| 0.40% | `python` | `_PyObject_Realloc` | memory |
| 0.38% | `python` | `bytearray_ass_subscript` | miscobj |
| 0.37% | `python` | `PyLong_AsSsize_t` | int |
| 0.37% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.35% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.35% | `python` | `_PySet_Contains` | miscobj |
| 0.35% | `python` | `PyList_New.constprop.0` | memory |
| 0.35% | `python` | `slot_sq_item` | unknown |
| 0.33% | `python` | `long_dealloc` | memory |
| 0.31% | `python` | `PyMethod_New` | memory |
| 0.30% | `python` | `long_richcompare` | int |
| 0.28% | `python` | `PyObject_Hash` | dynamic |
| 0.28% | `python` | `PyObject_Size` | dynamic |
| 0.27% | `python` | `_validate_inner` | unknown |
| 0.26% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.26% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.26% | `python` | `PyObject_IsInstance` | dynamic |
| 0.26% | `python` | `PyCMethod_New` | memory |
| 0.26% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.25% | `python` | `PyLong_FromString` | int |

## regex_dna

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 54.44% | `python` | `sre_ucs1_match` | library |
| 30.35% | `python` | `sre_ucs1_charset.isra.0` | library |
| 8.97% | `python` | `sre_search` | library |
| 1.05% | `python` | `pattern_subx` | library |
| 0.92% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.61% | `python` | `stringlib_bytes_join` | str |
| 0.31% | `python` | `_PyObject_Malloc` | memory |
| 0.28% | `python` | `PyBuffer_Release` | miscobj |
| 0.27% | `python` | `PyList_Append` | list |

## regex_effbot

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 68.68% | `python` | `sre_ucs1_match` | library |
| 14.65% | `python` | `sre_ucs1_charset.isra.0` | library |
| 8.47% | `python` | `sre_search` | library |
| 3.36% | `python` | `sre_ucs1_count` | library |
| 1.08% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.46% | `python` | `siphash13` | str |

## regex_v8

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 56.12% | `python` | `sre_ucs1_match` | library |
| 6.97% | `python` | `sre_search` | library |
| 5.85% | `python` | `sre_ucs1_count` | library |
| 2.46% | `python` | `pattern_subx` | library |
| 2.20% | `python` | `_PyObject_Malloc` | memory |
| 2.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.99% | `python` | `_PyObject_Free` | memory |
| 1.69% | `[JIT]` | `jit` | jit |
| 1.65% | `libc.so.6` | `_int_malloc` | libc |
| 1.59% | `python` | `pattern_new_match` | memory |
| 1.53% | `python` | `_sre_SRE_Pattern_search` | library |
| 1.06% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.90% | `libc.so.6` | `malloc` | libc |
| 0.82% | `python` | `_PyUnicode_ToLowercase` | str |
| 0.66% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.66% | `python` | `_PyUnicode_IsAlpha` | str |
| 0.56% | `libc.so.6` | `_int_free` | libc |
| 0.54% | `python` | `PyList_Append` | list |
| 0.53% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.50% | `python` | `_Py_Dealloc` | memory |
| 0.44% | `python` | `PyUnicode_Substring` | str |
| 0.42% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.40% | `libc.so.6` | `cfree@GLIBC_2.2.5` | libc |
| 0.34% | `python` | `_PyObject_Realloc` | memory |
| 0.31% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.28% | `python` | `sre_ucs1_charset.isra.0` | library |
| 0.27% | `python` | `method_vectorcall_FASTCALL_KEYWORDS_METHOD` | calls |
| 0.27% | `libc.so.6` | `_int_free_maybe_consolidate` | libc |
| 0.26% | `python` | `_Py_dict_lookup` | lookup |
| 0.26% | `python` | `list_dealloc` | memory |
| 0.25% | `python` | `PyErr_Occurred` | exceptions |

## richards

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 68.98% | `[JIT]` | `jit` | jit |
| 8.84% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 5.96% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.76% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.45% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.79% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.33% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.12% | `python` | `_PyCompactLong_Add` | unknown |
| 0.88% | `python` | `_Py_Dealloc` | memory |
| 0.82% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.69% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.50% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.39% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.36% | `python` | `long_div` | int |
| 0.31% | `python` | `long_dealloc` | memory |
| 0.27% | `python` | `_PyLong_FromMedium` | int |

## richards_super

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 71.14% | `[JIT]` | `jit` | jit |
| 8.97% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 5.73% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.55% | `python` | `_PyThreadState_PopFrame` | threading |
| 2.16% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.34% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.16% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.00% | `python` | `_PyCompactLong_Add` | unknown |
| 0.88% | `python` | `_Py_Dealloc` | memory |
| 0.66% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.56% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.41% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.36% | `python` | `long_dealloc` | memory |
| 0.35% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.35% | `python` | `long_div` | int |

## scimark

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 33.66% | `[JIT]` | `jit` | jit |
| 4.93% | `array.cpython-316-x86_64-linux-gnu.so` | `array_subscr` | library |
| 4.91% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 4.01% | `python` | `PyFloat_FromDouble` | float |
| 3.58% | `python` | `_Py_Dealloc` | memory |
| 3.29% | `python` | `PyObject_GetItem` | dynamic |
| 3.20% | `python` | `vgetargs1_impl.constprop.0` | calls |
| 2.80% | `python` | `convertitem.constprop.0` | unknown |
| 2.20% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.04% | `python` | `PyLong_AsSsize_t` | int |
| 1.81% | `array.cpython-316-x86_64-linux-gnu.so` | `array_ass_subscr` | library |
| 1.80% | `python` | `_Py_NewReference` | memory |
| 1.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.56% | `python` | `_PyCompactLong_Add` | unknown |
| 1.41% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.39% | `python` | `PyIndex_Check` | unknown |
| 1.35% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.31% | `python` | `PyType_GetModuleByDef` | dynamic |
| 1.29% | `python` | `PyArg_Parse` | calls |
| 1.23% | `array.cpython-316-x86_64-linux-gnu.so` | `d_setitem` | library |
| 1.12% | `python` | `PyObject_SetItem` | dynamic |
| 1.09% | `array.cpython-316-x86_64-linux-gnu.so` | `d_getitem` | library |
| 1.03% | `python` | `_PyCompactLong_Multiply` | unknown |
| 1.01% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.98% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.97% | `python` | `PyLong_FromLong` | int |
| 0.91% | `python` | `float_dealloc` | memory |
| 0.57% | `python` | `PyType_IsSubtype` | dynamic |
| 0.56% | `python` | `PyFloat_AsDouble` | float |
| 0.53% | `python` | `object_isinstance` | dynamic |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.50% | `array.cpython-316-x86_64-linux-gnu.so` | `PyIndex_Check@plt` | library |
| 0.50% | `python` | `tuple_dealloc` | memory |
| 0.48% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.48% | `python` | `_PyLong_FromMedium` | int |
| 0.47% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.47% | `python` | `float_richcompare` | float |
| 0.46% | `python` | `long_dealloc` | memory |
| 0.45% | `array.cpython-316-x86_64-linux-gnu.so` | `PyNumber_AsSsize_t@plt` | library |
| 0.44% | `array.cpython-316-x86_64-linux-gnu.so` | `PyType_GetModuleByDef@plt` | library |
| 0.42% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.42% | `python` | `_PyLong_Frexp` | int |
| 0.34% | `python` | `tuple_alloc` | memory |
| 0.31% | `python` | `_PyType_GetDict` | dynamic |
| 0.31% | `python` | `PyObject_IsInstance` | dynamic |
| 0.28% | `array.cpython-316-x86_64-linux-gnu.so` | `PyFloat_FromDouble@plt` | library |
| 0.27% | `python` | `make_range_object` | unknown |
| 0.27% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.27% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.26% | `python` | `getset_get` | dynamic |

## spectral_norm

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 47.11% | `[JIT]` | `jit` | jit |
| 10.15% | `python` | `_PyCompactLong_Add` | unknown |
| 5.16% | `python` | `long_div` | int |
| 4.24% | `python` | `_PyCompactLong_Multiply` | unknown |
| 4.05% | `python` | `enum_next` | miscobj |
| 3.45% | `python` | `float_compactlong_true_div` | float |
| 3.37% | `python` | `listiter_next` | list |
| 2.58% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.28% | `python` | `PyNumber_FloorDivide` | dynamic |
| 2.21% | `python` | `_PyLong_ExactDealloc` | memory |
| 2.15% | `python` | `_Py_NewReference` | memory |
| 1.85% | `python` | `PyFloat_FromDouble` | float |
| 1.54% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.47% | `python` | `_PyLong_FromMedium` | int |
| 1.29% | `python` | `PyLong_FromSsize_t` | int |
| 1.23% | `python` | `_Py_Dealloc` | memory |
| 1.18% | `python` | `PyLong_FromLong` | int |
| 0.91% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.82% | `python` | `nonzero_float_compactlong_guard` | unknown |
| 0.76% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.35% | `python` | `float_compactlong_guard` | float |
| 0.33% | `python` | `float_dealloc` | memory |
| 0.27% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |

## sphinx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 12.52% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.96% | `[JIT]` | `jit` | jit |
| 7.54% | `python` | `sre_ucs1_match` | library |
| 4.68% | `python` | `gc_collect_main` | gc |
| 3.20% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.52% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.37% | `python` | `_PyObject_Malloc` | memory |
| 2.22% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.88% | `python` | `sre_ucs1_charset.isra.0` | library |
| 1.52% | `python` | `_PyObject_Free` | memory |
| 1.51% | `python` | `_Py_dict_lookup` | lookup |
| 1.51% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.37% | `python` | `visit_decref` | gc |
| 1.05% | `python` | `_Py_Dealloc` | memory |
| 0.99% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.98% | `python` | `PyType_IsSubtype` | dynamic |
| 0.96% | `python` | `initialize_locals` | interpreter |
| 0.91% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.91% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.88% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `save.constprop.0` | library |
| 0.85% | `python` | `visit_reachable` | gc |
| 0.70% | `python` | `siphash13` | str |
| 0.60% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.60% | `python` | `PyUnicode_Format` | str |
| 0.58% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.48% | `python` | `_PyJIT_Entry` | compiler |
| 0.48% | `python` | `tuple_dealloc` | memory |
| 0.48% | `python` | `PyDict_GetItemRef` | dict |
| 0.46% | `python` | `gen_dealloc` | memory |
| 0.45% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.44% | `python` | `list_dealloc` | memory |
| 0.44% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.44% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.44% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `save_dict` | library |
| 0.43% | `python` | `sre_search` | library |
| 0.40% | `python` | `object_isinstance` | dynamic |
| 0.40% | `python` | `tuple_alloc` | memory |
| 0.38% | `python` | `sre_ucs2_match` | library |
| 0.37% | `python` | `_PyEval_Vector` | interpreter |
| 0.37% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.35% | `python` | `PyObject_IsInstance` | dynamic |
| 0.35% | `python` | `dict_traverse` | gc |
| 0.35% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 0.32% | `libc.so.6` | `_int_malloc` | libc |
| 0.31% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.30% | `python` | `pattern_subx` | library |
| 0.30% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.29% | `python` | `replace` | str |
| 0.29% | `python` | `getset_get` | dynamic |
| 0.28% | `python` | `_PyDict_Subscript` | dict |
| 0.28% | `python` | `find_name_in_mro` | lookup |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.27% | `python` | `PyObject_SetAttr` | dynamic |
| 0.26% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.26% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.25% | `libc.so.6` | `malloc` | libc |
| 0.25% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |

## sqlalchemy_declarative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.54% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.53% | `[JIT]` | `jit` | jit |
| 3.63% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.82% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.50% | `python` | `_PyObject_Malloc` | memory |
| 1.84% | `python` | `_Py_dict_lookup` | lookup |
| 1.77% | `python` | `_Py_Dealloc` | memory |
| 1.60% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.57% | `python` | `_PyObject_Free` | memory |
| 1.41% | `python` | `initialize_locals` | interpreter |
| 1.39% | `python` | `tuple_dealloc` | memory |
| 1.27% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.85% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.82% | `python` | `tuple_alloc` | memory |
| 0.80% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.77% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.76% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.75% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.68% | `python` | `PyObject_SetAttr` | dynamic |
| 0.65% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.59% | `python` | `PyType_IsSubtype` | dynamic |
| 0.56% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.55% | `python` | `dict_dealloc` | memory |
| 0.53% | `python` | `PyObject_IsTrue` | dynamic |
| 0.52% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.52% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.51% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.48% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.47% | `python` | `take_gil` | gil |
| 0.47% | `python` | `subtype_dealloc` | memory |
| 0.46% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.46% | `python` | `_PyDict_Subscript` | dict |
| 0.46% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.45% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.44% | `python` | `set_lookkey` | miscobj |
| 0.43% | `python` | `_PyEval_Vector` | interpreter |
| 0.39% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.38% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.36% | `python` | `list_dealloc` | memory |
| 0.35% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.34% | `python` | `find_name_in_mro` | lookup |
| 0.34% | `python` | `set_dealloc` | memory |
| 0.33% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.33% | `python` | `insertdict` | dict |
| 0.33% | `python` | `_PyJIT_Entry` | compiler |
| 0.31% | `python` | `PyObject_Hash` | dynamic |
| 0.30% | `python` | `_PyUnicode_InternMortal` | str |
| 0.29% | `python` | `PyDict_GetItemRef` | dict |
| 0.29% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `set_add_entry_takeref` | miscobj |
| 0.28% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.27% | `python` | `PyType_GenericAlloc` | memory |
| 0.27% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.25% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.25% | `python` | `_PyObject_GC_New` | gc |

## sqlalchemy_imperative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.68% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.35% | `[JIT]` | `jit` | jit |
| 4.21% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.25% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.07% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 1.95% | `python` | `_PyObject_Malloc` | memory |
| 1.89% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `_Py_dict_lookup` | lookup |
| 1.41% | `python` | `_Py_Dealloc` | memory |
| 1.39% | `python` | `initialize_locals` | interpreter |
| 1.16% | `python` | `_PyObject_Free` | memory |
| 0.98% | `python` | `tuple_dealloc` | memory |
| 0.90% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.76% | `python` | `gc_collect_main` | gc |
| 0.68% | `python` | `tuple_alloc` | memory |
| 0.66% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.66% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.65% | `python` | `PyObject_SetAttr` | dynamic |
| 0.63% | `python` | `PyObject_IsTrue` | dynamic |
| 0.63% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.62% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.61% | `python` | `dict_dealloc` | memory |
| 0.59% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.58% | `python` | `PyType_IsSubtype` | dynamic |
| 0.58% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.54% | `python` | `subtype_dealloc` | memory |
| 0.49% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.44% | `python` | `PyDict_GetItemRef` | dict |
| 0.43% | `python` | `_PyJIT_Entry` | compiler |
| 0.42% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.41% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.38% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.38% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.37% | `python` | `insertdict` | dict |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.35% | `python` | `_PyType_GetDict` | dynamic |
| 0.34% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.33% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.31% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.29% | `python` | `long_to_decimal_string_internal` | int |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.28% | `python` | `insert_to_emptydict` | dict |
| 0.28% | `python` | `list_dealloc` | memory |
| 0.27% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_query_execute` | library |
| 0.26% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.26% | `libsqlite3.so.0.8.6` | `sqlite3Parser` | library |
| 0.25% | `python` | `new_dict` | dict |
| 0.25% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.25% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.25% | `python` | `_PyDict_FromItems` | dict |

## sqlglot_v2

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.25% | `[JIT]` | `jit` | jit |
| 15.65% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.99% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.43% | `python` | `_PyObject_Malloc` | memory |
| 3.24% | `python` | `_PyObject_Free` | memory |
| 3.18% | `python` | `_Py_Dealloc` | memory |
| 2.59% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.46% | `python` | `PyType_IsSubtype` | dynamic |
| 2.32% | `python` | `dictiter_iternextitem` | dict |
| 2.08% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.52% | `python` | `PyObject_IsInstance` | dynamic |
| 1.33% | `python` | `tuple_dealloc` | memory |
| 1.28% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.27% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.18% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.14% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.10% | `python` | `object_isinstance` | dynamic |
| 1.08% | `python` | `PyCMethod_New` | memory |
| 1.04% | `python` | `_PyJIT_Entry` | compiler |
| 0.95% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.93% | `python` | `initialize_locals` | interpreter |
| 0.84% | `python` | `_PyObject_GC_New` | gc |
| 0.81% | `python` | `insert_to_emptydict` | dict |
| 0.80% | `python` | `getset_get` | dynamic |
| 0.79% | `python` | `_PyObject_LookupSpecial` | dynamic |
| 0.76% | `python` | `tuple_alloc` | memory |
| 0.73% | `python` | `meth_dealloc` | memory |
| 0.73% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.68% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.64% | `python` | `gen_dealloc` | memory |
| 0.61% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.61% | `python` | `_Py_dict_lookup` | lookup |
| 0.61% | `python` | `_PyObject_Calloc` | memory |
| 0.58% | `python` | `_Py_NewReference` | memory |
| 0.54% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.49% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.43% | `python` | `dict_get` | dict |
| 0.42% | `python` | `PyObject_GC_Del` | gc |
| 0.41% | `python` | `list_dealloc` | memory |
| 0.38% | `python` | `method_get` | dynamic |
| 0.38% | `python` | `PyObject_IsTrue` | dynamic |
| 0.38% | `python` | `tuple_hash` | tuple |
| 0.36% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.36% | `python` | `PyList_New` | memory |
| 0.34% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.33% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.33% | `python` | `make_gen` | miscobj |
| 0.33% | `python` | `func_clear` | unknown |
| 0.33% | `python` | `_PyEval_Vector` | interpreter |
| 0.32% | `python` | `dictitems_iter` | unknown |
| 0.31% | `python` | `cfunction_vectorcall_O` | calls |
| 0.30% | `python` | `dictiter_dealloc` | memory |
| 0.30% | `python` | `new_dict` | dict |
| 0.30% | `python` | `_PyObject_GC_Link` | gc |
| 0.28% | `python` | `PyMem_Calloc` | memory |
| 0.27% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.27% | `python` | `PyDescr_IsData` | dynamic |
| 0.27% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.26% | `python` | `PyLong_FromSsize_t` | int |
| 0.26% | `python` | `_PyTuple_FromPairSteal` | tuple |
| 0.26% | `python` | `PyObject_Hash` | dynamic |
| 0.25% | `python` | `PyDict_GetItemRef` | dict |

## sqlglot_v2_optimize

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.44% | `[JIT]` | `jit` | jit |
| 16.42% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.59% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.41% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 3.06% | `python` | `_Py_Dealloc` | memory |
| 2.94% | `python` | `_PyObject_Malloc` | memory |
| 2.89% | `python` | `PyType_IsSubtype` | dynamic |
| 2.88% | `python` | `_PyObject_Free` | memory |
| 2.49% | `python` | `dictiter_iternextitem` | dict |
| 1.89% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.50% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.46% | `python` | `PyObject_IsInstance` | dynamic |
| 1.29% | `python` | `tuple_dealloc` | memory |
| 1.17% | `python` | `PyCMethod_New` | memory |
| 1.14% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.10% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.08% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.97% | `python` | `object_isinstance` | dynamic |
| 0.92% | `python` | `_PyObject_LookupSpecial` | dynamic |
| 0.89% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.76% | `python` | `_Py_dict_lookup` | lookup |
| 0.76% | `python` | `getset_get` | dynamic |
| 0.75% | `python` | `_PyObject_GC_New` | gc |
| 0.72% | `python` | `meth_dealloc` | memory |
| 0.71% | `python` | `initialize_locals` | interpreter |
| 0.69% | `python` | `tuple_alloc` | memory |
| 0.66% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.63% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.57% | `python` | `_PyJIT_Entry` | compiler |
| 0.53% | `python` | `tuple_hash` | tuple |
| 0.52% | `python` | `_Py_NewReference` | memory |
| 0.51% | `python` | `dict_get` | dict |
| 0.50% | `python` | `_PyObject_Calloc` | memory |
| 0.47% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.47% | `python` | `insert_to_emptydict` | dict |
| 0.45% | `python` | `PyObject_Hash` | dynamic |
| 0.45% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `PyList_New` | memory |
| 0.41% | `python` | `cfunction_vectorcall_O` | calls |
| 0.41% | `python` | `method_get` | dynamic |
| 0.37% | `python` | `PyObject_IsTrue` | dynamic |
| 0.37% | `python` | `PyMember_GetOne` | lookup |
| 0.35% | `python` | `object_recursive_isinstance` | dynamic |
| 0.35% | `python` | `gc_collect_main` | gc |
| 0.35% | `python` | `_PyEval_Vector` | interpreter |
| 0.34% | `python` | `PyObject_GC_Del` | gc |
| 0.34% | `python` | `PyMem_Calloc` | memory |
| 0.32% | `python` | `_PyType_GetDict` | dynamic |
| 0.32% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.31% | `python` | `gen_dealloc` | memory |
| 0.31% | `python` | `PyDescr_IsData` | dynamic |
| 0.31% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.30% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.29% | `python` | `siphash13` | str |
| 0.29% | `python` | `func_clear` | unknown |
| 0.28% | `python` | `insertdict` | dict |
| 0.27% | `python` | `type___instancecheck__` | dynamic |
| 0.26% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.25% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |

## sqlglot_v2_parse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.18% | `[JIT]` | `jit` | jit |
| 14.88% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.36% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.62% | `python` | `initialize_locals` | interpreter |
| 2.46% | `python` | `_PyObject_Malloc` | memory |
| 2.21% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.06% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.87% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.85% | `python` | `gc_collect_main` | gc |
| 1.73% | `python` | `_Py_dict_lookup` | lookup |
| 1.66% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.53% | `python` | `_PyObject_Free` | memory |
| 1.41% | `python` | `_Py_Dealloc` | memory |
| 1.21% | `python` | `PyObject_RichCompare` | dynamic |
| 1.02% | `python` | `_PyCompactLong_Add` | unknown |
| 0.83% | `python` | `_PyJIT_Entry` | compiler |
| 0.80% | `python` | `PyType_IsSubtype` | dynamic |
| 0.72% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.72% | `python` | `dictiter_iternextitem` | dict |
| 0.68% | `python` | `visit_decref` | gc |
| 0.66% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.65% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.64% | `python` | `dict_get` | dict |
| 0.59% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.52% | `python` | `_PyEval_Vector` | interpreter |
| 0.50% | `python` | `PyDict_Contains` | dict |
| 0.50% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.46% | `python` | `PyObject_SetAttr` | dynamic |
| 0.42% | `python` | `clear_slots` | unknown |
| 0.39% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.36% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.36% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.36% | `python` | `insert_to_emptydict` | dict |
| 0.36% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.35% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.35% | `python` | `subtype_traverse` | gc |
| 0.35% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.34% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.33% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.33% | `python` | `object_richcompare` | dynamic |
| 0.33% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.32% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `PyLong_FromSsize_t` | int |
| 0.32% | `python` | `set_lookkey` | miscobj |
| 0.30% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.29% | `python` | `unicode_strip` | str |
| 0.29% | `python` | `PyObject_IsInstance` | dynamic |
| 0.28% | `python` | `dict_traverse` | gc |
| 0.28% | `python` | `dict_dealloc` | memory |
| 0.28% | `python` | `slot_tp_hash` | unknown |
| 0.26% | `python` | `PyObject_IsTrue` | dynamic |

## sqlglot_v2_transpile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.25% | `[JIT]` | `jit` | jit |
| 18.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.41% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.60% | `python` | `initialize_locals` | interpreter |
| 2.54% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.36% | `python` | `_PyObject_Malloc` | memory |
| 2.35% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.01% | `python` | `_Py_dict_lookup` | lookup |
| 1.88% | `python` | `_PyObject_Free` | memory |
| 1.79% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.64% | `python` | `gc_collect_main` | gc |
| 1.51% | `python` | `_Py_Dealloc` | memory |
| 1.48% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.06% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.93% | `python` | `PyType_IsSubtype` | dynamic |
| 0.87% | `python` | `_PyCompactLong_Add` | unknown |
| 0.81% | `python` | `PyObject_RichCompare` | dynamic |
| 0.77% | `python` | `_PyJIT_Entry` | compiler |
| 0.76% | `python` | `dict_get` | dict |
| 0.70% | `python` | `dictiter_iternextitem` | dict |
| 0.67% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.63% | `python` | `visit_decref` | gc |
| 0.59% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.46% | `python` | `PyObject_IsTrue` | dynamic |
| 0.43% | `python` | `PyDict_Contains` | dict |
| 0.41% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.41% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.40% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.39% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.39% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.38% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.37% | `python` | `subtype_traverse` | gc |
| 0.37% | `python` | `_PyEval_Vector` | interpreter |
| 0.36% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `python` | `PyObject_SetAttr` | dynamic |
| 0.34% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.34% | `python` | `PyObject_IsInstance` | dynamic |
| 0.34% | `python` | `insert_to_emptydict` | dict |
| 0.33% | `python` | `tuple_dealloc` | memory |
| 0.33% | `python` | `_PyObject_GC_New` | gc |
| 0.30% | `python` | `object_richcompare` | dynamic |
| 0.30% | `python` | `clear_slots` | unknown |
| 0.30% | `python` | `PyCMethod_New` | memory |
| 0.30% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.29% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.27% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.27% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.27% | `python` | `insertdict` | dict |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `dict_traverse` | gc |

## sqlite_synth

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.66% | `python` | `take_gil` | gil |
| 5.94% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 5.69% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 4.42% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 4.30% | `[JIT]` | `jit` | jit |
| 3.23% | `python` | `_Py_Dealloc` | memory |
| 3.00% | `libm.so.6` | `__cos_fma` | library |
| 2.32% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_query_execute` | library |
| 2.23% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 2.00% | `libc.so.6` | `pthread_cond_signal@@GLIBC_2.3.2` | libc |
| 1.85% | `python` | `_PyObject_Free` | memory |
| 1.72% | `python` | `drop_gil` | gil |
| 1.31% | `python` | `_PyObject_Malloc` | memory |
| 1.27% | `python` | `long_to_decimal_string_internal` | int |
| 1.18% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_fetch_one_row.constprop.0` | library |
| 1.04% | `libsqlite3.so.0.8.6` | `sqlite3BtreeInsert` | library |
| 1.04% | `python` | `_PyThreadState_Detach` | threading |
| 1.02% | `python` | `_PyThreadState_Attach` | threading |
| 1.02% | `python` | `PyEval_SaveThread` | interpreter |
| 1.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.95% | `python` | `_PyThreadState_MustExit` | threading |
| 0.81% | `python` | `tuple_dealloc` | memory |
| 0.79% | `python` | `PyFloat_FromDouble` | float |
| 0.78% | `libsqlite3.so.0.8.6` | `sqlite3_step` | library |
| 0.72% | `python` | `PyThread_get_thread_ident` | threading |
| 0.69% | `python` | `tuple_alloc` | memory |
| 0.68% | `python` | `_Py_NewReference` | memory |
| 0.56% | `python` | `_PyLong_FromMedium` | int |
| 0.53% | `libsqlite3.so.0.8.6` | `sqlite3VdbeHalt` | library |
| 0.53% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.53% | `python` | `_Py_IsMainThread` | unknown |
| 0.52% | `python` | `PyTuple_New` | memory |
| 0.51% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.48% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `bind_param` | library |
| 0.47% | `libsqlite3.so.0.8.6` | `0x00000000000bd72a` | library |
| 0.47% | `python` | `PyFloat_AsDouble` | float |
| 0.46% | `python` | `list_iter` | list |
| 0.46% | `libsqlite3.so.0.8.6` | `sqlite3_column_type` | library |
| 0.46% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.44% | `libsqlite3.so.0.8.6` | `sqlite3BtreeBeginTrans` | library |
| 0.43% | `python` | `PyList_New` | memory |
| 0.42% | `python` | `_Py_dict_lookup` | lookup |
| 0.42% | `python` | `pthread_mutex_unlock@plt` | unknown |
| 0.38% | `math.cpython-316-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.38% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.38% | `python` | `_PyCompactLong_Add` | unknown |
| 0.37% | `python` | `pthread_mutex_lock@plt` | unknown |
| 0.37% | `python` | `float_dealloc` | memory |
| 0.36% | `libsqlite3.so.0.8.6` | `sqlite3BtreeNext` | library |
| 0.36% | `python` | `PyObject_CallObject` | dynamic |
| 0.36% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.34% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_build_py_params` | library |
| 0.34% | `libsqlite3.so.0.8.6` | `sqlite3_reset` | library |
| 0.34% | `python` | `long_float` | int |
| 0.33% | `libsqlite3.so.0.8.6` | `sqlite3_column_double` | library |
| 0.33% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.33% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemGrow` | library |
| 0.33% | `python` | `list_dealloc` | memory |
| 0.32% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.31% | `libsqlite3.so.0.8.6` | `sqlite3BtreeCloseCursor` | library |
| 0.30% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `pysqlite_cursor_init` | library |
| 0.29% | `python` | `listiter_next` | list |
| 0.28% | `python` | `_PyDict_GetItemRef_KnownHash_LockHeld` | dict |
| 0.28% | `python` | `long_dealloc` | memory |
| 0.27% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.27% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `pysqlite_connection_execute` | library |
| 0.27% | `libsqlite3.so.0.8.6` | `0x00000000000bd749` | library |
| 0.26% | `python` | `_PyEval_Vector` | interpreter |
| 0.26% | `libsqlite3.so.0.8.6` | `sqlite3_mutex_enter` | library |
| 0.26% | `python` | `PyUnicode_New` | memory |
| 0.26% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemSetStr` | library |
| 0.26% | `python` | `PyLong_FromLongLong` | int |
| 0.26% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.26% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `step_callback` | library |
| 0.26% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `check_cursor` | library |

## sympy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 13.37% | `[JIT]` | `jit` | jit |
| 4.22% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.82% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.30% | `python` | `_Py_dict_lookup` | lookup |
| 2.16% | `python` | `_PyObject_Malloc` | memory |
| 2.08% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.04% | `python` | `_Py_Dealloc` | memory |
| 1.82% | `python` | `initialize_locals` | interpreter |
| 1.46% | `python` | `_PyObject_Free` | memory |
| 1.46% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.41% | `python` | `tuple_dealloc` | memory |
| 1.41% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.23% | `python` | `PyType_IsSubtype` | dynamic |
| 0.95% | `python` | `tuple_alloc` | memory |
| 0.92% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.89% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.88% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.83% | `python` | `_PyJIT_Entry` | compiler |
| 0.82% | `python` | `PyDict_GetItemRef` | dict |
| 0.75% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.68% | `python` | `insertdict` | dict |
| 0.61% | `python` | `_PyEval_Vector` | interpreter |
| 0.61% | `python` | `PyUnicode_RichCompare` | str |
| 0.60% | `python` | `dictiter_iternextitem` | dict |
| 0.58% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.57% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.55% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.53% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.53% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.51% | `python` | `setiter_iternext` | miscobj |
| 0.47% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.45% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.43% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.42% | `python` | `slot_tp_richcompare` | dynamic |
| 0.42% | `python` | `dict_dealloc` | memory |
| 0.41% | `python` | `dict_merge` | dict |
| 0.40% | `python` | `insert_to_emptydict` | dict |
| 0.40% | `python` | `PyObject_IsInstance` | dynamic |
| 0.39% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.37% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.36% | `python` | `PyObject_IsTrue` | dynamic |
| 0.35% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.35% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.34% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.33% | `python` | `_Py_NewReference` | memory |
| 0.33% | `python` | `PyDict_Next` | dict |
| 0.33% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `PyCMethod_New` | memory |
| 0.33% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.32% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.32% | `python` | `PyObject_Hash` | dynamic |
| 0.31% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.29% | `python` | `list_sort_impl` | list |
| 0.29% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.29% | `python` | `new_dict` | dict |
| 0.28% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.27% | `python` | `PyList_New.constprop.0` | memory |
| 0.27% | `python` | `_PyType_GetDict` | dynamic |

## telco

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.83% | `[JIT]` | `jit` | jit |
| 13.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.20% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.80% | `python` | `initialize_locals` | interpreter |
| 2.45% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.22% | `python` | `_PyObject_Malloc` | memory |
| 2.04% | `python` | `_PyObject_Free` | memory |
| 1.91% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.60% | `python` | `_Py_Dealloc` | memory |
| 1.55% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.11% | `python` | `long_to_decimal_string_internal` | int |
| 1.11% | `python` | `PyLong_FromString` | int |
| 1.07% | `python` | `_PyJIT_Entry` | compiler |
| 1.07% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.02% | `python` | `_PyEval_Vector` | interpreter |
| 0.98% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.97% | `python` | `clear_slots` | unknown |
| 0.95% | `python` | `subtype_dealloc` | memory |
| 0.80% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.72% | `python` | `_PyCompactLong_Add` | unknown |
| 0.69% | `python` | `_Py_dict_lookup` | lookup |
| 0.66% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.65% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.63% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.60% | `python` | `slot_nb_bool` | unknown |
| 0.60% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.60% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.58% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.57% | `python` | `PyObject_IsTrue` | dynamic |
| 0.56% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.51% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.51% | `python` | `PyNumber_Long` | dynamic |
| 0.49% | `python` | `tuple_alloc` | memory |
| 0.46% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.45% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.45% | `python` | `min_max` | unknown |
| 0.44% | `python` | `PyLong_FromSsize_t` | int |
| 0.41% | `python` | `tuple_dealloc` | memory |
| 0.41% | `python` | `sre_ucs1_match` | library |
| 0.41% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.38% | `python` | `tp_new_wrapper` | memory |
| 0.38% | `python` | `PyType_IsSubtype` | dynamic |
| 0.37% | `libc.so.6` | `_int_malloc` | libc |
| 0.37% | `python` | `PyObject_Size` | dynamic |
| 0.36% | `python` | `PyType_GenericAlloc` | memory |
| 0.36% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.35% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.34% | `python` | `object_isinstance` | dynamic |
| 0.33% | `python` | `PyObject_IsInstance` | dynamic |
| 0.33% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.33% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.32% | `python` | `PyObject_Str` | dynamic |
| 0.32% | `python` | `_PyUnicode_Equal` | str |
| 0.31% | `libc.so.6` | `malloc` | libc |
| 0.31% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.30% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.29% | `python` | `PyUnicode_New` | memory |
| 0.28% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.28% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.28% | `python` | `_Py_NewReference` | memory |
| 0.26% | `python` | `PyUnicode_Concat` | str |

## thrift

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.21% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.54% | `[JIT]` | `jit` | jit |
| 3.32% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.84% | `python` | `_PyObject_Malloc` | memory |
| 2.83% | `python` | `initialize_locals` | interpreter |
| 2.52% | `python` | `_Py_Dealloc` | memory |
| 2.39% | `python` | `_PyObject_Free` | memory |
| 2.18% | `apache::thrift::py::TType,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*,` | unknown |
| 1.87% | `python` | `_Py_dict_lookup` | lookup |
| 1.81% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.79% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.61% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.57% | `python` | `insert_to_emptydict` | dict |
| 1.44% | `python` | `PyDict_GetItemRef` | dict |
| 1.35% | `python` | `subtype_dealloc` | memory |
| 1.27% | `python` | `insertdict` | dict |
| 1.17% | `_object*)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType,` | unknown |
| 1.02% | `python` | `_PyType_AllocNoTrack` | memory |
| 1.02% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.00% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.93% | `python` | `PyLong_AsLong` | int |
| 0.90% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.86% | `python` | `PyTuple_Size` | tuple |
| 0.86% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.86% | `python` | `PyDict_Next` | dict |
| 0.82% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.78% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.76% | `_object*,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readStruct(_object*,` | unknown |
| 0.72% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `python` | `_PyEval_Vector` | interpreter |
| 0.70% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.70% | `python` | `vgetargs1_impl` | calls |
| 0.70% | `python` | `dict_dealloc` | memory |
| 0.68% | `python` | `tuple_dealloc` | memory |
| 0.65% | `python` | `PyDict_SetItem` | dict |
| 0.65% | `int)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readBytes(char**,` | unknown |
| 0.62% | `python` | `PyType_GenericAlloc` | memory |
| 0.61% | `python` | `PyDict_New` | memory |
| 0.59% | `python` | `_PyJIT_Entry` | compiler |
| 0.59% | `python` | `PyObject_GetAttr` | dynamic |
| 0.57% | `python` | `PyObject_Call` | dynamic |
| 0.56% | `python` | `PyUnicode_RichCompare` | str |
| 0.56% | `python` | `unicode_from_format` | str |
| 0.56% | `short&)` | `apache::thrift::py::BinaryProtocol::readFieldBegin(apache::thrift::py::TType&,` | unknown |
| 0.55% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.53% | `python` | `_PyDict_FromItems` | dict |
| 0.50% | `libc.so.6` | `malloc` | libc |
| 0.45% | `python` | `_PyDict_Next` | dict |
| 0.45% | `python` | `dict_merge` | dict |
| 0.44% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.43% | `python` | `_PyObject_Calloc` | memory |
| 0.43% | `python` | `tuple_alloc` | memory |
| 0.43% | `python` | `_PyObject_VectorcallDictTstate` | dynamic |
| 0.43% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.42% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.40% | `python` | `_Py_NewReference` | memory |
| 0.40% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.39% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.39% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.38% | `python` | `new_dict` | dict |
| 0.37% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.37% | `python` | `convertitem.constprop.0` | unknown |
| 0.36% | `python` | `find_first_nonascii` | str |
| 0.35% | `_object*)` | `apache::thrift::py::parse_struct_item_spec(apache::thrift::py::StructItemSpec*,` | unknown |
| 0.35% | `python` | `_PyType_GetDict` | dynamic |
| 0.33% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.33% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.32% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.32% | `python` | `PyList_New` | memory |
| 0.31% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.31% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.31% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.31% | `python` | `_PyObject_Realloc` | memory |
| 0.28% | `python` | `list_dealloc` | memory |
| 0.27% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.27% | `python` | `PyImport_ImportModuleLevelObject` | import |
| 0.27% | `python` | `PyTuple_New` | memory |
| 0.26% | `python` | `PyObject_IsTrue` | dynamic |
| 0.26% | `python` | `PyObject_GC_Del` | gc |
| 0.26% | `python` | `type_call` | dynamic |
| 0.25% | `python` | `object_new` | memory |

## tomli_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 34.53% | `[JIT]` | `jit` | jit |
| 6.52% | `python` | `set_lookkey` | miscobj |
| 4.71% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.50% | `python` | `_PyCompactLong_Add` | unknown |
| 3.32% | `python` | `_PyUnicode_Equal` | str |
| 3.25% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.25% | `python` | `_PySet_Contains` | miscobj |
| 1.79% | `python` | `_Py_dict_lookup` | lookup |
| 1.77% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.71% | `python` | `_PyObject_Malloc` | memory |
| 1.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.32% | `python` | `_PyDict_Subscript` | dict |
| 1.26% | `python` | `_PyIncrementalNewlineDecoder_decode` | memory |
| 1.17% | `python` | `_Py_Dealloc` | memory |
| 1.10% | `python` | `_PyObject_Free` | memory |
| 0.94% | `python` | `PyObject_GetItem` | dynamic |
| 0.85% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.81% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.79% | `python` | `_PyUnicode_FromUCS4.part.0` | str |
| 0.76% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.72% | `python` | `sre_ucs4_match` | library |
| 0.71% | `python` | `_Py_NewReference` | memory |
| 0.70% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.68% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.67% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.61% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.56% | `python` | `tuple_alloc` | memory |
| 0.52% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.44% | `python` | `PyDict_Contains` | dict |
| 0.44% | `python` | `replace` | str |
| 0.43% | `python` | `initialize_locals` | interpreter |
| 0.42% | `python` | `tuple_dealloc` | memory |
| 0.38% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.36% | `python` | `make_range_object` | unknown |
| 0.35% | `python` | `unicode_decode_utf8_impl` | str |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `python` | `func_clear` | unknown |
| 0.34% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.33% | `python` | `PyType_IsSubtype` | dynamic |
| 0.32% | `python` | `memcmp@plt` | unknown |
| 0.32% | `python` | `PyDict_GetItemRef` | dict |
| 0.31% | `python` | `siphash13` | str |
| 0.30% | `python` | `_PyJIT_Entry` | compiler |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.26% | `python` | `PyFunction_NewWithQualName` | memory |

## tornado_http

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.07% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.27% | `[JIT]` | `jit` | jit |
| 2.02% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.82% | `python` | `_PyObject_Malloc` | memory |
| 1.58% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.57% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.29% | `python` | `_PyObject_Free` | memory |
| 1.21% | `python` | `initialize_locals` | interpreter |
| 1.14% | `python` | `_Py_Dealloc` | memory |
| 1.07% | `python` | `sre_ucs1_match` | library |
| 0.80% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.74% | `python` | `_Py_dict_lookup` | lookup |
| 0.74% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.68% | `python` | `tuple_dealloc` | memory |
| 0.68% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.67% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.65% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.61% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.60% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.57% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.56% | `[nf_tables]` | `nft_do_chain` | unknown |
| 0.52% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.48% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.45% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.42% | `libc.so.6` | `malloc` | libc |
| 0.40% | `python` | `tuple_alloc` | memory |
| 0.40% | `python` | `PyType_IsSubtype` | dynamic |
| 0.40% | `python` | `_PyEval_Vector` | interpreter |
| 0.38% | `libc.so.6` | `_int_malloc` | libc |
| 0.37% | `python` | `_PyJIT_Entry` | compiler |
| 0.37% | `python` | `sre_ucs1_count` | library |
| 0.34% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.33% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.31% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.31% | `python` | `subtype_dealloc` | memory |
| 0.26% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.25% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.25% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.25% | `python` | `PyObject_ClearManagedDict` | dynamic |

## typing_runtime_protocols

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.46% | `[JIT]` | `jit` | jit |
| 7.02% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.79% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.40% | `python` | `_PyObject_Malloc` | memory |
| 2.65% | `python` | `_Py_Dealloc` | memory |
| 2.44% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 2.41% | `python` | `_Py_dict_lookup` | lookup |
| 2.32% | `python` | `_PyObject_Free` | memory |
| 2.27% | `python` | `weakref___new__` | memory |
| 2.23% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.19% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 2.06% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.57% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.55% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.54% | `python` | `tuple_dealloc` | memory |
| 1.46% | `python` | `set_lookkey` | miscobj |
| 1.38% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.37% | `python` | `tuple_alloc` | memory |
| 1.33% | `python` | `PyArg_UnpackTuple` | calls |
| 1.19% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.94% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.85% | `python` | `frame_dealloc` | memory |
| 0.81% | `python` | `initialize_locals` | interpreter |
| 0.77% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.76% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.76% | `python` | `getset_get` | dynamic |
| 0.74% | `python` | `_Py_type_getattro_impl` | dynamic |
| 0.74% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.73% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.72% | `python` | `_PyObject_GC_New` | gc |
| 0.60% | `python` | `PyWeakref_NewRef` | memory |
| 0.59% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.59% | `python` | `PyType_IsSubtype` | dynamic |
| 0.57% | `python` | `PyMapping_Check` | dynamic |
| 0.56% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.56% | `python` | `setiter_iternext` | miscobj |
| 0.54% | `python` | `PyObject_Hash` | dynamic |
| 0.52% | `python` | `_Py_NewReference` | memory |
| 0.52% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.50% | `python` | `type_call` | dynamic |
| 0.47% | `python` | `PyObject_GC_Del` | gc |
| 0.46% | `python` | `wrap_descr_get` | unknown |
| 0.45% | `python` | `weakref_richcompare` | miscobj |
| 0.42% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.42% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.41% | `python` | `PyList_New.constprop.0` | memory |
| 0.40% | `python` | `_PyEval_Vector` | interpreter |
| 0.40% | `python` | `dict_dealloc` | memory |
| 0.39% | `python` | `object_richcompare` | dynamic |
| 0.38% | `python` | `PyDictProxy_New` | memory |
| 0.37% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.37% | `python` | `PySequence_Contains` | dynamic |
| 0.37% | `python` | `weakref_hash` | miscobj |
| 0.37% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.36% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.36% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.35% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.35% | `python` | `PyTraceBack_Here` | exceptions |
| 0.35% | `python` | `tuple_hash` | tuple |
| 0.34% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.34% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.34% | `python` | `PyDict_Contains` | dict |
| 0.34% | `python` | `_Py_type_getattro` | lookup |
| 0.33% | `python` | `wrapper_call` | unknown |
| 0.32% | `python` | `builtin_getattr` | lookup |
| 0.31% | `python` | `_PyObject_GC_Link` | gc |
| 0.31% | `python` | `lru_cache_make_key` | unknown |
| 0.31% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.31% | `python` | `AttributeError_dealloc` | memory |
| 0.29% | `python` | `infinite_lru_cache_wrapper` | unknown |
| 0.28% | `python` | `weakref___init__` | miscobj |
| 0.28% | `python` | `PyObject_IsSubclass` | dynamic |
| 0.27% | `python` | `mappingproxy_dealloc` | memory |
| 0.26% | `python` | `_PyObject_Realloc` | memory |
| 0.26% | `python` | `wrapperdescr_call` | unknown |
| 0.25% | `python` | `tuple_richcompare` | tuple |

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
| 42.44% | `[JIT]` | `jit` | jit |
| 3.54% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.16% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `python` | `_Py_dict_lookup` | lookup |
| 2.76% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 2.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.66% | `python` | `PyObject_IsTrue` | dynamic |
| 2.52% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 1.73% | `python` | `_Py_convert_optional_to_ssize_t` | unknown |
| 1.67% | `python` | `_PyDict_Subscript` | dict |
| 1.64% | `python` | `PyObject_GetItem` | dynamic |
| 1.60% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.60% | `python` | `_io_BytesIO_read` | unknown |
| 1.48% | `python` | `_PyObject_Free` | memory |
| 1.16% | `python` | `insertdict` | dict |
| 1.07% | `python` | `bytes_subscript` | str |
| 1.02% | `python` | `PyLong_AsSsize_t` | int |
| 1.00% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.97% | `python` | `PyUnicode_Decode` | str |
| 0.92% | `python` | `_Py_Dealloc` | memory |
| 0.84% | `python` | `PyLong_FromSsize_t` | int |
| 0.82% | `python` | `PyObject_IsInstance` | dynamic |
| 0.81% | `python` | `find_first_nonascii` | str |
| 0.75% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.73% | `python` | `unicode_vectorcall` | str |
| 0.70% | `python` | `list_append` | list |
| 0.63% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.60% | `python` | `PyObject_Size` | dynamic |
| 0.59% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.56% | `python` | `list_subscript` | list |
| 0.54% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.50% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.50% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.41% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.41% | `python` | `PyUnicode_New.part.0` | memory |
| 0.41% | `python` | `siphash13` | str |
| 0.40% | `python` | `PyObject_Hash` | dynamic |
| 0.38% | `python` | `long_hash` | int |
| 0.36% | `python` | `bytes_length` | str |
| 0.35% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.32% | `python` | `_PyObject_Realloc` | memory |
| 0.31% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.30% | `python` | `PyObject_SetItem` | dynamic |
| 0.28% | `python` | `initialize_locals` | interpreter |
| 0.28% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.27% | `python` | `find_empty_slot.constprop.0` | dict |
| 0.25% | `python` | `_PyEvalFramePushAndInit` | interpreter |

## xdsl

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.98% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 10.08% | `[JIT]` | `jit` | jit |
| 4.14% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 3.26% | `python` | `_PyObject_Malloc` | memory |
| 2.49% | `python` | `gc_collect_main` | gc |
| 2.07% | `python` | `_Py_Dealloc` | memory |
| 1.98% | `python` | `_PyObject_Free` | memory |
| 1.82% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.81% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.33% | `python` | `_Py_dict_lookup` | lookup |
| 1.17% | `python` | `initialize_locals` | interpreter |
| 1.04% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.04% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 1.03% | `python` | `tuple_dealloc` | memory |
| 0.99% | `python` | `PyObject_SetAttr` | dynamic |
| 0.99% | `python` | `PyDict_GetItemRef` | dict |
| 0.95% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.93% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.87% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.82% | `python` | `visit_decref` | gc |
| 0.77% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.72% | `python` | `tuple_alloc` | memory |
| 0.68% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.68% | `python` | `_PyJIT_Entry` | compiler |
| 0.63% | `python` | `unicode_from_format` | str |
| 0.61% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.58% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.57% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.57% | `python` | `set_lookkey` | miscobj |
| 0.54% | `python` | `_PyEval_Vector` | interpreter |
| 0.52% | `python` | `visit_reachable` | gc |
| 0.51% | `python` | `subtype_traverse` | gc |
| 0.50% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.49% | `python` | `PyType_IsSubtype` | dynamic |
| 0.46% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.43% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.42% | `python` | `PyType_GenericAlloc` | memory |
| 0.40% | `python` | `dict_traverse` | gc |
| 0.39% | `python` | `subtype_dealloc` | memory |
| 0.38% | `python` | `_PyUnicode_InternMortal` | str |
| 0.36% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.36% | `python` | `_Py_NewReference` | memory |
| 0.33% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.32% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.31% | `python` | `PyObject_GC_Del` | gc |
| 0.31% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.31% | `python` | `PyObject_GetIter` | dynamic |
| 0.31% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.30% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.30% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.29% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.29% | `python` | `tuple_iter` | tuple |
| 0.28% | `python` | `zip_next` | unknown |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `_PyObject_GC_Link` | gc |
| 0.27% | `python` | `_PyUnicodeWriter_WriteASCIIString` | str |
| 0.26% | `python` | `_Py_type_getattro` | lookup |
| 0.25% | `python` | `PyWeakref_NewRef` | memory |
| 0.25% | `python` | `_PyUnicode_ResizeCompact` | str |

## xml_etree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 9.14% | `[JIT]` | `jit` | jit |
| 6.66% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.50% | `python` | `_PyObject_Malloc` | memory |
| 3.04% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_updatePosition` | library |
| 3.00% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_contentTok` | library |
| 2.91% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 2.71% | `python` | `_PyObject_Free` | memory |
| 2.62% | `python` | `gc_collect_main` | gc |
| 2.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.09% | `python` | `_Py_Dealloc` | memory |
| 1.87% | `python` | `visit_decref` | gc |
| 1.79% | `python` | `visit_reachable` | gc |
| 1.72% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `accountingDiffTolerated.part.0` | library |
| 1.69% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `sip24_update.isra.0` | library |
| 1.64% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `doContent` | library |
| 1.34% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_nameLength` | library |
| 1.33% | `python` | `_Py_dict_lookup` | lookup |
| 1.06% | `python` | `find_first_nonascii` | str |
| 1.06% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `lookup.constprop.0` | library |
| 1.05% | `python` | `_io_TextIOWrapper_write` | unknown |
| 0.94% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.88% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `treebuilder_handle_start` | library |
| 0.84% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_getAtts` | library |
| 0.84% | `python` | `PyUnicode_Contains` | str |
| 0.82% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_end_handler` | library |
| 0.82% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.80% | `python` | `initialize_locals` | interpreter |
| 0.76% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_gc_traverse` | library |
| 0.74% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.73% | `python` | `getset_get` | dynamic |
| 0.72% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `sip24_final` | library |
| 0.71% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `elementiter_next` | library |
| 0.69% | `python` | `siphash13` | str |
| 0.68% | `python` | `tuple_dealloc` | memory |
| 0.67% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.66% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.65% | `python` | `PyUnicode_New.part.0` | memory |
| 0.65% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.59% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.59% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `storeAtts` | library |
| 0.59% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.53% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.51% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.50% | `python` | `_PyEval_Vector` | interpreter |
| 0.49% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_dealloc` | library |
| 0.46% | `python` | `_PyObject_GC_New` | gc |
| 0.46% | `python` | `list_dealloc` | memory |
| 0.45% | `python` | `_PyJIT_Entry` | compiler |
| 0.45% | `python` | `PyType_IsSubtype` | dynamic |
| 0.43% | `python` | `_Py_NewReference` | memory |
| 0.43% | `python` | `_PyType_GetDict` | dynamic |
| 0.42% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.41% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `makeuniversal` | library |
| 0.40% | `python` | `PyUnicode_Concat` | str |
| 0.40% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_start_handler` | library |
| 0.38% | `python` | `long_to_decimal_string_internal` | int |
| 0.38% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.38% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.38% | `python` | `object_isinstance` | dynamic |
| 0.37% | `python` | `dict_dealloc` | memory |
| 0.36% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.36% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.35% | `python` | `_PyTuple_FromPair` | tuple |
| 0.35% | `python` | `unicode_dealloc` | memory |
| 0.35% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `utf8_toUtf8` | library |
| 0.34% | `python` | `PyList_Append` | list |
| 0.33% | `python` | `slot_tp_iternext` | unknown |
| 0.33% | `python` | `PyUnicode_Format` | str |
| 0.31% | `python` | `vgetargs1_impl` | calls |
| 0.30% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `treebuilder_extend_element_text_or_tail.isra.0` | library |
| 0.30% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_getitem` | library |
| 0.30% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `create_new_element.isra.0` | library |
| 0.30% | `python` | `_PyObject_GC_Link` | gc |
| 0.30% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.29% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.29% | `python` | `PyDict_GetItemWithError` | dict |
| 0.29% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_data_handler` | library |
| 0.29% | `python` | `PyList_New` | memory |
| 0.29% | `python` | `PyObject_GC_Del` | gc |
| 0.27% | `python` | `PySequence_Contains` | dynamic |
| 0.27% | `python` | `PyObject_IsTrue` | dynamic |
| 0.26% | `python` | `stringlib__two_way` | str |
| 0.26% | `python` | `_textiowrapper_writeflush` | unknown |
| 0.26% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.26% | `python` | `PyDescr_IsData` | dynamic |
| 0.26% | `python` | `gen_iternext` | miscobj |
| 0.26% | `python` | `bytes_richcompare` | str |
| 0.25% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.25% | `python` | `_PyObject_Realloc` | memory |


## Categories

### jit

17.89% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 17.89% | [JIT] | jit |

### memory

11.88% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.17% | python | _PyObject_Malloc |
| 1.83% | python | _Py_Dealloc |
| 1.71% | python | _PyObject_Free |
| 0.78% | python | tuple_dealloc |
| 0.69% | python | list_dealloc |
| 0.52% | python | tuple_alloc |
| 0.40% | python | _Py_NewReference |
| 0.25% | python | PyList_New.constprop.0 |
| 0.22% | python | _PyObject_Realloc |
| 0.22% | python | _PyType_AllocNoTrack |
| 0.16% | python | PyTuple_New |
| 0.14% | python | PyType_GenericAlloc |
| 0.13% | python | dict_dealloc |
| 0.13% | python | subtype_dealloc |
| 0.12% | python | gen_dealloc |
| 0.12% | python | PyUnicode_New.part.0 |
| 0.10% | python | PyCMethod_New |
| 0.10% | python | unicode_dealloc |
| 0.09% | python | listiter_dealloc |
| 0.09% | python | zip_new |
| 0.08% | python | long_dealloc |
| 0.08% | python | PyList_New |
| 0.07% | python | PyMethod_New |
| 0.07% | python | _PyLong_ExactDealloc |
| 0.07% | python | _PyObject_Calloc |
| 0.07% | python | PyUnicode_New |
| 0.07% | python | PyDict_New |
| 0.07% | python | _PyIncrementalNewlineDecoder_decode |
| 0.07% | python | PyFunction_NewWithQualName |
| 0.06% | python | PySlice_New |
| 0.06% | python | meth_dealloc |
| 0.06% | python | set_dealloc |
| 0.06% | python | method_dealloc |
| 0.05% | python | float_dealloc |
| 0.05% | python | _PyFloat_ExactDealloc |
| 0.05% | python | pattern_new_match |
| 0.05% | python | long_alloc |
| 0.05% | python | PyObject_CallFinalizerFromDealloc |
| 0.04% | python | PyMem_Free |
| 0.04% | python | func_dealloc |
| 0.04% | python | memcpy@plt |
| 0.04% | python | zip_dealloc |
| 0.04% | python | PyMem_Calloc |
| 0.04% | python | context_tp_dealloc |
| 0.03% | python | allocate_from_new_pool |
| 0.03% | python | memset@plt |
| 0.03% | python | slice_dealloc |
| 0.02% | python | object_new |
| 0.02% | python | tp_new_wrapper |
| 0.02% | python | frame_dealloc |
| 0.02% | python | PyMem_Realloc |
| 0.02% | python | PyMem_Malloc |
| 0.02% | python | cell_dealloc |
| 0.01% | python | object_dealloc |
| 0.01% | python | PyCell_New |
| 0.01% | python | _PyAsyncGenValueWrapperNew |
| 0.01% | python | StopIteration_dealloc |
| 0.01% | python | dictiter_dealloc |
| 0.01% | python | async_gen_asend_dealloc |
| 0.01% | python | async_gen_wrapped_val_dealloc |
| 0.01% | python | range_dealloc |
| 0.01% | python | dictview_dealloc |
| 0.01% | python | weakref___new__ |
| 0.01% | python | BaseException_new |
| 0.01% | python | BaseException_dealloc |
| 0.01% | python | match_dealloc |
| 0.01% | python | AttributeError_dealloc |
| 0.01% | python | tb_dealloc |
| 0.01% | python | _PyUnicode_ExactDealloc |
| 0.01% | python | _PyMem_RawMalloc |
| 0.01% | python | tupleiter_dealloc |
| 0.01% | python | slot_tp_new |
| 0.01% | python | PyWeakref_NewRef |
| 0.00% | python | unicode_new |
| 0.00% | python | PyFunction_New |
| 0.00% | python | code_dealloc |
| 0.00% | python | _PyMem_RawFree |
| 0.00% | python | rangeiter_dealloc |
| 0.00% | python | structseq_dealloc |
| 0.00% | python | PyObject_Realloc |
| 0.00% | python | _Py_NewReferenceNoTotal |
| 0.00% | python | setiter_dealloc |
| 0.00% | python | future_new_iter |
| 0.00% | python | reversed_new_impl |
| 0.00% | python | TaskObj_dealloc |
| 0.00% | python | type_new |

### interpreter

10.76% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 6.74% | python | _PyEval_EvalFrameDefault |
| 1.44% | python | _PyFrame_ClearExceptCode |
| 0.72% | python | initialize_locals |
| 0.65% | python | _PyEval_FrameClearAndPop |
| 0.48% | python | _PyEvalFramePushAndInit |
| 0.28% | python | _PyEval_Vector |
| 0.10% | python | _PyEval_SliceIndex |
| 0.04% | python | call_instrumentation_vector.part.0.isra.0 |
| 0.04% | python | _PyFrame_Traverse |
| 0.03% | python | _PyStack_UnpackDict |
| 0.03% | python | _Py_call_instrumentation_line |
| 0.02% | python | _PyCode_Quicken |
| 0.02% | python | _PyEval_UnpackIndices |
| 0.02% | python | _PyCode_CheckLineNumber |
| 0.02% | python | _PyEval_GetIter |
| 0.01% | python | _PyEvalFramePushAndInit_Ex |
| 0.01% | python | _PyEval_SliceIndexNotNone |
| 0.01% | python | _PyEval_GetAwaitable |
| 0.01% | python | _PyPegen_is_memoized |
| 0.01% | python | _PyFrame_New_NoTrack |
| 0.01% | python | _PyEval_MonitorRaise |
| 0.01% | python | _PyFrame_MakeAndSetFrameObject |
| 0.01% | python | PyEval_SaveThread |
| 0.01% | python | _PyCode_New |
| 0.01% | python | _PyEval_GetANext |
| 0.01% | python | _PyCode_GetCode |
| 0.00% | python | _PyPegen_expect_token |
| 0.00% | python | _PyEval_EnsureBuiltins |
| 0.00% | python | PyEval_GetFrame |
| 0.00% | python | _PyEval_ImportName |
| 0.00% | python | _PyPegen_update_memo |
| 0.00% | python | _PyEval_LoadGlobalStackRef |
| 0.00% | python | PyEval_EvalCode |
| 0.00% | python | _PyEval_CheckExceptTypeValid |

### library

8.54% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.56% | python | sre_ucs1_match |
| 0.45% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_ascii85 |
| 0.40% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base85 |
| 0.38% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base64 |
| 0.34% | python | sre_ucs1_charset.isra.0 |
| 0.32% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base32 |
| 0.26% | _pickle.cpython-315-x86_64-linux-gnu.so | save.constprop.0 |
| 0.25% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base32 |
| 0.25% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base64 |
| 0.21% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_hex_impl.isra.0 |
| 0.19% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_ascii85 |
| 0.13% | _json.cpython-316-x86_64-linux-gnu.so | scanstring_unicode |
| 0.12% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base85 |
| 0.12% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write |
| 0.11% | python | sre_search |
| 0.11% | array.cpython-316-x86_64-linux-gnu.so | array_subscr |
| 0.11% | _pickle.cpython-315-x86_64-linux-gnu.so | save_dict |
| 0.11% | _pickle.cpython-315-x86_64-linux-gnu.so | save_long |
| 0.10% | _pickle.cpython-315-x86_64-linux-gnu.so | load |
| 0.10% | python | sre_ucs1_count |
| 0.07% | _pickle.cpython-315-x86_64-linux-gnu.so | save_list |
| 0.06% | _pickle.cpython-315-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.06% | _json.cpython-316-x86_64-linux-gnu.so | scan_once_unicode |
| 0.06% | python | _sre_SRE_Pattern_prefixmatch |
| 0.06% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write.constprop.0 |
| 0.06% | libz.so.1.3 | 0x0000000000008c1c |
| 0.05% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_updatePosition |
| 0.05% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_contentTok |
| 0.04% | libz.so.1.3 | 0x0000000000008c20 |
| 0.04% | libz.so.1.3 | 0x0000000000002dba |
| 0.04% | array.cpython-316-x86_64-linux-gnu.so | array_ass_subscr |
| 0.04% | libz.so.1.3 | 0x0000000000002da3 |
| 0.04% | libz.so.1.3 | 0x0000000000008bf7 |
| 0.04% | libz.so.1.3 | 0x0000000000002db1 |
| 0.04% | libz.so.1.3 | 0x0000000000002dc6 |
| 0.04% | libz.so.1.3 | 0x0000000000002db6 |
| 0.04% | libz.so.1.3 | 0x0000000000002dae |
| 0.04% | _math_integer.cpython-316-x86_64-linux-gnu.so | factorial_partial_product |
| 0.04% | python | sre_ucs4_match |
| 0.03% | tracer.cpython-316-x86_64-linux-gnu.so | CTracer_trace |
| 0.03% | python | pattern_subx |
| 0.03% | array.cpython-316-x86_64-linux-gnu.so | d_setitem |
| 0.03% | libz.so.1.3 | 0x0000000000008192 |
| 0.03% | libz.so.1.3 | 0x0000000000008be6 |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | accountingDiffTolerated.part.0 |
| 0.03% | libsqlite3.so.0.8.6 | sqlite3VdbeExec |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | sip24_update.isra.0 |
| 0.03% | libm.so.6 | __ieee754_pow_fma |
| 0.03% | libz.so.1.3 | 0x0000000000008c25 |
| 0.03% | _heapq.cpython-316-x86_64-linux-gnu.so | siftup |
| 0.03% | libz.so.1.3 | 0x00000000000082aa |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | doContent |
| 0.03% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_put |
| 0.02% | array.cpython-316-x86_64-linux-gnu.so | d_getitem |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | save_unicode |
| 0.02% | libz.so.1.3 | 0x0000000000008c2c |
| 0.02% | libz.so.1.3 | 0x0000000000008bed |
| 0.02% | libz.so.1.3 | 0x0000000000008bd6 |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | Pickler_clear |
| 0.02% | libz.so.1.3 | 0x0000000000008c07 |
| 0.02% | libz.so.1.3 | 0x00000000000082b7 |
| 0.02% | _pickle.cpython-316-x86_64-linux-gnu.so | save.constprop.0 |
| 0.02% | _json.cpython-316-x86_64-linux-gnu.so | encoder_listencode_obj |
| 0.02% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_nameLength |
| 0.02% | libz.so.1.3 | 0x000000000000819f |
| 0.02% | libm.so.6 | __cos_fma |
| 0.02% | libz.so.1.3 | 0x0000000000008c18 |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | load_counted_binunicode |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | Pdata_push |
| 0.02% | libz.so.1.3 | 0x0000000000008c2f |
| 0.02% | pyexpat.cpython-316-x86_64-linux-gnu.so | lookup.constprop.0 |
| 0.02% | libz.so.1.3 | 0x0000000000008bdf |
| 0.02% | libz.so.1.3 | 0x0000000000008bf1 |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | do_append |
| 0.02% | libz.so.1.3 | 0x0000000000008c0a |
| 0.02% | libz.so.1.3 | 0x0000000000008bfa |
| 0.02% | python | _sre_SRE_Pattern_search |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoPut |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | ascii_escape_size |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | treebuilder_handle_start |
| 0.01% | libz.so.1.3 | 0x0000000000008c01 |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_getAtts |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_end_handler |
| 0.01% | python | sre_ucs2_match |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_gc_traverse |
| 0.01% | libz.so.1.3 | 0x0000000000008bd0 |
| 0.01% | libz.so.1.3 | 0x0000000000008c14 |
| 0.01% | libz.so.1.3 | 0x0000000000008c2a |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyIndex_Check@plt |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | sip24_final |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | elementiter_next |
| 0.01% | libz.so.1.3 | 0x0000000000008c0e |
| 0.01% | libz.so.1.3 | 0x0000000000008140 |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | save_dict |
| 0.01% | libz.so.1.3 | 0x0000000000008279 |
| 0.01% | libz.so.1.3 | 0x000000000000828a |
| 0.01% | libz.so.1.3 | 0x000000000000814f |
| 0.01% | libz.so.1.3 | 0x0000000000008267 |
| 0.01% | libz.so.1.3 | 0x0000000000008182 |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | do_setitems |
| 0.01% | libz.so.1.3 | 0x0000000000008258 |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyNumber_AsSsize_t@plt |
| 0.01% | libz.so.1.3 | 0x0000000000008172 |
| 0.01% | libz.so.1.3 | 0x0000000000008161 |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyType_GetModuleByDef@plt |
| 0.01% | libm.so.6 | __sin_fma |
| 0.01% | libz.so.1.3 | 0x000000000000829a |
| 0.01% | _sqlite3.cpython-316-x86_64-linux-gnu.so | _pysqlite_query_execute |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | write_escaped_ascii |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | storeAtts |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_get |
| 0.01% | binascii.cpython-316-x86_64-linux-gnu.so | ascii_buffer_converter |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_dealloc |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | Unpickler_clear |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | encoder_encode_key_value |
| 0.01% | ld-linux-x86-64.so.2 | _dl_relocate_object |
| 0.01% | _math_integer.cpython-316-x86_64-linux-gnu.so | math_integer_factorial |
| 0.01% | _heapq.cpython-316-x86_64-linux-gnu.so | siftdown |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_AsLongAndOverflow@plt |
| 0.01% | python | sre_ucs4_count |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | makeuniversal |
| 0.01% | libz.so.1.3 | inflate |
| 0.01% | libz.so.1.3 | 0x000000000000242e |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_start_handler |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyFloat_FromDouble@plt |
| 0.01% | libz.so.1.3 | 0x0000000000002419 |
| 0.01% | libz.so.1.3 | 0x0000000000002416 |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | Pickler_clear |
| 0.01% | libz.so.1.3 | 0x00000000000023f4 |
| 0.01% | _math_integer.cpython-316-x86_64-linux-gnu.so | math_integer_gcd |
| 0.01% | libz.so.1.3 | 0x00000000000082ae |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | utf8_toUtf8 |
| 0.01% | _random.cpython-316-x86_64-linux-gnu.so | genrand_uint32 |
| 0.01% | libssl.so.3 | 0x0000000000055398 |
| 0.01% | libz.so.1.3 | 0x0000000000008196 |
| 0.00% | libz.so.1.3 | 0x0000000000008c28 |
| 0.00% | libz.so.1.3 | 0x0000000000008c37 |
| 0.00% | _random.cpython-316-x86_64-linux-gnu.so | _random_Random_getrandbits |
| 0.00% | math.cpython-316-x86_64-linux-gnu.so | math_sqrt |
| 0.00% | _sqlite3.cpython-316-x86_64-linux-gnu.so | _pysqlite_fetch_one_row.constprop.0 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | PyDict_Next@plt |
| 0.00% | libz.so.1.3 | 0x0000000000008bfe |
| 0.00% | libz.so.1.3 | 0x0000000000008be3 |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | treebuilder_extend_element_text_or_tail.isra.0 |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_getitem |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | create_new_element.isra.0 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | marker |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_data_handler |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | _Pickler_Write |
| 0.00% | ld-linux-x86-64.so.2 | do_lookup_x |
| 0.00% | tracer.cpython-316-x86_64-linux-gnu.so | CTracer_set_pdata_stack.constprop.0 |
| 0.00% | libz.so.1.3 | 0x0000000000002403 |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3BtreeInsert |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyObject_IsTrue@plt |
| 0.00% | libz.so.1.3 | 0x000000000000827d |
| 0.00% | libz.so.1.3 | 0x0000000000008144 |
| 0.00% | libz.so.1.3 | 0x00000000000082bb |
| 0.00% | python | _sre_SRE_Pattern_sub |
| 0.00% | libz.so.1.3 | 0x000000000000829e |
| 0.00% | libz.so.1.3 | 0x000000000000828e |
| 0.00% | libz.so.1.3 | 0x0000000000008165 |
| 0.00% | python | _sre_SRE_Match_end |
| 0.00% | libz.so.1.3 | 0x0000000000008154 |
| 0.00% | libz.so.1.3 | 0x0000000000008186 |
| 0.00% | libz.so.1.3 | 0x000000000000825c |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3_step |
| 0.00% | libz.so.1.3 | 0x000000000000826c |
| 0.00% | libz.so.1.3 | 0x00000000000081a3 |
| 0.00% | _ssl.cpython-315-x86_64-linux-gnu.so | _ssl__SSLSocket_read |
| 0.00% | libz.so.1.3 | 0x0000000000008176 |
| 0.00% | unicodedata.cpython-316-x86_64-linux-gnu.so | unicodedata_UCD_combining |
| 0.00% | python | sys_trace_return |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_resize |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyObject_GetBuffer@plt |
| 0.00% | python | sys_trace_start |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | Pickler_traverse |
| 0.00% | _heapq.cpython-316-x86_64-linux-gnu.so | _heapq_heappop |
| 0.00% | array.cpython-316-x86_64-linux-gnu.so | i_getitem |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_FromLong@plt |
| 0.00% | libz.so.1.3 | 0x00000000000023f0 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoGet |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3VdbeHalt |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | memo_get |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyBuffer_Release@plt |
| 0.00% | _struct.cpython-316-x86_64-linux-gnu.so | pack |
| 0.00% | ld-linux-x86-64.so.2 | strcmp |
| 0.00% | _struct.cpython-316-x86_64-linux-gnu.so | s_pack_internal |
| 0.00% | _math_integer.cpython-316-x86_64-linux-gnu.so | _Py_Dealloc@plt |
| 0.00% | _json.cpython-316-x86_64-linux-gnu.so | encoder_write_string |
| 0.00% | libm.so.6 | pow@@GLIBC_2.29 |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | _Pickler_Write.constprop.0 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_New |
| 0.00% | math.cpython-316-x86_64-linux-gnu.so | math_cos |

### gc

8.05% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.81% | python | gc_collect_main |
| 1.42% | python | visit_decref |
| 1.37% | python | visit_reachable |
| 0.58% | python | PyObject_GC_UnTrack |
| 0.32% | python | list_traverse |
| 0.23% | python | dict_traverse |
| 0.22% | python | subtype_traverse |
| 0.17% | python | _PyObject_GC_New |
| 0.15% | python | PyObject_GC_Del |
| 0.11% | python | _PyObject_GC_Link |
| 0.11% | python | _PyObject_GC_NewVar |
| 0.06% | python | _PyGC_VisitFrameStack |
| 0.06% | python | tuple_traverse |
| 0.05% | python | TaskObj_traverse |
| 0.04% | python | PyObject_IS_GC |
| 0.04% | python | func_traverse |
| 0.04% | python | _PyTuple_MaybeUntrack |
| 0.03% | python | gen_traverse |
| 0.03% | python | set_traverse |
| 0.03% | python | type_is_gc |
| 0.02% | python | context_tp_traverse |
| 0.02% | python | type_traverse |
| 0.02% | python | PyObject_GC_Track |
| 0.01% | python | meth_traverse |
| 0.01% | python | FutureObj_traverse |
| 0.01% | python | TaskStepMethWrapper_traverse |
| 0.01% | python | _PyGC_VisitStackRef |
| 0.01% | python | method_traverse |
| 0.01% | python | FutureIter_traverse |
| 0.00% | python | gc_traverse |
| 0.00% | python | cell_traverse |
| 0.00% | python | descr_traverse |

### unknown

8.00% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.22% | python | _PyType_LookupStackRefAndVersion |
| 0.90% | [unknown] | 0xffffffff939cb32a |
| 0.50% | python | _PyCompactLong_Add |
| 0.36% | python | _Py_VectorCall_StackRefSteal |
| 0.28% | python | _Py_BuiltinCallFast_StackRef |
| 0.20% | [unknown] | 0xffffffff939cac57 |
| 0.19% | python | zip_next |
| 0.18% | python | _PyCompactLong_Subtract |
| 0.11% | python | lookup_method_ex.constprop.0 |
| 0.10% | python | _PyCallMethodDescriptorFast_StackRef |
| 0.09% | python | _PyRunRemoteDebugger |
| 0.09% | python | slot_mp_ass_subscript |
| 0.08% | python | _Py_bytes_upper |
| 0.08% | python | convertitem.constprop.0 |
| 0.08% | python | wrapperdescr_call |
| 0.08% | python | clear_slots |
| 0.07% | python | func_clear |
| 0.06% | python | make_range_object |
| 0.06% | python | _PyCompactLong_Multiply |
| 0.06% | python | _PyMember_GetOffset |
| 0.06% | python | _PyForIter_VirtualIteratorNext |
| 0.05% | python | _Py_type_getattro_stackref |
| 0.05% | python | PyBytesWriter_Create |
| 0.05% | python | _Py_IsMainThread |
| 0.05% | python | builtin_sum |
| 0.04% | python | _Py_BuildMap_StackRefSteal |
| 0.04% | python | wrap_objobjargproc |
| 0.04% | python | _Py_CallBuiltinClass_StackRef |
| 0.04% | python | _Py_BuiltinCallFastWithKeywords_StackRef |
| 0.04% | python | _PyCallMethodDescriptorFastWithKeywords_StackRef |
| 0.04% | python | _Py_VectorCallInstrumentation_StackRefSteal |
| 0.04% | python | PyIndex_Check |
| 0.03% | python | min_max |
| 0.03% | python | _PyStolenTuple_Free |
| 0.03% | python | memcmp@plt |
| 0.03% | python | sys_audit_tstate |
| 0.03% | python | build_indices_generic |
| 0.03% | python | _PyAsyncGenASend_Send |
| 0.03% | python | _PySuper_LookupDescr |
| 0.03% | python | Py_HashBuffer |
| 0.03% | python | _Py_BuildString_StackRefSteal |
| 0.03% | python | _Py_LoadAttr_StackRefSteal |
| 0.03% | python | builtin_issubclass |
| 0.03% | python | get_exception_handler.isra.0 |
| 0.02% | python | PyBytesWriter_FinishWithPointer |
| 0.02% | python | recursive_issubclass |
| 0.02% | python | vgetargskeywords_impl.constprop.0 |
| 0.02% | python | store_instance_attr_lock_held |
| 0.02% | [unknown] | 0xffffffff93c001c6 |
| 0.02% | python | _Py_MakeCoro |
| 0.02% | python | _PyInterpreterState_GetConfig |
| 0.02% | python | TaskStepMethWrapper_call |
| 0.02% | python | PySys_Audit |
| 0.02% | python | context_run |
| 0.02% | python | task_step_impl |
| 0.02% | python | TaskObj_clear |
| 0.02% | python | pthread_self@plt |
| 0.02% | python | _io_TextIOWrapper_write |
| 0.02% | python | any_find_slice |
| 0.02% | python | builtin_id |
| 0.02% | python | clone_combined_dict_keys |
| 0.02% | python | gen_finalize |
| 0.01% | python | _PyInterpreterState_Main |
| 0.01% | python | unsafe_long_compare |
| 0.01% | python | _Py_strhex_impl |
| 0.01% | python | pysiphash |
| 0.01% | python | _asyncio_Task___init__ |
| 0.01% | python | maybe_small_long |
| 0.01% | python | builtin_hasattr |
| 0.01% | [unknown] | 0xffffffff92ce5d2b |
| 0.01% | python | bounded_lru_cache_wrapper |
| 0.01% | python | vectorcall_maybe |
| 0.01% | python | unsafe_tuple_compare |
| 0.01% | python | PyContext_CopyCurrent |
| 0.01% | python | slot_tp_init |
| 0.01% | python | tailmatch |
| 0.01% | python | _Py_bytes_contains |
| 0.01% | python | supercheck |
| 0.01% | python | map_next |
| 0.01% | python | _PyCoro_GetAwaitableIter |
| 0.01% | python | wrapperdescr_get |
| 0.01% | python | compactlongs_guard |
| 0.01% | [unknown] | 0xffffffff93c00151 |
| 0.01% | python | task_wakeup |
| 0.01% | python | PyType_GetModule |
| 0.01% | python | insert_split_key |
| 0.01% | python | _PyContext_Exit |
| 0.01% | [unknown] | 0xffffffff93c0010f |
| 0.01% | python | _PyFunction_SetVersion |
| 0.01% | python | do_mkvalue |
| 0.01% | [unknown] | 0xffffffff93c011d3 |
| 0.01% | python | future_schedule_callbacks |
| 0.01% | python | dictitems_iter |
| 0.01% | python | slot_sq_contains |
| 0.01% | [unknown] | 0xffffffff92c57dd9 |
| 0.01% | python | lru_cache_make_key |
| 0.01% | python | _PyContext_Enter |
| 0.01% | python | slot_tp_hash |
| 0.01% | [unknown] | 0xffffffff92c532de |
| 0.01% | python | malloc@plt |
| 0.01% | python | FutureObj_clear |
| 0.01% | python | builtin_sorted |
| 0.01% | python | charmaptranslate_lookup |
| 0.01% | python | _PyOptimizer_Optimize |
| 0.01% | python | _PyIter_Send |
| 0.01% | python | _asyncio_future_discard_from_awaited_by |
| 0.01% | python | func_descr_get |
| 0.01% | python | compactlongs_and |
| 0.01% | python | _Py_slot_tp_getattr_hook |
| 0.01% | python | _Py_convert_optional_to_ssize_t |
| 0.01% | python | slot_nb_bool |
| 0.01% | [unknown] | 0xffffffff93c0009d |
| 0.01% | [unknown] | 0xffffffff93c001bd |
| 0.01% | python | _Py_module_getattro_impl |
| 0.01% | python | _PyJIT |
| 0.01% | python | binary_op1 |
| 0.01% | python | _PyBytes_Resize |
| 0.01% | python | slot_tp_iternext |
| 0.01% | python | strlen@plt |
| 0.01% | python | mro_implementation_unlocked |
| 0.01% | python | unsafe_object_compare |
| 0.01% | python | task_call_step_soon |
| 0.01% | python | _PyBytes_Concat |
| 0.01% | apache::thrift::py::TType, | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*, |
| 0.01% | python | _Py_Specialize_LoadAttr |
| 0.01% | [unknown] | 0xffffffff93c0128c |
| 0.01% | python | PyTime_AsSecondsDouble |
| 0.01% | python | slot_sq_length |
| 0.01% | python | merge_from_seq2_lock_held |
| 0.01% | python | _Py_ReachedRecursionLimitWithMargin |
| 0.01% | python | PyBytesWriter_GetData |
| 0.01% | python | match_getslice_by_index |
| 0.01% | python | gallop_left |
| 0.01% | python | merge_at |
| 0.01% | python | richcmp_eq |
| 0.01% | python | gallop_right |
| 0.01% | python | _io_BytesIO_read |
| 0.00% | python | listreviter_next |
| 0.00% | python | write_bytes_lock_held |
| 0.00% | python | _abc__abc_instancecheck |
| 0.00% | python | TaskObj_finalize |
| 0.00% | python | hashtable_unicode_hash |
| 0.00% | [unknown] | 0xffffffff93c01631 |
| 0.00% | python | slot_sq_item |
| 0.00% | [vdso] | 0x0000000000000b00 |
| 0.00% | python | _PyJit_translate_single_bytecode_to_trace |
| 0.00% | [unknown] | 0xffffffff92866fc0 |
| 0.00% | python | getset_set |
| 0.00% | python | slot_nb_add |
| 0.00% | python | setitem_take2_lock_held |
| 0.00% | python | _asyncio_Future_add_done_callback |
| 0.00% | [unknown] | 0xffffffff93c011a9 |
| 0.00% | [unknown] | 0xffffffff92c57678 |
| 0.00% | python | free@plt |
| 0.00% | python | nonzero_float_compactlong_guard |
| 0.00% | python | property_descr_get |
| 0.00% | python | _textiowrapper_writeflush |
| 0.00% | python | iter_iternext |
| 0.00% | python | call_soon |
| 0.00% | [unknown] | 0xffffffff93a44c0e |
| 0.00% | python | subtype_clear |
| 0.00% | python | PyBytesWriter_FinishWithSize |
| 0.00% | python | memmove@plt |
| 0.00% | python | _asyncio_future_add_to_awaited_by |
| 0.00% | python | va_build_value |
| 0.00% | python | future_add_done_callback |
| 0.00% | [unknown] | 0xffffffff929df75e |
| 0.00% | python | _Py_call_instrumentation_arg |
| 0.00% | [unknown] | 0xffffffff936e9148 |
| 0.00% | python | slot_tp_iter |
| 0.00% | [unknown] | 0xffffffff929a4ca7 |
| 0.00% | python | copy_values |
| 0.00% | python | _Py_BuiltinCallFastWithKeywords_StackRefSteal |
| 0.00% | python | copy_lock_held |
| 0.00% | python | chain_next |
| 0.00% | [unknown] | 0xffffffff92c54aac |
| 0.00% | python | memchr@plt |
| 0.00% | python | __errno_location@plt |
| 0.00% | python | strchr@plt |
| 0.00% | [unknown] | 0xffffffff92c54d84 |
| 0.00% | python | hashtable_unicode_compare |
| 0.00% | python | member_set |
| 0.00% | python | match_getindex |
| 0.00% | [unknown] | 0xffffffff936f3c9e |
| 0.00% | _object*) | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType, |
| 0.00% | python | _Py_Specialize_Call |
| 0.00% | python | _asyncio_Future___init__ |
| 0.00% | python | int_bit_length |
| 0.00% | python | write_str |
| 0.00% | python | pthread_mutex_unlock@plt |
| 0.00% | python | vgetargskeywords.constprop.0 |
| 0.00% | [unknown] | 0xffffffff93c01618 |
| 0.00% | python | countformat |
| 0.00% | python | match_group |
| 0.00% | python | _PyFunction_FromConstructor |
| 0.00% | python | _Py_bytes_lower |
| 0.00% | [unknown] | 0xffffffff93c0125b |
| 0.00% | [unknown] | 0xffffffff92ce5d79 |
| 0.00% | [unknown] | 0xffffffff92c25c73 |
| 0.00% | [nf_tables] | nft_do_chain |
| 0.00% | python | _Py_call_instrumentation |
| 0.00% | python | slot_tp_call |
| 0.00% | python | analyze_descriptor_load.constprop.0 |
| 0.00% | python | compactlong_float_guard |
| 0.00% | python | FutureIter_am_send |
| 0.00% | python | os_fspath |
| 0.00% | [unknown] | 0xffffffff939cb1a6 |
| 0.00% | python | do_raise |
| 0.00% | python | gen_close |
| 0.00% | python | realloc@plt |

### dynamic

6.36% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.71% | python | PyObject_RichCompareBool |
| 0.57% | python | _PyObject_GenericGetAttrWithDict |
| 0.31% | python | PyObject_GetItem |
| 0.30% | python | PyType_IsSubtype |
| 0.26% | python | _PyObject_GetAttrStackRef |
| 0.24% | python | _PyObject_MakeTpCall |
| 0.21% | python | PyObject_Hash |
| 0.18% | python | PyObject_Vectorcall |
| 0.18% | python | PyNumber_AsSsize_t |
| 0.17% | python | PyObject_GetOptionalAttr |
| 0.14% | python | _PyObject_GetMethodStackRef |
| 0.13% | python | PyObject_SetItem |
| 0.13% | python | _PyObject_TryGetInstanceAttribute |
| 0.13% | python | _PyType_GetDict |
| 0.12% | python | PyObject_IsTrue |
| 0.10% | python | PyObject_IsInstance |
| 0.10% | python | PyObject_RichCompare |
| 0.10% | python | PyObject_CallOneArg |
| 0.09% | python | _Py_type_getattro_impl |
| 0.09% | python | PyObject_Malloc |
| 0.09% | python | PyObject_Size |
| 0.08% | python | object_isinstance |
| 0.08% | python | getset_get |
| 0.08% | python | PyObject_GetIter |
| 0.08% | python | type_call |
| 0.08% | python | PyObject_VisitManagedDict |
| 0.07% | python | PyObject_ClearManagedDict |
| 0.07% | python | PyObject_SetAttr |
| 0.07% | python | PyObject_Free |
| 0.06% | python | PyObject_GenericSetAttr |
| 0.06% | python | slot_tp_richcompare |
| 0.06% | python | PyType_GetModuleByDef |
| 0.05% | python | PyObject_IsSubclass |
| 0.05% | python | PyObject_Call |
| 0.05% | python | _PyObject_LookupSpecial |
| 0.05% | python | _PyObject_VectorcallPrepend |
| 0.04% | python | PySequence_Fast |
| 0.04% | python | PyDescr_IsData |
| 0.04% | python | method_get |
| 0.04% | python | PyObject_ClearWeakRefs |
| 0.04% | python | _PyObject_RealIsSubclass |
| 0.03% | python | delitem_common |
| 0.03% | python | PyNumber_Remainder |
| 0.03% | python | PyObject_VectorcallMethod |
| 0.03% | python | PyIter_Next |
| 0.03% | python | PyObject_Str |
| 0.03% | python | PyObject_GetBuffer |
| 0.03% | python | PyObject_GetAttr |
| 0.03% | python | PySequence_Contains |
| 0.03% | python | PyNumber_Multiply |
| 0.02% | python | PyObject_Repr |
| 0.02% | python | _PyObject_VectorcallDictTstate |
| 0.02% | python | _PyObject_InitInlineValues |
| 0.02% | python | PyIter_Send |
| 0.02% | python | PyNumber_Add |
| 0.02% | python | PyNumber_FloorDivide |
| 0.02% | python | PyObject_DelItem |
| 0.02% | python | type_ready |
| 0.02% | python | object_init |
| 0.02% | python | object_get_class |
| 0.02% | python | PyObject_GenericHash |
| 0.02% | python | PyNumber_Index |
| 0.02% | python | object_richcompare |
| 0.01% | python | _PyObject_Call_Prepend |
| 0.01% | python | PyNumber_InPlaceAdd |
| 0.01% | python | _PyNumber_Index |
| 0.01% | python | PyObject_GenericGetAttr |
| 0.01% | python | _PySuper_Lookup |
| 0.01% | python | PyNumber_Negative |
| 0.01% | python | _PyObject_StoreInstanceAttribute |
| 0.01% | python | object_recursive_isinstance |
| 0.01% | python | PyNumber_Rshift |
| 0.01% | python | StopIteration_init |
| 0.01% | python | PyMapping_GetOptionalItem |
| 0.01% | python | _PyObject_RealIsInstance |
| 0.01% | python | PyMapping_Check |
| 0.01% | python | PyNumber_Lshift |
| 0.01% | python | PyNumber_Subtract |
| 0.01% | python | PyObject_LengthHint |
| 0.01% | python | type_name |
| 0.01% | python | PySequence_Tuple |
| 0.01% | python | PyNumber_Xor |
| 0.01% | python | PyNumber_Long |
| 0.00% | python | _PyNumber_PowerNoMod |
| 0.00% | python | type___instancecheck__ |
| 0.00% | python | PySequence_GetItem |
| 0.00% | python | PyIter_Check |
| 0.00% | python | PyNumber_TrueDivide |
| 0.00% | python | object___reduce_ex__ |
| 0.00% | python | _PyObject_SetAttributeErrorContext |
| 0.00% | python | PySequence_List |
| 0.00% | python | PyObject_HasAttrWithError |
| 0.00% | python | PyObject_GenericGetDict |
| 0.00% | python | object_vacall |
| 0.00% | python | _PyObject_CallFunctionVa |
| 0.00% | python | PyNumber_Float |
| 0.00% | python | _PyObject_MaterializeManagedDict_LockHeld |
| 0.00% | python | object_str |
| 0.00% | python | _PyObject_ClearFreeLists |
| 0.00% | python | PyObject_SelfIter |
| 0.00% | python | PyObject_SetAttrString |

### lookup

5.35% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 3.13% | python | unicodekeys_lookup_unicode |
| 2.01% | python | _Py_dict_lookup |
| 0.06% | python | find_name_in_mro |
| 0.03% | python | _Py_dict_lookup_threadsafe_stackref |
| 0.03% | python | builtin_getattr |
| 0.02% | python | _Py_hashtable_get_entry_generic |
| 0.02% | python | _Py_type_getattro |
| 0.01% | python | PyMember_GetOne |
| 0.01% | python | update_one_slot |
| 0.01% | python | PyMember_SetOne |
| 0.01% | python | member_get |
| 0.00% | python | _Py_hashtable_get |

### libc

4.79% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.74% | libc.so.6 | __memmove_avx_unaligned_erms |
| 0.50% | libc.so.6 | __memset_avx2_unaligned_erms |
| 0.33% | libc.so.6 | __memcmp_avx2_movbe |
| 0.17% | libc.so.6 | _int_malloc |
| 0.10% | libc.so.6 | malloc |
| 0.07% | libc.so.6 | __strlen_avx2 |
| 0.06% | libc.so.6 | _int_free_merge_chunk |
| 0.05% | libc.so.6 | _int_free |
| 0.04% | libc.so.6 | cfree@GLIBC_2.2.5 |
| 0.04% | libc.so.6 | unlink_chunk.isra.0 |
| 0.04% | libc.so.6 | __memchr_avx2 |
| 0.03% | libc.so.6 | pthread_mutex_lock@@GLIBC_2.2.5 |
| 0.03% | libcrypto.so.3 | 0x00000000002dcb4e |
| 0.03% | libc.so.6 | __strcmp_avx2 |
| 0.03% | libc.so.6 | __GI___pthread_self |
| 0.02% | libc.so.6 | pthread_mutex_unlock@@GLIBC_2.2.5 |
| 0.02% | libc.so.6 | __strchr_avx2 |
| 0.02% | libcrypto.so.3 | 0x00000000002dcb90 |
| 0.02% | libc.so.6 | _int_free_maybe_consolidate |
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
| 0.01% | libcrypto.so.3 | 0x00000000002dc9e6 |
| 0.01% | libc.so.6 | realloc |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba4 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd01 |
| 0.01% | libc.so.6 | pthread_cond_signal@@GLIBC_2.3.2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccd2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc6a |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba9 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccee |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc40 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc7e |
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
| 0.01% | libc.so.6 | _int_realloc |
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
| 0.01% | libcrypto.so.3 | OPENSSL_cleanse |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc60 |
| 0.01% | libcrypto.so.3 | OSSL_PARAM_locate |
| 0.01% | libcrypto.so.3 | BIO_ctrl |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb49 |
| 0.01% | libc.so.6 | pthread_rwlock_unlock@@GLIBC_2.34 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbbd |
| 0.01% | libc.so.6 | pthread_rwlock_rdlock@GLIBC_2.2.5 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb58 |
| 0.01% | libc.so.6 | __errno_location |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbb3 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb67 |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_ctrl |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_get_iv_length |
| 0.01% | libc.so.6 | clock_gettime@@GLIBC_2.17 |
| 0.01% | libcrypto.so.3 | 0x00000000000c0ddb |
| 0.01% | libc.so.6 | malloc_consolidate |
| 0.00% | libc.so.6 | __memrchr_avx2 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb53 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcd0a |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb27 |
| 0.00% | libcrypto.so.3 | 0x00000000002dc9db |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb0f |
| 0.00% | libc.so.6 | __printf_buffer |
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
| 0.00% | libcrypto.so.3 | 0x00000000002dc8e5 |
| 0.00% | libc.so.6 | __GI___readdir64 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb36 |
| 0.00% | libc.so.6 | __gconv_transform_utf8_internal |
| 0.00% | libcrypto.so.3 | 0x00000000002dcc65 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb85 |

### dict

3.38% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.65% | python | _PyDict_Subscript |
| 0.50% | python | dictiter_iternextkey |
| 0.35% | python | insertdict |
| 0.28% | python | PyDict_GetItemRef |
| 0.17% | python | dictkeys_decref.part.0.constprop.0 |
| 0.16% | python | build_indices_unicode |
| 0.16% | python | PyDict_Next |
| 0.10% | python | insert_to_emptydict |
| 0.09% | python | find_empty_slot.constprop.0 |
| 0.09% | python | dict_get |
| 0.09% | python | _PyDict_StoreSubscript |
| 0.07% | python | dictiter_iternextitem |
| 0.07% | python | PyDict_Contains |
| 0.07% | python | new_dict |
| 0.06% | python | _PyDict_FromItems |
| 0.05% | python | dict_setdefault_ref_lock_held |
| 0.05% | python | _PyDict_LoadBuiltinsFromGlobals |
| 0.04% | python | _PyDict_Next |
| 0.04% | python | dict_merge |
| 0.03% | python | dictresize |
| 0.03% | python | new_keys_object |
| 0.03% | python | PyDict_SetItem |
| 0.02% | python | insertdict.isra.0 |
| 0.02% | python | _PyDict_DelItem_KnownHash_LockHeld |
| 0.02% | python | dictiter_iternextvalue |
| 0.02% | python | _PyDict_SetItem_Take2 |
| 0.01% | python | dict_items |
| 0.01% | python | PyDict_GetItem |
| 0.01% | python | dict_ass_sub |
| 0.01% | python | PyDict_GetItemWithError |
| 0.01% | python | _PyDict_MergeUniq |
| 0.01% | python | dict_pop |
| 0.01% | python | _PyDict_LoadGlobalStackRef |
| 0.01% | python | dict_iter |
| 0.01% | python | _PyDict_GetItemRef_KnownHash_LockHeld |
| 0.00% | python | _PyDict_GetMethodStackRef |
| 0.00% | python | dict_vectorcall |
| 0.00% | python | dict___contains__ |
| 0.00% | python | insert_to_emptydict.isra.0 |
| 0.00% | python | dict_length |
| 0.00% | python | dict_update |
| 0.00% | python | dict_copy |

### str

2.54% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.26% | python | bytes_translate_impl |
| 0.20% | python | _PyUnicode_Equal |
| 0.17% | python | _PyUnicode_JoinArray.part.0 |
| 0.17% | python | siphash13 |
| 0.14% | python | PyUnicode_Format |
| 0.12% | python | PyUnicode_RichCompare |
| 0.11% | python | _copy_characters.constprop.0.isra.0 |
| 0.10% | python | _PyUnicode_ResizeCompact |
| 0.08% | python | replace |
| 0.07% | python | find_first_nonascii |
| 0.06% | python | bytes_richcompare |
| 0.05% | python | PyUnicode_Substring |
| 0.05% | python | PyBytes_FromStringAndSize |
| 0.04% | python | unicode_decode_utf8.part.0 |
| 0.04% | python | _PyUnicode_FromUCS4.part.0 |
| 0.04% | python | unicode_from_format |
| 0.04% | python | PyUnicode_Contains |
| 0.04% | python | _PyUnicodeWriter_PrepareInternal |
| 0.03% | python | unicode_repr |
| 0.03% | python | _PyUnicodeWriter_WriteStr |
| 0.03% | python | _PyUnicodeWriter_WriteSubstring |
| 0.03% | python | split |
| 0.03% | python | _PyUnicode_InternMortal |
| 0.03% | python | unicode_hash |
| 0.03% | python | unicode_replace |
| 0.02% | python | PyUnicode_Concat |
| 0.02% | python | PyUnicode_AsUTF8AndSize |
| 0.02% | python | unicode_decode_utf8_impl |
| 0.02% | python | _PyUnicode_BinarySlice |
| 0.02% | python | stringlib_bytes_join |
| 0.02% | python | _PyUnicodeWriter_Finish |
| 0.02% | python | _PyUnicode_TranslateCharmap |
| 0.02% | python | PyUnicodeWriter_WriteChar |
| 0.02% | python | unicode_join |
| 0.02% | python | bytes_subscript |
| 0.02% | python | unicode_startswith |
| 0.01% | python | _PyUnicode_FromUCS1.part.0 |
| 0.01% | python | bytes_hash |
| 0.01% | python | _PyUnicode_IsAlpha |
| 0.01% | python | _PyUnicodeWriter_WriteASCIIString |
| 0.01% | python | PyUnicodeWriter_WriteASCII |
| 0.01% | python | intern_constants |
| 0.01% | python | bytes_buffer_getbuffer |
| 0.01% | python | _PyUnicode_Result |
| 0.01% | python | unicode_fromformat_write_utf8 |
| 0.01% | python | _PyUnicode_InternImmortal |
| 0.01% | python | PyUnicode_InternFromString |
| 0.01% | python | PyUnicode_Splitlines |
| 0.01% | python | PyUnicode_AsEncodedString |
| 0.01% | python | _PyUnicode_DecodeUTF8Writer |
| 0.01% | python | PyBytes_FromStringAndSize.constprop.0 |
| 0.01% | python | _PyUnicodeWriter_Init |
| 0.01% | python | _PyUnicode_FindMaxChar |
| 0.01% | python | bytes_iteritem |
| 0.01% | python | unicode_expandtabs |
| 0.01% | python | PyUnicode_Decode |
| 0.01% | python | _PyUnicode_IsDecimalDigit |
| 0.01% | python | unicode_rfind |
| 0.00% | python | unicode_lower |
| 0.00% | python | unicode_encode |
| 0.00% | python | PyUnicodeWriter_WriteStr |
| 0.00% | python | unicode_strip |
| 0.00% | python | PyUnicode_AsUCS4 |
| 0.00% | python | _PyUnicode_FastCopyCharacters |
| 0.00% | python | PyUnicode_Append |
| 0.00% | python | stringlib__two_way |
| 0.00% | python | unicode_split |
| 0.00% | python | _PyUnicode_XStrip |
| 0.00% | python | PyBytes_FromObject |
| 0.00% | python | PyUnicode_FromString |
| 0.00% | python | PyUnicode_DecodeUTF8 |
| 0.00% | python | ascii_decode |
| 0.00% | python | _PyUnicode_ToLowercase |
| 0.00% | python | bytes_length |
| 0.00% | python | _PyUnicode_IsDigit |
| 0.00% | python | unicode_fromformat_write_str |
| 0.00% | python | PyUnicode_FindChar |
| 0.00% | python | PyUnicode_FromWideChar |
| 0.00% | python | PyUnicode_FromFormatV |
| 0.00% | python | unicode_mod |
| 0.00% | python | PyUnicodeWriter_Create |
| 0.00% | python | unicode_find |
| 0.00% | python | bytes_translate |
| 0.00% | python | unicode_rstrip |

### miscobj

2.46% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.11% | python | set_lookkey |
| 0.35% | python | PySlice_AdjustIndices |
| 0.19% | python | _PySet_Contains |
| 0.08% | python | PySlice_Unpack |
| 0.07% | python | gen_iternext |
| 0.06% | python | set_add_entry_takeref |
| 0.06% | python | make_gen |
| 0.04% | python | setiter_iternext |
| 0.04% | python | PyBuffer_Release |
| 0.04% | python | PyBool_FromLong |
| 0.04% | python | PyBuffer_FillInfo |
| 0.03% | python | enum_next |
| 0.03% | python | range_iter |
| 0.03% | python | set_issubset_impl |
| 0.03% | python | deque_append |
| 0.02% | python | _PyBuildSlice_ConsumeRefs |
| 0.02% | python | set_table_resize |
| 0.02% | python | set_merge_lock_held |
| 0.02% | python | deque_popleft |
| 0.01% | python | range_vectorcall |
| 0.01% | python | dequeiter_next |
| 0.01% | python | _PyGen_FetchStopIterationValue |
| 0.01% | python | PyGen_am_send |
| 0.01% | python | set_difference |
| 0.01% | python | deque_clear.part.0 |
| 0.01% | python | range_subscript |
| 0.01% | python | _PySlice_GetLongIndices |
| 0.01% | python | set_add |
| 0.01% | python | PySet_Add |
| 0.01% | python | _PySet_NextEntryRef |
| 0.00% | python | weakref_richcompare |
| 0.00% | python | set_iter |
| 0.00% | python | set_vectorcall |
| 0.00% | python | bytearray_ass_subscript_lock_held |
| 0.00% | python | weakref_hash |
| 0.00% | python | set_intersection |
| 0.00% | python | set_discard |
| 0.00% | python | deque_iter |

### int

2.40% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.74% | python | k_mul |
| 0.19% | python | x_divrem |
| 0.18% | python | long_to_decimal_string_internal |
| 0.15% | python | PyLong_FromSsize_t |
| 0.13% | python | PyLong_FromLong |
| 0.09% | python | PyLong_AsSsize_t |
| 0.08% | python | _PyLong_FromMedium |
| 0.08% | python | _PyLong_GCD |
| 0.07% | python | PyLong_AsLongAndOverflow |
| 0.07% | python | long_richcompare |
| 0.06% | python | x_add |
| 0.06% | python | long_hash |
| 0.04% | python | long_div |
| 0.04% | python | PyLong_FromString |
| 0.03% | python | x_sub |
| 0.03% | python | long_bitwise |
| 0.03% | python | PyLong_FromVoidPtr |
| 0.02% | python | PyLong_AsNativeBytes.constprop.0 |
| 0.02% | python | PyLong_AsLong |
| 0.02% | python | PyLong_FromUnsignedLong |
| 0.02% | python | long_lshift1 |
| 0.02% | python | long_rshift1 |
| 0.02% | python | long_mul |
| 0.02% | python | long_rshift |
| 0.02% | python | l_mod |
| 0.02% | python | long_to_decimal_string |
| 0.01% | python | long_lshift_method |
| 0.01% | python | _PyLong_Frexp |
| 0.01% | python | long_neg_method |
| 0.01% | python | long_add_method |
| 0.01% | python | _PyLong_Size_t_Converter |
| 0.01% | python | long_mul_method |
| 0.01% | python | PyLong_AsDouble |
| 0.01% | python | PyLong_FromUnsignedLongLong |
| 0.01% | python | PyLong_FromLongLong |
| 0.01% | python | long_mod |
| 0.00% | python | PyLong_AsInt |
| 0.00% | python | long_float |
| 0.00% | python | long_xor |
| 0.00% | python | long_sub |
| 0.00% | python | long_vectorcall |
| 0.00% | python | PyLong_GetSign |
| 0.00% | python | _PyLong_UInt64_Converter |
| 0.00% | python | long_true_divide |

### kernel

2.00% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.22% | [kernel.kallsyms] | __irqentry_text_end |
| 0.11% | [kernel.kallsyms] | error_entry |
| 0.08% | [kernel.kallsyms] | clear_page_erms |
| 0.06% | [kernel.kallsyms] | native_irq_return_iret |
| 0.06% | [kernel.kallsyms] | sync_regs |
| 0.05% | [kernel.kallsyms] | entry_SYSRETQ_unsafe_stack |
| 0.05% | [kernel.kallsyms] | syscall_return_via_sysret |
| 0.03% | [kernel.kallsyms] | __handle_mm_fault |
| 0.03% | [kernel.kallsyms] | zap_pte_range |
| 0.03% | [kernel.kallsyms] | get_mem_cgroup_from_mm |
| 0.03% | [kernel.kallsyms] | entry_SYSCALL_64_after_hwframe |
| 0.03% | [kernel.kallsyms] | memset_orig |
| 0.02% | [kernel.kallsyms] | do_anonymous_page |
| 0.02% | [kernel.kallsyms] | __count_memcg_events |
| 0.02% | [kernel.kallsyms] | mas_walk |
| 0.02% | [kernel.kallsyms] | entry_SYSCALL_64 |
| 0.02% | [kernel.kallsyms] | __d_lookup_rcu |
| 0.02% | [kernel.kallsyms] | handle_mm_fault |
| 0.02% | [kernel.kallsyms] | __alloc_pages |
| 0.02% | [kernel.kallsyms] | lru_gen_add_folio |
| 0.02% | [kernel.kallsyms] | __rcu_read_lock |
| 0.02% | [kernel.kallsyms] | __rcu_read_unlock |
| 0.02% | [kernel.kallsyms] | __mod_memcg_lruvec_state |
| 0.02% | [kernel.kallsyms] | rep_movs_alternative |
| 0.02% | [kernel.kallsyms] | rmqueue_bulk |
| 0.02% | [kernel.kallsyms] | perf_adjust_freq_unthr_context |
| 0.01% | [kernel.kallsyms] | __lruvec_stat_mod_folio |
| 0.01% | [kernel.kallsyms] | _raw_spin_lock |
| 0.01% | [kernel.kallsyms] | __mod_node_page_state |
| 0.01% | [kernel.kallsyms] | release_pages |
| 0.01% | [kernel.kallsyms] | link_path_walk.part.0.constprop.0 |
| 0.01% | [kernel.kallsyms] | lru_gen_del_folio.constprop.0 |
| 0.01% | [kernel.kallsyms] | rmqueue |
| 0.01% | [kernel.kallsyms] | percpu_counter_add_batch |
| 0.01% | [kernel.kallsyms] | cgroup_rstat_updated |
| 0.01% | [kernel.kallsyms] | lru_add_fn |
| 0.01% | [kernel.kallsyms] | get_page_from_freelist |
| 0.01% | [kernel.kallsyms] | folio_add_lru |
| 0.01% | [kernel.kallsyms] | blk_cgroup_congested |
| 0.01% | [kernel.kallsyms] | arch_exit_to_user_mode_prepare.isra.0 |
| 0.01% | [kernel.kallsyms] | get_vma_policy |
| 0.01% | [kernel.kallsyms] | do_user_addr_fault |
| 0.01% | [kernel.kallsyms] | __pte_offset_map |
| 0.01% | [kernel.kallsyms] | __free_one_page |
| 0.01% | [kernel.kallsyms] | _raw_spin_trylock |
| 0.01% | [kernel.kallsyms] | __mod_zone_page_state |
| 0.01% | [kernel.kallsyms] | handle_pte_fault |
| 0.01% | [kernel.kallsyms] | kmem_cache_alloc |
| 0.01% | [kernel.kallsyms] | alloc_anon_folio |
| 0.01% | [kernel.kallsyms] | __pte_offset_map_lock |
| 0.01% | [kernel.kallsyms] | folio_batch_move_lru |
| 0.01% | [kernel.kallsyms] | ext4_htree_store_dirent |
| 0.01% | [kernel.kallsyms] | native_write_msr |
| 0.01% | [kernel.kallsyms] | __rmqueue_pcplist |
| 0.01% | [kernel.kallsyms] | exc_page_fault |
| 0.01% | [kernel.kallsyms] | folio_remove_rmap_ptes |
| 0.01% | [kernel.kallsyms] | lock_vma_under_rcu |
| 0.01% | [kernel.kallsyms] | down_read_trylock |
| 0.01% | [kernel.kallsyms] | fpregs_assert_state_consistent |
| 0.01% | [kernel.kallsyms] | do_syscall_64 |
| 0.01% | [kernel.kallsyms] | inode_permission |
| 0.01% | [kernel.kallsyms] | asm_exc_page_fault |
| 0.01% | [kernel.kallsyms] | pte_offset_map_nolock |
| 0.01% | [kernel.kallsyms] | folio_add_new_anon_rmap |
| 0.01% | [kernel.kallsyms] | __update_load_avg_se |
| 0.01% | [kernel.kallsyms] | filldir64 |
| 0.01% | [kernel.kallsyms] | up_read |
| 0.01% | [kernel.kallsyms] | __update_load_avg_cfs_rq |
| 0.01% | [kernel.kallsyms] | free_unref_page_prepare |
| 0.01% | [kernel.kallsyms] | post_alloc_hook |
| 0.01% | [kernel.kallsyms] | half_md4_transform.isra.0 |
| 0.01% | [kernel.kallsyms] | str2hashbuf_signed |
| 0.01% | [kernel.kallsyms] | kmem_cache_free |
| 0.01% | [kernel.kallsyms] | __raw_spin_lock_irqsave |
| 0.01% | [kernel.kallsyms] | free_unref_page_commit |
| 0.00% | [kernel.kallsyms] | uncharge_folio |
| 0.00% | [kernel.kallsyms] | alloc_pages_mpol |
| 0.00% | [kernel.kallsyms] | free_unref_page_list |
| 0.00% | [kernel.kallsyms] | mem_cgroup_commit_charge |
| 0.00% | [kernel.kallsyms] | get_pfnblock_flags_mask |
| 0.00% | [kernel.kallsyms] | next_uptodate_folio |
| 0.00% | [kernel.kallsyms] | update_curr |
| 0.00% | [kernel.kallsyms] | update_load_avg |
| 0.00% | [kernel.kallsyms] | strncpy_from_user |
| 0.00% | [kernel.kallsyms] | count_memcg_events.constprop.0 |
| 0.00% | [kernel.kallsyms] | generic_permission |
| 0.00% | [kernel.kallsyms] | __mod_lruvec_state |
| 0.00% | [kernel.kallsyms] | copy_page |
| 0.00% | [kernel.kallsyms] | __virt_addr_valid |
| 0.00% | [kernel.kallsyms] | _raw_spin_unlock |
| 0.00% | [kernel.kallsyms] | rb_next |
| 0.00% | [kernel.kallsyms] | account_user_time |
| 0.00% | [kernel.kallsyms] | __kmalloc |
| 0.00% | [kernel.kallsyms] | vma_alloc_folio |
| 0.00% | [kernel.kallsyms] | read_tsc |
| 0.00% | [kernel.kallsyms] | native_read_msr |
| 0.00% | [kernel.kallsyms] | __hrtimer_run_queues |
| 0.00% | [kernel.kallsyms] | apparmor_inode_getattr |
| 0.00% | [kernel.kallsyms] | consume_stock |
| 0.00% | [kernel.kallsyms] | hrtimer_interrupt |
| 0.00% | [kernel.kallsyms] | filename_lookup |
| 0.00% | [kernel.kallsyms] | irqentry_exit_to_user_mode |
| 0.00% | [kernel.kallsyms] | __mem_cgroup_charge |
| 0.00% | [kernel.kallsyms] | free_pcppages_bulk |
| 0.00% | [kernel.kallsyms] | cond_accept_memory |
| 0.00% | [kernel.kallsyms] | timekeeping_advance |
| 0.00% | [kernel.kallsyms] | step_into |
| 0.00% | [kernel.kallsyms] | filemap_map_pages |
| 0.00% | [kernel.kallsyms] | __task_pid_nr_ns |
| 0.00% | [kernel.kallsyms] | update_cfs_group |
| 0.00% | [kernel.kallsyms] | try_charge_memcg |
| 0.00% | [kernel.kallsyms] | set_root |
| 0.00% | [kernel.kallsyms] | cp_new_stat |
| 0.00% | [kernel.kallsyms] | x64_sys_call |
| 0.00% | [kernel.kallsyms] | policy_nodemask |
| 0.00% | [kernel.kallsyms] | task_tick_fair |
| 0.00% | [kernel.kallsyms] | rb_insert_color |
| 0.00% | [kernel.kallsyms] | scheduler_tick |
| 0.00% | [kernel.kallsyms] | __slab_free |
| 0.00% | [kernel.kallsyms] | arch_scale_freq_tick |
| 0.00% | [kernel.kallsyms] | security_inode_permission |
| 0.00% | [kernel.kallsyms] | free_swap_cache |
| 0.00% | [kernel.kallsyms] | syscall_exit_to_user_mode |
| 0.00% | [kernel.kallsyms] | security_inode_getattr |
| 0.00% | [kernel.kallsyms] | __folio_throttle_swaprate |
| 0.00% | [kernel.kallsyms] | set_ptes.isra.0 |
| 0.00% | [kernel.kallsyms] | walk_component |
| 0.00% | [kernel.kallsyms] | native_apic_msr_eoi |
| 0.00% | [kernel.kallsyms] | ktime_get_update_offsets_now |

### list

1.98% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.33% | python | listiter_next |
| 0.32% | python | list_remove |
| 0.22% | python | list_slice_lock_held |
| 0.17% | python | list_ass_slice_lock_held |
| 0.13% | python | list_iter |
| 0.09% | python | list_sort_impl |
| 0.08% | python | list_slice_wrap |
| 0.07% | python | _PyList_AppendTakeRefListResize |
| 0.06% | python | _PyList_BinarySlice |
| 0.06% | python | list_extend_lock_held |
| 0.05% | python | _list_extend |
| 0.05% | python | list_append |
| 0.05% | python | _PyList_SliceSubscript |
| 0.04% | python | list_ass_subscript |
| 0.04% | python | _PyList_FromStackRefStealOnSuccess |
| 0.04% | python | _PyList_Concat |
| 0.03% | python | list_subscript |
| 0.02% | python | PyList_Append |
| 0.02% | python | list_length |
| 0.02% | python | list_contains |
| 0.01% | python | list_resize |
| 0.01% | python | list_pop |
| 0.01% | python | list_insert |
| 0.01% | python | list_sort |
| 0.01% | python | _PyList_Extend |
| 0.01% | python | list_vectorcall |
| 0.01% | python | list_index |
| 0.00% | python | _PyList_GetItemRef |
| 0.00% | python | list_to_tuple |
| 0.00% | python | list_richcompare |
| 0.00% | python | PyList_SetItem |
| 0.00% | python | PyList_Size |
| 0.00% | python | _PyList_AsTupleAndClear |
| 0.00% | python | list_iteritem |

### tuple

1.27% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.31% | python | tuple_richcompare |
| 0.31% | python | PyTuple_FromArray.part.0 |
| 0.29% | python | _PyTuple_FromStackRefStealOnSuccess |
| 0.16% | python | tuple_hash |
| 0.03% | python | PyTuple_GetSlice |
| 0.03% | python | PyTuple_FromArray |
| 0.02% | python | _PyTuple_FromArraySteal |
| 0.02% | python | tuple_subscript |
| 0.02% | python | _PyTuple_FromPair |
| 0.01% | python | tupleiter_next |
| 0.01% | python | tuple_iter |
| 0.01% | python | tuplegetter_descr_get |
| 0.01% | python | _PyTuple_FromPairSteal |
| 0.01% | python | _PyTuple_Concat |
| 0.01% | python | tuple_iteritem |
| 0.01% | python | _PyTuple_BinarySlice |
| 0.01% | python | _PyTuple_Resize |
| 0.00% | python | tuple_contains |
| 0.00% | python | tuple_length |
| 0.00% | python | PyTuple_Pack |
| 0.00% | python | PyTuple_Size |

### calls

0.68% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.19% | python | _PyArg_UnpackKeywords |
| 0.08% | python | _PyFunction_Vectorcall |
| 0.08% | python | _Py_CheckFunctionResult |
| 0.07% | python | vgetargs1_impl.constprop.0 |
| 0.06% | python | PyArg_UnpackTuple |
| 0.04% | python | cfunction_vectorcall_FASTCALL_KEYWORDS |
| 0.03% | python | PyArg_Parse |
| 0.02% | python | method_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.01% | python | cfunction_vectorcall_NOARGS |
| 0.01% | python | vgetargs1_impl |
| 0.01% | python | cfunction_vectorcall_O |
| 0.01% | python | method_vectorcall |
| 0.01% | python | PyArg_ParseTupleAndKeywords |
| 0.01% | python | method_vectorcall_O |
| 0.01% | python | method_vectorcall_VARARGS |
| 0.01% | python | cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.01% | python | method_vectorcall_NOARGS |
| 0.00% | python | _PyArg_UnpackStack |
| 0.00% | python | vectorcall_method |
| 0.00% | python | method_vectorcall_FASTCALL |
| 0.00% | python | method_vectorcall_VARARGS_KEYWORDS |
| 0.00% | python | cfunction_vectorcall_FASTCALL |

### threading

0.51% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.28% | python | _PyThreadState_PopFrame |
| 0.14% | python | _PyThreadState_PushFrame |
| 0.08% | python | PyThread_get_thread_ident |
| 0.01% | python | _PyThreadState_Attach |
| 0.01% | python | _PyThreadState_Detach |
| 0.01% | python | _PyThreadState_MustExit |

### exceptions

0.40% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.13% | python | PyErr_CheckSignals |
| 0.09% | python | _PyErr_CheckSignalsTstate |
| 0.03% | python | _PyErr_SetObject.part.0 |
| 0.03% | python | PyErr_ExceptionMatches |
| 0.03% | python | PyErr_Occurred |
| 0.01% | python | PyTraceBack_Here |
| 0.01% | python | PyErr_SetRaisedException |
| 0.01% | python | _PyErr_Restore |
| 0.01% | python | PyErr_GetRaisedException |
| 0.01% | python | PyErr_GivenExceptionMatches |
| 0.01% | python | PyException_GetTraceback |
| 0.01% | python | BaseException_vectorcall |
| 0.01% | python | PyErr_Format |
| 0.00% | python | AttributeError_init |
| 0.00% | python | PyFrame_GetCode |
| 0.00% | python | _PyErr_CreateException |
| 0.00% | python | _PyErr_SetKeyError |
| 0.00% | python | PyException_SetTraceback |

### compiler

0.34% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.33% | python | _PyJIT_Entry |
| 0.01% | python | optimize_uops.isra.0 |
| 0.00% | python | tok_get_normal_mode |
| 0.00% | python | tok_nextc |

### float

0.28% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.18% | python | PyFloat_FromDouble |
| 0.02% | python | float_richcompare |
| 0.02% | python | PyFloat_AsDouble |
| 0.02% | python | float_compactlong_true_div |
| 0.01% | python | float_add |
| 0.01% | python | float_pow |
| 0.00% | python | float_vectorcall |
| 0.00% | python | float_compactlong_guard |
| 0.00% | python | float_div |

### gil

0.06% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.04% | python | take_gil |
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
